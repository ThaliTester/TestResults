#### Test 822030602c9dbcd_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-22 18:30:26.069  3606  3622 D Finsky  : [288] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
08-22 18:30:26.078  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-22 18:30:26.090  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-22 18:30:26.093  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-22 18:30:26.127  1529  1551 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-22 18:30:26.127  1529  1551 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-22 18:30:26.127  1529  1551 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 18:30:26.127  1529  1551 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-22 18:30:26.159  3606  3622 D Finsky  : [288] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-22 18:30:27.103  3892  3892 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-22 18:30:27.108  3892  3892 D AndroidRuntime: CheckJNI is OFF
08-22 18:30:27.143  3892  3892 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-22 18:30:27.187  3892  3892 I Radio-JNI: register_android_hardware_Radio DONE
08-22 18:30:27.208  3892  3892 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-22 18:30:27.212   874   885 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-22 18:30:27.259  1993  2358 W SearchService: Abort, client detached.
08-22 18:30:27.277  3892  3892 D AndroidRuntime: Shutting down VM
08-22 18:30:27.278  1993  2305 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@713b547
08-22 18:30:27.279  1993  1993 I HotwordDetector: Closing mic
08-22 18:30:27.279  1993  2322 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-22 18:30:27.319   874  1399 I ActivityManager: Start proc 3902:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-22 18:30:27.349   376  2326 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-22 18:30:27.350   376  2326 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-22 18:30:27.355   376  1286 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-22 18:30:27.359  1993  2321 I MicroRecognitionRnrImpl: Detection finished
08-22 18:30:27.360  1993  2312 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-22 18:30:27.421  3902  3902 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-22 18:30:27.452  3902  3902 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-22 18:30:27.463  3902  3902 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 1050-1055)
08-22 18:30:27.463  3902  3902 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-22 18:30:27.486  3902  3902 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {53ab8f8}
08-22 18:30:27.487  3902  3902 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-22 18:30:27.487  3902  3902 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-22 18:30:27.503  3902  3902 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-22 18:30:27.505  3902  3902 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-22 18:30:27.528  3902  3902 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-22 18:30:27.541  3902  3902 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-22 18:30:27.541  3902  3902 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-22 18:30:27.541  3902  3902 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-22 18:30:27.541  3902  3902 I Adreno  : Build Date                       : 10/20/15
08-22 18:30:27.541  3902  3902 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-22 18:30:27.541  3902  3902 I Adreno  : Local Branch                     : M14
08-22 18:30:27.541  3902  3902 I Adreno  : Remote Branch                    : 
08-22 18:30:27.541  3902  3902 I Adreno  : Remote Branch                    : 
08-22 18:30:27.541  3902  3902 I Adreno  : Reconstruct Branch               : 
,08-22 18:30:27.625   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d49eee0:true
,08-22 18:30:27.698  3902  3902 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-22 18:30:27.722  3902  3902 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-22 18:30:27.835  3902  3941 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-22 18:30:27.853  3902  3927 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-22 18:30:27.886  3902  3941 I OpenGLRenderer: Initialized EGL, version 1.4
,08-22 18:30:27.940   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +653ms
,08-22 18:30:27.953  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-22 18:30:28.011  3902  3902 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3902
,08-22 18:30:28.142   874  1929 I ActivityManager: Killing 3068:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-22 18:30:28.186  3902  3902 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-22 18:30:28.211   874  1929 I ActivityManager: Killing 3316:com.google.android.gm/u0a78 (adj 15): empty #18
,08-22 18:30:28.340  3902  3943 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1679886032
,08-22 18:30:28.344  3902  3943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-22 18:30:28.344  3902  3943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-22 18:30:28.344  3902  3943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-22 18:30:28.344  3902  3943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-22 18:30:28.344  3902  3943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-22 18:30:28.344  3902  3943 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d9a1ef added. We now have 1 listener(s)
,08-22 18:30:28.348  3902  3943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-22 18:30:28.352  3902  3943 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-22 18:30:28.355  3902  3943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 18:30:28.357  3902  3943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 18:30:28.366  3902  3943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-22 18:30:28.366  3902  3943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-22 18:30:28.366  3902  3943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-22 18:30:28.366  3902  3943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-22 18:30:28.366  3902  3943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-22 18:30:28.366  3902  3943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-22 18:30:28.366  3902  3943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-22 18:30:28.366  3902  3943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-22 18:30:28.366  3902  3943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-22 18:30:28.366  3902  3943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-22 18:30:28.366  3902  3943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-22 18:30:28.366  3902  3943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-22 18:30:28.366  3902  3943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-22 18:30:28.366  3902  3943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-22 18:30:28.366  3902  3943 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98229da added. We now have 1 listener(s)
,08-22 18:30:28.367  3902  3943 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 18:30:28.371   874  1317 D WifiService: New client listening to asynchronous messages
,08-22 18:30:28.371  3902  3943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 18:30:28.371  3902  3943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-22 18:30:28.372  3902  3943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-22 18:30:28.372  3902  3943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-22 18:30:28.372  3902  3943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-22 18:30:28.377  3902  3943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 18:30:28.377  3902  3943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-22 18:30:28.385  3902  3943 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-22 18:30:28.386  3902  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-22 18:30:28.386  3902  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:28.386  3902  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:28.386  3902  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:30:28.386  3902  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:30:28.386  3902  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:28.386  3902  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:30:28.386  3902  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 18:30:28.386  3902  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-22 18:30:28.386  3902  3943 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 18:30:28.389  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:28.391  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:28.392  3902  3943 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-22 18:30:28.418  3902  3902 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-22 18:30:29.154  3902  3952 W jxcore-log: Initializing JXcore engine
,08-22 18:30:29.154  3902  3952 W jxcore-log: JXcore engine is ready
,08-22 18:30:29.192  3952  3952 W Thread-349: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8942 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-22 18:30:29.192  3952  3952 W Thread-349: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[11785]" dev="sockfs" ino=11785 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-22 18:30:29.192  3952  3952 W Thread-349: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-22 18:30:29.192  3952  3952 W Thread-349: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[27999]" dev="sockfs" ino=27999 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-22 18:30:29.207  3902  3952 W jxcore-log: Starting JXcore engine
,08-22 18:30:29.287  3902  3952 W jxcore-log: Platform android
08-22 18:30:29.287  3902  3952 W jxcore-log: 
08-22 18:30:29.288  3902  3952 W jxcore-log: Process ARCH arm
08-22 18:30:29.288  3902  3952 W jxcore-log: 
,08-22 18:30:29.480  3902  3952 I jxcore-log: JXcore Cordova bridge is ready!
08-22 18:30:29.480  3902  3952 I jxcore-log: 
08-22 18:30:29.480  3902  3952 W jxcore-log: JXcore engine is started
,08-22 18:30:29.492  3902  3943 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-22 18:30:29.497  3902  3902 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-22 18:30:39.019   874  1877 D NetlinkSocketObserver: NeighborEvent{elapsedMs=122610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-22 18:30:39.315  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-22 18:30:39.315  3902  3952 I jxcore-log: 
,08-22 18:30:39.318  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-22 18:30:39.318  3902  3952 I jxcore-log: 
,08-22 18:30:39.331  3902  3952 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:30:39.331  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:39.331  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:39.331  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:30:39.331  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:30:39.331  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:39.331  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:30:39.331  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 18:30:39.338  3902  3952 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 18:30:39.345  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-22 18:30:39.345  3902  3952 I jxcore-log: 
,08-22 18:30:39.352  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-22 18:30:39.352  3902  3952 I jxcore-log: 
,08-22 18:30:39.444   874  1316 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-22 18:30:39.876  3902  3952 D ExecuteNativeTests: Running unit tests
,08-22 18:30:39.935  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 18:30:39.935  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc added. We now have 2 listener(s)
,08-22 18:30:39.937  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-22 18:30:39.937  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:30:39.937  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 18:30:39.937  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:30:39.937  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 added. We now have 2 listener(s)
,08-22 18:30:39.937  3902  3952 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:30:39.938  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 18:30:39.945  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 18:30:39.958  3902  3952 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:30:39.958  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:39.958  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:39.958  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:30:39.958  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:30:39.958  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:39.958  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:30:39.958  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 18:30:39.963  3902  3952 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 18:30:39.963  3902  3952 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 18:30:39.966  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-22 18:30:39.966  3902  3952 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 18:30:39.966  3902  3952 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-22 18:30:39.967  3902  3952 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-22 18:30:39.968  3902  3952 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-22 18:30:39.968  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 18:30:39.968  3902  3952 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 18:30:39.968  3902  3952 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 18:30:39.968  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:39.969  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:39.969  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:39.969  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:39.969  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.969  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:30:39.970  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:30:39.970  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc removed from the list
08-22 18:30:39.970  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.970  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 removed from the list
08-22 18:30:39.970  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:39.971  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:39.971  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:39.972  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.972  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.975  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:39.975  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:39.975  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.976  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:39.977  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:39.980  3902  3952 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-22 18:30:39.983  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 18:30:39.983  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:39.983  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 18:30:39.984  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:39.984  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.985  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.985  3902  3952 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc not in the list
,08-22 18:30:39.985  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.986  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:39.986  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:39.986  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 18:30:39.986  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.986  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.987  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:39.989  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 18:30:39.989  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:39.989  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.989  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
,08-22 18:30:40.001  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-22 18:30:40.001  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-22 18:30:40.001  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-22 18:30:40.001  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-22 18:30:40.001  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-22 18:30:40.001  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-22 18:30:40.001  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-22 18:30:40.001  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-22 18:30:40.001  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-22 18:30:40.001  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-22 18:30:40.001  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-22 18:30:40.002  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-22 18:30:40.002  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-22 18:30:40.002  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-22 18:30:40.002  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-22 18:30:40.002  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-22 18:30:40.002  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-22 18:30:40.002  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-22 18:30:40.002  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-22 18:30:40.002  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-22 18:30:40.002  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-22 18:30:40.002  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-22 18:30:40.002  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-22 18:30:40.002  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-22 18:30:40.002  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-22 18:30:40.003  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-22 18:30:40.003  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-22 18:30:40.003  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-22 18:30:40.003  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-22 18:30:40.003  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-22 18:30:40.003  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-22 18:30:40.003  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:40.003  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:40.003  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:40.003  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:40.003  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.004  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.004  3902  3952 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc not in the list
08-22 18:30:40.004  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.004  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.004  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:40.004  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.004  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.004  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.004  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.005  3902  3952 I org.thaliproject.p2p.btconnecto,rlib.DiscoveryManager: stopAdvertising
08-22 18:30:40.006  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:40.006  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.006  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.006  3902  3952 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-22 18:30:40.008  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:30:40.015  3902  3952 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:30:40.015  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:40.015  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:40.015  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:30:40.015  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:30:40.015  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:40.015  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:30:40.015  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 18:30:40.019  3902  3952 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:40.019  3902  3952 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 18:30:40.019  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 18:30:40.020  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 18:30:40.022  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 18:30:40.022  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:30:40.022  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 18:30:40.024  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:40.027  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:40.028  3902  3952 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-22 18:30:40.028  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-22 18:30:40.040  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-22 18:30:40.042  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-22 18:30:40.043  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-22 18:30:40.046  3902  3952 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-22 18:30:40.052  3902  3952 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-22 18:30:40.052  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 18:30:40.052  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 18:30:40.053  3902  3952 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-22 18:30:40.054  3902  3952 D BluetoothAdapter: STATE_ON
08-22 18:30:40.061  2578  2588 D BtGatt.GattService: registerClient() - UUID=d7e5798d-ab26-4a67-a4f5-e44cab40646a
08-22 18:30:40.063  2578  2597 D BtGatt.GattService: onClientRegistered() - UUID=d7e5798d-ab26-4a67-a4f5-e44cab40646a, clientIf=5
08-22 18:30:40.063  3902  3913 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-22 18:30:40.064  2578  2590 D BtGatt.GattService: start scan with filters
08-22 18:30:40.068  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 18:30:40.068  2578  2601 D BtGatt.ScanManager: handling starting scan
08-22 18:30:40.068  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 18:30:40.068  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 18:30:40.068  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-22 18:30:40.070  2578  2601 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a394dc2
08-22 18:30:40.071  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 18:30:40.071  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-22 18:30:40.071  3902  3902 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 18:30:40.072  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-22 18:30:40.075  3902  3952 I io.jxcore.node.ConnectionHelper: start: OK
08-22 18:30:40.079  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:40.079  3902  3952 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 18:30:40.079  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:40.079  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-22 18:30:40.079  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.079  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 18:30:40.079  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 18:30:40.079  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 18:30:40.079  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 18:30:40.080  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 18:30:40.080  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 18:30:40.080  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-22 18:30:40.081  3902  3952 D BluetoothAdapter: STATE_ON
08-22 18:30:40.082  2578  2590 D BtGatt.GattService: stopScan() - queue size =1
08-22 18:30:40.083  2578  2597 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-22 18:30:40.083  2578  2597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:30:40.083  2578  2721 D BtGatt.GattService: unregisterClient() - clientIf=5
08-22 18:30:40.084  2578  2601 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-22 18:30:40.084  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:30:40.084  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 18:30:40.084  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 18:30:40.084  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 18:30:40.084  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-22 18:30:40.085  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 18:30:40.085  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 18:30:40.085  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 18:30:40.086  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 18:30:40.087  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:30:40.089  3902  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:30:40.089  3902  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:30:40.090  3902  3902 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 18:30:40.090  2578  2597 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-22 18:30:40.090  2578  2597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:30:40.090  2578  2601 D BtGatt.ScanManager: Starting BLE batch scan
08-22 18:30:40.090  2578  2601 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-22 18:30:40.090  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:40.091  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.091  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-22 18:30:40.091  3902  3952 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc not in the list
08-22 18:30:40.091  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.091  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.091  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:40.091  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.092  3902  3952 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-22 18:30:40.094  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:30:40.101  3902  3952 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:30:40.101  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:40.101  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:40.101  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:30:40.101  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:30:40.101  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:40.101  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:30:40.101  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 18:30:40.102  2578  2597 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-22 18:30:40.103  2578  2597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:30:40.105  3902  3952 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:40.105  3902  3952 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 18:30:40.105  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 18:30:40.105  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 18:30:40.105  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 18:30:40.105  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:30:40.105  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 18:30:40.109  3902  3952 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-22 18:30:40.109  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-22 18:30:40.109  2578  2597 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-22 18:30:40.109  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:40.109  2578  2597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:30:40.115  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:40.118  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-22 18:30:40.118  2578  2597 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-22 18:30:40.118  2578  2597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:30:40.118  2578  2601 D BtGatt.ScanManager: stopping BLe Batch
08-22 18:30:40.119  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-22 18:30:40.119  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-22 18:30:40.124  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-22 18:30:40.124  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 18:30:40.125  3902  3952 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-22 18:30:40.125  2578  2597 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-22 18:30:40.125  2578  2597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:30:40.125  2578  2601 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-22 18:30:40.125  3902  3952 D BluetoothAdapter: STATE_ON
08-22 18:30:40.130  2578  2721 D BtGatt.GattService: registerClient() - UUID=e1c3ddd7-a665-4b46-9dbd-c5a31e2069b4
08-22 18:30:40.131  2578  2597 D BtGatt.GattService: onClientRegistered() - UUID=e1c3ddd7-a665-4b46-9dbd-c5a31e2069b4, clientIf=5
08-22 18:30:40.132  3902  3914 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-22 18:30:40.132  2578  2597 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-22 18:30:40.132  2578  2597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:30:40.133  2578  2588 D BtGatt.GattService: start scan with filters
,08-22 18:30:40.138  2578  2601 D BtGatt.ScanManager: handling starting scan
,08-22 18:30:40.139  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 18:30:40.139  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-22 18:30:40.139  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 18:30:40.139  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 18:30:40.142  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 18:30:40.143  3902  3902 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 18:30:40.143  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 18:30:40.144  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 18:30:40.148  3902  3952 I io.jxcore.node.ConnectionHelper: start: OK
,08-22 18:30:40.148  2578  2597 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-22 18:30:40.148  2578  2597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:30:40.148  2578  2601 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-22 18:30:40.152  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:40.152  3902  3952 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 18:30:40.152  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-22 18:30:40.152  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-22 18:30:40.157  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.157  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 18:30:40.157  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 18:30:40.157  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 18:30:40.157  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-22 18:30:40.157  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 18:30:40.158  2578  2597 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-22 18:30:40.158  2578  2597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:30:40.158  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 18:30:40.158  2578  2601 D BtGatt.ScanManager: Starting BLE batch scan
,08-22 18:30:40.158  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-22 18:30:40.158  2578  2601 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-22 18:30:40.160  3902  3952 D BluetoothAdapter: STATE_ON
,08-22 18:30:40.161  2578  2588 D BtGatt.GattService: stopScan() - queue size =1,
,08-22 18:30:40.162  2578  2712 D BtGatt.GattService: unregisterClient() - clientIf=5,
08-22 18:30:40.163  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:30:40.163  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 18:30:40.163  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 18:30:40.163  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 18:30:40.163  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 18:30:40.165  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 18:30:40.165  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 18:30:40.165  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 18:30:40.165  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 18:30:40.166  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 18:30:40.168  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 18:30:40.168  3902  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:30:40.168  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.168  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:30:40.169  3902  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:30:40.169  3902  3952 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc not in the list
08-22 18:30:40.169  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 18:30:40.169  3902  3902 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 18:30:40.169  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.169  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:40.169  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.170  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.170  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:40.171  2578  2597 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-22 18:30:40.171  2578  2597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:30:40.173  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 18:30:40.173  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:40.173  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.173  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
,08-22 18:30:40.174  3902  3952 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-22 18:30:40.176  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 18:30:40.178  2578  2597 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-22 18:30:40.178  2578  2597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 18:30:40.185  3902  3952 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:30:40.185  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:40.185  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:40.185  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:30:40.185  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:30:40.185  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:40.185  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:30:40.185  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 18:30:40.188  2578  2597 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-22 18:30:40.188  2578  2597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:30:40.188  2578  2601 D BtGatt.ScanManager: stopping BLe Batch
,08-22 18:30:40.189  3902  3952 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:40.189  3902  3952 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 18:30:40.190  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-22 18:30:40.191  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-22 18:30:40.191  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-22 18:30:40.191  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 18:30:40.191  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 18:30:40.191  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:40.194  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:40.197  2578  2597 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-22 18:30:40.197  2578  2597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:30:40.197  2578  2601 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-22 18:30:40.199  3902  3952 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-22 18:30:40.199  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 18:30:40.204  2578  2597 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-22 18:30:40.205  2578  2597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 18:30:40.206  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 18:30:40.207  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-22 18:30:40.207  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 18:30:40.213  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 18:30:40.213  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 18:30:40.213  3902  3952 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 18:30:40.214  3902  3952 D BluetoothAdapter: STATE_ON
,08-22 18:30:40.217  2578  2721 D BtGatt.GattService: registerClient() - UUID=0507676e-04f4-41f5-881c-82a523b2c8f8
,08-22 18:30:40.218  2578  2597 D BtGatt.GattService: onClientRegistered() - UUID=0507676e-04f4-41f5-881c-82a523b2c8f8, clientIf=5
08-22 18:30:40.218  3902  3914 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-22 18:30:40.219  2578  2588 D BtGatt.GattService: start scan with filters
,08-22 18:30:40.223  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-22 18:30:40.223  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 18:30:40.224  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 18:30:40.224  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 18:30:40.224  2578  2601 D BtGatt.ScanManager: handling starting scan
,08-22 18:30:40.227  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 18:30:40.227  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-22 18:30:40.227  3902  3902 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 18:30:40.230  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 18:30:40.233  3902  3952 I io.jxcore.node.ConnectionHelper: start: OK
,08-22 18:30:40.233  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 18:30:40.233  3902  3952 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-22 18:30:40.233  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:40.233  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-22 18:30:40.234  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 18:30:40.234  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 18:30:40.234  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-22 18:30:40.234  2578  2597 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-22 18:30:40.234  2578  2597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 18:30:40.234  2578  2601 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-22 18:30:40.235  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-22 18:30:40.235  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-22 18:30:40.235  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-22 18:30:40.235  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-22 18:30:40.235  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 18:30:40.236  3902  3952 D BluetoothAdapter: STATE_ON
,08-22 18:30:40.237  2578  2588 D BtGatt.GattService: stopScan() - queue size =1
,08-22 18:30:40.239  2578  2590 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-22 18:30:40.239  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-22 18:30:40.239  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-22 18:30:40.239  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-22 18:30:40.239  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-22 18:30:40.240  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-22 18:30:40.241  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 18:30:40.241  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-22 18:30:40.241  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-22 18:30:40.242  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 18:30:40.242  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:30:40.243  2578  2597 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-22 18:30:40.243  2578  2597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:30:40.243  2578  2601 D BtGatt.ScanManager: Starting BLE batch scan
08-22 18:30:40.243  2578  2601 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-22 18:30:40.244  3902  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:30:40.245  3902  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:30:40.245  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:40.245  3902  3902 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 18:30:40.245  3902  3952 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 18:30:40.245  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-22 18:30:40.245  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:40.245  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:40.245  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.245  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:30:40.245  3902  3952 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc not in the list
08-22 18:30:40.246  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 18:30:40.246  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.246  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 18:30:40.246  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.247  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.247  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.248  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:40.248  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:40.248  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.248  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.249  3902  3952 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-22 18:30:40.249  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:40.250  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-22 18:30:40.250  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:40.250  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:40.250  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.250  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:40.250  3902  3952 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc not in the list
,08-22 18:30:40.250  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.250  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.250  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:40.250  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.251  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.251  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 18:30:40.251  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.252  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:40.252  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:40.252  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.252  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.253  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-22 18:30:40.254  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:40.254  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:40.254  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 18:30:40.254  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 18:30:40.254  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 18:30:40.254  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:40.254  3902  3952 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc not in the list
,08-22 18:30:40.254  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.255  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
,08-22 18:30:40.255  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 18:30:40.255  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 18:30:40.255  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:40.255  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 18:30:40.255  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:40.256  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 18:30:40.257  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 18:30:40.257  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 18:30:40.257  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list,
,08-22 18:30:40.258  3902  3952 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-22 18:30:40.259  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:40.259  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-22 18:30:40.259  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 18:30:40.259  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:40.259  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 18:30:40.259  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:40.259  3902  3952 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc not in the list
,08-22 18:30:40.259  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.259  2578  2597 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-22 18:30:40.259  2578  2597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:30:40.259  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.260  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:40.260  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 18:30:40.260  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.260  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.260  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:40.261  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:40.261  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 18:30:40.261  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.261  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.262  3902  3952 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-22 18:30:40.262  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 18:30:40.262  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:40.262  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 18:30:40.263  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:40.263  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 18:30:40.263  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.263  3902  3952 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc not in the list,
08-22 18:30:40.263  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.263  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
,08-22 18:30:40.263  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:40.263  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 18:30:40.263  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.263  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 18:30:40.263  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.266  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:40.266  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 18:30:40.266  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.266  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
,08-22 18:30:40.267  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-22 18:30:40.268  3902  3952 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-22 18:30:40.268  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 18:30:40.269  3902  3952 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-22 18:30:40.269  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-22 18:30:40.269  3902  3952 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-22 18:30:40.269  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:40.269  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:40.269  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:40.270  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 18:30:40.270  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.270  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:40.270  3902  3952 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc not in the list
08-22 18:30:40.270  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.270  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.270  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 18:30:40.270  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.270  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:40.270  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.270  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.271  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-22 18:30:40.271  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:40.271  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.271  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
,08-22 18:30:40.272  2578  2597 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-22 18:30:40.272  2578  2597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:30:40.273  3902  3952 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
08-22 18:30:40.273  3902  3952 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-22 18:30:40.274  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-22 18:30:40.283  3902  3952 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-22 18:30:40.283  3902  3952 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-22 18:30:40.283  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-22 18:30:40.283  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-22 18:30:40.284  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-22 18:30:40.284  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-22 18:30:40.285  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410],
08-22 18:30:40.285  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-22 18:30:40.285  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-22 18:30:40.286  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-22 18:30:40.286  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-22 18:30:40.286  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-22 18:30:40.286  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-22 18:30:40.286  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-22 18:30:40.286  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-22 18:30:40.286  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-22 18:30:40.286  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-22 18:30:40.286  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-22 18:30:40.286  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-22 18:30:40.288  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-22 18:30:40.288  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-22 18:30:40.288  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-22 18:30:40.288  2578  2597 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-22 18:30:40.288  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-22 18:30:40.288  2578  2597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:30:40.288  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-22 18:30:40.288  2578  2601 D BtGatt.ScanManager: stopping BLe Batch
08-22 18:30:40.288  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-22 18:30:40.288  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-22 18:30:40.288  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-22 18:30:40.289  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-22 18:30:40.289  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-22 18:30:40.289  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-22 18:30:40.289  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-22 18:30:40.289  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-22 18:30:40.289  3902  3952 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-22 18:30:40.290  3902  3952 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 18:30:40.290  3902  3952 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-22 18:30:40.291  3902  3952 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 18:30:40.291  3902  3952 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 18:30:40.291  3902  3952 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-22 18:30:40.291  3902  3952 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 18:30:40.291  3902  3952 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-22 18:30:40.291  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-22 18:30:40.295  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-22 18:30:40.296  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-22 18:30:40.296  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-22 18:30:40.297  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-22 18:30:40.297  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-22 18:30:40.297  3902  3952 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-22 18:30:40.297  3902  3952 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 18:30:40.297  3902  3952 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-22 18:30:40.298  2578  2597 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-22 18:30:40.298  2578  2597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 18:30:40.298  2578  2601 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-22 18:30:40.298  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:40.298  3902  3962 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 413)
08-22 18:30:40.299  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:40.299  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:40.299  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:40.299  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.299  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.299  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-22 18:30:40.300  3902  3952 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc not in the list
08-22 18:30:40.300  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.300  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
,08-22 18:30:40.300  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:40.300  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.300  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.300  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.300  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.301  3902  3962 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 18:30:40.302  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:40.302  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:40.302  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.302  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.303  3902  3952 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-22 18:30:40.303  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 18:30:40.303  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:40.303  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:40.304  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:40.304  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.304  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.304  3902  3952 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc not in the list
08-22 18:30:40.304  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.304  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.304  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:40.304  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.304  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.304  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.304  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.305  3902  3963 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 413
,08-22 18:30:40.305  3902  3963 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 413)
08-22 18:30:40.305  2578  2704 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-22 18:30:40.305  3902  3962 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 413)
08-22 18:30:40.305  3902  3963 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 413)
08-22 18:30:40.307  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:40.307  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:40.307  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.307  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.307  3902  3952 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-22 18:30:40.308  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:40.308  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:40.308  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:40.309  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 18:30:40.309  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.309  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.309  3902  3952 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc not in the list
08-22 18:30:40.309  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.309  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.309  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:40.309  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.309  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.309  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.309  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.310  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:40.310  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:40.310  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 18:30:40.310  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.311  3902  3952 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-22 18:30:40.311  3902  3952 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-22 18:30:40.311  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 18:30:40.311  3902  3952 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-22 18:30:40.311  3902  3952 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-22 18:30:40.311  3902  3952 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-22 18:30:40.311  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-22 18:30:40.311  3902  3952 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-22 18:30:40.311  3902  3952 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-22 18:30:40.311  3902  3952 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-22 18:30:40.311  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-22 18:30:40.312  3902  3952 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,08-22 18:30:40.312  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:40.312  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:40.312  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:40.312  2578  2597 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-22 18:30:40.312  2578  2597 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:30:40.312  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:40.312  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.312  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.312  3902  3952 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc not in the list
08-22 18:30:40.312  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.313  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
,08-22 18:30:40.313  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:40.313  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.313  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.313  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.313  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.315  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:40.315  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:40.315  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 18:30:40.315  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.316  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:40.316  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.316  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.316  3902  3952 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc not in the list
08-22 18:30:40.316  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.316  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.316  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:40.316  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.316  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.316  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 18:30:40.317  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.317  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:40.317  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.317  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.317  3902  3952 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc not in the list
08-22 18:30:40.317  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:40.317  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:40.317  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:40.317  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:40.317  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.317  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.317  3902  3952 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc not in the list
,08-22 18:30:40.317  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.317  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.318  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:40.318  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.318  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.318  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.318  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.319  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:40.319  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:40.319  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 18:30:40.319  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.324  3902  3952 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-22 18:30:40.325  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:30:40.327  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-22 18:30:40.329  3902  3952 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-22 18:30:40.329  3902  3952 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-22 18:30:40.330  3902  3902 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-22 18:30:40.331  3902  3964 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 18:30:40.331  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-22 18:30:40.332  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 18:30:40.332  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:40.333  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-22 18:30:40.333  3902  3964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-22 18:30:40.333  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-22 18:30:40.333  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-22 18:30:40.334  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.334  3902  3964 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-22 18:30:40.334  3902  3964 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-22 18:30:40.334  3902  3964 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-22 18:30:40.334  3902  3952 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-22 18:30:40.335  3902  3902 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-22 18:30:40.335  3902  3902 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-22 18:30:40.335  3902  3952 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc not in the list
08-22 18:30:40.336  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.336  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 18:30:40.336  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-22 18:30:40.336  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 18:30:40.337  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.338  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:40.340  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 18:30:40.340  3902  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 18:30:40.341  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.341  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:40.341  3902  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 18:30:40.341  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:40.341  3902  3902 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 18:30:40.341  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:40.341  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:40.341  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.341  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.341  3902  3952 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc not in the list
08-22 18:30:40.341  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.341  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
,08-22 18:30:40.342  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:40.342  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.342  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.342  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.342  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.343  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:40.343  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:40.344  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.344  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.345  3902  3952 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-22 18:30:40.345  3902  3952 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-22 18:30:40.345  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 18:30:40.345  3902  3952 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 18:30:40.345  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:40.345  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-22 18:30:40.345  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:40.345  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:40.345  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.345  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.346  3902  3952 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc not in the list
08-22 18:30:40.346  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.346  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.346  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:40.346  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.346  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.346  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.346  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.347  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:40.347  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:40.347  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.347  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
,08-22 18:30:40.350  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 18:30:40.350  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:40.350  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 18:30:40.350  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:40.350  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.350  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.350  3902  3952 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc not in the list
,08-22 18:30:40.351  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.351  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.351  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:40.351  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 18:30:40.351  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.351  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.351  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.352  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 18:30:40.352  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:40.352  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.352  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
,08-22 18:30:40.352  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:40.352  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-22 18:30:40.352  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:40.353  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 18:30:40.353  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.353  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:40.353  3902  3952 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b7c94cc not in the list
08-22 18:30:40.353  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:40.353  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
,08-22 18:30:40.353  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:40.353  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.353  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:40.353  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:40.353  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:40.354  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:40.354  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:40.354  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 18:30:40.354  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b29b315 not in the list
08-22 18:30:40.355  3902  3952 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-22 18:30:40.355  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 18:30:40.355  3902  3952 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-22 18:30:40.355  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 18:30:40.355  3902  3952 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-22 18:30:40.355  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-22 18:30:40.357  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-22 18:30:40.357  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-22 18:30:40.357  3902  3952 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1,
08-22 18:30:40.357  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-22 18:30:40.357  3902  3952 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-22 18:30:40.358  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-22 18:30:40.358  3902  3952 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-22 18:30:40.358  3902  3952 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-22 18:30:40.358  3902  3952 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-22 18:30:40.358  3902  3952 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-22 18:30:40.359  3902  3952 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-22 18:30:40.359  3902  3952 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-22 18:30:40.359  3902  3952 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-22 18:30:40.359  3902  3952 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-22 18:30:40.360  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:30:40.360  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d6645ef added. We now have 2 listener(s)
08-22 18:30:40.360  3902  3952 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:30:40.361  3902  3952 D BluetoothAdapter: enable(): BT is already enabled..!
08-22 18:30:40.362   874   884 D WifiService: setWifiEnabled: true pid=3902, uid=10000
,08-22 18:30:40.362   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-22 18:30:40.362  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:30:40.362  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b4c8fc added. We now have 3 listener(s)
08-22 18:30:40.362  3902  3952 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 18:30:40.367  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:30:40.367  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@81e8b85 added. We now have 4 listener(s)
08-22 18:30:40.367  3902  3952 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 18:30:40.368  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:30:40.368  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1621dda added. We now have 5 listener(s)
08-22 18:30:40.368  3902  3952 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 18:30:40.370   874  1404 D WifiService: setWifiEnabled: false pid=3902, uid=10000
08-22 18:30:40.370   874  1404 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-22 18:30:40.374  2578  2592 D BluetoothAdapterState: Current state: ON, message: 23
,08-22 18:30:40.374  2578  2592 D BluetoothAdapterProperties: Setting state to 13
,08-22 18:30:40.374  2578  2592 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-22 18:30:40.374  2578  2592 D BluetoothAdapterProperties: onBluetoothDisable()
,08-22 18:30:40.376  2578  2592 I BluetoothAdapterState: Entering PendingCommandState
08-22 18:30:40.377  2578  2578 D BluetoothMapService: onReceive
08-22 18:30:40.377  2578  2578 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-22 18:30:40.377  2578  2578 D BluetoothMapService: STATE_TURNING_OFF
08-22 18:30:40.377  2578  2578 D BluetoothMapService: MAP Service closeService in
,08-22 18:30:40.377  2578  2578 D BluetoothMapMasInstance0: MAP Service shutdown
08-22 18:30:40.377  2578  2578 D ObexServerSockets0: shutdown(block = true)
08-22 18:30:40.378  2578  2578 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-22 18:30:40.378  2578  2578 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-22 18:30:40.378  2578  2723 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-22 18:30:40.378  2578  2704 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-22 18:30:40.379  2578  2722 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-22 18:30:40.380  2578  2578 I BtOppRfcommListener: stopping Accept Thread
,08-22 18:30:40.380  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:30:40.380  2578  3522 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-22 18:30:40.380  2578  3522 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-22 18:30:40.383  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:40.383  3902  3952 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:30:40.383  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:40.383  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:40.383  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:30:40.383  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:40.383  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:40.383  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:30:40.383  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 18:30:40.384  3902  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:40.384  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:40.384  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:40.384  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:40.384  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:30:40.384  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:40.384  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:40.384  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:30:40.384  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 18:30:40.384  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:40.384  3902  3952 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 18:30:40.384  3902  3952 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 18:30:40.385  3902  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:40.386  3902  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 18:30:40.388  1476  1476 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-22 18:30:40.388  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:40.390  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:40.391   874  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-22 18:30:40.392   874  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-22 18:30:40.392   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-22 18:30:40.392   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-22 18:30:40.393   874   887 I ActivityManager: Start proc 3967:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-22 18:30:40.394  2578  2597 D BluetoothAdapterProperties: Scan Mode:20
08-22 18:30:40.397  2578  2592 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-22 18:30:40.399  2578  2578 D HeadsetService: Received stop request...Stopping profile...
08-22 18:30:40.400   874  1878 D DhcpClient: Clearing IP address
,08-22 18:30:40.401  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:40.402   874   874 D BluetoothHeadset: Proxy object disconnected
08-22 18:30:40.402   874   874 D BluetoothHeadset: Proxy object disconnected
,08-22 18:30:40.402   372   872 D CommandListener: Clearing all IP addresses on wlan0
08-22 18:30:40.403  2578  2578 D A2dpService: Received stop request...Stopping profile...
08-22 18:30:40.404  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:40.404  2578  2716 D A2dpStateMachine: Exit Disconnected: -1
,08-22 18:30:40.405  1921  2074 D BluetoothHeadset: Proxy object disconnected
,08-22 18:30:40.406  1374  1374 D BluetoothA2dp: Proxy object disconnected
,08-22 18:30:40.406  2578  2578 V BluetoothAdapterState: isTurningOff()=true
,08-22 18:30:40.406   874   874 D BluetoothHeadset: Proxy object disconnected
08-22 18:30:40.406  2578  2578 V BluetoothAdapterState: isTurningOn()=false
,08-22 18:30:40.406  2578  2578 V BluetoothAdapterState: isBleTurningOn()=false
08-22 18:30:40.406  2578  2578 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 18:30:40.406  1374  2029 D BluetoothHeadset: Proxy object disconnected
,08-22 18:30:40.406   874   874 D BluetoothA2dp: Proxy object disconnected
08-22 18:30:40.407  1374  1374 D HeadsetProfile: Bluetooth service disconnected
08-22 18:30:40.407   372   872 D CommandListener: Setting iface cfg
08-22 18:30:40.408  2578  2578 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-22 18:30:40.408  2578  2597 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-22 18:30:40.408  2578  2578 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-22 18:30:40.408  2578  2692 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 18:30:40.408  2578  2692 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 18:30:40.408  2578  2692 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 18:30:40.409  2578  2597 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-22 18:30:40.409  2578  2578 D HidService: Received stop request...Stopping profile...
08-22 18:30:40.409  2578  2578 D HidService: Stopping Bluetooth HidService
08-22 18:30:40.410  1374  1374 D BluetoothInputDevice: Proxy object disconnected
08-22 18:30:40.410  1374  1374 D HidProfile: Bluetooth service disconnected
08-22 18:30:40.410  1529  2397 V NativeCrypto: Read error: ssl=0x9b418c00: I/O error during system call, Connection timed out
08-22 18:30:40.412   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-22 18:30:40.412   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-22 18:30:40.412   874  1316 D WifiStateMachine: Start Disconnecting Watchdog 1
08-22 18:30:40.415   395   395 E Parcel  : Reading a NULL string not supported here.
08-22 18:30:40.417   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-22 18:30:40.417  1529  2397 V NativeCrypto: SSL shutdown failed: ssl=0x9b418c00: I/O error during system call, Broken pipe
08-22 18:30:40.418   372   872 D CommandListener: Clearing all IP addresses on wlan0
08-22 18:30:40.423   874  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-22 18:30:40.422  2578  2578 D HealthService: Received stop request...Stopping profile...
08-22 18:30:40.428   874  1879 D DhcpClient: Receive thread stopped
08-22 18:30:40.428  2578  2578 D PanService: Received stop request...Stopping profile...
08-22 18:30:40.430  2578  2578 D BluetoothMapService: Received stop request...Stopping profile...
08-22 18:30:40.430  2578  2578 D BluetoothMapService: stop()
08-22 18:30:40.430   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
08-22 18:30:40.431  2578  2578 D BluetoothMapAppObserver: deinitObservers()
08-22 18:30:40.431  2578  2578 D BluetoothMapAppObserver: removeReceiver()
08-22 18:30:40.433  3902  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:40.434  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:40.434  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:40.434  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:40.434  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:30:40.434  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:40.434  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:40.434  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:40.434  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:30:40.434  3902  3902 W org.thalipr,oject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:40.434  3902  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:30:40.434  2578  2578 V BluetoothAdapterState: isTurningOff()=true
08-22 18:30:40.434  2578  2578 V BluetoothAdapterState: isTurningOn()=false
08-22 18:30:40.434  2578  2578 V BluetoothAdapterState: isBleTurningOn()=false
08-22 18:30:40.435  2578  2578 V BluetoothAdapterState: isBleTurningOff()=false
08-22 18:30:40.435   874  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-22 18:30:40.435  2578  2597 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-22 18:30:40.436  2578  2578 V BluetoothAdapterState: isTurningOff()=true
08-22 18:30:40.436  2578  2578 V BluetoothAdapterState: isTurningOn()=false
08-22 18:30:40.436  2578  2578 V BluetoothAdapterState: isBleTurningOn()=false
08-22 18:30:40.436  2578  2578 V BluetoothAdapterState: isBleTurningOff()=false
08-22 18:30:40.436  3902  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:40.436  2578  2578 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-22 18:30:40.436  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:40.436  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:40.436  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:40.436  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:30:40.436  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:40.436  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:40.436  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:40.436  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:30:40.436  2578  2597 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-22 18:30:40.436  2578  2578 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-22 18:30:40.437  2578  2578 V BluetoothAdapterState: isTurningOff()=true
08-22 18:30:40.437  2578  2578 V BluetoothAdapterState: isTurningOn()=false
08-22 18:30:40.437  2578  2578 V BluetoothAdapterState: isBleTurningOn()=false
08-22 18:30:40.437  2578  2578 V BluetoothAdapterState: isBleTurningOff()=false
08-22 18:30:40.437  3902  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:40.437  3902  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:30:40.437  2578  2578 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-22 18:30:40.437  2578  2597 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-22 18:30:40.437  2578  2578 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-22 18:30:40.437  2578  2692 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 18:30:40.438  2578  2692 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 18:30:40.438  2578  2692 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 18:30:40.438  2578  2692 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 18:30:40.438  2578  2692 W bt_l2cap: L2CAP - PSM,: 0x0019 not found for deregistration
08-22 18:30:40.438  2578  2692 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 18:30:40.440  2578  2578 V BluetoothAdapterState: isTurningOff()=true
08-22 18:30:40.440  2578  2578 V BluetoothAdapterState: isTurningOn()=false
08-22 18:30:40.440  2157  2291 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:30:40.440  2578  2578 V BluetoothAdapterState: isBleTurningOn()=false
08-22 18:30:40.440  2578  2578 V BluetoothAdapterState: isBleTurningOff()=false
08-22 18:30:40.444  2578  2578 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-22 18:30:40.444  2578  2578 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-22 18:30:40.446  2578  2578 D BluetoothMapService: MAP Service closeService in
08-22 18:30:40.447  2578  2578 V BluetoothAdapterState: isTurningOff()=true
08-22 18:30:40.447  2578  2578 V BluetoothAdapterState: isTurningOn()=false
08-22 18:30:40.447  2578  2578 V BluetoothAdapterState: isBleTurningOn()=false
08-22 18:30:40.447  2578  2578 V BluetoothAdapterState: isBleTurningOff()=false
08-22 18:30:40.447  2578  2592 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-22 18:30:40.447  2578  2578 D BluetoothMapService: cleanup()
08-22 18:30:40.447  2578  2592 D BluetoothAdapterProperties: Setting state to 15
08-22 18:30:40.447  2578  2578 D BluetoothMapService: MAP Service closeService in
08-22 18:30:40.447  2578  2592 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-22 18:30:40.447  2578  2592 I BluetoothAdapterState: Entering BleOnState
08-22 18:30:40.448   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 18:30:40.448   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 18:30:40.448  1374  1392 D BluetoothA2dp: onBluetoothStateChange: up=false
08-22 18:30:40.449  1374  2029 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-22 18:30:40.450  1374  1393 D BluetoothPan: onBluetoothStateChange on: false
08-22 18:30:40.450   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 18:30:40.450   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-22 18:30:40.451  1374  1392 D BluetoothMap: onBluetoothStateChange: up=false
08-22 18:30:40.451  1921  2074 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 18:30:40.452  1374  2029 D BluetoothPbap: onBluetoothStateChange: up=false
08-22 18:30:40.453  1374  1393 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 18:30:40.447  1374  1374 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-22 18:30:40.455  1374  1374 D PanProfile: Bluetooth service disconnected
08-22 18:30:40.456  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:40.457  2578  2592 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-22 18:30:40.458  2578  2592 D BluetoothAdapterProperties: Setting state to 16
08-22 18:30:40.458  2578  2592 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-22 18:30:40.458  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:40.458  2578  2592 D BluetoothAdapterProperties: onBleDisable
08-22 18:30:40.458  2578  2592 I BluetoothAdapterState: Entering PendingCommandState
08-22 18:30:40.458  2578  2593 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-22 18:30:40.459  2578  2597 D BluetoothAdapterProperties: Scan Mode:20
08-22 18:30:40.460  2578  2692 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-22 18:30:40.460  2578  2692 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 18:30:40.461  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:40.464  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:40.465   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-22 18:30:40.481   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-22 18:30:40.482   874  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-22 18:30:40.482   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-22 18:30:40.484   874   891 D Tethering: MasterInitialState.processMessage what=3
08-22 18:30:40.489  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:40.490  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:40.491  3524  3524 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@ddaf4fc and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-22 18:30:40.492  1993  1993 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-22 18:30:40.504  3967  3967 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-22 18:30:40.514  3967  3967 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 18:30:40.519  1529  1529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-22 18:30:40.529   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@82a6e5d:true
08-22 18:30:40.532   874  1971 I ActivityManager: Start proc 3987:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-22 18:30:40.533   372   872 E Netd    : netlink response contains error (No such file or directory)
08-22 18:30:40.540  3967  3967 D LocalBluetoothProfileManager: Adding local MAP profile
08-22 18:30:40.543  3967  3967 D BluetoothMap: Create BluetoothMap proxy object
08-22 18:30:40.547  3967  3967 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-22 18:30:40.558  3967  3967 D DockEventReceiver: finishStartingService: stopping service
,08-22 18:30:40.563  3987  3987 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-22 18:30:40.566   874  1972 I ActivityManager: Killing 3524:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-22 18:30:40.662  2578  2597 I bt_hci  : shut_down
,08-22 18:30:40.680  2578  2602 I bt_vendor: low_power_mode_cb
,08-22 18:30:40.686  2578  2602 D bt_hwcfg: hw_epilog_process
,08-22 18:30:40.702  2578  2602 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-22 18:30:40.702  2578  2602 I bt_vendor: epilog_cb
,08-22 18:30:40.702  2578  2602 I bt_hci  : epilog_finished_callback
,08-22 18:30:40.709  2578  2597 I bt_hci_h4: hal_close
,08-22 18:30:40.710  2578  2597 I bt_userial_vendor: device fd = 51 close
,08-22 18:30:40.737  3987  3987 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 18:30:40.737  3987  3987 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at java.io.File.exists(File.java:361)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 18:30:40.737  3987  3987 D StrictMode: ,	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 18:30:40.737  3987  3987 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 18:30:40.738  3987  3987 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 18:30:40.738  3987  3987 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.os.StrictMode$,AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 18:30:40.738  3987  3987 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63),
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.r.k.a(PG:2107)
,08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.r.y.a(PG:2188)
,08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.r.e.b(PG:170)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251),
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48),
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 18:30:40.738  3987  3987 D StrictMode: 	,at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206),
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013),
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 18:30:40.738  3987  3987 D StrictMode: 	,at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 18:30:40.738  3987  3987 D StrictMode: ,	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
,08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 18:30:40.738  3987  3987 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.r.k.d(PG:583)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.r.e.b(PG:170)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 18:30:40.738  3987  3987 D StrictMode: StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 18:30:40.,738  3987  3987 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at java.io.File.exists(File.java:361)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 18:30:40.738  3987  3987 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at java.io.File.exists(File.java:361)
08-22 18:30:40.738  3987  3987 D StrictMode: ,	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
,08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:40.738  3987  3987 D StrictMode: 	,at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013),
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java),
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102),
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread.main(Ac,tivityThread.java:5417)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:40.738  3987  3987 D StrictMode: 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-22 18:30:40.738  3987  3987 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
,08-22 18:30:40.738  3987  3987 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at java.io.File.lastModified(File.java:569),
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
,08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
,08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 18:30:40.738  3987  3987 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-22 18:30:40.784   874   884 I ActivityManager: Start proc 4016:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-22 18:30:40.785   874   884 I ActivityManager: Killing 3571:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-22 18:30:40.841  3902  3902 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-22 18:30:40.844  2578  2593 D bt_stack_manager: event_shut_down_stack finished.
,08-22 18:30:40.845  2578  2592 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-22 18:30:40.846  2578  2592 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-22 18:30:40.847  2578  2578 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-22 18:30:40.848  2578  2578 D BtGatt.GattService: Received stop request...Stopping profile...
08-22 18:30:40.848  2578  2578 D BtGatt.GattService: stop()
08-22 18:30:40.848  2578  2578 D BtGatt.AdvertiseManager: advertise clients cleared
,08-22 18:30:40.851  2578  2578 V BluetoothAdapterState: isTurningOff()=false
08-22 18:30:40.851  2578  2578 V BluetoothAdapterState: isTurningOn()=false
08-22 18:30:40.851  2578  2578 V BluetoothAdapterState: isBleTurningOn()=false
08-22 18:30:40.851  2578  2578 V BluetoothAdapterState: isBleTurningOff()=true
08-22 18:30:40.851  2578  2592 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-22 18:30:40.851  2578  2592 D BluetoothAdapterProperties: Setting state to 10
08-22 18:30:40.851  2578  2592 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-22 18:30:40.852  2578  2592 I BluetoothAdapterState: Entering OffState
08-22 18:30:40.852   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-22 18:30:40.856  4016  4016 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-22 18:30:40.861  2578  2578 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-22 18:30:40.861  2578  2578 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-22 18:30:40.861  2578  2578 I BluetoothServiceJni: cleanupNative: return from cleanup
08-22 18:30:40.862  2578  2593 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-22 18:30:40.863  2578  2593 D bt_stack_manager: event_clean_up_stack finished.
,08-22 18:30:40.866  2578  2578 I art     : System.exit called, status: 0
,08-22 18:30:40.866  2578  2578 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-22 18:30:40.904   874  1972 I ActivityManager: Process com.android.bluetooth (pid 2578) has died
,08-22 18:30:40.988  4016  4016 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-22 18:30:41.014  3967  3967 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 18:30:41.051  3987  4006 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-22 18:30:41.057   874   884 I ActivityManager: Start proc 4045:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-22 18:30:41.071  3967  3967 D DockEventReceiver: finishStartingService: stopping service
,08-22 18:30:41.077   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5e25f3d:true
,08-22 18:30:41.148  4045  4045 D AdapterServiceConfig: Adding HeadsetService
,08-22 18:30:41.148  4045  4045 D AdapterServiceConfig: Adding A2dpService
,08-22 18:30:41.149  4045  4045 D AdapterServiceConfig: Adding HidService
,08-22 18:30:41.149  4045  4045 D AdapterServiceConfig: Adding HealthService
,08-22 18:30:41.150  4045  4045 D AdapterServiceConfig: Adding PanService
,08-22 18:30:41.151  4045  4045 D AdapterServiceConfig: Adding GattService
,08-22 18:30:41.151  4045  4045 D AdapterServiceConfig: Adding BluetoothMapService
,08-22 18:30:41.154   874  1926 I ActivityManager: Killing 3152:android.process.acore/u0a5 (adj 15): empty #17
,08-22 18:30:41.185  1529  1529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 18:30:41.221  1749  1749 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-22 18:30:41.224  1749  2428 I iu.UploadsManager: num queued entries: 0
,08-22 18:30:41.224  1749  2428 I iu.UploadsManager: num updated entries: 0
08-22 18:30:41.225  1749  2428 I iu.SyncManager: NEXT; no task
,08-22 18:30:41.232  1749  1749 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-22 18:30:41.236  1749  1749 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-22 18:30:41.262   874  1404 I ActivityManager: Start proc 4058:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-22 18:30:41.325  4058  4058 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-22 18:30:41.330  4058  4058 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-22 18:30:41.342  4058  4058 D SprintDMHelper: simOperator: 
08-22 18:30:41.342  4058  4058 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-22 18:30:41.388   874  1929 I ActivityManager: Start proc 4070:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-22 18:30:41.390   874  1929 I ActivityManager: Killing 3739:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-22 18:30:41.530  2462  4084 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-22 18:30:41.563   874  1399 I ActivityManager: Start proc 4085:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-22 18:30:41.571   874  1926 I ActivityManager: Killing 3754:com.android.musicfx/u0a18 (adj 15): empty #17
,08-22 18:30:41.623  4085  4085 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-22 18:30:41.677  4085  4085 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-22 18:30:41.677  4085  4085 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-22 18:30:41.677  4085  4085 I GAv4    :   adb logcat -s GAv4
,08-22 18:30:41.694  4085  4085 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-22 18:30:41.700  4085  4085 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-22 18:30:41.732  4085  4102 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-22 18:30:41.834  4085  4085 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-22 18:30:41.870  4085  4085 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-22 18:30:41.879  4085  4085 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5468-5471)
08-22 18:30:41.879  4085  4085 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-22 18:30:41.896  4085  4085 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {43952c}
,08-22 18:30:41.896  4085  4085 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-22 18:30:41.898  4085  4085 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-22 18:30:41.906  4085  4085 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-22 18:30:41.908  4085  4085 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-22 18:30:41.923  4085  4085 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-22 18:30:41.936  4085  4085 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-22 18:30:41.936  4085  4085 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-22 18:30:41.936  4085  4085 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-22 18:30:41.936  4085  4085 I Adreno  : Build Date                       : 10/20/15
08-22 18:30:41.936  4085  4085 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-22 18:30:41.936  4085  4085 I Adreno  : Local Branch                     : M14
08-22 18:30:41.936  4085  4085 I Adreno  : Remote Branch                    : 
08-22 18:30:41.936  4085  4085 I Adreno  : Remote Branch                    : 
08-22 18:30:41.936  4085  4085 I Adreno  : Reconstruct Branch               : 
,08-22 18:30:42.001  4085  4085 I NSApplication: Starting up...
,08-22 18:30:42.016  4085  4131 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-22 18:30:42.043   874   885 I ActivityManager: Start proc 4136:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-22 18:30:42.044   874   885 I ActivityManager: Killing 2232:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-22 18:30:42.144  4136  4136 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-22 18:30:42.353   874  1972 I ActivityManager: Killing 3777:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-22 18:30:43.387   874  1404 D WifiService: setWifiEnabled: true pid=3902, uid=10000
,08-22 18:30:43.387   874  1404 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-22 18:30:43.404   874  1316 D WifiConfigStore: Loading config and enabling all networks 
,08-22 18:30:43.414  3902  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 18:30:43.415  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:43.415  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:43.415  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:43.415  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:30:43.415  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:43.415  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:43.415  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:43.415  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:30:43.415  3902  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:43.415  3902  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:30:43.417  3902  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 18:30:43.418  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:43.418  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:43.418  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:43.418  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:30:43.418  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:43.418  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:43.418  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:43.418  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:30:43.418  3902  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 18:30:43.418  3902  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:30:43.446   874  1316 D WifiConfigStore: loaded 0 passpoint configs
,08-22 18:30:43.447   874  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-22 18:30:43.448   874  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-22 18:30:43.448   874  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-22 18:30:43.449   874  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-22 18:30:43.449   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-22 18:30:43.449   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-22 18:30:43.467   874  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=10.50 rxSuccessRate=15.50 delta 1000 -> 994
,08-22 18:30:43.467   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-22 18:30:43.470   372   872 D CommandListener: Setting iface cfg
,08-22 18:30:43.472   874  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
,08-22 18:30:43.472   874  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-22 18:30:43.476   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-22 18:30:43.476   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 18:30:43.488   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-22 18:30:43.549   874  1315 D WifiNative-HAL: p2pGetDeviceAddress
,08-22 18:30:43.556   874  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-22 18:30:43.565   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-22 18:30:43.569  1476  1476 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-22 18:30:43.988  1476  1476 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-22 18:30:44.028  1476  1476 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-22 18:30:44.029  1476  1476 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-22 18:30:44.038   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 18:30:44.054   874  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-22 18:30:44.055   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-22 18:30:44.055   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 18:30:44.081   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 18:30:44.100   372   872 D CommandListener: Setting iface cfg
,08-22 18:30:44.101   874  1316 D WifiStateMachine: Start Dhcp Watchdog 2
,08-22 18:30:44.118   874  1318 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-22 18:30:44.121   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-22 18:30:44.144   874  4160 D DhcpClient: Receive thread started
,08-22 18:30:44.225   874  1316 E native  : do suspend false
,08-22 18:30:44.245   874  1878 D DhcpClient: Broadcasting DHCPDISCOVER
,08-22 18:30:44.258   874  4160 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172695, domain null
,08-22 18:30:44.259   874  1878 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172695 seconds
,08-22 18:30:44.262   874  1878 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-22 18:30:44.276   874  4160 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-22 18:30:44.278   874  1878 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-22 18:30:44.282   372   872 D CommandListener: Setting iface cfg
,08-22 18:30:44.292   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-22 18:30:44.295   874  1878 D DhcpClient: Scheduling renewal in 86399s
,08-22 18:30:44.311   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-22 18:30:44.314   874  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,08-22 18:30:44.315   874  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-22 18:30:44.316   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-22 18:30:44.320   874  1318 D ConnectivityService: Adding iface wlan0 to network 101
,08-22 18:30:44.323   874  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-22 18:30:44.401   874  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-22 18:30:44.401   874  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-22 18:30:44.402   874  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-22 18:30:44.403   874  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-22 18:30:44.405   874  1318 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-22 18:30:44.417   874  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-22 18:30:44.421   874  1318 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-22 18:30:44.422   874  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-22 18:30:44.422   874  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101],
08-22 18:30:44.422   874  1318 D ConnectivityService:    accepting network in place of null
,08-22 18:30:44.422   874  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-22 18:30:44.423   874  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-22 18:30:44.424   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-22 18:30:44.436   874  4159 D NetlinkSocketObserver: NeighborEvent{elapsedMs=128028, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-22 18:30:44.471   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 18:30:44.509   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 18:30:44.512   874  4158 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:401b:801::200e
,08-22 18:30:44.517   874  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-22 18:30:44.518   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-22 18:30:44.528   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-22 18:30:44.529   874  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-22 18:30:44.541  3902  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 18:30:44.541  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:44.541  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:44.541  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:44.541  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:30:44.541  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:44.541  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:44.541  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:30:44.541  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 18:30:44.541  3902  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:44.541  3902  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:44.545  3902  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:44.545  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:44.545  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:44.545  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:44.545  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:30:44.545  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:44.545  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:44.545  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:30:44.545  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 18:30:44.545  3902  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:44.545  3902  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:44.550  1993  1993 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-22 18:30:44.572  1749  1749 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-22 18:30:44.575  1749  2428 I iu.UploadsManager: num queued entries: 0
,08-22 18:30:44.575   874  4158 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 22 Aug 2016 16:30:44 GMT], X-Android-Received-Millis=[1471883444574], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471883444553]}
08-22 18:30:44.575  1749  2428 I iu.UploadsManager: num updated entries: 0
,08-22 18:30:44.576  1749  2428 I iu.SyncManager: NEXT; no task
,08-22 18:30:44.579   874  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-22 18:30:44.579   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-22 18:30:44.579   874  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-22 18:30:44.581   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-22 18:30:44.583  1749  1749 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-22 18:30:44.584  1749  1749 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-22 18:30:44.588  4058  4058 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-22 18:30:44.591  1749  4172 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-22 18:30:44.591  1749  4172 W BaseAppContext: Using Auth Proxy for data requests.
,08-22 18:30:44.593  1749  4172 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,08-22 18:30:44.598  4058  4058 D SprintDMHelper: simOperator: 
,08-22 18:30:44.599  4058  4058 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-22 18:30:44.599  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 18:30:44.601  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 18:30:44.649  1529  3057 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-22 18:30:44.649  1529  3057 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-22 18:30:44.651  1529  3057 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-22 18:30:44.651  1529  3057 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 18:30:44.675  1749  4172 E MDM     : [177] SitrepService.a: Error sending sitrep.
,08-22 18:30:44.717  2462  4175 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-22 18:30:45.516   874  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-22 18:30:46.150   874  1926 I ActivityManager: Killing 3695:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-22 18:30:46.395   874  2754 D WifiService: setWifiEnabled: false pid=3902, uid=10000
,08-22 18:30:46.395   874  2754 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-22 18:30:46.423  1476  1476 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-22 18:30:46.430   874  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-22 18:30:46.431   874  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-22 18:30:46.432   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-22 18:30:46.432   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 18:30:46.448   874  1878 D DhcpClient: Clearing IP address
,08-22 18:30:46.448   372   872 D CommandListener: Clearing all IP addresses on wlan0
,08-22 18:30:46.452   372   872 D CommandListener: Setting iface cfg
,08-22 18:30:46.456  1529  4179 V NativeCrypto: Read error: ssl=0x9b11ce00: I/O error during system call, Connection timed out
,08-22 18:30:46.459  1529  4179 V NativeCrypto: SSL shutdown failed: ssl=0x9b11ce00: I/O error during system call, Broken pipe
,08-22 18:30:46.463   874  1399 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-22 18:30:46.464   874  4158 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-22 18:30:46.464   874  4158 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:401b:801::200e
,08-22 18:30:46.470   874  4160 D DhcpClient: Receive thread stopped
08-22 18:30:46.471   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-22 18:30:46.472   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-22 18:30:46.472   874  1316 D WifiStateMachine: Start Disconnecting Watchdog 2
08-22 18:30:46.479   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-22 18:30:46.483   874  4158 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:401b:801::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
08-22 18:30:46.483   372   872 D CommandListener: Clearing all IP addresses on wlan0
08-22 18:30:46.484   395   395 E Parcel  : Reading a NULL string not supported here.
,08-22 18:30:46.488   874  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-22 18:30:46.498   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
08-22 18:30:46.500  3902  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:46.500  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:46.500  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:46.500  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:46.500  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:30:46.500  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:46.500  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:46.500  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:46.500  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:30:46.500  3902  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:46.501  3902  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:30:46.501  2157  2291 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:30:46.501  3902  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:46.501  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:46.501  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:46.501  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:46.501  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:30:46.501  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:46.501  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:46.501  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:46.501  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:30:46.502  3902  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:46.502  3902  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:30:46.504   874  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-22 18:30:46.526   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 18:30:46.554   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 18:30:46.555   874  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-22 18:30:46.555   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-22 18:30:46.558   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-22 18:30:46.560  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:46.561  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:46.561  1993  1993 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-22 18:30:46.576  1749  1749 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-22 18:30:46.580  1749  2428 I iu.UploadsManager: num queued entries: 0
,08-22 18:30:46.581  1749  2428 I iu.UploadsManager: num updated entries: 0
,08-22 18:30:46.583  1749  1749 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-22 18:30:46.584  1749  1749 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-22 18:30:46.586  4058  4058 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-22 18:30:46.591  4058  4058 D SprintDMHelper: simOperator: 
,08-22 18:30:46.591  4058  4058 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-22 18:30:46.618  1749  2428 I iu.SyncManager: NEXT; no task
,08-22 18:30:46.621  2462  4193 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-22 18:30:46.636   372   872 E Netd    : netlink response contains error (No such file or directory)
,08-22 18:30:46.638   874  1318 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-22 18:30:46.638   874  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-22 18:30:49.453   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5798ff0:true
,08-22 18:30:49.456  4045  4045 D BluetoothAdapterState: make() - Creating AdapterState
,08-22 18:30:49.465  4045  4196 I BluetoothAdapterState: Entering OffState
08-22 18:30:49.464  4045  4045 I bt_bluedroid: init
,08-22 18:30:49.469  4045  4197 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-22 18:30:49.469  4045  4197 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-22 18:30:49.469  4045  4197 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-22 18:30:49.469  4045  4197 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-22 18:30:49.471  4045  4045 I bt_bluedroid: get_profile_interface socket
,08-22 18:30:49.477  4045  4200 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-22 18:30:49.478  4045  4045 I bt_bluedroid: get_profile_interface sdp
,08-22 18:30:49.481  4045  4200 D BluetoothAdapterProperties: Name is: Nexus 6
,08-22 18:30:49.488  4045  4055 I bt_bluedroid: config_hci_snoop_log
,08-22 18:30:49.490   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-22 18:30:49.497  4045  4196 D BluetoothAdapterState: Current state: OFF, message: 0
,08-22 18:30:49.497  4045  4196 D BluetoothAdapterProperties: Setting state to 14
,08-22 18:30:49.497  4045  4196 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-22 18:30:49.499  4045  4196 D BluetoothBondStateMachine: make
,08-22 18:30:49.503  4045  4201 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-22 18:30:49.506  4045  4196 I BluetoothAdapterState: Entering PendingCommandState
,08-22 18:30:49.508  4045  4045 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-22 18:30:49.511  4045  4045 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a394dc2
,08-22 18:30:49.513  4045  4045 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-22 18:30:49.513  4045  4045 D BtGatt.GattService: Received start request. Starting profile...
,08-22 18:30:49.514  4045  4045 D BtGatt.GattService: start()
08-22 18:30:49.514  4045  4045 I bt_bluedroid: get_profile_interface gatt
,08-22 18:30:49.516  4045  4045 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a394dc2
,08-22 18:30:49.516  4045  4045 D BtGatt.AdvertiseManager: advertise manager created
,08-22 18:30:49.523  4045  4045 V BluetoothAdapterState: isTurningOff()=false
08-22 18:30:49.523  4045  4045 V BluetoothAdapterState: isTurningOn()=false
08-22 18:30:49.523  4045  4045 V BluetoothAdapterState: isBleTurningOn()=true
08-22 18:30:49.523  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
08-22 18:30:49.524  4045  4196 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-22 18:30:49.524  4045  4196 I bt_bluedroid: enable
08-22 18:30:49.524  4045  4197 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-22 18:30:49.525  4045  4197 I bt_hci  : start_up
,08-22 18:30:49.541  4045  4197 I bt_vendor: alloc value 0xb39b9189
,08-22 18:30:49.543  4045  4197 I bt_vendor: init
08-22 18:30:49.543  4045  4197 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-22 18:30:49.543  4045  4197 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-22 18:30:49.656  4045  4197 D bt_hci  : start_up starting async portion
,08-22 18:30:49.656  4045  4204 I bt_hci  : event_finish_startup
,08-22 18:30:49.657  4045  4204 I bt_hci_h4: hal_open
08-22 18:30:49.657  4045  4204 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-22 18:30:49.668  4045  4204 I bt_userial_vendor: device fd = 51 open
,08-22 18:30:49.696  4045  4204 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-22 18:30:49.727  4045  4204 D bt_hwcfg: Chipset BCM4354A2
,08-22 18:30:49.727  4045  4204 D bt_hwcfg: Target name = [BCM4354A2]
,08-22 18:30:49.728  4045  4204 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-22 18:30:50.397  4045  4204 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-22 18:30:50.398  4045  4204 D bt_hwcfg: Settlement delay -- 100 ms
,08-22 18:30:50.398  4045  4204 I bt_hwcfg: Setting fw settlement delay to 100 
,08-22 18:30:50.515  4045  4204 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-22 18:30:50.516  4045  4204 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-22 18:30:50.545  4045  4204 I bt_hwcfg: vendor lib fwcfg completed
,08-22 18:30:50.545  4045  4204 I bt_vendor: firmware callback
,08-22 18:30:50.546  4045  4204 I bt_hci  : firmware_config_callback
,08-22 18:30:50.558  4045  4206 I bt_btu  : btu_task pending for preload complete event
,08-22 18:30:50.558  4045  4206 I bt_btu_task: Bluetooth chip preload is complete
,08-22 18:30:50.558  4045  4206 I bt_btu  : btu_task received preload complete event
,08-22 18:30:50.569  4045  4206 I         : BTE_InitTraceLevels -- TRC_HCI
,08-22 18:30:50.569  4045  4206 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-22 18:30:50.570  4045  4206 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-22 18:30:50.570  4045  4206 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-22 18:30:50.570  4045  4206 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-22 18:30:50.571  4045  4206 I         : BTE_InitTraceLevels -- TRC_A2D
08-22 18:30:50.571  4045  4206 I         : BTE_InitTraceLevels -- TRC_BNEP
08-22 18:30:50.571  4045  4206 I         : BTE_InitTraceLevels -- TRC_BTM
08-22 18:30:50.571  4045  4206 I         : BTE_InitTraceLevels -- TRC_GAP
08-22 18:30:50.572  4045  4206 I         : BTE_InitTraceLevels -- TRC_PAN
08-22 18:30:50.572  4045  4206 I         : BTE_InitTraceLevels -- TRC_SDP
08-22 18:30:50.572  4045  4206 I         : BTE_InitTraceLevels -- TRC_GATT
08-22 18:30:50.573  4045  4206 I         : BTE_InitTraceLevels -- TRC_SMP
08-22 18:30:50.573  4045  4206 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-22 18:30:50.573  4045  4206 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-22 18:30:50.707  4045  4206 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3936d9d
08-22 18:30:50.707  4045  4206 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3936d9d 
,08-22 18:30:50.719  4045  4200 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-22 18:30:50.720  4045  4200 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-22 18:30:50.721  4045  4200 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-22 18:30:50.725  4045  4200 D BluetoothAdapterProperties: Name is: Nexus 6
,08-22 18:30:50.728  4045  4200 D BluetoothAdapterProperties: Scan Mode:20
,08-22 18:30:50.729  4045  4200 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-22 18:30:50.729  4045  4200 D bt_hci  : do_postload posting postload work item
,08-22 18:30:50.729  4045  4204 I bt_hci  : event_postload
,08-22 18:30:50.730  4045  4204 I bt_vendor: sco_config_cb
,08-22 18:30:50.730  4045  4204 I bt_hci  : sco_config_callback postload finished.
,08-22 18:30:50.734  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:50.735  4045  4200 D bt_bte_conf: Device ID record 1 : primary
,08-22 18:30:50.735  4045  4200 D bt_bte_conf:   vendorId            = 000f
08-22 18:30:50.735  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:50.735  4045  4200 D bt_bte_conf:   vendorIdSource      = 0001
,08-22 18:30:50.736  4045  4200 D bt_bte_conf:   product             = 1200
08-22 18:30:50.736  4045  4200 D bt_bte_conf:   version             = 1436
,08-22 18:30:50.736  4045  4200 D bt_bte_conf:   clientExecutableURL = 
08-22 18:30:50.736  4045  4200 D bt_bte_conf:   serviceDescription  = 
,08-22 18:30:50.737  4045  4200 D bt_bte_conf:   documentationURL    = 
08-22 18:30:50.737  4045  4200 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-22 18:30:50.738  4045  4197 D bt_stack_manager: event_start_up_stack finished,
08-22 18:30:50.738  4045  4196 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-22 18:30:50.738  4045  4196 D BluetoothAdapterProperties: Setting state to 15
08-22 18:30:50.738  4045  4196 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-22 18:30:50.739  4045  4196 I BluetoothAdapterState: Entering BleOnState
08-22 18:30:50.742  4045  4204 I bt_vendor: low_power_mode_cb
08-22 18:30:50.745  4045  4196 D BluetoothAdapterState: Current state: BLE ON, message: 1,
08-22 18:30:50.745  4045  4196 D BluetoothAdapterProperties: Setting state to 11
08-22 18:30:50.746  4045  4196 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-22 18:30:50.753  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:50.754  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:50.757  4045  4045 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a394dc2
08-22 18:30:50.758  4045  4045 D HeadsetService: Received start request. Starting profile...
,08-22 18:30:50.762  4045  4045 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-22 18:30:50.762  4045  4045 D HeadsetStateMachine: make
08-22 18:30:50.769  4045  4196 I BluetoothAdapterState: Entering PendingCommandState
,08-22 18:30:50.772  4045  4045 D HeadsetStateMachine: max_hf_connections = 1
,08-22 18:30:50.773  4045  4045 I bt_bluedroid: get_profile_interface handsfree
08-22 18:30:50.773  4045  4200 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-22 18:30:50.773  4045  4200 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-22 18:30:50.780  4045  4045 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a394dc2
,08-22 18:30:50.780  4045  4045 D A2dpService: Received start request. Starting profile...
,08-22 18:30:50.781  4045  4045 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-22 18:30:50.781  1529  1529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 18:30:50.781  4045  4045 I bt_bluedroid: get_profile_interface avrcp
,08-22 18:30:50.787  4045  4045 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-22 18:30:50.788  4045  4045 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-22 18:30:50.788  4045  4045 D A2dpStateMachine: make
08-22 18:30:50.789  4045  4045 I bt_bluedroid: get_profile_interface a2dp
,08-22 18:30:50.790  4045  4200 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-22 18:30:50.792  4045  4214 D A2dpStateMachine: Enter Disconnected: -2
,08-22 18:30:50.793  4045  4045 I BluetoothHidServiceJni: classInitNative: succeeds
,08-22 18:30:50.795  4045  4045 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a394dc2
,08-22 18:30:50.796  3967  3967 D BluetoothInputDevice: Proxy object connected
,08-22 18:30:50.796  4045  4045 D HidService: Received start request. Starting profile...
08-22 18:30:50.796  4045  4045 I bt_bluedroid: get_profile_interface hidhost
,08-22 18:30:50.796  3967  3967 D HidProfile: Bluetooth service connected
08-22 18:30:50.797  4045  4200 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39183e5
08-22 18:30:50.797  4045  4200 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-22 18:30:50.797  4045  4045 D HidService: setHidService(): set to: null
,08-22 18:30:50.798  4045  4045 I BluetoothHealthServiceJni: classInitNative: succeeds
08-22 18:30:50.799  4045  4045 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a394dc2
08-22 18:30:50.800  4045  4045 D HealthService: Received start request. Starting profile...
,08-22 18:30:50.801  4045  4045 I bt_bluedroid: get_profile_interface health
,08-22 18:30:50.802  4045  4045 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-22 18:30:50.804  4045  4045 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a394dc2
,08-22 18:30:50.805  3967  3967 D BluetoothPan: BluetoothPAN Proxy object connected
,08-22 18:30:50.805  4045  4045 D PanService: Received start request. Starting profile...
08-22 18:30:50.806  4045  4045 D BluetoothPanServiceJni: initializeNative(L110): pan
08-22 18:30:50.806  4045  4045 I bt_bluedroid: get_profile_interface pan
08-22 18:30:50.806  3967  3967 D PanProfile: Bluetooth service connected
,08-22 18:30:50.807  4045  4200 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-22 18:30:50.811  4045  4045 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a394dc2
,08-22 18:30:50.813  3967  3967 D BluetoothMap: Proxy object connected
,08-22 18:30:50.813  4045  4045 D BluetoothMapService: Received start request. Starting profile...
08-22 18:30:50.813  4045  4045 D BluetoothMapService: start()
08-22 18:30:50.813  3967  3967 D MapProfile: Bluetooth service connected
,08-22 18:30:50.814  3967  3967 D BluetoothMap: getConnectedDevices()
,08-22 18:30:50.815  3967  3967 D BluetoothMap: Bluetooth is Not enabled
,08-22 18:30:50.817  4045  4045 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-22 18:30:50.819  4045  4045 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-22 18:30:50.819  4045  4045 D BluetoothMapAppObserver: createReceiver()
,08-22 18:30:50.820  4045  4045 D BluetoothMapAppObserver: initObservers()
,08-22 18:30:50.821  4045  4045 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-22 18:30:50.831  4045  4045 V BluetoothAdapterState: isTurningOff()=false
,08-22 18:30:50.831  4045  4045 V BluetoothAdapterState: isTurningOn()=true
08-22 18:30:50.831  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
08-22 18:30:50.831  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 18:30:50.833  4045  4212 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-22 18:30:50.835  4045  4045 V BluetoothAdapterState: isTurningOff()=false
,08-22 18:30:50.835  4045  4045 V BluetoothAdapterState: isTurningOn()=true
08-22 18:30:50.835  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
08-22 18:30:50.835  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false,
08-22 18:30:50.836  4045  4045 V BluetoothAdapterState: isTurningOff()=false
08-22 18:30:50.836  4045  4045 V BluetoothAdapterState: isTurningOn()=true
08-22 18:30:50.836  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 18:30:50.836  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
08-22 18:30:50.836  4045  4045 V BluetoothAdapterState: isTurningOff()=false
08-22 18:30:50.836  4045  4045 V BluetoothAdapterState: isTurningOn()=true
,08-22 18:30:50.836  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
08-22 18:30:50.836  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 18:30:50.836  4045  4045 V BluetoothAdapterState: isTurningOff()=false
,08-22 18:30:50.836  4045  4045 V BluetoothAdapterState: isTurningOn()=true
,08-22 18:30:50.836  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 18:30:50.837  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 18:30:50.837  4045  4045 V BluetoothAdapterState: isTurningOff()=false
08-22 18:30:50.837  4045  4045 V BluetoothAdapterState: isTurningOn()=true
08-22 18:30:50.837  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 18:30:50.837  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
08-22 18:30:50.837  4045  4196 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-22 18:30:50.838  4045  4196 D BluetoothAdapterProperties: ScanMode =  20
,08-22 18:30:50.838  4045  4196 D BluetoothAdapterProperties: State =  11
,08-22 18:30:50.838  4045  4196 D BluetoothAdapterProperties: Setting state to 12
08-22 18:30:50.838  4045  4196 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-22 18:30:50.839  3967  3977 D BluetoothPbap: onBluetoothStateChange: up=true
,08-22 18:30:50.840  4045  4200 D BluetoothAdapterProperties: Scan Mode:21
,08-22 18:30:50.840  4045  4200 D BluetoothAdapterProperties: Discoverable Timeout:120
08-22 18:30:50.840  4045  4196 I BluetoothAdapterState: Entering OnState
08-22 18:30:50.841   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 18:30:50.841  3967  3979 D BluetoothMap: onBluetoothStateChange: up=true
08-22 18:30:50.841   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-22 18:30:50.841  1374  1392 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 18:30:50.844  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:50.844  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:50.844  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:50.844  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:30:50.844  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:30:50.844  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:50.844  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:50.844  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:30:50.845  1374  1393 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-22 18:30:50.845  1374  1374 D BluetoothA2dp: Proxy object connected
08-22 18:30:50.847  3902  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:30:50.848  1374  2029 D BluetoothPan: onBluetoothStateChange on: true
,08-22 18:30:50.849  1374  1374 D BluetoothInputDevice: Proxy object connected
,08-22 18:30:50.849  1374  1374 D HidProfile: Bluetooth service connected
08-22 18:30:50.850   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-22 18:30:50.850   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-22 18:30:50.851  4045  4045 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-22 18:30:50.851   874   874 D BluetoothA2dp: Proxy object connected
,08-22 18:30:50.852  3967  3977 D BluetoothPan: onBluetoothStateChange on: true
,08-22 18:30:50.852  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:50.852  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:50.852  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:50.852  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:30:50.852  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:30:50.852  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:50.852  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:50.852  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:30:50.852  1374  1393 D BluetoothMap: onBluetoothStateChange: up=true
,08-22 18:30:50.852  1374  1374 D BluetoothPan: BluetoothPAN Proxy object connected
08-22 18:30:50.852  4045  4045 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-22 18:30:50.852  1374  1374 D PanProfile: Bluetooth service connected
08-22 18:30:50.854  4045  4045 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 18:30:50.859  1374  1374 D BluetoothMap: Proxy object connected
08-22 18:30:50.859  1374  1374 D MapProfile: Bluetooth service connected
08-22 18:30:50.859  1374  1374 D BluetoothMap: getConnectedDevices()
08-22 18:30:50.859  3902  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:30:50.861  3967  3979 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-22 18:30:50.862  1921  1944 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 18:30:50.862  4045  4045 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 18:30:50.862  1374  2029 D BluetoothPbap: onBluetoothStateChange: up=true
08-22 18:30:50.864  4045  4045 D ObexServerSockets: Succeed to create listening sockets 
08-22 18:30:50.864  1374  1392 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 18:30:50.865  4045  4045 D ObexServerSockets0: startAccept()
,08-22 18:30:50.865  4045  4045 D ObexServerSockets0: prepareForNewConnect()
08-22 18:30:50.868   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
08-22 18:30:50.870  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:50.873  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:50.873  3967  3967 D LocalBluetoothProfileManager: Adding local A2DP profile
08-22 18:30:50.874  4045  4045 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-22 18:30:50.874  4045  4045 D BluetoothSdpJni: SDP Create record success - handle: 0
08-22 18:30:50.874  4045  4045 D BluetoothMapService: onReceive
,08-22 18:30:50.875  4045  4045 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:30:50.875  4045  4045 D BluetoothMapService: STATE_ON
08-22 18:30:50.876  4045  4223 D ObexServerSockets0: Accepting socket connection...
08-22 18:30:50.876  4045  4224 D ObexServerSockets0: Accepting socket connection...
08-22 18:30:50.878  3967  3967 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-22 18:30:50.888  3967  3967 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 18:30:50.892  3967  3967 D BluetoothA2dp: Proxy object connected
,08-22 18:30:50.896  1529  1529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 18:30:50.901  3967  3967 D DockEventReceiver: finishStartingService: stopping service
08-22 18:30:50.905  3967  3967 D BluetoothPbap: Proxy object connected
08-22 18:30:50.905  1374  1374 D BluetoothPbap: Proxy object connected
08-22 18:30:50.905  1374  1374 D PbapServerProfile: Bluetooth service connected
08-22 18:30:50.905  4045  4045 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-22 18:30:50.906  3967  3967 D PbapServerProfile: Bluetooth service connected
08-22 18:30:50.906  4045  4045 D ObexServerSockets0: prepareForNewConnect()
,08-22 18:30:50.915  4045  4228 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 18:30:50.930  4045  4232 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 18:30:50.932  4045  4232 I BtOppRfcommListener: Accept thread started.
,08-22 18:30:50.942   874   874 D BluetoothHeadset: Proxy object connected
08-22 18:30:50.942   874   874 D BluetoothHeadset: Proxy object connected
,08-22 18:30:50.943  1921  2074 D BluetoothHeadset: Proxy object connected
08-22 18:30:50.943   874   874 D BluetoothHeadset: Proxy object connected
,08-22 18:30:50.943  1374  2029 D BluetoothHeadset: Proxy object connected
08-22 18:30:50.943  1374  1374 D HeadsetProfile: Bluetooth service connected
,08-22 18:30:50.950   874   891 D BluetoothHeadset: Proxy object connected
,08-22 18:30:50.962  1921  1951 D BluetoothHeadset: Proxy object connected
,08-22 18:30:50.965  1374  1392 D BluetoothHeadset: Proxy object connected
,08-22 18:30:50.965  1374  1374 D HeadsetProfile: Bluetooth service connected
,08-22 18:30:50.984  3967  3979 D BluetoothHeadset: Proxy object connected
08-22 18:30:50.985  3967  3967 D HeadsetProfile: Bluetooth service connected
,08-22 18:30:52.410  4045  4196 D BluetoothAdapterState: Current state: ON, message: 23
,08-22 18:30:52.410  4045  4196 D BluetoothAdapterProperties: Setting state to 13
,08-22 18:30:52.411  4045  4196 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-22 18:30:52.412  4045  4196 D BluetoothAdapterProperties: onBluetoothDisable()
,08-22 18:30:52.421  4045  4196 I BluetoothAdapterState: Entering PendingCommandState
,08-22 18:30:52.425  4045  4045 D BluetoothMapService: onReceive
08-22 18:30:52.425  4045  4045 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-22 18:30:52.426  4045  4045 D BluetoothMapService: STATE_TURNING_OFF
08-22 18:30:52.427  4045  4045 D BluetoothMapService: MAP Service closeService in,
,08-22 18:30:52.427  4045  4045 D BluetoothMapMasInstance0: MAP Service shutdown
08-22 18:30:52.428   874  1318 D ConnectivityService: handlePromptUnvalidated 101
08-22 18:30:52.431  4045  4200 D BluetoothAdapterProperties: Scan Mode:20
,08-22 18:30:52.432  3902  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:52.432  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:52.432  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:52.432  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:52.432  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:30:52.432  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:52.432  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:52.432  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:52.432  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:30:52.427  4045  4045 D ObexServerSockets0: shutdown(block = true)
08-22 18:30:52.434  3902  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 18:30:52.435  4045  4196 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-22 18:30:52.435  3902  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:30:52.435  4045  4223 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-22 18:30:52.437  4045  4045 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-22 18:30:52.438  4045  4224 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-22 18:30:52.441  3902  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:52.441  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:52.441  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:52.441  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:52.441  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:30:52.441  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:52.441  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:52.441  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:52.441  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:30:52.441  3967  3967 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-22 18:30:52.442  3902  3902 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:52.442  3902  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:30:52.444  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:52.444  4045  4208 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-22 18:30:52.445  4045  4045 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-22 18:30:52.445  4045  4045 I BtOppRfcommListener: stopping Accept Thread
08-22 18:30:52.446  4045  4232 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-22 18:30:52.446  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:52.447  4045  4232 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-22 18:30:52.449  4045  4045 D HeadsetService: Received stop request...Stopping profile...
08-22 18:30:52.452   874   874 D BluetoothHeadset: Proxy object disconnected
08-22 18:30:52.453  4045  4045 D A2dpService: Received stop request...Stopping profile...
08-22 18:30:52.453  3967  3977 D BluetoothHeadset: Proxy object disconnected
08-22 18:30:52.453   874   874 D BluetoothHeadset: Proxy object disconnected
08-22 18:30:52.453  4045  4214 D A2dpStateMachine: Exit Disconnected: -1
,08-22 18:30:52.454  1921  2075 D BluetoothHeadset: Proxy object disconnected
08-22 18:30:52.454   874   874 D BluetoothHeadset: Proxy object disconnected
08-22 18:30:52.455  1374  1393 D BluetoothHeadset: Proxy object disconnected
08-22 18:30:52.455  1374  1374 D HeadsetProfile: Bluetooth service disconnected
08-22 18:30:52.456   874   874 D BluetoothA2dp: Proxy object disconnected
08-22 18:30:52.456  4045  4045 D HidService: Received stop request...Stopping profile...
,08-22 18:30:52.456  4045  4045 D HidService: Stopping Bluetooth HidService
08-22 18:30:52.456  1374  1374 D BluetoothA2dp: Proxy object disconnected
08-22 18:30:52.458  1374  1374 D BluetoothInputDevice: Proxy object disconnected
08-22 18:30:52.458  4045  4045 D HealthService: Received stop request...Stopping profile...
08-22 18:30:52.458  1374  1374 D HidProfile: Bluetooth service disconnected
08-22 18:30:52.460  4045  4045 D PanService: Received stop request...Stopping profile...
08-22 18:30:52.461  1374  1374 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-22 18:30:52.461  1374  1374 D PanProfile: Bluetooth service disconnected
08-22 18:30:52.463  4045  4045 D BluetoothMapService: Received stop request...Stopping profile...
08-22 18:30:52.463  1529  1529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-22 18:30:52.463  4045  4045 D BluetoothMapService: stop()
08-22 18:30:52.465  4045  4045 D BluetoothMapAppObserver: deinitObservers()
08-22 18:30:52.465  4045  4045 D BluetoothMapAppObserver: removeReceiver()
08-22 18:30:52.466  1374  1374 D BluetoothMap: Proxy object disconnected
08-22 18:30:52.466  1374  1374 D MapProfile: Bluetooth service disconnected
,08-22 18:30:52.461  3967  3967 D DockEventReceiver: finishStartingService: stopping service
,08-22 18:30:52.467  4045  4045 V BluetoothAdapterState: isTurningOff()=true
08-22 18:30:52.467  4045  4045 V BluetoothAdapterState: isTurningOn()=false
08-22 18:30:52.467  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
08-22 18:30:52.467  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 18:30:52.469  4045  4045 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-22 18:30:52.469  4045  4206 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 18:30:52.470  4045  4206 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 18:30:52.470  4045  4206 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 18:30:52.469  4045  4200 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-22 18:30:52.470  4045  4200 E bt_btif : btif_hf_upstreams_evt: Invalid index 65534
08-22 18:30:52.469  4045  4045 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-22 18:30:52.471  4045  4045 V BluetoothAdapterState: isTurningOff()=true
,08-22 18:30:52.471  4045  4045 V BluetoothAdapterState: isTurningOn()=false
08-22 18:30:52.471  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
08-22 18:30:52.471  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 18:30:52.471  3967  3967 D HeadsetProfile: Bluetooth service disconnected
,08-22 18:30:52.471  4045  4045 V BluetoothAdapterState: isTurningOff()=true
08-22 18:30:52.471  4045  4045 V BluetoothAdapterState: isTurningOn()=false
08-22 18:30:52.471  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
08-22 18:30:52.471  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
08-22 18:30:52.472  3967  3967 D BluetoothA2dp: Proxy object disconnected
08-22 18:30:52.472  3967  3967 D BluetoothInputDevice: Proxy object disconnected
08-22 18:30:52.473  3967  3967 D HidProfile: Bluetooth service disconnected
08-22 18:30:52.473  3967  3967 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-22 18:30:52.473  3967  3967 D PanProfile: Bluetooth service disconnected
08-22 18:30:52.475  3967  3967 D BluetoothMap: Proxy object disconnected
08-22 18:30:52.475  3967  3967 D MapProfile: Bluetooth service disconnected
08-22 18:30:52.475  4045  4206 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 18:30:52.475  4045  4206 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 18:30:52.475  4045  4206 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 18:30:52.475  4045  4206 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-22 18:30:52.475  4045  4206 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 18:30:52.475  4045  4206 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 18:30:52.475  4045  4200 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-22 18:30:52.477  4045  4045 V BluetoothAdapterState: isTurningOff()=true
08-22 18:30:52.477  4045  4045 V BluetoothAdapterState: isTurningOn()=false
08-22 18:30:52.477  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
08-22 18:30:52.477  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 18:30:52.477  4045  4045 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-22 18:30:52.478  4045  4200 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-22 18:30:52.478  4045  4045 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-22 18:30:52.478  4045  4045 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-22 18:30:52.478  4045  4200 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-22 18:30:52.479  4045  4045 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-22 18:30:52.479  4045  4045 V BluetoothAdapterState: isTurningOff()=true
08-22 18:30:52.479  4045  4045 V BluetoothAdapterState: isTurningOn()=false
08-22 18:30:52.479  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
08-22 18:30:52.479  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 18:30:52.480  4045  4045 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-22 18:30:52.480  4045  4045 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-22 18:30:52.482  1374  1374 D BluetoothPbap: Proxy object disconnected
,08-22 18:30:52.482  1374  1374 D PbapServerProfile: Bluetooth service disconnected
,08-22 18:30:52.482  3967  3967 D BluetoothPbap: Proxy object disconnected
,08-22 18:30:52.482  4045  4045 D BluetoothMapService: MAP Service closeService in
08-22 18:30:52.483  4045  4045 V BluetoothAdapterState: isTurningOff()=true
08-22 18:30:52.483  4045  4045 V BluetoothAdapterState: isTurningOn()=false
08-22 18:30:52.483  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
08-22 18:30:52.483  4045  4045 V BluetoothAdapterState: isBleTurningOff()=false
08-22 18:30:52.483  4045  4045 D BluetoothMapService: cleanup()
,08-22 18:30:52.483  4045  4045 D BluetoothMapService: MAP Service closeService in
08-22 18:30:52.483  4045  4196 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-22 18:30:52.483  4045  4196 D BluetoothAdapterProperties: Setting state to 15
08-22 18:30:52.483  4045  4196 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-22 18:30:52.484  4045  4196 I BluetoothAdapterState: Entering BleOnState
08-22 18:30:52.486  3967  3979 D BluetoothPbap: onBluetoothStateChange: up=false
08-22 18:30:52.487   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-22 18:30:52.487  3967  3977 D BluetoothMap: onBluetoothStateChange: up=false
08-22 18:30:52.488   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-22 18:30:52.488  1374  1393 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 18:30:52.488  1374  2029 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-22 18:30:52.489  3967  3967 D PbapServerProfile: Bluetooth service disconnected
08-22 18:30:52.489  1374  1392 D BluetoothPan: onBluetoothStateChange on: false
,08-22 18:30:52.490   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 18:30:52.490   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-22 18:30:52.490  3967  3979 D BluetoothPan: onBluetoothStateChange on: false
08-22 18:30:52.491  1374  1393 D BluetoothMap: onBluetoothStateChange: up=false
08-22 18:30:52.491  3967  3977 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-22 18:30:52.491  1921  1944 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-22 18:30:52.492  3967  3979 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 18:30:52.492  1374  2029 D BluetoothPbap: onBluetoothStateChange: up=false
08-22 18:30:52.493  1374  1392 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 18:30:52.493  3967  3977 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 18:30:52.494  4045  4196 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-22 18:30:52.494  4045  4196 D BluetoothAdapterProperties: Setting state to 16
08-22 18:30:52.494  4045  4196 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-22 18:30:52.494  4045  4196 D BluetoothAdapterProperties: onBleDisable
08-22 18:30:52.494  4045  4196 I BluetoothAdapterState: Entering PendingCommandState
08-22 18:30:52.495  4045  4197 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-22 18:30:52.496  4045  4206 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-22 18:30:52.496  4045  4206 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 18:30:52.497  4045  4200 D BluetoothAdapterProperties: Scan Mode:20
08-22 18:30:52.497  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:52.498  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:52.499  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:52.500  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:52.503  3967  3967 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 18:30:52.507  1529  1529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 18:30:52.510  3967  3967 D DockEventReceiver: finishStartingService: stopping service
,08-22 18:30:52.696  4045  4200 I bt_hci  : shut_down
,08-22 18:30:52.697  4045  4204 D bt_hwcfg: hw_epilog_process
,08-22 18:30:52.709  4045  4204 I bt_vendor: low_power_mode_cb
,08-22 18:30:52.738  4045  4204 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-22 18:30:52.739  4045  4204 I bt_vendor: epilog_cb
08-22 18:30:52.739  4045  4204 I bt_hci  : epilog_finished_callback
,08-22 18:30:52.746  4045  4200 I bt_hci_h4: hal_close
,08-22 18:30:52.748  4045  4200 I bt_userial_vendor: device fd = 51 close
,08-22 18:30:52.865  4045  4197 D bt_stack_manager: event_shut_down_stack finished.
08-22 18:30:52.866  4045  4196 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-22 18:30:52.873  4045  4045 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-22 18:30:52.873  4045  4196 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-22 18:30:52.874  4045  4045 D BtGatt.GattService: Received stop request...Stopping profile...
08-22 18:30:52.875  4045  4045 D BtGatt.GattService: stop()
,08-22 18:30:52.875  4045  4045 D BtGatt.AdvertiseManager: advertise clients cleared
,08-22 18:30:52.879  4045  4045 V BluetoothAdapterState: isTurningOff()=false
,08-22 18:30:52.880  4045  4045 V BluetoothAdapterState: isTurningOn()=false
08-22 18:30:52.880  4045  4045 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 18:30:52.880  4045  4045 V BluetoothAdapterState: isBleTurningOff()=true
08-22 18:30:52.882  4045  4196 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-22 18:30:52.882  4045  4196 D BluetoothAdapterProperties: Setting state to 10
08-22 18:30:52.882  4045  4196 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-22 18:30:52.883   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
08-22 18:30:52.883  4045  4196 I BluetoothAdapterState: Entering OffState
,08-22 18:30:52.904  4045  4045 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-22 18:30:52.904  4045  4045 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-22 18:30:52.905  4045  4197 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-22 18:30:52.915  4045  4197 D bt_stack_manager: event_clean_up_stack finished.
,08-22 18:30:52.915  4045  4045 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-22 18:30:52.920  4045  4045 I art     : System.exit called, status: 0
,08-22 18:30:52.920  4045  4045 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-22 18:30:52.966   874   884 I ActivityManager: Process com.android.bluetooth (pid 4045) has died
,08-22 18:30:55.407  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 18:30:55.407  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:58.416  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 18:30:58.416  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30378e8 added. We now have 6 listener(s)
,08-22 18:30:58.417  3902  3952 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 18:30:58.424  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 18:30:58.426  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c15b01 added. We now have 7 listener(s),
,08-22 18:30:58.427  3902  3952 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 18:30:58.430  3902  3952 I System.out: IsBluetoothEnabled
,08-22 18:30:58.439  3902  3952 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:58.477   874   891 I ActivityManager: Start proc 4243:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-22 18:30:58.596  4243  4243 D AdapterServiceConfig: Adding HeadsetService
08-22 18:30:58.596  4243  4243 D AdapterServiceConfig: Adding A2dpService
08-22 18:30:58.597  4243  4243 D AdapterServiceConfig: Adding HidService
08-22 18:30:58.597  4243  4243 D AdapterServiceConfig: Adding HealthService
08-22 18:30:58.597  4243  4243 D AdapterServiceConfig: Adding PanService
08-22 18:30:58.597  4243  4243 D AdapterServiceConfig: Adding GattService
08-22 18:30:58.597  4243  4243 D AdapterServiceConfig: Adding BluetoothMapService
,08-22 18:30:58.609   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d1952d:true
,08-22 18:30:58.611  4243  4243 D BluetoothAdapterState: make() - Creating AdapterState
,08-22 18:30:58.620  4243  4255 I BluetoothAdapterState: Entering OffState
08-22 18:30:58.620  4243  4243 I bt_bluedroid: init
,08-22 18:30:58.623  4243  4256 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-22 18:30:58.623  4243  4256 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-22 18:30:58.623  4243  4256 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-22 18:30:58.623  4243  4256 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-22 18:30:58.624  4243  4243 I bt_bluedroid: get_profile_interface socket
08-22 18:30:58.627  4243  4259 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-22 18:30:58.629  4243  4243 I bt_bluedroid: get_profile_interface sdp
08-22 18:30:58.629  4243  4259 D BluetoothAdapterProperties: Name is: Nexus 6
,08-22 18:30:58.631  4243  4254 I bt_bluedroid: config_hci_snoop_log
,08-22 18:30:58.632   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-22 18:30:58.640  4243  4255 D BluetoothAdapterState: Current state: OFF, message: 0
08-22 18:30:58.640  4243  4255 D BluetoothAdapterProperties: Setting state to 14
,08-22 18:30:58.640  4243  4255 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-22 18:30:58.642  4243  4255 D BluetoothBondStateMachine: make
,08-22 18:30:58.644  4243  4260 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-22 18:30:58.647  4243  4255 I BluetoothAdapterState: Entering PendingCommandState
,08-22 18:30:58.649  4243  4243 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-22 18:30:58.655  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a394dc2
,08-22 18:30:58.657  4243  4243 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-22 18:30:58.658  4243  4243 D BtGatt.GattService: Received start request. Starting profile...
,08-22 18:30:58.658  4243  4243 D BtGatt.GattService: start()
08-22 18:30:58.658  4243  4243 I bt_bluedroid: get_profile_interface gatt
,08-22 18:30:58.660  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a394dc2
,08-22 18:30:58.660  4243  4243 D BtGatt.AdvertiseManager: advertise manager created
,08-22 18:30:58.669  4243  4243 V BluetoothAdapterState: isTurningOff()=false
08-22 18:30:58.669  4243  4243 V BluetoothAdapterState: isTurningOn()=false
08-22 18:30:58.669  4243  4243 V BluetoothAdapterState: isBleTurningOn()=true
08-22 18:30:58.670  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 18:30:58.670  4243  4255 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-22 18:30:58.671  4243  4255 I bt_bluedroid: enable
08-22 18:30:58.672  4243  4256 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-22 18:30:58.672  4243  4256 I bt_hci  : start_up
,08-22 18:30:58.678  4243  4256 I bt_vendor: alloc value 0xb3a25189
08-22 18:30:58.678  4243  4256 I bt_vendor: init
08-22 18:30:58.678  4243  4256 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-22 18:30:58.678  4243  4256 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-22 18:30:58.787  4243  4256 D bt_hci  : start_up starting async portion
08-22 18:30:58.788  4243  4263 I bt_hci  : event_finish_startup
08-22 18:30:58.788  4243  4263 I bt_hci_h4: hal_open
08-22 18:30:58.788  4243  4263 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-22 18:30:58.796  4243  4263 I bt_userial_vendor: device fd = 51 open
,08-22 18:30:58.828  4243  4263 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-22 18:30:58.860  4243  4263 D bt_hwcfg: Chipset BCM4354A2
08-22 18:30:58.861  4243  4263 D bt_hwcfg: Target name = [BCM4354A2]
,08-22 18:30:58.862  4243  4263 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-22 18:30:59.532  4243  4263 I bt_hwcfg: bt vendor lib: set UART baud 115200,
,08-22 18:30:59.533  4243  4263 D bt_hwcfg: Settlement delay -- 100 ms
,08-22 18:30:59.533  4243  4263 I bt_hwcfg: Setting fw settlement delay to 100 
,08-22 18:30:59.651  4243  4263 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-22 18:30:59.653  4243  4263 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-22 18:30:59.681  4243  4263 I bt_hwcfg: vendor lib fwcfg completed
,08-22 18:30:59.682  4243  4263 I bt_vendor: firmware callback
08-22 18:30:59.682  4243  4263 I bt_hci  : firmware_config_callback
,08-22 18:30:59.695  4243  4265 I bt_btu  : btu_task pending for preload complete event
,08-22 18:30:59.696  4243  4265 I bt_btu_task: Bluetooth chip preload is complete
08-22 18:30:59.696  4243  4265 I bt_btu  : btu_task received preload complete event
,08-22 18:30:59.707  4243  4265 I         : BTE_InitTraceLevels -- TRC_HCI
,08-22 18:30:59.708  4243  4265 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-22 18:30:59.708  4243  4265 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-22 18:30:59.708  4243  4265 I         : BTE_InitTraceLevels -- TRC_AVDT
08-22 18:30:59.708  4243  4265 I         : BTE_InitTraceLevels -- TRC_AVRC
08-22 18:30:59.709  4243  4265 I         : BTE_InitTraceLevels -- TRC_A2D
,08-22 18:30:59.709  4243  4265 I         : BTE_InitTraceLevels -- TRC_BNEP
08-22 18:30:59.709  4243  4265 I         : BTE_InitTraceLevels -- TRC_BTM
08-22 18:30:59.709  4243  4265 I         : BTE_InitTraceLevels -- TRC_GAP
08-22 18:30:59.709  4243  4265 I         : BTE_InitTraceLevels -- TRC_PAN
08-22 18:30:59.710  4243  4265 I         : BTE_InitTraceLevels -- TRC_SDP
08-22 18:30:59.710  4243  4265 I         : BTE_InitTraceLevels -- TRC_GATT
,08-22 18:30:59.710  4243  4265 I         : BTE_InitTraceLevels -- TRC_SMP
08-22 18:30:59.710  4243  4265 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-22 18:30:59.710  4243  4265 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-22 18:30:59.841  4243  4265 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39a2d9d
,08-22 18:30:59.841  4243  4265 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39a2d9d 
,08-22 18:30:59.864  4243  4259 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-22 18:30:59.865  4243  4259 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-22 18:30:59.866  4243  4259 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-22 18:30:59.869  4243  4259 D BluetoothAdapterProperties: Name is: Nexus 6
,08-22 18:30:59.872  4243  4259 D BluetoothAdapterProperties: Scan Mode:20
08-22 18:30:59.873  4243  4259 D BluetoothAdapterProperties: Discoverable Timeout:120
08-22 18:30:59.873  4243  4259 D bt_hci  : do_postload posting postload work item
,08-22 18:30:59.873  4243  4263 I bt_hci  : event_postload
08-22 18:30:59.874  4243  4263 I bt_vendor: sco_config_cb
08-22 18:30:59.874  4243  4263 I bt_hci  : sco_config_callback postload finished.
08-22 18:30:59.877  4243  4259 D bt_bte_conf: Device ID record 1 : primary
,08-22 18:30:59.877  4243  4259 D bt_bte_conf:   vendorId            = 000f
,08-22 18:30:59.877  4243  4259 D bt_bte_conf:   vendorIdSource      = 0001
,08-22 18:30:59.878  4243  4259 D bt_bte_conf:   product             = 1200
,08-22 18:30:59.878  4243  4259 D bt_bte_conf:   version             = 1436
,08-22 18:30:59.878  4243  4259 D bt_bte_conf:   clientExecutableURL = 
,08-22 18:30:59.878  4243  4259 D bt_bte_conf:   serviceDescription  = 
,08-22 18:30:59.879  4243  4259 D bt_bte_conf:   documentationURL    = 
,08-22 18:30:59.879  4243  4259 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-22 18:30:59.879  4243  4256 D bt_stack_manager: event_start_up_stack finished
,08-22 18:30:59.880  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:59.882  4243  4255 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-22 18:30:59.883  4243  4255 D BluetoothAdapterProperties: Setting state to 15
08-22 18:30:59.884  4243  4255 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-22 18:30:59.887  4243  4255 I BluetoothAdapterState: Entering BleOnState
,08-22 18:30:59.891  4243  4263 I bt_vendor: low_power_mode_cb
08-22 18:30:59.893  4243  4255 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-22 18:30:59.893  4243  4255 D BluetoothAdapterProperties: Setting state to 11
08-22 18:30:59.893  4243  4255 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-22 18:30:59.905  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:59.909  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a394dc2
,08-22 18:30:59.911  4243  4243 D HeadsetService: Received start request. Starting profile...
,08-22 18:30:59.912  1529  1529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 18:30:59.920  4243  4255 I BluetoothAdapterState: Entering PendingCommandState
08-22 18:30:59.920  4243  4243 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-22 18:30:59.921  4243  4243 D HeadsetStateMachine: make
,08-22 18:30:59.929  4243  4243 D HeadsetStateMachine: max_hf_connections = 1
,08-22 18:30:59.929  4243  4243 I bt_bluedroid: get_profile_interface handsfree
08-22 18:30:59.929  4243  4259 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-22 18:30:59.929  4243  4259 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-22 18:30:59.933  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a394dc2
08-22 18:30:59.933  4243  4243 D A2dpService: Received start request. Starting profile...
,08-22 18:30:59.934  4243  4243 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-22 18:30:59.934  4243  4243 I bt_bluedroid: get_profile_interface avrcp
,08-22 18:30:59.939  4243  4243 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-22 18:30:59.939  4243  4243 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-22 18:30:59.939  4243  4243 D A2dpStateMachine: make
,08-22 18:30:59.940  4243  4243 I bt_bluedroid: get_profile_interface a2dp
,08-22 18:30:59.941  4243  4259 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-22 18:30:59.943  4243  4275 D A2dpStateMachine: Enter Disconnected: -2
,08-22 18:30:59.944  4243  4243 I BluetoothHidServiceJni: classInitNative: succeeds
,08-22 18:30:59.944  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a394dc2
,08-22 18:30:59.945  4243  4243 D HidService: Received start request. Starting profile...
,08-22 18:30:59.945  4243  4243 I bt_bluedroid: get_profile_interface hidhost
08-22 18:30:59.945  4243  4243 D HidService: setHidService(): set to: null
08-22 18:30:59.946  4243  4243 I BluetoothHealthServiceJni: classInitNative: succeeds
08-22 18:30:59.946  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a394dc2
08-22 18:30:59.947  4243  4259 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39843e5
08-22 18:30:59.947  4243  4259 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-22 18:30:59.947  4243  4243 D HealthService: Received start request. Starting profile...
,08-22 18:30:59.949  4243  4243 I bt_bluedroid: get_profile_interface health
,08-22 18:30:59.950  4243  4243 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-22 18:30:59.951  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a394dc2
,08-22 18:30:59.952  4243  4243 D PanService: Received start request. Starting profile...
08-22 18:30:59.952  4243  4243 D BluetoothPanServiceJni: initializeNative(L110): pan
08-22 18:30:59.952  4243  4243 I bt_bluedroid: get_profile_interface pan
,08-22 18:30:59.953  4243  4259 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-22 18:30:59.956  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a394dc2
,08-22 18:30:59.956  4243  4243 D BluetoothMapService: Received start request. Starting profile...
08-22 18:30:59.957  4243  4243 D BluetoothMapService: start()
,08-22 18:30:59.960  4243  4243 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-22 18:30:59.961  4243  4243 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-22 18:30:59.961  4243  4243 D BluetoothMapAppObserver: createReceiver()
,08-22 18:30:59.962  4243  4243 D BluetoothMapAppObserver: initObservers()
,08-22 18:30:59.962  4243  4243 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-22 18:30:59.973  4243  4243 V BluetoothAdapterState: isTurningOff()=false
,08-22 18:30:59.973  4243  4273 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-22 18:30:59.973  4243  4243 V BluetoothAdapterState: isTurningOn()=true
08-22 18:30:59.973  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 18:30:59.973  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 18:30:59.975  4243  4243 V BluetoothAdapterState: isTurningOff()=false
,08-22 18:30:59.975  4243  4243 V BluetoothAdapterState: isTurningOn()=true
08-22 18:30:59.975  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
08-22 18:30:59.975  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 18:30:59.975  4243  4243 V BluetoothAdapterState: isTurningOff()=false
08-22 18:30:59.975  4243  4243 V BluetoothAdapterState: isTurningOn()=true
08-22 18:30:59.975  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
08-22 18:30:59.975  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 18:30:59.976  4243  4243 V BluetoothAdapterState: isTurningOff()=false
08-22 18:30:59.976  4243  4243 V BluetoothAdapterState: isTurningOn()=true
08-22 18:30:59.976  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 18:30:59.976  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
08-22 18:30:59.976  4243  4243 V BluetoothAdapterState: isTurningOff()=false
08-22 18:30:59.976  4243  4243 V BluetoothAdapterState: isTurningOn()=true,
08-22 18:30:59.976  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 18:30:59.976  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
08-22 18:30:59.976  4243  4243 V BluetoothAdapterState: isTurningOff()=false
,08-22 18:30:59.977  4243  4243 V BluetoothAdapterState: isTurningOn()=true
,08-22 18:30:59.977  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 18:30:59.977  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
08-22 18:30:59.977  4243  4255 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-22 18:30:59.977  4243  4255 D BluetoothAdapterProperties: ScanMode =  20
,08-22 18:30:59.977  4243  4255 D BluetoothAdapterProperties: State =  11
08-22 18:30:59.978  4243  4259 D BluetoothAdapterProperties: Scan Mode:21
,08-22 18:30:59.979  4243  4259 D BluetoothAdapterProperties: Discoverable Timeout:120
08-22 18:30:59.979  4243  4255 D BluetoothAdapterProperties: Setting state to 12
08-22 18:30:59.979  4243  4255 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-22 18:30:59.980  4243  4255 I BluetoothAdapterState: Entering OnState
,08-22 18:30:59.980  3967  3979 D BluetoothPbap: onBluetoothStateChange: up=true
,08-22 18:30:59.982   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-22 18:30:59.982  3967  3977 D BluetoothMap: onBluetoothStateChange: up=true
,08-22 18:30:59.982  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:59.982  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:59.982  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:59.982  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:30:59.982  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,08-22 18:30:59.982  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:59.982  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:59.982  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:30:59.984   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 18:30:59.984  3902  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:30:59.984  1374  1392 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 18:30:59.985  1374  2029 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-22 18:30:59.986  3967  3967 D BluetoothMap: Proxy object connected
08-22 18:30:59.987  1374  1374 D BluetoothA2dp: Proxy object connected
08-22 18:30:59.987  3967  3967 D MapProfile: Bluetooth service connected
08-22 18:30:59.987  3967  3967 D BluetoothMap: getConnectedDevices()
08-22 18:30:59.987  1374  1392 D BluetoothPan: onBluetoothStateChange on: true
08-22 18:30:59.988  1374  1374 D BluetoothInputDevice: Proxy object connected
08-22 18:30:59.988  1374  1374 D HidProfile: Bluetooth service connected
,08-22 18:30:59.989   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 18:30:59.989   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 18:30:59.989   874   874 D BluetoothA2dp: Proxy object connected
08-22 18:30:59.989  3967  3977 D BluetoothPan: onBluetoothStateChange on: true
08-22 18:30:59.990  1374  1374 D BluetoothPan: BluetoothPAN Proxy object connected
08-22 18:30:59.990  1374  1374 D PanProfile: Bluetooth service connected
08-22 18:30:59.991  4243  4243 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-22 18:30:59.991  4243  4243 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-22 18:30:59.991  1374  1392 D BluetoothMap: onBluetoothStateChange: up=true
08-22 18:30:59.992  4243  4243 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 18:30:59.992  3967  3967 D BluetoothPan: BluetoothPAN Proxy object connected
08-22 18:30:59.993  3967  3967 D PanProfile: Bluetooth service connected
08-22 18:30:59.993  1374  1374 D BluetoothMap: Proxy object connected
08-22 18:30:59.993  1374  1374 D MapProfile: Bluetooth service connected
08-22 18:30:59.993  3967  3977 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-22 18:30:59.993  1374  1374 D BluetoothMap: getConnectedDevices()
08-22 18:30:59.994  4243  4243 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 18:30:59.995  4243  4243 D ObexServerSockets: Succeed to create listening sockets 
08-22 18:30:59.995  4243  4243 D ObexServerSockets0: startAccept()
,08-22 18:30:59.995  4243  4243 D ObexServerSockets0: prepareForNewConnect()
08-22 18:30:59.996  1921  1944 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 18:30:59.996  3967  4280 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 18:30:59.996  1374  2029 D BluetoothPbap: onBluetoothStateChange: up=true
08-22 18:30:59.997  4243  4243 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-22 18:30:59.998  4243  4243 D BluetoothSdpJni: SDP Create record success - handle: 0
08-22 18:30:59.998  4243  4281 D ObexServerSockets0: Accepting socket connection...
,08-22 18:30:59.998  4243  4282 D ObexServerSockets0: Accepting socket connection...
,08-22 18:30:59.999  1374  1393 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-22 18:31:00.000  3967  3979 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 18:31:00.000  3967  3967 D BluetoothInputDevice: Proxy object connected
,08-22 18:31:00.003  3967  3967 D HidProfile: Bluetooth service connected
,08-22 18:31:00.003   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,08-22 18:31:00.006  4243  4243 D BluetoothMapService: onReceive
,08-22 18:31:00.006  4243  4243 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-22 18:31:00.006  4243  4243 D BluetoothMapService: STATE_ON
08-22 18:31:00.007  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:31:00.007  3967  3967 D BluetoothA2dp: Proxy object connected
,08-22 18:31:00.013  3967  3967 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 18:31:00.018  3967  3967 D DockEventReceiver: finishStartingService: stopping service
,08-22 18:31:00.018  1529  1529 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 18:31:00.029  3967  3967 D BluetoothPbap: Proxy object connected
,08-22 18:31:00.029  3967  3967 D PbapServerProfile: Bluetooth service connected
,08-22 18:31:00.033  4243  4243 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-22 18:31:00.033  4243  4243 D ObexServerSockets0: prepareForNewConnect()
,08-22 18:31:00.036  4243  4287 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 18:31:00.043  1374  1374 D BluetoothPbap: Proxy object connected
,08-22 18:31:00.043  1374  1374 D PbapServerProfile: Bluetooth service connected
,08-22 18:31:00.052  4243  4291 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 18:31:00.056  4243  4291 I BtOppRfcommListener: Accept thread started.
,08-22 18:31:00.083   874   874 D BluetoothHeadset: Proxy object connected
,08-22 18:31:00.083  3967  4280 D BluetoothHeadset: Proxy object connected
,08-22 18:31:00.084   874   874 D BluetoothHeadset: Proxy object connected
,08-22 18:31:00.084  1921  2074 D BluetoothHeadset: Proxy object connected
08-22 18:31:00.084   874   874 D BluetoothHeadset: Proxy object connected,
08-22 18:31:00.084  3967  3967 D HeadsetProfile: Bluetooth service connected
08-22 18:31:00.084  1374  1393 D BluetoothHeadset: Proxy object connected
,08-22 18:31:00.084   874   891 D BluetoothHeadset: Proxy object connected
,08-22 18:31:00.087  1374  1374 D HeadsetProfile: Bluetooth service connected
,08-22 18:31:00.089   874   891 D BluetoothHeadset: Proxy object connected
,08-22 18:31:00.096  1921  1951 D BluetoothHeadset: Proxy object connected
,08-22 18:31:00.097  3967  3979 D BluetoothHeadset: Proxy object connected
,08-22 18:31:00.097  3967  3967 D HeadsetProfile: Bluetooth service connected
,08-22 18:31:00.100  1374  1392 D BluetoothHeadset: Proxy object connected
,08-22 18:31:00.101  1374  1374 D HeadsetProfile: Bluetooth service connected
,08-22 18:31:00.459  3902  3952 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:31:00.459  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:00.459  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:31:00.459  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:31:00.459  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:31:00.459  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:31:00.459  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:31:00.459  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:31:00.467  3902  3952 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:31:00.470  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 18:31:00.471  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9d43da6 added. We now have 8 listener(s)
,08-22 18:31:00.472  3902  3952 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 18:31:00.477   874  1971 D WifiService: setWifiEnabled: false pid=3902, uid=10000
,08-22 18:31:00.478   874  1971 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-22 18:31:00.491  3902  3952 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:31:00.492   874  1973 D WifiService: setWifiEnabled: true pid=3902, uid=10000
,08-22 18:31:00.492   874  1973 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-22 18:31:00.506   874  1316 D WifiConfigStore: Loading config and enabling all networks 
,08-22 18:31:00.529  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:31:00.529  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:00.529  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:31:00.529  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:31:00.529  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:31:00.529  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:31:00.529  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:31:00.529  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:31:00.536  3902  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:31:00.537   874  1316 D WifiConfigStore: loaded 0 passpoint configs
08-22 18:31:00.538   874  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-22 18:31:00.539   874  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-22 18:31:00.540   874  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-22 18:31:00.540   874  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-22 18:31:00.540   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-22 18:31:00.540   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-22 18:31:00.557   874  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.88 rxSuccessRate=1.16 delta 1000 -> 1000
,08-22 18:31:00.557   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-22 18:31:00.561   372   872 D CommandListener: Setting iface cfg
,08-22 18:31:00.567   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-22 18:31:00.567   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 18:31:00.567   874  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,08-22 18:31:00.567   874  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-22 18:31:00.576   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-22 18:31:00.634   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-22 18:31:00.637  1476  1476 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-22 18:31:00.691   874  1315 D WifiNative-HAL: p2pGetDeviceAddress
,08-22 18:31:00.693   874  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-22 18:31:01.111  1476  1476 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-22 18:31:01.159  1476  1476 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-22 18:31:01.159  1476  1476 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-22 18:31:01.170   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 18:31:01.184   874  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-22 18:31:01.184   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-22 18:31:01.184   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 18:31:01.205   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 18:31:01.218   372   872 D CommandListener: Setting iface cfg
,08-22 18:31:01.219   874  1316 D WifiStateMachine: Start Dhcp Watchdog 3
,08-22 18:31:01.233   874  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-22 18:31:01.234   874  1318 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-22 18:31:01.236   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-22 18:31:01.261   874  4299 D DhcpClient: Receive thread started
,08-22 18:31:01.342   874  1316 E native  : do suspend false
,08-22 18:31:01.362   874  1878 D DhcpClient: Broadcasting DHCPDISCOVER
,08-22 18:31:01.376   874  4299 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-22 18:31:01.378   874  1878 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-22 18:31:01.383   874  1878 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-22 18:31:01.401   874  4299 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-22 18:31:01.402   874  1878 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-22 18:31:01.409   372   872 D CommandListener: Setting iface cfg
,08-22 18:31:01.420   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-22 18:31:01.424   874  1878 D DhcpClient: Scheduling renewal in 86399s
,08-22 18:31:01.435   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-22 18:31:01.438   874  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,08-22 18:31:01.440   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-22 18:31:01.446   874  1318 D ConnectivityService: Adding iface wlan0 to network 102
,08-22 18:31:01.452   874  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-22 18:31:01.498   874  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-22 18:31:01.500   874  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-22 18:31:01.501   874  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-22 18:31:01.503   874  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-22 18:31:01.505   874  1318 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-22 18:31:01.511  3902  3952 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:31:01.511  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:01.511  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:31:01.511  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:31:01.511  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:31:01.511  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:31:01.511  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:31:01.511  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:31:01.513   874  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-22 18:31:01.513  3902  3952 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:31:01.517   874  1318 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-22 18:31:01.517  3902  3952 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-22 18:31:01.517   874  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-22 18:31:01.517   874  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-22 18:31:01.517   874  1318 D ConnectivityService:    accepting network in place of null
08-22 18:31:01.517   874  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-22 18:31:01.518   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-22 18:31:01.518  3902  3952 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-22 18:31:01.519   874  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-22 18:31:01.520  3902  3952 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@52840e Bundle[{}]
,08-22 18:31:01.521  3902  3952 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-22 18:31:01.521  3902  3952 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-22 18:31:01.521  3902  3952 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-22 18:31:01.522  3902  3952 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-22 18:31:01.523  3902  3952 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-22 18:31:01.523  3902  3952 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-22 18:31:01.524   874  4298 D NetlinkSocketObserver: NeighborEvent{elapsedMs=145116, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-22 18:31:01.528  3902  3952 I System.out: Running OutgoingSocketThread
,08-22 18:31:01.529  3902  4304 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 443)
,08-22 18:31:01.529  3902  4304 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48149
08-22 18:31:01.529  3902  4304 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-22 18:31:01.546   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 18:31:01.585   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 18:31:01.595   874  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-22 18:31:01.595   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-22 18:31:01.601   874  4297 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-22 18:31:01.603   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-22 18:31:01.607   874  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-22 18:31:01.622  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:31:01.622  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:01.622  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:31:01.622  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:31:01.622  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:31:01.622  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:31:01.622  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:31:01.622  3902  3902 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 18:31:01.623  1993  1993 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-22 18:31:01.625  3902  3902 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 18:31:01.659  1749  1749 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-22 18:31:01.668  1749  1749 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-22 18:31:01.669  1749  1749 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-22 18:31:01.671  4058  4058 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-22 18:31:01.673   874  4297 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 22 Aug 2016 16:31:01 GMT], X-Android-Received-Millis=[1471883461672], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471883461649]}
08-22 18:31:01.673   874  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-22 18:31:01.674   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-22 18:31:01.674   874  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102],
08-22 18:31:01.675   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-22 18:31:01.699  1749  4315 I MDM     : [180] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-22 18:31:01.699  1749  4315 W BaseAppContext: Using Auth Proxy for data requests.
,08-22 18:31:01.701  4058  4058 D SprintDMHelper: simOperator: 
,08-22 18:31:01.701  4058  4058 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-22 18:31:01.710  1749  4315 V GoogleAuthProtoRequest: [180] a.<init>: mAccountName set to: thalitester@gmail.com
,08-22 18:31:01.724  1749  2428 I iu.UploadsManager: num queued entries: 0
,08-22 18:31:01.724  1749  2428 I iu.UploadsManager: num updated entries: 0
08-22 18:31:01.724  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 18:31:01.728  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 18:31:01.747  1749  2428 I iu.SyncManager: NEXT; no task
,08-22 18:31:01.769  1529  2981 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-22 18:31:01.769  1529  2981 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-22 18:31:01.770  1529  2981 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 18:31:01.770  1529  2981 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 18:31:01.774  1529  2033 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-22 18:31:01.774  1529  2033 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-22 18:31:01.775  1529  2033 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 18:31:01.775  1529  2033 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 18:31:01.791  3652  4312 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-22 18:31:01.791  3652  4312 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-22 18:31:01.791  3652  4312 E HttpOperation: 	at jdm.a(PG:82)
08-22 18:31:01.791  3652  4312 E HttpOperation: 	at jcs.o(PG:406)
08-22 18:31:01.791  3652  4312 E HttpOperation: 	at jcn.a(PG:1379)
08-22 18:31:01.791  3652  4312 E HttpOperation: 	at jcs.i(PG:143)
08-22 18:31:01.791  3652  4312 E HttpOperation: 	at blb.a(PG:3937)
08-22 18:31:01.791  3652  4312 E HttpOperation: 	at czp.a(PG:18188)
08-22 18:31:01.791  3652  4312 E HttpOperation: 	at czp.a(PG:9081)
08-22 18:31:01.791  3652  4312 E HttpOperation: 	at czq.run(PG:1686)
08-22 18:31:01.791  3652  4312 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-22 18:31:01.791  3652  4312 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-22 18:31:01.791  3652  4312 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-22 18:31:01.791  3652  4312 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-22 18:31:01.791  3652  4312 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-22 18:31:01.791  3652  4312 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-22 18:31:01.791  3652  4312 E HttpOperation: 	at jdj.a(PG:4091)
08-22 18:31:01.791  3652  4312 E HttpOperation: 	at jdj.a(PG:1125)
08-22 18:31:01.791  3652  4312 E HttpOperation: 	at jdm.a(PG:77)
08-22 18:31:01.791  3652  4312 E HttpOperation: 	... 12 more
08-22 18:31:01.791  3652  4312 E HttpOperation: Caused by: faj: BadAuthentication
08-22 18:31:01.791  3652  4312 E HttpOperation: 	at fal.a(PG:38)
08-22 18:31:01.791  3652  4312 E HttpOperation: 	at jdj.a(PG:4089)
08-22 18:31:01.791  3652  4312 E HttpOperation: 	... 14 more
,08-22 18:31:01.797  1749  4315 E MDM     : [180] SitrepService.a: Error sending sitrep.
,08-22 18:31:01.834  2462  4318 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-22 18:31:01.840  1529  1551 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-22 18:31:01.841  1529  1551 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-22 18:31:01.841  1529  1551 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 18:31:01.841  1529  1551 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 18:31:01.858  3652  4312 E HttpOperation: [getmobileexperiments] Unexpected exception
08-22 18:31:01.858  3652  4312 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-22 18:31:01.858  3652  4312 E HttpOperation: 	at jdm.a(PG:82)
08-22 18:31:01.858  3652  4312 E HttpOperation: 	at jcs.o(PG:406)
08-22 18:31:01.858  3652  4312 E HttpOperation: 	at jcn.a(PG:1379)
08-22 18:31:01.858  3652  4312 E HttpOperation: 	at jcs.i(PG:143)
08-22 18:31:01.858  3652  4312 E HttpOperation: 	at hec.a(PG:42)
08-22 18:31:01.858  3652  4312 E HttpOperation: 	at hee.a(PG:102)
08-22 18:31:01.858  3652  4312 E HttpOperation: 	at czr.a(PG:65)
08-22 18:31:01.858  3652  4312 E HttpOperation: 	at kka.a(PG:108)
08-22 18:31:01.858  3652  4312 E HttpOperation: 	at czp.a(PG:19176)
08-22 18:31:01.858  3652  4312 E HttpOperation: 	at czp.a(PG:9081)
08-22 18:31:01.858  3652  4312 E HttpOperation: 	at czq.run(PG:1686)
08-22 18:31:01.858  3652  4312 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-22 18:31:01.858  3652  4312 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-22 18:31:01.858  3652  4312 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-22 18:31:01.858  3652  4312 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-22 18:31:01.858  3652  4312 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-22 18:31:01.858  3652  4312 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-22 18:31:01.858  3652  4312 E HttpOperation: 	at jdj.a(PG:4091)
08-22 18:31:01.858  3652  4312 E HttpOperation: 	at jdj.a(PG:1125)
08-22 18:31:01.858  3652  4312 E HttpOperation: 	at jdm.a(PG:77)
08-22 18:31:01.858  3652  4312 E HttpOperation: 	... 15 more
08-22 18:31:01.858  3652  4312 E HttpOperation: Caused by: faj: BadAuthentication
08-22 18:31:01.858  3652  4312 E HttpOperation: 	at fal.a(PG:38)
08-22 18:31:01.858  3652  4312 E HttpOperation: 	at jdj.a(PG:4089)
08-22 18:31:01.858  3652  4312 E HttpOperation: 	... 17 more
,08-22 18:31:01.858  3652  4312 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-22 18:31:01.858  3652  4312 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-22 18:31:01.858  3652  4312 E ExperimentLoader: 	at jdm.a(PG:82)
08-22 18:31:01.858  3652  4312 E ExperimentLoader: 	at jcs.o(PG:406)
08-22 18:31:01.858  3652  4312 E ExperimentLoader: 	at jcn.a(PG:1379)
08-22 18:31:01.858  3652  4312 E ExperimentLoader: 	at jcs.i(PG:143)
08-22 18:31:01.858  3652  4312 E ExperimentLoader: 	at hec.a(PG:42)
08-22 18:31:01.858  3652  4312 E ExperimentLoader: 	at hee.a(PG:102)
08-22 18:31:01.858  3652  4312 E ExperimentLoader: 	at czr.a(PG:65)
08-22 18:31:01.858  3652  4312 E ExperimentLoader: 	at kka.a(PG:108)
08-22 18:31:01.858  3652  4312 E ExperimentLoader: 	at czp.a(PG:19176)
08-22 18:31:01.858  3652  4312 E ExperimentLoader: 	at czp.a(PG:9081)
08-22 18:31:01.858  3652  4312 E ExperimentLoader: 	at czq.run(PG:1686)
08-22 18:31:01.858  3652  4312 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-22 18:31:01.858  3652  4312 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-22 18:31:01.858  3652  4312 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-22 18:31:01.858  3652  4312 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-22 18:31:01.858  3652  4312 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-22 18:31:01.858  3652  4312 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-22 18:31:01.858  3652  4312 E ExperimentLoader: 	at jdj.a(PG:4091)
08-22 18:31:01.858  3652  4312 E ExperimentLoader: 	at jdj.a(PG:1125)
08-22 18:31:01.858  3652  4312 E ExperimentLoader: 	at jdm.a(PG:77)
08-22 18:31:01.858  3652  4312 E ExperimentLoader: 	... 15 more
08-22 18:31:01.858  3652  4312 E ExperimentLoader: Caused by: faj: BadAuthentication
08-22 18:31:01.858  3652  4312 E ExperimentLoader: 	at fal.a(PG:38)
08-22 18:31:01.858  3652  4312 E ExperimentLoader: 	,at jdj.a(PG:4089)
08-22 18:31:01.858  3652  4312 E ExperimentLoader: 	... 17 more
,08-22 18:31:01.985   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 134046, reason: Periodic, SyncResult: stats [ numIoExceptions: 1],
,08-22 18:31:02.530  3902  3952 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 444)
08-22 18:31:02.531  3902  3952 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 444)
,08-22 18:31:02.541  3902  3952 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 449)
,08-22 18:31:02.543  3902  3952 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-22 18:31:02.543  3902  3952 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 450)
,08-22 18:31:02.549  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:31:02.550  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e8b03e7 added. We now have 2 listener(s)
,08-22 18:31:02.552  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
,08-22 18:31:02.552  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:31:02.552  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:31:02.552  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:31:02.552  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80b3b94 added. We now have 9 listener(s)
08-22 18:31:02.552  3902  3952 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:31:02.553  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 18:31:02.557  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 18:31:02.566  3902  3952 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:31:02.566  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:02.566  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:31:02.566  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:31:02.566  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:31:02.566  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:31:02.566  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:31:02.566  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 18:31:02.569  3902  3952 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 18:31:02.569  3902  3952 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 18:31:02.569  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:31:02.569  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@df68e32 added. We now have 3 listener(s)
,08-22 18:31:02.571  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-22 18:31:02.571  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:31:02.571  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:31:02.571  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:31:02.571  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df9f783 added. We now have 10 listener(s)
08-22 18:31:02.572  3902  3952 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:31:02.572  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:02.572  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:02.572  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 18:31:02.572  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:02.572  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 18:31:02.576  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:31:02.572  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:31:02.582  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-22 18:31:02.582  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e8b03e7 removed from the list
08-22 18:31:02.582  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:02.582  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80b3b94 removed from the list
,08-22 18:31:02.588  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:31:02.588  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:02.588  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:02.589  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:02.589  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:31:02.590  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 18:31:02.590  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:02.590  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:02.590  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@80b3b94 not in the list
08-22 18:31:02.590  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 18:31:02.590  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:02.592  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:02.592  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:02.592  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 18:31:02.592  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df9f783 removed from the list
08-22 18:31:02.592  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:02.592  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:02.592  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:02.592  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-22 18:31:02.592  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@df68e32 removed from the list
08-22 18:31:02.593   874  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
08-22 18:31:02.594  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:31:02.594  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2a7d00 added. We now have 2 listener(s)
08-22 18:31:02.595  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-22 18:31:02.596  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:31:02.596  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:31:02.596  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 18:31:02.596  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52d6939 added. We now have 9 listener(s)
08-22 18:31:02.596  3902  3952 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:31:02.597  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 18:31:02.608  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 18:31:02.615  3902  3952 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:31:02.615  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:02.615  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:31:02.615  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:31:02.615  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:31:02.615  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:31:02.615  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:31:02.615  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 18:31:02.619  3902  3952 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 18:31:02.619  3902  3952 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 18:31:02.619  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 18:31:02.620  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cda88df added. We now have 3 listener(s)
,08-22 18:31:02.623  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:31:02.624  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 18:31:02.624  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 18:31:02.624  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 18:31:02.625  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 18:31:02.625  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a692c added. We now have 10 listener(s)
,08-22 18:31:02.625  3902  3952 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 18:31:02.626  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 18:31:02.626  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-22 18:31:02.626  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 18:31:02.626  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:31:02.626  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:31:02.626  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 18:31:02.634  3902  3952 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-22 18:31:02.634  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 18:31:02.644  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 18:31:02.645  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-22 18:31:02.645  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 18:31:02.650  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-22 18:31:02.650  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 18:31:02.650  3902  3952 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 18:31:02.651  3902  3952 D BluetoothAdapter: STATE_ON
,08-22 18:31:02.654  4243  4271 D BtGatt.GattService: registerClient() - UUID=66e1dca9-d954-4675-a651-a55f0fd346af
,08-22 18:31:02.655  4243  4259 D BtGatt.GattService: onClientRegistered() - UUID=66e1dca9-d954-4675-a651-a55f0fd346af, clientIf=5
,08-22 18:31:02.656  3902  3913 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-22 18:31:02.658  4243  4253 D BtGatt.GattService: start scan with filters
,08-22 18:31:02.665  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-22 18:31:02.665  4243  4262 D BtGatt.ScanManager: handling starting scan
,08-22 18:31:02.665  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-22 18:31:02.666  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 18:31:02.666  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 18:31:02.669  4243  4262 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a394dc2
08-22 18:31:02.669  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 18:31:02.669  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 18:31:02.669  3902  3902 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 18:31:02.671  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 18:31:02.674  3902  3952 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-22 18:31:02.674  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-22 18:31:02.674  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-22 18:31:02.674  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:02.674  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 18:31:02.674  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 18:31:02.675  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 18:31:02.675  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 18:31:02.675  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 18:31:02.675  4243  4259 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-22 18:31:02.675  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:31:02.675  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 18:31:02.675  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 18:31:02.676  3902  3952 D BluetoothAdapter: STATE_ON
08-22 18:31:02.676  4243  4262 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-22 18:31:02.677  4243  4271 D BtGatt.GattService: stopScan() - queue size =1
08-22 18:31:02.678  4243  4253 D BtGatt.GattService: unregisterClient() - clientIf=5
08-22 18:31:02.679  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:31:02.680  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 18:31:02.680  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 18:31:02.680  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 18:31:02.680  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-22 18:31:02.681  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 18:31:02.682  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 18:31:02.682  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 18:31:02.683  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 18:31:02.684  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 18:31:02.689  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-22 18:31:02.689  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 18:31:02.689  3902  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:31:02.689  4243  4262 D BtGatt.ScanManager: Starting BLE batch scan
08-22 18:31:02.690  3902  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:31:02.690  4243  4262 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-22 18:31:02.690  3902  3902 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 18:31:02.694  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:02.694  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-22 18:31:02.695  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:31:02.695  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:02.695  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:02.695  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:31:02.695  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:31:02.695  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2a7d00 removed from the list
08-22 18:31:02.695  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:02.695  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52d6939 removed from the list
,08-22 18:31:02.695  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:02.696  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:02.696  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:02.696  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:02.698  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:02.698  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:02.698  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:02.698  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52d6939 not in the list
08-22 18:31:02.698  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:02.698  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:02.700  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 18:31:02.700  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:02.700  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:02.700  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a3a692c removed from the list
08-22 18:31:02.700  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:02.700  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:02.701  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:02.701  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:31:02.701  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cda88df removed from the list
08-22 18:31:02.702  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:31:02.702  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7aec18 added. We now have 2 listener(s)
,08-22 18:31:02.705  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-22 18:31:02.706  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:31:02.706  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:31:02.706  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:31:02.706  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d60671 added. We now have 9 listener(s)
08-22 18:31:02.706  3902  3952 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 18:31:02.707  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 18:31:02.709  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 18:31:02.716  3902  3952 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:31:02.716  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:02.716  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:31:02.716  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:31:02.716  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:31:02.716  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:31:02.716  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:31:02.716  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 18:31:02.719  3902  3952 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 18:31:02.719  3902  3952 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 18:31:02.720  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:31:02.720  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c06b4d7 added. We now have 3 listener(s)
08-22 18:31:02.722  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 18:31:02.722  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:31:02.722  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:31:02.722  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:31:02.723  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3eb1c4 added. We now have 10 listener(s)
08-22 18:31:02.723  3902  3952 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:31:02.723  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-22 18:31:02.724  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-22 18:31:02.724  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:31:02.725  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 18:31:02.725  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-22 18:31:02.725  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 18:31:02.725  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-22 18:31:02.728  4243  4259 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-22 18:31:02.729  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:31:02.732  3902  3952 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-22 18:31:02.732  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 18:31:02.733  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:31:02.739  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-22 18:31:02.740  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-22 18:31:02.740  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-22 18:31:02.743  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-22 18:31:02.743  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 18:31:02.747  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 18:31:02.747  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 18:31:02.747  3902  3952 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 18:31:02.749  3902  3952 D BluetoothAdapter: STATE_ON
,08-22 18:31:02.755  4243  4272 D BtGatt.GattService: registerClient() - UUID=681d9f68-9f67-40c6-bebc-3520a701b9fb
,08-22 18:31:02.755  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-22 18:31:02.755  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:31:02.756  4243  4259 D BtGatt.GattService: onClientRegistered() - UUID=681d9f68-9f67-40c6-bebc-3520a701b9fb, clientIf=5
08-22 18:31:02.756  4243  4262 D BtGatt.ScanManager: stopping BLe Batch
08-22 18:31:02.756  3902  3914 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-22 18:31:02.757  4243  4271 D BtGatt.GattService: start scan with filters
,08-22 18:31:02.760  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-22 18:31:02.760  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 18:31:02.760  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 18:31:02.761  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 18:31:02.762  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-22 18:31:02.762  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 18:31:02.762  4243  4262 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-22 18:31:02.764  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 18:31:02.764  3902  3902 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 18:31:02.764  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-22 18:31:02.765  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 18:31:02.768  4243  4259 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-22 18:31:02.769  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:31:02.769  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 18:31:02.769  3902  3952 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-22 18:31:02.769  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:02.769  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-22 18:31:02.769  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 18:31:02.769  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:02.769  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:02.769  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 18:31:02.769  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:31:02.770  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7aec18 removed from the list
08-22 18:31:02.770  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:02.770  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d60671 removed from the list
,08-22 18:31:02.770  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:02.770  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:31:02.770  4243  4262 D BtGatt.ScanManager: handling starting scan
08-22 18:31:02.770  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:02.770  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-22 18:31:02.770  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:02.770  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:31:02.771  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:02.771  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:02.771  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:02.771  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d60671 not in the list
08-22 18:31:02.772  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-22 18:31:02.772  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 18:31:02.772  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 18:31:02.772  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 18:31:02.772  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-22 18:31:02.773  3902  3952 D BluetoothAdapter: STATE_ON
08-22 18:31:02.773  4243  4253 D BtGatt.GattService: stopScan() - queue size =1
,08-22 18:31:02.774  4243  4254 D BtGatt.GattService: unregisterClient() - clientIf=5
08-22 18:31:02.774  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:31:02.774  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 18:31:02.774  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 18:31:02.774  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 18:31:02.774  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-22 18:31:02.776  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 18:31:02.776  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-22 18:31:02.776  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 18:31:02.776  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 18:31:02.776  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:02.777  4243  4259 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-22 18:31:02.777  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:31:02.777  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:02.777  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:02.778  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:02.778  3902  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:31:02.778  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3eb1c4 removed from the list
08-22 18:31:02.778  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:02.778  3902  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:31:02.778  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 18:31:02.778  3902  3902 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 18:31:02.778  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:02.778  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:31:02.778  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c06b4d7 removed from the list
08-22 18:31:02.779  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:31:02.779  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6572630 added. We now have 2 listener(s)
,08-22 18:31:02.780  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 18:31:02.780  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:31:02.780  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:31:02.780  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:31:02.781  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9de12a9 added. We now have 9 listener(s)
08-22 18:31:02.781  3902  3952 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 18:31:02.781  4243  4262 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-22 18:31:02.781  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 18:31:02.785  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 18:31:02.788  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-22 18:31:02.788  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:31:02.788  4243  4262 D BtGatt.ScanManager: Starting BLE batch scan
08-22 18:31:02.788  4243  4262 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-22 18:31:02.790  3902  3952 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:31:02.790  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:02.790  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:31:02.790  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:31:02.790  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:31:02.790  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:31:02.790  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:31:02.790  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 18:31:02.791  3902  3952 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 18:31:02.791  3902  3952 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 18:31:02.793  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 18:31:02.793  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@81d67cf added. We now have 3 listener(s)
,08-22 18:31:02.795  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-22 18:31:02.796  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-22 18:31:02.796  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:31:02.796  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:31:02.796  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:31:02.796  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340755c added. We now have 10 listener(s)
,08-22 18:31:02.796  3902  3952 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:31:02.796  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 18:31:02.796  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 18:31:02.796  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-22 18:31:02.796  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:31:02.796  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-22 18:31:02.797  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:31:02.800  4243  4259 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-22 18:31:02.800  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:31:02.800  3902  3952 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-22 18:31:02.800  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 18:31:02.804  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 18:31:02.805  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-22 18:31:02.805  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 18:31:02.808  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-22 18:31:02.808  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:31:02.808  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-22 18:31:02.808  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 18:31:02.808  3902  3952 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 18:31:02.809  3902  3952 D BluetoothAdapter: STATE_ON
,08-22 18:31:02.811  4243  4283 D BtGatt.GattService: registerClient() - UUID=970d5b13-ebbe-4b7b-987b-9a990703afb1
,08-22 18:31:02.811  4243  4259 D BtGatt.GattService: onClientRegistered() - UUID=970d5b13-ebbe-4b7b-987b-9a990703afb1, clientIf=5
08-22 18:31:02.811  3902  3913 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-22 18:31:02.812  4243  4253 D BtGatt.GattService: start scan with filters
,08-22 18:31:02.814  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-22 18:31:02.814  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 18:31:02.815  4243  4262 D BtGatt.ScanManager: stopping BLe Batch
,08-22 18:31:02.815  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 18:31:02.815  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-22 18:31:02.815  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-22 18:31:02.815  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 18:31:02.818  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 18:31:02.818  3902  3902 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 18:31:02.818  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 18:31:02.819  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-22 18:31:02.819  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:31:02.820  4243  4262 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-22 18:31:02.820  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 18:31:02.824  4243  4259 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-22 18:31:02.824  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 18:31:02.825  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:02.825  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:02.825  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:31:02.825  4243  4262 D BtGatt.ScanManager: handling starting scan
,08-22 18:31:02.825  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:02.825  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:02.825  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 18:31:02.825  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:31:02.825  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6572630 removed from the list
08-22 18:31:02.825  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:02.825  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9de12a9 removed from the list
,08-22 18:31:02.826  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:02.826  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:31:02.827  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:02.827  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-22 18:31:02.827  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:02.827  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 18:31:02.828  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:02.828  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:02.828  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:02.828  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9de12a9 not in the list
,08-22 18:31:02.828  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 18:31:02.828  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-22 18:31:02.828  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 18:31:02.828  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 18:31:02.828  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-22 18:31:02.828  3902  3952 D BluetoothAdapter: STATE_ON
08-22 18:31:02.829  4243  4253 D BtGatt.GattService: stopScan() - queue size =1
08-22 18:31:02.829  4243  4259 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-22 18:31:02.829  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:31:02.829  4243  4262 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-22 18:31:02.830  4243  4254 D BtGatt.GattService: unregisterClient() - clientIf=5
08-22 18:31:02.830  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-22 18:31:02.830  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 18:31:02.830  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-22 18:31:02.830  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 18:31:02.830  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-22 18:31:02.831  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 18:31:02.831  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 18:31:02.831  3902  3952 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-22 18:31:02.831  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 18:31:02.831  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:02.832  3902  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:31:02.832  3902  3902 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 18:31:02.832  3902  3902 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 18:31:02.833  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:02.833  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:02.833  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:02.833  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@340755c removed from the list
08-22 18:31:02.833  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:02.833  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:02.833  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:31:02.833  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:31:02.833  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@81d67cf removed from the list
08-22 18:31:02.833  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-22 18:31:02.833  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:31:02.833  4243  4262 D BtGatt.ScanManager: Starting BLE batch scan
08-22 18:31:02.833  4243  4262 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-22 18:31:02.834  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:31:02.834  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8b48 added. We now have 2 listener(s)
08-22 18:31:02.835  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 18:31:02.835  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 18:31:02.835  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:31:02.835  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:31:02.835  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e46de1 added. We now have 9 listener(s)
,08-22 18:31:02.835  3902  3952 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:31:02.836  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 18:31:02.838  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 18:31:02.840  4243  4259 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-22 18:31:02.840  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:31:02.841  3902  3952 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:31:02.841  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:02.841  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:31:02.841  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:31:02.841  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:31:02.841  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:31:02.841  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:31:02.841  3902  3952 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 18:31:02.842  3902  3952 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 18:31:02.843  3902  3952 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 18:31:02.843  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:31:02.843  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@50881c7 added. We now have 3 listener(s)
08-22 18:31:02.844  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-22 18:31:02.844  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 18:31:02.844  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:31:02.846  3902  3902 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:31:02.846  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 18:31:02.846  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:31:02.846  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:31:02.846  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 18:31:02.847  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31413f4 added. We now have 10 listener(s)
08-22 18:31:02.847  3902  3952 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:31:02.847  3902  3952 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 18:31:02.847  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:02.847  3902  3952 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:31:02.847  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:02.847  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:02.847  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 18:31:02.847  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:31:02.847  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8b48 removed from the list
08-22 18:31:02.847  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:02.847  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e46de1 removed from the list
08-22 18:31:02.847  3902  3952 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 18:31:02.848  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:02.848  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:02.848  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:02.848  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-22 18:31:02.848  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:31:02.848  4243  4262 D BtGatt.ScanManager: stopping BLe Batch
,08-22 18:31:02.849  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:02.849  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:02.849  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:02.849  3902  3952 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e46de1 not in the list
08-22 18:31:02.849  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:02.849  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:31:02.850  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:02.850  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:02.850  3902  3952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 18:31:02.850  3902  3952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31413f4 removed from the list
08-22 18:31:02.850  3902  3952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:02.850  3902  3952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:02.850  3902  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:02.850  3902  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:31:02.850  3902  3952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@50881c7 removed from the list
08-22 18:31:02.851  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-22 18:31:02.851  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-22 18:31:02.851  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-22 18:31:02.851  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 18:31:02.851  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-22 18:31:02.851  3902  3952 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-22 18:31:02.853  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-22 18:31:02.853  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 18:31:02.853  4243  4262 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-22 18:31:02.856  3902  4326 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 458, name: My test thread name)
,08-22 18:31:02.856  3902  4326 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 458, thread name: My test thread name)
08-22 18:31:02.856  3902  4326 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 458, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-22 18:31:02.857  4243  4259 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-22 18:31:02.857  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 18:31:02.858  3902  4327 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 460, name: My test thread name)
,08-22 18:31:02.858  3902  4327 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 460, thread name: My test thread name)
08-22 18:31:02.858  3902  4327 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 460, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-22 18:31:02.860  3902  3952 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-22 18:31:02.860  3902  3952 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-22 18:31:02.860  3902  3952 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-22 18:31:02.860  3902  3952 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-22 18:31:02.860  3902  3952 D com.test.thalitest.ThaliTestRunner: Total duration: 22926 ms
08-22 18:31:02.861  3902  3952 I jxcore-log: Total number of executed tests:  80
08-22 18:31:02.861  3902  3952 I jxcore-log: 
,08-22 18:31:02.861  3902  3952 I jxcore-log: Number of passed tests:  80
08-22 18:31:02.861  3902  3952 I jxcore-log: 
08-22 18:31:02.862  3902  3952 I jxcore-log: Number of failed tests:  0
08-22 18:31:02.862  3902  3952 I jxcore-log: 
08-22 18:31:02.862  3902  3952 I jxcore-log: Number of ignored tests:  0
08-22 18:31:02.862  3902  3952 I jxcore-log: 
08-22 18:31:02.862  3902  3952 I jxcore-log: Total duration:  22926
08-22 18:31:02.862  3902  3952 I jxcore-log: 
,08-22 18:31:02.862  3902  3952 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-22 18:31:02.862  3902  3952 I jxcore-log: 
,08-22 18:31:02.865  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:31:02.865  3902  3952 I jxcore-log: 
08-22 18:31:02.867  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:31:02.867  3902  3952 I jxcore-log: 
08-22 18:31:02.868  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:31:02.868  3902  3952 I jxcore-log: 
08-22 18:31:02.869  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:31:02.869  3902  3952 I jxcore-log: 
08-22 18:31:02.870  3902  3902 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-22 18:31:02.870  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:31:02.870  3902  3952 I jxcore-log: 
08-22 18:31:02.871  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:31:02.871  3902  3952 I jxcore-log: 
08-22 18:31:02.873  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:31:02.873  3902  3952 I jxcore-log: 
,08-22 18:31:02.874  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 18:31:02.874  3902  3952 I jxcore-log: 
08-22 18:31:02.875  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 18:31:02.875  3902  3952 I jxcore-log: 
08-22 18:31:02.876  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 18:31:02.876  3902  3952 I jxcore-log: 
08-22 18:31:02.877  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-22 18:31:02.877  3902  3952 I jxcore-log: 
08-22 18:31:02.877  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-22 18:31:02.877  3902  3952 I jxcore-log: 
,08-22 18:31:02.878  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:31:02.878  3902  3952 I jxcore-log: 
08-22 18:31:02.879  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:31:02.879  3902  3952 I jxcore-log: 
08-22 18:31:02.880  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 18:31:02.880  3902  3952 I jxcore-log: 
08-22 18:31:02.880  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 18:31:02.880  3902  3952 I jxcore-log: 
,08-22 18:31:02.881  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 18:31:02.881  3902  3952 I jxcore-log: 
,08-22 18:31:02.881  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 18:31:02.881  3902  3952 I jxcore-log: 
,08-22 18:31:02.882  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 18:31:02.882  3902  3952 I jxcore-log: 
08-22 18:31:02.883  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 18:31:02.883  3902  3952 I jxcore-log: 
,08-22 18:31:02.883  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 18:31:02.883  3902  3952 I jxcore-log: 
08-22 18:31:02.884  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 18:31:02.884  3902  3952 I jxcore-log: 
,08-22 18:31:02.884  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 18:31:02.884  3902  3952 I jxcore-log: 
,08-22 18:31:02.885  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 18:31:02.885  3902  3952 I jxcore-log: 
08-22 18:31:02.885  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:31:02.885  3902  3952 I jxcore-log: 
08-22 18:31:02.886  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:31:02.886  3902  3952 I jxcore-log: 
08-22 18:31:02.887  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:31:02.887  3902  3952 I jxcore-log: 
,08-22 18:31:02.887  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:31:02.887  3902  3952 I jxcore-log: 
08-22 18:31:02.888  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:31:02.888  3902  3952 I jxcore-log: 
08-22 18:31:02.888  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:31:02.888  3902  3952 I jxcore-log: 
,08-22 18:31:03.190  3902  3902 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-22 18:31:03.194  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 18:31:03.194  3902  3952 I jxcore-log: 
,08-22 18:31:03.279  3902  3902 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-22 18:31:03.282  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 18:31:03.282  3902  3952 I jxcore-log: 
,08-22 18:31:03.333  3902  3902 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-22 18:31:03.338  3902  3952 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 18:31:03.338  3902  3952 I jxcore-log: 
,08-22 18:31:03.512  4328  4328 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-22 18:31:03.517  4328  4328 D AndroidRuntime: CheckJNI is OFF
,08-22 18:31:03.559  4328  4328 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-22 18:31:03.607  4328  4328 I Radio-JNI: register_android_hardware_Radio DONE
,08-22 18:31:03.629  4328  4328 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-22 18:31:03.640   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-22 18:31:03.641   874   887 I ActivityManager: Killing 3902:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-22 18:31:03.723   874  1399 D GraphicsStats: Buffer count: 2
,08-22 18:31:03.723   874  1399 I WindowState: WIN DEATH: Window{da6d010 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-22 18:31:03.724   874  1317 D WifiService: Client connection lost with reason: 4
,08-22 18:31:03.734   874   897 W PackageSettings: Skipping PackageSetting{29940c7 com.example.hello/10273} due to missing metadata
,08-22 18:31:03.742   874   887 W ActivityManager: Force removing ActivityRecord{640a3f1 u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
,08-22 18:31:03.769   874   897 I art     : Starting a blocking GC Explicit
,08-22 18:31:03.782   874  1920 W ActivityManager: Spurious death for ProcessRecord{9de12a9 0:com.test.thalitest/u0a0}, curProc for 3902: null
,08-22 18:31:03.814   874   897 I art     : Explicit concurrent mark sweep GC freed 15402(1014KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 896us total 43.242ms
,08-22 18:31:03.825   874  1399 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3902 uid 10000
08-22 18:31:03.827  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-22 18:31:03.836   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-22 18:31:03.838  4328  4328 I art     : System.exit called, status: 0
,08-22 18:31:03.838  4328  4328 I AndroidRuntime: VM exiting with result code 0.
,08-22 18:31:03.858   874   897 I ActivityManager: Start proc 4339:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-22 18:31:03.859   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-22 18:31:03.882  4243  4243 D BluetoothMapAppObserver: onReceive
,08-22 18:31:03.882  4243  4243 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-22 18:31:03.885  2157  2264 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-22 18:31:03.886  3725  3725 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) },
,08-22 18:31:03.906  1993  1993 W ThreadPoolDumper: Queue length for executor AudioRouter with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,08-22 18:31:03.907  1863  1863 I Keyboard.Facilitator: resetDictionaries() : en_US
08-22 18:31:03.909  1863  4355 I Keyboard.Facilitator.DecoderInitializer: run()
08-22 18:31:03.911  1863  4355 I Decoder : createOrResetDecoder
,08-22 18:31:03.931   874  1306 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-22 18:31:03.953  1921  1921 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-22 18:31:03.960   874  1314 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-22 18:31:03.975   874   884 I ActivityManager: Start proc 4357:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver,
,08-22 18:31:03.979   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-22 18:31:03.979  1529  1529 I ConfigService: onCreate
,08-22 18:31:03.987  1529  4362 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-22 18:31:03.987  1529  4362 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 18:31:03.987  1529  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 18:31:03.987  1529  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 18:31:03.987  1529  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 18:31:03.987  1529  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 18:31:03.987  1529  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 18:31:03.987  1529  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 18:31:03.987  1529  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 18:31:03.987  1529  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 18:31:03.987  1529  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 18:31:03.987  1529  4362 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 18:31:03.987  1529  4362 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 18:31:03.987  1529  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 18:31:03.987  1529  4362 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-22 18:31:03.987  1529  4362 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-22 18:31:03.987  1529  4362 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-22 18:31:03.987  1529  4362 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-22 18:31:03.987  1529  4362 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-22 18:31:03.987  1529  4362 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 18:31:03.987  1529  4362 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 18:31:03.987  1529  4362 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 18:31:03.987  1529  4362 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 18:31:03.987  1529  4362 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 18:31:03.987  1529  4362 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 18:31:03.987  1529  4362 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 18:31:03.987  1529  4362 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 18:31:03.987  1529  4362 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 18:31:03.987  1529  4362 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 18:31:03.987  1529  4362 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 18:31:03.987  1529  4362 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 18:31:03.987  1529  4362 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 18:31:03.987  1529  4362 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-22 18:31:03.987  1529  4362 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-22 18:31:03.987  1529  4362 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-22 18:31:03.987  1529  4362 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-22 18:31:03.988  1529  4362 W SQLiteOpenHelper: Opened config.db in read-only mode
08-22 18:31:03.995  1529  4352 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-22 18:31:03.996  1529  4352 E ClearcutLoggerIntentService: disk I/O error (code 3850)
08-22 18:31:03.996  1529  4352 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-22 18:31:03.996  1529  4352 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-22 18:31:03.996  1529  4352 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-22 18:31:03.996  1529  4352 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-22 18:31:03.996  1529  4352 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-22 18:31:03.996  1529  4352 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-22 18:31:03.996  1529  4352 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-22 18:31:03.996  1529  4352 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-22 18:31:03.996  1529  4352 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-22 18:31:03.996  1529  4352 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-22 18:31:03.996  1529  4352 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-22 18:31:03.996  1529  4352 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-22 18:31:03.996  1529  4352 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-22 18:31:03.996  1529  4352 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,08-22 18:31:04.013  1993  4370 I MicroRecognitionRnrImpl: Starting detection.
,08-22 18:31:04.016  1993  4371 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@3252172
,08-22 18:31:04.017   376  4373 I AudioFlinger: AudioFlinger's thread 0xb1bc0000 ready to run
,08-22 18:31:04.021   376  1286 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-22 18:31:04.022  1993  4371 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@3252172
08-22 18:31:04.024  1863  4355 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-22 18:31:04.032   376  4373 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
08-22 18:31:04.032   376  4373 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
08-22 18:31:04.032   376  4373 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
08-22 18:31:04.037  1938  2034 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-22 18:31:04.038   376  4373 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
08-22 18:31:04.042   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-22 18:31:04.043   874   886 E PackageManager: Failed to write settings, restoring backup
08-22 18:31:04.043   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-22 18:31:04.043   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-22 18:31:04.043   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-22 18:31:04.043   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-22 18:31:04.043   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-22 18:31:04.043   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:31:04.043   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-22 18:31:04.043   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-22 18:31:04.047   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-22 18:31:04.047   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-22 18:31:04.047   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-22 18:31:04.047   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 18:31:04.047   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 18:31:04.047   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 18:31:04.047   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-22 18:31:04.047   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-22 18:31:04.047   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-22 18:31:04.047   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-22 18:31:04.047   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-22 18:31:04.047   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-22 18:31:04.047   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-22 18:31:04.047   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-22 18:31:04.047   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-22 18:31:04.047   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-22 18:31:04.047   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 18:31:04.047   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 18:31:04.047   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 18:31:04.047   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 18:31:04.047   874   887 E DropBoxManagerService: 	... 13 more
08-22 18:31:04.050   874  1926 I ActivityManager: Start proc 4375:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-22 18:31:04.050  1938  2034 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-22 18:31:04.050  1938  2034 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1938
08-22 18:31:04.050  1938  2034 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-22 18:31:04.050  1938  2034 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-22 18:31:04.050  1938  2034 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-22 18:31:04.050  1938  2034 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-22 18:31:04.050  1938  2034 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-22 18:31:04.050  1938  2034 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-22 18:31:04.050  1938  2034 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-22 18:31:04.050  1938  2034 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-22 18:31:04.050  1938  2034 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-22 18:31:04.050  1938  2034 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-22 18:31:04.050  1938  2034 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-22 18:31:04.050  1938  2034 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-22 18:31:04.052   874  1920 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-22 18:31:04.053   874  4381 E DropBoxManagerService: Can't write: system_app_crash
08-22 18:31:04.053   874  4381 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-22 18:31:04.053   874  4381 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-22 18:31:04.053   874  4381 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 18:31:04.053   874  4381 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 18:31:04.053   874  4381 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 18:31:04.053   874  4381 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-22 18:31:04.053   874  4381 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-22 18:31:04.053   874  4381 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 18:31:04.053   874  4381 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 18:31:04.053   874  4381 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 18:31:04.053   874  4381 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 18:31:04.053   874  4381 E DropBoxManagerService: 	... 5 more
08-22 18:31:04.055  1993  2003 W SearchService: Abort, client detached.
08-22 18:31:04.059  1993  1993 I HotwordDetector: Closing mic
08-22 18:31:04.059  1993  2305 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@3252172
08-22 18:31:04.059  1993  4371 E AudioRecord-JNI: Error -4 during AudioRecord native read
,08-22 18:31:04.069   874  4388 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-22 18:31:04.076  1993  4389 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,08-22 18:31:04.106   874  4388 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-22 18:31:04.106   874  4388 I Adreno  : Build Date                       : 10/20/15
08-22 18:31:04.106   874  4388 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-22 18:31:04.106   874  4388 I Adreno  : Local Branch                     : M14
08-22 18:31:04.106   874  4388 I Adreno  : Remote Branch                    : 
08-22 18:31:04.106   874  4388 I Adreno  : Remote Branch                    : 
08-22 18:31:04.106   874  4388 I Adreno  : Reconstruct Branch               : 
,08-22 18:31:04.110   874  4388 I OpenGLRenderer: Initialized EGL, version 1.4
,08-22 18:31:04.153  4357  4357 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-22 18:31:04.156   376  4373 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,08-22 18:31:04.157   376  4373 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
,08-22 18:31:04.160   376  1286 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-22 18:31:04.160  1993  2312 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-22 18:31:04.161  1993  4370 I MicroRecognitionRnrImpl: Detection finished
,08-22 18:31:04.167  1863  4355 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-22 18:31:04.170  1863  4355 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-22 18:31:04.171  1863  4355 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-22 18:31:04.175  1863  4355 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-22 18:31:04.175  1863  4355 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-22 18:31:04.178  1863  4355 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-22 18:31:04.178  1863  4355 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-22 18:31:04.181  1863  4355 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-22 18:31:04.181  1863  4355 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-22 18:31:04.183  1863  4355 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-22 18:31:04.184  1863  4355 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-22 18:31:04.184  1863  4355 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-22 18:31:04.184  1863  4355 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-22 18:31:04.219  1749  4396 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-22 18:31:04.220  1749  4396 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-22 18:31:04.232  4357  4357 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-22 18:31:04.245  4357  4400 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-22 18:31:04.248   874  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-22 18:31:04.255   874  4308 I ActivityManager: Start proc 4401:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-22 18:31:04.261  4357  4398 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-22 18:31:04.261  4357  4398 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 18:31:04.261  4357  4398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 18:31:04.261  4357  4398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 18:31:04.261  4357  4398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 18:31:04.261  4357  4398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 18:31:04.261  4357  4398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 18:31:04.261  4357  4398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 18:31:04.261  4357  4398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 18:31:04.261  4357  4398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 18:31:04.261  4357  4398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 18:31:04.261  4357  4398 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 18:31:04.261  4357  4398 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 18:31:04.261  4357  4398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 18:31:04.261  4357  4398 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-22 18:31:04.261  4357  4398 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-22 18:31:04.261  4357  4398 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-22 18:31:04.261  4357  4398 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-22 18:31:04.261  4357  4398 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-22 18:31:04.261  4357  4398 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:31:04.261  4357  4398 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-22 18:31:04.261  4357  4398 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-22 18:31:04.261  4357  4398 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-22 18:31:04.261  4357  4398 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 18:31:04.261  4357  4398 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 18:31:04.261  4357  4398 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 18:31:04.261  4357  4398 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 18:31:04.261  4357  4398 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 18:31:04.261  4357  4398 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 18:31:04.261  4357  4398 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 18:31:04.261  4357  4398 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 18:31:04.261  4357  4398 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 18:31:04.261  4357  4398 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 18:31:04.261  4357  4398 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 18:31:04.261  4357  4398 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 18:31:04.261  4357  4398 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 18:31:04.261  4357  4398 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-22 18:31:04.261  4357  4398 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-22 18:31:04.261  4357  4398 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-22 18:31:04.261  4357  4398 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-22 18:31:04.261  4357  4398 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-22 18:31:04.261  4357  4398 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:31:04.261  4357  4398 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-22 18:31:04.261  4357  4398 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-22 18:31:04.283  4401  4401 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-22 18:31:04.304  1529  1529 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-22 18:31:04.305  1529  1529 D AndroidRuntime: Shutting down VM
,08-22 18:31:04.307  1529  1529 E AndroidRuntime: FATAL EXCEPTION: main
08-22 18:31:04.307  1529  1529 E AndroidRuntime: Process: com.google.process.gapps, PID: 1529
08-22 18:31:04.307  1529  1529 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-22 18:31:04.307  1529  1529 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-22 18:31:04.307  1529  1529 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-22 18:31:04.307  1529  1529 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-22 18:31:04.307  1529  1529 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:31:04.307  1529  1529 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-22 18:31:04.307  1529  1529 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 18:31:04.307  1529  1529 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:31:04.307  1529  1529 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 18:31:04.307  1529  1529 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 18:31:04.307  1529  1529 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-22 18:31:04.307  1529  1529 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-22 18:31:04.307  1529  1529 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-22 18:31:04.307  1529  1529 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-22 18:31:04.307  1529  1529 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-22 18:31:04.307  1529  1529 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-22 18:31:04.307  1529  1529 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-22 18:31:04.307  1529  1529 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-22 18:31:04.307  1529  1529 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-22 18:31:04.307  1529  1529 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-22 18:31:04.307  1529  1529 E AndroidRuntime: 	... 8 more
,08-22 18:31:04.311   874  4416 E DropBoxManagerService: Can't write: system_app_crash
08-22 18:31:04.311   874  4416 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-22 18:31:04.311   874  4416 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-22 18:31:04.311   874  4416 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 18:31:04.311   874  4416 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 18:31:04.311   874  4416 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 18:31:04.311   874  4416 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-22 18:31:04.311   874  4416 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-22 18:31:04.311   874  4416 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 18:31:04.311   874  4416 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 18:31:04.311   874  4416 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 18:31:04.311   874  4416 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 18:31:04.311   874  4416 E DropBoxManagerService: 	... 5 more
,08-22 18:31:04.328  4357  4398 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-22 18:31:04.335  4357  4400 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-22 18:31:04.335  4357  4400 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-22 18:31:04.336  4357  4400 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-22 18:31:04.336  4357  4400 E AndroidRuntime: Process: android.process.acore, PID: 4357
08-22 18:31:04.336  4357  4400 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 18:31:04.336  4357  4400 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 18:31:04.336  4357  4400 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 18:31:04.336  4357  4400 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 18:31:04.336  4357  4400 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 18:31:04.336  4357  4400 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 18:31:04.336  4357  4400 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 18:31:04.336  4357  4400 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 18:31:04.336  4357  4400 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 18:31:04.336  4357  4400 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 18:31:04.336  4357  4400 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 18:31:04.336  4357  4400 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 18:31:04.336  4357  4400 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 18:31:04.336  4357  4400 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 18:31:04.336  4357  4400 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-22 18:31:04.336  4357  4400 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-22 18:31:04.336  4357  4400 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-22 18:31:04.336  4357  4400 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-22 18:31:04.336  4357  4400 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-22 18:31:04.336  4357  4400 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-22 18:31:04.336  4357  4400 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-22 18:31:04.336  4357  4400 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:31:04.336  4357  4400 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-22 18:31:04.336  4357  4400 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-22 18:31:04.338  4357  4398 I Process : Sending signal. PID: 4357 SIG: 9
,08-22 18:31:04.339   874  4417 E DropBoxManagerService: Can't write: system_app_crash
08-22 18:31:04.339   874  4417 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-22 18:31:04.339   874  4417 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-22 18:31:04.339   874  4417 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 18:31:04.339   874  4417 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 18:31:04.339   874  4417 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 18:31:04.339   874  4417 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-22 18:31:04.339   874  4417 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-22 18:31:04.339   874  4417 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 18:31:04.339   874  4417 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 18:31:04.339   874  4417 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 18:31:04.339   874  4417 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 18:31:04.339   874  4417 E DropBoxManagerService: 	... 5 more
,08-22 18:31:04.353   283   283 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,08-22 18:31:04.354   283   283 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
08-22 18:31:04.354   283   283 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
,08-22 18:31:04.354   283   283 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
08-22 18:31:04.354   283   283 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-22 18:31:04.354   283   283 E qdoverlay: MdpCtrl close error in unset
,08-22 18:31:04.388   874   885 I ActivityManager: Process android.process.acore (pid 4357) has died
,08-22 18:31:04.389   874   885 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-22 18:31:04.403   874  1316 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 13 -> obsolete
,08-22 18:31:04.615   283   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-22 18:31:04.615   283   283 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-22 18:31:04.615   283   283 E qdoverlay: MdpCtrl close error in unset

```
