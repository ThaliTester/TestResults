#### Test 61432979f791f6f_thali05_motorola-Nexus 6 Logs


```
--------- beginning of system
I/ActivityManager(  821): Start proc 3137:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
--------- beginning of main
I/UpdateIcingCorporaServi( 1572): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ConfigFetchTask( 1769): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/UpdateIcingCorporaServi( 1572): UpdateCorporaTask done [took 39 ms] updated apps [took 39 ms] 
I/ConfigFetchService( 1769): fetch service done; releasing wakelock
I/ConfigFetchService( 1769): stopping self
,W/BaseAppContext( 1769): Using Auth Proxy for data requests.
W/BaseAppContext( 1769): Using Auth Proxy for data requests.
W/BaseAppContext( 1769): Using Auth Proxy for data requests.
W/BaseAppContext( 1769): Using Auth Proxy for data requests.
W/BaseAppContext( 1769): Using Auth Proxy for data requests.
W/BaseAppContext( 1769): Using Auth Proxy for data requests.
D/AndroidRuntime( 3160): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3160): CheckJNI is OFF
I/art     ( 1769): Explicit concurrent mark sweep GC freed 24160(1636KB) AllocSpace objects, 13(208KB) LOS objects, 36% free, 27MB/43MB, paused 1.134ms total 38.770ms
D/AndroidRuntime( 3160): Calling main entry com.android.commands.am.Am
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{87222ba token=Token{1bca17e5 ActivityRecord{219f4adc u0 com.test.thalitest/.MainActivity t2}}} to stack=1 task=2 at 0
I/HotwordDetector( 1572): Closing mic
I/MicrophoneInputStream( 1572): mic_close com.google.android.apps.gsa.speech.audio.u@3bb4e675
D/AndroidRuntime( 3160): Shutting down VM
V/WindowManager(  821): Adding window Window{38ac5e9d u0 Starting com.test.thalitest} at 2 of 7 (after Window{24b103a3 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/ActivityManager(  821): Start proc 3176:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1572): Hotword detection finished
I/HotwordRecognitionRnr( 1572): Stopping hotword detection.
I/ActivityManager(  821): Killing 2782:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
D/ChimeraCfgMgr( 1769): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1769): Module APK com.google.android.play.games already loaded
I/WebViewFactory( 3176): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3176): Time to load native libraries: 1 ms (timestamps 2714-2715)
I/LibraryLoader( 3176): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3176): Binding Chromium to main looper Looper (main, tid 1) {1da800b8}
I/LibraryLoader( 3176): Expected native library version number "",actual native library version number ""
I/chromium( 3176): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3176): Initializing chromium process, singleProcess=true
W/art     ( 3176): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3176): ApplicationContext is null in ApplicationStatus
W/chromium( 3176): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3176): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3176): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3176): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3176): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1657996563
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/GAv4    ( 3137): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3137):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3137):   adb logcat -s GAv4
D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@312e354b:true
W/GAv4    ( 3137): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3137): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/art     ( 3176): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3176): onDetachedFromWindow called when already detached. Ignoring
W/GAv4    ( 3137): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3137): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
D/SystemWebViewEngine( 3176): CordovaWebView is running on device made by: motorola
W/art     ( 3176): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3176): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3176): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3176): Validating map...
V/WindowManager(  821): Adding window Window{4618bb1 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{38ac5e9d u0 Starting com.test.thalitest})
W/chromium( 3176): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3176): Initialized EGL, version 1.4
D/OpenGLRenderer( 3176): Enabling debug mode 0
I/ActivityManager(  821): Displayed com.test.thalitest/.MainActivity: +469ms
I/Keyboard.Facilitator( 1227): onFinishInput()
W/ResourcesManager( 3137): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3137): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/BindingManager( 3176): Cannot call determinedVisibility() - never saw a connection for the pid: 3176
V/JNIHelp ( 3137): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ActivityManager(  821): Killing 2646:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
I/ProviderInstaller( 3137): Installed default security provider GmsCore_OpenSSL
D/JsMessageQueue( 3176): Set native->JS mode to OnlineEventsBridgeMode
V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  821): Killing 2813:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
D/jxcore_app_log( 3176): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576399872
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3176): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3176):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3176):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3176):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3176):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3176): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20196bad added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3176): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3176):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3176):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3176):     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3176):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3176):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3176):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3176):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3176):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3176):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3176): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17895530 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3176): addListener: New listener added - the number of listeners is now 1
D/WifiService(  821): New client listening to asynchronous messages
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3176): setDiscoveryMode: Discovery mode BLE is supported
I/chromium( 3176): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  821): Killing 2849:com.android.settings/1000 (adj 15): empty #17
,W/jxcore-log( 3176): Initializing JXcore engine
W/jxcore-log( 3176): JXcore engine is ready
W/Thread-340( 3251): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12801]" dev="sockfs" ino=12801 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-340( 3251): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-340( 3251): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10956]" dev="sockfs" ino=10956 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-340( 3251): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[19910]" dev="sockfs" ino=19910 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 3176): Starting JXcore engine
W/jxcore-log( 3176): Platform android
W/jxcore-log( 3176): 
W/jxcore-log( 3176): Process ARCH arm
W/jxcore-log( 3176): 
,I/jxcore-log( 3176): JXcore Cordova bridge is ready!
I/jxcore-log( 3176): 
W/jxcore-log( 3176): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 3176): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/ConfigService( 1246): onDestroy
,V/io.jxcore.node.JXcoreExtension( 3176): isBleMultipleAdvertisementSupported: SUPPORTED
,I/jxcore-log( 3176): BLE multiple advertisement supported
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): My device name is: motorola-Nexus 6
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 3176): ,
,I/io.jxcore.node.ConnectivityInfo( 3176): updateConnectivityInfo: ,
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - BSSID name: null
I/io.jxcore.node.ConnectivityInfo( 3176):     - is connected/connecting to active network: false
I/io.jxcore.node.ConnectivityInfo( 3176):     - active network type is Wi-Fi: false
,I/io.jxcore.node.ConnectivityInfo( 3176):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 3176): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,I/jxcore-log( 3176): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 3176): 
,I/ActivityManager(  821): Waited long enough for: ServiceRecord{394fab11 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2688): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2688): [1] 5.onFinished: Installation state replication failed.,
D/Finsky  ( 2688): [1] 5.onFinished: Scheduling replication attempt 1.
,I/jxcore-log( 3176): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,I/jxcore-log( 3176): 
,I/jxcore-log( 3176): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,I/jxcore-log( 3176): 
,I/jxcore-log( 3176): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
,I/jxcore-log( 3176): 
,I/jxcore-log( 3176): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
,I/jxcore-log( 3176): 
,I/jxcore-log( 3176): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): Unit Test app is loaded
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"on","blueTooth":"on","wifi":"on","cellular":"doNotCare"},
I/jxcore-log( 3176): 
,I/chromium( 3176): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2688): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2688): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2688): [1] 5.onFinished: Scheduling replication attempt 2.
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,I/art     (  821): Explicit concurrent mark sweep GC freed 34974(1789KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.994ms total 78.734ms
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1246): Explicit concurrent mark sweep GC freed 25270(1383KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.264ms total 60.221ms
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2688): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2688): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2688): [1] 5.onFinished: Scheduling replication attempt 3.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1227): run()
I/Keyboard.Facilitator( 1227): flushDynamicLanguageModels()
,I/ConfigService( 1246): onCreate
,I/ConfigService( 1246): onDestroy
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2688): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2688): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2688): [1] 5.onFinished: Scheduling replication attempt 4.
,I/PowerManagerService(  821): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (322 us)
,I/DisplayManagerService(  821): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager(  821): Display changed displayId=0
,I/kickstart(  872): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000,
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  872): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2,
I/kickstart(  872): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl(  821): Excessive delay in setPowerMode(): 264ms
,I/DreamManagerService(  821): Entering dreamland.
I/PowerManagerService(  821): Dozing...
I/DreamController(  821): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  821): cancelDelayedScan -> 17
,E/native  (  821): do suspend false,
,I/Keyboard.Facilitator( 1227): onFinishInput()
,E/WifiStateMachine(  821): cancelDelayedScan -> 19
,E/native  (  821): do suspend true
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  821): WifiStateMachine Disconnected CMD_START_SCAN source -2 18, 19 -> obsolete
,I/kickstart(  872): STATUS: Received file 'm9kefs2'
I/kickstart(  872): STATUS: 950272 bytes transferred in 1.002452 seconds
I/kickstart(  872): STATUS: Successfully downloaded files from target 
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  872): STATUS: Sahara protocol completed
,I/wpa_supplicant( 1147): wlan0: Reject scan trigger since one is already pending
,W/wpa_supplicant( 1147): wlan0: Failed to initiate AP scan
,I/wpa_supplicant( 1147): wlan0: Reject scan trigger since one is already pending
,W/wpa_supplicant( 1147): wlan0: Failed to initiate AP scan
,I/wpa_supplicant( 1147): wlan0: Reject scan trigger since one is already pending
,W/wpa_supplicant( 1147): wlan0: Failed to initiate AP scan
,I/wpa_supplicant( 1147): wlan0: Reject scan trigger since one is already pending
,W/wpa_supplicant( 1147): wlan0: Failed to initiate AP scan
,I/wpa_supplicant( 1147): wlan0: Reject scan trigger since one is already pending,
W/wpa_supplicant( 1147): wlan0: Failed to initiate AP scan
,I/wpa_supplicant( 1147): wlan0: Reject scan trigger since one is already pending
,W/wpa_supplicant( 1147): wlan0: Failed to initiate AP scan
,I/wpa_supplicant( 1147): wlan0: Reject scan trigger since one is already pending
,W/wpa_supplicant( 1147): wlan0: Failed to initiate AP scan
,I/wpa_supplicant( 1147): wlan0: Reject scan trigger since one is already pending
W/wpa_supplicant( 1147): wlan0: Failed to initiate AP scan
,I/wpa_supplicant( 1147): wlan0: Reject scan trigger since one is already pending
W/wpa_supplicant( 1147): wlan0: Failed to initiate AP scan
,E/WifiStateMachine(  821): WifiStateMachine Disconnected CMD_START_SCAN source -2 16, 19 -> obsolete
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@368a2db7}
,I/wpa_supplicant( 1147): wlan0: Trying to associate with SSID 'NG700'
,I/wpa_supplicant( 1147): wlan0: Associated with f4:f2:6d:22:99:3e
,I/wpa_supplicant( 1147): wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1147): wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,D/ConnectivityService(  821): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING,
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  821): Start Dhcp Watchdog 1
,E/WifiStateMachine(  821):  WifiLinkLayerStats: 
E/WifiStateMachine(  821):  my bss beacon rx: 1
E/WifiStateMachine(  821):  RSSI mgmt: -42
E/WifiStateMachine(  821):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  821):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  on_time : 0 tx_time=62 rx_time=109 scan_time=0
,E/native  (  821): do suspend false,
,E/WifiStateMachine(  821): scanCount==0 - aborting
,I/dhcpcd  ( 3283): version 5.5.6 starting
,I/dhcpcd  ( 3283): wlan0: rebinding lease of 192.168.1.125
,I/dhcpcd  ( 3283): wlan0: acknowledged 192.168.1.125 from 192.168.1.1,
,I/dhcpcd  ( 3283): wlan0: leased 192.168.1.125 for 172800 seconds
,E/native  (  821): do suspend true
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  821): Adding iface wlan0 to network 100
,E/WifiStateMachine(  821): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  821): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  821): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  821): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService(  821): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  821): Setting Dns servers for network 100 to [/192.168.1.1]
,D/ConnectivityService(  821): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  821): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821):    accepting network in place of null
,D/ConnectivityService(  821): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} },
D/ConnectivityService(  821): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100],
D/ConnectivityManager.CallbackHandler( 1057): CM callback handler got msg 524290
,D/CSLegacyTypeTracker(  821): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  821): MasterInitialState.processMessage what=3
,V/BackupManagerService(  821): Scheduling immediate backup pass
,V/BackupManagerService(  821): Running a backup pass
,V/BackupManagerService(  821): clearing pending backups
,I/NetworkMonitor( 2870): type=WIFI subType= reason=null isConnected=true
,V/PerformBackupTask(  821): Beginning backup of 14 targets
,D/PerformBackupTask(  821): invokeAgentForBackup on @pm@
,V/MusicLeanback( 2870): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1322): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1322): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  821): getDataEnabled: retVal=false
,V/BackupServiceBinder(  821): doBackup() invoked
,I/PMBA    (  821): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,I/ActivityManager(  821): Start proc 3325:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,E/GpsLocationProvider(  821): No APN found to select.
,I/BackupRestoreController(  821): Getting widget state for user: 0
,W/GmsBackupTransport( 1796): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1796): starting performBackup for @pm@
D/GpsLocationProvider(  821): NTP server returned: 1457078853395 (Fri Mar 04 09:07:33 GMT+01:00 2016) reference: 177459 certainty: 18 system time offset: -520
,D/AlarmManagerService(  821): Setting time of day to sec=1457078853
W/AlarmManagerService(  821): Unable to set rtc to 1457078853: Invalid argument
,V/GmsBackupTransport( 1796): performBackup done for @pm@
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/DriveInitializer( 1769): Background init thread started
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Mar 2016 08:07:33 GMT], X-Android-Received-Millis=[1457078853457], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1457078853910]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Validated
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  821): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1057): CM callback handler got msg 524290
,W/DriveInitializer( 1769): Awaiting to be initialized
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  821): Start proc 3365:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GoogleAuthProtoRequest( 3325): [330] a.<init>: mAccountName set to: thalitester@gmail.com
,D/SprintDMReceiver( 3365): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,W/GLSActivity( 1246): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1246): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1246): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1246): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1246): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1246): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1246): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SprintDMHelper( 3365): simOperator:  IMSI: null
D/SprintDMReceiver( 3365): Not Sprint UICC, don't do anything.
,W/GmsBackupTransport( 1796): Error sending final backup to server: 
W/GmsBackupTransport( 1796): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1796): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1796): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1796): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1796): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1796): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1796): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1796): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1796): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1796): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1796): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1796): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1796): 	... 1 more
,I/SystemUpdateService( 1769): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1769): onCreate
,D/SystemUpdateService( 1769): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/BackupManagerService(  821): Now staging backup of com.google.android.talk
,D/BackupManagerService(  821): Now staging backup of com.google.android.dialer
,I/SystemUpdateService( 1769): active receiver: enabled
,I/SystemUpdateService( 1769): Already downloaded, skipping offpeak checks.
D/BackupManagerService(  821): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  821): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  821): Now staging backup of com.google.android.gm
,D/BackupManagerService(  821): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  821): Now staging backup of com.android.nfc
,I/SystemUpdateService( 1769): network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: true
D/BackupManagerService(  821): Now staging backup of com.google.android.apps.genie.geniewidget
I/SystemUpdateService( 1769): now status is 0 (complete)
I/SystemUpdateService( 1769): processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
I/SystemUpdateService( 1769): file has been verified
I/SystemUpdateService( 1769): OTA package size = 105451271
,W/DriveInitializer( 1769): Background init thread ended
D/BackupManagerService(  821): Now staging backup of com.google.android.marvin.talkback
I/SystemUpdateService( 1769): showing system update notification
,D/BackupManagerService(  821): Now staging backup of com.google.android.inputmethod.latin
V/GoogleAuthProtoRequest( 3325): [331] a.<init>: mAccountName set to: thalitester@gmail.com
,D/BackupManagerService(  821): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  821): Now staging backup of com.android.vending
,D/BackupManagerService(  821): Now staging backup of android
I/ValidateNoPeople(  821): skipping global notification
,D/BackupManagerService(  821): Now staging backup of com.google.android.googlequicksearchbox
,I/ActivityManager(  821): Start proc 3397:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/art     (  369): Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 198us total 9.846ms
,I/GmsBackupTransport( 1796): Next backup will happen in 43199887 millis.
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 199us total 9.155ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 202us total 9.547ms
,I/BackupManagerService(  821): Backup pass finished.
,D/SystemUpdateService( 1769): onDestroy
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/iu.SyncManager( 1769): SYNC; picasa accounts
I/art     ( 1246): Explicit concurrent mark sweep GC freed 20131(1075KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.217ms total 54.831ms
,E/HttpOperation( 2982): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2982): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2982): 	at jdm.a(PG:82)
E/HttpOperation( 2982): 	at jcs.o(PG:406)
E/HttpOperation( 2982): 	at jcn.a(PG:1379)
E/HttpOperation( 2982): 	at jcs.i(PG:143)
E/HttpOperation( 2982): 	at blb.a(PG:3937)
E/HttpOperation( 2982): 	at czp.a(PG:18188)
E/HttpOperation( 2982): 	at czp.a(PG:9081)
E/HttpOperation( 2982): 	at czq.run(PG:1686)
E/HttpOperation( 2982): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2982): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2982): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2982): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2982): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2982): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2982): 	at jdj.a(PG:4091)
E/HttpOperation( 2982): 	at jdj.a(PG:1125)
E/HttpOperation( 2982): 	at jdm.a(PG:77)
E/HttpOperation( 2982): 	... 12 more
E/HttpOperation( 2982): Caused by: faj: BadAuthentication
E/HttpOperation( 2982): 	at fal.a(PG:38)
E/HttpOperation( 2982): 	at jdj.a(PG:4089)
E/HttpOperation( 2982): 	... 14 more
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/NetworkLogImpl( 1769): Loaded NetworkSpeedPredictor
I/iu.Environment( 1769): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,W/ExperimentUpdateService( 3325): [330] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3325): [330] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3325): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3325): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3325): 	at com.a.a.k.run(SourceFile:110)
I/iu.UploadsManager( 1769): num queued entries: 0
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/iu.UploadsManager( 1769): num updated entries: 0
,D/ChimeraCfgMgr( 1769): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1769): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/iu.SyncManager( 1769): NEXT; no task
,I/art     (  821): Explicit concurrent mark sweep GC freed 59222(3MB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.520ms total 63.643ms
,W/ExperimentUpdateService( 3325): [331] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3325): [331] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3325): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3325): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3325): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  821): Start proc 3426:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,E/HttpOperation( 2982): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2982): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2982): 	at jdm.a(PG:82)
E/HttpOperation( 2982): 	at jcs.o(PG:406)
E/HttpOperation( 2982): 	at jcn.a(PG:1379)
E/HttpOperation( 2982): 	at jcs.i(PG:143)
E/HttpOperation( 2982): 	at hec.a(PG:42)
E/HttpOperation( 2982): 	at hee.a(PG:102)
E/HttpOperation( 2982): 	at czr.a(PG:65)
E/HttpOperation( 2982): 	at kka.a(PG:108)
E/HttpOperation( 2982): 	at czp.a(PG:19176)
E/HttpOperation( 2982): 	at czp.a(PG:9081)
E/HttpOperation( 2982): 	at czq.run(PG:1686)
E/HttpOperation( 2982): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2982): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2982): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2982): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2982): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2982): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2982): 	at jdj.a(PG:4091)
E/HttpOperation( 2982): 	at jdj.a(PG:1125)
E/HttpOperation( 2982): 	at jdm.a(PG:77)
E/HttpOperation( 2982): 	... 15 more
E/HttpOperation( 2982): Caused by: faj: BadAuthentication
E/HttpOperation( 2982): 	at fal.a(PG:38)
E/HttpOperation( 2982): 	at jdj.a(PG:4089)
E/HttpOperation( 2982): 	... 17 more
E/ExperimentLoader( 2982): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2982): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2982): 	at jdm.a(PG:82)
E/ExperimentLoader( 2982): 	at jcs.o(PG:406)
E/ExperimentLoader( 2982): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2982): 	at jcs.i(PG:143)
E/ExperimentLoader( 2982): 	at hec.a(PG:42)
E/ExperimentLoader( 2982): 	at hee.a(PG:102)
E/ExperimentLoader( 2982): 	at czr.a(PG:65)
E/ExperimentLoader( 2982): 	at kka.a(PG:108)
E/ExperimentLoader( 2982): 	at czp.a(PG:19176)
E/ExperimentLoader( 2982): 	at czp.a(PG:9081)
E/ExperimentLoader( 2982): 	at czq.run(PG:1686)
E/ExperimentLoader( 2982): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2982): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2982): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2982): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2982): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2982): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2982): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2982): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2982): 	at jdm.a(PG:77)
E/ExperimentLoader( 2982): 	... 15 more
E/ExperimentLoader( 2982): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2982): 	at fal.a(PG:38)
E/ExperimentLoader( 2982): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2982): 	... 17 more
,V/KeepSync( 3397): Connecting to GoogleApiClient
,I/VacuumService( 1246): Vacuum at: now=1457078853909 tag=VacuumService
,I/GoogleURLConnFactory( 1246): Using platform SSLCertificateSocketFactory
,W/Uploader( 1246): No account for auth token provided
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 36917, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,W/BaseAppContext( 1769): Using Auth Proxy for data requests.
,I/GAv4    ( 3426): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3426):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3426):   adb logcat -s GAv4
,I/ActivityManager(  821): Start proc 3461:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,W/BaseAppContext( 1769): Using Auth Proxy for data requests.
,W/GAv4    ( 3426): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3426): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GAv4    ( 3426): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1769): Handling authorization failure
E/ClientConnectionOperation( 1769): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1769): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1769): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1769): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1769): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1769): 	... 7 more
,V/KeepSync( 3397): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3397): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3397): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3397): (284) automatic index on blob_node(is_deleted)
,I/Babel   ( 2615): connection state changed from DISCONNECTED to CONNECTED
,I/ActivityManager(  821): Killing 2405:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3397): IOException
E/KeepSync( 3397): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3397): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3397): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3397): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3397): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3397): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3397): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3397): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3397): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3397): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3397): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3397): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3397): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3397): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3397): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3397): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3397): 	... 10 more
W/KeepSync( 3397): Sync result 2
,I/ActivityManager(  821): Killing 2749:com.google.android.gm/u0a78 (adj 15): empty #17
D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 36922, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/GCM     ( 1246): Connected
,D/GCM     ( 1246): Message class com.google.f.a.a.p
,I/WebViewFactory( 3426): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3426): Time to load native libraries: 2 ms (timestamps 8399-8401)
,I/LibraryLoader( 3426): Expected native library version number "",actual native library version number ""
,W/Uploader( 1246): No account for auth token provided
,V/WebViewChromiumFactoryProvider( 3426): Binding Chromium to main looper Looper (main, tid 1) {278133ea}
I/LibraryLoader( 3426): Expected native library version number "",actual native library version number ""
,I/chromium( 3426): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3426): Initializing chromium process, singleProcess=true
W/art     ( 3426): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3426): ApplicationContext is null in ApplicationStatus
,W/chromium( 3426): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3426): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3426): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3426): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/GAV2    ( 3461): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3461): Created application version: 3.6.8 (30608)
,W/AudioManagerAndroid( 3426): Requires BLUETOOTH permission
,I/NSApplication( 3426): Starting up...
,I/ActivityManager(  821): Start proc 3518:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,I/ActivityManager(  821): Killing 2342:com.google.android.calendar/u0a37 (adj 15): empty #17
,W/Uploader( 1246): No account for auth token provided
,I/art     ( 1246): Explicit concurrent mark sweep GC freed 21328(1252KB) AllocSpace objects, 5(362KB) LOS objects, 37% free, 26MB/42MB, paused 1.357ms total 39.795ms
,I/BooksSync( 3461): Starting books sync for 61035162, extras: ade
,W/Uploader( 1246): No account for auth token provided
,I/BooksConfig( 3461): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1246): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1246): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1246): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1246): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1246): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1246): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1246): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  821): Start proc 3548:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
I/ActivityManager(  821): Killing 2920:com.android.providers.calendar/u0a3 (adj 15): empty #17
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3461): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3461): Soft error
E/BooksSync( 3461): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3461): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3461): Sync error
E/BooksSync( 3461): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3461): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3461): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 36922, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  821): Killing 3085:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  821): Killing 1461:android.process.acore/u0a5 (adj 15): empty #18
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1246): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1246): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1246): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1246): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1246): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1246): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1246): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1246): No account for auth token provided
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 27824(1275KB) AllocSpace objects, 5(119KB) LOS objects, 31% free, 34MB/50MB, paused 2.113ms total 57.702ms
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1246): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1246): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1246): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1246): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1246): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1246): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1246): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/Finsky  ( 2688): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2688): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2688): [1] 5.onFinished: Scheduling replication attempt 5.
,W/Uploader( 1246): No account for auth token provided
,I/ActivityManager(  821): Killing 3106:com.android.musicfx/u0a18 (adj 15): empty #17
,W/Uploader( 1246): No account for auth token provided
,I/ActivityManager(  821): Start proc 3565:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,W/Uploader( 1246): No account for auth token provided
,E/SQLiteLog( 3565): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  821): Start proc 3585:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,W/Uploader( 1246): No account for auth token provided
,W/ResourcesManager( 3585): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3585): Created com.android.providers.calendar.CalendarAlarmManager@1da800b8(com.android.providers.calendar.CalendarProvider2@17108e91)
,I/AnalyticsLogBase( 3565): PlayLogger.onLoggerConnected
,I/ActivityManager(  821): Start proc 3607:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/ActivityManager(  821): Killing 1843:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,D/TimeService( 3607): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1457078856790
D/        ( 3607): TimeServiceNative: User Time to be set is 1457078856790
D/QC-time-services( 3607): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3607): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3607): Lib:time_genoff_operation: pargs->ts_val = 1457078856790
D/QC-time-services(  373): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3607): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  373): Daemon:Received base = 2, unit = 1, operation = 0,value = 1457078856790,
,D/QC-time-services(  373): Daemon:genoff_opr: Base = 2, val = 1457078856790, operation = 0
D/QC-time-services(  373): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS6/21/70 4:19:35
D/QC-time-services(  373): Daemon:Value read from RTC seconds = 17381975000
D/QC-time-services(  373): Daemon:new time 1457078856790 
D/QC-time-services(  373): Daemon: delta 1439696881790 genoff 1439696881790 
D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696881790 to memory
,D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  373): Updating the TOD offset
D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696881790 to memory
D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  373): Daemon:Update to modem bit set
,D/QC-time-services(  373): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  373): Daemon: Base = 2, Value being sent to MODEM = 1141114056790
,E/QC-time-services( 3607): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  373): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  373): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,W/Uploader( 1246):  no longer exists, so no auth token.
,I/ActivityManager(  821): Start proc 3626:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/ActivityManager(  821): Killing 3137:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,W/Uploader( 1246): No account for auth token provided
,I/GAv4    ( 3626): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3626):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3626):   adb logcat -s GAv4
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAv4    ( 3626): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3626): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3626): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/Uploader( 1246): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1246): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1246): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1246): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1246): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1246): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1246): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/ActivityManager(  821): Killing 3038:com.android.defcontainer/u0a7 (adj 15): empty #17
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Herrevad( 1769): NQAS connected
,D/WifiService(  821): New client listening to asynchronous messages
,E/Uploader( 1246): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1246): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1246): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1246): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1246): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1246): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1246): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1246): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/art     ( 1769): Explicit concurrent mark sweep GC freed 14286(1111KB) AllocSpace objects, 14(224KB) LOS objects, 35% free, 28MB/44MB, paused 1.311ms total 59.024ms
,I/CalendarProvider2( 3585): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3585): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel   ( 2615): UserRecoverableAuthException.
,E/Babel   ( 2615): eei: BadAuthentication
E/Babel   ( 2615): 	at eeg.a(Unknown Source)
E/Babel   ( 2615): 	at eeg.a(Unknown Source)
E/Babel   ( 2615): 	at eeg.a(Unknown Source)
E/Babel   ( 2615): 	at g.a(Unknown Source)
E/Babel   ( 2615): 	at cae.a(SourceFile:3089)
E/Babel   ( 2615): 	at cae.a(SourceFile:1131)
E/Babel   ( 2615): 	at cws.a(SourceFile:4333)
E/Babel   ( 2615): 	at cws.a(SourceFile:1419)
E/Babel   ( 2615): 	at crl.a(SourceFile:492)
E/Babel   ( 2615): 	at crl.a(SourceFile:1468)
E/Babel   ( 2615): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2615): 	at cas.b(SourceFile:106)
E/Babel   ( 2615): 	at cap.d(SourceFile:335)
E/Babel   ( 2615): 	at caq.run(SourceFile:81)
E/Babel   ( 2615): Error getting auth token
E/Babel   ( 2615): dvm
E/Babel   ( 2615): 	at g.a(Unknown Source)
E/Babel   ( 2615): 	at cae.a(SourceFile:3089)
E/Babel   ( 2615): 	at cae.a(SourceFile:1131)
E/Babel   ( 2615): 	at cws.a(SourceFile:4333)
E/Babel   ( 2615): 	at cws.a(SourceFile:1419)
E/Babel   ( 2615): 	at crl.a(SourceFile:492)
E/Babel   ( 2615): 	at crl.a(SourceFile:1468)
E/Babel   ( 2615): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2615): 	at cas.b(SourceFile:106)
E/Babel   ( 2615): 	at cap.d(SourceFile:335)
E/Babel   ( 2615): 	at caq.run(SourceFile:81)
,E/Babel   ( 2615): Account registration failed 1-Redacted-21
,E/Babel   ( 2615): cyp: null -- null,
E/Babel   ( 2615): 	at cae.a(SourceFile:3121)
E/Babel   ( 2615): 	at cae.a(SourceFile:1131)
E/Babel   ( 2615): 	at cws.a(SourceFile:4333)
E/Babel   ( 2615): ,	at cws.a(SourceFile:1419)
E/Babel   ( 2615): 	at crl.a(SourceFile:492)
E/Babel   ( 2615): 	at crl.a(SourceFile:1468)
E/Babel   ( 2615): 	,at cqu.a(SourceFile:4416)
E/Babel   ( 2615): 	at cas.b(SourceFile:106)
E/Babel   ( 2615): 	at cap.d(SourceFile:335)
E/Babel   ( 2615): 	at caq.run(SourceFile:81)
,I/art     ( 2615): Note: end time exceeds epoch: ,
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native,
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1246): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Babel   ( 2615): Unexpected exception while authenticating.,
,E/Babel   ( 2615): eej: User intervention required. Notification has been pushed.,
,E/Babel   ( 2615): ,	,at eeg.b(Unknown Source)
E/Babel   ( 2615): 	at eeg.b(Unknown Source)
E/Babel   ( 2615): 	at g.a(Unknown Source)
E/Babel   ( 2615): 	at cae.b(SourceFile:1146)
E/Babel   ( 2615): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2615): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2615): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2615): 	at java.lang.Thread.run(Thread.java:818)
,W/Uploader( 1246): No account for auth token provided
,E/SQLiteLog( 3585): (284) automatic index on view_events(_id)
,I/GAV2    ( 3461): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 3565): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  821): Killing 1572:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,D/WifiService(  821): Client connection lost with reason: 4
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,I/art     (  821): Explicit concurrent mark sweep GC freed 16354(783KB) AllocSpace objects, 4(441KB) LOS objects, 31% free, 34MB/50MB, paused 1.398ms total 93.212ms
,D/Finsky  ( 2688): [273] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2688): [273] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@368a2db7}
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1246): Explicit concurrent mark sweep GC freed 45066(2MB) AllocSpace objects, 4(353KB) LOS objects, 36% free, 27MB/43MB, paused 1.724ms total 62.974ms
,D/Finsky  ( 2688): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2688): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2688): [1] 5.onFinished: Giving up after 6 failures.
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2982): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2982): java.io.IOException: Cannot obtain authentication token
,E/HttpOperation( 2982): 	at jdm.a(PG:82)
E/HttpOperation( 2982): 	at jcs.o(PG:406)
E/HttpOperation( 2982): 	at jcn.a(PG:1379)
E/HttpOperation( 2982): 	,at jcs.i(PG:143)
E/HttpOperation( 2982): 	at blb.a(PG:3937)
E/HttpOperation( 2982): 	at czp.a(PG:18188)
E/HttpOperation( 2982): 	at czp.a(PG:9081)
E/HttpOperation( 2982): 	at czq.run(PG:1686)
E/HttpOperation( 2982): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422),
E/HttpOperation( 2982): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2982): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2982): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2982): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2982): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2982): 	at jdj.a(PG:4091)
E/HttpOperation( 2982): 	at jdj.a(PG:1125)
E/HttpOperation( 2982): 	at jdm.a(PG:77)
E/HttpOperation( 2982): 	... 12 more
E/HttpOperation( 2982): Caused by: faj: BadAuthentication
E/HttpOperation( 2982): 	at fal.a(PG:38)
E/HttpOperation( 2982): 	at jdj.a(PG:4089)
E/HttpOperation( 2982): 	... 14 more
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2982): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2982): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2982): 	at jdm.a(PG:82)
E/HttpOperation( 2982): 	at jcs.o(PG:406)
E/HttpOperation( 2982): 	at jcn.a(PG:1379)
E/HttpOperation( 2982): 	at jcs.i(PG:143)
E/HttpOperation( 2982): 	at hec.a(PG:42)
E/HttpOperation( 2982): 	at hee.a(PG:102)
E/HttpOperation( 2982): 	at czr.a(PG:65)
E/HttpOperation( 2982): 	at kka.a(PG:108)
E/HttpOperation( 2982): 	at czp.a(PG:19176)
E/HttpOperation( 2982): 	at czp.a(PG:9081)
E/HttpOperation( 2982): 	at czq.run(PG:1686)
E/HttpOperation( 2982): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2982): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2982): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2982): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2982): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2982): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2982): 	at jdj.a(PG:4091)
E/HttpOperation( 2982): 	at jdj.a(PG:1125)
E/HttpOperation( 2982): 	at jdm.a(PG:77)
E/HttpOperation( 2982): 	... 15 more
E/HttpOperation( 2982): Caused by: faj: BadAuthentication
E/HttpOperation( 2982): 	at fal.a(PG:38)
E/HttpOperation( 2982): 	at jdj.a(PG:4089)
E/HttpOperation( 2982): 	... 17 more
E/ExperimentLoader( 2982): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2982): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2982): 	at jdm.a(PG:82)
E/ExperimentLoader( 2982): 	at jcs.o(PG:406)
E/ExperimentLoader( 2982): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2982): 	at jcs.i(PG:143)
E/ExperimentLoader( 2982): 	at hec.a(PG:42)
E/ExperimentLoader( 2982): 	at hee.a(PG:102)
E/ExperimentLoader( 2982): 	at czr.a(PG:65)
E/ExperimentLoader( 2982): 	at kka.a(PG:108)
E/ExperimentLoader( 2982): 	at czp.a(PG:19176)
E/ExperimentLoader( 2982): 	at czp.a(PG:9081)
E/ExperimentLoader( 2982): 	at czq.run(PG:1686)
E/ExperimentLoader( 2982): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2982): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2982): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2982): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2982): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2982): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2982): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2982): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2982): 	at jdm.a(PG:77)
E/ExperimentLoader( 2982): 	... 15 more
E/ExperimentLoader( 2982): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2982): 	at fal.a(PG:38)
E/ExperimentLoader( 2982): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2982): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 208868, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3325): [332] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3325): [333] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ExperimentUpdateService( 3325): [332] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3325): [332] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3325): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3325): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3325): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3325): [333] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3325): [333] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3325): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3325): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3325): 	at com.a.a.k.run(SourceFile:110)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1227): run()
I/Keyboard.Facilitator( 1227): flushDynamicLanguageModels()
,I/ConfigService( 1246): onCreate
,I/ConfigService( 1246): onDestroy
,I/BooksSync( 3461): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3397): Connecting to GoogleApiClient
,I/BooksConfig( 3461): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1769): Handling authorization failure
E/ClientConnectionOperation( 1769): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1769): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1769): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1769): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1769): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1769): 	... 7 more
,V/KeepSync( 3397): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3397): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3397): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3397): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 3461): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3461): Soft error
E/BooksSync( 3461): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3461): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3461): Sync error
E/BooksSync( 3461): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3461): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3461): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 212275, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3397): IOException
E/KeepSync( 3397): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3397): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3397): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3397): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3397): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3397): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3397): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3397): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3397): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3397): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3397): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3397): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3397): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3397): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3397): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3397): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3397): 	... 10 more
W/KeepSync( 3397): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 209867, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,I/jxcore-log( 3176): Reconnected to the test server
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): TAP version 13
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # setup
,I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # 1. multiplex can send data
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # teardown
,I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 1 String should be length:200
,I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # setup
,I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # 2. enqueue and run in order
,I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # teardown
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 2 firstPromise setTimeout
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 3 firstPromise result
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 4 firstPromise testValue
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 5 secondPromise setTimeout
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 6 secondPromise result
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 7 secondPromise testValue
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 8 thirdPromise in promise
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 9 thirdPromise result
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 10 thirdPromise testValue
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # setup
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # 3. enqueueAtTop and run backwards
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # teardown
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 11 thirdPromise - first to run
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 12 thirdPromise - in resolve
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 13 secondPromise - second to run
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 14 secondPromise - in catch
I/jxcore-log( 3176): 
I/jxcore-log( 3176): ok 15 firstPromise - third to run
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 16 firstPromise - in then
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 17 testing promises
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # setup
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # 4. mix enqueue and enqueueAtTop
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # teardown
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 18 fourth
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 19 fourth
I/jxcore-log( 3176): 
I/jxcore-log( 3176): ok 20 second
I/jxcore-log( 3176): 
I/jxcore-log( 3176): ok 21 secondPromise - in then
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 22 first
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 23 firstPromise - in catch
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 24 third
I/jxcore-log( 3176): 
I/jxcore-log( 3176): ok 25 thirdPromise - in then
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 26 testingPromises
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # setup,
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # 5. queues handled independently
I/jxcore-log( 3176): ,
,I/jxcore-log( 3176): # teardown
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 27 all short operations completed before the long resolves
I/jxcore-log( 3176): 
I/jxcore-log( 3176): # setup
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # 6. basic
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # teardown
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 28 sane
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # setup
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # 7. another
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # teardown
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 29 sane
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # setup
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # 8. #startListeningForAdvertisements should fail if start not called
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # teardown
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 30 specific error should be returned
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # setup
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 31 error should be null
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 32 error should be null
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # 9. #startUpdateAdvertisingAndListening should fail if start not called
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # teardown
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 33 specific error should be returned
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # setup
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 34 error should be null
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 35 error should be null
I/jxcore-log( 3176): 
I/jxcore-log( 3176): # 10. should be able to call #stopListeningForAdvertisements many times
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # teardown
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 36 error should be null
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 37 error should be null
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 38 error should be null
I/jxcore-log( 3176): 
I/jxcore-log( 3176): ok 39 error should be null
I/jxcore-log( 3176): 
I/jxcore-log( 3176): # setup
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 40 error should be null
I/jxcore-log( 3176): 
I/jxcore-log( 3176): ok 41 error should be null
I/jxcore-log( 3176): 
I/jxcore-log( 3176): # 11. should be able to call #startListeningForAdvertisements many times
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # teardown
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 42 error should be null
I/jxcore-log( 3176): 
I/jxcore-log( 3176): ok 43 error should be null
I/jxcore-log( 3176): 
I/jxcore-log( 3176): ok 44 error should be null
I/jxcore-log( 3176): 
I/jxcore-log( 3176): ok 45 error should be null
I/jxcore-log( 3176): 
I/jxcore-log( 3176): # setup
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
I/jxcore-log( 3176): 
I/jxcore-log( 3176): ok 46 error should be null
I/jxcore-log( 3176): 
I/jxcore-log( 3176): ok 47 error should be null
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # 12. should be able to call #startUpdateAdvertisingAndListening many times
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # teardown
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 48 error should be null
,I/jxcore-log( 3176): 
I/jxcore-log( 3176): ok 49 error should be null
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 50 error should be null,
I/jxcore-log( 3176): 
I/jxcore-log( 3176): ok 51 error should be null
I/jxcore-log( 3176): 
I/jxcore-log( 3176): # setup
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).,
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 52 error should be null,
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 53 error should be null
I/jxcore-log( 3176): ,
I/jxcore-log( 3176): # 13. should be able to call #stopAdvertisingAndListening many times
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # teardown,
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 54 error should be null,
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 55 error should be null,
I/jxcore-log( 3176): 
I/jxcore-log( 3176): ok 56 error should be null,
I/jxcore-log( 3176): 
I/jxcore-log( 3176): ok 57 error should be null,
I/jxcore-log( 3176): 
I/jxcore-log( 3176): # setup,
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 58 error should be null,
I/jxcore-log( 3176): 
I/jxcore-log( 3176): ok 59 error should be null
,I/jxcore-log( 3176): 
I/jxcore-log( 3176): # 14. #start should fail if called twice in a row,
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # teardown,
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 60 first call should succeed,
I/jxcore-log( 3176): 
I/jxcore-log( 3176): ok 61 first call should succeed
,I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 62 specific error should be returned
I/jxcore-log( 3176): 
I/jxcore-log( 3176): # setup
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 63 error should be null
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 64 error should be null
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # 15. does not emit duplicate discoveryAdvertisingStateUpdate
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # teardown
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 65 called only once
I/jxcore-log( 3176): ,
I/jxcore-log( 3176): ok 66 discovery state matches
I/jxcore-log( 3176): 
I/jxcore-log( 3176): ok 67 advertising state matches
I/jxcore-log( 3176): ,
,I/jxcore-log( 3176): # setup
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): INFO thaliMobile Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
I/jxcore-log( 3176): 
I/jxcore-log( 3176): INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 68 error should be null
I/jxcore-log( 3176): 
I/jxcore-log( 3176): ok 69 error should be null
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # 16. does not send duplicate availability changes
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # teardown
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 70 should be called once
,I/jxcore-log( 3176): 
I/jxcore-log( 3176): ok 71 should not have been called more than once
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # setup
,I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 72 error should be null
,I/jxcore-log( 3176): 
I/jxcore-log( 3176): ok 73 error should be null
I/jxcore-log( 3176): 
I/jxcore-log( 3176): # 17. can get the network status
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # teardown
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): not ok 74 network status should have certain non-empty properties
,I/jxcore-log( 3176): 
I/jxcore-log( 3176):   ---
I/jxcore-log( 3176): 
I/jxcore-log( 3176):     operator: throws
I/jxcore-log( 3176): 
,I/jxcore-log( 3176):     expected: |-
I/jxcore-log( 3176): 
I/jxcore-log( 3176):       undefined
I/jxcore-log( 3176): 
,I/jxcore-log( 3176):     actual: |-
I/jxcore-log( 3176): 
I/jxcore-log( 3176):       [TypeError: undefined must be a string]
I/jxcore-log( 3176): 
,I/jxcore-log( 3176):   ...
I/jxcore-log( 3176): 
I/jxcore-log( 3176): # setup
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 75 error should be null
,I/jxcore-log( 3176): 
I/jxcore-log( 3176): ok 76 error should be null
I/jxcore-log( 3176): 
I/jxcore-log( 3176): # 18. wifi peer is marked unavailable if announcements stop
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # teardown
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 77 host address should match
I/jxcore-log( 3176): 
I/jxcore-log( 3176): ok 78 port should match
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 79 host address should be null
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 80 port should should be null
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # setup
,I/jxcore-log( 3176): 
,I/jxcore-log( 3176): INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,I/jxcore-log( 3176): 
,I/jxcore-log( 3176): ok 81 error should be null
I/jxcore-log( 3176): ,
I/jxcore-log( 3176): ok 82 error should be null
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # 19. Can call start/stopListeningForAdvertisements
,I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # teardown,
I/jxcore-log( 3176): 
,I/io.jxcore.node.ConnectionHelper( 3176): start: Port number: -1, start advertisements: false
,I/io.jxcore.node.ConnectivityInfo( 3176): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 3176):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 3176): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
D/io.jxcore.node.ConnectivityInfo( 3176): startMonitoring: OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3176): bind: Binding a new listener
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3176): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3176): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:CF:C5:D9:E5:61"}
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3176): setConnectionTimeout: 15000 -> 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3176): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): start: OK
I/io.jxcore.node.ConnectionHelper( 3176): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): start: Discovery mode: BLE, start discovery: true, start advertiser: false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3176): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3176): bind: Binding a new listener
,V/io.jxcore.node.ConnectivityInfo( 3176): setIsWifiEnabled: true,
I/io.jxcore.node.ConnectivityInfo( 3176): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 3176):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - force notify: true
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/io.jxcore.node.JXcoreExtension( 3176): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
W/BluetoothAdapter( 3176): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3176): Waiting for incoming connections...
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3176): setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3176): setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils( 3176): createScanFilter: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", use manufacturer ID: false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils( 3176): createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=b6a44ad1-d319-4b3a-815d-8b805a47fb51, mUuidMask=11111111-1111-1111-1110-000000000000, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3176): startScanner: Starting...
,D/BtGatt.GattService( 2117): registerClient() - UUID=9946d7e6-9e3f-4b69-bd0c-f78d4e23a85c
,D/BtGatt.GattService( 2117): onClientRegistered() - UUID=9946d7e6-9e3f-4b69-bd0c-f78d4e23a85c, clientIf=5
D/BluetoothLeScanner( 3176): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.GattService( 2117): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3176): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): startBlePeerDiscoverer: OK
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BtGatt.ScanManager( 2117): handling starting scan
,D/BluetoothAdapterService( 2117): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32a311f6
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,I/io.jxcore.node.ConnectionHelper( 3176): onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): start: OK
,I/io.jxcore.node.ConnectionHelper( 3176): start: OK
,I/jxcore-log( 3176): ok 83 Can call startListeningForAdvertisements without error
I/jxcore-log( 3176): 
I/io.jxcore.node.ConnectionHelper( 3176): stopListeningForAdvertisements
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): stopDiscovery
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3176): stopScanner: Stopping...
D/BtGatt.GattService( 2117): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): addFilterToController: 2
D/BtGatt.GattService( 2117): stopScan() - queue size =1
,D/BtGatt.GattService( 2117): onScanFilterConfig() - clientIf=5, action = 0 status = 0, filterType=2, availableSpace=47
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): unregisterClient() - clientIf=5
D/BtGatt.GattService( 2117): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3176): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3176): setState: State changed from STARTING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3176): onIsScannerStartedChanged: false
D/BtGatt.ScanManager( 2117): Starting BLE batch scan
D/BtGatt.ScanManager( 2117): configuring batch scan storage, appIf 5
,D/BtGatt.GattService( 2117): onBatchScanStorageConfigured() - clientIf=5, status=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
I/jxcore-log( 3176): ok 84 Can call stopListeningForAdvertisements without error
I/jxcore-log( 3176): 
D/BtGatt.GattService( 2117): onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2117): stopping BLe Batch
,D/BtGatt.GattService( 2117): onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
I/jxcore-log( 3176): # setup
I/jxcore-log( 3176): 
D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,I/jxcore-log( 3176): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"on","blueTooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"on","blueTooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
I/jxcore-log( 3176): 
,I/io.jxcore.node.ConnectionHelper( 3176): stopListeningForAdvertisements
,D/BluetoothLeScanner( 3176): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3176): stop: Stopped
,I/jxcore-log( 3176): ok 85 Should be able to call stopListeningForAdvertisments in teardown,
I/jxcore-log( 3176): ,
I/io.jxcore.node.ConnectionHelper( 3176): stop: Stopping all activities and killing all connections...
,D/io.jxcore.node.HandshakeHelper( 3176): shutdown
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3176): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3176): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3176): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3176): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3176): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3176): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): stopForRestart
,D/org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper( 3176): stopProvideBluetoothMacAddressMode
,I/io.jxcore.node.ConnectionHelper( 3176): onConnectionManagerStateChanged: NOT_STARTED,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3176): stopScannerAndAdvertiser
,D/BluetoothLeScanner( 3176): could not find callback wrapper
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3176): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3176): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): stopBlePeerDiscoverer: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3176): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3176): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): updateState: State: NOT_STARTED, is discovering: false, is advertising: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): start: Discovery mode: BLE, start discovery: false, start advertiser: false
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3176): bind: Binding a new listener
D/io.jxcore.node.ConnectivityInfo( 3176): stopMonitoring: Stopped
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3176): ok 86 Should be able to call stopAdvertisingAndListening in teardown
I/jxcore-log( 3176): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3176): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3176): bind: Binding a new listener
I/jxcore-log( 3176): # 20. Calling startListeningForAdvertisements twice is NOT an error
I/jxcore-log( 3176): 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3176): setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3176): setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils( 3176): createScanFilter: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", use manufacturer ID: false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils( 3176): createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=b6a44ad1-d319-4b3a-815d-8b805a47fb51, mUuidMask=11111111-1111-1111-1110-000000000000, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): start: Discovery mode: BLE, start discovery: false, start advertiser: false
,I/io.jxcore.node.ConnectionHelper( 3176): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
V/io.jxcore.node.ConnectivityInfo( 3176): setIsWifiEnabled: true
,I/jxcore-log( 3176): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
I/jxcore-log( 3176): 
,I/io.jxcore.node.ConnectivityInfo( 3176): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 3176):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 3176): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
I/jxcore-log( 3176): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"on","blueTooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # teardown
I/jxcore-log( 3176): 
,I/io.jxcore.node.ConnectionHelper( 3176): start: Port number: -1, start advertisements: false
D/io.jxcore.node.HandshakeHelper( 3176): reinitiate
,I/io.jxcore.node.ConnectivityInfo( 3176): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 3176):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - force notify: true
,D/io.jxcore.node.JXcoreExtension( 3176): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
D/io.jxcore.node.ConnectivityInfo( 3176): startMonitoring: OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3176): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3176): setConnectionTimeout: 15000 -> 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3176): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): start: Discovery mode: BLE, start discovery: true, start advertiser: false
I/io.jxcore.node.ConnectionHelper( 3176): onConnectionManagerStateChanged: RUNNING
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3176): startScanner: Starting...
W/BluetoothAdapter( 3176): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3176): Waiting for incoming connections...
,D/BtGatt.GattService( 2117): registerClient() - UUID=67e7f90e-72ab-4eed-843e-08ea1344a2b0
,D/BtGatt.GattService( 2117): onClientRegistered() - UUID=67e7f90e-72ab-4eed-843e-08ea1344a2b0, clientIf=5
D/BluetoothLeScanner( 3176): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.GattService( 2117): start scan with filters
D/BtGatt.ScanManager( 2117): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3176): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): startBlePeerDiscoverer: OK
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BtGatt.GattService( 2117): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): addFilterToController: 2
D/BtGatt.GattService( 2117): onScanFilterConfig() - clientIf=5, action = 0 status = 0, filterType=2, availableSpace=47
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2117): Starting BLE batch scan
D/BtGatt.ScanManager( 2117): configuring batch scan storage, appIf 5
,D/BtGatt.GattService( 2117): onBatchScanStorageConfigured() - clientIf=5, status=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,I/io.jxcore.node.ConnectionHelper( 3176): onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): start: OK
I/io.jxcore.node.ConnectionHelper( 3176): start: OK
,I/jxcore-log( 3176): ok 87 Can call startListeningForAdvertisements without error
I/jxcore-log( 3176): 
I/io.jxcore.node.ConnectionHelper( 3176): start: Port number: -1, start advertisements: false
V/io.jxcore.node.ConnectivityInfo( 3176): startMonitoring: Already started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): start
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): start: Already running, call stop() first in order to restart
V/io.jxcore.node.ConnectionHelper( 3176): start: Discovery manager already running
,I/io.jxcore.node.ConnectionHelper( 3176): start: OK
I/jxcore-log( 3176): ok 88 Can call startListeningForAdvertisements twice without error
I/jxcore-log( 3176): 
I/jxcore-log( 3176): # setup
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"on","blueTooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 3176): 
I/jxcore-log( 3176): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
I/jxcore-log( 3176): 
,I/io.jxcore.node.ConnectionHelper( 3176): stopListeningForAdvertisements
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): stopDiscovery
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3176): stopScanner: Stopping...
,D/BtGatt.GattService( 2117): stopScan() - queue size =1
,D/BtGatt.GattService( 2117): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,D/BtGatt.GattService( 2117): unregisterClient() - clientIf=5
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2117): stopping BLe Batch
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3176): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3176): setState: State changed from STARTING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3176): onIsScannerStartedChanged: false
D/BtGatt.GattService( 2117): onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,I/jxcore-log( 3176): ok 89 Should be able to call stopListeningForAdvertisments in teardown
I/jxcore-log( 3176): 
,I/io.jxcore.node.ConnectionHelper( 3176): stop: Stopping all activities and killing all connections...
D/io.jxcore.node.HandshakeHelper( 3176): shutdown
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3176): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3176): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3176): shutdown
D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3176): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3176): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3176): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3176): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper( 3176): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3176): stopScannerAndAdvertiser
D/BluetoothLeScanner( 3176): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3176): stop: Stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3176): stop: Stopped
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): stopBlePeerDiscoverer: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3176): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3176): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): start: Discovery mode: BLE, start discovery: false, start advertiser: false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3176): bind: Binding a new listener
,D/io.jxcore.node.ConnectivityInfo( 3176): stopMonitoring: Stopped
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/jxcore-log( 3176): ok 90 Should be able to call stopAdvertisingAndListening in teardown
I/jxcore-log( 3176): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3176): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3176): bind: Binding a new listener
,I/jxcore-log( 3176): # 21. Can call start/stopUpdateAdvertisingAndListening
I/jxcore-log( 3176): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3176): setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3176): setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils( 3176): createScanFilter: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", use manufacturer ID: false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils( 3176): createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=b6a44ad1-d319-4b3a-815d-8b805a47fb51, mUuidMask=11111111-1111-1111-1110-000000000000, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): start: Discovery mode: BLE, start discovery: false, start advertiser: false
,I/io.jxcore.node.ConnectionHelper( 3176): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,V/io.jxcore.node.ConnectivityInfo( 3176): setIsWifiEnabled: true
I/jxcore-log( 3176): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
I/jxcore-log( 3176): 
I/io.jxcore.node.ConnectivityInfo( 3176): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Bluetooth enabled: true
,I/io.jxcore.node.ConnectivityInfo( 3176):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 3176):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 3176): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
I/jxcore-log( 3176): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"on","blueTooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # teardown
I/jxcore-log( 3176): 
,I/io.jxcore.node.ConnectionHelper( 3176): start: Port number: 4242, start advertisements: true
,D/io.jxcore.node.HandshakeHelper( 3176): reinitiate
,I/io.jxcore.node.ConnectivityInfo( 3176): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 3176):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - force notify: true
,D/io.jxcore.node.JXcoreExtension( 3176): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
D/io.jxcore.node.ConnectivityInfo( 3176): startMonitoring: OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): start
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3176): bind: Binding a new listener
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3176): setConnectionTimeout: 15000 -> 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3176): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): start: OK
I/io.jxcore.node.ConnectionHelper( 3176): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): start: Discovery mode: BLE, start discovery: true, start advertiser: true
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3176): startScannerAndAdvertiser
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3176): startScanner: Starting...
,W/BluetoothAdapter( 3176): getBluetoothService() called with no BluetoothManagerCallback
,D/BtGatt.GattService( 2117): registerClient() - UUID=1fabaccd-161e-42b6-96d8-38f2d5d7db01
D/BtGatt.GattService( 2117): onClientRegistered() - UUID=1fabaccd-161e-42b6-96d8-38f2d5d7db01, clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3176): Waiting for incoming connections...
D/BluetoothLeScanner( 3176): onClientRegistered() - status=0 clientIf=5
D/BtGatt.GattService( 2117): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3176): setState: State changed from NOT_STARTED to STARTING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3176): startAdvertiser: Starting...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3176): createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
D/BtGatt.ScanManager( 2117): handling starting scan
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3176): createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3176): setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,D/BtGatt.GattService( 2117): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2117): addFilterToController: 2
,D/BtGatt.GattService( 2117): onScanFilterConfig() - clientIf=5, action = 0 status = 0, filterType=2, availableSpace=47
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): Starting BLE batch scan
D/BtGatt.ScanManager( 2117): configuring batch scan storage, appIf 5
D/BtGatt.GattService( 2117): registerClient() - UUID=a3c73ea3-2dc3-4f06-9b35-bfb87eed7928
,D/BtGatt.GattService( 2117): onClientRegistered() - UUID=a3c73ea3-2dc3-4f06-9b35-bfb87eed7928, clientIf=6
D/BluetoothLeAdvertiser( 3176): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2117): onBatchScanStorageConfigured() - clientIf=5, status=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.AdvertiseManager( 2117): message : 0
,D/BtGatt.AdvertiseManager( 2117): starting multi advertising
,D/BtGatt.GattService( 2117): onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,D/BtGatt.GattService( 2117): onAdvertiseDataSet() - clientIf=6, status=0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3176): setState: State changed from NOT_STARTED to STARTING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3176): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): startBlePeerDiscoverer: OK
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3176): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3176): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3176): updateState: State changed from [NOT_STARTED] to [SCANNING, ADVERTISING]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING, ADVERTISING]
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): start: OK
I/io.jxcore.node.ConnectionHelper( 3176): start: OK
D/io.jxcore.node.JXcoreExtension( 3176): METHOD_NAME_START_UPDATE_ADVERTISING_AND_LISTENING: errorString == null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): updateState: State: NOT_STARTED, is discovering: true, is advertising: true
I/io.jxcore.node.ConnectionHelper( 3176): onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
I/io.jxcore.node.ConnectionHelper( 3176): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,I/jxcore-log( 3176): ok 91 Can call startUpdateAdvertisingAndListening without error
I/jxcore-log( 3176): 
I/io.jxcore.node.ConnectionHelper( 3176): stop: Stopping all activities and killing all connections...
D/io.jxcore.node.HandshakeHelper( 3176): shutdown
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3176): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3176): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3176): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3176): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3176): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3176): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3176): release: No more listeners, de-initializing...
I/io.jxcore.node.ConnectionHelper( 3176): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3176): release: No more listeners, de-initializing...
D/io.jxcore.node.ConnectivityInfo( 3176): stopMonitoring: Stopped
,I/jxcore-log( 3176): ok 92 Can call stopAdvertisingAndListening without error
I/jxcore-log( 3176): 
I/jxcore-log( 3176): # setup
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"on","blueTooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
I/jxcore-log( 3176): 
I/jxcore-log( 3176): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
I/jxcore-log( 3176): 
,I/io.jxcore.node.ConnectionHelper( 3176): stopListeningForAdvertisements
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3176): stopScanner: Stopping...
,D/BtGatt.GattService( 2117): stopScan() - queue size =1
,D/BtGatt.GattService( 2117): unregisterClient() - clientIf=5
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3176): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3176): setState: State changed from STARTING to NOT_STARTED
D/BtGatt.GattService( 2117): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3176): onIsScannerStartedChanged: false,
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3176): updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): updateState: State: NOT_STARTED, is discovering: false, is advertising: true
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2117): stopping BLe Batch
I/io.jxcore.node.ConnectionHelper( 3176): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: true
D/BtGatt.GattService( 2117): onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
I/jxcore-log( 3176): ok 93 Should be able to call stopListeningForAdvertisments in teardown,
I/jxcore-log( 3176): 
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,I/io.jxcore.node.ConnectionHelper( 3176): stop: Stopping all activities and killing all connections...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3176): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3176): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3176): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3176): release: No more listeners, de-initializing...,
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3176): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3176): release: No more listeners, de-initializing...,
I/jxcore-log( 3176): ok 94 Should be able to call stopAdvertisingAndListening in teardown
I/jxcore-log( 3176): 
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 266283125366
D/BtGatt.GattService( 2117): Batch record : [114, -121, -43, -12, -52, 87, 1, -128, -49, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
I/jxcore-log( 3176): # 22. Calling startUpdateAdvertisingAndListening twice is NOT an error
I/jxcore-log( 3176): ,
I/jxcore-log( 3176): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
I/jxcore-log( 3176): 
,I/jxcore-log( 3176): # teardown
,I/jxcore-log( 3176): 
,I/io.jxcore.node.ConnectionHelper( 3176): start: Port number: 4242, start advertisements: true,
D/io.jxcore.node.HandshakeHelper( 3176): reinitiate
,I/io.jxcore.node.ConnectivityInfo( 3176): updateConnectivityInfo: ,
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Bluetooth LE multiple advertisement supported: true,
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 3176):     - is connected/connecting to active network: true
,I/io.jxcore.node.ConnectivityInfo( 3176):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 3176): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
D/io.jxcore.node.ConnectivityInfo( 3176): startMonitoring: OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3176): bind: Binding a new listener,
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3176): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3176): setConnectionTimeout: 15000 -> 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3176): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3176): start: OK
I/io.jxcore.node.ConnectionHelper( 3176): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3176): start: Discovery mode: BLE, start discovery: true, start advertiser: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3176): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3176): bind: Binding a new listener
D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3176): getBluetoothService() called with no BluetoothManagerCallback
,V/io.jxcore.node.ConnectivityInfo( 3176): setIsWifiEnabled: true
,I/io.jxcore.node.ConnectivityInfo( 3176): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 3176):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 3176):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 3176): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3176): startScannerAndAdvertiser
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3176): startScanner: Starting...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3176): Waiting for incoming connections...
,D/BtGatt.GattService( 2117): registerClient() - UUID=ccef4246-199c-4ce3-9d24-357003a53bbd,
D/BtGatt.GattService( 2117): onClientRegistered() - UUID=ccef4246-199c-4ce3-9d24-357003a53bbd, clientIf=5
D/BluetoothLeScanner( 3176): onClientRegistered() - status=0 clientIf=5
D/BtGatt.GattService( 2117): start scan with filters
,D/BtGatt.ScanManager( 2117): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3176): setState: State changed from NOT_STARTED to STARTING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3176): createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3176): createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3176): setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BtGatt.GattService( 2117): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2117): addFilterToController: 2
D/BtGatt.GattService( 2117): onScanFilterConfig() - clientIf=5, action = 0 status = 0, filterType=2, availableSpace=47,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2117): Starting BLE batch scan
D/BtGatt.ScanManager( 2117): configuring batch scan storage, appIf 5
,D/BtGatt.AdvertiseManager( 2117): message : 1
D/BtGatt.GattService( 2117): onBatchScanStorageConfigured() - clientIf=5, status=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.AdvertiseManager( 2117): stop advertise for client 6
D/BtGatt.GattService( 2117): onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): onAdvertiseInstanceDisabled() - clientIf=6, status=0,
D/BtGatt.GattService( 2117): Client app is not null!
D/BtGatt.GattService( 2117): unregisterClient() - clientIf=6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3176): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3176): setState: State changed from RUNNING to NOT_STARTED
,D/BtGatt.GattService( 2117): registerClient() - UUID=bbe4e643-cb6c-4455-98d7-283dcb5bedda
,D/BtGatt.GattService( 2117): onClientRegistered() - UUID=bbe4e643-cb6c-4455-98d7-283dcb5bedda, clientIf=6
D/BluetoothLeAdvertiser( 3176): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2117): message : 0
,D/BtGatt.AdvertiseManager( 2117): starting multi advertising
,D/BtGatt.GattService( 2117): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2117): onAdvertiseDataSet() - clientIf=6, status=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3176): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3176): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3176): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3176): onIsAdvertiserStartedChanged: true
,D/BtGatt.ScanManager( 2117): awakened up at time 267292
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 267302287865
D/BtGatt.GattService( 2117): Batch record : [47, 86, 52, -95, 75, 101, 1, -128, -64, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -106, -83, 42, -72, -57, 98, 1, -128, -66, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 268316
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,I/art     (  821): Explicit concurrent mark sweep GC freed 28841(1273KB) AllocSpace objects, 7(489KB) LOS objects, 32% free, 33MB/49MB, paused 1.356ms total 86.071ms
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 268415074584
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 269429
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 269443394792
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 270459
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 271486
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,V/GoogleAuthProtoRequest( 3325): [334] a.<init>: mAccountName set to: thalitester@gmail.com
,D/BtGatt.ScanManager( 2117): awakened up at time 272504,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3325): [334] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3325): [334] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3325): ,	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3325): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3325): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3325): 	at com.a.a.k.run(SourceFile:110)
,V/GoogleAuthProtoRequest( 3325): [335] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3325): [335] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3325): [335] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3325): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3325): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3325): 	at com.a.a.k.run(SourceFile:110)
,D/BtGatt.ScanManager( 2117): awakened up at time 273016
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 273024320780,
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 273531
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0,
D/BtGatt.GattService( 2117): current time is 273540192759
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 274553,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 274565273748
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 275579,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 276605
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 277631
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 277641660882
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 278656
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 278666484163
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 279683
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 279696538017
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 280711
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 281736
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 282763
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 282772320724
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 283787
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 283801205047
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 284814
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 284831530202
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 285845
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 286879
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 287906
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 287920631139
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 288934
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 288948003378
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 289962
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 289974487075
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 290987
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 292015
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 293042
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 293055620668
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,D/BtGatt.ScanManager( 2117): awakened up at time 294069
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 294085947491
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 295100
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 296130
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 297155
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 298183
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 298198139051
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 299206
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 299218576655
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2982): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2982): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2982): 	at jdm.a(PG:82)
E/HttpOperation( 2982): 	at jcs.o(PG:406)
E/HttpOperation( 2982): 	at jcn.a(PG:1379)
E/HttpOperation( 2982): 	at jcs.i(PG:143)
E/HttpOperation( 2982): 	at blb.a(PG:3937)
E/HttpOperation( 2982): 	at czp.a(PG:18188)
E/HttpOperation( 2982): 	at czp.a(PG:9081)
E/HttpOperation( 2982): 	at czq.run(PG:1686)
E/HttpOperation( 2982): 	,at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2982): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2982): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2982): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2982): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2982): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2982): 	at jdj.a(PG:4091)
E/HttpOperation( 2982): 	at jdj.a(PG:1125)
E/HttpOperation( 2982): 	at jdm.a(PG:77)
E/HttpOperation( 2982): 	... 12 more
E/HttpOperation( 2982): Caused by: faj: BadAuthentication
E/HttpOperation( 2982): 	at fal.a(PG:38)
E/HttpOperation( 2982): 	at jdj.a(PG:4089)
E/HttpOperation( 2982): 	... 14 more
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2982): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2982): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2982): 	at jdm.a(PG:82)
E/HttpOperation( 2982): 	at jcs.o(PG:406)
E/HttpOperation( 2982): 	at jcn.a(PG:1379)
E/HttpOperation( 2982): 	at jcs.i(PG:143)
E/HttpOperation( 2982): 	at hec.a(PG:42)
E/HttpOperation( 2982): 	at hee.a(PG:102)
E/HttpOperation( 2982): 	at czr.a(PG:65)
E/HttpOperation( 2982): 	at kka.a(PG:108)
E/HttpOperation( 2982): 	at czp.a(PG:19176)
E/HttpOperation( 2982): 	at czp.a(PG:9081)
E/HttpOperation( 2982): 	at czq.run(PG:1686)
E/HttpOperation( 2982): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2982): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2982): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2982): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2982): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2982): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2982): 	at jdj.a(PG:4091)
E/HttpOperation( 2982): 	at jdj.a(PG:1125)
E/HttpOperation( 2982): 	at jdm.a(PG:77)
E/HttpOperation( 2982): 	... 15 more
E/HttpOperation( 2982): Caused by: faj: BadAuthentication
E/HttpOperation( 2982): 	at fal.a(PG:38)
E/HttpOperation( 2982): 	at jdj.a(PG:4089)
E/HttpOperation( 2982): 	... 17 more
,E/ExperimentLoader( 2982): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2982): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2982): 	at jdm.a(PG:82)
E/ExperimentLoader( 2982): 	at jcs.o(PG:406)
E/ExperimentLoader( 2982): 	,at jcn.a(PG:1379)
E/ExperimentLoader( 2982): 	at jcs.i(PG:143)
E/ExperimentLoader( 2982): 	at hec.a(PG:42)
E/ExperimentLoader( 2982): 	at hee.a(PG:102)
E/ExperimentLoader( 2982): 	,at czr.a(PG:65)
E/ExperimentLoader( 2982): 	at kka.a(PG:108)
E/ExperimentLoader( 2982): 	at czp.a(PG:19176)
E/ExperimentLoader( 2982): 	at czp.a(PG:9081)
E/ExperimentLoader( 2982): 	at czq.run(PG:1686)
E/ExperimentLoader( 2982): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2982): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2982): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2982): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2982): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2982): Caused by: android.accounts.AuthenticatorException: Recoverable error
,E/ExperimentLoader( 2982): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2982): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2982): 	at jdm.a(PG:77)
E/ExperimentLoader( 2982): 	... 15 more
E/ExperimentLoader( 2982): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2982): 	at fal.a(PG:38)
E/ExperimentLoader( 2982): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2982): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 271251, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/BtGatt.ScanManager( 2117): awakened up at time 300234
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 301262
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 302290
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 303321
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 303335019362
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 304348
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 304360692330
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 305375
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 306403
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 307431
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 308458
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 308472351548
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 309487
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 309502882745
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 310516
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 311542,
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 312570,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0,
,D/BtGatt.ScanManager( 2117): awakened up at time 313596,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 313609122223
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 314622
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 314635737691
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 315648
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 316672
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 317698
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 317714803211
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 318728
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 318741552533
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 319758
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 319772967949
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 13, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 320786
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 321812,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 322838,
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 322856191490
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 323870
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 323885231542
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@c62ee45}
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.25 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,D/BtGatt.ScanManager( 2117): awakened up at time 324898
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 324910781125
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 325925
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@c62ee45}
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/kickstart(  872): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  872): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  872): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,I/kickstart(  872): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,D/BtGatt.ScanManager( 2117): awakened up at time 326444
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 326955
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,I/kickstart(  872): STATUS: Received file 'm9kefs1'
I/kickstart(  872): STATUS: 950272 bytes transferred in 1.051444 seconds
I/kickstart(  872): STATUS: Successfully downloaded files from target 
I/kickstart(  872): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  872): STATUS: Sahara protocol completed
,D/BtGatt.ScanManager( 2117): awakened up at time 327982
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 327995168571
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 329008
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,I/art     (  821): Explicit concurrent mark sweep GC freed 28100(1419KB) AllocSpace objects, 3(236KB) LOS objects, 32% free, 33MB/49MB, paused 1.437ms total 82.514ms
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 329103004404
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,I/BooksSync( 3461): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3397): Connecting to GoogleApiClient
,I/BooksConfig( 3461): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1769): Handling authorization failure
E/ClientConnectionOperation( 1769): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1769): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1769): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1769): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1769): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1769): 	... 7 more
,V/KeepSync( 3397): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3397): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3397): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3397): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3461): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3461): Soft error
E/BooksSync( 3461): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3461): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3461): Sync error
E/BooksSync( 3461): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3461): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3461): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 305037, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1246): Explicit concurrent mark sweep GC freed 50120(2MB) AllocSpace objects, 17(1874KB) LOS objects, 37% free, 26MB/42MB, paused 1.526ms total 26.667ms
,E/KeepSync( 3397): IOException
E/KeepSync( 3397): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3397): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3397): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3397): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3397): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3397): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3397): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3397): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3397): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3397): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3397): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3397): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3397): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3397): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3397): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3397): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3397): 	... 10 more
W/KeepSync( 3397): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 302612, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/BtGatt.ScanManager( 2117): awakened up at time 330118
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 330131651539
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 20, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 331144
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 332166
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 333194
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 333204315080
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 334221
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 334228987736
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -75, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 335242
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 336265
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 337294
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 338319
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 338331289661
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 339344
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 339358113150
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 340371
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 341396
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 342424
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 343449
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 343463860284
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 344477
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 344489581169
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 345503
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 346526
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 347551
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 347561582158
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 348575
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 348589470595
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1246): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1246): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1246): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1246): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1246): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1246): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1246): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2688): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2688): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2688): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2688): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2688): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2688): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2688): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2688): Ignoring header User-Agent because its value was null.
,D/BtGatt.ScanManager( 2117): awakened up at time 349602
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 349611546219
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -71, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 350625
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 351652
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 352676
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 352690866426
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 353705
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 353718666270
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 354731
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 354741830332
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 355759
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 356792
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 357819
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 357831774914
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 358844
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 358857358351
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 359869
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 359883120538
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 360901
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 361932
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 362958
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 362973984027
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 363989
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 364003131474
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 365020
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 365032527984
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 366044
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 367069
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 368094
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 368102240848
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 369114
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 369121296681
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 370139
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 371165
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 372191
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 373214
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 373223057721
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 374237,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 374251975845
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 375264
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 376288
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 377313
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 378339
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 378351735531
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 379366
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 379380438448
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 380392
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 381418
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 382446
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 383476
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 383490319644
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 384503
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 384518007977
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 385531
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,I/art     (  821): Explicit concurrent mark sweep GC freed 26204(1307KB) AllocSpace objects, 3(48KB) LOS objects, 31% free, 34MB/50MB, paused 1.411ms total 72.692ms,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 386632
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 387662
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,I/art     ( 2117): Explicit concurrent mark sweep GC freed 25916(1382KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 22MB/37MB, paused 1.019ms total 114.721ms
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 387785973965
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 388801
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 388810769538
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 389825,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 389836989121
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 390853,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 391878
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,V/GoogleAuthProtoRequest( 3325): [336] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3325): [336] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3325): [336] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3325): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3325): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3325): 	at com.a.a.k.run(SourceFile:110)
,D/BtGatt.ScanManager( 2117): awakened up at time 392903
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 392914367609
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,V/GoogleAuthProtoRequest( 3325): [337] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3325): [337] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3325): [337] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3325): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3325): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.a.a(SourceFile:93),
W/ExperimentUpdateService( 3325): 	at com.a.a.k.run(SourceFile:110)
,D/BtGatt.ScanManager( 2117): awakened up at time 393418
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0,
D/BtGatt.GattService( 2117): current time is 393424231984
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 393930
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 393939888702
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -72, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 394953
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 394965906202
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 395980
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 397007,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 398034
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 398046239586
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 399062
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 399075239690
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 400088,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 400102019169
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 20, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 401115
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 402143,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 403168
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 403183968751
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 404199
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 404216672865
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 405229
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 406257
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 407281
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 408307
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 408321415676
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 409333
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 409342209165
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 410355
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 411385
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 412411
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 413433
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 413445923018
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 414458
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 414467899945
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 415482
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 416509
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 417534
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 417547182131
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 418562
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 418575984943
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 419589
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 419602792807
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 420616
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 421643
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 422671
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2982): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2982): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2982): 	at jdm.a(PG:82)
E/HttpOperation( 2982): 	at jcs.o(PG:406)
E/HttpOperation( 2982): 	at jcn.a(PG:1379)
E/HttpOperation( 2982): 	at jcs.i(PG:143)
E/HttpOperation( 2982): 	at blb.a(PG:3937)
E/HttpOperation( 2982): 	at czp.a(PG:18188)
E/HttpOperation( 2982): 	at czp.a(PG:9081)
E/HttpOperation( 2982): 	at czq.run(PG:1686)
E/HttpOperation( 2982): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2982): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2982): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2982): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2982): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2982): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2982): 	at jdj.a(PG:4091)
E/HttpOperation( 2982): 	at jdj.a(PG:1125)
E/HttpOperation( 2982): 	at jdm.a(PG:77)
E/HttpOperation( 2982): 	... 12 more
E/HttpOperation( 2982): Caused by: faj: BadAuthentication
E/HttpOperation( 2982): 	at fal.a(PG:38)
E/HttpOperation( 2982): 	at jdj.a(PG:4089)
E/HttpOperation( 2982): 	... 14 more
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2982): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2982): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2982): 	at jdm.a(PG:82)
E/HttpOperation( 2982): 	at jcs.o(PG:406)
E/HttpOperation( 2982): 	at jcn.a(PG:1379)
E/HttpOperation( 2982): 	at jcs.i(PG:143)
E/HttpOperation( 2982): 	at hec.a(PG:42)
E/HttpOperation( 2982): 	at hee.a(PG:102)
E/HttpOperation( 2982): 	at czr.a(PG:65)
E/HttpOperation( 2982): 	at kka.a(PG:108)
E/HttpOperation( 2982): 	at czp.a(PG:19176)
E/HttpOperation( 2982): 	at czp.a(PG:9081)
E/HttpOperation( 2982): 	at czq.run(PG:1686)
E/HttpOperation( 2982): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2982): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2982): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2982): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2982): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2982): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2982): 	at jdj.a(PG:4091)
E/HttpOperation( 2982): 	at jdj.a(PG:1125)
E/HttpOperation( 2982): 	at jdm.a(PG:77)
E/HttpOperation( 2982): 	... 15 more
E/HttpOperation( 2982): Caused by: faj: BadAuthentication
E/HttpOperation( 2982): 	at fal.a(PG:38)
E/HttpOperation( 2982): 	at jdj.a(PG:4089)
E/HttpOperation( 2982): 	... 17 more
,E/ExperimentLoader( 2982): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2982): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2982): 	at jdm.a(PG:82)
E/ExperimentLoader( 2982): 	at jcs.o(PG:406)
E/ExperimentLoader( 2982): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2982): 	at jcs.i(PG:143)
E/ExperimentLoader( 2982): 	at hec.a(PG:42)
E/ExperimentLoader( 2982): 	at hee.a(PG:102)
E/ExperimentLoader( 2982): 	at czr.a(PG:65)
E/ExperimentLoader( 2982): 	at kka.a(PG:108)
E/ExperimentLoader( 2982): 	at czp.a(PG:19176)
E/ExperimentLoader( 2982): 	at czp.a(PG:9081)
E/ExperimentLoader( 2982): 	at czq.run(PG:1686)
E/ExperimentLoader( 2982): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2982): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2982): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2982): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2982): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2982): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2982): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2982): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2982): 	at jdm.a(PG:77)
E/ExperimentLoader( 2982): 	... 15 more
E/ExperimentLoader( 2982): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2982): 	at fal.a(PG:38)
E/ExperimentLoader( 2982): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2982): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 422926, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/BtGatt.ScanManager( 2117): awakened up at time 423700
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 423709986608
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 424725
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 424738340357
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 425754
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 426785
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 427816
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 427829675356
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 428843
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 428857867335
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 429872
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 429882065616
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 430897,
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 431924
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 432950
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 432965318948
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 433980
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 433993197645
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 435007
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 436035
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 437062
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 438088
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 438103162071
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 439116
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 439131584258
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 440144
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 441172
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 442196
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 443225
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 443241233267
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 444257
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 444269323475
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 445283
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 446309
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 447339
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 448367
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 448383222119
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 449397
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 449410624358
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 450424
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 451451
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 452479
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 453505
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 453513150346
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -72, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 454524
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 454533212690
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 455539
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,I/art     (  821): Explicit concurrent mark sweep GC freed 26138(1363KB) AllocSpace objects, 4(346KB) LOS objects, 32% free, 33MB/49MB, paused 1.268ms total 68.483ms
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 456629
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 457655
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 457669477845
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 458683
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 458694174355
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 459708
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 459721522636
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 460735
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 461762
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 462787
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 462803028989
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 463816
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 463829135342
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 464843
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 464852353415
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 465867
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 466892
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 467922
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 467935930445
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 468950
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 468966464351
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -72, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 469982
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 469994553153
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 471006
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 472032
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 473055
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 473068071381
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 474081
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 474091391901
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 475106
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 476133
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 477161
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 478187
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 478199042577
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 479214
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 479227685180
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 480241
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 481269
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 482298
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,I/BooksSync( 3461): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3397): Connecting to GoogleApiClient
,I/BooksConfig( 3461): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1769): Handling authorization failure
E/ClientConnectionOperation( 1769): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1769): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1769): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1769): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1769): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1769): 	... 7 more
,V/KeepSync( 3397): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3397): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3397): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3397): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3461): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3461): Soft error
E/BooksSync( 3461): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3461): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3461): Sync error
E/BooksSync( 3461): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3461): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3461): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 460748, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BtGatt.ScanManager( 2117): awakened up at time 483312
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 483317753356
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,E/KeepSync( 3397): IOException
E/KeepSync( 3397): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3397): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3397): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3397): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3397): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3397): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3397): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3397): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3397): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3397): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3397): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3397): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3397): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3397): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3397): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3397): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3397): 	... 10 more
W/KeepSync( 3397): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 455894, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/BtGatt.ScanManager( 2117): awakened up at time 484333
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 484347160491
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 485357
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 486381,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 487403,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 488427
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0,
D/BtGatt.GattService( 2117): current time is 488437040333
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 489455,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 489466378562
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 490480
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 491505
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 492531
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 492538495696
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 493555
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 493564733873
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 494581
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 494596501685
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 495608
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 496633
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 497656
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 497665983038
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -72, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 498682
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 498693386058
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 499707
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 499718281370
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 500732
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 501756
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 502783
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 502791839442
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 503805
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 503818419702
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 504833
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 504841740483
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 16, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 505857
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 506888
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 507914
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 507927073659
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 508941
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 508953897148
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 509968
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 509981628137
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 510997
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 512025
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 513051
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 513059787928
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 514073
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 514082464907
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 515096
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 516114
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 517138
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 518163
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 518169327301
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 519184
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,I/art     (  821): Explicit concurrent mark sweep GC freed 26303(1303KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 2.762ms total 75.343ms
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 519269832300
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 520283
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 521308
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 522331
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 523354
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 523370434851
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 524382
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 524391939538
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 525406
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 526435
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 527464
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 528492
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 528502187245
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -72, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 529515
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 529525726203
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 530541
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 531570
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 532596
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 532604477608
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 533623
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 533630418128
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 534644,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 534657087138
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 535671
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 536699
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 537725
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 537739699220
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 538752
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 538762715001
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 539777,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 539790803543
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 540803
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 541827
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 542854
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 542864101510
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 543879
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 543893755208
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -72, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 544908
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 544922653645
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 545936
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 546961
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 547986
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 547999379529
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 549013
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0,
D/BtGatt.GattService( 2117): current time is 549027290310
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 550044,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 551069
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 552094
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 553123
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 553134542913
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 554148
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 554158458277
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 555175
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 556201
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 557233
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 558259,
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0,
D/BtGatt.GattService( 2117): current time is 558273192233
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 559287,
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 559301740150
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 560313
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 561344
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 562366
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 563393
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 563406510096
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 564424
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 564438766710
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 565452,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 566479
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 567512
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 567523672074
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 568537,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 568549300459
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 569562
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 569569987438
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 570584
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 571603
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 572627
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 572638536238
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 573654
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 573665726290
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 574681
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 574692201863
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 13, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 575706
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 576721
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 577742
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 577752641549
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 578768
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 578779947851
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 579792
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 579801344152
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 16, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 580815
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 581841
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 582865
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 582878472849
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 583893
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 583906452432
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 584919
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 584929543577
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 585942
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 586964
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 587994
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 588008707847
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 589022
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 589028626857
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 590042
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 591069
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 592097
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 593126
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 593140323366
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 594152
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,I/art     ( 2117): Explicit concurrent mark sweep GC freed 31130(1507KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 22MB/37MB, paused 1.368ms total 37.823ms
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 594199798001
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 595212
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 596237
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 597265
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 598291
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 598300778572
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 599314
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 599330228259
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 600343
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 601367
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 602394
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 603421
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 603436004925
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 604451
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 604463882893
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 605477
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 606507
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 607533
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 607546544298
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 608560
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 608572995964
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 609587
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 609599618881
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 13, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 610613
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 611639
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 612667
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 612679059921
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 613694
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 613706618046
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 614719
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 614732180597
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 615746
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 616772,
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 617797,
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 617809422523
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 618824
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 618836070908
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -73, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 619850
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,I/art     (  821): Explicit concurrent mark sweep GC freed 22738(1280KB) AllocSpace objects, 2(220KB) LOS objects, 32% free, 33MB/49MB, paused 2.406ms total 88.639ms,
D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 619950415075
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 20, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 620962
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 621986
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 623016
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 623030657157
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 624043
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 624051757208
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 625068
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 626096
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 627126
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 628149
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 628160172103
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 629181
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 629193516998
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 630210
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 631235
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 632262
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,V/GoogleAuthProtoRequest( 3325): [338] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3325): [338] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3325): [338] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3325): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3325): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3325): 	at com.a.a.k.run(SourceFile:110)
,D/BtGatt.ScanManager( 2117): awakened up at time 633144
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 633148884445
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 633651
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 633663046059
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -78, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 634676
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 634690695538
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 635701
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 636725
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 637749
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 637762797516
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 638775
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 638789904390
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 639803
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 639812628088
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 16, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 640825
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 641852
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 642877
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 642892015378
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -62, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 643907
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 643919839232
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -61, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 644933
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 644946371159
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -61, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 645962
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 646985
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 648012,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 648023976314
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -79, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 649036
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 649049893397
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 650062
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 651085
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 652115
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 653142
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 653149150947
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 654162
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 654172397561
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 655187
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 656212
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 657235
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 658262
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 658269813497
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 659283
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 659296651987
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 660311
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 661339
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 662368
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,V/GoogleAuthProtoRequest( 3325): [339] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3325): [339] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3325): [339] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3325): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3325): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3325): 	at com.a.a.k.run(SourceFile:110)
,D/BtGatt.ScanManager( 2117): awakened up at time 663363
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 663370690475
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -75, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 663875
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 663888417402
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 664902
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 664913663287
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -76, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 665929
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 666955
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0,
,D/BtGatt.ScanManager( 2117): awakened up at time 667982,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 667991977765
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 669006,
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 669018045160
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 670032
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2982): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2982): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2982): 	at jdm.a(PG:82)
E/HttpOperation( 2982): 	at jcs.o(PG:406)
E/HttpOperation( 2982): 	at jcn.a(PG:1379)
E/HttpOperation( 2982): 	at jcs.i(PG:143)
E/HttpOperation( 2982): 	at blb.a(PG:3937)
E/HttpOperation( 2982): 	at czp.a(PG:18188)
E/HttpOperation( 2982): 	at czp.a(PG:9081)
E/HttpOperation( 2982): 	at czq.run(PG:1686)
E/HttpOperation( 2982): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2982): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2982): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2982): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2982): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2982): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2982): 	at jdj.a(PG:4091)
E/HttpOperation( 2982): 	at jdj.a(PG:1125)
E/HttpOperation( 2982): 	at jdm.a(PG:77)
E/HttpOperation( 2982): 	... 12 more
E/HttpOperation( 2982): Caused by: faj: BadAuthentication
E/HttpOperation( 2982): 	at fal.a(PG:38)
E/HttpOperation( 2982): 	at jdj.a(PG:4089)
E/HttpOperation( 2982): 	... 14 more
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1246): Explicit concurrent mark sweep GC freed 56514(2MB) AllocSpace objects, 8(882KB) LOS objects, 36% free, 27MB/43MB, paused 1.539ms total 44.995ms
,E/HttpOperation( 2982): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2982): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2982): 	at jdm.a(PG:82)
E/HttpOperation( 2982): 	at jcs.o(PG:406)
E/HttpOperation( 2982): 	at jcn.a(PG:1379)
E/HttpOperation( 2982): 	at jcs.i(PG:143)
E/HttpOperation( 2982): 	at hec.a(PG:42)
E/HttpOperation( 2982): 	at hee.a(PG:102)
E/HttpOperation( 2982): 	at czr.a(PG:65)
E/HttpOperation( 2982): 	at kka.a(PG:108)
E/HttpOperation( 2982): 	at czp.a(PG:19176)
E/HttpOperation( 2982): 	at czp.a(PG:9081)
E/HttpOperation( 2982): 	at czq.run(PG:1686)
E/HttpOperation( 2982): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2982): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2982): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2982): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2982): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2982): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2982): 	at jdj.a(PG:4091)
E/HttpOperation( 2982): 	at jdj.a(PG:1125)
E/HttpOperation( 2982): 	at jdm.a(PG:77)
E/HttpOperation( 2982): 	... 15 more
E/HttpOperation( 2982): Caused by: faj: BadAuthentication
E/HttpOperation( 2982): 	at fal.a(PG:38)
E/HttpOperation( 2982): 	at jdj.a(PG:4089)
E/HttpOperation( 2982): 	... 17 more
,E/ExperimentLoader( 2982): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2982): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2982): 	at jdm.a(PG:82)
E/ExperimentLoader( 2982): 	at jcs.o(PG:406)
E/ExperimentLoader( 2982): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2982): 	at jcs.i(PG:143)
E/ExperimentLoader( 2982): 	at hec.a(PG:42)
E/ExperimentLoader( 2982): 	at hee.a(PG:102)
E/ExperimentLoader( 2982): 	at czr.a(PG:65)
E/ExperimentLoader( 2982): 	at kka.a(PG:108)
E/ExperimentLoader( 2982): 	at czp.a(PG:19176),
E/ExperimentLoader( 2982): 	at czp.a(PG:9081)
E/ExperimentLoader( 2982): 	at czq.run(PG:1686)
E/ExperimentLoader( 2982): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2982): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2982): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2982): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2982): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2982): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2982): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2982): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2982): 	at jdm.a(PG:77)
E/ExperimentLoader( 2982): 	... 15 more
,E/ExperimentLoader( 2982): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2982): 	at fal.a(PG:38)
E/ExperimentLoader( 2982): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2982): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 670299, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/BtGatt.ScanManager( 2117): awakened up at time 671061
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 672085
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 673111
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 673120672346
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 674136
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 674150330054
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 675163
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 676187
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 677214
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 678239
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 678252960000
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -75, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 679267
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 679280857812
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -76, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 680294,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 681321
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 682348,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 683374,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 683388449269
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 684403
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 684413498279
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 685431
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 686460
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 687488,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 687502928851
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,I/art     (  821): Explicit concurrent mark sweep GC freed 25462(1308KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.342ms total 86.401ms
,D/BtGatt.ScanManager( 2117): awakened up at time 688522
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 688531932132
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 689548
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 689561804110
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 690574
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 691601
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 692626
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 692638162807
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -76, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 693651
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 693659366974
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -75, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 694672
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 694682111765
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 13, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 695696
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 696726
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 697751
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 697762215201
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 698777
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 698790434680
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 699804
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 699813580773
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 700829
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 701857
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 702884
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 702894144991
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 703909
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 703923230668
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 704936
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 704952142386
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 20, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 705965
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 706991
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 708016
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 708029381708
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -78, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 709042
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 709056408530
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -78, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 710069
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 711097
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 712122
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 713151
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 713159326706
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 714173,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 714183688007
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 715199
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 716222
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 717247
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0,
,D/BtGatt.ScanManager( 2117): awakened up at time 718272
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 718284083839
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 719297
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 719311715662
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 720325
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 721353
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 722376
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 722389301963
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -75, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 723402
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 723410319462
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 724428
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 724441954670
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -76, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 725459
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 726486,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 727513
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 727524355242
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,D/BtGatt.ScanManager( 2117): awakened up at time 728537
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 728553550554
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 729567
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 729581193418
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 730593
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 731621
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 732646
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 732660420657
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 733674
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 733688878208
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 734702
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 734716602166
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 16, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 735729
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,V/KeepSync( 3397): Connecting to GoogleApiClient
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1769): Handling authorization failure,
E/ClientConnectionOperation( 1769): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1769): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1769): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1769): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1769): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1769): 	... 7 more
,V/KeepSync( 3397): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3397): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3397): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3397): (284) automatic index on blob_node(is_deleted),
,D/BtGatt.ScanManager( 2117): awakened up at time 736745
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3397): IOException
E/KeepSync( 3397): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3397): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3397): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3397): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3397): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3397): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3397): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3397): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3397): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3397): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3397): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3397): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3397): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3397): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3397): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3397): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3397): 	... 10 more
W/KeepSync( 3397): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 736390, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/BtGatt.ScanManager( 2117): awakened up at time 737766
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 737783380394
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -76, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 738796
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 738809942321
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 739822
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 739834248414
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -78, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 740848
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 741872
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 742896
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 742908320028
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,D/BtGatt.ScanManager( 2117): awakened up at time 743922
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 743934597631
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 744951
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 745978
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 747002
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 748027
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 748040945130
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 749054
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 749070596952
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 750082
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 751104
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 752131
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 753152
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 753160488722
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -75, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 754175
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 754187748148
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 755203
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 756228
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 757254
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 758277
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 758287120907
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 759301
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 759314360907
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 760327
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 761354
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 762382
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 763409
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 763421683822
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 764435
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 764449088561
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 765461,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,I/art     (  821): Explicit concurrent mark sweep GC freed 27345(1415KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.455ms total 99.341ms
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,I/BooksSync( 3461): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3461): GmsCore Version = 7.8.99 (2134222-430)
,D/BtGatt.ScanManager( 2117): awakened up at time 766584
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3461): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3461): Soft error
E/BooksSync( 3461): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3461): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3461): Sync error
E/BooksSync( 3461): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3461): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3461): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 746272, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/BtGatt.ScanManager( 2117): awakened up at time 767611
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 767621059289
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 768636,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 768649483247
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -78, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 769663,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 769673439757
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -76, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 770688
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0,
,D/BtGatt.ScanManager( 2117): awakened up at time 771715
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 772744
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 772758323714
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 773771
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 773782332776
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -67, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 774797
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 774809658713
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 775821,
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 776845
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 777871
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 777882358348
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 778897
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 778909289285
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 779922
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 779936495430
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 780949
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 781975
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 783001
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 783013933554
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -78, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 784028
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 784041459543
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 785053
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 786076
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 787102
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 788127
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 788141848708
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 789155
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 789169282770
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 790182
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 791203
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 792230
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 793255
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 793264500008
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 794281
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 794296620060
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 795309
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 796336,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 797362
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 798386
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 798398659538
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 799412
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 799427033964
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -75, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 800439
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 801465
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,I/art     ( 2117): Explicit concurrent mark sweep GC freed 31004(1503KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 22MB/37MB, paused 1.247ms total 48.832ms
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 802541
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 802550485317
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 803566
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 803579597452
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 804594
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 804600621150
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -67, 13, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 805614
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 806636
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 807668
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 807685119274
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 808699
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 808713944117
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 809726
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 809738915315
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 16, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 810751
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 811777
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 812806
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 812819307345
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -76, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 813829,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 813837246459
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -74, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 814852
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 814862526927
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -75, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 815879
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 816903
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 817930
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 817943471249
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 818948
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 818959339061
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 819972,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 821001
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 822030
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 823055
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 823069913435
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 824082
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 824093691976
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 825107
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 826136
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 827166,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 828195
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 828209430203
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -79, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 829222
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 829233288328,
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -80, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 830247
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 831276
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 832305
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 833331
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 833345638483
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 834359
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 834373397180
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 835390
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 836415
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 837442
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 837452358481
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 838467
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 838482350877
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 839495,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 839508659991
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 840521
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 841547
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 842574,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 842582599104
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -78, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 843597
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 843612584364
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -78, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 844625
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 844637358426
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 845653,
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 846679
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 847702
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,I/art     (  821): Explicit concurrent mark sweep GC freed 25590(1347KB) AllocSpace objects, 3(142KB) LOS objects, 32% free, 33MB/49MB, paused 2.123ms total 87.718ms
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 847801576758
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 848815
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 848826311237
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 849841
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 849851784726
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 850866
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 851893
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 852916
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 852929185923
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 853942
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 853952376964
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 854967
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 854977810193
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -63, 20, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 855992
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 857022
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 858049
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 858063971077
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -78, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 859077
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 859089369983
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 860102,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 861127
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 862153
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 863178
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 863192843055
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 864209
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 864225820346
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 865238
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 866263
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 867291
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 868315
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 868327737219
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 869345
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 869361045292
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 870371
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 871401,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 872427
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 872440862843
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 873459
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 873474360030
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 874489
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 874504830759
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 875518
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 876541
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 877564
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 877576058205
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 878590
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 878597564090
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 879609
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 879622257475
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 16, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 880636
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 881662
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 882688
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 882701280287
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -67, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 883715
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 883727079870
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 884740
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 884753307005
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 885766
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 886796
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 887826,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 887839719972
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 888853,
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 888865039243
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -78, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 889879,
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 889895204503
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 20, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 890907
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 891933,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 892964
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 892977503877
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 893992
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 894008261949
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 895021
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 896048
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 897076
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 898101,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 898108826791
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 899124,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 899135565176
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 900148
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 901176,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 902203
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 903231
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 903243802779
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 904258
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 904273266685
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 905287
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 906312
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 907336
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 908363
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 908373970381
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 909387
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 909397791579
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 910413
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 911439
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 912466
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 912478260223
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 913492
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 913502520119
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -67, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 914516
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 914527473035
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 13, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 915541
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 916561
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 917586
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 917598900951,
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 918613
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 918627141211
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 919639
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 919650293814
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 920662
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 921688,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 922716
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 922730630272
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 923744
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 923754009698
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 924771
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 924785875687
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 925798
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 926824
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 927852
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 927858389228
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 928874
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 928884144748
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 929901
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 930924
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 931955
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 932984
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 932997895163
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -76, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 934011
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 934026429069
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 935040
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 936072
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 937099
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 938123
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 938136831880
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 939151
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 939164614328
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 940181
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 941201
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 942228
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 943256
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 943272218753
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -106, -83, 42, -72, -57, 98, 1, -128, -64, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 944283,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 944291705003
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 945307,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 946335
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,I/art     (  821): Explicit concurrent mark sweep GC freed 23909(1341KB) AllocSpace objects, 1(110KB) LOS objects, 32% free, 33MB/49MB, paused 1.358ms total 75.334ms
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 947435
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 947448348804
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 948461
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 948473502085
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 949486
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 949501491772
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 950514
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 951542
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 952569
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 952583810625
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 953598
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 953611191354
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 954623
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 954631475103
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 13, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 955646
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 956671
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 957695
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 957706366248
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 958721
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 958729648956
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 959744
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 959757469997
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 16, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 960770
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 961792
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 962816
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 962832236506
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 963846
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 963861679214
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 964877
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 964888949474
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 20, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 965902
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 966931
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 967953
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 967962034108
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 968976
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 968992016400
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 970005
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 971032
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 972061
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 973088
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 973100939940
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 974114
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 974122891294
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 975137
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 976163
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 977191
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 978217
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 978233202073
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 979246
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 979258740719
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 980272
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 981296
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 982321
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 983346
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 983356174207
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 984373
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 984388058113
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 985400
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 986428
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 987453,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 987466340143
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 988479
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 988493138528
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 989507
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 989522115142
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 13, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 990538
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 991565
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 992593
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 992602735714
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 993620,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 993633720505
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 994646
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 994658459515
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 16, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 995665
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 996689
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 997718,
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 997731787743
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 998745
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 998759120399
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 999773
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 999782973732
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,D/BtGatt.ScanManager( 2117): awakened up at time 1000791,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1001812
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1002835
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1002849832376
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1003865
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1003874986282
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1004890
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1004908490709
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 21, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1005921
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1006945
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1007973
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,I/art     ( 2117): Explicit concurrent mark sweep GC freed 31549(1530KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 22MB/37MB, paused 1.356ms total 37.206ms,
D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1008021719927
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1009034
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1009042054926
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1010054
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1011075
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1012101
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1013130
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1013143962789
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1014156
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1014167460341
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1015181
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1016206
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1017232
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1018257
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1018268769558
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1019282
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1019294387162
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -67, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1020308
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1021336
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1022363
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1022375920442
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1023392
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1023399589244
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1024414
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1024428677420
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1025443
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1026471
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1027494
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1027506304450
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1028520
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1028533005648
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1029546
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1029558908356
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1030571
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1031594
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1032623
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1032636215594
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1033651
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1033662483979
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1034676
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1034689448250
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1035702
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1036729
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1037756
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1037770546269
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1038782
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1038793230071
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1039808
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1039821840435
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 20, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1040839
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1041865
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1042891
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1042908741319
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1043922
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1043932269600
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1044949
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1045977
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1047001
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,I/art     (  821): Explicit concurrent mark sweep GC freed 22665(1277KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.599ms total 89.168ms
D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1048115
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1048126844599
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1049139
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1049149760327
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1050163,
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1051195
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1052223
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1053248
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1053258519753
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1054274
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1054285887773
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1055300
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1056328
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1057351
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1058373
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1058385841001
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1059398
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1059412934021
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1060428
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1061449
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1062470
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1062479976677
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -67, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1063493
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1063505127666
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1064518
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1064529981936
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1065544
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1066571
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1067597
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1068626
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1068637283393
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -78, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1069650
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1069661710997
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 16, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1070674
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1071702
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1072722
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1072731531673
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1073746
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1073758852297
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1074772
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1074783069224
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1075796,
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1076822
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1077847
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1077861883285
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/GCM     ( 1246): Message class com.google.f.a.a.i
,D/BtGatt.ScanManager( 2117): awakened up at time 1078655
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1078663960733
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -47, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1079170
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1079184872295
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1080196
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1081221
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1082245
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1083270
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1083285020992
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1084297
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1084308764845,
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1085322
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1086346
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0,
,D/BtGatt.ScanManager( 2117): awakened up at time 1087370
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1088403,
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1088416295885
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1089431
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1089445840260
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1090461,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1091487
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1092511
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1092521152082
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1093535
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1093549032654
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1094562
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1094572832341
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1095587
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1096613
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1097636
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1097651175309
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1098665
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1098676310361
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1099690,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1099702929319
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1100717
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1101743
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1102771
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1102786960047
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1103801
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1103812276973
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1104828
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1105853
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1106879
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1107907
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1107920503170
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -67, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1108933
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1108942581867
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1109956
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1110981
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1112004
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1113032
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1113044835303
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,V/GoogleAuthProtoRequest( 3325): [340] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3325): [340] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3325): [340] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3325): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3325): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3325): 	at com.a.a.k.run(SourceFile:110)
,D/BtGatt.ScanManager( 2117): awakened up at time 1113548
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1113555976865
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1114062,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1114075155563
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -76, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1115091
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0,
,D/BtGatt.ScanManager( 2117): awakened up at time 1116115
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1117140
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1118166
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1118180153374
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1119193
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1119204081759
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1120221
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1121249
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1122269
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1123292
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1123302932955
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1124317
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1124331145247
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1125344
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1126370
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1127398
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1127411332381
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1128424
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1128437165089
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1129449
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1129462116234
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1130475
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1131505
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1132529
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1132543622119
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1133557
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1133571605347
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -66, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1134585
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,I/art     (  821): Explicit concurrent mark sweep GC freed 23524(1298KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 2.772ms total 84.974ms
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1134684732014
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1135701
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1136731
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1137754
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1137766542950
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1138781
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1138793148418
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1139809
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1139821906439
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 20, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1140836
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1141864
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1142892
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1142906921958
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,V/GoogleAuthProtoRequest( 3325): [341] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3325): [341] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3325): [341] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3325): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3325): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3325): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3325): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3325): 	at com.a.a.k.run(SourceFile:110)
,D/BtGatt.ScanManager( 2117): awakened up at time 1143578
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1143583887948
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -76, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1144089
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1144101892739
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -76, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1145117
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1146144
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1147173
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1148199
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1148212775342
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1149226
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1149239897164
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1150251
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1151273
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1152297
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1153321
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1153331769402
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1154346
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1154359057579
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1155374
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1156401
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1157429,
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1157442462474
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1158456
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1158467563932
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1159482
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1159495134348
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1160511
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1161542
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1162564,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1162575963670
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1163592
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1163599492628
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1164603
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1164611442888
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 16, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2982): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2982): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2982): 	at jdm.a(PG:82)
E/HttpOperation( 2982): 	at jcs.o(PG:406)
E/HttpOperation( 2982): 	at jcn.a(PG:1379)
E/HttpOperation( 2982): 	at jcs.i(PG:143)
E/HttpOperation( 2982): 	at blb.a(PG:3937)
E/HttpOperation( 2982): 	at czp.a(PG:18188)
E/HttpOperation( 2982): 	at czp.a(PG:9081)
E/HttpOperation( 2982): 	at czq.run(PG:1686)
E/HttpOperation( 2982): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2982): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2982): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2982): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2982): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2982): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2982): 	at jdj.a(PG:4091)
E/HttpOperation( 2982): 	at jdj.a(PG:1125)
E/HttpOperation( 2982): 	at jdm.a(PG:77)
E/HttpOperation( 2982): 	... 12 more
E/HttpOperation( 2982): Caused by: faj: BadAuthentication
E/HttpOperation( 2982): 	at fal.a(PG:38)
E/HttpOperation( 2982): 	at jdj.a(PG:4089)
E/HttpOperation( 2982): 	... 14 more
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2982): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2982): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2982): 	at jdm.a(PG:82)
E/HttpOperation( 2982): 	at jcs.o(PG:406)
E/HttpOperation( 2982): 	at jcn.a(PG:1379)
E/HttpOperation( 2982): 	at jcs.i(PG:143)
E/HttpOperation( 2982): 	at hec.a(PG:42)
E/HttpOperation( 2982): 	at hee.a(PG:102)
E/HttpOperation( 2982): 	at czr.a(PG:65)
E/HttpOperation( 2982): 	at kka.a(PG:108)
E/HttpOperation( 2982): 	at czp.a(PG:19176)
E/HttpOperation( 2982): ,	at czp.a(PG:9081)
E/HttpOperation( 2982): 	at czq.run(PG:1686)
E/HttpOperation( 2982): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2982): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
E/HttpOperation( 2982): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2982): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2982): 	at java.lang.Thread.run(Thread.java:818),
E/HttpOperation( 2982): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2982): 	at jdj.a(PG:4091)
E/HttpOperation( 2982): 	at jdj.a(PG:1125)
E/HttpOperation( 2982): 	,at jdm.a(PG:77)
E/HttpOperation( 2982): 	... 15 more
E/HttpOperation( 2982): Caused by: faj: BadAuthentication
E/HttpOperation( 2982): 	at fal.a(PG:38)
,E/HttpOperation( 2982): 	at jdj.a(PG:4089)
E/HttpOperation( 2982): 	... 17 more
,E/ExperimentLoader( 2982): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2982): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2982): 	at jdm.a(PG:82)
E/ExperimentLoader( 2982): 	,at jcs.o(PG:406)
E/ExperimentLoader( 2982): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2982): 	at jcs.i(PG:143)
E/ExperimentLoader( 2982): 	,at hec.a(PG:42)
E/ExperimentLoader( 2982): 	at hee.a(PG:102)
E/ExperimentLoader( 2982): 	at czr.a(PG:65)
E/ExperimentLoader( 2982): 	at kka.a(PG:108)
,E/ExperimentLoader( 2982): 	at czp.a(PG:19176)
E/ExperimentLoader( 2982): 	at czp.a(PG:9081)
E/ExperimentLoader( 2982): 	,at czq.run(PG:1686)
E/ExperimentLoader( 2982): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2982): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2982): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2982): ,	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2982): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2982): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2982): 	,at jdj.a(PG:4091)
E/ExperimentLoader( 2982): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2982): 	at jdm.a(PG:77)
E/ExperimentLoader( 2982): 	... 15 more,
E/ExperimentLoader( 2982): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2982): 	at fal.a(PG:38)
E/ExperimentLoader( 2982): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2982): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1164445, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/BtGatt.ScanManager( 2117): awakened up at time 1165626
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1166653
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1167676,
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1168705
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1168721445282
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1169735
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1169748837417
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1170761
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1171786
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1172818
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1172831591426
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1173843
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1173851761842
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1174866,
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1174880276321
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 20, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1175894,
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1176921
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1177952
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1177967408872,
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,D/BtGatt.ScanManager( 2117): awakened up at time 1178980
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1179000424340
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1180015
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1181041
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1182066
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1183082
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1183093221787
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1184107
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1184122381995
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1185135
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1186161
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1187188
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1188212
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1188227009910
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,W/bt-btm  ( 2117): Request to stop oneshot timer with non empty queue
,D/BtGatt.ScanManager( 2117): awakened up at time 1193233
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,W/bt-btm  ( 2117): Stopping oneshot timer
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1193252646783
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1194262
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1194271626262
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -65, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1195287
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1196317
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1197348
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1197359300167
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1198372
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1198381289073
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -64, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1199396
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1199407086781
,D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -67, 13, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1200421
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1201445
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1202472
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1202488046154
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1203501
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1203511830685
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1204527
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1204541183341
D/BtGatt.GattService( 2117): Batch record : [-106, -83, 42, -72, -57, 98, 1, -128, -77, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1205555
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1206582
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1207609
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1207621377871
D/BtGatt.GattService( 2117): Batch record : [-113, -16, 59, -113, -65, 81, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1208634
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1208648038287
D/BtGatt.GattService( 2117): Batch record : [-113, -16, 59, -113, -65, 81, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1209662
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1209675895318
,D/BtGatt.GattService( 2117): Batch record : [-113, -16, 59, -113, -65, 81, 1, -128, -65, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1210688
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1211714
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1212740,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2117): current time is 1212756942036
D/BtGatt.GattService( 2117): Batch record : [-113, -16, 59, -113, -65, 81, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1213769,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1213782732452
D/BtGatt.GattService( 2117): Batch record : [-113, -16, 59, -113, -65, 81, 1, -128, -64, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1214796
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1215824,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,I/art     (  821): Explicit concurrent mark sweep GC freed 24966(1303KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.533ms total 84.020ms
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1216937
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,I/art     ( 2117): Explicit concurrent mark sweep GC freed 31428(1534KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 22MB/37MB, paused 1.110ms total 53.906ms
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1218019
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1218032474273
D/BtGatt.GattService( 2117): Batch record : [-113, -16, 59, -113, -65, 81, 1, -128, -77, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1219045
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1219051882294
D/BtGatt.GattService( 2117): Batch record : [-113, -16, 59, -113, -65, 81, 1, -128, -77, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1220064
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1221085
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1222104
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1223128
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1223140803022
D/BtGatt.GattService( 2117): Batch record : [-113, -16, 59, -113, -65, 81, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1224155,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1224167978021
D/BtGatt.GattService( 2117): Batch record : [-113, -16, 59, -113, -65, 81, 1, -128, -65, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1225184
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1226213
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1227241
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1228264
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1228271783332
D/BtGatt.GattService( 2117): Batch record : [-113, -16, 59, -113, -65, 81, 1, -128, -67, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1229286
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2117): current time is 1229299383644
,D/BtGatt.GattService( 2117): Batch record : [-113, -16, 59, -113, -65, 81, 1, -128, -64, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2117): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2117): awakened up at time 1230312
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1231334
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,I/UsageStatsService(  821): User[0] Flushing usage stats to disk
,D/BtGatt.ScanManager( 2117): awakened up at time 1232359
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1233387
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1234415
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1235441
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1236471
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1237497
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1238524
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0,
,D/BtGatt.ScanManager( 2117): awakened up at time 1239552
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1240579
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1241604
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1242623
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,V/KeepSync( 3397): Connecting to GoogleApiClient
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1769): Handling authorization failure
E/ClientConnectionOperation( 1769): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1769): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1769): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1769): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1769): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1769): 	... 7 more
,V/KeepSync( 3397): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3397): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3397): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3397): (284) automatic index on blob_node(is_deleted)
,I/art     ( 1246): Explicit concurrent mark sweep GC freed 68676(3MB) AllocSpace objects, 11(1213KB) LOS objects, 37% free, 27MB/43MB, paused 1.887ms total 68.119ms
,I/GLSUser ( 1246): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1246): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1246): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1246): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1246): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 3397): IOException
E/KeepSync( 3397): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3397): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3397): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3397): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3397): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3397): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3397): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3397): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3397): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3397): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3397): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3397): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3397): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3397): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3397): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3397): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3397): 	... 10 more
W/KeepSync( 3397): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1242898, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/BtGatt.ScanManager( 2117): awakened up at time 1243642
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1244667
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1245692
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1246723
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1247743
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1248767
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1249790
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1250816
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1251843
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1252866
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1253895
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1254922
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1255945
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1256971
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1257994
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1259019
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1260046
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1261073
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1262100
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1263126
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1264153
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1265176
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1266201
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1267226
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1268251
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1269275
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1270301
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1271325
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1272351
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1273374
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1274399
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1275427
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2117): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1276451
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1277473
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1278497
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1279521
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1280545
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1281572
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1282598,
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1283624
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1284651
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1285678
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1286702
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1287725
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1288751
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1289777
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1290802
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1291825
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1292851
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2117): awakened up at time 1293876
,D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
,I/art     (  821): Explicit concurrent mark sweep GC freed 25942(1365KB) AllocSpace objects, 5(80KB) LOS objects, 32% free, 33MB/49MB, paused 2.316ms total 84.981ms
,D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
,TIME-OUT KILL (timeout was 1200000ms),D/BtGatt.ScanManager( 2117): awakened up at time 1294987
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2117): awakened up at time 1296012
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2117): awakened up at time 1297038
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2117): awakened up at time 1298062
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2117): awakened up at time 1299081
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2117): awakened up at time 1300106
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/AndroidRuntime( 3949): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3949): CheckJNI is OFF
D/AndroidRuntime( 3949): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  821): Killing 3176:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  821): Skipping PackageSetting{4ca7fdd com.example.hello/10273} due to missing metadata
E/libprocessgroup(  821): failed to kill 1 processes for processgroup 3176
W/ActivityManager(  821): Force removing ActivityRecord{219f4adc u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
E/JavaBinder(  821): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  821): !!! FAILED BINDER TRANSACTION !!!
V/ActivityManager(  821): Display changed displayId=0
W/DisplayManagerService(  821): Failed to notify process 3176 that displays changed, assuming it died.
W/DisplayManagerService(  821): android.os.DeadObjectException
W/DisplayManagerService(  821): 	at android.os.BinderProxy.transactNative(Native Method)
W/DisplayManagerService(  821): 	at android.os.BinderProxy.transact(Binder.java:496)
W/DisplayManagerService(  821): 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
W/DisplayManagerService(  821): 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1094)
W/DisplayManagerService(  821): 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:932)
W/DisplayManagerService(  821): 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:112)
W/DisplayManagerService(  821): 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1027)
W/DisplayManagerService(  821): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DisplayManagerService(  821): 	at android.os.Looper.loop(Looper.java:135)
W/DisplayManagerService(  821): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DisplayManagerService(  821): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
D/BtGatt.GattService( 2117): Binder is dead - unregistering client (5)!
D/BtGatt.GattService( 2117): Binder is dead - unregistering client (6)!
D/BtGatt.GattService( 2117): stopScan() - queue size =1
D/BtGatt.AdvertiseManager( 2117): message : 1
D/BtGatt.AdvertiseManager( 2117): stop advertise for client 6
D/BtGatt.AdvertiseManager( 2117): app died - unregistering client : 6
D/BtGatt.GattService( 2117): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2117): stopping BLe Batch
D/WifiService(  821): Client connection lost with reason: 4
D/BtGatt.GattService( 2117): unregisterClient() - clientIf=6
D/BtGatt.GattService( 2117): onAdvertiseInstanceDisabled() - clientIf=255, status=0
E/BtGatt.ContextMap( 2117): Context not found for ID 255
I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
D/BtGatt.GattService( 2117): onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2117): flushPendingBatchResults - clientIf = 5
D/BtGatt.GattService( 2117): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2117): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2117): app died, unregister client - 5
D/BtGatt.GattService( 2117): unregisterClient() - clientIf=5
I/Keyboard.Facilitator( 1227): resetDictionaries() : en_US
D/BuaReceiver( 3068): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
D/TaskPersister(  821): removeObsoleteFile: deleting file=2_task.xml
I/Keyboard.Facilitator.DecoderInitializer( 1227): run()
I/ActivityManager(  821): Start proc 3966:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
I/Decoder ( 1227): createOrResetDecoder
I/art     ( 1057): Explicit concurrent mark sweep GC freed 35587(1480KB) AllocSpace objects, 1(30MB) LOS objects, 21% free, 58MB/74MB, paused 1.180ms total 55.482ms
I/art     (  821): Explicit concurrent mark sweep GC freed 11374(901KB) AllocSpace objects, 3(142KB) LOS objects, 32% free, 33MB/49MB, paused 1.335ms total 90.409ms
I/art     (  821): WaitForGcToComplete blocked for 84.489ms for cause Explicit
I/ActivityManager(  821): Start proc 3983:com.google.android.googlequicksearchbox:search/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService
W/InputMethodManagerService(  821): Got RemoteException sending setActive(false) notification to pid 3176 uid 10265
I/Keyboard.Facilitator( 1227): onFinishInput()
I/ConfigService( 1246): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1227): run()
I/art     ( 1355): Explicit concurrent mark sweep GC freed 4962(361KB) AllocSpace objects, 13(1519KB) LOS objects, 31% free, 35MB/51MB, paused 1.043ms total 19.475ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1227): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1227): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1227): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1227): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1227): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1227): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1227): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1227): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1227): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1227): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1227): run()
I/StatsUtilsManager( 1227): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1227): shouldRecordStats() = Too Soon
D/JobSchedulerService(  821): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/VoicemailCleanupService( 3966): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  821): Start proc 4007:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
I/art     (  821): Explicit concurrent mark sweep GC freed 4665(229KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.985ms total 124.329ms
I/art     (  369): Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 202us total 12.639ms
I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 199us total 8.688ms
I/ActivityManager(  821): Killing 2870:com.google.android.music:main/u0a66 (adj 15): empty #17
I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 209us total 9.979ms
I/ContactLocale( 3966): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/art     ( 3949): System.exit called, status: 0
I/AndroidRuntime( 3949): VM exiting with result code 0.
D/Launcher.Workspace( 1355): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1355): 11683562 - stripEmptyScreens()
E/SQLiteLog( 1355): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
I/ActivityManager(  821): Start proc 4037:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
I/ActivityManager(  821): Killing 3365:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
E/SQLiteLog( 3966): (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 3966): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 3966): Process: android.process.acore, PID: 3966
E/AndroidRuntime( 3966): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3966): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 3966): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 3966): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 3966): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 3966): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 3966): 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
E/AndroidRuntime( 3966): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
E/AndroidRuntime( 3966): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 3966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3966): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 3966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ContextImpl( 4037): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
I/ActivityManager(  821): Start proc 4060:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  821): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  821): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  821): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  821): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  821): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  821): 	... 5 more
E/SQLiteLog( 1246): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1246): Shutting down VM
E/AndroidRuntime( 1246): FATAL EXCEPTION: main
E/AndroidRuntime( 1246): Process: com.google.process.gapps, PID: 1246
E/AndroidRuntime( 1246): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1246): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 1246): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 1246): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 1246): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1246): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1246): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 1246): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1246): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1246): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 1246): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 1246): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1246): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1246): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1246): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1246): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1246): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1246): 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
E/AndroidRuntime( 1246): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
E/AndroidRuntime( 1246): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
E/AndroidRuntime( 1246): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 1246): 	... 9 more
D/OpenGLRenderer(  821): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  821): Validating map...
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  821): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  821): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  821): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  821): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  821): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  821): 	... 5 more
E/SQLiteDatabase( 4037): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4037): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4037): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4037): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4037): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4037): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4037): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4037): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4037): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4037): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4037): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4037): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4037): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4037): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4037): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4037): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/SQLiteDatabase( 4037): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/SQLiteDatabase( 4037): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4037): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4037): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4037): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 4037): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4037): Process: com.android.keychain, PID: 4037
E/AndroidRuntime( 4037): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4037): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4037): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4037): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4037): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4037): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4037): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4037): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4037): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4037): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4037): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4037): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4037): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4037): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4037): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/AndroidRuntime( 4037): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/AndroidRuntime( 4037): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4037): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4037): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4037): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  821): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  821): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  821): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  821): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  821): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  821): 	... 5 more
D/AndroidRuntime( 3983): Shutting down VM
I/OpenGLRenderer(  821): Initialized EGL, version 1.4
D/OpenGLRenderer(  821): Enabling debug mode 0
I/ActivityManager(  821): Start proc 4095:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
E/SharedPreferencesImpl( 3983): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
E/AndroidRuntime( 3983): FATAL EXCEPTION: main
E/AndroidRuntime( 3983): Process: com.google.android.googlequicksearchbox:search, PID: 3983
E/AndroidRuntime( 3983): java.lang.RuntimeException: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR worker
E/AndroidRuntime( 3983): 	at com.google.android.search.core.bh$2.onFailure(SearchController.java:381)
E/AndroidRuntime( 3983): 	at com.google.android.apps.gsa.shared.util.c.a.r$1.run(TaskRunnerImpl.java:329)
E/AndroidRuntime( 3983): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 3983): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 3983): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 3983): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 3983): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 3983): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 3983): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 3983): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 3983): Caused by: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR worker
E/AndroidRuntime( 3983): 	at java.util.concurrent.FutureTask.report(FutureTask.java:93)
E/AndroidRuntime( 3983): 	at java.util.concurrent.FutureTask.get(FutureTask.java:163)
E/AndroidRuntime( 3983): 	at com.google.android.apps.gsa.shared.util.c.d.get(LazyListenableFuture.java:124)
E/AndroidRuntime( 3983): 	at com.google.android.apps.gsa.shared.util.c.d$1.call(LazyListenableFuture.java:46)
E/AndroidRuntime( 3983): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 3983): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 3983): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 3983): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 3983): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/AndroidRuntime( 3983): Caused by: com.google.android.libraries.velour.dynloader.h: Failed to load JAR worker
E/AndroidRuntime( 3983): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:216)
E/AndroidRuntime( 3983): 	at com.google.android.apps.gsa.shared.e.k.auz(ExtraDexRegistry.java:344)
E/AndroidRuntime( 3983): 	at com.google.android.apps.gsa.shared.e.k.a(ExtraDexRegistry.java:303)
E/AndroidRuntime( 3983): 	at com.google.android.apps.gsa.shared.e.k$1.auD(ExtraDexRegistry.java:323)
E/AndroidRuntime( 3983): 	at com.google.android.apps.gsa.shared.e.k$1.call(ExtraDexRegistry.java:318)
E/AndroidRuntime( 3983): 	... 5 more
E/AndroidRuntime( 3983): Caused by: java.io.IOException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 3983): 	at java.io.File.createNewFile(File.java:941)
E/AndroidRuntime( 3983): 	at com.google.android.libraries.velour.dynloader.i.bjP(JarLoader.java:278)
E/AndroidRuntime( 3983): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:207)
E/AndroidRuntime( 3983): 	... 9 more
E/AndroidRuntime( 3983): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 3983): 	at libcore.io.Posix.open(Native Method)
E/AndroidRuntime( 3983): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/AndroidRuntime( 3983): 	at java.io.File.createNewFile(File.java:934)
E/AndroidRuntime( 3983): 	... 11 more
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  821): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  821): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  821): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  821): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  821): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  821): 	... 5 more
D/GFEEDBACK_SendErrorReportOperation( 1769): Error doing instant send: java.io.IOException: failed to create reports directory
E/GFEEDBACK_SendErrorReportOperation( 1769): Error saving report: java.io.IOException: failed to create reports directory

```
