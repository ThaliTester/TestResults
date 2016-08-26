#### Test 82728424c383411_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
08-26 10:52:18.449   875  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
08-26 10:52:19.225  3808  3808 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-26 10:52:19.229  3808  3808 D AndroidRuntime: CheckJNI is OFF
08-26 10:52:19.265  3808  3808 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-26 10:52:19.306  3808  3808 I Radio-JNI: register_android_hardware_Radio DONE
08-26 10:52:19.326  3808  3808 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 10:52:19.330   875  1389 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 10:52:19.375  2032  2401 W SearchService: Abort, client detached.
08-26 10:52:19.380  3808  3808 D AndroidRuntime: Shutting down VM
08-26 10:52:19.381  2032  2032 I HotwordDetector: Closing mic
08-26 10:52:19.382  2032  2322 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@20548f7
08-26 10:52:19.383  2032  2333 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-26 10:52:19.403   875  1998 I ActivityManager: Start proc 3817:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-26 10:52:19.451   376  2335 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-26 10:52:19.452   376  2335 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-26 10:52:19.459   376  1280 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-26 10:52:19.463  2032  2328 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-26 10:52:19.463  2032  2332 I MicroRecognitionRnrImpl: Detection finished
08-26 10:52:19.500  3817  3817 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-26 10:52:19.534  3817  3817 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-26 10:52:19.546  3817  3817 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 4450-4456)
08-26 10:52:19.546  3817  3817 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 10:52:19.568  3817  3817 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e124064}
08-26 10:52:19.568  3817  3817 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 10:52:19.568  3817  3817 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 10:52:19.576  3817  3817 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-26 10:52:19.578  3817  3817 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 10:52:19.621  3817  3817 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-26 10:52:19.635  3817  3817 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 10:52:19.635  3817  3817 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 10:52:19.635  3817  3817 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 10:52:19.635  3817  3817 I Adreno  : Build Date                       : 10/20/15
08-26 10:52:19.635  3817  3817 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 10:52:19.635  3817  3817 I Adreno  : Local Branch                     : M14
08-26 10:52:19.635  3817  3817 I Adreno  : Remote Branch                    : 
08-26 10:52:19.635  3817  3817 I Adreno  : Remote Branch                    : 
08-26 10:52:19.635  3817  3817 I Adreno  : Reconstruct Branch               : 
,08-26 10:52:19.731   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e51822b:true
,08-26 10:52:19.820  3817  3817 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-26 10:52:19.841  3817  3817 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-26 10:52:19.961  3817  3856 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-26 10:52:19.987  3817  3842 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-26 10:52:20.015  3817  3856 I OpenGLRenderer: Initialized EGL, version 1.4
,08-26 10:52:20.071   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +693ms
,08-26 10:52:20.073  1870  1870 I Keyboard.Facilitator: onFinishInput()
,08-26 10:52:20.202  3817  3817 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3817
,08-26 10:52:20.220   875   886 I ActivityManager: Killing 2970:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-26 10:52:20.273   875   886 I ActivityManager: Killing 3192:com.google.android.gm/u0a78 (adj 15): empty #18
,08-26 10:52:20.309  3817  3817 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 10:52:20.452  3817  3858 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1699284688
,08-26 10:52:20.459  3817  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 10:52:20.459  3817  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 10:52:20.459  3817  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 10:52:20.459  3817  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 10:52:20.459  3817  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-26 10:52:20.459  3817  3858 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dedaca8 added. We now have 1 listener(s)
,08-26 10:52:20.463  3817  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-26 10:52:20.464  3817  3858 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 10:52:20.465  3817  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 10:52:20.465  3817  3858 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 10:52:20.468  3817  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 10:52:20.468  3817  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 10:52:20.468  3817  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 10:52:20.468  3817  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-26 10:52:20.468  3817  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 10:52:20.468  3817  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 10:52:20.468  3817  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 10:52:20.468  3817  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 10:52:20.468  3817  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 10:52:20.468  3817  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 10:52:20.468  3817  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 10:52:20.468  3817  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 10:52:20.468  3817  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 10:52:20.468  3817  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-26 10:52:20.468  3817  3858 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e29aa7 added. We now have 1 listener(s)
08-26 10:52:20.468  3817  3858 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:20.471   875  1309 D WifiService: New client listening to asynchronous messages
08-26 10:52:20.477  3817  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 10:52:20.477  3817  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 10:52:20.477  3817  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 10:52:20.477  3817  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 10:52:20.477  3817  3858 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-26 10:52:20.480  3817  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 10:52:20.483  3817  3858 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-26 10:52:20.489  3817  3858 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-26 10:52:20.489  3817  3858 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:20.489  3817  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:20.489  3817  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:20.489  3817  3858 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:20.489  3817  3858 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:20.489  3817  3858 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:20.489  3817  3858 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:20.489  3817  3858 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:52:20.490  3817  3858 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 10:52:20.490  3817  3858 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 10:52:20.492  3817  3858 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 10:52:20.492  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:20.494  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:20.518  3817  3817 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 10:52:21.282  3817  3866 W jxcore-log: Initializing JXcore engine
,08-26 10:52:21.282  3817  3866 W jxcore-log: JXcore engine is ready
,08-26 10:52:21.322  3866  3866 W Thread-333: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8991 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-26 10:52:21.322  3866  3866 W Thread-333: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11679]" dev="sockfs" ino=11679 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-26 10:52:21.322  3866  3866 W Thread-333: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-26 10:52:21.322  3866  3866 W Thread-333: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24295]" dev="sockfs" ino=24295 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-26 10:52:21.335  3817  3866 W jxcore-log: Starting JXcore engine
,08-26 10:52:21.418  3817  3866 W jxcore-log: Platform android
08-26 10:52:21.418  3817  3866 W jxcore-log: 
,08-26 10:52:21.418  3817  3866 W jxcore-log: Process ARCH arm
08-26 10:52:21.418  3817  3866 W jxcore-log: 
,08-26 10:52:21.485   875  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-26 10:52:21.659  3817  3866 I jxcore-log: JXcore Cordova bridge is ready!
08-26 10:52:21.659  3817  3866 I jxcore-log: 
,08-26 10:52:21.659  3817  3866 W jxcore-log: JXcore engine is started
,08-26 10:52:21.668  3817  3858 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 10:52:21.674  3817  3817 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 10:52:24.512   875  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-26 10:52:27.547   875  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-26 10:52:27.930   875  1308 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-26 10:52:29.635  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 10:52:29.643  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 10:52:29.645  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 10:52:29.680  1504  3651 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-26 10:52:29.681  1504  3651 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-26 10:52:29.681  1504  3651 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 10:52:29.681  1504  3651 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 10:52:29.707  3512  3512 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-26 10:52:29.707  3512  3512 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-26 10:52:29.707  3512  3512 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,08-26 10:52:30.574   875  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-26 10:52:31.858  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 10:52:31.858  3817  3866 I jxcore-log: 
,08-26 10:52:31.861  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 10:52:31.861  3817  3866 I jxcore-log: 
,08-26 10:52:31.871  3817  3866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:31.871  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:31.871  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:31.871  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:31.871  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:31.871  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:31.871  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:31.871  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 10:52:31.877  3817  3866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 10:52:31.880  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 10:52:31.880  3817  3866 I jxcore-log: 
,08-26 10:52:31.882  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 10:52:31.882  3817  3866 I jxcore-log: 
,08-26 10:52:32.491  3817  3866 D executeNativeTests: Running unit tests
,08-26 10:52:32.543  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 10:52:32.543  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 added. We now have 2 listener(s)
08-26 10:52:32.544  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 10:52:32.544  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:52:32.544  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:52:32.544  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:32.544  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 added. We now have 2 listener(s)
08-26 10:52:32.544  3817  3866 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:32.545  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 10:52:32.556  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 10:52:32.568  3817  3866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:32.568  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:32.568  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:32.568  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:32.568  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:32.568  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:32.568  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:32.568  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 10:52:32.574  3817  3866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 10:52:32.575  3817  3866 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 10:52:32.581  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:32.587  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 10:52:32.589  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:32.590  3817  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 10:52:32.591  3817  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 10:52:32.597  3817  3866 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-26 10:52:32.598  3817  3866 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 10:52:32.598  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-26 10:52:32.599  3817  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 10:52:32.599  3817  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 10:52:32.600  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 10:52:32.601  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:32.602  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:32.603  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:32.603  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 10:52:32.604  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:52:32.604  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 10:52:32.605  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 removed from the list
08-26 10:52:32.606  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.606  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 removed from the list
08-26 10:52:32.606  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 10:52:32.607  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.608  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.608  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:32.610  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:32.610  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:32.610  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.610  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
,08-26 10:52:32.613  3817  3866 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-26 10:52:32.614  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:32.614  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:32.614  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:32.615  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:32.615  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.615  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.615  3817  3866 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 not in the list
,08-26 10:52:32.615  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.615  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.615  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:32.615  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 10:52:32.615  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.615  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.615  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.618  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:32.618  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:32.618  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.618  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
,08-26 10:52:32.625  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-26 10:52:32.625  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 10:52:32.626  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 10:52:32.626  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 10:52:32.626  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 10:52:32.626  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 10:52:32.626  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 10:52:32.626  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 10:52:32.626  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 10:52:32.626  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 10:52:32.626  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 10:52:32.626  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-26 10:52:32.626  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 10:52:32.626  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 10:52:32.627  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 10:52:32.627  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 10:52:32.627  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 10:52:32.627  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 10:52:32.627  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 10:52:32.627  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 10:52:32.627  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 10:52:32.627  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 10:52:32.627  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 10:52:32.627  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-26 10:52:32.627  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 10:52:32.628  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 10:52:32.628  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 10:52:32.628  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 10:52:32.628  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 10:52:32.628  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 10:52:32.628  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 10:52:32.628  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:32.628  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:32.628  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:32.628  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:32.628  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.629  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.629  3817  3866 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 not in the list
08-26 10:52:32.629  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.629  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.629  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:32.629  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.629  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.629  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.629  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.631  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:32.631  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:32.631  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.631  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.632  3817  3866 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 10:52:32.634  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:32.640  3817  3866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:32.640  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:32.640  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:32.640  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:32.640  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:32.640  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:32.640  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:32.640  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:52:32.644  3817  3866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:32.644  3817  3866 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 10:52:32.644  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 10:52:32.644  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 10:52:32.645  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 10:52:32.645  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:32.645  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 10:52:32.649  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:32.651  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:32.656  3817  3866 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 10:52:32.656  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 10:52:32.671  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 10:52:32.674  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 10:52:32.674  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 10:52:32.679  3817  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-26 10:52:32.685  3817  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-26 10:52:32.685  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 10:52:32.685  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 10:52:32.687  3817  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 10:52:32.689  3817  3866 D BluetoothAdapter: STATE_ON
08-26 10:52:32.696  2696  2712 D BtGatt.GattService: registerClient() - UUID=e70170b0-0589-40e8-860e-3e5f3c7adaef
08-26 10:52:32.697  2696  2753 D BtGatt.GattService: onClientRegistered() - UUID=e70170b0-0589-40e8-860e-3e5f3c7adaef, clientIf=5
08-26 10:52:32.698  3817  3828 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 10:52:32.700  2696  2900 D BtGatt.GattService: start scan with filters
,08-26 10:52:32.705  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 10:52:32.706  2696  2765 D BtGatt.ScanManager: handling starting scan
,08-26 10:52:32.706  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 10:52:32.706  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 10:52:32.707  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 10:52:32.709  2696  2765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b1b9ce
,08-26 10:52:32.711  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 10:52:32.711  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 10:52:32.712  3817  3817 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 10:52:32.714  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 10:52:32.718  3817  3866 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 10:52:32.719  2696  2753 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 10:52:32.719  2696  2753 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 10:52:32.720  2696  2765 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 10:52:32.724  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 10:52:32.724  3817  3866 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 10:52:32.725  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:32.725  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-26 10:52:32.725  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.725  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 10:52:32.725  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 10:52:32.725  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 10:52:32.725  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 10:52:32.726  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 10:52:32.727  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 10:52:32.727  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 10:52:32.728  3817  3866 D BluetoothAdapter: STATE_ON
,08-26 10:52:32.729  2696  2712 D BtGatt.GattService: stopScan() - queue size =1
,08-26 10:52:32.730  2696  2753 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 10:52:32.730  2696  2753 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 10:52:32.731  2696  2765 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 10:52:32.731  2696  2765 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 10:52:32.731  2696  2900 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 10:52:32.732  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 10:52:32.732  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 10:52:32.732  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 10:52:32.732  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 10:52:32.732  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 10:52:32.734  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 10:52:32.734  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 10:52:32.735  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 10:52:32.735  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 10:52:32.735  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 10:52:32.737  3817  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 10:52:32.738  3817  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 10:52:32.738  3817  3817 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 10:52:32.738  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 10:52:32.738  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.738  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 10:52:32.738  3817  3866 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 not in the list
08-26 10:52:32.738  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.739  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
,08-26 10:52:32.739  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:32.739  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.740  3817  3866 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 10:52:32.743  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:32.749  3817  3866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:32.749  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:32.749  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:32.749  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:32.749  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:32.749  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:32.749  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:32.749  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:52:32.750  2696  2753 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 10:52:32.750  2696  2753 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 10:52:32.752  3817  3866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:32.752  3817  3866 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 10:52:32.753  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 10:52:32.753  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 10:52:32.753  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 10:52:32.753  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:32.753  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 10:52:32.754  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:32.757  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:32.758  2696  2753 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 10:52:32.758  2696  2753 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:32.761  3817  3866 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 10:52:32.761  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 10:52:32.766  2696  2753 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 10:52:32.767  2696  2753 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:32.767  2696  2765 D BtGatt.ScanManager: stopping BLe Batch
08-26 10:52:32.767  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 10:52:32.768  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 10:52:32.768  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 10:52:32.771  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 10:52:32.771  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 10:52:32.771  3817  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 10:52:32.771  3817  3866 D BluetoothAdapter: STATE_ON
08-26 10:52:32.773  2696  2753 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 10:52:32.773  2696  2753 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:32.773  2696  2765 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 10:52:32.774  2696  2898 D BtGatt.GattService: registerClient() - UUID=7bd2b30f-9834-455a-894e-a48c8e45cdbd
08-26 10:52:32.774  2696  2753 D BtGatt.GattService: onClientRegistered() - UUID=7bd2b30f-9834-455a-894e-a48c8e45cdbd, clientIf=5
,08-26 10:52:32.775  3817  3829 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 10:52:32.777  2696  2712 D BtGatt.GattService: start scan with filters
,08-26 10:52:32.780  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 10:52:32.780  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 10:52:32.780  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 10:52:32.781  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 10:52:32.782  2696  2753 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 10:52:32.782  2696  2753 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 10:52:32.784  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 10:52:32.784  2696  2765 D BtGatt.ScanManager: handling starting scan
08-26 10:52:32.784  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 10:52:32.784  3817  3817 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 10:52:32.786  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 10:52:32.790  3817  3866 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 10:52:32.790  2696  2753 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 10:52:32.790  2696  2753 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:32.790  2696  2765 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 10:52:32.792  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 10:52:32.792  3817  3866 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 10:52:32.793  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:32.793  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 10:52:32.793  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 10:52:32.793  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 10:52:32.793  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 10:52:32.793  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 10:52:32.793  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 10:52:32.793  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 10:52:32.794  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 10:52:32.794  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 10:52:32.795  3817  3866 D BluetoothAdapter: STATE_ON
,08-26 10:52:32.795  2696  2898 D BtGatt.GattService: stopScan() - queue size =1
08-26 10:52:32.795  2696  2753 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 10:52:32.795  2696  2753 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:32.795  2696  2765 D BtGatt.ScanManager: Starting BLE batch scan
08-26 10:52:32.795  2696  2765 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 10:52:32.796  2696  2712 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 10:52:32.796  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 10:52:32.796  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 10:52:32.797  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 10:52:32.797  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 10:52:32.797  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 10:52:32.798  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 10:52:32.798  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 10:52:32.798  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 10:52:32.798  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 10:52:32.799  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 10:52:32.800  3817  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 10:52:32.800  3817  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 10:52:32.801  3817  3817 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 10:52:32.801  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:32.801  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.801  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 10:52:32.801  3817  3866 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 not in the list
08-26 10:52:32.801  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.801  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
,08-26 10:52:32.801  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:32.801  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.802  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 10:52:32.802  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.803  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:32.803  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:32.803  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 10:52:32.803  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
,08-26 10:52:32.804  3817  3866 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 10:52:32.806  2696  2753 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 10:52:32.806  2696  2753 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:32.807  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 10:52:32.810  3817  3866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:32.810  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:32.810  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:32.810  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:32.810  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:32.810  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:32.810  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:32.810  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 10:52:32.811  2696  2753 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 10:52:32.811  2696  2753 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 10:52:32.813  3817  3866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:32.813  3817  3866 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 10:52:32.813  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 10:52:32.813  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 10:52:32.815  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:32.817  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:32.818  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 10:52:32.818  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 10:52:32.818  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 10:52:32.818  2696  2753 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 10:52:32.818  2696  2753 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:32.818  2696  2765 D BtGatt.ScanManager: stopping BLe Batch
,08-26 10:52:32.821  3817  3866 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 10:52:32.821  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 10:52:32.824  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 10:52:32.824  2696  2753 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 10:52:32.824  2696  2753 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:32.824  2696  2765 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 10:52:32.825  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 10:52:32.825  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 10:52:32.827  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 10:52:32.828  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 10:52:32.828  3817  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 10:52:32.828  3817  3866 D BluetoothAdapter: STATE_ON
,08-26 10:52:32.829  2696  2753 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 10:52:32.829  2696  2753 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:32.830  2696  2900 D BtGatt.GattService: registerClient() - UUID=4b6c0eae-da26-4ee7-ad36-1c36c5a9b041
08-26 10:52:32.831  2696  2753 D BtGatt.GattService: onClientRegistered() - UUID=4b6c0eae-da26-4ee7-ad36-1c36c5a9b041, clientIf=5
08-26 10:52:32.831  3817  3828 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 10:52:32.831  2696  2712 D BtGatt.GattService: start scan with filters
,08-26 10:52:32.834  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 10:52:32.834  2696  2765 D BtGatt.ScanManager: handling starting scan
08-26 10:52:32.834  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 10:52:32.834  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 10:52:32.834  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 10:52:32.837  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 10:52:32.838  3817  3817 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 10:52:32.838  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 10:52:32.840  2696  2753 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 10:52:32.840  2696  2753 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 10:52:32.840  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-26 10:52:32.840  2696  2765 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 10:52:32.842  3817  3866 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 10:52:32.842  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:32.842  3817  3866 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 10:52:32.842  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 10:52:32.842  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 10:52:32.842  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 10:52:32.842  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 10:52:32.842  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 10:52:32.843  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 10:52:32.843  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 10:52:32.843  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 10:52:32.843  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 10:52:32.843  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 10:52:32.844  3817  3866 D BluetoothAdapter: STATE_ON
08-26 10:52:32.844  2696  2712 D BtGatt.GattService: stopScan() - queue size =1
,08-26 10:52:32.845  2696  2709 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 10:52:32.845  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 10:52:32.845  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 10:52:32.845  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 10:52:32.846  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 10:52:32.846  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 10:52:32.847  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 10:52:32.847  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 10:52:32.847  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 10:52:32.847  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 10:52:32.848  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:52:32.849  3817  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 10:52:32.849  3817  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 10:52:32.849  3817  3817 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 10:52:32.850  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 10:52:32.850  3817  3866 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 10:52:32.850  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:32.850  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:32.850  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 10:52:32.851  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 10:52:32.851  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:52:32.851  3817  3866 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 not in the list
08-26 10:52:32.851  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.851  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
,08-26 10:52:32.851  2696  2753 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 10:52:32.851  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:32.851  2696  2753 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:32.851  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:32.851  2696  2765 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 10:52:32.851  2696  2765 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 10:52:32.851  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.851  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:32.853  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 10:52:32.853  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:32.853  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.854  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.854  3817  3866 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 10:52:32.854  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 10:52:32.855  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:32.855  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:32.855  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 10:52:32.855  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.855  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.855  3817  3866 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 not in the list
08-26 10:52:32.855  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.855  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.855  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:32.855  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.855  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:32.855  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.855  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.857  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:32.857  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 10:52:32.857  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.857  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.858  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 10:52:32.858  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:32.858  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 10:52:32.858  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:32.859  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:32.859  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.859  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.859  3817  3866 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 not in the list
08-26 10:52:32.859  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.859  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.859  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:32.859  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.859  1504  2305 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-26 10:52:32.859  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.859  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.859  1504  2305 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-26 10:52:32.859  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.859  1504  2305 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 10:52:32.860  1504  2305 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-26 10:52:32.861  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:32.861  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:32.861  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.861  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.861  3817  3866 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 10:52:32.862  2696  2753 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 10:52:32.863  2696  2753 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:32.863  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:32.863  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is disco,vering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:32.863  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:32.863  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:32.863  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.863  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.863  3817  3866 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 not in the list
08-26 10:52:32.863  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.863  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.864  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:32.864  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.864  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.864  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.864  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:32.865  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:32.865  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:32.865  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.865  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.866  3817  3866 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 10:52:32.866  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 10:52:32.868  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:32.868  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:32.868  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:32.868  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.868  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.868  3817  3866 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 not in the list
,08-26 10:52:32.868  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.868  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.868  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:32.868  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.868  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.868  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.869  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.869  2696  2753 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 10:52:32.869  2696  2753 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:32.871  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:32.871  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:32.871  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.871  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.871  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 10:52:32.873  3817  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 10:52:32.873  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 10:52:32.874  3817  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 10:52:32.874  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 10:52:32.874  3817  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 10:52:32.874  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:32.874  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 10:52:32.874  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:32.874  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:32.875  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.875  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:32.875  3817  3866 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 not in the list
08-26 10:52:32.875  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.875  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.875  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:32.875  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 10:52:32.875  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.875  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.875  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:32.875  2696  2753 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 10:52:32.875  2696  2753 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:32.876  2696  2765 D BtGatt.ScanManager: stopping BLe Batch
08-26 10:52:32.876  3550  3879 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-26 10:52:32.876  3550  3879 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 10:52:32.876  3550  3879 E HttpOperation: 	at jdm.a(PG:82)
08-26 10:52:32.876  3550  3879 E HttpOperation: 	at jcs.o(PG:406)
08-26 10:52:32.876  3550  3879 E HttpOperation: 	at jcn.a(PG:1379)
08-26 10:52:32.876  3550  3879 E HttpOperation: 	at jcs.i(PG:143)
08-26 10:52:32.876  3550  3879 E HttpOperation: 	at blb.a(PG:3937)
08-26 10:52:32.876  3550  3879 E HttpOperation: 	at czp.a(PG:18188)
08-26 10:52:32.876  3550  3879 E HttpOperation: 	at czp.a(PG:9081)
08-26 10:52:32.876  3550  3879 E HttpOperation: 	at czq.run(PG:1686)
08-26 10:52:32.876  3550  3879 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 10:52:32.876  3550  3879 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 10:52:32.876  3550  3879 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 10:52:32.876  3550  3879 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 10:52:32.876  3550  3879 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 10:52:32.876  3550  3879 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 10:52:32.876  3550  3879 E HttpOperation: 	at jdj.a(PG:4091)
08-26 10:52:32.876  3550  3879 E HttpOperation: 	at jdj.a(PG:1125)
08-26 10:52:32.876  3550  3879 E HttpOperation: 	at jdm.a(PG:77)
08-26 10:52:32.876  3550  3879 E HttpOperation: 	... 12 more
08-26 10:52:32.876  3550  3879 E HttpOperation: Caused by: faj: BadAuthentication
08-26 10:52:32.876  3550  3879 E HttpOperation: 	at fal.a(PG:38)
08-26 10:52:32.876  3550  3879 E HttpOperation: 	at jdj.a(PG:4089)
08-26 10:52:32.876  3550  3879 E HttpOperation: 	... 14 more
,08-26 10:52:32.876  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:32.877  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:32.877  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.877  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.878  3817  3866 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 10:52:32.878  3817  3866 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 10:52:32.878  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-26 10:52:32.881  2696  2753 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 10:52:32.882  2696  2753 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:32.882  2696  2765 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 10:52:32.883  3817  3866 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-26 10:52:32.883  3817  3866 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 10:52:32.883  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-26 10:52:32.883  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 10:52:32.883  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 10:52:32.883  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 10:52:32.884  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410],
08-26 10:52:32.884  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 10:52:32.884  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 10:52:32.884  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 10:52:32.884  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-26 10:52:32.884  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 10:52:32.884  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 10:52:32.884  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 10:52:32.884  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-26 10:52:32.884  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 10:52:32.884  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 10:52:32.884  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 10:52:32.884  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-26 10:52:32.884  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 10:52:32.884  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 10:52:32.885  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 10:52:32.885  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-26 10:52:32.885  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 10:52:32.885  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 10:52:32.885  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 10:52:32.885  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 10:52:32.885  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 10:52:32.885  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 10:52:32.885  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 10:52:32.885  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 10:52:32.885  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 10:52:32.885  3817  3866 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 10:52:32.886  3817  3866 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 10:52:32.886  3817  3866 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 10:52:32.886  3817  3866 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 10:52:32.886  3817  3866 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 10:52:32.886  3817  3866 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 10:52:32.886  3817  3866 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 10:52:32.886  3817  3866 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 10:52:32.886  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 10:52:32.887  2696  2753 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 10:52:32.887  2696  2753 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:32.890  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 10:52:32.890  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 10:52:32.890  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 10:52:32.891  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 10:52:32.891  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 10:52:32.891  3817  3866 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 10:52:32.891  3817  3866 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 10:52:32.891  3817  3866 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 10:52:32.891  3817  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 397)
08-26 10:52:32.892  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:32.892  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:32.892  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:32.892  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:32.892  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.892  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.892  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 10:52:32.893  3817  3866 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 not in the list
08-26 10:52:32.893  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.893  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.893  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:32.893  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.893  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.893  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.893  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.894  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:32.894  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:32.894  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.894  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.895  3817  3866 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 10:52:32.895  3817  3880 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 10:52:32.895  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:32.895  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:32.895  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:32.895  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:32.895  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.896  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.896  3817  3866 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 not in the list
08-26 10:52:32.896  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.896  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.896  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:32.896  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.896  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.896  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.896  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.898  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:32.898  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:32.898  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.898  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.898  3817  3866 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 10:52:32.898  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:32.899  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:32.899  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:32.899  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:32.899  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.899  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.899  3817  3866 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 not in the list
08-26 10:52:32.899  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.899  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.899  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:32.899  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.899  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.899  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.900  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.901  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:32.901  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:32.901  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.901  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.901  3817  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 397
08-26 10:52:32.901  3817  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 397)
08-26 10:52:32.901  2696  2895 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-26 10:52:32.901  3817  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 397)
08-26 10:52:32.901  3817  3866 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 10:52:32.901  3817  3866 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 10:52:32.902  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 10:52:32.902  3817  3866 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 10:52:32.902  3817  3866 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 10:52:32.902  3817  3866 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 10:52:32.902  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 10:52:32.902  3817  3866 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 10:52:32.902  3817  3866 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 10:52:32.902  3817  3866 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 10:52:32.902  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 10:52:32.902  3817  3866 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 10:52:32.902  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:32.902  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:32.902  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:32.902  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:32.903  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.903  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.903  3817  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 397)
08-26 10:52:32.903  3817  3866 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 not in the list
08-26 10:52:32.903  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.903  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.903  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:32.903  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.903  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.903  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.903  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.905  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:32.905  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:32.905  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.905  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.906  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:32.906  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.906  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.906  3817  3866 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 not in the list
08-26 10:52:32.906  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.906  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.906  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:32.906  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.906  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.906  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.907  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.907  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:32.907  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.907  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.907  3817  3866 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 not in the list
08-26 10:52:32.907  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:32.907  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:32.907  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:32.907  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:32.907  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.907  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.907  3817  3866 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 not in the list
08-26 10:52:32.907  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.907  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.907  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:32.907  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.907  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.908  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.908  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.909  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:32.909  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:32.909  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.909  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.910  3817  3866 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 10:52:32.911  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:32.911  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 10:52:32.912  3817  3866 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 10:52:32.912  3817  3866 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 10:52:32.912  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 10:52:32.912  3817  3817 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 10:52:32.912  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 10:52:32.912  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:32.913  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 10:52:32.913  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 10:52:32.913  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 10:52:32.913  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.913  3817  3866 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 10:52:32.913  3817  3817 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 10:52:32.913  3817  3866 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 not in the list
08-26 10:52:32.913  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.913  3817  3882 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 10:52:32.913  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 10:52:32.913  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 10:52:32.913  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 10:52:32.913  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.913  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.914  3817  3882 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-26 10:52:32.914  3817  3882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 10:52:32.914  3817  3882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 10:52:32.915  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 10:52:32.915  3817  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 10:52:32.915  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.915  3817  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 10:52:32.915  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:32.915  3817  3817 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 10:52:32.915  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:32.915  3817  3817 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 10:52:32.915  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:32.915  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:32.915  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.915  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.915  3817  3866 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 not in the list
08-26 10:52:32.915  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.915  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.915  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:32.915  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.915  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.915  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 10:52:32.915  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.916  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:32.916  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:32.916  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.917  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.917  3817  3866 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 10:52:32.918  3817  3866 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 10:52:32.918  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 10:52:32.918  3817  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 10:52:32.918  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:32.918  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:32.918  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:32.918  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:32.918  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.918  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.918  3817  3866 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 not in the list
08-26 10:52:32.918  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.918  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.918  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:32.918  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.919  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.919  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.919  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.921  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:32.921  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:32.921  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.921  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.925  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:32.925  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:32.925  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:32.925  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:32.925  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.925  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.925  3817  3866 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 not in the list
08-26 10:52:32.925  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.925  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.925  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:32.925  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.925  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.925  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.925  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.926  1504  2975 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-26 10:52:32.926  1504  2975 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-26 10:52:32.926  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:32.926  1504  2975 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 10:52:32.926  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:32.926  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.926  1504  2975 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-26 10:52:32.926  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.927  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:32.927  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:32.927  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:32.927  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:32.927  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.927  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.927  3817  3866 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7500978 not in the list
08-26 10:52:32.928  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.928  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.928  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:32.928  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.928  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.928  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:32.928  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:32.929  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:32.929  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:32.929  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:32.929  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac6c851 not in the list
08-26 10:52:32.930  3817  3866 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 10:52:32.930  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 10:52:32.930  3817  3866 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 10:52:32.930  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 10:52:32.930  3817  3866 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 10:52:32.930  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 10:52:32.933  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 10:52:32.933  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 10:52:32.934  3817  3866 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 10:52:32.934  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 10:52:32.934  3817  3866 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 10:52:32.934  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 10:52:32.934  3817  3866 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 10:52:32.934  3817  3866 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 10:52:32.935  3817  3866 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 10:52:32.935  3817  3866 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 10:52:32.935  3817  3866 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 10:52:32.935  3817  3866 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 10:52:32.935  3817  3866 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 10:52:32.935  3817  3866 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 10:52:32.936  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:32.937  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@69e0cb added. We now have 2 listener(s)
08-26 10:52:32.937  3817  3866 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:32.938  3817  3866 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 10:52:32.938   875  1518 D WifiService: setWifiEnabled: true pid=3817, uid=10000
08-26 10:52:32.938   875  1518 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 10:52:32.939  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:32.939  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@794c0a8 added. We now have 3 listener(s)
08-26 10:52:32.939  3817  3866 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:32.943  3550  3879 E HttpOperation: [getmobileexperiments] Unexpected exception
08-26 10:52:32.943  3550  3879 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-26 10:52:32.943  3550  3879 E HttpOperation: 	at jdm.a(PG:82)
08-26 10:52:32.943  3550  3879 E HttpOperation: 	at jcs.o(PG:406)
08-26 10:52:32.943  3550  3879 E HttpOperation: 	at jcn.a(PG:1379)
08-26 10:52:32.943  3550  3879 E HttpOperation: 	at jcs.i(PG:143)
08-26 10:52:32.943  3550  3879 E HttpOperation: 	at hec.a(PG:42)
08-26 10:52:32.943  3550  3879 E HttpOperation: 	at hee.a(PG:102)
08-26 10:52:32.943  3550  3879 E HttpOperation: 	at czr.a(PG:65)
08-26 10:52:32.943  3550  3879 E HttpOperation: 	at kka.a(PG:108)
08-26 10:52:32.943  3550  3879 E HttpOperation: 	at czp.a(PG:19176)
08-26 10:52:32.943  3550  3879 E HttpOperation: 	at czp.a(PG:9081)
08-26 10:52:32.943  3550  3879 E HttpOperation: 	at czq.run(PG:1686)
08-26 10:52:32.943  3550  3879 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 10:52:32.943  3550  3879 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 10:52:32.943  3550  3879 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 10:52:32.943  3550  3879 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 10:52:32.943  3550  3879 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-26 10:52:32.943  3550  3879 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 10:52:32.943  3550  3879 E HttpOperation: 	at jdj.a(PG:4091)
08-26 10:52:32.943  3550  3879 E HttpOperation: 	at jdj.a(PG:1125)
08-26 10:52:32.943  3550  3879 E HttpOperation: 	at jdm.a(PG:77)
08-26 10:52:32.943  3550  3879 E HttpOperation: 	... 15 more
08-26 10:52:32.943  3550  3879 E HttpOperation: Caused by: faj: BadAuthentication
08-26 10:52:32.943  3550  3879 E HttpOperation: 	at fal.a(PG:38)
08-26 10:52:32.943  3550  3879 E HttpOperation: 	at jdj.a(PG:4089)
08-26 10:52:32.943  3550  3879 E HttpOperation: 	... 17 more
08-26 10:52:32.944  3550  3879 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-26 10:52:32.944  3550  3879 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-26 10:52:32.944  3550  3879 E ExperimentLoader: 	at jdm.a(PG:82)
08-26 10:52:32.944  3550  3879 E ExperimentLoader: 	at jcs.o(PG:406)
08-26 10:52:32.944  3550  3879 E ExperimentLoader: 	at jcn.a(PG:1379)
08-26 10:52:32.944  3550  3879 E ExperimentLoader: 	at jcs.i(PG:143)
08-26 10:52:32.944  3550  3879 E ExperimentLoader: 	at hec.a(PG:42)
08-26 10:52:32.944  3550  3879 E ExperimentLoader: 	at hee.a(PG:102)
08-26 10:52:32.944  3550  3879 E ExperimentLoader: 	at czr.a(PG:65)
08-26 10:52:32.944  3550  3879 E ExperimentLoader: 	at kka.a(PG:108)
08-26 10:52:32.944  3550  3879 E ExperimentLoader: 	at czp.a(PG:19176)
08-26 10:52:32.944  3550  3879 E ExperimentLoader: 	at czp.a(PG:9081)
08-26 10:52:32.944  3550  3879 E ExperimentLoader: 	at czq.run(PG:1686)
08-26 10:52:32.944  3550  3879 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-26 10:52:32.944  3550  3879 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-26 10:52:32.944  3550  3879 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 10:52:32.944  3550  3879 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 10:52:32.944  3550  3879 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-26 10:52:32.944  3550  3879 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-26 10:52:32.944  3550  3879 E ExperimentLoader: 	at jdj.a(PG:4091)
08-26 10:52:32.944  3550  3879 E ExperimentLoader: 	at jdj.a(PG:1125)
08-26 10:52:32.944  3550  3879 E ExperimentLoader: 	at jdm.a(PG:77)
08-26 10:52:32.944  3550  3879 E ExperimentLoader: 	... 15 more
08-26 10:52:32.944  3550  3879 E ExperimentLoader: Caused by: faj: BadAuthentication
08-26 10:52:32.944  3550  3879 E ExperimentLoader: 	at fal.a(PG:38)
08-26 10:52:32.944  3550  3879 E ExperimentLoader: 	at jdj.a(PG:4089)
08-26 10:52:32.944  3550  3879 E ExperimentLoader: 	... 17 more
08-26 10:52:32.947  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:32.948  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6f967c1 added. We now have 4 listener(s)
08-26 10:52:32.948  3817  3866 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 10:52:32.949  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:32.949  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6142b66 added. We now have 5 listener(s)
,08-26 10:52:32.949  3817  3866 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:32.952   875   885 D WifiService: setWifiEnabled: false pid=3817, uid=10000
08-26 10:52:32.952   875   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 10:52:32.956  2696  2748 D BluetoothAdapterState: Current state: ON, message: 23
08-26 10:52:32.956  2696  2748 D BluetoothAdapterProperties: Setting state to 13
08-26 10:52:32.956  2696  2748 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 10:52:32.957  2696  2748 D BluetoothAdapterProperties: onBluetoothDisable()
,08-26 10:52:32.957  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:32.957  2696  2748 I BluetoothAdapterState: Entering PendingCommandState
08-26 10:52:32.958  2696  2753 D BluetoothAdapterProperties: Scan Mode:20
08-26 10:52:32.958  2696  2748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-26 10:52:32.960  2696  2696 D HeadsetService: Received stop request...Stopping profile...
08-26 10:52:32.960  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:32.960  3817  3866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:32.960  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:32.960  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:32.960  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:32.960  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:32.960  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:32.960  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:32.960  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:52:32.961  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:32.961  3817  3866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:32.961  3817  3866 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 10:52:32.963  2696  2696 V BluetoothAdapterState: isTurningOff()=true
,08-26 10:52:32.963  2696  2696 V BluetoothAdapterState: isTurningOn()=false
08-26 10:52:32.963  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
08-26 10:52:32.963  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 10:52:32.970  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 10:52:32.971  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:32.971   875  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 10:52:32.971   875  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-26 10:52:32.971   875  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 10:52:32.972   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 10:52:32.973  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:32.975   875   875 D BluetoothHeadset: Proxy object disconnected
08-26 10:52:32.975   875   875 D BluetoothHeadset: Proxy object disconnected
08-26 10:52:32.976  1943  1956 D BluetoothHeadset: Proxy object disconnected
,08-26 10:52:32.976  1363  1377 D BluetoothHeadset: Proxy object disconnected
,08-26 10:52:32.976   875   875 D BluetoothHeadset: Proxy object disconnected
,08-26 10:52:32.977  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 10:52:32.977  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:32.977  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:32.977  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:32.977  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:32.977  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:32.977  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:32.977  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:32.977  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:52:32.977  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:32.977  3817  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:32.978   372   873 D CommandListener: Clearing all IP addresses on wlan0
,08-26 10:52:32.979  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:32.980   875   888 I ActivityManager: Start proc 3886:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-26 10:52:32.983  1504  2534 V NativeCrypto: Read error: ssl=0x9b418800: I/O error during system call, Connection timed out
,08-26 10:52:32.983  2696  2696 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-26 10:52:32.983  2696  2696 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 10:52:32.983  2696  2753 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-26 10:52:32.983  2696  2696 D BluetoothMapService: onReceive
08-26 10:52:32.984  2696  2881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 10:52:32.984  2696  2881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 10:52:32.984  2696  2696 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:32.984  2696  2881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 10:52:32.984  2696  2696 D BluetoothMapService: STATE_TURNING_OFF
08-26 10:52:32.984  2696  2753 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-26 10:52:32.984  1504  2534 V NativeCrypto: SSL shutdown failed: ssl=0x9b418800: I/O error during system call, Broken pipe
,08-26 10:52:32.984  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:32.986  2696  2696 D A2dpService: Received stop request...Stopping profile...
08-26 10:52:32.986  2696  2902 D A2dpStateMachine: Exit Disconnected: -1
08-26 10:52:32.987   875  2119 D DhcpClient: Clearing IP address
08-26 10:52:32.987   875  1998 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-26 10:52:32.988   875  2099 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-26 10:52:32.988   875   875 D BluetoothA2dp: Proxy object disconnected
08-26 10:52:32.988   875  1308 D WifiStateMachine: Start Disconnecting Watchdog 1
08-26 10:52:32.988  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 10:52:32.989  2696  2696 D HidService: Received stop request...Stopping profile...
08-26 10:52:32.989  2696  2696 D HidService: Stopping Bluetooth HidService
08-26 10:52:32.988  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:32.988  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:32.988  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:32.988  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:32.988  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:32.988  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:32.988  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:32.988  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 10:52:32.993   395   395 E Parcel  : Reading a NULL string not supported here.
08-26 10:52:32.994   875  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 10:52:32.994  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:32.994  3817  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:32.995   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-26 10:52:32.995  2696  2696 D HealthService: Received stop request...Stopping profile...
08-26 10:52:32.995   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-26 10:52:32.996   372   873 D CommandListener: Setting iface cfg
08-26 10:52:32.996   372   873 D CommandListener: Clearing all IP addresses on wlan0
08-26 10:52:32.996  1363  1363 D HeadsetProfile: Bluetooth service disconnected
08-26 10:52:32.996  1363  1363 D BluetoothA2dp: Proxy object disconnected
08-26 10:52:32.996  1363  1363 D BluetoothInputDevice: Proxy object disconnected
,08-26 10:52:32.996  1363  1363 D HidProfile: Bluetooth service disconnected
08-26 10:52:32.998  2696  2696 D PanService: Received stop request...Stopping profile...
08-26 10:52:32.999  2696  2696 D BluetoothMapService: MAP Service closeService in
,08-26 10:52:32.999  2696  2696 D BluetoothMapMasInstance0: MAP Service shutdown
08-26 10:52:32.999  2696  2696 D ObexServerSockets0: shutdown(block = true)
08-26 10:52:32.999   875  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-26 10:52:32.999  2696  2907 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-26 10:52:33.000  2696  2696 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 10:52:33.000  2696  2908 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-26 10:52:33.000  2696  2895 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-26 10:52:33.000  2696  2696 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 10:52:33.000  2696  2696 I BtOppRfcommListener: stopping Accept Thread
08-26 10:52:33.000  2696  3433 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-26 10:52:33.000  1363  1363 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 10:52:33.000  1363  1363 D PanProfile: Bluetooth service disconnected
08-26 10:52:33.001  2696  3433 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 10:52:33.002   875  2099 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-26 10:52:33.002  2696  2696 D BluetoothMapService: Received stop request...Stopping profile...
08-26 10:52:33.002  2696  2696 D BluetoothMapService: stop()
08-26 10:52:33.003  2696  2696 D BluetoothMapAppObserver: deinitObservers()
08-26 10:52:33.003  2696  2696 D BluetoothMapAppObserver: removeReceiver()
08-26 10:52:33.004   875  1308 D WifiConfigStore: Retrieve network priorities after PNO.
08-26 10:52:33.007  1363  1363 D BluetoothMap: Proxy object disconnected
08-26 10:52:33.007  2696  2696 V BluetoothAdapterState: isTurningOff()=true
,08-26 10:52:33.007  1363  1363 D MapProfile: Bluetooth service disconnected
08-26 10:52:33.007  2696  2696 V BluetoothAdapterState: isTurningOn()=false
08-26 10:52:33.007  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
08-26 10:52:33.007  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
08-26 10:52:33.008  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:33.008  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:33.008  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:33.008  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:33.008  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:33.008  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:33.008  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:33.008  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:33.008  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:33.009  2696  2881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 10:52:33.009  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:33.010  3817  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 10:52:33.010  2696  2881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 10:52:33.011  2696  2753 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-26 10:52:33.011  2696  2881 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 10:52:33.011  2696  2881 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 10:52:33.011  2696  2881 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 10:52:33.011  2696  2881 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 10:52:33.013  2696  2696 V BluetoothAdapterState: isTurningOff()=true
08-26 10:52:33.013  2696  2696 V BluetoothAdapterState: isTurningOn()=false
08-26 10:52:33.013  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
08-26 10:52:33.013  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
08-26 10:52:33.013  2696  2696 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 10:52:33.013  2696  2753 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 10:52:33.014  2696  2696 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 10:52:33.014  2696  2696 V BluetoothAdapterState: isTurningOff()=true
08-26 10:52:33.014  2696  2696 V BluetoothAdapterState: isTurningOn()=false
08-26 10:52:33.014  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 10:52:33.014  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
08-26 10:52:33.014  2696  2696 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 10:52:33.014  2696  2753 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-26 10:52:33.015  2696  2696 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 10:52:33.015  2696  2696 V BluetoothAdapterState: isTurningOff()=true
08-26 10:52:33.015  2696  2696 V BluetoothAdapterState: isTurningOn()=false
08-26 10:52:33.015  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
08-26 10:52:33.015  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
08-26 10:52:33.015  2696  2696 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 10:52:33.016  2696  2696 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 10:52:33.016  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:33.016  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:33.016  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:33.016  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:33.016  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:33.016  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:33.016  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:33.016  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:33.016  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:33.016   875  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 10:52:33.017  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:33.017  3817  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:33.021  2696  2696 D BluetoothMapService: MAP Service closeService in
08-26 10:52:33.021  2696  2696 V BluetoothAdapterState: isTurningOff()=true
08-26 10:52:33.021  2696  2696 V BluetoothAdapterState: isTurningOn()=false
,08-26 10:52:33.021  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
08-26 10:52:33.021  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
08-26 10:52:33.026  2696  2748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-26 10:52:33.026  2696  2748 D BluetoothAdapterProperties: Setting state to 15
08-26 10:52:33.026  2696  2748 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 10:52:33.027  2696  2748 I BluetoothAdapterState: Entering BleOnState
08-26 10:52:33.027  1363  2084 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 10:52:33.027  2696  2696 D BluetoothMapService: cleanup()
08-26 10:52:33.027  2696  2696 D BluetoothMapService: MAP Service closeService in
08-26 10:52:33.028  1363  1377 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 10:52:33.028   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 10:52:33.029  1363  1376 D BluetoothMap: onBluetoothStateChange: up=false
08-26 10:52:33.029  1943  2129 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 10:52:33.029   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 10:52:33.029  1363  2084 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 10:52:33.030  1363  1377 D BluetoothPan: onBluetoothStateChange on: false
08-26 10:52:33.030   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 10:52:33.030  1363  1376 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 10:52:33.031   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 10:52:33.031  2696  2748 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-26 10:52:33.031  2696  2748 D BluetoothAdapterProperties: Setting state to 16
08-26 10:52:33.031  2696  2748 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-26 10:52:33.032  2696  2748 D BluetoothAdapterProperties: onBleDisable
08-26 10:52:33.032  2696  2748 I BluetoothAdapterState: Entering PendingCommandState
08-26 10:52:33.032  2696  2749 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-26 10:52:33.033  2696  2881 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 10:52:33.033  2696  2881 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 10:52:33.034  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:33.033  2696  2753 D BluetoothAdapterProperties: Scan Mode:20
08-26 10:52:33.035  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:33.037  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:33.038  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:33.044  1884  2304 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 10:52:33.049   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-26 10:52:33.064   875  2127 D DhcpClient: Receive thread stopped
08-26 10:52:33.065   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 127500, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
08-26 10:52:33.067   875   884 I art     : Background partial concurrent mark sweep GC freed 46698(2MB) AllocSpace objects, 11(248KB) LOS objects, 33% free, 29MB/44MB, paused 1.099ms total 104.263ms
08-26 10:52:33.069   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-26 10:52:33.070   875  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-26 10:52:33.070   875  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:33.074   875   892 D Tethering: MasterInitialState.processMessage what=3
08-26 10:52:33.075  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:33.076  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:33.080  3379  3379 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@dedaca8 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-26 10:52:33.086  3886  3886 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-26 10:52:33.100  3886  3886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 10:52:33.106  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 10:52:33.106   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b1fa1cb:true
,08-26 10:52:33.118   875  1959 I ActivityManager: Start proc 3908:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-26 10:52:33.122   372   873 E Netd    : netlink response contains error (No such file or directory)
,08-26 10:52:33.123   875  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 10:52:33.128  3886  3886 D LocalBluetoothProfileManager: Adding local MAP profile
08-26 10:52:33.129  3886  3886 D BluetoothMap: Create BluetoothMap proxy object
,08-26 10:52:33.136  3886  3886 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-26 10:52:33.147  3908  3908 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-26 10:52:33.150  3886  3886 D DockEventReceiver: finishStartingService: stopping service
,08-26 10:52:33.156   875  1959 I ActivityManager: Killing 3379:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-26 10:52:33.243  2696  2753 I bt_hci  : shut_down
,08-26 10:52:33.252  2696  2767 I bt_vendor: low_power_mode_cb
08-26 10:52:33.252  2696  2767 D bt_hwcfg: hw_epilog_process
,08-26 10:52:33.271  2696  2767 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-26 10:52:33.271  2696  2767 I bt_vendor: epilog_cb
,08-26 10:52:33.271  2696  2767 I bt_hci  : epilog_finished_callback
,08-26 10:52:33.276  2696  2753 I bt_hci_h4: hal_close
,08-26 10:52:33.276  2696  2753 I bt_userial_vendor: device fd = 51 close
,08-26 10:52:33.330  3908  3908 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 10:52:33.330  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 10:52:33.330  3908  3908 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 10:52:33.330  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 10:52:33.330  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 10:52:33.331  3908  3908 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 10:52:33.331  3908  3908 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 10:52:33.331  3908  3908 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.r.k.d(PG:583)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 10:52:33.331  3908  3908 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 10:52:33.331  3908  3908 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 10:52:33.331  3908  3908 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 10:52:33.331  3908  3908 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 10:52:33.386   875  1679 I ActivityManager: Start proc 3938:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-26 10:52:33.387   875  1679 I ActivityManager: Killing 3563:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-26 10:52:33.416  3817  3817 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 10:52:33.420  2696  2749 D bt_stack_manager: event_shut_down_stack finished.
,08-26 10:52:33.422  2696  2748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 10:52:33.427  2696  2696 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 10:52:33.427  2696  2748 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-26 10:52:33.428  2696  2696 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 10:52:33.428  2696  2696 D BtGatt.GattService: stop()
08-26 10:52:33.428  2696  2696 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 10:52:33.436  2696  2696 V BluetoothAdapterState: isTurningOff()=false
08-26 10:52:33.436  2696  2696 V BluetoothAdapterState: isTurningOn()=false
08-26 10:52:33.436  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
08-26 10:52:33.436  2696  2696 V BluetoothAdapterState: isBleTurningOff()=true
,08-26 10:52:33.436  2696  2748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-26 10:52:33.437  2696  2748 D BluetoothAdapterProperties: Setting state to 10
,08-26 10:52:33.437  2696  2748 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-26 10:52:33.438  2696  2748 I BluetoothAdapterState: Entering OffState
,08-26 10:52:33.440   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-26 10:52:33.463  3938  3938 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-26 10:52:33.483  2696  2696 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-26 10:52:33.483  2696  2696 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-26 10:52:33.483  2696  2696 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 10:52:33.484  2696  2749 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-26 10:52:33.486  2696  2749 D bt_stack_manager: event_clean_up_stack finished.
,08-26 10:52:33.497  2696  2696 I art     : System.exit called, status: 0
,08-26 10:52:33.497  2696  2696 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 10:52:33.558   875  1679 I ActivityManager: Process com.android.bluetooth (pid 2696) has died
08-26 10:52:33.560  3938  3938 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-26 10:52:33.591  3886  3886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 10:52:33.641   875  1998 I ActivityManager: Start proc 3966:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-26 10:52:33.651  3886  3886 D DockEventReceiver: finishStartingService: stopping service
,08-26 10:52:33.668  3908  3932 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 10:52:33.698   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@339e1ab:true
,08-26 10:52:33.724  3966  3966 D AdapterServiceConfig: Adding HeadsetService
08-26 10:52:33.724  3966  3966 D AdapterServiceConfig: Adding A2dpService
08-26 10:52:33.724  3966  3966 D AdapterServiceConfig: Adding HidService
08-26 10:52:33.724  3966  3966 D AdapterServiceConfig: Adding HealthService
,08-26 10:52:33.725  3966  3966 D AdapterServiceConfig: Adding PanService
,08-26 10:52:33.726  3966  3966 D AdapterServiceConfig: Adding GattService
,08-26 10:52:33.726  3966  3966 D AdapterServiceConfig: Adding BluetoothMapService
08-26 10:52:33.728   875  3081 I ActivityManager: Killing 3446:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-26 10:52:33.758  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 10:52:33.786  1699  1699 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 10:52:33.791  1699  1699 D SystemUpdateService: onCreate
,08-26 10:52:33.798  1699  1699 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 10:52:33.805  1699  3979 I SystemUpdateService: active receiver: enabled
,08-26 10:52:33.809  1699  3979 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 10:52:33.809  1699  1699 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 10:52:33.811  1699  3979 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-26 10:52:33.811  1699  3979 I SystemUpdateService: now status is 0 (complete)
08-26 10:52:33.811  1699  3979 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip,
08-26 10:52:33.811  1699  3979 I SystemUpdateService: file has been verified
,08-26 10:52:33.811  1699  3979 I SystemUpdateService: OTA package size = 12249756
,08-26 10:52:33.814  1699  3979 I SystemUpdateService: showing system update notification
,08-26 10:52:33.818  1699  2512 I iu.UploadsManager: num queued entries: 0
,08-26 10:52:33.819  1699  2512 I iu.UploadsManager: num updated entries: 0
,08-26 10:52:33.822  1699  2512 I iu.SyncManager: NEXT; no task
,08-26 10:52:33.833  1699  1699 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 10:52:33.835  1699  1699 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 10:52:33.835  1699  1699 D SystemUpdateService: onDestroy
,08-26 10:52:33.852   875  1992 I ActivityManager: Start proc 3981:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-26 10:52:33.901  3981  3981 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-26 10:52:33.904  3981  3981 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:33.910  3981  3981 D SprintDMHelper: simOperator: 
,08-26 10:52:33.910  3981  3981 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 10:52:33.947   875   886 I ActivityManager: Start proc 3994:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-26 10:52:33.948   875   886 I ActivityManager: Killing 3493:android.process.acore/u0a5 (adj 15): empty #17
,08-26 10:52:34.130  2259  4008 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-26 10:52:34.132   875  1998 I ActivityManager: Start proc 4009:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-26 10:52:34.134   875  3081 I ActivityManager: Killing 3675:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-26 10:52:34.212  4009  4009 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-26 10:52:34.260  4009  4009 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-26 10:52:34.260  4009  4009 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 10:52:34.260  4009  4009 I GAv4    :   adb logcat -s GAv4
,08-26 10:52:34.279  4009  4009 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-26 10:52:34.287  4009  4009 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-26 10:52:34.314  4009  4026 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 10:52:34.415  4009  4009 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-26 10:52:34.460  4009  4009 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-26 10:52:34.468  4009  4009 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9374-9378)
08-26 10:52:34.468  4009  4009 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 10:52:34.475  4009  4009 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4398fd8}
08-26 10:52:34.475  4009  4009 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 10:52:34.476  4009  4009 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 10:52:34.482  4009  4009 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-26 10:52:34.484  4009  4009 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 10:52:34.505  4009  4009 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-26 10:52:34.520  4009  4009 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 10:52:34.520  4009  4009 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 10:52:34.520  4009  4009 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 10:52:34.520  4009  4009 I Adreno  : Build Date                       : 10/20/15
08-26 10:52:34.520  4009  4009 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 10:52:34.520  4009  4009 I Adreno  : Local Branch                     : M14
08-26 10:52:34.520  4009  4009 I Adreno  : Remote Branch                    : 
08-26 10:52:34.520  4009  4009 I Adreno  : Remote Branch                    : 
08-26 10:52:34.520  4009  4009 I Adreno  : Reconstruct Branch               : 
,08-26 10:52:34.576  4009  4009 I NSApplication: Starting up...
,08-26 10:52:34.586  4009  4055 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-26 10:52:34.620   875  1984 I ActivityManager: Start proc 4060:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-26 10:52:34.621   875  1984 I ActivityManager: Killing 3692:com.android.musicfx/u0a18 (adj 15): empty #17
,08-26 10:52:34.694  4060  4060 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-26 10:52:34.909   875  1962 I ActivityManager: Killing 2093:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-26 10:52:35.964   875  1962 D WifiService: setWifiEnabled: true pid=3817, uid=10000
,08-26 10:52:35.964   875  1962 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 10:52:35.975   875  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-26 10:52:35.985  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 10:52:35.985  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:35.985  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:35.985  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:35.985  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:35.985  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:35.985  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:35.985  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:35.985  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 10:52:35.986  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 10:52:35.988  3817  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 10:52:35.991  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 10:52:35.992  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:35.992  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:35.992  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:35.992  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:35.992  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:35.992  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:35.992  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:35.992  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 10:52:35.993  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 10:52:35.994  3817  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 10:52:36.012   875  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-26 10:52:36.015   875  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-26 10:52:36.017   875  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-26 10:52:36.020   875  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 10:52:36.021   875  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-26 10:52:36.021   875  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-26 10:52:36.022   875  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 10:52:36.037   372   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 10:52:36.037   875  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=11.00 rxSuccessRate=15.50 delta 1000 -> 994
08-26 10:52:36.038   372   873 D CommandListener: Setting iface cfg
,08-26 10:52:36.039   875  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-26 10:52:36.039   875  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 10:52:36.047   875  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-26 10:52:36.047   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 10:52:36.048   875  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 10:52:36.049   875  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 10:52:36.056   875  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 10:52:36.172   875  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 10:52:36.179  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 10:52:36.611  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 10:52:36.662  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 10:52:36.663  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 10:52:36.664   875  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 10:52:36.681   875  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-26 10:52:36.682   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 10:52:36.682   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 10:52:36.713   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 10:52:36.730   372   873 D CommandListener: Setting iface cfg
,08-26 10:52:36.733   875  1308 D WifiStateMachine: Start Dhcp Watchdog 2
,08-26 10:52:36.744   875  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 10:52:36.745   875  1310 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-26 10:52:36.746   875  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 10:52:36.778   875  4083 D DhcpClient: Receive thread started
,08-26 10:52:36.861   875  1308 E native  : do suspend false
,08-26 10:52:36.881   875  2119 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 10:52:36.902   875  4083 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172691, domain null
,08-26 10:52:36.903   875  2119 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172691 seconds
,08-26 10:52:36.906   875  2119 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 10:52:36.938   875  4083 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 10:52:36.940   875  2119 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 10:52:36.945   372   873 D CommandListener: Setting iface cfg
,08-26 10:52:36.956   875  2119 D DhcpClient: Scheduling renewal in 86399s
,08-26 10:52:36.956   875  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 10:52:36.971   875  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 10:52:36.973   875  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 10:52:36.975   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 10:52:36.980   875  1310 D ConnectivityService: Adding iface wlan0 to network 101
,08-26 10:52:36.985   875  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 10:52:37.050   875  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 10:52:37.050   875  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-26 10:52:37.052   875  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-26 10:52:37.054   875  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-26 10:52:37.056   875  1310 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-26 10:52:37.067   875  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 10:52:37.073   875  1310 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-26 10:52:37.073   875  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-26 10:52:37.073   875  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-26 10:52:37.074   875  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: [],
08-26 10:52:37.074   875  1310 D ConnectivityService:    accepting network in place of null
,08-26 10:52:37.074   875  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 10:52:37.075   875  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 10:52:37.093   875  4082 D NetlinkSocketObserver: NeighborEvent{elapsedMs=132003, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 10:52:37.123   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 10:52:37.159   875  4081 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.78,2a00:1450:4001:806::200e
,08-26 10:52:37.171   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 10:52:37.181   875  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-26 10:52:37.181   875  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:37.190   875  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-26 10:52:37.199   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-26 10:52:37.213  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 10:52:37.214  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:37.214  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:37.214  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:37.214  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:37.214  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:37.214  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:37.214  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:37.214  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 10:52:37.214  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:37.214  3817  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 10:52:37.217  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 10:52:37.217  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:37.217  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:37.217  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:37.217  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:37.217  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:37.217  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:37.217  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:37.217  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:52:37.217  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:37.217  3817  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:37.220  1699  1699 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 10:52:37.223  1699  1699 D SystemUpdateService: onCreate
,08-26 10:52:37.225  1699  1699 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 10:52:37.228  1699  4093 I SystemUpdateService: active receiver: enabled
,08-26 10:52:37.232  1699  4093 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 10:52:37.236  1699  4093 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-26 10:52:37.236  1699  4093 I SystemUpdateService: now status is 0 (complete)
,08-26 10:52:37.236  1699  4093 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 10:52:37.236  1699  4093 I SystemUpdateService: file has been verified
08-26 10:52:37.236  1699  4093 I SystemUpdateService: OTA package size = 12249756
,08-26 10:52:37.238   875  4081 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 08:52:37 GMT], X-Android-Received-Millis=[1472201557237], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472201557209]}
08-26 10:52:37.239   875  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-26 10:52:37.239   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-26 10:52:37.239   875  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 10:52:37.241   875  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 10:52:37.246  1699  4093 I SystemUpdateService: showing system update notification
,08-26 10:52:37.250  1699  1699 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 10:52:37.253  1699  2512 I iu.UploadsManager: num queued entries: 0
,08-26 10:52:37.254  1699  2512 I iu.UploadsManager: num updated entries: 0
,08-26 10:52:37.255  1699  1699 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 10:52:37.256  1699  2512 I iu.SyncManager: NEXT; no task
08-26 10:52:37.256  1699  4098 I MDM     : [172] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-26 10:52:37.256  1699  4098 W BaseAppContext: Using Auth Proxy for data requests.
08-26 10:52:37.256  1699  1699 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-26 10:52:37.257  1699  4098 V GoogleAuthProtoRequest: [172] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 10:52:37.259  3981  3981 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:37.264  3981  3981 D SprintDMHelper: simOperator: 
08-26 10:52:37.264  3981  3981 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-26 10:52:37.265  1699  1699 D SystemUpdateService: onDestroy
,08-26 10:52:37.292  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-26 10:52:37.292  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-26 10:52:37.292  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 10:52:37.292  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 10:52:37.313  1699  4098 E MDM     : [172] SitrepService.a: Error sending sitrep.
,08-26 10:52:37.399  2259  4101 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 10:52:37.573  1699  1699 I GCM     : Message from null null
08-26 10:52:37.574  1699  1699 E GCM     : Dropping message from null
,08-26 10:52:38.180   875  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-26 10:52:38.816   875  1995 I ActivityManager: Killing 3713:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-26 10:52:38.970   875   886 D WifiService: setWifiEnabled: false pid=3817, uid=10000
08-26 10:52:38.971   875   886 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 10:52:38.990  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 10:52:38.992   875  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 10:52:38.992   875  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-26 10:52:38.992   875  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 10:52:38.992   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 10:52:39.007   875  2119 D DhcpClient: Clearing IP address
,08-26 10:52:39.007   372   873 D CommandListener: Clearing all IP addresses on wlan0
,08-26 10:52:39.009   372   873 D CommandListener: Setting iface cfg
,08-26 10:52:39.021  1504  4106 V NativeCrypto: Read error: ssl=0x9b418800: I/O error during system call, Connection timed out
,08-26 10:52:39.023  1504  4106 V NativeCrypto: SSL shutdown failed: ssl=0x9b418800: I/O error during system call, Broken pipe
,08-26 10:52:39.027   875  1308 D WifiStateMachine: Start Disconnecting Watchdog 2
08-26 10:52:39.027   875  1679 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-26 10:52:39.028   875  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 10:52:39.028   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 10:52:39.028   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-26 10:52:39.030   372   873 D CommandListener: Clearing all IP addresses on wlan0
08-26 10:52:39.035   395   395 E Parcel  : Reading a NULL string not supported here.
08-26 10:52:39.033   875  4081 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-26 10:52:39.039   875  4081 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on <unknown ssid>, connectivitycheck.gstatic.com=172.217.22.78,2a00:1450:4001:806::200e
,08-26 10:52:39.046   875  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-26 10:52:39.047   875  4083 D DhcpClient: Receive thread stopped
08-26 10:52:39.050   875  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 10:52:39.054   875  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 10:52:39.057   875  4081 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:806::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-26 10:52:39.061  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 10:52:39.061  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:39.061  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:39.061  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:39.061  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:39.061  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:39.061  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:39.061  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:39.061  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:39.061  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:39.061  3817  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:39.062  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 10:52:39.062  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:39.062  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:39.062  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
08-26 10:52:39.062  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:39.062  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:39.062  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:39.062  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:39.062  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:39.062  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:39.062  3817  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:39.063  1884  2304 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 10:52:39.093   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 10:52:39.109   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 10:52:39.110   875  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 10:52:39.110   875  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:39.112   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-26 10:52:39.114  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:39.115  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:39.122  1699  1699 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) },
,08-26 10:52:39.124  1699  1699 D SystemUpdateService: onCreate
,08-26 10:52:39.126  1699  1699 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 10:52:39.131  1699  4115 I SystemUpdateService: active receiver: enabled
,08-26 10:52:39.136  1699  1699 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 10:52:39.136  1699  4115 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 10:52:39.141  1699  4115 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-26 10:52:39.141  1699  4115 I SystemUpdateService: now status is 0 (complete)
08-26 10:52:39.142  1699  4115 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 10:52:39.142  1699  4115 I SystemUpdateService: file has been verified
08-26 10:52:39.142  1699  4115 I SystemUpdateService: OTA package size = 12249756
08-26 10:52:39.141  1699  2512 I iu.UploadsManager: num queued entries: 0
,08-26 10:52:39.148  1699  1699 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 10:52:39.148  1699  1699 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 10:52:39.151  3981  3981 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:39.155  3981  3981 D SprintDMHelper: simOperator: 
08-26 10:52:39.155  3981  3981 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 10:52:39.169  1699  2512 I iu.UploadsManager: num updated entries: 0
,08-26 10:52:39.178   372   873 E Netd    : netlink response contains error (No such file or directory)
,08-26 10:52:39.178   875  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 10:52:39.180  2259  4120 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-26 10:52:39.183  1699  2512 I iu.SyncManager: NEXT; no task
,08-26 10:52:39.187  1699  4115 I SystemUpdateService: showing system update notification
,08-26 10:52:39.194  1699  1699 D SystemUpdateService: onDestroy
,08-26 10:52:42.010   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7be98c5:true
,08-26 10:52:42.010  3966  3966 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 10:52:42.014  3966  3966 I bt_bluedroid: init
,08-26 10:52:42.015  3966  4122 I BluetoothAdapterState: Entering OffState
,08-26 10:52:42.021  3966  4123 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 10:52:42.021  3966  4123 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-26 10:52:42.021  3966  4123 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-26 10:52:42.022  3966  4123 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 10:52:42.023  3966  3966 I bt_bluedroid: get_profile_interface socket
08-26 10:52:42.026  3966  3966 I bt_bluedroid: get_profile_interface sdp
08-26 10:52:42.030  3966  4126 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 10:52:42.031  3966  4126 D BluetoothAdapterProperties: Name is: Nexus 6
08-26 10:52:42.033  3966  3977 I bt_bluedroid: config_hci_snoop_log
,08-26 10:52:42.038   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 10:52:42.054  3966  4122 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 10:52:42.054  3966  4122 D BluetoothAdapterProperties: Setting state to 14
,08-26 10:52:42.055  3966  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-26 10:52:42.056  3966  4122 D BluetoothBondStateMachine: make
,08-26 10:52:42.059  3966  4129 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 10:52:42.063  3966  4122 I BluetoothAdapterState: Entering PendingCommandState
,08-26 10:52:42.065  3966  3966 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 10:52:42.068  3966  3966 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b1b9ce
,08-26 10:52:42.068  3966  3966 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 10:52:42.069  3966  3966 D BtGatt.GattService: Received start request. Starting profile...
,08-26 10:52:42.069  3966  3966 D BtGatt.GattService: start()
08-26 10:52:42.069  3966  3966 I bt_bluedroid: get_profile_interface gatt
,08-26 10:52:42.070  3966  3966 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b1b9ce
08-26 10:52:42.070  3966  3966 D BtGatt.AdvertiseManager: advertise manager created
,08-26 10:52:42.075  3966  3966 V BluetoothAdapterState: isTurningOff()=false
,08-26 10:52:42.075  3966  3966 V BluetoothAdapterState: isTurningOn()=false
,08-26 10:52:42.075  3966  3966 V BluetoothAdapterState: isBleTurningOn()=true
,08-26 10:52:42.075  3966  3966 V BluetoothAdapterState: isBleTurningOff()=false
08-26 10:52:42.076  3966  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-26 10:52:42.076  3966  4122 I bt_bluedroid: enable
08-26 10:52:42.076  3966  4123 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-26 10:52:42.077  3966  4123 I bt_hci  : start_up
,08-26 10:52:42.085  3966  4123 I bt_vendor: alloc value 0xb39e9189
,08-26 10:52:42.085  3966  4123 I bt_vendor: init
08-26 10:52:42.085  3966  4123 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-26 10:52:42.085  3966  4123 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 10:52:42.193  3966  4123 D bt_hci  : start_up starting async portion
,08-26 10:52:42.194  3966  4132 I bt_hci  : event_finish_startup
08-26 10:52:42.194  3966  4132 I bt_hci_h4: hal_open
08-26 10:52:42.194  3966  4132 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 10:52:42.205  3966  4132 I bt_userial_vendor: device fd = 51 open
,08-26 10:52:42.233  3966  4132 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 10:52:42.265  3966  4132 D bt_hwcfg: Chipset BCM4354A2
,08-26 10:52:42.265  3966  4132 D bt_hwcfg: Target name = [BCM4354A2]
08-26 10:52:42.266  3966  4132 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 10:52:42.929  3966  4132 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 10:52:42.931  3966  4132 D bt_hwcfg: Settlement delay -- 100 ms
,08-26 10:52:42.932  3966  4132 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 10:52:43.049  3966  4132 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 10:52:43.050  3966  4132 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 10:52:43.078  3966  4132 I bt_hwcfg: vendor lib fwcfg completed
,08-26 10:52:43.078  3966  4132 I bt_vendor: firmware callback
08-26 10:52:43.079  3966  4132 I bt_hci  : firmware_config_callback
,08-26 10:52:43.091  3966  4134 I bt_btu  : btu_task pending for preload complete event
,08-26 10:52:43.092  3966  4134 I bt_btu_task: Bluetooth chip preload is complete
,08-26 10:52:43.092  3966  4134 I bt_btu  : btu_task received preload complete event
,08-26 10:52:43.102  3966  4134 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 10:52:43.102  3966  4134 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-26 10:52:43.103  3966  4134 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-26 10:52:43.103  3966  4134 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 10:52:43.103  3966  4134 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 10:52:43.103  3966  4134 I         : BTE_InitTraceLevels -- TRC_A2D
,08-26 10:52:43.104  3966  4134 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 10:52:43.104  3966  4134 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 10:52:43.104  3966  4134 I         : BTE_InitTraceLevels -- TRC_GAP
,08-26 10:52:43.104  3966  4134 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 10:52:43.105  3966  4134 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 10:52:43.105  3966  4134 I         : BTE_InitTraceLevels -- TRC_GATT
,08-26 10:52:43.105  3966  4134 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 10:52:43.105  3966  4134 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 10:52:43.106  3966  4134 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 10:52:43.236  3966  4134 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3966d9d
,08-26 10:52:43.237  3966  4134 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3966d9d 
,08-26 10:52:43.259  3966  4126 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-26 10:52:43.261  3966  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 10:52:43.262  3966  4126 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 10:52:43.265  3966  4126 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 10:52:43.271  3966  4126 D BluetoothAdapterProperties: Scan Mode:20
,08-26 10:52:43.272  3966  4126 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 10:52:43.272  3966  4126 D bt_hci  : do_postload posting postload work item
08-26 10:52:43.272  3966  4132 I bt_hci  : event_postload
,08-26 10:52:43.272  3966  4132 I bt_vendor: sco_config_cb
08-26 10:52:43.272  3966  4132 I bt_hci  : sco_config_callback postload finished.
08-26 10:52:43.276  3966  4126 D bt_bte_conf: Device ID record 1 : primary
,08-26 10:52:43.276  3966  4126 D bt_bte_conf:   vendorId            = 000f
08-26 10:52:43.276  3966  4126 D bt_bte_conf:   vendorIdSource      = 0001
08-26 10:52:43.276  3966  4126 D bt_bte_conf:   product             = 1200
,08-26 10:52:43.276  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:43.276  3966  4126 D bt_bte_conf:   version             = 1436
,08-26 10:52:43.277  3966  4126 D bt_bte_conf:   clientExecutableURL = 
,08-26 10:52:43.277  3966  4126 D bt_bte_conf:   serviceDescription  = 
08-26 10:52:43.277  3966  4126 D bt_bte_conf:   documentationURL    = 
08-26 10:52:43.277  3966  4126 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-26 10:52:43.278  3966  4123 D bt_stack_manager: event_start_up_stack finished
08-26 10:52:43.278  3966  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-26 10:52:43.279  3966  4122 D BluetoothAdapterProperties: Setting state to 15
,08-26 10:52:43.279  3966  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-26 10:52:43.280  3966  4122 I BluetoothAdapterState: Entering BleOnState
08-26 10:52:43.283  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:43.286  3966  4132 I bt_vendor: low_power_mode_cb
08-26 10:52:43.289  3966  4122 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-26 10:52:43.289  3966  4122 D BluetoothAdapterProperties: Setting state to 11
08-26 10:52:43.290  3966  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-26 10:52:43.297  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:43.298  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:43.303  3966  3966 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b1b9ce
08-26 10:52:43.304  3966  3966 D HeadsetService: Received start request. Starting profile...
,08-26 10:52:43.308  3966  3966 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 10:52:43.308  3966  3966 D HeadsetStateMachine: make
,08-26 10:52:43.321  3966  4122 I BluetoothAdapterState: Entering PendingCommandState
,08-26 10:52:43.321  3966  3966 D HeadsetStateMachine: max_hf_connections = 1
,08-26 10:52:43.322  3966  3966 I bt_bluedroid: get_profile_interface handsfree
08-26 10:52:43.322  3966  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-26 10:52:43.322  3966  4126 E bt_btif : btif_hf_upstreams_evt: Invalid index 3,
,08-26 10:52:43.327  3966  3966 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b1b9ce
,08-26 10:52:43.328  3966  3966 D A2dpService: Received start request. Starting profile...
08-26 10:52:43.329  3966  3966 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 10:52:43.329  3966  3966 I bt_bluedroid: get_profile_interface avrcp
,08-26 10:52:43.337  3966  3966 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 10:52:43.337  3966  3966 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 10:52:43.337  3966  3966 D A2dpStateMachine: make
,08-26 10:52:43.338  3966  3966 I bt_bluedroid: get_profile_interface a2dp
,08-26 10:52:43.339  3966  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-26 10:52:43.340  3966  4142 D A2dpStateMachine: Enter Disconnected: -2
,08-26 10:52:43.340  3966  3966 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 10:52:43.341  3966  3966 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b1b9ce
,08-26 10:52:43.342  3966  3966 D HidService: Received start request. Starting profile...
08-26 10:52:43.342  3886  3886 D BluetoothInputDevice: Proxy object connected
08-26 10:52:43.342  3966  3966 I bt_bluedroid: get_profile_interface hidhost
08-26 10:52:43.342  3966  3966 D HidService: setHidService(): set to: null
08-26 10:52:43.342  3966  4126 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39483e5
08-26 10:52:43.342  3966  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-26 10:52:43.342  3886  3886 D HidProfile: Bluetooth service connected
,08-26 10:52:43.343  3966  3966 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 10:52:43.343  3966  3966 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b1b9ce
08-26 10:52:43.344  3966  3966 D HealthService: Received start request. Starting profile...
,08-26 10:52:43.345  3966  3966 I bt_bluedroid: get_profile_interface health
,08-26 10:52:43.347  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 10:52:43.349  3966  3966 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 10:52:43.349  3966  3966 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b1b9ce
,08-26 10:52:43.351  3886  3886 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 10:52:43.351  3966  3966 D PanService: Received start request. Starting profile...
08-26 10:52:43.351  3966  3966 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-26 10:52:43.351  3966  3966 I bt_bluedroid: get_profile_interface pan
,08-26 10:52:43.352  3966  4126 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 10:52:43.352  3886  3886 D PanProfile: Bluetooth service connected
,08-26 10:52:43.353  3966  3966 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b1b9ce
08-26 10:52:43.355  3966  3966 D BluetoothMapService: Received start request. Starting profile...
08-26 10:52:43.355  3966  3966 D BluetoothMapService: start()
,08-26 10:52:43.355  3886  3886 D BluetoothMap: Proxy object connected
08-26 10:52:43.355  3886  3886 D MapProfile: Bluetooth service connected
08-26 10:52:43.356  3886  3886 D BluetoothMap: getConnectedDevices()
08-26 10:52:43.356  3886  3886 D BluetoothMap: Bluetooth is Not enabled
08-26 10:52:43.357  3966  3966 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-26 10:52:43.358  3966  3966 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-26 10:52:43.358  3966  3966 D BluetoothMapAppObserver: createReceiver()
,08-26 10:52:43.360  3966  3966 D BluetoothMapAppObserver: initObservers()
08-26 10:52:43.360  3966  3966 D BluetoothMapAppObserver: getEnabledAccountItems()
08-26 10:52:43.368  3966  3966 V BluetoothAdapterState: isTurningOff()=false
08-26 10:52:43.368  3966  3966 V BluetoothAdapterState: isTurningOn()=true
08-26 10:52:43.368  3966  3966 V BluetoothAdapterState: isBleTurningOn()=false
08-26 10:52:43.368  3966  3966 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 10:52:43.370  3966  3966 V BluetoothAdapterState: isTurningOff()=false
08-26 10:52:43.370  3966  3966 V BluetoothAdapterState: isTurningOn()=true
08-26 10:52:43.370  3966  3966 V BluetoothAdapterState: isBleTurningOn()=false
08-26 10:52:43.370  3966  4140 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-26 10:52:43.370  3966  3966 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 10:52:43.370  3966  3966 V BluetoothAdapterState: isTurningOff()=false
,08-26 10:52:43.370  3966  3966 V BluetoothAdapterState: isTurningOn()=true
08-26 10:52:43.370  3966  3966 V BluetoothAdapterState: isBleTurningOn()=false
08-26 10:52:43.370  3966  3966 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 10:52:43.370  3966  3966 V BluetoothAdapterState: isTurningOff()=false
,08-26 10:52:43.370  3966  3966 V BluetoothAdapterState: isTurningOn()=true
,08-26 10:52:43.371  3966  3966 V BluetoothAdapterState: isBleTurningOn()=false
08-26 10:52:43.371  3966  3966 V BluetoothAdapterState: isBleTurningOff()=false
08-26 10:52:43.372  3966  3966 V BluetoothAdapterState: isTurningOff()=false
,08-26 10:52:43.372  3966  3966 V BluetoothAdapterState: isTurningOn()=true
08-26 10:52:43.372  3966  3966 V BluetoothAdapterState: isBleTurningOn()=false
08-26 10:52:43.372  3966  3966 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 10:52:43.372  3966  3966 V BluetoothAdapterState: isTurningOff()=false
08-26 10:52:43.372  3966  3966 V BluetoothAdapterState: isTurningOn()=true
08-26 10:52:43.372  3966  3966 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 10:52:43.372  3966  3966 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 10:52:43.372  3966  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-26 10:52:43.373  3966  4122 D BluetoothAdapterProperties: ScanMode =  20
,08-26 10:52:43.373  3966  4122 D BluetoothAdapterProperties: State =  11
,08-26 10:52:43.373  3966  4122 D BluetoothAdapterProperties: Setting state to 12
08-26 10:52:43.373  3966  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 10:52:43.374  1363  2084 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 10:52:43.374  3966  4126 D BluetoothAdapterProperties: Scan Mode:21
08-26 10:52:43.375  3966  4126 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 10:52:43.376  3966  4122 I BluetoothAdapterState: Entering OnState
08-26 10:52:43.376  1363  1363 D BluetoothInputDevice: Proxy object connected
08-26 10:52:43.376  1363  1363 D HidProfile: Bluetooth service connected
,08-26 10:52:43.378  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:43.378  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:43.378  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:43.378  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:43.378  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:43.378  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:43.378  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:43.378  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:43.378  1363  2084 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 10:52:43.378   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 10:52:43.379  3886  3899 D BluetoothMap: onBluetoothStateChange: up=true
08-26 10:52:43.379  3886  3898 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 10:52:43.379  3817  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:43.379   875   875 D BluetoothA2dp: Proxy object connected
08-26 10:52:43.380  1363  1377 D BluetoothMap: onBluetoothStateChange: up=true
08-26 10:52:43.382  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:43.382  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:43.382  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:43.382  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:43.382  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:43.382  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:43.382  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:43.382  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:43.382  1363  1363 D BluetoothMap: Proxy object connected
08-26 10:52:43.382  1363  1363 D MapProfile: Bluetooth service connected
08-26 10:52:43.382  1363  1363 D BluetoothMap: getConnectedDevices()
,08-26 10:52:43.383  1943  1955 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 10:52:43.383   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 10:52:43.383  3817  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:43.383  3886  3899 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 10:52:43.383  1363  1376 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 10:52:43.385  1363  1363 D BluetoothA2dp: Proxy object connected
08-26 10:52:43.385  1363  1377 D BluetoothPan: onBluetoothStateChange on: true
08-26 10:52:43.386  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 10:52:43.386  1363  1363 D PanProfile: Bluetooth service connected
08-26 10:52:43.386  3886  3899 D BluetoothPan: onBluetoothStateChange on: true
08-26 10:52:43.386   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 10:52:43.387  1363  1376 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 10:52:43.388  3966  3966 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 10:52:43.388  3966  3966 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 10:52:43.389   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 10:52:43.390   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
08-26 10:52:43.390  3966  3966 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 10:52:43.392  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:43.393  3966  3966 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 10:52:43.393  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:43.393  3886  3886 D LocalBluetoothProfileManager: Adding local A2DP profile
08-26 10:52:43.393  3966  3966 D ObexServerSockets: Succeed to create listening sockets 
08-26 10:52:43.393  3966  3966 D ObexServerSockets0: startAccept()
08-26 10:52:43.393  3966  3966 D ObexServerSockets0: prepareForNewConnect()
08-26 10:52:43.395  3966  3966 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-26 10:52:43.395  3966  3966 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-26 10:52:43.396  3966  3966 D BluetoothMapService: onReceive
08-26 10:52:43.396  3966  4151 D ObexServerSockets0: Accepting socket connection...
08-26 10:52:43.396  3966  3966 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:43.396  3966  3966 D BluetoothMapService: STATE_ON
08-26 10:52:43.396  3886  3886 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-26 10:52:43.396  3966  4152 D ObexServerSockets0: Accepting socket connection...
,08-26 10:52:43.405  3886  3886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 10:52:43.407  3886  3886 D BluetoothA2dp: Proxy object connected
,08-26 10:52:43.410  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 10:52:43.410  3886  3886 D DockEventReceiver: finishStartingService: stopping service
,08-26 10:52:43.415  1363  1363 D BluetoothPbap: Proxy object connected
08-26 10:52:43.415  1363  1363 D PbapServerProfile: Bluetooth service connected
,08-26 10:52:43.416  3886  3886 D BluetoothPbap: Proxy object connected
,08-26 10:52:43.416  3886  3886 D PbapServerProfile: Bluetooth service connected
,08-26 10:52:43.420  3966  3966 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 10:52:43.420  3966  3966 D ObexServerSockets0: prepareForNewConnect()
,08-26 10:52:43.422  3966  4156 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 10:52:43.432  3966  4160 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 10:52:43.433  3966  4160 I BtOppRfcommListener: Accept thread started.
,08-26 10:52:43.478   875   875 D BluetoothHeadset: Proxy object connected,
08-26 10:52:43.478   875   875 D BluetoothHeadset: Proxy object connected
08-26 10:52:43.479  1943  2129 D BluetoothHeadset: Proxy object connected
,08-26 10:52:43.479  1363  1377 D BluetoothHeadset: Proxy object connected
,08-26 10:52:43.479  1363  1363 D HeadsetProfile: Bluetooth service connected
,08-26 10:52:43.480   875   875 D BluetoothHeadset: Proxy object connected
08-26 10:52:43.483  1943  2274 D BluetoothHeadset: Proxy object connected
08-26 10:52:43.484   875   892 D BluetoothHeadset: Proxy object connected
,08-26 10:52:43.487   875   892 D BluetoothHeadset: Proxy object connected
,08-26 10:52:43.488   875   892 D BluetoothHeadset: Proxy object connected
,08-26 10:52:43.501  3886  3898 D BluetoothHeadset: Proxy object connected
,08-26 10:52:43.504  3886  3886 D HeadsetProfile: Bluetooth service connected
,08-26 10:52:44.987  3966  4122 D BluetoothAdapterState: Current state: ON, message: 23
08-26 10:52:44.988  3966  4122 D BluetoothAdapterProperties: Setting state to 13
08-26 10:52:44.988  3966  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-26 10:52:44.990  3966  4122 D BluetoothAdapterProperties: onBluetoothDisable()
,08-26 10:52:44.992  3966  4122 I BluetoothAdapterState: Entering PendingCommandState
08-26 10:52:44.998  3966  3966 D BluetoothMapService: onReceive
08-26 10:52:44.998  3966  3966 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:44.998  3966  3966 D BluetoothMapService: STATE_TURNING_OFF
08-26 10:52:44.999  3966  3966 D BluetoothMapService: MAP Service closeService in
,08-26 10:52:44.999  3966  3966 D BluetoothMapMasInstance0: MAP Service shutdown
08-26 10:52:45.000  3966  3966 D ObexServerSockets0: shutdown(block = true)
,08-26 10:52:45.001  3966  4151 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-26 10:52:45.005  3966  4126 D BluetoothAdapterProperties: Scan Mode:20
08-26 10:52:45.006  3966  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-26 10:52:45.006  3966  3966 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 10:52:45.007  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:45.007  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:45.007  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:45.007  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:45.007  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:45.007  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:45.007  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:45.007  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:45.007  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:45.007  3966  4152 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-26 10:52:45.009  3966  4136 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-26 10:52:45.010  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:45.010  3966  3966 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 10:52:45.010  3817  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:45.013  3966  3966 D HeadsetService: Received stop request...Stopping profile...
,08-26 10:52:45.020  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:45.020  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:45.020  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:45.020  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:45.020  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:45.020  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 10:52:45.020  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:45.020  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:45.020  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:45.022  3817  3817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 10:52:45.022   875   875 D BluetoothHeadset: Proxy object disconnected
08-26 10:52:45.022  3817  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:45.022   875   875 D BluetoothHeadset: Proxy object disconnected
08-26 10:52:45.022  3886  3899 D BluetoothHeadset: Proxy object disconnected
,08-26 10:52:45.023  1943  1956 D BluetoothHeadset: Proxy object disconnected
,08-26 10:52:45.023  1363  1376 D BluetoothHeadset: Proxy object disconnected
08-26 10:52:45.023  3966  3966 I BtOppRfcommListener: stopping Accept Thread
08-26 10:52:45.023   875   875 D BluetoothHeadset: Proxy object disconnected
,08-26 10:52:45.022  3886  3886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 10:52:45.024  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:45.024  3966  4160 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 10:52:45.024  3966  4160 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 10:52:45.025  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:45.026  3966  3966 D A2dpService: Received stop request...Stopping profile...
,08-26 10:52:45.027  3966  4142 D A2dpStateMachine: Exit Disconnected: -1
,08-26 10:52:45.031   875   875 D BluetoothA2dp: Proxy object disconnected
,08-26 10:52:45.032  3966  3966 V BluetoothAdapterState: isTurningOff()=true
,08-26 10:52:45.032  3966  3966 V BluetoothAdapterState: isTurningOn()=false
,08-26 10:52:45.032  3966  3966 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 10:52:45.032  3966  3966 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 10:52:45.032  3886  3886 D HeadsetProfile: Bluetooth service disconnected
08-26 10:52:45.033  3966  3966 D HidService: Received stop request...Stopping profile...
,08-26 10:52:45.033  3966  3966 D HidService: Stopping Bluetooth HidService
,08-26 10:52:45.035  3966  3966 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 10:52:45.035  3966  3966 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-26 10:52:45.035  3966  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-26 10:52:45.035  3966  4134 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 10:52:45.035  3966  4134 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 10:52:45.036  3966  4134 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 10:52:45.036  3966  4126 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-26 10:52:45.036  1363  1363 D HeadsetProfile: Bluetooth service disconnected
,08-26 10:52:45.037  1363  1363 D BluetoothA2dp: Proxy object disconnected
,08-26 10:52:45.037  1363  1363 D BluetoothInputDevice: Proxy object disconnected
08-26 10:52:45.037  1363  1363 D HidProfile: Bluetooth service disconnected
,08-26 10:52:45.038  3966  3966 D HealthService: Received stop request...Stopping profile...
,08-26 10:52:45.040  3966  3966 D PanService: Received stop request...Stopping profile...
,08-26 10:52:45.041  1363  1363 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 10:52:45.041  1363  1363 D PanProfile: Bluetooth service disconnected
,08-26 10:52:45.042  3966  3966 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 10:52:45.042  3966  3966 D BluetoothMapService: stop()
08-26 10:52:45.042  3966  3966 D BluetoothMapAppObserver: deinitObservers()
,08-26 10:52:45.043  3966  3966 D BluetoothMapAppObserver: removeReceiver(),
08-26 10:52:45.044  3886  3886 D DockEventReceiver: finishStartingService: stopping service
08-26 10:52:45.044  1363  1363 D BluetoothMap: Proxy object disconnected
,08-26 10:52:45.044  1363  1363 D MapProfile: Bluetooth service disconnected
08-26 10:52:45.046  3966  3966 V BluetoothAdapterState: isTurningOff()=true
,08-26 10:52:45.046  3966  3966 V BluetoothAdapterState: isTurningOn()=false
,08-26 10:52:45.046  3966  3966 V BluetoothAdapterState: isBleTurningOn()=false
08-26 10:52:45.046  3966  3966 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 10:52:45.046  3886  3886 D BluetoothA2dp: Proxy object disconnected
08-26 10:52:45.046  3886  3886 D BluetoothInputDevice: Proxy object disconnected
08-26 10:52:45.046  3886  3886 D HidProfile: Bluetooth service disconnected
08-26 10:52:45.047  3886  3886 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 10:52:45.047  3886  3886 D PanProfile: Bluetooth service disconnected
08-26 10:52:45.047  3886  3886 D BluetoothMap: Proxy object disconnected
,08-26 10:52:45.047  3886  3886 D MapProfile: Bluetooth service disconnected
08-26 10:52:45.048  3966  4134 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 10:52:45.048  3966  4134 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 10:52:45.048  3966  4134 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 10:52:45.048  3966  4134 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 10:52:45.048  3966  4134 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 10:52:45.048  3966  4134 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 10:52:45.048  3966  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-26 10:52:45.049  3966  3966 V BluetoothAdapterState: isTurningOff()=true
08-26 10:52:45.049  3966  3966 V BluetoothAdapterState: isTurningOn()=false
,08-26 10:52:45.049  3966  3966 V BluetoothAdapterState: isBleTurningOn()=false
08-26 10:52:45.049  3966  3966 V BluetoothAdapterState: isBleTurningOff()=false
08-26 10:52:45.050  3966  3966 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 10:52:45.051  3966  4126 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 10:52:45.051  3966  3966 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-26 10:52:45.051  3966  3966 V BluetoothAdapterState: isTurningOff()=true
,08-26 10:52:45.051  3966  3966 V BluetoothAdapterState: isTurningOn()=false
08-26 10:52:45.051  3966  3966 V BluetoothAdapterState: isBleTurningOn()=false
08-26 10:52:45.051  3966  3966 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 10:52:45.051  3966  3966 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 10:52:45.052  3966  4126 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-26 10:52:45.052  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 10:52:45.052  3966  3966 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 10:52:45.053  3966  3966 V BluetoothAdapterState: isTurningOff()=true
08-26 10:52:45.053  3966  3966 V BluetoothAdapterState: isTurningOn()=false
08-26 10:52:45.053  3966  3966 V BluetoothAdapterState: isBleTurningOn()=false
08-26 10:52:45.053  3966  3966 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 10:52:45.054  3966  3966 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 10:52:45.054  3966  3966 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 10:52:45.057  3966  3966 D BluetoothMapService: MAP Service closeService in
08-26 10:52:45.057  3966  3966 V BluetoothAdapterState: isTurningOff()=true
08-26 10:52:45.057  3966  3966 V BluetoothAdapterState: isTurningOn()=false
,08-26 10:52:45.057  3966  3966 V BluetoothAdapterState: isBleTurningOn()=false
08-26 10:52:45.057  3966  3966 V BluetoothAdapterState: isBleTurningOff()=false
08-26 10:52:45.057  3966  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-26 10:52:45.057  3966  3966 D BluetoothMapService: cleanup()
,08-26 10:52:45.057  3966  3966 D BluetoothMapService: MAP Service closeService in
08-26 10:52:45.057  3966  4122 D BluetoothAdapterProperties: Setting state to 15
08-26 10:52:45.058  3966  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 10:52:45.058  3966  4122 I BluetoothAdapterState: Entering BleOnState
08-26 10:52:45.059  1363  1376 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 10:52:45.059  1363  1363 D BluetoothPbap: Proxy object disconnected
08-26 10:52:45.059  1363  1363 D PbapServerProfile: Bluetooth service disconnected
08-26 10:52:45.060  1363  1377 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 10:52:45.060   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 10:52:45.060  3886  3898 D BluetoothMap: onBluetoothStateChange: up=false
08-26 10:52:45.061  3886  3886 D BluetoothPbap: Proxy object disconnected
08-26 10:52:45.061  3886  3886 D PbapServerProfile: Bluetooth service disconnected
08-26 10:52:45.063  3886  4164 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 10:52:45.063  1363  1376 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 10:52:45.064  1943  1955 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 10:52:45.064   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 10:52:45.064  3886  3899 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 10:52:45.064  1363  1377 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 10:52:45.069  1363  2084 D BluetoothPan: onBluetoothStateChange on: false
,08-26 10:52:45.069  3886  3898 D BluetoothPan: onBluetoothStateChange on: false
08-26 10:52:45.070  3886  3898 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 10:52:45.070   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 10:52:45.070  3886  3899 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 10:52:45.071  1363  1376 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 10:52:45.071   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 10:52:45.071  3966  4122 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 10:52:45.071  3966  4122 D BluetoothAdapterProperties: Setting state to 16
08-26 10:52:45.072  3966  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-26 10:52:45.072  3966  4122 D BluetoothAdapterProperties: onBleDisable
,08-26 10:52:45.072  3966  4122 I BluetoothAdapterState: Entering PendingCommandState
08-26 10:52:45.073  3966  4123 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-26 10:52:45.073  3966  4134 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 10:52:45.073  3966  4134 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 10:52:45.075  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:45.076  3966  4126 D BluetoothAdapterProperties: Scan Mode:20
08-26 10:52:45.077  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:45.077  3886  3886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 10:52:45.078  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:45.079  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:45.080   875  1310 D ConnectivityService: handlePromptUnvalidated 101
08-26 10:52:45.083  3886  3886 D DockEventReceiver: finishStartingService: stopping service
08-26 10:52:45.083  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 10:52:45.274  3966  4126 I bt_hci  : shut_down
,08-26 10:52:45.275  3966  4132 D bt_hwcfg: hw_epilog_process
,08-26 10:52:45.277  3966  4132 I bt_vendor: low_power_mode_cb
,08-26 10:52:45.296  3966  4132 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-26 10:52:45.297  3966  4132 I bt_vendor: epilog_cb
,08-26 10:52:45.297  3966  4132 I bt_hci  : epilog_finished_callback
,08-26 10:52:45.305  3966  4126 I bt_hci_h4: hal_close
,08-26 10:52:45.306  3966  4126 I bt_userial_vendor: device fd = 51 close
,08-26 10:52:45.429  3966  4123 D bt_stack_manager: event_shut_down_stack finished.
,08-26 10:52:45.433  3966  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 10:52:45.439  3966  3966 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 10:52:45.441  3966  4122 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-26 10:52:45.442  3966  3966 D BtGatt.GattService: Received stop request...Stopping profile...
,08-26 10:52:45.442  3966  3966 D BtGatt.GattService: stop()
,08-26 10:52:45.443  3966  3966 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 10:52:45.448  3966  3966 V BluetoothAdapterState: isTurningOff()=false
,08-26 10:52:45.448  3966  3966 V BluetoothAdapterState: isTurningOn()=false
,08-26 10:52:45.449  3966  3966 V BluetoothAdapterState: isBleTurningOn()=false
08-26 10:52:45.449  3966  3966 V BluetoothAdapterState: isBleTurningOff()=true
08-26 10:52:45.450  3966  4122 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-26 10:52:45.450  3966  4122 D BluetoothAdapterProperties: Setting state to 10,
08-26 10:52:45.451  3966  4122 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-26 10:52:45.453  3966  4122 I BluetoothAdapterState: Entering OffState
08-26 10:52:45.454   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-26 10:52:45.470  3966  3966 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-26 10:52:45.470  3966  3966 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-26 10:52:45.470  3966  4123 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-26 10:52:45.473  3966  4123 D bt_stack_manager: event_clean_up_stack finished.
,08-26 10:52:45.473  3966  3966 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 10:52:45.475  3966  3966 I art     : System.exit called, status: 0
,08-26 10:52:45.475  3966  3966 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 10:52:45.534   875   885 I ActivityManager: Process com.android.bluetooth (pid 3966) has died
,08-26 10:52:47.985  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 10:52:47.985  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:50.993  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 10:52:50.993  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6c93f54 added. We now have 6 listener(s)
08-26 10:52:50.994  3817  3866 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 10:52:50.998  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 10:52:50.998  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f3befd added. We now have 7 listener(s)
08-26 10:52:50.999  3817  3866 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 10:52:51.001  3817  3866 I System.out: IsBluetoothEnabled
,08-26 10:52:51.011  3817  3866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:51.060   875   892 I ActivityManager: Start proc 4171:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-26 10:52:51.195  4171  4171 D AdapterServiceConfig: Adding HeadsetService
,08-26 10:52:51.196  4171  4171 D AdapterServiceConfig: Adding A2dpService
,08-26 10:52:51.196  4171  4171 D AdapterServiceConfig: Adding HidService
,08-26 10:52:51.197  4171  4171 D AdapterServiceConfig: Adding HealthService
,08-26 10:52:51.197  4171  4171 D AdapterServiceConfig: Adding PanService
,08-26 10:52:51.198  4171  4171 D AdapterServiceConfig: Adding GattService
08-26 10:52:51.198  4171  4171 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 10:52:51.226   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b0a6dce:true
,08-26 10:52:51.228  4171  4171 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 10:52:51.238  4171  4183 I BluetoothAdapterState: Entering OffState
08-26 10:52:51.237  4171  4171 I bt_bluedroid: init
,08-26 10:52:51.241  4171  4184 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 10:52:51.241  4171  4184 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 10:52:51.241  4171  4184 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 10:52:51.242  4171  4184 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 10:52:51.243  4171  4171 I bt_bluedroid: get_profile_interface socket
,08-26 10:52:51.248  4171  4171 I bt_bluedroid: get_profile_interface sdp
,08-26 10:52:51.249  4171  4187 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 10:52:51.252  4171  4187 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 10:52:51.257  4171  4182 I bt_bluedroid: config_hci_snoop_log
,08-26 10:52:51.263   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 10:52:51.275  4171  4183 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 10:52:51.275  4171  4183 D BluetoothAdapterProperties: Setting state to 14
08-26 10:52:51.275  4171  4183 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-26 10:52:51.280  4171  4183 D BluetoothBondStateMachine: make
,08-26 10:52:51.285  4171  4189 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 10:52:51.292  4171  4171 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 10:52:51.295  4171  4183 I BluetoothAdapterState: Entering PendingCommandState
,08-26 10:52:51.297  4171  4171 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b1b9ce
,08-26 10:52:51.298  4171  4171 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 10:52:51.300  4171  4171 D BtGatt.GattService: Received start request. Starting profile...
08-26 10:52:51.300  4171  4171 D BtGatt.GattService: start()
08-26 10:52:51.300  4171  4171 I bt_bluedroid: get_profile_interface gatt
,08-26 10:52:51.301  4171  4171 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b1b9ce
,08-26 10:52:51.302  4171  4171 D BtGatt.AdvertiseManager: advertise manager created
,08-26 10:52:51.312  4171  4171 V BluetoothAdapterState: isTurningOff()=false
08-26 10:52:51.312  4171  4171 V BluetoothAdapterState: isTurningOn()=false
08-26 10:52:51.313  4171  4171 V BluetoothAdapterState: isBleTurningOn()=true
08-26 10:52:51.313  4171  4171 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 10:52:51.313  4171  4183 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-26 10:52:51.314  4171  4183 I bt_bluedroid: enable
,08-26 10:52:51.315  4171  4184 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-26 10:52:51.316  4171  4184 I bt_hci  : start_up
,08-26 10:52:51.326  4171  4184 I bt_vendor: alloc value 0xb3a39189
,08-26 10:52:51.326  4171  4184 I bt_vendor: init
08-26 10:52:51.327  4171  4184 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-26 10:52:51.327  4171  4184 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 10:52:51.434  4171  4184 D bt_hci  : start_up starting async portion
,08-26 10:52:51.435  4171  4192 I bt_hci  : event_finish_startup
08-26 10:52:51.435  4171  4192 I bt_hci_h4: hal_open
,08-26 10:52:51.435  4171  4192 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 10:52:51.450  4171  4192 I bt_userial_vendor: device fd = 51 open
,08-26 10:52:51.477  4171  4192 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 10:52:51.509  4171  4192 D bt_hwcfg: Chipset BCM4354A2
,08-26 10:52:51.509  4171  4192 D bt_hwcfg: Target name = [BCM4354A2]
08-26 10:52:51.510  4171  4192 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 10:52:52.179  4171  4192 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 10:52:52.180  4171  4192 D bt_hwcfg: Settlement delay -- 100 ms
08-26 10:52:52.181  4171  4192 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 10:52:52.297  4171  4192 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 10:52:52.299  4171  4192 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 10:52:52.328  4171  4192 I bt_hwcfg: vendor lib fwcfg completed
,08-26 10:52:52.329  4171  4192 I bt_vendor: firmware callback
08-26 10:52:52.329  4171  4192 I bt_hci  : firmware_config_callback
,08-26 10:52:52.340  4171  4194 I bt_btu  : btu_task pending for preload complete event
,08-26 10:52:52.341  4171  4194 I bt_btu_task: Bluetooth chip preload is complete
,08-26 10:52:52.341  4171  4194 I bt_btu  : btu_task received preload complete event
,08-26 10:52:52.351  4171  4194 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 10:52:52.352  4171  4194 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-26 10:52:52.352  4171  4194 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-26 10:52:52.352  4171  4194 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-26 10:52:52.352  4171  4194 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-26 10:52:52.353  4171  4194 I         : BTE_InitTraceLevels -- TRC_A2D
,08-26 10:52:52.353  4171  4194 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-26 10:52:52.353  4171  4194 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 10:52:52.354  4171  4194 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 10:52:52.354  4171  4194 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 10:52:52.354  4171  4194 I         : BTE_InitTraceLevels -- TRC_SDP
,08-26 10:52:52.354  4171  4194 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 10:52:52.355  4171  4194 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 10:52:52.355  4171  4194 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 10:52:52.355  4171  4194 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 10:52:52.495  4171  4194 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39b6d9d
,08-26 10:52:52.495  4171  4194 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39b6d9d 
,08-26 10:52:52.503  4171  4187 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
,08-26 10:52:52.505  4171  4187 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 10:52:52.506  4171  4187 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 10:52:52.510  4171  4187 D BluetoothAdapterProperties: Name is: Nexus 6
08-26 10:52:52.515  4171  4187 D BluetoothAdapterProperties: Scan Mode:20
,08-26 10:52:52.515  4171  4187 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 10:52:52.516  4171  4187 D bt_hci  : do_postload posting postload work item
08-26 10:52:52.517  4171  4192 I bt_hci  : event_postload
08-26 10:52:52.517  4171  4192 I bt_vendor: sco_config_cb
08-26 10:52:52.517  4171  4192 I bt_hci  : sco_config_callback postload finished.
,08-26 10:52:52.521  4171  4187 D bt_bte_conf: Device ID record 1 : primary
,08-26 10:52:52.521  4171  4187 D bt_bte_conf:   vendorId            = 000f
08-26 10:52:52.522  4171  4187 D bt_bte_conf:   vendorIdSource      = 0001
,08-26 10:52:52.522  4171  4187 D bt_bte_conf:   product             = 1200
,08-26 10:52:52.522  4171  4187 D bt_bte_conf:   version             = 1436
08-26 10:52:52.522  4171  4187 D bt_bte_conf:   clientExecutableURL = 
,08-26 10:52:52.522  4171  4187 D bt_bte_conf:   serviceDescription  = 
,08-26 10:52:52.523  4171  4187 D bt_bte_conf:   documentationURL    = 
,08-26 10:52:52.523  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:52.523  4171  4187 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-26 10:52:52.524  4171  4184 D bt_stack_manager: event_start_up_stack finished
08-26 10:52:52.526  4171  4192 I bt_vendor: low_power_mode_cb
,08-26 10:52:52.526  4171  4183 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-26 10:52:52.526  4171  4183 D BluetoothAdapterProperties: Setting state to 15
08-26 10:52:52.527  4171  4183 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-26 10:52:52.529  4171  4183 I BluetoothAdapterState: Entering BleOnState
08-26 10:52:52.534  4171  4183 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-26 10:52:52.534  4171  4183 D BluetoothAdapterProperties: Setting state to 11
,08-26 10:52:52.535  4171  4183 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-26 10:52:52.546  4171  4171 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b1b9ce
,08-26 10:52:52.550  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:52.551  4171  4171 D HeadsetService: Received start request. Starting profile...
,08-26 10:52:52.555  4171  4171 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 10:52:52.555  4171  4171 D HeadsetStateMachine: make
,08-26 10:52:52.563  4171  4183 I BluetoothAdapterState: Entering PendingCommandState
,08-26 10:52:52.568  4171  4171 D HeadsetStateMachine: max_hf_connections = 1
,08-26 10:52:52.568  4171  4171 I bt_bluedroid: get_profile_interface handsfree
,08-26 10:52:52.569  4171  4187 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-26 10:52:52.569  4171  4187 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-26 10:52:52.573  4171  4171 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b1b9ce
,08-26 10:52:52.574  4171  4171 D A2dpService: Received start request. Starting profile...
,08-26 10:52:52.574  4171  4171 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 10:52:52.575  4171  4171 I bt_bluedroid: get_profile_interface avrcp
,08-26 10:52:52.581  4171  4171 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 10:52:52.581  4171  4171 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-26 10:52:52.581  4171  4171 D A2dpStateMachine: make
,08-26 10:52:52.582  4171  4171 I bt_bluedroid: get_profile_interface a2dp
,08-26 10:52:52.584  4171  4187 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-26 10:52:52.588  4171  4203 D A2dpStateMachine: Enter Disconnected: -2
,08-26 10:52:52.588  4171  4171 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 10:52:52.591  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 10:52:52.591  4171  4171 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b1b9ce
,08-26 10:52:52.592  4171  4171 D HidService: Received start request. Starting profile...
08-26 10:52:52.593  4171  4171 I bt_bluedroid: get_profile_interface hidhost
,08-26 10:52:52.593  4171  4171 D HidService: setHidService(): set to: null
08-26 10:52:52.593  4171  4187 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39983e5
08-26 10:52:52.593  4171  4187 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-26 10:52:52.593  4171  4171 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 10:52:52.594  4171  4171 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b1b9ce
,08-26 10:52:52.595  4171  4171 D HealthService: Received start request. Starting profile...
,08-26 10:52:52.596  4171  4171 I bt_bluedroid: get_profile_interface health
,08-26 10:52:52.597  4171  4171 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 10:52:52.598  4171  4171 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b1b9ce
,08-26 10:52:52.598  4171  4171 D PanService: Received start request. Starting profile...
08-26 10:52:52.598  4171  4171 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 10:52:52.598  4171  4171 I bt_bluedroid: get_profile_interface pan
,08-26 10:52:52.599  4171  4187 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 10:52:52.601  4171  4171 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b1b9ce
,08-26 10:52:52.601  4171  4171 D BluetoothMapService: Received start request. Starting profile...
,08-26 10:52:52.601  4171  4171 D BluetoothMapService: start()
,08-26 10:52:52.604  4171  4171 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-26 10:52:52.605  4171  4171 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-26 10:52:52.605  4171  4171 D BluetoothMapAppObserver: createReceiver()
,08-26 10:52:52.606  4171  4171 D BluetoothMapAppObserver: initObservers()
,08-26 10:52:52.606  4171  4171 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 10:52:52.615  4171  4171 V BluetoothAdapterState: isTurningOff()=false
,08-26 10:52:52.615  4171  4171 V BluetoothAdapterState: isTurningOn()=true
,08-26 10:52:52.615  4171  4171 V BluetoothAdapterState: isBleTurningOn()=false
08-26 10:52:52.615  4171  4171 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 10:52:52.617  4171  4171 V BluetoothAdapterState: isTurningOff()=false
,08-26 10:52:52.617  4171  4171 V BluetoothAdapterState: isTurningOn()=true
08-26 10:52:52.617  4171  4171 V BluetoothAdapterState: isBleTurningOn()=false
08-26 10:52:52.617  4171  4171 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 10:52:52.617  4171  4201 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 10:52:52.620  4171  4171 V BluetoothAdapterState: isTurningOff()=false
08-26 10:52:52.620  4171  4171 V BluetoothAdapterState: isTurningOn()=true
08-26 10:52:52.620  4171  4171 V BluetoothAdapterState: isBleTurningOn()=false
08-26 10:52:52.620  4171  4171 V BluetoothAdapterState: isBleTurningOff()=false
08-26 10:52:52.620  4171  4171 V BluetoothAdapterState: isTurningOff()=false
,08-26 10:52:52.620  4171  4171 V BluetoothAdapterState: isTurningOn()=true
08-26 10:52:52.620  4171  4171 V BluetoothAdapterState: isBleTurningOn()=false
08-26 10:52:52.621  4171  4171 V BluetoothAdapterState: isBleTurningOff()=false
08-26 10:52:52.621  4171  4171 V BluetoothAdapterState: isTurningOff()=false
,08-26 10:52:52.621  4171  4171 V BluetoothAdapterState: isTurningOn()=true
08-26 10:52:52.621  4171  4171 V BluetoothAdapterState: isBleTurningOn()=false
08-26 10:52:52.621  4171  4171 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 10:52:52.621  4171  4171 V BluetoothAdapterState: isTurningOff()=false
,08-26 10:52:52.621  4171  4171 V BluetoothAdapterState: isTurningOn()=true
08-26 10:52:52.621  4171  4171 V BluetoothAdapterState: isBleTurningOn()=false
08-26 10:52:52.621  4171  4171 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 10:52:52.622  4171  4183 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-26 10:52:52.622  4171  4183 D BluetoothAdapterProperties: ScanMode =  20
08-26 10:52:52.622  4171  4183 D BluetoothAdapterProperties: State =  11
,08-26 10:52:52.623  4171  4183 D BluetoothAdapterProperties: Setting state to 12
08-26 10:52:52.623  4171  4183 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 10:52:52.623  1363  1377 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 10:52:52.625  4171  4183 I BluetoothAdapterState: Entering OnState
,08-26 10:52:52.625  4171  4187 D BluetoothAdapterProperties: Scan Mode:21
,08-26 10:52:52.626  4171  4187 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 10:52:52.627  1363  2084 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 10:52:52.627  1363  1363 D BluetoothInputDevice: Proxy object connected
08-26 10:52:52.627  1363  1363 D HidProfile: Bluetooth service connected
08-26 10:52:52.628   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 10:52:52.630  3886  3899 D BluetoothMap: onBluetoothStateChange: up=true
08-26 10:52:52.630   875   875 D BluetoothA2dp: Proxy object connected
08-26 10:52:52.631  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:52.631  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:52.631  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:52.631  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:52.631  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:52.631  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:52.631  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:52.631  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 10:52:52.633  3886  4164 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 10:52:52.634  4171  4171 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 10:52:52.634  3886  3886 D BluetoothMap: Proxy object connected
08-26 10:52:52.634  3886  3886 D MapProfile: Bluetooth service connected
08-26 10:52:52.634  3886  3886 D BluetoothMap: getConnectedDevices()
08-26 10:52:52.634  3817  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 10:52:52.634  4171  4171 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 10:52:52.636  4171  4171 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 10:52:52.638  4171  4171 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 10:52:52.639  1363  1376 D BluetoothMap: onBluetoothStateChange: up=true
08-26 10:52:52.640  4171  4171 D ObexServerSockets: Succeed to create listening sockets 
08-26 10:52:52.640  4171  4171 D ObexServerSockets0: startAccept()
08-26 10:52:52.640  4171  4171 D ObexServerSockets0: prepareForNewConnect()
08-26 10:52:52.642  4171  4171 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-26 10:52:52.642  4171  4171 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-26 10:52:52.644  1943  1955 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 10:52:52.644  1363  1363 D BluetoothMap: Proxy object connected
08-26 10:52:52.644  1363  1363 D MapProfile: Bluetooth service connected
08-26 10:52:52.645   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 10:52:52.645  1363  1363 D BluetoothMap: getConnectedDevices()
,08-26 10:52:52.645  3886  3898 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 10:52:52.646  4171  4208 D ObexServerSockets0: Accepting socket connection...
08-26 10:52:52.647  1363  1377 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 10:52:52.647  4171  4209 D ObexServerSockets0: Accepting socket connection...
,08-26 10:52:52.648  1363  1363 D BluetoothA2dp: Proxy object connected
08-26 10:52:52.648  1363  2084 D BluetoothPan: onBluetoothStateChange on: true
08-26 10:52:52.650  3886  4164 D BluetoothPan: onBluetoothStateChange on: true
,08-26 10:52:52.651  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 10:52:52.651  1363  1363 D PanProfile: Bluetooth service connected
08-26 10:52:52.652  3886  3898 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 10:52:52.653   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 10:52:52.653  3886  3899 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 10:52:52.655  1363  1377 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 10:52:52.656   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 10:52:52.657  3886  3886 D BluetoothInputDevice: Proxy object connected
,08-26 10:52:52.657  3886  3886 D HidProfile: Bluetooth service connected
08-26 10:52:52.658   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
08-26 10:52:52.659  4171  4171 D BluetoothMapService: onReceive
08-26 10:52:52.659  4171  4171 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 10:52:52.659  4171  4171 D BluetoothMapService: STATE_ON
08-26 10:52:52.661  3886  3886 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 10:52:52.661  3886  3886 D PanProfile: Bluetooth service connected
08-26 10:52:52.662  3886  3886 D BluetoothA2dp: Proxy object connected
08-26 10:52:52.661  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:52.672  3886  3886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 10:52:52.680  4171  4171 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 10:52:52.680  4171  4171 D ObexServerSockets0: prepareForNewConnect()
08-26 10:52:52.681  3886  3886 D DockEventReceiver: finishStartingService: stopping service
08-26 10:52:52.683  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 10:52:52.690  3886  3886 D BluetoothPbap: Proxy object connected
,08-26 10:52:52.690  1363  1363 D BluetoothPbap: Proxy object connected
08-26 10:52:52.690  3886  3886 D PbapServerProfile: Bluetooth service connected
08-26 10:52:52.690  1363  1363 D PbapServerProfile: Bluetooth service connected
,08-26 10:52:52.693  4171  4211 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 10:52:52.713  4171  4217 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 10:52:52.714  4171  4217 I BtOppRfcommListener: Accept thread started.
,08-26 10:52:52.728   875   875 D BluetoothHeadset: Proxy object connected
08-26 10:52:52.728   875   875 D BluetoothHeadset: Proxy object connected
,08-26 10:52:52.729  3886  3898 D BluetoothHeadset: Proxy object connected
,08-26 10:52:52.730  3886  3886 D HeadsetProfile: Bluetooth service connected
08-26 10:52:52.730  1943  2129 D BluetoothHeadset: Proxy object connected
,08-26 10:52:52.730  1363  1376 D BluetoothHeadset: Proxy object connected
08-26 10:52:52.730  1363  1363 D HeadsetProfile: Bluetooth service connected
,08-26 10:52:52.730   875   875 D BluetoothHeadset: Proxy object connected
,08-26 10:52:52.746  1943  2274 D BluetoothHeadset: Proxy object connected
,08-26 10:52:52.746   875   892 D BluetoothHeadset: Proxy object connected
,08-26 10:52:52.753  3886  4164 D BluetoothHeadset: Proxy object connected
,08-26 10:52:52.754   875   892 D BluetoothHeadset: Proxy object connected
08-26 10:52:52.754  3886  3886 D HeadsetProfile: Bluetooth service connected
,08-26 10:52:52.757   875   892 D BluetoothHeadset: Proxy object connected
,08-26 10:52:53.031  3817  3866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:53.031  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:53.031  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:53.031  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 10:52:53.031  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:53.031  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:53.031  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:53.031  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 10:52:53.039  3817  3866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 10:52:53.044  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 10:52:53.044  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7a797f2 added. We now have 8 listener(s)
,08-26 10:52:53.045  3817  3866 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 10:52:53.050   875  1995 D WifiService: setWifiEnabled: false pid=3817, uid=10000
08-26 10:52:53.050   875  1995 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 10:52:53.063  3817  3866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:53.064   875  1959 D WifiService: setWifiEnabled: true pid=3817, uid=10000
,08-26 10:52:53.064   875  1959 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 10:52:53.081   875  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-26 10:52:53.098  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:53.098  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:53.098  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:53.098  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:53.098  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:53.098  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 10:52:53.098  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 10:52:53.098  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 10:52:53.106  3817  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 10:52:53.124   875  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-26 10:52:53.126   875  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-26 10:52:53.126   875  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-26 10:52:53.127   875  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 10:52:53.127   875  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-26 10:52:53.127   875  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-26 10:52:53.128   875  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 10:52:53.140   372   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-26 10:52:53.141   875  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.91 rxSuccessRate=1.16 delta 1000 -> 1000
,08-26 10:52:53.141   372   873 D CommandListener: Setting iface cfg
08-26 10:52:53.142   875  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
08-26 10:52:53.142   875  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 10:52:53.145   875  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 10:52:53.145   875  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 10:52:53.155   875  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3,
08-26 10:52:53.156   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 10:52:53.172   875  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 10:52:53.214   875  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 10:52:53.216  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 10:52:53.647  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 10:52:53.692  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 10:52:53.693  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 10:52:53.696   875  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 10:52:53.708   875  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 10:52:53.708   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 10:52:53.709   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 10:52:53.725   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 10:52:53.736   372   873 D CommandListener: Setting iface cfg
,08-26 10:52:53.737   875  1308 D WifiStateMachine: Start Dhcp Watchdog 3
,08-26 10:52:53.748   875  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 10:52:53.748   875  1310 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-26 10:52:53.749   875  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 10:52:53.796   875  4226 D DhcpClient: Receive thread started
,08-26 10:52:53.876   875  1308 E native  : do suspend false
,08-26 10:52:53.896   875  2119 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 10:52:53.911   875  4226 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-26 10:52:53.912   875  2119 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-26 10:52:53.915   875  2119 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 10:52:53.929   875  4226 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 10:52:53.930   875  2119 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 10:52:53.935   372   873 D CommandListener: Setting iface cfg
,08-26 10:52:53.945   875  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 10:52:53.947   875  2119 D DhcpClient: Scheduling renewal in 86399s
,08-26 10:52:53.962   875  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 10:52:53.967   875  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 10:52:53.968   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 10:52:53.971   875  1310 D ConnectivityService: Adding iface wlan0 to network 102
,08-26 10:52:53.984   875  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 10:52:54.023   875  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 10:52:54.023   875  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-26 10:52:54.026   875  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-26 10:52:54.029   875  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-26 10:52:54.030   875  1310 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-26 10:52:54.041   875  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 10:52:54.048   875  1310 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-26 10:52:54.048   875  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-26 10:52:54.049   875  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-26 10:52:54.049   875  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-26 10:52:54.049   875  1310 D ConnectivityService:    accepting network in place of null
08-26 10:52:54.049   875  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 10:52:54.050   875  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 10:52:54.065   875  4225 D NetlinkSocketObserver: NeighborEvent{elapsedMs=148975, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 10:52:54.086  3817  3866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:54.086  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:54.086  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:54.086  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:54.086  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:54.086  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:54.086  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:54.086  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 10:52:54.088  3817  3866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 10:52:54.091  3817  3866 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 10:52:54.092  3817  3866 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 10:52:54.094  3817  3866 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@333a4da Bundle[{}]
,08-26 10:52:54.094  3817  3866 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 10:52:54.095  3817  3866 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-26 10:52:54.095  3817  3866 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 10:52:54.096  3817  3866 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 10:52:54.096  3817  3866 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-26 10:52:54.097  3817  3866 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 10:52:54.101  3817  3866 I System.out: Running OutgoingSocketThread
,08-26 10:52:54.104   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 10:52:54.104  3817  4232 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 427)
,08-26 10:52:54.106  3817  4232 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 41815
,08-26 10:52:54.107  3817  4232 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 10:52:54.133   372   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 10:52:54.137   875  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-26 10:52:54.137   875  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 10:52:54.139   875  4223 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.46,2a00:1450:4001:817::200e
,08-26 10:52:54.143   875  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-26 10:52:54.144   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-26 10:52:54.155  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 10:52:54.155  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:54.155  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:54.155  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:54.155  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:54.155  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:54.155  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:54.155  3817  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 10:52:54.157  3817  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 10:52:54.164  1699  1699 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 10:52:54.170  1699  1699 D SystemUpdateService: onCreate
,08-26 10:52:54.184  1699  1699 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 10:52:54.199  1699  4236 I SystemUpdateService: active receiver: enabled
,08-26 10:52:54.204  1699  4236 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 10:52:54.207  1699  1699 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 10:52:54.216  1699  4236 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-26 10:52:54.216  1699  4236 I SystemUpdateService: now status is 0 (complete)
,08-26 10:52:54.216  1699  4236 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 10:52:54.216  1699  4236 I SystemUpdateService: file has been verified
08-26 10:52:54.216  1699  4236 I SystemUpdateService: OTA package size = 12249756
,08-26 10:52:54.218   875  4223 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 08:52:54 GMT], X-Android-Received-Millis=[1472201574217], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472201574186]}
,08-26 10:52:54.225  1699  4236 I SystemUpdateService: showing system update notification
,08-26 10:52:54.226   875  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-26 10:52:54.226   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-26 10:52:54.226   875  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 10:52:54.227   875  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 10:52:54.229  1699  1699 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-26 10:52:54.231  1699  1699 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 10:52:54.233  3981  3981 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-26 10:52:54.236  1699  4239 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-26 10:52:54.236  1699  4239 W BaseAppContext: Using Auth Proxy for data requests.
,08-26 10:52:54.238  3981  3981 D SprintDMHelper: simOperator: 
08-26 10:52:54.238  3981  3981 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 10:52:54.247  1699  4239 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 10:52:54.271  1699  2512 I iu.UploadsManager: num queued entries: 0
,08-26 10:52:54.271  1699  2512 I iu.UploadsManager: num updated entries: 0
,08-26 10:52:54.273  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 10:52:54.275  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 10:52:54.291  1699  2512 I iu.SyncManager: NEXT; no task
,08-26 10:52:54.301  1699  1699 D SystemUpdateService: onDestroy
,08-26 10:52:54.319  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-26 10:52:54.320  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-26 10:52:54.320  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 10:52:54.320  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 10:52:54.344  1699  4239 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-26 10:52:54.394  2259  4242 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 10:52:54.534  1504  4246 I GCM     : Ack for not saved message 110
,08-26 10:52:55.040   875   895 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-26 10:52:55.050  1870  1870 I Keyboard.Facilitator: onFinishInput()
,08-26 10:52:55.064   875   895 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 10:52:55.064   875   895 I Adreno  : Build Date                       : 10/20/15
08-26 10:52:55.064   875   895 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 10:52:55.064   875   895 I Adreno  : Local Branch                     : M14
08-26 10:52:55.064   875   895 I Adreno  : Remote Branch                    : 
08-26 10:52:55.064   875   895 I Adreno  : Remote Branch                    : 
08-26 10:52:55.064   875   895 I Adreno  : Reconstruct Branch               : 
,08-26 10:52:55.097   280  3861 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (304 us)
,08-26 10:52:55.104  3817  3866 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 428)
,08-26 10:52:55.104  3817  3866 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 428)
,08-26 10:52:55.112  3817  3866 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 433)
,08-26 10:52:55.114  3817  3866 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-26 10:52:55.114  3817  3866 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 434)
,08-26 10:52:55.122  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 10:52:55.123  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d39e43 added. We now have 2 listener(s)
08-26 10:52:55.128  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 10:52:55.129  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:52:55.129  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 10:52:55.130  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 10:52:55.130  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@424fcc0 added. We now have 9 listener(s)
,08-26 10:52:55.130  3817  3866 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 10:52:55.132  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 10:52:55.135  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:55.136   875  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-26 10:52:55.140  3817  3866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:55.140  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:55.140  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:55.140  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:55.140  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:55.140  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:55.140  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:55.140  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 10:52:55.142  3817  3866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 10:52:55.143  3817  3866 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 10:52:55.143  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:52:55.143  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893413e added. We now have 3 listener(s)
,08-26 10:52:55.144  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 10:52:55.145  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:52:55.145  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 10:52:55.145  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:55.145  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@887db9f added. We now have 10 listener(s)
,08-26 10:52:55.145  3817  3866 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 10:52:55.145  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:55.145  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 10:52:55.145  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:55.145  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 10:52:55.145  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 10:52:55.146  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:52:55.146  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 10:52:55.146  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d39e43 removed from the list
08-26 10:52:55.146  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 10:52:55.146  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:55.149  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@424fcc0 removed from the list
,08-26 10:52:55.149  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:55.149  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:55.150  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 10:52:55.150  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:55.151  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 10:52:55.151  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:55.151  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:55.151  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@424fcc0 not in the list
08-26 10:52:55.151  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 10:52:55.151  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:55.153  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:55.153  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 10:52:55.153  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:55.153  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@887db9f removed from the list
08-26 10:52:55.153  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 10:52:55.153  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:55.153  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:55.153  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:52:55.154  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893413e removed from the list
08-26 10:52:55.154  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 10:52:55.154  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bd24ec added. We now have 2 listener(s)
08-26 10:52:55.155  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:55.156  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 10:52:55.156  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 10:52:55.156  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:52:55.156  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:55.156  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@650d0b5 added. We now have 9 listener(s)
08-26 10:52:55.157  3817  3866 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:55.157  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
08-26 10:52:55.160  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:55.165  3817  3866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:55.165  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:55.165  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:55.165  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:55.165  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:55.165  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:55.165  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:55.165  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:52:55.168  3817  3866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 10:52:55.169  3817  3866 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 10:52:55.170  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:52:55.170  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51892bb added. We now have 3 listener(s)
,08-26 10:52:55.173  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:55.175  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:55.177  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 10:52:55.177  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:52:55.177  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 10:52:55.178  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:55.178  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcda3d8 added. We now have 10 listener(s)
08-26 10:52:55.178  3817  3866 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 10:52:55.179  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 10:52:55.179  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 10:52:55.179  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 10:52:55.179  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:55.180  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 10:52:55.187  3817  3866 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 10:52:55.187  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 10:52:55.190  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 10:52:55.191  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 10:52:55.191  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 10:52:55.194  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 10:52:55.194  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 10:52:55.194  3817  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 10:52:55.195  3817  3866 D BluetoothAdapter: STATE_ON
,08-26 10:52:55.197  4171  4182 D BtGatt.GattService: registerClient() - UUID=8de440fa-a226-411d-9c74-43a4072ee924
08-26 10:52:55.200  4171  4187 D BtGatt.GattService: onClientRegistered() - UUID=8de440fa-a226-411d-9c74-43a4072ee924, clientIf=5
08-26 10:52:55.202  3817  3828 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 10:52:55.203  4171  4181 D BtGatt.GattService: start scan with filters
08-26 10:52:55.206  4171  4191 D BtGatt.ScanManager: handling starting scan
08-26 10:52:55.206  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 10:52:55.206  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 10:52:55.206  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 10:52:55.206  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 10:52:55.207  4171  4191 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b1b9ce
,08-26 10:52:55.209  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 10:52:55.209  4171  4187 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 10:52:55.209  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 10:52:55.209  3817  3817 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 10:52:55.209  4171  4187 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:55.210  4171  4191 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 10:52:55.211  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 10:52:55.214  3817  3866 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 10:52:55.215  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 10:52:55.215  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-26 10:52:55.216  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:55.216  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 10:52:55.216  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts,
,08-26 10:52:55.216  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 10:52:55.216  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 10:52:55.216  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 10:52:55.216  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 10:52:55.216  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 10:52:55.217  3817  3866 D BluetoothAdapter: STATE_ON
08-26 10:52:55.217  4171  4200 D BtGatt.GattService: stopScan() - queue size =1
08-26 10:52:55.218  4171  4188 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 10:52:55.218  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 10:52:55.218  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 10:52:55.218  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 10:52:55.218  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 10:52:55.219  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 10:52:55.219  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 10:52:55.219  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 10:52:55.220  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 10:52:55.220  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 10:52:55.220  4171  4187 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 10:52:55.220  4171  4187 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:55.220  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 10:52:55.221  4171  4191 D BtGatt.ScanManager: Starting BLE batch scan
08-26 10:52:55.221  4171  4191 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 10:52:55.222  3817  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 10:52:55.222  3817  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 10:52:55.222  3817  3817 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 10:52:55.224  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:55.224  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:55.224  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 10:52:55.224  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:55.224  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:55.224  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:52:55.224  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:52:55.224  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bd24ec removed from the list
08-26 10:52:55.224  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:55.224  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@650d0b5 removed from the list
,08-26 10:52:55.225  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:55.225  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:55.225  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:55.225  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:55.226  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 10:52:55.226  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:55.226  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 10:52:55.226  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@650d0b5 not in the list
08-26 10:52:55.226  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:55.226  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:55.227  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:55.227  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 10:52:55.227  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:55.227  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fcda3d8 removed from the list
08-26 10:52:55.227  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:55.227  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:55.227  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:55.228  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:52:55.228  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51892bb removed from the list
08-26 10:52:55.228  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 10:52:55.228  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e652584 added. We now have 2 listener(s)
08-26 10:52:55.228  4171  4187 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 10:52:55.228  4171  4187 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 10:52:55.230  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 10:52:55.230  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:52:55.230  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 10:52:55.230  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:55.230  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a97616d added. We now have 9 listener(s)
,08-26 10:52:55.230  3817  3866 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 10:52:55.231  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 10:52:55.238  4171  4187 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 10:52:55.238  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 10:52:55.238  4171  4187 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:55.243  3817  3866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:55.243  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:55.243  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:55.243  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:55.243  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:55.243  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:55.243  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,08-26 10:52:55.243  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:52:55.244  4171  4187 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 10:52:55.244  4171  4187 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:55.244  4171  4191 D BtGatt.ScanManager: stopping BLe Batch
,08-26 10:52:55.245  3817  3866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:55.245  3817  3866 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 10:52:55.246  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:52:55.246  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d889e33 added. We now have 3 listener(s)
,08-26 10:52:55.247  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:55.249  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:55.249  4171  4187 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 10:52:55.249  4171  4187 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:55.250  4171  4191 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 10:52:55.251  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 10:52:55.252  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:52:55.252  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:52:55.252  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-26 10:52:55.253  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d115f0 added. We now have 10 listener(s)
08-26 10:52:55.253  3817  3866 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-26 10:52:55.253  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 10:52:55.253  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 10:52:55.253  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 10:52:55.253  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 10:52:55.253  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:55.254  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 10:52:55.254  4171  4187 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 10:52:55.254  4171  4187 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:55.257  3817  3866 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 10:52:55.257  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 10:52:55.260  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 10:52:55.260  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 10:52:55.260  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 10:52:55.263  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 10:52:55.263  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 10:52:55.263  3817  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 10:52:55.263  3817  3866 D BluetoothAdapter: STATE_ON,
08-26 10:52:55.265  4171  4188 D BtGatt.GattService: registerClient() - UUID=5aef7f7b-769d-4929-a8fc-e64d745edb47
,08-26 10:52:55.265  4171  4187 D BtGatt.GattService: onClientRegistered() - UUID=5aef7f7b-769d-4929-a8fc-e64d745edb47, clientIf=5
08-26 10:52:55.265  3817  3828 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 10:52:55.266  4171  4182 D BtGatt.GattService: start scan with filters
,08-26 10:52:55.268  4171  4191 D BtGatt.ScanManager: handling starting scan
,08-26 10:52:55.268  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 10:52:55.268  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 10:52:55.268  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 10:52:55.269  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 10:52:55.272  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 10:52:55.272  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 10:52:55.272  3817  3817 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 10:52:55.273  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 10:52:55.274  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 10:52:55.275  3817  3866 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-26 10:52:55.275  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 10:52:55.275  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:55.275  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:55.275  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 10:52:55.275  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:55.275  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 10:52:55.275  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:52:55.275  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e652584 removed from the list
08-26 10:52:55.275  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 10:52:55.275  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a97616d removed from the list
08-26 10:52:55.275  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:55.275  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 10:52:55.276  4171  4187 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 10:52:55.276  4171  4187 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 10:52:55.276  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:55.276  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-26 10:52:55.276  4171  4191 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 10:52:55.276  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:55.276  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 10:52:55.277  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:55.277  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:55.277  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:55.277  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a97616d not in the list
,08-26 10:52:55.277  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 10:52:55.277  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 10:52:55.277  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 10:52:55.277  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 10:52:55.277  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 10:52:55.278  3817  3866 D BluetoothAdapter: STATE_ON
08-26 10:52:55.278  4171  4181 D BtGatt.GattService: stopScan() - queue size =1
,08-26 10:52:55.279  4171  4200 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 10:52:55.279  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 10:52:55.279  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 10:52:55.279  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 10:52:55.279  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 10:52:55.279  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 10:52:55.280  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 10:52:55.280  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 10:52:55.280  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 10:52:55.280  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 10:52:55.281  4171  4187 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 10:52:55.281  4171  4187 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:55.281  4171  4191 D BtGatt.ScanManager: Starting BLE batch scan
08-26 10:52:55.281  4171  4191 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 10:52:55.281  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:55.283  3817  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 10:52:55.283  3817  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 10:52:55.283  3817  3817 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 10:52:55.283  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 10:52:55.284  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:55.284  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:55.284  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d115f0 removed from the list
08-26 10:52:55.284  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:55.284  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:55.284  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:55.284  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:52:55.284  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d889e33 removed from the list
08-26 10:52:55.284  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:52:55.284  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9a11c added. We now have 2 listener(s)
08-26 10:52:55.286  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 10:52:55.286  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:52:55.286  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:52:55.286  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:55.287  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6985125 added. We now have 9 listener(s)
08-26 10:52:55.287  3817  3866 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 10:52:55.287  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 10:52:55.289  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 10:52:55.290  4171  4187 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 10:52:55.290  4171  4187 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:55.292  3817  3866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:55.292  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:55.292  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:55.292  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:55.292  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:55.292  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:55.292  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:55.292  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 10:52:55.293  3817  3866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 10:52:55.293  3817  3866 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 10:52:55.294  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:52:55.294  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:55.295  4171  4187 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 10:52:55.295  4171  4187 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:55.295  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8fa0ab added. We now have 3 listener(s)
08-26 10:52:55.296  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:55.297  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 10:52:55.297  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:52:55.297  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:52:55.297  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:55.297  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5db308 added. We now have 10 listener(s)
08-26 10:52:55.297  3817  3866 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:55.297  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 10:52:55.297  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 10:52:55.297  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 10:52:55.297  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 10:52:55.297  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 10:52:55.300  3817  3866 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 10:52:55.300  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 10:52:55.300  4171  4187 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 10:52:55.300  4171  4187 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:55.301  4171  4191 D BtGatt.ScanManager: stopping BLe Batch
,08-26 10:52:55.304  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 10:52:55.304  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 10:52:55.304  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 10:52:55.305  4171  4187 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 10:52:55.305  4171  4187 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:55.305  4171  4191 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 10:52:55.307  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 10:52:55.307  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 10:52:55.307  3817  3866 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 10:52:55.307  3817  3866 D BluetoothAdapter: STATE_ON
,08-26 10:52:55.308  4171  4182 D BtGatt.GattService: registerClient() - UUID=21d7e9fb-83b0-455f-a981-be4be9b7ca8e
,08-26 10:52:55.308  4171  4187 D BtGatt.GattService: onClientRegistered() - UUID=21d7e9fb-83b0-455f-a981-be4be9b7ca8e, clientIf=5
08-26 10:52:55.309  3817  3828 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 10:52:55.309  4171  4181 D BtGatt.GattService: start scan with filters
,08-26 10:52:55.309  4171  4187 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 10:52:55.309  4171  4187 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 10:52:55.310  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 10:52:55.310  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 10:52:55.311  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 10:52:55.311  4171  4191 D BtGatt.ScanManager: handling starting scan
08-26 10:52:55.311  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 10:52:55.312  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 10:52:55.312  3817  3817 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 10:52:55.312  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 10:52:55.313  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 10:52:55.316  4171  4187 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 10:52:55.316  4171  4187 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:55.316  4171  4191 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 10:52:55.317  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 10:52:55.317  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:55.317  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:55.317  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:55.317  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:55.317  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 10:52:55.317  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 10:52:55.317  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9a11c removed from the list
,08-26 10:52:55.317  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:55.317  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6985125 removed from the list
08-26 10:52:55.317  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:55.317  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:52:55.318  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:55.318  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 10:52:55.318  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:55.318  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 10:52:55.319  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:55.319  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:55.319  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 10:52:55.319  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6985125 not in the list
08-26 10:52:55.319  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 10:52:55.319  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 10:52:55.319  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 10:52:55.319  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 10:52:55.319  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 10:52:55.320  3817  3866 D BluetoothAdapter: STATE_ON
08-26 10:52:55.320  4171  4182 D BtGatt.GattService: stopScan() - queue size =1
,08-26 10:52:55.320  4171  4181 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 10:52:55.321  4171  4187 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 10:52:55.321  4171  4187 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:55.321  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 10:52:55.321  4171  4191 D BtGatt.ScanManager: Starting BLE batch scan
08-26 10:52:55.321  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 10:52:55.321  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 10:52:55.321  4171  4191 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 10:52:55.321  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 10:52:55.321  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 10:52:55.322  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 10:52:55.322  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 10:52:55.322  3817  3866 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 10:52:55.322  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 10:52:55.322  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 10:52:55.323  3817  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 10:52:55.323  3817  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 10:52:55.323  3817  3817 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 10:52:55.323  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:55.323  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 10:52:55.323  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 10:52:55.323  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5db308 removed from the list
08-26 10:52:55.323  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:55.323  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:55.323  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:55.323  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 10:52:55.324  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8fa0ab removed from the list
08-26 10:52:55.324  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:52:55.324  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ef7b4 added. We now have 2 listener(s)
,08-26 10:52:55.325  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 10:52:55.325  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:52:55.325  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:52:55.325  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 10:52:55.325  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d607fdd added. We now have 9 listener(s)
08-26 10:52:55.325  3817  3866 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:55.326  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 10:52:55.328  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 10:52:55.329  4171  4187 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 10:52:55.329  4171  4187 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 10:52:55.331  3817  3866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 10:52:55.331  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 10:52:55.331  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 10:52:55.331  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 10:52:55.331  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 10:52:55.331  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 10:52:55.331  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 10:52:55.331  3817  3866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 10:52:55.332  3817  3866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 10:52:55.333  3817  3866 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 10:52:55.333  4171  4187 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 10:52:55.333  4171  4187 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 10:52:55.333  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 10:52:55.334  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1357a23 added. We now have 3 listener(s)
,08-26 10:52:55.335  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 10:52:55.335  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 10:52:55.336  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 10:52:55.336  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 10:52:55.336  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 10:52:55.336  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90ddb20 added. We now have 10 listener(s)
08-26 10:52:55.336  3817  3866 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 10:52:55.336  3817  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 10:52:55.336  3817  3866 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 10:52:55.336  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 10:52:55.337  3817  3866 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 10:52:55.337  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:55.337  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:55.337  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 10:52:55.337  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 10:52:55.337  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@59ef7b4 removed from the list
,08-26 10:52:55.337  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:55.337  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d607fdd removed from the list
08-26 10:52:55.337  3817  3866 D io.jxcore.node.ConnectivityMonitor: stop
08-26 10:52:55.337  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:55.338  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:55.338  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:55.338  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 10:52:55.338  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:55.338  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:55.339  3817  3866 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d607fdd not in the list
08-26 10:52:55.339  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:55.339  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:55.339  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 10:52:55.339  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 10:52:55.340  3817  3866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 10:52:55.340  3817  3866 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90ddb20 removed from the list
08-26 10:52:55.340  3817  3866 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 10:52:55.340  3817  3866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 10:52:55.340  3817  3866 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 10:52:55.340  3817  3866 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 10:52:55.340  3817  3866 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1357a23 removed from the list
08-26 10:52:55.340  4171  4187 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 10:52:55.340  4171  4187 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:55.340  4171  4191 D BtGatt.ScanManager: stopping BLe Batch
08-26 10:52:55.341  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-26 10:52:55.341  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-26 10:52:55.341  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 10:52:55.341  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 10:52:55.341  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 10:52:55.341  3817  3866 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 10:52:55.344  4171  4187 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 10:52:55.344  4171  4187 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 10:52:55.344  4171  4191 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 10:52:55.346  3817  4250 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: My test thread name)
08-26 10:52:55.346  3817  4250 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 441, thread name: My test thread name)
,08-26 10:52:55.346  3817  4250 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 441, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 10:52:55.347  3817  4251 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 443, name: My test thread name)
08-26 10:52:55.347  3817  4251 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 443, thread name: My test thread name)
,08-26 10:52:55.348  3817  4251 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 443, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 10:52:55.349  4171  4187 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 10:52:55.349  4171  4187 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-26 10:52:55.349  3817  3866 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 10:52:55.349  3817  3866 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 10:52:55.349  3817  3866 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 10:52:55.349  3817  3866 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 10:52:55.349  3817  3866 D com.test.thalitest.ThaliTestRunner: Total duration: 22808 ms
,08-26 10:52:55.351  3817  3866 I jxcore-log: *Native tests were executed*
08-26 10:52:55.351  3817  3866 I jxcore-log: 
08-26 10:52:55.351  3817  3866 I jxcore-log: Total number of executed tests:  80
08-26 10:52:55.351  3817  3866 I jxcore-log: 
,08-26 10:52:55.351  3817  3866 I jxcore-log: Number of passed tests:  80
08-26 10:52:55.351  3817  3866 I jxcore-log: 
08-26 10:52:55.351  3817  3866 I jxcore-log: Number of failed tests:  0
08-26 10:52:55.351  3817  3866 I jxcore-log: 
08-26 10:52:55.351  3817  3866 I jxcore-log: Number of ignored tests:  0
08-26 10:52:55.351  3817  3866 I jxcore-log: 
08-26 10:52:55.352  3817  3866 I jxcore-log: Total duration:  22808
08-26 10:52:55.352  3817  3866 I jxcore-log: 
,08-26 10:52:55.352  3817  3866 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 10:52:55.352  3817  3866 I jxcore-log: 
08-26 10:52:55.354  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:55.354  3817  3866 I jxcore-log: 
,08-26 10:52:55.356  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:55.356  3817  3866 I jxcore-log: 
08-26 10:52:55.357  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:55.357  3817  3866 I jxcore-log: 
08-26 10:52:55.358  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:55.358  3817  3866 I jxcore-log: 
08-26 10:52:55.359  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:55.359  3817  3866 I jxcore-log: 
08-26 10:52:55.359  3817  3817 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 10:52:55.360  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:55.360  3817  3866 I jxcore-log: 
08-26 10:52:55.361  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:55.361  3817  3866 I jxcore-log: 
08-26 10:52:55.362  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 10:52:55.362  3817  3866 I jxcore-log: 
08-26 10:52:55.363  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 10:52:55.363  3817  3866 I jxcore-log: 
08-26 10:52:55.363  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 10:52:55.363  3817  3866 I jxcore-log: 
08-26 10:52:55.364  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 10:52:55.364  3817  3866 I jxcore-log: 
08-26 10:52:55.365  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 10:52:55.365  3817  3866 I jxcore-log: 
08-26 10:52:55.366  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 10:52:55.366  3817  3866 I jxcore-log: 
08-26 10:52:55.366  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:55.366  3817  3866 I jxcore-log: 
08-26 10:52:55.367  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:55.367  3817  3866 I jxcore-log: 
08-26 10:52:55.367  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 10:52:55.367  3817  3866 I jxcore-log: 
08-26 10:52:55.368  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 10:52:55.368  3817  3866 I jxcore-log: 
08-26 10:52:55.369  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 10:52:55.369  3817  3866 I jxcore-log: 
08-26 10:52:55.370  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 10:52:55.370  3817  3866 I jxcore-log: 
08-26 10:52:55.370  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 10:52:55.370  3817  3866 I jxcore-log: 
08-26 10:52:55.371  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 10:52:55.371  3817  3866 I jxcore-log: 
,08-26 10:52:55.371  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 10:52:55.371  3817  3866 I jxcore-log: 
08-26 10:52:55.371  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 10:52:55.371  3817  3866 I jxcore-log: 
08-26 10:52:55.372  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 10:52:55.372  3817  3866 I jxcore-log: 
08-26 10:52:55.372  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:55.372  3817  3866 I jxcore-log: 
,08-26 10:52:55.373  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:55.373  3817  3866 I jxcore-log: 
08-26 10:52:55.373  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:55.373  3817  3866 I jxcore-log: 
,08-26 10:52:55.374  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:55.374  3817  3866 I jxcore-log: 
08-26 10:52:55.374  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:55.374  3817  3866 I jxcore-log: 
08-26 10:52:55.374  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:55.374  3817  3866 I jxcore-log: 
,08-26 10:52:55.375  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 10:52:55.375  3817  3866 I jxcore-log: 
,08-26 10:52:55.686  3817  3817 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-26 10:52:55.687  3817  3817 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 10:52:55.716   875   895 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-26 10:52:55.717  3817  3817 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@333a4da Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@e6a3cd9, 16908290=android.view.AbsSavedState$1@e6a3cd9}, android:focusedViewId=100}]}]
08-26 10:52:55.717  3817  3817 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-26 10:52:55.717  3817  3817 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 10:52:55.717  3817  3817 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-26 10:52:55.719   875   895 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-26 10:52:55.722  3817  3817 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 10:52:55.723   875   893 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
08-26 10:52:55.723   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
08-26 10:52:55.723   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
08-26 10:52:55.727  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 10:52:55.727  3817  3866 I jxcore-log: 
,08-26 10:52:55.783  3817  3817 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 10:52:55.784  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 10:52:55.784  3817  3866 I jxcore-log: 
,08-26 10:52:55.824  3817  3817 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 10:52:55.825  3817  3866 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 10:52:55.825  3817  3866 I jxcore-log: 
,08-26 10:52:55.954   280   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-26 10:52:55.957   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-26 10:52:55.963   875  1333 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
,08-26 10:52:55.966   875   895 I DreamManagerService: Entering dreamland.
,08-26 10:52:55.968   875   895 I PowerManagerService: Dozing...
,08-26 10:52:55.969   875   890 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-26 10:52:56.010   376  1317 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-26 10:52:56.010   376  1317 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-26 10:52:56.018  1931  4256 D NfcService: Discovery configuration equal, not updating.
,08-26 10:52:56.021   875  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 10:52:56.029   875  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 10:52:56.030   875  1308 E native  : do suspend false
,08-26 10:52:56.043   875  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 10:52:56.052   875  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 10:52:56.054   875  1308 E native  : do suspend true
,08-26 10:52:56.059  4252  4252 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-26 10:52:56.069  4252  4252 D AndroidRuntime: CheckJNI is OFF
,08-26 10:52:56.123  4252  4252 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-26 10:52:56.151   376  1316 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-26 10:52:56.151   376  1316 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-26 10:52:56.191  4252  4252 I Radio-JNI: register_android_hardware_Radio DONE
,08-26 10:52:56.212  4252  4252 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 10:52:56.222   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-26 10:52:56.223   875   888 I ActivityManager: Killing 3817:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-26 10:52:56.318   875  1678 D GraphicsStats: Buffer count: 2
08-26 10:52:56.318   875  1518 I WindowState: WIN DEATH: Window{c5b4c1b u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-26 10:52:56.319   875  1309 D WifiService: Client connection lost with reason: 4
,08-26 10:52:56.323   875   898 W PackageSettings: Skipping PackageSetting{2f62923 com.example.hello/10273} due to missing metadata
,08-26 10:52:56.358   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-26 10:52:56.359   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-26 10:52:56.360   875   888 E ActivityManager: Failure starting process com.test.thalitest
08-26 10:52:56.360   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-26 10:52:56.360   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-26 10:52:56.360   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-26 10:52:56.360   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-26 10:52:56.360   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-26 10:52:56.360   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-26 10:52:56.360   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-26 10:52:56.360   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-26 10:52:56.360   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-26 10:52:56.360   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-26 10:52:56.360   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-26 10:52:56.360   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-26 10:52:56.360   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-26 10:52:56.360   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-26 10:52:56.360   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-26 10:52:56.360   875   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:56.360   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 10:52:56.360   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 10:52:56.360   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-26 10:52:56.360   875   888 I ActivityManager:   Force finishing activity ActivityRecord{5943040 u0 com.test.thalitest/.MainActivity t2}
,08-26 10:52:56.362   875   898 I art     : Starting a blocking GC Explicit
,08-26 10:52:56.367   875  1995 W ActivityManager: Spurious death for ProcessRecord{c11834e 0:com.test.thalitest/u0a0}, curProc for 3817: null
,08-26 10:52:56.404   875   898 I art     : Explicit concurrent mark sweep GC freed 17607(1122KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 728us total 41.141ms
,08-26 10:52:56.435   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-26 10:52:56.441  4252  4252 I art     : System.exit called, status: 0
,08-26 10:52:56.441  4252  4252 I AndroidRuntime: VM exiting with result code 0.
,08-26 10:52:56.450   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-26 10:52:56.470   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-26 10:52:56.473  4171  4171 D BluetoothMapAppObserver: onReceive
,08-26 10:52:56.474  4171  4171 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-26 10:52:56.479   875  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 10:52:56.479  1884  2278 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 10:52:56.483  3661  3661 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-26 10:52:56.493  1870  1870 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-26 10:52:56.505  1943  1943 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-26 10:52:56.514   875  1959 I ActivityManager: Start proc 4271:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-26 10:52:56.523  1870  4274 I Keyboard.Facilitator.DecoderInitializer: run()
,08-26 10:52:56.529  1870  4274 I Decoder : createOrResetDecoder
,08-26 10:52:56.564   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-26 10:52:56.570  1504  1504 I ConfigService: onCreate
,08-26 10:52:56.572  1504  4284 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-26 10:52:56.572  1504  4284 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 10:52:56.572  1504  4284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 10:52:56.572  1504  4284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 10:52:56.572  1504  4284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 10:52:56.572  1504  4284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 10:52:56.572  1504  4284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 10:52:56.572  1504  4284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 10:52:56.572  1504  4284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 10:52:56.572  1504  4284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 10:52:56.572  1504  4284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 10:52:56.572  1504  4284 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 10:52:56.572  1504  4284 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 10:52:56.572  1504  4284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 10:52:56.572  1504  4284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 10:52:56.572  1504  4284 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-26 10:52:56.572  1504  4284 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-26 10:52:56.572  1504  4284 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-26 10:52:56.573  1504  4284 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-26 10:52:56.573  1504  4284 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 10:52:56.573  1504  4284 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 10:52:56.573  1504  4284 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 10:52:56.573  1504  4284 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 10:52:56.573  1504  4284 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 10:52:56.573  1504  4284 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 10:52:56.573  1504  4284 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 10:52:56.573  1504  4284 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 10:52:56.573  1504  4284 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 10:52:56.573  1504  4284 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 10:52:56.573  1504  4284 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 10:52:56.573  1504  4284 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 10:52:56.573  1504  4284 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 10:52:56.573  1504  4284 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 10:52:56.573  1504  4284 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-26 10:52:56.573  1504  4284 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-26 10:52:56.573  1504  4284 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-26 10:52:56.574  1504  4284 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-26 10:52:56.576  4271  4271 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-26 10:52:56.581   875   885 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3817 uid 10000
,08-26 10:52:56.582  1870  1870 I Keyboard.Facilitator: onFinishInput()
,08-26 10:52:56.584  1870  4274 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-26 10:52:56.616   875  1334 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
,08-26 10:52:56.616   875  1334 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
08-26 10:52:56.616   875  1334 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
,08-26 10:52:56.616   875  1334 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
08-26 10:52:56.616   875  1334 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
,08-26 10:52:56.617   875  1334 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
,08-26 10:52:56.617   875  1334 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
08-26 10:52:56.617   875  1334 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
08-26 10:52:56.617   875  1334 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
08-26 10:52:56.617   875  1334 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
08-26 10:52:56.617   875  1334 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
08-26 10:52:56.617   875  1334 W System.err: 	... 4 more
,08-26 10:52:56.617   875  1334 D skia    : ------- write threw an exception
,08-26 10:52:56.623  1963  2080 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-26 10:52:56.624   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-26 10:52:56.624   875   887 E PackageManager: Failed to write settings, restoring backup
08-26 10:52:56.624   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-26 10:52:56.624   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-26 10:52:56.624   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-26 10:52:56.624   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-26 10:52:56.624   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-26 10:52:56.624   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:56.624   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 10:52:56.624   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 10:52:56.627   875   888 E DropBoxManagerService: Can't write: system_server_wtf
08-26 10:52:56.627   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-26 10:52:56.627   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 10:52:56.627   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 10:52:56.627   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 10:52:56.627   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 10:52:56.627   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 10:52:56.627   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 10:52:56.627   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-26 10:52:56.627   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-26 10:52:56.627   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-26 10:52:56.627   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 10:52:56.627   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 10:52:56.627   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-26 10:52:56.627   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 10:52:56.627   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-26 10:52:56.627   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 10:52:56.627   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 10:52:56.627   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 10:52:56.627   875   888 E DropBoxManagerService: ,	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 10:52:56.627   875   888 E DropBoxManagerService: 	... 13 more
,08-26 10:52:56.635   875  1995 I ActivityManager: Start proc 4289:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-26 10:52:56.636  1963  2080 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-26 10:52:56.636  1963  2080 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1963
08-26 10:52:56.636  1963  2080 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 10:52:56.636  1963  2080 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 10:52:56.636  1963  2080 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 10:52:56.636  1963  2080 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 10:52:56.636  1963  2080 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 10:52:56.636  1963  2080 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 10:52:56.636  1963  2080 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-26 10:52:56.636  1963  2080 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-26 10:52:56.636  1963  2080 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 10:52:56.636  1963  2080 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 10:52:56.636  1963  2080 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 10:52:56.636  1963  2080 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 10:52:56.636  1870  4274 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-26 10:52:56.638   875  1984 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-26 10:52:56.641   875  4295 E DropBoxManagerService: Can't write: system_app_crash
08-26 10:52:56.641   875  4295 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-26 10:52:56.641   875  4295 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 10:52:56.641   875  4295 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 10:52:56.641   875  4295 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 10:52:56.641   875  4295 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 10:52:56.641   875  4295 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 10:52:56.641   875  4295 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 10:52:56.641   875  4295 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 10:52:56.641   875  4295 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 10:52:56.641   875  4295 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 10:52:56.641   875  4295 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 10:52:56.641   875  4295 E DropBoxManagerService: 	... 5 more
,08-26 10:52:56.653  1963  2080 I Process : Sending signal. PID: 1963 SIG: 9
,08-26 10:52:56.655  1870  4274 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-26 10:52:56.655  1870  4274 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-26 10:52:56.657  1870  4274 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-26 10:52:56.657  1870  4274 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-26 10:52:56.658  1870  4274 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-26 10:52:56.658  1870  4274 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-26 10:52:56.659  1870  4274 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-26 10:52:56.659  1870  4274 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-26 10:52:56.659  1870  4274 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-26 10:52:56.659  1870  4274 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-26 10:52:56.659  1870  4274 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-26 10:52:56.659  1870  4274 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-26 10:52:56.667  4271  4271 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-26 10:52:56.684   875  1984 I ActivityManager: Start proc 4304:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-26 10:52:56.688  4271  4303 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-26 10:52:56.713  4304  4304 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-26 10:52:56.717  4271  4286 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 10:52:56.717  4271  4286 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 10:52:56.717  4271  4286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 10:52:56.717  4271  4286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 10:52:56.717  4271  4286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 10:52:56.717  4271  4286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 10:52:56.717  4271  4286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 10:52:56.717  4271  4286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 10:52:56.717  4271  4286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 10:52:56.717  4271  4286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 10:52:56.717  4271  4286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 10:52:56.717  4271  4286 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 10:52:56.717  4271  4286 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 10:52:56.717  4271  4286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 10:52:56.717  4271  4286 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 10:52:56.717  4271  4286 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 10:52:56.717  4271  4286 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 10:52:56.717  4271  4286 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 10:52:56.717  4271  4286 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 10:52:56.717  4271  4286 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:56.717  4271  4286 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 10:52:56.717  4271  4286 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 10:52:56.718  4271  4286 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-26 10:52:56.718  4271  4286 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 10:52:56.718  4271  4286 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 10:52:56.718  4271  4286 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 10:52:56.718  4271  4286 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 10:52:56.718  4271  4286 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 10:52:56.718  4271  4286 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 10:52:56.718  4271  4286 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 10:52:56.718  4271  4286 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 10:52:56.718  4271  4286 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 10:52:56.718  4271  4286 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 10:52:56.718  4271  4286 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 10:52:56.718  4271  4286 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 10:52:56.718  4271  4286 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 10:52:56.718  4271  4286 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 10:52:56.718  4271  4286 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 10:52:56.718  4271  4286 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 10:52:56.718  4271  4286 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 10:52:56.718  4271  4286 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 10:52:56.718  4271  4286 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:56.718  4271  4286 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-26 10:52:56.718  4271  4286 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 10:52:56.737  1504  1504 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-26 10:52:56.737   875  1679 D GraphicsStats: Buffer count: 1
08-26 10:52:56.737   875  1518 I WindowState: WIN DEATH: Window{5743b8c u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-26 10:52:56.738  1504  1504 D AndroidRuntime: Shutting down VM
08-26 10:52:56.738  1504  1504 E AndroidRuntime: FATAL EXCEPTION: main
08-26 10:52:56.738  1504  1504 E AndroidRuntime: Process: com.google.process.gapps, PID: 1504
08-26 10:52:56.738  1504  1504 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 10:52:56.738  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-26 10:52:56.738  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-26 10:52:56.738  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-26 10:52:56.738  1504  1504 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:56.738  1504  1504 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 10:52:56.738  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 10:52:56.738  1504  1504 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:56.738  1504  1504 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 10:52:56.738  1504  1504 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 10:52:56.738  1504  1504 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 10:52:56.738  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 10:52:56.738  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 10:52:56.738  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 10:52:56.738  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 10:52:56.738  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 10:52:56.738  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-26 10:52:56.738  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-26 10:52:56.738  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-26 10:52:56.738  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-26 10:52:56.738  1504  1504 E AndroidRuntime: 	... 8 more
,08-26 10:52:56.749   875  1679 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1963) has died
08-26 10:52:56.750   875  1679 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-26 10:52:56.751   875  1679 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-26 10:52:56.768   875   888 I ActivityManager: Start proc 4321:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-26 10:52:56.771   875  4326 E DropBoxManagerService: Can't write: system_app_crash
08-26 10:52:56.771   875  4326 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-26 10:52:56.771   875  4326 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 10:52:56.771   875  4326 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 10:52:56.771   875  4326 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 10:52:56.771   875  4326 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 10:52:56.771   875  4326 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 10:52:56.771   875  4326 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 10:52:56.771   875  4326 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 10:52:56.771   875  4326 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 10:52:56.771   875  4326 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 10:52:56.771   875  4326 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 10:52:56.771   875  4326 E DropBoxManagerService: 	... 5 more
,08-26 10:52:56.773  1504  1504 I Process : Sending signal. PID: 1504 SIG: 9
,08-26 10:52:56.797  1699  4329 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 352)
08-26 10:52:56.797  1699  4329 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@db2754a
08-26 10:52:56.797   875   886 I ActivityManager: Process com.google.process.gapps (pid 1504) early provider death
08-26 10:52:56.809  4271  4286 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-26 10:52:56.814   875  1309 D WifiService: Client connection lost with reason: 4
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 10:52:56.817  4271  4303 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 10:52:56.818  4271  4303 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-26 10:52:56.818  4271  4303 E AndroidRuntime: Process: android.process.acore, PID: 4271
08-26 10:52:56.818  4271  4303 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 10:52:56.818  4271  4303 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 10:52:56.818  4271  4303 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 10:52:56.818  4271  4303 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 10:52:56.818  4271  4303 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 10:52:56.818  4271  4303 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 10:52:56.818  4271  4303 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 10:52:56.818  4271  4303 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 10:52:56.818  4271  4303 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 10:52:56.818  4271  4303 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 10:52:56.818  4271  4303 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 10:52:56.818  4271  4303 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 10:52:56.818  4271  4303 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 10:52:56.818  4271  4303 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 10:52:56.818  4271  4303 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 10:52:56.818  4271  4303 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 10:52:56.818  4271  4303 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 10:52:56.818  4271  4303 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 10:52:56.818  4271  4303 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 10:52:56.818  4271  4303 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 10:52:56.818  4271  4303 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 10:52:56.818  4271  4303 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:56.818  4271  4303 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 10:52:56.818  4271  4303 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 10:52:56.818   875   886 I ActivityManager: Process com.google.process.gapps (pid 1504) has died
08-26 10:52:56.819   875   886 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
08-26 10:52:56.819   875   886 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
08-26 10:52:56.819   875   886 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
08-26 10:52:56.819   875   886 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 31000ms
08-26 10:52:56.820   875  1984 W ActivityManager: Spurious death for ProcessRecord{6b78743 0:com.google.process.gapps/u0a11}, curProc for 1504: null
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 10:52:56.823  4321  4321 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 10:52:56.823  4321  4321 D AndroidRuntime: Shutting down VM
08-26 10:52:56.833   875  1679 I ActivityManager: Start proc 4335:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-26 10:52:56.836  1699  1699 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-26 10:52:56.840  4321  4321 E AndroidRuntime: FATAL EXCEPTION: main
08-26 10:52:56.840  4321  4321 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4321
08-26 10:52:56.840  4321  4321 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 10:52:56.840  4321  4321 E AndroidRuntime: 	... 10 more
,08-26 10:52:56.841   875  4341 E DropBoxManagerService: Can't write: system_app_crash
08-26 10:52:56.841   875  4341 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-26 10:52:56.841   875  4341 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 10:52:56.841   875  4341 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 10:52:56.841   875  4341 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 10:52:56.841   875  4341 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 10:52:56.841   875  4341 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 10:52:56.841   875  4341 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 10:52:56.841   875  4341 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 10:52:56.841   875  4341 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 10:52:56.841   875  4341 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 10:52:56.841   875  4341 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 10:52:56.841   875  4341 E DropBoxManagerService: 	... 5 more
,08-26 10:52:56.842   875  1959 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-26 10:52:56.843  4321  4321 I Process : Sending signal. PID: 4321 SIG: 9
08-26 10:52:56.845   875  4348 E DropBoxManagerService: Can't write: system_app_crash
08-26 10:52:56.845   875  4348 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-26 10:52:56.845   875  4348 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 10:52:56.845   875  4348 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 10:52:56.845   875  4348 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 10:52:56.845   875  4348 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 10:52:56.845   875  4348 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 10:52:56.845   875  4348 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 10:52:56.845   875  4348 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 10:52:56.845   875  4348 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 10:52:56.845   875  4348 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 10:52:56.845   875  4348 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 10:52:56.845   875  4348 E DropBoxManagerService: 	... 5 more
,08-26 10:52:56.856  4271  4303 I Process : Sending signal. PID: 4271 SIG: 9
,08-26 10:52:56.867  4335  4335 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-26 10:52:56.872  4335  4335 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-26 10:52:56.873   875   885 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4321) has died
,08-26 10:52:56.874  1699  1699 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-26 10:52:56.874  1699  1699 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-26 10:52:56.875   875   885 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-26 10:52:56.875  4335  4335 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 10:52:56.875  4335  4335 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 10:52:56.876  4335  4335 D AndroidRuntime: Shutting down VM
,08-26 10:52:56.876  4335  4335 E AndroidRuntime: FATAL EXCEPTION: main
08-26 10:52:56.876  4335  4335 E AndroidRuntime: Process: com.google.process.gapps, PID: 4335
08-26 10:52:56.876  4335  4335 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.content,.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 10:52:56.876  4335  4335 E AndroidRuntime: 	... 10 more
,08-26 10:52:56.881  1699  1699 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-26 10:52:56.881  1699  1699 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-26 10:52:56.888  1699  4351 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-26 10:52:56.889   875   888 I ActivityManager: Start proc 4352:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-26 10:52:56.894  4335  4335 I Process : Sending signal. PID: 4335 SIG: 9
,08-26 10:52:56.894   875  4363 E DropBoxManagerService: Can't write: system_app_crash
08-26 10:52:56.894   875  4363 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-26 10:52:56.894   875  4363 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 10:52:56.894   875  4363 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 10:52:56.894   875  4363 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 10:52:56.894   875  4363 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 10:52:56.894   875  4363 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 10:52:56.894   875  4363 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 10:52:56.894   875  4363 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 10:52:56.894   875  4363 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 10:52:56.894   875  4363 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 10:52:56.894   875  4363 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 10:52:56.894   875  4363 E DropBoxManagerService: 	... 5 more
,08-26 10:52:56.909  1699  4351 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-26 10:52:56.909  1699  4351 E AndroidRuntime: Process: com.google.android.gms, PID: 1699
08-26 10:52:56.909  1699  4351 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 10:52:56.909  1699  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-26 10:52:56.909  1699  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-26 10:52:56.909  1699  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-26 10:52:56.909  1699  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-26 10:52:56.909  1699  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-26 10:52:56.909  1699  4351 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-26 10:52:56.909  1699  4351 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-26 10:52:56.909  1699  4351 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-26 10:52:56.909  1699  4351 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-26 10:52:56.909  1699  4351 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 10:52:56.909  1699  4351 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 10:52:56.909  1699  4351 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-26 10:52:56.909  1699  4351 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-26 10:52:56.909  1699  4351 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-26 10:52:56.909  1699  4351 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-26 10:52:56.909  1699  4351 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-26 10:52:56.909  1699  4351 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-26 10:52:56.909  1699  4351 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,08-26 10:52:56.911   875  4367 E DropBoxManagerService: Can't write: system_app_crash
08-26 10:52:56.911   875  4367 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-26 10:52:56.911   875  4367 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 10:52:56.911   875  4367 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 10:52:56.911   875  4367 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 10:52:56.911   875  4367 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 10:52:56.911   875  4367 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 10:52:56.911   875  4367 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 10:52:56.911   875  4367 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 10:52:56.911   875  4367 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 10:52:56.911   875  4367 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 10:52:56.911   875  4367 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 10:52:56.911   875  4367 E DropBoxManagerService: 	... 5 more
,08-26 10:52:56.911  1699  4351 I Process : Sending signal. PID: 1699 SIG: 9
,08-26 10:52:56.924   278   278 E lowmemorykiller: Error writing /proc/4271/oom_score_adj; errno=22

```
