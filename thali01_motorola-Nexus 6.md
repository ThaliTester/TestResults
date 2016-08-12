#### Test 797638300d10dad_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-12 15:11:05.327  3685  3697 D Finsky  : [309] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
08-12 15:11:05.341  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-12 15:11:05.349  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-12 15:11:05.351  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-12 15:11:05.391  1501  2270 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-12 15:11:05.392  1501  2270 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-12 15:11:05.392  1501  2270 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 15:11:05.392  1501  2270 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-12 15:11:05.433  3685  3697 D Finsky  : [309] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-12 15:11:06.339  3934  3934 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 15:11:06.345  3934  3934 D AndroidRuntime: CheckJNI is OFF
08-12 15:11:06.390  3934  3934 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-12 15:11:06.441  3934  3934 I Radio-JNI: register_android_hardware_Radio DONE
08-12 15:11:06.464  3934  3934 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 15:11:06.470   874  1957 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 15:11:06.512  1991  2384 W SearchService: Abort, client detached.
08-12 15:11:06.518  3934  3934 D AndroidRuntime: Shutting down VM
08-12 15:11:06.523  1991  1991 I HotwordDetector: Closing mic
08-12 15:11:06.524  1991  2331 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@a67e309
08-12 15:11:06.525  1991  2348 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-12 15:11:06.537   874  1954 I ActivityManager: Start proc 3943:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-12 15:11:06.576   377  2350 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-12 15:11:06.577   377  2350 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-12 15:11:06.582   377  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-12 15:11:06.584  1991  2345 I MicroRecognitionRnrImpl: Detection finished
08-12 15:11:06.585  1991  2334 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-12 15:11:06.628  3943  3943 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-12 15:11:06.649  3943  3943 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-12 15:11:06.655  3943  3943 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 87-90)
08-12 15:11:06.655  3943  3943 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 15:11:06.667  3943  3943 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {94275f3}
08-12 15:11:06.667  3943  3943 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 15:11:06.667  3943  3943 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 15:11:06.673  3943  3943 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-12 15:11:06.674  3943  3943 E SysUtils: ApplicationContext is null in ApplicationStatus
08-12 15:11:06.687  3943  3943 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-12 15:11:06.697  3943  3943 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 15:11:06.698  3943  3943 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 15:11:06.698  3943  3943 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 15:11:06.698  3943  3943 I Adreno  : Build Date                       : 10/20/15
08-12 15:11:06.698  3943  3943 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 15:11:06.698  3943  3943 I Adreno  : Local Branch                     : M14
08-12 15:11:06.698  3943  3943 I Adreno  : Remote Branch                    : 
08-12 15:11:06.698  3943  3943 I Adreno  : Remote Branch                    : 
08-12 15:11:06.698  3943  3943 I Adreno  : Reconstruct Branch               : 
08-12 15:11:06.761   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c62f909:true
,08-12 15:11:06.831  3943  3943 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-12 15:11:06.847  3943  3943 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-12 15:11:06.923  3943  3981 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-12 15:11:06.933  3943  3968 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-12 15:11:06.973  3943  3981 I OpenGLRenderer: Initialized EGL, version 1.4
,08-12 15:11:07.036   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +515ms
,08-12 15:11:07.041  1862  1862 I Keyboard.Facilitator: onFinishInput()
,08-12 15:11:07.093  3943  3943 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3943
,08-12 15:11:07.204  3943  3943 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 15:11:07.340   874  1955 I ActivityManager: Killing 3183:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,08-12 15:11:07.354  3943  3983 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1680410320
,08-12 15:11:07.359  3943  3983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 15:11:07.359  3943  3983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 15:11:07.359  3943  3983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 15:11:07.359  3943  3983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 15:11:07.359  3943  3983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-12 15:11:07.359  3943  3983 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14e1a46 added. We now have 1 listener(s)
,08-12 15:11:07.362  3943  3983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-12 15:11:07.363  3943  3983 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-12 15:11:07.364  3943  3983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 15:11:07.364  3943  3983 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 15:11:07.367  3943  3983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 15:11:07.367  3943  3983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 15:11:07.367  3943  3983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 15:11:07.367  3943  3983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-12 15:11:07.367  3943  3983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 15:11:07.367  3943  3983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 15:11:07.367  3943  3983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 15:11:07.367  3943  3983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 15:11:07.367  3943  3983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 15:11:07.367  3943  3983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 15:11:07.367  3943  3983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 15:11:07.367  3943  3983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 15:11:07.367  3943  3983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 15:11:07.367  3943  3983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-12 15:11:07.367  3943  3983 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b6235d added. We now have 1 listener(s)
08-12 15:11:07.367  3943  3983 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 15:11:07.370   874  1310 D WifiService: New client listening to asynchronous messages,
08-12 15:11:07.371  3943  3983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 15:11:07.371  3943  3983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-12 15:11:07.371  3943  3983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 15:11:07.371  3943  3983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 15:11:07.371  3943  3983 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-12 15:11:07.397   874  1955 I ActivityManager: Killing 3259:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-12 15:11:07.435  3943  3983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 15:11:07.435  3943  3983 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-12 15:11:07.448  3943  3983 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-12 15:11:07.449  3943  3983 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 15:11:07.449  3943  3983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 15:11:07.449  3943  3983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 15:11:07.449  3943  3983 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 15:11:07.449  3943  3983 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 15:11:07.449  3943  3983 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 15:11:07.449  3943  3983 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 15:11:07.449  3943  3983 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 15:11:07.449  3943  3983 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-12 15:11:07.450  3943  3983 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 15:11:07.453  3943  3983 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 15:11:07.453  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 15:11:07.454  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 15:11:07.642  3943  3943 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 15:11:08.225  3943  3991 W jxcore-log: Initializing JXcore engine
,08-12 15:11:08.226  3943  3991 W jxcore-log: JXcore engine is ready
,08-12 15:11:08.265  3991  3991 W Thread-361: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-12 15:11:08.265  3991  3991 W Thread-361: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[11991]" dev="sockfs" ino=11991 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-12 15:11:08.265  3991  3991 W Thread-361: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-12 15:11:08.265  3991  3991 W Thread-361: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[25572]" dev="sockfs" ino=25572 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-12 15:11:08.285  3943  3991 W jxcore-log: Starting JXcore engine
,08-12 15:11:08.378  3943  3991 W jxcore-log: Platform android
08-12 15:11:08.378  3943  3991 W jxcore-log: 
,08-12 15:11:08.378  3943  3991 W jxcore-log: Process ARCH arm
08-12 15:11:08.378  3943  3991 W jxcore-log: 
,08-12 15:11:08.596  3943  3991 I jxcore-log: JXcore Cordova bridge is ready!
08-12 15:11:08.596  3943  3991 I jxcore-log: 
,08-12 15:11:08.596  3943  3991 W jxcore-log: JXcore engine is started
,08-12 15:11:08.609  3943  3983 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 15:11:08.619  3943  3943 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 15:11:16.791  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 15:11:16.796  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 15:11:16.797  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 15:11:16.816  1501  2270 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-12 15:11:16.816  1501  2270 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 15:11:16.816  1501  2270 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 15:11:16.816  1501  2270 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 15:11:16.829  3685  3685 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 15:11:16.829  3685  3685 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-12 15:11:16.829  3685  3685 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-12 15:11:18.905  3943  3991 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 15:11:18.905  3943  3991 I jxcore-log: 
,08-12 15:11:18.907  3943  3991 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 15:11:18.907  3943  3991 I jxcore-log: 
,08-12 15:11:18.922  3943  3991 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 15:11:18.922  3943  3991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 15:11:18.922  3943  3991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 15:11:18.922  3943  3991 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 15:11:18.922  3943  3991 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 15:11:18.922  3943  3991 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 15:11:18.922  3943  3991 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 15:11:18.922  3943  3991 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 15:11:18.927  3943  3991 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 15:11:18.929  3943  3991 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 15:11:18.929  3943  3991 I jxcore-log: 
08-12 15:11:18.931  3943  3991 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 15:11:18.931  3943  3991 I jxcore-log: 
,08-12 15:11:19.275  3943  3991 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
,08-12 15:11:19.276  3943  3991 I jxcore-log: Failed to execute UT.
08-12 15:11:19.276  3943  3991 I jxcore-log: 
,08-12 15:11:19.276  3943  3991 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 15:11:19.276  3943  3991 I jxcore-log: 
08-12 15:11:19.279  3943  3991 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 15:11:19.279  3943  3991 I jxcore-log: 
,08-12 15:11:19.306  3943  3943 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 15:11:19.897   874  1309 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-12 15:11:19.901  4003  4003 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-12 15:11:19.906  4003  4003 D AndroidRuntime: CheckJNI is OFF
,08-12 15:11:19.943  4003  4003 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-12 15:11:19.985  4003  4003 I Radio-JNI: register_android_hardware_Radio DONE
,08-12 15:11:20.005  4003  4003 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 15:11:20.017   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-12 15:11:20.017   874   887 I ActivityManager: Killing 3943:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-12 15:11:20.111   874  1954 D GraphicsStats: Buffer count: 2,
08-12 15:11:20.111   874   884 I WindowState: WIN DEATH: Window{bbf3679 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 15:11:20.112   874  1310 D WifiService: Client connection lost with reason: 4
,08-12 15:11:20.161   874   887 W ActivityManager: Force removing ActivityRecord{7a8a086 u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
08-12 15:11:20.163   874   897 W PackageSettings: Skipping PackageSetting{b85007e com.example.hello/10273} due to missing metadata
,08-12 15:11:20.191   874   897 I art     : Starting a blocking GC Explicit
,08-12 15:11:20.200   874  1728 W ActivityManager: Spurious death for ProcessRecord{583751e 0:com.test.thalitest/u0a0}, curProc for 3943: null
,08-12 15:11:20.223   874  1727 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3943 uid 10000
,08-12 15:11:20.224  1862  1862 I Keyboard.Facilitator: onFinishInput()
,08-12 15:11:20.260  1991  1991 W ThreadPoolDumper: Queue length for executor AudioRouter with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,08-12 15:11:20.272   874   897 I art     : Explicit concurrent mark sweep GC freed 39023(2MB) AllocSpace objects, 14(292KB) LOS objects, 33% free, 29MB/43MB, paused 1.198ms total 77.967ms
,08-12 15:11:20.298  1991  4015 I MicroRecognitionRnrImpl: Starting detection.
,08-12 15:11:20.301  1991  4016 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@157f6f1
,08-12 15:11:20.304   377  4018 I AudioFlinger: AudioFlinger's thread 0xb3380000 ready to run
,08-12 15:11:20.306   377  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-12 15:11:20.307  1991  4016 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@157f6f1
,08-12 15:11:20.315   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-12 15:11:20.317   377  4018 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
08-12 15:11:20.317   377  4018 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
,08-12 15:11:20.318   377  4018 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,08-12 15:11:20.321  4003  4003 I art     : System.exit called, status: 0
08-12 15:11:20.321  4003  4003 I AndroidRuntime: VM exiting with result code 0.
,08-12 15:11:20.324   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-12 15:11:20.325   377  4018 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,08-12 15:11:20.356  2674  2674 D BluetoothMapAppObserver: onReceive
,08-12 15:11:20.357  2674  2674 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-12 15:11:20.357   874  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-12 15:11:20.357  2052  2274 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 15:11:20.363  3786  3786 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-12 15:11:20.364  1862  1862 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-12 15:11:20.373  1862  4022 I Keyboard.Facilitator.DecoderInitializer: run()
,08-12 15:11:20.377  1862  4022 I Decoder : createOrResetDecoder
,08-12 15:11:20.400  1991  1991 I HotwordWorkerImpl: onReady
,08-12 15:11:20.403  1926  1926 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-12 15:11:20.430  1501  1501 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
08-12 15:11:20.430  1501  1501 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-12 15:11:20.452  1501  1501 I ConfigService: onCreate
,08-12 15:11:20.454  1714  4028 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-12 15:11:20.455  1714  4028 D AccountUtils: Clearing selected account for com.test.thalitest
,08-12 15:11:20.460   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-12 15:11:20.463  3223  4026 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-12 15:11:20.466  1714  4028 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-12 15:11:20.473  1714  1714 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-12 15:11:20.473  1714  1714 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-12 15:11:20.474  1714  4033 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-12 15:11:20.475  1714  4033 E DriveAsyncService: disk I/O error (code 3850)
08-12 15:11:20.475  1714  4033 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 15:11:20.475  1714  4033 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 15:11:20.475  1714  4033 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-12 15:11:20.475  1714  4033 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 15:11:20.475  1714  4033 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 15:11:20.475  1714  4033 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 15:11:20.475  1714  4033 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-12 15:11:20.475  1714  4033 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(SourceFile:483)
08-12 15:11:20.475  1714  4033 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:458)
08-12 15:11:20.475  1714  4033 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(SourceFile:1501)
08-12 15:11:20.475  1714  4033 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bj.a(SourceFile:16)
08-12 15:11:20.475  1714  4033 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-12 15:11:20.475  1714  4033 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 15:11:20.475  1714  4033 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 15:11:20.475  1714  4033 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
08-12 15:11:20.476  1714  4028 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-12 15:11:20.476  1714  4028 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 15:11:20.476  1714  4028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 15:11:20.476  1714  4028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 15:11:20.476  1714  4028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 15:11:20.476  1714  4028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 15:11:20.476  1714  4028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 15:11:20.476  1714  4028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 15:11:20.476  1714  4028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 15:11:20.476  1714  4028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 15:11:20.476  1714  4028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 15:11:20.476  1714  4028 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 15:11:20.476  1714  4028 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 15:11:20.476  1714  4028 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 15:11:20.476  1714  4028 E SQLiteDatabase: 	at, android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 15:11:20.476  1714  4028 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-12 15:11:20.476  1714  4028 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-12 15:11:20.476  1714  4028 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 15:11:20.476  1714  4028 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 15:11:20.476  1714  4028 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-12 15:11:20.476  1714  4028 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 15:11:20.476  1714  4028 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-12 15:11:20.476  1714  4028 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 15:11:20.476  1714  4028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 15:11:20.476  1714  4028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 15:11:20.476  1714  4028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 15:11:20.476  1714  4028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 15:11:20.476  1714  4028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 15:11:20.476  1714  4028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 15:11:20.476  1714  4028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 15:11:20.476  1714  4028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 15:11:20.476  1714  4028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 15:11:20.476  1714  4028 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 15:11:20.476  1714  4028 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 15:11:20.476  1714  4028 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 15:11:20.476  1714  4028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 15:11:20.476  1714  4028 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-12 15:11:20.476  1714  4028 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-12 15:11:20.476  1714  4028 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 15:11:20.476  1714  4028 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 15:11:20.476  1714  4028 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-12 15:11:20.476  1714  4028 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 15:11:20.477  1714  4028 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
08-12 15:11:20.478  1714  4034 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
08-12 15:11:20.478  1714  4034 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 15:11:20.478  1714  4034 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 15:11:20.478  1714  4034 E SQLi,teDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 15:11:20.478  1714  4034 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 15:11:20.478  1714  4034 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 15:11:20.478  1714  4034 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 15:11:20.478  1714  4034 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 15:11:20.478  1714  4034 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 15:11:20.478  1714  4034 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 15:11:20.478  1714  4034 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 15:11:20.478  1714  4034 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 15:11:20.478  1714  4034 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 15:11:20.478  1714  4034 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 15:11:20.478  1714  4034 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-12 15:11:20.478  1714  4034 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-12 15:11:20.478  1714  4034 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-12 15:11:20.478  1714  4034 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-12 15:11:20.478  1714  4034 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-12 15:11:20.478  1714  4034 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 15:11:20.478  1714  4034 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 15:11:20.478  1714  4034 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-12 15:11:20.478  1714  4034 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 15:11:20.478  1714  4034 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
08-12 15:11:20.478  1714  4034 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 15:11:20.478  1714  4034 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 15:11:20.478  1714  4034 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 15:11:20.478  1714  4034 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 15:11:20.478  1714  4034 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 15:11:20.478  1714  4034 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 15:11:20.478  1714  4034 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 15:11:20.478  1714  4034 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 15:11:20.478  1714  4034 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 15:11:20.478  1714  4034 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 15:11:20.478  1714  4034 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 15:11:,20.478  1714  4034 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 15:11:20.478  1714  4034 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 15:11:20.478  1714  4034 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-12 15:11:20.478  1714  4034 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-12 15:11:20.478  1714  4034 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-12 15:11:20.478  1714  4034 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-12 15:11:20.478  1714  4034 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-12 15:11:20.478  1714  4034 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 15:11:20.478  1714  4034 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 15:11:20.478  1714  4034 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-12 15:11:20.478  1714  4034 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 15:11:20.480  1714  4034 W SQLiteOpenHelper: Opened metrics.db in read-only mode
08-12 15:11:20.480  1714  4034 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
08-12 15:11:20.480  1714  4034 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
08-12 15:11:20.481  1714  4034 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
08-12 15:11:20.482  1714  4034 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
--------- beginning of crash
08-12 15:11:20.484  1714  4034 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
08-12 15:11:20.484  1714  4034 E AndroidRuntime: Process: com.google.android.gms, PID: 1714
08-12 15:11:20.484  1714  4034 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-12 15:11:20.484  1714  4034 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 15:11:20.484  1714  4034 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 15:11:20.484  1714  4034 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 15:11:20.484  1714  4034 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 15:11:20.484  1714  4034 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 15:11:20.484  1714  4034 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
08-12 15:11:20.484  1714  4034 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-12 15:11:20.484  1714  4034 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 15:11:20.484  1714  4034 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 15:11:20.484  1714  4034 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 15:11:20.484  1714  4034 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 15:11:20.489  1714  1714 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-12 15:11:20.489  1714  1714 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-12 15:11:20.490  1991  4037 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-12 15:11:20.495  1714  4039 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-12 15:11:20.495   874  4038 E DropBoxManagerService: Can't write: system_app_crash
08-12 15:11:20.495   874  4038 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop108.tmp: open failed: EROFS (Read-only file system)
08-12 15:11:20.495   874  4038 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 15:11:20.495   874  4038 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 15:11:20.495   874  4038 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 15:11:20.495   874  4038 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 15:11:20.495   874  4038 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 15:11:20.495   874  4038 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 15:11:20.495   874  4038 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 15:11:20.495   874  4038 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 15:11:20.495   874  4038 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 15:11:20.495   874  4038 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 15:11:20.495   874  4038 E DropBoxManagerService: 	... 5 more
08-12 15:11:20.496  3223  3255 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj7DD7659E0) - 
08-12 15:11:20.497  3223  3255 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
08-12 15:11:20.497  3223  3255 E AndroidRuntime: Process: android.process.acore, PID: 3223
08-12 15:11:20.497  3223  3255 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
08-12 15:11:20.497  3223  3255 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 15:11:20.497  3223  3255 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-12 15:11:20.497  3223  3255 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
08-12 15:11:20.497  3223  3255 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
08-12 15:11:20.497  3223  3255 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
08-12 15:11:20.497  3223  3255 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
08-12 15:11:20.497  3223  3255 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
08-12 15:11:20.497  3223  3255 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
08-12 15:11:20.497  3223  3255 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-12 15:11:20.497  3223  3255 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 15:11:20.497  3223  3255 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 15:11:20.497  3223  3255 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 15:11:20.506  1714  4039 I Process : Sending signal. PID: 1714 SIG: 9
08-12 15:11:20.509   874  4041 E DropBoxManagerService: Can't write: system_app_crash
08-12 15:11:20.509   874  4041 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
08-12 15:11:20.509   874  4041 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 15:11:20.509   874  4041 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 15:11:20.509   874  4041 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 15:11:20.509   874  4041 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 15:11:20.509   874  4041 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 15:11:20.509   874  4041 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 15:11:20.509   874  4041 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 15:11:20.509   874  4041 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 15:11:20.509   874  4041 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 15:11:20.509   874  4041 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 15:11:20.509   874  4041 E DropBoxManagerService: 	... 5 more
,08-12 15:11:20.523  1991  4037 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-12 15:11:20.524   874  4042 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-12 15:11:20.528  1862  4022 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-12 15:11:20.536  3223  4026 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
08-12 15:11:20.537  3223  4026 I Process : Sending signal. PID: 3223 SIG: 9
08-12 15:11:20.538   874  1953 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@d777211)
08-12 15:11:20.538   874   884 I ActivityManager: Start proc 4043:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-12 15:11:20.539   874  1953 I ActivityManager: Process com.google.android.gms (pid 1714) has died
08-12 15:11:20.539   874  1311 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-12 15:11:20.540   874  1953 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
08-12 15:11:20.540   874  1953 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
08-12 15:11:20.540   874  1953 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 11000ms
08-12 15:11:20.540   874  1311 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-12 15:11:20.540   874  1953 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 11000ms
08-12 15:11:20.540   874  1953 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 11000ms
08-12 15:11:20.541   874  1953 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 11000ms
08-12 15:11:20.541   874  1953 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 11000ms
08-12 15:11:20.541  1991  4037 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
08-12 15:11:20.542  1991  4037 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-12 15:11:20.542  1991  4037 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 1991
08-12 15:11:20.542  1991  4037 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 15:11:20.542  1991  4037 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 15:11:20.542  1991  4037 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-12 15:11:20.542  1991  4037 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 15:11:20.542  1991  4037 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 15:11:20.542  1991  4037 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 15:11:20.542  1991  4037 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-12 15:11:20.542  1991  4037 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-12 15:11:20.542  1991  4037 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-12 15:11:20.542  1991  4037 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-12 15:11:20.542  1991  4037 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-12 15:11:20.542  1991  4037 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-12 15:11:20.542  1991  4037 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-12 15:11:20.542  1991  4037 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-12 15:11:20.542  1991  4037 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-12 15:11:20.542  1991  4037 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 15:11:20.542  1991  4037 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 15:11:20.542  1991  4037 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 15:11:20.542  1991  4037 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 15:11:20.554  1938  2010 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-12 15:11:20.554   874  4057 E DropBoxManagerService: Can't write: system_app_crash
08-12 15:11:20.554   874  4057 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
08-12 15:11:20.554   874  4057 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 15:11:20.554   874  4057 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 15:11:20.554   874  4057 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 15:11:20.554   874  4057 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 15:11:20.554   874  4057 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 15:11:20.554   874  4057 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 15:11:20.554   874  4057 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 15:11:20.554   874  4057 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 15:11:20.554   874  4057 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 15:11:20.554   874  4057 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 15:11:20.554   874  4057 E DropBoxManagerService: 	... 5 more
08-12 15:11:20.555   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-12 15:11:20.556   874   886 E PackageManager: Failed to write settings, restoring backup
08-12 15:11:20.556   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-12 15:11:20.556   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-12 15:11:20.556   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-12 15:11:20.556   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-12 15:11:20.556   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-12 15:11:20.556   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 15:11:20.556   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-12 15:11:20.556   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 15:11:20.556  1938  2010 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-12 15:11:20.556  1938  2010 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1938
08-12 15:11:20.556  1938  2010 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 15:11:20.556  1938  2010 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 15:11:20.556  1938  2010 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 15:11:20.556  1938  2010 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 15:11:20.556  1938  2010 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 15:11:20.556  1938  2010 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 15:11:20.556  1938  2010 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240,)
08-12 15:11:20.556  1938  2010 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-12 15:11:20.556  1938  2010 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 15:11:20.556  1938  2010 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 15:11:20.556  1938  2010 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 15:11:20.556  1938  2010 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 15:11:20.558   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-12 15:11:20.558   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-12 15:11:20.558   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 15:11:20.558   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 15:11:20.558   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 15:11:20.558   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 15:11:20.558   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 15:11:20.558   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 15:11:20.558   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-12 15:11:20.558   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-12 15:11:20.558   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-12 15:11:20.558   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 15:11:20.558   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 15:11:20.558   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-12 15:11:20.558   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 15:11:20.558   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-12 15:11:20.558   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 15:11:20.558   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 15:11:20.558   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 15:11:20.558   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 15:11:20.558   874   887 E DropBoxManagerService: 	... 13 more
08-12 15:11:20.559  1938  2620 E ReflectionEngine: Failed to save models
08-12 15:11:20.559  1938  2620 E ReflectionEngine: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/files/engine_16: open failed: EROFS (Read-only file system)
08-12 15:11:20.559  1938  2620 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 15:11:20.559  1938  2620 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 15:11:20.559  1938  2620 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 15:11:20.559  1938  2620 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.BT(ReflectionEngine.java:123)
08-12 15:11:20.559  1938  2620 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:240)
08-12 15:11:20.559  1938  2620 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.b(Ref,lectionServiceHandler.java:117)
08-12 15:11:20.559  1938  2620 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-12 15:11:20.559  1938  2620 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-12 15:11:20.559  1938  2620 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 15:11:20.559  1938  2620 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 15:11:20.559  1938  2620 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 15:11:20.559  1938  2620 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 15:11:20.559  1938  2620 E ReflectionEngine: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-12 15:11:20.559  1938  2620 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 15:11:20.559  1938  2620 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 15:11:20.559  1938  2620 E ReflectionEngine: 	at java.lang.Thread.run(Thread.java:818)
08-12 15:11:20.559  1938  2620 E ReflectionEngine: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-12 15:11:20.559  1938  2620 E ReflectionEngine: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 15:11:20.559  1938  2620 E ReflectionEngine: 	at libcore.io.Posix.open(Native Method)
08-12 15:11:20.559  1938  2620 E ReflectionEngine: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 15:11:20.559  1938  2620 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 15:11:20.559  1938  2620 E ReflectionEngine: 	... 16 more
08-12 15:11:20.568   874   885 I ActivityManager: Start proc 4059:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
08-12 15:11:20.580   874  4042 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 15:11:20.580   874  4042 I Adreno  : Build Date                       : 10/20/15
08-12 15:11:20.580   874  4042 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 15:11:20.580   874  4042 I Adreno  : Local Branch                     : M14
08-12 15:11:20.580   874  4042 I Adreno  : Remote Branch                    : 
08-12 15:11:20.580   874  4042 I Adreno  : Remote Branch                    : 
08-12 15:11:20.580   874  4042 I Adreno  : Reconstruct Branch               : 
08-12 15:11:20.580   874  1727 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
08-12 15:11:20.580   874  1727 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-12 15:11:20.587   874  1727 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-12 15:11:20.590   874  4070 E DropBoxManagerService: Can't write: system_app_crash
08-12 15:11:20.590   874  4070 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-12 15:11:20.590   874  4070 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 15:11:20.590   874  4070 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 15:11:20.590   874  4070 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 15:11:20.590   874  4070 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 15:11:20.590   874  4070 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 15:11:20.590   874  4070 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 15:11:20.590   874  4070 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 15:11:20.590   874  4070 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 15:11:20.590   874  4070 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 15:11:20.590   874  4070 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 15:11:20.590   874  4070 E DropBoxManagerService: 	... 5 more
08-12 15:11:20.590   874  1727 I ActivityManager: Killing 1938:com.google.android.googlequicksearchbox/u0a28 (adj 0): crash
08-12 15:11:20.593   874  4042 I OpenGLRenderer: Initialized EGL, version 1.4
,08-12 15:11:20.606  1862  4022 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-12 15:11:20.608  1862  4022 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-12 15:11:20.608  1862  4022 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-12 15:11:20.640   874  1957 D GraphicsStats: Buffer count: 2
,08-12 15:11:20.641  1991  1991 E AttachedClient: AttachedClient[8323646643020, ClientConfig[mFlags=[210d800202] mSuggestFlags=[3b] mClientStats=SearchBoxStats[gel/android-search-app]]]: failed callback onGenericEvent()
08-12 15:11:20.641  1991  1991 E AttachedClient: android.os.DeadObjectException
08-12 15:11:20.641  1991  1991 E AttachedClient: 	at android.os.BinderProxy.transactNative(Native Method)
08-12 15:11:20.641  1991  1991 E AttachedClient: 	at android.os.BinderProxy.transact(Binder.java:503)
08-12 15:11:20.641  1991  1991 E AttachedClient: 	at com.google.android.apps.gsa.search.shared.service.l.c(ISearchServiceUiCallback.java:578)
08-12 15:11:20.641  1991  1991 E AttachedClient: 	at com.google.android.search.core.service.a.c(AttachedClient.java:4725)
08-12 15:11:20.641  1991  1991 E AttachedClient: 	at com.google.android.search.core.service.a.b(AttachedClient.java:185)
08-12 15:11:20.641  1991  1991 E AttachedClient: 	at com.google.android.search.core.ad.c(SearchController.java:51069)
08-12 15:11:20.641  1991  1991 E AttachedClient: 	at com.google.android.search.core.service.SearchService.bca(SearchService.java:373)
08-12 15:11:20.641  1991  1991 E AttachedClient: 	at com.google.android.search.core.service.SearchService$1.run(SearchService.java:83)
08-12 15:11:20.641  1991  1991 E AttachedClient: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 15:11:20.641  1991  1991 E AttachedClient: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 15:11:20.641  1991  1991 E AttachedClient: 	at android.os.Looper.loop(Looper.java:148)
08-12 15:11:20.641  1991  1991 E AttachedClient: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 15:11:20.641  1991  1991 E AttachedClient: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 15:11:20.641  1991  1991 E AttachedClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 15:11:20.641  1991  1991 E AttachedClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-12 15:11:20.641  1991  1991 I SearchService: Ignoring already detached client
,08-12 15:11:20.656  1991  2331 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@157f6f1
,08-12 15:11:20.657  1991  4016 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-12 15:11:20.657  1991  1991 I HotwordDetector: Closing mic
,08-12 15:11:20.660   874  1727 I ActivityManager: Start proc 4073:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-12 15:11:20.663   874  1953 W ActivityManager: Spurious death for ProcessRecord{476f55b 0:com.google.android.googlequicksearchbox/u0a28}, curProc for 1938: null
,08-12 15:11:20.665   874   892 W AppOps  : Finishing op nesting under-run: uid 1000 pkg android code 24 time=1465474415550 duration=35 nesting=0
08-12 15:11:20.702  1862  4022 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-12 15:11:20.702  1862  4022 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-12 15:11:20.703   377  4018 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-12 15:11:20.703  1862  4022 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-12 15:11:20.703  1862  4022 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-12 15:11:20.703   377  4018 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-12 15:11:20.704  1862  4022 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-12 15:11:20.704  1862  4022 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-12 15:11:20.704  1862  4022 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-12 15:11:20.704  1862  4022 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-12 15:11:20.704  1862  4022 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-12 15:11:20.704  1862  4022 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-12 15:11:20.706   377  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-12 15:11:20.710  1991  2334 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-12 15:11:20.710  1991  4015 I MicroRecognitionRnrImpl: Detection finished
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-12 15:11:20.715  ,4073  4073 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 15:11:20.715  4073  4073 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 15:11:20.715  4059  4059 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm
08-12 15:11:20.715  4073  4073 D AndroidRuntime: Shutting down VM
,08-12 15:11:20.721  4073  4073 E AndroidRuntime: FATAL EXCEPTION: main
08-12 15:11:20.721  4073  4073 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4073
08-12 15:11:20.721  4073  4073 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-12 15:11:20.721  4073  4073 E AndroidRuntime: 	... 10 more
08-12 15:11:20.723   874  1727 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-12 15:11:20.724   874  4091 E DropBoxManagerService: Can't write: system_app_crash
08-12 15:11:20.724   874  4091 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
08-12 15:11:20.724   874  4091 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 15:11:20.724   874  4091 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 15:11:20.724   874  4091 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 15:11:20.724   874  4091 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 15:11:20.724   874  4091 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 15:11:20.724   874  4091 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 15:11:20.724   874  4091 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 15:11:20.724   874  4091 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 15:11:20.724   874  4091 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 15:11:20.724   874  4091 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 15:11:20.724   874  4091 E DropBoxManagerService: 	... 5 more
,08-12 15:11:20.741  1991  4090 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,08-12 15:11:20.743   874  1949 I ActivityManager: Start proc 4092:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
08-12 15:11:20.750  4059  4059 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
,08-12 15:11:20.754   280   280 E lowmemorykiller: Error writing /proc/3223/oom_score_adj; errno=22
,08-12 15:11:20.755   280   280 E lowmemorykiller: Error writing /proc/3223/oom_score_adj; errno=22
,08-12 15:11:20.778   280   280 E lowmemorykiller: Error writing /proc/3223/oom_score_adj; errno=22
,08-12 15:11:20.792   874   874 I ActivityManager: Start proc 4107:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,08-12 15:11:20.802  4059  4105 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.keychain/databases/grants.db'.
08-12 15:11:20.802  4059  4105 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 15:11:20.802  4059  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 15:11:20.802  4059  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 15:11:20.802  4059  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 15:11:20.802  4059  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 15:11:20.802  4059  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 15:11:20.802  4059  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 15:11:20.802  4059  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 15:11:20.802  4059  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 15:11:20.802  4059  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 15:11:20.802  4059  4105 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 15:11:20.802  4059  4105 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 15:11:20.802  4059  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 15:11:20.802  4059  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 15:11:20.802  4059  4105 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-12 15:11:20.802  4059  4105 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-12 15:11:20.802  4059  4105 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 15:11:20.802  4059  4105 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 15:11:20.802  4059  4105 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-12 15:11:20.802  4059  4105 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 15:11:20.802  4059  4105 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-12 15:11:20.802  4059  4105 E AndroidRuntime: Process: com.android.keychain, PID: 4059
08-12 15:11:20.802  4059  4105 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 15:11:20.802  4059  4105 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 15:11:20.802  4059  4105 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 15:11:20.802  4059  4105 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 15:11:20.802  4059  4105 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 15:11:20.802  4059  4105 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 15:11:20.802  4059  4105 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 15:11:20.802  4059  4105 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 15:11:20.802  4059  4105 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 15:11:20.802  4059  4105 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 15:11:20.802  4059  4105 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 15:11:20.802  4059  4105 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 15:11:20.802  4059  4105 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 15:11:20.802  4059  4105 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 15:11:20.802  4059  4105 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-12 15:11:20.802  4059  4105 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-12 15:11:20.802  4059  4105 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 15:11:20.802  4059  4105 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 15:11:20.802  4059  4105 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 15:11:20.802  4059  4105 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 15:11:20.806   874  4118 E DropBoxManagerService: Can't write: system_app_crash
08-12 15:11:20.806   874  4118 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
08-12 15:11:20.806   874  4118 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 15:11:20.806   874  4118 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 15:11:20.806   874  4118 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 15:11:20.806   874  4118 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 15:11:20.806   874  4118 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 15:11:20.806   874  4118 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 15:11:20.806   874  4118 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 15:11:20.806   874  4118 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 15:11:20.806   874  4118 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 15:11:20.806   874  4118 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 15:11:20.806   874  4118 E DropBoxManagerService: 	... 5 more
,08-12 15:11:20.822  4092  4092 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-12 15:11:20.848  4107  4107 W System  : ClassLoader referenced unknown path: /system/app/DocumentsUI/lib/arm
,08-12 15:11:20.859  4092  4092 I MultiDex: VM with version 2.1.0 has multidex support
,08-12 15:11:20.859  4092  4092 I MultiDex: install
08-12 15:11:20.859  4092  4092 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-12 15:11:20.886  4107  4107 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.documentsui/databases/recents.db'.
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:398)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1398)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 15:11:20.886  4107  4107 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-12 15:11:20.892  4107  4107 D AndroidRuntime: Shutting down VM
,08-12 15:11:20.893  4107  4107 E AndroidRuntime: FATAL EXCEPTION: main
08-12 15:11:20.893  4107  4107 E AndroidRuntime: Process: com.android.documentsui, PID: 4107
08-12 15:11:20.893  4107  4107 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:398)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1398)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
08-12 15:11:20.893  4107  4107 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-12 15:11:2,0.893  4107  4107 E AndroidRuntime: 	... 8 more
,08-12 15:11:20.898   282   282 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,08-12 15:11:20.898   282   282 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
08-12 15:11:20.898   282   282 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
08-12 15:11:20.898   282   282 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
,08-12 15:11:20.898   282   282 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
,08-12 15:11:20.898   282   282 E qdoverlay: MdpCtrl close error in unset
08-12 15:11:20.900   874  4121 E DropBoxManagerService: Can't write: system_app_crash
08-12 15:11:20.900   874  4121 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
08-12 15:11:20.900   874  4121 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 15:11:20.900   874  4121 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 15:11:20.900   874  4121 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 15:11:20.900   874  4121 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 15:11:20.900   874  4121 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 15:11:20.900   874  4121 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 15:11:20.900   874  4121 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 15:11:20.900   874  4121 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 15:11:20.900   874  4121 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 15:11:20.900   874  4121 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 15:11:20.900   874  4121 E DropBoxManagerService: 	... 5 more
,08-12 15:11:20.939   874  1953 I ActivityManager: Process android.process.acore (pid 3223) has died
,08-12 15:11:20.939   874  1953 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-12 15:11:20.956   874  1728 I ActivityManager: Start proc 4125:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider

```
