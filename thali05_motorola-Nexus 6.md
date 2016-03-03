#### Test 6136236661fd38c_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1366): Explicit concurrent mark sweep GC freed 23678(1263KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 2.047ms total 46.086ms
D/Finsky  ( 2707): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2707): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2707): [1] 5.onFinished: Scheduling replication attempt 2.
,D/AndroidRuntime( 3213): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3213): CheckJNI is OFF
D/AndroidRuntime( 3213): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{13d280f7 token=Token{1f6644f6 ActivityRecord{ae4ad91 u0 com.test.thalitest/.MainActivity t34}}} to stack=1 task=34 at 0
V/WindowManager(  820): Adding window Window{21bcfcce u0 Starting com.test.thalitest} at 2 of 7 (after Window{2d054800 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/MicrophoneInputStream( 1524): mic_close com.google.android.apps.gsa.speech.audio.u@fa0249d
I/HotwordDetector( 1524): Closing mic
D/AndroidRuntime( 3213): Shutting down VM
I/ActivityManager(  820): Start proc 3227:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1524): Hotword detection finished
I/HotwordRecognitionRnr( 1524): Stopping hotword detection.
I/ActivityManager(  820): Killing 2838:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1720112403
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/WebViewFactory( 3227): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3227): Time to load native libraries: 4 ms (timestamps 8711-8715)
I/LibraryLoader( 3227): Expected native library version number "",actual native library version number ""
I/kickstart(  870): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  870): STATUS: Wrote to /sys/power/wake_lock
V/WebViewChromiumFactoryProvider( 3227): Binding Chromium to main looper Looper (main, tid 1) {1525f2df}
I/LibraryLoader( 3227): Expected native library version number "",actual native library version number ""
I/chromium( 3227): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3227): Initializing chromium process, singleProcess=true
W/art     ( 3227): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3227): ApplicationContext is null in ApplicationStatus
W/chromium( 3227): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
E/kickstart(  870): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  870): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
W/chromium( 3227): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3227): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3227): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3227): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2dc8357e:true
W/art     ( 3227): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3227): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3227): CordovaWebView is running on device made by: motorola
W/art     ( 3227): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3227): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3227): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3227): Validating map...
V/WindowManager(  820): Adding window Window{2f2afa2e u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{21bcfcce u0 Starting com.test.thalitest})
W/chromium( 3227): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3227): Initialized EGL, version 1.4
D/OpenGLRenderer( 3227): Enabling debug mode 0
I/Keyboard.Facilitator( 1229): onFinishInput()
I/ActivityManager(  820): Displayed com.test.thalitest/.MainActivity: +717ms
W/BindingManager( 3227): Cannot call determinedVisibility() - never saw a connection for the pid: 3227
D/JsMessageQueue( 3227): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3227): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576395776
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3227): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3227):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3227):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3227):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3227):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3227): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2748ab51 added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3227): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3227):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3227):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3227):     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3227):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3227):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3227):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3227):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3227):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3227):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3227): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31c1c424 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3227): addListener: New listener added - the number of listeners is now 1
D/WifiService(  820): New client listening to asynchronous messages
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3227): setDiscoveryMode: Discovery mode BLE is supported
I/chromium( 3227): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/kickstart(  870): STATUS: Received file 'm9kefs2'
I/kickstart(  870): STATUS: 950272 bytes transferred in 1.001374 seconds
I/kickstart(  870): STATUS: Successfully downloaded files from target 
I/kickstart(  870): STATUS: Wrote to /sys/power/wake_unlock
I/kickstart(  870): STATUS: Sahara protocol completed
,W/jxcore-log( 3227): Initializing JXcore engine
W/jxcore-log( 3227): JXcore engine is ready
W/Thread-338( 3280): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12958]" dev="sockfs" ino=12958 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-338( 3280): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-338( 3280): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[13033]" dev="sockfs" ino=13033 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-338( 3280): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20076]" dev="sockfs" ino=20076 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 3227): Starting JXcore engine
W/jxcore-log( 3227): Platform android
W/jxcore-log( 3227): 
W/jxcore-log( 3227): Process ARCH arm
W/jxcore-log( 3227): 
,I/jxcore-log( 3227): JXcore Cordova bridge is ready!
I/jxcore-log( 3227): 
W/jxcore-log( 3227): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 3227): SDK.Build.VERSION: 22
I/org.thaliproject.p2p.ThaliPermissions( 3227): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/ActivityManager(  820): Killing 2867:com.android.settings/1000 (adj 15): empty #17
,V/io.jxcore.node.JXcoreExtension( 3227): isBleMultipleAdvertisementSupported: SUPPORTED
,I/jxcore-log( 3227): WARN testUtils BLE multiple advertisement issue: null
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): INFO testUtils Toggling radios to: true
,I/jxcore-log( 3227): 
,D/BluetoothAdapter( 3227): enable(): BT is already enabled..!,
,I/jxcore-log( 3227): Unit Test app is loaded
,I/jxcore-log( 3227): 
,D/WifiService(  820): setWifiEnabled: true pid=3227, uid=10265
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,I/chromium( 3227): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,I/jxcore-log( 3227): My device name is: motorola-Nexus 6
I/jxcore-log( 3227): 
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,I/jxcore-log( 3227): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
,I/jxcore-log( 3227): 
,I/jxcore-log( 3227): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
,I/jxcore-log( 3227): 
,I/jxcore-log( 3227): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 3227): 
I/jxcore-log( 3227): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 3227): 
,I/io.jxcore.node.ConnectivityInfo( 3227): updateConnectivityInfo: 
,I/io.jxcore.node.ConnectivityInfo( 3227):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 3227):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 3227):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 3227):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 3227):     - BSSID name: null
I/io.jxcore.node.ConnectivityInfo( 3227):     - is connected/connecting to active network: false
I/io.jxcore.node.ConnectivityInfo( 3227):     - active network type is Wi-Fi: false
I/io.jxcore.node.ConnectivityInfo( 3227):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 3227): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,I/jxcore-log( 3227): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
,I/jxcore-log( 3227): 
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3227): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
I/jxcore-log( 3227): 
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/jxcore-log( 3227): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
,I/jxcore-log( 3227): 
V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2707): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2707): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2707): [1] 5.onFinished: Scheduling replication attempt 3.
,I/jxcore-log( 3227): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
,I/jxcore-log( 3227): 
,I/jxcore-log( 3227): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
I/jxcore-log( 3227): ,
,I/ValidateNoPeople(  820): skipping global notification
,I/art     (  820): Explicit concurrent mark sweep GC freed 40278(2MB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.583ms total 89.762ms
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2707): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2707): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2707): [1] 5.onFinished: Scheduling replication attempt 4.
,I/PowerManagerService(  820): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  820): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (317 us)
,I/DisplayManagerService(  820): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  820): Display changed displayId=0
,D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  820): Excessive delay in setPowerMode(): 254ms
,I/DreamManagerService(  820): Entering dreamland.
,I/PowerManagerService(  820): Dozing...
I/DreamController(  820): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  820): cancelDelayedScan -> 17
,I/Keyboard.Facilitator( 1229): onFinishInput()
,E/native  (  820): do suspend false
,E/WifiStateMachine(  820): cancelDelayedScan -> 19
,E/native  (  820): do suspend true
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  820): WifiStateMachine Disconnected CMD_START_SCAN source -2 18, 19 -> obsolete
,E/WifiStateMachine(  820): WifiStateMachine Disconnected CMD_START_SCAN source -2 16, 19 -> obsolete
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2707): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2707): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2707): [1] 5.onFinished: Scheduling replication attempt 5.
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2707): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2707): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2707): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1229): run()
I/Keyboard.Facilitator( 1229): flushDynamicLanguageModels()
,I/ConfigService( 1366): onCreate
,I/ConfigService( 1366): onDestroy
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@10526105}
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@10526105}
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1366): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1366): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1366): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1366): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1366): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1366): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1366): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2707): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2707): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2707): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2707): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2707): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2707): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2707): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2707): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/Finsky  ( 2707): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2707): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1366): Explicit concurrent mark sweep GC freed 47241(2MB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.552ms total 43.444ms,
,I/art     (  820): Explicit concurrent mark sweep GC freed 45708(2MB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.537ms total 81.706ms
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2707): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2707): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 2707): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 2707): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2707): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/DeviceConnectionService( 1797): client connected with version: 7571000
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1366): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1366): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1366): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1366): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1366): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1366): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1366): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2707): Failed to get auth token: User intervention required. Notification has been pushed.,
E/PlayEventLogger( 2707): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2707): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2707): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2707): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2707): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2707): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2707): Ignoring header User-Agent because its value was null.
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2707): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2707): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2707): [1] 5.onFinished: Scheduling replication attempt 1.
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2707): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2707): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2707): [1] 5.onFinished: Scheduling replication attempt 2.
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 2707): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2707): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2707): [1] 5.onFinished: Scheduling replication attempt 3.
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2707): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2707): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2707): [1] 5.onFinished: Scheduling replication attempt 4.
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2707): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2707): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2707): [1] 5.onFinished: Scheduling replication attempt 5.
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 2707): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2707): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2707): [1] 5.onFinished: Giving up after 6 failures.
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,W/bt-btm  ( 2122): Stopping oneshot timer,
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 27334(1196KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.408ms total 78.160ms
,W/GLSActivity( 1366): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1366): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1366): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1366): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1366): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1366): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1366): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2707): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2707): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2707): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2707): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2707): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2707): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2707): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2707): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,I/art     ( 1366): Explicit concurrent mark sweep GC freed 60813(2MB) AllocSpace objects, 3(331KB) LOS objects, 37% free, 26MB/42MB, paused 958us total 36.023ms
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,I/UsageStatsService(  820): User[0] Flushing usage stats to disk
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1366): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1366): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1366): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1366): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1366): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1366): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1366): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1366): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1366): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1366): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1366): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2707): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2707): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2707): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2707): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2707): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2707): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2707): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2707): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1400000ms)
```
