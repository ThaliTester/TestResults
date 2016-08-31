#### Test 834526170a57107_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-31 15:54:26.562   977   977 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
08-31 15:54:26.563   977   977 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,08-31 15:54:26.592   977   977 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
08-31 15:54:26.592   977   977 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
08-31 15:54:27.252  3433  3433 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-31 15:54:27.257  3433  3433 D AndroidRuntime: CheckJNI is OFF
08-31 15:54:27.301  3433  3433 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-31 15:54:27.354  3433  3433 I Radio-JNI: register_android_hardware_Radio DONE
08-31 15:54:27.378  3433  3433 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-31 15:54:27.384   874   885 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-31 15:54:27.421  2031  2045 W SearchService: Abort, client detached.
08-31 15:54:27.450  3433  3433 D AndroidRuntime: Shutting down VM
08-31 15:54:27.450  2031  2031 I HotwordDetector: Closing mic
08-31 15:54:27.450  2031  2321 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@7c3b4c4
08-31 15:54:27.451  2031  2340 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-31 15:54:27.471   874  1976 I ActivityManager: Start proc 3442:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-31 15:54:27.484  2031  2031 W ErrorReporter: reportError [type: 29, code: 917507]: null
08-31 15:54:27.504   377  2342 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-31 15:54:27.505   377  2342 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-31 15:54:27.509   377  1276 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-31 15:54:27.511  2031  2335 I MicroRecognitionRnrImpl: Detection finished
08-31 15:54:27.511  2031  2324 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-31 15:54:27.576  3442  3442 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-31 15:54:27.577   977   977 I kickstart: STATUS: Received file 'm9kefs2'
08-31 15:54:27.578   977   977 I kickstart: STATUS: 950272 bytes transferred in 0.984760 seconds
08-31 15:54:27.578   977   977 I kickstart: STATUS: Successfully downloaded files from target 
08-31 15:54:27.578   977   977 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
08-31 15:54:27.581   977   977 I kickstart: STATUS: Sahara protocol completed
08-31 15:54:27.609  3442  3442 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-31 15:54:27.692  3442  3442 I LibraryLoader: Time to load native libraries: 78 ms (timestamps 2455-2533)
,08-31 15:54:27.692  3442  3442 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 15:54:27.711  3442  3442 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {842e63d}
,08-31 15:54:27.711  3442  3442 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 15:54:27.711  3442  3442 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 15:54:27.718  3442  3442 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-31 15:54:27.719  3442  3442 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 15:54:27.752  3442  3457 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,08-31 15:54:27.759  3442  3442 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-31 15:54:27.771  3442  3442 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-31 15:54:27.771  3442  3442 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 15:54:27.771  3442  3442 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 15:54:27.771  3442  3442 I Adreno  : Build Date                       : 10/20/15
,08-31 15:54:27.771  3442  3442 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 15:54:27.771  3442  3442 I Adreno  : Local Branch                     : M14
08-31 15:54:27.771  3442  3442 I Adreno  : Remote Branch                    : 
08-31 15:54:27.771  3442  3442 I Adreno  : Remote Branch                    : 
08-31 15:54:27.771  3442  3442 I Adreno  : Reconstruct Branch               : 
,08-31 15:54:27.814   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c86fafb:true
,08-31 15:54:27.883  3442  3442 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 15:54:27.896  3442  3442 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-31 15:54:27.937  3442  3480 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-31 15:54:27.953  3442  3466 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-31 15:54:27.976  3442  3480 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 15:54:28.030   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +580ms
,08-31 15:54:28.030  1866  1866 I Keyboard.Facilitator: onFinishInput()
,08-31 15:54:28.066  3442  3442 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3442
,08-31 15:54:28.148  3442  3442 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 15:54:28.272   874  1373 I ActivityManager: Killing 2822:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,08-31 15:54:28.304   874  1373 I ActivityManager: Killing 3119:com.qualcomm.telephony/1001 (adj 15): empty #18,
,08-31 15:54:28.409  3442  3483 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1697117904
,08-31 15:54:28.415  3442  3483 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 15:54:28.415  3442  3483 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 15:54:28.415  3442  3483 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 15:54:28.415  3442  3483 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 15:54:28.415  3442  3483 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-31 15:54:28.415  3442  3483 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e74c31 added. We now have 1 listener(s)
,08-31 15:54:28.418  3442  3483 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-31 15:54:28.419  3442  3483 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 15:54:28.421  3442  3483 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 15:54:28.421  3442  3483 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 15:54:28.427  3442  3483 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 15:54:28.427  3442  3483 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 15:54:28.427  3442  3483 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 15:54:28.427  3442  3483 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-31 15:54:28.427  3442  3483 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 15:54:28.427  3442  3483 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 15:54:28.427  3442  3483 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 15:54:28.427  3442  3483 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 15:54:28.427  3442  3483 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 15:54:28.427  3442  3483 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 15:54:28.427  3442  3483 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 15:54:28.427  3442  3483 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 15:54:28.427  3442  3483 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 15:54:28.427  3442  3483 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-31 15:54:28.427  3442  3483 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6e0284 added. We now have 1 listener(s)
,08-31 15:54:28.427  3442  3483 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:54:28.430   874  1306 D WifiService: New client listening to asynchronous messages
,08-31 15:54:28.431  3442  3483 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 15:54:28.431  3442  3483 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-31 15:54:28.431  3442  3483 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 15:54:28.431  3442  3483 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 15:54:28.431  3442  3483 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 15:54:28.433  3442  3483 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:54:28.433  3442  3483 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-31 15:54:28.435  3442  3483 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:54:28.435  3442  3483 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:54:28.435  3442  3483 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:54:28.435  3442  3483 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 15:54:28.435  3442  3483 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:54:28.435  3442  3483 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:54:28.435  3442  3483 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:54:28.435  3442  3483 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:54:28.435  3442  3483 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:54:28.435  3442  3483 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-31 15:54:28.435  3442  3483 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:54:28.436  3442  3483 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 15:54:28.472  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:54:28.474  3442  3442 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 15:54:28.635  1515  1515 I ConfigService: onDestroy
,08-31 15:54:29.436  3442  3492 W jxcore-log: Initializing JXcore engine
,08-31 15:54:29.436  3442  3492 W jxcore-log: JXcore engine is ready
,08-31 15:54:29.472  3492  3492 W Thread-286: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8957 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-31 15:54:29.472  3492  3492 W Thread-286: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10754]" dev="sockfs" ino=10754 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-31 15:54:29.472  3492  3492 W Thread-286: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-31 15:54:29.472  3492  3492 W Thread-286: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25660]" dev="sockfs" ino=25660 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-31 15:54:29.489  3442  3492 W jxcore-log: Starting JXcore engine
,08-31 15:54:29.572  3442  3492 W jxcore-log: Platform android
08-31 15:54:29.572  3442  3492 W jxcore-log: 
,08-31 15:54:29.573  3442  3492 W jxcore-log: Process ARCH arm
08-31 15:54:29.573  3442  3492 W jxcore-log: 
,08-31 15:54:29.821  3442  3492 I jxcore-log: JXcore Cordova bridge is ready!
08-31 15:54:29.821  3442  3492 I jxcore-log: 
,08-31 15:54:29.822  3442  3492 W jxcore-log: JXcore engine is started
,08-31 15:54:29.834  3442  3483 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 15:54:29.840  3442  3442 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 15:54:38.045   874   887 I ActivityManager: Waited long enough for: ServiceRecord{925fd09 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,08-31 15:54:39.483  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 15:54:39.483  3442  3492 I jxcore-log: 
,08-31 15:54:39.486  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 15:54:39.486  3442  3492 I jxcore-log: 
,08-31 15:54:39.487  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:54:39.487  3442  3492 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:54:39.487  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:54:39.487  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 15:54:39.487  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:54:39.487  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:54:39.487  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:54:39.487  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:54:39.487  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:54:39.488  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:54:39.488  3442  3492 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:54:39.490  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 15:54:39.490  3442  3492 I jxcore-log: 
,08-31 15:54:39.492  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 15:54:39.492  3442  3492 I jxcore-log: 
,08-31 15:54:39.992  3442  3492 D executeNativeTests: Running unit tests
,08-31 15:54:40.050  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 15:54:40.050  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893a5cb added. We now have 2 listener(s)
08-31 15:54:40.051  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 15:54:40.051  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 15:54:40.051  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 15:54:40.051  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 15:54:40.052  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 added. We now have 2 listener(s)
,08-31 15:54:40.052  3442  3492 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:54:40.052  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 15:54:40.053  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:54:40.055  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:54:40.056  3442  3492 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:54:40.056  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:54:40.056  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 15:54:40.056  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:54:40.056  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:54:40.056  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:54:40.056  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:54:40.056  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:54:40.056  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:54:40.056  3442  3492 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:54:40.057  3442  3492 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-31 15:54:40.057  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:54:40.063  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 15:54:40.064  3442  3492 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 15:54:40.064  3442  3492 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 15:54:40.068  3442  3492 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-31 15:54:40.069  3442  3492 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 15:54:40.070  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 15:54:40.070  3442  3492 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-31 15:54:40.070  3442  3492 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 15:54:40.071  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 15:54:40.073  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:54:40.073  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 15:54:40.075  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 15:54:40.076  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.076  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 15:54:40.076  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:54:40.076  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893a5cb removed from the list
,08-31 15:54:40.076  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.077  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 removed from the list
,08-31 15:54:40.077  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:54:40.077  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:54:40.078  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 15:54:40.078  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:54:40.080  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:54:40.080  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 15:54:40.080  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.081  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
,08-31 15:54:40.083  3442  3492 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-31 15:54:40.084  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 15:54:40.084  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:54:40.084  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 15:54:40.084  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:54:40.084  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 15:54:40.084  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.084  3442  3492 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893a5cb not in the list
,08-31 15:54:40.084  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.084  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.084  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 15:54:40.084  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.084  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:54:40.085  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.085  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:54:40.085  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:54:40.085  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 15:54:40.085  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.085  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.098  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-31 15:54:40.098  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 15:54:40.098  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-31 15:54:40.098  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 15:54:40.098  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 15:54:40.098  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-31 15:54:40.099  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 15:54:40.099  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-31 15:54:40.099  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-31 15:54:40.099  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 15:54:40.099  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-31 15:54:40.099  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 15:54:40.099  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 15:54:40.099  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-31 15:54:40.099  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 15:54:40.099  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-31 15:54:40.099  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 15:54:40.099  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 15:54:40.099  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 15:54:40.099  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-31 15:54:40.099  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 15:54:40.099  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 15:54:40.099  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 15:54:40.099  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 15:54:40.099  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 15:54:40.100  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 15:54:40.100  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 15:54:40.100  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-31 15:54:40.100  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 15:54:40.100  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 15:54:40.100  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 15:54:40.100  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:54:40.100  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:54:40.100  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:54:40.100  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:54:40.100  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.100  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.100  3442  3492 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893a5cb not in the list
,08-31 15:54:40.100  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.100  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.100  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:54:40.101  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.101  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.101  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.101  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.101  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:54:40.101  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:54:40.101  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.101  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
,08-31 15:54:40.102  3442  3492 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 15:54:40.103  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:54:40.104  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:54:40.104  3442  3492 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:54:40.104  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:54:40.104  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 15:54:40.104  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:54:40.104  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:54:40.104  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:54:40.104  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:54:40.104  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:54:40.104  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:54:40.104  3442  3492 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:54:40.104  3442  3492 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:54:40.105  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:54:40.105  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:54:40.105  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 15:54:40.105  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 15:54:40.105  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:54:40.105  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 15:54:40.107  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-31 15:54:40.108  3442  3492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-31 15:54:40.108  3442  3492 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 15:54:40.109  3442  3492 I io.jxcore.node.ConnectionHelper: start: OK
08-31 15:54:40.109  3442  3442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-31 15:54:40.110  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:54:40.110  3442  3492 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
08-31 15:54:40.111  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:54:40.111  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:54:40.112  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 15:54:40.112  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.112  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 15:54:40.112  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 15:54:40.112  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 15:54:40.112  3442  3492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 15:54:40.112  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 15:54:40.113  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 15:54:40.113  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:54:40.114  3442  3492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 15:54:40.114  3442  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:54:40.114  3442  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:54:40.114  3442  3442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 15:54:40.114  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:54:40.114  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.115  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:54:40.115  3442  3492 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893a5cb not in the list
08-31 15:54:40.115  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.115  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.115  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:54:40.115  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.116  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.116  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.116  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:54:40.116  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:54:40.116  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.116  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.117  3442  3492 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 15:54:40.119  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:54:40.120  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:54:40.120  3442  3492 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:54:40.120  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:54:40.120  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 15:54:40.120  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:54:40.120  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:54:40.120  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:54:40.120  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:54:40.120  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:54:40.120  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:54:40.120  3442  3492 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:54:40.120  3442  3492 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:54:40.120  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:54:40.120  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 15:54:40.120  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 15:54:40.121  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:54:40.121  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 15:54:40.121  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:54:40.122  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-31 15:54:40.123  3442  3492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-31 15:54:40.123  3442  3492 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-31 15:54:40.123  3442  3442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-31 15:54:40.123  3442  3492 I io.jxcore.node.ConnectionHelper: start: OK
08-31 15:54:40.123  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:54:40.123  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:54:40.123  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 15:54:40.123  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.123  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 15:54:40.123  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 15:54:40.123  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 15:54:40.124  3442  3492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 15:54:40.124  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 15:54:40.124  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 15:54:40.124  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:54:40.124  3442  3492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 15:54:40.125  3442  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:54:40.125  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:54:40.125  3442  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:54:40.125  3442  3492 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 15:54:40.125  3442  3442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 15:54:40.125  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:54:40.125  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:54:40.125  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:54:40.125  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.125  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:54:40.125  3442  3492 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893a5cb not in the list
08-31 15:54:40.125  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.125  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.126  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:54:40.126  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.126  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.126  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.127  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:54:40.127  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:54:40.127  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.127  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.127  3442  3492 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-31 15:54:40.128  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:54:40.128  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:54:40.128  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:54:40.128  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:54:40.128  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.128  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.128  3442  3492 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893a5cb not in the list
08-31 15:54:40.129  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.129  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.129  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:54:40.129  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.129  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.129  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.129  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.129  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:54:40.129  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:54:40.129  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.130  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.130  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 15:54:40.131  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:54:40.131  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:54:40.131  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:54:40.131  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:54:40.131  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.131  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.131  3442  3492 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893a5cb not in the list
08-31 15:54:40.131  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.131  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.131  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:54:40.131  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.131  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.131  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.132  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.132  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:54:40.132  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:54:40.132  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.132  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.133  3442  3492 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-31 15:54:40.133  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:54:40.133  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:54:40.133  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:54:40.133  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:54:40.133  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.133  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.133  3442  3492 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893a5cb not in the list
08-31 15:54:40.133  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.133  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.133  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:54:40.133  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.134  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.134  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.134  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.134  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:54:40.134  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:54:40.134  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.134  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.135  3442  3492 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-31 15:54:40.135  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:54:40.135  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:54:40.135  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:54:40.135  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:54:40.135  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.135  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.135  3442  3492 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893a5cb not in the list
08-31 15:54:40.135  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.135  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.135  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:54:40.135  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.135  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.136  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.136  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.136  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:54:40.136  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:54:40.136  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.136  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.136  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 15:54:40.138  3442  3492 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 15:54:40.138  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 15:54:40.138  3442  3492 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 15:54:40.138  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 15:54:40.138  3442  3492 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 15:54:40.138  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:54:40.138  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:54:40.140  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:54:40.140  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:54:40.140  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.140  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.141  3442  3492 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893a5cb not in the list
08-31 15:54:40.141  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.141  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.141  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:54:40.141  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.141  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.141  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.141  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:54:40.143  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:54:40.143  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:54:40.143  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.143  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.144  3442  3492 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:54:40.145  3442  3492 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 15:54:40.145  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 15:54:40.149  3442  3492 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:54:40.149  3442  3492 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 15:54:40.149  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 15:54:40.149  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 15:54:40.149  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 15:54:40.149  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 15:54:40.149  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 15:54:40.150  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 15:54:40.150  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 15:54:40.150  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 15:54:40.150  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 15:54:40.150  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 15:54:40.150  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 15:54:40.150  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 15:54:40.150  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 15:54:40.150  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 15:54:40.150  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 15:54:40.150  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 15:54:40.150  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 15:54:40.150  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 15:54:40.150  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 15:54:40.150  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 15:54:40.151  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 15:54:40.151  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 15:54:40.151  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 15:54:40.151  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 15:54:40.151  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 15:54:40.151  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 15:54:40.151  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 15:54:40.151  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 15:54:40.151  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 15:54:40.151  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 15:54:40.151  3442  3492 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 15:54:40.151  3442  3492 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 15:54:40.152  3442  3492 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 15:54:40.152  3442  3492 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:54:40.152  3442  3492 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 15:54:40.152  3442  3492 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 15:54:40.152  3442  3492 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:54:40.152  3442  3492 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 15:54:40.152  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-31 15:54:40.153  3442  3492 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
08-31 15:54:40.153  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-31 15:54:40.154  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-31 15:54:40.154  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-31 15:54:40.154  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 15:54:40.154  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 15:54:40.154  3442  3492 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 15:54:40.154  3442  3492 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:54:40.155  3442  3492 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 15:54:40.155  3442  3494 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 350)
08-31 15:54:40.155  3442  3494 E BluetoothDevice: Bluetooth is not enabled
08-31 15:54:40.155  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:54:40.155  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:54:40.155  3442  3494 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): null (thread ID: 350)
08-31 15:54:40.155  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:54:40.155  3442  3494 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 350)
08-31 15:54:40.155  3442  3494 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): null (thread ID: 350)
08-31 15:54:40.155  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:54:40.155  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.156  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.156  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-31 15:54:40.156  3442  3442 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> 00:11:22:33:44:55]: Failed to connect (tried 1 time(s)): null
,08-31 15:54:40.156  3442  3442 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: Failed to connect (tried 1 time(s)): null
08-31 15:54:40.157  3442  3442 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 15:54:40.157  3442  3442 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 15:54:40.160  3442  3494 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Failed to find a thread with ID 350
08-31 15:54:40.160  3442  3494 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 350)
,08-31 15:54:40.160  3442  3492 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893a5cb not in the list
,08-31 15:54:40.160  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.161  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
,08-31 15:54:40.161  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:54:40.161  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 15:54:40.161  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:54:40.161  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.161  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.161  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-31 15:54:40.161  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:54:40.161  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 15:54:40.161  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
,08-31 15:54:40.162  3442  3495 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 350
08-31 15:54:40.162  3442  3492 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-31 15:54:40.162  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 15:54:40.162  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:54:40.162  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:54:40.163  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:54:40.163  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 15:54:40.164  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.164  3442  3492 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893a5cb not in the list
08-31 15:54:40.164  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.164  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.164  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 15:54:40.164  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.164  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.164  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.164  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.164  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 15:54:40.164  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:54:40.164  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.164  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.165  3442  3492 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 15:54:40.165  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:54:40.165  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 15:54:40.165  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:54:40.165  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:54:40.165  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.165  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.166  3442  3492 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893a5cb not in the list
,08-31 15:54:40.166  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.166  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.166  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:54:40.166  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.166  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.166  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 15:54:40.166  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.166  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:54:40.166  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:54:40.166  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.166  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.167  3442  3492 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,08-31 15:54:40.167  3442  3492 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 15:54:40.167  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 15:54:40.167  3442  3492 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-31 15:54:40.167  3442  3492 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 15:54:40.167  3442  3492 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 15:54:40.167  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-31 15:54:40.167  3442  3492 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 15:54:40.167  3442  3492 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 15:54:40.167  3442  3492 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 15:54:40.167  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 15:54:40.167  3442  3492 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-31 15:54:40.168  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 15:54:40.168  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:54:40.168  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:54:40.168  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:54:40.168  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 15:54:40.168  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.168  3442  3492 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893a5cb not in the list
08-31 15:54:40.168  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.168  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.168  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:54:40.168  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 15:54:40.168  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.168  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.168  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.169  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:54:40.169  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:54:40.169  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 15:54:40.169  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.169  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:54:40.169  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.169  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.169  3442  3492 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893a5cb not in the list
08-31 15:54:40.169  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.169  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.169  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 15:54:40.169  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.170  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.170  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.170  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.170  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 15:54:40.170  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.170  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.170  3442  3492 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893a5cb not in the list
08-31 15:54:40.170  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:54:40.170  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 15:54:40.170  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:54:40.170  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 15:54:40.170  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.170  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.170  3442  3492 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893a5cb not in the list
08-31 15:54:40.170  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.170  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.171  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:54:40.171  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.171  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.171  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.171  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.171  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:54:40.171  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:54:40.171  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.171  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.172  3442  3492 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 15:54:40.173  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:54:40.173  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
08-31 15:54:40.173  3442  3492 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
08-31 15:54:40.173  3442  3442 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
08-31 15:54:40.173  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 15:54:40.173  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:54:40.173  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 15:54:40.173  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.173  3442  3492 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
08-31 15:54:40.174  3442  3442 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-31 15:54:40.174  3442  3492 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893a5cb not in the list
08-31 15:54:40.174  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.174  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 15:54:40.174  3442  3492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 15:54:40.174  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 15:54:40.174  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.174  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.174  3442  3492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 15:54:40.175  3442  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:54:40.175  3442  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:54:40.175  3442  3442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 15:54:40.175  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.175  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:54:40.175  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:54:40.175  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:54:40.175  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:54:40.176  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.176  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.176  3442  3492 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893a5cb not in the list
08-31 15:54:40.176  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.176  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.176  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:54:40.176  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.176  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.176  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.177  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.177  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:54:40.177  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:54:40.177  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.177  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.178  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 15:54:40.178  3442  3492 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 15:54:40.178  3442  3492 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-31 15:54:40.178  3442  3492 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 15:54:40.178  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 15:54:40.179  3442  3492 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 15:54:40.179  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:54:40.179  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:54:40.179  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:54:40.179  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:54:40.179  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.179  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.179  3442  3492 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893a5cb not in the list
08-31 15:54:40.179  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.179  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.179  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:54:40.179  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.179  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.180  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.180  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.180  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:54:40.180  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 15:54:40.180  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.180  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.183  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:54:40.183  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:54:40.183  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:54:40.184  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:54:40.184  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.184  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.184  3442  3492 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893a5cb not in the list
08-31 15:54:40.184  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.184  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.184  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:54:40.185  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.185  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.185  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.185  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.186  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:54:40.186  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:54:40.186  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.186  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.188  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:54:40.188  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:54:40.188  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:54:40.188  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:54:40.188  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.188  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.189  3442  3492 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@893a5cb not in the list
08-31 15:54:40.189  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.189  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.189  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:54:40.189  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.189  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.189  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:54:40.189  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:54:40.190  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:54:40.190  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:54:40.190  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:54:40.190  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@963a1a8 not in the list
08-31 15:54:40.192  3442  3492 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-31 15:54:40.192  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 15:54:40.192  3442  3492 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-31 15:54:40.192  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 15:54:40.192  3442  3492 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-31 15:54:40.192  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 15:54:40.195  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 15:54:40.195  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-31 15:54:40.196  3442  3492 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 15:54:40.197  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 15:54:40.197  3442  3492 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-31 15:54:40.197  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 15:54:40.197  3442  3492 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-31 15:54:40.197  3442  3492 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-31 15:54:40.198  3442  3492 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-31 15:54:40.198  3442  3492 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-31 15:54:40.199  3442  3492 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-31 15:54:40.199  3442  3492 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-31 15:54:40.199  3442  3492 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 15:54:40.200  3442  3492 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-31 15:54:40.201  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:54:40.201  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@45770f2 added. We now have 2 listener(s)
08-31 15:54:40.201  3442  3492 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:54:40.203   874  1716 D WifiService: setWifiEnabled: true pid=3442, uid=10000
08-31 15:54:40.203   874  1716 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 15:54:40.208  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:54:40.208  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ad10343 added. We now have 3 listener(s)
08-31 15:54:40.208  3442  3492 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:54:40.209  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:54:40.209  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:54:40.210  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:54:40.211  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2cefdc0 added. We now have 4 listener(s)
08-31 15:54:40.211  3442  3492 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:54:40.213  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:54:40.213  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5f2baf9 added. We now have 5 listener(s)
08-31 15:54:40.213  3442  3492 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:54:40.214   874   884 D WifiService: setWifiEnabled: false pid=3442, uid=10000
08-31 15:54:40.214   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 15:54:40.216   874   891 I ActivityManager: Start proc 3497:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
08-31 15:54:40.218   874  1305 D WifiConfigStore: Loading config and enabling all networks 
08-31 15:54:40.222  3442  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:54:40.222  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:54:40.222  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:54:40.222  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 15:54:40.222  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:54:40.222  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:54:40.222  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:54:40.222  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:54:40.222  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:54:40.222  3442  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:54:40.222  3442  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:54:40.234   874   887 I ActivityManager: Start proc 3509:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-31 15:54:40.234  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:54:40.235  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:54:40.235  3442  3492 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:54:40.235  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:54:40.235  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 15:54:40.235  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:54:40.235  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:54:40.235  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:54:40.235  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:54:40.235  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:54:40.235  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:54:40.235  3442  3492 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:54:40.236  3442  3492 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:54:40.236   874  1305 D WifiConfigStore: loaded 0 passpoint configs
08-31 15:54:40.236  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:54:40.237   874  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-31 15:54:40.237   874  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-31 15:54:40.238   874  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-31 15:54:40.238   874  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-31 15:54:40.238   874  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-31 15:54:40.238   874  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-31 15:54:40.279  3509  3509 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-31 15:54:40.289   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-31 15:54:40.290   373   873 D CommandListener: Setting iface cfg
08-31 15:54:40.291   874  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '109 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 109 Failed to set address (No such device)'
08-31 15:54:40.291   874  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 15:54:40.300   874  1304 D WifiNative-HAL: p2pGetDeviceAddress
,08-31 15:54:40.300   874  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-31 15:54:40.311   874  1305 D WifiConfigStore: Retrieve network priorities after PNO.
08-31 15:54:40.313  3442  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:54:40.313  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:54:40.313  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:54:40.313  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 15:54:40.313  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:54:40.313  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:54:40.313  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:54:40.313  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:54:40.313  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:54:40.313  3442  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:54:40.314  3442  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:54:40.314  3442  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:54:40.314  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:54:40.314  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:54:40.314  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 15:54:40.314  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:54:40.314  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:54:40.314  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:54:40.314  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:54:40.314  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:54:40.314  3442  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:54:40.314  3442  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:54:40.316  3497  3497 D AdapterServiceConfig: Adding HeadsetService
08-31 15:54:40.316  3497  3497 D AdapterServiceConfig: Adding A2dpService
08-31 15:54:40.316  3497  3497 D AdapterServiceConfig: Adding HidService
08-31 15:54:40.316  3497  3497 D AdapterServiceConfig: Adding HealthService
08-31 15:54:40.317  3497  3497 D AdapterServiceConfig: Adding PanService
08-31 15:54:40.317  3497  3497 D AdapterServiceConfig: Adding GattService
08-31 15:54:40.317  3497  3497 D AdapterServiceConfig: Adding BluetoothMapService
08-31 15:54:40.319  2107  2300 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 15:54:40.336  3509  3509 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-31 15:54:40.342   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d5e86fd:true
,08-31 15:54:40.343  3497  3497 D BluetoothAdapterState: make() - Creating AdapterState
,08-31 15:54:40.345  3497  3497 I bt_bluedroid: init
,08-31 15:54:40.346  3497  3534 I BluetoothAdapterState: Entering OffState
,08-31 15:54:40.349  3497  3536 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 15:54:40.350  3497  3536 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-31 15:54:40.350  3497  3536 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-31 15:54:40.350  3497  3536 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 15:54:40.351  3497  3497 I bt_bluedroid: get_profile_interface socket
08-31 15:54:40.352  3497  3539 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 15:54:40.352  3497  3497 I bt_bluedroid: get_profile_interface sdp
08-31 15:54:40.353  3497  3539 D BluetoothAdapterProperties: Name is: Nexus 6
08-31 15:54:40.354  3497  3514 I bt_bluedroid: config_hci_snoop_log
,08-31 15:54:40.355   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-31 15:54:40.358  3497  3534 D BluetoothAdapterState: Current state: OFF, message: 0
,08-31 15:54:40.358  3497  3534 D BluetoothAdapterProperties: Setting state to 14
08-31 15:54:40.358  3497  3534 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-31 15:54:40.360  3497  3534 D BluetoothBondStateMachine: make
,08-31 15:54:40.361   874  1373 I ActivityManager: Killing 2802:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-31 15:54:40.361  3497  3541 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 15:54:40.404  3497  3534 I BluetoothAdapterState: Entering PendingCommandState
08-31 15:54:40.404  3497  3497 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-31 15:54:40.407  3497  3497 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
,08-31 15:54:40.408  3497  3497 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 15:54:40.408  3497  3497 D BtGatt.GattService: Received start request. Starting profile...
08-31 15:54:40.409  3497  3497 D BtGatt.GattService: start()
08-31 15:54:40.409  3497  3497 I bt_bluedroid: get_profile_interface gatt
,08-31 15:54:40.409  3497  3497 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
08-31 15:54:40.409  3497  3497 D BtGatt.AdvertiseManager: advertise manager created
,08-31 15:54:40.420  3497  3497 V BluetoothAdapterState: isTurningOff()=false
08-31 15:54:40.420  3497  3497 V BluetoothAdapterState: isTurningOn()=false
,08-31 15:54:40.421  3497  3497 V BluetoothAdapterState: isBleTurningOn()=true
08-31 15:54:40.421  3497  3497 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 15:54:40.422  3497  3534 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-31 15:54:40.422  3497  3534 I bt_bluedroid: enable
08-31 15:54:40.422  3497  3536 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-31 15:54:40.423  3497  3536 I bt_hci  : start_up
,08-31 15:54:40.437  3497  3536 I bt_vendor: alloc value 0xb39b0189
,08-31 15:54:40.437  3497  3536 I bt_vendor: init
08-31 15:54:40.437  3497  3536 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-31 15:54:40.437  3497  3536 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-31 15:54:40.543  3497  3536 D bt_hci  : start_up starting async portion
,08-31 15:54:40.544  3497  3544 I bt_hci  : event_finish_startup
,08-31 15:54:40.544  3497  3544 I bt_hci_h4: hal_open
08-31 15:54:40.544  3497  3544 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 15:54:40.557  3497  3544 I bt_userial_vendor: device fd = 51 open
,08-31 15:54:40.587  3497  3544 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 15:54:40.619  3497  3544 D bt_hwcfg: Chipset BCM4354A2
08-31 15:54:40.619  3497  3544 D bt_hwcfg: Target name = [BCM4354A2]
,08-31 15:54:40.620  3497  3544 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-31 15:54:40.676  3442  3442 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 15:54:41.511  3497  3544 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-31 15:54:41.513  3497  3544 D bt_hwcfg: Settlement delay -- 100 ms
,08-31 15:54:41.513  3497  3544 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 15:54:41.631  3497  3544 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 15:54:41.633  3497  3544 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-31 15:54:41.660  3497  3544 I bt_hwcfg: vendor lib fwcfg completed
,08-31 15:54:41.660  3497  3544 I bt_vendor: firmware callback
08-31 15:54:41.660  3497  3544 I bt_hci  : firmware_config_callback
,08-31 15:54:41.673  3497  3547 I bt_btu  : btu_task pending for preload complete event
08-31 15:54:41.673  3497  3547 I bt_btu_task: Bluetooth chip preload is complete
08-31 15:54:41.674  3497  3547 I bt_btu  : btu_task received preload complete event
,08-31 15:54:41.685  3497  3547 I         : BTE_InitTraceLevels -- TRC_HCI
08-31 15:54:41.685  3497  3547 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 15:54:41.685  3497  3547 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-31 15:54:41.686  3497  3547 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-31 15:54:41.686  3497  3547 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 15:54:41.686  3497  3547 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 15:54:41.686  3497  3547 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 15:54:41.687  3497  3547 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 15:54:41.687  3497  3547 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 15:54:41.687  3497  3547 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 15:54:41.687  3497  3547 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 15:54:41.688  3497  3547 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 15:54:41.688  3497  3547 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 15:54:41.688  3497  3547 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 15:54:41.689  3497  3547 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 15:54:41.826  3497  3547 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb392dd9d
,08-31 15:54:41.826  3497  3547 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb392dd9d 
,08-31 15:54:41.856  3497  3539 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-31 15:54:41.857  3497  3539 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-31 15:54:41.857  3497  3539 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-31 15:54:41.859  3497  3539 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 15:54:41.863  3497  3539 D BluetoothAdapterProperties: Scan Mode:20
,08-31 15:54:41.863  3497  3539 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 15:54:41.863  3497  3539 D bt_hci  : do_postload posting postload work item
08-31 15:54:41.864  3497  3544 I bt_hci  : event_postload
,08-31 15:54:41.864  3497  3544 I bt_vendor: sco_config_cb
08-31 15:54:41.864  3497  3544 I bt_hci  : sco_config_callback postload finished.
08-31 15:54:41.869  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:54:41.870  3497  3544 I bt_vendor: low_power_mode_cb
,08-31 15:54:41.873  3497  3539 D bt_bte_conf: Device ID record 1 : primary
08-31 15:54:41.873  3497  3539 D bt_bte_conf:   vendorId            = 000f
,08-31 15:54:41.873  3497  3539 D bt_bte_conf:   vendorIdSource      = 0001
,08-31 15:54:41.873  3497  3539 D bt_bte_conf:   product             = 1200
,08-31 15:54:41.873  3497  3539 D bt_bte_conf:   version             = 1436
,08-31 15:54:41.873  3497  3539 D bt_bte_conf:   clientExecutableURL = 
,08-31 15:54:41.873  3497  3539 D bt_bte_conf:   serviceDescription  = 
,08-31 15:54:41.873  3497  3539 D bt_bte_conf:   documentationURL    = 
,08-31 15:54:41.873  3497  3539 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-31 15:54:41.874  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:54:41.874  3497  3536 D bt_stack_manager: event_start_up_stack finished
08-31 15:54:41.874  3497  3534 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-31 15:54:41.875  3497  3534 D BluetoothAdapterProperties: Setting state to 15
,08-31 15:54:41.875  3497  3534 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-31 15:54:41.876  3497  3534 I BluetoothAdapterState: Entering BleOnState
,08-31 15:54:41.883  3497  3534 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-31 15:54:41.884  3497  3534 D BluetoothAdapterProperties: Setting state to 11
08-31 15:54:41.884  3497  3534 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-31 15:54:41.890  3497  3497 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
,08-31 15:54:41.893  3497  3497 D HeadsetService: Received start request. Starting profile...
,08-31 15:54:41.896  3497  3497 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 15:54:41.896  3497  3497 D HeadsetStateMachine: make
,08-31 15:54:41.902  3497  3534 I BluetoothAdapterState: Entering PendingCommandState
,08-31 15:54:41.906  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:54:41.908  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:54:41.921   874   887 I ActivityManager: Start proc 3554:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-31 15:54:41.922  3497  3497 D HeadsetStateMachine: max_hf_connections = 1
,08-31 15:54:41.922  3497  3497 I bt_bluedroid: get_profile_interface handsfree
,08-31 15:54:41.923  3497  3539 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-31 15:54:41.923  3497  3539 E bt_btif : btif_hf_upstreams_evt: Invalid index -1,
,08-31 15:54:41.927  3497  3497 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
08-31 15:54:41.928   874   874 D BluetoothA2dp: Proxy object connected
08-31 15:54:41.929  3497  3497 D A2dpService: Received start request. Starting profile...
08-31 15:54:41.929  3497  3497 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-31 15:54:41.930  3497  3497 I bt_bluedroid: get_profile_interface avrcp
,08-31 15:54:41.943  3497  3497 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 15:54:41.948  3497  3497 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-31 15:54:41.948  3497  3497 D A2dpStateMachine: make
,08-31 15:54:41.950  3497  3497 I bt_bluedroid: get_profile_interface a2dp
,08-31 15:54:41.950  3497  3539 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-31 15:54:41.953  3497  3497 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 15:54:41.953  3497  3567 D A2dpStateMachine: Enter Disconnected: -2
,08-31 15:54:41.954  3497  3497 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
,08-31 15:54:41.955  1346  1346 D BluetoothInputDevice: Proxy object connected
,08-31 15:54:41.955  1346  1346 D HidProfile: Bluetooth service connected
08-31 15:54:41.956  3497  3497 D HidService: Received start request. Starting profile...
,08-31 15:54:41.956  3497  3497 I bt_bluedroid: get_profile_interface hidhost
08-31 15:54:41.956  3497  3539 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb390f3e5,
08-31 15:54:41.956  3497  3497 D HidService: setHidService(): set to: null
,08-31 15:54:41.956  3497  3539 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-31 15:54:41.956  3497  3497 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 15:54:41.957  3497  3497 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
,08-31 15:54:41.958  3497  3497 D HealthService: Received start request. Starting profile...
08-31 15:54:41.959  3497  3497 I bt_bluedroid: get_profile_interface health
,08-31 15:54:41.960  3497  3497 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-31 15:54:41.960  3497  3497 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
08-31 15:54:41.962  1346  1346 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 15:54:41.962  3497  3497 D PanService: Received start request. Starting profile...
08-31 15:54:41.962  3497  3497 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 15:54:41.962  3497  3497 I bt_bluedroid: get_profile_interface pan
08-31 15:54:41.962  1346  1346 D PanProfile: Bluetooth service connected
08-31 15:54:41.962  3497  3539 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-31 15:54:41.969  3497  3497 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
08-31 15:54:41.971  1346  1346 D BluetoothMap: Proxy object connected
08-31 15:54:41.971  3497  3497 D BluetoothMapService: Received start request. Starting profile...
08-31 15:54:41.971  3497  3497 D BluetoothMapService: start()
08-31 15:54:41.971  1346  1346 D MapProfile: Bluetooth service connected
08-31 15:54:41.971  1346  1346 D BluetoothMap: getConnectedDevices()
08-31 15:54:41.972  1346  1346 D BluetoothMap: Bluetooth is Not enabled
08-31 15:54:41.973  3497  3497 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-31 15:54:41.974  3497  3497 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-31 15:54:41.974  3497  3497 D BluetoothMapAppObserver: createReceiver()
08-31 15:54:41.975  3497  3497 D BluetoothMapAppObserver: initObservers()
08-31 15:54:41.975  3497  3497 D BluetoothMapAppObserver: getEnabledAccountItems()
08-31 15:54:41.983  3497  3552 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-31 15:54:41.984  3497  3497 V BluetoothAdapterState: isTurningOff()=false
08-31 15:54:41.984  3497  3497 V BluetoothAdapterState: isTurningOn()=true
08-31 15:54:41.984  3497  3497 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:54:41.984  3497  3497 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:54:41.985  3554  3554 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-31 15:54:41.986  3497  3497 V BluetoothAdapterState: isTurningOff()=false
08-31 15:54:41.986  3497  3497 V BluetoothAdapterState: isTurningOn()=true
08-31 15:54:41.986  3497  3497 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:54:41.986  3497  3497 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:54:41.986  3497  3497 V BluetoothAdapterState: isTurningOff()=false
08-31 15:54:41.986  3497  3497 V BluetoothAdapterState: isTurningOn()=true
08-31 15:54:41.986  3497  3497 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:54:41.986  3497  3497 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:54:41.987  3497  3497 V BluetoothAdapterState: isTurningOff()=false
08-31 15:54:41.987  3497  3497 V BluetoothAdapterState: isTurningOn()=true
08-31 15:54:41.987  3497  3497 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:54:41.987  3497  3497 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:54:41.987  3497  3497 V BluetoothAdapterState: isTurningOff()=false
08-31 15:54:41.987  3497  3497 V BluetoothAdapterState: isTurningOn()=true
08-31 15:54:41.987  3497  3497 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:54:41.987  3497  3497 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:54:41.988  3497  3497 V BluetoothAdapterState: isTurningOff()=false
08-31 15:54:41.988  3497  3497 V BluetoothAdapterState: isTurningOn()=true
08-31 15:54:41.988  3497  3497 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:54:41.988  3497  3497 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:54:41.988  3497  3534 D BluetoothAdapterState: Current state: PENDING,_COMMAND, message: 2
08-31 15:54:41.988  3497  3534 D BluetoothAdapterProperties: ScanMode =  20
08-31 15:54:41.989  3497  3534 D BluetoothAdapterProperties: State =  11
08-31 15:54:41.989  3497  3539 D BluetoothAdapterProperties: Scan Mode:21
08-31 15:54:41.990  3497  3539 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 15:54:41.990  3497  3534 D BluetoothAdapterProperties: Setting state to 12
,08-31 15:54:41.990  3497  3534 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 15:54:41.990  3497  3534 I BluetoothAdapterState: Entering OnState
08-31 15:54:41.991  1346  2054 D BluetoothMap: onBluetoothStateChange: up=true
08-31 15:54:41.992   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 15:54:41.992  3442  3442 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-31 15:54:41.994  1346  1361 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 15:54:41.996  3442  3442 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-31 15:54:41.996   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:54:41.996  1346  1358 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 15:54:41.997  1346  2054 D BluetoothPan: onBluetoothStateChange on: true
08-31 15:54:41.997  1951  1963 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:54:41.997  3442  3442 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-31 15:54:41.997   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 15:54:41.997   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 15:54:42.001  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:54:42.001  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:54:42.001  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:54:42.001  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:54:42.001  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:54:42.001  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:54:42.001  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:54:42.001  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:54:42.001   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 15:54:42.002  3497  3497 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-31 15:54:42.002  3497  3497 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-31 15:54:42.003  3442  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:54:42.005  3497  3497 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 15:54:42.005  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:54:42.005  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:54:42.005  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:54:42.005  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:54:42.005  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:54:42.005  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:54:42.005  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:54:42.005  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:54:42.006  1346  1662 D LocalBluetoothProfileManager: Adding local A2DP profile
08-31 15:54:42.007  3497  3497 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:54:42.007  3442  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:54:42.008  3497  3497 D ObexServerSockets: Succeed to create listening sockets 
08-31 15:54:42.008  3497  3497 D ObexServerSockets0: startAccept()
08-31 15:54:42.008  3497  3497 D ObexServerSockets0: prepareForNewConnect()
08-31 15:54:42.009  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:54:42.010  3497  3497 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-31 15:54:42.010  3497  3497 D BluetoothSdpJni: SDP Create record success - handle: 0
08-31 15:54:42.010  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:54:42.010  3497  3497 D BluetoothMapService: onReceive
08-31 15:54:42.010  3497  3497 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:54:42.010  3497  3497 D BluetoothMapService: STATE_ON
,08-31 15:54:42.011  3497  3576 D ObexServerSockets0: Accepting socket connection...
,08-31 15:54:42.012  3497  3575 D ObexServerSockets0: Accepting socket connection...
08-31 15:54:42.013  1346  1662 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-31 15:54:42.013  1346  1346 D BluetoothA2dp: Proxy object connected
,08-31 15:54:42.018   874  1980 I ActivityManager: Killing 2955:com.google.android.gm/u0a78 (adj 15): empty #17
,08-31 15:54:42.031  3497  3497 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-31 15:54:42.032  3497  3497 D ObexServerSockets0: prepareForNewConnect()
,08-31 15:54:42.055  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 15:54:42.069   874  1968 I ActivityManager: Start proc 3577:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-31 15:54:42.094   874   891 D BluetoothHeadset: Proxy object connected
,08-31 15:54:42.096   874   891 D BluetoothHeadset: Proxy object connected
,08-31 15:54:42.098  1951  2081 D BluetoothHeadset: Proxy object connected
,08-31 15:54:42.099   874   891 D BluetoothHeadset: Proxy object connected
,08-31 15:54:42.115  1346  2054 D BluetoothHeadset: Proxy object connected
,08-31 15:54:42.116  1346  1346 D HeadsetProfile: Bluetooth service connected
,08-31 15:54:42.126  3577  3577 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-31 15:54:42.279  3577  3577 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 15:54:42.279  3577  3577 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 15:54:42.279  3577  3577 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ActivityThread.main(A,ctivityThread.java:5417)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 15:54:42.279  3577  3577 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 15:54:42.279  3577  3577 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.r.k.d(PG:583)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 15:54:42.279  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 15:54:42.280  3577  3577 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 15:54:42.280  3577  3577 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at java.io.File.exists(File.java:361)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 15:54:42.280  3577  3577 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 15:54:42.280  3577  3577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 15:54:42.294  3554  3554 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 15:54:42.306   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c5b3a13:true
08-31 15:54:42.306  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 15:54:42.316  1346  1346 D BluetoothPbap: Proxy object connected
08-31 15:54:42.317  1346  1346 D PbapServerProfile: Bluetooth service connected
08-31 15:54:42.321  3554  3554 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-31 15:54:42.329  3554  3554 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-31 15:54:42.346  3497  3605 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:54:42.354  3554  3554 D LocalBluetoothProfileManager: Adding local MAP profile
08-31 15:54:42.355  3554  3554 D BluetoothMap: Create BluetoothMap proxy object
08-31 15:54:42.358  3497  3610 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:54:42.360  3497  3610 I BtOppRfcommListener: Accept thread started.
,08-31 15:54:42.374  3554  3554 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-31 15:54:42.379  3554  3554 D DockEventReceiver: finishStartingService: stopping service
,08-31 15:54:42.379  3554  3554 D BluetoothA2dp: Proxy object connected
,08-31 15:54:42.386  3554  3554 D BluetoothInputDevice: Proxy object connected
,08-31 15:54:42.386  3554  3554 D HidProfile: Bluetooth service connected
,08-31 15:54:42.389  3554  3554 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 15:54:42.390  3554  3554 D PanProfile: Bluetooth service connected
08-31 15:54:42.390  3554  3554 D BluetoothMap: Proxy object connected
08-31 15:54:42.391  3554  3554 D MapProfile: Bluetooth service connected
08-31 15:54:42.391  3554  3554 D BluetoothMap: getConnectedDevices()
,08-31 15:54:42.394  3554  3554 D BluetoothPbap: Proxy object connected
,08-31 15:54:42.394  3554  3554 D PbapServerProfile: Bluetooth service connected
,08-31 15:54:42.397   874  1484 I ActivityManager: Killing 3137:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-31 15:54:42.433  3554  3566 D BluetoothHeadset: Proxy object connected
,08-31 15:54:42.433  3554  3554 D HeadsetProfile: Bluetooth service connected
,08-31 15:54:42.568  3577  3592 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-31 15:54:42.585   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39868ae:true
,08-31 15:54:43.241   874  2009 D WifiService: setWifiEnabled: true pid=3442, uid=10000
08-31 15:54:43.241   874  2009 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 15:54:43.256   874  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-31 15:54:43.270  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:54:43.270  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:54:43.270  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:54:43.270  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:54:43.270  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:54:43.270  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:54:43.270  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:54:43.270  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:54:43.276   874  1305 D WifiConfigStore: loaded 0 passpoint configs
08-31 15:54:43.277   874  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-31 15:54:43.277   874  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-31 15:54:43.278   874  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-31 15:54:43.278  3442  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:54:43.281   874  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-31 15:54:43.281   874  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-31 15:54:43.281   874  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-31 15:54:43.285  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
08-31 15:54:43.285  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:54:43.285  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:54:43.285  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:54:43.285  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:54:43.285  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:54:43.285  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:54:43.285  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:54:43.285  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:54:43.287  3442  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:54:43.351   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-31 15:54:43.352   373   873 D CommandListener: Setting iface cfg
08-31 15:54:43.352   874  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '111 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 111 Failed to set address (No such device)'
08-31 15:54:43.352   874  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 15:54:43.358   874  1304 D WifiNative-HAL: p2pGetDeviceAddress
,08-31 15:54:43.359   874  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
08-31 15:54:43.359   874  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 15:54:43.371   874  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 15:54:43.455  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:54:43.464  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:54:43.467  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:54:43.492  1515  2246 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-31 15:54:43.492  1515  2246 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-31 15:54:43.492  1515  2246 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:54:43.492  1515  2246 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:54:43.516  2716  2716 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-31 15:54:43.516  2716  2716 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-31 15:54:43.516  2716  2716 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-31 15:54:43.772  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-31 15:54:43.820  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-31 15:54:43.820  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-31 15:54:43.825   874  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 15:54:43.838   874  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 15:54:43.839   874  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 15:54:43.840   874  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-31 15:54:43.870   874  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 15:54:43.892   373   873 D CommandListener: Setting iface cfg
,08-31 15:54:43.908   874  1305 D WifiStateMachine: Start Dhcp Watchdog 1
,08-31 15:54:43.934   874  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-31 15:54:43.934   874  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
08-31 15:54:43.935   874  1307 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,08-31 15:54:43.960   874  3627 D DhcpClient: Receive thread started
,08-31 15:54:44.043   874  1305 E native  : do suspend false
,08-31 15:54:44.066   874  3626 D DhcpClient: Broadcasting DHCPDISCOVER
,08-31 15:54:44.085   874  3627 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 171119, domain null
,08-31 15:54:44.086   874  3626 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 171119 seconds
,08-31 15:54:44.090   874  3626 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-31 15:54:44.112   874  3627 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-31 15:54:44.113   874  3626 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-31 15:54:44.118   373   873 D CommandListener: Setting iface cfg
,08-31 15:54:44.127   874  3626 D DhcpClient: Scheduling renewal in 86399s
,08-31 15:54:44.127   874  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-31 15:54:44.136   874  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-31 15:54:44.137   874  1305 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-31 15:54:44.138   874  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-31 15:54:44.142   874  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 15:54:44.144   874  1307 D ConnectivityService: Adding iface wlan0 to network 100
,08-31 15:54:44.218   874  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-31 15:54:44.219   874  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,08-31 15:54:44.222   874  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,08-31 15:54:44.226   874  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,08-31 15:54:44.230   874  1307 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,08-31 15:54:44.242   874  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-31 15:54:44.246   874  1307 D ConnectivityService: scheduleUnvalidatedPrompt 100
,08-31 15:54:44.247   874  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
08-31 15:54:44.247   874  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
,08-31 15:54:44.247   874  1307 D ConnectivityService:    accepting network in place of null
08-31 15:54:44.247   874  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-31 15:54:44.248   874  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-31 15:54:44.253   874  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 15:54:44.296   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 15:54:44.327   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 15:54:44.332   874  1307 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,08-31 15:54:44.344   874  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-31 15:54:44.345   874  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:54:44.349   874  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,08-31 15:54:44.355   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-31 15:54:44.362   874  2011 V BackupManagerService: Scheduling immediate backup pass
08-31 15:54:44.363  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:54:44.363  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:54:44.363  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:54:44.363  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:54:44.363  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:54:44.363  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:54:44.363  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:54:44.363  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 15:54:44.363   874   874 V BackupManagerService: Running a backup pass
08-31 15:54:44.365  3442  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:54:44.365   874  1324 V BackupManagerService: clearing pending backups
,08-31 15:54:44.371  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:54:44.371  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:54:44.371  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:54:44.371  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:54:44.371  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:54:44.371  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:54:44.371  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:54:44.371  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 15:54:44.371   874  1324 V PerformBackupTask: Beginning backup of 16 targets
,08-31 15:54:44.395  3442  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 15:54:44.396  1736  1736 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 15:54:44.397   874  1324 D PerformBackupTask: invokeAgentForBackup on @pm@
,08-31 15:54:44.400  1736  1736 D SystemUpdateService: onCreate
,08-31 15:54:44.404  1736  1736 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 15:54:44.406   874  1324 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
,08-31 15:54:44.407  1736  3642 I SystemUpdateService: active receiver: enabled
,08-31 15:54:44.412  1736  3642 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 15:54:44.416  1736  3642 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-31 15:54:44.416  1736  3642 I SystemUpdateService: now status is 0 (complete)
08-31 15:54:44.416  1736  3642 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 15:54:44.416  1736  3642 I SystemUpdateService: file has been verified
08-31 15:54:44.416  1736  3642 I SystemUpdateService: OTA package size = 12249756
,08-31 15:54:44.424  1736  3642 I SystemUpdateService: showing system update notification
,08-31 15:54:44.449  1736  1736 D SystemUpdateService: onDestroy
,08-31 15:54:44.470  1736  3655 I iu.SyncManager: SYNC; picasa accounts
,08-31 15:54:44.476   874  1324 I BackupRestoreController: Getting widget state for user: 0
,08-31 15:54:44.491  3509  3646 V GoogleAuthProtoRequest: [282] a.<init>: mAccountName set to: thalitester@gmail.com
,08-31 15:54:44.506  2107  2119 W GmsBackupTransport: Unknown package in backup request: @pm@
,08-31 15:54:44.507  2107  2119 V GmsBackupTransport: starting performBackup for @pm@
,08-31 15:54:44.510  2107  2119 V GmsBackupTransport: performBackup done for @pm@
,08-31 15:54:44.521  1736  1736 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-31 15:54:44.523  1736  1736 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 15:54:44.532  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:54:44.532  1736  3654 I MDM     : [147] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-31 15:54:44.533  1736  3654 W BaseAppContext: Using Auth Proxy for data requests.
,08-31 15:54:44.536  1736  1736 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-31 15:54:44.537  1736  1736 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 15:54:44.539  1736  3655 I iu.UploadsManager: num queued entries: 0
,08-31 15:54:44.540  1736  3655 I iu.UploadsManager: num updated entries: 0
,08-31 15:54:44.541  1736  3655 I iu.SyncManager: NEXT; no task
,08-31 15:54:44.543  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-31 15:54:44.544  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-31 15:54:44.544  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:54:44.544  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:54:44.548   874   885 I ActivityManager: Start proc 3659:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-31 15:54:44.555  1736  3654 V GoogleAuthProtoRequest: [147] a.<init>: mAccountName set to: thalitester@gmail.com
,08-31 15:54:44.561  1515  2078 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
,08-31 15:54:44.561  1515  2078 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
08-31 15:54:44.562  1515  2078 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:54:44.562  1515  2078 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:54:44.575  1515  2078 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-31 15:54:44.575  1515  2078 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-31 15:54:44.575  1515  2078 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-31 15:54:44.575  1515  2078 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-31 15:54:44.575  1515  2078 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-31 15:54:44.575  1515  2078 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-31 15:54:44.575  1515  2078 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-31 15:54:44.577  2107  2122 W GmsBackupTransport: Error sending final backup to server: 
08-31 15:54:44.577  2107  2122 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
08-31 15:54:44.577  2107  2122 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
08-31 15:54:44.577  2107  2122 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
08-31 15:54:44.577  2107  2122 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
08-31 15:54:44.577  2107  2122 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
08-31 15:54:44.577  2107  2122 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
08-31 15:54:44.577  2107  2122 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
08-31 15:54:44.577  2107  2122 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-31 15:54:44.577  2107  2122 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-31 15:54:44.577  2107  2122 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-31 15:54:44.577  2107  2122 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-31 15:54:44.577  2107  2122 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-31 15:54:44.577  2107  2122 W GmsBackupTransport: 	... 1 more
,08-31 15:54:44.579  2107  2120 I GmsBackupTransport: Next backup will happen in 43199998 millis.
08-31 15:54:44.579   874  1324 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
,08-31 15:54:44.585  3659  3659 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-31 15:54:44.593  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-31 15:54:44.594  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-31 15:54:44.594  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:54:44.594  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:54:44.596  3659  3659 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:54:44.603  3659  3659 D SprintDMHelper: simOperator: 
08-31 15:54:44.603  3659  3659 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 15:54:44.604  3509  3646 W ExperimentUpdateService: [282] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-31 15:54:44.605  3509  3646 W ExperimentUpdateService: [282] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-31 15:54:44.605  3509  3646 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-31 15:54:44.605  3509  3646 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-31 15:54:44.605  3509  3646 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-31 15:54:44.605  3509  3646 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-31 15:54:44.605  3509  3646 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-31 15:54:44.605  3509  3646 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-31 15:54:44.605  3509  3646 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-31 15:54:44.605  3509  3646 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-31 15:54:44.605  3509  3646 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-31 15:54:44.605  3509  3646 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-31 15:54:44.610  1736  3654 E MDM     : [147] SitrepService.a: Error sending sitrep.
,08-31 15:54:44.614  1736  3656 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,08-31 15:54:44.629   874  1976 I ActivityManager: Start proc 3674:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-31 15:54:44.678   874  2011 I ActivityManager: Start proc 3689:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-31 15:54:44.691  1736  1736 E ConnectivityChangeReceiver: Ignoring connectivity change
,08-31 15:54:44.703   874  1324 I BackupManagerService: Backup pass finished.
,08-31 15:54:44.713   874   885 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1736 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 15:54:44.714  3689  3689 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-31 15:54:44.716  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:54:44.780  3689  3703 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-31 15:54:44.846  3689  3703 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-31 15:54:44.872  3689  3703 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-31 15:54:44.884  1736  3657 W DriveInitializer: Awaiting to be initialized
,08-31 15:54:44.888  1736  3716 W DriveInitializer: Background init thread started
,08-31 15:54:44.942  1736  3716 W DriveInitializer: Background init thread ended
,08-31 15:54:44.945  3689  3689 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-31 15:54:44.945  1515  2078 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-31 15:54:44.945  1515  2078 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-31 15:54:44.945  1515  2078 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:54:44.945  1515  2078 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-31 15:54:44.965  3253  3673 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-31 15:54:44.965  3253  3673 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-31 15:54:44.965  3253  3673 E HttpOperation: 	at jdm.a(PG:82)
08-31 15:54:44.965  3253  3673 E HttpOperation: 	at jcs.o(PG:406)
08-31 15:54:44.965  3253  3673 E HttpOperation: 	at jcn.a(PG:1379)
08-31 15:54:44.965  3253  3673 E HttpOperation: 	at jcs.i(PG:143)
08-31 15:54:44.965  3253  3673 E HttpOperation: 	at blb.a(PG:3937)
08-31 15:54:44.965  3253  3673 E HttpOperation: 	at czp.a(PG:18188)
08-31 15:54:44.965  3253  3673 E HttpOperation: 	at czp.a(PG:9081)
08-31 15:54:44.965  3253  3673 E HttpOperation: 	at czq.run(PG:1686)
08-31 15:54:44.965  3253  3673 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 15:54:44.965  3253  3673 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 15:54:44.965  3253  3673 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 15:54:44.965  3253  3673 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 15:54:44.965  3253  3673 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-31 15:54:44.965  3253  3673 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 15:54:44.965  3253  3673 E HttpOperation: 	at jdj.a(PG:4091)
08-31 15:54:44.965  3253  3673 E HttpOperation: 	at jdj.a(PG:1125)
08-31 15:54:44.965  3253  3673 E HttpOperation: 	at jdm.a(PG:77)
08-31 15:54:44.965  3253  3673 E HttpOperation: 	... 12 more
08-31 15:54:44.965  3253  3673 E HttpOperation: Caused by: faj: BadAuthentication
08-31 15:54:44.965  3253  3673 E HttpOperation: 	at fal.a(PG:38)
08-31 15:54:44.965  3253  3673 E HttpOperation: 	at jdj.a(PG:4089)
08-31 15:54:44.965  3253  3673 E HttpOperation: 	... 14 more
,08-31 15:54:44.986   874  1484 I ActivityManager: Start proc 3749:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-31 15:54:45.007  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-31 15:54:45.007  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-31 15:54:45.007  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:54:45.007  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:54:45.017  3253  3673 E HttpOperation: [getmobileexperiments] Unexpected exception
08-31 15:54:45.017  3253  3673 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-31 15:54:45.017  3253  3673 E HttpOperation: 	at jdm.a(PG:82)
08-31 15:54:45.017  3253  3673 E HttpOperation: 	at jcs.o(PG:406)
08-31 15:54:45.017  3253  3673 E HttpOperation: 	at jcn.a(PG:1379)
08-31 15:54:45.017  3253  3673 E HttpOperation: 	at jcs.i(PG:143)
08-31 15:54:45.017  3253  3673 E HttpOperation: 	at hec.a(PG:42)
08-31 15:54:45.017  3253  3673 E HttpOperation: 	at hee.a(PG:102)
08-31 15:54:45.017  3253  3673 E HttpOperation: 	at czr.a(PG:65)
08-31 15:54:45.017  3253  3673 E HttpOperation: 	at kka.a(PG:108)
08-31 15:54:45.017  3253  3673 E HttpOperation: 	at czp.a(PG:19176)
08-31 15:54:45.017  3253  3673 E HttpOperation: 	at czp.a(PG:9081)
08-31 15:54:45.017  3253  3673 E HttpOperation: 	at czq.run(PG:1686)
08-31 15:54:45.017  3253  3673 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 15:54:45.017  3253  3673 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 15:54:45.017  3253  3673 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 15:54:45.017  3253  3673 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 15:54:45.017  3253  3673 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-31 15:54:45.017  3253  3673 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 15:54:45.017  3253  3673 E HttpOperation: 	at jdj.a(PG:4091)
08-31 15:54:45.017  3253  3673 E HttpOperation: 	at jdj.a(PG:1125)
08-31 15:54:45.017  3253  3673 E HttpOperation: 	at jdm.a(PG:77)
08-31 15:54:45.017  3253  3673 E HttpOperation: 	... 15 more
08-31 15:54:45.017  3253  3673 E HttpOperation: Caused by: faj: BadAuthentication
08-31 15:54:45.017  3253  3673 E HttpOperation: 	at fal.a(PG:38)
08-31 15:54:45.017  3253  3673 E HttpOperation: 	at jdj.a(PG:4089)
08-31 15:54:45.017  3253  3673 E HttpOperation: 	... 17 more
,08-31 15:54:45.017  3253  3673 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-31 15:54:45.017  3253  3673 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-31 15:54:45.017  3253  3673 E ExperimentLoader: 	at jdm.a(PG:82)
08-31 15:54:45.017  3253  3673 E ExperimentLoader: 	at jcs.o(PG:406)
08-31 15:54:45.017  3253  3673 E ExperimentLoader: 	at jcn.a(PG:1379)
08-31 15:54:45.017  3253  3673 E ExperimentLoader: 	at jcs.i(PG:143)
08-31 15:54:45.017  3253  3673 E ExperimentLoader: 	at hec.a(PG:42)
08-31 15:54:45.017  3253  3673 E ExperimentLoader: 	at hee.a(PG:102)
08-31 15:54:45.017  3253  3673 E ExperimentLoader: 	at czr.a(PG:65)
08-31 15:54:45.017  3253  3673 E ExperimentLoader: 	at kka.a(PG:108)
08-31 15:54:45.017  3253  3673 E ExperimentLoader: 	at czp.a(PG:19176)
08-31 15:54:45.017  3253  3673 E ExperimentLoader: 	at czp.a(PG:9081)
08-31 15:54:45.017  3253  3673 E ExperimentLoader: 	at czq.run(PG:1686)
08-31 15:54:45.017  3253  3673 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 15:54:45.017  3253  3673 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 15:54:45.017  3253  3673 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 15:54:45.017  3253  3673 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 15:54:45.017  3253  3673 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-31 15:54:45.017  3253  3673 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-31 15:54:45.017  3253  3673 E ExperimentLoader: 	at jdj.a(PG:4091)
08-31 15:54:45.017  3253  3673 E ExperimentLoader: 	at jdj.a(PG:1125)
08-31 15:54:45.017  3253  3673 E ExperimentLoader: 	at jdm.a(PG:77)
08-31 15:54:45.017  3253  3673 E ExperimentLoader: 	... 15 more
08-31 15:54:45.017  3253  3673 E ExperimentLoader: Caused by: faj: BadAuthentication
08-31 15:54:45.017  3253  3673 E ExperimentLoader: 	at fal.a(PG:38)
08-31 15:54:45.017  3253  3673 E ExperimentLoader: 	at jdj.a(PG:4089)
08-31 15:54:45.017  3253  3673 E ExperimentLoader: 	... 17 more
,08-31 15:54:45.035  3747  3747 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads283912016.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads283912016.dex
,08-31 15:54:45.059  3749  3749 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-31 15:54:45.065   874  3625 D NetlinkSocketObserver: NeighborEvent{elapsedMs=119905, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-31 15:54:45.093  3747  3747 I dex2oat : dex2oat took 59.278ms (threads: 4) arena alloc=331KB java alloc=37KB native alloc=1656KB free=1671KB
,08-31 15:54:45.132  2994  3721 V KeepSync: Connecting to GoogleApiClient
,08-31 15:54:45.132   874  1976 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-31 15:54:45.134  3689  3689 W InstanceID/Rpc: Found 10011
,08-31 15:54:45.206   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 24794, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-31 15:54:45.266   874   886 I ActivityManager: Start proc 3802:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-31 15:54:45.277  1515  2246 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-31 15:54:45.277  1515  2246 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-31 15:54:45.277  1515  2246 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:54:45.277  1515  2246 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:54:45.282  3802  3802 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-31 15:54:45.288  1736  3795 V BaseAuthAsyncOperation: access token request failed
,08-31 15:54:45.298  2994  3721 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-31 15:54:45.397  3749  3749 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-31 15:54:45.397  3749  3749 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-31 15:54:45.397  3749  3749 I GAv4    :   adb logcat -s GAv4
,08-31 15:54:45.412  3749  3749 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-31 15:54:45.419  3749  3749 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-31 15:54:45.449  3749  3822 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-31 15:54:45.491  3802  3802 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-31 15:54:45.502  3802  3802 I BooksApp: Created application version: 3.6.9 (30609)
,08-31 15:54:45.618  3802  3842 I BooksSync: Starting books sync for 61035162, extras: ade
,08-31 15:54:45.632  3749  3749 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-31 15:54:45.693  3749  3749 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-31 15:54:45.708  3749  3749 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 543-549)
,08-31 15:54:45.708  3749  3749 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 15:54:45.730  3749  3749 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2720d87}
,08-31 15:54:45.731  3749  3749 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 15:54:45.731  3749  3749 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 15:54:45.741  3749  3749 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-31 15:54:45.742  3749  3749 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 15:54:45.777  3749  3749 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-31 15:54:45.793  3749  3749 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 15:54:45.793  3749  3749 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 15:54:45.793  3749  3749 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 15:54:45.793  3749  3749 I Adreno  : Build Date                       : 10/20/15
08-31 15:54:45.793  3749  3749 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 15:54:45.793  3749  3749 I Adreno  : Local Branch                     : M14
08-31 15:54:45.793  3749  3749 I Adreno  : Remote Branch                    : 
08-31 15:54:45.793  3749  3749 I Adreno  : Remote Branch                    : 
08-31 15:54:45.793  3749  3749 I Adreno  : Reconstruct Branch               : 
,08-31 15:54:45.900  3749  3861 W AudioManagerAndroid: Requires BLUETOOTH permission
08-31 15:54:45.902  3749  3749 I NSApplication: Starting up...
,08-31 15:54:45.935   874   884 I ActivityManager: Start proc 3866:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-31 15:54:45.972  1515  2246 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-31 15:54:45.972  1515  2246 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-31 15:54:45.972  1515  2246 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:54:45.972  1515  2246 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:54:46.011  3866  3866 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-31 15:54:46.028  2994  3721 E KeepSync: IOException
08-31 15:54:46.028  2994  3721 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-31 15:54:46.028  2994  3721 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-31 15:54:46.028  2994  3721 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-31 15:54:46.028  2994  3721 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-31 15:54:46.028  2994  3721 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-31 15:54:46.028  2994  3721 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-31 15:54:46.028  2994  3721 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-31 15:54:46.028  2994  3721 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-31 15:54:46.028  2994  3721 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-31 15:54:46.028  2994  3721 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-31 15:54:46.028  2994  3721 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-31 15:54:46.028  2994  3721 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-31 15:54:46.028  2994  3721 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-31 15:54:46.028  2994  3721 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-31 15:54:46.028  2994  3721 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-31 15:54:46.028  2994  3721 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-31 15:54:46.028  2994  3721 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-31 15:54:46.028  2994  3721 E KeepSync: 	... 10 more
08-31 15:54:46.028  2994  3721 W KeepSync: Sync result 2
,08-31 15:54:46.035   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 24817, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-31 15:54:46.036   874  1373 I ActivityManager: Killing 2610:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-31 15:54:46.165  3802  3881 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-31 15:54:46.213  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-31 15:54:46.213  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-31 15:54:46.213  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:54:46.213  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:54:46.245   874  2009 D WifiService: setWifiEnabled: false pid=3442, uid=10000
,08-31 15:54:46.245   874  2009 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-31 15:54:46.247  1515  3668 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-31 15:54:46.247  1515  3668 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-31 15:54:46.247  1515  3668 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 15:54:46.247  1515  3668 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:54:46.253  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-31 15:54:46.254   874  1305 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 15:54:46.255   874  1305 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-31 15:54:46.255   874  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-31 15:54:46.255   874  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 15:54:46.262   874  3626 D DhcpClient: Clearing IP address
,08-31 15:54:46.262   373   873 D CommandListener: Clearing all IP addresses on wlan0
08-31 15:54:46.262  3802  3881 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-31 15:54:46.264   373   873 D CommandListener: Setting iface cfg
08-31 15:54:46.266  3689  3798 E GoogleConversionReporter: Error sending ping
08-31 15:54:46.266  3689  3798 E GoogleConversionReporter: org.apache.http.conn.ConnectTimeoutException: Connect to /172.217.16.194:443 timed out
08-31 15:54:46.266  3689  3798 E GoogleConversionReporter: 	at org.apache.http.conn.scheme.PlainSocketFactory.connectSocket(PlainSocketFactory.java:126)
08-31 15:54:46.266  3689  3798 E GoogleConversionReporter: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:149)
08-31 15:54:46.266  3689  3798 E GoogleConversionReporter: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:169)
08-31 15:54:46.266  3689  3798 E GoogleConversionReporter: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:124)
08-31 15:54:46.266  3689  3798 E GoogleConversionReporter: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:366)
08-31 15:54:46.266  3689  3798 E GoogleConversionReporter: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:560)
08-31 15:54:46.266  3689  3798 E GoogleConversionReporter: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:492)
08-31 15:54:46.266  3689  3798 E GoogleConversionReporter: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:470)
08-31 15:54:46.266  3689  3798 E GoogleConversionReporter: 	at android.net.http.AndroidHttpClient.execute(AndroidHttpClient.java:250)
08-31 15:54:46.266  3689  3798 E GoogleConversionReporter: 	at alr.a(SourceFile:217)
08-31 15:54:46.266  3689  3798 E GoogleConversionReporter: 	at alu.run(SourceFile:173)
08-31 15:54:46.266  3689  3798 E GoogleConversionReporter: 	at java.lang.Thread.run(Thread.java:818)
,08-31 15:54:46.269   874  3627 D DhcpClient: Receive thread stopped
,08-31 15:54:46.270  2376  3746 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,08-31 15:54:46.271   874  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-31 15:54:46.271   874  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-31 15:54:46.273   874  1305 D WifiStateMachine: Start Disconnecting Watchdog 1
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: java.net.SocketTimeoutException: failed to connect to clients3.google.com/172.217.18.14 (port 80) after 5000ms: isConnected failed: ETIMEDOUT (Connection timed out)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:232)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:171)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at java.net.Socket.connect(Socket.java:884)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectCleartext(SocketConnector.java:67)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connect(Connection.java:152)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingServ,ice: Caused by: android.system.ErrnoException: isConnected failed: ETIMEDOUT (Connection timed out)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:223)
08-31 15:54:46.271  2376  3746 W Babel_NetworkConnectionCheckingService: 	... 23 more
08-31 15:54:46.273  2376  3746 I Babel   : connection state changed from UNKNOWN to CONNECTED
08-31 15:54:46.274   874  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 15:54:46.274   398   398 E Parcel  : Reading a NULL string not supported here.
08-31 15:54:46.275   373   873 D CommandListener: Clearing all IP addresses on wlan0
08-31 15:54:46.277   874  1307 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-31 15:54:46.280   874  1305 D WifiConfigStore: Retrieve network priorities after PNO.
08-31 15:54:46.282  2107  2300 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:54:46.284  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:54:46.284  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:54:46.284  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:54:46.284  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:54:46.284  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:54:46.284  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:54:46.284  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:54:46.284  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:54:46.284   874  1305 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 15:54:46.285  3442  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:54:46.289  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:54:46.289  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:54:46.289  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:54:46.289  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:54:46.289  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:54:46.289  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:54:46.289  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:54:46.289  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:54:46.293  3442  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:54:46.295   874  1968 I ActivityManager: Killing 2869:android.process.acore/u0a5 (adj 15): empty #17
,08-31 15:54:46.305  3802  3842 E BooksSync: Soft error
08-31 15:54:46.305  3802  3842 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-31 15:54:46.305  3802  3842 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-31 15:54:46.305  3802  3842 E BooksSync: Sync error
08-31 15:54:46.305  3802  3842 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-31 15:54:46.305  3802  3842 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-31 15:54:46.305  3802  3842 I BooksSync: Finished books sync
,08-31 15:54:46.314   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 15:54:46.332   874   884 I ActivityManager: Killing 3336:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-31 15:54:46.333   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 24818, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-31 15:54:46.334   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-31 15:54:46.336   874  1307 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-31 15:54:46.336   874  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:54:46.370   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-31 15:54:46.370  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:54:46.372  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:54:46.442   373   873 E Netd    : netlink response contains error (No such file or directory)
,08-31 15:54:46.443   874  1307 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-31 15:54:46.549   874  1980 I ActivityManager: Killing 3351:com.android.musicfx/u0a18 (adj 15): empty #17
,08-31 15:54:46.746  1736  1736 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-31 15:54:46.756  1736  1736 D SystemUpdateService: onCreate
,08-31 15:54:46.765  1736  1736 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 15:54:46.772  1736  3898 I SystemUpdateService: active receiver: enabled
,08-31 15:54:46.779  1736  3898 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 15:54:46.783  1736  3898 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-31 15:54:46.783  1736  3898 I SystemUpdateService: now status is 0 (complete)
08-31 15:54:46.784  1736  3898 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-31 15:54:46.784  1736  3898 I SystemUpdateService: file has been verified
08-31 15:54:46.784  1736  3898 I SystemUpdateService: OTA package size = 12249756
,08-31 15:54:46.790  1736  3898 I SystemUpdateService: showing system update notification
,08-31 15:54:46.802  1736  1736 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-31 15:54:46.806  1736  3655 I iu.UploadsManager: num queued entries: 0
,08-31 15:54:46.809  1736  3655 I iu.UploadsManager: num updated entries: 0
,08-31 15:54:46.813  1736  3655 I iu.SyncManager: NEXT; no task
,08-31 15:54:46.814  1736  1736 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-31 15:54:46.816  1736  1736 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 15:54:46.820  3659  3659 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:54:46.825  1736  1736 D SystemUpdateService: onDestroy
,08-31 15:54:46.829  3659  3659 D SprintDMHelper: simOperator: 
,08-31 15:54:46.829  3659  3659 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 15:54:46.851  2376  3900 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-31 15:54:49.256  3497  3534 D BluetoothAdapterState: Current state: ON, message: 23
,08-31 15:54:49.257  3497  3534 D BluetoothAdapterProperties: Setting state to 13
,08-31 15:54:49.257  3497  3534 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-31 15:54:49.260  3497  3534 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 15:54:49.265  3497  3534 I BluetoothAdapterState: Entering PendingCommandState
,08-31 15:54:49.268  3497  3539 D BluetoothAdapterProperties: Scan Mode:20
,08-31 15:54:49.269  3497  3534 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-31 15:54:49.273  3497  3497 D BluetoothMapService: onReceive
,08-31 15:54:49.273  3497  3497 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:54:49.273  3497  3497 D BluetoothMapService: STATE_TURNING_OFF
08-31 15:54:49.274  3497  3497 D BluetoothMapService: MAP Service closeService in
08-31 15:54:49.274  3497  3497 D BluetoothMapMasInstance0: MAP Service shutdown
08-31 15:54:49.275  3497  3497 D ObexServerSockets0: shutdown(block = true)
08-31 15:54:49.276  3497  3575 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-31 15:54:49.279  3442  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:54:49.279  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:54:49.279  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:54:49.279  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:54:49.279  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:54:49.279  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:54:49.279  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:54:49.279  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:54:49.279  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:54:49.280  3497  3497 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 15:54:49.282  3497  3576 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-31 15:54:49.283  3497  3549 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-31 15:54:49.284  3442  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:54:49.284  3442  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:54:49.291  3442  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:54:49.291  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:54:49.291  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:54:49.291  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:54:49.291  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:54:49.291  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:54:49.291  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:54:49.291  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:54:49.291  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:54:49.291  3442  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:54:49.292  3442  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:54:49.292  3497  3497 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 15:54:49.293  3497  3497 I BtOppRfcommListener: stopping Accept Thread
08-31 15:54:49.294  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:54:49.294  3497  3610 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-31 15:54:49.295  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:54:49.296  3497  3610 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 15:54:49.298  3554  3554 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 15:54:49.299  3497  3497 D HeadsetService: Received stop request...Stopping profile...
,08-31 15:54:49.302   874   874 D BluetoothHeadset: Proxy object disconnected
08-31 15:54:49.302  3554  3564 D BluetoothHeadset: Proxy object disconnected
08-31 15:54:49.302   874   874 D BluetoothHeadset: Proxy object disconnected
08-31 15:54:49.303  1951  2081 D BluetoothHeadset: Proxy object disconnected
,08-31 15:54:49.303   874   874 D BluetoothHeadset: Proxy object disconnected
08-31 15:54:49.303  1346  2054 D BluetoothHeadset: Proxy object disconnected
08-31 15:54:49.304  1346  1346 D HeadsetProfile: Bluetooth service disconnected
08-31 15:54:49.304  3497  3497 D A2dpService: Received stop request...Stopping profile...
08-31 15:54:49.304  3497  3567 D A2dpStateMachine: Exit Disconnected: -1
08-31 15:54:49.306   874   874 D BluetoothA2dp: Proxy object disconnected
,08-31 15:54:49.307  1346  1346 D BluetoothA2dp: Proxy object disconnected
,08-31 15:54:49.308  3497  3497 D HidService: Received stop request...Stopping profile...
,08-31 15:54:49.308  3497  3497 D HidService: Stopping Bluetooth HidService
,08-31 15:54:49.310  1346  1346 D BluetoothInputDevice: Proxy object disconnected
08-31 15:54:49.310  1346  1346 D HidProfile: Bluetooth service disconnected
,08-31 15:54:49.312  3497  3497 D HealthService: Received stop request...Stopping profile...
,08-31 15:54:49.313  3497  3497 D PanService: Received stop request...Stopping profile...
,08-31 15:54:49.315  1346  1346 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 15:54:49.315  1346  1346 D PanProfile: Bluetooth service disconnected
08-31 15:54:49.315  3497  3497 D BluetoothMapService: Received stop request...Stopping profile...
08-31 15:54:49.315  3497  3497 D BluetoothMapService: stop()
,08-31 15:54:49.314  3554  3554 D HeadsetProfile: Bluetooth service disconnected
,08-31 15:54:49.316  3497  3497 D BluetoothMapAppObserver: deinitObservers()
08-31 15:54:49.316  3497  3497 D BluetoothMapAppObserver: removeReceiver()
08-31 15:54:49.316  3554  3554 D BluetoothA2dp: Proxy object disconnected
08-31 15:54:49.317  1346  1346 D BluetoothMap: Proxy object disconnected
08-31 15:54:49.317  1346  1346 D MapProfile: Bluetooth service disconnected
,08-31 15:54:49.318  3497  3497 V BluetoothAdapterState: isTurningOff()=true
08-31 15:54:49.318  3497  3497 V BluetoothAdapterState: isTurningOn()=false
,08-31 15:54:49.318  3497  3497 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:54:49.318  3497  3497 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 15:54:49.320  3554  3554 D BluetoothInputDevice: Proxy object disconnected
08-31 15:54:49.320  3497  3497 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-31 15:54:49.320  3554  3554 D HidProfile: Bluetooth service disconnected
08-31 15:54:49.320  3497  3497 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 15:54:49.320  3497  3539 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-31 15:54:49.320  3497  3547 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 15:54:49.320  3497  3547 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 15:54:49.320  3497  3547 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 15:54:49.320  3497  3539 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-31 15:54:49.322  3497  3497 V BluetoothAdapterState: isTurningOff()=true
,08-31 15:54:49.322  3497  3497 V BluetoothAdapterState: isTurningOn()=false
08-31 15:54:49.322  3497  3497 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 15:54:49.322  3497  3497 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:54:49.323  3554  3554 D DockEventReceiver: finishStartingService: stopping service
,08-31 15:54:49.323  3497  3539 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-31 15:54:49.323  3497  3547 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 15:54:49.324  3497  3497 V BluetoothAdapterState: isTurningOff()=true
,08-31 15:54:49.324  3497  3547 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 15:54:49.324  3497  3547 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:54:49.324  3497  3547 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:54:49.324  3497  3547 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-31 15:54:49.324  3497  3547 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:54:49.324  3497  3497 V BluetoothAdapterState: isTurningOn()=false
08-31 15:54:49.325  3497  3497 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:54:49.325  3497  3497 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:54:49.327  3554  3554 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 15:54:49.327  3554  3554 D PanProfile: Bluetooth service disconnected
08-31 15:54:49.327  3554  3554 D BluetoothMap: Proxy object disconnected
08-31 15:54:49.327  3554  3554 D MapProfile: Bluetooth service disconnected
,08-31 15:54:49.329  3497  3497 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 15:54:49.329  3497  3539 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 15:54:49.329  3497  3497 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 15:54:49.329  3497  3497 V BluetoothAdapterState: isTurningOff()=true
,08-31 15:54:49.329  3497  3497 V BluetoothAdapterState: isTurningOn()=false
08-31 15:54:49.330  3497  3497 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:54:49.330  3497  3497 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 15:54:49.330  3497  3497 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 15:54:49.330  3497  3539 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-31 15:54:49.330  3497  3497 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-31 15:54:49.330  3497  3497 V BluetoothAdapterState: isTurningOff()=true
,08-31 15:54:49.330  3497  3497 V BluetoothAdapterState: isTurningOn()=false
,08-31 15:54:49.330  3497  3497 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 15:54:49.330  3497  3497 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:54:49.331  3497  3497 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-31 15:54:49.331  3497  3497 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-31 15:54:49.333  3497  3497 D BluetoothMapService: MAP Service closeService in
08-31 15:54:49.333  3497  3497 V BluetoothAdapterState: isTurningOff()=true
,08-31 15:54:49.333  3497  3497 V BluetoothAdapterState: isTurningOn()=false
08-31 15:54:49.333  3497  3497 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 15:54:49.333  3497  3497 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:54:49.333  3497  3534 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-31 15:54:49.333  3497  3534 D BluetoothAdapterProperties: Setting state to 15
08-31 15:54:49.333  3497  3534 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-31 15:54:49.334  3497  3497 D BluetoothMapService: cleanup()
,08-31 15:54:49.334  3497  3497 D BluetoothMapService: MAP Service closeService in
,08-31 15:54:49.334  3497  3534 I BluetoothAdapterState: Entering BleOnState
,08-31 15:54:49.335  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 15:54:49.335  1346  1361 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:54:49.336  3554  3564 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 15:54:49.337  1346  1346 D BluetoothPbap: Proxy object disconnected
08-31 15:54:49.337  1346  1346 D PbapServerProfile: Bluetooth service disconnected
08-31 15:54:49.338  1346  1361 D BluetoothMap: onBluetoothStateChange: up=false
08-31 15:54:49.338  3554  3554 D BluetoothPbap: Proxy object disconnected
08-31 15:54:49.338  3554  3554 D PbapServerProfile: Bluetooth service disconnected
,08-31 15:54:49.340  3554  3564 D BluetoothMap: onBluetoothStateChange: up=false
,08-31 15:54:49.340   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 15:54:49.340  1346  1358 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 15:54:49.343   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:54:49.344  1346  2054 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 15:54:49.344  1346  1361 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-31 15:54:49.344  1346  1358 D BluetoothPan: onBluetoothStateChange on: false
08-31 15:54:49.345  3554  3906 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 15:54:49.345  3554  3566 D BluetoothPan: onBluetoothStateChange on: false
08-31 15:54:49.346  1951  2183 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:54:49.346   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 15:54:49.346  3554  3564 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:54:49.346   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 15:54:49.347  3554  3906 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 15:54:49.347  3497  3534 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-31 15:54:49.347  3497  3534 D BluetoothAdapterProperties: Setting state to 16
08-31 15:54:49.347  3497  3534 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-31 15:54:49.348  3497  3534 D BluetoothAdapterProperties: onBleDisable
08-31 15:54:49.348  3497  3534 I BluetoothAdapterState: Entering PendingCommandState
08-31 15:54:49.348  3497  3536 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-31 15:54:49.351  3497  3539 D BluetoothAdapterProperties: Scan Mode:20
08-31 15:54:49.351  3497  3547 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-31 15:54:49.351  3497  3547 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 15:54:49.351  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:54:49.352  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:54:49.352  3554  3554 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 15:54:49.354  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:54:49.355  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:54:49.356  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 15:54:49.361  3554  3554 D DockEventReceiver: finishStartingService: stopping service
,08-31 15:54:49.553  3497  3539 I bt_hci  : shut_down
,08-31 15:54:49.554  3497  3544 D bt_hwcfg: hw_epilog_process
,08-31 15:54:49.565  3497  3544 I bt_vendor: low_power_mode_cb
,08-31 15:54:49.591  3497  3544 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-31 15:54:49.591  3497  3544 I bt_vendor: epilog_cb
08-31 15:54:49.591  3497  3544 I bt_hci  : epilog_finished_callback
,08-31 15:54:49.599  3497  3539 I bt_hci_h4: hal_close
,08-31 15:54:49.601  3497  3539 I bt_userial_vendor: device fd = 51 close
,08-31 15:54:49.726  3497  3536 D bt_stack_manager: event_shut_down_stack finished.
,08-31 15:54:49.727  3497  3534 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-31 15:54:49.730  3497  3534 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-31 15:54:49.731  3497  3497 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 15:54:49.732  3497  3497 D BtGatt.GattService: Received stop request...Stopping profile...
,08-31 15:54:49.732  3497  3497 D BtGatt.GattService: stop()
08-31 15:54:49.732  3497  3497 D BtGatt.AdvertiseManager: advertise clients cleared
,08-31 15:54:49.736  3497  3497 V BluetoothAdapterState: isTurningOff()=false
,08-31 15:54:49.737  3497  3497 V BluetoothAdapterState: isTurningOn()=false
08-31 15:54:49.737  3497  3497 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 15:54:49.737  3497  3497 V BluetoothAdapterState: isBleTurningOff()=true
08-31 15:54:49.738  3497  3534 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-31 15:54:49.738  3497  3534 D BluetoothAdapterProperties: Setting state to 10
08-31 15:54:49.738  3497  3534 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-31 15:54:49.739  3497  3534 I BluetoothAdapterState: Entering OffState
,08-31 15:54:49.741   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-31 15:54:49.761  3497  3497 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-31 15:54:49.762  3497  3497 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-31 15:54:49.762  3497  3497 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-31 15:54:49.763  3497  3536 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-31 15:54:49.766  3497  3536 D bt_stack_manager: event_clean_up_stack finished.
,08-31 15:54:49.781  3497  3497 I art     : System.exit called, status: 0
,08-31 15:54:49.781  3497  3497 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 15:54:49.851   874  1964 I ActivityManager: Process com.android.bluetooth (pid 3497) has died
,08-31 15:54:50.519  3802  3828 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-31 15:54:50.752  3689  3777 E YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1033 Scheduled config refresh failed
,08-31 15:54:50.763   874  1924 I ActivityManager: Killing 3375:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-31 15:54:50.779   874  3623 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on <unknown ssid>, connectivitycheck.gstatic.com=2a00:1450:4001:81c::200e
,08-31 15:54:50.793   874  3623 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.SocketException: Binding socket to network 100 failed: ENONET (Machine is not on the network)
,08-31 15:54:50.796   874  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-31 15:54:50.819   874  1924 I ActivityManager: Killing 3181:com.google.android.gms.wearable/u0a11 (adj 15): empty #18
,08-31 15:54:51.053  1515  3915 I VacuumService: Vacuum at: now=1472651691053 tag=VacuumService
,08-31 15:54:52.249   874  1307 D ConnectivityService: handlePromptUnvalidated 100
,08-31 15:54:52.302   874   891 I ActivityManager: Start proc 3916:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-31 15:54:52.437  3916  3916 D AdapterServiceConfig: Adding HeadsetService
,08-31 15:54:52.437  3916  3916 D AdapterServiceConfig: Adding A2dpService
,08-31 15:54:52.437  3916  3916 D AdapterServiceConfig: Adding HidService
08-31 15:54:52.438  3916  3916 D AdapterServiceConfig: Adding HealthService
,08-31 15:54:52.438  3916  3916 D AdapterServiceConfig: Adding PanService
08-31 15:54:52.438  3916  3916 D AdapterServiceConfig: Adding GattService
,08-31 15:54:52.438  3916  3916 D AdapterServiceConfig: Adding BluetoothMapService
,08-31 15:54:52.455   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2dcb3ed:true
,08-31 15:54:52.455  3916  3916 D BluetoothAdapterState: make() - Creating AdapterState
,08-31 15:54:52.462  3916  3916 I bt_bluedroid: init
,08-31 15:54:52.464  3916  3928 I BluetoothAdapterState: Entering OffState
,08-31 15:54:52.469  3916  3929 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 15:54:52.470  3916  3929 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 15:54:52.470  3916  3929 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-31 15:54:52.470  3916  3929 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 15:54:52.472  3916  3916 I bt_bluedroid: get_profile_interface socket
,08-31 15:54:52.475  3916  3932 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 15:54:52.477  3916  3932 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 15:54:52.477  3916  3916 I bt_bluedroid: get_profile_interface sdp
,08-31 15:54:52.485  3916  3927 I bt_bluedroid: config_hci_snoop_log
,08-31 15:54:52.488   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-31 15:54:52.499  3916  3928 D BluetoothAdapterState: Current state: OFF, message: 0
,08-31 15:54:52.500  3916  3928 D BluetoothAdapterProperties: Setting state to 14
,08-31 15:54:52.500  3916  3928 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-31 15:54:52.506  3916  3928 D BluetoothBondStateMachine: make
,08-31 15:54:52.511  3916  3933 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 15:54:52.518  3916  3928 I BluetoothAdapterState: Entering PendingCommandState
,08-31 15:54:52.521  3916  3916 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-31 15:54:52.530  3916  3916 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
,08-31 15:54:52.533  3916  3916 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 15:54:52.534  3916  3916 D BtGatt.GattService: Received start request. Starting profile...
,08-31 15:54:52.535  3916  3916 D BtGatt.GattService: start()
08-31 15:54:52.535  3916  3916 I bt_bluedroid: get_profile_interface gatt
,08-31 15:54:52.537  3916  3916 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
,08-31 15:54:52.538  3916  3916 D BtGatt.AdvertiseManager: advertise manager created
,08-31 15:54:52.553  3916  3916 V BluetoothAdapterState: isTurningOff()=false
,08-31 15:54:52.554  3916  3916 V BluetoothAdapterState: isTurningOn()=false
,08-31 15:54:52.554  3916  3916 V BluetoothAdapterState: isBleTurningOn()=true
,08-31 15:54:52.554  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:54:52.555  3916  3928 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-31 15:54:52.556  3916  3928 I bt_bluedroid: enable
,08-31 15:54:52.557  3916  3929 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-31 15:54:52.557  3916  3929 I bt_hci  : start_up
,08-31 15:54:52.577  3916  3929 I bt_vendor: alloc value 0xb39b0189
08-31 15:54:52.577  3916  3929 I bt_vendor: init
,08-31 15:54:52.577  3916  3929 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-31 15:54:52.578  3916  3929 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-31 15:54:52.687  3916  3929 D bt_hci  : start_up starting async portion
,08-31 15:54:52.688  3916  3936 I bt_hci  : event_finish_startup
08-31 15:54:52.689  3916  3936 I bt_hci_h4: hal_open
08-31 15:54:52.689  3916  3936 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 15:54:52.695  3916  3936 I bt_userial_vendor: device fd = 51 open
,08-31 15:54:52.729  3916  3936 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 15:54:52.761  3916  3936 D bt_hwcfg: Chipset BCM4354A2
,08-31 15:54:52.761  3916  3936 D bt_hwcfg: Target name = [BCM4354A2]
08-31 15:54:52.762  3916  3936 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-31 15:54:53.389  3916  3936 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-31 15:54:53.391  3916  3936 D bt_hwcfg: Settlement delay -- 100 ms
,08-31 15:54:53.391  3916  3936 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 15:54:53.509  3916  3936 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 15:54:53.510  3916  3936 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-31 15:54:53.539  3916  3936 I bt_hwcfg: vendor lib fwcfg completed
,08-31 15:54:53.539  3916  3936 I bt_vendor: firmware callback
,08-31 15:54:53.540  3916  3936 I bt_hci  : firmware_config_callback
,08-31 15:54:53.553  3916  3938 I bt_btu  : btu_task pending for preload complete event
,08-31 15:54:53.554  3916  3938 I bt_btu_task: Bluetooth chip preload is complete
08-31 15:54:53.554  3916  3938 I bt_btu  : btu_task received preload complete event
,08-31 15:54:53.566  3916  3938 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 15:54:53.567  3916  3938 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-31 15:54:53.567  3916  3938 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 15:54:53.567  3916  3938 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 15:54:53.568  3916  3938 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 15:54:53.568  3916  3938 I         : BTE_InitTraceLevels -- TRC_A2D
,08-31 15:54:53.569  3916  3938 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 15:54:53.569  3916  3938 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 15:54:53.569  3916  3938 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 15:54:53.570  3916  3938 I         : BTE_InitTraceLevels -- TRC_PAN
,08-31 15:54:53.570  3916  3938 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 15:54:53.571  3916  3938 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 15:54:53.571  3916  3938 I         : BTE_InitTraceLevels -- TRC_SMP
,08-31 15:54:53.571  3916  3938 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 15:54:53.571  3916  3938 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 15:54:53.707  3916  3938 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb392dd9d
,08-31 15:54:53.708  3916  3938 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb392dd9d 
,08-31 15:54:53.720  3916  3932 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-31 15:54:53.721  3916  3932 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-31 15:54:53.723  3916  3932 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 15:54:53.726  3916  3932 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 15:54:53.730  3916  3932 D BluetoothAdapterProperties: Scan Mode:20
,08-31 15:54:53.731  3916  3932 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 15:54:53.731  3916  3932 D bt_hci  : do_postload posting postload work item
08-31 15:54:53.731  3916  3936 I bt_hci  : event_postload
,08-31 15:54:53.731  3916  3936 I bt_vendor: sco_config_cb
08-31 15:54:53.731  3916  3936 I bt_hci  : sco_config_callback postload finished.
08-31 15:54:53.734  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:54:53.734  3916  3932 D bt_bte_conf: Device ID record 1 : primary
08-31 15:54:53.734  3916  3932 D bt_bte_conf:   vendorId            = 000f
08-31 15:54:53.735  3916  3932 D bt_bte_conf:   vendorIdSource      = 0001
,08-31 15:54:53.735  3916  3932 D bt_bte_conf:   product             = 1200
08-31 15:54:53.735  3916  3932 D bt_bte_conf:   version             = 1436
08-31 15:54:53.735  3916  3932 D bt_bte_conf:   clientExecutableURL = 
,08-31 15:54:53.736  3916  3932 D bt_bte_conf:   serviceDescription  = 
08-31 15:54:53.736  3916  3932 D bt_bte_conf:   documentationURL    = 
,08-31 15:54:53.736  3916  3932 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-31 15:54:53.736  3916  3929 D bt_stack_manager: event_start_up_stack finished
08-31 15:54:53.738  3916  3936 I bt_vendor: low_power_mode_cb
,08-31 15:54:53.738  3916  3928 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-31 15:54:53.739  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:54:53.739  3916  3928 D BluetoothAdapterProperties: Setting state to 15
08-31 15:54:53.739  3916  3928 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-31 15:54:53.741  3916  3928 I BluetoothAdapterState: Entering BleOnState
,08-31 15:54:53.750  3916  3928 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-31 15:54:53.750  3916  3928 D BluetoothAdapterProperties: Setting state to 11
08-31 15:54:53.750  3916  3928 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-31 15:54:53.754  3916  3916 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
,08-31 15:54:53.758  3916  3916 D HeadsetService: Received start request. Starting profile...
,08-31 15:54:53.761  3916  3916 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 15:54:53.761  3916  3916 D HeadsetStateMachine: make
,08-31 15:54:53.762  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:54:53.764  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:54:53.772  3916  3928 I BluetoothAdapterState: Entering PendingCommandState
,08-31 15:54:53.774  3916  3916 D HeadsetStateMachine: max_hf_connections = 1
,08-31 15:54:53.774  3916  3916 I bt_bluedroid: get_profile_interface handsfree
,08-31 15:54:53.774  3916  3932 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-31 15:54:53.774  3916  3932 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-31 15:54:53.778  3916  3916 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
,08-31 15:54:53.779  3916  3916 D A2dpService: Received start request. Starting profile...
,08-31 15:54:53.779  3916  3916 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 15:54:53.780  3916  3916 I bt_bluedroid: get_profile_interface avrcp
,08-31 15:54:53.786  3916  3916 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 15:54:53.786  3916  3916 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 15:54:53.787  3916  3916 D A2dpStateMachine: make
,08-31 15:54:53.788  3916  3916 I bt_bluedroid: get_profile_interface a2dp
,08-31 15:54:53.789  3916  3932 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-31 15:54:53.793  3916  3947 D A2dpStateMachine: Enter Disconnected: -2
,08-31 15:54:53.794  3916  3916 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 15:54:53.795  3916  3916 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
,08-31 15:54:53.796  3916  3916 D HidService: Received start request. Starting profile...
,08-31 15:54:53.797  3916  3916 I bt_bluedroid: get_profile_interface hidhost
,08-31 15:54:53.797  3916  3932 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb390f3e5
08-31 15:54:53.797  3916  3916 D HidService: setHidService(): set to: null
08-31 15:54:53.797  3916  3932 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-31 15:54:53.799  3916  3916 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 15:54:53.801  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 15:54:53.803  3916  3916 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
,08-31 15:54:53.804  3916  3916 D HealthService: Received start request. Starting profile...
,08-31 15:54:53.806  3916  3916 I bt_bluedroid: get_profile_interface health
,08-31 15:54:53.806  3916  3916 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 15:54:53.807  3916  3916 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
,08-31 15:54:53.808  3916  3916 D PanService: Received start request. Starting profile...,
,08-31 15:54:53.808  3916  3916 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 15:54:53.808  3916  3916 I bt_bluedroid: get_profile_interface pan
,08-31 15:54:53.812  3916  3932 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 15:54:53.815  3916  3916 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
,08-31 15:54:53.815  3916  3916 D BluetoothMapService: Received start request. Starting profile...
,08-31 15:54:53.815  3916  3916 D BluetoothMapService: start()
,08-31 15:54:53.818  3916  3916 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-31 15:54:53.819  3916  3916 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER,
08-31 15:54:53.819  3916  3916 D BluetoothMapAppObserver: createReceiver()
,08-31 15:54:53.821  3916  3916 D BluetoothMapAppObserver: initObservers()
,08-31 15:54:53.821  3916  3916 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-31 15:54:53.834  3916  3916 V BluetoothAdapterState: isTurningOff()=false
,08-31 15:54:53.834  3916  3916 V BluetoothAdapterState: isTurningOn()=true
08-31 15:54:53.834  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:54:53.834  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 15:54:53.837  3916  3916 V BluetoothAdapterState: isTurningOff()=false
,08-31 15:54:53.837  3916  3916 V BluetoothAdapterState: isTurningOn()=true
08-31 15:54:53.837  3916  3944 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-31 15:54:53.837  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 15:54:53.837  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:54:53.838  3916  3916 V BluetoothAdapterState: isTurningOff()=false
,08-31 15:54:53.838  3916  3916 V BluetoothAdapterState: isTurningOn()=true
08-31 15:54:53.838  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:54:53.838  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:54:53.841  3916  3916 V BluetoothAdapterState: isTurningOff()=false
,08-31 15:54:53.842  3916  3916 V BluetoothAdapterState: isTurningOn()=true
08-31 15:54:53.842  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:54:53.842  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:54:53.842  3916  3916 V BluetoothAdapterState: isTurningOff()=false
08-31 15:54:53.842  3916  3916 V BluetoothAdapterState: isTurningOn()=true
08-31 15:54:53.842  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:54:53.843  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 15:54:53.843  3916  3916 V BluetoothAdapterState: isTurningOff()=false
,08-31 15:54:53.843  3916  3916 V BluetoothAdapterState: isTurningOn()=true
08-31 15:54:53.843  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 15:54:53.843  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:54:53.844  3916  3928 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-31 15:54:53.844  3916  3928 D BluetoothAdapterProperties: ScanMode =  20
,08-31 15:54:53.844  3916  3928 D BluetoothAdapterProperties: State =  11
08-31 15:54:53.845  3916  3928 D BluetoothAdapterProperties: Setting state to 12
08-31 15:54:53.845  3916  3928 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 15:54:53.846  1346  1358 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:54:53.847  3916  3928 I BluetoothAdapterState: Entering OnState
,08-31 15:54:53.847  3554  3566 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 15:54:53.848  3916  3932 D BluetoothAdapterProperties: Scan Mode:21
08-31 15:54:53.849  3916  3932 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 15:54:53.851  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:54:53.851  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:54:53.851  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:54:53.851  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:54:53.851  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:54:53.851  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:54:53.851  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:54:53.851  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:54:53.852  3916  3916 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-31 15:54:53.852  3916  3916 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-31 15:54:53.854  1346  2054 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 15:54:53.854  3442  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:54:53.855  3916  3916 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:54:53.857  3554  3564 D BluetoothMap: onBluetoothStateChange: up=true,
08-31 15:54:53.858  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:54:53.858  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:54:53.858  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:54:53.858  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:54:53.858  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:54:53.858  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:54:53.858  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:54:53.858  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:54:53.858   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:54:53.858  1346  1361 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 15:54:53.859  3916  3916 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:54:53.860  3442  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:54:53.861   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:54:53.861  3916  3916 D ObexServerSockets: Succeed to create listening sockets 
,08-31 15:54:53.861  3916  3916 D ObexServerSockets0: startAccept()
,08-31 15:54:53.861  3916  3916 D ObexServerSockets0: prepareForNewConnect()
,08-31 15:54:53.861  1346  1358 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 15:54:53.863  3916  3916 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-31 15:54:53.863  3916  3916 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-31 15:54:53.864  3916  3953 D ObexServerSockets0: Accepting socket connection...
,08-31 15:54:53.866  1346  2054 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 15:54:53.866  1346  1346 D BluetoothMap: Proxy object connected
,08-31 15:54:53.866  1346  1346 D MapProfile: Bluetooth service connected,
,08-31 15:54:53.866  1346  1346 D BluetoothMap: getConnectedDevices()
,08-31 15:54:53.866  3916  3954 D ObexServerSockets0: Accepting socket connection...,
,08-31 15:54:53.867  3554  3554 D BluetoothMap: Proxy object connected
,08-31 15:54:53.867  3554  3554 D MapProfile: Bluetooth service connected
,08-31 15:54:53.867  3554  3554 D BluetoothMap: getConnectedDevices()
08-31 15:54:53.868  1346  1346 D BluetoothA2dp: Proxy object connected
,08-31 15:54:53.868  1346  1358 D BluetoothPan: onBluetoothStateChange on: true
,08-31 15:54:53.869  3554  3554 D BluetoothInputDevice: Proxy object connected
08-31 15:54:53.869  3554  3554 D HidProfile: Bluetooth service connected
,08-31 15:54:53.870  1346  1346 D BluetoothInputDevice: Proxy object connected
,08-31 15:54:53.870  1346  1346 D HidProfile: Bluetooth service connected
,08-31 15:54:53.870  3554  3564 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 15:54:53.872  1346  1346 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 15:54:53.872  1346  1346 D PanProfile: Bluetooth service connected
,08-31 15:54:53.874  3554  3566 D BluetoothPan: onBluetoothStateChange on: true
,08-31 15:54:53.876  3554  3554 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 15:54:53.876  1951  1963 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:54:53.876  3554  3554 D PanProfile: Bluetooth service connected
08-31 15:54:53.876   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 15:54:53.877   874   874 D BluetoothA2dp: Proxy object connected
,08-31 15:54:53.877  3554  3564 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:54:53.877   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:54:53.878  3554  3906 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 15:54:53.880  3554  3554 D BluetoothA2dp: Proxy object connected
,08-31 15:54:53.881   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 15:54:53.882  3916  3916 D BluetoothMapService: onReceive
08-31 15:54:53.882  3916  3916 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:54:53.882  3916  3916 D BluetoothMapService: STATE_ON
,08-31 15:54:53.884  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:54:53.885  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:54:53.890  3554  3554 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 15:54:53.896  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 15:54:53.901  3554  3554 D DockEventReceiver: finishStartingService: stopping service
,08-31 15:54:53.906  3554  3554 D BluetoothPbap: Proxy object connected
,08-31 15:54:53.906  1346  1346 D BluetoothPbap: Proxy object connected
08-31 15:54:53.906  3554  3554 D PbapServerProfile: Bluetooth service connected
08-31 15:54:53.906  1346  1346 D PbapServerProfile: Bluetooth service connected
,08-31 15:54:53.911  3916  3916 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-31 15:54:53.912  3916  3916 D ObexServerSockets0: prepareForNewConnect()
,08-31 15:54:53.917  3916  3959 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 15:54:53.932  3916  3963 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 15:54:53.933  3916  3963 I BtOppRfcommListener: Accept thread started.
,08-31 15:54:53.947   874   874 D BluetoothHeadset: Proxy object connected
,08-31 15:54:53.947  3554  3566 D BluetoothHeadset: Proxy object connected
,08-31 15:54:53.948   874   874 D BluetoothHeadset: Proxy object connected
,08-31 15:54:53.948  3554  3554 D HeadsetProfile: Bluetooth service connected
08-31 15:54:53.948  1951  2081 D BluetoothHeadset: Proxy object connected
,08-31 15:54:53.948   874   874 D BluetoothHeadset: Proxy object connected
08-31 15:54:53.948  1346  1358 D BluetoothHeadset: Proxy object connected
,08-31 15:54:53.949  1346  1346 D HeadsetProfile: Bluetooth service connected
,08-31 15:54:53.957   874   891 D BluetoothHeadset: Proxy object connected
,08-31 15:54:53.961   874   891 D BluetoothHeadset: Proxy object connected
,08-31 15:54:53.978  1951  2183 D BluetoothHeadset: Proxy object connected
,08-31 15:54:53.978  3554  3906 D BluetoothHeadset: Proxy object connected
,08-31 15:54:53.979   874   891 D BluetoothHeadset: Proxy object connected
08-31 15:54:53.979  3554  3554 D HeadsetProfile: Bluetooth service connected
,08-31 15:54:55.259  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 15:54:55.260  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:54:55.582  2716  2727 D Finsky  : [173] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-31 15:54:55.609  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:54:55.627  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:54:55.630  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:54:55.656  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-31 15:54:55.656  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.,
,08-31 15:54:55.656  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 15:54:55.656  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:54:55.675  2716  2727 D Finsky  : [173] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-31 15:54:58.268  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 15:54:58.268  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@61b0db5 added. We now have 6 listener(s)
08-31 15:54:58.269  3442  3492 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:54:58.274  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 15:54:58.275  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6b02c4a added. We now have 7 listener(s)
08-31 15:54:58.275  3442  3492 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:54:58.279  3442  3492 I System.out: IsBluetoothEnabled
,08-31 15:54:58.295  3916  3928 D BluetoothAdapterState: Current state: ON, message: 23
,08-31 15:54:58.296  3916  3928 D BluetoothAdapterProperties: Setting state to 13
08-31 15:54:58.296  3916  3928 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-31 15:54:58.300  3916  3928 D BluetoothAdapterProperties: onBluetoothDisable()
,08-31 15:54:58.302  3916  3916 D BluetoothMapService: onReceive
08-31 15:54:58.303  3916  3916 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:54:58.303  3916  3916 D BluetoothMapService: STATE_TURNING_OFF
08-31 15:54:58.304  3916  3916 D BluetoothMapService: MAP Service closeService in
08-31 15:54:58.304  3916  3916 D BluetoothMapMasInstance0: MAP Service shutdown
08-31 15:54:58.304  3916  3916 D ObexServerSockets0: shutdown(block = true)
08-31 15:54:58.305  3916  3953 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-31 15:54:58.306  3442  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:54:58.306  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:54:58.306  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:54:58.306  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:54:58.306  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:54:58.306  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:54:58.306  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:54:58.306  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:54:58.306  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:54:58.308  3916  3916 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 15:54:58.309  3916  3954 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-31 15:54:58.310  3916  3928 I BluetoothAdapterState: Entering PendingCommandState
08-31 15:54:58.312  3916  3941 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-31 15:54:58.313  3442  3442 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:54:58.313  3442  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:54:58.313  3916  3932 D BluetoothAdapterProperties: Scan Mode:20
08-31 15:54:58.314  3916  3928 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-31 15:54:58.316  3554  3554 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 15:54:58.313  3916  3916 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-31 15:54:58.319  3916  3916 I BtOppRfcommListener: stopping Accept Thread
08-31 15:54:58.319  3916  3963 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-31 15:54:58.325  3916  3963 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 15:54:58.326  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:54:58.327  3916  3916 D HeadsetService: Received stop request...Stopping profile...
,08-31 15:54:58.334   874   874 D BluetoothHeadset: Proxy object disconnected
08-31 15:54:58.336  3554  3906 D BluetoothHeadset: Proxy object disconnected
08-31 15:54:58.336   874   874 D BluetoothHeadset: Proxy object disconnected
,08-31 15:54:58.337  1951  1962 D BluetoothHeadset: Proxy object disconnected
08-31 15:54:58.337   874   874 D BluetoothHeadset: Proxy object disconnected
08-31 15:54:58.337  3916  3916 D A2dpService: Received stop request...Stopping profile...
08-31 15:54:58.337  1346  1358 D BluetoothHeadset: Proxy object disconnected
,08-31 15:54:58.338  3916  3947 D A2dpStateMachine: Exit Disconnected: -1
08-31 15:54:58.339   874   874 D BluetoothA2dp: Proxy object disconnected
08-31 15:54:58.341  3916  3916 D HidService: Received stop request...Stopping profile...
08-31 15:54:58.341  3916  3916 D HidService: Stopping Bluetooth HidService
,08-31 15:54:58.342  3916  3916 V BluetoothAdapterState: isTurningOff()=true
08-31 15:54:58.342  3916  3916 V BluetoothAdapterState: isTurningOn()=false
,08-31 15:54:58.343  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 15:54:58.343  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:54:58.343  1346  1346 D HeadsetProfile: Bluetooth service disconnected
08-31 15:54:58.343  3916  3916 D HealthService: Received stop request...Stopping profile...
08-31 15:54:58.344  1346  1346 D BluetoothA2dp: Proxy object disconnected
08-31 15:54:58.344  1346  1346 D BluetoothInputDevice: Proxy object disconnected
,08-31 15:54:58.344  1346  1346 D HidProfile: Bluetooth service disconnected
08-31 15:54:58.346  3916  3916 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-31 15:54:58.346  3916  3916 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 15:54:58.346  3916  3932 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-31 15:54:58.347  3916  3938 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 15:54:58.347  3916  3938 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 15:54:58.347  3916  3916 D PanService: Received stop request...Stopping profile...
08-31 15:54:58.347  3916  3938 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 15:54:58.347  3916  3932 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-31 15:54:58.349  3916  3916 D BluetoothMapService: Received stop request...Stopping profile...
,08-31 15:54:58.349  3916  3916 D BluetoothMapService: stop()
08-31 15:54:58.349  1346  1346 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 15:54:58.349  1346  1346 D PanProfile: Bluetooth service disconnected
08-31 15:54:58.349  3916  3916 D BluetoothMapAppObserver: deinitObservers()
,08-31 15:54:58.350  3916  3916 D BluetoothMapAppObserver: removeReceiver()
08-31 15:54:58.351  1346  1346 D BluetoothMap: Proxy object disconnected
08-31 15:54:58.352  1346  1346 D MapProfile: Bluetooth service disconnected
08-31 15:54:58.352  3554  3554 D DockEventReceiver: finishStartingService: stopping service
,08-31 15:54:58.354  3554  3554 D HeadsetProfile: Bluetooth service disconnected
,08-31 15:54:58.355  3554  3554 D BluetoothA2dp: Proxy object disconnected
08-31 15:54:58.355  3916  3916 V BluetoothAdapterState: isTurningOff()=true
08-31 15:54:58.355  3916  3916 V BluetoothAdapterState: isTurningOn()=false
08-31 15:54:58.355  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:54:58.355  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:54:58.356  3554  3554 D BluetoothInputDevice: Proxy object disconnected
08-31 15:54:58.356  3554  3554 D HidProfile: Bluetooth service disconnected
08-31 15:54:58.357  3916  3938 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-31 15:54:58.357  3916  3938 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 15:54:58.357  3916  3938 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:54:58.357  3916  3916 V BluetoothAdapterState: isTurningOff()=true
08-31 15:54:58.357  3916  3938 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-31 15:54:58.357  3916  3916 V BluetoothAdapterState: isTurningOn()=false
08-31 15:54:58.357  3916  3938 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:54:58.357  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:54:58.357  3916  3938 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:54:58.357  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:54:58.357  3916  3932 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-31 15:54:58.358  3554  3554 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 15:54:58.358  3916  3916 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 15:54:58.358  3916  3916 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 15:54:58.358  3916  3932 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 15:54:58.358  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 15:54:58.358  3554  3554 D PanProfile: Bluetooth service disconnected
08-31 15:54:58.358  3916  3916 V BluetoothAdapterState: isTurningOff()=true
08-31 15:54:58.358  3916  3916 V BluetoothAdapterState: isTurningOn()=false
,08-31 15:54:58.358  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:54:58.359  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:54:58.359  3916  3916 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 15:54:58.359  3916  3932 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-31 15:54:58.359  3554  3554 D BluetoothMap: Proxy object disconnected
08-31 15:54:58.359  3554  3554 D MapProfile: Bluetooth service disconnected
08-31 15:54:58.359  3916  3916 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 15:54:58.359  3916  3916 V BluetoothAdapterState: isTurningOff()=true
08-31 15:54:58.359  3916  3916 V BluetoothAdapterState: isTurningOn()=false
08-31 15:54:58.360  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:54:58.360  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:54:58.360  3916  3916 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-31 15:54:58.360  3916  3916 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-31 15:54:58.361  3916  3916 D BluetoothMapService: MAP Service closeService in
08-31 15:54:58.361  3916  3916 V BluetoothAdapterState: isTurningOff()=true
08-31 15:54:58.361  3916  3916 V BluetoothAdapterState: isTurningOn()=false
08-31 15:54:58.361  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:54:58.361  3916  3916 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:54:58.361  3916  3928 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-31 15:54:58.361  3916  3916 D BluetoothMapService: cleanup()
08-31 15:54:58.362  3916  3928 D BluetoothAdapterProperties: Setting state to 15
08-31 15:54:58.362  3916  3916 D BluetoothMapService: MAP Service closeService in
08-31 15:54:58.362  3916  3928 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-31 15:54:58.363  3916  3928 I BluetoothAdapterState: Entering BleOnState
08-31 15:54:58.365  1346  1346 D BluetoothPbap: Proxy object disconnected
08-31 15:54:58.365  1346  1346 D PbapServerProfile: Bluetooth service disconnected
08-31 15:54:58.365  3554  3554 D BluetoothPbap: Proxy object disconnected
08-31 15:54:58.365  3554  3554 D PbapServerProfile: Bluetooth service disconnected
,08-31 15:54:58.367  1346  1358 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 15:54:58.367  3554  3564 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 15:54:58.369  1346  1361 D BluetoothMap: onBluetoothStateChange: up=false
,08-31 15:54:58.369  3554  3566 D BluetoothMap: onBluetoothStateChange: up=false,
08-31 15:54:58.370   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:54:58.370  1346  2054 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 15:54:58.370   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:54:58.370  1346  1358 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 15:54:58.373  1346  1361 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-31 15:54:58.373  1346  2054 D BluetoothPan: onBluetoothStateChange on: false
,08-31 15:54:58.374  3554  3906 D BluetoothPbap: onBluetoothStateChange: up=false
,08-31 15:54:58.374  3554  3564 D BluetoothPan: onBluetoothStateChange on: false
08-31 15:54:58.375  1951  1963 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 15:54:58.375   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 15:54:58.376  3554  3566 D BluetoothHeadset: onBluetoothStateChange: up=false
08-31 15:54:58.377   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-31 15:54:58.377  3554  3906 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 15:54:58.377  3916  3928 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-31 15:54:58.378  3916  3928 D BluetoothAdapterProperties: Setting state to 16
08-31 15:54:58.378  3916  3928 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-31 15:54:58.378  3916  3928 D BluetoothAdapterProperties: onBleDisable
08-31 15:54:58.378  3916  3928 I BluetoothAdapterState: Entering PendingCommandState
,08-31 15:54:58.379  3916  3929 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-31 15:54:58.380  3916  3938 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-31 15:54:58.381  3916  3938 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-31 15:54:58.381  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:54:58.382  3916  3932 D BluetoothAdapterProperties: Scan Mode:20
,08-31 15:54:58.383  3554  3554 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-31 15:54:58.386  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:54:58.388  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 15:54:58.395  3554  3554 D DockEventReceiver: finishStartingService: stopping service
,08-31 15:54:58.584  3916  3932 I bt_hci  : shut_down
,08-31 15:54:58.585  3916  3936 D bt_hwcfg: hw_epilog_process
,08-31 15:54:58.589  3916  3936 I bt_vendor: low_power_mode_cb
,08-31 15:54:58.608  3916  3936 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-31 15:54:58.608  3916  3936 I bt_vendor: epilog_cb
,08-31 15:54:58.608  3916  3936 I bt_hci  : epilog_finished_callback
,08-31 15:54:58.617  3916  3932 I bt_hci_h4: hal_close
,08-31 15:54:58.619  3916  3932 I bt_userial_vendor: device fd = 51 close
,08-31 15:54:58.746  3916  3929 D bt_stack_manager: event_shut_down_stack finished.
,08-31 15:54:58.747  3916  3928 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-31 15:54:58.753  3916  3916 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 15:54:58.752  3916  3928 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-31 15:54:58.755  3916  3916 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 15:54:58.755  3916  3916 D BtGatt.GattService: stop()
08-31 15:54:58.756  3916  3916 D BtGatt.AdvertiseManager: advertise clients cleared
,08-31 15:54:58.763  3916  3916 V BluetoothAdapterState: isTurningOff()=false
,08-31 15:54:58.763  3916  3916 V BluetoothAdapterState: isTurningOn()=false
08-31 15:54:58.764  3916  3916 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 15:54:58.764  3916  3916 V BluetoothAdapterState: isBleTurningOff()=true
08-31 15:54:58.765  3916  3928 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-31 15:54:58.766  3916  3928 D BluetoothAdapterProperties: Setting state to 10
08-31 15:54:58.766  3916  3928 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-31 15:54:58.767  3916  3928 I BluetoothAdapterState: Entering OffState
,08-31 15:54:58.770   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-31 15:54:58.794  3916  3916 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-31 15:54:58.794  3916  3916 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-31 15:54:58.795  3916  3929 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-31 15:54:58.800  3916  3929 D bt_stack_manager: event_clean_up_stack finished.
,08-31 15:54:58.800  3916  3916 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-31 15:54:58.805  3916  3916 I art     : System.exit called, status: 0
,08-31 15:54:58.805  3916  3916 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 15:54:58.870   874  1964 I ActivityManager: Process com.android.bluetooth (pid 3916) has died
,08-31 15:54:59.300  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:54:59.301  3442  3492 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:54:59.301  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:54:59.301  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:54:59.301  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:54:59.301  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:54:59.301  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:54:59.301  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:54:59.301  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:54:59.301  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:54:59.302  3442  3492 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:54:59.356   874   891 I ActivityManager: Start proc 3973:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-31 15:54:59.481  3973  3973 D AdapterServiceConfig: Adding HeadsetService
,08-31 15:54:59.482  3973  3973 D AdapterServiceConfig: Adding A2dpService
08-31 15:54:59.482  3973  3973 D AdapterServiceConfig: Adding HidService
,08-31 15:54:59.483  3973  3973 D AdapterServiceConfig: Adding HealthService
08-31 15:54:59.483  3973  3973 D AdapterServiceConfig: Adding PanService
,08-31 15:54:59.483  3973  3973 D AdapterServiceConfig: Adding GattService
,08-31 15:54:59.483  3973  3973 D AdapterServiceConfig: Adding BluetoothMapService
,08-31 15:54:59.497   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3af0519:true
08-31 15:54:59.497  3973  3973 D BluetoothAdapterState: make() - Creating AdapterState
,08-31 15:54:59.503  3973  3973 I bt_bluedroid: init
,08-31 15:54:59.503  3973  3985 I BluetoothAdapterState: Entering OffState
,08-31 15:54:59.509  3973  3986 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 15:54:59.509  3973  3986 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 15:54:59.510  3973  3986 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-31 15:54:59.510  3973  3986 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-31 15:54:59.512  3973  3973 I bt_bluedroid: get_profile_interface socket
,08-31 15:54:59.514  3973  3973 I bt_bluedroid: get_profile_interface sdp
,08-31 15:54:59.520  3973  3989 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-31 15:54:59.520  3973  3984 I bt_bluedroid: config_hci_snoop_log
,08-31 15:54:59.523  3973  3989 D BluetoothAdapterProperties: Name is: Nexus 6
08-31 15:54:59.524   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-31 15:54:59.538  3973  3985 D BluetoothAdapterState: Current state: OFF, message: 0
,08-31 15:54:59.538  3973  3985 D BluetoothAdapterProperties: Setting state to 14
08-31 15:54:59.539  3973  3985 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-31 15:54:59.543  3973  3985 D BluetoothBondStateMachine: make
,08-31 15:54:59.549  3973  3990 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 15:54:59.557  3973  3985 I BluetoothAdapterState: Entering PendingCommandState
,08-31 15:54:59.558  3973  3973 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-31 15:54:59.562  3973  3973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
,08-31 15:54:59.563  3973  3973 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 15:54:59.564  3973  3973 D BtGatt.GattService: Received start request. Starting profile...
08-31 15:54:59.564  3973  3973 D BtGatt.GattService: start()
08-31 15:54:59.564  3973  3973 I bt_bluedroid: get_profile_interface gatt
,08-31 15:54:59.565  3973  3973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
08-31 15:54:59.565  3973  3973 D BtGatt.AdvertiseManager: advertise manager created
,08-31 15:54:59.577  3973  3973 V BluetoothAdapterState: isTurningOff()=false
,08-31 15:54:59.577  3973  3973 V BluetoothAdapterState: isTurningOn()=false
08-31 15:54:59.578  3973  3973 V BluetoothAdapterState: isBleTurningOn()=true
08-31 15:54:59.578  3973  3973 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:54:59.578  3973  3985 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-31 15:54:59.579  3973  3985 I bt_bluedroid: enable
08-31 15:54:59.579  3973  3986 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-31 15:54:59.579  3973  3986 I bt_hci  : start_up
,08-31 15:54:59.590  3973  3986 I bt_vendor: alloc value 0xb39b0189
,08-31 15:54:59.590  3973  3986 I bt_vendor: init
,08-31 15:54:59.591  3973  3986 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-31 15:54:59.591  3973  3986 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-31 15:54:59.699  3973  3986 D bt_hci  : start_up starting async portion
,08-31 15:54:59.700  3973  3993 I bt_hci  : event_finish_startup
,08-31 15:54:59.700  3973  3993 I bt_hci_h4: hal_open
,08-31 15:54:59.700  3973  3993 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-31 15:54:59.711  3973  3993 I bt_userial_vendor: device fd = 51 open
,08-31 15:54:59.743  3973  3993 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 15:54:59.775  3973  3993 D bt_hwcfg: Chipset BCM4354A2
08-31 15:54:59.775  3973  3993 D bt_hwcfg: Target name = [BCM4354A2]
,08-31 15:54:59.776  3973  3993 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-31 15:55:00.419  3973  3993 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-31 15:55:00.421  3973  3993 D bt_hwcfg: Settlement delay -- 100 ms
,08-31 15:55:00.422  3973  3993 I bt_hwcfg: Setting fw settlement delay to 100 
,08-31 15:55:00.538  3973  3993 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-31 15:55:00.540  3973  3993 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-31 15:55:00.568  3973  3993 I bt_hwcfg: vendor lib fwcfg completed
,08-31 15:55:00.569  3973  3993 I bt_vendor: firmware callback
,08-31 15:55:00.569  3973  3993 I bt_hci  : firmware_config_callback
,08-31 15:55:00.580  3973  3995 I bt_btu  : btu_task pending for preload complete event
,08-31 15:55:00.580  3973  3995 I bt_btu_task: Bluetooth chip preload is complete
08-31 15:55:00.580  3973  3995 I bt_btu  : btu_task received preload complete event
,08-31 15:55:00.590  3973  3995 I         : BTE_InitTraceLevels -- TRC_HCI
08-31 15:55:00.591  3973  3995 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 15:55:00.591  3973  3995 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 15:55:00.591  3973  3995 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 15:55:00.592  3973  3995 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-31 15:55:00.592  3973  3995 I         : BTE_InitTraceLevels -- TRC_A2D
,08-31 15:55:00.592  3973  3995 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-31 15:55:00.592  3973  3995 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 15:55:00.593  3973  3995 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 15:55:00.593  3973  3995 I         : BTE_InitTraceLevels -- TRC_PAN
,08-31 15:55:00.593  3973  3995 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 15:55:00.593  3973  3995 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 15:55:00.594  3973  3995 I         : BTE_InitTraceLevels -- TRC_SMP
,08-31 15:55:00.594  3973  3995 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 15:55:00.594  3973  3995 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 15:55:00.727  3973  3995 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb392dd9d
,08-31 15:55:00.727  3973  3995 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb392dd9d 
,08-31 15:55:00.738  3973  3989 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-31 15:55:00.739  3973  3989 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-31 15:55:00.740  3973  3989 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-31 15:55:00.743  3973  3989 D BluetoothAdapterProperties: Name is: Nexus 6
,08-31 15:55:00.748  3973  3989 D BluetoothAdapterProperties: Scan Mode:20
,08-31 15:55:00.749  3973  3989 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 15:55:00.749  3973  3989 D bt_hci  : do_postload posting postload work item
,08-31 15:55:00.750  3973  3993 I bt_hci  : event_postload
08-31 15:55:00.750  3973  3993 I bt_vendor: sco_config_cb
08-31 15:55:00.750  3973  3993 I bt_hci  : sco_config_callback postload finished.
,08-31 15:55:00.753  3973  3989 D bt_bte_conf: Device ID record 1 : primary
08-31 15:55:00.753  3973  3989 D bt_bte_conf:   vendorId            = 000f
08-31 15:55:00.753  3973  3989 D bt_bte_conf:   vendorIdSource      = 0001
08-31 15:55:00.753  3973  3989 D bt_bte_conf:   product             = 1200
08-31 15:55:00.753  3973  3989 D bt_bte_conf:   version             = 1436
08-31 15:55:00.753  3973  3989 D bt_bte_conf:   clientExecutableURL = 
08-31 15:55:00.753  3973  3989 D bt_bte_conf:   serviceDescription  = 
,08-31 15:55:00.753  3973  3989 D bt_bte_conf:   documentationURL    = 
08-31 15:55:00.754  3973  3989 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-31 15:55:00.754  3973  3986 D bt_stack_manager: event_start_up_stack finished
,08-31 15:55:00.754  3973  3985 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-31 15:55:00.755  3973  3985 D BluetoothAdapterProperties: Setting state to 15
,08-31 15:55:00.755  3973  3985 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-31 15:55:00.761  3973  3985 I BluetoothAdapterState: Entering BleOnState
08-31 15:55:00.761  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:55:00.763  3973  3985 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-31 15:55:00.764  3973  3985 D BluetoothAdapterProperties: Setting state to 11
08-31 15:55:00.764  3973  3985 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-31 15:55:00.766  3973  3993 I bt_vendor: low_power_mode_cb
08-31 15:55:00.772  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:55:00.780  3973  3973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
,08-31 15:55:00.781  3973  3973 D HeadsetService: Received start request. Starting profile...
08-31 15:55:00.784  3973  3973 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 15:55:00.784  3973  3973 D HeadsetStateMachine: make
08-31 15:55:00.790  3973  3985 I BluetoothAdapterState: Entering PendingCommandState
,08-31 15:55:00.793  3973  3973 D HeadsetStateMachine: max_hf_connections = 1
,08-31 15:55:00.793  3973  3973 I bt_bluedroid: get_profile_interface handsfree
08-31 15:55:00.794  3973  3989 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-31 15:55:00.794  3973  3989 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-31 15:55:00.796  3973  3973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
,08-31 15:55:00.796  3973  3973 D A2dpService: Received start request. Starting profile...
,08-31 15:55:00.797  3973  3973 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-31 15:55:00.797  3973  3973 I bt_bluedroid: get_profile_interface avrcp
,08-31 15:55:00.804  3973  3973 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 15:55:00.804  3973  3973 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-31 15:55:00.805  3973  3973 D A2dpStateMachine: make
08-31 15:55:00.806  3973  3973 I bt_bluedroid: get_profile_interface a2dp
,08-31 15:55:00.807  3973  3989 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-31 15:55:00.810  3973  4003 D A2dpStateMachine: Enter Disconnected: -2
,08-31 15:55:00.811  3973  3973 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 15:55:00.811  3973  3973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
,08-31 15:55:00.812  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-31 15:55:00.813  3973  3973 D HidService: Received start request. Starting profile...,
08-31 15:55:00.813  3973  3973 I bt_bluedroid: get_profile_interface hidhost
08-31 15:55:00.813  3973  3989 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb390f3e5
08-31 15:55:00.813  3973  3989 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-31 15:55:00.813  3973  3973 D HidService: setHidService(): set to: null
08-31 15:55:00.814  3973  3973 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-31 15:55:00.816  3973  3973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
,08-31 15:55:00.817  3973  3973 D HealthService: Received start request. Starting profile...
,08-31 15:55:00.818  3973  3973 I bt_bluedroid: get_profile_interface health
,08-31 15:55:00.819  3973  3973 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 15:55:00.820  3973  3973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
,08-31 15:55:00.821  3973  3973 D PanService: Received start request. Starting profile...
,08-31 15:55:00.822  3973  3973 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 15:55:00.822  3973  3973 I bt_bluedroid: get_profile_interface pan
,08-31 15:55:00.822  3973  3989 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 15:55:00.828  3973  3973 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
,08-31 15:55:00.829  3973  3973 D BluetoothMapService: Received start request. Starting profile...
08-31 15:55:00.829  3973  3973 D BluetoothMapService: start()
,08-31 15:55:00.831  3973  3973 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-31 15:55:00.832  3973  3973 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-31 15:55:00.832  3973  3973 D BluetoothMapAppObserver: createReceiver()
,08-31 15:55:00.833  3973  3973 D BluetoothMapAppObserver: initObservers()
,08-31 15:55:00.833  3973  3973 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-31 15:55:00.841  3973  3973 V BluetoothAdapterState: isTurningOff()=false
,08-31 15:55:00.841  3973  3973 V BluetoothAdapterState: isTurningOn()=true
,08-31 15:55:00.841  3973  3973 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:55:00.841  3973  3973 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 15:55:00.844  3973  4001 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-31 15:55:00.844  3973  3973 V BluetoothAdapterState: isTurningOff()=false
,08-31 15:55:00.844  3973  3973 V BluetoothAdapterState: isTurningOn()=true
08-31 15:55:00.844  3973  3973 V BluetoothAdapterState: isBleTurningOn()=false
,08-31 15:55:00.844  3973  3973 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:55:00.845  3973  3973 V BluetoothAdapterState: isTurningOff()=false
08-31 15:55:00.845  3973  3973 V BluetoothAdapterState: isTurningOn()=true
08-31 15:55:00.845  3973  3973 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:55:00.845  3973  3973 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:55:00.845  3973  3973 V BluetoothAdapterState: isTurningOff()=false
,08-31 15:55:00.845  3973  3973 V BluetoothAdapterState: isTurningOn()=true
08-31 15:55:00.846  3973  3973 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:55:00.846  3973  3973 V BluetoothAdapterState: isBleTurningOff()=false
,08-31 15:55:00.846  3973  3973 V BluetoothAdapterState: isTurningOff()=false
08-31 15:55:00.846  3973  3973 V BluetoothAdapterState: isTurningOn()=true
,08-31 15:55:00.846  3973  3973 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:55:00.847  3973  3973 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:55:00.847  3973  3973 V BluetoothAdapterState: isTurningOff()=false
,08-31 15:55:00.847  3973  3973 V BluetoothAdapterState: isTurningOn()=true
08-31 15:55:00.847  3973  3973 V BluetoothAdapterState: isBleTurningOn()=false
08-31 15:55:00.848  3973  3973 V BluetoothAdapterState: isBleTurningOff()=false
08-31 15:55:00.848  3973  3985 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-31 15:55:00.848  3973  3985 D BluetoothAdapterProperties: ScanMode =  20
08-31 15:55:00.848  3973  3985 D BluetoothAdapterProperties: State =  11
08-31 15:55:00.851  3973  3989 D BluetoothAdapterProperties: Scan Mode:21
08-31 15:55:00.851  3973  3985 D BluetoothAdapterProperties: Setting state to 12
,08-31 15:55:00.851  3973  3989 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 15:55:00.851  3973  3985 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-31 15:55:00.852  1346  1358 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:55:00.853  3973  3985 I BluetoothAdapterState: Entering OnState
08-31 15:55:00.853  3554  3566 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 15:55:00.855  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:55:00.855  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:55:00.855  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:55:00.855  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:55:00.855  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:55:00.855  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:55:00.855  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:55:00.855  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:55:00.857  1346  1361 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 15:55:00.858  3442  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:55:00.859  3554  3564 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 15:55:00.859  3973  3973 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-31 15:55:00.860  3973  3973 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-31 15:55:00.862   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-31 15:55:00.862  3973  3973 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 15:55:00.862  1346  2054 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 15:55:00.864  3973  3973 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 15:55:00.864   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:55:00.865  1346  1358 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 15:55:00.865  3973  3973 D ObexServerSockets: Succeed to create listening sockets 
08-31 15:55:00.866  3973  3973 D ObexServerSockets0: startAccept()
,08-31 15:55:00.866  3973  3973 D ObexServerSockets0: prepareForNewConnect()
,08-31 15:55:00.867  3554  3554 D BluetoothInputDevice: Proxy object connected
,08-31 15:55:00.867  3554  3554 D HidProfile: Bluetooth service connected
08-31 15:55:00.868  1346  1361 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 15:55:00.868  3973  3973 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-31 15:55:00.868  3973  3973 D BluetoothSdpJni: SDP Create record success - handle: 0
08-31 15:55:00.870  3973  4009 D ObexServerSockets0: Accepting socket connection...
08-31 15:55:00.870  1346  1346 D BluetoothMap: Proxy object connected
08-31 15:55:00.870  1346  1346 D MapProfile: Bluetooth service connected
08-31 15:55:00.870  1346  1346 D BluetoothMap: getConnectedDevices()
08-31 15:55:00.870  1346  1358 D BluetoothPan: onBluetoothStateChange on: true
08-31 15:55:00.872  3554  3554 D BluetoothMap: Proxy object connected
,08-31 15:55:00.872  3554  3554 D MapProfile: Bluetooth service connected
08-31 15:55:00.872  3554  3554 D BluetoothMap: getConnectedDevices()
08-31 15:55:00.872  1346  1346 D BluetoothInputDevice: Proxy object connected
08-31 15:55:00.872  1346  1346 D HidProfile: Bluetooth service connected
08-31 15:55:00.872  3554  3906 D BluetoothPbap: onBluetoothStateChange: up=true
08-31 15:55:00.874  3554  3564 D BluetoothPan: onBluetoothStateChange on: true
08-31 15:55:00.874  3973  4010 D ObexServerSockets0: Accepting socket connection...
,08-31 15:55:00.874  1346  1346 D BluetoothA2dp: Proxy object connected
08-31 15:55:00.877  1951  1963 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:55:00.877  1346  1346 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 15:55:00.877  1346  1346 D PanProfile: Bluetooth service connected
,08-31 15:55:00.878   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 15:55:00.879   874   874 D BluetoothA2dp: Proxy object connected
08-31 15:55:00.879  3554  3906 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:55:00.880   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-31 15:55:00.881  3554  3566 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 15:55:00.883  3554  3554 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 15:55:00.883  3554  3554 D PanProfile: Bluetooth service connected
,08-31 15:55:00.884  3554  3554 D BluetoothA2dp: Proxy object connected
,08-31 15:55:00.884   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,08-31 15:55:00.885  3973  3973 D BluetoothMapService: onReceive
,08-31 15:55:00.886  3973  3973 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:55:00.886  3973  3973 D BluetoothMapService: STATE_ON
,08-31 15:55:00.887  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:55:00.892  3554  3554 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 15:55:00.897  3554  3554 D DockEventReceiver: finishStartingService: stopping service
,08-31 15:55:00.900  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-31 15:55:00.913  1346  1346 D BluetoothPbap: Proxy object connected
,08-31 15:55:00.913  3554  3554 D BluetoothPbap: Proxy object connected
08-31 15:55:00.913  1346  1346 D PbapServerProfile: Bluetooth service connected
08-31 15:55:00.913  3554  3554 D PbapServerProfile: Bluetooth service connected
,08-31 15:55:00.919  3973  3973 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-31 15:55:00.919  3973  3973 D ObexServerSockets0: prepareForNewConnect()
,08-31 15:55:00.930  3973  4018 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 15:55:00.944  3973  4022 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 15:55:00.946  3973  4022 I BtOppRfcommListener: Accept thread started.
,08-31 15:55:00.954   874   874 D BluetoothHeadset: Proxy object connected
,08-31 15:55:00.955  3554  3906 D BluetoothHeadset: Proxy object connected
,08-31 15:55:00.955   874   874 D BluetoothHeadset: Proxy object connected
08-31 15:55:00.956  3554  3554 D HeadsetProfile: Bluetooth service connected
,08-31 15:55:00.956  1951  2081 D BluetoothHeadset: Proxy object connected
,08-31 15:55:00.956   874   874 D BluetoothHeadset: Proxy object connected
08-31 15:55:00.957  1346  1358 D BluetoothHeadset: Proxy object connected
,08-31 15:55:00.957  1346  1346 D HeadsetProfile: Bluetooth service connected
,08-31 15:55:00.962   874   891 D BluetoothHeadset: Proxy object connected
,08-31 15:55:00.965   874   891 D BluetoothHeadset: Proxy object connected
,08-31 15:55:00.978  1951  2183 D BluetoothHeadset: Proxy object connected
,08-31 15:55:00.980  3554  3566 D BluetoothHeadset: Proxy object connected
,08-31 15:55:00.980  3554  3554 D HeadsetProfile: Bluetooth service connected
08-31 15:55:00.980   874   891 D BluetoothHeadset: Proxy object connected
,08-31 15:55:01.325  3442  3492 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:55:01.325  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:55:01.325  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:55:01.325  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:55:01.325  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:55:01.325  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:55:01.325  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:55:01.325  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:55:01.332  3442  3492 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:55:01.335  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 15:55:01.337  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1bd97bb added. We now have 8 listener(s)
,08-31 15:55:01.337  3442  3492 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:55:01.343   874   884 D WifiService: setWifiEnabled: false pid=3442, uid=10000
,08-31 15:55:01.343   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 15:55:01.355  3442  3492 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:55:01.356   874  1980 D WifiService: setWifiEnabled: true pid=3442, uid=10000
08-31 15:55:01.357   874  1980 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-31 15:55:01.368   874  1305 D WifiConfigStore: Loading config and enabling all networks 
,08-31 15:55:01.386  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:55:01.386  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:55:01.386  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:55:01.386  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:55:01.386  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:55:01.386  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:55:01.386  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:55:01.386  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:55:01.393  3442  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:55:01.399   874  1305 D WifiConfigStore: loaded 0 passpoint configs
,08-31 15:55:01.400   874  1305 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-31 15:55:01.401   874  1305 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-31 15:55:01.402   874  1305 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-31 15:55:01.402   874  1305 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-31 15:55:01.402   874  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-31 15:55:01.402   874  1305 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-31 15:55:01.420   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-31 15:55:01.421   373   873 D CommandListener: Setting iface cfg
,08-31 15:55:01.422   874  1304 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,08-31 15:55:01.422   874  1304 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 15:55:01.436   874  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 15:55:01.490   874  1304 D WifiNative-HAL: p2pGetDeviceAddress
,08-31 15:55:01.491   874  1304 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-31 15:55:01.491   874  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-31 15:55:02.380  3442  3492 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:55:02.380  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:55:02.380  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:55:02.380  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:55:02.380  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:55:02.380  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:55:02.380  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:55:02.380  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:55:02.388  3442  3492 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:55:02.404  3442  3492 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-31 15:55:02.407  3442  3492 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-31 15:55:02.409  3442  3492 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ede13fb Bundle[{}]
,08-31 15:55:02.410  3442  3492 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 15:55:02.410  3442  3492 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-31 15:55:02.411  3442  3492 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-31 15:55:02.412  3442  3492 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-31 15:55:02.413  3442  3492 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-31 15:55:02.414  3442  3492 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-31 15:55:02.419  3442  3492 I System.out: Running OutgoingSocketThread
,08-31 15:55:02.422  3442  4028 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 379)
,08-31 15:55:02.424  3442  4028 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42131
,08-31 15:55:02.424  3442  4028 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-31 15:55:03.071   874  1305 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.08 rxSuccessRate=0.04 delta 1000 -> 1000
,08-31 15:55:03.074   874  1305 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-31 15:55:03.074   874  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 15:55:03.094   874  1305 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-31 15:55:03.153   874  1305 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-31 15:55:03.158  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-31 15:55:03.422  3442  3492 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 380)
,08-31 15:55:03.423  3442  3492 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 380)
,08-31 15:55:03.462  3442  3492 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 385)
,08-31 15:55:03.464  3442  3492 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-31 15:55:03.465  3442  3492 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 386)
,08-31 15:55:03.471  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 15:55:03.472  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@796c4d8 added. We now have 2 listener(s)
,08-31 15:55:03.477  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 15:55:03.478  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:55:03.478  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:55:03.478  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:55:03.479  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23bd031 added. We now have 9 listener(s)
08-31 15:55:03.479  3442  3492 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:55:03.480  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 15:55:03.485  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 15:55:03.495  3442  3492 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:55:03.495  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:55:03.495  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:55:03.495  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:55:03.495  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:55:03.495  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:55:03.495  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:55:03.495  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:55:03.501  3442  3492 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:55:03.502  3442  3492 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 15:55:03.502  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 15:55:03.502  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aa3f497 added. We now have 3 listener(s)
,08-31 15:55:03.506  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:55:03.507  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 15:55:03.507  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:55:03.508  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:55:03.508  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 15:55:03.508  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f5684 added. We now have 10 listener(s)
,08-31 15:55:03.509  3442  3492 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:55:03.509  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 15:55:03.509  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:55:03.509  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:55:03.510  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 15:55:03.510  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:55:03.510  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:55:03.510  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 15:55:03.510  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:55:03.510  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@796c4d8 removed from the list
08-31 15:55:03.511  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 15:55:03.511  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23bd031 removed from the list
08-31 15:55:03.511  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 15:55:03.512  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:55:03.514  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:55:03.514  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:55:03.517  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:55:03.517  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:55:03.517  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:55:03.518  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23bd031 not in the list
08-31 15:55:03.518  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:55:03.518  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:55:03.520  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 15:55:03.521  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:55:03.521  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:55:03.521  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f5684 removed from the list
08-31 15:55:03.521  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:55:03.522  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:55:03.522  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:55:03.522  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:55:03.522  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aa3f497 removed from the list
08-31 15:55:03.524  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:55:03.525  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc3e6d added. We now have 2 listener(s)
,08-31 15:55:03.530  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 15:55:03.531  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:55:03.531  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:55:03.531  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:55:03.532  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@249faa2 added. We now have 9 listener(s)
,08-31 15:55:03.532  3442  3492 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:55:03.533  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 15:55:03.539  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 15:55:03.546  3442  3492 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:55:03.546  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:55:03.546  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:55:03.546  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:55:03.546  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:55:03.546  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:55:03.546  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:55:03.546  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:55:03.548  3442  3492 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:55:03.548  3442  3492 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 15:55:03.548  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 15:55:03.549  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37d56f0 added. We now have 3 listener(s)
08-31 15:55:03.550  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 15:55:03.550  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 15:55:03.550  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 15:55:03.551  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 15:55:03.551  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a7b5469 added. We now have 10 listener(s)
08-31 15:55:03.551  3442  3492 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:55:03.551  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:55:03.552  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 15:55:03.552  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-31 15:55:03.552  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 15:55:03.552  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 15:55:03.552  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 15:55:03.558  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:55:03.558  3442  3492 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-31 15:55:03.559  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 15:55:03.565  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 15:55:03.567  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-31 15:55:03.568  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 15:55:03.573  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 15:55:03.573  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 15:55:03.574  3442  3492 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 15:55:03.575  3442  3492 D BluetoothAdapter: STATE_ON
,08-31 15:55:03.581  3973  4008 D BtGatt.GattService: registerClient() - UUID=88b86357-da47-4500-bf31-d240e680a08f
,08-31 15:55:03.582  3973  3989 D BtGatt.GattService: onClientRegistered() - UUID=88b86357-da47-4500-bf31-d240e680a08f, clientIf=5
,08-31 15:55:03.584  3442  3453 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-31 15:55:03.585  3973  3983 D BtGatt.GattService: start scan with filters
,08-31 15:55:03.588  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-31 15:55:03.589  3973  3992 D BtGatt.ScanManager: handling starting scan
,08-31 15:55:03.590  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 15:55:03.591  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-31 15:55:03.591  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-31 15:55:03.591  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 15:55:03.594  3973  3992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@adbc8df
,08-31 15:55:03.599  3973  3989 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
08-31 15:55:03.599  3973  3989 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 15:55:03.600  3973  3992 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-31 15:55:03.605  3442  3492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 15:55:03.606  3442  3492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 15:55:03.606  3442  3442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 15:55:03.608  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-31 15:55:03.609  3973  3989 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-31 15:55:03.609  3973  3989 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 15:55:03.609  3973  3992 D BtGatt.ScanManager: Starting BLE batch scan
08-31 15:55:03.609  3973  3992 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-31 15:55:03.612  3442  3492 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 15:55:03.612  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 15:55:03.612  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 15:55:03.612  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:55:03.612  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 15:55:03.612  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 15:55:03.612  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-31 15:55:03.612  3442  3492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 15:55:03.613  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 15:55:03.613  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 15:55:03.613  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 15:55:03.614  3442  3492 D BluetoothAdapter: STATE_ON
,08-31 15:55:03.615  3973  4014 D BtGatt.GattService: stopScan() - queue size =1
08-31 15:55:03.616  3973  4008 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-31 15:55:03.616  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:55:03.616  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 15:55:03.616  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-31 15:55:03.617  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 15:55:03.617  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 15:55:03.618  3442  3492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 15:55:03.619  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 15:55:03.619  3442  3492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 15:55:03.619  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 15:55:03.619  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 15:55:03.621  3442  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:55:03.621  3442  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 15:55:03.621  3442  3442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 15:55:03.624  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 15:55:03.624  3973  3989 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 15:55:03.624  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:55:03.624  3973  3989 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 15:55:03.624  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:55:03.624  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 15:55:03.625  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 15:55:03.625  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 15:55:03.625  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 15:55:03.625  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cc3e6d removed from the list
,08-31 15:55:03.625  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:55:03.625  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@249faa2 removed from the list
,08-31 15:55:03.625  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 15:55:03.625  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:55:03.626  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:55:03.626  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:55:03.627  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 15:55:03.627  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 15:55:03.627  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 15:55:03.627  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@249faa2 not in the list
,08-31 15:55:03.627  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 15:55:03.627  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:55:03.628  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP],
08-31 15:55:03.629  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-31 15:55:03.629  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 15:55:03.629  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-31 15:55:03.629  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-31 15:55:03.629  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a7b5469 removed from the list
,08-31 15:55:03.629  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 15:55:03.630  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 15:55:03.630  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:55:03.630  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-31 15:55:03.630  3973  3989 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-31 15:55:03.630  3973  3989 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 15:55:03.630  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37d56f0 removed from the list
,08-31 15:55:03.631  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:55:03.631   874  1305 D WifiConfigStore: Retrieve network priorities after PNO.
08-31 15:55:03.631  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@febce25 added. We now have 2 listener(s)
,08-31 15:55:03.637  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 15:55:03.637  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:55:03.637  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:55:03.638  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:55:03.638  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d43bfa added. We now have 9 listener(s)
08-31 15:55:03.638  3442  3492 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:55:03.639  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 15:55:03.640  3973  3989 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 15:55:03.640  3973  3989 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 15:55:03.640  3973  3992 D BtGatt.ScanManager: stopping BLe Batch
08-31 15:55:03.641  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:55:03.641   874  1305 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-31 15:55:03.641   874  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-31 15:55:03.641   874  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-31 15:55:03.646  3973  3989 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 15:55:03.646  3973  3989 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 15:55:03.646  3442  3492 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:55:03.646  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:55:03.646  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:55:03.646  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:55:03.646  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:55:03.646  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:55:03.646  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:55:03.646  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:55:03.646  3973  3992 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-31 15:55:03.648  3442  3492 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:55:03.648  3442  3492 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:55:03.652  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:55:03.654  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:55:03.654  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:55:03.654  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c311408 added. We now have 3 listener(s)
,08-31 15:55:03.656  3973  3989 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 15:55:03.656  3973  3989 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 15:55:03.656  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 15:55:03.656  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:55:03.656  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:55:03.656  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 15:55:03.656  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3027a1 added. We now have 10 listener(s)
,08-31 15:55:03.656  3442  3492 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:55:03.657  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:55:03.657  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:55:03.657  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 15:55:03.657  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-31 15:55:03.657  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:55:03.658  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 15:55:03.659   874  1305 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 15:55:03.661  3442  3492 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 15:55:03.661  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 15:55:03.664  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 15:55:03.665  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 15:55:03.665  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 15:55:03.667  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 15:55:03.667  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 15:55:03.667  3442  3492 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 15:55:03.668  3442  3492 D BluetoothAdapter: STATE_ON
,08-31 15:55:03.669   373   873 D CommandListener: Setting iface cfg
08-31 15:55:03.670   874  1305 D WifiStateMachine: Start Dhcp Watchdog 2
08-31 15:55:03.671  3973  4012 D BtGatt.GattService: registerClient() - UUID=56d6205a-f749-4286-a91a-0a53252df039
08-31 15:55:03.671  3973  3989 D BtGatt.GattService: onClientRegistered() - UUID=56d6205a-f749-4286-a91a-0a53252df039, clientIf=5
08-31 15:55:03.671  3442  3453 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-31 15:55:03.672  3973  4014 D BtGatt.GattService: start scan with filters
,08-31 15:55:03.674  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 15:55:03.674  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 15:55:03.674  3973  3992 D BtGatt.ScanManager: handling starting scan
,08-31 15:55:03.674  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 15:55:03.674  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 15:55:03.676  3442  3492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 15:55:03.676  3442  3492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 15:55:03.676  3442  3442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 15:55:03.677  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-31 15:55:03.679  3973  3989 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 15:55:03.679  3973  3989 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 15:55:03.679  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:55:03.679  3442  3492 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-31 15:55:03.679  3973  3992 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-31 15:55:03.679  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:55:03.679  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:55:03.679  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:55:03.679   874  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-31 15:55:03.680  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:55:03.680   874  1307 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-31 15:55:03.680  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:55:03.680  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 15:55:03.680  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:55:03.680  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@febce25 removed from the list
08-31 15:55:03.680  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:55:03.680  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d43bfa removed from the list
08-31 15:55:03.680  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:55:03.680  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:55:03.680   874  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
08-31 15:55:03.681  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-31 15:55:03.681  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-31 15:55:03.681  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:55:03.681  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:55:03.682  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAd,vertising
08-31 15:55:03.682  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:55:03.682  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:55:03.682  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d43bfa not in the list
08-31 15:55:03.682  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 15:55:03.682  3442  3492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 15:55:03.682  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 15:55:03.682  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 15:55:03.682  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 15:55:03.683  3442  3492 D BluetoothAdapter: STATE_ON
08-31 15:55:03.683  3973  4012 D BtGatt.GattService: stopScan() - queue size =1
08-31 15:55:03.684  3973  4014 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 15:55:03.684  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:55:03.684  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 15:55:03.684  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 15:55:03.684  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 15:55:03.684  3973  3989 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-31 15:55:03.684  3973  3989 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 15:55:03.685  3973  3992 D BtGatt.ScanManager: Starting BLE batch scan
08-31 15:55:03.685  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 15:55:03.685  3973  3992 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-31 15:55:03.686  3442  3492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 15:55:03.686  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 15:55:03.686  3442  3492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 15:55:03.686  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 15:55:03.687  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:55:03.687  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 15:55:03.688  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:55:03.688  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:55:03.688  3442  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:55:03.688  3442  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 15:55:03.688  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3027a1 removed from the list
08-31 15:55:03.688  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:55:03.688  3442  3442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 15:55:03.688  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 15:55:03.688  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:55:03.688  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:55:03.688  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c311408 removed from the list
08-31 15:55:03.689  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:55:03.689  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4069cdd added. We now have 2 listener(s)
,08-31 15:55:03.690  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 15:55:03.690  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:55:03.690  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:55:03.691  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:55:03.691  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8a5052 added. We now have 9 listener(s)
,08-31 15:55:03.691  3442  3492 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:55:03.691  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 15:55:03.693  3973  3989 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-31 15:55:03.693  3973  3989 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 15:55:03.693  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 15:55:03.697  3442  3492 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:55:03.697  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:55:03.697  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:55:03.697  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:55:03.697  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:55:03.697  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:55:03.697  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:55:03.697  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:55:03.698  3973  3989 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-31 15:55:03.698  3973  3989 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 15:55:03.699  3442  3492 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:55:03.699  3442  3492 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-31 15:55:03.699  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:55:03.699  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc5c20 added. We now have 3 listener(s)
08-31 15:55:03.700  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-31 15:55:03.701  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:55:03.701  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 15:55:03.701  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:55:03.701  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 15:55:03.701  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:55:03.702  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d529d9 added. We now have 10 listener(s)
08-31 15:55:03.702  3442  3492 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:55:03.702  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:55:03.702  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 15:55:03.702  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 15:55:03.702  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:55:03.702  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 15:55:03.704  3973  3989 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-31 15:55:03.704  3973  3989 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 15:55:03.704  3973  3992 D BtGatt.ScanManager: stopping BLe Batch
08-31 15:55:03.704   874  4031 D DhcpClient: Receive thread started
,08-31 15:55:03.705  3442  3492 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-31 15:55:03.705  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 15:55:03.708  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 15:55:03.709  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-31 15:55:03.709  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 15:55:03.709  3973  3989 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 15:55:03.709  3973  3989 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 15:55:03.709  3973  3992 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-31 15:55:03.711  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 15:55:03.711  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 15:55:03.711  3442  3492 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 15:55:03.712  3442  3492 D BluetoothAdapter: STATE_ON
,08-31 15:55:03.714  3973  4014 D BtGatt.GattService: registerClient() - UUID=7621e850-55bf-4c3f-a4ef-39db97baccfc
,08-31 15:55:03.714  3973  3989 D BtGatt.GattService: onClientRegistered() - UUID=7621e850-55bf-4c3f-a4ef-39db97baccfc, clientIf=5
08-31 15:55:03.714  3973  3989 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-31 15:55:03.714  3442  3452 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-31 15:55:03.714  3973  3989 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 15:55:03.714  3973  4013 D BtGatt.GattService: start scan with filters
,08-31 15:55:03.716  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-31 15:55:03.716  3973  3992 D BtGatt.ScanManager: handling starting scan
08-31 15:55:03.716  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 15:55:03.716  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 15:55:03.716  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 15:55:03.719  3442  3492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 15:55:03.719  3442  3442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 15:55:03.719  3442  3492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 15:55:03.720  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 15:55:03.721  3973  3989 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-31 15:55:03.721  3973  3989 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 15:55:03.721  3973  3992 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-31 15:55:03.724  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 15:55:03.724  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 15:55:03.724  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:55:03.724  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:55:03.724  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:55:03.724  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-31 15:55:03.725  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:55:03.725  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4069cdd removed from the list
08-31 15:55:03.725  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:55:03.725  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8a5052 removed from the list
08-31 15:55:03.725  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:55:03.725  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:55:03.725  3973  3989 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-31 15:55:03.725  3973  3989 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 15:55:03.725  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-31 15:55:03.725  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-31 15:55:03.725  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:55:03.725  3973  3992 D BtGatt.ScanManager: Starting BLE batch scan
08-31 15:55:03.725  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:55:03.725  3973  3992 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-31 15:55:03.726  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:55:03.726  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:55:03.726  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:55:03.726  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8a5052 not in the list
08-31 15:55:03.726  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 15:55:03.726  3442  3492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 15:55:03.726  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 15:55:03.727  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 15:55:03.727  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-31 15:55:03.727  3442  3492 D BluetoothAdapter: STATE_ON
08-31 15:55:03.728  3973  4012 D BtGatt.GattService: stopScan() - queue size =1
08-31 15:55:03.728  3973  3984 D BtGatt.GattService: unregisterClient() - clientIf=5
08-31 15:55:03.728  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 15:55:03.728  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 15:55:03.728  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 15:55:03.729  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 15:55:03.729  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 15:55:03.729  3442  3492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 15:55:03.730  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 15:55:03.730  3442  3492 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-31 15:55:03.730  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 15:55:03.730  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:55:03.731  3442  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:55:03.731  3442  3442 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:55:03.731  3442  3442 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 15:55:03.731  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:55:03.731  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:55:03.731  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:55:03.731  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d529d9 removed from the list
08-31 15:55:03.731  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:55:03.731  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:55:03.732  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:55:03.732  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:55:03.732  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cc5c20 removed from the list
08-31 15:55:03.732  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:55:03.732  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2658a95 added. We now have 2 listener(s)
,08-31 15:55:03.734  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 15:55:03.734  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:55:03.734  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:55:03.734  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:55:03.734  3973  3989 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-31 15:55:03.734  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b397aa added. We now have 9 listener(s)
08-31 15:55:03.734  3973  3989 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 15:55:03.734  3442  3492 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:55:03.734  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 15:55:03.737  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 15:55:03.739  3973  3989 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-31 15:55:03.739  3973  3989 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-31 15:55:03.739  3442  3492 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:55:03.739  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:55:03.739  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:55:03.739  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:55:03.739  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:55:03.739  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:55:03.739  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:55:03.739  3442  3492 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:55:03.741  3442  3492 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:55:03.741  3442  3492 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 15:55:03.742  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-31 15:55:03.742  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5558f38 added. We now have 3 listener(s)
08-31 15:55:03.742  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:55:03.743  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:55:03.744  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-31 15:55:03.744  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:55:03.744  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 15:55:03.744  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:55:03.744  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4613b11 added. We now have 10 listener(s)
08-31 15:55:03.744  3442  3492 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:55:03.745  3442  3492 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:55:03.745  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 15:55:03.745  3973  3989 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-31 15:55:03.745  3442  3492 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:55:03.745  3973  3989 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 15:55:03.745  3973  3992 D BtGatt.ScanManager: stopping BLe Batch
,08-31 15:55:03.745  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:55:03.745  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:55:03.745  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:55:03.745  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:55:03.745  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2658a95 removed from the list
08-31 15:55:03.745  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 15:55:03.745  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b397aa removed from the list
08-31 15:55:03.745  3442  3492 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 15:55:03.746  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:55:03.746  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 15:55:03.746  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:55:03.747  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:55:03.747  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-31 15:55:03.747  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:55:03.747  3442  3492 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b397aa not in the list
,08-31 15:55:03.747  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:55:03.747  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:55:03.748  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:55:03.748  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:55:03.748  3442  3492 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:55:03.748  3442  3492 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4613b11 removed from the list
,08-31 15:55:03.748  3442  3492 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 15:55:03.748  3442  3492 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:55:03.748  3442  3492 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:55:03.748  3442  3492 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:55:03.748  3442  3492 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5558f38 removed from the list,
08-31 15:55:03.749  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-31 15:55:03.749  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-31 15:55:03.749  3973  3989 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-31 15:55:03.749  3973  3989 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 15:55:03.749  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-31 15:55:03.749  3973  3992 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-31 15:55:03.749  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:55:03.750  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-31 15:55:03.750  3442  3492 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 15:55:03.753  3973  3989 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-31 15:55:03.754  3973  3989 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-31 15:55:03.755  3442  4032 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 393, name: My test thread name)
,08-31 15:55:03.755  3442  4032 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 393, thread name: My test thread name)
08-31 15:55:03.755  3442  4032 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 393, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-31 15:55:03.756  3442  4033 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 395, name: My test thread name)
08-31 15:55:03.756  3442  4033 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 395, thread name: My test thread name)
08-31 15:55:03.756  3442  4033 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 395, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-31 15:55:03.758  3442  3492 E com.test.thalitest.ThaliTestRunner: DiscoveryManager1 isRunning should return true
08-31 15:55:03.758  3442  3492 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
08-31 15:55:03.758  3442  3492 E com.test.thalitest.ThaliTestRunner:      but: was <false>
,08-31 15:55:03.758  3442  3492 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-31 15:55:03.758  3442  3492 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 79
08-31 15:55:03.758  3442  3492 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  1
08-31 15:55:03.758  3442  3492 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-31 15:55:03.758  3442  3492 D com.test.thalitest.ThaliTestRunner: Total duration: 23709 ms
,08-31 15:55:03.759  3442  3492 I jxcore-log: *Native tests were executed*
08-31 15:55:03.759  3442  3492 I jxcore-log: 
,08-31 15:55:03.760  3442  3492 I jxcore-log: Total number of executed tests:  80
08-31 15:55:03.760  3442  3492 I jxcore-log: 
08-31 15:55:03.760  3442  3492 I jxcore-log: Number of passed tests:  79
08-31 15:55:03.760  3442  3492 I jxcore-log: 
08-31 15:55:03.760  3442  3492 I jxcore-log: Number of failed tests:  1
08-31 15:55:03.760  3442  3492 I jxcore-log: 
08-31 15:55:03.760  3442  3492 I jxcore-log: Number of ignored tests:  0
08-31 15:55:03.760  3442  3492 I jxcore-log: 
,08-31 15:55:03.760  3442  3492 I jxcore-log: Total duration:  23709
08-31 15:55:03.760  3442  3492 I jxcore-log: 
08-31 15:55:03.761  3442  3492 I jxcore-log: Failed to execute UT.
08-31 15:55:03.761  3442  3492 I jxcore-log: 
08-31 15:55:03.761  3442  3492 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-31 15:55:03.761  3442  3492 I jxcore-log: 
,08-31 15:55:03.765  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:55:03.765  3442  3492 I jxcore-log: 
08-31 15:55:03.767  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:55:03.767  3442  3492 I jxcore-log: 
08-31 15:55:03.769  3442  3442 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-31 15:55:03.769  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:55:03.769  3442  3492 I jxcore-log: 
08-31 15:55:03.770  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:55:03.770  3442  3492 I jxcore-log: 
08-31 15:55:03.771  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 15:55:03.771  3442  3492 I jxcore-log: 
08-31 15:55:03.772  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 15:55:03.772  3442  3492 I jxcore-log: 
08-31 15:55:03.774  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:55:03.774  3442  3492 I jxcore-log: 
08-31 15:55:03.776  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:55:03.776  3442  3492 I jxcore-log: 
08-31 15:55:03.777  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 15:55:03.777  3442  3492 I jxcore-log: 
08-31 15:55:03.778  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 15:55:03.778  3442  3492 I jxcore-log: 
08-31 15:55:03.779  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 15:55:03.779  3442  3492 I jxcore-log: 
,08-31 15:55:03.780  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 15:55:03.780  3442  3492 I jxcore-log: 
,08-31 15:55:03.781  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 15:55:03.781  3442  3492 I jxcore-log: 
,08-31 15:55:03.782   874  1305 E native  : do suspend false
08-31 15:55:03.782  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:55:03.782  3442  3492 I jxcore-log: 
08-31 15:55:03.783  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:55:03.783  3442  3492 I jxcore-log: 
08-31 15:55:03.783  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 15:55:03.783  3442  3492 I jxcore-log: 
08-31 15:55:03.784  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 15:55:03.784  3442  3492 I jxcore-log: 
08-31 15:55:03.784  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:55:03.784  3442  3492 I jxcore-log: 
,08-31 15:55:03.785  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:55:03.785  3442  3492 I jxcore-log: 
,08-31 15:55:03.786  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 15:55:03.786  3442  3492 I jxcore-log: 
08-31 15:55:03.786  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 15:55:03.786  3442  3492 I jxcore-log: 
08-31 15:55:03.787  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:55:03.787  3442  3492 I jxcore-log: 
,08-31 15:55:03.788  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:55:03.788  3442  3492 I jxcore-log: 
,08-31 15:55:03.789  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 15:55:03.789  3442  3492 I jxcore-log: 
08-31 15:55:03.790  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 15:55:03.790  3442  3492 I jxcore-log: 
08-31 15:55:03.791   874  3626 D DhcpClient: Broadcasting DHCPDISCOVER
08-31 15:55:03.791  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 15:55:03.791  3442  3492 I jxcore-log: 
,08-31 15:55:03.792  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 15:55:03.792  3442  3492 I jxcore-log: 
,08-31 15:55:03.793  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 15:55:03.793  3442  3492 I jxcore-log: 
08-31 15:55:03.793  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 15:55:03.793  3442  3492 I jxcore-log: 
08-31 15:55:03.794  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 15:55:03.794  3442  3492 I jxcore-log: 
,08-31 15:55:03.795  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 15:55:03.795  3442  3492 I jxcore-log: 
,08-31 15:55:03.796  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 15:55:03.796  3442  3492 I jxcore-log: 
,08-31 15:55:03.845   874  4031 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172780, domain null
,08-31 15:55:03.845   874  3626 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172780 seconds
08-31 15:55:03.846   874  3626 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-31 15:55:03.861   874  4031 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-31 15:55:03.861   874  3626 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-31 15:55:03.862   373   873 D CommandListener: Setting iface cfg
,08-31 15:55:03.868   874  3626 D DhcpClient: Scheduling renewal in 86399s
,08-31 15:55:03.871   874  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-31 15:55:03.883   874  1305 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-31 15:55:03.884   874  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-31 15:55:03.884   874  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-31 15:55:03.885   874  1307 D ConnectivityService: Adding iface wlan0 to network 101
,08-31 15:55:03.895   874  1305 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 15:55:03.927   874  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-31 15:55:03.927   874  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-31 15:55:03.928   874  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-31 15:55:03.929   874  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-31 15:55:03.930   874  1307 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-31 15:55:03.937   874  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-31 15:55:03.941   874  1307 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-31 15:55:03.941   874  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-31 15:55:03.941   874  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-31 15:55:03.941   874  1305 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-31 15:55:03.941   874  1307 D ConnectivityService:    accepting network in place of null
,08-31 15:55:03.942   874  1305 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-31 15:55:03.943   874  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-31 15:55:03.952   874  4030 D NetlinkSocketObserver: NeighborEvent{elapsedMs=138793, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-31 15:55:03.964   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 15:55:03.993   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-31 15:55:03.997   874  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-31 15:55:03.997   874  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:55:04.000   874  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-31 15:55:04.004   874   891 D Tethering: MasterInitialState.processMessage what=3
08-31 15:55:04.014  3442  3442 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:55:04.014  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:55:04.014  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:55:04.014  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:55:04.014  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:55:04.014  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:55:04.014  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:55:04.014  3442  3442 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:55:04.016  3442  3442 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:55:04.018  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:55:04.018  3442  3492 I jxcore-log: 
,08-31 15:55:04.019   874  4029 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.174,2a00:1450:4001:805::200e
08-31 15:55:04.025  1736  1736 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-31 15:55:04.028  1736  1736 D SystemUpdateService: onCreate
,08-31 15:55:04.032  1736  1736 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-31 15:55:04.048  1736  4045 I SystemUpdateService: active receiver: enabled
,08-31 15:55:04.051  1736  1736 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 15:55:04.056  1736  3655 I iu.UploadsManager: num queued entries: 0
,08-31 15:55:04.056  1736  3655 I iu.UploadsManager: num updated entries: 0
08-31 15:55:04.057  1736  3655 I iu.SyncManager: NEXT; no task
,08-31 15:55:04.062  1736  1736 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-31 15:55:04.063  1736  1736 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-31 15:55:04.066  3659  3659 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:55:04.071  3659  3659 D SprintDMHelper: simOperator: 
,08-31 15:55:04.071  3659  3659 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-31 15:55:04.083  1736  4048 I MDM     : [174] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-31 15:55:04.083  1736  4048 W BaseAppContext: Using Auth Proxy for data requests.
,08-31 15:55:04.090  1736  4048 V GoogleAuthProtoRequest: [174] a.<init>: mAccountName set to: thalitester@gmail.com
,08-31 15:55:04.099   874  4029 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 13:55:03 GMT], X-Android-Received-Millis=[1472651704098], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472651704065]}
,08-31 15:55:04.102   874  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-31 15:55:04.102   874  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-31 15:55:04.102   874  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-31 15:55:04.102  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:55:04.104   874  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-31 15:55:04.105  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 15:55:04.109  1736  4045 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-31 15:55:04.122  3442  3442 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 15:55:04.123  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 15:55:04.123  3442  3492 I jxcore-log: 
,08-31 15:55:04.145   874  1305 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 3, 5 -> obsolete
,08-31 15:55:04.151  1515  2246 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-31 15:55:04.151  1515  2246 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-31 15:55:04.151  1515  2246 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-31 15:55:04.151  1515  2246 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 15:55:04.187  3442  3442 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 15:55:04.188  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,08-31 15:55:04.188  3442  3492 I jxcore-log: 
08-31 15:55:04.190  1736  4045 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-31 15:55:04.190  1736  4045 I SystemUpdateService: now status is 0 (complete)
,08-31 15:55:04.190  1736  4045 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip,
,08-31 15:55:04.190  1736  4045 I SystemUpdateService: file has been verified
,08-31 15:55:04.190  1736  4045 I SystemUpdateService: OTA package size = 12249756
,08-31 15:55:04.191  1736  4048 E MDM     : [174] SitrepService.a: Error sending sitrep.
,08-31 15:55:04.205  1736  4045 I SystemUpdateService: showing system update notification
,08-31 15:55:04.218  1736  1736 D SystemUpdateService: onDestroy
,08-31 15:55:04.231  3442  3442 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 15:55:04.232  3442  3492 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 15:55:04.232  3442  3492 I jxcore-log: 
,08-31 15:55:04.259  2376  4051 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-31 15:55:04.307  1515  4062 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-31 15:55:04.309  1515  4062 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-31 15:55:04.443  4034  4034 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-31 15:55:04.448  4034  4034 D AndroidRuntime: CheckJNI is OFF
,08-31 15:55:04.492  4034  4034 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-31 15:55:04.540  4034  4034 I Radio-JNI: register_android_hardware_Radio DONE
,08-31 15:55:04.564  4034  4034 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 15:55:04.574   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-31 15:55:04.574   874   887 I ActivityManager: Killing 3442:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-31 15:55:04.652   874   897 W PackageSettings: Skipping PackageSetting{4a65050 com.example.hello/10273} due to missing metadata
,08-31 15:55:04.664   874   885 I WindowState: WIN DEATH: Window{d8898eb u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-31 15:55:04.665   874  1306 D WifiService: Client connection lost with reason: 4
08-31 15:55:04.665   874   884 D GraphicsStats: Buffer count: 2
,08-31 15:55:04.694   874   897 I art     : Starting a blocking GC Explicit
,08-31 15:55:04.695   874   887 W ActivityManager: Force removing ActivityRecord{466fad0 u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
,08-31 15:55:04.714   874  1484 W ActivityManager: Spurious death for ProcessRecord{63075e0 0:com.test.thalitest/u0a0}, curProc for 3442: null
,08-31 15:55:04.741   874  1976 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3442 uid 10000
,08-31 15:55:04.743  1515  4062 W Uploader:  no longer exists, so no auth token.
,08-31 15:55:04.747  1866  1866 I Keyboard.Facilitator: onFinishInput()
,08-31 15:55:04.803   874   897 I art     : Explicit concurrent mark sweep GC freed 19968(1254KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 1.439ms total 109.140ms
,08-31 15:55:04.808  2031  4080 I MicroRecognitionRnrImpl: Starting detection.
,08-31 15:55:04.809  2031  4081 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@274f4d2
,08-31 15:55:04.813   377  4083 I AudioFlinger: AudioFlinger's thread 0xb1d00000 ready to run
,08-31 15:55:04.814   377  1276 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,08-31 15:55:04.816  2031  4081 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@274f4d2
,08-31 15:55:04.826   377  4083 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,08-31 15:55:04.826   377  4083 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
08-31 15:55:04.826   377  4083 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,08-31 15:55:04.832   377  4083 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,08-31 15:55:04.833   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-31 15:55:04.836  4034  4034 I art     : System.exit called, status: 0
,08-31 15:55:04.836  4034  4034 I AndroidRuntime: VM exiting with result code 0.
,08-31 15:55:04.849   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-31 15:55:04.870  2107  2267 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 15:55:04.870  1866  1866 I Keyboard.Facilitator: resetDictionaries() : en_US
08-31 15:55:04.871  3973  3973 D BluetoothMapAppObserver: onReceive
08-31 15:55:04.871  3973  3973 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-31 15:55:04.874  3322  3322 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-31 15:55:04.877  1866  4087 I Keyboard.Facilitator.DecoderInitializer: run()
,08-31 15:55:04.880   874  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 15:55:04.888  1866  4087 I Decoder : createOrResetDecoder
,08-31 15:55:04.906  2031  2031 I HotwordWorkerImpl: onReady
,08-31 15:55:04.911  1951  1951 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-31 15:55:04.917   874  1968 I ActivityManager: Start proc 4090:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-31 15:55:04.932  1515  1515 I ConfigService: onCreate
,08-31 15:55:04.950  1866  4087 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-31 15:55:04.965   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-31 15:55:04.974  4090  4090 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-31 15:55:04.984  1866  4087 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-31 15:55:04.994  1866  4087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-31 15:55:04.995  1866  4087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-31 15:55:04.996   874  1307 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-31 15:55:05.010  1966  2055 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-31 15:55:05.010   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-31 15:55:05.010  1866  4087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-31 15:55:05.010  1866  4087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-31 15:55:05.010   874   886 E PackageManager: Failed to write settings, restoring backup
08-31 15:55:05.010   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-31 15:55:05.010   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-31 15:55:05.010   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-31 15:55:05.010   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-31 15:55:05.010   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-31 15:55:05.010   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:55:05.010   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:55:05.010   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 15:55:05.012  1866  4087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-31 15:55:05.012  1866  4087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-31 15:55:05.013  1866  4087 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-31 15:55:05.013  1866  4087 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-31 15:55:05.013  1866  4087 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-31 15:55:05.013  1866  4087 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-31 15:55:05.013  1866  4087 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-31 15:55:05.014  1866  4087 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-31 15:55:05.017   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-31 15:55:05.017   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-31 15:55:05.017   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 15:55:05.017   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 15:55:05.017   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 15:55:05.017   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 15:55:05.017   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 15:55:05.017   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 15:55:05.017   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-31 15:55:05.017   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-31 15:55:05.017   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-31 15:55:05.017   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 15:55:05.017   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 15:55:05.017   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:55:05.017   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 15:55:05.017   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-31 15:55:05.017   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 15:55:05.017   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 15:55:05.017   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 15:55:05.017   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 15:55:05.017   874   887 E DropBoxManagerService: 	... 13 more
,08-31 15:55:05.026   874  1924 I ActivityManager: Start proc 4106:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-31 15:55:05.026  1966  2055 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-31 15:55:05.026  1966  2055 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1966
08-31 15:55:05.026  1966  2055 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 15:55:05.026  1966  2055 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 15:55:05.026  1966  2055 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 15:55:05.026  1966  2055 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 15:55:05.026  1966  2055 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 15:55:05.026  1966  2055 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-31 15:55:05.026  1966  2055 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-31 15:55:05.026  1966  2055 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-31 15:55:05.026  1966  2055 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 15:55:05.026  1966  2055 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 15:55:05.026  1966  2055 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:55:05.026  1966  2055 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 15:55:05.029   874  1373 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-31 15:55:05.032  2031  2043 W SearchService: Abort, client detached.
,08-31 15:55:05.032   874  4112 E DropBoxManagerService: Can't write: system_app_crash
08-31 15:55:05.032   874  4112 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
08-31 15:55:05.032   874  4112 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 15:55:05.032   874  4112 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 15:55:05.032   874  4112 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 15:55:05.032   874  4112 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 15:55:05.032   874  4112 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 15:55:05.032   874  4112 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 15:55:05.032   874  4112 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 15:55:05.032   874  4112 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 15:55:05.032   874  4112 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 15:55:05.032   874  4112 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 15:55:05.032   874  4112 E DropBoxManagerService: 	... 5 more
,08-31 15:55:05.036  2031  2031 I HotwordDetector: Closing mic
08-31 15:55:05.036  2031  2321 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@274f4d2
08-31 15:55:05.036  2031  4081 E AudioRecord-JNI: Error -4 during AudioRecord native read
,08-31 15:55:05.045   874  4120 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-31 15:55:05.054  2031  4121 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,08-31 15:55:05.068  4090  4090 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-31 15:55:05.073   874  4120 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 15:55:05.073   874  4120 I Adreno  : Build Date                       : 10/20/15
08-31 15:55:05.073   874  4120 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 15:55:05.073   874  4120 I Adreno  : Local Branch                     : M14
08-31 15:55:05.073   874  4120 I Adreno  : Remote Branch                    : 
08-31 15:55:05.073   874  4120 I Adreno  : Remote Branch                    : 
08-31 15:55:05.073   874  4120 I Adreno  : Reconstruct Branch               : 
,08-31 15:55:05.078   874  4120 I OpenGLRenderer: Initialized EGL, version 1.4
08-31 15:55:05.092   377  4083 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-31 15:55:05.093   377  4083 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-31 15:55:05.097   377  1276 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-31 15:55:05.109  2031  2324 I MicroRecognitionRnrImpl: Stopping hotword detection.
,08-31 15:55:05.111  2031  4080 I MicroRecognitionRnrImpl: Detection finished
,08-31 15:55:05.121   874  1980 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-31 15:55:05.141   874  1964 I ActivityManager: Start proc 4128:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-31 15:55:05.144  1966  1966 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@242a92c new=com.google.android.velvet.VelvetApplication@242a92c
,08-31 15:55:05.197  1966  1966 I GEL     : handleIntent(Intent { act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL })
,08-31 15:55:05.251  1515  4056 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-31 15:55:05.252  1515  4056 E ClearcutLoggerIntentService: disk I/O error (code 3850)
08-31 15:55:05.252  1515  4056 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 15:55:05.252  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-31 15:55:05.252  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-31 15:55:05.252  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-31 15:55:05.252  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-31 15:55:05.252  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-31 15:55:05.252  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-31 15:55:05.252  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-31 15:55:05.252  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-31 15:55:05.252  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-31 15:55:05.252  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-31 15:55:05.252  1515  4056 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 15:55:05.252  1515  4056 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 15:55:05.252  1515  4056 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
08-31 15:55:05.253   874   892 I ActivityManager: Displayed com.google.android.googlequicksearchbox/com.google.android.launcher.GEL: +127ms
08-31 15:55:05.253  1515  4056 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-31 15:55:05.253  1515  4056 E ClearcutLoggerIntentService: disk I/O error (code 3850)
08-31 15:55:05.253  1515  4056 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 15:55:05.253  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-31 15:55:05.253  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-31 15:55:05.253  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-31 15:55:05.253  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-31 15:55:05.253  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-31 15:55:05.253  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-31 15:55:05.253  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-31 15:55:05.253  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-31 15:55:05.253  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-31 15:55:05.253  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-31 15:55:05.253  1515  4056 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 15:55:05.253  1515  4056 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 15:55:05.253  1515  4056 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
08-31 15:55:05.254  1515  4056 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-31 15:55:05.255  1515  4056 E ClearcutLoggerIntentService: disk I/O error (code 3850)
08-31 15:55:05.255  1515  4056 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 15:55:05.255  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-31 15:55:05.255  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-31 15:55:05.255  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-31 15:55:05.255  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-31 15:55:05.255  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-31 15:55:05.255  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-31 15:55:05.255  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-31 15:55:05.255  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-31 15:55:05.255  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-31 15:55:05.255  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-31 15:55:05.255  1515  4056 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 15:55:05.255  1515  4056 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 15:55:05.255  1515  4056 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
08-31 15:55:05.257  1515  4056 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-31 15:55:05.261  1515  4056 E ClearcutLoggerIntentService: disk I/O error (code 3850)
08-31 15:55:05.261  1515  4056 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 15:55:05.261  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-31 15:55:05.261  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-31 15:55:05.261  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-31 15:55:05.261  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-31 15:55:05.261  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-31 15:55:05.261  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-31 15:55:05.261  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-31 15:55:05.261  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-31 15:55:05.261  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-31 15:55:05.261  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-31 15:55:05.261  1515  4056 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 15:55:05.261  1515  4056 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 15:55:05.261  1515  4056 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
08-31 15:55:05.263  1515  4056 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-31 15:55:05.263  1515  4056 E ClearcutLoggerIntentService: disk I/O error (code 3850)
08-31 15:55:05.263  1515  4056 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 15:55:05.263  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-31 15:55:05.263  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-31 15:55:05.263  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-31 15:55:05.263  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-31 15:55:05.263  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-31 15:55:05.263  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-31 15:55:05.263  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-31 15:55:05.263  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-31 15:55:05.263  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-31 15:55:05.263  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-31 15:55:05.263  1515  4056 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 15:55:05.263  1515  4056 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 15:55:05.263  1515  4056 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
08-31 15:55:05.264  1515  4056 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-31 15:55:05.265  1515  4056 E ClearcutLoggerIntentService: disk I/O error (code 3850)
08-31 15:55:05.265  1515  4056 E ClearcutLoggerIntentService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 15:55:05.265  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-31 15:55:05.265  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-31 15:55:05.265  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-31 15:55:05.265  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-31 15:55:05.265  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-31 15:55:05.265  1515  4056 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-31 15:55:05.265  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:103)
08-31 15:55:05.265  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-31 15:55:05.265  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-31 15:55:05.265  1515  4056 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-31 15:55:05.265  1515  4056 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 15:55:05.265  1515  4056 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 15:55:05.265  1515  4056 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
08-31 15:55:05.266  4090  4143 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-31 15:55:05.277  4128  4128 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-31 15:55:05.295  1515  1515 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-31 15:55:05.295  1515  1515 D AndroidRuntime: Shutting down VM
08-31 15:55:05.297  1515  1515 E AndroidRuntime: FATAL EXCEPTION: main
08-31 15:55:05.297  1515  1515 E AndroidRuntime: Process: com.google.process.gapps, PID: 1515
08-31 15:55:05.297  1515  1515 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 15:55:05.297  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-31 15:55:05.297  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-31 15:55:05.297  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-31 15:55:05.297  1515  1515 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:55:05.297  1515  1515 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:55:05.297  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 15:55:05.297  1515  1515 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:55:05.297  1515  1515 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 15:55:05.297  1515  1515 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 15:55:05.297  1515  1515 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 15:55:05.297  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 15:55:05.297  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 15:55:05.297  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 15:55:05.297  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 15:55:05.297  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-31 15:55:05.297  1515  1515 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-31 15:55:05.297  1515  1515 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-31 15:55:05.297  1515  1515 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-31 15:55:05.297  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-31 15:55:05.297  1515  1515 E AndroidRuntime: 	... 8 more
08-31 15:55:05.301   874  4148 E DropBoxManagerService: Can't write: system_app_crash
08-31 15:55:05.301   874  4148 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-31 15:55:05.301   874  4148 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 15:55:05.301   874  4148 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 15:55:05.301   874  4148 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 15:55:05.301   874  4148 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 15:55:05.301   874  4148 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 15:55:05.301   874  4148 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 15:55:05.301   874  4148 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 15:55:05.301   874  4148 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 15:55:05.301   874  4148 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 15:55:05.301   874  4148 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 15:55:05.301   874  4148 E DropBoxManagerService: 	... 5 more
08-31 15:55:05.313  4090  4105 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-31 15:55:05.313  4090  4105 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 15:55:05.313  4090  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 15:55:05.313  4090  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 15:55:05.313  4090  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 15:55:05.313  4090  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 15:55:05.313  4090  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 15:55:05.313  4090  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 15:55:05.313  4090  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 15:55:05.313  4090  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 15:55:05.313  4090  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 15:55:05.313  4090  4105 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 15:55:05.313  4090  4105 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 15:55:05.313  4090  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 15:55:05.313  4090  4105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 15:55:05.313  4090  4105 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-31 15:55:05.313  4090  4105 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-31 15:55:05.313  4090  4105 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-31 15:55:05.313  4090  4105 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-31 15:55:05.313  4090  4105 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:55:05.313  4090  4105 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:55:05.313  4090  4105 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 15:55:05.313  4090  4105 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-31 15:55:05.313  4090  4105 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 15:55:05.313  4090  4105 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 15:55:05.313  4090  4105 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 15:55:05.313  4090  4105 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 15:55:05.313  4090  4105 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 15:55:05.313  4090  4105 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 15:55:05.313  4090  4105 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 15:55:05.313  4090  4105 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 15:55:05.313  4090  4105 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 15:55:05.313  4090  4105 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 15:55:05.313  4090  4105 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 15:55:05.313  4090  4105 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 15:55:05.313  4090  4105 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 15:55:05.313  4090  4105 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 15:55:05.313  4090  4105 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-31 15:55:05.313  4090  4105 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-31 15:55:05.313  4090  4105 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-31 15:55:05.313  4090  4105 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-31 15:55:05.313  4090  4105 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:55:05.313  4090  4105 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:55:05.313  4090  4105 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 15:55:05.372  1736  4150 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-31 15:55:05.373  1736  4150 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-31 15:55:05.411  2031  2414 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/jar_store.db'.
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.k.aNy(JarStoreDatabase.java:652)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.o.oz(JarStoreDatabase.java:413)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.j.ov(JarStoreDatabase.java:565)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.g.os(JarStore.java:162)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.x.gZ(VelourReleaseState.java:388)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.x.pv(VelourReleaseState.java:140)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at com.google.android.apps.gsa.velour.x.aNH(VelourReleaseState.java:257)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at com.google.android.apps.gsa.search.core.google.ad.d(SearchUrlHelper.java:1536)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at com.google.android.apps.gsa.search.core.google.ad.c(SearchUrlHelper.java:1235)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at com.google.android.apps.gsa.search.core.google.ad.a(SearchUrlHelper.java:1417)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at com.google.android.apps.gsa.search.core.google.ad.a(SearchUrlHelper.java:1436)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at com.google.android.apps.gsa.search.core.google.ad.a(SearchUrlHelper.java:1362)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at com.google.android.apps.gsa.search.core.google.ad.a(SearchUrlHelper.java:1173)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at com.google.android.apps.gsa.search.core.google.ad.aa(SearchUrlHelper.java:898)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at com.google.android.search.core.google.a.b.b(GwsSuggestionFetcher.java:176)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at com.google.android.search.core.google.a.b.a(GwsSuggestionFetcher.java:113)
08-31 15:55:05.411  2031  2414 E ,SQLiteDatabase: 	at com.google.android.c.a.a.a.e.run(RefreshZeroPrefixSuggestionsTask.java:65)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-31 15:55:05.411  2031  2414 E SQLiteDatabase: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: Couldn't open jar_store.db for writing (will try read-only):
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.k.aNy(JarStoreDatabase.java:652)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.o.oz(JarStoreDatabase.java:413)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.j.ov(JarStoreDatabase.java:565)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.g.os(JarStore.java:162)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.x.gZ(VelourReleaseState.java:388)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.x.pv(VelourReleaseState.java:140)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.velour.x.aNH(VelourReleaseState.java:257)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.search.core.google.ad.d(SearchUrlHelper.java:1536)
08-31 15:55:05,.411  2031  2414 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.search.core.google.ad.c(SearchUrlHelper.java:1235)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.search.core.google.ad.a(SearchUrlHelper.java:1417)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.search.core.google.ad.a(SearchUrlHelper.java:1436)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.search.core.google.ad.a(SearchUrlHelper.java:1362)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.search.core.google.ad.a(SearchUrlHelper.java:1173)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.search.core.google.ad.aa(SearchUrlHelper.java:898)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at com.google.android.search.core.google.a.b.b(GwsSuggestionFetcher.java:176)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at com.google.android.search.core.google.a.b.a(GwsSuggestionFetcher.java:113)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at com.google.android.c.a.a.a.e.run(RefreshZeroPrefixSuggestionsTask.java:65)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-31 15:55:05.411  2031  2414 E SQLiteOpenHelper: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-31 15:55:05.416  4090  4105 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-31 15:55:05.419  2031  2414 W SQLiteOpenHelper: Opened jar_store.db in read-only mode
08-31 15:55:05.423   282   282 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
08-31 15:55:05.423   282   282 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
08-31 15:55:05.423   282   282 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
08-31 15:55:05.423   282   282 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
08-31 15:55:05.423   282   282 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
08-31 15:55:05.423   282   282 E qdoverlay: MdpCtrl close error in unset
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:55:05.424  4090  4143 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 15:55:05.425  4090  4143 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-31 15:55:05.425  4090  4143 E AndroidRuntime: Process: android.process.acore, PID: 4090
08-31 15:55:05.425  4090  4143 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 15:55:05.425  4090  4143 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 15:55:05.425  4090  4143 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 15:55:05.425  4090  4143 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 15:55:05.425  4090  4143 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 15:55:05.425  4090  4143 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 15:55:05.425  4090  4143 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 15:55:05.425  4090  4143 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 15:55:05.425  4090  4143 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 15:55:05.425  4090  4143 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 15:55:05.425  4090  4143 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 15:55:05.425  4090  4143 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 15:55:05.425  4090  4143 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 15:55:05.425  4090  4143 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 15:55:05.425  4090  4143 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-31 15:55:05.425  4090  4143 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-31 15:55:05.425  4090  4143 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 15:55:05.425  4090  4143 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 15:55:05.425  4090  4143 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 15:55:05.425  4090  4143 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 15:55:05.425  4090  4143 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 15:55:05.425  4090  4143 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:55:05.425  4090  4143 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 15:55:05.425  4090  4143 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 15:55:05.427  4090  4105 I Process : Sending signal. PID: 4090 SIG: 9
08-31 15:55:05.429   874  4151 E DropBoxManagerService: Can't write: system_app_crash
08-31 15:55:05.429   874  4151 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-31 15:55:05.429   874  4151 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 15:55:05.429   874  4151 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 15:55:05.429   874  4151 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 15:55:05.429   874  4151 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 15:55:05.429   874  4151 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 15:55:05.429   874  4151 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 15:55:05.429   874  4151 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 15:55:05.429   874  4151 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 15:55:05.429   874  4151 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 15:55:05.429   874  4151 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 15:55:05.429   874  4151 E DropBoxManagerService: 	... 5 more
,08-31 15:55:05.454   874  1924 I ActivityManager: Process android.process.acore (pid 4090) has died
08-31 15:55:05.454   874  1924 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms

```
