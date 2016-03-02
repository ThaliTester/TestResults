#### Test 613623661dfc74c_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1257): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1257): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1257): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1257): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2722): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2722): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2722): [1] 5.onFinished: Scheduling replication attempt 1.
,D/AndroidRuntime( 3223): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3223): CheckJNI is OFF
D/AndroidRuntime( 3223): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{29e66ad token=Token{363bf7c4 ActivityRecord{333552d7 u0 com.test.thalitest/.MainActivity t34}}} to stack=1 task=34 at 0
D/AndroidRuntime( 3223): Shutting down VM
V/WindowManager(  821): Adding window Window{27e07b5c u0 Starting com.test.thalitest} at 2 of 7 (after Window{305ea08a u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/HotwordDetector( 1508): Closing mic
I/MicrophoneInputStream( 1508): mic_close com.google.android.apps.gsa.speech.audio.u@228335
I/ActivityManager(  821): Start proc 3237:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1508): Stopping hotword detection.
I/HotwordRecognitionRnr( 1508): Hotword detection finished
I/ActivityManager(  821): Killing 2848:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660265747
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/kickstart(  874): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  874): STATUS: Wrote to /sys/power/wake_lock
,I/WebViewFactory( 3237): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,E/kickstart(  874): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  874): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
I/LibraryLoader( 3237): Time to load native libraries: 2 ms (timestamps 7123-7125)
I/LibraryLoader( 3237): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3237): Binding Chromium to main looper Looper (main, tid 1) {5906024}
I/LibraryLoader( 3237): Expected native library version number "",actual native library version number ""
I/chromium( 3237): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3237): Initializing chromium process, singleProcess=true
W/art     ( 3237): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3237): ApplicationContext is null in ApplicationStatus
W/chromium( 3237): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3237): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3237): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3237): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3237): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d67738c:true
W/art     ( 3237): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3237): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3237): CordovaWebView is running on device made by: motorola
W/art     ( 3237): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3237): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3237): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3237): Validating map...
V/WindowManager(  821): Adding window Window{2474d7bc u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{27e07b5c u0 Starting com.test.thalitest})
W/chromium( 3237): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3237): Initialized EGL, version 1.4
D/OpenGLRenderer( 3237): Enabling debug mode 0
I/ActivityManager(  821): Displayed com.test.thalitest/.MainActivity: +840ms
I/Keyboard.Facilitator( 1239): onFinishInput()
W/BindingManager( 3237): Cannot call determinedVisibility() - never saw a connection for the pid: 3237
D/JsMessageQueue( 3237): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3237): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576326144
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3237): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3237):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3237):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3237):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3237):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3237): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e6d38ee added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3237): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3237):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3237):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3237):     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3237):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3237):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3237):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3237):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3237):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3237):     - Scan report delay in milliseconds: 500
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3237): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c423025 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3237): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  821): New client listening to asynchronous messages
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3237): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3237): setDiscoveryMode: Discovery mode BLE is supported
,I/chromium( 3237): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/kickstart(  874): STATUS: Received file 'm9kefs2'
I/kickstart(  874): STATUS: 950272 bytes transferred in 0.991532 seconds
I/kickstart(  874): STATUS: Successfully downloaded files from target 
,I/kickstart(  874): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  874): STATUS: Sahara protocol completed
,W/jxcore-log( 3237): Initializing JXcore engine
W/jxcore-log( 3237): JXcore engine is ready
,W/Thread-345( 3294): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12846]" dev="sockfs" ino=12846 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-345( 3294): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-345( 3294): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[9848]" dev="sockfs" ino=9848 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-345( 3294): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20222]" dev="sockfs" ino=20222 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3237): Starting JXcore engine
,W/jxcore-log( 3237): Platform android
W/jxcore-log( 3237): 
W/jxcore-log( 3237): Process ARCH arm
W/jxcore-log( 3237): 
,I/jxcore-log( 3237): JXcore Cordova bridge is ready!
I/jxcore-log( 3237): 
W/jxcore-log( 3237): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 3237): execute: REQUEST_ACCESS_COARSE_LOCATION,
,I/ActivityManager(  821): Killing 2881:com.android.settings/1000 (adj 15): empty #17
,V/io.jxcore.node.JXcoreExtension( 3237): isBleMultipleAdvertisementSupported: SUPPORTED
,I/jxcore-log( 3237): BLE multiple advertisement supported
I/jxcore-log( 3237): 
,I/jxcore-log( 3237): INFO testUtils Toggling radios to: true
I/jxcore-log( 3237): 
,D/BluetoothAdapter( 3237): enable(): BT is already enabled..!
,I/jxcore-log( 3237): Unit Test app is loaded
I/jxcore-log( 3237): 
,D/WifiService(  821): setWifiEnabled: true pid=3237, uid=10265
,E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
,I/chromium( 3237): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,I/art     ( 1257): Explicit concurrent mark sweep GC freed 21905(1143KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.337ms total 48.025ms
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,I/jxcore-log( 3237): My device name is: motorola-Nexus 6
I/jxcore-log( 3237): 
,I/jxcore-log( 3237): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3237): 
,I/jxcore-log( 3237): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3237): 
,I/jxcore-log( 3237): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3237): 
,I/jxcore-log( 3237): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3237): 
,I/jxcore-log( 3237): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 3237): 
,I/jxcore-log( 3237): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 3237): 
,I/io.jxcore.node.ConnectivityInfo( 3237): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 3237):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 3237):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 3237):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 3237):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 3237):     - BSSID name: null
I/io.jxcore.node.ConnectivityInfo( 3237):     - is connected/connecting to active network: false
I/io.jxcore.node.ConnectivityInfo( 3237):     - active network type is Wi-Fi: false
I/io.jxcore.node.ConnectivityInfo( 3237):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 3237): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,I/jxcore-log( 3237): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 3237): 
,I/jxcore-log( 3237): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 3237): 
,V/GLSActivity( 1257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1257): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1257): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1257): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1257): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 36144(1838KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.638ms total 86.046ms
,D/Finsky  ( 2722): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2722): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2722): [1] 5.onFinished: Scheduling replication attempt 2.
,I/jxcore-log( 3237): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3237): 
,I/jxcore-log( 3237): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log( 3237): 
,I/jxcore-log( 3237): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 3237): 
,I/jxcore-log( 3237): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
I/jxcore-log( 3237): 
,I/jxcore-log( 3237): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log( 3237): 
,I/jxcore-log( 3237): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log( 3237): 
,I/jxcore-log( 3237): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js,
I/jxcore-log( 3237): 
,I/jxcore-log( 3237): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 3237): 
,I/jxcore-log( 3237): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3237): 
,I/jxcore-log( 3237): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
I/jxcore-log( 3237): ,
,I/ValidateNoPeople(  821): skipping global notification
,V/GLSActivity( 1257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1257): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1257): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1257): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1257): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2722): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2722): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2722): [1] 5.onFinished: Scheduling replication attempt 3.
,I/PowerManagerService(  821): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  280): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (317 us)
,I/DisplayManagerService(  821): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  280): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  280): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  821): Display changed displayId=0
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  280): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  821): Excessive delay in setPowerMode(): 276ms
,I/DreamManagerService(  821): Entering dreamland.
,I/PowerManagerService(  821): Dozing...
,I/DreamController(  821): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  821): cancelDelayedScan -> 16
,E/native  (  821): do suspend false
,I/Keyboard.Facilitator( 1239): onFinishInput()
,E/WifiStateMachine(  821): cancelDelayedScan -> 18,
,E/native  (  821): do suspend true
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  821): WifiStateMachine Disconnected CMD_START_SCAN source -2 17, 18 -> obsolete
,E/WifiStateMachine(  821): WifiStateMachine Disconnected CMD_START_SCAN source -2 15, 18 -> obsolete
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,V/GLSActivity( 1257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1257): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1257): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1257): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1257): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2722): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2722): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2722): [1] 5.onFinished: Scheduling replication attempt 4.
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,V/GLSActivity( 1257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1257): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1257): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1257): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1257): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2722): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2722): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2722): [1] 5.onFinished: Scheduling replication attempt 5.
,V/GLSActivity( 1257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1257): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1257): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1257): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1257): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2722): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2722): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2722): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1239): run()
I/Keyboard.Facilitator( 1239): flushDynamicLanguageModels()
,I/ConfigService( 1257): onCreate
,I/ConfigService( 1257): onDestroy
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,V/GLSActivity( 1257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1257): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1257): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1257): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1257): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1257): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1257): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1257): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1257): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1257): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1257): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1257): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2722): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2722): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2722): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2722): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2722): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2722): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2722): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2722): Ignoring header User-Agent because its value was null.
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@33f05f4b}
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@33f05f4b}
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,I/EventLogService( 1794): Opted in for usage reporting
I/EventLogService( 1794): Aggregate from 1456918778867 (log), 1456918778867 (data)
,W/EventLogAggregator( 1794): Unknown tag: snet_gcore
W/EventLogAggregator( 1794): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1794): dumping service [account]
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,I/art     (  821): Explicit concurrent mark sweep GC freed 48673(2MB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.760ms total 97.104ms
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,V/GLSActivity( 1257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1257): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1257): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1257): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1257): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1257): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1257): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1257): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1257): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1257): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1257): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1257): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2722): Failed to get auth token: User intervention required. Notification has been pushed.
,E/PlayEventLogger( 2722): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2722): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2722): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2722): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2722): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
,E/PlayEventLogger( 2722): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2722): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,I/art     ( 1257): Explicit concurrent mark sweep GC freed 52415(2MB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.719ms total 43.729ms
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,W/bt-btm  ( 2125): Stopping oneshot timer
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,V/GLSActivity( 1257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1257): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1257): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1257): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1257): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1257): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1257): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1257): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1257): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1257): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1257): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1257): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2722): Failed to get auth token: User intervention required. Notification has been pushed.
,E/PlayEventLogger( 2722): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2722): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2722): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2722): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2722): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2722): 	,at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2722): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,I/UsageStatsService(  821): User[0] Flushing usage stats to disk
,V/GLSActivity( 1257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1257): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1257): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1257): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1257): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1257): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1257): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
,W/GLSActivity( 1257): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1257): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1257): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1257): ,	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1257): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1257): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2722): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2722): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2722): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2722): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2722): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2722): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2722): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2722): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2125): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1200000ms)
```
