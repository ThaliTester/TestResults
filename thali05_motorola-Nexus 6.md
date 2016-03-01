#### Test 6122644500803c8_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2672): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2672): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2672): [1] 5.onFinished: Scheduling replication attempt 2.
D/AndroidRuntime( 3151): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3151): CheckJNI is OFF
D/AndroidRuntime( 3151): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{2453e2cd token=Token{ee75064 ActivityRecord{4ca29f7 u0 com.test.thalitest/.MainActivity t34}}} to stack=1 task=34 at 0
D/AndroidRuntime( 3151): Shutting down VM
I/HotwordDetector( 1502): Closing mic
I/MicrophoneInputStream( 1502): mic_close com.google.android.apps.gsa.speech.audio.u@3fb8dd91
V/WindowManager(  820): Adding window Window{3a4a47fc u0 Starting com.test.thalitest} at 2 of 7 (after Window{a0d1c31 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/ActivityManager(  820): Start proc 3165:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1502): Stopping hotword detection.
I/HotwordRecognitionRnr( 1502): Hotword detection finished
I/ActivityManager(  820): Killing 2764:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
I/art     ( 1376): Explicit concurrent mark sweep GC freed 24466(1292KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 772us total 32.002ms
I/WebViewFactory( 3165): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3165): Time to load native libraries: 2 ms (timestamps 6112-6114)
I/LibraryLoader( 3165): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3165): Binding Chromium to main looper Looper (main, tid 1) {61fa233}
I/LibraryLoader( 3165): Expected native library version number "",actual native library version number ""
I/chromium( 3165): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3165): Initializing chromium process, singleProcess=true
W/art     ( 3165): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3165): ApplicationContext is null in ApplicationStatus
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660618003
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,W/chromium( 3165): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3165): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3165): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3165): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3165): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  820): Message: 20
,D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cada82c:true
,D/BluetoothAdapter( 3165): 601306405: getState() :  mService = null. Returning STATE_OFF,
,I/kickstart(  878): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  878): STATUS: Wrote to /sys/power/wake_lock
,W/art     ( 3165): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3165): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3165): CordovaWebView is running on device made by: motorola
,E/kickstart(  878): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  878): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,W/art     ( 3165): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3165): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3165): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3165): Validating map...
,V/WindowManager(  820): Adding window Window{1481745c u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{3a4a47fc u0 Starting com.test.thalitest})
,W/chromium( 3165): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3165): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3165): Enabling debug mode 0
,I/ActivityManager(  820): Displayed com.test.thalitest/.MainActivity: +604ms
,I/Keyboard.Facilitator( 1222): onFinishInput()
,W/BindingManager( 3165): Cannot call determinedVisibility() - never saw a connection for the pid: 3165
,D/JsMessageQueue( 3165): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3165): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1578641280
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3165): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3165):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3165):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3165):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3165):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3165): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25df9a5a added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3165): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3165): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3165):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3165):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3165):     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3165):     - Discovery mode: BLE_AND_WIFI
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3165):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3165):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3165):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3165):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3165):     - Scan report delay in milliseconds: 500
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3165): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11ed0226 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3165): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  820): New client listening to asynchronous messages
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3165): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3165): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3165): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3165): setDiscoveryMode: BLE_AND_WIFI -> BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3165): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3165): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3165): setScanMode: 1 -> 2
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3165): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3165): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 3165): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/kickstart(  878): STATUS: Received file 'm9kefs2'
I/kickstart(  878): STATUS: 950272 bytes transferred in 1.001477 seconds
I/kickstart(  878): STATUS: Successfully downloaded files from target 
,I/kickstart(  878): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  878): STATUS: Sahara protocol completed
,W/jxcore-log( 3165): Initializing JXcore engine
W/jxcore-log( 3165): JXcore engine is ready
,W/Thread-330( 3220): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[9992]" dev="sockfs" ino=9992 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-330( 3220): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-330( 3220): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10215]" dev="sockfs" ino=10215 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-330( 3220): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20570]" dev="sockfs" ino=20570 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3165): Starting JXcore engine
,W/jxcore-log( 3165): Platform android
W/jxcore-log( 3165): 
W/jxcore-log( 3165): Process ARCH arm
W/jxcore-log( 3165): 
,I/jxcore-log( 3165): JXcore Cordova bridge is ready!
I/jxcore-log( 3165): 
W/jxcore-log( 3165): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 3165): execute: REQUEST_ACCESS_COARSE_LOCATION,
,I/ActivityManager(  820): Killing 2631:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3165): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
V/io.jxcore.node.JXcoreExtension( 3165): isBleMultipleAdvertisementSupported: NOT_RESOLVED
,I/jxcore-log( 3165): BLE multiple advertisement supported
I/jxcore-log( 3165): 
,I/jxcore-log( 3165): My device name is: motorola-Nexus 6
I/jxcore-log( 3165): 
,I/jxcore-log( 3165): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3165): 
,I/jxcore-log( 3165): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3165): 
,I/jxcore-log( 3165): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3165): 
I/jxcore-log( 3165): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3165): 
,I/jxcore-log( 3165): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 3165): 
,I/jxcore-log( 3165): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 3165): 
,I/io.jxcore.node.ConnectivityInfo( 3165): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 3165):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 3165):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 3165):     - is Wi-Fi enabled: false
I/io.jxcore.node.ConnectivityInfo( 3165):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 3165):     - BSSID name: null
I/io.jxcore.node.ConnectivityInfo( 3165):     - is connected/connecting to active network: false
I/io.jxcore.node.ConnectivityInfo( 3165):     - active network type is Wi-Fi: false
I/io.jxcore.node.ConnectivityInfo( 3165):     - force notify: true
,D/io.jxcore.node.JXcoreExtension( 3165): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
I/jxcore-log( 3165): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 3165): 
,I/jxcore-log( 3165): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 3165): 
,I/jxcore-log( 3165): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3165): 
,I/jxcore-log( 3165): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log( 3165): 
,I/jxcore-log( 3165): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 3165): 
,I/jxcore-log( 3165): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 3165): 
,I/jxcore-log( 3165): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 3165): 
,I/jxcore-log( 3165): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3165): 
,I/jxcore-log( 3165): Unit Test app is loaded
I/jxcore-log( 3165): 
,I/jxcore-log( 3165): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"off","blueTooth":"off","wifi":"off","cellular":"doNotCare"}
I/jxcore-log( 3165): 
,I/chromium( 3165): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,I/art     (  820): Explicit concurrent mark sweep GC freed 18522(897KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.537ms total 75.142ms
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2672): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2672): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2672): [1] 5.onFinished: Scheduling replication attempt 3.
,I/PowerManagerService(  820): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  820): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (238 us)
,I/DisplayManagerService(  820): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  820): Display changed displayId=0
,D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6482000,
D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0,
D/SurfaceControl(  820): Excessive delay in setPowerMode(): 270ms
,I/DreamManagerService(  820): Entering dreamland.
,I/PowerManagerService(  820): Dozing...
,I/DreamController(  820): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0,
,E/wifi    (  820): android_net_wifi_getLinkLayerStats: failed to get link statistics
E/WifiStateMachine(  820): cancelDelayedScan -> 1
D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/wifi    (  820): android_net_wifi_getLinkLayerStats: failed to get link statistics
,E/WifiStateMachine(  820): cancelDelayedScan -> 2
,I/Keyboard.Facilitator( 1222): onFinishInput()
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
,D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 2672): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2672): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2672): [1] 5.onFinished: Scheduling replication attempt 4.
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2672): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2672): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2672): [1] 5.onFinished: Scheduling replication attempt 5.
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2672): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2672): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2672): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1222): run()
I/Keyboard.Facilitator( 1222): flushDynamicLanguageModels()
,I/ConfigService( 1376): onCreate
,I/ConfigService( 1376): onDestroy
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1376): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1376): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1376): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1376): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1376): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1376): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1376): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2672): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2672): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2672): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2672): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2672): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2672): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2672): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2672): Ignoring header User-Agent because its value was null.
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1376): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1376): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1376): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1376): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1376): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1376): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1376): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2672): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2672): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2672): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2672): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2672): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2672): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2672): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2672): Ignoring header User-Agent because its value was null.
,I/art     ( 1376): Explicit concurrent mark sweep GC freed 49810(2MB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.883ms total 64.551ms
,I/art     (  820): Explicit concurrent mark sweep GC freed 38566(1912KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.838ms total 72.229ms
,I/EventLogService( 1741): Opted in for usage reporting
I/EventLogService( 1741): Aggregate from 1456843758429 (log), 1456843758429 (data)
,W/EventLogAggregator( 1741): Unknown tag: snet_gcore
W/EventLogAggregator( 1741): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1741): dumping service [account]
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1376): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1376): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
,W/GLSActivity( 1376): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1376): 	,at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1376): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
,W/GLSActivity( 1376): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1376): 	at android.os.Binder.execTransact(Binder.java:446),
,E/PlayEventLogger( 2672): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 2672): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2672): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2672): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2672): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2672): ,	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2672): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2672): Ignoring header User-Agent because its value was null.
,I/UsageStatsService(  820): User[0] Flushing usage stats to disk
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1376): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1376): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1376): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1376): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1376): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1376): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1376): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1376): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1376): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1376): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1376): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1376): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2672): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 2672): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2672): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2672): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2672): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867),
E/PlayEventLogger( 2672): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2672): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2672): Ignoring header User-Agent because its value was null.
,TIME-OUT KILL (timeout was 1200000ms)
```
