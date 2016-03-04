#### Test 614329799926788_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2668): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2668): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2668): [1] 5.onFinished: Scheduling replication attempt 1.
D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/AndroidRuntime( 3145): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3145): CheckJNI is OFF
D/AndroidRuntime( 3145): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{16315c6 token=Token{da1ffa1 ActivityRecord{3c634c08 u0 com.test.thalitest/.MainActivity t2}}} to stack=1 task=2 at 0
V/WindowManager(  820): Adding window Window{9aa01d9 u0 Starting com.test.thalitest} at 2 of 7 (after Window{1171044 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
D/AndroidRuntime( 3145): Shutting down VM
I/HotwordDetector( 1471): Closing mic
I/MicrophoneInputStream( 1471): mic_close com.google.android.apps.gsa.speech.audio.u@3b145caf
I/ActivityManager(  820): Start proc 3159:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  359): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  359): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  359): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1471): Stopping hotword detection.
I/HotwordRecognitionRnr( 1471): Hotword detection finished
I/Keyboard.Facilitator.LanguageModelFlusher( 1213): run()
I/Keyboard.Facilitator( 1213): flushDynamicLanguageModels()
I/art     (  820): Explicit concurrent mark sweep GC freed 24743(1185KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.062ms total 56.530ms
I/ConfigService( 1494): onCreate
I/ActivityManager(  820): Killing 2792:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659176211
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/ActivityManager(  820): Killing 2626:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
I/WebViewFactory( 3159): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3159): Time to load native libraries: 3 ms (timestamps 6688-6691)
I/LibraryLoader( 3159): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3159): Binding Chromium to main looper Looper (main, tid 1) {135bc229}
I/LibraryLoader( 3159): Expected native library version number "",actual native library version number ""
I/chromium( 3159): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3159): Initializing chromium process, singleProcess=true
W/art     ( 3159): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3159): ApplicationContext is null in ApplicationStatus
W/chromium( 3159): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3159): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3159): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3159): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3159): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3aca667c:true
W/art     ( 3159): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3159): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3159): CordovaWebView is running on device made by: motorola
W/art     ( 3159): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3159): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3159): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3159): Validating map...
V/WindowManager(  820): Adding window Window{eb266ac u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{9aa01d9 u0 Starting com.test.thalitest})
W/chromium( 3159): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3159): Initialized EGL, version 1.4
D/OpenGLRenderer( 3159): Enabling debug mode 0
I/ActivityManager(  820): Displayed com.test.thalitest/.MainActivity: +1s177ms
I/Keyboard.Facilitator( 1213): onFinishInput()
W/BindingManager( 3159): Cannot call determinedVisibility() - never saw a connection for the pid: 3159
D/JsMessageQueue( 3159): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3159): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576392960
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3159): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3159):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3159):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3159):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3159):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3159): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375b754b added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3159): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3159):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3159):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3159):     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3159):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3159):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3159):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3159):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3159):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3159):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3159): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a7029e6 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3159): addListener: New listener added - the number of listeners is now 1
D/WifiService(  820): New client listening to asynchronous messages
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3159): setDiscoveryMode: Discovery mode BLE is supported
I/chromium( 3159): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3159): Initializing JXcore engine
W/jxcore-log( 3159): JXcore engine is ready
,W/Thread-329( 3216): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12473]" dev="sockfs" ino=12473 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-329( 3216): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-329( 3216): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10928]" dev="sockfs" ino=10928 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0,
W/Thread-329( 3216): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21129]" dev="sockfs" ino=21129 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3159): Starting JXcore engine
,W/jxcore-log( 3159): Platform android
W/jxcore-log( 3159): 
,W/jxcore-log( 3159): Process ARCH arm
W/jxcore-log( 3159): 
,I/jxcore-log( 3159): JXcore Cordova bridge is ready!
I/jxcore-log( 3159): 
W/jxcore-log( 3159): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 3159): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/ConfigService( 1494): onDestroy
,V/io.jxcore.node.JXcoreExtension( 3159): isBleMultipleAdvertisementSupported: SUPPORTED
,I/jxcore-log( 3159): BLE multiple advertisement supported
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): My device name is: motorola-Nexus 6
I/jxcore-log( 3159): 
,I/art     ( 1494): Explicit concurrent mark sweep GC freed 19834(1071KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.185ms total 21.103ms
,I/jxcore-log( 3159): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 3159): 
,I/io.jxcore.node.ConnectivityInfo( 3159): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - BSSID name: null
I/io.jxcore.node.ConnectivityInfo( 3159):     - is connected/connecting to active network: false
I/io.jxcore.node.ConnectivityInfo( 3159):     - active network type is Wi-Fi: false
I/io.jxcore.node.ConnectivityInfo( 3159):     - force notify: true
,D/io.jxcore.node.JXcoreExtension( 3159): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
I/jxcore-log( 3159): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
I/jxcore-log( 3159): 
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2668): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2668): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2668): [1] 5.onFinished: Scheduling replication attempt 2.
,I/jxcore-log( 3159): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): Unit Test app is loaded
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"on","blueTooth":"on","wifi":"on","cellular":"doNotCare"}
I/jxcore-log( 3159): 
,I/chromium( 3159): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2668): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2668): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2668): [1] 5.onFinished: Scheduling replication attempt 3.
,I/wpa_supplicant( 1185): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2668): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2668): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2668): [1] 5.onFinished: Scheduling replication attempt 4.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1213): run()
I/Keyboard.Facilitator( 1213): flushDynamicLanguageModels()
,I/ConfigService( 1494): onCreate
,I/ConfigService( 1494): onDestroy
,I/PowerManagerService(  820): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  820): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (313 us)
,I/DisplayManagerService(  820): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6082000
,D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  820): Display changed displayId=0
,I/kickstart(  876): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  876): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  876): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,I/kickstart(  876): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  820): Excessive delay in setPowerMode(): 283ms
,I/DreamManagerService(  820): Entering dreamland.
,I/PowerManagerService(  820): Dozing...
I/DreamController(  820): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  820): cancelDelayedScan -> 16
,E/native  (  820): do suspend false
,I/Keyboard.Facilitator( 1213): onFinishInput()
,E/WifiStateMachine(  820): cancelDelayedScan -> 18
,E/native  (  820): do suspend true
,D/audio_hw_primary(  359): adev_set_parameters: enter: screen_state=off,
D/mot_vr_audio_hw(  359): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  820): WifiStateMachine Disconnected CMD_START_SCAN source -2 17, 18 -> obsolete
,E/WifiStateMachine(  820): WifiStateMachine Disconnected CMD_START_SCAN source -2 15, 18 -> obsolete
,I/kickstart(  876): STATUS: Received file 'm9kefs1',
I/kickstart(  876): STATUS: 950272 bytes transferred in 0.994651 seconds
I/kickstart(  876): STATUS: Successfully downloaded files from target 
,I/kickstart(  876): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  876): STATUS: Sahara protocol completed
,I/wpa_supplicant( 1185): wlan0: Trying to associate with SSID 'NG700'
,I/wpa_supplicant( 1185): wlan0: Associated with f4:f2:6d:22:99:3e
,I/wpa_supplicant( 1185): wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1185): wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,D/ConnectivityService(  820): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  355): Setting iface cfg
,E/WifiStateMachine(  820): Start Dhcp Watchdog 1,
,E/WifiStateMachine(  820):  WifiLinkLayerStats: ,
E/WifiStateMachine(  820):  my bss beacon rx: 1
E/WifiStateMachine(  820):  RSSI mgmt: -40
E/WifiStateMachine(  820):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  820):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  on_time : 0 tx_time=61 rx_time=67 scan_time=0
,E/native  (  820): do suspend false
,E/WifiStateMachine(  820): scanCount==0 - aborting
,I/dhcpcd  ( 3242): version 5.5.6 starting
,I/dhcpcd  ( 3242): wlan0: rebinding lease of 192.168.1.125
,I/dhcpcd  ( 3242): wlan0: acknowledged 192.168.1.125 from 192.168.1.1
,I/dhcpcd  ( 3242): wlan0: leased 192.168.1.125 for 172800 seconds
,E/native  (  820): do suspend true
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  820): Adding iface wlan0 to network 100
,E/WifiStateMachine(  820): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  820): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  820): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  820): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  820): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  820): Setting Dns servers for network 100 to [/192.168.1.1]
,D/ConnectivityService(  820): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  820): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  820):    accepting network in place of null
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
D/ConnectivityService(  820): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
D/ConnectivityService(  820): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  820): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524290
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,V/BackupManagerService(  820): Scheduling immediate backup pass
,V/BackupManagerService(  820): Running a backup pass
,I/NetworkMonitor( 2828): type=WIFI subType= reason=null isConnected=true
,V/BackupManagerService(  820): clearing pending backups
,V/MusicLeanback( 2828): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
V/PerformBackupTask(  820): Beginning backup of 14 targets
,D/PerformBackupTask(  820): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  820): doBackup() invoked
,I/PMBA    (  820): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,I/BackupRestoreController(  820): Getting widget state for user: 0
,I/ActivityManager(  820): Start proc 3282:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,D/PhoneInterfaceManager( 1257): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1257): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
D/AlarmManagerService(  820): Setting time of day to sec=1457077289
W/AlarmManagerService(  820): Unable to set rtc to 1457077289: Invalid argument
,E/GpsLocationProvider(  820): No APN found to select.
,D/GpsLocationProvider(  820): NTP server returned: 1457077289981 (Fri Mar 04 08:41:29 GMT+01:00 2016) reference: 167993 certainty: 28 system time offset: -42
,W/GmsBackupTransport( 1805): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1805): starting performBackup for @pm@
,V/GmsBackupTransport( 1805): performBackup done for @pm@
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Mar 2016 07:41:30 GMT], X-Android-Received-Millis=[1457077290051], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1457077289565]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Validated
,D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  820): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1065): CM callback handler got msg 524290
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1494): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1494): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1494): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1494): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1494): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1494): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1494): 	at android.os.Binder.execTransact(Binder.java:446)
,E/Auth.Api.Credentials( 1769): [CredentialSyncAdapter] Unknown sync event.
,I/ActivityManager(  820): Start proc 3316:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,W/GmsBackupTransport( 1805): Error sending final backup to server: 
W/GmsBackupTransport( 1805): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1805): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1805): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1805): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1805): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1805): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1805): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1805): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1805): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1805): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1805): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1805): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1805): 	... 1 more
,D/BackupManagerService(  820): Now staging backup of com.google.android.talk
,D/BackupManagerService(  820): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  820): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  820): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  820): Now staging backup of com.google.android.gm
,D/BackupManagerService(  820): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  820): Now staging backup of com.android.nfc
,D/BackupManagerService(  820): Now staging backup of com.google.android.apps.genie.geniewidget
,D/SprintDMReceiver( 3316): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/BackupManagerService(  820): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  820): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  820): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  820): Now staging backup of com.android.vending
,D/BackupManagerService(  820): Now staging backup of android
,D/BackupManagerService(  820): Now staging backup of com.google.android.googlequicksearchbox
,D/SprintDMHelper( 3316): simOperator:  IMSI: null
D/SprintDMReceiver( 3316): Not Sprint UICC, don't do anything.
,I/GmsBackupTransport( 1805): Next backup will happen in 43199951 millis.
,W/DriveInitializer( 1769): Background init thread started
I/BackupManagerService(  820): Backup pass finished.
,I/SystemUpdateService( 1769): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1769): onCreate
,D/SystemUpdateService( 1769): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1769): active receiver: enabled
,I/SystemUpdateService( 1769): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1769): network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: true
I/SystemUpdateService( 1769): now status is 0 (complete)
I/SystemUpdateService( 1769): processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
I/SystemUpdateService( 1769): file has been verified
I/SystemUpdateService( 1769): OTA package size = 105451271
,I/art     (  820): Explicit concurrent mark sweep GC freed 62327(3MB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 1.832ms total 74.818ms
,I/SystemUpdateService( 1769): showing system update notification
,I/ValidateNoPeople(  820): skipping global notification
,W/art     ( 1769): No such thread id for suspend: 36
W/art     ( 1769): No such thread id for suspend: 36
,W/art     ( 1769): No such thread id for suspend: 36
W/art     ( 1769): No such thread id for suspend: 36
,D/SystemUpdateService( 1769): onDestroy
,W/DriveInitializer( 1769): Awaiting to be initialized
,I/art     ( 1494): Explicit concurrent mark sweep GC freed 19348(1045KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 591us total 21.241ms
,I/iu.SyncManager( 1769): SYNC; picasa accounts
,W/DriveInitializer( 1769): Background init thread ended
,D/NetworkLogImpl( 1769): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1769): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1769): num queued entries: 0
,I/iu.UploadsManager( 1769): num updated entries: 0
,I/iu.SyncManager( 1769): NEXT; no task
,D/ChimeraCfgMgr( 1769): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1769): [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,I/ActivityManager(  820): Start proc 3361:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  820): Start proc 3379:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,E/HttpOperation( 2941): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2941): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2941): 	at jdm.a(PG:82)
E/HttpOperation( 2941): 	at jcs.o(PG:406)
E/HttpOperation( 2941): 	at jcn.a(PG:1379)
E/HttpOperation( 2941): 	at jcs.i(PG:143)
E/HttpOperation( 2941): 	at blb.a(PG:3937)
E/HttpOperation( 2941): 	at czp.a(PG:18188)
E/HttpOperation( 2941): 	at czp.a(PG:9081)
E/HttpOperation( 2941): 	at czq.run(PG:1686)
E/HttpOperation( 2941): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2941): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2941): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2941): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2941): 	at jdj.a(PG:4091)
E/HttpOperation( 2941): 	at jdj.a(PG:1125)
E/HttpOperation( 2941): 	at jdm.a(PG:77)
E/HttpOperation( 2941): 	... 12 more
E/HttpOperation( 2941): Caused by: faj: BadAuthentication
E/HttpOperation( 2941): 	at fal.a(PG:38)
E/HttpOperation( 2941): 	at jdj.a(PG:4089)
E/HttpOperation( 2941): 	... 14 more
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2941): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2941): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2941): 	at jdm.a(PG:82)
E/HttpOperation( 2941): 	at jcs.o(PG:406)
E/HttpOperation( 2941): 	at jcn.a(PG:1379)
E/HttpOperation( 2941): 	at jcs.i(PG:143)
E/HttpOperation( 2941): 	at hec.a(PG:42)
E/HttpOperation( 2941): 	at hee.a(PG:102)
E/HttpOperation( 2941): 	at czr.a(PG:65)
E/HttpOperation( 2941): 	at kka.a(PG:108)
E/HttpOperation( 2941): 	at czp.a(PG:19176)
E/HttpOperation( 2941): 	at czp.a(PG:9081)
E/HttpOperation( 2941): 	at czq.run(PG:1686)
E/HttpOperation( 2941): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2941): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2941): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2941): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2941): 	at jdj.a(PG:4091)
E/HttpOperation( 2941): 	at jdj.a(PG:1125)
E/HttpOperation( 2941): 	at jdm.a(PG:77)
E/HttpOperation( 2941): 	... 15 more
E/HttpOperation( 2941): Caused by: faj: BadAuthentication
E/HttpOperation( 2941): 	at fal.a(PG:38)
E/HttpOperation( 2941): 	at jdj.a(PG:4089)
E/HttpOperation( 2941): 	... 17 more
E/ExperimentLoader( 2941): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2941): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2941): 	at jdm.a(PG:82)
E/ExperimentLoader( 2941): 	at jcs.o(PG:406)
E/ExperimentLoader( 2941): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2941): 	at jcs.i(PG:143)
E/ExperimentLoader( 2941): 	at hec.a(PG:42)
E/ExperimentLoader( 2941): 	at hee.a(PG:102)
E/ExperimentLoader( 2941): 	at czr.a(PG:65)
E/ExperimentLoader( 2941): 	at kka.a(PG:108)
E/ExperimentLoader( 2941): 	at czp.a(PG:19176)
E/ExperimentLoader( 2941): 	at czp.a(PG:9081)
E/ExperimentLoader( 2941): 	at czq.run(PG:1686)
E/ExperimentLoader( 2941): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2941): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2941): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2941): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2941): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2941): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2941): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2941): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2941): 	at jdm.a(PG:77)
E/ExperimentLoader( 2941): 	... 15 more
E/ExperimentLoader( 2941): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2941): 	at fal.a(PG:38)
E/ExperimentLoader( 2941): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2941): 	... 17 more
,I/GAv4    ( 3361): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3361):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3361):   adb logcat -s GAv4
,W/GAv4    ( 3361): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3361): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3361): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 2088): connection state changed from DISCONNECTED to CONNECTED
,I/ActivityManager(  820): Killing 2290:com.android.settings/1000 (adj 15): empty #17
,D/GCM     ( 1494): Connected
,D/GCM     ( 1494): Message class com.google.f.a.a.p
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 37714, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager(  820): Killing 2412:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/ActivityManager(  820): Start proc 3421:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/art     (  370): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 756us total 34.333ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 209us total 12.925ms
,I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 205us total 9.866ms
,I/WebViewFactory( 3361): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3361): Time to load native libraries: 2 ms (timestamps 8989-8991)
,I/LibraryLoader( 3361): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3361): Binding Chromium to main looper Looper (main, tid 1) {fa62b3}
,I/LibraryLoader( 3361): Expected native library version number "",actual native library version number ""
,I/chromium( 3361): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3361): Initializing chromium process, singleProcess=true
W/art     ( 3361): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3361): ApplicationContext is null in ApplicationStatus
V/KeepSync( 3379): Connecting to GoogleApiClient
,W/chromium( 3361): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3361): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3361): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 3361): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 3361): Requires BLUETOOTH permission
,I/NSApplication( 3361): Starting up...
,I/ActivityManager(  820): Start proc 3463:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,W/BaseAppContext( 1769): Using Auth Proxy for data requests.
,W/BaseAppContext( 1769): Using Auth Proxy for data requests.
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3379): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3379): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3379): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3379): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3379): IOException
E/KeepSync( 3379): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3379): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3379): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3379): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3379): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3379): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3379): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3379): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3379): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3379): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3379): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3379): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3379): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3379): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3379): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3379): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3379): 	... 10 more
,W/KeepSync( 3379): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 37720, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  820): Killing 2724:com.google.android.gm/u0a78 (adj 15): empty #17
,I/art     ( 1494): Explicit concurrent mark sweep GC freed 21005(1192KB) AllocSpace objects, 5(362KB) LOS objects, 37% free, 26MB/42MB, paused 865us total 23.638ms
,W/GAV2    ( 3421): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3421): Created application version: 3.6.8 (30608)
,I/ActivityManager(  820): Start proc 3494:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
I/ActivityManager(  820): Killing 2348:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/BooksSync( 3421): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3421): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 30736(1405KB) AllocSpace objects, 5(119KB) LOS objects, 32% free, 33MB/49MB, paused 1.393ms total 52.213ms
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3421): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3421): Soft error,
E/BooksSync( 3421): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3421): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3421): Sync error
E/BooksSync( 3421): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3421): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3421): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 37720, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager(  820): Killing 3060:com.android.musicfx/u0a18 (adj 15): empty #17
,I/ActivityManager(  820): Killing 3039:com.google.android.partnersetup/u0a16 (adj 15): empty #18
,I/ActivityManager(  820): Killing 1843:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,I/ActivityManager(  820): Start proc 3518:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,E/SQLiteLog( 3518): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  820): Start proc 3542:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/AnalyticsLogBase( 3518): PlayLogger.onLoggerConnected
,I/ActivityManager(  820): Killing 3088:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,D/TimeService( 3542): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1457077293324
,D/        ( 3542): TimeServiceNative: User Time to be set is 1457077293324
D/QC-time-services( 3542): Lib:time_genoff_operation: pargs->base = 2
,D/QC-time-services( 3542): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3542): Lib:time_genoff_operation: pargs->ts_val = 1457077293324
,D/QC-time-services(  374): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3542): Lib:time_genoff_operation: Send to server  passed!!,
D/QC-time-services(  374): Daemon:Received base = 2, unit = 1, operation = 0,value = 1457077293324
,D/QC-time-services(  374): Daemon:genoff_opr: Base = 2, val = 1457077293324, operation = 0
D/QC-time-services(  374): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS6/21/70 3:53:32
D/QC-time-services(  374): Daemon:Value read from RTC seconds = 17380412000,
D/QC-time-services(  374): Daemon:new time 1457077293324 
,D/QC-time-services(  374): Daemon: delta 1439696881324 genoff 1439696881324 
D/QC-time-services(  374): Daemon:genoff_persistent_update: Writing genoff = 1439696881324 to memory
,D/QC-time-services(  374): Daemon:Opening File: /data/time/ats_2,
,D/QC-time-services(  374): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  374): Updating the TOD offset
,D/QC-time-services(  374): Daemon:genoff_persistent_update: Writing genoff = 1439696881324 to memory
,D/QC-time-services(  374): Daemon:Opening File: /data/time/ats_1,
D/QC-time-services(  374): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  374): Daemon:Update to modem bit set
D/QC-time-services(  374): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  374): Daemon: Base = 2, Value being sent to MODEM = 1141112493324
,E/QC-time-services( 3542): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  374): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  374): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40,
,I/ActivityManager(  820): Start proc 3561:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/ActivityManager(  820): Killing 2996:com.android.defcontainer/u0a7 (adj 15): empty #17
,I/GAv4    ( 3561): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3561):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3561):   adb logcat -s GAv4
,W/GAv4    ( 3561): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3561): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 3561): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  820): Killing 1471:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,D/WifiService(  820): Client connection lost with reason: 4
,V/Herrevad( 1769): NQAS connected
,D/WifiService(  820): New client listening to asynchronous messages
,I/art     ( 1769): Explicit concurrent mark sweep GC freed 14346(1126KB) AllocSpace objects, 17(272KB) LOS objects, 35% free, 28MB/44MB, paused 1.225ms total 45.898ms
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1494): Vacuum at: now=1457077294321 tag=VacuumService
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel   ( 2088): UserRecoverableAuthException.
,E/Babel   ( 2088): eei: BadAuthentication
E/Babel   ( 2088): 	at eeg.a(Unknown Source)
E/Babel   ( 2088): 	at eeg.a(Unknown Source)
E/Babel   ( 2088): 	at eeg.a(Unknown Source)
E/Babel   ( 2088): 	at g.a(Unknown Source)
E/Babel   ( 2088): 	at cae.a(SourceFile:3089)
E/Babel   ( 2088): 	at cae.a(SourceFile:1131)
E/Babel   ( 2088): 	at cws.a(SourceFile:4333)
E/Babel   ( 2088): 	at cws.a(SourceFile:1419)
E/Babel   ( 2088): 	at crl.a(SourceFile:492)
E/Babel   ( 2088): 	at crl.a(SourceFile:1468)
E/Babel   ( 2088): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2088): 	at cas.b(SourceFile:106)
E/Babel   ( 2088): 	at cap.d(SourceFile:335)
E/Babel   ( 2088): 	at caq.run(SourceFile:81)
E/Babel   ( 2088): Error getting auth token
E/Babel   ( 2088): dvm
E/Babel   ( 2088): 	at g.a(Unknown Source)
E/Babel   ( 2088): 	at cae.a(SourceFile:3089)
E/Babel   ( 2088): 	at cae.a(SourceFile:1131)
E/Babel   ( 2088): 	at cws.a(SourceFile:4333)
E/Babel   ( 2088): 	at cws.a(SourceFile:1419)
E/Babel   ( 2088): 	at crl.a(SourceFile:492)
E/Babel   ( 2088): 	at crl.a(SourceFile:1468)
E/Babel   ( 2088): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2088): 	at cas.b(SourceFile:106)
E/Babel   ( 2088): 	at cap.d(SourceFile:335)
E/Babel   ( 2088): 	at caq.run(SourceFile:81)
,E/Babel   ( 2088): Account registration failed 1-Redacted-21
,E/Babel   ( 2088): cyp: null -- null
E/Babel   ( 2088): 	at cae.a(SourceFile:3121)
E/Babel   ( 2088): 	at cae.a(SourceFile:1131)
E/Babel   ( 2088): 	,at cws.a(SourceFile:4333)
E/Babel   ( 2088): 	at cws.a(SourceFile:1419)
E/Babel   ( 2088): 	at crl.a(SourceFile:492)
E/Babel   ( 2088): 	at crl.a(SourceFile:1468)
E/Babel   ( 2088): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2088): 	at cas.b(SourceFile:106),
E/Babel   ( 2088): 	at cap.d(SourceFile:335)
E/Babel   ( 2088): 	at caq.run(SourceFile:81)
,I/art     ( 2088): Note: end time exceeds epoch: 
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1494): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Babel   ( 2088): Unexpected exception while authenticating.
E/Babel   ( 2088): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2088): 	at eeg.b(Unknown Source)
E/Babel   ( 2088): 	at eeg.b(Unknown Source)
E/Babel   ( 2088): 	at g.a(Unknown Source)
E/Babel   ( 2088): 	at cae.b(SourceFile:1146)
E/Babel   ( 2088): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2088): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2088): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2088): 	at java.lang.Thread.run(Thread.java:818)
,V/GoogleAuthProtoRequest( 3282): [320] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3282): [320] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3282): [320] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3282): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
,W/ExperimentUpdateService( 3282): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3282): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3282): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3282): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3282): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3282): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3282): ,	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3282): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3282): ,	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1494): Using platform SSLCertificateSocketFactory
,W/Uploader( 1494): No account for auth token provided
,I/art     (  820): Explicit concurrent mark sweep GC freed 17860(815KB) AllocSpace objects, 2(126KB) LOS objects, 32% free, 33MB/49MB, paused 3.031ms total 84.995ms
,W/Uploader( 1494): No account for auth token provided
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1494): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1494): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1494): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1494): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1494): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1494): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1494): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1494): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1494): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1494): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1494): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1494): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1494): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1494): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1494): No account for auth token provided
,W/Uploader( 1494): No account for auth token provided
,W/Uploader( 1494): No account for auth token provided
,I/GAV2    ( 3421): Thread[GAThread,5,main]: No campaign data found.
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1494): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1494): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1494): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1494): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1494): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1494): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1494): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/art     ( 1494): Explicit concurrent mark sweep GC freed 46360(2MB) AllocSpace objects, 6(419KB) LOS objects, 36% free, 27MB/43MB, paused 1.642ms total 62.923ms
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1494): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1494): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1494): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1494): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1494): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1494): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1494): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1494): No account for auth token provided
,W/Uploader( 1494): No account for auth token provided
,W/Uploader( 1494): No account for auth token provided
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAV2    ( 3518): Thread[GAThread,5,main]: No campaign data found.
,D/Finsky  ( 2668): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2668): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2668): [1] 5.onFinished: Scheduling replication attempt 5.
,W/Uploader( 1494):  no longer exists, so no auth token.
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1494): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1494): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1494): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1494): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1494): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1494): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1494): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1494): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1494): No account for auth token provided
,W/Uploader( 1494): No account for auth token provided
,D/Finsky  ( 2668): [239] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2668): [239] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,V/GoogleAuthProtoRequest( 3282): [321] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3282): [321] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3282): [321] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3282): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3282): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3282): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3282): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3282): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3282): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3282): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3282): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3282): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3282): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2668): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2668): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2668): [1] 5.onFinished: Giving up after 6 failures.
,I/Keyboard.Facilitator.LanguageModelFlusher( 1213): run()
I/Keyboard.Facilitator( 1213): flushDynamicLanguageModels()
,I/ConfigService( 1494): onCreate
,I/BooksSync( 3421): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3421): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2941): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2941): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2941): 	at jdm.a(PG:82)
E/HttpOperation( 2941): 	at jcs.o(PG:406)
E/HttpOperation( 2941): 	at jcn.a(PG:1379)
E/HttpOperation( 2941): 	at jcs.i(PG:143)
E/HttpOperation( 2941): 	at blb.a(PG:3937)
E/HttpOperation( 2941): 	at czp.a(PG:18188)
E/HttpOperation( 2941): 	at czp.a(PG:9081)
E/HttpOperation( 2941): 	at czq.run(PG:1686)
E/HttpOperation( 2941): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2941): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2941): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2941): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2941): 	at jdj.a(PG:4091)
E/HttpOperation( 2941): 	at jdj.a(PG:1125)
E/HttpOperation( 2941): 	at jdm.a(PG:77)
E/HttpOperation( 2941): 	... 12 more
E/HttpOperation( 2941): Caused by: faj: BadAuthentication
E/HttpOperation( 2941): 	at fal.a(PG:38)
E/HttpOperation( 2941): 	at jdj.a(PG:4089)
E/HttpOperation( 2941): 	... 14 more
,E/BooksAccountManager( 3421): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3421): Soft error
E/BooksSync( 3421): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3421): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3421): Sync error
E/BooksSync( 3421): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3421): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3421): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 201342, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2941): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2941): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2941): 	at jdm.a(PG:82)
E/HttpOperation( 2941): 	at jcs.o(PG:406)
E/HttpOperation( 2941): 	at jcn.a(PG:1379)
E/HttpOperation( 2941): 	at jcs.i(PG:143)
E/HttpOperation( 2941): 	at hec.a(PG:42)
E/HttpOperation( 2941): 	at hee.a(PG:102)
E/HttpOperation( 2941): 	at czr.a(PG:65)
E/HttpOperation( 2941): 	at kka.a(PG:108)
E/HttpOperation( 2941): 	at czp.a(PG:19176)
E/HttpOperation( 2941): 	at czp.a(PG:9081)
E/HttpOperation( 2941): 	at czq.run(PG:1686)
E/HttpOperation( 2941): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2941): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2941): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2941): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2941): 	at jdj.a(PG:4091)
E/HttpOperation( 2941): 	at jdj.a(PG:1125)
E/HttpOperation( 2941): 	at jdm.a(PG:77)
E/HttpOperation( 2941): 	... 15 more
E/HttpOperation( 2941): Caused by: faj: BadAuthentication
E/HttpOperation( 2941): 	at fal.a(PG:38)
E/HttpOperation( 2941): 	at jdj.a(PG:4089)
E/HttpOperation( 2941): 	... 17 more
,E/ExperimentLoader( 2941): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2941): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2941): 	at jdm.a(PG:82)
E/ExperimentLoader( 2941): 	at jcs.o(PG:406)
E/ExperimentLoader( 2941): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2941): 	at jcs.i(PG:143)
E/ExperimentLoader( 2941): 	at hec.a(PG:42)
E/ExperimentLoader( 2941): 	at hee.a(PG:102)
E/ExperimentLoader( 2941): 	at czr.a(PG:65)
,E/ExperimentLoader( 2941): 	at kka.a(PG:108)
E/ExperimentLoader( 2941): 	at czp.a(PG:19176)
E/ExperimentLoader( 2941): 	at czp.a(PG:9081)
E/ExperimentLoader( 2941): 	at czq.run(PG:1686)
E/ExperimentLoader( 2941): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2941): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2941): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2941): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2941): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2941): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2941): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2941): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2941): 	at jdm.a(PG:77)
E/ExperimentLoader( 2941): 	... 15 more
E/ExperimentLoader( 2941): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2941): 	at fal.a(PG:38)
E/ExperimentLoader( 2941): 	,at jdj.a(PG:4089)
E/ExperimentLoader( 2941): 	... 17 more
,I/art     (  820): Explicit concurrent mark sweep GC freed 27374(1206KB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 1.440ms total 67.108ms
,V/KeepSync( 3379): Connecting to GoogleApiClient
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 199753, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1769): Handling authorization failure
E/ClientConnectionOperation( 1769): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1769): ,	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1769): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1769): ,	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1769): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1769): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1769): 	,at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689),
E/ClientConnectionOperation( 1769): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1769): 	... 7 more
V/KeepSync( 3379): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3379): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3379): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3379): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3379): IOException
E/KeepSync( 3379): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3379): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3379): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3379): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3379): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3379): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3379): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3379): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3379): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3379): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3379): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3379): ,	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3379): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3379): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3379): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3379): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3379): 	... 10 more
,W/KeepSync( 3379): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 202083, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/ConfigService( 1494): onDestroy
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3282): [322] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3282): [322] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3282): [322] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3282): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3282): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3282): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3282): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3282): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3282): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3282): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3282): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3282): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3282): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,I/jxcore-log( 3159): Reconnected to the test server
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): TAP version 13
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # setup,
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # 1. multiplex can send data
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # teardown
,I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 1 String should be length:200
,I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # setup
,I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # 2. enqueue and run in order
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # teardown
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 2 firstPromise setTimeout
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 3 firstPromise result
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 4 firstPromise testValue
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 5 secondPromise setTimeout
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 6 secondPromise result
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 7 secondPromise testValue
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 8 thirdPromise in promise
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 9 thirdPromise result
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 10 thirdPromise testValue
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # setup
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # 3. enqueueAtTop and run backwards
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # teardown
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 11 thirdPromise - first to run
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 12 thirdPromise - in resolve
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 13 secondPromise - second to run
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 14 secondPromise - in catch
I/jxcore-log( 3159): ,
I/jxcore-log( 3159): ok 15 firstPromise - third to run
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 16 firstPromise - in then
I/jxcore-log( 3159): 
I/jxcore-log( 3159): ok 17 testing promises
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # setup
,I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # 4. mix enqueue and enqueueAtTop
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # teardown
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 18 fourth
I/jxcore-log( 3159): ,
,I/jxcore-log( 3159): ok 19 fourth
I/jxcore-log( 3159): 
I/jxcore-log( 3159): ok 20 second
I/jxcore-log( 3159): 
I/jxcore-log( 3159): ok 21 secondPromise - in then
,I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 22 first
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 23 firstPromise - in catch,
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 24 third
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 25 thirdPromise - in then
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 26 testingPromises
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # setup
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # 5. queues handled independently
I/jxcore-log( 3159): 
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2941): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2941): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2941): 	at jdm.a(PG:82)
E/HttpOperation( 2941): 	at jcs.o(PG:406)
E/HttpOperation( 2941): 	at jcn.a(PG:1379)
E/HttpOperation( 2941): 	at jcs.i(PG:143)
E/HttpOperation( 2941): 	at blb.a(PG:3937)
E/HttpOperation( 2941): 	at czp.a(PG:18188)
E/HttpOperation( 2941): 	at czp.a(PG:9081)
E/HttpOperation( 2941): 	at czq.run(PG:1686)
E/HttpOperation( 2941): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2941): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2941): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2941): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2941): 	at jdj.a(PG:4091)
E/HttpOperation( 2941): 	at jdj.a(PG:1125)
E/HttpOperation( 2941): 	at jdm.a(PG:77)
E/HttpOperation( 2941): 	... 12 more
E/HttpOperation( 2941): Caused by: faj: BadAuthentication
E/HttpOperation( 2941): 	at fal.a(PG:38)
E/HttpOperation( 2941): 	at jdj.a(PG:4089)
E/HttpOperation( 2941): 	... 14 more
,I/jxcore-log( 3159): # teardown
I/jxcore-log( 3159): 
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2941): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2941): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2941): 	at jdm.a(PG:82)
E/HttpOperation( 2941): 	at jcs.o(PG:406)
E/HttpOperation( 2941): 	at jcn.a(PG:1379)
E/HttpOperation( 2941): 	at jcs.i(PG:143)
E/HttpOperation( 2941): 	at hec.a(PG:42)
E/HttpOperation( 2941): 	at hee.a(PG:102)
E/HttpOperation( 2941): 	at czr.a(PG:65)
E/HttpOperation( 2941): 	at kka.a(PG:108)
E/HttpOperation( 2941): 	at czp.a(PG:19176)
E/HttpOperation( 2941): 	at czp.a(PG:9081)
E/HttpOperation( 2941): 	at czq.run(PG:1686)
E/HttpOperation( 2941): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2941): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2941): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2941): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2941): 	at jdj.a(PG:4091)
E/HttpOperation( 2941): 	at jdj.a(PG:1125)
E/HttpOperation( 2941): 	at jdm.a(PG:77)
E/HttpOperation( 2941): 	... 15 more
E/HttpOperation( 2941): Caused by: faj: BadAuthentication
E/HttpOperation( 2941): 	at fal.a(PG:38)
E/HttpOperation( 2941): 	at jdj.a(PG:4089)
E/HttpOperation( 2941): 	... 17 more
,E/ExperimentLoader( 2941): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2941): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2941): 	at jdm.a(PG:82)
E/ExperimentLoader( 2941): 	at jcs.o(PG:406)
E/ExperimentLoader( 2941): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2941): 	at jcs.i(PG:143)
E/ExperimentLoader( 2941): 	at hec.a(PG:42)
E/ExperimentLoader( 2941): 	at hee.a(PG:102)
,E/ExperimentLoader( 2941): 	at czr.a(PG:65)
E/ExperimentLoader( 2941): 	at kka.a(PG:108)
E/ExperimentLoader( 2941): 	at czp.a(PG:19176)
E/ExperimentLoader( 2941): 	at czp.a(PG:9081)
E/ExperimentLoader( 2941): 	at czq.run(PG:1686)
E/ExperimentLoader( 2941): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2941): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2941): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2941): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2941): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2941): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2941): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2941): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2941): 	at jdm.a(PG:77)
E/ExperimentLoader( 2941): 	... 15 more
E/ExperimentLoader( 2941): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2941): 	at fal.a(PG:38)
E/ExperimentLoader( 2941): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2941): 	... 17 more
,I/jxcore-log( 3159): ok 27 all short operations completed before the long resolves
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # setup,
I/jxcore-log( 3159): 
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 290508, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3421): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3421): GmsCore Version = 7.8.99 (2134222-430)
,I/jxcore-log( 3159): # 6. basic,
I/jxcore-log( 3159): 
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1494): Explicit concurrent mark sweep GC freed 53498(3MB) AllocSpace objects, 13(1433KB) LOS objects, 36% free, 27MB/43MB, paused 1.244ms total 38.557ms
,I/jxcore-log( 3159): # teardown
I/jxcore-log( 3159): 
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3421): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3421): Soft error
E/BooksSync( 3421): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3421): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3421): Sync error
E/BooksSync( 3421): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3421): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3421): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 290860, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3159): ok 28 sane
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # setup
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # 7. another
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # teardown
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 29 sane
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # setup
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # 8. #startListeningForAdvertisements should fail if start not called
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # teardown
,I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 30 specific error should be returned
,I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # setup
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 31 error should be null
I/jxcore-log( 3159): ,
I/jxcore-log( 3159): ok 32 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # 9. #startUpdateAdvertisingAndListening should fail if start not called
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # teardown
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 33 specific error should be returned
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # setup
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 34 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 35 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # 10. should be able to call #stopListeningForAdvertisements many times
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # teardown
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 36 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 37 error should be null
I/jxcore-log( 3159): 
I/jxcore-log( 3159): ok 38 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 39 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # setup
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 40 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 41 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # 11. should be able to call #startListeningForAdvertisements many times
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # teardown
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 42 error should be null
I/jxcore-log( 3159): ,
I/jxcore-log( 3159): ok 43 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 44 error should be null,
I/jxcore-log( 3159): 
I/jxcore-log( 3159): ok 45 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # setup,
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).,
I/jxcore-log( 3159): 
I/jxcore-log( 3159): ok 46 error should be null
I/jxcore-log( 3159): 
I/jxcore-log( 3159): ok 47 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # 12. should be able to call #startUpdateAdvertisingAndListening many times
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # teardown,
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 48 error should be null,
I/jxcore-log( 3159): 
I/jxcore-log( 3159): ok 49 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 50 error should be null,
I/jxcore-log( 3159): 
I/jxcore-log( 3159): ok 51 error should be null
I/jxcore-log( 3159): 
I/jxcore-log( 3159): # setup
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
,I/jxcore-log( 3159): 
I/jxcore-log( 3159): ok 52 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 53 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # 13. should be able to call #stopAdvertisingAndListening many times
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # teardown
I/jxcore-log( 3159): ,
,I/jxcore-log( 3159): ok 54 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 55 error should be null
I/jxcore-log( 3159): 
I/jxcore-log( 3159): ok 56 error should be null
I/jxcore-log( 3159): 
I/jxcore-log( 3159): ok 57 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # setup
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 58 error should be null
,I/jxcore-log( 3159): 
I/jxcore-log( 3159): ok 59 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # 14. #start should fail if called twice in a row
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # teardown
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 60 first call should succeed
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 61 first call should succeed
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 62 specific error should be returned
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # setup
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 63 error should be null
,I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 64 error should be null
,I/jxcore-log( 3159): 
I/jxcore-log( 3159): # 15. does not emit duplicate discoveryAdvertisingStateUpdate
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # teardown
,I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 65 called only once
,I/jxcore-log( 3159): 
I/jxcore-log( 3159): ok 66 discovery state matches
I/jxcore-log( 3159): 
I/jxcore-log( 3159): ok 67 advertising state matches
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # setup,
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): INFO thaliMobile Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 68 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 69 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # 16. does not send duplicate availability changes
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # teardown
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 70 should be called once
I/jxcore-log( 3159): 
I/jxcore-log( 3159): ok 71 should not have been called more than once
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # setup
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 72 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 73 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # 17. can get the network status
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # teardown
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): not ok 74 network status should have certain non-empty properties
I/jxcore-log( 3159): 
I/jxcore-log( 3159):   ---
I/jxcore-log( 3159): 
,I/jxcore-log( 3159):     operator: throws
I/jxcore-log( 3159): 
I/jxcore-log( 3159):     expected: |-
I/jxcore-log( 3159): 
,I/jxcore-log( 3159):       undefined
I/jxcore-log( 3159): 
I/jxcore-log( 3159):     actual: |-
I/jxcore-log( 3159): 
,I/jxcore-log( 3159):       [TypeError: undefined must be a string]
I/jxcore-log( 3159): 
I/jxcore-log( 3159):   ...
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # setup
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 75 error should be null
I/jxcore-log( 3159): 
I/jxcore-log( 3159): ok 76 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # 18. wifi peer is marked unavailable if announcements stop
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # teardown
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 77 host address should match
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 78 port should match
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 79 host address should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 80 port should should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # setup
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).,
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 81 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): ok 82 error should be null
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # 19. Can call start/stopListeningForAdvertisements
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # teardown
I/jxcore-log( 3159): 
,I/io.jxcore.node.ConnectionHelper( 3159): start: Port number: -1, start advertisements: false,
,I/io.jxcore.node.ConnectivityInfo( 3159): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 3159):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - force notify: true
,D/io.jxcore.node.JXcoreExtension( 3159): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
D/io.jxcore.node.ConnectivityInfo( 3159): startMonitoring: OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3159): bind: Binding a new listener
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3159): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3159): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:CF:C5:D9:E5:61"},
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3159): setConnectionTimeout: 15000 -> 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): startListeningForIncomingConnections,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3159): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): start: OK
I/io.jxcore.node.ConnectionHelper( 3159): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): start: Discovery mode: BLE, start discovery: true, start advertiser: false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3159): bind: Binding a new listener
,V/io.jxcore.node.ConnectivityInfo( 3159): setIsWifiEnabled: true
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3159): getBluetoothService() called with no BluetoothManagerCallback
,I/io.jxcore.node.ConnectivityInfo( 3159): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 3159):     - is connected/connecting to active network: true
,I/io.jxcore.node.ConnectivityInfo( 3159):     - active network type is Wi-Fi: true,
I/io.jxcore.node.ConnectivityInfo( 3159):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 3159): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3159): Waiting for incoming connections...
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3159): setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3159): setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils( 3159): createScanFilter: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", use manufacturer ID: false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils( 3159): createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=b6a44ad1-d319-4b3a-815d-8b805a47fb51, mUuidMask=11111111-1111-1111-1110-000000000000, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3159): startScanner: Starting...
,D/BtGatt.GattService( 2122): registerClient() - UUID=24788e84-a108-4cf1-ad47-3c8e1cb8ed9d
,D/BtGatt.GattService( 2122): onClientRegistered() - UUID=24788e84-a108-4cf1-ad47-3c8e1cb8ed9d, clientIf=5
D/BluetoothLeScanner( 3159): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.GattService( 2122): start scan with filters,
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3159): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): startBlePeerDiscoverer: OK
,D/BtGatt.ScanManager( 2122): handling starting scan
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothAdapterService( 2122): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@273d634f
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
,I/io.jxcore.node.ConnectionHelper( 3159): onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): start: OK
,I/io.jxcore.node.ConnectionHelper( 3159): start: OK
I/jxcore-log( 3159): ok 83 Can call startListeningForAdvertisements without error
I/jxcore-log( 3159): 
I/io.jxcore.node.ConnectionHelper( 3159): stopListeningForAdvertisements
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): stopDiscovery
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3159): stopScanner: Stopping...
D/BtGatt.GattService( 2122): stopScan() - queue size =1,
D/BtGatt.GattService( 2122): unregisterClient() - clientIf=5
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3159): stop: Stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3159): setState: State changed from STARTING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3159): onIsScannerStartedChanged: false
D/BtGatt.GattService( 2122): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
I/jxcore-log( 3159): ok 84 Can call stopListeningForAdvertisements without error
I/jxcore-log( 3159): 
D/BtGatt.ScanManager( 2122): addFilterToController: 2
,D/BtGatt.GattService( 2122): onScanFilterConfig() - clientIf=5, action = 0 status = 0, filterType=2, availableSpace=47
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
I/jxcore-log( 3159): # setup
I/jxcore-log( 3159): 
,D/BtGatt.GattService( 2122): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
I/jxcore-log( 3159): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"on","blueTooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 3159): 
D/BtGatt.ScanManager( 2122): Starting BLE batch scan,
D/BtGatt.ScanManager( 2122): configuring batch scan storage, appIf 5
I/jxcore-log( 3159): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"on","blueTooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
I/jxcore-log( 3159): 
D/BtGatt.GattService( 2122): onBatchScanStorageConfigured() - clientIf=5, status=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2122): stopping BLe Batch
,D/BtGatt.GattService( 2122): onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,I/io.jxcore.node.ConnectionHelper( 3159): stopListeningForAdvertisements
,D/BluetoothLeScanner( 3159): could not find callback wrapper
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3159): stop: Stopped
,I/jxcore-log( 3159): ok 85 Should be able to call stopListeningForAdvertisments in teardown
I/jxcore-log( 3159): 
I/io.jxcore.node.ConnectionHelper( 3159): stop: Stopping all activities and killing all connections...
D/io.jxcore.node.HandshakeHelper( 3159): shutdown
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3159): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3159): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3159): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3159): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3159): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3159): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper( 3159): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3159): stopScannerAndAdvertiser
,I/io.jxcore.node.ConnectionHelper( 3159): onConnectionManagerStateChanged: NOT_STARTED
D/BluetoothLeScanner( 3159): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3159): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3159): stop: Stopped
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): stopBlePeerDiscoverer: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3159): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3159): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): updateState: State: NOT_STARTED, is discovering: false, is advertising: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): start: Discovery mode: BLE, start discovery: false, start advertiser: false
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3159): bind: Binding a new listener
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/io.jxcore.node.ConnectivityInfo( 3159): stopMonitoring: Stopped
,I/jxcore-log( 3159): ok 86 Should be able to call stopAdvertisingAndListening in teardown
I/jxcore-log( 3159): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3159): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3159): bind: Binding a new listener
,I/jxcore-log( 3159): # 20. Calling startListeningForAdvertisements twice is NOT an error
I/jxcore-log( 3159): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3159): setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3159): setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils( 3159): createScanFilter: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", use manufacturer ID: false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils( 3159): createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=b6a44ad1-d319-4b3a-815d-8b805a47fb51, mUuidMask=11111111-1111-1111-1110-000000000000, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): start: Discovery mode: BLE, start discovery: false, start advertiser: false
,I/io.jxcore.node.ConnectionHelper( 3159): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
V/io.jxcore.node.ConnectivityInfo( 3159): setIsWifiEnabled: true
,I/jxcore-log( 3159): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
I/jxcore-log( 3159): 
I/io.jxcore.node.ConnectivityInfo( 3159): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 3159):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 3159): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
I/jxcore-log( 3159): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"on","blueTooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # teardown
,I/jxcore-log( 3159): 
,I/io.jxcore.node.ConnectionHelper( 3159): start: Port number: -1, start advertisements: false
,D/io.jxcore.node.HandshakeHelper( 3159): reinitiate
,I/io.jxcore.node.ConnectivityInfo( 3159): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 3159):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - force notify: true
,D/io.jxcore.node.JXcoreExtension( 3159): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
D/io.jxcore.node.ConnectivityInfo( 3159): startMonitoring: OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): start
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3159): bind: Binding a new listener
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3159): setConnectionTimeout: 15000 -> 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3159): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3159): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): start: Discovery mode: BLE, start discovery: true, start advertiser: false
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3159): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3159): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3159): startScanner: Starting...
,D/BtGatt.GattService( 2122): registerClient() - UUID=2aa29a49-f38a-4dad-819b-18bb3e1f5c6f
D/BtGatt.GattService( 2122): onClientRegistered() - UUID=2aa29a49-f38a-4dad-819b-18bb3e1f5c6f, clientIf=5
,D/BluetoothLeScanner( 3159): onClientRegistered() - status=0 clientIf=5
D/BtGatt.GattService( 2122): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3159): setState: State changed from NOT_STARTED to STARTING
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): startBlePeerDiscoverer: OK
D/BtGatt.ScanManager( 2122): handling starting scan
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BtGatt.GattService( 2122): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): addFilterToController: 2
,D/BtGatt.GattService( 2122): onScanFilterConfig() - clientIf=5, action = 0 status = 0, filterType=2, availableSpace=47
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): updateState: State: RUNNING_BLE, is discovering: false, is advertising: false
I/io.jxcore.node.ConnectionHelper( 3159): onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): start: OK
D/BtGatt.GattService( 2122): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
I/io.jxcore.node.ConnectionHelper( 3159): start: OK
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2122): Starting BLE batch scan
D/BtGatt.ScanManager( 2122): configuring batch scan storage, appIf 5
I/jxcore-log( 3159): ok 87 Can call startListeningForAdvertisements without error
I/jxcore-log( 3159): 
,I/io.jxcore.node.ConnectionHelper( 3159): start: Port number: -1, start advertisements: false
V/io.jxcore.node.ConnectivityInfo( 3159): startMonitoring: Already started
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): start
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): start: Already running, call stop() first in order to restart
,V/io.jxcore.node.ConnectionHelper( 3159): start: Discovery manager already running
I/io.jxcore.node.ConnectionHelper( 3159): start: OK
D/BtGatt.GattService( 2122): onBatchScanStorageConfigured() - clientIf=5, status=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
I/jxcore-log( 3159): ok 88 Can call startListeningForAdvertisements twice without error
I/jxcore-log( 3159): 
D/BtGatt.GattService( 2122): onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
I/jxcore-log( 3159): # setup
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"on","blueTooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 3159): 
I/jxcore-log( 3159): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
I/jxcore-log( 3159): 
,I/io.jxcore.node.ConnectionHelper( 3159): stopListeningForAdvertisements
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): stopDiscovery
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3159): stopScanner: Stopping...
,D/BtGatt.GattService( 2122): stopScan() - queue size =1
D/BtGatt.GattService( 2122): unregisterClient() - clientIf=5
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3159): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3159): setState: State changed from STARTING to NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3159): onIsScannerStartedChanged: false
D/BtGatt.GattService( 2122): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): stopping BLe Batch
,D/BtGatt.GattService( 2122): onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,I/jxcore-log( 3159): ok 89 Should be able to call stopListeningForAdvertisments in teardown
I/jxcore-log( 3159): 
,I/io.jxcore.node.ConnectionHelper( 3159): stop: Stopping all activities and killing all connections...
,D/io.jxcore.node.HandshakeHelper( 3159): shutdown
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3159): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3159): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3159): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3159): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): setState: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3159): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3159): onServerStopped
I/io.jxcore.node.ConnectionHelper( 3159): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper( 3159): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3159): stopScannerAndAdvertiser
D/BluetoothLeScanner( 3159): could not find callback wrapper
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3159): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3159): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): stopBlePeerDiscoverer: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3159): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3159): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): updateState: State: NOT_STARTED, is discovering: false, is advertising: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): start: Discovery mode: BLE, start discovery: false, start advertiser: false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3159): bind: Binding a new listener
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/io.jxcore.node.ConnectivityInfo( 3159): stopMonitoring: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3159): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
I/jxcore-log( 3159): ok 90 Should be able to call stopAdvertisingAndListening in teardown
I/jxcore-log( 3159): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3159): bind: Binding a new listener
,I/jxcore-log( 3159): # 21. Can call start/stopUpdateAdvertisingAndListening,
I/jxcore-log( 3159): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3159): setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3159): setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils( 3159): createScanFilter: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", use manufacturer ID: false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils( 3159): createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=b6a44ad1-d319-4b3a-815d-8b805a47fb51, mUuidMask=11111111-1111-1111-1110-000000000000, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=-1, mManufacturerData=null, mManufacturerDataMask=null]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): start: Discovery mode: BLE, start discovery: false, start advertiser: false
,I/io.jxcore.node.ConnectionHelper( 3159): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,V/io.jxcore.node.ConnectivityInfo( 3159): setIsWifiEnabled: true
,I/io.jxcore.node.ConnectivityInfo( 3159): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Wi-Fi Direct supported: true
,I/io.jxcore.node.ConnectivityInfo( 3159):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 3159):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 3159): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,I/jxcore-log( 3159): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
I/jxcore-log( 3159): 
I/jxcore-log( 3159): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"on","blueTooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # teardown
I/jxcore-log( 3159): 
,I/io.jxcore.node.ConnectionHelper( 3159): start: Port number: 4242, start advertisements: true
,D/io.jxcore.node.HandshakeHelper( 3159): reinitiate
,I/io.jxcore.node.ConnectivityInfo( 3159): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 3159):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - force notify: true
,D/io.jxcore.node.JXcoreExtension( 3159): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
D/io.jxcore.node.ConnectivityInfo( 3159): startMonitoring: OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3159): bind: Binding a new listener
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3159): setConnectionTimeout: 15000 -> 15000,
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): startListeningForIncomingConnections,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3159): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): start: Discovery mode: BLE, start discovery: true, start advertiser: true
,I/io.jxcore.node.ConnectionHelper( 3159): onConnectionManagerStateChanged: RUNNING
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3159): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3159): startScannerAndAdvertiser
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3159): startScanner: Starting...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3159): Waiting for incoming connections...
,D/BtGatt.GattService( 2122): registerClient() - UUID=bdc77d4d-7c2b-4729-8e4d-f74535b79625,
D/BtGatt.GattService( 2122): onClientRegistered() - UUID=bdc77d4d-7c2b-4729-8e4d-f74535b79625, clientIf=5
,D/BluetoothLeScanner( 3159): onClientRegistered() - status=0 clientIf=5
D/BtGatt.GattService( 2122): start scan with filters
,D/BtGatt.ScanManager( 2122): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3159): setState: State changed from NOT_STARTED to STARTING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3159): startAdvertiser: Starting...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3159): createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3159): createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3159): setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BtGatt.GattService( 2122): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): addFilterToController: 2
D/BtGatt.GattService( 2122): onScanFilterConfig() - clientIf=5, action = 0 status = 0, filterType=2, availableSpace=47
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2122): Starting BLE batch scan
D/BtGatt.ScanManager( 2122): configuring batch scan storage, appIf 5
,D/BtGatt.GattService( 2122): onBatchScanStorageConfigured() - clientIf=5, status=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): registerClient() - UUID=dbb0841e-adb7-42db-9cb6-99b49afbd98c
,D/BtGatt.GattService( 2122): onClientRegistered() - UUID=dbb0841e-adb7-42db-9cb6-99b49afbd98c, clientIf=6
D/BluetoothLeAdvertiser( 3159): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2122): message : 0
,D/BtGatt.AdvertiseManager( 2122): starting multi advertising
,D/BtGatt.GattService( 2122): onAdvertiseInstanceEnabled() - clientIf=6, status=0
,D/BtGatt.GattService( 2122): onAdvertiseDataSet() - clientIf=6, status=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3159): onStartSuccess
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3159): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3159): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3159): onIsAdvertiserStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): startBlePeerDiscoverer: OK
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3159): updateState: State changed from [NOT_STARTED] to [SCANNING, ADVERTISING]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING, ADVERTISING]
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): start: OK
I/io.jxcore.node.ConnectionHelper( 3159): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): updateState: State: NOT_STARTED, is discovering: true, is advertising: true
D/io.jxcore.node.JXcoreExtension( 3159): METHOD_NAME_START_UPDATE_ADVERTISING_AND_LISTENING: errorString == null
,I/io.jxcore.node.ConnectionHelper( 3159): onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
I/io.jxcore.node.ConnectionHelper( 3159): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,I/jxcore-log( 3159): ok 91 Can call startUpdateAdvertisingAndListening without error
I/jxcore-log( 3159): 
,I/io.jxcore.node.ConnectionHelper( 3159): stop: Stopping all activities and killing all connections...
,D/io.jxcore.node.HandshakeHelper( 3159): shutdown
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3159): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3159): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3159): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3159): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3159): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3159): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3159): release: No more listeners, de-initializing...
I/io.jxcore.node.ConnectionHelper( 3159): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3159): release: No more listeners, de-initializing...
,D/io.jxcore.node.ConnectivityInfo( 3159): stopMonitoring: Stopped
,I/jxcore-log( 3159): ok 92 Can call stopAdvertisingAndListening without error
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # setup,
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"on","blueTooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
I/jxcore-log( 3159): 
,I/io.jxcore.node.ConnectionHelper( 3159): stopListeningForAdvertisements
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3159): stopScanner: Stopping...
,D/BtGatt.GattService( 2122): stopScan() - queue size =1
,D/BtGatt.GattService( 2122): unregisterClient() - clientIf=5,
D/BtGatt.GattService( 2122): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3159): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3159): setState: State changed from STARTING to NOT_STARTED
D/BtGatt.ScanManager( 2122): stopping BLe Batch
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3159): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3159): updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): updateState: State: NOT_STARTED, is discovering: false, is advertising: true
,I/io.jxcore.node.ConnectionHelper( 3159): onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: true
D/BtGatt.GattService( 2122): onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,I/jxcore-log( 3159): ok 93 Should be able to call stopListeningForAdvertisments in teardown
I/jxcore-log( 3159): 
,I/io.jxcore.node.ConnectionHelper( 3159): stop: Stopping all activities and killing all connections...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3159): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3159): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3159): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3159): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3159): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3159): release: No more listeners, de-initializing...
D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 301656143842
I/jxcore-log( 3159): ok 94 Should be able to call stopAdvertisingAndListening in teardown
I/jxcore-log( 3159): 
,D/BtGatt.GattService( 2122): Batch record : [81, 101, 46, -30, 12, 69, 1, -128, -49, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
I/jxcore-log( 3159): # 22. Calling startUpdateAdvertisingAndListening twice is NOT an error
I/jxcore-log( 3159): 
I/jxcore-log( 3159): INFO thaliMobileNativeWrapper discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
I/jxcore-log( 3159): 
,I/jxcore-log( 3159): # teardown
I/jxcore-log( 3159): 
,I/io.jxcore.node.ConnectionHelper( 3159): start: Port number: 4242, start advertisements: true
,D/io.jxcore.node.HandshakeHelper( 3159): reinitiate
,I/io.jxcore.node.ConnectivityInfo( 3159): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 3159):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - force notify: true
,D/io.jxcore.node.JXcoreExtension( 3159): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
D/io.jxcore.node.ConnectivityInfo( 3159): startMonitoring: OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3159): bind: Binding a new listener
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3159): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3159): setConnectionTimeout: 15000 -> 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3159): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3159): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3159): start: Discovery mode: BLE, start discovery: true, start advertiser: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3159): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3159): bind: Binding a new listener
I/io.jxcore.node.ConnectionHelper( 3159): onConnectionManagerStateChanged: RUNNING,
V/io.jxcore.node.ConnectivityInfo( 3159): setIsWifiEnabled: true
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
I/io.jxcore.node.ConnectivityInfo( 3159): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - is Wi-Fi enabled: true
,I/io.jxcore.node.ConnectivityInfo( 3159):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 3159):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 3159):     - force notify: true
,D/io.jxcore.node.JXcoreExtension( 3159): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
W/BluetoothAdapter( 3159): getBluetoothService() called with no BluetoothManagerCallback,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3159): startScannerAndAdvertiser
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3159): startScanner: Starting...
,D/BtGatt.GattService( 2122): registerClient() - UUID=e59cd163-2838-486e-b6f5-6cdad2c9ab26
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3159): Waiting for incoming connections...
,D/BtGatt.GattService( 2122): onClientRegistered() - UUID=e59cd163-2838-486e-b6f5-6cdad2c9ab26, clientIf=5
,D/BluetoothLeScanner( 3159): onClientRegistered() - status=0 clientIf=5
D/BtGatt.GattService( 2122): start scan with filters
D/BtGatt.ScanManager( 2122): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3159): setState: State changed from NOT_STARTED to STARTING,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3159): createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3159): createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3159): setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[0, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/BtGatt.AdvertiseManager( 2122): message : 1,
D/BtGatt.GattService( 2122): onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.AdvertiseManager( 2122): stop advertise for client 6
D/BtGatt.ScanManager( 2122): addFilterToController: 2,
D/BtGatt.GattService( 2122): onScanFilterConfig() - clientIf=5, action = 0 status = 0, filterType=2, availableSpace=47
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): onAdvertiseInstanceDisabled() - clientIf=6, status=0
D/BtGatt.GattService( 2122): Client app is not null!,
D/BtGatt.GattService( 2122): unregisterClient() - clientIf=6
,D/BtGatt.GattService( 2122): onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3159): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3159): setState: State changed from RUNNING to NOT_STARTED
,D/BtGatt.ScanManager( 2122): Starting BLE batch scan
D/BtGatt.ScanManager( 2122): configuring batch scan storage, appIf 5
D/BtGatt.GattService( 2122): onBatchScanStorageConfigured() - clientIf=5, status=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): registerClient() - UUID=3238c7fe-249e-4f41-8a94-ec1060e58c4a
,D/BtGatt.GattService( 2122): onClientRegistered() - UUID=3238c7fe-249e-4f41-8a94-ec1060e58c4a, clientIf=6
D/BluetoothLeAdvertiser( 3159): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.AdvertiseManager( 2122): message : 0,
,D/BtGatt.AdvertiseManager( 2122): starting multi advertising,
,D/BtGatt.GattService( 2122): onAdvertiseInstanceEnabled() - clientIf=6, status=0,
,D/BtGatt.GattService( 2122): onAdvertiseDataSet() - clientIf=6, status=0,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3159): onStartSuccess
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3159): setState: State changed from NOT_STARTED to STARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3159): setState: State changed from STARTING to RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3159): onIsAdvertiserStartedChanged: true
,D/BtGatt.ScanManager( 2122): awakened up at time 302655,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 302669015248
D/BtGatt.GattService( 2122): Batch record : [-82, -42, 84, 0, -38, 107, 1, -128, -65, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 303686,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 303696599102
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 304712
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 304727091185
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 305741,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 306765
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 307791
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 307804143944
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 308818
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 308829991235
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -75, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 309846
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 309858848266
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 310872
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 311896,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 312923,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 312933535505
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 313948
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 313962182223
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 314977
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 314992088837
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 316006
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 317031,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 318058
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 318071066076
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 319084
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 319094555242
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 320108
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,V/KeepSync( 3379): Connecting to GoogleApiClient
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 31385(1424KB) AllocSpace objects, 10(725KB) LOS objects, 32% free, 33MB/49MB, paused 1.512ms total 81.810ms
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
,V/KeepSync( 3379): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3379): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3379): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3379): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3379): IOException
E/KeepSync( 3379): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3379): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3379): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3379): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3379): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3379): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3379): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3379): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3379): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3379): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3379): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3379): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3379): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3379): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3379): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3379): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3379): 	... 10 more
W/KeepSync( 3379): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 294327, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/BtGatt.ScanManager( 2122): awakened up at time 321131
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0,
,D/BtGatt.ScanManager( 2122): awakened up at time 322153
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 323180
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 323192500136
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 324207
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 324218565136
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2f5d4aa6}
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.25 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
,D/BtGatt.ScanManager( 2122): awakened up at time 325232
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0,
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2f5d4aa6}
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@39db8ce7}
,D/BtGatt.ScanManager( 2122): awakened up at time 326123
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/kickstart(  876): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  876): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  876): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  876): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,D/BtGatt.ScanManager( 2122): awakened up at time 326630
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,I/kickstart(  876): STATUS: Received file 'm9kefs2'
I/kickstart(  876): STATUS: 950272 bytes transferred in 0.982463 seconds
,I/kickstart(  876): STATUS: Successfully downloaded files from target 
I/kickstart(  876): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  876): STATUS: Sahara protocol completed
,D/BtGatt.ScanManager( 2122): awakened up at time 327659
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 328684
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 328698958051
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 329713
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 329725771748
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 330739
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 331765
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 332792
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 332804839247
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 333821
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 333833634663
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 334846
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 334859061173
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 335872
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 336896
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 337923
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 337937718360,
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 338950,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 338963165547
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 339977
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 339989724401,
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 341002,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 342024
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 343047
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0,
D/BtGatt.GattService( 2122): current time is 343058750076
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 344072
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 344079725284
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 345096
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 345103115857
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 346118
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@39db8ce7}
,D/BtGatt.ScanManager( 2122): awakened up at time 347145
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BtGatt.ScanManager( 2122): awakened up at time 348162
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 348169126168
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,W/GLSActivity( 1494): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1494): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1494): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1494): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1494): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1494): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1494): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2668): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2668): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2668): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2668): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2668): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2668): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2668): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2668): Ignoring header User-Agent because its value was null.
,D/BtGatt.ScanManager( 2122): awakened up at time 349183
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 349196657522
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -62, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 350209,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 351232
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 352256
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 353283
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 353295860177
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 354310,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 354325805541
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 355341,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 356365,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 357392,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 358414
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 358427073352
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 359442
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 359451168612
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -66, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 360466
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 361493
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 362517
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 363542
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 363552608298
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 364566
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 364579235381
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 365592,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 366617
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 367642
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 367657268609
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 368671
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 368682043921
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 369696,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 369710431577
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 370723
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 371749
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 372776
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 372788853034
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 373801
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 373811559231
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -66, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 374826,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 374833223814
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 375848,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 376875,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 377901,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0,
D/BtGatt.GattService( 2122): current time is 377914222511
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 378933
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 378941623865
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 379958
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 379973456885
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 16, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 380987
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 382021
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 383050
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 383064605374
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 384078
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 384091882300
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -76, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 385105
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 386131
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,I/art     (  820): Explicit concurrent mark sweep GC freed 27036(1411KB) AllocSpace objects, 3(236KB) LOS objects, 32% free, 33MB/49MB, paused 1.863ms total 78.645ms,
,V/GoogleAuthProtoRequest( 3282): [323] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/BtGatt.ScanManager( 2122): awakened up at time 387151
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,W/ExperimentUpdateService( 3282): [323] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3282): [323] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3282): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3282): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3282): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3282): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3282): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3282): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3282): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3282): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3282): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3282): 	at com.a.a.k.run(SourceFile:110)
,D/BtGatt.ScanManager( 2122): awakened up at time 387660,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 387668044539
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 388175
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 388186096518
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,D/BtGatt.ScanManager( 2122): awakened up at time 389199
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 389209275788
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -66, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 390223
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 391249
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 392271
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 393294
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 393305592505
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 394319
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 394327910630
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 395344
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 396366
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 397391
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 398413
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 398428450680
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 399441
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 399450463961
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 400463
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 401486
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 402514,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 403542
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 403557352345
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 404573
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 404586628855
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -66, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 405602
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 406625
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 407651
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 407666636614
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 408680
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 408693308072
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -62, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 409707
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 409719953020
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 410734
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 411764
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 412789
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 412799387810
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 413814
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 413826380466
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 414840,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 414850206612
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 2941): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception,
E/HttpOperation( 2941): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2941): 	at jdm.a(PG:82)
E/HttpOperation( 2941): 	,at jcs.o(PG:406)
E/HttpOperation( 2941): 	at jcn.a(PG:1379)
E/HttpOperation( 2941): 	,at jcs.i(PG:143)
E/HttpOperation( 2941): 	at blb.a(PG:3937)
E/HttpOperation( 2941): 	,at czp.a(PG:18188)
E/HttpOperation( 2941): 	at czp.a(PG:9081)
E/HttpOperation( 2941): 	,at czq.run(PG:1686)
E/HttpOperation( 2941): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2941): ,	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2941): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2941): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2941): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2941): ,	at jdj.a(PG:4091)
E/HttpOperation( 2941): 	at jdj.a(PG:1125)
E/HttpOperation( 2941): 	at jdm.a(PG:77)
E/HttpOperation( 2941): 	... 12 more
E/HttpOperation( 2941): Caused by: faj: BadAuthentication
E/HttpOperation( 2941): 	at fal.a(PG:38)
E/HttpOperation( 2941): 	at jdj.a(PG:4089)
E/HttpOperation( 2941): 	... 14 more
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2941): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2941): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2941): 	at jdm.a(PG:82)
E/HttpOperation( 2941): 	at jcs.o(PG:406)
E/HttpOperation( 2941): 	at jcn.a(PG:1379)
E/HttpOperation( 2941): 	at jcs.i(PG:143)
E/HttpOperation( 2941): 	at hec.a(PG:42)
E/HttpOperation( 2941): 	at hee.a(PG:102)
E/HttpOperation( 2941): 	at czr.a(PG:65)
E/HttpOperation( 2941): 	at kka.a(PG:108)
E/HttpOperation( 2941): 	at czp.a(PG:19176)
E/HttpOperation( 2941): 	at czp.a(PG:9081)
E/HttpOperation( 2941): 	at czq.run(PG:1686)
E/HttpOperation( 2941): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2941): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2941): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2941): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2941): 	at jdj.a(PG:4091)
E/HttpOperation( 2941): 	at jdj.a(PG:1125)
E/HttpOperation( 2941): 	at jdm.a(PG:77)
E/HttpOperation( 2941): 	... 15 more
E/HttpOperation( 2941): Caused by: faj: BadAuthentication
E/HttpOperation( 2941): 	at fal.a(PG:38)
E/HttpOperation( 2941): 	at jdj.a(PG:4089)
E/HttpOperation( 2941): 	... 17 more
,E/ExperimentLoader( 2941): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2941): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2941): 	at jdm.a(PG:82)
E/ExperimentLoader( 2941): ,	at jcs.o(PG:406)
E/ExperimentLoader( 2941): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2941): 	at jcs.i(PG:143)
E/ExperimentLoader( 2941): 	,at hec.a(PG:42)
E/ExperimentLoader( 2941): 	at hee.a(PG:102)
E/ExperimentLoader( 2941): 	at czr.a(PG:65)
E/ExperimentLoader( 2941): 	at kka.a(PG:108)
E/ExperimentLoader( 2941): 	at czp.a(PG:19176)
E/ExperimentLoader( 2941): 	at czp.a(PG:9081),
E/ExperimentLoader( 2941): 	at czq.run(PG:1686)
E/ExperimentLoader( 2941): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2941): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2941): ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2941): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2941): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2941): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2941): 	at jdj.a(PG:4091)
,E/ExperimentLoader( 2941): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2941): 	at jdm.a(PG:77)
E/ExperimentLoader( 2941): 	... 15 more
E/ExperimentLoader( 2941): Caused by: faj: BadAuthentication
,E/ExperimentLoader( 2941): 	at fal.a(PG:38)
E/ExperimentLoader( 2941): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2941): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 414966, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/BtGatt.ScanManager( 2122): awakened up at time 415864
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 416892
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 417919
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 417930886558
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -49, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 418946
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 418959112183
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 419972
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 419983587443
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 20, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 420997
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 422024
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 423051
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,I/art     ( 2122): Explicit concurrent mark sweep GC freed 26022(1388KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 22MB/37MB, paused 1.310ms total 74.724ms
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 423136948692
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 424152
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 424167587962
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 425181
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 426211
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 427242
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 428266
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 428279161763
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 429291
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 429309485825
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 430323
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 431351
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 432373
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 433401
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 433412284730
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 434427
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 434439973948
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 435454
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 436482
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 437505
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 438532
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 438541187019
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 439556
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 439567684258
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 440585
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 441609
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 442635
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 442645695924
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 443663
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 443676734882
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 444682
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 444692246184
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,I/BooksSync( 3421): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3421): GmsCore Version = 7.8.99 (2134222-430),
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3421): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3421): Soft error
E/BooksSync( 3421): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3421): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3421): Sync error
E/BooksSync( 3421): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3421): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3421): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 416158, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/BtGatt.ScanManager( 2122): awakened up at time 445706
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 446733
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 447758
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,I/art     (  820): Explicit concurrent mark sweep GC freed 28337(1421KB) AllocSpace objects, 5(268KB) LOS objects, 32% free, 33MB/49MB, paused 1.382ms total 92.936ms
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 447863084151
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 448879
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 448893594463
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 449906
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 449919186754
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 450932,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 451961
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 452984
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 452998596076
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 454015
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 454027225867
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 455042
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 455054622325
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 456069,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 457099
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 458131,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 458143857324
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,D/BtGatt.ScanManager( 2122): awakened up at time 459160,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 459173227063
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 460186
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 461209
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 462238
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 463265
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 463279910812
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 464293
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 464302330082
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -66, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 465316
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 466342
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 467371
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 468396
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 468411947060
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 469432
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 469446006643
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 470458
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 471482
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 472506
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 473531
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 473540389766
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 474555
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 474568873568
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,V/KeepSync( 3379): Connecting to GoogleApiClient
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3379): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3379): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 3379): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3379): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3379): IOException
E/KeepSync( 3379): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3379): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3379): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3379): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3379): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3379): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3379): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3379): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3379): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3379): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3379): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3379): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3379): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3379): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3379): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3379): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3379): 	... 10 more
W/KeepSync( 3379): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 452184, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/BtGatt.ScanManager( 2122): awakened up at time 475572
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 476595
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 477620
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 477633890598
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -66, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 478649,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 478660904764
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -103, 46, -4, -74, 41, 109, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 479674
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 479689276431
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,D/BtGatt.ScanManager( 2122): awakened up at time 480701
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 481725
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 482753
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 482765760752
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 483779
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 483792860127
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 484806
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 484818396793
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 485831
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 486855
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 487881,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 487893153198
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 488906,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 488920480490,
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,D/BtGatt.ScanManager( 2122): awakened up at time 489932,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 489945779968
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 490958
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0,
,D/BtGatt.ScanManager( 2122): awakened up at time 491985,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 493013
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 493024284030
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 494036
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 494048527831
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 495061
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 496086
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 497111
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 498136
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 498149494809
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 499162
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 499172641267
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 500187
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 501218
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 502242
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 503268
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 503283998817
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -103, 46, -4, -74, 41, 109, 1, -128, -74, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 504296
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 504312733140
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 505327
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 506352
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 507378
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 508402,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 508412892201
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 509426
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 509439992513
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 510442
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 511466
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 512491
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 513514
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 513526640741
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 514540
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 514553991001
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 515565
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 516586
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 517612
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 517624638552
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 518641
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 518649733499
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 519662
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 519672704280
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 520685
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 521711
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 522733
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 522745671987
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 523758
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 523770126935
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 524783
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,I/art     (  820): Explicit concurrent mark sweep GC freed 25906(1317KB) AllocSpace objects, 2(126KB) LOS objects, 32% free, 33MB/49MB, paused 2.180ms total 86.308ms
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 524880278601
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 525894
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 526920,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 527941,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 527952849954
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 528964
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 528971518235
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 529984,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0,
D/BtGatt.GattService( 2122): current time is 529991355526
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 531004
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 532029,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 533055
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 533069014066
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 534082
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 534092159431
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 535107
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 536134
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 537165
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 538189
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 538199550627
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 539212
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 539223234689
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 540238
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 541263
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 542290
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 543324
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 543336239844
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 544351
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 544368129427
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 545381,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 546406
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 547434,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0,
,D/BtGatt.ScanManager( 2122): awakened up at time 548461
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 548470617863
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 549484
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 549497561039
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 550511
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 551534
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 552560
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 553586
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 553599762809
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -66, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 554613
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 554622706819
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 555637
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 556665
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 557691
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 558718
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 558733452963
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 559745
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 559758921192
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 13, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 560771
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 561796
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 562821,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 562834024211
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 563853
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 563867823586
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 564881
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 564894690409
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 565912
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 566939
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 567972
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 567983338168
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 568997
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 569010133011
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 570024,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0,
D/BtGatt.GattService( 2122): current time is 570039425198
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 571048
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 572074,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 573102
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 573115438010
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 574128,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 574141955197
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 575154
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 576183,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 577208
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 578235
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 578249122383
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 579263
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 579279776341
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 580291
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 581315
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 582341
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 583366
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 583376668474
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 584391
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 584401545557
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 585413
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 586440
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 587469
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 588496
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 588511119514
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 589523
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 589536661076
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 590551
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 591578
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 592604
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 592613676544
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 593628
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 593641437845
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 594655
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 594664231855
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 595679
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 596706
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 597732
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 597742794042
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 598759
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 598773097948
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 599787
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 599801920551
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 600815
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 601841
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 602867
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 602879257946
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 603892
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 603903292373
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 604917
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 604931009299
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 605944
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 606970
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 607996
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 608010436590
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 609022
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 609033283152
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 610046
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 610061784870
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 20, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 611074
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 612102
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 613129
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 613143196692
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 614157
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 614172548567
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 615186
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 616214
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 617242
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 618269
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 618283157576
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 619296
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 619308889034
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 620322,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 621349
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 622377
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 623402
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,I/art     (  820): Explicit concurrent mark sweep GC freed 24680(1375KB) AllocSpace objects, 1(110KB) LOS objects, 32% free, 33MB/49MB, paused 2.505ms total 87.890ms
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 623499049709
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 624520
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 624531979292
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 625545
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 626575
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,V/GoogleAuthProtoRequest( 3282): [324] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1494): Explicit concurrent mark sweep GC freed 56489(2MB) AllocSpace objects, 10(1102KB) LOS objects, 36% free, 27MB/43MB, paused 2.292ms total 65.455ms
,W/ExperimentUpdateService( 3282): [324] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3282): [324] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3282): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3282): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3282): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3282): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3282): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3282): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3282): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3282): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3282): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3282): 	at com.a.a.k.run(SourceFile:110)
,D/BtGatt.ScanManager( 2122): awakened up at time 627486
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 627994
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 628007743353
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 629020
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 629033002103
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 630047
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,I/art     ( 2122): Explicit concurrent mark sweep GC freed 30891(1494KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 22MB/37MB, paused 1.231ms total 46.680ms
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 630105597779
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 21, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 631120
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 632148
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0,
,D/BtGatt.ScanManager( 2122): awakened up at time 633175
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 633187355226
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 634202
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 634216148663
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 635228
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 636253
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 637278
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 638304,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 638317462724
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 639330,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 639342434495
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 640355
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 641375,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 642402
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 643428
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 643440400431
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 644454,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 644469452722
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 645483,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 646510
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 647535
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 647552284908
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 648565
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 648580506314
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 649595
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 649607438189
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 650622
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/Finsky  ( 2668): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/Finsky  ( 2668): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BtGatt.ScanManager( 2122): awakened up at time 651637
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2668): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 2668): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 2668): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features,
,D/Finsky  ( 2668): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2668): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/DeviceConnectionService( 1805): client connected with version: 7571000
,D/BtGatt.ScanManager( 2122): awakened up at time 652662
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 652677200896
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 653691
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 653698329020
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0, -103, 46, -4, -74, 41, 109, 1, -128, -73, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 654712
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 654722330426
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 655735
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 656762
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 657786
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 657797762144
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 658811
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 658818655529
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 659832
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 659843687039
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 16, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 660857
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0,
,D/BtGatt.ScanManager( 2122): awakened up at time 661883,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 662906,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 662921462975
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2941): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2941): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2941): 	at jdm.a(PG:82)
E/HttpOperation( 2941): 	at jcs.o(PG:406)
E/HttpOperation( 2941): 	at jcn.a(PG:1379)
E/HttpOperation( 2941): 	at jcs.i(PG:143)
E/HttpOperation( 2941): 	at blb.a(PG:3937)
E/HttpOperation( 2941): 	at czp.a(PG:18188)
E/HttpOperation( 2941): 	at czp.a(PG:9081)
E/HttpOperation( 2941): 	at czq.run(PG:1686)
E/HttpOperation( 2941): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2941): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2941): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2941): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2941): 	at jdj.a(PG:4091)
E/HttpOperation( 2941): 	at jdj.a(PG:1125)
E/HttpOperation( 2941): 	at jdm.a(PG:77)
E/HttpOperation( 2941): 	... 12 more
E/HttpOperation( 2941): Caused by: faj: BadAuthentication
E/HttpOperation( 2941): 	at fal.a(PG:38)
E/HttpOperation( 2941): 	at jdj.a(PG:4089)
E/HttpOperation( 2941): 	... 14 more
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2941): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2941): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2941): 	at jdm.a(PG:82)
E/HttpOperation( 2941): 	at jcs.o(PG:406)
E/HttpOperation( 2941): 	at jcn.a(PG:1379)
E/HttpOperation( 2941): 	at jcs.i(PG:143)
E/HttpOperation( 2941): 	at hec.a(PG:42)
E/HttpOperation( 2941): 	at hee.a(PG:102)
E/HttpOperation( 2941): 	at czr.a(PG:65)
E/HttpOperation( 2941): 	at kka.a(PG:108)
E/HttpOperation( 2941): 	at czp.a(PG:19176)
,E/HttpOperation( 2941): 	at czp.a(PG:9081)
E/HttpOperation( 2941): 	at czq.run(PG:1686)
E/HttpOperation( 2941): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2941): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2941): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2941): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2941): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2941): 	at jdj.a(PG:4091)
E/HttpOperation( 2941): 	at jdj.a(PG:1125)
E/HttpOperation( 2941): 	at jdm.a(PG:77)
E/HttpOperation( 2941): 	... 15 more
,E/HttpOperation( 2941): Caused by: faj: BadAuthentication
E/HttpOperation( 2941): 	at fal.a(PG:38)
E/HttpOperation( 2941): 	at jdj.a(PG:4089)
E/HttpOperation( 2941): 	... 17 more
E/ExperimentLoader( 2941): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2941): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2941): 	at jdm.a(PG:82)
E/ExperimentLoader( 2941): 	,at jcs.o(PG:406)
E/ExperimentLoader( 2941): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2941): 	at jcs.i(PG:143)
E/ExperimentLoader( 2941): 	at hec.a(PG:42)
E/ExperimentLoader( 2941): 	at hee.a(PG:102),
E/ExperimentLoader( 2941): 	at czr.a(PG:65)
E/ExperimentLoader( 2941): 	at kka.a(PG:108)
E/ExperimentLoader( 2941): 	at czp.a(PG:19176)
E/ExperimentLoader( 2941): 	at czp.a(PG:9081)
E/ExperimentLoader( 2941): 	,at czq.run(PG:1686)
E/ExperimentLoader( 2941): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2941): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2941): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2941): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
E/ExperimentLoader( 2941): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2941): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2941): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2941): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2941): 	at jdm.a(PG:77)
,E/ExperimentLoader( 2941): 	... 15 more
E/ExperimentLoader( 2941): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2941): 	at fal.a(PG:38)
E/ExperimentLoader( 2941): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2941): 	... 17 more,
,D/BtGatt.ScanManager( 2122): awakened up at time 663929
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 663935922454
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 663482, reason: 10074, SyncResult: stats [ numIoExceptions: 1],
,D/BtGatt.ScanManager( 2122): awakened up at time 664950
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 664963560110
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 665976
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 666995,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 21634(1037KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.424ms total 73.855ms
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2668): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2668): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2668): [1] 5.onFinished: Scheduling replication attempt 1.
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 668018,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 668027859692
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 669041
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 669049259171
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 670062
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 671086,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 672111
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 673138
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 673150939169
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 674165
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 674177469065
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 675191
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 676219,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 677245
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 678276
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 678286507709,
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 679301
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 679311308802
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 680326
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 681353
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 682379
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 683404
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 683416031770
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 684429,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 684441335311
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 685459
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 686483,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 687503
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 687510609476
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2668): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2668): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2668): [1] 5.onFinished: Scheduling replication attempt 2.
,D/BtGatt.ScanManager( 2122): awakened up at time 688524
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 688537345309
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 689551
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 689565185153
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 690581
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 691609
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 692631
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 692640902339
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 693655
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 693670408432
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 694689
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 694708795828
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 695721
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 696753
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 697775
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 697782519472
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -75, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 698800
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 698812431920
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 699827
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 699843051190
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 700856
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 701883
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 702914
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 702920243012
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 703935
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 703949738637
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 704963
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 704976245095
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 705991
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 707015
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 708042
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 708055930458
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2668): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2668): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 2668): [1] 5.onFinished: Scheduling replication attempt 3.
,D/BtGatt.ScanManager( 2122): awakened up at time 709073
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 709084849624
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 710099
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 711126
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 712154,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 713180
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 713195383685
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 714210
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 714224600039
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 715238,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 716267,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 717295
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 718322
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 718334651704
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 719348
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 719363169829
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 720375
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 721400
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 722424
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 723452
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 723461481442
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,I/BooksSync( 3421): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3421): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3421): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3421): Soft error
E/BooksSync( 3421): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3421): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3421): Sync error
E/BooksSync( 3421): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3421): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3421): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 695283, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/BtGatt.ScanManager( 2122): awakened up at time 724477
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 724490998160
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 725505
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,I/art     (  820): Explicit concurrent mark sweep GC freed 27428(1440KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.451ms total 77.472ms,
D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 726612
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 727635
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 727647032274
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/BtGatt.ScanManager( 2122): awakened up at time 728668
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 728677765294
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2668): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2668): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2668): [1] 5.onFinished: Scheduling replication attempt 4.
,D/BtGatt.ScanManager( 2122): awakened up at time 729692
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 729699162533
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 730714
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 731742
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 732766
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 732777997636
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 733792
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 733807199354
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 734822
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 734836042948
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 735849
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 736875
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 737904
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 737917156280
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 738934
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 738943255290
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 739958
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 739975043988
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 740988
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 742015
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 743043
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 743055563622
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 744070
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 744082315340
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 745096,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 746122
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 747148
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 748173
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 748185315495
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2668): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2668): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2668): [1] 5.onFinished: Scheduling replication attempt 5.
,D/BtGatt.ScanManager( 2122): awakened up at time 749199
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 749214190286
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 750227
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 751251
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 752275
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 753294
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 753301687368
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,V/KeepSync( 3379): Connecting to GoogleApiClient
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 3379): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3379): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3379): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3379): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1494): Explicit concurrent mark sweep GC freed 49609(2MB) AllocSpace objects, 14(1544KB) LOS objects, 37% free, 26MB/42MB, paused 2.123ms total 64.732ms
,E/KeepSync( 3379): IOException
E/KeepSync( 3379): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3379): ,	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3379): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3379): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3379): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3379): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410),
E/KeepSync( 3379): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3379): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3379): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3379): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305),
E/KeepSync( 3379): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3379): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3379): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3379): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3379): ,	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3379): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3379): 	... 10 more
W/KeepSync( 3379): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 737936, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/BtGatt.ScanManager( 2122): awakened up at time 754314
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 754325997159
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 755338
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0,
,D/BtGatt.ScanManager( 2122): awakened up at time 756364
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 757390
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 758417,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 758429390751
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 759442
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 759451324188
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 760465
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 761491,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 762515
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 762530543666
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 763545
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 763558124916
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 764571
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 764580239239
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 765593
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 766619,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 767647
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 767659307935
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 768673
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 768683803247
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2668): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 2668): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2668): [1] 5.onFinished: Giving up after 6 failures.
,D/BtGatt.ScanManager( 2122): awakened up at time 769696
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 769712650643
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 13, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 770724
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 771751
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 772774
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 772786402881
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 773801
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 773813989600
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 774827
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 774841739651
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 775855
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,I/art     (  820): Explicit concurrent mark sweep GC freed 24384(1176KB) AllocSpace objects, 2(126KB) LOS objects, 32% free, 33MB/49MB, paused 2.629ms total 93.798ms
D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 776976
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 778002
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 778010324338
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 779025
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 779037209702
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 780051
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 781078
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 782105
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 783131
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 783141941627
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 784158
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 784170517408
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 785182
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 786206
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 787231
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 788257
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 788269401469
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 789284
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 789298653396
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 790312
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 791337,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 792365
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 793392
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 793400690373
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 794415
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 794430341779
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 795451
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 796473
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 797501,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 797514478861
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 798529
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 798541179955
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 799555
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 799568496100
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 800581
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 801608
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 802633
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 802646678807
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 803663
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 803676611359
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,D/BtGatt.ScanManager( 2122): awakened up at time 804690
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 804702851775,
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -76, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 805718
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 806746
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 807771
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 807783965837
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 808798
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 808811197034
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 809825
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 809837768128
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 810853
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 811881
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 812911
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 812924491824
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 813935
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 813944505053
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 814959
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 815983
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 817008
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 818032
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 818041284427
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 819054
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 819064095259
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 820078
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 821106
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 822132,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 823158
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 823171615831
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 824184
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 824195239164
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 825212
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 826234
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 827254
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 828274
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 828282511402
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 829298
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 829312913693
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 830324
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 831345
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 832372
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 833397
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 833410359316
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 834424
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 834440576347
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 835453
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 836477,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,I/art     ( 2122): Explicit concurrent mark sweep GC freed 31139(1507KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 22MB/37MB, paused 1.427ms total 39.989ms
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 837542,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 837551110825
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 838564,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 838578291242
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 839592
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 839602503481
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 13, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 840616
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 841641
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 842667
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 843691
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 843701867125
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 844714
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 844726665302
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 845741
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 846764
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 847785
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 847794968113
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 848811
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 848819354363,
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,D/BtGatt.ScanManager( 2122): awakened up at time 849833
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 849847367435
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 850859
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 851883
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 852909
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 852918567903
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 853932
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 853946739673
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 854960
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 854971970090
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 20, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 855985
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 857011
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 858038
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 858053982015
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 859068
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 859082805244
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 860095
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 861124
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 862151
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 863176
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 863188534826
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 864204
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 864220545555
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 865233
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 866260
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 867288
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 868315
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 868326399512
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,D/BtGatt.ScanManager( 2122): awakened up at time 869343
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 869356528157
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 870373
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 871400,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 872426
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 873456
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,I/art     (  820): Explicit concurrent mark sweep GC freed 26236(1452KB) AllocSpace objects, 2(126KB) LOS objects, 32% free, 33MB/49MB, paused 2.953ms total 93.255ms
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 873564078468
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 874579
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 874591711020
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 875605
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 876636
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 877666
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 877680732477
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 878693
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 878707390393
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 879722
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 879737046018
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 16, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 880751,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 881772
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 882799
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 882811148412
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 883826
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 883839593464
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 884852
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 884864387474
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 885877
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 886904
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 887935
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 887946753723
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 888962
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 888977250962
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 889990
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 891016
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 892045
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 893072
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 893088138981
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 894100
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 894115191585
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 895126
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 896152
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 897175
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 898200
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 898214668094
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 899228
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 899239805437
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 900252
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 901277
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 902304
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 903331
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 903343647988
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 904358
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 904372886060
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 905386
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 906412
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 907442
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 908468
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 908479257934
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 909492
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 909502801631
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 910516
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 911541
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 912565
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 912581123870
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 913595
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 913607335900
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 914621
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 914633335275
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 915647
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0,
,D/BtGatt.ScanManager( 2122): awakened up at time 916674
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 917700
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 917715669649
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 918730
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 918744459128
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 919759
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 920790
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 921815
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 922841
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 922849118866
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 923864
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 923878189230
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 924892
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 924903374073
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 20, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 925917
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 926942,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 927966
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 927979133708
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 928993
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 929005414072
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 930020
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 931047
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 932071
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 933093
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 933105619903
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 934119
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 934128245424
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 935138
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 936161
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 937189
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 938214
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 938229446829
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 939241
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 939249634120
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -76, 6, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 940263
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 941286
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 942314
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 943341
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 943358333650
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 944371,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 944381956566
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 945396
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 946422,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 947446
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 947461281669
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 948475
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 948490465314
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 949503
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 949512186460
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 950527,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 951555,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 952581
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 952590747500
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 953605
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 953618490052
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 954633
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 954648198697
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 16, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 955661
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 956686
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 957711,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 957720737082
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 958735
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 958750001665
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 959762
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 959772504164
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 960787
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 961814
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 962846
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 962866000986
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 963878,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 963891408902
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 964905
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 964918465412
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 20, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 965932
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 966957
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0,
,D/BtGatt.ScanManager( 2122): awakened up at time 967982,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0,
D/BtGatt.GattService( 2122): current time is 967994804369
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 969009
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 969025631765
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 970039
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 971068
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 972095
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 973122
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 973131964367
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 974146
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,I/art     (  820): Explicit concurrent mark sweep GC freed 23507(1324KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.930ms total 85.124ms
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 974246598690
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 975261
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 976289,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 977315
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 978345
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 978357590459
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 979374
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 979383618115
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 980398
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 981426
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 982454
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 982471262958
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 983484
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 983500242176
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 984512,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 984522511759
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 985539
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 986570
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 987596
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 987610387956
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 988625
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 988634541028
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 989648
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 989664683371
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 990673
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 991699
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 992726
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 992736730454
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 993753
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 993762992380
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 994779
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 994793138370
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 995802
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 996822
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 997847
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 997861591181
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 998875
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 998888740087
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 999902
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 999916521701
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 20, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1000927
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1001952
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1002977
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1002989038054
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1004002
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1004016526699
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1005028
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1006050
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1007077
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1008101
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1008112287844
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1009126
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1009139697843
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1010152
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1011175
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1012201
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1013227
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1013240514560
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1014254,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1014265685081
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1015279
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1016307
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1017331
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1018355
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1018369657996
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1019382
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1019392489871
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1020406
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1021430
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1022459
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1022473276067
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1023486
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1023502410077
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1024515
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1024528191171
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1025540
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1026566
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1027594
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1027609231899
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1028622
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1028630518617
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -71, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1029645
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1029657291846
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1030672
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1031698
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1032721
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1032732457782
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1033745
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1033756835542
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -66, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1034771,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1034783750594
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1035796,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1036820,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1037848,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1037859641166
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1038875
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1038885837519
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1039902,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1039915927467
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 20, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1040928
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1041953,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1042978,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,I/art     ( 2122): Explicit concurrent mark sweep GC freed 30950(1502KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 22MB/37MB, paused 1.326ms total 39.485ms
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1043030226737
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1044044
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1044057539757
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -75, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1045071
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1046097
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1047122
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1048146
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1048157948401
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1049171
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1049181930328
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1050194
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1051216
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1052238
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1053264
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1053277466733
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1054289
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1054302832722
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1055315
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1056335
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1057357
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1058382
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1058392273554
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1059406
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1059421424959
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1060434
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1061460
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1062487
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1062501790010
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1063516
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1063529287093
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1064544
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1064557862666
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1065571
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1066600,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1067626,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1067637302873
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1068651
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1068662986206
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/GCM     ( 1494): Message class com.google.f.a.a.i
,D/BtGatt.ScanManager( 2122): awakened up at time 1069166,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1069173868185
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1069678,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1070708
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,I/art     (  820): Explicit concurrent mark sweep GC freed 24618(1367KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.470ms total 94.680ms
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1071832
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1072860,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1072872969954
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1073887
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1073902856204
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1074917
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1074930745735
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1075943
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1076972
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1077996
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1078008077661
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1079022
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1079036948389
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1080050
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1081073
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1082099
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1083125
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1083138360055
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1084152
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1084162061044
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1085176
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1086205
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1087228
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1088253
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1088265273594
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1089279
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1089293708490
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1090306
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1091331
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1092358
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1092370941822
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1093384
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1093397141769
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1094410
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1094422355102
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1095435
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1096459
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1097483
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1097506578851
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1098526
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1098545748799
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1099559
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1099574571455
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1100587
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1101612
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1102641
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1102653979370
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1103667
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1103679488068
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1104693
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1104702523015
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1105716,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1106742
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,V/GoogleAuthProtoRequest( 3282): [325] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3282): [325] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3282): [325] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3282): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3282): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3282): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3282): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3282): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3282): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3282): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3282): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3282): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3282): 	at com.a.a.k.run(SourceFile:110)
,D/BtGatt.ScanManager( 2122): awakened up at time 1107697
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1107701528535
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1108204
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1108216104993
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1109229
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1109242727336
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1110256
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1111284
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1112311
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1112318754939
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1113332
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1113342102647
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1114355
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1114368933480
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 8, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1115382
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1116406
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1117433
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1117443142229
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1118456
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1118470594312
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1119482
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1119491298270
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 13, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1120504,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1121531,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1122557
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1122571684102
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1123585
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1123599933633
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1124613
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1124626741132
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1125641
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1126665
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1127694
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1127703584100
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1128717
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1128728583162
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1129742
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1129752670714
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1130767
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1131795
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1132824
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1132839883681
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1133852
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1133867885191
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1134881
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1135907
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1136933
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1137960
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1137973059252
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1138986
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1138998365346
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1140012
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1141036
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1142066,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1143099
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1143114844928
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1144128
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1144141483990
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1145155
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1146182
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1147204
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1148233
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1148246278832
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1149260
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1149271067373
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 9, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1150284
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1151312
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1152338
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1152351362528
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1153365
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1153378072997
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1154393
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1154409767319
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1155423
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1156449
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1157475
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1157491199505
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1158507,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1158521941953
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1159534
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1159550363203
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 16, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,I/art     (  820): Explicit concurrent mark sweep GC freed 25715(1390KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 2.225ms total 53.303ms
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2941): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2941): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2941): 	at jdm.a(PG:82)
E/HttpOperation( 2941): 	at jcs.o(PG:406)
E/HttpOperation( 2941): 	at jcn.a(PG:1379)
E/HttpOperation( 2941): 	at jcs.i(PG:143)
E/HttpOperation( 2941): 	at blb.a(PG:3937)
E/HttpOperation( 2941): 	at czp.a(PG:18188)
E/HttpOperation( 2941): 	at czp.a(PG:9081)
E/HttpOperation( 2941): 	at czq.run(PG:1686)
E/HttpOperation( 2941): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2941): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2941): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2941): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2941): 	at jdj.a(PG:4091)
E/HttpOperation( 2941): 	at jdj.a(PG:1125)
E/HttpOperation( 2941): 	at jdm.a(PG:77)
E/HttpOperation( 2941): 	... 12 more
E/HttpOperation( 2941): Caused by: faj: BadAuthentication
E/HttpOperation( 2941): 	at fal.a(PG:38)
E/HttpOperation( 2941): 	at jdj.a(PG:4089)
E/HttpOperation( 2941): 	... 14 more
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2941): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2941): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2941): 	at jdm.a(PG:82)
E/HttpOperation( 2941): 	at jcs.o(PG:406)
E/HttpOperation( 2941): 	at jcn.a(PG:1379)
E/HttpOperation( 2941): 	at jcs.i(PG:143)
E/HttpOperation( 2941): 	at hec.a(PG:42)
E/HttpOperation( 2941): 	at hee.a(PG:102)
E/HttpOperation( 2941): 	at czr.a(PG:65)
E/HttpOperation( 2941): 	at kka.a(PG:108)
E/HttpOperation( 2941): 	at czp.a(PG:19176)
E/HttpOperation( 2941): 	at czp.a(PG:9081)
E/HttpOperation( 2941): 	at czq.run(PG:1686)
E/HttpOperation( 2941): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2941): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2941): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2941): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2941): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2941): 	at jdj.a(PG:4091)
E/HttpOperation( 2941): 	at jdj.a(PG:1125)
E/HttpOperation( 2941): 	at jdm.a(PG:77)
E/HttpOperation( 2941): 	... 15 more
E/HttpOperation( 2941): Caused by: faj: BadAuthentication
E/HttpOperation( 2941): 	at fal.a(PG:38)
E/HttpOperation( 2941): 	at jdj.a(PG:4089)
E/HttpOperation( 2941): 	... 17 more
,E/ExperimentLoader( 2941): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2941): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2941): 	at jdm.a(PG:82)
E/ExperimentLoader( 2941): 	at jcs.o(PG:406)
,E/ExperimentLoader( 2941): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2941): 	at jcs.i(PG:143)
E/ExperimentLoader( 2941): 	at hec.a(PG:42)
E/ExperimentLoader( 2941): 	at hee.a(PG:102)
E/ExperimentLoader( 2941): 	at czr.a(PG:65)
E/ExperimentLoader( 2941): 	at kka.a(PG:108)
E/ExperimentLoader( 2941): 	at czp.a(PG:19176)
E/ExperimentLoader( 2941): 	at czp.a(PG:9081)
E/ExperimentLoader( 2941): 	at czq.run(PG:1686)
E/ExperimentLoader( 2941): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2941): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2941): 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2941): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2941): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2941): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2941): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2941): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2941): 	at jdm.a(PG:77)
E/ExperimentLoader( 2941): 	... 15 more
E/ExperimentLoader( 2941): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2941): 	at fal.a(PG:38)
E/ExperimentLoader( 2941): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2941): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1159877, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/BtGatt.ScanManager( 2122): awakened up at time 1160563
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1161590
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1162617
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1162632127889
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1163645,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1163659146274
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1164672
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1164685456430
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1165698
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1166724
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1167749
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1167762525699
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1168774
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1168786685647
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1169800
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1169812705178
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 19, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1170826
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1171851
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1172877
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1172888774239
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,D/BtGatt.ScanManager( 2122): awakened up at time 1173904
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1173912699603
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1174927
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1175952
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1176975
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1178001
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1178009738508
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1179025
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1179038811841
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -71, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1180052
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1181079
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1182106
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1183131
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1183141905069
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1184155
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1184166352724
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 5, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1185180
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0,
,D/BtGatt.ScanManager( 2122): awakened up at time 1186206
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1187232
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1188258
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1188270816004
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81],
,D/BtGatt.ScanManager( 2122): awakened up at time 1189284,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1189298713764
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 10, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1190312,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1191337
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1192365
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1192377003919
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1193391
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1193401087773
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1194414
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1194426303502
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 11, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1195440
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1196464,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1197492
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1197506769542
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1198519
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1198530546781
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1199544
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1199557535843
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -66, 15, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1200571
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1201593
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1202622
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1202635252561
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -66, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1203650
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1203668413863
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1204683
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1204695267352
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 18, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0],
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1205709
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1206733
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1207760
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1207771421778
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1208785
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1208796363652
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -72, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1209811,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1210837
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1211862
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1212885
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1212897559380
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1213911
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1213924426671
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1214937,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1215965
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1216991
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1218017
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1218033721149
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1219049,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1219061485159
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1220074,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0,
,D/BtGatt.ScanManager( 2122): awakened up at time 1221100
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1222122
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1223145
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1223158078751
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,I/BooksSync( 3421): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3421): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3421): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3421): Soft error
E/BooksSync( 3421): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3421): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3421): Sync error
E/BooksSync( 3421): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3421): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3421): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1223671, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,W/bt-btm  ( 2122): Request to stop oneshot timer with non empty queue
,D/BtGatt.ScanManager( 2122): awakened up at time 1228171
,W/bt-btm  ( 2122): Stopping oneshot timer
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1228183669166
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1229189
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1229202494478
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -65, 7, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1230223
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,I/art     (  820): Explicit concurrent mark sweep GC freed 29058(1448KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.670ms total 98.676ms
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1231345
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,I/UsageStatsService(  820): User[0] Flushing usage stats to disk
,D/BtGatt.ScanManager( 2122): awakened up at time 1232371
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1232381774373
,D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1233396
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1233406219268
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1234419
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1234433180205
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -63, 12, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1235447
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1236475
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1237503
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1237515746975
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1238528,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1238540957599
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -74, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1239552
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1239562062495
D/BtGatt.GattService( 2122): Batch record : [-103, 46, -4, -74, 41, 109, 1, -128, -73, 14, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1240575
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0,
,D/BtGatt.ScanManager( 2122): awakened up at time 1241601
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1242622
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1242635613119
,D/BtGatt.GattService( 2122): Batch record : [-49, 2, 59, -101, -96, 93, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1243648
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.GattService( 2122): current time is 1243662516087,
,D/BtGatt.GattService( 2122): Batch record : [-49, 2, 59, -101, -96, 93, 1, -128, -64, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
,D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1244675
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.GattService( 2122): current time is 1244689409993
D/BtGatt.GattService( 2122): Batch record : [-49, 2, 59, -101, -96, 93, 1, -128, -65, 17, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81, 0]
D/BtGatt.GattService( 2122): ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 0, -8, -107, -57, -121, 60, 81]
,D/BtGatt.ScanManager( 2122): awakened up at time 1245702
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1246727
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1247754
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1248782
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1249811
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1250834
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1251858
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,I/art     ( 2122): Explicit concurrent mark sweep GC freed 31339(1528KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 22MB/37MB, paused 2.076ms total 40.308ms
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1252923
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1253943
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1254964
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1255987
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1257014
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1258036,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1259060,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1260087
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1261112
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1262140
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1263167
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1264193
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1265225
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1266250
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1267281
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/HeadsetStateMachine( 2122): Disconnected process message: 10, size: 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1268307
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1269331
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1270356
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1271381
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1272404
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1273432
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1274456
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1275483,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1276505
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1277531
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1278556
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5,
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1279589
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1280615,
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1281645
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1282674
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1283698
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,V/KeepSync( 3379): Connecting to GoogleApiClient
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,E/ClientConnectionOperation( 1769): 	at com.google.android.gms.auth.p.a(SourceFile:365)
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
,V/KeepSync( 3379): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3379): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3379): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3379): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3379): IOException
E/KeepSync( 3379): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3379): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3379): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3379): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3379): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3379): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3379): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3379): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3379): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3379): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3379): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3379): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3379): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3379): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3379): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3379): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3379): 	... 10 more
,W/KeepSync( 3379): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 1278832, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,D/BtGatt.ScanManager( 2122): awakened up at time 1284726
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1285752
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0,
,D/BtGatt.ScanManager( 2122): awakened up at time 1286782
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1287808
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1288840
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1289867
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1290893
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1291921
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1292946
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1293974
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1294999
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1296027
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1297053
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1298083
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1299104
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1300129
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1301156
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,V/GoogleAuthProtoRequest( 3282): [326] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1494): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1494): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1494): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1494): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1494): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 25680(1337KB) AllocSpace objects, 6(190KB) LOS objects, 32% free, 33MB/49MB, paused 1.891ms total 97.313ms
,W/ExperimentUpdateService( 3282): [326] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3282): [326] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3282): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3282): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3282): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3282): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3282): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3282): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3282): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3282): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3282): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3282): 	at com.a.a.k.run(SourceFile:110)
,D/BtGatt.ScanManager( 2122): awakened up at time 1301890,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1302419
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,I/EventLogService( 1769): Opted in for usage reporting,
I/EventLogService( 1769): Aggregate from 1457076623939 (log), 1457076623939 (data)
,W/EventLogAggregator( 1769): Unknown tag: snet_gcore
W/EventLogAggregator( 1769): Unknown tag: snet_launch_service
,I/art     ( 1494): Explicit concurrent mark sweep GC freed 60359(2MB) AllocSpace objects, 3(330KB) LOS objects, 36% free, 27MB/43MB, paused 1.903ms total 67.396ms
,I/ServiceDumpSys( 1769): dumping service [account]
,D/BtGatt.ScanManager( 2122): awakened up at time 1302936
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1303449
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1304476
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0,
,D/BtGatt.ScanManager( 2122): awakened up at time 1305502,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1306525,
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,D/BtGatt.ScanManager( 2122): awakened up at time 1307553
,D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
,D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
,TIME-OUT KILL (timeout was 1200000ms),D/BtGatt.ScanManager( 2122): awakened up at time 1308575
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2122): awakened up at time 1309600
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2122): awakened up at time 1310624
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/AndroidRuntime( 3895): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3895): CheckJNI is OFF
D/AndroidRuntime( 3895): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  820): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  820): Killing 3159:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  820): Skipping PackageSetting{286b48a com.example.hello/10273} due to missing metadata
D/BtGatt.GattService( 2122): Binder is dead - unregistering client (5)!
D/BtGatt.GattService( 2122): Binder is dead - unregistering client (6)!
I/WindowState(  820): WIN DEATH: Window{eb266ac u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  820): Client connection lost with reason: 4
D/BtGatt.GattService( 2122): stopScan() - queue size =1
D/BtGatt.AdvertiseManager( 2122): message : 1
D/BtGatt.AdvertiseManager( 2122): stop advertise for client 6
D/BtGatt.AdvertiseManager( 2122): app died - unregistering client : 6
D/BtGatt.GattService( 2122): onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2122): stopping BLe Batch
D/BtGatt.GattService( 2122): unregisterClient() - clientIf=6
D/BtGatt.GattService( 2122): onAdvertiseInstanceDisabled() - clientIf=255, status=0
E/BtGatt.ContextMap( 2122): Context not found for ID 255
D/BtGatt.GattService( 2122): onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2122): flushPendingBatchResults - clientIf = 5
D/BtGatt.GattService( 2122): onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
D/BtGatt.ScanManager( 2122): callback done for clientIf - 5 status - 0
D/BtGatt.ScanManager( 2122): app died, unregister client - 5
D/BtGatt.GattService( 2122): unregisterClient() - clientIf=5
W/ActivityManager(  820): Force removing ActivityRecord{3c634c08 u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
V/ActivityManager(  820): Display changed displayId=0
I/ActivityManager(  820): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
W/ActivityManager(  820): Spurious death for ProcessRecord{12cc1cb8 3159:com.test.thalitest/u0a265}, curProc for 3159: null
D/TaskPersister(  820): removeObsoleteFile: deleting file=2_task.xml
D/BuaReceiver( 3022): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/Keyboard.Facilitator( 1213): resetDictionaries() : en_US
I/InputReader(  820): Reconfiguring input devices.  changes=0x00000010
I/art     ( 1065): Explicit concurrent mark sweep GC freed 68590(2MB) AllocSpace objects, 1(30MB) LOS objects, 21% free, 58MB/74MB, paused 1.096ms total 55.249ms
I/Keyboard.Facilitator.DecoderInitializer( 1213): run()
I/Decoder ( 1213): createOrResetDecoder
I/ActivityManager(  820): Start proc 3912:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
D/VoicemailCleanupService( 1349): Cleaning up data for package: com.test.thalitest
I/art     (  820): Explicit concurrent mark sweep GC freed 9718(834KB) AllocSpace objects, 4(158KB) LOS objects, 32% free, 33MB/49MB, paused 1.907ms total 79.495ms
I/art     (  820): WaitForGcToComplete blocked for 48.818ms for cause Explicit
I/ActivityManager(  820): Start proc 3929:com.google.android.googlequicksearchbox:search/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService
I/ConfigService( 1494): onCreate
W/InputMethodManagerService(  820): Got RemoteException sending setActive(false) notification to pid 3159 uid 10265
I/Keyboard.Facilitator( 1213): onFinishInput()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1213): run()
D/JobSchedulerService(  820): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  820): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/Keyboard.Facilitator.MainLanguageModelLoader( 1213): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run()
I/art     ( 1279): Explicit concurrent mark sweep GC freed 4950(361KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 875us total 18.405ms
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loading LM = contacts
I/ActivityManager(  820): Start proc 3950:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1213): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1213): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1213): run()
I/ActivityManager(  820): Killing 2828:com.google.android.music:main/u0a66 (adj 15): empty #17
I/Keyboard.Facilitator.RecurringTaskScheduler( 1213): run()
I/StatsUtilsManager( 1213): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1213): shouldRecordStats() = Too Soon
I/art     (  820): Explicit concurrent mark sweep GC freed 6555(331KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.297ms total 126.759ms
D/Launcher.Workspace( 1279): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1279): 11683562 - stripEmptyScreens()
W/ContextImpl( 3950): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
E/NetworkScheduler.SchedulerReceiver( 1494): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1494): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  820): Killing 3316:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
I/art     ( 3895): System.exit called, status: 0
I/AndroidRuntime( 3895): VM exiting with result code 0.
D/ChimeraCfgMgr( 1769): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1769): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1769): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1769): Clearing selected account for com.test.thalitest
I/LocationSettingsChecker( 1769): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1769): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1769): Module APK com.google.android.play.games already loaded
E/SQLiteLog( 1769): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 1769): (3850) statement aborts at 167: [DELETE FROM FileContent112 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
E/DocListDatabase( 1769): Failed to delete from FileContent112
E/DocListDatabase( 1769): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1769): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1769): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1769): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1769): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1769): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1769): 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
E/DocListDatabase( 1769): 	at com.google.android.gms.drive.database.f.a(SourceFile:968)
E/DocListDatabase( 1769): 	at com.google.android.gms.drive.b.e.run(SourceFile:72)
E/DocListDatabase( 1769): 	at com.google.android.gms.drive.h.ar.run(SourceFile:51)
E/DocListDatabase( 1769): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DocListDatabase( 1769): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DocListDatabase( 1769): 	at java.lang.Thread.run(Thread.java:818)
I/Process ( 1769): Sending signal. PID: 1769 SIG: 9
I/ActivityManager(  820): Start proc 3991:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableControlService
I/ActivityManager(  820): Start proc 4012:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
E/lowmemorykiller(  257): Error writing /proc/1769/oom_score_adj; errno=22
W/ResourcesManager( 3991): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3991): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/WifiService(  820): Client connection lost with reason: 4
I/ActivityManager(  820): Process com.google.android.gms (pid 1769) has died
W/ActivityManager(  820): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  820): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
W/ActivityManager(  820): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  820): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager(  820): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
D/AndroidRuntime( 3929): Shutting down VM
I/MultiDex( 3991): VM with version 2.1.0 has multidex support
I/MultiDex( 3991): install
I/MultiDex( 3991): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  820): Start proc 4041:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
E/SharedPreferencesImpl( 3929): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
--------- beginning of crash
E/AndroidRuntime( 3929): FATAL EXCEPTION: main
E/AndroidRuntime( 3929): Process: com.google.android.googlequicksearchbox:search, PID: 3929
E/AndroidRuntime( 3929): java.lang.RuntimeException: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR worker
E/AndroidRuntime( 3929): 	at com.google.android.search.core.bh$2.onFailure(SearchController.java:381)
E/AndroidRuntime( 3929): 	at com.google.android.apps.gsa.shared.util.c.a.r$1.run(TaskRunnerImpl.java:329)
E/AndroidRuntime( 3929): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 3929): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 3929): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 3929): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 3929): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 3929): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 3929): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 3929): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 3929): Caused by: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR worker
E/AndroidRuntime( 3929): 	at java.util.concurrent.FutureTask.report(FutureTask.java:93)
E/AndroidRuntime( 3929): 	at java.util.concurrent.FutureTask.get(FutureTask.java:163)
E/AndroidRuntime( 3929): 	at com.google.android.apps.gsa.shared.util.c.d.get(LazyListenableFuture.java:124)
E/AndroidRuntime( 3929): 	at com.google.android.apps.gsa.shared.util.c.d$1.call(LazyListenableFuture.java:46)
E/AndroidRuntime( 3929): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 3929): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 3929): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 3929): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 3929): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/AndroidRuntime( 3929): Caused by: com.google.android.libraries.velour.dynloader.h: Failed to load JAR worker
E/AndroidRuntime( 3929): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:216)
E/AndroidRuntime( 3929): 	at com.google.android.apps.gsa.shared.e.k.auz(ExtraDexRegistry.java:344)
E/AndroidRuntime( 3929): 	at com.google.android.apps.gsa.shared.e.k.a(ExtraDexRegistry.java:303)
E/AndroidRuntime( 3929): 	at com.google.android.apps.gsa.shared.e.k$1.auD(ExtraDexRegistry.java:323)
E/AndroidRuntime( 3929): 	at com.google.android.apps.gsa.shared.e.k$1.call(ExtraDexRegistry.java:318)
E/AndroidRuntime( 3929): 	... 5 more
E/AndroidRuntime( 3929): Caused by: java.io.IOException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 3929): 	at java.io.File.createNewFile(File.java:941)
E/AndroidRuntime( 3929): 	at com.google.android.libraries.velour.dynloader.i.bjP(JarLoader.java:278)
E/AndroidRuntime( 3929): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:207)
E/AndroidRuntime( 3929): 	... 9 more
E/AndroidRuntime( 3929): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 3929): 	at libcore.io.Posix.open(Native Method)
E/AndroidRuntime( 3929): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/AndroidRuntime( 3929): 	at java.io.File.createNewFile(File.java:934)
E/AndroidRuntime( 3929): 	... 11 more
W/Launcher( 1279): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3e788d61 new=com.google.android.velvet.VelvetApplication@3e788d61
I/art     (  370): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 238us total 10.615ms
E/SQLiteLog( 1279): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
E/DropBoxManagerService(  820): Can't write: system_app_crash
E/DropBoxManagerService(  820): java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  820): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  820): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  820): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  820): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  820): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  820): 	... 5 more
I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 207us total 9.775ms
D/OpenGLRenderer(  820): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  820): Validating map...
I/art     (  370): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 199us total 9.627ms
V/JNIHelp ( 3991): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/ActivityManager(  820): Start proc 4061:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
I/ProviderInstaller( 3991): Installed default security provider GmsCore_OpenSSL
W/NativeLibraryUtils( 3991): Failed to open lock file
W/NativeLibraryUtils( 3991): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 3991): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 3991): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 3991): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 3991): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 3991): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 3991): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 3991): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 3991): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 3991): 	... 3 more
I/OpenGLRenderer(  820): Initialized EGL, version 1.4
D/OpenGLRenderer(  820): Enabling debug mode 0
I/ActivityManager(  820): Start proc 4084:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
W/ResourcesManager( 4084): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4084): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 4084): VM with version 2.1.0 has multidex support
I/MultiDex( 4084): install
I/MultiDex( 4084): VM has multidex support, MultiDex support library is disabled.
E/SQLiteDatabase( 4084): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 4084): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4084): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4084): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4084): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1181)
E/SQLiteDatabase( 4084): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1200)
E/SQLiteDatabase( 4084): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 4084): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4084): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4084): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4084): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4084): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4084): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4084): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 4084): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4084): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4084): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4084): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4084): 	at com.google.android.gms.security.snet.aa.b(SourceFile:826)
E/SQLiteDatabase( 4084): 	at com.google.android.gms.security.snet.aa.a(SourceFile:847)
E/SQLiteDatabase( 4084): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 4084): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4084): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4084): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4084): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4084): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4084): 	at java.lang.Thread.run(Thread.java:818)
V/JNIHelp ( 4084): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...

```
