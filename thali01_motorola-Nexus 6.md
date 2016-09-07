#### Test 84265062e3ffea4_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-07 12:05:03.317  3433  3444 D Finsky  : [256] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,09-07 12:05:03.339  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-07 12:05:03.352  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-07 12:05:03.356  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-07 12:05:03.412  1528  2285 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-07 12:05:03.413  1528  2285 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-07 12:05:03.413  1528  2285 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:05:03.414  1528  2285 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-07 12:05:03.446  3433  3444 D Finsky  : [256] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
09-07 12:05:03.955  3683  3683 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-07 12:05:03.960  3683  3683 D AndroidRuntime: CheckJNI is OFF
09-07 12:05:04.005  3683  3683 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-07 12:05:04.053  3683  3683 I Radio-JNI: register_android_hardware_Radio DONE
09-07 12:05:04.077  3683  3683 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-07 12:05:04.081   874  2014 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-07 12:05:04.114  2036  2050 W SearchService: Abort, client detached.
09-07 12:05:04.119  3683  3683 D AndroidRuntime: Shutting down VM
09-07 12:05:04.124  2036  2036 I HotwordDetector: Closing mic
09-07 12:05:04.125  2036  2348 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@a6e2113
09-07 12:05:04.125  2036  2357 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-07 12:05:04.144   874  1403 I ActivityManager: Start proc 3693:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-07 12:05:04.181   377  2360 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-07 12:05:04.182   377  2360 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-07 12:05:04.187   377  1286 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-07 12:05:04.192  2036  2356 I MicroRecognitionRnrImpl: Detection finished
09-07 12:05:04.192  2036  2354 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-07 12:05:04.216  3693  3693 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-07 12:05:04.240  3693  3693 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-07 12:05:04.251  3693  3693 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2869-2872)
09-07 12:05:04.251  3693  3693 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 12:05:04.276  3693  3693 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {36d2c87}
09-07 12:05:04.277  3693  3693 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 12:05:04.278  3693  3693 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-07 12:05:04.292  3693  3693 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-07 12:05:04.295  3693  3693 E SysUtils: ApplicationContext is null in ApplicationStatus
09-07 12:05:04.314  3693  3693 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-07 12:05:04.325  3693  3693 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 12:05:04.325  3693  3693 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 12:05:04.325  3693  3693 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 12:05:04.325  3693  3693 I Adreno  : Build Date                       : 10/20/15
09-07 12:05:04.325  3693  3693 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 12:05:04.325  3693  3693 I Adreno  : Local Branch                     : M14
09-07 12:05:04.325  3693  3693 I Adreno  : Remote Branch                    : 
09-07 12:05:04.325  3693  3693 I Adreno  : Remote Branch                    : 
09-07 12:05:04.325  3693  3693 I Adreno  : Reconstruct Branch               : 
,09-07 12:05:04.378   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9d703d0:true
,09-07 12:05:04.425  3693  3693 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-07 12:05:04.439  3693  3693 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-07 12:05:04.531  3693  3731 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-07 12:05:04.548  3693  3718 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-07 12:05:04.593  3693  3731 I OpenGLRenderer: Initialized EGL, version 1.4
,09-07 12:05:04.679   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +560ms
,09-07 12:05:04.688  1890  1890 I Keyboard.Facilitator: onFinishInput()
,09-07 12:05:04.720  3693  3693 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3693
,09-07 12:05:04.889  3693  3693 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-07 12:05:04.964   874  1974 I ActivityManager: Killing 3150:com.google.android.gm/u0a78 (adj 15): empty #17
,09-07 12:05:05.007   874  1974 I ActivityManager: Killing 2676:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
,09-07 12:05:05.140  3693  3734 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1701119696
,09-07 12:05:05.152  3693  3734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 12:05:05.152  3693  3734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 12:05:05.152  3693  3734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 12:05:05.152  3693  3734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 12:05:05.152  3693  3734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-07 12:05:05.152  3693  3734 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6fda5b added. We now have 1 listener(s)
,09-07 12:05:05.157  3693  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-07 12:05:05.158  3693  3734 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 12:05:05.158  3693  3734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:05:05.158  3693  3734 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 12:05:05.162  3693  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 12:05:05.162  3693  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 12:05:05.162  3693  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 12:05:05.162  3693  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-07 12:05:05.162  3693  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 12:05:05.162  3693  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 12:05:05.162  3693  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 12:05:05.162  3693  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 12:05:05.162  3693  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 12:05:05.162  3693  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 12:05:05.162  3693  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 12:05:05.162  3693  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 12:05:05.162  3693  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 12:05:05.162  3693  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-07 12:05:05.162  3693  3734 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fe35e36 added. We now have 1 listener(s)
09-07 12:05:05.162  3693  3734 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 12:05:05.166   874  1317 D WifiService: New client listening to asynchronous messages
,09-07 12:05:05.167  3693  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 12:05:05.167  3693  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-07 12:05:05.167  3693  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-07 12:05:05.167  3693  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-07 12:05:05.167  3693  3734 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-07 12:05:05.172  3693  3734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:05:05.172  3693  3734 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-07 12:05:05.181  3693  3734 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:05:05.183  3693  3734 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:05:05.183  3693  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:05.183  3693  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 12:05:05.183  3693  3734 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:05.183  3693  3734 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:05.183  3693  3734 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:05:05.183  3693  3734 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:05:05.183  3693  3734 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 12:05:05.183  3693  3734 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-07 12:05:05.184  3693  3734 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 12:05:05.186  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:05.187  3693  3734 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-07 12:05:05.187  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:05.217  3693  3693 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-07 12:05:06.033  3693  3744 W jxcore-log: Initializing JXcore engine
09-07 12:05:06.033  3693  3744 W jxcore-log: JXcore engine is ready
,09-07 12:05:06.071  3744  3744 W Thread-310: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8952 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-07 12:05:06.071  3744  3744 W Thread-310: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10663]" dev="sockfs" ino=10663 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-07 12:05:06.071  3744  3744 W Thread-310: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-07 12:05:06.071  3744  3744 W Thread-310: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24808]" dev="sockfs" ino=24808 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-07 12:05:06.082  3693  3744 W jxcore-log: Starting JXcore engine
,09-07 12:05:06.162  3693  3744 W jxcore-log: Platform android
09-07 12:05:06.162  3693  3744 W jxcore-log: 
09-07 12:05:06.162  3693  3744 W jxcore-log: Process ARCH arm
09-07 12:05:06.162  3693  3744 W jxcore-log: 
,09-07 12:05:06.446  3693  3744 I jxcore-log: JXcore Cordova bridge is ready!
09-07 12:05:06.446  3693  3744 I jxcore-log: 
,09-07 12:05:06.447  3693  3744 W jxcore-log: JXcore engine is started
,09-07 12:05:06.456  3693  3734 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-07 12:05:06.460  3693  3693 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-07 12:05:08.549   874  1883 D NetlinkSocketObserver: NeighborEvent{elapsedMs=117170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 12:05:10.991   874  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-07 12:05:14.024   874  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-07 12:05:14.363  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:05:14.369  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-07 12:05:14.370  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:05:14.392  1528  2055 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 12:05:14.392  1528  2055 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 12:05:14.392  1528  2055 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:05:14.392  1528  2055 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:05:14.400   874  1315 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-07 12:05:14.407  3433  3433 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 12:05:14.407  3433  3433 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-07 12:05:14.407  3433  3433 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-07 12:05:16.311  3693  3744 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 12:05:16.311  3693  3744 I jxcore-log: 
,09-07 12:05:16.314  3693  3744 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 12:05:16.314  3693  3744 I jxcore-log: 
,09-07 12:05:16.319  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:05:16.319  3693  3744 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:05:16.319  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:16.319  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 12:05:16.319  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:16.319  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:16.319  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:05:16.319  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:05:16.319  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:05:16.320  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:16.320  3693  3744 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 12:05:16.323  3693  3744 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 12:05:16.323  3693  3744 I jxcore-log: 
,09-07 12:05:16.324  3693  3744 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 12:05:16.324  3693  3744 I jxcore-log: 
,09-07 12:05:16.867  3693  3744 D executeNativeTests: Running unit tests
,09-07 12:05:16.946  3693  3744 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 12:05:16.946  3693  3744 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e46b added. We now have 2 listener(s)
09-07 12:05:16.947  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 12:05:16.947  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:05:16.947  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 12:05:16.947  3693  3744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:05:16.947  3693  3744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 added. We now have 2 listener(s)
09-07 12:05:16.947  3693  3744 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 12:05:16.948  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 12:05:16.953  3693  3744 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:05:16.960  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:16.961  3693  3744 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:05:16.961  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:16.961  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 12:05:16.961  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:16.961  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:16.961  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:05:16.961  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:05:16.961  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:05:16.961  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:05:16.961  3693  3744 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 12:05:16.962  3693  3744 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 12:05:16.964  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:16.967  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:16.972  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 12:05:16.973  3693  3744 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 12:05:16.973  3693  3744 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 12:05:16.979  3693  3744 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-07 12:05:16.981  3693  3744 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-07 12:05:16.982  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 12:05:16.982  3693  3744 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 12:05:16.984  3693  3744 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 12:05:16.989  3693  3744 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 12:05:16.989  3693  3744 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 12:05:16.989  3693  3744 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:16.990  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 12:05:16.990  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:16.990  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:05:16.990  3693  3744 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:05:16.990  3693  3744 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e46b removed from the list
,09-07 12:05:16.990  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:16.990  3693  3744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 removed from the list
09-07 12:05:16.990  3693  3744 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:16.990  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,09-07 12:05:16.991  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 12:05:16.991  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:16.991  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:16.992  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:16.992  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 12:05:16.992  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:16.993  3693  3744 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-07 12:05:16.993  3693  3744 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 12:05:16.993  3693  3744 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:16.994  3693  3744 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 12:05:16.994  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:16.994  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:16.994  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:16.994  3693  3744 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e46b not in the list
09-07 12:05:16.994  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:16.994  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:16.994  3693  3744 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:16.994  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 12:05:16.994  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:16.994  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:16.994  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:16.995  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:16.996  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:16.996  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:16.996  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
,09-07 12:05:17.015  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-07 12:05:17.015  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 12:05:17.015  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 12:05:17.016  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 12:05:17.016  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-07 12:05:17.016  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 12:05:17.016  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-07 12:05:17.017  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 12:05:17.017  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 12:05:17.017  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-07 12:05:17.017  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 12:05:17.018  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 12:05:17.018  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-07 12:05:17.018  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 12:05:17.018  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 12:05:17.019  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-07 12:05:17.019  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 12:05:17.019  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-07 12:05:17.020  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 12:05:17.020  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 12:05:17.020  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-07 12:05:17.020  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 12:05:17.021  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 12:05:17.021  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 12:05:17.021  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 12:05:17.021  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 12:05:17.022  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 12:05:17.022  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 12:05:17.022  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 12:05:17.023  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 12:05:17.023  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 12:05:17.023  3693  3744 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:17.023  3693  3744 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:17.024  3693  3744 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:17.024  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:17.024  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.024  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.025  3693  3744 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e46b not in the list
09-07 12:05:17.025  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.025  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
,09-07 12:05:17.026  3693  3744 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:17.026  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.026  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.026  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 12:05:17.026  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.026  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:17.026  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:17.026  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.026  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.027  3693  3744 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-07 12:05:17.028  3693  3744 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:05:17.030  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:05:17.030  3693  3744 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:05:17.030  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:17.030  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 12:05:17.030  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:17.030  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:17.030  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:05:17.030  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:05:17.030  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 12:05:17.030  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:17.031  3693  3744 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 12:05:17.031  3693  3744 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:05:17.031  3693  3744 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 12:05:17.031  3693  3744 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 12:05:17.031  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 12:05:17.031  3693  3744 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:05:17.031  3693  3744 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 12:05:17.034  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:17.034  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
09-07 12:05:17.034  3693  3744 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-07 12:05:17.035  3693  3744 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-07 12:05:17.035  3693  3744 I io.jxcore.node.ConnectionHelper: start: OK
09-07 12:05:17.036  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:17.036  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:17.037  3693  3693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-07 12:05:17.037  3693  3744 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
,09-07 12:05:17.038  3693  3744 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:17.038  3693  3744 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:17.038  3693  3744 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-07 12:05:17.039  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.039  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 12:05:17.039  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 12:05:17.039  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 12:05:17.039  3693  3744 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 12:05:17.039  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 12:05:17.040  3693  3744 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 12:05:17.040  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:05:17.041  3693  3744 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 12:05:17.041  3693  3693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:05:17.041  3693  3693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 12:05:17.041  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:17.041  3693  3693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 12:05:17.041  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.041  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 12:05:17.041  3693  3744 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e46b not in the list
,09-07 12:05:17.041  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 12:05:17.041  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.042  3693  3744 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 12:05:17.042  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.043  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 12:05:17.043  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.043  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:17.043  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:17.043  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.043  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.044   874  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-07 12:05:17.044  3693  3744 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 12:05:17.047  3693  3744 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:05:17.049  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:05:17.049  3693  3744 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:05:17.049  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:17.049  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 12:05:17.049  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:17.049  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:17.049  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:05:17.049  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:05:17.049  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:05:17.049  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:17.049  3693  3744 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 12:05:17.050  3693  3744 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:05:17.050  3693  3744 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 12:05:17.050  3693  3744 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 12:05:17.050  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 12:05:17.050  3693  3744 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:05:17.050  3693  3744 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 12:05:17.052  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:17.054  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
09-07 12:05:17.055  3693  3744 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-07 12:05:17.055  3693  3744 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 12:05:17.055  3693  3744 I io.jxcore.node.ConnectionHelper: start: OK
09-07 12:05:17.055  3693  3744 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:17.055  3693  3744 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:17.056  3693  3744 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 12:05:17.055  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:17.056  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.056  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 12:05:17.056  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 12:05:17.056  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 12:05:17.056  3693  3744 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 12:05:17.057  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 12:05:17.057  3693  3744 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 12:05:17.057  3693  3693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-07 12:05:17.057  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:05:17.057  3693  3744 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 12:05:17.058  3693  3744 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:17.058  3693  3744 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-07 12:05:17.058  3693  3693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:05:17.058  3693  3744 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:17.058  3693  3744 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:17.058  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:17.058  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.058  3693  3693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:05:17.060  3693  3693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 12:05:17.059  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:05:17.060  3693  3744 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e46b not in the list
09-07 12:05:17.061  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.061  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.061  3693  3744 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:17.061  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.061  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.061  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.062  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:17.062  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:17.062  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.062  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.062  3693  3744 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-07 12:05:17.063  3693  3744 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:17.063  3693  3744 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:17.063  3693  3744 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:17.063  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:17.063  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.063  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.063  3693  3744 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e46b not in the list
09-07 12:05:17.063  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.064  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.064  3693  3744 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:17.064  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.064  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.064  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.064  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.064  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:17.064  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:17.064  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.064  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.065  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 12:05:17.065  3693  3744 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:17.065  3693  3744 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:17.065  3693  3744 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:17.066  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:17.066  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.066  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.066  3693  3744 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e46b not in the list
09-07 12:05:17.066  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.066  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.066  3693  3744 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:17.066  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.066  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.066  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.066  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.066  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:17.066  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:17.067  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.067  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.067  3693  3744 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-07 12:05:17.067  3693  3744 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:17.067  3693  3744 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:17.067  3693  3744 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:17.067  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:17.067  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.067  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.068  3693  3744 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e46b not in the list
09-07 12:05:17.068  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.068  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.068  3693  3744 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:17.068  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.068  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.068  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.068  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.068  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:17.068  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:17.068  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.068  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.069  3693  3744 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-07 12:05:17.069  3693  3744 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:17.069  3693  3744 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:17.069  3693  3744 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:17.069  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:17.069  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.069  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.069  3693  3744 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e46b not in the list
09-07 12:05:17.069  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.070  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.070  3693  3744 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:17.070  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.070  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.070  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.070  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.070  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:17.070  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:17.070  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.070  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.071  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 12:05:17.071  3693  3744 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 12:05:17.071  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 12:05:17.071  3693  3744 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 12:05:17.071  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 12:05:17.071  3693  3744 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 12:05:17.071  3693  3744 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:17.071  3693  3744 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:17.071  3693  3744 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:17.071  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:17.071  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.071  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.071  3693  3744 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e46b not in the list
09-07 12:05:17.071  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.071  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.072  3693  3744 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:17.072  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.072  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.072  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.072  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.072  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:17.072  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:17.072  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.072  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.073  3693  3744 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:05:17.073  3693  3744 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 12:05:17.073  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 12:05:17.075  3693  3744 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:05:17.075  3693  3744 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-07 12:05:17.075  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 12:05:17.075  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 12:05:17.075  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 12:05:17.075  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 12:05:17.075  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 12:05:17.075  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 12:05:17.076  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 12:05:17.076  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 12:05:17.076  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 12:05:17.076  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 12:05:17.076  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 12:05:17.076  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 12:05:17.076  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 12:05:17.076  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 12:05:17.076  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 12:05:17.076  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 12:05:17.076  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 12:05:17.076  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 12:05:17.076  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 12:05:17.076  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 12:05:17.076  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 12:05:17.076  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-07 12:05:17.076  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 12:05:17.076  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 12:05:17.077  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 12:05:17.077  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 12:05:17.077  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 12:05:17.077  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 12:05:17.077  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 12:05:17.077  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 12:05:17.077  3693  3744 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-07 12:05:17.077  3693  3744 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 12:05:17.077  3693  3744 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 12:05:17.077  3693  3744 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:05:17.077  3693  3744 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 12:05:17.077  3693  3744 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 12:05:17.077  3693  3744 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:05:17.077  3693  3744 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 12:05:17.078  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-07 12:05:17.078  3693  3744 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
09-07 12:05:17.079  3693  3744 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-07 12:05:17.079  3693  3744 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-07 12:05:17.079  3693  3744 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-07 12:05:17.080  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 12:05:17.080  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 12:05:17.080  3693  3744 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-07 12:05:17.080  3693  3744 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:05:17.080  3693  3744 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 12:05:17.080  3693  3744 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:17.080  3693  3744 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:17.080  3693  3744 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:17.081  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:17.081  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.081  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.081  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-07 12:05:17.081  3693  3756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 374)
09-07 12:05:17.081  3693  3756 E BluetoothDevice: Bluetooth is not enabled
09-07 12:05:17.081  3693  3744 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e46b not in the list
09-07 12:05:17.081  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.081  3693  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): null (thread ID: 374)
09-07 12:05:17.081  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.081  3693  3744 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:17.081  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.081  3693  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 374)
09-07 12:05:17.081  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.081  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.082  3693  3756 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): null (thread ID: 374)
09-07 12:05:17.082  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.082  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:17.082  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:17.082  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.082  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.082  3693  3693 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> 00:11:22:33:44:55]: Failed to connect (tried 1 time(s)): null
09-07 12:05:17.082  3693  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Failed to find a thread with ID 374
09-07 12:05:17.082  3693  3756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 374)
09-07 12:05:17.083  3693  3744 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-07 12:05:17.083  3693  3693 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: Failed to connect (tried 1 time(s)): null
09-07 12:05:17.083  3693  3693 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 12:05:17.083  3693  3693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 12:05:17.083  3693  3744 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:17.083  3693  3744 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:17.083  3693  3744 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:17.083  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:17.084  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.084  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.084  3693  3744 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e46b not in the list
09-07 12:05:17.084  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.084  3693  3757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 374
09-07 12:05:17.085  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.085  3693  3744 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:17.085  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.085  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.085  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.085  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.085  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:17.085  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:17.085  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.085  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.086  3693  3744 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-07 12:05:17.086  3693  3744 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:17.086  3693  3744 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:17.086  3693  3744 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:17.086  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:17.086  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.086  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.086  3693  3744 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e46b not in the list
09-07 12:05:17.086  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.086  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.086  3693  3744 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:17.086  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.086  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.086  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.087  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.087  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:17.087  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:17.087  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.087  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.087  3693  3744 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 12:05:17.087  3693  3744 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-07 12:05:17.087  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 12:05:17.087  3693  3744 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 12:05:17.088  3693  3744 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 12:05:17.088  3693  3744 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 12:05:17.088  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 12:05:17.088  3693  3744 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 12:05:17.088  3693  3744 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 12:05:17.088  3693  3744 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 12:05:17.088  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 12:05:17.088  3693  3744 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,09-07 12:05:17.088  3693  3744 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 12:05:17.088  3693  3744 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:17.088  3693  3744 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:17.088  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:17.088  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.088  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.088  3693  3744 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e46b not in the list
09-07 12:05:17.088  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.089  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.089  3693  3744 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 12:05:17.089  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.089  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.089  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.089  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.089  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:17.089  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:17.089  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.089  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.089  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 12:05:17.090  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.090  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:17.090  3693  3744 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e46b not in the list
09-07 12:05:17.090  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.090  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
,09-07 12:05:17.090  3693  3744 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 12:05:17.090  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.090  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.090  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.090  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list,
09-07 12:05:17.090  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 12:05:17.090  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 12:05:17.090  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.090  3693  3744 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e46b not in the list
,09-07 12:05:17.090  3693  3744 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 12:05:17.090  3693  3744 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:17.090  3693  3744 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:17.090  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:17.090  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 12:05:17.091  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.091  3693  3744 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e46b not in the list
09-07 12:05:17.091  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.091  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.091  3693  3744 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 12:05:17.091  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.091  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:17.091  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 12:05:17.091  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.091  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:17.091  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:17.091  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-07 12:05:17.091  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.092  3693  3744 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 12:05:17.092  3693  3744 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:05:17.092  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
,09-07 12:05:17.092  3693  3744 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
09-07 12:05:17.093  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 12:05:17.093  3693  3693 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
09-07 12:05:17.093  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:17.093  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-07 12:05:17.093  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.093  3693  3744 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
,09-07 12:05:17.093  3693  3693 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 12:05:17.093  3693  3744 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e46b not in the list
09-07 12:05:17.093  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 12:05:17.093  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-07 12:05:17.093  3693  3744 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 12:05:17.093  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 12:05:17.093  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.093  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:17.093  3693  3744 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 12:05:17.094  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.094  3693  3693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:05:17.094  3693  3744 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:17.094  3693  3744 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 12:05:17.094  3693  3744 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:17.094  3693  3693 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:05:17.094  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:17.094  3693  3693 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 12:05:17.094  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.094  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.094  3693  3744 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e46b not in the list
,09-07 12:05:17.094  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.094  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.094  3693  3744 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:17.094  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.094  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.094  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.094  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.094  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:17.094  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:17.094  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.095  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.095  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 12:05:17.095  3693  3744 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 12:05:17.095  3693  3744 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-07 12:05:17.095  3693  3744 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 12:05:17.095  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 12:05:17.095  3693  3744 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 12:05:17.095  3693  3744 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:17.095  3693  3744 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:17.096  3693  3744 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:17.096  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 12:05:17.096  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.096  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.096  3693  3744 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e46b not in the list
09-07 12:05:17.096  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.096  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.096  3693  3744 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 12:05:17.096  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.096  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.096  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.096  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.096  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:17.096  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:17.096  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.096  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
,09-07 12:05:17.097  3693  3744 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:17.097  3693  3744 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:17.097  3693  3744 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:17.098  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:17.098  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 12:05:17.098  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.098  3693  3744 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e46b not in the list
09-07 12:05:17.098  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.098  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.098  3693  3744 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:17.098  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.098  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.098  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 12:05:17.098  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.098  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:17.098  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:17.098  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.098  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.099  3693  3744 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:17.099  3693  3744 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:17.099  3693  3744 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 12:05:17.099  3693  3744 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:17.099  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.099  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.099  3693  3744 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff6e46b not in the list
09-07 12:05:17.099  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 12:05:17.099  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.099  3693  3744 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:17.099  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.099  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:17.099  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:17.099  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:17.100  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:17.100  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:17.100  3693  3744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:17.100  3693  3744 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7a0bc8 not in the list
09-07 12:05:17.100  3693  3744 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-07 12:05:17.101  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 12:05:17.101  3693  3744 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-07 12:05:17.101  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 12:05:17.101  3693  3744 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-07 12:05:17.101  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 12:05:17.102  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 12:05:17.102  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-07 12:05:17.103  3693  3744 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-07 12:05:17.103  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 12:05:17.103  3693  3744 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-07 12:05:17.103  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 12:05:17.103  3693  3744 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-07 12:05:17.103  3693  3744 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-07 12:05:17.103  3693  3744 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-07 12:05:17.103  3693  3744 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-07 12:05:17.104  3693  3744 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-07 12:05:17.104  3693  3744 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-07 12:05:17.104  3693  3744 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-07 12:05:17.104  3693  3744 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-07 12:05:17.104  3693  3744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:05:17.105  3693  3744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@db58a12 added. We now have 2 listener(s)
09-07 12:05:17.105  3693  3744 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:05:17.105   874  1403 D WifiService: setWifiEnabled: true pid=3693, uid=10000
09-07 12:05:17.105   874  1403 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 12:05:17.106  3693  3744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:05:17.106  3693  3744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24975e3 added. We now have 3 listener(s)
09-07 12:05:17.106  3693  3744 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:05:17.107  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:17.107  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:17.107  3693  3744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:05:17.107  3693  3744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bc48be0 added. We now have 4 listener(s)
,09-07 12:05:17.107  3693  3744 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:05:17.108  3693  3744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:05:17.108  3693  3744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@48dfe99 added. We now have 5 listener(s)
09-07 12:05:17.108  3693  3744 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:05:17.109   874  2222 D WifiService: setWifiEnabled: false pid=3693, uid=10000
09-07 12:05:17.109   874  2222 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-07 12:05:17.122  1475  1475 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 12:05:17.123   874  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-07 12:05:17.123   874  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-07 12:05:17.124   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 12:05:17.124   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 12:05:17.127   874   891 I ActivityManager: Start proc 3759:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
09-07 12:05:17.129  3693  3744 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:05:17.130   874  1884 D DhcpClient: Clearing IP address
,09-07 12:05:17.130   373   872 D CommandListener: Clearing all IP addresses on wlan0
09-07 12:05:17.133  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:17.133  3693  3744 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:05:17.133  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:17.133  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 12:05:17.133  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:17.133  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:17.133  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:05:17.133  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:05:17.133  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:05:17.133  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:17.133  3693  3744 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 12:05:17.133  3693  3744 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 12:05:17.134   373   872 D CommandListener: Setting iface cfg
09-07 12:05:17.134  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:17.136  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:17.137   874  1888 D DhcpClient: Receive thread stopped
09-07 12:05:17.139  1528  2514 V NativeCrypto: Read error: ssl=0xaee54000: I/O error during system call, Connection timed out
09-07 12:05:17.141  1528  2514 V NativeCrypto: SSL shutdown failed: ssl=0xaee54000: I/O error during system call, Broken pipe
09-07 12:05:17.142   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 12:05:17.143   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-07 12:05:17.144   874  1393 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,09-07 12:05:17.144   874  1880 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-07 12:05:17.144   874  1315 D WifiStateMachine: Start Disconnecting Watchdog 1
09-07 12:05:17.145   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 12:05:17.145   396   396 E Parcel  : Reading a NULL string not supported here.
09-07 12:05:17.146   874  1880 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-07 12:05:17.147   874  1319 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-07 12:05:17.179   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 12:05:17.207   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 12:05:17.208   874  1319 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-07 12:05:17.209   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:05:17.210   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-07 12:05:17.212   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-07 12:05:17.215  3693  3693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:17.215  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:17.215  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:17.215  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 12:05:17.215  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:17.215  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:17.215  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:17.215  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:17.215  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:05:17.215  3693  3693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:05:17.215  3693  3693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:05:17.218  3344  3344 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@b6fda5b and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-07 12:05:17.219  3693  3693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:17.219  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:17.219  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:17.219  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 12:05:17.219  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:17.219  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:17.219  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:17.219  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:17.219  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:05:17.219  3693  3693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:17.219  3693  3693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:05:17.221  1729  1729 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 12:05:17.231  3759  3759 D AdapterServiceConfig: Adding HeadsetService
,09-07 12:05:17.231  3759  3759 D AdapterServiceConfig: Adding A2dpService
09-07 12:05:17.231  3759  3759 D AdapterServiceConfig: Adding HidService
09-07 12:05:17.231  3759  3759 D AdapterServiceConfig: Adding HealthService
09-07 12:05:17.231  3759  3759 D AdapterServiceConfig: Adding PanService
09-07 12:05:17.232  3759  3759 D AdapterServiceConfig: Adding GattService
09-07 12:05:17.232  3759  3759 D AdapterServiceConfig: Adding BluetoothMapService
,09-07 12:05:17.236  1729  1729 D SystemUpdateService: onCreate
,09-07 12:05:17.239  1729  1729 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 12:05:17.250  1729  1729 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-07 12:05:17.258  1729  2478 I iu.UploadsManager: num queued entries: 0
,09-07 12:05:17.258   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@784e054:true
,09-07 12:05:17.259  3759  3759 D BluetoothAdapterState: make() - Creating AdapterState
09-07 12:05:17.261  3759  3759 I bt_bluedroid: init
09-07 12:05:17.261  3759  3781 I BluetoothAdapterState: Entering OffState
,09-07 12:05:17.264  1729  1729 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 12:05:17.264  3759  3783 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-07 12:05:17.265   373   872 E Netd    : netlink response contains error (No such file or directory)
09-07 12:05:17.265  1729  1729 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-07 12:05:17.265  3759  3783 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-07 12:05:17.265  3759  3783 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 12:05:17.265  3759  3783 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-07 12:05:17.266   874  1319 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-07 12:05:17.266   874  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-07 12:05:17.266  3759  3759 I bt_bluedroid: get_profile_interface socket
09-07 12:05:17.267  3759  3786 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-07 12:05:17.267  3759  3759 I bt_bluedroid: get_profile_interface sdp
,09-07 12:05:17.275  1729  3779 I SystemUpdateService: active receiver: enabled
,09-07 12:05:17.277  1729  2478 I iu.UploadsManager: num updated entries: 0
,09-07 12:05:17.277   874   884 I ActivityManager: Start proc 3787:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
09-07 12:05:17.279  3759  3786 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 12:05:17.281  3759  3772 I bt_bluedroid: config_hci_snoop_log
,09-07 12:05:17.282   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
09-07 12:05:17.282   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,09-07 12:05:17.285  3693  3693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:05:17.286  3759  3781 D BluetoothAdapterState: Current state: OFF, message: 0
09-07 12:05:17.286  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:17.286  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:17.286  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 12:05:17.286  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:17.286  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:17.286  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:17.286  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:17.286  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:05:17.286  3759  3781 D BluetoothAdapterProperties: Setting state to 14
09-07 12:05:17.286  3759  3781 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-07 12:05:17.287  3693  3693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:17.287  3693  3693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:05:17.287   874  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 12:05:17.288  3759  3781 D BluetoothBondStateMachine: make
09-07 12:05:17.288  3693  3693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:05:17.289  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:17.289  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:17.289  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 12:05:17.289  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:17.289  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:17.289  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:17.289  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:17.289  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:05:17.289  3693  3693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:17.289  3693  3693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:05:17.289  1909  2315 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 12:05:17.293  3759  3799 I BluetoothBondStateMachine: StableState(): Entering Off State
09-07 12:05:17.295  3759  3781 I BluetoothAdapterState: Entering PendingCommandState
09-07 12:05:17.296  3759  3759 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-07 12:05:17.299  3759  3759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a754cd9
,09-07 12:05:17.299  3759  3759 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 12:05:17.300  3759  3759 D BtGatt.GattService: Received start request. Starting profile...
09-07 12:05:17.300  3759  3759 D BtGatt.GattService: start()
09-07 12:05:17.300  3759  3759 I bt_bluedroid: get_profile_interface gatt
09-07 12:05:17.300  1729  2478 I iu.SyncManager: NEXT; no task
09-07 12:05:17.301  3759  3759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a754cd9
,09-07 12:05:17.301  3759  3759 D BtGatt.AdvertiseManager: advertise manager created
,09-07 12:05:17.305  3759  3759 V BluetoothAdapterState: isTurningOff()=false
,09-07 12:05:17.305  3759  3759 V BluetoothAdapterState: isTurningOn()=false
09-07 12:05:17.305  3759  3759 V BluetoothAdapterState: isBleTurningOn()=true
09-07 12:05:17.305  3759  3759 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:05:17.305  3759  3781 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-07 12:05:17.306  3759  3781 I bt_bluedroid: enable
09-07 12:05:17.306  3759  3783 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-07 12:05:17.306  3759  3783 I bt_hci  : start_up
,09-07 12:05:17.309  1729  3779 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 12:05:17.312  3787  3787 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-07 12:05:17.314  3759  3783 I bt_vendor: alloc value 0xb3a71189
,09-07 12:05:17.314  3759  3783 I bt_vendor: init
09-07 12:05:17.314  3759  3783 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-07 12:05:17.314  3759  3783 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
09-07 12:05:17.314  3787  3787 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:05:17.317  1729  3779 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-07 12:05:17.317  1729  3779 I SystemUpdateService: now status is 0 (complete)
09-07 12:05:17.317  1729  3779 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 12:05:17.317  1729  3779 I SystemUpdateService: file has been verified
09-07 12:05:17.317  1729  3779 I SystemUpdateService: OTA package size = 12249756
,09-07 12:05:17.321  3787  3787 D SprintDMHelper: simOperator: 
,09-07 12:05:17.321  3787  3787 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 12:05:17.327  1729  3779 I SystemUpdateService: showing system update notification
,09-07 12:05:17.344   874  1393 I ActivityManager: Start proc 3805:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-07 12:05:17.366  1729  1729 D SystemUpdateService: onDestroy
,09-07 12:05:17.368   874   885 I ActivityManager: Killing 2948:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-07 12:05:17.421  3759  3783 D bt_hci  : start_up starting async portion
,09-07 12:05:17.422  3759  3804 I bt_hci  : event_finish_startup
09-07 12:05:17.422  3759  3804 I bt_hci_h4: hal_open
09-07 12:05:17.422  3759  3804 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-07 12:05:17.431  3759  3804 I bt_userial_vendor: device fd = 51 open
,09-07 12:05:17.460   874  1716 I ActivityManager: Start proc 3821:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
09-07 12:05:17.461  3759  3804 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 12:05:17.466   874  1716 I ActivityManager: Killing 3344:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-07 12:05:17.494  3759  3804 D bt_hwcfg: Chipset BCM4354A2
09-07 12:05:17.494  3759  3804 D bt_hwcfg: Target name = [BCM4354A2]
09-07 12:05:17.495  3759  3804 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-07 12:05:17.528  3821  3821 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-07 12:05:17.590  3821  3821 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-07 12:05:17.590  3821  3821 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-07 12:05:17.590  3821  3821 I GAv4    :   adb logcat -s GAv4
,09-07 12:05:17.594  3693  3693 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 12:05:17.607  3821  3821 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-07 12:05:17.613  3821  3821 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,09-07 12:05:17.631  3821  3838 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-07 12:05:17.750  3821  3821 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-07 12:05:17.783  3821  3821 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-07 12:05:17.803  3821  3821 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6421-6424)
,09-07 12:05:17.804  3821  3821 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 12:05:17.814  3821  3821 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f98104b}
,09-07 12:05:17.815  3821  3821 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 12:05:17.815  3821  3821 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-07 12:05:17.822  3821  3821 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-07 12:05:17.824  3821  3821 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-07 12:05:17.841  3821  3821 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-07 12:05:17.855  3821  3821 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 12:05:17.855  3821  3821 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 12:05:17.855  3821  3821 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 12:05:17.855  3821  3821 I Adreno  : Build Date                       : 10/20/15
09-07 12:05:17.855  3821  3821 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 12:05:17.855  3821  3821 I Adreno  : Local Branch                     : M14
09-07 12:05:17.855  3821  3821 I Adreno  : Remote Branch                    : 
09-07 12:05:17.855  3821  3821 I Adreno  : Remote Branch                    : 
09-07 12:05:17.855  3821  3821 I Adreno  : Reconstruct Branch               : 
,09-07 12:05:17.911  3821  3821 I NSApplication: Starting up...
,09-07 12:05:17.921  3821  3867 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-07 12:05:17.963   874  1393 I ActivityManager: Start proc 3872:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-07 12:05:17.970   874  1393 I ActivityManager: Killing 3011:com.google.android.keep/u0a79 (adj 15): empty #17
,09-07 12:05:18.054  3872  3872 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-07 12:05:18.057  3759  3804 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-07 12:05:18.057  3759  3804 D bt_hwcfg: Settlement delay -- 100 ms
09-07 12:05:18.057  3759  3804 I bt_hwcfg: Setting fw settlement delay to 100 
,09-07 12:05:18.174  3759  3804 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-07 12:05:18.174  3759  3804 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-07 12:05:18.206  3759  3804 I bt_hwcfg: vendor lib fwcfg completed
09-07 12:05:18.207  3759  3804 I bt_vendor: firmware callback
09-07 12:05:18.207  3759  3804 I bt_hci  : firmware_config_callback
,09-07 12:05:18.230  3759  3885 I bt_btu  : btu_task pending for preload complete event
,09-07 12:05:18.231  3759  3885 I bt_btu_task: Bluetooth chip preload is complete
09-07 12:05:18.231  3759  3885 I bt_btu  : btu_task received preload complete event
,09-07 12:05:18.240  3759  3885 I         : BTE_InitTraceLevels -- TRC_HCI
09-07 12:05:18.240  3759  3885 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 12:05:18.241  3759  3885 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-07 12:05:18.241  3759  3885 I         : BTE_InitTraceLevels -- TRC_AVDT
09-07 12:05:18.241  3759  3885 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 12:05:18.241  3759  3885 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 12:05:18.242  3759  3885 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 12:05:18.242  3759  3885 I         : BTE_InitTraceLevels -- TRC_BTM
,09-07 12:05:18.243  3759  3885 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 12:05:18.243  3759  3885 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 12:05:18.243  3759  3885 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 12:05:18.243  3759  3885 I         : BTE_InitTraceLevels -- TRC_GATT
,09-07 12:05:18.243  3759  3885 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 12:05:18.244  3759  3885 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 12:05:18.244  3759  3885 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 12:05:18.245   874  1998 I ActivityManager: Killing 3390:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-07 12:05:18.306   874  1393 I ActivityManager: Start proc 3888:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-07 12:05:18.377  3759  3885 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39eed9d
,09-07 12:05:18.379  3759  3885 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39eed9d 
,09-07 12:05:18.404  3759  3786 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-07 12:05:18.406  3759  3786 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-07 12:05:18.407  3759  3786 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 12:05:18.409  3759  3786 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 12:05:18.413  3759  3786 D BluetoothAdapterProperties: Scan Mode:20
,09-07 12:05:18.414  3759  3786 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 12:05:18.415  3759  3786 D bt_hci  : do_postload posting postload work item
,09-07 12:05:18.415  3759  3804 I bt_hci  : event_postload
,09-07 12:05:18.415  3759  3804 I bt_vendor: sco_config_cb
09-07 12:05:18.415  3759  3804 I bt_hci  : sco_config_callback postload finished.
,09-07 12:05:18.420  3759  3804 I bt_vendor: low_power_mode_cb
,09-07 12:05:18.421  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:18.423  3759  3786 D bt_bte_conf: Device ID record 1 : primary
,09-07 12:05:18.423  3759  3786 D bt_bte_conf:   vendorId            = 000f
09-07 12:05:18.423  3759  3786 D bt_bte_conf:   vendorIdSource      = 0001
,09-07 12:05:18.423  3759  3786 D bt_bte_conf:   product             = 1200
09-07 12:05:18.423  3759  3786 D bt_bte_conf:   version             = 1436
09-07 12:05:18.424  3759  3786 D bt_bte_conf:   clientExecutableURL = 
,09-07 12:05:18.424  3759  3786 D bt_bte_conf:   serviceDescription  = 
09-07 12:05:18.424  3759  3786 D bt_bte_conf:   documentationURL    = 
,09-07 12:05:18.424  3759  3786 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-07 12:05:18.424  3759  3783 D bt_stack_manager: event_start_up_stack finished
09-07 12:05:18.425  3759  3781 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-07 12:05:18.425  3759  3781 D BluetoothAdapterProperties: Setting state to 15
09-07 12:05:18.425  3759  3781 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-07 12:05:18.425  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:18.425  3759  3781 I BluetoothAdapterState: Entering BleOnState
,09-07 12:05:18.427  3888  3888 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-07 12:05:18.431  3759  3781 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-07 12:05:18.431  3759  3781 D BluetoothAdapterProperties: Setting state to 11
,09-07 12:05:18.431  3759  3781 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-07 12:05:18.436  3759  3759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a754cd9
09-07 12:05:18.437  3759  3759 D HeadsetService: Received start request. Starting profile...
,09-07 12:05:18.444  3759  3759 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-07 12:05:18.444  3759  3759 D HeadsetStateMachine: make
,09-07 12:05:18.449  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:18.455  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:18.462  3759  3781 I BluetoothAdapterState: Entering PendingCommandState
,09-07 12:05:18.464  3759  3759 D HeadsetStateMachine: max_hf_connections = 1
,09-07 12:05:18.464  3759  3759 I bt_bluedroid: get_profile_interface handsfree
09-07 12:05:18.464  3759  3786 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-07 12:05:18.464  3759  3786 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-07 12:05:18.469  3759  3759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a754cd9
09-07 12:05:18.470   874   874 D BluetoothA2dp: Proxy object connected
,09-07 12:05:18.471  3759  3759 D A2dpService: Received start request. Starting profile...
09-07 12:05:18.471  3759  3759 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-07 12:05:18.472  3759  3759 I bt_bluedroid: get_profile_interface avrcp
,09-07 12:05:18.479  3759  3759 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-07 12:05:18.480  3759  3759 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 12:05:18.480  3759  3759 D A2dpStateMachine: make
,09-07 12:05:18.483  3759  3759 I bt_bluedroid: get_profile_interface a2dp
,09-07 12:05:18.484  3759  3786 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-07 12:05:18.485  3759  3916 D A2dpStateMachine: Enter Disconnected: -2
09-07 12:05:18.485  3759  3759 I BluetoothHidServiceJni: classInitNative: succeeds
09-07 12:05:18.489  3759  3759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a754cd9
09-07 12:05:18.490  3759  3759 D HidService: Received start request. Starting profile...
09-07 12:05:18.490  3759  3759 I bt_bluedroid: get_profile_interface hidhost
,09-07 12:05:18.490  3759  3759 D HidService: setHidService(): set to: null
09-07 12:05:18.491  3759  3759 I BluetoothHealthServiceJni: classInitNative: succeeds
09-07 12:05:18.492  3759  3786 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39d03e5
09-07 12:05:18.492  3759  3786 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-07 12:05:18.492  3759  3759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a754cd9
09-07 12:05:18.492  3759  3759 D HealthService: Received start request. Starting profile...
,09-07 12:05:18.492  3888  3888 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
09-07 12:05:18.494  3759  3759 I bt_bluedroid: get_profile_interface health
09-07 12:05:18.494  1368  1368 D BluetoothInputDevice: Proxy object connected
09-07 12:05:18.494  3759  3759 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-07 12:05:18.495  1368  1368 D HidProfile: Bluetooth service connected
09-07 12:05:18.495  3759  3759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a754cd9
09-07 12:05:18.496  3759  3759 D PanService: Received start request. Starting profile...
,09-07 12:05:18.496  3759  3759 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 12:05:18.497  3759  3759 I bt_bluedroid: get_profile_interface pan
09-07 12:05:18.497  3759  3786 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-07 12:05:18.497  1368  1368 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 12:05:18.498  1368  1368 D PanProfile: Bluetooth service connected
09-07 12:05:18.504  3759  3759 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a754cd9
09-07 12:05:18.509   874  2020 I ActivityManager: Start proc 3922:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,09-07 12:05:18.509   874  2020 I ActivityManager: Killing 1702:android.process.acore/u0a5 (adj 15): empty #17
,09-07 12:05:18.553  1368  1368 D BluetoothMap: Proxy object connected
,09-07 12:05:18.553  3759  3759 D BluetoothMapService: Received start request. Starting profile...
09-07 12:05:18.554  3759  3759 D BluetoothMapService: start()
09-07 12:05:18.554  1368  1368 D MapProfile: Bluetooth service connected
09-07 12:05:18.554  1368  1368 D BluetoothMap: getConnectedDevices()
,09-07 12:05:18.555  1368  1368 D BluetoothMap: Bluetooth is Not enabled
,09-07 12:05:18.560  3759  3759 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-07 12:05:18.561  3759  3759 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-07 12:05:18.561  3759  3759 D BluetoothMapAppObserver: createReceiver()
09-07 12:05:18.562  3759  3759 D BluetoothMapAppObserver: initObservers()
09-07 12:05:18.562  3759  3759 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-07 12:05:18.567  3922  3922 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltKeep/lib/arm
,09-07 12:05:18.569  3759  3759 V BluetoothAdapterState: isTurningOff()=false
09-07 12:05:18.569  3759  3759 V BluetoothAdapterState: isTurningOn()=true
,09-07 12:05:18.569  3759  3759 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:05:18.569  3759  3759 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 12:05:18.571  3759  3759 V BluetoothAdapterState: isTurningOff()=false
09-07 12:05:18.571  3759  3759 V BluetoothAdapterState: isTurningOn()=true
09-07 12:05:18.571  3759  3759 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 12:05:18.571  3759  3759 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:05:18.572  3759  3905 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 12:05:18.572  3759  3759 V BluetoothAdapterState: isTurningOff()=false
09-07 12:05:18.572  3759  3759 V BluetoothAdapterState: isTurningOn()=true
09-07 12:05:18.572  3759  3759 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:05:18.572  3759  3759 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:05:18.572  3759  3759 V BluetoothAdapterState: isTurningOff()=false
09-07 12:05:18.572  3759  3759 V BluetoothAdapterState: isTurningOn()=true
09-07 12:05:18.573  3759  3759 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 12:05:18.573  3759  3759 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:05:18.573  3759  3759 V BluetoothAdapterState: isTurningOff()=false
09-07 12:05:18.573  3759  3759 V BluetoothAdapterState: isTurningOn()=true
09-07 12:05:18.573  3759  3759 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:05:18.573  3759  3759 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:05:18.573  3759  3759 V BluetoothAdapterState: isTurningOff()=false
09-07 12:05:18.574  3759  3759 V BluetoothAdapterState: isTurningOn()=true
09-07 12:05:18.574  3759  3759 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 12:05:18.574  3759  3759 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:05:18.574  3759  3781 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-07 12:05:18.575  3759  3781 D BluetoothAdapterProperties: ScanMode =  20
09-07 12:05:18.575  3759  3781 D BluetoothAdapterProperties: State =  11
,09-07 12:05:18.575  3759  3781 D BluetoothAdapterProperties: Setting state to 12
,09-07 12:05:18.576  3759  3781 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-07 12:05:18.576  3759  3781 I BluetoothAdapterState: Entering OnState
,09-07 12:05:18.576  1368  1384 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 12:05:18.576  3759  3786 D BluetoothAdapterProperties: Scan Mode:21
,09-07 12:05:18.577  3759  3786 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 12:05:18.578  1368  1390 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 12:05:18.578  1368  2054 D BluetoothPan: onBluetoothStateChange on: true
,09-07 12:05:18.579   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 12:05:18.579  3693  3693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-07 12:05:18.579  1368  2069 D BluetoothMap: onBluetoothStateChange: up=true
09-07 12:05:18.580   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 12:05:18.580  1973  1986 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 12:05:18.581   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 12:05:18.581   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 12:05:18.582   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-07 12:05:18.583  3759  3759 D BluetoothMapService: onReceive
09-07 12:05:18.583  3759  3759 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:05:18.583  3759  3759 D BluetoothMapService: STATE_ON
,09-07 12:05:18.586  3693  3693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-07 12:05:18.588  3759  3759 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-07 12:05:18.588  1368  1666 D LocalBluetoothProfileManager: Adding local A2DP profile
09-07 12:05:18.589  3759  3759 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-07 12:05:18.590  3693  3693 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-07 12:05:18.590  3759  3759 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 12:05:18.592  3759  3759 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 12:05:18.593  3759  3759 D ObexServerSockets: Succeed to create listening sockets 
09-07 12:05:18.593  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:18.593  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:18.593  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:18.593  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:18.593  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:18.593  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:18.593  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:18.593  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:05:18.594  3759  3759 D ObexServerSockets0: startAccept()
09-07 12:05:18.594  3759  3759 D ObexServerSockets0: prepareForNewConnect()
,09-07 12:05:18.595  3759  3759 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-07 12:05:18.595  3759  3759 D BluetoothSdpJni: SDP Create record success - handle: 0
09-07 12:05:18.595  3759  3936 D ObexServerSockets0: Accepting socket connection...
09-07 12:05:18.596  3759  3937 D ObexServerSockets0: Accepting socket connection...
09-07 12:05:18.597  3693  3693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:05:18.600  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:18.600  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:18.600  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:18.600  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:18.600  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:18.600  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:18.600  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:18.600  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:05:18.601  1368  1368 D BluetoothA2dp: Proxy object connected
,09-07 12:05:18.601  1368  1666 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-07 12:05:18.603  3693  3693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:05:18.604  3759  3759 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-07 12:05:18.604  3759  3759 D ObexServerSockets0: prepareForNewConnect()
,09-07 12:05:18.605  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:18.606  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:18.680   874   891 D BluetoothHeadset: Proxy object connected
,09-07 12:05:18.680   874   891 D BluetoothHeadset: Proxy object connected
,09-07 12:05:18.682  1973  1985 D BluetoothHeadset: Proxy object connected
,09-07 12:05:18.682   874   891 D BluetoothHeadset: Proxy object connected
,09-07 12:05:18.685   874   884 I ActivityManager: Start proc 3943:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-07 12:05:18.704  1368  2054 D BluetoothHeadset: Proxy object connected
,09-07 12:05:18.710  1368  1368 D HeadsetProfile: Bluetooth service connected
,09-07 12:05:18.735  3943  3943 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-07 12:05:18.753  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 12:05:18.756   874  1974 I ActivityManager: Killing 3543:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-07 12:05:18.816   874  1974 I ActivityManager: Start proc 3959:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-07 12:05:18.892  3959  3959 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-07 12:05:19.024  3959  3959 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 12:05:19.024  3959  3959 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 12:05:19.024  3959  3959 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 12:05:19.024  3959  3959 D StrictMode: ,	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 12:05:19.024  3959  3959 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrument,ation.java:1013)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 12:05:19.024  3959  3959 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.r.k.d(PG:583)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.Activity,Thread.main(ActivityThread.java:5417)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 12:05:19.024  3959  3959 D StrictMode: StrictMode policy violation; ~duration=54 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 12:05:19.024  3959  3959 D StrictMode: StrictMode policy violation; ~duration=54 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 12:05:19.024  3959  3959 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 12:05:19.025  3959  3959 D StrictMode: StrictMode policy violation; ~duration=53 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 12:05:19.025  3959  3959 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 12:05:19.025  3959  3959 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-07 12:05:19.025  3959  3959 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-07 12:05:19.025  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-07 12:05:19.025  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:19.025  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 12:05:19.025  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:19.025  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:19.025  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 12:05:19.025  3959  3959 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 12:05:19.025  3959  3959 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 12:05:19.025  3959  3959 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 12:05:19.025  3959  3959 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 12:05:19.025  3959  3959 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 12:05:19.025  3959  3959 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:19.025  3959  3959 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:05:19.025  3959  3959 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 12:05:19.025  3959  3959 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:05:19.025  3959  3959 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 12:05:19.025  3959  3959 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 12:05:19.045  3943  3943 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 12:05:19.052   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bbdd8e0:true
09-07 12:05:19.057  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 12:05:19.074  3943  3943 D LocalBluetoothProfileManager: Adding local A2DP profile
09-07 12:05:19.078  3943  3943 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-07 12:05:19.085  3943  3943 D LocalBluetoothProfileManager: Adding local MAP profile
09-07 12:05:19.086  3943  3943 D BluetoothMap: Create BluetoothMap proxy object
09-07 12:05:19.089  1368  1368 D BluetoothPbap: Proxy object connected
09-07 12:05:19.089  1368  1368 D PbapServerProfile: Bluetooth service connected
09-07 12:05:19.094  3943  3943 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
09-07 12:05:19.098  3943  3943 D DockEventReceiver: finishStartingService: stopping service
09-07 12:05:19.100  3943  3943 D BluetoothA2dp: Proxy object connected
,09-07 12:05:19.104  3943  3943 D BluetoothInputDevice: Proxy object connected
,09-07 12:05:19.106  3759  3993 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 12:05:19.109  3943  3943 D HidProfile: Bluetooth service connected
,09-07 12:05:19.111  3943  3943 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 12:05:19.112  3943  3943 D PanProfile: Bluetooth service connected
09-07 12:05:19.112  3943  3943 D BluetoothMap: Proxy object connected
09-07 12:05:19.112  3943  3943 D MapProfile: Bluetooth service connected
,09-07 12:05:19.112  3943  3943 D BluetoothMap: getConnectedDevices()
,09-07 12:05:19.114  3943  3943 D BluetoothPbap: Proxy object connected
,09-07 12:05:19.115  3943  3943 D PbapServerProfile: Bluetooth service connected
,09-07 12:05:19.117   874   884 I ActivityManager: Killing 3558:com.android.musicfx/u0a18 (adj 15): empty #17
,09-07 12:05:19.161  3759  3998 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 12:05:19.164  3759  3998 I BtOppRfcommListener: Accept thread started.
,09-07 12:05:19.181  3943  3954 D BluetoothHeadset: Proxy object connected
,09-07 12:05:19.182  3943  3943 D HeadsetProfile: Bluetooth service connected
,09-07 12:05:19.246  3959  3983 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-07 12:05:19.270   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c074740:true
,09-07 12:05:20.138   874   884 D WifiService: setWifiEnabled: true pid=3693, uid=10000
09-07 12:05:20.139   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 12:05:20.151   874  1315 D WifiConfigStore: Loading config and enabling all networks 
,09-07 12:05:20.171  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:20.171  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:20.171  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:20.171  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:20.171  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:20.171  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:20.171  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:20.171  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:05:20.175  3693  3693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:05:20.182  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:20.182  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:20.182  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:20.182  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:20.182  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:20.182  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:20.182  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:20.182  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:05:20.185   874  1315 D WifiConfigStore: loaded 0 passpoint configs
09-07 12:05:20.186   874  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-07 12:05:20.187  3693  3693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:05:20.187   874  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-07 12:05:20.188   874  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-07 12:05:20.189   874  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-07 12:05:20.189   874  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-07 12:05:20.189   874  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-07 12:05:20.205   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-07 12:05:20.206   874  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.62 rxSuccessRate=6.62 delta 1000 -> 994
09-07 12:05:20.206   373   872 D CommandListener: Setting iface cfg
09-07 12:05:20.207   874  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-07 12:05:20.207   874  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-07 12:05:20.210   874  1314 D WifiNative-HAL: p2pGetDeviceAddress
,09-07 12:05:20.214   874  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-07 12:05:20.216   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-07 12:05:20.216   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 12:05:20.222   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-07 12:05:20.299   874  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-07 12:05:20.304  1475  1475 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 12:05:20.740  1475  1475 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 12:05:20.810  1475  1475 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 12:05:20.812  1475  1475 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-07 12:05:20.818   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 12:05:20.834   874  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 12:05:20.835   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-07 12:05:20.836   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 12:05:20.860   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 12:05:20.882   373   872 D CommandListener: Setting iface cfg,
09-07 12:05:20.884   874  1315 D WifiStateMachine: Start Dhcp Watchdog 2
,09-07 12:05:20.901   874  1319 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-07 12:05:20.904   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-07 12:05:20.940   874  4009 D DhcpClient: Receive thread started
,09-07 12:05:21.022   874  1315 E native  : do suspend false
,09-07 12:05:21.042   874  1884 D DhcpClient: Broadcasting DHCPDISCOVER
,09-07 12:05:21.059   874  4009 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172693, domain null
,09-07 12:05:21.060   874  1884 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172693 seconds
,09-07 12:05:21.064   874  1884 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-07 12:05:21.092   874  4009 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-07 12:05:21.094   874  1884 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-07 12:05:21.100   373   872 D CommandListener: Setting iface cfg
,09-07 12:05:21.111   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-07 12:05:21.116   874  1884 D DhcpClient: Scheduling renewal in 86399s
,09-07 12:05:21.128   874  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-07 12:05:21.133   874  1319 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 12:05:21.133   874  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,09-07 12:05:21.135   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-07 12:05:21.138   874  1319 D ConnectivityService: Adding iface wlan0 to network 101
,09-07 12:05:21.143   874  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 12:05:21.193   874  1319 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-07 12:05:21.193   874  1319 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-07 12:05:21.196   874  1319 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-07 12:05:21.197   874  1319 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-07 12:05:21.197   874  1319 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-07 12:05:21.207   874  1319 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 12:05:21.213   874  1319 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-07 12:05:21.213   874  1319 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-07 12:05:21.214   874  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-07 12:05:21.214   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 12:05:21.214   874  1319 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-07 12:05:21.214   874  1319 D ConnectivityService:    accepting network in place of null
,09-07 12:05:21.216   874  1319 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 12:05:21.253   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 12:05:21.303   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 12:05:21.312   874  1319 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-07 12:05:21.312   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:05:21.318   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-07 12:05:21.322   874  1319 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-07 12:05:21.343  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:21.343  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:21.343  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:21.343  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:21.343  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:21.343  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:05:21.343  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:05:21.343  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 12:05:21.345  3693  3693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 12:05:21.350  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:21.350  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:21.350  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:21.350  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:21.350  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:21.350  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:05:21.350  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:05:21.350  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 12:05:21.351  1729  1729 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 12:05:21.353  3693  3693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 12:05:21.354  1729  1729 D SystemUpdateService: onCreate
,09-07 12:05:21.358  1729  1729 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 12:05:21.360  1729  4019 I SystemUpdateService: active receiver: enabled
,09-07 12:05:21.364  1729  4019 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 12:05:21.366  1729  4019 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-07 12:05:21.366  1729  4019 I SystemUpdateService: now status is 0 (complete)
09-07 12:05:21.366  1729  4019 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 12:05:21.366  1729  4019 I SystemUpdateService: file has been verified
09-07 12:05:21.366  1729  4019 I SystemUpdateService: OTA package size = 12249756
,09-07 12:05:21.374  1729  4019 I SystemUpdateService: showing system update notification
,09-07 12:05:21.377  1729  1729 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-07 12:05:21.379  1729  2478 I iu.UploadsManager: num queued entries: 0
,09-07 12:05:21.379  1729  2478 I iu.UploadsManager: num updated entries: 0
,09-07 12:05:21.380  1729  2478 I iu.SyncManager: NEXT; no task
,09-07 12:05:21.384  1729  1729 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 12:05:21.385  1729  1729 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 12:05:21.387  3787  3787 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:05:21.390  1729  4023 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-07 12:05:21.390  1729  4023 W BaseAppContext: Using Auth Proxy for data requests.
09-07 12:05:21.391  1729  1729 D SystemUpdateService: onDestroy
09-07 12:05:21.391  1729  4023 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 12:05:21.392  3787  3787 D SprintDMHelper: simOperator: 
09-07 12:05:21.392  3787  3787 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 12:05:21.398  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:05:21.399  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:05:21.435  1528  2055 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-07 12:05:21.435  1528  2055 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-07 12:05:21.435  1528  2055 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:05:21.435  1528  2055 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:05:21.449  1729  4023 E MDM     : [178] SitrepService.a: Error sending sitrep.
,09-07 12:05:22.312   874  1319 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-07 12:05:22.479   874  4008 D NetlinkSocketObserver: NeighborEvent{elapsedMs=131100, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 12:05:23.144   874  1716 D WifiService: setWifiEnabled: false pid=3693, uid=10000
,09-07 12:05:23.145   874  1716 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 12:05:23.162  1475  1475 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-07 12:05:23.165   874  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-07 12:05:23.166   874  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-07 12:05:23.166   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-07 12:05:23.166   874  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 12:05:23.185   874  1884 D DhcpClient: Clearing IP address
,09-07 12:05:23.186   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-07 12:05:23.189   373   872 D CommandListener: Setting iface cfg
,09-07 12:05:23.201   874  4009 D DhcpClient: Receive thread stopped
,09-07 12:05:23.201   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 12:05:23.201   874  1319 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-07 12:05:23.208   396   396 E Parcel  : Reading a NULL string not supported here.
09-07 12:05:23.208   874  1319 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-07 12:05:23.208   874  1315 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-07 12:05:23.212   874  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-07 12:05:23.255   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 12:05:23.281   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 12:05:23.282   373   872 D CommandListener: Clearing all IP addresses on wlan0
09-07 12:05:23.283   874  1319 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-07 12:05:23.283   874  1319 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:05:23.286   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-07 12:05:23.303  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:23.303  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:23.303  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:23.303  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:23.303  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:23.303  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:23.303  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:23.303  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:05:23.306  3693  3693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:05:23.309  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:23.309  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:23.309  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:23.309  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:23.309  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:23.309  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:23.309  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:23.309  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:05:23.309   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 12:05:23.311  3693  3693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:05:23.312  1909  2315 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 12:05:23.313   874  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-07 12:05:23.314  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:23.314  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:23.314  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:23.314  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:23.314  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:23.314  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:23.314  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:23.314  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:05:23.316  3693  3693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:05:23.317  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:23.320  1729  1729 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 12:05:23.323  1729  1729 D SystemUpdateService: onCreate
,09-07 12:05:23.327  1729  1729 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 12:05:23.334  1729  4036 I SystemUpdateService: active receiver: enabled
,09-07 12:05:23.338  1729  1729 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-07 12:05:23.340  1729  4036 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 12:05:23.341  1729  4036 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-07 12:05:23.342  1729  4036 I SystemUpdateService: now status is 0 (complete)
,09-07 12:05:23.342  1729  1729 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-07 12:05:23.343  1729  4036 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 12:05:23.343  1729  4036 I SystemUpdateService: file has been verified
09-07 12:05:23.343  1729  4036 I SystemUpdateService: OTA package size = 12249756
,09-07 12:05:23.344  1729  1729 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-07 12:05:23.342  1729  2478 I iu.UploadsManager: num queued entries: 0
,09-07 12:05:23.344  1729  2478 I iu.UploadsManager: num updated entries: 0
,09-07 12:05:23.346  1729  2478 I iu.SyncManager: NEXT; no task
,09-07 12:05:23.347  1729  4036 I SystemUpdateService: showing system update notification
,09-07 12:05:23.350  3787  3787 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:05:23.355  1729  1729 D SystemUpdateService: onDestroy
,09-07 12:05:23.358  3787  3787 D SprintDMHelper: simOperator: 
09-07 12:05:23.358  3787  3787 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 12:05:23.386   373   872 E Netd    : netlink response contains error (No such file or directory)
,09-07 12:05:23.387   874  1319 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-07 12:05:23.636  3922  3929 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (com.google.android.gms.reminders.model.RemindersBuffer@de63847)
,09-07 12:05:26.159  3759  3781 D BluetoothAdapterState: Current state: ON, message: 23
,09-07 12:05:26.160  3759  3781 D BluetoothAdapterProperties: Setting state to 13
09-07 12:05:26.160  3759  3781 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-07 12:05:26.162  3759  3781 D BluetoothAdapterProperties: onBluetoothDisable()
,09-07 12:05:26.165  3759  3781 I BluetoothAdapterState: Entering PendingCommandState
,09-07 12:05:26.173  3759  3759 D BluetoothMapService: onReceive
,09-07 12:05:26.174  3759  3759 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-07 12:05:26.174  3759  3759 D BluetoothMapService: STATE_TURNING_OFF
09-07 12:05:26.178  3759  3786 D BluetoothAdapterProperties: Scan Mode:20
09-07 12:05:26.179  3759  3781 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-07 12:05:26.186  3759  3759 D BluetoothMapService: MAP Service closeService in
09-07 12:05:26.186  3759  3759 D BluetoothMapMasInstance0: MAP Service shutdown
09-07 12:05:26.186  3759  3759 D ObexServerSockets0: shutdown(block = true)
09-07 12:05:26.187  3759  3936 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-07 12:05:26.187  3693  3693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:05:26.188  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:26.188  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:26.188  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:26.188  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:26.188  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:26.188  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:26.188  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:26.188  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:05:26.190  3693  3693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:05:26.191  3693  3693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:05:26.191  3759  3759 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-07 12:05:26.191  3759  3937 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-07 12:05:26.192  3759  3900 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-07 12:05:26.192  3759  3759 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-07 12:05:26.192  3759  3759 I BtOppRfcommListener: stopping Accept Thread
09-07 12:05:26.193  3759  3998 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 12:05:26.193  3759  3998 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 12:05:26.194  3693  3693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:05:26.194  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:26.194  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:26.194  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:26.194  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:26.194  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:26.194  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:26.194  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:26.194  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:05:26.195  3693  3693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:26.195  3693  3693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:05:26.195  3759  3759 D HeadsetService: Received stop request...Stopping profile...
09-07 12:05:26.198  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:26.199  1973  2095 D BluetoothHeadset: Proxy object disconnected
09-07 12:05:26.199   874   874 D BluetoothHeadset: Proxy object disconnected
,09-07 12:05:26.199  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:26.199  1368  1384 D BluetoothHeadset: Proxy object disconnected
09-07 12:05:26.200   874   874 D BluetoothHeadset: Proxy object disconnected
,09-07 12:05:26.200  3759  3759 D A2dpService: Received stop request...Stopping profile...
,09-07 12:05:26.200   874   874 D BluetoothHeadset: Proxy object disconnected
09-07 12:05:26.200  3759  3916 D A2dpStateMachine: Exit Disconnected: -1
,09-07 12:05:26.201  3943  3955 D BluetoothHeadset: Proxy object disconnected
,09-07 12:05:26.202  1368  1368 D HeadsetProfile: Bluetooth service disconnected
,09-07 12:05:26.203  1368  1368 D BluetoothA2dp: Proxy object disconnected
,09-07 12:05:26.203  3759  3759 D HidService: Received stop request...Stopping profile...
,09-07 12:05:26.203  3759  3759 D HidService: Stopping Bluetooth HidService
09-07 12:05:26.204   874   874 D BluetoothA2dp: Proxy object disconnected,
,09-07 12:05:26.204  1368  1368 D BluetoothInputDevice: Proxy object disconnected
,09-07 12:05:26.205  1368  1368 D HidProfile: Bluetooth service disconnected
09-07 12:05:26.205  3759  3759 D HealthService: Received stop request...Stopping profile...
09-07 12:05:26.208  3759  3759 D PanService: Received stop request...Stopping profile...
,09-07 12:05:26.209  1368  1368 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 12:05:26.209  1368  1368 D PanProfile: Bluetooth service disconnected
,09-07 12:05:26.210  3943  3943 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 12:05:26.212  3943  3943 D HeadsetProfile: Bluetooth service disconnected
09-07 12:05:26.212  3943  3943 D BluetoothA2dp: Proxy object disconnected
,09-07 12:05:26.212  3759  3759 D BluetoothMapService: Received stop request...Stopping profile...
09-07 12:05:26.212  3759  3759 D BluetoothMapService: stop()
,09-07 12:05:26.212  3943  3943 D BluetoothInputDevice: Proxy object disconnected
09-07 12:05:26.213  3943  3943 D HidProfile: Bluetooth service disconnected
,09-07 12:05:26.213  3943  3943 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 12:05:26.213  3943  3943 D PanProfile: Bluetooth service disconnected
09-07 12:05:26.214  3759  3759 D BluetoothMapAppObserver: deinitObservers()
09-07 12:05:26.214  3759  3759 D BluetoothMapAppObserver: removeReceiver()
,09-07 12:05:26.215  1368  1368 D BluetoothMap: Proxy object disconnected
09-07 12:05:26.215  1368  1368 D MapProfile: Bluetooth service disconnected
09-07 12:05:26.215  3759  3759 V BluetoothAdapterState: isTurningOff()=true
,09-07 12:05:26.215  3759  3759 V BluetoothAdapterState: isTurningOn()=false
09-07 12:05:26.215  3759  3759 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:05:26.216  3759  3759 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 12:05:26.216  3943  3943 D DockEventReceiver: finishStartingService: stopping service
09-07 12:05:26.217  3759  3759 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 12:05:26.217  3759  3759 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-07 12:05:26.217  3759  3759 V BluetoothAdapterState: isTurningOff()=true
09-07 12:05:26.217  3759  3759 V BluetoothAdapterState: isTurningOn()=false
,09-07 12:05:26.217  3759  3759 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:05:26.217  3759  3759 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:05:26.218  3759  3885 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 12:05:26.218  3759  3885 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 12:05:26.218  3943  3943 D BluetoothMap: Proxy object disconnected
,09-07 12:05:26.218  3759  3885 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 12:05:26.218  3759  3786 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-07 12:05:26.218  3759  3786 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-07 12:05:26.219  3943  3943 D MapProfile: Bluetooth service disconnected,
09-07 12:05:26.220  3759  3759 V BluetoothAdapterState: isTurningOff()=true
09-07 12:05:26.220  3759  3759 V BluetoothAdapterState: isTurningOn()=false
09-07 12:05:26.220  3759  3759 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 12:05:26.220  3759  3759 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:05:26.220  3759  3759 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-07 12:05:26.220  3759  3759 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 12:05:26.221  3759  3759 V BluetoothAdapterState: isTurningOff()=true
09-07 12:05:26.221  3759  3759 V BluetoothAdapterState: isTurningOn()=false
09-07 12:05:26.221  3759  3759 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 12:05:26.221  3759  3759 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:05:26.221  3759  3759 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 12:05:26.221  3759  3885 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 12:05:26.221  3759  3885 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 12:05:26.221  3759  3885 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 12:05:26.221  3759  3759 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 12:05:26.221  3759  3885 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 12:05:26.222  3759  3885 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-07 12:05:26.222  3759  3786 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 12:05:26.222  3759  3885 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 12:05:26.222  3759  3759 V BluetoothAdapterState: isTurningOff()=true
09-07 12:05:26.222  3759  3786 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-07 12:05:26.222  3759  3759 V BluetoothAdapterState: isTurningOn()=false
09-07 12:05:26.222  3759  3759 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 12:05:26.222  3759  3786 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-07 12:05:26.222  3759  3759 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:05:26.222  3759  3759 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 12:05:26.222  3759  3759 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object,
09-07 12:05:26.224   874  4007 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-07 12:05:26.225   874  1319 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-07 12:05:26.226  3759  3759 D BluetoothMapService: MAP Service closeService in
,09-07 12:05:26.226  3759  3759 V BluetoothAdapterState: isTurningOff()=true
09-07 12:05:26.226  3759  3759 V BluetoothAdapterState: isTurningOn()=false
09-07 12:05:26.226  3759  3759 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 12:05:26.226  3759  3759 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:05:26.227  3759  3781 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-07 12:05:26.227  3759  3781 D BluetoothAdapterProperties: Setting state to 15
,09-07 12:05:26.227  3759  3781 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-07 12:05:26.227  3759  3759 D BluetoothMapService: cleanup()
09-07 12:05:26.227  3759  3759 D BluetoothMapService: MAP Service closeService in
09-07 12:05:26.228  3759  3781 I BluetoothAdapterState: Entering BleOnState
09-07 12:05:26.228  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 12:05:26.228  1368  1390 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 12:05:26.229  3943  3943 D BluetoothPbap: Proxy object disconnected
09-07 12:05:26.229  3943  3943 D PbapServerProfile: Bluetooth service disconnected
,09-07 12:05:26.230  1368  2054 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 12:05:26.231  1368  2069 D BluetoothPan: onBluetoothStateChange on: false
09-07 12:05:26.233   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 12:05:26.233  3943  4044 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 12:05:26.234  1368  1384 D BluetoothMap: onBluetoothStateChange: up=false
,09-07 12:05:26.238  3943  3954 D BluetoothPbap: onBluetoothStateChange: up=false
,09-07 12:05:26.241  3943  3955 D BluetoothPan: onBluetoothStateChange on: false
,09-07 12:05:26.242  3943  4044 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-07 12:05:26.242   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-07 12:05:26.242  1973  1986 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 12:05:26.243  3943  3954 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 12:05:26.243  1368  1390 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 12:05:26.243   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 12:05:26.243   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false,
09-07 12:05:26.243  1368  2054 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 12:05:26.244  3943  3955 D BluetoothMap: onBluetoothStateChange: up=false
09-07 12:05:26.244  3759  3781 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-07 12:05:26.245  3759  3781 D BluetoothAdapterProperties: Setting state to 16
09-07 12:05:26.245  3759  3781 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-07 12:05:26.245  3759  3781 D BluetoothAdapterProperties: onBleDisable
09-07 12:05:26.246  3759  3781 I BluetoothAdapterState: Entering PendingCommandState
09-07 12:05:26.246  3759  3783 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-07 12:05:26.247  3759  3786 D BluetoothAdapterProperties: Scan Mode:20
,09-07 12:05:26.247  3759  3885 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-07 12:05:26.247  3759  3885 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 12:05:26.248  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:26.250  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:26.250  3943  3943 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 12:05:26.254  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:26.255  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:26.260  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 12:05:26.264  3943  3943 D DockEventReceiver: finishStartingService: stopping service
,09-07 12:05:26.431  2298  4025 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,09-07 12:05:26.431  2298  4025 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-07 12:05:26.435  2298  4025 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-07 12:05:26.443   874  1716 I ActivityManager: Killing 2155:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-07 12:05:26.449  3759  3786 I bt_hci  : shut_down
,09-07 12:05:26.450  3759  3804 D bt_hwcfg: hw_epilog_process
,09-07 12:05:26.546  3759  3804 I bt_vendor: low_power_mode_cb
,09-07 12:05:26.562  3759  3804 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-07 12:05:26.562  3759  3804 I bt_vendor: epilog_cb
,09-07 12:05:26.563  3759  3804 I bt_hci  : epilog_finished_callback
09-07 12:05:26.566  3759  3786 I bt_hci_h4: hal_close
09-07 12:05:26.567  3759  3786 I bt_userial_vendor: device fd = 51 close
,09-07 12:05:26.683  3759  3783 D bt_stack_manager: event_shut_down_stack finished.
09-07 12:05:26.684  3759  3781 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-07 12:05:26.691  3759  3759 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 12:05:26.692  3759  3781 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-07 12:05:26.692  3759  3759 D BtGatt.GattService: Received stop request...Stopping profile...
09-07 12:05:26.693  3759  3759 D BtGatt.GattService: stop()
,09-07 12:05:26.693  3759  3759 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 12:05:26.698  3759  3759 V BluetoothAdapterState: isTurningOff()=false
,09-07 12:05:26.699  3759  3759 V BluetoothAdapterState: isTurningOn()=false
09-07 12:05:26.699  3759  3759 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:05:26.699  3759  3759 V BluetoothAdapterState: isBleTurningOff()=true
09-07 12:05:26.700  3759  3781 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-07 12:05:26.701  3759  3781 D BluetoothAdapterProperties: Setting state to 10
,09-07 12:05:26.701  3759  3781 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-07 12:05:26.703  3759  3781 I BluetoothAdapterState: Entering OffState
09-07 12:05:26.706   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-07 12:05:26.732  3759  3759 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-07 12:05:26.732  3759  3759 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-07 12:05:26.733  3759  3783 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-07 12:05:26.740  3759  3783 D bt_stack_manager: event_clean_up_stack finished.
,09-07 12:05:26.740  3759  3759 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-07 12:05:26.746  3759  3759 I art     : System.exit called, status: 0
,09-07 12:05:26.746  3759  3759 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-07 12:05:26.805   874  2222 I ActivityManager: Process com.android.bluetooth (pid 3759) has died
,09-07 12:05:29.203   874   891 I ActivityManager: Start proc 4050:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-07 12:05:29.217   874  1319 D ConnectivityService: handlePromptUnvalidated 101
,09-07 12:05:29.354  4050  4050 D AdapterServiceConfig: Adding HeadsetService
,09-07 12:05:29.354  4050  4050 D AdapterServiceConfig: Adding A2dpService
,09-07 12:05:29.355  4050  4050 D AdapterServiceConfig: Adding HidService
,09-07 12:05:29.356  4050  4050 D AdapterServiceConfig: Adding HealthService
09-07 12:05:29.357  4050  4050 D AdapterServiceConfig: Adding PanService
09-07 12:05:29.358  4050  4050 D AdapterServiceConfig: Adding GattService
,09-07 12:05:29.359  4050  4050 D AdapterServiceConfig: Adding BluetoothMapService
,09-07 12:05:29.373   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@af0250b:true
,09-07 12:05:29.374  4050  4050 D BluetoothAdapterState: make() - Creating AdapterState
,09-07 12:05:29.379  4050  4062 I BluetoothAdapterState: Entering OffState
,09-07 12:05:29.379  4050  4050 I bt_bluedroid: init
,09-07 12:05:29.382  4050  4063 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-07 12:05:29.382  4050  4063 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-07 12:05:29.382  4050  4063 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 12:05:29.382  4050  4063 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-07 12:05:29.383  4050  4050 I bt_bluedroid: get_profile_interface socket
,09-07 12:05:29.384  4050  4066 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 12:05:29.385  4050  4066 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 12:05:29.386  4050  4050 I bt_bluedroid: get_profile_interface sdp
,09-07 12:05:29.388  4050  4061 I bt_bluedroid: config_hci_snoop_log
,09-07 12:05:29.389   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-07 12:05:29.393  4050  4062 D BluetoothAdapterState: Current state: OFF, message: 0
,09-07 12:05:29.393  4050  4062 D BluetoothAdapterProperties: Setting state to 14
09-07 12:05:29.393  4050  4062 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-07 12:05:29.395  4050  4062 D BluetoothBondStateMachine: make
,09-07 12:05:29.398  4050  4067 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-07 12:05:29.401  4050  4062 I BluetoothAdapterState: Entering PendingCommandState
,09-07 12:05:29.404  4050  4050 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-07 12:05:29.411  4050  4050 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a754cd9
,09-07 12:05:29.413  4050  4050 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 12:05:29.414  4050  4050 D BtGatt.GattService: Received start request. Starting profile...
,09-07 12:05:29.414  4050  4050 D BtGatt.GattService: start()
09-07 12:05:29.415  4050  4050 I bt_bluedroid: get_profile_interface gatt
,09-07 12:05:29.416  4050  4050 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a754cd9
,09-07 12:05:29.417  4050  4050 D BtGatt.AdvertiseManager: advertise manager created
,09-07 12:05:29.427  4050  4050 V BluetoothAdapterState: isTurningOff()=false
,09-07 12:05:29.427  4050  4050 V BluetoothAdapterState: isTurningOn()=false
,09-07 12:05:29.427  4050  4050 V BluetoothAdapterState: isBleTurningOn()=true
,09-07 12:05:29.427  4050  4050 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 12:05:29.428  4050  4062 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-07 12:05:29.428  4050  4062 I bt_bluedroid: enable
,09-07 12:05:29.428  4050  4063 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-07 12:05:29.429  4050  4063 I bt_hci  : start_up
,09-07 12:05:29.445  4050  4063 I bt_vendor: alloc value 0xb3a71189
09-07 12:05:29.445  4050  4063 I bt_vendor: init
,09-07 12:05:29.445  4050  4063 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-07 12:05:29.446  4050  4063 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-07 12:05:29.554  4050  4063 D bt_hci  : start_up starting async portion
,09-07 12:05:29.554  4050  4070 I bt_hci  : event_finish_startup
09-07 12:05:29.554  4050  4070 I bt_hci_h4: hal_open
09-07 12:05:29.555  4050  4070 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-07 12:05:29.561  4050  4070 I bt_userial_vendor: device fd = 51 open
,09-07 12:05:29.595  4050  4070 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 12:05:29.627  4050  4070 D bt_hwcfg: Chipset BCM4354A2
,09-07 12:05:29.628  4050  4070 D bt_hwcfg: Target name = [BCM4354A2]
09-07 12:05:29.629  4050  4070 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-07 12:05:30.299  4050  4070 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-07 12:05:30.300  4050  4070 D bt_hwcfg: Settlement delay -- 100 ms
,09-07 12:05:30.301  4050  4070 I bt_hwcfg: Setting fw settlement delay to 100 
,09-07 12:05:30.419  4050  4070 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 12:05:30.420  4050  4070 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-07 12:05:30.448  4050  4070 I bt_hwcfg: vendor lib fwcfg completed
,09-07 12:05:30.449  4050  4070 I bt_vendor: firmware callback
,09-07 12:05:30.449  4050  4070 I bt_hci  : firmware_config_callback
,09-07 12:05:30.462  4050  4072 I bt_btu  : btu_task pending for preload complete event
,09-07 12:05:30.463  4050  4072 I bt_btu_task: Bluetooth chip preload is complete
09-07 12:05:30.463  4050  4072 I bt_btu  : btu_task received preload complete event
,09-07 12:05:30.474  4050  4072 I         : BTE_InitTraceLevels -- TRC_HCI
,09-07 12:05:30.474  4050  4072 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 12:05:30.475  4050  4072 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-07 12:05:30.475  4050  4072 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-07 12:05:30.476  4050  4072 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 12:05:30.476  4050  4072 I         : BTE_InitTraceLevels -- TRC_A2D
,09-07 12:05:30.476  4050  4072 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 12:05:30.476  4050  4072 I         : BTE_InitTraceLevels -- TRC_BTM
,09-07 12:05:30.477  4050  4072 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 12:05:30.477  4050  4072 I         : BTE_InitTraceLevels -- TRC_PAN
,09-07 12:05:30.477  4050  4072 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 12:05:30.477  4050  4072 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 12:05:30.478  4050  4072 I         : BTE_InitTraceLevels -- TRC_SMP
,09-07 12:05:30.478  4050  4072 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 12:05:30.480  4050  4072 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 12:05:30.611  4050  4072 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39eed9d
,09-07 12:05:30.611  4050  4072 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39eed9d 
,09-07 12:05:30.635  4050  4066 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
09-07 12:05:30.636  4050  4066 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-07 12:05:30.637  4050  4066 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-07 12:05:30.639  4050  4066 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 12:05:30.643  4050  4066 D BluetoothAdapterProperties: Scan Mode:20
,09-07 12:05:30.644  4050  4066 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 12:05:30.644  4050  4066 D bt_hci  : do_postload posting postload work item
,09-07 12:05:30.646  4050  4070 I bt_hci  : event_postload
,09-07 12:05:30.646  4050  4070 I bt_vendor: sco_config_cb
,09-07 12:05:30.646  4050  4070 I bt_hci  : sco_config_callback postload finished.
,09-07 12:05:30.648  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:30.649  4050  4066 D bt_bte_conf: Device ID record 1 : primary
,09-07 12:05:30.649  4050  4066 D bt_bte_conf:   vendorId            = 000f
,09-07 12:05:30.650  4050  4066 D bt_bte_conf:   vendorIdSource      = 0001
,09-07 12:05:30.650  4050  4066 D bt_bte_conf:   product             = 1200
09-07 12:05:30.650  4050  4066 D bt_bte_conf:   version             = 1436,
,09-07 12:05:30.650  4050  4066 D bt_bte_conf:   clientExecutableURL = 
09-07 12:05:30.651  4050  4066 D bt_bte_conf:   serviceDescription  = 
,09-07 12:05:30.651  4050  4066 D bt_bte_conf:   documentationURL    = 
09-07 12:05:30.651  4050  4066 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-07 12:05:30.652  4050  4063 D bt_stack_manager: event_start_up_stack finished
09-07 12:05:30.652  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:30.653  4050  4062 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-07 12:05:30.653  4050  4062 D BluetoothAdapterProperties: Setting state to 15
,09-07 12:05:30.653  4050  4062 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-07 12:05:30.654  4050  4070 I bt_vendor: low_power_mode_cb
,09-07 12:05:30.656  4050  4062 I BluetoothAdapterState: Entering BleOnState
,09-07 12:05:30.660  4050  4062 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-07 12:05:30.660  4050  4062 D BluetoothAdapterProperties: Setting state to 11
,09-07 12:05:30.660  4050  4062 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-07 12:05:30.669  4050  4050 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a754cd9
,09-07 12:05:30.671  4050  4050 D HeadsetService: Received start request. Starting profile...
09-07 12:05:30.677  4050  4050 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 12:05:30.677  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:30.677  4050  4050 D HeadsetStateMachine: make
09-07 12:05:30.681  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:30.693  4050  4050 D HeadsetStateMachine: max_hf_connections = 1
09-07 12:05:30.693  4050  4050 I bt_bluedroid: get_profile_interface handsfree
,09-07 12:05:30.694  4050  4066 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-07 12:05:30.694  4050  4062 I BluetoothAdapterState: Entering PendingCommandState
09-07 12:05:30.694  4050  4066 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-07 12:05:30.697  4050  4050 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a754cd9
,09-07 12:05:30.698  4050  4050 D A2dpService: Received start request. Starting profile...
09-07 12:05:30.699  4050  4050 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-07 12:05:30.699  4050  4050 I bt_bluedroid: get_profile_interface avrcp
,09-07 12:05:30.704  4050  4050 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-07 12:05:30.707  4050  4050 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 12:05:30.707  4050  4050 D A2dpStateMachine: make
,09-07 12:05:30.709  4050  4050 I bt_bluedroid: get_profile_interface a2dp
,09-07 12:05:30.710  4050  4066 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-07 12:05:30.713  4050  4082 D A2dpStateMachine: Enter Disconnected: -2
,09-07 12:05:30.714  4050  4050 I BluetoothHidServiceJni: classInitNative: succeeds
,09-07 12:05:30.715  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 12:05:30.716  4050  4050 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a754cd9
,09-07 12:05:30.718  4050  4050 D HidService: Received start request. Starting profile...
,09-07 12:05:30.718  4050  4050 I bt_bluedroid: get_profile_interface hidhost
,09-07 12:05:30.719  4050  4066 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39d03e5
,09-07 12:05:30.719  4050  4050 D HidService: setHidService(): set to: null
09-07 12:05:30.719  4050  4066 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-07 12:05:30.719  4050  4050 I BluetoothHealthServiceJni: classInitNative: succeeds
09-07 12:05:30.720  4050  4050 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a754cd9
09-07 12:05:30.721  4050  4050 D HealthService: Received start request. Starting profile...
,09-07 12:05:30.722  4050  4050 I bt_bluedroid: get_profile_interface health
,09-07 12:05:30.724  4050  4050 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-07 12:05:30.726  4050  4050 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a754cd9
,09-07 12:05:30.726  4050  4050 D PanService: Received start request. Starting profile...
09-07 12:05:30.726  4050  4050 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-07 12:05:30.727  4050  4050 I bt_bluedroid: get_profile_interface pan
,09-07 12:05:30.727  4050  4066 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-07 12:05:30.730  4050  4050 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a754cd9
,09-07 12:05:30.731  4050  4050 D BluetoothMapService: Received start request. Starting profile...
09-07 12:05:30.731  4050  4050 D BluetoothMapService: start()
,09-07 12:05:30.734  4050  4050 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-07 12:05:30.735  4050  4050 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-07 12:05:30.735  4050  4050 D BluetoothMapAppObserver: createReceiver()
,09-07 12:05:30.736  4050  4050 D BluetoothMapAppObserver: initObservers()
,09-07 12:05:30.736  4050  4050 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-07 12:05:30.744  4050  4050 V BluetoothAdapterState: isTurningOff()=false
,09-07 12:05:30.744  4050  4050 V BluetoothAdapterState: isTurningOn()=true
09-07 12:05:30.744  4050  4080 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-07 12:05:30.744  4050  4050 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 12:05:30.744  4050  4050 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 12:05:30.746  4050  4050 V BluetoothAdapterState: isTurningOff()=false
,09-07 12:05:30.746  4050  4050 V BluetoothAdapterState: isTurningOn()=true
09-07 12:05:30.746  4050  4050 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:05:30.746  4050  4050 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:05:30.747  4050  4050 V BluetoothAdapterState: isTurningOff()=false
09-07 12:05:30.747  4050  4050 V BluetoothAdapterState: isTurningOn()=true
,09-07 12:05:30.747  4050  4050 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:05:30.747  4050  4050 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:05:30.747  4050  4050 V BluetoothAdapterState: isTurningOff()=false
,09-07 12:05:30.747  4050  4050 V BluetoothAdapterState: isTurningOn()=true
,09-07 12:05:30.747  4050  4050 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:05:30.747  4050  4050 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:05:30.747  4050  4050 V BluetoothAdapterState: isTurningOff()=false
,09-07 12:05:30.747  4050  4050 V BluetoothAdapterState: isTurningOn()=true
09-07 12:05:30.747  4050  4050 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 12:05:30.747  4050  4050 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:05:30.748  4050  4050 V BluetoothAdapterState: isTurningOff()=false
09-07 12:05:30.748  4050  4050 V BluetoothAdapterState: isTurningOn()=true
09-07 12:05:30.748  4050  4050 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:05:30.748  4050  4050 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:05:30.748  4050  4062 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-07 12:05:30.748  4050  4062 D BluetoothAdapterProperties: ScanMode =  20
09-07 12:05:30.748  4050  4062 D BluetoothAdapterProperties: State =  11
09-07 12:05:30.749  4050  4066 D BluetoothAdapterProperties: Scan Mode:21
09-07 12:05:30.749  4050  4066 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 12:05:30.750  4050  4062 D BluetoothAdapterProperties: Setting state to 12
,09-07 12:05:30.750  4050  4062 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-07 12:05:30.751  4050  4062 I BluetoothAdapterState: Entering OnState
09-07 12:05:30.752  1368  1390 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 12:05:30.753  1368  2069 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 12:05:30.754  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:30.754  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:30.754  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:30.754  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:30.754  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:30.754  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:30.754  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:30.754  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:05:30.755  1368  1384 D BluetoothPan: onBluetoothStateChange on: true
09-07 12:05:30.755  1368  1368 D BluetoothInputDevice: Proxy object connected
09-07 12:05:30.756  1368  1368 D HidProfile: Bluetooth service connected
09-07 12:05:30.757   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 12:05:30.757  3693  3693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:05:30.757  3943  4044 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 12:05:30.758  1368  1368 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 12:05:30.758  1368  1368 D PanProfile: Bluetooth service connected
,09-07 12:05:30.759  1368  1390 D BluetoothMap: onBluetoothStateChange: up=true
09-07 12:05:30.761  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:30.761  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:30.761  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:30.761  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:30.761  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:30.761  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:30.761  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:30.761  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:05:30.762  1368  1368 D BluetoothMap: Proxy object connected
09-07 12:05:30.762  3943  3955 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 12:05:30.762  1368  1368 D MapProfile: Bluetooth service connected
09-07 12:05:30.762  1368  1368 D BluetoothMap: getConnectedDevices()
09-07 12:05:30.764  4050  4050 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-07 12:05:30.764  3693  3693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:05:30.764  3943  4044 D BluetoothPan: onBluetoothStateChange on: true
09-07 12:05:30.764  4050  4050 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-07 12:05:30.765  3943  3943 D BluetoothA2dp: Proxy object connected
,09-07 12:05:30.766  3943  3955 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 12:05:30.766  4050  4050 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 12:05:30.768   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 12:05:30.768  4050  4050 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 12:05:30.768  3943  3943 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 12:05:30.768  3943  3943 D PanProfile: Bluetooth service connected
09-07 12:05:30.768  1973  1985 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 12:05:30.768  3943  4044 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 12:05:30.768  3943  3943 D BluetoothInputDevice: Proxy object connected
09-07 12:05:30.769  4050  4050 D ObexServerSockets: Succeed to create listening sockets 
,09-07 12:05:30.769  3943  3943 D HidProfile: Bluetooth service connected
09-07 12:05:30.769  4050  4050 D ObexServerSockets0: startAccept()
09-07 12:05:30.769  4050  4050 D ObexServerSockets0: prepareForNewConnect()
09-07 12:05:30.769  1368  2069 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 12:05:30.770  4050  4050 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-07 12:05:30.770  4050  4050 D BluetoothSdpJni: SDP Create record success - handle: 0
09-07 12:05:30.770  1368  1368 D BluetoothA2dp: Proxy object connected
,09-07 12:05:30.771   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 12:05:30.771   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 12:05:30.772   874   874 D BluetoothA2dp: Proxy object connected
09-07 12:05:30.772  1368  1390 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 12:05:30.772  3943  3954 D BluetoothMap: onBluetoothStateChange: up=true
,09-07 12:05:30.774  4050  4088 D ObexServerSockets0: Accepting socket connection...
,09-07 12:05:30.775  4050  4089 D ObexServerSockets0: Accepting socket connection...
,09-07 12:05:30.775  3943  3943 D BluetoothMap: Proxy object connected
09-07 12:05:30.775  3943  3943 D MapProfile: Bluetooth service connected
,09-07 12:05:30.775  3943  3943 D BluetoothMap: getConnectedDevices()
,09-07 12:05:30.776   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-07 12:05:30.777  4050  4050 D BluetoothMapService: onReceive
,09-07 12:05:30.777  4050  4050 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED,
09-07 12:05:30.777  4050  4050 D BluetoothMapService: STATE_ON
,09-07 12:05:30.778  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:30.779  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:30.785  3943  3943 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 12:05:30.791  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 12:05:30.793  3943  3943 D DockEventReceiver: finishStartingService: stopping service
,09-07 12:05:30.798  3943  3943 D BluetoothPbap: Proxy object connected
09-07 12:05:30.798  3943  3943 D PbapServerProfile: Bluetooth service connected
,09-07 12:05:30.798  1368  1368 D BluetoothPbap: Proxy object connected
09-07 12:05:30.799  1368  1368 D PbapServerProfile: Bluetooth service connected
,09-07 12:05:30.803  4050  4050 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-07 12:05:30.803  4050  4050 D ObexServerSockets0: prepareForNewConnect()
,09-07 12:05:30.807  4050  4093 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 12:05:30.818  4050  4097 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 12:05:30.820  4050  4097 I BtOppRfcommListener: Accept thread started.
,09-07 12:05:30.858  1973  2095 D BluetoothHeadset: Proxy object connected
,09-07 12:05:30.859   874   874 D BluetoothHeadset: Proxy object connected
,09-07 12:05:30.859  1368  2054 D BluetoothHeadset: Proxy object connected
,09-07 12:05:30.859   874   874 D BluetoothHeadset: Proxy object connected
,09-07 12:05:30.859  1368  1368 D HeadsetProfile: Bluetooth service connected
09-07 12:05:30.859   874   874 D BluetoothHeadset: Proxy object connected
09-07 12:05:30.860  3943  3955 D BluetoothHeadset: Proxy object connected
,09-07 12:05:30.860  3943  3943 D HeadsetProfile: Bluetooth service connected
,09-07 12:05:30.867   874   891 D BluetoothHeadset: Proxy object connected
,09-07 12:05:30.869  1973  1986 D BluetoothHeadset: Proxy object connected
,09-07 12:05:30.870  3943  3954 D BluetoothHeadset: Proxy object connected
,09-07 12:05:30.871  3943  3943 D HeadsetProfile: Bluetooth service connected
,09-07 12:05:30.872   874   891 D BluetoothHeadset: Proxy object connected
,09-07 12:05:30.875  1368  1384 D BluetoothHeadset: Proxy object connected
,09-07 12:05:30.876  1368  1368 D HeadsetProfile: Bluetooth service connected
,09-07 12:05:32.160  3693  3744 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 12:05:32.160  3693  3744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:35.168  3693  3744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:05:35.168  3693  3744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c138d3f added. We now have 6 listener(s)
,09-07 12:05:35.169  3693  3744 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 12:05:35.176  3693  3744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 12:05:35.177  3693  3744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@716860c added. We now have 7 listener(s)
09-07 12:05:35.177  3693  3744 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 12:05:35.181  3693  3744 I System.out: IsBluetoothEnabled
,09-07 12:05:35.194  4050  4062 D BluetoothAdapterState: Current state: ON, message: 23
,09-07 12:05:35.195  4050  4062 D BluetoothAdapterProperties: Setting state to 13
,09-07 12:05:35.195  4050  4062 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13,
,09-07 12:05:35.196  4050  4062 D BluetoothAdapterProperties: onBluetoothDisable()
,09-07 12:05:35.202  4050  4062 I BluetoothAdapterState: Entering PendingCommandState
,09-07 12:05:35.207  4050  4050 D BluetoothMapService: onReceive
,09-07 12:05:35.207  4050  4050 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:05:35.207  4050  4050 D BluetoothMapService: STATE_TURNING_OFF
,09-07 12:05:35.214  4050  4050 D BluetoothMapService: MAP Service closeService in
,09-07 12:05:35.214  4050  4050 D BluetoothMapMasInstance0: MAP Service shutdown
,09-07 12:05:35.214  3693  3693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
,09-07 12:05:35.215  4050  4050 D ObexServerSockets0: shutdown(block = true)
,09-07 12:05:35.215  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:35.215  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:35.215  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:35.215  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:35.215  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:35.215  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:35.215  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:35.215  3693  3693 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:05:35.216  4050  4088 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-07 12:05:35.217  3693  3693 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:05:35.217  4050  4050 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-07 12:05:35.217  3693  3693 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:05:35.218  4050  4089 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-07 12:05:35.218  4050  4074 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-07 12:05:35.219  4050  4050 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-07 12:05:35.219  4050  4050 I BtOppRfcommListener: stopping Accept Thread
,09-07 12:05:35.219  4050  4097 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-07 12:05:35.220  4050  4066 D BluetoothAdapterProperties: Scan Mode:20
,09-07 12:05:35.220  4050  4097 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 12:05:35.220  4050  4062 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-07 12:05:35.222  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:35.222  3693  3744 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:35.222  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:35.222  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:35.222  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:35.222  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:35.222  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:35.222  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:35.222  3693  3744 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:05:35.223  3693  3744 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:35.223  3693  3744 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:05:35.224  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:35.224  4050  4050 D HeadsetService: Received stop request...Stopping profile...
,09-07 12:05:35.227  1973  1985 D BluetoothHeadset: Proxy object disconnected
09-07 12:05:35.228   874   874 D BluetoothHeadset: Proxy object disconnected
09-07 12:05:35.228  4050  4050 V BluetoothAdapterState: isTurningOff()=true
09-07 12:05:35.228  4050  4050 V BluetoothAdapterState: isTurningOn()=false
,09-07 12:05:35.228  4050  4050 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 12:05:35.229  4050  4050 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:05:35.229  1368  2069 D BluetoothHeadset: Proxy object disconnected
,09-07 12:05:35.229   874   874 D BluetoothHeadset: Proxy object disconnected
,09-07 12:05:35.229   874   874 D BluetoothHeadset: Proxy object disconnected
09-07 12:05:35.229  3943  3954 D BluetoothHeadset: Proxy object disconnected
,09-07 12:05:35.230  4050  4050 D A2dpService: Received stop request...Stopping profile...
09-07 12:05:35.230  4050  4082 D A2dpStateMachine: Exit Disconnected: -1
09-07 12:05:35.231  1368  1368 D HeadsetProfile: Bluetooth service disconnected
,09-07 12:05:35.233   874   874 D BluetoothA2dp: Proxy object disconnected
,09-07 12:05:35.234  4050  4062 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
09-07 12:05:35.234  4050  4062 I BluetoothAdapterState: Deferring BLE_TURN_ON request...
09-07 12:05:35.234  3943  3943 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 12:05:35.235  4050  4050 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 12:05:35.235  4050  4050 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 12:05:35.235  4050  4066 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-07 12:05:35.235  4050  4072 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 12:05:35.235  4050  4072 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 12:05:35.235  4050  4072 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 12:05:35.236  4050  4066 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-07 12:05:35.236  4050  4050 D HidService: Received stop request...Stopping profile...
09-07 12:05:35.237  4050  4050 D HidService: Stopping Bluetooth HidService
09-07 12:05:35.238  3943  3943 D HeadsetProfile: Bluetooth service disconnected
09-07 12:05:35.239  3943  3943 D BluetoothA2dp: Proxy object disconnected
09-07 12:05:35.242  4050  4050 D HealthService: Received stop request...Stopping profile...,
09-07 12:05:35.248  4050  4050 D PanService: Received stop request...Stopping profile...
09-07 12:05:35.249  4050  4050 V BluetoothAdapterState: isTurningOff()=true
09-07 12:05:35.249  4050  4050 V BluetoothAdapterState: isTurningOn()=false
09-07 12:05:35.249  4050  4050 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:05:35.249  4050  4050 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:05:35.249  4050  4050 D BluetoothMapService: Received stop request...Stopping profile...
09-07 12:05:35.250  4050  4050 D BluetoothMapService: stop()
09-07 12:05:35.250  4050  4050 D BluetoothMapAppObserver: deinitObservers()
09-07 12:05:35.250  4050  4050 D BluetoothMapAppObserver: removeReceiver()
09-07 12:05:35.252  1368  1368 D BluetoothA2dp: Proxy object disconnected
09-07 12:05:35.252  1368  1368 D BluetoothInputDevice: Proxy object disconnected
09-07 12:05:35.252  1368  1368 D HidProfile: Bluetooth service disconnected
,09-07 12:05:35.252  1368  1368 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 12:05:35.252  1368  1368 D PanProfile: Bluetooth service disconnected
09-07 12:05:35.252  1368  1368 D BluetoothMap: Proxy object disconnected
09-07 12:05:35.252  1368  1368 D MapProfile: Bluetooth service disconnected
09-07 12:05:35.253  4050  4066 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-07 12:05:35.253  4050  4072 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.,
,09-07 12:05:35.253  4050  4072 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 12:05:35.254  4050  4072 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 12:05:35.254  4050  4072 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 12:05:35.254  4050  4072 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-07 12:05:35.254  4050  4072 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 12:05:35.254  4050  4050 V BluetoothAdapterState: isTurningOff()=true
09-07 12:05:35.254  4050  4050 V BluetoothAdapterState: isTurningOn()=false
09-07 12:05:35.255  4050  4050 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:05:35.255  4050  4050 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:05:35.255  3943  3943 D BluetoothInputDevice: Proxy object disconnected
,09-07 12:05:35.255  3943  3943 D HidProfile: Bluetooth service disconnected
09-07 12:05:35.255  4050  4050 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 12:05:35.255  4050  4050 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 12:05:35.256  4050  4066 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 12:05:35.256  4050  4050 V BluetoothAdapterState: isTurningOff()=true
09-07 12:05:35.256  4050  4050 V BluetoothAdapterState: isTurningOn()=false
,09-07 12:05:35.256  4050  4050 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:05:35.256  4050  4050 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:05:35.257  4050  4050 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 12:05:35.257  4050  4066 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-07 12:05:35.257  4050  4050 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 12:05:35.257  4050  4050 V BluetoothAdapterState: isTurningOff()=true
,09-07 12:05:35.257  4050  4050 V BluetoothAdapterState: isTurningOn()=false
09-07 12:05:35.257  4050  4050 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:05:35.257  4050  4050 V BluetoothAdapterState: isBleTurningOff()=false
09-07 12:05:35.258  4050  4050 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 12:05:35.258  4050  4050 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-07 12:05:35.258  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 12:05:35.259  4050  4050 D BluetoothMapService: MAP Service closeService in
09-07 12:05:35.259  4050  4050 V BluetoothAdapterState: isTurningOff()=true
09-07 12:05:35.259  4050  4050 V BluetoothAdapterState: isTurningOn()=false
09-07 12:05:35.259  4050  4050 V BluetoothAdapterState: isBleTurningOn()=false
09-07 12:05:35.259  4050  4050 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 12:05:35.259  4050  4050 D BluetoothMapService: cleanup()
09-07 12:05:35.260  4050  4050 D BluetoothMapService: MAP Service closeService in
09-07 12:05:35.260  4050  4062 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-07 12:05:35.260  4050  4062 D BluetoothAdapterProperties: Setting state to 15
09-07 12:05:35.260  4050  4062 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-07 12:05:35.260  4050  4062 I BluetoothAdapterState: Entering BleOnState
,09-07 12:05:35.260  4050  4062 D BluetoothAdapterState: Current state: BLE ON, message: 0
09-07 12:05:35.260  3943  3943 D DockEventReceiver: finishStartingService: stopping service
09-07 12:05:35.260  1368  1390 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 12:05:35.261  3943  3943 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 12:05:35.261  3943  3943 D PanProfile: Bluetooth service disconnected
09-07 12:05:35.261  1368  2069 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-07 12:05:35.261  3943  3943 D BluetoothMap: Proxy object disconnected
09-07 12:05:35.261  3943  3943 D MapProfile: Bluetooth service disconnected
09-07 12:05:35.262  1368  1384 D BluetoothPan: onBluetoothStateChange on: false
09-07 12:05:35.263   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 12:05:35.263  3943  3955 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 12:05:35.265  1368  2054 D BluetoothMap: onBluetoothStateChange: up=false
,09-07 12:05:35.266  3943  4044 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 12:05:35.266  3943  3954 D BluetoothPan: onBluetoothStateChange on: false
09-07 12:05:35.267  3943  3955 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 12:05:35.267   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 12:05:35.268  1973  2095 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-07 12:05:35.268  3943  4044 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 12:05:35.269  1368  1390 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 12:05:35.269   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 12:05:35.270   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 12:05:35.270  1368  2069 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 12:05:35.270  3943  3954 D BluetoothMap: onBluetoothStateChange: up=false
,09-07 12:05:35.271  4050  4062 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-07 12:05:35.271  4050  4062 D BluetoothAdapterProperties: Setting state to 16
09-07 12:05:35.271  4050  4062 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-07 12:05:35.272  4050  4062 D BluetoothAdapterProperties: onBleDisable
09-07 12:05:35.272  4050  4063 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-07 12:05:35.272  4050  4062 I BluetoothAdapterState: Entering PendingCommandState
,09-07 12:05:35.273  4050  4072 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-07 12:05:35.273  4050  4072 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 12:05:35.274  4050  4066 D BluetoothAdapterProperties: Scan Mode:20
09-07 12:05:35.276  3943  3943 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 12:05:35.276  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:35.279  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:35.281  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 12:05:35.290  3943  3943 D DockEventReceiver: finishStartingService: stopping service
,09-07 12:05:35.479  4050  4066 I bt_hci  : shut_down
,09-07 12:05:35.491  4050  4070 I bt_vendor: low_power_mode_cb
,09-07 12:05:35.495  4050  4070 D bt_hwcfg: hw_epilog_process
,09-07 12:05:35.516  4050  4070 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-07 12:05:35.517  4050  4070 I bt_vendor: epilog_cb
,09-07 12:05:35.517  4050  4070 I bt_hci  : epilog_finished_callback,
,09-07 12:05:35.520  4050  4066 I bt_hci_h4: hal_close
,09-07 12:05:35.520  4050  4066 I bt_userial_vendor: device fd = 51 close
,09-07 12:05:35.644  4050  4063 D bt_stack_manager: event_shut_down_stack finished.
,09-07 12:05:35.645  4050  4062 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-07 12:05:35.652  4050  4050 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 12:05:35.652  4050  4062 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-07 12:05:35.653  4050  4050 D BtGatt.GattService: Received stop request...Stopping profile...
,09-07 12:05:35.654  4050  4050 D BtGatt.GattService: stop()
,09-07 12:05:35.654  4050  4050 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 12:05:35.659  4050  4050 V BluetoothAdapterState: isTurningOff()=false
,09-07 12:05:35.660  4050  4050 V BluetoothAdapterState: isTurningOn()=false
,09-07 12:05:35.660  4050  4050 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 12:05:35.660  4050  4050 V BluetoothAdapterState: isBleTurningOff()=true
09-07 12:05:35.661  4050  4062 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-07 12:05:35.662  4050  4062 D BluetoothAdapterProperties: Setting state to 10
09-07 12:05:35.663  4050  4062 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-07 12:05:35.664  4050  4062 I BluetoothAdapterState: Entering OffState
,09-07 12:05:35.675  3693  3693 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:35.676  3943  3943 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 12:05:35.684  1528  1528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 12:05:35.692  3943  3943 D DockEventReceiver: finishStartingService: stopping service
,09-07 12:05:35.971  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:05:35.980  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:05:35.985  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:05:36.018  1528  2958 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 12:05:36.018  1528  2958 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 12:05:36.018  1528  2958 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:05:36.018  1528  2958 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:05:36.047  3433  3433 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 12:05:36.047  3433  3433 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-07 12:05:36.048  3433  3433 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-07 12:05:44.358   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-07 12:05:44.369  1890  1890 I Keyboard.Facilitator: onFinishInput()
,09-07 12:05:44.387   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 12:05:44.387   874   894 I Adreno  : Build Date                       : 10/20/15
09-07 12:05:44.387   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 12:05:44.387   874   894 I Adreno  : Local Branch                     : M14
09-07 12:05:44.387   874   894 I Adreno  : Remote Branch                    : 
09-07 12:05:44.387   874   894 I Adreno  : Remote Branch                    : 
09-07 12:05:44.387   874   894 I Adreno  : Reconstruct Branch               : 
,09-07 12:05:44.435   280   360 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (310 us)
,09-07 12:05:45.138  3693  3693 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-07 12:05:45.138  3693  3693 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-07 12:05:45.171   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-07 12:05:45.176  3693  3693 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@464dd95 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@ab6eb55, 16908290=android.view.AbsSavedState$1@ab6eb55}, android:focusedViewId=100}]}]
,09-07 12:05:45.176  3693  3693 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-07 12:05:45.176  3693  3693 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-07 12:05:45.176  3693  3693 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-07 12:05:45.187   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-07 12:05:45.196   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-07 12:05:45.197   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
,09-07 12:05:45.197   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-07 12:05:45.435   280   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-07 12:05:45.439   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-07 12:05:45.439   874  1342 D SurfaceControl: Excessive delay in setPowerMode(): 243ms
,09-07 12:05:45.444   874   894 I DreamManagerService: Entering dreamland.
,09-07 12:05:45.449   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-07 12:05:45.450   874   894 I PowerManagerService: Dozing...
,09-07 12:05:45.493   377  1326 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-07 12:05:45.497   377  1326 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-07 12:05:45.505   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 12:05:45.514   874  1315 E native  : do suspend false
,09-07 12:05:45.525  1954  4115 D NfcService: Discovery configuration equal, not updating.
,09-07 12:05:45.565   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 12:05:45.573   874  1315 E native  : do suspend true
,09-07 12:05:45.633   377  1287 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-07 12:05:45.633   377  1287 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-07 12:05:53.971  1909  2675 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-07 12:05:56.447  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:05:56.469  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:05:56.474  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:05:56.500  1528  1541 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 12:05:56.500  1528  1541 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 12:05:56.501  1528  1541 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:05:56.501  1528  1541 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:05:56.519  3433  3433 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 12:05:56.519  3433  3433 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 12:05:56.519  3433  3433 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-07 12:06:23.290   874  1319 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,09-07 12:06:29.412  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:06:29.424  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:06:29.428  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:06:29.470  1528  2055 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 12:06:29.470  1528  2055 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-07 12:06:29.470  1528  2055 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:06:29.470  1528  2055 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:06:29.494  3433  3433 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 12:06:29.495  3433  3433 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 12:06:29.495  3433  3433 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-07 12:06:44.381  1890  1969 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-07 12:06:44.381  1890  1969 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-07 12:06:44.426  1528  1528 I ConfigService: onCreate
,09-07 12:06:49.523  1528  1528 I ConfigService: onDestroy
,09-07 12:07:03.483  1528  2134 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-07 12:08:59.936  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:08:59.953  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:08:59.955  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:09:00.012  1528  1541 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 12:09:00.013  1528  1541 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-07 12:09:00.013  1528  1541 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 12:09:00.014  1528  1541 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:09:00.052  1528  1541 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 12:09:00.052  1528  1541 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 12:09:00.052  1528  1541 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 12:09:00.052  1528  1541 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-07 12:09:00.052  1528  1541 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-07 12:09:00.052  1528  1541 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-07 12:09:00.052  1528  1541 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-07 12:09:00.061  3433  3466 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-07 12:09:00.061  3433  3466 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-07 12:09:00.061  3433  3466 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-07 12:09:00.061  3433  3466 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-07 12:09:00.061  3433  3466 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-07 12:09:00.061  3433  3466 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-07 12:09:00.061  3433  3466 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-07 12:14:00.230  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:14:00.255  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:14:00.263  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:14:00.345  1528  2958 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-07 12:14:00.345  1528  2958 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-07 12:14:00.345  1528  2958 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:14:00.346  1528  2958 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:14:00.380  1528  2958 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 12:14:00.380  1528  2958 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 12:14:00.380  1528  2958 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 12:14:00.380  1528  2958 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-07 12:14:00.380  1528  2958 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-07 12:14:00.380  1528  2958 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-07 12:14:00.380  1528  2958 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-07 12:14:00.389  3433  3466 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-07 12:14:00.389  3433  3466 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-07 12:14:00.389  3433  3466 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-07 12:14:00.389  3433  3466 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-07 12:14:00.389  3433  3466 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-07 12:14:00.389  3433  3466 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-07 12:14:00.389  3433  3466 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-07 12:15:01.030  3433  3433 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,09-07 12:15:01.055  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:15:01.069  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:15:01.071  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:15:01.113  1528  2285 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-07 12:15:01.113  1528  2285 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-07 12:15:01.113  1528  2285 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 12:15:01.113  1528  2285 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:15:01.156  3433  3433 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-07 12:15:01.177  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:15:01.227  1528  1541 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 12:15:01.227  1528  1541 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-07 12:15:01.227  1528  1541 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:15:01.227  1528  1541 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:15:01.291  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:15:01.352  1528  2958 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 12:15:01.352  1528  2958 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-07 12:15:01.352  1528  2958 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 12:15:01.354  1528  2958 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:15:01.409  3433  3433 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-07 12:15:01.680  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:15:01.722  1528  2958 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 12:15:01.723  1528  2958 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-07 12:15:01.723  1528  2958 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:15:01.723  1528  2958 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:15:01.768  3433  3433 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-07 12:15:01.769  3433  3433 D Finsky  : [1] WearSupportService.startHygiene: disabled
09-07 12:15:01.770  3433  3433 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,09-07 12:15:01.780  3433  3484 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,09-07 12:15:01.785  3433  3433 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,09-07 12:15:16.702  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:15:16.710  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:15:16.711  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:15:16.759  1528  1540 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 12:15:16.759  1528  1540 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 12:15:16.760  1528  1540 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:15:16.760  1528  1540 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:15:16.811  3433  3433 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 12:15:16.812  3433  3433 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 12:15:16.813  3433  3433 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,09-07 12:15:37.107  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:15:37.124  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:15:37.130  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:15:37.216  1528  2285 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 12:15:37.216  1528  2285 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 12:15:37.217  1528  2285 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:15:37.217  1528  2285 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:15:37.266  3433  3433 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 12:15:37.272  3433  3433 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 12:15:37.272  3433  3433 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,09-07 12:15:57.559  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:15:57.574  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:15:57.578  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:15:57.656  1528  1541 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 12:15:57.656  1528  1541 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 12:15:57.656  1528  1541 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 12:15:57.657  1528  1541 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:15:57.711  3433  3433 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 12:15:57.711  3433  3433 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 12:15:57.711  3433  3433 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-07 12:16:18.050  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:16:18.064  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:16:18.066  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:16:18.110  1528  2958 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 12:16:18.110  1528  2958 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 12:16:18.110  1528  2958 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:16:18.110  1528  2958 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:16:18.159  3433  3433 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 12:16:18.160  3433  3433 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 12:16:18.161  3433  3433 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-07 12:16:38.458  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:16:38.474  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:16:38.478  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:16:38.539  1528  2958 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 12:16:38.540  1528  2958 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 12:16:38.540  1528  2958 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 12:16:38.540  1528  2958 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:16:38.585  3433  3433 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-07 12:16:38.586  3433  3433 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 12:16:38.587  3433  3433 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-07 12:16:58.931  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:16:58.951  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:16:58.958  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:16:59.048  1528  2285 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 12:16:59.048  1528  2285 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 12:16:59.049  1528  2285 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 12:16:59.049  1528  2285 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:16:59.117  3433  3433 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 12:16:59.120  3433  3433 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-07 12:16:59.123  3433  3433 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-07 12:17:01.305  1528  2134 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-07 12:18:24.496   874  1299 E qti_sensors_hal: waitForResponse: pthread_cond_timedwait() rc=110 (cond: 0)
,09-07 12:18:24.497   874  1299 E qti_sensors_hal: deactivateDpc: ERROR: No response from the request
,09-07 12:18:27.004   874  1306 I PowerManagerService: Waking up from dozing (uid 1000)...
,09-07 12:18:27.005   874   874 V KeyguardServiceDelegate: onStartedWakingUp()
09-07 12:18:27.006   874   894 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
,09-07 12:18:27.013  1890  1890 I Keyboard.Facilitator: onFinishInput()
,09-07 12:18:27.016   874   894 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@4fa66d7)
,09-07 12:18:27.021  3693  3693 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-07 12:18:27.021  3693  3693 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
09-07 12:18:27.022   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
,09-07 12:18:27.029   874   884 V KeyguardServiceDelegate: **** SHOWN CALLED ****
,09-07 12:18:27.030   280   280 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6b24000
09-07 12:18:27.030   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
09-07 12:18:27.036  1909  1909 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,09-07 12:18:27.047   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 12:18:27.048  1954  2082 E BrcmNfcJni: nfaConnectionCallback: unknown event ????
09-07 12:18:27.048  1954  2082 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_TECH_CFG_EVT; status=0x0
09-07 12:18:27.048  1954  2082 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_PROTO_CFG_EVT; status=0x0
09-07 12:18:27.048  1954  2071 D BrcmNfcJni: RoutingManager::commitRouting
09-07 12:18:27.049  1954  2082 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_UPDATED_EVT
,09-07 12:18:27.050   874  1315 E native  : do suspend false
,09-07 12:18:27.057  3693  3693 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-07 12:18:27.057  3693  3693 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
09-07 12:18:27.059   874  1393 I ActivityManager: Start proc 4177:com.google.android.apps.fitness/u0a51 for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider
,09-07 12:18:27.060   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-07 12:18:27.060   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-07 12:18:27.083   874   894 I DisplayPowerController: Unblocked screen on after 78 ms
09-07 12:18:27.086   874   894 V KeyguardServiceDelegate: onScreenTurnedOn()
09-07 12:18:27.086   874   894 I DreamManagerService: Gently waking up from dream.
09-07 12:18:27.087   874  2226 I DreamManagerService: Leaving dreamland.
09-07 12:18:27.087   874   889 I DreamController: Stopping dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-07 12:18:27.101  4177  4177 W System  : ClassLoader referenced unknown path: /system/app/FitnessPrebuilt/lib/arm
,09-07 12:18:27.114   874  2222 I ActivityManager: Killing 3582:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-07 12:18:27.275   280   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,09-07 12:18:27.275   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,09-07 12:18:27.277   874  1342 D SurfaceControl: Excessive delay in setPowerMode(): 255ms
,09-07 12:18:27.828  1954  2343 D NfcService: Discovery configuration equal, not updating.
,09-07 12:18:33.576   874  1306 I PowerManagerService: Going to sleep due to power button (uid 1000)...
,09-07 12:18:33.585  1890  1890 I Keyboard.Facilitator: onFinishInput()
,09-07 12:18:34.167  3693  3693 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-07 12:18:34.167  3693  3693 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-07 12:18:34.219   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-07 12:18:34.223  3693  3693 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@464dd95 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@ab6eb55, 16908290=android.view.AbsSavedState$1@ab6eb55}, android:focusedViewId=100}]}]
,09-07 12:18:34.224  3693  3693 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-07 12:18:34.224  3693  3693 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-07 12:18:34.224  3693  3693 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-07 12:18:34.237   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
,09-07 12:18:34.237   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
09-07 12:18:34.237   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-07 12:18:34.488   280   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-07 12:18:34.491   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-07 12:18:34.492   874  1342 D SurfaceControl: Excessive delay in setPowerMode(): 255ms
09-07 12:18:34.495   874   894 I DreamManagerService: Entering dreamland.
09-07 12:18:34.495   874   894 I PowerManagerService: Dozing...
,09-07 12:18:34.497   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-07 12:18:34.576   874  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 12:18:34.583   874  1315 E native  : do suspend true
,09-07 12:18:34.699   377  1326 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
09-07 12:18:34.699   377  1326 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-07 12:19:00.520  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:19:00.544  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:19:00.549  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:19:00.621  1528  2055 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 12:19:00.622  1528  2055 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-07 12:19:00.622  1528  2055 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 12:19:00.622  1528  2055 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:19:00.654  1528  2055 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 12:19:00.654  1528  2055 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 12:19:00.654  1528  2055 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 12:19:00.654  1528  2055 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-07 12:19:00.654  1528  2055 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-07 12:19:00.654  1528  2055 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-07 12:19:00.654  1528  2055 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-07 12:19:00.658  3433  3466 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-07 12:19:00.658  3433  3466 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-07 12:19:00.658  3433  3466 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-07 12:19:00.658  3433  3466 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-07 12:19:00.658  3433  3466 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-07 12:19:00.658  3433  3466 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-07 12:19:00.658  3433  3466 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-07 12:19:33.629  1890  1969 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-07 12:19:33.629  1890  1969 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-07 12:19:33.670  1528  1528 I ConfigService: onCreate
,09-07 12:19:38.782  1528  1528 I ConfigService: onDestroy
,09-07 12:20:27.083  1909  2675 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-07 12:23:30.361   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,09-07 12:24:00.792  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:24:00.812  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:24:00.821  1528  1528 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 12:24:00.917  1528  2055 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 12:24:00.917  1528  2055 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-07 12:24:00.917  1528  2055 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 12:24:00.918  1528  2055 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 12:24:00.968  1528  2055 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 12:24:00.968  1528  2055 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 12:24:00.968  1528  2055 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 12:24:00.968  1528  2055 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-07 12:24:00.968  1528  2055 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-07 12:24:00.968  1528  2055 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-07 12:24:00.968  1528  2055 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-07 12:24:00.983  3433  3466 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-07 12:24:00.983  3433  3466 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-07 12:24:00.983  3433  3466 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-07 12:24:00.983  3433  3466 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-07 12:24:00.983  3433  3466 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-07 12:24:00.983  3433  3466 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-07 12:24:00.983  3433  3466 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms),09-07 12:28:35.117  4225  4225 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-07 12:28:35.122  4225  4225 D AndroidRuntime: CheckJNI is OFF
09-07 12:28:35.157  4225  4225 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-07 12:28:35.197  4225  4225 I Radio-JNI: register_android_hardware_Radio DONE
09-07 12:28:35.217  4225  4225 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-07 12:28:35.229   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-07 12:28:35.229   874   887 I ActivityManager: Killing 3693:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-07 12:28:35.290   874  1716 D GraphicsStats: Buffer count: 2
09-07 12:28:35.291   874  1974 I WindowState: WIN DEATH: Window{edb0100 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 12:28:35.292   874  1317 D WifiService: Client connection lost with reason: 4
09-07 12:28:35.349   874   897 W PackageSettings: Skipping PackageSetting{7486e22 com.example.hello/10273} due to missing metadata
09-07 12:28:35.371   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-07 12:28:35.371   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-07 12:28:35.371   874   887 E ActivityManager: Failure starting process com.test.thalitest
09-07 12:28:35.371   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-07 12:28:35.371   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-07 12:28:35.371   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-07 12:28:35.371   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-07 12:28:35.371   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-07 12:28:35.371   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-07 12:28:35.371   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-07 12:28:35.371   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-07 12:28:35.371   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-07 12:28:35.371   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-07 12:28:35.371   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-07 12:28:35.371   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-07 12:28:35.371   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-07 12:28:35.371   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-07 12:28:35.371   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-07 12:28:35.371   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:28:35.371   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:28:35.371   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 12:28:35.371   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-07 12:28:35.372   874   887 I ActivityManager:   Force finishing activity ActivityRecord{39cec21 u0 com.test.thalitest/.MainActivity t4}
09-07 12:28:35.373   874   897 I art     : Starting a blocking GC Explicit
09-07 12:28:35.391   874   884 W ActivityManager: Spurious death for ProcessRecord{90bd2c1 0:com.test.thalitest/u0a0}, curProc for 3693: null
09-07 12:28:35.457   874   897 I art     : Explicit concurrent mark sweep GC freed 23085(1620KB) AllocSpace objects, 7(140KB) LOS objects, 33% free, 28MB/43MB, paused 796us total 83.517ms
09-07 12:28:35.480   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-07 12:28:35.486  4225  4225 I art     : System.exit called, status: 0
09-07 12:28:35.486  4225  4225 I AndroidRuntime: VM exiting with result code 0.
09-07 12:28:35.489   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-07 12:28:35.502   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-07 12:28:35.521   874  1306 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-07 12:28:35.522  1909  2280 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-07 12:28:35.528  3529  3529 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-07 12:28:35.535  1890  1890 I Keyboard.Facilitator: resetDictionaries() : en_US
09-07 12:28:35.555  1890  4238 I Keyboard.Facilitator.DecoderInitializer: run()
09-07 12:28:35.560  1973  1973 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-07 12:28:35.564  1890  4238 I Decoder : createOrResetDecoder
09-07 12:28:35.570   874  2222 I ActivityManager: Start proc 4240:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-07 12:28:35.598   874  1313 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
09-07 12:28:35.600   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-07 12:28:35.611  4240  4240 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-07 12:28:35.616  1528  1528 I ConfigService: onCreate
09-07 12:28:35.627  1528  4253 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-07 12:28:35.627  1528  4253 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 12:28:35.627  1528  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 12:28:35.627  1528  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 12:28:35.627  1528  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 12:28:35.627  1528  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 12:28:35.627  1528  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 12:28:35.627  1528  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 12:28:35.627  1528  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 12:28:35.627  1528  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 12:28:35.627  1528  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 12:28:35.627  1528  4253 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 12:28:35.627  1528  4253 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 12:28:35.627  1528  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 12:28:35.627  1528  4253 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 12:28:35.627  1528  4253 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-07 12:28:35.627  1528  4253 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-07 12:28:35.627  1528  4253 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-07 12:28:35.627  1528  4253 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-07 12:28:35.627  1528  4253 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 12:28:35.627  1528  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 12:28:35.627  1528  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 12:28:35.627  1528  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 12:28:35.627  1528  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 12:28:35.627  1528  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 12:28:35.627  1528  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 12:28:35.627  1528  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 12:28:35.627  1528  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 12:28:35.627  1528  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 12:28:35.627  1528  4253 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 12:28:35.627  1528  4253 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 12:28:35.627  1528  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 12:28:35.627  1528  4253 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 12:28:35.627  1528  4253 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-07 12:28:35.627  1528  4253 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-07 12:28:35.627  1528  4253 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-07 12:28:35.628  1528  4253 W SQLiteOpenHelper: Opened config.db in read-only mode
09-07 12:28:35.635   874  1974 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3693 uid 10000
09-07 12:28:35.637  1890  1890 I Keyboard.Facilitator: onFinishInput()
09-07 12:28:35.640  1987  2061 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-07 12:28:35.640   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-07 12:28:35.641   874   886 E PackageManager: Failed to write settings, restoring backup
09-07 12:28:35.641   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-07 12:28:35.641   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-07 12:28:35.641   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-07 12:28:35.641   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-07 12:28:35.641   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-07 12:28:35.641   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:28:35.641   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:28:35.641   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 12:28:35.646   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-07 12:28:35.646   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-07 12:28:35.646   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 12:28:35.646   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 12:28:35.646   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 12:28:35.646   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 12:28:35.646   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 12:28:35.646   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 12:28:35.646   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-07 12:28:35.646   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-07 12:28:35.646   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-07 12:28:35.646   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 12:28:35.646   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 12:28:35.646   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:28:35.646   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 12:28:35.646   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-07 12:28:35.646   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 12:28:35.646   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 12:28:35.646   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 12:28:35.646   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 12:28:35.646   874   887 E DropBoxManagerService: 	... 13 more
09-07 12:28:35.659   874  1393 I ActivityManager: Start proc 4257:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-07 12:28:35.660  1987  2061 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-07 12:28:35.660  1987  2061 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1987
09-07 12:28:35.660  1987  2061 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 12:28:35.660  1987  2061 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-07 12:28:35.660  1987  2061 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-07 12:28:35.660  1987  2061 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-07 12:28:35.660  1987  2061 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-07 12:28:35.660  1987  2061 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-07 12:28:35.660  1987  2061 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-07 12:28:35.660  1987  2061 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-07 12:28:35.660  1987  2061 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 12:28:35.660  1987  2061 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 12:28:35.660  1987  2061 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:28:35.660  1987  2061 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 12:28:35.662   874  2014 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 12:28:35.663   874  4262 E DropBoxManagerService: Can't write: system_app_crash
09-07 12:28:35.663   874  4262 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
09-07 12:28:35.663   874  4262 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 12:28:35.663   874  4262 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 12:28:35.663   874  4262 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 12:28:35.663   874  4262 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 12:28:35.663   874  4262 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 12:28:35.663   874  4262 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 12:28:35.663   874  4262 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 12:28:35.663   874  4262 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 12:28:35.663   874  4262 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 12:28:35.663   874  4262 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 12:28:35.663   874  4262 E DropBoxManagerService: 	... 5 more
09-07 12:28:35.666  1987  2061 I Process : Sending signal. PID: 1987 SIG: 9
09-07 12:28:35.671  1890  4238 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-07 12:28:35.687  4240  4240 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-07 12:28:35.714  4240  4270 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-07 12:28:35.716  1890  4238 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-07 12:28:35.719   874  2222 I ActivityManager: Start proc 4272:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-07 12:28:35.722  1890  4238 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-07 12:28:35.722  1890  4238 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-07 12:28:35.724  1890  4238 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-07 12:28:35.725  1890  4238 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-07 12:28:35.726  1890  4238 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-07 12:28:35.726  1890  4238 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-07 12:28:35.728  1890  4238 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-07 12:28:35.729  1890  4238 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-07 12:28:35.729  1890  4238 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-07 12:28:35.729  1890  4238 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-07 12:28:35.729  1890  4238 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-07 12:28:35.729  1890  4238 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-07 12:28:35.736   874  1393 D GraphicsStats: Buffer count: 1
09-07 12:28:35.736   874  3059 I WindowState: WIN DEATH: Window{3a30cac u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-07 12:28:35.743   874  1393 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1987) has died
09-07 12:28:35.744   874  1393 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-07 12:28:35.746   874  1393 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-07 12:28:35.765   874  1998 I ActivityManager: Start proc 4285:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 12:28:35.789  4240  4255 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-07 12:28:35.789  4240  4255 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 12:28:35.789  4240  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 12:28:35.789  4240  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 12:28:35.789  4240  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 12:28:35.789  4240  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 12:28:35.789  4240  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 12:28:35.789  4240  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 12:28:35.789  4240  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 12:28:35.789  4240  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 12:28:35.789  4240  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 12:28:35.789  4240  4255 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 12:28:35.789  4240  4255 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 12:28:35.789  4240  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 12:28:35.789  4240  4255 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 12:28:35.789  4240  4255 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-07 12:28:35.789  4240  4255 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-07 12:28:35.789  4240  4255 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-07 12:28:35.789  4240  4255 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-07 12:28:35.789  4240  4255 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:28:35.789  4240  4255 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:28:35.789  4240  4255 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 12:28:35.793  4272  4272 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 12:28:35.811  4285  4285 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 12:28:35.811  4285  4285 D AndroidRuntime: Shutting down VM
09-07 12:28:35.820  1528  1528 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-07 12:28:35.821  4285  4285 E AndroidRuntime: FATAL EXCEPTION: main
09-07 12:28:35.821  4285  4285 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4285
09-07 12:28:35.821  4285  4285 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 12:28:35.821  4285  4285 E AndroidRuntime: 	... 10 more
09-07 12:28:35.821  1528  1528 D AndroidRuntime: Shutting down VM
09-07 12:28:35.822  1528  1528 E AndroidRuntime: FATAL EXCEPTION: main
09-07 12:28:35.822  1528  1528 E AndroidRuntime: Process: com.google.process.gapps, PID: 1528
09-07 12:28:35.822  1528  1528 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 12:28:35.822  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-07 12:28:35.822  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-07 12:28:35.822  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-07 12:28:35.822  1528  1528 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:28:35.822  1528  1528 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:28:35.822  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 12:28:35.822  1528  1528 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:28:35.822  1528  1528 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 12:28:35.822  1528  1528 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 12:28:35.822  1528  1528 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 12:28:35.822  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-07 12:28:35.822  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-07 12:28:35.822  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-07 12:28:35.822  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-07 12:28:35.822  1528  1528 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-07 12:28:35.822  1528  1528 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-07 12:28:35.822  1528  1528 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-07 12:28:35.822  1528  1528 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-07 12:28:35.822  1528  1528 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-07 12:28:35.822  1528  1528 E AndroidRuntime: 	... 8 more
09-07 12:28:35.825   874  4301 E DropBoxManagerService: Can't write: system_app_crash
09-07 12:28:35.825   874  4301 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
09-07 12:28:35.825   874  4301 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 12:28:35.825   874  4301 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 12:28:35.825   874  4301 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 12:28:35.825   874  4301 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 12:28:35.825   874  4301 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 12:28:35.825   874  4301 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 12:28:35.825   874  4301 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 12:28:35.825   874  4301 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 12:28:35.825   874  4301 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 12:28:35.825   874  4301 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 12:28:35.825   874  4301 E DropBoxManagerService: 	... 5 more
09-07 12:28:35.826   874  1716 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 12:28:35.827  4285  4285 I Process : Sending signal. PID: 4285 SIG: 9
09-07 12:28:35.830  4240  4255 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-07 12:28:35.830  4240  4255 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 12:28:35.830  4240  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 12:28:35.830  4240  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 12:28:35.830  4240  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 12:28:35.830  4240  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 12:28:35.830  4240  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 12:28:35.830  4240  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 12:28:35.830  4240  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 12:28:35.830  4240  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 12:28:35.830  4240  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 12:28:35.830  4240  4255 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 12:28:35.830  4240  4255 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 12:28:35.830  4240  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 12:28:35.830  4240  4255 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 12:28:35.830  4240  4255 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-07 12:28:35.830  4240  4255 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-07 12:28:35.830  4240  4255 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-07 12:28:35.830  4240  4255 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-07 12:28:35.830  4240  4255 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:28:35.830  4240  4255 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:28:35.830  4240  4255 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 12:28:35.831   874  4302 E DropBoxManagerService: Can't write: system_app_crash
09-07 12:28:35.831   874  4302 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
09-07 12:28:35.831   874  4302 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 12:28:35.831   874  4302 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 12:28:35.831   874  4302 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 12:28:35.831   874  4302 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 12:28:35.831   874  4302 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 12:28:35.831   874  4302 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 12:28:35.831   874  4302 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 12:28:35.831   874  4302 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 12:28:35.831   874  4302 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 12:28:35.831   874  4302 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 12:28:35.831   874  4302 E DropBoxManagerService: 	... 5 more
09-07 12:28:35.833  1528  1528 I Process : Sending signal. PID: 1528 SIG: 9
09-07 12:28:35.859   874  1716 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4285) has died
09-07 12:28:35.860   874  1716 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-07 12:28:35.869   874  1317 D WifiService: Client connection lost with reason: 4
09-07 12:28:35.870  1729  4300 E BulkCursor: Unable to get window because the remote process is dead
09-07 12:28:35.871  1729  4300 W BulkCursor: Remote process exception when closing
09-07 12:28:35.874   874   887 I ActivityManager: Start proc 4304:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 12:28:35.875   874  1972 I ActivityManager: Killing 3650:com.google.android.apps.books/u0a34 (adj 15): empty #17
09-07 12:28:35.900  4240  4255 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:28:35.905  4240  4270 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 12:28:35.905  4240  4270 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-07 12:28:35.905  4240  4270 E AndroidRuntime: Process: android.process.acore, PID: 4240
09-07 12:28:35.905  4240  4270 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 12:28:35.905  4240  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 12:28:35.905  4240  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 12:28:35.905  4240  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 12:28:35.905  4240  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 12:28:35.905  4240  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 12:28:35.905  4240  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 12:28:35.905  4240  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 12:28:35.905  4240  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 12:28:35.905  4240  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 12:28:35.905  4240  4270 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 12:28:35.905  4240  4270 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 12:28:35.905  4240  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 12:28:35.905  4240  4270 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 12:28:35.905  4240  4270 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-07 12:28:35.905  4240  4270 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-07 12:28:35.905  4240  4270 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-07 12:28:35.905  4240  4270 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-07 12:28:35.905  4240  4270 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-07 12:28:35.905  4240  4270 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-07 12:28:35.905  4240  4270 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-07 12:28:35.905  4240  4270 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:28:35.905  4240  4270 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 12:28:35.905  4240  4270 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 12:28:35.906  4240  4255 I Process : Sending signal. PID: 4240 SIG: 9
09-07 12:28:35.924   874  2226 I ActivityManager: Process com.google.process.gapps (pid 1528) has died
09-07 12:28:35.924   874  2226 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
09-07 12:28:35.924   874  2226 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
09-07 12:28:35.924   874  2226 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
09-07 12:28:35.924   874  2226 I ActivityManager: Killing 1729:com.google.android.gms/u0a11 (adj 5): depends on provider com.google.android.gsf/.gservices.GservicesProvider in dying proc com.google.process.gapps
09-07 12:28:35.976   874  2014 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@7755ec8)
09-07 12:28:35.977   874  1319 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:28:35.978   280   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
