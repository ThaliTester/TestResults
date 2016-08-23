#### Test 79763830edacfaa_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-23 16:34:42.470   979   979 I kickstart: STATUS: Received file 'm9kefs2'
,08-23 16:34:42.470   979   979 I kickstart: STATUS: 950272 bytes transferred in 0.998574 seconds
08-23 16:34:42.470   979   979 I kickstart: STATUS: Successfully downloaded files from target 
08-23 16:34:42.471   979   979 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
08-23 16:34:42.474   979   979 I kickstart: STATUS: Sahara protocol completed
08-23 16:34:43.117  3408  3408 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-23 16:34:43.122  3408  3408 D AndroidRuntime: CheckJNI is OFF
08-23 16:34:43.165  3408  3408 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-23 16:34:43.215  3408  3408 I Radio-JNI: register_android_hardware_Radio DONE
08-23 16:34:43.237  3408  3408 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-23 16:34:43.241   876  1946 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-23 16:34:43.281  3408  3408 D AndroidRuntime: Shutting down VM
08-23 16:34:43.283  2035  2047 W SearchService: Abort, client detached.
08-23 16:34:43.306  2035  2035 I HotwordDetector: Closing mic
08-23 16:34:43.306  2035  2323 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@e44bd6e
08-23 16:34:43.306  2035  2328 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-23 16:34:43.317   876   887 I ActivityManager: Start proc 3417:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-23 16:34:43.329  2035  2035 W ErrorReporter: reportError [type: 29, code: 917507]: null
08-23 16:34:43.357   378  2330 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-23 16:34:43.360   378  2330 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-23 16:34:43.369   378  1280 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-23 16:34:43.372  2035  2327 I MicroRecognitionRnrImpl: Detection finished
08-23 16:34:43.372  2035  2325 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-23 16:34:43.412  3417  3417 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-23 16:34:43.457  3417  3417 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-23 16:34:43.546  3417  3417 I LibraryLoader: Time to load native libraries: 82 ms (timestamps 3339-3421)
,08-23 16:34:43.547  3417  3417 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-23 16:34:43.577  3417  3417 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2190540}
,08-23 16:34:43.578  3417  3417 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 16:34:43.578  3417  3417 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 16:34:43.590  3417  3417 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-23 16:34:43.592  3417  3417 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-23 16:34:43.640  3417  3432 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,08-23 16:34:43.649  3417  3417 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-23 16:34:43.664  3417  3417 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 16:34:43.664  3417  3417 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 16:34:43.664  3417  3417 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 16:34:43.664  3417  3417 I Adreno  : Build Date                       : 10/20/15
08-23 16:34:43.664  3417  3417 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 16:34:43.664  3417  3417 I Adreno  : Local Branch                     : M14
08-23 16:34:43.664  3417  3417 I Adreno  : Remote Branch                    : 
08-23 16:34:43.664  3417  3417 I Adreno  : Remote Branch                    : 
08-23 16:34:43.664  3417  3417 I Adreno  : Reconstruct Branch               : 
,08-23 16:34:43.780   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d85c1b:true
,08-23 16:34:43.827  3417  3417 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-23 16:34:43.838  3417  3417 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-23 16:34:43.868  3417  3454 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-23 16:34:43.877  3417  3441 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-23 16:34:43.907  3417  3454 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 16:34:43.955   876   894 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +658ms
,08-23 16:34:43.973  1868  1868 I Keyboard.Facilitator: onFinishInput()
,08-23 16:34:44.024  3417  3417 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3417
,08-23 16:34:44.106   876  1699 I ActivityManager: Killing 2819:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,08-23 16:34:44.138   876  1699 I ActivityManager: Killing 3114:com.qualcomm.telephony/1001 (adj 15): empty #18
,08-23 16:34:44.228  3417  3417 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 16:34:44.314  3417  3456 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1712654032
,08-23 16:34:44.318  3417  3456 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 16:34:44.318  3417  3456 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 16:34:44.318  3417  3456 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 16:34:44.318  3417  3456 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 16:34:44.318  3417  3456 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 16:34:44.318  3417  3456 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a016c4 added. We now have 1 listener(s)
,08-23 16:34:44.320  3417  3456 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-23 16:34:44.322  3417  3456 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 16:34:44.323  3417  3456 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 16:34:44.323  3417  3456 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 16:34:44.327  3417  3456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 16:34:44.327  3417  3456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 16:34:44.327  3417  3456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 16:34:44.327  3417  3456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-23 16:34:44.327  3417  3456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 16:34:44.327  3417  3456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 16:34:44.327  3417  3456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 16:34:44.327  3417  3456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 16:34:44.327  3417  3456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 16:34:44.327  3417  3456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 16:34:44.327  3417  3456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 16:34:44.327  3417  3456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 16:34:44.327  3417  3456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 16:34:44.327  3417  3456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-23 16:34:44.328  3417  3456 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba03073 added. We now have 1 listener(s)
08-23 16:34:44.328  3417  3456 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 16:34:44.330   876  1310 D WifiService: New client listening to asynchronous messages
,08-23 16:34:44.331  3417  3456 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 16:34:44.331  3417  3456 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 16:34:44.331  3417  3456 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-23 16:34:44.331  3417  3456 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 16:34:44.331  3417  3456 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 16:34:44.333  3417  3456 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 16:34:44.334  3417  3456 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-23 16:34:44.335  3417  3456 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 16:34:44.336  3417  3456 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 16:34:44.336  3417  3456 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 16:34:44.336  3417  3456 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-23 16:34:44.336  3417  3456 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 16:34:44.336  3417  3456 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 16:34:44.336  3417  3456 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 16:34:44.336  3417  3456 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 16:34:44.336  3417  3456 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 16:34:44.336  3417  3456 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-23 16:34:44.336  3417  3456 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 16:34:44.337  3417  3456 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 16:34:44.393  3417  3417 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 16:34:44.395  3417  3417 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 16:34:45.099  3417  3464 W jxcore-log: Initializing JXcore engine
08-23 16:34:45.099  3417  3464 W jxcore-log: JXcore engine is ready
08-23 16:34:45.138  3464  3464 W Thread-281: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8975 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-23 16:34:45.138  3464  3464 W Thread-281: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10663]" dev="sockfs" ino=10663 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-23 16:34:45.138  3464  3464 W Thread-281: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-23 16:34:45.138  3464  3464 W Thread-281: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24832]" dev="sockfs" ino=24832 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-23 16:34:45.153  3417  3464 W jxcore-log: Starting JXcore engine
08-23 16:34:45.230  3417  3464 W jxcore-log: Platform android
08-23 16:34:45.230  3417  3464 W jxcore-log: 
08-23 16:34:45.231  3417  3464 W jxcore-log: Process ARCH arm
08-23 16:34:45.231  3417  3464 W jxcore-log: 
08-23 16:34:45.454  3417  3464 I jxcore-log: JXcore Cordova bridge is ready!
08-23 16:34:45.454  3417  3464 I jxcore-log: 
08-23 16:34:45.454  3417  3464 W jxcore-log: JXcore engine is started
08-23 16:34:45.461  3417  3456 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-23 16:34:45.466  3417  3417 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-23 16:34:45.967  1513  1513 I ConfigService: onDestroy
,08-23 16:34:55.116   876   889 I ActivityManager: Waited long enough for: ServiceRecord{a07b15f u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,08-23 16:34:55.192  3417  3464 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 16:34:55.192  3417  3464 I jxcore-log: 
,08-23 16:34:55.195  3417  3464 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 16:34:55.195  3417  3464 I jxcore-log: 
,08-23 16:34:55.197  3417  3464 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 16:34:55.197  3417  3464 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 16:34:55.197  3417  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 16:34:55.197  3417  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-23 16:34:55.197  3417  3464 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 16:34:55.197  3417  3464 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 16:34:55.197  3417  3464 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 16:34:55.197  3417  3464 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 16:34:55.197  3417  3464 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 16:34:55.197  3417  3464 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 16:34:55.198  3417  3464 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 16:34:55.200  3417  3464 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 16:34:55.200  3417  3464 I jxcore-log: 
,08-23 16:34:55.202  3417  3464 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 16:34:55.202  3417  3464 I jxcore-log: 
,08-23 16:34:55.697  3417  3464 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
,08-23 16:34:55.697  3417  3464 I jxcore-log: Failed to execute UT.
08-23 16:34:55.697  3417  3464 I jxcore-log: 
08-23 16:34:55.699  3417  3464 I jxcore-log: Unit Test app is loaded
08-23 16:34:55.699  3417  3464 I jxcore-log: 
,08-23 16:34:55.705  3417  3464 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 16:34:55.705  3417  3464 I jxcore-log: 
,08-23 16:34:55.711   876   886 D WifiService: setWifiEnabled: true pid=3417, uid=10000
08-23 16:34:55.711   876   886 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 16:34:55.721  3417  3417 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-23 16:34:55.725  3417  3464 I jxcore-log: My device name is: motorola-Nexus 6
08-23 16:34:55.725  3417  3464 I jxcore-log: 
,08-23 16:34:55.734  3417  3464 I jxcore-log: WARN testUtils: myNameCallback not set!
08-23 16:34:55.734  3417  3464 I jxcore-log: 
,08-23 16:34:55.735   876   893 I ActivityManager: Start proc 3468:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
08-23 16:34:55.739   876  1309 D WifiConfigStore: Loading config and enabling all networks 
,08-23 16:34:55.743  3417  3417 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 16:34:55.743  3417  3417 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 16:34:55.743  3417  3417 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 16:34:55.743  3417  3417 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-23 16:34:55.743  3417  3417 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 16:34:55.743  3417  3417 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 16:34:55.743  3417  3417 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 16:34:55.743  3417  3417 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 16:34:55.743  3417  3417 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 16:34:55.743  3417  3417 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 16:34:55.743  3417  3417 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 16:34:55.755   876  1309 D WifiConfigStore: loaded 0 passpoint configs
,08-23 16:34:55.756   876  1309 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-23 16:34:55.757   876  1309 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-23 16:34:55.757   876  1309 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-23 16:34:55.758   876  1309 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-23 16:34:55.758   876  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-23 16:34:55.758   876  1309 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-23 16:34:55.761   876   889 I ActivityManager: Start proc 3479:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-23 16:34:55.806  3479  3479 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-23 16:34:55.811   374   874 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-23 16:34:55.812   374   874 D CommandListener: Setting iface cfg
,08-23 16:34:55.813   876  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '103 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 103 Failed to set address (No such device)'
08-23 16:34:55.813   876  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-23 16:34:55.817   876  1308 D WifiNative-HAL: p2pGetDeviceAddress
08-23 16:34:55.818   876  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-23 16:34:55.844  3468  3468 D AdapterServiceConfig: Adding HeadsetService
,08-23 16:34:55.845   876  1309 D WifiConfigStore: Retrieve network priorities after PNO.
08-23 16:34:55.845  3468  3468 D AdapterServiceConfig: Adding A2dpService
08-23 16:34:55.845  3468  3468 D AdapterServiceConfig: Adding HidService
,08-23 16:34:55.845  3468  3468 D AdapterServiceConfig: Adding HealthService
08-23 16:34:55.845  3468  3468 D AdapterServiceConfig: Adding PanService
08-23 16:34:55.846  3468  3468 D AdapterServiceConfig: Adding GattService
08-23 16:34:55.846  3468  3468 D AdapterServiceConfig: Adding BluetoothMapService
08-23 16:34:55.847   876  1309 D WifiConfigStore: Retrieve network priorities after PNO.
08-23 16:34:55.862  3479  3479 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
08-23 16:34:55.872   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f5ee4d7:true
08-23 16:34:55.872  3468  3468 D BluetoothAdapterState: make() - Creating AdapterState
08-23 16:34:55.874  3468  3468 I bt_bluedroid: init
08-23 16:34:55.874  3468  3505 I BluetoothAdapterState: Entering OffState
,08-23 16:34:55.876  3468  3506 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-23 16:34:55.877  3468  3506 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-23 16:34:55.877  3468  3506 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-23 16:34:55.877  3468  3506 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-23 16:34:55.878  3468  3468 I bt_bluedroid: get_profile_interface socket
08-23 16:34:55.879  3468  3509 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-23 16:34:55.879  3468  3468 I bt_bluedroid: get_profile_interface sdp
,08-23 16:34:55.881  3468  3509 D BluetoothAdapterProperties: Name is: Nexus 6
08-23 16:34:55.882  3468  3484 I bt_bluedroid: config_hci_snoop_log
08-23 16:34:55.882   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-23 16:34:55.884   876  2211 I ActivityManager: Killing 2798:com.google.android.calendar/u0a37 (adj 15): empty #17
08-23 16:34:55.885  3468  3505 D BluetoothAdapterState: Current state: OFF, message: 0
08-23 16:34:55.885  3468  3505 D BluetoothAdapterProperties: Setting state to 14
08-23 16:34:55.885  3468  3505 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-23 16:34:55.886  3468  3505 D BluetoothBondStateMachine: make
08-23 16:34:55.887  3468  3510 I BluetoothBondStateMachine: StableState(): Entering Off State
08-23 16:34:55.912  3468  3505 I BluetoothAdapterState: Entering PendingCommandState
08-23 16:34:55.912  3468  3468 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-23 16:34:55.914  3468  3468 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3df7ca
08-23 16:34:55.915  3468  3468 D BtGatt.DebugUtils: handleDebugAction() action=null
08-23 16:34:55.915  3468  3468 D BtGatt.GattService: Received start request. Starting profile...
08-23 16:34:55.915  3468  3468 D BtGatt.GattService: start()
08-23 16:34:55.915  3468  3468 I bt_bluedroid: get_profile_interface gatt
08-23 16:34:55.915  3468  3468 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3df7ca
08-23 16:34:55.916  3468  3468 D BtGatt.AdvertiseManager: advertise manager created
08-23 16:34:55.919  3468  3468 V BluetoothAdapterState: isTurningOff()=false
08-23 16:34:55.919  3468  3468 V BluetoothAdapterState: isTurningOn()=false
08-23 16:34:55.919  3468  3468 V BluetoothAdapterState: isBleTurningOn()=true
08-23 16:34:55.920  3468  3468 V BluetoothAdapterState: isBleTurningOff()=false
08-23 16:34:55.920  3468  3505 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-23 16:34:55.920  3468  3505 I bt_bluedroid: enable
08-23 16:34:55.920  3468  3506 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-23 16:34:55.920  3468  3506 I bt_hci  : start_up
,08-23 16:34:55.928  3468  3506 I bt_vendor: alloc value 0xb3955189
08-23 16:34:55.928  3468  3506 I bt_vendor: init
,08-23 16:34:55.928  3468  3506 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-23 16:34:55.928  3468  3506 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-23 16:34:56.037  3468  3506 D bt_hci  : start_up starting async portion
08-23 16:34:56.037  3468  3513 I bt_hci  : event_finish_startup
,08-23 16:34:56.038  3468  3513 I bt_hci_h4: hal_open
08-23 16:34:56.038  3468  3513 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-23 16:34:56.045  3468  3513 I bt_userial_vendor: device fd = 51 open
,08-23 16:34:56.080  3468  3513 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-23 16:34:56.111  3468  3513 D bt_hwcfg: Chipset BCM4354A2
,08-23 16:34:56.111  3468  3513 D bt_hwcfg: Target name = [BCM4354A2]
08-23 16:34:56.112  3468  3513 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-23 16:34:56.859  3468  3513 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-23 16:34:56.860  3468  3513 D bt_hwcfg: Settlement delay -- 100 ms
08-23 16:34:56.860  3468  3513 I bt_hwcfg: Setting fw settlement delay to 100 
,08-23 16:34:56.977  3468  3513 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-23 16:34:56.978  3468  3513 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-23 16:34:57.009  3468  3513 I bt_hwcfg: vendor lib fwcfg completed
,08-23 16:34:57.009  3468  3513 I bt_vendor: firmware callback
,08-23 16:34:57.017  3468  3513 I bt_hci  : firmware_config_callback
,08-23 16:34:57.028  3468  3515 I bt_btu  : btu_task pending for preload complete event
08-23 16:34:57.028  3468  3515 I bt_btu_task: Bluetooth chip preload is complete
08-23 16:34:57.028  3468  3515 I bt_btu  : btu_task received preload complete event
,08-23 16:34:57.037  3468  3515 I         : BTE_InitTraceLevels -- TRC_HCI
,08-23 16:34:57.037  3468  3515 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-23 16:34:57.037  3468  3515 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-23 16:34:57.038  3468  3515 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-23 16:34:57.038  3468  3515 I         : BTE_InitTraceLevels -- TRC_AVRC
08-23 16:34:57.038  3468  3515 I         : BTE_InitTraceLevels -- TRC_A2D
,08-23 16:34:57.038  3468  3515 I         : BTE_InitTraceLevels -- TRC_BNEP
08-23 16:34:57.039  3468  3515 I         : BTE_InitTraceLevels -- TRC_BTM
08-23 16:34:57.039  3468  3515 I         : BTE_InitTraceLevels -- TRC_GAP
,08-23 16:34:57.039  3468  3515 I         : BTE_InitTraceLevels -- TRC_PAN
08-23 16:34:57.039  3468  3515 I         : BTE_InitTraceLevels -- TRC_SDP
,08-23 16:34:57.039  3468  3515 I         : BTE_InitTraceLevels -- TRC_GATT
08-23 16:34:57.040  3468  3515 I         : BTE_InitTraceLevels -- TRC_SMP
08-23 16:34:57.040  3468  3515 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-23 16:34:57.040  3468  3515 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-23 16:34:57.180  3468  3515 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38d2d9d
08-23 16:34:57.180  3468  3515 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38d2d9d 
,08-23 16:34:57.186  3468  3509 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-23 16:34:57.187  3468  3509 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-23 16:34:57.188  3468  3509 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-23 16:34:57.190  3468  3509 D BluetoothAdapterProperties: Name is: Nexus 6
,08-23 16:34:57.193  3468  3509 D BluetoothAdapterProperties: Scan Mode:20
,08-23 16:34:57.193  3468  3509 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-23 16:34:57.193  3468  3509 D bt_hci  : do_postload posting postload work item
,08-23 16:34:57.194  3468  3513 I bt_hci  : event_postload
08-23 16:34:57.194  3468  3513 I bt_vendor: sco_config_cb
,08-23 16:34:57.194  3468  3513 I bt_hci  : sco_config_callback postload finished.
,08-23 16:34:57.196  3417  3417 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 16:34:57.204  3468  3513 I bt_vendor: low_power_mode_cb
,08-23 16:34:57.211  3468  3509 D bt_bte_conf: Device ID record 1 : primary
,08-23 16:34:57.211  3468  3509 D bt_bte_conf:   vendorId            = 000f
08-23 16:34:57.211  3468  3509 D bt_bte_conf:   vendorIdSource      = 0001
08-23 16:34:57.211  3468  3509 D bt_bte_conf:   product             = 1200
,08-23 16:34:57.211  3468  3509 D bt_bte_conf:   version             = 1436
08-23 16:34:57.211  3468  3509 D bt_bte_conf:   clientExecutableURL = 
,08-23 16:34:57.211  3468  3509 D bt_bte_conf:   serviceDescription  = 
08-23 16:34:57.211  3468  3509 D bt_bte_conf:   documentationURL    = 
,08-23 16:34:57.211  3468  3509 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-23 16:34:57.211  3468  3506 D bt_stack_manager: event_start_up_stack finished
,08-23 16:34:57.212  3468  3505 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-23 16:34:57.212  3468  3505 D BluetoothAdapterProperties: Setting state to 15
,08-23 16:34:57.212  3468  3505 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-23 16:34:57.213  3468  3505 I BluetoothAdapterState: Entering BleOnState
08-23 16:34:57.217  3468  3505 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-23 16:34:57.218  3468  3505 D BluetoothAdapterProperties: Setting state to 11
,08-23 16:34:57.218  3468  3505 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-23 16:34:57.224  3468  3468 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3df7ca
,08-23 16:34:57.224  3468  3468 D HeadsetService: Received start request. Starting profile...
08-23 16:34:57.227  3468  3468 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-23 16:34:57.227  3468  3468 D HeadsetStateMachine: make
,08-23 16:34:57.227  3417  3417 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 16:34:57.243   876   889 I ActivityManager: Start proc 3523:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-23 16:34:57.245  3468  3468 D HeadsetStateMachine: max_hf_connections = 1
,08-23 16:34:57.245  3468  3468 I bt_bluedroid: get_profile_interface handsfree
,08-23 16:34:57.246  3468  3509 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-23 16:34:57.248  3468  3509 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-23 16:34:57.254  3468  3505 I BluetoothAdapterState: Entering PendingCommandState
,08-23 16:34:57.257  3468  3468 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3df7ca
,08-23 16:34:57.258   876   876 D BluetoothA2dp: Proxy object connected
08-23 16:34:57.258  3468  3468 D A2dpService: Received start request. Starting profile...
08-23 16:34:57.258  3468  3468 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-23 16:34:57.259  3468  3468 I bt_bluedroid: get_profile_interface avrcp
,08-23 16:34:57.270  3468  3468 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-23 16:34:57.271  3468  3468 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-23 16:34:57.271  3468  3468 D A2dpStateMachine: make
,08-23 16:34:57.274  3468  3468 I bt_bluedroid: get_profile_interface a2dp
,08-23 16:34:57.278  3468  3509 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-23 16:34:57.279  3468  3468 I BluetoothHidServiceJni: classInitNative: succeeds
08-23 16:34:57.280  3468  3468 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3df7ca
08-23 16:34:57.280  3468  3536 D A2dpStateMachine: Enter Disconnected: -2,
08-23 16:34:57.281  1366  1366 D BluetoothInputDevice: Proxy object connected
08-23 16:34:57.281  1366  1366 D HidProfile: Bluetooth service connected
08-23 16:34:57.282  3468  3468 D HidService: Received start request. Starting profile...
,08-23 16:34:57.282  3468  3468 I bt_bluedroid: get_profile_interface hidhost
08-23 16:34:57.282  3468  3468 D HidService: setHidService(): set to: null
08-23 16:34:57.283  3468  3509 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38b43e5
08-23 16:34:57.283  3468  3468 I BluetoothHealthServiceJni: classInitNative: succeeds,
08-23 16:34:57.283  3468  3509 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-23 16:34:57.283  3468  3468 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3df7ca
,08-23 16:34:57.284  3468  3468 D HealthService: Received start request. Starting profile...
,08-23 16:34:57.287  3468  3468 I bt_bluedroid: get_profile_interface health
,08-23 16:34:57.287  3468  3468 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-23 16:34:57.288  3468  3468 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3df7ca
08-23 16:34:57.289  1366  1366 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 16:34:57.289  3468  3468 D PanService: Received start request. Starting profile...
08-23 16:34:57.289  1366  1366 D PanProfile: Bluetooth service connected
08-23 16:34:57.289  3468  3468 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-23 16:34:57.289  3468  3468 I bt_bluedroid: get_profile_interface pan
,08-23 16:34:57.290  3468  3509 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-23 16:34:57.294  3468  3468 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3df7ca
08-23 16:34:57.295  1366  1366 D BluetoothMap: Proxy object connected
08-23 16:34:57.295  3468  3468 D BluetoothMapService: Received start request. Starting profile...
08-23 16:34:57.295  3468  3468 D BluetoothMapService: start()
08-23 16:34:57.295  1366  1366 D MapProfile: Bluetooth service connected
,08-23 16:34:57.295  1366  1366 D BluetoothMap: getConnectedDevices()
08-23 16:34:57.296  1366  1366 D BluetoothMap: Bluetooth is Not enabled
08-23 16:34:57.297  3468  3468 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-23 16:34:57.297  3468  3468 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-23 16:34:57.297  3468  3468 D BluetoothMapAppObserver: createReceiver()
08-23 16:34:57.299  3468  3468 D BluetoothMapAppObserver: initObservers()
,08-23 16:34:57.299  3468  3468 D BluetoothMapAppObserver: getEnabledAccountItems()
08-23 16:34:57.306  3468  3468 V BluetoothAdapterState: isTurningOff()=false
08-23 16:34:57.306  3468  3468 V BluetoothAdapterState: isTurningOn()=true
08-23 16:34:57.306  3468  3468 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 16:34:57.306  3468  3468 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 16:34:57.308  3468  3468 V BluetoothAdapterState: isTurningOff()=false
,08-23 16:34:57.308  3468  3468 V BluetoothAdapterState: isTurningOn()=true
,08-23 16:34:57.308  3468  3468 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 16:34:57.308  3468  3468 V BluetoothAdapterState: isBleTurningOff()=false
08-23 16:34:57.308  3468  3522 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-23 16:34:57.308  3468  3468 V BluetoothAdapterState: isTurningOff()=false
,08-23 16:34:57.308  3468  3468 V BluetoothAdapterState: isTurningOn()=true
08-23 16:34:57.309  3468  3468 V BluetoothAdapterState: isBleTurningOn()=false
08-23 16:34:57.309  3468  3468 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 16:34:57.309  3468  3468 V BluetoothAdapterState: isTurningOff()=false
,08-23 16:34:57.309  3468  3468 V BluetoothAdapterState: isTurningOn()=true
08-23 16:34:57.309  3468  3468 V BluetoothAdapterState: isBleTurningOn()=false
08-23 16:34:57.309  3468  3468 V BluetoothAdapterState: isBleTurningOff()=false
08-23 16:34:57.309  3468  3468 V BluetoothAdapterState: isTurningOff()=false
08-23 16:34:57.309  3468  3468 V BluetoothAdapterState: isTurningOn()=true
08-23 16:34:57.309  3468  3468 V BluetoothAdapterState: isBleTurningOn()=false
08-23 16:34:57.309  3468  3468 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 16:34:57.309  3468  3468 V BluetoothAdapterState: isTurningOff()=false
,08-23 16:34:57.309  3468  3468 V BluetoothAdapterState: isTurningOn()=true
,08-23 16:34:57.309  3468  3468 V BluetoothAdapterState: isBleTurningOn()=false
08-23 16:34:57.309  3468  3468 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 16:34:57.310  3468  3505 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-23 16:34:57.310  3468  3505 D BluetoothAdapterProperties: ScanMode =  20
08-23 16:34:57.310  3468  3505 D BluetoothAdapterProperties: State =  11
08-23 16:34:57.311  3468  3505 D BluetoothAdapterProperties: Setting state to 12
08-23 16:34:57.311  3468  3505 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-23 16:34:57.312   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 16:34:57.312  3468  3505 I BluetoothAdapterState: Entering OnState
08-23 16:34:57.312  3468  3509 D BluetoothAdapterProperties: Scan Mode:21
,08-23 16:34:57.312  3468  3509 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-23 16:34:57.313  1366  2071 D BluetoothPan: onBluetoothStateChange on: true
,08-23 16:34:57.313  1366  1380 D BluetoothMap: onBluetoothStateChange: up=true
08-23 16:34:57.313  1939  1958 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 16:34:57.314  1366  1379 D BluetoothPbap: onBluetoothStateChange: up=true
08-23 16:34:57.314  3417  3417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-23 16:34:57.315   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 16:34:57.315   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-23 16:34:57.315   876   893 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 16:34:57.315  1366  2071 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-23 16:34:57.316   876   876 I Telecom : BluetoothPhoneService: queryPhoneState
,08-23 16:34:57.316  3417  3417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-23 16:34:57.317  3468  3468 D BluetoothMapService: onReceive
08-23 16:34:57.317  3468  3468 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 16:34:57.317  3468  3468 D BluetoothMapService: STATE_ON
,08-23 16:34:57.318  3417  3417 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-23 16:34:57.320  1366  1658 D LocalBluetoothProfileManager: Adding local A2DP profile
08-23 16:34:57.322  3417  3417 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 16:34:57.322  3417  3417 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 16:34:57.322  3417  3417 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 16:34:57.322  3417  3417 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 16:34:57.322  3417  3417 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 16:34:57.322  3417  3417 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 16:34:57.322  3417  3417 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 16:34:57.322  3417  3417 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 16:34:57.324  3417  3417 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 16:34:57.325  3417  3417 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 16:34:57.326  3468  3468 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-23 16:34:57.326  3468  3468 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-23 16:34:57.328  3468  3468 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 16:34:57.329  3523  3523 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-23 16:34:57.332  3468  3468 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 16:34:57.332  3468  3468 D ObexServerSockets: Succeed to create listening sockets 
08-23 16:34:57.333  3468  3468 D ObexServerSockets0: startAccept()
,08-23 16:34:57.333  3468  3468 D ObexServerSockets0: prepareForNewConnect()
08-23 16:34:57.334  3468  3468 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-23 16:34:57.334  3468  3468 D BluetoothSdpJni: SDP Create record success - handle: 0
08-23 16:34:57.335  3468  3544 D ObexServerSockets0: Accepting socket connection...
08-23 16:34:57.337  3468  3545 D ObexServerSockets0: Accepting socket connection...
08-23 16:34:57.337   876  1309 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,08-23 16:34:57.338  3468  3468 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-23 16:34:57.338  3468  3468 D ObexServerSockets0: prepareForNewConnect()
08-23 16:34:57.338   876  1309 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=1 roam=3
08-23 16:34:57.338   876  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 16:34:57.339  1366  1658 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-23 16:34:57.339  1366  1366 D BluetoothA2dp: Proxy object connected
08-23 16:34:57.342   876  1309 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
08-23 16:34:57.362   876  1903 I ActivityManager: Killing 2954:com.google.android.gm/u0a78 (adj 15): empty #17
,08-23 16:34:57.400   876  1309 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-23 16:34:57.401  1480  1480 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-23 16:34:57.404  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 16:34:57.413   876   893 D BluetoothHeadset: Proxy object connected
,08-23 16:34:57.415  1939  2371 D BluetoothHeadset: Proxy object connected
08-23 16:34:57.416   876   893 D BluetoothHeadset: Proxy object connected
,08-23 16:34:57.416   876   893 D BluetoothHeadset: Proxy object connected
,08-23 16:34:57.417   876  1699 I ActivityManager: Start proc 3546:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-23 16:34:57.444  1366  2071 D BluetoothHeadset: Proxy object connected
,08-23 16:34:57.444  1366  1366 D HeadsetProfile: Bluetooth service connected
,08-23 16:34:57.452  3546  3546 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-23 16:34:57.579  3546  3546 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 16:34:57.579  3546  3546 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at java.io.File.exists(File.java:361)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 16:34:57.579  3546  3546 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-23 16:34:57.580  3546  3546 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 16:34:57.580  3546  3546 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 16:34:57.580  3546  3546 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.r.e.b(PG:170)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 16:34:57.580  3546  3546 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.r.k.d(PG:583)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.r.e.b(PG:170)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 16:34:57.580  3546  3546 D StrictMode: StrictMode policy violation; ~duration=56 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at java.io.File.exists(File.java:361)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 16:34:57.580  3546  3546 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at java.io.File.exists(File.java:361)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 16:34:57.580  3546  3546 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 16:34:57.580  3546  3546 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 16:34:57.589  3523  3523 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-23 16:34:57.605   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8d10c54:true
08-23 16:34:57.609  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-23 16:34:57.614  3523  3523 D LocalBluetoothProfileManager: Adding local A2DP profile
08-23 16:34:57.617  3523  3523 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-23 16:34:57.629  1366  1366 D BluetoothPbap: Proxy object connected
08-23 16:34:57.629  1366  1366 D PbapServerProfile: Bluetooth service connected
08-23 16:34:57.629  3523  3523 D LocalBluetoothProfileManager: Adding local MAP profile
08-23 16:34:57.630  3523  3523 D BluetoothMap: Create BluetoothMap proxy object
08-23 16:34:57.639  3468  3574 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 16:34:57.647  3523  3523 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-23 16:34:57.655  3468  3581 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 16:34:57.656  3468  3581 I BtOppRfcommListener: Accept thread started.
08-23 16:34:57.658  3523  3523 D DockEventReceiver: finishStartingService: stopping service
08-23 16:34:57.659  3523  3523 D BluetoothA2dp: Proxy object connected
,08-23 16:34:57.662  3523  3523 D BluetoothInputDevice: Proxy object connected
,08-23 16:34:57.662  3523  3523 D HidProfile: Bluetooth service connected
,08-23 16:34:57.664  3523  3523 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 16:34:57.664  3523  3523 D PanProfile: Bluetooth service connected
08-23 16:34:57.664  3523  3523 D BluetoothMap: Proxy object connected
,08-23 16:34:57.665  3523  3523 D MapProfile: Bluetooth service connected
08-23 16:34:57.665  3523  3523 D BluetoothMap: getConnectedDevices()
,08-23 16:34:57.666  3523  3523 D BluetoothPbap: Proxy object connected
,08-23 16:34:57.667  3523  3523 D PbapServerProfile: Bluetooth service connected
,08-23 16:34:57.668   876  1381 I ActivityManager: Killing 3135:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-23 16:34:57.719  3523  3535 D BluetoothHeadset: Proxy object connected
,08-23 16:34:57.720  3523  3523 D HeadsetProfile: Bluetooth service connected
,08-23 16:34:57.821  3546  3563 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-23 16:34:57.845   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5ce95d9:true
,08-23 16:34:57.862  1480  1480 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-23 16:34:57.889  1480  1480 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-23 16:34:57.889  1480  1480 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-23 16:34:57.891   876  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 16:34:57.898   876  1309 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-23 16:34:57.899   876  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 16:34:57.899   876  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-23 16:34:57.912   876  1309 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 16:34:57.920   374   874 D CommandListener: Setting iface cfg
,08-23 16:34:57.924   876  1309 D WifiStateMachine: Start Dhcp Watchdog 1
,08-23 16:34:57.935   876  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-23 16:34:57.935   876  1311 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,08-23 16:34:57.938   876  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-23 16:34:57.964   876  3587 D DhcpClient: Receive thread started
,08-23 16:34:58.044   876  1309 E native  : do suspend false
,08-23 16:34:58.064   876  3586 D DhcpClient: Broadcasting DHCPDISCOVER
,08-23 16:34:58.082   876  3587 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 171133, domain null
,08-23 16:34:58.084   876  3586 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 171133 seconds
,08-23 16:34:58.088   876  3586 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-23 16:34:58.102   876  3587 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-23 16:34:58.103   876  3586 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-23 16:34:58.107   374   874 D CommandListener: Setting iface cfg
,08-23 16:34:58.116   876  3586 D DhcpClient: Scheduling renewal in 86399s
,08-23 16:34:58.117   876  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-23 16:34:58.130   876  1309 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-23 16:34:58.132   876  1309 D WifiConfigStore: No blacklist allowed without epno enabled
,08-23 16:34:58.133   876  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-23 16:34:58.140   876  1311 D ConnectivityService: Adding iface wlan0 to network 100
,08-23 16:34:58.143   876  1309 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-23 16:34:58.189   876  1311 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-23 16:34:58.189   876  1311 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,08-23 16:34:58.191   876  1311 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,08-23 16:34:58.192   876  1311 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,08-23 16:34:58.194   876  1311 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,08-23 16:34:58.202   876  1311 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-23 16:34:58.207   876  1311 D ConnectivityService: scheduleUnvalidatedPrompt 100
08-23 16:34:58.207   876  1311 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
08-23 16:34:58.207   876  1311 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
08-23 16:34:58.208   876  1311 D ConnectivityService:    accepting network in place of null
08-23 16:34:58.208   876  1309 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-23 16:34:58.208   876  1309 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-23 16:34:58.209   876  1311 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-23 16:34:58.214   876  3585 D NetlinkSocketObserver: NeighborEvent{elapsedMs=118087, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-23 16:34:58.235   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 16:34:58.270   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 16:34:58.274   876  1311 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,08-23 16:34:58.278   876  1311 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-23 16:34:58.278   876  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 16:34:58.282   876   893 D Tethering: MasterInitialState.processMessage what=3
,08-23 16:34:58.285   876  1903 V BackupManagerService: Scheduling immediate backup pass
08-23 16:34:58.285   876   876 V BackupManagerService: Running a backup pass,
08-23 16:34:58.288   876  3584 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-23 16:34:58.289  3417  3417 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 16:34:58.289  3417  3417 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 16:34:58.289  3417  3417 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 16:34:58.289  3417  3417 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 16:34:58.289  3417  3417 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 16:34:58.289  3417  3417 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 16:34:58.289  3417  3417 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 16:34:58.289  3417  3417 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 16:34:58.292  3417  3417 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 16:34:58.292   876  1311 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
08-23 16:34:58.293   876  1333 V BackupManagerService: clearing pending backups
08-23 16:34:58.301   876  1333 V PerformBackupTask: Beginning backup of 16 targets
,08-23 16:34:58.322   876  1333 D PerformBackupTask: invokeAgentForBackup on @pm@
,08-23 16:34:58.326  1710  1710 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-23 16:34:58.331  1710  1710 D SystemUpdateService: onCreate
,08-23 16:34:58.339  1710  1710 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-23 16:34:58.342  1710  3604 I SystemUpdateService: active receiver: enabled
,08-23 16:34:58.351  1710  3604 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-23 16:34:58.352   876  1333 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
,08-23 16:34:58.353  1710  3604 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-23 16:34:58.353  1710  3604 I SystemUpdateService: now status is 0 (complete)
,08-23 16:34:58.353  1710  3604 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-23 16:34:58.353  1710  3604 I SystemUpdateService: file has been verified
08-23 16:34:58.353  1710  3604 I SystemUpdateService: OTA package size = 12249756
,08-23 16:34:58.359  1710  3604 I SystemUpdateService: showing system update notification
,08-23 16:34:58.359   876  1906 D AlarmManagerService: Setting time of day to sec=1471962897
08-23 16:34:57.922   876  1906 W AlarmManagerService: Unable to set rtc to 1471962897: Invalid argument
08-23 16:34:57.922   876  3584 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 23 Aug 2016 14:34:58 GMT], X-Android-Received-Millis=[1471962898359], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471962898333]}
,08-23 16:34:57.927   876   886 I ActivityManager: Start proc 3609:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-23 16:34:57.932   876  1311 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-23 16:34:57.932   876  1311 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
08-23 16:34:57.932   876  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-23 16:34:57.933   876  1311 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION,
,08-23 16:34:57.954   876  1333 I BackupRestoreController: Getting widget state for user: 0
,08-23 16:34:57.957  3609  3609 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-23 16:34:57.960  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:34:57.963  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:34:57.985  1710  3626 I iu.SyncManager: SYNC; picasa accounts
,08-23 16:34:57.994  1710  1710 D NetworkLogImpl: Loaded NetworkSpeedPredictor
08-23 16:34:57.995  1710  1710 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-23 16:34:58.021  1710  3625 I MDM     : [146] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-23 16:34:58.021  1710  3625 W BaseAppContext: Using Auth Proxy for data requests.
,08-23 16:34:58.033  1710  1710 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-23 16:34:58.034  1710  1710 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-23 16:34:58.035  1710  1710 D SystemUpdateService: onDestroy
08-23 16:34:58.035  1710  3625 V GoogleAuthProtoRequest: [146] a.<init>: mAccountName set to: thalitester@gmail.com
08-23 16:34:58.037  3609  3627 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-23 16:34:58.041  1710  3626 I iu.UploadsManager: num queued entries: 0
,08-23 16:34:58.041  1710  3626 I iu.UploadsManager: num updated entries: 0
08-23 16:34:58.042  1710  3626 I iu.SyncManager: NEXT; no task
,08-23 16:34:58.046   876   886 I ActivityManager: Start proc 3635:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-23 16:34:58.088  3479  3602 V GoogleAuthProtoRequest: [278] a.<init>: mAccountName set to: thalitester@gmail.com
,08-23 16:34:58.093  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-23 16:34:58.094  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-23 16:34:58.094  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 16:34:58.094  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:34:58.102  3609  3627 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-23 16:34:58.103   876  3653 D GpsLocationProvider: NTP server returned: 1471962897922 (Tue Aug 23 16:34:57 GMT+02:00 2016) reference: 118234 certainty: 12 system time offset: -181
08-23 16:34:58.104   876  3653 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,08-23 16:34:58.112  3635  3635 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-23 16:34:58.114  3635  3635 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-23 16:34:58.124  3635  3635 D SprintDMHelper: simOperator: 
,08-23 16:34:58.124  3635  3635 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-23 16:34:58.134  3609  3627 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-23 16:34:58.138   876  1903 I ActivityManager: Start proc 3656:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-23 16:34:58.179  1710  3651 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,08-23 16:34:58.181  1710  3625 E MDM     : [146] SitrepService.a: Error sending sitrep.
,08-23 16:34:58.192  1884  1896 W GmsBackupTransport: Unknown package in backup request: @pm@
,08-23 16:34:58.195  1884  1896 V GmsBackupTransport: starting performBackup for @pm@
,08-23 16:34:58.206  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-23 16:34:58.207  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-23 16:34:58.207  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:34:58.207  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:34:58.210  3609  3609 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-23 16:34:58.237  1884  1896 V GmsBackupTransport: performBackup done for @pm@
,08-23 16:34:58.247  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:34:58.267  1513  1978 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
,08-23 16:34:58.267  1513  1978 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
08-23 16:34:58.267  1513  1978 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:34:58.267  1513  1978 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:34:58.291  3479  3602 W ExperimentUpdateService: [278] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-23 16:34:58.292  3479  3602 W ExperimentUpdateService: [278] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 16:34:58.292  3479  3602 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 16:34:58.292  3479  3602 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-23 16:34:58.292  3479  3602 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-23 16:34:58.292  3479  3602 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-23 16:34:58.292  3479  3602 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-23 16:34:58.292  3479  3602 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-23 16:34:58.292  3479  3602 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-23 16:34:58.292  3479  3602 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-23 16:34:58.292  3479  3602 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-23 16:34:58.292  3479  3602 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-23 16:34:58.325  1513  1978 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-23 16:34:58.325  1513  1978 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-23 16:34:58.325  1513  1978 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-23 16:34:58.325  1513  1978 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-23 16:34:58.325  1513  1978 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-23 16:34:58.325  1513  1978 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-23 16:34:58.325  1513  1978 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-23 16:34:58.330  1884  2262 W GmsBackupTransport: Error sending final backup to server: 
08-23 16:34:58.330  1884  2262 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
08-23 16:34:58.330  1884  2262 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
08-23 16:34:58.330  1884  2262 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
08-23 16:34:58.330  1884  2262 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
08-23 16:34:58.330  1884  2262 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
08-23 16:34:58.330  1884  2262 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
08-23 16:34:58.330  1884  2262 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
08-23 16:34:58.330  1884  2262 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-23 16:34:58.330  1884  2262 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-23 16:34:58.330  1884  2262 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-23 16:34:58.330  1884  2262 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-23 16:34:58.330  1884  2262 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-23 16:34:58.330  1884  2262 W GmsBackupTransport: 	... 1 more
,08-23 16:34:58.352  1884  1896 I GmsBackupTransport: Next backup will happen in 43199975 millis.
,08-23 16:34:58.352   876  1333 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
,08-23 16:34:58.464  1513  2261 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 16:34:58.464  1513  2261 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 16:34:58.464  1513  2261 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 16:34:58.464  1513  2261 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:34:58.472   876  1699 I ActivityManager: Start proc 3701:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-23 16:34:58.495  3220  3655 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-23 16:34:58.495  3220  3655 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 16:34:58.495  3220  3655 E HttpOperation: 	at jdm.a(PG:82)
08-23 16:34:58.495  3220  3655 E HttpOperation: 	at jcs.o(PG:406)
08-23 16:34:58.495  3220  3655 E HttpOperation: 	at jcn.a(PG:1379)
08-23 16:34:58.495  3220  3655 E HttpOperation: 	at jcs.i(PG:143)
08-23 16:34:58.495  3220  3655 E HttpOperation: 	at blb.a(PG:3937)
08-23 16:34:58.495  3220  3655 E HttpOperation: 	at czp.a(PG:18188)
08-23 16:34:58.495  3220  3655 E HttpOperation: 	at czp.a(PG:9081)
08-23 16:34:58.495  3220  3655 E HttpOperation: 	at czq.run(PG:1686)
08-23 16:34:58.495  3220  3655 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 16:34:58.495  3220  3655 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 16:34:58.495  3220  3655 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 16:34:58.495  3220  3655 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 16:34:58.495  3220  3655 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 16:34:58.495  3220  3655 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 16:34:58.495  3220  3655 E HttpOperation: 	at jdj.a(PG:4091)
08-23 16:34:58.495  3220  3655 E HttpOperation: 	at jdj.a(PG:1125)
08-23 16:34:58.495  3220  3655 E HttpOperation: 	at jdm.a(PG:77)
08-23 16:34:58.495  3220  3655 E HttpOperation: 	... 12 more
08-23 16:34:58.495  3220  3655 E HttpOperation: Caused by: faj: BadAuthentication
08-23 16:34:58.495  3220  3655 E HttpOperation: 	at fal.a(PG:38)
08-23 16:34:58.495  3220  3655 E HttpOperation: 	at jdj.a(PG:4089)
08-23 16:34:58.495  3220  3655 E HttpOperation: 	... 14 more
,08-23 16:34:58.521  3609  3609 W InstanceID/Rpc: Found 10011
,08-23 16:34:58.525  3701  3701 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
08-23 16:34:58.525  1710  1710 E ConnectivityChangeReceiver: Ignoring connectivity change
,08-23 16:34:58.532  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 16:34:58.532  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 16:34:58.532  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:34:58.532  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:34:58.551  3220  3655 E HttpOperation: [getmobileexperiments] Unexpected exception
08-23 16:34:58.551  3220  3655 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 16:34:58.551  3220  3655 E HttpOperation: 	at jdm.a(PG:82)
08-23 16:34:58.551  3220  3655 E HttpOperation: 	at jcs.o(PG:406)
08-23 16:34:58.551  3220  3655 E HttpOperation: 	at jcn.a(PG:1379)
08-23 16:34:58.551  3220  3655 E HttpOperation: 	at jcs.i(PG:143)
08-23 16:34:58.551  3220  3655 E HttpOperation: 	at hec.a(PG:42)
08-23 16:34:58.551  3220  3655 E HttpOperation: 	at hee.a(PG:102)
08-23 16:34:58.551  3220  3655 E HttpOperation: 	at czr.a(PG:65)
08-23 16:34:58.551  3220  3655 E HttpOperation: 	at kka.a(PG:108)
08-23 16:34:58.551  3220  3655 E HttpOperation: 	at czp.a(PG:19176)
08-23 16:34:58.551  3220  3655 E HttpOperation: 	at czp.a(PG:9081)
08-23 16:34:58.551  3220  3655 E HttpOperation: 	at czq.run(PG:1686)
08-23 16:34:58.551  3220  3655 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 16:34:58.551  3220  3655 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 16:34:58.551  3220  3655 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 16:34:58.551  3220  3655 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 16:34:58.551  3220  3655 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 16:34:58.551  3220  3655 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 16:34:58.551  3220  3655 E HttpOperation: 	at jdj.a(PG:4091)
08-23 16:34:58.551  3220  3655 E HttpOperation: 	at jdj.a(PG:1125)
08-23 16:34:58.551  3220  3655 E HttpOperation: 	at jdm.a(PG:77)
08-23 16:34:58.551  3220  3655 E HttpOperation: 	... 15 more
08-23 16:34:58.551  3220  3655 E HttpOperation: Caused by: faj: BadAuthentication
08-23 16:34:58.551  3220  3655 E HttpOperation: 	at fal.a(PG:38)
08-23 16:34:58.551  3220  3655 E HttpOperation: 	at jdj.a(PG:4089)
08-23 16:34:58.551  3220  3655 E HttpOperation: 	... 17 more
,08-23 16:34:58.551  3220  3655 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-23 16:34:58.551  3220  3655 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-23 16:34:58.551  3220  3655 E ExperimentLoader: 	at jdm.a(PG:82)
08-23 16:34:58.551  3220  3655 E ExperimentLoader: 	at jcs.o(PG:406)
08-23 16:34:58.551  3220  3655 E ExperimentLoader: 	at jcn.a(PG:1379)
08-23 16:34:58.551  3220  3655 E ExperimentLoader: 	at jcs.i(PG:143)
08-23 16:34:58.551  3220  3655 E ExperimentLoader: 	at hec.a(PG:42)
08-23 16:34:58.551  3220  3655 E ExperimentLoader: 	at hee.a(PG:102)
08-23 16:34:58.551  3220  3655 E ExperimentLoader: 	at czr.a(PG:65)
08-23 16:34:58.551  3220  3655 E ExperimentLoader: 	at kka.a(PG:108)
08-23 16:34:58.551  3220  3655 E ExperimentLoader: 	at czp.a(PG:19176)
08-23 16:34:58.551  3220  3655 E ExperimentLoader: 	at czp.a(PG:9081)
08-23 16:34:58.551  3220  3655 E ExperimentLoader: 	at czq.run(PG:1686)
08-23 16:34:58.551  3220  3655 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 16:34:58.551  3220  3655 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 16:34:58.551  3220  3655 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 16:34:58.551  3220  3655 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 16:34:58.551  3220  3655 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-23 16:34:58.551  3220  3655 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 16:34:58.551  3220  3655 E ExperimentLoader: 	at jdj.a(PG:4091)
08-23 16:34:58.551  3220  3655 E ExperimentLoader: 	at jdj.a(PG:1125)
08-23 16:34:58.551  3220  3655 E ExperimentLoader: 	at jdm.a(PG:77)
08-23 16:34:58.551  3220  3655 E ExperimentLoader: 	... 15 more
08-23 16:34:58.551  3220  3655 E ExperimentLoader: Caused by: faj: BadAuthentication
08-23 16:34:58.551  3220  3655 E ExperimentLoader: 	at fal.a(PG:38)
08-23 16:34:58.551  3220  3655 E ExperimentLoader: 	at jdj.a(PG:4089)
08-23 16:34:58.551  3220  3655 E ExperimentLoader: 	... 17 more
,08-23 16:34:58.557   876  1333 I BackupManagerService: Backup pass finished.
,08-23 16:34:58.569   876  1382 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1710 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 16:34:58.603  3694  3694 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads516836475.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads516836475.dex
,08-23 16:34:58.623  2227  3700 I Babel   : connection state changed from UNKNOWN to CONNECTED
,08-23 16:34:58.661   876  1382 I ActivityManager: Killing 2606:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-23 16:34:58.723  3694  3694 I dex2oat : dex2oat took 120.846ms (threads: 4) arena alloc=274KB java alloc=41KB native alloc=1642KB free=1429KB
,08-23 16:34:58.736  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:34:58.746  1513  3754 I VacuumService: Vacuum at: now=1471962898746 tag=VacuumService
,08-23 16:34:58.791   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 25813, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-23 16:34:58.801  1710  3652 W DriveInitializer: Awaiting to be initialized
,08-23 16:34:58.803  1710  3759 W DriveInitializer: Background init thread started
,08-23 16:34:58.869   876   888 I ActivityManager: Start proc 3761:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-23 16:34:58.882  3761  3761 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-23 16:34:58.925  3701  3701 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-23 16:34:58.925  3701  3701 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-23 16:34:58.925  3701  3701 I GAv4    :   adb logcat -s GAv4
,08-23 16:34:58.929  1710  3759 W DriveInitializer: Background init thread ended
,08-23 16:34:58.968  3701  3701 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-23 16:34:59.030  3701  3701 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-23 16:34:59.071  3701  3791 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-23 16:34:59.072  3761  3761 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-23 16:34:59.079  3761  3761 I BooksApp: Created application version: 3.6.9 (30609)
,08-23 16:34:59.157  2986  3784 V KeepSync: Connecting to GoogleApiClient
,08-23 16:34:59.160   876  2211 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-23 16:34:59.197  3761  3797 I BooksSync: Starting books sync for 61035162, extras: ade
,08-23 16:34:59.206  1513  1978 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-23 16:34:59.206  1513  1978 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-23 16:34:59.206  1513  1978 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:34:59.206  1513  1978 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:34:59.217  1710  3811 V BaseAuthAsyncOperation: access token request failed
,08-23 16:34:59.219  2986  3784 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-23 16:34:59.243  3701  3701 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-23 16:34:59.299  3701  3701 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-23 16:34:59.306  3701  3701 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9616-9619)
08-23 16:34:59.306  3701  3701 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-23 16:34:59.347  3701  3701 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {eaaba92}
,08-23 16:34:59.347  3701  3701 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 16:34:59.347  3701  3701 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 16:34:59.353  3701  3701 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-23 16:34:59.463  3701  3701 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-23 16:34:59.494  3701  3701 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-23 16:34:59.513  3701  3701 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-23 16:34:59.514  3701  3701 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-23 16:34:59.514  3701  3701 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 16:34:59.514  3701  3701 I Adreno  : Build Date                       : 10/20/15
08-23 16:34:59.514  3701  3701 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 16:34:59.514  3701  3701 I Adreno  : Local Branch                     : M14
08-23 16:34:59.514  3701  3701 I Adreno  : Remote Branch                    : 
08-23 16:34:59.514  3701  3701 I Adreno  : Remote Branch                    : 
08-23 16:34:59.514  3701  3701 I Adreno  : Reconstruct Branch               : 
,08-23 16:34:59.624  3701  3829 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-23 16:34:59.633  3701  3701 I NSApplication: Starting up...
,08-23 16:34:59.652   876  2014 I ActivityManager: Start proc 3834:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-23 16:34:59.654   876  2014 I ActivityManager: Killing 2864:android.process.acore/u0a5 (adj 15): empty #17
,08-23 16:34:59.761  3834  3834 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-23 16:34:59.819  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-23 16:34:59.819  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-23 16:34:59.819  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 16:34:59.819  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:34:59.845  2986  3784 E KeepSync: IOException
08-23 16:34:59.845  2986  3784 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-23 16:34:59.845  2986  3784 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-23 16:34:59.845  2986  3784 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-23 16:34:59.845  2986  3784 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-23 16:34:59.845  2986  3784 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-23 16:34:59.845  2986  3784 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-23 16:34:59.845  2986  3784 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-23 16:34:59.845  2986  3784 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-23 16:34:59.845  2986  3784 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-23 16:34:59.845  2986  3784 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-23 16:34:59.845  2986  3784 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-23 16:34:59.845  2986  3784 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-23 16:34:59.845  2986  3784 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-23 16:34:59.845  2986  3784 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-23 16:34:59.845  2986  3784 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 16:34:59.845  2986  3784 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 16:34:59.845  2986  3784 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-23 16:34:59.845  2986  3784 E KeepSync: 	... 10 more
08-23 16:34:59.846  2986  3784 W KeepSync: Sync result 2
,08-23 16:34:59.849   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 25824, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-23 16:34:59.850   876  1381 I ActivityManager: Killing 3313:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-23 16:34:59.930  3761  3850 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-23 16:34:59.981  1513  2260 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 16:34:59.981  1513  2260 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 16:34:59.981  1513  2260 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:34:59.981  1513  2260 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:35:00.018  1513  2261 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 16:35:00.018  1513  2261 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 16:35:00.018  1513  2261 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:35:00.018  1513  2261 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:35:00.041  3761  3850 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-23 16:35:00.042  3761  3797 E BooksSync: Soft error
08-23 16:35:00.042  3761  3797 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 16:35:00.042  3761  3797 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-23 16:35:00.042  3761  3797 E BooksSync: Sync error
08-23 16:35:00.042  3761  3797 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 16:35:00.042  3761  3797 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 16:35:00.043  3761  3797 I BooksSync: Finished books sync
,08-23 16:35:00.053   876  1974 I ActivityManager: Killing 3330:com.android.musicfx/u0a18 (adj 15): empty #17
,08-23 16:35:00.053   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 25825, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-23 16:35:00.238   876  2014 I ActivityManager: Killing 2712:com.android.vending/u0a19 (adj 15): empty #17
,08-23 16:35:00.246  3417  3464 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-23 16:35:00.246  3417  3464 I jxcore-log: 
,08-23 16:35:00.360   876  1298 I ActivityManager: Start proc 3861:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,08-23 16:35:00.405  3861  3861 W System  : ClassLoader referenced unknown path: /system/priv-app/Phonesky/lib/arm
,08-23 16:35:00.473  3861  3861 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-23 16:35:00.509  3861  3861 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,08-23 16:35:00.512   876  1311 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-23 16:35:00.520  3861  3861 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-23 16:35:00.521  3861  3861 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-23 16:35:00.544  3861  3861 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,08-23 16:35:00.544  3861  3861 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,08-23 16:35:00.561  3861  3861 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-23 16:35:00.567  3861  3899 D Ads     : Skipping gmscore version check
,08-23 16:35:00.569  3861  3861 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-23 16:35:00.579  3861  3899 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-23 16:35:00.676  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:35:00.701  1513  2261 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-23 16:35:00.701  1513  2261 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-23 16:35:00.701  1513  2261 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:35:00.701  1513  2261 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:35:00.730  3861  3861 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-23 16:35:00.731  3861  3861 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-23 16:35:00.731  3861  3861 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-23 16:35:00.746   876  1382 I ActivityManager: Killing 2132:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-23 16:35:01.274  3417  3464 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-23 16:35:01.274  3417  3464 I jxcore-log: 
,08-23 16:35:01.300  3417  3464 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-23 16:35:01.300  3417  3464 I jxcore-log: 
,08-23 16:35:01.305  3417  3464 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-23 16:35:01.305  3417  3464 I jxcore-log: 
,08-23 16:35:01.325  3417  3464 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-23 16:35:01.325  3417  3464 I jxcore-log: 
,08-23 16:35:01.332  3417  3464 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-23 16:35:01.332  3417  3464 I jxcore-log: 
,08-23 16:35:02.456   876   887 I ActivityManager: Killing 3351:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-23 16:35:04.099  3761  3794 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-23 16:35:04.685  3417  3464 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-23 16:35:04.685  3417  3464 I jxcore-log: 
,08-23 16:35:04.698  3417  3464 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-23 16:35:04.698  3417  3464 I jxcore-log: 
,08-23 16:35:04.708  3417  3464 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-23 16:35:04.708  3417  3464 I jxcore-log: 
,08-23 16:35:04.884  3417  3464 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-23 16:35:04.884  3417  3464 I jxcore-log: 
,08-23 16:35:05.523  3861  3861 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,08-23 16:35:05.559  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:35:05.627  1513  2260 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-23 16:35:05.627  1513  2260 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-23 16:35:05.628  1513  2260 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 16:35:05.629  1513  2260 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:35:05.682  3861  3861 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-23 16:35:05.703  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:35:05.773   876  1311 D ConnectivityService: handlePromptUnvalidated 100
,08-23 16:35:05.778  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-23 16:35:05.778  3417  3464 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-23 16:35:05.778  3417  3464 I jxcore-log: 
08-23 16:35:05.778  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-23 16:35:05.778  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:35:05.778  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:35:05.860  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:35:05.863  3861  3907 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-23 16:35:05.868  3861  3861 W Finsky  : [1] GearheadStateMonitor$3.onConnectionFailed: Could not connect to GMS for Auto connection state: ConnectionResult{statusCode=SERVICE_VERSION_UPDATE_REQUIRED, resolution=null, message=null}
,08-23 16:35:05.868  3861  3861 V Finsky  : [1] GearheadStateMonitor.access$100: mIsProjecting:false
,08-23 16:35:05.910  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-23 16:35:05.910  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-23 16:35:05.910  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:35:05.910  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:35:05.942  3861  3861 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-23 16:35:06.023  3417  3464 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-23 16:35:06.023  3417  3464 I jxcore-log: 
,08-23 16:35:06.030  3417  3464 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-23 16:35:06.030  3417  3464 I jxcore-log: 
,08-23 16:35:06.173  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:35:06.217  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-23 16:35:06.217  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-23 16:35:06.217  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:35:06.218  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:35:06.236  3417  3464 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-23 16:35:06.236  3417  3464 I jxcore-log: 
,08-23 16:35:06.257  3861  3861 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-23 16:35:06.259  3417  3464 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-23 16:35:06.259  3417  3464 I jxcore-log: 
,08-23 16:35:06.262  3861  3861 D Finsky  : [1] WearSupportService.startHygiene: disabled
,08-23 16:35:06.264  3417  3464 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-23 16:35:06.264  3417  3464 I jxcore-log: 
,08-23 16:35:06.267  3861  3861 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,08-23 16:35:06.270  3417  3464 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-23 16:35:06.270  3417  3464 I jxcore-log: 
,08-23 16:35:06.274  3861  3861 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,08-23 16:35:06.289  3417  3464 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-23 16:35:06.289  3417  3464 I jxcore-log: 
,08-23 16:35:06.293  3861  3909 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-23 16:35:06.308  3417  3464 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-23 16:35:06.308  3417  3464 I jxcore-log: 
,08-23 16:35:06.386  3417  3464 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-23 16:35:06.386  3417  3464 I jxcore-log: 
,08-23 16:35:06.392  3417  3464 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-23 16:35:06.392  3417  3464 I jxcore-log: 
,08-23 16:35:06.421  3417  3464 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-23 16:35:06.421  3417  3464 I jxcore-log: 
,08-23 16:35:06.433  3417  3464 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-23 16:35:06.439  3417  3464 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-23 16:35:06.439  3417  3464 I jxcore-log: 
,08-23 16:35:06.521  3417  3464 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 16:35:06.521  3417  3464 I jxcore-log: 
,08-23 16:35:06.523  3417  3464 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 16:35:06.523  3417  3464 I jxcore-log: 
,08-23 16:35:06.524  3417  3464 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 16:35:06.524  3417  3464 I jxcore-log: 
,08-23 16:35:09.166  3861  3875 D Finsky  : [301] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-23 16:35:09.180  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:35:09.220  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-23 16:35:09.221  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-23 16:35:09.221  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 16:35:09.221  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:35:09.248  3861  3875 D Finsky  : [301] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-23 16:35:10.413   876  1309 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 2, 3 -> obsolete
,08-23 16:35:29.858   876   896 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-23 16:35:29.869  1868  1868 I Keyboard.Facilitator: onFinishInput()
,08-23 16:35:29.880   876   896 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 16:35:29.880   876   896 I Adreno  : Build Date                       : 10/20/15
08-23 16:35:29.880   876   896 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 16:35:29.880   876   896 I Adreno  : Local Branch                     : M14
08-23 16:35:29.880   876   896 I Adreno  : Remote Branch                    : 
08-23 16:35:29.880   876   896 I Adreno  : Remote Branch                    : 
08-23 16:35:29.880   876   896 I Adreno  : Reconstruct Branch               : 
,08-23 16:35:29.945   282   301 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (345 us)
,08-23 16:35:30.531  3417  3417 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-23 16:35:30.531  3417  3417 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-23 16:35:30.571   876   896 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-23 16:35:30.573  3417  3417 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@32bc696 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@8a4ea64, 16908290=android.view.AbsSavedState$1@8a4ea64}, android:focusedViewId=100}]}]
,08-23 16:35:30.573  3417  3417 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-23 16:35:30.574  3417  3417 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-23 16:35:30.574  3417  3417 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-23 16:35:30.577   876   896 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-23 16:35:30.582  2986  3918 V KeepSync: Connecting to GoogleApiClient
,08-23 16:35:30.582   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-23 16:35:30.582   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
08-23 16:35:30.582   876   894 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
08-23 16:35:30.585   876  1699 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-23 16:35:30.617  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:35:30.618  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:35:30.631  1513  2260 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-23 16:35:30.631  1513  2260 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-23 16:35:30.631  1513  2260 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:35:30.631  1513  2260 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:35:30.642  1710  3921 V BaseAuthAsyncOperation: access token request failed
,08-23 16:35:30.642  2986  3918 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-23 16:35:30.677  1513  1978 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-23 16:35:30.677  1513  1978 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-23 16:35:30.677  1513  1978 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 16:35:30.677  1513  1978 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:35:30.691  2986  3918 E KeepSync: IOException
08-23 16:35:30.691  2986  3918 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-23 16:35:30.691  2986  3918 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-23 16:35:30.691  2986  3918 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-23 16:35:30.691  2986  3918 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-23 16:35:30.691  2986  3918 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-23 16:35:30.691  2986  3918 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-23 16:35:30.691  2986  3918 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-23 16:35:30.691  2986  3918 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-23 16:35:30.691  2986  3918 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-23 16:35:30.691  2986  3918 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-23 16:35:30.691  2986  3918 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-23 16:35:30.691  2986  3918 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-23 16:35:30.691  2986  3918 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-23 16:35:30.691  2986  3918 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-23 16:35:30.691  2986  3918 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 16:35:30.691  2986  3918 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 16:35:30.691  2986  3918 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-23 16:35:30.691  2986  3918 E KeepSync: 	... 10 more
,08-23 16:35:30.691  2986  3918 W KeepSync: Sync result 2
,08-23 16:35:30.695   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 150187, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-23 16:35:30.809   282   344 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-23 16:35:30.811   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-23 16:35:30.820   876  1336 D SurfaceControl: Excessive delay in setPowerMode(): 238ms
,08-23 16:35:30.822   876   896 I DreamManagerService: Entering dreamland.
,08-23 16:35:30.822   876   896 I PowerManagerService: Dozing...
08-23 16:35:30.823   876   891 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-23 16:35:30.853  1513  3847 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 16:35:30.854  1513  3847 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 16:35:30.854  1513  3847 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:35:30.854  1513  3847 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:35:30.861   378  1281 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-23 16:35:30.861   378  1281 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-23 16:35:30.868  3220  3923 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-23 16:35:30.868  3220  3923 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 16:35:30.868  3220  3923 E HttpOperation: 	at jdm.a(PG:82)
08-23 16:35:30.868  3220  3923 E HttpOperation: 	at jcs.o(PG:406)
08-23 16:35:30.868  3220  3923 E HttpOperation: 	at jcn.a(PG:1379)
08-23 16:35:30.868  3220  3923 E HttpOperation: 	at jcs.i(PG:143)
08-23 16:35:30.868  3220  3923 E HttpOperation: 	at blb.a(PG:3937)
08-23 16:35:30.868  3220  3923 E HttpOperation: 	at czp.a(PG:18188)
08-23 16:35:30.868  3220  3923 E HttpOperation: 	at czp.a(PG:9087)
08-23 16:35:30.868  3220  3923 E HttpOperation: 	at czq.run(PG:1686)
08-23 16:35:30.868  3220  3923 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 16:35:30.868  3220  3923 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 16:35:30.868  3220  3923 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 16:35:30.868  3220  3923 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 16:35:30.868  3220  3923 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 16:35:30.868  3220  3923 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 16:35:30.868  3220  3923 E HttpOperation: 	at jdj.a(PG:4091)
08-23 16:35:30.868  3220  3923 E HttpOperation: 	at jdj.a(PG:1125)
08-23 16:35:30.868  3220  3923 E HttpOperation: 	at jdm.a(PG:77)
08-23 16:35:30.868  3220  3923 E HttpOperation: 	... 12 more
08-23 16:35:30.868  3220  3923 E HttpOperation: Caused by: faj: BadAuthentication
08-23 16:35:30.868  3220  3923 E HttpOperation: 	at fal.a(PG:38)
08-23 16:35:30.868  3220  3923 E HttpOperation: 	at jdj.a(PG:4089)
08-23 16:35:30.868  3220  3923 E HttpOperation: 	... 14 more
,08-23 16:35:30.869  1927  3925 D NfcService: Discovery configuration equal, not updating.
,08-23 16:35:30.870   876  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 16:35:30.879   876  1309 E native  : do suspend false
,08-23 16:35:30.896   876  1309 D WifiConfigStore: No blacklist allowed without epno enabled
,08-23 16:35:30.909   876  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 16:35:30.911   876  1309 E native  : do suspend true
,08-23 16:35:31.001   378   378 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-23 16:35:31.002   378   378 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-23 16:35:31.255  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 16:35:31.255  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 16:35:31.256  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:35:31.257  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:35:31.319  3220  3929 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-23 16:35:31.319  3220  3929 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 16:35:31.319  3220  3929 E HttpOperation: 	at jdm.a(PG:82)
08-23 16:35:31.319  3220  3929 E HttpOperation: 	at jcs.o(PG:406)
08-23 16:35:31.319  3220  3929 E HttpOperation: 	at jcn.a(PG:1379)
08-23 16:35:31.319  3220  3929 E HttpOperation: 	at jcs.i(PG:143)
08-23 16:35:31.319  3220  3929 E HttpOperation: 	at blb.a(PG:3937)
08-23 16:35:31.319  3220  3929 E HttpOperation: 	at czp.a(PG:18188)
08-23 16:35:31.319  3220  3929 E HttpOperation: 	at czp.a(PG:9081)
08-23 16:35:31.319  3220  3929 E HttpOperation: 	at czq.run(PG:1686)
08-23 16:35:31.319  3220  3929 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 16:35:31.319  3220  3929 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 16:35:31.319  3220  3929 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 16:35:31.319  3220  3929 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 16:35:31.319  3220  3929 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 16:35:31.319  3220  3929 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 16:35:31.319  3220  3929 E HttpOperation: 	at jdj.a(PG:4091)
08-23 16:35:31.319  3220  3929 E HttpOperation: 	at jdj.a(PG:1125)
08-23 16:35:31.319  3220  3929 E HttpOperation: 	at jdm.a(PG:77)
08-23 16:35:31.319  3220  3929 E HttpOperation: 	... 12 more
08-23 16:35:31.319  3220  3929 E HttpOperation: Caused by: faj: BadAuthentication
08-23 16:35:31.319  3220  3929 E HttpOperation: 	at fal.a(PG:38)
08-23 16:35:31.319  3220  3929 E HttpOperation: 	at jdj.a(PG:4089)
08-23 16:35:31.319  3220  3929 E HttpOperation: 	... 14 more
,08-23 16:35:31.372   876  1309 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,08-23 16:35:31.409  1513  1978 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 16:35:31.410  1513  1978 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-23 16:35:31.410  1513  1978 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:35:31.411  1513  1978 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:35:31.459  3220  3929 E HttpOperation: [getmobileexperiments] Unexpected exception
08-23 16:35:31.459  3220  3929 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 16:35:31.459  3220  3929 E HttpOperation: 	at jdm.a(PG:82)
08-23 16:35:31.459  3220  3929 E HttpOperation: 	at jcs.o(PG:406)
08-23 16:35:31.459  3220  3929 E HttpOperation: 	at jcn.a(PG:1379)
08-23 16:35:31.459  3220  3929 E HttpOperation: 	at jcs.i(PG:143)
08-23 16:35:31.459  3220  3929 E HttpOperation: 	at hec.a(PG:42)
08-23 16:35:31.459  3220  3929 E HttpOperation: 	at hee.a(PG:102)
08-23 16:35:31.459  3220  3929 E HttpOperation: 	at czr.a(PG:65)
08-23 16:35:31.459  3220  3929 E HttpOperation: 	at kka.a(PG:108)
08-23 16:35:31.459  3220  3929 E HttpOperation: 	at czp.a(PG:19176)
08-23 16:35:31.459  3220  3929 E HttpOperation: 	at czp.a(PG:9081)
08-23 16:35:31.459  3220  3929 E HttpOperation: 	at czq.run(PG:1686)
08-23 16:35:31.459  3220  3929 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 16:35:31.459  3220  3929 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 16:35:31.459  3220  3929 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 16:35:31.459  3220  3929 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 16:35:31.459  3220  3929 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 16:35:31.459  3220  3929 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 16:35:31.459  3220  3929 E HttpOperation: 	at jdj.a(PG:4091)
08-23 16:35:31.459  3220  3929 E HttpOperation: 	at jdj.a(PG:1125)
08-23 16:35:31.459  3220  3929 E HttpOperation: 	at jdm.a(PG:77)
08-23 16:35:31.459  3220  3929 E HttpOperation: 	... 15 more
08-23 16:35:31.459  3220  3929 E HttpOperation: Caused by: faj: BadAuthentication
08-23 16:35:31.459  3220  3929 E HttpOperation: 	at fal.a(PG:38)
08-23 16:35:31.459  3220  3929 E HttpOperation: 	at jdj.a(PG:4089)
08-23 16:35:31.459  3220  3929 E HttpOperation: 	... 17 more
,08-23 16:35:31.464  3220  3929 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-23 16:35:31.464  3220  3929 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-23 16:35:31.464  3220  3929 E ExperimentLoader: 	at jdm.a(PG:82)
08-23 16:35:31.464  3220  3929 E ExperimentLoader: 	at jcs.o(PG:406)
08-23 16:35:31.464  3220  3929 E ExperimentLoader: 	at jcn.a(PG:1379)
08-23 16:35:31.464  3220  3929 E ExperimentLoader: 	at jcs.i(PG:143)
08-23 16:35:31.464  3220  3929 E ExperimentLoader: 	at hec.a(PG:42)
08-23 16:35:31.464  3220  3929 E ExperimentLoader: 	at hee.a(PG:102)
08-23 16:35:31.464  3220  3929 E ExperimentLoader: 	at czr.a(PG:65)
08-23 16:35:31.464  3220  3929 E ExperimentLoader: 	at kka.a(PG:108)
08-23 16:35:31.464  3220  3929 E ExperimentLoader: 	at czp.a(PG:19176)
08-23 16:35:31.464  3220  3929 E ExperimentLoader: 	at czp.a(PG:9081)
08-23 16:35:31.464  3220  3929 E ExperimentLoader: 	at czq.run(PG:1686)
08-23 16:35:31.464  3220  3929 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 16:35:31.464  3220  3929 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 16:35:31.464  3220  3929 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 16:35:31.464  3220  3929 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 16:35:31.464  3220  3929 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-23 16:35:31.464  3220  3929 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 16:35:31.464  3220  3929 E ExperimentLoader: 	at jdj.a(PG:4091)
08-23 16:35:31.464  3220  3929 E ExperimentLoader: 	at jdj.a(PG:1125)
08-23 16:35:31.464  3220  3929 E ExperimentLoader: 	at jdm.a(PG:77)
08-23 16:35:31.464  3220  3929 E ExperimentLoader: 	... 15 more
08-23 16:35:31.464  3220  3929 E ExperimentLoader: Caused by: faj: BadAuthentication
08-23 16:35:31.464  3220  3929 E ExperimentLoader: 	at fal.a(PG:38)
08-23 16:35:31.464  3220  3929 E ExperimentLoader: 	at jdj.a(PG:4089)
08-23 16:35:31.464  3220  3929 E ExperimentLoader: 	... 17 more
,08-23 16:35:31.631   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 119108, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-23 16:35:31.668  3761  3932 I BooksSync: Starting books sync for 61035162, extras: ade
,08-23 16:35:31.689  3761  3933 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-23 16:35:31.739  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 16:35:31.740  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-23 16:35:31.740  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 16:35:31.740  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:35:31.844  1513  1978 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 16:35:31.845  1513  1978 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 16:35:31.845  1513  1978 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 16:35:31.845  1513  1978 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:35:31.898  3761  3933 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-23 16:35:31.902  3761  3932 E BooksSync: Soft error
08-23 16:35:31.902  3761  3932 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 16:35:31.902  3761  3932 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 16:35:31.903  3761  3932 E BooksSync: Sync error
08-23 16:35:31.903  3761  3932 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 16:35:31.903  3761  3932 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 16:35:31.905  3761  3932 I BooksSync: Finished books sync
,08-23 16:35:31.924   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 151910, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-23 16:35:34.518  1884  2490 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-23 16:35:35.033  3479  3934 V GoogleAuthProtoRequest: [279] a.<init>: mAccountName set to: thalitester@gmail.com
,08-23 16:35:35.114  1513  3847 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-23 16:35:35.115  1513  3847 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-23 16:35:35.115  1513  3847 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 16:35:35.115  1513  3847 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:35:35.171  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:35:35.197  3479  3934 W ExperimentUpdateService: [279] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
08-23 16:35:35.197  3479  3934 W ExperimentUpdateService: [279] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 16:35:35.197  3479  3934 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 16:35:35.197  3479  3934 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-23 16:35:35.197  3479  3934 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-23 16:35:35.197  3479  3934 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-23 16:35:35.197  3479  3934 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-23 16:35:35.197  3479  3934 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-23 16:35:35.197  3479  3934 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-23 16:35:35.197  3479  3934 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-23 16:35:35.197  3479  3934 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-23 16:35:35.197  3479  3934 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-23 16:35:35.249  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-23 16:35:35.249  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-23 16:35:35.249  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:35:35.249  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:35:35.263  3861  3861 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-23 16:35:35.263  3861  3861 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-23 16:35:35.264  3861  3861 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
08-23 16:35:35.264  1513  3936 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
08-23 16:35:35.267  1513  3936 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-23 16:35:35.303  1513  3936 W Uploader:  no longer exists, so no auth token.
,08-23 16:35:35.721  1513  1513 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-23 16:35:36.175  1513  3945 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,08-23 16:35:36.559  1513  3936 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-23 16:35:36.560  1513  3936 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-23 16:35:36.560  1513  3936 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:35:36.561  1513  3936 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:35:36.595  1513  3936 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-23 16:35:36.595  1513  3936 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-23 16:35:36.595  1513  3936 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-23 16:35:36.595  1513  3936 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-23 16:35:36.595  1513  3936 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-23 16:35:36.595  1513  3936 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-23 16:35:36.595  1513  3936 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-23 16:35:36.595  1513  3936 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-23 16:35:36.595  1513  3936 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-23 16:35:36.595  1513  3936 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-23 16:35:36.595  1513  3936 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-23 16:35:36.595  1513  3936 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-23 16:35:36.595  1513  3936 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-23 16:35:37.000  1513  3936 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-23 16:35:37.000  1513  3936 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-23 16:35:37.001  1513  3936 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 16:35:37.001  1513  3936 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:35:37.055  1513  3936 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-23 16:35:37.055  1513  3936 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-23 16:35:37.055  1513  3936 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-23 16:35:37.055  1513  3936 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-23 16:35:37.055  1513  3936 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-23 16:35:37.055  1513  3936 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-23 16:35:37.055  1513  3936 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-23 16:35:37.055  1513  3936 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-23 16:35:37.055  1513  3936 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-23 16:35:37.055  1513  3936 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-23 16:35:37.055  1513  3936 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-23 16:35:37.055  1513  3936 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-23 16:35:37.055  1513  3936 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-23 16:35:37.495  1513  3936 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-23 16:35:37.496  1513  3936 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-23 16:35:37.496  1513  3936 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:35:37.497  1513  3936 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:35:37.537  1513  3936 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-23 16:35:37.537  1513  3936 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-23 16:35:37.537  1513  3936 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-23 16:35:37.537  1513  3936 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-23 16:35:37.537  1513  3936 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-23 16:35:37.537  1513  3936 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-23 16:35:37.537  1513  3936 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-23 16:35:37.537  1513  3936 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-23 16:35:37.537  1513  3936 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-23 16:35:37.537  1513  3936 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-23 16:35:37.537  1513  3936 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-23 16:35:37.537  1513  3936 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-23 16:35:37.537  1513  3936 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-23 16:35:37.757   876  1309 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 4, 7 -> obsolete
,08-23 16:36:01.265  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:36:01.278  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:36:01.285  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:36:01.345  1513  2260 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-23 16:36:01.345  1513  2260 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-23 16:36:01.345  1513  2260 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 16:36:01.346  1513  2260 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:36:01.395  3861  3861 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-23 16:36:01.396  3861  3861 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-23 16:36:01.397  3861  3861 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-23 16:36:03.228  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 16:36:03.229  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-23 16:36:03.229  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 16:36:03.229  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:36:03.247  3220  3951 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-23 16:36:03.247  3220  3951 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 16:36:03.247  3220  3951 E HttpOperation: 	at jdm.a(PG:82)
08-23 16:36:03.247  3220  3951 E HttpOperation: 	at jcs.o(PG:406)
08-23 16:36:03.247  3220  3951 E HttpOperation: 	at jcn.a(PG:1379)
08-23 16:36:03.247  3220  3951 E HttpOperation: 	at jcs.i(PG:143)
08-23 16:36:03.247  3220  3951 E HttpOperation: 	at blb.a(PG:3937)
08-23 16:36:03.247  3220  3951 E HttpOperation: 	at czp.a(PG:18188)
08-23 16:36:03.247  3220  3951 E HttpOperation: 	at czp.a(PG:9081)
08-23 16:36:03.247  3220  3951 E HttpOperation: 	at czq.run(PG:1686)
08-23 16:36:03.247  3220  3951 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 16:36:03.247  3220  3951 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 16:36:03.247  3220  3951 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 16:36:03.247  3220  3951 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 16:36:03.247  3220  3951 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 16:36:03.247  3220  3951 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 16:36:03.247  3220  3951 E HttpOperation: 	at jdj.a(PG:4091)
08-23 16:36:03.247  3220  3951 E HttpOperation: 	at jdj.a(PG:1125)
08-23 16:36:03.247  3220  3951 E HttpOperation: 	at jdm.a(PG:77)
08-23 16:36:03.247  3220  3951 E HttpOperation: 	... 12 more
08-23 16:36:03.247  3220  3951 E HttpOperation: Caused by: faj: BadAuthentication
08-23 16:36:03.247  3220  3951 E HttpOperation: 	at fal.a(PG:38)
08-23 16:36:03.247  3220  3951 E HttpOperation: 	at jdj.a(PG:4089)
08-23 16:36:03.247  3220  3951 E HttpOperation: 	... 14 more
,08-23 16:36:03.300  1513  1978 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 16:36:03.300  1513  1978 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-23 16:36:03.300  1513  1978 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 16:36:03.300  1513  1978 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:36:03.329  3220  3951 E HttpOperation: [getmobileexperiments] Unexpected exception
08-23 16:36:03.329  3220  3951 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 16:36:03.329  3220  3951 E HttpOperation: 	at jdm.a(PG:82)
08-23 16:36:03.329  3220  3951 E HttpOperation: 	at jcs.o(PG:406)
08-23 16:36:03.329  3220  3951 E HttpOperation: 	at jcn.a(PG:1379)
08-23 16:36:03.329  3220  3951 E HttpOperation: 	at jcs.i(PG:143)
08-23 16:36:03.329  3220  3951 E HttpOperation: 	at hec.a(PG:42)
08-23 16:36:03.329  3220  3951 E HttpOperation: 	at hee.a(PG:102)
08-23 16:36:03.329  3220  3951 E HttpOperation: 	at czr.a(PG:65)
08-23 16:36:03.329  3220  3951 E HttpOperation: 	at kka.a(PG:108)
08-23 16:36:03.329  3220  3951 E HttpOperation: 	at czp.a(PG:19176)
08-23 16:36:03.329  3220  3951 E HttpOperation: 	at czp.a(PG:9081)
08-23 16:36:03.329  3220  3951 E HttpOperation: 	at czq.run(PG:1686)
08-23 16:36:03.329  3220  3951 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 16:36:03.329  3220  3951 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 16:36:03.329  3220  3951 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 16:36:03.329  3220  3951 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 16:36:03.329  3220  3951 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 16:36:03.329  3220  3951 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 16:36:03.329  3220  3951 E HttpOperation: 	at jdj.a(PG:4091)
08-23 16:36:03.329  3220  3951 E HttpOperation: 	at jdj.a(PG:1125)
08-23 16:36:03.329  3220  3951 E HttpOperation: 	at jdm.a(PG:77)
08-23 16:36:03.329  3220  3951 E HttpOperation: 	... 15 more
08-23 16:36:03.329  3220  3951 E HttpOperation: Caused by: faj: BadAuthentication
08-23 16:36:03.329  3220  3951 E HttpOperation: 	at fal.a(PG:38)
08-23 16:36:03.329  3220  3951 E HttpOperation: 	at jdj.a(PG:4089)
08-23 16:36:03.329  3220  3951 E HttpOperation: 	... 17 more
08-23 16:36:03.329  3220  3951 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-23 16:36:03.329  3220  3951 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-23 16:36:03.329  3220  3951 E ExperimentLoader: 	at jdm.a(PG:82)
08-23 16:36:03.329  3220  3951 E ExperimentLoader: 	at jcs.o(PG:406)
08-23 16:36:03.329  3220  3951 E ExperimentLoader: 	at jcn.a(PG:1379)
08-23 16:36:03.329  3220  3951 E ExperimentLoader: 	at jcs.i(PG:143)
08-23 16:36:03.329  3220  3951 E ExperimentLoader: 	at hec.a(PG:42)
08-23 16:36:03.329  3220  3951 E ExperimentLoader: 	at hee.a(PG:102)
08-23 16:36:03.329  3220  3951 E ExperimentLoader: 	at czr.a(PG:65)
08-23 16:36:03.329  3220  3951 E ExperimentLoader: 	at kka.a(PG:108)
08-23 16:36:03.329  3220  3951 E ExperimentLoader: 	at czp.a(PG:19176)
08-23 16:36:03.329  3220  3951 E ExperimentLoader: 	at czp.a(PG:9081)
08-23 16:36:03.329  3220  3951 E ExperimentLoader: 	at czq.run(PG:1686)
08-23 16:36:03.329  3220  3951 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 16:36:03.329  3220  3951 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 16:36:03.329  3220  3951 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 16:36:03.329  3220  3951 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 16:36:03.329  3220  3951 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-23 16:36:03.329  3220  3951 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 16:36:03.329  3220  3951 E ExperimentLoader: 	at jdj.a(PG:4091)
08-23 16:36:03.329  3220  3951 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-23 16:36:03.329  3220  3951 E ExperimentLoader: 	at jdm.a(PG:77)
08-23 16:36:03.329  3220  3951 E ExperimentLoader: 	... 15 more
08-23 16:36:03.329  3220  3951 E ExperimentLoader: Caused by: faj: BadAuthentication
08-23 16:36:03.329  3220  3951 E ExperimentLoader: 	at fal.a(PG:38)
08-23 16:36:03.329  3220  3951 E ExperimentLoader: 	at jdj.a(PG:4089)
08-23 16:36:03.329  3220  3951 E ExperimentLoader: 	... 17 more
,08-23 16:36:03.491   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 183269, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-23 16:36:21.338   876  3585 D NetlinkSocketObserver: NeighborEvent{elapsedMs=201650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 16:36:29.911  1868  1907 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-23 16:36:29.911  1868  1907 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-23 16:36:29.963  1513  1513 I ConfigService: onCreate
,08-23 16:36:33.769  2986  3955 V KeepSync: Connecting to GoogleApiClient
,08-23 16:36:33.769   876  1946 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-23 16:36:33.813  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:36:33.814  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:36:33.843  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-23 16:36:33.843  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-23 16:36:33.843  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:36:33.843  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:36:33.861  1710  3956 V BaseAuthAsyncOperation: access token request failed
,08-23 16:36:33.862  2986  3955 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-23 16:36:33.912  1513  2261 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-23 16:36:33.912  1513  2261 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-23 16:36:33.912  1513  2261 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:36:33.912  1513  2261 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:36:33.929  2986  3955 E KeepSync: IOException
08-23 16:36:33.929  2986  3955 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-23 16:36:33.929  2986  3955 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-23 16:36:33.929  2986  3955 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-23 16:36:33.929  2986  3955 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-23 16:36:33.929  2986  3955 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-23 16:36:33.929  2986  3955 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-23 16:36:33.929  2986  3955 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-23 16:36:33.929  2986  3955 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-23 16:36:33.929  2986  3955 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-23 16:36:33.929  2986  3955 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-23 16:36:33.929  2986  3955 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-23 16:36:33.929  2986  3955 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-23 16:36:33.929  2986  3955 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-23 16:36:33.929  2986  3955 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-23 16:36:33.929  2986  3955 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 16:36:33.929  2986  3955 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 16:36:33.929  2986  3955 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-23 16:36:33.929  2986  3955 E KeepSync: 	... 10 more
08-23 16:36:33.929  2986  3955 W KeepSync: Sync result 2
,08-23 16:36:33.934   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 211058, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-23 16:36:35.015  1513  1513 I ConfigService: onDestroy
,08-23 16:37:00.081  1513  2058 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-23 16:37:04.150  3761  3959 I BooksSync: Starting books sync for 61035162, extras: ade
,08-23 16:37:04.183  3761  3960 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-23 16:37:04.208  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:37:04.211  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:37:04.254  1513  2261 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 16:37:04.254  1513  2261 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-23 16:37:04.255  1513  2261 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:37:04.255  1513  2261 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:37:04.304  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:37:04.307  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:37:04.345  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-23 16:37:04.345  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 16:37:04.345  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 16:37:04.345  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:37:04.369  3761  3960 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-23 16:37:04.370  3761  3959 E BooksSync: Soft error
08-23 16:37:04.370  3761  3959 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 16:37:04.370  3761  3959 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 16:37:04.371  3761  3959 E BooksSync: Sync error
08-23 16:37:04.371  3761  3959 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 16:37:04.371  3761  3959 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 16:37:04.372  3761  3959 I BooksSync: Finished books sync
,08-23 16:37:04.380   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 215326, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-23 16:37:05.276  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:37:05.278  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:37:05.291  3479  3961 V GoogleAuthProtoRequest: [280] a.<init>: mAccountName set to: thalitester@gmail.com
,08-23 16:37:05.321  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-23 16:37:05.321  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-23 16:37:05.321  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:37:05.321  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:37:05.341  3479  3961 W ExperimentUpdateService: [280] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-23 16:37:05.342  3479  3961 W ExperimentUpdateService: [280] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 16:37:05.342  3479  3961 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 16:37:05.342  3479  3961 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-23 16:37:05.342  3479  3961 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-23 16:37:05.342  3479  3961 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-23 16:37:05.342  3479  3961 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-23 16:37:05.342  3479  3961 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-23 16:37:05.342  3479  3961 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-23 16:37:05.342  3479  3961 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-23 16:37:05.342  3479  3961 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-23 16:37:05.342  3479  3961 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-23 16:37:34.794  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:37:34.797  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:37:34.822  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-23 16:37:34.822  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 16:37:34.822  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:37:34.822  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:37:34.840  3220  3964 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-23 16:37:34.840  3220  3964 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 16:37:34.840  3220  3964 E HttpOperation: 	at jdm.a(PG:82)
08-23 16:37:34.840  3220  3964 E HttpOperation: 	at jcs.o(PG:406)
08-23 16:37:34.840  3220  3964 E HttpOperation: 	at jcn.a(PG:1379)
08-23 16:37:34.840  3220  3964 E HttpOperation: 	at jcs.i(PG:143)
08-23 16:37:34.840  3220  3964 E HttpOperation: 	at blb.a(PG:3937)
08-23 16:37:34.840  3220  3964 E HttpOperation: 	at czp.a(PG:18188)
08-23 16:37:34.840  3220  3964 E HttpOperation: 	at czp.a(PG:9081)
08-23 16:37:34.840  3220  3964 E HttpOperation: 	at czq.run(PG:1686)
08-23 16:37:34.840  3220  3964 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 16:37:34.840  3220  3964 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 16:37:34.840  3220  3964 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 16:37:34.840  3220  3964 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 16:37:34.840  3220  3964 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 16:37:34.840  3220  3964 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 16:37:34.840  3220  3964 E HttpOperation: 	at jdj.a(PG:4091)
08-23 16:37:34.840  3220  3964 E HttpOperation: 	at jdj.a(PG:1125)
08-23 16:37:34.840  3220  3964 E HttpOperation: 	at jdm.a(PG:77)
08-23 16:37:34.840  3220  3964 E HttpOperation: 	... 12 more
08-23 16:37:34.840  3220  3964 E HttpOperation: Caused by: faj: BadAuthentication
08-23 16:37:34.840  3220  3964 E HttpOperation: 	at fal.a(PG:38)
08-23 16:37:34.840  3220  3964 E HttpOperation: 	at jdj.a(PG:4089)
08-23 16:37:34.840  3220  3964 E HttpOperation: 	... 14 more
,08-23 16:37:34.907  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 16:37:34.907  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-23 16:37:34.907  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 16:37:34.907  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:37:34.953  3220  3964 E HttpOperation: [getmobileexperiments] Unexpected exception
08-23 16:37:34.953  3220  3964 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 16:37:34.953  3220  3964 E HttpOperation: 	at jdm.a(PG:82)
08-23 16:37:34.953  3220  3964 E HttpOperation: 	at jcs.o(PG:406)
08-23 16:37:34.953  3220  3964 E HttpOperation: 	at jcn.a(PG:1379)
08-23 16:37:34.953  3220  3964 E HttpOperation: 	at jcs.i(PG:143)
08-23 16:37:34.953  3220  3964 E HttpOperation: ,	at hec.a(PG:42)
08-23 16:37:34.953  3220  3964 E HttpOperation: 	at hee.a(PG:102)
08-23 16:37:34.953  3220  3964 E HttpOperation: 	at czr.a(PG:65)
08-23 16:37:34.953  3220  3964 E HttpOperation: 	at kka.a(PG:108)
08-23 16:37:34.953  3220  3964 E HttpOperation: 	at czp.a(PG:19176)
08-23 16:37:34.953  3220  3964 E HttpOperation: 	at czp.a(PG:9081)
08-23 16:37:34.953  3220  3964 E HttpOperation: 	at czq.run(PG:1686)
08-23 16:37:34.953  3220  3964 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 16:37:34.953  3220  3964 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 16:37:34.953  3220  3964 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 16:37:34.953  3220  3964 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 16:37:34.953  3220  3964 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 16:37:34.953  3220  3964 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 16:37:34.953  3220  3964 E HttpOperation: 	at jdj.a(PG:4091)
08-23 16:37:34.953  3220  3964 E HttpOperation: 	at jdj.a(PG:1125)
08-23 16:37:34.953  3220  3964 E HttpOperation: 	at jdm.a(PG:77)
08-23 16:37:34.953  3220  3964 E HttpOperation: 	... 15 more
08-23 16:37:34.953  3220  3964 E HttpOperation: Caused by: faj: BadAuthentication
08-23 16:37:34.953  3220  3964 E HttpOperation: 	at fal.a(PG:38)
08-23 16:37:34.953  3220  3964 E HttpOperation: 	at jdj.a(PG:4089)
08-23 16:37:34.953  3220  3964 E HttpOperation: 	... 17 more
,08-23 16:37:34.954  3220  3964 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-23 16:37:34.954  3220  3964 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-23 16:37:34.954  3220  3964 E ExperimentLoader: 	at jdm.a(PG:82)
08-23 16:37:34.954  3220  3964 E ExperimentLoader: 	at jcs.o(PG:406)
08-23 16:37:34.954  3220  3964 E ExperimentLoader: 	at jcn.a(PG:1379)
08-23 16:37:34.954  3220  3964 E ExperimentLoader: 	at jcs.i(PG:143)
08-23 16:37:34.954  3220  3964 E ExperimentLoader: 	at hec.a(PG:42)
08-23 16:37:34.954  3220  3964 E ExperimentLoader: 	at hee.a(PG:102)
08-23 16:37:34.954  3220  3964 E ExperimentLoader: 	at czr.a(PG:65)
08-23 16:37:34.954  3220  3964 E ExperimentLoader: 	at kka.a(PG:108)
08-23 16:37:34.954  3220  3964 E ExperimentLoader: 	at czp.a(PG:19176)
08-23 16:37:34.954  3220  3964 E ExperimentLoader: 	at czp.a(PG:9081)
08-23 16:37:34.954  3220  3964 E ExperimentLoader: 	at czq.run(PG:1686)
08-23 16:37:34.954  3220  3964 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 16:37:34.954  3220  3964 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 16:37:34.954  3220  3964 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 16:37:34.954  3220  3964 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 16:37:34.954  3220  3964 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-23 16:37:34.954  3220  3964 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 16:37:34.954  3220  3964 E ExperimentLoader: 	at jdj.a(PG:4091)
08-23 16:37:34.954  3220  3964 E ExperimentLoader: 	at jdj.a(PG:1125)
08-23 16:37:34.954  3220  3964 E ExperimentLoader: 	at jdm.a(PG:77)
08-23 16:37:34.954  3220  3964 E ExperimentLoader: 	... 15 more
08-23 16:37:34.954  3220  3964 E ExperimentLoader: Caused by: faj: BadAuthentication
08-23 16:37:34.954  3220  3964 E ExperimentLoader: 	at fal.a(PG:38)
08-23 16:37:34.954  3220  3964 E ExperimentLoader: 	at jdj.a(PG:4089)
08-23 16:37:34.954  3220  3964 E ExperimentLoader: 	... 17 more
,08-23 16:37:35.097   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 246454, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-23 16:38:34.191  2986  3972 V KeepSync: Connecting to GoogleApiClient
,08-23 16:38:34.192   876  2211 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-23 16:38:34.255  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:38:34.257  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:38:34.313  1513  2260 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-23 16:38:34.314  1513  2260 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-23 16:38:34.314  1513  2260 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:38:34.314  1513  2260 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:38:34.338  1710  3973 V BaseAuthAsyncOperation: access token request failed
,08-23 16:38:34.339  2986  3972 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-23 16:38:34.391  1513  2260 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-23 16:38:34.391  1513  2260 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-23 16:38:34.391  1513  2260 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-23 16:38:34.391  1513  2260 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:38:34.405  2986  3972 E KeepSync: IOException
08-23 16:38:34.405  2986  3972 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-23 16:38:34.405  2986  3972 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
,08-23 16:38:34.405  2986  3972 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-23 16:38:34.405  2986  3972 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-23 16:38:34.405  2986  3972 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-23 16:38:34.405  2986  3972 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-23 16:38:34.405  2986  3972 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-23 16:38:34.405  2986  3972 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-23 16:38:34.405  2986  3972 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-23 16:38:34.405  2986  3972 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-23 16:38:34.405  2986  3972 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-23 16:38:34.405  2986  3972 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-23 16:38:34.405  2986  3972 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-23 16:38:34.405  2986  3972 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-23 16:38:34.405  2986  3972 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 16:38:34.405  2986  3972 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 16:38:34.405  2986  3972 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-23 16:38:34.405  2986  3972 E KeepSync: 	... 10 more
08-23 16:38:34.405  2986  3972 W KeepSync: Sync result 2
,08-23 16:38:34.417   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 334353, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-23 16:39:03.165   876  3585 D NetlinkSocketObserver: NeighborEvent{elapsedMs=363477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-23 16:39:05.513  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:39:05.519  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:39:05.536  3479  3978 V GoogleAuthProtoRequest: [281] a.<init>: mAccountName set to: thalitester@gmail.com
,08-23 16:39:05.560  1513  1978 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-23 16:39:05.560  1513  1978 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-23 16:39:05.560  1513  1978 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:39:05.561  1513  1978 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:39:05.576  3479  3978 W ExperimentUpdateService: [281] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-23 16:39:05.577  3479  3978 W ExperimentUpdateService: [281] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 16:39:05.577  3479  3978 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 16:39:05.577  3479  3978 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-23 16:39:05.577  3479  3978 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-23 16:39:05.577  3479  3978 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-23 16:39:05.577  3479  3978 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-23 16:39:05.577  3479  3978 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
,08-23 16:39:05.577  3479  3978 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-23 16:39:05.577  3479  3978 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-23 16:39:05.577  3479  3978 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-23 16:39:05.577  3479  3978 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-23 16:39:10.601  3761  3979 I BooksSync: Starting books sync for 61035162, extras: ade
,08-23 16:39:10.634  3761  3980 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-23 16:39:10.649  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:39:10.651  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:39:10.679  1513  2261 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 16:39:10.680  1513  2261 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 16:39:10.680  1513  2261 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 16:39:10.680  1513  2261 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:39:10.709  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:39:10.711  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:39:10.738  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 16:39:10.738  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-23 16:39:10.738  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:39:10.738  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:39:10.757  3761  3980 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-23 16:39:10.758  3761  3979 E BooksSync: Soft error
08-23 16:39:10.758  3761  3979 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 16:39:10.758  3761  3979 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 16:39:10.758  3761  3979 E BooksSync: Sync error
08-23 16:39:10.758  3761  3979 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 16:39:10.758  3761  3979 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 16:39:10.758  3761  3979 I BooksSync: Finished books sync
,08-23 16:39:10.770   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 370870, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-23 16:39:41.101  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:39:41.102  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:39:41.128  1513  1978 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 16:39:41.128  1513  1978 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 16:39:41.128  1513  1978 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:39:41.128  1513  1978 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:39:41.157  3220  3983 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-23 16:39:41.157  3220  3983 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 16:39:41.157  3220  3983 E HttpOperation: 	at jdm.a(PG:82)
08-23 16:39:41.157  3220  3983 E HttpOperation: 	at jcs.o(PG:406)
08-23 16:39:41.157  3220  3983 E HttpOperation: 	at jcn.a(PG:1379)
08-23 16:39:41.157  3220  3983 E HttpOperation: 	at jcs.i(PG:143)
08-23 16:39:41.157  3220  3983 E HttpOperation: 	at blb.a(PG:3937)
08-23 16:39:41.157  3220  3983 E HttpOperation: 	at czp.a(PG:18188)
08-23 16:39:41.157  3220  3983 E HttpOperation: 	at czp.a(PG:9081)
08-23 16:39:41.157  3220  3983 E HttpOperation: 	at czq.run(PG:1686)
08-23 16:39:41.157  3220  3983 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 16:39:41.157  3220  3983 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 16:39:41.157  3220  3983 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 16:39:41.157  3220  3983 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 16:39:41.157  3220  3983 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 16:39:41.157  3220  3983 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 16:39:41.157  3220  3983 E HttpOperation: 	at jdj.a(PG:4091)
08-23 16:39:41.157  3220  3983 E HttpOperation: 	at jdj.a(PG:1125)
08-23 16:39:41.157  3220  3983 E HttpOperation: 	at jdm.a(PG:77)
08-23 16:39:41.157  3220  3983 E HttpOperation: 	... 12 more
08-23 16:39:41.157  3220  3983 E HttpOperation: Caused by: faj: BadAuthentication
08-23 16:39:41.157  3220  3983 E HttpOperation: 	at fal.a(PG:38)
08-23 16:39:41.157  3220  3983 E HttpOperation: 	at jdj.a(PG:4089)
08-23 16:39:41.157  3220  3983 E HttpOperation: 	... 14 more
,08-23 16:39:41.242  1513  3847 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-23 16:39:41.242  1513  3847 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 16:39:41.242  1513  3847 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:39:41.242  1513  3847 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:39:41.269  3220  3983 E HttpOperation: [getmobileexperiments] Unexpected exception
08-23 16:39:41.269  3220  3983 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 16:39:41.269  3220  3983 E HttpOperation: 	at jdm.a(PG:82)
08-23 16:39:41.269  3220  3983 E HttpOperation: 	at jcs.o(PG:406)
08-23 16:39:41.269  3220  3983 E HttpOperation: 	at jcn.a(PG:1379)
08-23 16:39:41.269  3220  3983 E HttpOperation: 	at jcs.i(PG:143)
08-23 16:39:41.269  3220  3983 E HttpOperation: 	at hec.a(PG:42)
08-23 16:39:41.269  3220  3983 E HttpOperation: 	at hee.a(PG:102)
08-23 16:39:41.269  3220  3983 E HttpOperation: 	at czr.a(PG:65)
08-23 16:39:41.269  3220  3983 E HttpOperation: 	at kka.a(PG:108)
08-23 16:39:41.269  3220  3983 E HttpOperation: 	at czp.a(PG:19176)
08-23 16:39:41.269  3220  3983 E HttpOperation: 	at czp.a(PG:9081)
08-23 16:39:41.269  3220  3983 E HttpOperation: 	at czq.run(PG:1686)
08-23 16:39:41.269  3220  3983 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 16:39:41.269  3220  3983 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 16:39:41.269  3220  3983 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 16:39:41.269  3220  3983 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 16:39:41.269  3220  3983 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 16:39:41.269  3220  3983 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 16:39:41.269  3220  3983 E HttpOperation: 	at jdj.a(PG:4091)
08-23 16:39:41.269  3220  3983 E HttpOperation: 	at jdj.a(PG:1125)
08-23 16:39:41.269  3220  3983 E HttpOperation: 	at jdm.a(PG:77)
08-23 16:39:41.269  3220  3983 E HttpOperation: 	... 15 more
08-23 16:39:41.269  3220  3983 E HttpOperation: Caused by: faj: BadAuthentication
08-23 16:39:41.269  3220  3983 E HttpOperation: 	at fal.a(PG:38)
08-23 16:39:41.269  3220  3983 E HttpOperation: 	at jdj.a(PG:4089)
08-23 16:39:41.269  3220  3983 E HttpOperation: 	... 17 more
,08-23 16:39:41.270  3220  3983 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-23 16:39:41.270  3220  3983 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-23 16:39:41.270  3220  3983 E ExperimentLoader: 	at jdm.a(PG:82)
08-23 16:39:41.270  3220  3983 E ExperimentLoader: 	at jcs.o(PG:406)
08-23 16:39:41.270  3220  3983 E ExperimentLoader: 	at jcn.a(PG:1379)
08-23 16:39:41.270  3220  3983 E ExperimentLoader: 	at jcs.i(PG:143)
08-23 16:39:41.270  3220  3983 E ExperimentLoader: 	at hec.a(PG:42)
08-23 16:39:41.270  3220  3983 E ExperimentLoader: 	at hee.a(PG:102)
08-23 16:39:41.270  3220  3983 E ExperimentLoader: 	at czr.a(PG:65)
08-23 16:39:41.270  3220  3983 E ExperimentLoader: 	at kka.a(PG:108)
08-23 16:39:41.270  3220  3983 E ExperimentLoader: 	at czp.a(PG:19176)
08-23 16:39:41.270  3220  3983 E ExperimentLoader: 	at czp.a(PG:9081)
08-23 16:39:41.270  3220  3983 E ExperimentLoader: 	at czq.run(PG:1686)
08-23 16:39:41.270  3220  3983 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 16:39:41.270  3220  3983 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 16:39:41.270  3220  3983 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 16:39:41.270  3220  3983 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 16:39:41.270  3220  3983 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-23 16:39:41.270  3220  3983 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 16:39:41.270  3220  3983 E ExperimentLoader: 	at jdj.a(PG:4091)
08-23 16:39:41.270  3220  3983 E ExperimentLoader: 	at jdj.a(PG:1125)
08-23 16:39:41.270  3220  3983 E ExperimentLoader: 	at jdm.a(PG:77)
08-23 16:39:41.270  3220  3983 E ExperimentLoader: 	... 15 more
08-23 16:39:41.270  3220  3983 E ExperimentLoader: Caused by: faj: BadAuthentication
08-23 16:39:41.270  3220  3983 E ExperimentLoader: 	at fal.a(PG:38)
08-23 16:39:41.270  3220  3983 E ExperimentLoader: 	at jdj.a(PG:4089)
08-23 16:39:41.270  3220  3983 E ExperimentLoader: 	... 17 more
,08-23 16:39:41.363   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 400710, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-23 16:39:42.618   876  3585 D NetlinkSocketObserver: NeighborEvent{elapsedMs=402930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 16:40:00.640  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:40:00.655  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:40:00.659  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:40:00.720  1513  2260 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-23 16:40:00.721  1513  2260 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-23 16:40:00.721  1513  2260 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:40:00.721  1513  2260 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:40:00.765  1513  2260 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-23 16:40:00.765  1513  2260 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-23 16:40:00.765  1513  2260 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-23 16:40:00.765  1513  2260 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-23 16:40:00.765  1513  2260 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-23 16:40:00.765  1513  2260 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-23 16:40:00.765  1513  2260 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-23 16:40:00.779  3861  3895 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-23 16:40:00.779  3861  3895 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-23 16:40:00.779  3861  3895 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-23 16:40:00.779  3861  3895 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-23 16:40:00.779  3861  3895 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-23 16:40:00.779  3861  3895 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-23 16:40:00.779  3861  3895 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-23 16:40:02.937   876  3585 D NetlinkSocketObserver: NeighborEvent{elapsedMs=423250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-23 16:40:44.911   876  3585 D NetlinkSocketObserver: NeighborEvent{elapsedMs=465224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 16:41:01.978   876  3585 D NetlinkSocketObserver: NeighborEvent{elapsedMs=482290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-23 16:41:45.711   876  3585 D NetlinkSocketObserver: NeighborEvent{elapsedMs=526023, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 16:42:34.716  2986  4000 V KeepSync: Connecting to GoogleApiClient
,08-23 16:42:34.718   876  1382 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-23 16:42:34.758  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:42:34.760  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:42:34.780  1513  2260 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-23 16:42:34.780  1513  2260 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-23 16:42:34.781  1513  2260 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 16:42:34.781  1513  2260 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:42:34.793  1710  4001 V BaseAuthAsyncOperation: access token request failed
,08-23 16:42:34.794  2986  4000 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-23 16:42:34.829  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-23 16:42:34.830  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-23 16:42:34.830  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:42:34.830  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:42:34.850  2986  4000 E KeepSync: IOException
08-23 16:42:34.850  2986  4000 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-23 16:42:34.850  2986  4000 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-23 16:42:34.850  2986  4000 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-23 16:42:34.850  2986  4000 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-23 16:42:34.850  2986  4000 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-23 16:42:34.850  2986  4000 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-23 16:42:34.850  2986  4000 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-23 16:42:34.850  2986  4000 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-23 16:42:34.850  2986  4000 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-23 16:42:34.850  2986  4000 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-23 16:42:34.850  2986  4000 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-23 16:42:34.850  2986  4000 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-23 16:42:34.850  2986  4000 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-23 16:42:34.850  2986  4000 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-23 16:42:34.850  2986  4000 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 16:42:34.850  2986  4000 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 16:42:34.850  2986  4000 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-23 16:42:34.850  2986  4000 E KeepSync: 	... 10 more
,08-23 16:42:34.850  2986  4000 W KeepSync: Sync result 2
,08-23 16:42:34.860   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 574930, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-23 16:43:05.764  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:43:05.769  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:43:05.781  3479  4005 V GoogleAuthProtoRequest: [282] a.<init>: mAccountName set to: thalitester@gmail.com
,08-23 16:43:05.814  1513  2260 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-23 16:43:05.814  1513  2260 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-23 16:43:05.814  1513  2260 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:43:05.814  1513  2260 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,08-23 16:43:05.828  3479  4005 W ExperimentUpdateService: [282] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-23 16:43:05.828  3479  4005 W ExperimentUpdateService: [282] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 16:43:05.828  3479  4005 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 16:43:05.828  3479  4005 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117),
08-23 16:43:05.828  3479  4005 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-23 16:43:05.828  3479  4005 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-23 16:43:05.828  3479  4005 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-23 16:43:05.828  3479  4005 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-23 16:43:05.828  3479  4005 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-23 16:43:05.828  3479  4005 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-23 16:43:05.828  3479  4005 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-23 16:43:05.828  3479  4005 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-23 16:43:23.211  3761  4006 I BooksSync: Starting books sync for 61035162, extras: ade
,08-23 16:43:23.240  3761  4007 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-23 16:43:23.252  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:43:23.254  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:43:23.284  1513  3847 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 16:43:23.284  1513  3847 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-23 16:43:23.284  1513  3847 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 16:43:23.284  1513  3847 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:43:23.338  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:43:23.341  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:43:23.365  1513  3847 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-23 16:43:23.365  1513  3847 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-23 16:43:23.365  1513  3847 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:43:23.365  1513  3847 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:43:23.382  3761  4007 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-23 16:43:23.382  3761  4006 E BooksSync: Soft error
08-23 16:43:23.382  3761  4006 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 16:43:23.382  3761  4006 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-23 16:43:23.383  3761  4006 E BooksSync: Sync error
08-23 16:43:23.383  3761  4006 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 16:43:23.383  3761  4006 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-23 16:43:23.383  3761  4006 I BooksSync: Finished books sync
,08-23 16:43:23.385   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 623436, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-23 16:44:06.471   876  3585 D NetlinkSocketObserver: NeighborEvent{elapsedMs=666784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-23 16:44:50.138   876  3585 D NetlinkSocketObserver: NeighborEvent{elapsedMs=710451, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 16:45:06.218   876  3585 D NetlinkSocketObserver: NeighborEvent{elapsedMs=726531, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-23 16:45:23.356  1513  2058 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-23 16:45:49.978   876  3585 D NetlinkSocketObserver: NeighborEvent{elapsedMs=770291, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 16:50:35.378  3861  3861 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,08-23 16:50:35.406  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:50:35.605  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:50:35.607  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:50:35.708  1513  3847 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-23 16:50:35.708  1513  3847 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-23 16:50:35.708  1513  3847 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:50:35.709  1513  3847 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:50:35.763  3861  3861 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-23 16:50:35.792  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:50:35.894  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-23 16:50:35.895  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-23 16:50:35.895  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:50:35.896  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:50:36.001  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:50:36.095  1513  3847 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-23 16:50:36.096  1513  3847 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.,
,08-23 16:50:36.096  1513  3847 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:50:36.097  1513  3847 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:50:36.164  3861  3861 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-23 16:50:36.498  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:50:36.537  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-23 16:50:36.538  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-23 16:50:36.538  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:50:36.539  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:50:36.581  3861  3861 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-23 16:50:36.582  3861  3861 D Finsky  : [1] WearSupportService.startHygiene: disabled
,08-23 16:50:36.585  3861  3861 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,08-23 16:50:36.593  3861  3907 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-23 16:50:36.597  3861  3861 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,08-23 16:50:40.417   876  3585 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1060730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-23 16:50:51.513  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:50:51.527  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:50:51.531  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:50:51.574  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-23 16:50:51.574  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-23 16:50:51.574  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:50:51.574  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:50:51.619  3861  3861 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-23 16:50:51.619  3861  3861 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-23 16:50:51.620  3861  3861 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,08-23 16:50:51.844   876  3585 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1072157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 16:51:11.768  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:51:11.770  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:51:11.781  3479  4038 V GoogleAuthProtoRequest: [283] a.<init>: mAccountName set to: thalitester@gmail.com
,08-23 16:51:11.826  1513  2260 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-23 16:51:11.826  1513  2260 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-23 16:51:11.826  1513  2260 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:51:11.826  1513  2260 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:51:11.847  3479  4038 W ExperimentUpdateService: [283] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-23 16:51:11.847  3479  4038 W ExperimentUpdateService: [283] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 16:51:11.847  3479  4038 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-23 16:51:11.847  3479  4038 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-23 16:51:11.847  3479  4038 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-23 16:51:11.847  3479  4038 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-23 16:51:11.847  3479  4038 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-23 16:51:11.847  3479  4038 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-23 16:51:11.847  3479  4038 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-23 16:51:11.847  3479  4038 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-23 16:51:11.847  3479  4038 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-23 16:51:11.847  3479  4038 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-23 16:51:12.012  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:51:12.051  1513  1978 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-23 16:51:12.052  1513  1978 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-23 16:51:12.052  1513  1978 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:51:12.052  1513  1978 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:51:12.091  3861  3861 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-23 16:51:12.091  3861  3861 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-23 16:51:12.091  3861  3861 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,08-23 16:51:32.500  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:51:32.521  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:51:32.527  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:51:32.609  1513  1978 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-23 16:51:32.609  1513  1978 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-23 16:51:32.610  1513  1978 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:51:32.610  1513  1978 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:51:32.683  3861  3861 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-23 16:51:32.684  3861  3861 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-23 16:51:32.694  3861  3861 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-23 16:51:53.061  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:51:53.090  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:51:53.097  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:51:53.175  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-23 16:51:53.175  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-23 16:51:53.175  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 16:51:53.176  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:51:53.202  3861  3861 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-23 16:51:53.203  3861  3861 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-23 16:51:53.203  3861  3861 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-23 16:52:13.439  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:52:13.451  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:52:13.456  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:52:13.519  1513  1978 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-23 16:52:13.519  1513  1978 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-23 16:52:13.520  1513  1978 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 16:52:13.520  1513  1978 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:52:13.561  3861  3861 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-23 16:52:13.561  3861  3861 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-23 16:52:13.562  3861  3861 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-23 16:52:33.935  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:52:33.950  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:52:33.955  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 16:52:34.006  1513  1978 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-23 16:52:34.006  1513  1978 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-23 16:52:34.006  1513  1978 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 16:52:34.006  1513  1978 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 16:52:34.036  3861  3861 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-23 16:52:34.037  3861  3861 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-23 16:52:34.037  3861  3861 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-23 16:53:18.140   876   888 I UsageStatsService: User[0] Flushing usage stats to disk
,08-23 16:53:32.688  1513  2058 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,TIME-OUT KILL (timeout was 1400000ms)
```
