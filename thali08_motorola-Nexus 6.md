#### Test 80598852be6cebf_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
08-09 14:33:13.605   973   973 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
08-09 14:33:13.606   973   973 I kickstart: STATUS: Wrote to /sys/power/wake_lock
08-09 14:33:13.634   973   973 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
08-09 14:33:13.635   973   973 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
08-09 14:33:14.536  1515  1515 I ConfigService: onDestroy
08-09 14:33:14.633   973   973 I kickstart: STATUS: Received file 'm9kefs1'
08-09 14:33:14.634   973   973 I kickstart: STATUS: 950272 bytes transferred in 0.997096 seconds
08-09 14:33:14.634   973   973 I kickstart: STATUS: Successfully downloaded files from target 
08-09 14:33:14.634   973   973 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
08-09 14:33:14.637   973   973 I kickstart: STATUS: Sahara protocol completed
,08-09 14:33:16.056  3313  3313 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-09 14:33:16.061  3313  3313 D AndroidRuntime: CheckJNI is OFF
08-09 14:33:16.102  3313  3313 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-09 14:33:16.153  3313  3313 I Radio-JNI: register_android_hardware_Radio DONE
08-09 14:33:16.175  3313  3313 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-09 14:33:16.179   870  1757 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-09 14:33:16.210  1801  1966 W SearchService: Abort, client detached.
08-09 14:33:16.222  1801  1801 I HotwordDetector: Closing mic
08-09 14:33:16.223  3313  3313 D AndroidRuntime: Shutting down VM
08-09 14:33:16.223  1801  2098 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@5314889
08-09 14:33:16.223  1801  2119 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-09 14:33:16.240   870   881 I ActivityManager: Start proc 3322:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-09 14:33:16.256  1801  1801 W ErrorReporter: reportError [type: 29, code: 917507]: null
08-09 14:33:16.281   375  2121 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-09 14:33:16.283   375  2121 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-09 14:33:16.288   375  1284 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-09 14:33:16.290  1801  2117 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-09 14:33:16.292  1801  2118 I MicroRecognitionRnrImpl: Detection finished
08-09 14:33:16.311  3322  3322 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-09 14:33:16.340  3322  3322 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-09 14:33:16.349  3322  3322 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3477-3480)
08-09 14:33:16.350  3322  3322 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-09 14:33:16.365  3322  3322 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e09b4d5}
08-09 14:33:16.365  3322  3322 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-09 14:33:16.366  3322  3322 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-09 14:33:16.372  3322  3322 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-09 14:33:16.373  3322  3322 E SysUtils: ApplicationContext is null in ApplicationStatus
08-09 14:33:16.394  3322  3337 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
08-09 14:33:16.400  3322  3322 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-09 14:33:16.411  3322  3322 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-09 14:33:16.411  3322  3322 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-09 14:33:16.411  3322  3322 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-09 14:33:16.411  3322  3322 I Adreno  : Build Date                       : 10/20/15
08-09 14:33:16.411  3322  3322 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-09 14:33:16.411  3322  3322 I Adreno  : Local Branch                     : M14
08-09 14:33:16.411  3322  3322 I Adreno  : Remote Branch                    : 
08-09 14:33:16.411  3322  3322 I Adreno  : Remote Branch                    : 
08-09 14:33:16.411  3322  3322 I Adreno  : Reconstruct Branch               : 
,08-09 14:33:16.506   870   887 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@374ee26:true
,08-09 14:33:16.536  3322  3322 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-09 14:33:16.549  3322  3322 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-09 14:33:16.613  3322  3359 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-09 14:33:16.624  3322  3346 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-09 14:33:16.681  3322  3359 I OpenGLRenderer: Initialized EGL, version 1.4
,08-09 14:33:16.762  1660  1660 I Keyboard.Facilitator: onFinishInput()
,08-09 14:33:16.762   870   888 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +536ms
,08-09 14:33:16.834  3322  3322 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3322
,08-09 14:33:16.927  3322  3322 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-09 14:33:17.049   870   881 I ActivityManager: Killing 2691:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,08-09 14:33:17.099   870   881 I ActivityManager: Killing 2979:com.qualcomm.telephony/1001 (adj 15): empty #18
,08-09 14:33:17.231  3322  3362 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1681917648
,08-09 14:33:17.238  3322  3362 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-09 14:33:17.238  3322  3362 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-09 14:33:17.238  3322  3362 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-09 14:33:17.238  3322  3362 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-09 14:33:17.238  3322  3362 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-09 14:33:17.238  3322  3362 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1862f49 added. We now have 1 listener(s)
,08-09 14:33:17.243  3322  3362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-09 14:33:17.245  3322  3362 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-09 14:33:17.245  3322  3362 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-09 14:33:17.246  3322  3362 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-09 14:33:17.250  3322  3362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-09 14:33:17.250  3322  3362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-09 14:33:17.250  3322  3362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-09 14:33:17.250  3322  3362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-09 14:33:17.250  3322  3362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-09 14:33:17.250  3322  3362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-09 14:33:17.250  3322  3362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-09 14:33:17.250  3322  3362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-09 14:33:17.250  3322  3362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-09 14:33:17.250  3322  3362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-09 14:33:17.250  3322  3362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-09 14:33:17.250  3322  3362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-09 14:33:17.250  3322  3362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-09 14:33:17.250  3322  3362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-09 14:33:17.250  3322  3362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c42327c added. We now have 1 listener(s)
08-09 14:33:17.250  3322  3362 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 14:33:17.255   870  1313 D WifiService: New client listening to asynchronous messages
,08-09 14:33:17.256  3322  3362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-09 14:33:17.256  3322  3362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-09 14:33:17.258  3322  3362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-09 14:33:17.258  3322  3362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-09 14:33:17.258  3322  3362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-09 14:33:17.260  3322  3362 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 14:33:17.261  3322  3362 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-09 14:33:17.263  3322  3362 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 14:33:17.263  3322  3362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 14:33:17.263  3322  3362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:17.263  3322  3362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 14:33:17.263  3322  3362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:17.263  3322  3362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:17.263  3322  3362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:17.263  3322  3362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:17.263  3322  3362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 14:33:17.263  3322  3362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-09 14:33:17.263  3322  3362 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 14:33:17.264  3322  3362 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-09 14:33:17.370  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:17.373  3322  3322 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-09 14:33:17.991  3322  3371 W jxcore-log: Initializing JXcore engine
,08-09 14:33:17.992  3322  3371 W jxcore-log: JXcore engine is ready
,08-09 14:33:18.058  3371  3371 W Thread-285: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8939 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-09 14:33:18.061  3371  3371 W Thread-285: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[13280]" dev="sockfs" ino=13280 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-09 14:33:18.061  3371  3371 W Thread-285: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-09 14:33:18.061  3371  3371 W Thread-285: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[23814]" dev="sockfs" ino=23814 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-09 14:33:18.076  3322  3371 W jxcore-log: Starting JXcore engine
,08-09 14:33:18.159  3322  3371 W jxcore-log: Platform android
08-09 14:33:18.159  3322  3371 W jxcore-log: 
,08-09 14:33:18.159  3322  3371 W jxcore-log: Process ARCH arm
08-09 14:33:18.159  3322  3371 W jxcore-log: 
,08-09 14:33:18.375  3322  3371 I jxcore-log: JXcore Cordova bridge is ready!
08-09 14:33:18.375  3322  3371 I jxcore-log: 
,08-09 14:33:18.376  3322  3371 W jxcore-log: JXcore engine is started
,08-09 14:33:18.389  3322  3362 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-09 14:33:18.393  3322  3322 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-09 14:33:22.055  1801  1816 W art     : Suspending all threads took: 6.676ms
,08-09 14:33:24.031   870   883 I ActivityManager: Waited long enough for: ServiceRecord{a44978 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,08-09 14:33:28.470  3322  3371 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-09 14:33:28.470  3322  3371 I jxcore-log: 
,08-09 14:33:28.473  3322  3371 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-09 14:33:28.473  3322  3371 I jxcore-log: 
,08-09 14:33:28.478  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:28.478  3322  3371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 14:33:28.478  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:28.478  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 14:33:28.478  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:28.478  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:28.478  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:28.478  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:28.478  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 14:33:28.479  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 14:33:28.479  3322  3371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 14:33:28.481  3322  3371 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-09 14:33:28.481  3322  3371 I jxcore-log: 
,08-09 14:33:28.483  3322  3371 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-09 14:33:28.483  3322  3371 I jxcore-log: 
,08-09 14:33:28.812  3322  3371 D ExecuteNativeTests: Running unit tests
,08-09 14:33:28.870  3322  3371 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 14:33:28.871  3322  3371 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f11aa1 added. We now have 2 listener(s)
,08-09 14:33:28.872  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-09 14:33:28.872  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 14:33:28.872  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-09 14:33:28.872  3322  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 14:33:28.872  3322  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 added. We now have 2 listener(s)
08-09 14:33:28.872  3322  3371 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 14:33:28.873  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 14:33:28.875  3322  3371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 14:33:28.882  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:28.882  3322  3371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 14:33:28.882  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:28.882  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 14:33:28.882  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:28.882  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:28.882  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:28.882  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:28.882  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 14:33:28.882  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:28.882  3322  3371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:28.882  3322  3371 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-09 14:33:28.884  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-09 14:33:28.886  3322  3371 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-09 14:33:28.886  3322  3371 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-09 14:33:28.887  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:28.888  3322  3371 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-09 14:33:28.889  3322  3371 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-09 14:33:28.889  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-09 14:33:28.889  3322  3371 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 14:33:28.889  3322  3371 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 14:33:28.889  3322  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:28.890  3322  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:28.890  3322  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:28.890  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:28.890  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.890  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 14:33:28.890  3322  3371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 14:33:28.891  3322  3371 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f11aa1 removed from the list
08-09 14:33:28.891  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:28.891  3322  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 removed from the list
08-09 14:33:28.891  3322  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:28.891  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.892  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.892  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.892  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-09 14:33:28.892  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:28.892  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:28.892  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:28.895  3322  3371 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-09 14:33:28.896  3322  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:28.896  3322  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:28.896  3322  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:28.896  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-09 14:33:28.896  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.896  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.896  3322  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f11aa1 not in the list
08-09 14:33:28.896  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:28.897  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
,08-09 14:33:28.897  3322  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:28.897  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.897  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.897  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.897  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.898  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:28.898  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:28.898  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 14:33:28.898  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
,08-09 14:33:28.906  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-09 14:33:28.906  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-09 14:33:28.906  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-09 14:33:28.907  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-09 14:33:28.907  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-09 14:33:28.907  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-09 14:33:28.907  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-09 14:33:28.907  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-09 14:33:28.907  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-09 14:33:28.907  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-09 14:33:28.907  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-09 14:33:28.907  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-09 14:33:28.907  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-09 14:33:28.907  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-09 14:33:28.907  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-09 14:33:28.907  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-09 14:33:28.907  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-09 14:33:28.907  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-09 14:33:28.907  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-09 14:33:28.907  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-09 14:33:28.907  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-09 14:33:28.908  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-09 14:33:28.908  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-09 14:33:28.908  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-09 14:33:28.909  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-09 14:33:28.909  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-09 14:33:28.909  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-09 14:33:28.909  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-09 14:33:28.909  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-09 14:33:28.909  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-09 14:33:28.909  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-09 14:33:28.909  3322  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:28.910  3322  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:28.910  3322  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:28.910  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:28.910  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.910  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.910  3322  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f11aa1 not in the list
,08-09 14:33:28.910  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:28.910  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:28.910  3322  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:28.910  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.910  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.910  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.911  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.912  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:28.912  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:28.912  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:28.912  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:28.913  3322  3371 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-09 14:33:28.916  3322  3371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 14:33:28.917  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:28.917  3322  3371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 14:33:28.917  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:28.917  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 14:33:28.917  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:28.917  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:28.917  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:28.917  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:28.917  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 14:33:28.917  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:28.917  3322  3371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:28.917  3322  3371 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 14:33:28.917  3322  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 14:33:28.917  3322  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 14:33:28.918  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-09 14:33:28.918  3322  3371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 14:33:28.918  3322  3371 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-09 14:33:28.919  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:28.922  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,08-09 14:33:28.925  3322  3371 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,08-09 14:33:28.926  3322  3371 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-09 14:33:28.926  3322  3322 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-09 14:33:28.926  3322  3371 I io.jxcore.node.ConnectionHelper: start: OK
08-09 14:33:28.927  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:28.927  3322  3371 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
,08-09 14:33:28.929  3322  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:28.929  3322  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:28.929  3322  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-09 14:33:28.929  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.929  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 14:33:28.929  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-09 14:33:28.929  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-09 14:33:28.929  3322  3371 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-09 14:33:28.929  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-09 14:33:28.930  3322  3371 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-09 14:33:28.931  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 14:33:28.931  3322  3371 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 14:33:28.932  3322  3322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 14:33:28.932  3322  3322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 14:33:28.932  3322  3322 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-09 14:33:28.932  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:28.932  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.932  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 14:33:28.932  3322  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f11aa1 not in the list
08-09 14:33:28.932  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:28.932  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:28.932  3322  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:28.932  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.933  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.933  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.933  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-09 14:33:28.933  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:28.933  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:28.933  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:28.934  3322  3371 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-09 14:33:28.935  3322  3371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 14:33:28.938  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:28.939  3322  3371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 14:33:28.939  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:28.939  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 14:33:28.939  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:28.939  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:28.939  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:28.939  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:28.939  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 14:33:28.939  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:28.939  3322  3371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 14:33:28.939  3322  3371 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 14:33:28.940  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:28.940  3322  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 14:33:28.940  3322  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 14:33:28.940  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-09 14:33:28.940  3322  3371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 14:33:28.940  3322  3371 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-09 14:33:28.941  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-09 14:33:28.942  3322  3371 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-09 14:33:28.942  3322  3371 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-09 14:33:28.942  3322  3371 I io.jxcore.node.ConnectionHelper: start: OK
08-09 14:33:28.942  3322  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:28.942  3322  3322 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-09 14:33:28.942  3322  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:28.942  3322  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-09 14:33:28.942  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.942  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-09 14:33:28.942  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-09 14:33:28.942  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-09 14:33:28.942  3322  3371 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-09 14:33:28.943  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-09 14:33:28.943  3322  3371 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-09 14:33:28.944  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 14:33:28.945  3322  3371 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-09 14:33:28.945  3322  3322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 14:33:28.945  3322  3322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 14:33:28.945  3322  3322 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 14:33:28.946  3322  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:28.946  3322  3371 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-09 14:33:28.946  3322  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:28.946  3322  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:28.947  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:28.947  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 14:33:28.947  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 14:33:28.948  3322  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f11aa1 not in the list
08-09 14:33:28.948  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:28.948  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:28.948  3322  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:28.949  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 14:33:28.950  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.950  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.951  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:28.951  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:28.951  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 14:33:28.951  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
,08-09 14:33:28.953  3322  3371 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-09 14:33:28.955  3322  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-09 14:33:28.955  3322  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:28.956  3322  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:28.956  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:28.956  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 14:33:28.957  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.957  3322  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f11aa1 not in the list
08-09 14:33:28.957  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:28.957  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:28.958  3322  3371 D io.jxcore.node.ConnectivityMonitor: stop
,08-09 14:33:28.958  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.958  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.958  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.959  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 14:33:28.959  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-09 14:33:28.959  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:28.959  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:28.959  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:28.960  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-09 14:33:28.960  3322  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:28.960  3322  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:28.960  3322  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:28.961  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:28.961  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.961  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.961  3322  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f11aa1 not in the list
,08-09 14:33:28.961  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:28.961  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:28.961  3322  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:28.961  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.961  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 14:33:28.961  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.961  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.962  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-09 14:33:28.962  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:28.962  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:28.962  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:28.963  3322  3371 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-09 14:33:28.963  3322  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:28.963  3322  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:28.963  3322  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-09 14:33:28.963  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:28.963  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 14:33:28.963  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.963  3322  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f11aa1 not in the list
08-09 14:33:28.963  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:28.963  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:28.963  3322  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:28.963  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.963  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 14:33:28.963  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.963  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 14:33:28.964  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:28.964  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:28.964  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 14:33:28.964  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:28.964  3322  3371 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-09 14:33:28.964  3322  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:28.964  3322  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:28.964  3322  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:28.965  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:28.965  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.965  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 14:33:28.965  3322  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f11aa1 not in the list
08-09 14:33:28.965  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:28.965  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:28.965  3322  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:28.965  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.965  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.965  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 14:33:28.965  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.965  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:28.965  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:28.965  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:28.965  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:28.966  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-09 14:33:28.967  3322  3371 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 14:33:28.967  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-09 14:33:28.967  3322  3371 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 14:33:28.968  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-09 14:33:28.968  3322  3371 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 14:33:28.968  3322  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:28.968  3322  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:28.968  3322  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:28.968  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:28.968  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.968  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.968  3322  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f11aa1 not in the list
,08-09 14:33:28.968  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:28.968  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
,08-09 14:33:28.969  3322  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:28.969  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 14:33:28.969  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.969  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.969  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.969  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-09 14:33:28.970  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:28.970  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:28.970  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:28.971  3322  3371 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-09 14:33:28.971  3322  3371 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-09 14:33:28.971  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-09 14:33:28.974  3322  3371 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 14:33:28.974  3322  3371 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-09 14:33:28.974  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-09 14:33:28.974  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-09 14:33:28.974  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-09 14:33:28.974  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-09 14:33:28.974  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-09 14:33:28.974  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-09 14:33:28.974  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-09 14:33:28.974  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-09 14:33:28.974  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-09 14:33:28.974  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-09 14:33:28.974  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-09 14:33:28.974  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-09 14:33:28.974  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-09 14:33:28.974  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-09 14:33:28.974  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-09 14:33:28.975  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-09 14:33:28.975  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-09 14:33:28.975  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-09 14:33:28.975  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-09 14:33:28.975  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-09 14:33:28.975  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-09 14:33:28.975  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-09 14:33:28.975  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-09 14:33:28.975  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-09 14:33:28.975  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-09 14:33:28.975  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-09 14:33:28.975  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-09 14:33:28.975  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-09 14:33:28.975  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-09 14:33:28.979  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-09 14:33:28.979  3322  3371 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-09 14:33:28.979  3322  3371 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-09 14:33:28.979  3322  3371 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-09 14:33:28.979  3322  3371 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 14:33:28.979  3322  3371 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-09 14:33:28.979  3322  3371 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-09 14:33:28.979  3322  3371 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 14:33:28.979  3322  3371 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-09 14:33:28.980  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-09 14:33:28.981  3322  3371 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
08-09 14:33:28.981  3322  3371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-09 14:33:28.982  3322  3371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1,
08-09 14:33:28.982  3322  3371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-09 14:33:28.983  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-09 14:33:28.983  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55,
08-09 14:33:28.983  3322  3371 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-09 14:33:28.983  3322  3371 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 14:33:28.984  3322  3371 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-09 14:33:28.984  3322  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:28.984  3322  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:28.984  3322  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-09 14:33:28.984  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:28.985  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.985  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.985  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-09 14:33:28.993  3322  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f11aa1 not in the list
08-09 14:33:28.993  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:28.994  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
,08-09 14:33:28.994  3322  3374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 349
08-09 14:33:28.994  3322  3371 D io.jxcore.node.ConnectivityMonitor: stop
,08-09 14:33:28.994  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.994  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.994  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 14:33:28.994  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.995  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:28.995  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:28.995  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 14:33:28.995  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:28.996  3322  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 349)
08-09 14:33:28.996  3322  3371 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-09 14:33:28.996  3322  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 349),
08-09 14:33:28.997  3322  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:28.997  3322  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:28.997  3322  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-09 14:33:28.997  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:28.997  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.997  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.997  3322  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f11aa1 not in the list
08-09 14:33:28.997  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:28.997  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:28.997  3322  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:28.997  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 14:33:28.998  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 14:33:28.998  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:28.998  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:28.998  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:28.998  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:28.998  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:28.998  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:28.999  3322  3371 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-09 14:33:28.999  3322  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:28.999  3322  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:28.999  3322  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:29.000  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:29.000  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.000  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.000  3322  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f11aa1 not in the list
08-09 14:33:29.000  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:29.000  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:29.000  3322  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:29.000  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.000  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.000  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.000  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.001  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:29.001  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:29.001  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:29.001  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:29.001  3322  3371 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-09 14:33:29.001  3322  3371 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-09 14:33:29.001  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgo,ing connection(s) left
08-09 14:33:29.002  3322  3371 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-09 14:33:29.002  3322  3371 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-09 14:33:29.002  3322  3371 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-09 14:33:29.002  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-09 14:33:29.002  3322  3371 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-09 14:33:29.002  3322  3371 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-09 14:33:29.002  3322  3371 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-09 14:33:29.002  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-09 14:33:29.002  3322  3371 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-09 14:33:29.002  3322  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:29.002  3322  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:29.002  3322  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:29.003  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:29.003  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.003  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.003  3322  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f11aa1 not in the list
08-09 14:33:29.003  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:29.003  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:29.003  3322  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:29.003  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.003  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.003  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.003  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.004  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:29.004  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:29.004  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:29.004  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:29.004  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:29.004  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.004  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.004  3322  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f11aa1 not in the list
08-09 14:33:29.004  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:29.004  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:29.005  3322  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:29.005  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.005  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.005  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:29.005  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:29.005  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:29.005  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.005  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.005  3322  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f11aa1 not in the list
08-09 14:33:29.005  3322  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:29.005  3322  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:29.005  3322  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:29.005  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:29.006  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.006  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.006  3322  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f11aa1 not in the list
08-09 14:33:29.006  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:29.006  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:29.006  3322  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:29.006  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.006  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.006  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.006  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.007  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:29.007  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:29.007  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:29.007  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:29.008  3322  3371 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-09 14:33:29.009  3322  3371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 14:33:29.009  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
08-09 14:33:29.009  3322  3371 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
08-09 14:33:29.009  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-09 14:33:29.010  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:29.010  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-09 14:33:29.010  3322  3322 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
08-09 14:33:29.010  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.010  3322  3371 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
08-09 14:33:29.010  3322  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f11aa1 not in the list
08-09 14:33:29.010  3322  3322 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-09 14:33:29.010  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:29.010  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-09 14:33:29.010  3322  3371 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-09 14:33:29.010  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-09 14:33:29.010  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.010  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.011  3322  3371 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 14:33:29.012  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:29.012  3322  3322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 14:33:29.012  3322  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:29.012  3322  3322 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 14:33:29.012  3322  3322 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 14:33:29.012  3322  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:29.012  3322  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:29.012  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:29.012  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.012  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.012  3322  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f11aa1 not in the list
08-09 14:33:29.012  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:29.012  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:29.012  3322  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:29.012  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.012  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.013  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.013  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.013  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:29.013  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:29.013  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:29.013  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:29.014  3322  3371 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-09 14:33:29.014  3322  3371 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-09 14:33:29.014  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-09 14:33:29.015  3322  3371 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 14:33:29.015  3322  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:29.015  3322  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:29.015  3322  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:29.015  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:29.015  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.015  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.015  3322  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f11aa1 not in the list
08-09 14:33:29.015  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:29.015  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:29.015  3322  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:29.016  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.016  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.016  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.016  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.016  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:29.016  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:29.016  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:29.016  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:29.019  3322  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:29.019  3322  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:29.019  3322  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:29.020  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:29.020  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.020  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.020  3322  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f11aa1 not in the list
08-09 14:33:29.020  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:29.020  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:29.020  3322  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:29.020  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.020  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.020  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.020  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.021  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:29.021  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:29.021  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:29.021  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:29.023  3322  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 14:33:29.023  3322  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 14:33:29.023  3322  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 14:33:29.024  3322  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 14:33:29.024  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.024  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.024  3322  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f11aa1 not in the list
08-09 14:33:29.024  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:29.024  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:29.024  3322  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-09 14:33:29.024  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.024  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 14:33:29.024  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 14:33:29.025  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 14:33:29.025  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 14:33:29.025  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 14:33:29.025  3322  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 14:33:29.025  3322  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b94c6 not in the list
08-09 14:33:29.026  3322  3371 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-09 14:33:29.026  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-09 14:33:29.026  3322  3371 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-09 14:33:29.027  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-09 14:33:29.027  3322  3371 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-09 14:33:29.027  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-09 14:33:29.028  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-09 14:33:29.029  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-09 14:33:29.029  3322  3371 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-09 14:33:29.029  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-09 14:33:29.029  3322  3371 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-09 14:33:29.029  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-09 14:33:29.029  3322  3371 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-09 14:33:29.030  3322  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-09 14:33:29.030  3322  3371 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-09 14:33:29.030  3322  3371 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-09 14:33:29.031  3322  3371 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-09 14:33:29.031  3322  3371 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-09 14:33:29.031  3322  3371 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-09 14:33:29.031  3322  3371 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-09 14:33:29.032  3322  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 14:33:29.032  3322  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b5a1b20 added. We now have 2 listener(s)
08-09 14:33:29.032  3322  3371 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 14:33:29.033   870  1737 D WifiService: setWifiEnabled: true pid=3322, uid=10000
08-09 14:33:29.033   870  1737 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-09 14:33:29.037  3322  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 14:33:29.037  3322  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4617cd9 added. We now have 3 listener(s)
08-09 14:33:29.038  3322  3371 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 14:33:29.038  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:29.038  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:29.039  3322  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 14:33:29.039  3322  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a62769e added. We now have 4 listener(s)
08-09 14:33:29.039  3322  3371 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 14:33:29.040  3322  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 14:33:29.040  3322  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@844d57f added. We now have 5 listener(s)
08-09 14:33:29.040  3322  3371 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 14:33:29.041   870   881 D WifiService: setWifiEnabled: false pid=3322, uid=10000
08-09 14:33:29.041   870   881 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-09 14:33:29.047   870   887 I ActivityManager: Start proc 3377:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
08-09 14:33:29.048   870  1312 D WifiConfigStore: Loading config and enabling all networks 
08-09 14:33:29.052  3322  3322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:29.053  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:29.053  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:29.053  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 14:33:29.053  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:29.053  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:29.053  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:29.053  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:29.053  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 14:33:29.053  3322  3322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:29.053  3322  3322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:29.069   870  1312 D WifiConfigStore: loaded 0 passpoint configs
08-09 14:33:29.069   870  1312 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-09 14:33:29.070   870  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-09 14:33:29.070   870  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-09 14:33:29.070   870  1312 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
08-09 14:33:29.071   870  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-09 14:33:29.071   870  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 3
08-09 14:33:29.071   870  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-09 14:33:29.071   870  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-09 14:33:29.071   870  1312 E WifiConfigStore: found sortedWifiConfigurations : "ktwtestwifi"WPA_EAP
08-09 14:33:29.083   870   883 I ActivityManager: Start proc 3389:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-09 14:33:29.084  3322  3371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 14:33:29.087  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:29.087  3322  3371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 14:33:29.087  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:29.087  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 14:33:29.087  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:29.087  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:29.087  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:29.087  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:29.087  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 14:33:29.088  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:29.088  3322  3371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:29.088  3322  3371 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 14:33:29.089  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:29.113  3389  3389 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-09 14:33:29.148   371   868 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-09 14:33:29.149   371   868 D CommandListener: Setting iface cfg
08-09 14:33:29.149   870  1311 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '34 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 34 Failed to set address (No such device)'
08-09 14:33:29.149   870  1311 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-09 14:33:29.151   870  1311 D WifiNative-HAL: p2pGetDeviceAddress
,08-09 14:33:29.151   870  1311 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
08-09 14:33:29.166  3389  3389 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-09 14:33:29.186   870  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-09 14:33:29.187  3322  3322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:29.187  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:29.187  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:29.187  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 14:33:29.187  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:29.187  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:29.187  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:29.187  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:29.187  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 14:33:29.188  3322  3322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:29.188  3322  3322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:29.189  3322  3322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:29.189  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:29.189  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:29.189  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-09 14:33:29.189  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:29.189  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:29.189  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:29.189  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:29.189  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 14:33:29.189  3322  3322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:29.189  3322  3322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 14:33:29.197  1939  2071 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-09 14:33:29.231  3377  3377 D AdapterServiceConfig: Adding HeadsetService
,08-09 14:33:29.232  3377  3377 D AdapterServiceConfig: Adding A2dpService
08-09 14:33:29.232  3377  3377 D AdapterServiceConfig: Adding HidService
08-09 14:33:29.232  3377  3377 D AdapterServiceConfig: Adding HealthService
08-09 14:33:29.232  3377  3377 D AdapterServiceConfig: Adding PanService
08-09 14:33:29.232  3377  3377 D AdapterServiceConfig: Adding GattService
08-09 14:33:29.232  3377  3377 D AdapterServiceConfig: Adding BluetoothMapService
,08-09 14:33:29.279   870   887 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a923fc5:true
,08-09 14:33:29.279  3377  3377 D BluetoothAdapterState: make() - Creating AdapterState
,08-09 14:33:29.283  3377  3377 I bt_bluedroid: init
,08-09 14:33:29.284  3377  3419 I BluetoothAdapterState: Entering OffState
,08-09 14:33:29.286  3377  3420 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-09 14:33:29.287  3377  3420 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-09 14:33:29.287  3377  3420 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-09 14:33:29.287  3377  3420 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-09 14:33:29.288  3377  3377 I bt_bluedroid: get_profile_interface socket
,08-09 14:33:29.290  3377  3377 I bt_bluedroid: get_profile_interface sdp
,08-09 14:33:29.291  3377  3423 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-09 14:33:29.292  3377  3388 I bt_bluedroid: config_hci_snoop_log
,08-09 14:33:29.293  3377  3423 D BluetoothAdapterProperties: Name is: Nexus 6
08-09 14:33:29.293   870   887 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-09 14:33:29.297  3377  3419 D BluetoothAdapterState: Current state: OFF, message: 0
,08-09 14:33:29.297  3377  3419 D BluetoothAdapterProperties: Setting state to 14
08-09 14:33:29.297  3377  3419 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-09 14:33:29.300  3377  3419 D BluetoothBondStateMachine: make
,08-09 14:33:29.303  3377  3424 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-09 14:33:29.307  3377  3419 I BluetoothAdapterState: Entering PendingCommandState
,08-09 14:33:29.308  3377  3377 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-09 14:33:29.310  3377  3377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1062b7
,08-09 14:33:29.310  3377  3377 D BtGatt.DebugUtils: handleDebugAction() action=null
08-09 14:33:29.311  3377  3377 D BtGatt.GattService: Received start request. Starting profile...
08-09 14:33:29.311  3377  3377 D BtGatt.GattService: start()
,08-09 14:33:29.311  3377  3377 I bt_bluedroid: get_profile_interface gatt
,08-09 14:33:29.312  3377  3377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1062b7
08-09 14:33:29.312  3377  3377 D BtGatt.AdvertiseManager: advertise manager created
,08-09 14:33:29.317  3377  3377 V BluetoothAdapterState: isTurningOff()=false
,08-09 14:33:29.317  3377  3377 V BluetoothAdapterState: isTurningOn()=false
08-09 14:33:29.317  3377  3377 V BluetoothAdapterState: isBleTurningOn()=true
08-09 14:33:29.318  3377  3377 V BluetoothAdapterState: isBleTurningOff()=false
08-09 14:33:29.318  3377  3419 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-09 14:33:29.319  3377  3419 I bt_bluedroid: enable
,08-09 14:33:29.319  3377  3420 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-09 14:33:29.320  3377  3420 I bt_hci  : start_up
,08-09 14:33:29.331  3377  3420 I bt_vendor: alloc value 0xb39c1189
08-09 14:33:29.331  3377  3420 I bt_vendor: init
,08-09 14:33:29.331  3377  3420 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-09 14:33:29.332  3377  3420 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-09 14:33:29.385  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:33:29.407  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:33:29.412  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:33:29.439  3377  3420 D bt_hci  : start_up starting async portion
,08-09 14:33:29.440  3377  3427 I bt_hci  : event_finish_startup
,08-09 14:33:29.441  3377  3427 I bt_hci_h4: hal_open
,08-09 14:33:29.441  3377  3427 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-09 14:33:29.447  3377  3427 I bt_userial_vendor: device fd = 51 open
,08-09 14:33:29.450  1515  1983 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-09 14:33:29.450  1515  1983 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-09 14:33:29.450  1515  1983 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 14:33:29.450  1515  1983 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 14:33:29.472  2573  2573 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-09 14:33:29.472  2573  2573 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-09 14:33:29.472  2573  2573 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,08-09 14:33:29.481  3377  3427 I bt_hwcfg: bt vendor lib: set UART baud 3000000,
,08-09 14:33:29.499   870  1823 I ActivityManager: Killing 2663:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-09 14:33:29.512  3322  3322 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-09 14:33:29.514  3377  3427 D bt_hwcfg: Chipset BCM4354A2
08-09 14:33:29.514  3377  3427 D bt_hwcfg: Target name = [BCM4354A2]
08-09 14:33:29.514  3377  3427 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-09 14:33:30.168  3377  3427 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-09 14:33:30.170  3377  3427 D bt_hwcfg: Settlement delay -- 100 ms
08-09 14:33:30.170  3377  3427 I bt_hwcfg: Setting fw settlement delay to 100 
,08-09 14:33:30.287  3377  3427 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-09 14:33:30.288  3377  3427 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-09 14:33:30.317  3377  3427 I bt_hwcfg: vendor lib fwcfg completed
,08-09 14:33:30.318  3377  3427 I bt_vendor: firmware callback
08-09 14:33:30.318  3377  3427 I bt_hci  : firmware_config_callback
,08-09 14:33:30.329  3377  3430 I bt_btu  : btu_task pending for preload complete event
,08-09 14:33:30.330  3377  3430 I bt_btu_task: Bluetooth chip preload is complete
,08-09 14:33:30.330  3377  3430 I bt_btu  : btu_task received preload complete event
,08-09 14:33:30.344  3377  3430 I         : BTE_InitTraceLevels -- TRC_HCI
,08-09 14:33:30.344  3377  3430 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-09 14:33:30.344  3377  3430 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-09 14:33:30.344  3377  3430 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-09 14:33:30.345  3377  3430 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-09 14:33:30.345  3377  3430 I         : BTE_InitTraceLevels -- TRC_A2D
08-09 14:33:30.345  3377  3430 I         : BTE_InitTraceLevels -- TRC_BNEP
08-09 14:33:30.346  3377  3430 I         : BTE_InitTraceLevels -- TRC_BTM
08-09 14:33:30.346  3377  3430 I         : BTE_InitTraceLevels -- TRC_GAP
08-09 14:33:30.346  3377  3430 I         : BTE_InitTraceLevels -- TRC_PAN
08-09 14:33:30.346  3377  3430 I         : BTE_InitTraceLevels -- TRC_SDP
08-09 14:33:30.347  3377  3430 I         : BTE_InitTraceLevels -- TRC_GATT
08-09 14:33:30.347  3377  3430 I         : BTE_InitTraceLevels -- TRC_SMP
08-09 14:33:30.347  3377  3430 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-09 14:33:30.348  3377  3430 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-09 14:33:30.481  3377  3430 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb393ed9d
,08-09 14:33:30.482  3377  3430 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb393ed9d 
,08-09 14:33:30.493  3377  3423 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-09 14:33:30.494  3377  3423 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-09 14:33:30.495  3377  3423 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-09 14:33:30.498  3377  3423 D BluetoothAdapterProperties: Name is: Nexus 6
,08-09 14:33:30.502  3377  3423 D BluetoothAdapterProperties: Scan Mode:20
,08-09 14:33:30.502  3377  3423 D BluetoothAdapterProperties: Discoverable Timeout:120
08-09 14:33:30.504  3377  3423 D bt_hci  : do_postload posting postload work item
08-09 14:33:30.504  3377  3427 I bt_hci  : event_postload
,08-09 14:33:30.504  3377  3427 I bt_vendor: sco_config_cb
08-09 14:33:30.504  3377  3427 I bt_hci  : sco_config_callback postload finished.
08-09 14:33:30.507  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:30.511  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:30.512  3377  3427 I bt_vendor: low_power_mode_cb
,08-09 14:33:30.516  3377  3423 D bt_bte_conf: Device ID record 1 : primary
08-09 14:33:30.516  3377  3423 D bt_bte_conf:   vendorId            = 000f
08-09 14:33:30.516  3377  3423 D bt_bte_conf:   vendorIdSource      = 0001
08-09 14:33:30.516  3377  3423 D bt_bte_conf:   product             = 1200
08-09 14:33:30.516  3377  3423 D bt_bte_conf:   version             = 1436
08-09 14:33:30.517  3377  3423 D bt_bte_conf:   clientExecutableURL = 
08-09 14:33:30.517  3377  3423 D bt_bte_conf:   serviceDescription  = 
08-09 14:33:30.517  3377  3423 D bt_bte_conf:   documentationURL    = 
08-09 14:33:30.517  3377  3423 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-09 14:33:30.518  3377  3420 D bt_stack_manager: event_start_up_stack finished
08-09 14:33:30.519  3377  3419 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-09 14:33:30.520  3377  3419 D BluetoothAdapterProperties: Setting state to 15
08-09 14:33:30.520  3377  3419 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-09 14:33:30.522  3377  3419 I BluetoothAdapterState: Entering BleOnState
,08-09 14:33:30.529  3377  3419 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-09 14:33:30.530  3377  3419 D BluetoothAdapterProperties: Setting state to 11
,08-09 14:33:30.530  3377  3419 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-09 14:33:30.540  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:30.542  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:30.543  3377  3377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1062b7,
,08-09 14:33:30.543  3377  3377 D HeadsetService: Received start request. Starting profile...
08-09 14:33:30.547  3377  3377 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-09 14:33:30.547  3377  3377 D HeadsetStateMachine: make
,08-09 14:33:30.554   870   883 I ActivityManager: Start proc 3438:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-09 14:33:30.557  3377  3377 D HeadsetStateMachine: max_hf_connections = 1
,08-09 14:33:30.557  3377  3377 I bt_bluedroid: get_profile_interface handsfree
08-09 14:33:30.558  3377  3423 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-09 14:33:30.558  3377  3423 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-09 14:33:30.565  3377  3377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1062b7
,08-09 14:33:30.567  3377  3419 I BluetoothAdapterState: Entering PendingCommandState
08-09 14:33:30.567   870   870 D BluetoothA2dp: Proxy object connected
,08-09 14:33:30.567  3377  3377 D A2dpService: Received start request. Starting profile...
08-09 14:33:30.568  3377  3377 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-09 14:33:30.568  3377  3377 I bt_bluedroid: get_profile_interface avrcp
,08-09 14:33:30.574  3377  3377 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-09 14:33:30.575  3377  3377 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-09 14:33:30.575  3377  3377 D A2dpStateMachine: make
08-09 14:33:30.576  3377  3377 I bt_bluedroid: get_profile_interface a2dp,
08-09 14:33:30.576  3377  3423 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-09 14:33:30.579  3377  3451 D A2dpStateMachine: Enter Disconnected: -2
,08-09 14:33:30.579  3377  3377 I BluetoothHidServiceJni: classInitNative: succeeds
,08-09 14:33:30.580  3377  3377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1062b7
,08-09 14:33:30.581  1370  1370 D BluetoothInputDevice: Proxy object connected
08-09 14:33:30.581  3377  3377 D HidService: Received start request. Starting profile...
08-09 14:33:30.581  1370  1370 D HidProfile: Bluetooth service connected
08-09 14:33:30.582  3377  3377 I bt_bluedroid: get_profile_interface hidhost
08-09 14:33:30.582  3377  3423 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39203e5
08-09 14:33:30.582  3377  3423 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-09 14:33:30.582  3377  3377 D HidService: setHidService(): set to: null
,08-09 14:33:30.585  3377  3377 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-09 14:33:30.587  3377  3377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1062b7
,08-09 14:33:30.588  3377  3377 D HealthService: Received start request. Starting profile...
,08-09 14:33:30.590  3377  3377 I bt_bluedroid: get_profile_interface health
,08-09 14:33:30.590  3377  3377 V BluetoothAdapterState: isTurningOff()=false
08-09 14:33:30.591  3377  3377 V BluetoothAdapterState: isTurningOn()=true
,08-09 14:33:30.591  3377  3377 V BluetoothAdapterState: isBleTurningOn()=false
08-09 14:33:30.591  3377  3377 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 14:33:30.593  3377  3437 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-09 14:33:30.594  3377  3377 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-09 14:33:30.594  3377  3377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1062b7
,08-09 14:33:30.595  3377  3377 D PanService: Received start request. Starting profile...
,08-09 14:33:30.595  1370  1370 D BluetoothPan: BluetoothPAN Proxy object connected
08-09 14:33:30.595  3377  3377 D BluetoothPanServiceJni: initializeNative(L110): pan
08-09 14:33:30.595  3377  3377 I bt_bluedroid: get_profile_interface pan
08-09 14:33:30.596  3377  3423 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-09 14:33:30.596  1370  1370 D PanProfile: Bluetooth service connected
,08-09 14:33:30.598  3377  3377 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1062b7
,08-09 14:33:30.599  1370  1370 D BluetoothMap: Proxy object connected
08-09 14:33:30.599  3377  3377 D BluetoothMapService: Received start request. Starting profile...
08-09 14:33:30.599  3377  3377 D BluetoothMapService: start()
08-09 14:33:30.599  1370  1370 D MapProfile: Bluetooth service connected
08-09 14:33:30.599  1370  1370 D BluetoothMap: getConnectedDevices()
08-09 14:33:30.600  1370  1370 D BluetoothMap: Bluetooth is Not enabled
,08-09 14:33:30.601  3377  3377 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-09 14:33:30.602  3377  3377 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-09 14:33:30.602  3377  3377 D BluetoothMapAppObserver: createReceiver()
08-09 14:33:30.603  3377  3377 D BluetoothMapAppObserver: initObservers()
08-09 14:33:30.603  3377  3377 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-09 14:33:30.609  3377  3377 V BluetoothAdapterState: isTurningOff()=false
08-09 14:33:30.609  3377  3377 V BluetoothAdapterState: isTurningOn()=true
,08-09 14:33:30.609  3377  3377 V BluetoothAdapterState: isBleTurningOn()=false
08-09 14:33:30.609  3377  3377 V BluetoothAdapterState: isBleTurningOff()=false
08-09 14:33:30.609  3377  3377 V BluetoothAdapterState: isTurningOff()=false
08-09 14:33:30.609  3377  3377 V BluetoothAdapterState: isTurningOn()=true
08-09 14:33:30.609  3377  3377 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 14:33:30.610  3377  3377 V BluetoothAdapterState: isBleTurningOff()=false
08-09 14:33:30.610  3377  3377 V BluetoothAdapterState: isTurningOff()=false
08-09 14:33:30.610  3377  3377 V BluetoothAdapterState: isTurningOn()=true
08-09 14:33:30.610  3377  3377 V BluetoothAdapterState: isBleTurningOn()=false
08-09 14:33:30.610  3377  3377 V BluetoothAdapterState: isBleTurningOff()=false
08-09 14:33:30.610  3377  3377 V BluetoothAdapterState: isTurningOff()=false
,08-09 14:33:30.610  3377  3377 V BluetoothAdapterState: isTurningOn()=true
08-09 14:33:30.610  3377  3377 V BluetoothAdapterState: isBleTurningOn()=false
08-09 14:33:30.610  3377  3377 V BluetoothAdapterState: isBleTurningOff()=false
08-09 14:33:30.610  3377  3377 V BluetoothAdapterState: isTurningOff()=false
08-09 14:33:30.610  3377  3377 V BluetoothAdapterState: isTurningOn()=true
08-09 14:33:30.611  3377  3377 V BluetoothAdapterState: isBleTurningOn()=false
08-09 14:33:30.611  3377  3377 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 14:33:30.611  3377  3419 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-09 14:33:30.611  3377  3419 D BluetoothAdapterProperties: ScanMode =  20
08-09 14:33:30.611  3377  3419 D BluetoothAdapterProperties: State =  11
08-09 14:33:30.611  3377  3419 D BluetoothAdapterProperties: Setting state to 12
08-09 14:33:30.612  3377  3419 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-09 14:33:30.612  3377  3419 I BluetoothAdapterState: Entering OnState
08-09 14:33:30.612  1370  1842 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-09 14:33:30.613  1370  1381 D BluetoothMap: onBluetoothStateChange: up=true
08-09 14:33:30.613   870   887 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 14:33:30.614  3377  3423 D BluetoothAdapterProperties: Scan Mode:21
08-09 14:33:30.614  3377  3423 D BluetoothAdapterProperties: Discoverable Timeout:120
08-09 14:33:30.614   870   887 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 14:33:30.615   870   887 D BluetoothA2dp: onBluetoothStateChange: up=true
08-09 14:33:30.615   870   887 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 14:33:30.615  1370  1382 D BluetoothPan: onBluetoothStateChange on: true
08-09 14:33:30.615  1370  1840 D BluetoothPbap: onBluetoothStateChange: up=true
08-09 14:33:30.616  3322  3322 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-09 14:33:30.617  1738  1860 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-09 14:33:30.619   870   870 I Telecom : BluetoothPhoneService: queryPhoneState
,08-09 14:33:30.620  3322  3322 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-09 14:33:30.620  3377  3377 D BluetoothMapService: onReceive
08-09 14:33:30.620  3377  3377 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:30.620  3377  3377 D BluetoothMapService: STATE_ON
08-09 14:33:30.622  3322  3322 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-09 14:33:30.623  1370  1673 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-09 14:33:30.626  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:30.626  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:30.626  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 14:33:30.626  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:30.626  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:30.626  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:30.626  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:30.626  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 14:33:30.627  1370  1370 D BluetoothA2dp: Proxy object connected
08-09 14:33:30.628  3322  3322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:30.629  3377  3377 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-09 14:33:30.630  3377  3377 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-09 14:33:30.631  3377  3377 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 14:33:30.631  1370  1673 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-09 14:33:30.632  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:30.632  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:30.632  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 14:33:30.632  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:30.632  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:30.632  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:30.632  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:30.632  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 14:33:30.633  3377  3377 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 14:33:30.634  3322  3322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:30.635  3377  3377 D ObexServerSockets: Succeed to create listening sockets 
,08-09 14:33:30.635  3377  3377 D ObexServerSockets0: startAccept()
08-09 14:33:30.635  3377  3377 D ObexServerSockets0: prepareForNewConnect()
,08-09 14:33:30.636  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:30.637  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:30.637  3438  3438 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-09 14:33:30.637  3377  3458 D ObexServerSockets0: Accepting socket connection...
08-09 14:33:30.637  3377  3377 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-09 14:33:30.637  3377  3377 D BluetoothSdpJni: SDP Create record success - handle: 0
08-09 14:33:30.638  3377  3459 D ObexServerSockets0: Accepting socket connection...
,08-09 14:33:30.641  3377  3377 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-09 14:33:30.641  3377  3377 D ObexServerSockets0: prepareForNewConnect()
,08-09 14:33:30.646   870  1757 I ActivityManager: Killing 2806:com.google.android.gm/u0a78 (adj 15): empty #17
,08-09 14:33:30.689  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 14:33:30.707   870  1389 I ActivityManager: Start proc 3460:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-09 14:33:30.715   870   887 D BluetoothHeadset: Proxy object connected
,08-09 14:33:30.718   870   887 D BluetoothHeadset: Proxy object connected
,08-09 14:33:30.719   870   887 D BluetoothHeadset: Proxy object connected
,08-09 14:33:30.721  1738  1753 D BluetoothHeadset: Proxy object connected
,08-09 14:33:30.739  1370  1842 D BluetoothHeadset: Proxy object connected
,08-09 14:33:30.740  1370  1370 D HeadsetProfile: Bluetooth service connected
,08-09 14:33:30.758  3460  3460 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-09 14:33:30.949  3460  3460 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at java.io.File.exists(File.java:361)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-09 14:33:30.949  3460  3460 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-09 14:33:30.949  3460  3460 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-09 14:33:30.949  3460  3460 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.r.e.b(PG:170)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-09 14:33:30.949  3460  3460 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.r.k.d(PG:583)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.r.e.b(PG:170)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-09 14:33:30.949  3460  3460 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at java.io.File.exists(File.java:361)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 14:33:30.949  3460  3460 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-09 14:33:30.950  3460  3460 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 14:33:30.950  3460  3460 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at java.io.File.exists(File.java:361)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-09 14:33:30.950  3460  3460 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 14:33:30.950  3460  3460 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 14:33:30.950  3460  3460 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-09 14:33:30.957  3438  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-09 14:33:30.968   870   887 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37c43ef:true
,08-09 14:33:30.971  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 14:33:30.987  3438  3438 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-09 14:33:30.991  1370  1370 D BluetoothPbap: Proxy object connected
08-09 14:33:30.992  1370  1370 D PbapServerProfile: Bluetooth service connected
08-09 14:33:30.993  3438  3438 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-09 14:33:31.010  3377  3489 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 14:33:31.023  3438  3438 D LocalBluetoothProfileManager: Adding local MAP profile
,08-09 14:33:31.024  3438  3438 D BluetoothMap: Create BluetoothMap proxy object
,08-09 14:33:31.029  3438  3438 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-09 14:33:31.031  3377  3493 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 14:33:31.033  3377  3493 I BtOppRfcommListener: Accept thread started.
,08-09 14:33:31.034  3438  3438 D DockEventReceiver: finishStartingService: stopping service
,08-09 14:33:31.036  3438  3438 D BluetoothA2dp: Proxy object connected
,08-09 14:33:31.042  3438  3438 D BluetoothInputDevice: Proxy object connected
,08-09 14:33:31.043  3438  3438 D HidProfile: Bluetooth service connected
,08-09 14:33:31.046  3438  3438 D BluetoothPan: BluetoothPAN Proxy object connected
,08-09 14:33:31.046  3438  3438 D PanProfile: Bluetooth service connected
,08-09 14:33:31.047  3438  3438 D BluetoothMap: Proxy object connected
08-09 14:33:31.047  3438  3438 D MapProfile: Bluetooth service connected
,08-09 14:33:31.047  3438  3438 D BluetoothMap: getConnectedDevices()
,08-09 14:33:31.050  3438  3438 D BluetoothPbap: Proxy object connected
,08-09 14:33:31.050  3438  3438 D PbapServerProfile: Bluetooth service connected
,08-09 14:33:31.052   870  1737 I ActivityManager: Killing 2999:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-09 14:33:31.104  3438  3450 D BluetoothHeadset: Proxy object connected
,08-09 14:33:31.105  3438  3438 D HeadsetProfile: Bluetooth service connected
,08-09 14:33:31.219  3460  3475 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-09 14:33:31.235   870   887 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9f61148:true
,08-09 14:33:32.094   870  1389 D WifiService: setWifiEnabled: true pid=3322, uid=10000
,08-09 14:33:32.095   870  1389 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-09 14:33:32.109   870  1312 D WifiConfigStore: Loading config and enabling all networks 
,08-09 14:33:32.126  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:32.126  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:32.126  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 14:33:32.126  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:32.126  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:32.126  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:32.126  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:32.126  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 14:33:32.132  3322  3322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-09 14:33:32.139  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:32.139  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:32.139  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 14:33:32.139  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:32.139  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:32.139  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:32.139  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:32.139  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 14:33:32.142  3322  3322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-09 14:33:32.149   870  1312 D WifiConfigStore: loaded 0 passpoint configs
,08-09 14:33:32.150   870  1312 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-09 14:33:32.150   870  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-09 14:33:32.151   870  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-09 14:33:32.151   870  1312 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
,08-09 14:33:32.152   870  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-09 14:33:32.153   870  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 3
,08-09 14:33:32.153   870  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-09 14:33:32.153   870  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-09 14:33:32.153   870  1312 E WifiConfigStore: found sortedWifiConfigurations : "ktwtestwifi"WPA_EAP
08-09 14:33:32.156  1462  1462 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-09 14:33:32.240   371   868 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-09 14:33:32.242   371   868 D CommandListener: Setting iface cfg
,08-09 14:33:32.244   870  1311 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '36 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 36 Failed to set address (No such device)'
,08-09 14:33:32.244   870  1311 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-09 14:33:32.253   870  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-09 14:33:32.262   870  1311 D WifiNative-HAL: p2pGetDeviceAddress
,08-09 14:33:32.264   870  1311 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-09 14:33:32.265   870  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-09 14:33:32.627  1462  1462 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-09 14:33:32.670  1462  1462 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-09 14:33:32.670  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-09 14:33:32.676   870  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-09 14:33:32.698   870  1312 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-09 14:33:32.699   870  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-09 14:33:32.699   870  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-09 14:33:32.727   870  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-09 14:33:32.747   371   868 D CommandListener: Setting iface cfg
,08-09 14:33:32.762   870  1312 D WifiStateMachine: Start Dhcp Watchdog 1
,08-09 14:33:32.784   870  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-09 14:33:32.785   870  1314 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,08-09 14:33:32.785   870  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-09 14:33:32.791   870  3505 D DhcpClient: Receive thread started
,08-09 14:33:32.876   870  1312 E native  : do suspend false
,08-09 14:33:32.898   870  3504 D DhcpClient: Broadcasting DHCPDISCOVER
,08-09 14:33:32.923   870  3505 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 168005, domain null
,08-09 14:33:32.925   870  3504 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 168005 seconds
,08-09 14:33:32.929   870  3504 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-09 14:33:32.944   870  3505 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-09 14:33:32.946   870  3504 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-09 14:33:32.951   371   868 D CommandListener: Setting iface cfg
,08-09 14:33:32.962   870  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-09 14:33:32.962   870  3504 D DhcpClient: Scheduling renewal in 86399s
,08-09 14:33:32.977   870  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-09 14:33:32.982   870  1312 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-09 14:33:32.984   870  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-09 14:33:32.989   870  1314 D ConnectivityService: Adding iface wlan0 to network 100
,08-09 14:33:33.000   870  1312 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-09 14:33:33.034   870  1314 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-09 14:33:33.035   870  1314 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,08-09 14:33:33.039   870  1314 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,08-09 14:33:33.039   870  1314 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,08-09 14:33:33.040   870  1314 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,08-09 14:33:33.047   870  1314 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-09 14:33:33.054   870  1314 D ConnectivityService: scheduleUnvalidatedPrompt 100
,08-09 14:33:33.054   870  1314 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
,08-09 14:33:33.054   870  1312 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-09 14:33:33.054   870  1314 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
,08-09 14:33:33.055   870  1314 D ConnectivityService:    accepting network in place of null
08-09 14:33:33.055   870  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-09 14:33:33.056   870  1314 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} },
,08-09 14:33:33.062   870  3503 D NetlinkSocketObserver: NeighborEvent{elapsedMs=120192, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 14:33:33.094   371   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-09 14:33:33.132   371   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-09 14:33:33.133   870  3502 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.201.238,2a00:1450:4001:814::200e
,08-09 14:33:33.135   870  1314 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,08-09 14:33:33.141   870  1314 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-09 14:33:33.144   870  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:33.146   870  1314 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
08-09 14:33:33.147   870   887 D Tethering: MasterInitialState.processMessage what=3
,08-09 14:33:33.158   870  1823 V BackupManagerService: Scheduling immediate backup pass
,08-09 14:33:33.160   870   870 V BackupManagerService: Running a backup pass
08-09 14:33:33.161  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:33.161  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:33.161  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 14:33:33.161  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:33.161  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:33.161  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:33.161  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 14:33:33.161  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 14:33:33.161   870  1333 V BackupManagerService: clearing pending backups
,08-09 14:33:33.163  3322  3322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-09 14:33:33.165   870  1333 V PerformBackupTask: Beginning backup of 16 targets
,08-09 14:33:33.167  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:33.167  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:33.167  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 14:33:33.167  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 14:33:33.167  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:33.167  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 14:33:33.167  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 14:33:33.167  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 14:33:33.170  3322  3322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-09 14:33:33.178  1801  1801 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-09 14:33:33.194   870  1333 D PerformBackupTask: invokeAgentForBackup on @pm@
,08-09 14:33:33.198   870  1333 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
,08-09 14:33:33.202  1905  1905 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-09 14:33:33.205   870  1709 D AlarmManagerService: Setting time of day to sec=1470746013
,08-09 14:33:33.036   870  1709 W AlarmManagerService: Unable to set rtc to 1470746013: Invalid argument
,08-09 14:33:33.040  1905  1905 D SystemUpdateService: onCreate
,08-09 14:33:33.043   870  3502 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Aug 2016 12:33:33 GMT], X-Android-Received-Millis=[1470746013042], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470746013187]}
,08-09 14:33:33.048   870  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-09 14:33:33.048   870  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
08-09 14:33:33.049   870  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-09 14:33:33.049   870  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-09 14:33:33.050  1905  1905 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-09 14:33:33.054  1905  3521 I SystemUpdateService: active receiver: enabled
,08-09 14:33:33.060  1905  3521 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-09 14:33:33.061  1905  3521 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-09 14:33:33.061  1905  3521 I SystemUpdateService: now status is 0 (complete)
08-09 14:33:33.062  1905  3521 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-09 14:33:33.062  1905  3521 I SystemUpdateService: file has been verified
08-09 14:33:33.062  1905  3521 I SystemUpdateService: OTA package size = 12249756
08-09 14:33:33.062   870  1333 I BackupRestoreController: Getting widget state for user: 0
08-09 14:33:33.066  1905  3521 I SystemUpdateService: showing system update notification
,08-09 14:33:33.070   870  1756 I ActivityManager: Start proc 3525:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-09 14:33:33.100  3525  3525 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-09 14:33:33.104   870  3539 D GpsLocationProvider: NTP server returned: 1470746013037 (Tue Aug 09 14:33:33 GMT+02:00 2016) reference: 120337 certainty: 8 system time offset: -66
,08-09 14:33:33.104   870  3539 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
08-09 14:33:33.112  1905  1905 D SystemUpdateService: onDestroy
,08-09 14:33:33.131  1905  3548 I iu.SyncManager: SYNC; picasa accounts
,08-09 14:33:33.143  3389  3519 V GoogleAuthProtoRequest: [282] a.<init>: mAccountName set to: thalitester@gmail.com
,08-09 14:33:33.148  1905  1905 D NetworkLogImpl: Loaded NetworkSpeedPredictor
08-09 14:33:33.149  1939  2095 W GmsBackupTransport: Unknown package in backup request: @pm@
08-09 14:33:33.149  1905  1905 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-09 14:33:33.159  1939  2095 V GmsBackupTransport: starting performBackup for @pm@
,08-09 14:33:33.162  1905  1905 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-09 14:33:33.162  1905  3547 I MDM     : [185] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-09 14:33:33.162  1905  3547 W BaseAppContext: Using Auth Proxy for data requests.
08-09 14:33:33.163  1905  1905 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-09 14:33:33.170  1905  3548 I iu.UploadsManager: num queued entries: 0
08-09 14:33:33.170  1905  3548 I iu.UploadsManager: num updated entries: 0
08-09 14:33:33.171  1905  3548 I iu.SyncManager: NEXT; no task
,08-09 14:33:33.172  1939  2095 V GmsBackupTransport: performBackup done for @pm@
,08-09 14:33:33.173  3525  3546 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-09 14:33:33.175   870  1757 I ActivityManager: Start proc 3555:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-09 14:33:33.182  1905  3547 V GoogleAuthProtoRequest: [185] a.<init>: mAccountName set to: thalitester@gmail.com
,08-09 14:33:33.197  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:33:33.215  3555  3555 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-09 14:33:33.218  3555  3555 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-09 14:33:33.221  1515  1983 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
,08-09 14:33:33.222  1515  1983 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
,08-09 14:33:33.222  1515  1983 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 14:33:33.222  1515  1983 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 14:33:33.225  3525  3546 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-09 14:33:33.228  3555  3555 D SprintDMHelper: simOperator: 
08-09 14:33:33.228  3555  3555 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-09 14:33:33.239   870  1824 I ActivityManager: Start proc 3569:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
08-09 14:33:33.256  1515  1983 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-09 14:33:33.256  1515  1983 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-09 14:33:33.256  1515  1983 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-09 14:33:33.256  1515  1983 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-09 14:33:33.256  1515  1983 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-09 14:33:33.256  1515  1983 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-09 14:33:33.256  1515  1983 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-09 14:33:33.266  3525  3546 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-09 14:33:33.266  1939  1962 W GmsBackupTransport: Error sending final backup to server: 
08-09 14:33:33.266  1939  1962 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
08-09 14:33:33.266  1939  1962 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
08-09 14:33:33.266  1939  1962 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
08-09 14:33:33.266  1939  1962 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
08-09 14:33:33.266  1939  1962 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
08-09 14:33:33.266  1939  1962 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
08-09 14:33:33.266  1939  1962 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
08-09 14:33:33.266  1939  1962 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-09 14:33:33.266  1939  1962 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-09 14:33:33.266  1939  1962 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-09 14:33:33.266  1939  1962 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-09 14:33:33.266  1939  1962 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-09 14:33:33.266  1939  1962 W GmsBackupTransport: 	... 1 more
,08-09 14:33:33.273  1939  2095 I GmsBackupTransport: Next backup will happen in 43199990 millis.
08-09 14:33:33.274   870  1333 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
,08-09 14:33:33.280  1515  2043 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-09 14:33:33.280  1515  2043 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-09 14:33:33.280  1515  2043 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 14:33:33.280  1515  2043 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 14:33:33.304  3389  3519 W ExperimentUpdateService: [282] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-09 14:33:33.304  3389  3519 W ExperimentUpdateService: [282] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-09 14:33:33.304  3389  3519 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-09 14:33:33.304  3389  3519 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-09 14:33:33.304  3389  3519 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-09 14:33:33.304  3389  3519 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-09 14:33:33.304  3389  3519 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-09 14:33:33.304  3389  3519 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-09 14:33:33.304  3389  3519 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-09 14:33:33.304  3389  3519 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-09 14:33:33.304  3389  3519 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-09 14:33:33.304  3389  3519 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-09 14:33:33.323  1905  3545 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,08-09 14:33:33.344  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-09 14:33:33.344  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-09 14:33:33.346  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 14:33:33.347  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 14:33:33.376  1905  1905 E ConnectivityChangeReceiver: Ignoring connectivity change
,08-09 14:33:33.395  1905  3547 E MDM     : [185] SitrepService.a: Error sending sitrep.
,08-09 14:33:33.398   870  1680 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1905 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-09 14:33:33.408  3525  3525 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-09 14:33:33.414   870  1333 I BackupManagerService: Backup pass finished.
,08-09 14:33:33.491   870  1757 I ActivityManager: Start proc 3621:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-09 14:33:33.517  3596  3596 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads121557418.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads121557418.dex
,08-09 14:33:33.556  3525  3525 W InstanceID/Rpc: Found 10011
,08-09 14:33:33.571  3525  3651 W YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1035 Unknown task tag innertube_config_fetch_charging; aborting...
,08-09 14:33:33.586  3621  3621 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-09 14:33:33.596   870   882 I ActivityManager: Start proc 3662:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-09 14:33:33.629  3596  3596 I dex2oat : dex2oat took 120.229ms (threads: 4) arena alloc=319KB java alloc=29KB native alloc=1514KB free=1557KB
,08-09 14:33:33.633  3662  3662 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-09 14:33:33.634  2358  3619 I Babel   : connection state changed from DISCONNECTED to CONNECTED
08-09 14:33:33.636   870  1756 I ActivityManager: Killing 2466:com.android.providers.calendar/u0a3 (adj 15): empty #17
08-09 14:33:33.637  1905  3552 W DriveInitializer: Awaiting to be initialized
08-09 14:33:33.638  1905  3680 W DriveInitializer: Background init thread started
,08-09 14:33:33.692  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-09 14:33:33.692  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-09 14:33:33.693  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 14:33:33.693  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 14:33:33.724  3131  3591 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-09 14:33:33.724  3131  3591 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-09 14:33:33.724  3131  3591 E HttpOperation: 	at jdm.a(PG:82)
08-09 14:33:33.724  3131  3591 E HttpOperation: 	at jcs.o(PG:406)
08-09 14:33:33.724  3131  3591 E HttpOperation: 	at jcn.a(PG:1379)
08-09 14:33:33.724  3131  3591 E HttpOperation: 	at jcs.i(PG:143)
08-09 14:33:33.724  3131  3591 E HttpOperation: 	at blb.a(PG:3937)
08-09 14:33:33.724  3131  3591 E HttpOperation: 	at czp.a(PG:18188)
08-09 14:33:33.724  3131  3591 E HttpOperation: 	at czp.a(PG:9081)
08-09 14:33:33.724  3131  3591 E HttpOperation: 	at czq.run(PG:1686)
08-09 14:33:33.724  3131  3591 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 14:33:33.724  3131  3591 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 14:33:33.724  3131  3591 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 14:33:33.724  3131  3591 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 14:33:33.724  3131  3591 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-09 14:33:33.724  3131  3591 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 14:33:33.724  3131  3591 E HttpOperation: 	at jdj.a(PG:4091)
08-09 14:33:33.724  3131  3591 E HttpOperation: 	at jdj.a(PG:1125)
08-09 14:33:33.724  3131  3591 E HttpOperation: 	at jdm.a(PG:77)
08-09 14:33:33.724  3131  3591 E HttpOperation: 	... 12 more
08-09 14:33:33.724  3131  3591 E HttpOperation: Caused by: faj: BadAuthentication
08-09 14:33:33.724  3131  3591 E HttpOperation: 	at fal.a(PG:38)
08-09 14:33:33.724  3131  3591 E HttpOperation: 	at jdj.a(PG:4089)
08-09 14:33:33.724  3131  3591 E HttpOperation: 	... 14 more
,08-09 14:33:33.784  1905  3680 W DriveInitializer: Background init thread ended
,08-09 14:33:33.806  1515  3579 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-09 14:33:33.806  1515  3579 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-09 14:33:33.806  1515  3579 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 14:33:33.806  1515  3579 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 14:33:33.823  3131  3591 E HttpOperation: [getmobileexperiments] Unexpected exception
08-09 14:33:33.823  3131  3591 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-09 14:33:33.823  3131  3591 E HttpOperation: 	at jdm.a(PG:82)
08-09 14:33:33.823  3131  3591 E HttpOperation: 	at jcs.o(PG:406)
08-09 14:33:33.823  3131  3591 E HttpOperation: 	at jcn.a(PG:1379)
08-09 14:33:33.823  3131  3591 E HttpOperation: 	at jcs.i(PG:143)
08-09 14:33:33.823  3131  3591 E HttpOperation: 	at hec.a(PG:42)
08-09 14:33:33.823  3131  3591 E HttpOperation: 	at hee.a(PG:102)
08-09 14:33:33.823  3131  3591 E HttpOperation: 	at czr.a(PG:65)
08-09 14:33:33.823  3131  3591 E HttpOperation: 	at kka.a(PG:108)
08-09 14:33:33.823  3131  3591 E HttpOperation: 	at czp.a(PG:19176)
08-09 14:33:33.823  3131  3591 E HttpOperation: 	at czp.a(PG:9081)
08-09 14:33:33.823  3131  3591 E HttpOperation: 	at czq.run(PG:1686)
08-09 14:33:33.823  3131  3591 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 14:33:33.823  3131  3591 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 14:33:33.823  3131  3591 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 14:33:33.823  3131  3591 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 14:33:33.823  3131  3591 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-09 14:33:33.823  3131  3591 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 14:33:33.823  3131  3591 E HttpOperation: 	at jdj.a(PG:4091)
08-09 14:33:33.823  3131  3591 E HttpOperation: 	at jdj.a(PG:1125)
08-09 14:33:33.823  3131  3591 E HttpOperation: 	at jdm.a(PG:77)
08-09 14:33:33.823  3131  3591 E HttpOperation: 	... 15 more
08-09 14:33:33.823  3131  3591 E HttpOperation: Caused by: faj: BadAuthentication
08-09 14:33:33.823  3131  3591 E HttpOperation: 	at fal.a(PG:38)
08-09 14:33:33.823  3131  3591 E HttpOperation: 	at jdj.a(PG:4089)
08-09 14:33:33.823  3131  3591 E HttpOperation: 	... 17 more
,08-09 14:33:33.824  3131  3591 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-09 14:33:33.824  3131  3591 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-09 14:33:33.824  3131  3591 E ExperimentLoader: 	at jdm.a(PG:82)
08-09 14:33:33.824  3131  3591 E ExperimentLoader: 	at jcs.o(PG:406)
08-09 14:33:33.824  3131  3591 E ExperimentLoader: 	at jcn.a(PG:1379)
08-09 14:33:33.824  3131  3591 E ExperimentLoader: 	at jcs.i(PG:143)
08-09 14:33:33.824  3131  3591 E ExperimentLoader: 	at hec.a(PG:42)
08-09 14:33:33.824  3131  3591 E ExperimentLoader: 	at hee.a(PG:102)
08-09 14:33:33.824  3131  3591 E ExperimentLoader: 	at czr.a(PG:65)
08-09 14:33:33.824  3131  3591 E ExperimentLoader: 	at kka.a(PG:108)
08-09 14:33:33.824  3131  3591 E ExperimentLoader: 	at czp.a(PG:19176)
08-09 14:33:33.824  3131  3591 E ExperimentLoader: 	at czp.a(PG:9081)
08-09 14:33:33.824  3131  3591 E ExperimentLoader: 	at czq.run(PG:1686)
08-09 14:33:33.824  3131  3591 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 14:33:33.824  3131  3591 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 14:33:33.824  3131  3591 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 14:33:33.824  3131  3591 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 14:33:33.824  3131  3591 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-09 14:33:33.824  3131  3591 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 14:33:33.824  3131  3591 E ExperimentLoader: 	at jdj.a(PG:4091)
08-09 14:33:33.824  3131  3591 E ExperimentLoader: 	at jdj.a(PG:1125)
08-09 14:33:33.824  3131  3591 E ExperimentLoader: 	at jdm.a(PG:77)
08-09 14:33:33.824  3131  3591 E ExperimentLoader: 	... 15 more
08-09 14:33:33.824  3131  3591 E ExperimentLoader: Caused by: faj: BadAuthentication
08-09 14:33:33.824  3131  3591 E ExperimentLoader: 	at fal.a(PG:38)
08-09 14:33:33.824  3131  3591 E ExperimentLoader: 	at jdj.a(PG:4089)
08-09 14:33:33.824  3131  3591 E ExperimentLoader: 	... 17 more
,08-09 14:33:33.871  3662  3662 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-09 14:33:33.878  3662  3662 I BooksApp: Created application version: 3.6.9 (30609)
,08-09 14:33:33.938   870  1823 I ActivityManager: Killing 3111:android.process.acore/u0a5 (adj 15): empty #17
,08-09 14:33:33.940   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 24167, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-09 14:33:34.009  3662  3704 I BooksSync: Starting books sync for 61035162, extras: ade
,08-09 14:33:34.073  3621  3621 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-09 14:33:34.073  3621  3621 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-09 14:33:34.073  3621  3621 I GAv4    :   adb logcat -s GAv4
,08-09 14:33:34.082  3621  3621 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-09 14:33:34.088  3621  3621 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-09 14:33:34.120  3621  3712 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-09 14:33:34.161  2850  3707 V KeepSync: Connecting to GoogleApiClient
,08-09 14:33:34.162   870  1680 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-09 14:33:34.326  1515  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-09 14:33:34.327  1515  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-09 14:33:34.327  1515  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 14:33:34.327  1515  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 14:33:34.327  3621  3621 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-09 14:33:34.368  1905  3726 V BaseAuthAsyncOperation: access token request failed
,08-09 14:33:34.379  2850  3707 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-09 14:33:34.385  3621  3621 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-09 14:33:34.398  3621  3621 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1696-1699)
,08-09 14:33:34.398  3621  3621 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-09 14:33:34.421  3621  3621 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ec4885f}
,08-09 14:33:34.422  3621  3621 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-09 14:33:34.423  3621  3621 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-09 14:33:34.430  3621  3621 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-09 14:33:34.439  3621  3621 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-09 14:33:34.463  3621  3621 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-09 14:33:34.505  3621  3621 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-09 14:33:34.506  3621  3621 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-09 14:33:34.506  3621  3621 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-09 14:33:34.506  3621  3621 I Adreno  : Build Date                       : 10/20/15
08-09 14:33:34.506  3621  3621 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-09 14:33:34.506  3621  3621 I Adreno  : Local Branch                     : M14
08-09 14:33:34.506  3621  3621 I Adreno  : Remote Branch                    : 
08-09 14:33:34.506  3621  3621 I Adreno  : Remote Branch                    : 
08-09 14:33:34.506  3621  3621 I Adreno  : Reconstruct Branch               : 
,08-09 14:33:34.555  3662  3739 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-09 14:33:34.629  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-09 14:33:34.629  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-09 14:33:34.630  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 14:33:34.630  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 14:33:34.634  3621  3747 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-09 14:33:34.635  3621  3621 I NSApplication: Starting up...
,08-09 14:33:34.658   870   881 I ActivityManager: Start proc 3752:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-09 14:33:34.695  1515  3581 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-09 14:33:34.696  1515  3581 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-09 14:33:34.696  1515  3581 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 14:33:34.696  1515  3581 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 14:33:34.714  3662  3739 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-09 14:33:34.716  3662  3704 E BooksSync: Soft error
08-09 14:33:34.716  3662  3704 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-09 14:33:34.716  3662  3704 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-09 14:33:34.716  3662  3704 E BooksSync: Sync error
08-09 14:33:34.716  3662  3704 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-09 14:33:34.716  3662  3704 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-09 14:33:34.716  3662  3704 I BooksSync: Finished books sync
08-09 14:33:34.720   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 24175, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-09 14:33:34.722   870  1756 I ActivityManager: Killing 3217:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-09 14:33:34.730  3752  3752 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-09 14:33:34.790  1515  1983 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-09 14:33:34.791  1515  1983 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-09 14:33:34.791  1515  1983 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 14:33:34.791  1515  1983 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 14:33:34.810  2850  3707 E KeepSync: IOException
08-09 14:33:34.810  2850  3707 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-09 14:33:34.810  2850  3707 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-09 14:33:34.810  2850  3707 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-09 14:33:34.810  2850  3707 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-09 14:33:34.810  2850  3707 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-09 14:33:34.810  2850  3707 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-09 14:33:34.810  2850  3707 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-09 14:33:34.810  2850  3707 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-09 14:33:34.810  2850  3707 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-09 14:33:34.810  2850  3707 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-09 14:33:34.810  2850  3707 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-09 14:33:34.810  2850  3707 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-09 14:33:34.810  2850  3707 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-09 14:33:34.810  2850  3707 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-09 14:33:34.810  2850  3707 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-09 14:33:34.810  2850  3707 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-09 14:33:34.810  2850  3707 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-09 14:33:34.810  2850  3707 E KeepSync: 	... 10 more
,08-09 14:33:34.811  2850  3707 W KeepSync: Sync result 2
,08-09 14:33:34.814   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 24175, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-09 14:33:34.818   870  1680 I ActivityManager: Killing 3232:com.android.musicfx/u0a18 (adj 15): empty #17
,08-09 14:33:34.895  1905  3767 I PeopleSync: onPerformSync() [5005f081]
,08-09 14:33:34.921  1905  3769 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-09 14:33:34.931   870  1680 D WifiService: setWifiEnabled: false pid=3322, uid=10000
08-09 14:33:34.931   870  1680 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-09 14:33:34.933  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:33:34.952  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-09 14:33:34.955   870  1312 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-09 14:33:34.956   870  1312 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-09 14:33:34.956   870  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-09 14:33:34.956   870  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-09 14:33:34.962  1515  1983 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: mail
,08-09 14:33:34.962  1515  1983 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> mail without consulting the cloud.
08-09 14:33:34.962  1515  1983 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 14:33:34.962  1515  1983 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 14:33:34.963   870  3504 D DhcpClient: Clearing IP address
,08-09 14:33:34.963   371   868 D CommandListener: Clearing all IP addresses on wlan0
,08-09 14:33:34.966   371   868 D CommandListener: Setting iface cfg
,08-09 14:33:34.967  1515  3587 V NativeCrypto: Read error: ssl=0x9b2ff800: I/O error during system call, Connection timed out
08-09 14:33:34.968  1515  3587 V NativeCrypto: SSL shutdown failed: ssl=0x9b2ff800: I/O error during system call, Broken pipe
08-09 14:33:34.971   870  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-09 14:33:34.971   870  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-09 14:33:34.975   394   394 E Parcel  : Reading a NULL string not supported here.
,08-09 14:33:34.977   870  1312 D WifiStateMachine: Start Disconnecting Watchdog 1
08-09 14:33:34.978   870  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-09 14:33:34.984   870  1314 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-09 14:33:34.985   870  3505 D DhcpClient: Receive thread stopped
08-09 14:33:34.988   371   868 D CommandListener: Clearing all IP addresses on wlan0
08-09 14:33:34.997   870  1312 D WifiConfigStore: Retrieve network priorities after PNO.
08-09 14:33:35.000  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:35.000  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:35.000  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 14:33:35.000  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:35.000  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:35.000  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:35.000  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:35.000  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 14:33:35.002  3322  3322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 14:33:35.004  1939  2071 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 14:33:35.006  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:35.006  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:35.006  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 14:33:35.006  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:35.006  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:35.006  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:35.006  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:35.006  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 14:33:35.008  1515  1983 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-09 14:33:35.008  1515  1983 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-09 14:33:35.008  1515  1983 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-09 14:33:35.008  1515  1983 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-09 14:33:35.008  1515  1983 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-09 14:33:35.008  1515  1983 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-09 14:33:35.008  1515  1983 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
08-09 14:33:35.008  3322  3322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:35.010  1905  3769 W SubscribedFeeds: Hard error
08-09 14:33:35.011   870  1312 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-09 14:33:35.031  1905  3771 I PeopleDatabaseHelper: cleanUpNonGplusAccounts done.
,08-09 14:33:35.032   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 24214, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,08-09 14:33:35.033   870   882 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 154518, reason: Periodic
,08-09 14:33:35.038   371   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-09 14:33:35.059  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:33:35.063  1515  3777 I VacuumService: Vacuum at: now=1470746015063 tag=VacuumService
,08-09 14:33:35.065   371   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-09 14:33:35.066   870  1314 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-09 14:33:35.066   870  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:35.072  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:35.072   870   887 D Tethering: MasterInitialState.processMessage what=3
,08-09 14:33:35.073  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:35.082  1801  1801 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-09 14:33:35.113   371   868 E Netd    : netlink response contains error (No such file or directory)
,08-09 14:33:35.204  1905  3767 I PeopleSync: Setting subscription: result=true [5005f081]
,08-09 14:33:35.204  1905  3767 I PeopleSync: Starting sync, feed=null [5005f081]
,08-09 14:33:35.236  1905  3767 W BaseAppContext: Using Auth Proxy for data requests.
,08-09 14:33:35.239  1905  3767 W BaseAppContext: Using Auth Proxy for data requests.
,08-09 14:33:35.251  1905  3767 W BaseAppContext: Using Auth Proxy for data requests.
,08-09 14:33:35.257  1905  3767 I PeopleSync: Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,08-09 14:33:35.264   870   880 I ActivityManager: Killing 3033:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-09 14:33:35.343  2358  3794 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-09 14:33:35.344  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings
08-09 14:33:35.344  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings without consulting the cloud.
08-09 14:33:35.344  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 14:33:35.344  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 14:33:35.350  1905  1905 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-09 14:33:35.352  1905  1905 D SystemUpdateService: onCreate
,08-09 14:33:35.354  1905  1905 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-09 14:33:35.355  1905  3797 I SystemUpdateService: active receiver: enabled
,08-09 14:33:35.357  1905  3797 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-09 14:33:35.358  1905  3797 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-09 14:33:35.358  1905  3797 I SystemUpdateService: now status is 0 (complete)
08-09 14:33:35.358  1905  3797 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-09 14:33:35.358  1905  3797 I SystemUpdateService: file has been verified
,08-09 14:33:35.359  1905  3797 I SystemUpdateService: OTA package size = 12249756
,08-09 14:33:35.362  1905  3797 I SystemUpdateService: showing system update notification
,08-09 14:33:35.367  1905  1905 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-09 14:33:35.369  1905  3548 I iu.UploadsManager: num queued entries: 0
,08-09 14:33:35.369  1905  3548 I iu.UploadsManager: num updated entries: 0
,08-09 14:33:35.371  1905  1905 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-09 14:33:35.372  1905  1905 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-09 14:33:35.370  1905  3548 I iu.SyncManager: NEXT; no task
,08-09 14:33:35.374  3555  3555 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-09 14:33:35.375  1905  1905 D SystemUpdateService: onDestroy
,08-09 14:33:35.378  3555  3555 D SprintDMHelper: simOperator: 
,08-09 14:33:35.378  3555  3555 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-09 14:33:35.383  1905  3767 I PeopleSync: Sync finished, successful=false, took 118ms
,08-09 14:33:35.406  1905  3767 I PeopleSync: Cannot authenticate [5005f081]
08-09 14:33:35.406  1905  3767 I PeopleSync: com.google.android.gms.auth.ae: BadAuthentication
08-09 14:33:35.406  1905  3767 I PeopleSync: 	at com.google.android.gms.auth.p.b(SourceFile:480)
08-09 14:33:35.406  1905  3767 I PeopleSync: 	at com.google.android.gms.auth.p.a(SourceFile:397)
08-09 14:33:35.406  1905  3767 I PeopleSync: 	at com.google.android.gms.auth.p.a(SourceFile:342)
08-09 14:33:35.406  1905  3767 I PeopleSync: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
08-09 14:33:35.406  1905  3767 I PeopleSync: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
08-09 14:33:35.406  1905  3767 I PeopleSync: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
08-09 14:33:35.406  1905  3767 I PeopleSync: 	at com.google.android.gms.people.service.g.b(SourceFile:171)
08-09 14:33:35.406  1905  3767 I PeopleSync: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
08-09 14:33:35.406  1905  3767 I PeopleSync: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
08-09 14:33:35.406  1905  3767 I PeopleSync: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
08-09 14:33:35.406  1905  3767 I PeopleSync: 	at com.google.android.gms.plus.service.v2whitelisted.b.a(SourceFile:1190)
08-09 14:33:35.406  1905  3767 I PeopleSync: 	at com.google.android.gms.people.sync.aa.g(SourceFile:1085)
08-09 14:33:35.406  1905  3767 I PeopleSync: 	at com.google.android.gms.people.sync.aa.a(SourceFile:240)
08-09 14:33:35.406  1905  3767 I PeopleSync: 	at com.google.android.gms.people.sync.s.a(SourceFile:274)
08-09 14:33:35.406  1905  3767 I PeopleSync: 	at com.google.android.gms.people.sync.s.a(SourceFile:189)
08-09 14:33:35.406  1905  3767 I PeopleSync: 	at com.google.android.gms.people.sync.s.a(SourceFile:91)
08-09 14:33:35.406  1905  3767 I PeopleSync: 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:98)
08-09 14:33:35.406  1905  3767 I PeopleSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
,08-09 14:33:35.427  1905  3767 I PeopleSync: ***Sync finished***, duration: 531 [5005f081]
,08-09 14:33:35.436   870   882 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 24214, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,08-09 14:33:35.437   870   882 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 154908, reason: Periodic
,08-09 14:33:35.471  1905  1905 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-09 14:33:35.471  1905  1905 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-09 14:33:35.476  1905  1905 W PlaySystemBroadcastReceiver: Processed handlePeopleChanged at 122773
,08-09 14:33:35.480  1905  1905 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-09 14:33:35.480  1905  1905 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-09 14:33:35.483  1905  3802 W DataBroker: No player ID found and calling context is not the dest app
,08-09 14:33:37.946  3377  3419 D BluetoothAdapterState: Current state: ON, message: 23
,08-09 14:33:37.947  3377  3419 D BluetoothAdapterProperties: Setting state to 13
,08-09 14:33:37.947  3377  3419 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-09 14:33:37.949  3377  3419 D BluetoothAdapterProperties: onBluetoothDisable()
,08-09 14:33:37.956  3377  3419 I BluetoothAdapterState: Entering PendingCommandState
,08-09 14:33:37.960  3377  3377 D BluetoothMapService: onReceive
08-09 14:33:37.961  3377  3377 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:37.961  3377  3377 D BluetoothMapService: STATE_TURNING_OFF
08-09 14:33:37.962  3377  3377 D BluetoothMapService: MAP Service closeService in
,08-09 14:33:37.962  3377  3377 D BluetoothMapMasInstance0: MAP Service shutdown
08-09 14:33:37.963  3377  3377 D ObexServerSockets0: shutdown(block = true)
,08-09 14:33:37.968  3377  3377 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-09 14:33:37.968  3377  3377 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-09 14:33:37.969  3377  3458 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-09 14:33:37.969  3322  3322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:37.969  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:37.969  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:37.969  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 14:33:37.969  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:37.969  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:37.969  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:37.969  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:37.969  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 14:33:37.969  3377  3433 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-09 14:33:37.969  3377  3459 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-09 14:33:37.970  3322  3322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:37.970  3377  3377 I BtOppRfcommListener: stopping Accept Thread
08-09 14:33:37.970  3322  3322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:37.971  3377  3493 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 14:33:37.971  3377  3493 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-09 14:33:37.979  3322  3322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 14:33:37.979  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:37.979  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:37.979  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 14:33:37.979  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:37.979  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:37.979  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:37.979  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:37.979  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 14:33:37.980  3322  3322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:37.980  3322  3322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 14:33:37.982  3377  3423 D BluetoothAdapterProperties: Scan Mode:20
,08-09 14:33:37.983  3377  3419 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-09 14:33:37.987  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:37.987  3377  3377 D HeadsetService: Received stop request...Stopping profile...
08-09 14:33:37.988  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:37.989  3377  3377 V BluetoothAdapterState: isTurningOff()=true
08-09 14:33:37.989  3377  3377 V BluetoothAdapterState: isTurningOn()=false
,08-09 14:33:37.989  3377  3377 V BluetoothAdapterState: isBleTurningOn()=false
08-09 14:33:37.989  1738  1753 D BluetoothHeadset: Proxy object disconnected
08-09 14:33:37.989  3377  3377 V BluetoothAdapterState: isBleTurningOff()=false
08-09 14:33:37.989  1370  1381 D BluetoothHeadset: Proxy object disconnected
08-09 14:33:37.990   870   870 D BluetoothHeadset: Proxy object disconnected
,08-09 14:33:37.990  3438  3449 D BluetoothHeadset: Proxy object disconnected
08-09 14:33:37.990   870   870 D BluetoothHeadset: Proxy object disconnected
08-09 14:33:37.990   870   870 D BluetoothHeadset: Proxy object disconnected
08-09 14:33:37.991  3377  3377 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-09 14:33:37.991  3377  3377 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-09 14:33:37.991  3377  3423 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-09 14:33:37.991  3377  3430 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 14:33:37.991  3377  3430 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-09 14:33:37.991  3377  3430 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 14:33:37.991  3377  3423 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-09 14:33:37.993  3377  3377 D A2dpService: Received stop request...Stopping profile...
08-09 14:33:37.993  1370  1370 D HeadsetProfile: Bluetooth service disconnected
,08-09 14:33:37.993  3377  3451 D A2dpStateMachine: Exit Disconnected: -1
08-09 14:33:37.986  3438  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-09 14:33:37.999  1370  1370 D BluetoothA2dp: Proxy object disconnected
,08-09 14:33:38.000   870   870 D BluetoothA2dp: Proxy object disconnected
08-09 14:33:38.001  3377  3377 D HidService: Received stop request...Stopping profile...
08-09 14:33:38.001  3377  3377 D HidService: Stopping Bluetooth HidService
08-09 14:33:38.003  1370  1370 D BluetoothInputDevice: Proxy object disconnected
08-09 14:33:38.003  1370  1370 D HidProfile: Bluetooth service disconnected
08-09 14:33:38.005  3377  3377 D HealthService: Received stop request...Stopping profile...
08-09 14:33:38.005  3438  3438 D HeadsetProfile: Bluetooth service disconnected
08-09 14:33:38.007  3377  3377 D PanService: Received stop request...Stopping profile...
,08-09 14:33:38.009  3377  3377 D BluetoothMapService: Received stop request...Stopping profile...
08-09 14:33:38.009  3377  3377 D BluetoothMapService: stop()
08-09 14:33:38.009  1370  1370 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-09 14:33:38.009  1370  1370 D PanProfile: Bluetooth service disconnected
08-09 14:33:38.009  3377  3377 D BluetoothMapAppObserver: deinitObservers()
08-09 14:33:38.010  3377  3377 D BluetoothMapAppObserver: removeReceiver()
,08-09 14:33:38.011  3377  3377 V BluetoothAdapterState: isTurningOff()=true
,08-09 14:33:38.011  3377  3377 V BluetoothAdapterState: isTurningOn()=false
08-09 14:33:38.011  1370  1370 D BluetoothMap: Proxy object disconnected
08-09 14:33:38.011  3377  3377 V BluetoothAdapterState: isBleTurningOn()=false
08-09 14:33:38.011  3377  3377 V BluetoothAdapterState: isBleTurningOff()=false
08-09 14:33:38.011  1370  1370 D MapProfile: Bluetooth service disconnected
,08-09 14:33:38.012  3377  3423 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-09 14:33:38.012  3377  3430 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 14:33:38.013  3377  3430 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 14:33:38.013  3377  3430 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 14:33:38.013  3377  3430 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-09 14:33:38.013  3377  3430 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 14:33:38.013  3377  3430 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 14:33:38.012  3377  3377 V BluetoothAdapterState: isTurningOff()=true
08-09 14:33:38.013  3377  3377 V BluetoothAdapterState: isTurningOn()=false
08-09 14:33:38.013  3377  3377 V BluetoothAdapterState: isBleTurningOn()=false
08-09 14:33:38.013  3377  3377 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 14:33:38.014  3377  3377 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-09 14:33:38.014  3377  3423 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-09 14:33:38.014  3377  3377 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-09 14:33:38.018  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 14:33:38.018  3377  3377 V BluetoothAdapterState: isTurningOff()=true
,08-09 14:33:38.020  3377  3377 V BluetoothAdapterState: isTurningOn()=false
,08-09 14:33:38.020  3377  3377 V BluetoothAdapterState: isBleTurningOn()=false
08-09 14:33:38.020  3377  3377 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 14:33:38.020  3377  3377 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-09 14:33:38.022  3377  3377 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-09 14:33:38.022  3377  3377 V BluetoothAdapterState: isTurningOff()=true
,08-09 14:33:38.022  3377  3377 V BluetoothAdapterState: isTurningOn()=false
,08-09 14:33:38.022  3377  3377 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 14:33:38.023  3377  3377 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 14:33:38.023  3377  3377 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-09 14:33:38.023  3377  3423 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-09 14:33:38.023  3377  3377 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-09 14:33:38.024  3377  3377 D BluetoothMapService: MAP Service closeService in
08-09 14:33:38.024  3377  3377 V BluetoothAdapterState: isTurningOff()=true
08-09 14:33:38.024  3377  3377 V BluetoothAdapterState: isTurningOn()=false
,08-09 14:33:38.024  3377  3377 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 14:33:38.024  3377  3377 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 14:33:38.024  3377  3377 D BluetoothMapService: cleanup()
08-09 14:33:38.024  3377  3377 D BluetoothMapService: MAP Service closeService in
08-09 14:33:38.025  3377  3419 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-09 14:33:38.025  3377  3419 D BluetoothAdapterProperties: Setting state to 15
,08-09 14:33:38.025  3377  3419 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-09 14:33:38.026  3377  3419 I BluetoothAdapterState: Entering BleOnState
08-09 14:33:38.028  3438  3438 D DockEventReceiver: finishStartingService: stopping service
08-09 14:33:38.028  3438  3449 D BluetoothA2dp: onBluetoothStateChange: up=false,
08-09 14:33:38.029  3438  3438 D BluetoothInputDevice: Proxy object disconnected
08-09 14:33:38.029  1370  1381 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-09 14:33:38.029  3438  3438 D HidProfile: Bluetooth service disconnected
08-09 14:33:38.029  3438  3438 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-09 14:33:38.029  3438  3438 D PanProfile: Bluetooth service disconnected
08-09 14:33:38.030  3438  3438 D BluetoothMap: Proxy object disconnected
08-09 14:33:38.030  3438  3449 D BluetoothPan: onBluetoothStateChange on: false
08-09 14:33:38.030  3438  3438 D MapProfile: Bluetooth service disconnected
08-09 14:33:38.031  1370  1840 D BluetoothMap: onBluetoothStateChange: up=false
08-09 14:33:38.031  3438  3438 D BluetoothPbap: Proxy object disconnected
08-09 14:33:38.031  3438  3438 D PbapServerProfile: Bluetooth service disconnected
08-09 14:33:38.033   870   887 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 14:33:38.033   870   887 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 14:33:38.033   870   887 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 14:33:38.034  3438  3450 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-09 14:33:38.036   870   887 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 14:33:38.036  1370  1842 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 14:33:38.037  1370  1382 D BluetoothPan: onBluetoothStateChange on: false
08-09 14:33:38.038  1370  1381 D BluetoothPbap: onBluetoothStateChange: up=false
08-09 14:33:38.038  3438  3449 D BluetoothMap: onBluetoothStateChange: up=false
08-09 14:33:38.039  1370  1840 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 14:33:38.039  3438  3450 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 14:33:38.039  1738  1754 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 14:33:38.041  3438  3449 D BluetoothPbap: onBluetoothStateChange: up=false
,08-09 14:33:38.045  3377  3419 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-09 14:33:38.049  3377  3419 D BluetoothAdapterProperties: Setting state to 16
08-09 14:33:38.049  3377  3419 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-09 14:33:38.049  3438  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-09 14:33:38.049  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:38.050  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:38.052  3377  3419 D BluetoothAdapterProperties: onBleDisable
08-09 14:33:38.052  3377  3419 I BluetoothAdapterState: Entering PendingCommandState
,08-09 14:33:38.053  3377  3420 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-09 14:33:38.054  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 14:33:38.054  3377  3423 D BluetoothAdapterProperties: Scan Mode:20
,08-09 14:33:38.055  3377  3430 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-09 14:33:38.055  3377  3430 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 14:33:38.055  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:38.057  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-09 14:33:38.067  3438  3438 D DockEventReceiver: finishStartingService: stopping service
,08-09 14:33:38.257  3377  3423 I bt_hci  : shut_down
,08-09 14:33:38.270  3377  3427 D bt_hwcfg: hw_epilog_process
,08-09 14:33:38.270  3377  3427 I bt_vendor: low_power_mode_cb
,08-09 14:33:38.291  3377  3427 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-09 14:33:38.291  3377  3427 I bt_vendor: epilog_cb
,08-09 14:33:38.292  3377  3427 I bt_hci  : epilog_finished_callback
,08-09 14:33:38.301  3377  3423 I bt_hci_h4: hal_close
,08-09 14:33:38.302  3377  3423 I bt_userial_vendor: device fd = 51 close
,08-09 14:33:38.444  3377  3420 D bt_stack_manager: event_shut_down_stack finished.
,08-09 14:33:38.444  3377  3419 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-09 14:33:38.449  3377  3377 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-09 14:33:38.450  3377  3377 D BtGatt.GattService: Received stop request...Stopping profile...
,08-09 14:33:38.450  3377  3377 D BtGatt.GattService: stop()
,08-09 14:33:38.449  3377  3419 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-09 14:33:38.450  3377  3377 D BtGatt.AdvertiseManager: advertise clients cleared
08-09 14:33:38.452  3377  3377 V BluetoothAdapterState: isTurningOff()=false
,08-09 14:33:38.452  3377  3377 V BluetoothAdapterState: isTurningOn()=false
08-09 14:33:38.452  3377  3377 V BluetoothAdapterState: isBleTurningOn()=false
08-09 14:33:38.453  3377  3377 V BluetoothAdapterState: isBleTurningOff()=true
08-09 14:33:38.453  3377  3419 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-09 14:33:38.454  3377  3419 D BluetoothAdapterProperties: Setting state to 10
08-09 14:33:38.454  3377  3419 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-09 14:33:38.455  3377  3419 I BluetoothAdapterState: Entering OffState
08-09 14:33:38.457   870   887 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-09 14:33:38.470  3377  3377 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-09 14:33:38.470  3377  3377 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-09 14:33:38.470  3377  3420 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-09 14:33:38.472  3377  3420 D bt_stack_manager: event_clean_up_stack finished.
08-09 14:33:38.473  3377  3377 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-09 14:33:38.474  3377  3377 I art     : System.exit called, status: 0
,08-09 14:33:38.474  3377  3377 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-09 14:33:38.527   870  1389 I ActivityManager: Process com.android.bluetooth (pid 3377) has died,
,08-09 14:33:38.899  3662  3701 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-09 14:33:40.891   870  1314 D ConnectivityService: handlePromptUnvalidated 100
,08-09 14:33:40.996   870   887 I ActivityManager: Start proc 3819:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-09 14:33:41.117  3819  3819 D AdapterServiceConfig: Adding HeadsetService
08-09 14:33:41.117  3819  3819 D AdapterServiceConfig: Adding A2dpService
,08-09 14:33:41.118  3819  3819 D AdapterServiceConfig: Adding HidService
08-09 14:33:41.118  3819  3819 D AdapterServiceConfig: Adding HealthService
08-09 14:33:41.118  3819  3819 D AdapterServiceConfig: Adding PanService
08-09 14:33:41.118  3819  3819 D AdapterServiceConfig: Adding GattService
08-09 14:33:41.118  3819  3819 D AdapterServiceConfig: Adding BluetoothMapService
,08-09 14:33:41.149   870   887 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4c07be4:true
,08-09 14:33:41.149  3819  3819 D BluetoothAdapterState: make() - Creating AdapterState
,08-09 14:33:41.153  3819  3819 I bt_bluedroid: init
,08-09 14:33:41.156  3819  3831 I BluetoothAdapterState: Entering OffState
08-09 14:33:41.158  3819  3832 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-09 14:33:41.158  3819  3832 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-09 14:33:41.158  3819  3832 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-09 14:33:41.159  3819  3832 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-09 14:33:41.160  3819  3819 I bt_bluedroid: get_profile_interface socket
08-09 14:33:41.162  3819  3819 I bt_bluedroid: get_profile_interface sdp
,08-09 14:33:41.165  3819  3830 I bt_bluedroid: config_hci_snoop_log
08-09 14:33:41.168   870   887 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-09 14:33:41.174  3819  3835 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-09 14:33:41.178  3819  3835 D BluetoothAdapterProperties: Name is: Nexus 6
,08-09 14:33:41.183  3819  3831 D BluetoothAdapterState: Current state: OFF, message: 0
,08-09 14:33:41.183  3819  3831 D BluetoothAdapterProperties: Setting state to 14
08-09 14:33:41.183  3819  3831 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-09 14:33:41.186  3819  3831 D BluetoothBondStateMachine: make
,08-09 14:33:41.188  3819  3836 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-09 14:33:41.192  3819  3831 I BluetoothAdapterState: Entering PendingCommandState
,08-09 14:33:41.193  3819  3819 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-09 14:33:41.196  3819  3819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1062b7
,08-09 14:33:41.197  3819  3819 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-09 14:33:41.197  3819  3819 D BtGatt.GattService: Received start request. Starting profile...
08-09 14:33:41.197  3819  3819 D BtGatt.GattService: start()
08-09 14:33:41.197  3819  3819 I bt_bluedroid: get_profile_interface gatt
,08-09 14:33:41.198  3819  3819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1062b7
08-09 14:33:41.198  3819  3819 D BtGatt.AdvertiseManager: advertise manager created
,08-09 14:33:41.204  3819  3819 V BluetoothAdapterState: isTurningOff()=false
08-09 14:33:41.204  3819  3819 V BluetoothAdapterState: isTurningOn()=false
,08-09 14:33:41.204  3819  3819 V BluetoothAdapterState: isBleTurningOn()=true
08-09 14:33:41.204  3819  3819 V BluetoothAdapterState: isBleTurningOff()=false
08-09 14:33:41.205  3819  3831 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-09 14:33:41.205  3819  3831 I bt_bluedroid: enable
,08-09 14:33:41.205  3819  3832 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-09 14:33:41.206  3819  3832 I bt_hci  : start_up
,08-09 14:33:41.212  3819  3832 I bt_vendor: alloc value 0xb39c1189
,08-09 14:33:41.212  3819  3832 I bt_vendor: init
08-09 14:33:41.212  3819  3832 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-09 14:33:41.213  3819  3832 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-09 14:33:41.320  3819  3832 D bt_hci  : start_up starting async portion
,08-09 14:33:41.320  3819  3839 I bt_hci  : event_finish_startup
08-09 14:33:41.320  3819  3839 I bt_hci_h4: hal_open
,08-09 14:33:41.320  3819  3839 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-09 14:33:41.327  3819  3839 I bt_userial_vendor: device fd = 51 open
,08-09 14:33:41.363  3819  3839 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-09 14:33:41.395  3819  3839 D bt_hwcfg: Chipset BCM4354A2
,08-09 14:33:41.395  3819  3839 D bt_hwcfg: Target name = [BCM4354A2]
,08-09 14:33:41.396  3819  3839 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-09 14:33:42.062  3819  3839 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-09 14:33:42.063  3819  3839 D bt_hwcfg: Settlement delay -- 100 ms
08-09 14:33:42.064  3819  3839 I bt_hwcfg: Setting fw settlement delay to 100 
,08-09 14:33:42.180  3819  3839 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-09 14:33:42.181  3819  3839 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-09 14:33:42.211  3819  3839 I bt_hwcfg: vendor lib fwcfg completed
,08-09 14:33:42.212  3819  3839 I bt_vendor: firmware callback
08-09 14:33:42.212  3819  3839 I bt_hci  : firmware_config_callback
,08-09 14:33:42.224  3819  3842 I bt_btu  : btu_task pending for preload complete event
,08-09 14:33:42.224  3819  3842 I bt_btu_task: Bluetooth chip preload is complete
,08-09 14:33:42.224  3819  3842 I bt_btu  : btu_task received preload complete event
,08-09 14:33:42.234  3819  3842 I         : BTE_InitTraceLevels -- TRC_HCI
,08-09 14:33:42.234  3819  3842 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-09 14:33:42.235  3819  3842 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-09 14:33:42.235  3819  3842 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-09 14:33:42.235  3819  3842 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-09 14:33:42.236  3819  3842 I         : BTE_InitTraceLevels -- TRC_A2D
,08-09 14:33:42.236  3819  3842 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-09 14:33:42.236  3819  3842 I         : BTE_InitTraceLevels -- TRC_BTM
08-09 14:33:42.236  3819  3842 I         : BTE_InitTraceLevels -- TRC_GAP
08-09 14:33:42.237  3819  3842 I         : BTE_InitTraceLevels -- TRC_PAN
08-09 14:33:42.237  3819  3842 I         : BTE_InitTraceLevels -- TRC_SDP
08-09 14:33:42.237  3819  3842 I         : BTE_InitTraceLevels -- TRC_GATT
08-09 14:33:42.237  3819  3842 I         : BTE_InitTraceLevels -- TRC_SMP
08-09 14:33:42.238  3819  3842 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-09 14:33:42.238  3819  3842 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-09 14:33:42.371  3819  3842 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb393ed9d
,08-09 14:33:42.372  3819  3842 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb393ed9d 
,08-09 14:33:42.383  3819  3835 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-09 14:33:42.385  3819  3835 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-09 14:33:42.386  3819  3835 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-09 14:33:42.389  3819  3835 D BluetoothAdapterProperties: Name is: Nexus 6
08-09 14:33:42.393  3819  3835 D BluetoothAdapterProperties: Scan Mode:20
,08-09 14:33:42.393  3819  3835 D BluetoothAdapterProperties: Discoverable Timeout:120
08-09 14:33:42.393  3819  3835 D bt_hci  : do_postload posting postload work item
,08-09 14:33:42.394  3819  3839 I bt_hci  : event_postload
08-09 14:33:42.394  3819  3839 I bt_vendor: sco_config_cb
08-09 14:33:42.394  3819  3839 I bt_hci  : sco_config_callback postload finished.
,08-09 14:33:42.396  3819  3835 D bt_bte_conf: Device ID record 1 : primary
,08-09 14:33:42.397  3819  3835 D bt_bte_conf:   vendorId            = 000f
08-09 14:33:42.397  3819  3835 D bt_bte_conf:   vendorIdSource      = 0001
08-09 14:33:42.397  3819  3835 D bt_bte_conf:   product             = 1200
,08-09 14:33:42.397  3819  3835 D bt_bte_conf:   version             = 1436
08-09 14:33:42.398  3819  3835 D bt_bte_conf:   clientExecutableURL = 
,08-09 14:33:42.398  3819  3835 D bt_bte_conf:   serviceDescription  = 
08-09 14:33:42.398  3819  3835 D bt_bte_conf:   documentationURL    = 
08-09 14:33:42.398  3819  3835 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-09 14:33:42.400  3819  3832 D bt_stack_manager: event_start_up_stack finished
08-09 14:33:42.401  3819  3831 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-09 14:33:42.402  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:42.402  3819  3831 D BluetoothAdapterProperties: Setting state to 15
08-09 14:33:42.402  3819  3831 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-09 14:33:42.404  3819  3839 I bt_vendor: low_power_mode_cb
,08-09 14:33:42.404  3819  3831 I BluetoothAdapterState: Entering BleOnState
08-09 14:33:42.405  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:42.410  3819  3831 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-09 14:33:42.410  3819  3831 D BluetoothAdapterProperties: Setting state to 11
08-09 14:33:42.410  3819  3831 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-09 14:33:42.420  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:42.421  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:42.427  3819  3819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1062b7
08-09 14:33:42.430  3819  3819 D HeadsetService: Received start request. Starting profile...
,08-09 14:33:42.436  3819  3819 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-09 14:33:42.438  3819  3819 D HeadsetStateMachine: make
08-09 14:33:42.439  3819  3831 I BluetoothAdapterState: Entering PendingCommandState
,08-09 14:33:42.448  3819  3819 D HeadsetStateMachine: max_hf_connections = 1
,08-09 14:33:42.448  3819  3819 I bt_bluedroid: get_profile_interface handsfree
08-09 14:33:42.448  3819  3835 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-09 14:33:42.448  3819  3835 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-09 14:33:42.452  3819  3819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1062b7
,08-09 14:33:42.452  3819  3819 D A2dpService: Received start request. Starting profile...
,08-09 14:33:42.453  3819  3819 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-09 14:33:42.453  3819  3819 I bt_bluedroid: get_profile_interface avrcp
,08-09 14:33:42.460  3819  3819 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-09 14:33:42.460  3819  3819 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-09 14:33:42.460  3819  3819 D A2dpStateMachine: make
,08-09 14:33:42.462  3819  3819 I bt_bluedroid: get_profile_interface a2dp
,08-09 14:33:42.462  3819  3835 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-09 14:33:42.464  3819  3851 D A2dpStateMachine: Enter Disconnected: -2
,08-09 14:33:42.467  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 14:33:42.467  3819  3819 I BluetoothHidServiceJni: classInitNative: succeeds
08-09 14:33:42.468  3819  3819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1062b7
,08-09 14:33:42.469  3819  3819 D HidService: Received start request. Starting profile...
08-09 14:33:42.469  3819  3819 I bt_bluedroid: get_profile_interface hidhost
08-09 14:33:42.469  3819  3835 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39203e5
08-09 14:33:42.469  3819  3835 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-09 14:33:42.470  3819  3819 D HidService: setHidService(): set to: null
,08-09 14:33:42.470  3819  3819 I BluetoothHealthServiceJni: classInitNative: succeeds
08-09 14:33:42.471  3819  3819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1062b7
08-09 14:33:42.472  3819  3819 D HealthService: Received start request. Starting profile...
,08-09 14:33:42.475  3819  3819 I bt_bluedroid: get_profile_interface health
,08-09 14:33:42.476  3819  3819 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-09 14:33:42.479  3819  3819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1062b7
,08-09 14:33:42.481  3819  3819 D PanService: Received start request. Starting profile...
,08-09 14:33:42.482  3819  3819 D BluetoothPanServiceJni: initializeNative(L110): pan
08-09 14:33:42.482  3819  3819 I bt_bluedroid: get_profile_interface pan
08-09 14:33:42.483  3819  3835 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-09 14:33:42.489  3819  3819 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c1062b7
,08-09 14:33:42.490  3819  3819 D BluetoothMapService: Received start request. Starting profile...
,08-09 14:33:42.490  3819  3819 D BluetoothMapService: start()
,08-09 14:33:42.494  3819  3819 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-09 14:33:42.495  3819  3819 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-09 14:33:42.495  3819  3819 D BluetoothMapAppObserver: createReceiver()
,08-09 14:33:42.496  3819  3819 D BluetoothMapAppObserver: initObservers()
08-09 14:33:42.497  3819  3819 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-09 14:33:42.505  3819  3819 V BluetoothAdapterState: isTurningOff()=false
,08-09 14:33:42.505  3819  3819 V BluetoothAdapterState: isTurningOn()=true
08-09 14:33:42.506  3819  3819 V BluetoothAdapterState: isBleTurningOn()=false
08-09 14:33:42.506  3819  3849 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-09 14:33:42.506  3819  3819 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 14:33:42.507  3819  3819 V BluetoothAdapterState: isTurningOff()=false
08-09 14:33:42.507  3819  3819 V BluetoothAdapterState: isTurningOn()=true
08-09 14:33:42.507  3819  3819 V BluetoothAdapterState: isBleTurningOn()=false
08-09 14:33:42.507  3819  3819 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 14:33:42.509  3819  3819 V BluetoothAdapterState: isTurningOff()=false
,08-09 14:33:42.509  3819  3819 V BluetoothAdapterState: isTurningOn()=true
08-09 14:33:42.509  3819  3819 V BluetoothAdapterState: isBleTurningOn()=false
08-09 14:33:42.509  3819  3819 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 14:33:42.510  3819  3819 V BluetoothAdapterState: isTurningOff()=false
08-09 14:33:42.510  3819  3819 V BluetoothAdapterState: isTurningOn()=true
08-09 14:33:42.510  3819  3819 V BluetoothAdapterState: isBleTurningOn()=false
08-09 14:33:42.510  3819  3819 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 14:33:42.510  3819  3819 V BluetoothAdapterState: isTurningOff()=false
08-09 14:33:42.510  3819  3819 V BluetoothAdapterState: isTurningOn()=true
08-09 14:33:42.510  3819  3819 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 14:33:42.510  3819  3819 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 14:33:42.511  3819  3819 V BluetoothAdapterState: isTurningOff()=false
,08-09 14:33:42.511  3819  3819 V BluetoothAdapterState: isTurningOn()=true
08-09 14:33:42.511  3819  3819 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 14:33:42.511  3819  3819 V BluetoothAdapterState: isBleTurningOff()=false
08-09 14:33:42.511  3819  3831 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-09 14:33:42.511  3819  3831 D BluetoothAdapterProperties: ScanMode =  20
08-09 14:33:42.511  3819  3831 D BluetoothAdapterProperties: State =  11
08-09 14:33:42.512  3819  3831 D BluetoothAdapterProperties: Setting state to 12
,08-09 14:33:42.512  3819  3831 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-09 14:33:42.513  3819  3831 I BluetoothAdapterState: Entering OnState
08-09 14:33:42.513  3438  3449 D BluetoothA2dp: onBluetoothStateChange: up=true
08-09 14:33:42.515  3819  3835 D BluetoothAdapterProperties: Scan Mode:21
08-09 14:33:42.515  3819  3835 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-09 14:33:42.518  1370  1840 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-09 14:33:42.520  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:42.520  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:42.520  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 14:33:42.520  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:42.520  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:42.520  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:42.520  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:42.520  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 14:33:42.521  3438  3449 D BluetoothPan: onBluetoothStateChange on: true
,08-09 14:33:42.522  3322  3322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:42.522  1370  1370 D BluetoothInputDevice: Proxy object connected
08-09 14:33:42.522  1370  1370 D HidProfile: Bluetooth service connected
,08-09 14:33:42.523  1370  1382 D BluetoothMap: onBluetoothStateChange: up=true
,08-09 14:33:42.525  3819  3819 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-09 14:33:42.526  3819  3819 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-09 14:33:42.526   870   887 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-09 14:33:42.526   870   887 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 14:33:42.527   870   887 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-09 14:33:42.527  3819  3819 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 14:33:42.527   870   870 D BluetoothA2dp: Proxy object connected
,08-09 14:33:42.528  3438  3450 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-09 14:33:42.530  3819  3819 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 14:33:42.530   870   887 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-09 14:33:42.521  3438  3438 D BluetoothA2dp: Proxy object connected
,08-09 14:33:42.530  1370  1381 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-09 14:33:42.531  3819  3819 D ObexServerSockets: Succeed to create listening sockets 
,08-09 14:33:42.531  3819  3819 D ObexServerSockets0: startAccept()
08-09 14:33:42.531  3819  3819 D ObexServerSockets0: prepareForNewConnect()
,08-09 14:33:42.533  1370  1842 D BluetoothPan: onBluetoothStateChange on: true
08-09 14:33:42.533  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:42.533  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:42.533  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 14:33:42.533  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:42.533  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 14:33:42.533  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:42.533  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:42.533  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 14:33:42.533  3819  3819 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-09 14:33:42.534  3819  3819 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-09 14:33:42.534  3438  3438 D BluetoothInputDevice: Proxy object connected
,08-09 14:33:42.534  3438  3438 D HidProfile: Bluetooth service connected
,08-09 14:33:42.535  1370  1370 D BluetoothA2dp: Proxy object connected
08-09 14:33:42.535  3819  3861 D ObexServerSockets0: Accepting socket connection...
,08-09 14:33:42.537  3819  3860 D ObexServerSockets0: Accepting socket connection...
08-09 14:33:42.537  1370  1382 D BluetoothPbap: onBluetoothStateChange: up=true
08-09 14:33:42.538  3322  3322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:42.538  3438  3450 D BluetoothMap: onBluetoothStateChange: up=true
08-09 14:33:42.538  1370  1370 D BluetoothPan: BluetoothPAN Proxy object connected
08-09 14:33:42.538  1370  1370 D PanProfile: Bluetooth service connected
08-09 14:33:42.539  1370  1370 D BluetoothMap: Proxy object connected
08-09 14:33:42.539  1370  1370 D MapProfile: Bluetooth service connected
08-09 14:33:42.539  1370  1370 D BluetoothMap: getConnectedDevices()
08-09 14:33:42.540  1370  1840 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 14:33:42.540  3438  3449 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 14:33:42.540  1738  1754 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 14:33:42.541  3438  3859 D BluetoothPbap: onBluetoothStateChange: up=true
08-09 14:33:42.542   870   870 I Telecom : BluetoothPhoneService: queryPhoneState
08-09 14:33:42.543  3819  3819 D BluetoothMapService: onReceive
08-09 14:33:42.543  3819  3819 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:42.544  3819  3819 D BluetoothMapService: STATE_ON
08-09 14:33:42.544  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:42.545  3438  3438 D BluetoothPan: BluetoothPAN Proxy object connected
08-09 14:33:42.545  3438  3438 D PanProfile: Bluetooth service connected
08-09 14:33:42.545  3438  3438 D BluetoothMap: Proxy object connected
08-09 14:33:42.545  3438  3438 D MapProfile: Bluetooth service connected
08-09 14:33:42.545  3438  3438 D BluetoothMap: getConnectedDevices()
08-09 14:33:42.546  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:42.553  3438  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-09 14:33:42.559  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 14:33:42.559  3438  3438 D DockEventReceiver: finishStartingService: stopping service
,08-09 14:33:42.568  1370  1370 D BluetoothPbap: Proxy object connected
,08-09 14:33:42.569  1370  1370 D PbapServerProfile: Bluetooth service connected
,08-09 14:33:42.569  3438  3438 D BluetoothPbap: Proxy object connected
08-09 14:33:42.569  3438  3438 D PbapServerProfile: Bluetooth service connected
,08-09 14:33:42.574  3819  3819 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-09 14:33:42.574  3819  3819 D ObexServerSockets0: prepareForNewConnect()
,08-09 14:33:42.577  3819  3865 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 14:33:42.596  3819  3869 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 14:33:42.597  3819  3869 I BtOppRfcommListener: Accept thread started.
,08-09 14:33:42.628   870   887 D BluetoothHeadset: Proxy object connected
,08-09 14:33:42.628  1738  1860 D BluetoothHeadset: Proxy object connected
,08-09 14:33:42.628  1370  1842 D BluetoothHeadset: Proxy object connected
,08-09 14:33:42.628  1370  1370 D HeadsetProfile: Bluetooth service connected
,08-09 14:33:42.629   870   870 D BluetoothHeadset: Proxy object connected
08-09 14:33:42.629  3438  3449 D BluetoothHeadset: Proxy object connected
,08-09 14:33:42.629   870   870 D BluetoothHeadset: Proxy object connected
,08-09 14:33:42.629   870   870 D BluetoothHeadset: Proxy object connected
,08-09 14:33:42.629  3438  3438 D HeadsetProfile: Bluetooth service connected
08-09 14:33:42.630   870   887 D BluetoothHeadset: Proxy object connected
,08-09 14:33:42.640  1370  1381 D BluetoothHeadset: Proxy object connected
,08-09 14:33:42.641  1370  1370 D HeadsetProfile: Bluetooth service connected
,08-09 14:33:42.641  3438  3859 D BluetoothHeadset: Proxy object connected
08-09 14:33:42.641  3438  3438 D HeadsetProfile: Bluetooth service connected
08-09 14:33:42.641  1738  1753 D BluetoothHeadset: Proxy object connected
,08-09 14:33:43.927  2573  2584 D Finsky  : [173] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-09 14:33:43.946  3322  3371 D io.jxcore.node.ConnectivityMonitor: stop
,08-09 14:33:43.946  3322  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 14:33:43.952  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:33:43.966  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:33:43.969  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:33:44.019  1515  3581 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-09 14:33:44.019  1515  3581 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-09 14:33:44.019  1515  3581 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 14:33:44.020  1515  3581 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 14:33:44.070  2573  2584 D Finsky  : [173] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-09 14:33:46.955  3322  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-09 14:33:46.955  3322  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bdb4a9b added. We now have 6 listener(s)
08-09 14:33:46.956  3322  3371 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 14:33:46.965  3322  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-09 14:33:46.965  3322  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bfc2e38 added. We now have 7 listener(s)
08-09 14:33:46.966  3322  3371 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 14:33:46.969  3322  3371 I System.out: IsBluetoothEnabled
,08-09 14:33:46.979  3819  3831 D BluetoothAdapterState: Current state: ON, message: 23
08-09 14:33:46.980  3819  3831 D BluetoothAdapterProperties: Setting state to 13
,08-09 14:33:46.980  3819  3831 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-09 14:33:46.982  3819  3831 D BluetoothAdapterProperties: onBluetoothDisable()
,08-09 14:33:46.990  3819  3831 I BluetoothAdapterState: Entering PendingCommandState
08-09 14:33:46.994  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:46.994  3322  3371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:46.994  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:46.994  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 14:33:46.994  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:46.994  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:46.994  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:46.994  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:46.994  3322  3371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 14:33:46.998  3322  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:46.998  3322  3371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:46.998  3819  3819 D BluetoothMapService: onReceive
08-09 14:33:47.000  3322  3322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:47.000  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 14:33:47.000  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 14:33:47.000  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 14:33:47.000  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 14:33:47.000  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 14:33:47.000  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 14:33:47.000  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 14:33:47.000  3322  3322 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 14:33:47.000  3819  3819 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-09 14:33:47.000  3819  3819 D BluetoothMapService: STATE_TURNING_OFF
08-09 14:33:47.000  3819  3835 D BluetoothAdapterProperties: Scan Mode:20
08-09 14:33:47.000  3819  3831 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-09 14:33:47.001  3819  3819 D BluetoothMapService: MAP Service closeService in
,08-09 14:33:47.001  3322  3322 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 14:33:47.001  3819  3819 D BluetoothMapMasInstance0: MAP Service shutdown
,08-09 14:33:47.001  3322  3322 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 14:33:47.001  3819  3819 D ObexServerSockets0: shutdown(block = true)
08-09 14:33:47.002  3819  3860 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-09 14:33:47.004  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:47.005  3819  3819 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-09 14:33:47.006  3819  3861 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-09 14:33:47.006  3819  3845 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-09 14:33:47.006  3819  3819 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-09 14:33:47.007  3819  3819 I BtOppRfcommListener: stopping Accept Thread
08-09 14:33:47.007  3819  3869 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 14:33:47.008  3819  3869 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-09 14:33:47.009  3819  3831 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,08-09 14:33:47.009  3819  3831 I BluetoothAdapterState: Deferring BLE_TURN_ON request...
08-09 14:33:47.010  3438  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-09 14:33:47.010  3819  3819 D HeadsetService: Received stop request...Stopping profile...
08-09 14:33:47.017  1738  1984 D BluetoothHeadset: Proxy object disconnected
08-09 14:33:47.018  1370  1842 D BluetoothHeadset: Proxy object disconnected
08-09 14:33:47.018   870   870 D BluetoothHeadset: Proxy object disconnected
,08-09 14:33:47.018  1370  1370 D HeadsetProfile: Bluetooth service disconnected
08-09 14:33:47.018  3819  3819 D A2dpService: Received stop request...Stopping profile...
08-09 14:33:47.018  3438  3449 D BluetoothHeadset: Proxy object disconnected
08-09 14:33:47.019   870   870 D BluetoothHeadset: Proxy object disconnected
08-09 14:33:47.019   870   870 D BluetoothHeadset: Proxy object disconnected
08-09 14:33:47.019  3819  3851 D A2dpStateMachine: Exit Disconnected: -1
,08-09 14:33:47.020   870   870 D BluetoothA2dp: Proxy object disconnected
08-09 14:33:47.021  1370  1370 D BluetoothA2dp: Proxy object disconnected
08-09 14:33:47.021  3819  3819 D HidService: Received stop request...Stopping profile...
08-09 14:33:47.021  3819  3819 D HidService: Stopping Bluetooth HidService
08-09 14:33:47.022  1370  1370 D BluetoothInputDevice: Proxy object disconnected
,08-09 14:33:47.023  3819  3819 D HealthService: Received stop request...Stopping profile...
,08-09 14:33:47.025  1370  1370 D HidProfile: Bluetooth service disconnected
,08-09 14:33:47.026  3819  3819 D PanService: Received stop request...Stopping profile...
,08-09 14:33:47.026  1370  1370 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-09 14:33:47.026  1370  1370 D PanProfile: Bluetooth service disconnected
,08-09 14:33:47.027  3819  3819 D BluetoothMapService: Received stop request...Stopping profile...
08-09 14:33:47.027  3819  3819 D BluetoothMapService: stop()
,08-09 14:33:47.028  3819  3819 D BluetoothMapAppObserver: deinitObservers()
08-09 14:33:47.028  3819  3819 D BluetoothMapAppObserver: removeReceiver()
,08-09 14:33:47.028  3438  3438 D DockEventReceiver: finishStartingService: stopping service
,08-09 14:33:47.028  1370  1370 D BluetoothMap: Proxy object disconnected
08-09 14:33:47.029  1370  1370 D MapProfile: Bluetooth service disconnected
08-09 14:33:47.030  3438  3438 D HeadsetProfile: Bluetooth service disconnected
08-09 14:33:47.030  3438  3438 D BluetoothA2dp: Proxy object disconnected
08-09 14:33:47.030  3438  3438 D BluetoothInputDevice: Proxy object disconnected
,08-09 14:33:47.030  3819  3819 V BluetoothAdapterState: isTurningOff()=true
08-09 14:33:47.030  3438  3438 D HidProfile: Bluetooth service disconnected
08-09 14:33:47.030  3819  3819 V BluetoothAdapterState: isTurningOn()=false
08-09 14:33:47.030  3819  3819 V BluetoothAdapterState: isBleTurningOn()=false
08-09 14:33:47.030  3819  3819 V BluetoothAdapterState: isBleTurningOff()=false
08-09 14:33:47.030  3438  3438 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-09 14:33:47.030  3438  3438 D PanProfile: Bluetooth service disconnected
08-09 14:33:47.031  3438  3438 D BluetoothMap: Proxy object disconnected
08-09 14:33:47.031  3438  3438 D MapProfile: Bluetooth service disconnected
08-09 14:33:47.034  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 14:33:47.036  3819  3819 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-09 14:33:47.036  3819  3819 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-09 14:33:47.036  3819  3835 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-09 14:33:47.036  3819  3842 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-09 14:33:47.036  3819  3819 V BluetoothAdapterState: isTurningOff()=true
08-09 14:33:47.036  3819  3842 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 14:33:47.036  3819  3819 V BluetoothAdapterState: isTurningOn()=false,
08-09 14:33:47.036  3819  3842 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-09 14:33:47.036  3819  3819 V BluetoothAdapterState: isBleTurningOn()=false
08-09 14:33:47.036  3819  3819 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 14:33:47.036  3819  3835 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
,08-09 14:33:47.037  3819  3835 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-09 14:33:47.037  3819  3842 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-09 14:33:47.037  3819  3819 V BluetoothAdapterState: isTurningOff()=true
08-09 14:33:47.037  3819  3842 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-09 14:33:47.037  3819  3819 V BluetoothAdapterState: isTurningOn()=false
08-09 14:33:47.037  3819  3819 V BluetoothAdapterState: isBleTurningOn()=false
08-09 14:33:47.037  3819  3819 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 14:33:47.038  3819  3842 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 14:33:47.038  3819  3819 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-09 14:33:47.038  3819  3842 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 14:33:47.038  3819  3819 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-09 14:33:47.038  3819  3842 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
,08-09 14:33:47.038  3819  3835 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-09 14:33:47.038  3819  3842 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-09 14:33:47.038  3819  3819 V BluetoothAdapterState: isTurningOff()=true
08-09 14:33:47.038  3819  3819 V BluetoothAdapterState: isTurningOn()=false
,08-09 14:33:47.038  3819  3819 V BluetoothAdapterState: isBleTurningOn()=false
08-09 14:33:47.038  3819  3819 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 14:33:47.038  3819  3819 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-09 14:33:47.038  3819  3835 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-09 14:33:47.039  3819  3819 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-09 14:33:47.039  3819  3819 V BluetoothAdapterState: isTurningOff()=true
08-09 14:33:47.039  3819  3819 V BluetoothAdapterState: isTurningOn()=false
08-09 14:33:47.040  3819  3819 V BluetoothAdapterState: isBleTurningOn()=false
08-09 14:33:47.040  3819  3819 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 14:33:47.040  3819  3819 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-09 14:33:47.040  3819  3819 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-09 14:33:47.041  3819  3819 D BluetoothMapService: MAP Service closeService in
08-09 14:33:47.043  3819  3819 V BluetoothAdapterState: isTurningOff()=true
08-09 14:33:47.043  3819  3819 V BluetoothAdapterState: isTurningOn()=false
08-09 14:33:47.043  3819  3819 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 14:33:47.043  3819  3819 V BluetoothAdapterState: isBleTurningOff()=false
08-09 14:33:47.043  3819  3831 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-09 14:33:47.043  3819  3831 D BluetoothAdapterProperties: Setting state to 15
08-09 14:33:47.046  3819  3831 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-09 14:33:47.046  3819  3819 D BluetoothMapService: cleanup()
08-09 14:33:47.046  3819  3819 D BluetoothMapService: MAP Service closeService in
,08-09 14:33:47.046  3819  3831 I BluetoothAdapterState: Entering BleOnState
,08-09 14:33:47.047  3819  3831 D BluetoothAdapterState: Current state: BLE ON, message: 0
08-09 14:33:47.047  3438  3450 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 14:33:47.048  1370  1840 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-09 14:33:47.048  1370  1370 D BluetoothPbap: Proxy object disconnected
08-09 14:33:47.048  1370  1370 D PbapServerProfile: Bluetooth service disconnected
08-09 14:33:47.048  3438  3438 D BluetoothPbap: Proxy object disconnected
08-09 14:33:47.049  3438  3438 D PbapServerProfile: Bluetooth service disconnected
,08-09 14:33:47.049  3438  3449 D BluetoothPan: onBluetoothStateChange on: false
08-09 14:33:47.051  1370  1381 D BluetoothMap: onBluetoothStateChange: up=false
08-09 14:33:47.051   870   887 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 14:33:47.051   870   887 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 14:33:47.052   870   887 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-09 14:33:47.053  3438  3450 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-09 14:33:47.053   870   887 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 14:33:47.054  1370  1842 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 14:33:47.054  1370  1382 D BluetoothPan: onBluetoothStateChange on: false
08-09 14:33:47.055  1370  1840 D BluetoothPbap: onBluetoothStateChange: up=false
,08-09 14:33:47.055  3438  3859 D BluetoothMap: onBluetoothStateChange: up=false
08-09 14:33:47.056  1370  1381 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 14:33:47.056  3438  3449 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 14:33:47.057  1738  1754 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-09 14:33:47.057  3438  3450 D BluetoothPbap: onBluetoothStateChange: up=false
08-09 14:33:47.058  3819  3831 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-09 14:33:47.058  3819  3831 D BluetoothAdapterProperties: Setting state to 16
08-09 14:33:47.058  3819  3831 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-09 14:33:47.058  3819  3831 D BluetoothAdapterProperties: onBleDisable
08-09 14:33:47.058  3819  3831 I BluetoothAdapterState: Entering PendingCommandState
08-09 14:33:47.060  3819  3832 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-09 14:33:47.060  3819  3835 D BluetoothAdapterProperties: Scan Mode:20
08-09 14:33:47.061  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:47.061  3819  3842 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-09 14:33:47.061  3819  3842 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 14:33:47.062  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 14:33:47.063  3438  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-09 14:33:47.067  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 14:33:47.075  3438  3438 D DockEventReceiver: finishStartingService: stopping service
,08-09 14:33:47.263  3819  3835 I bt_hci  : shut_down
,08-09 14:33:47.264  3819  3839 D bt_hwcfg: hw_epilog_process
,08-09 14:33:47.265  3819  3839 I bt_vendor: low_power_mode_cb
,08-09 14:33:47.294  3819  3839 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-09 14:33:47.295  3819  3839 I bt_vendor: epilog_cb
,08-09 14:33:47.295  3819  3839 I bt_hci  : epilog_finished_callback
,08-09 14:33:47.304  3819  3835 I bt_hci_h4: hal_close
,08-09 14:33:47.306  3819  3835 I bt_userial_vendor: device fd = 51 close
,08-09 14:33:47.446  3819  3832 D bt_stack_manager: event_shut_down_stack finished.
08-09 14:33:47.446  3819  3831 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-09 14:33:47.453  3819  3831 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-09 14:33:47.454  3819  3819 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-09 14:33:47.455  3819  3819 D BtGatt.GattService: Received stop request...Stopping profile...
,08-09 14:33:47.455  3819  3819 D BtGatt.GattService: stop()
,08-09 14:33:47.456  3819  3819 D BtGatt.AdvertiseManager: advertise clients cleared
,08-09 14:33:47.461  3819  3819 V BluetoothAdapterState: isTurningOff()=false
,08-09 14:33:47.461  3819  3819 V BluetoothAdapterState: isTurningOn()=false
08-09 14:33:47.461  3819  3819 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 14:33:47.462  3819  3819 V BluetoothAdapterState: isBleTurningOff()=true
,08-09 14:33:47.463  3819  3831 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-09 14:33:47.464  3819  3831 D BluetoothAdapterProperties: Setting state to 10
08-09 14:33:47.464  3819  3831 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-09 14:33:47.466  3819  3831 I BluetoothAdapterState: Entering OffState
08-09 14:33:47.478  3322  3322 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 14:33:47.481  3438  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-09 14:33:47.494  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 14:33:47.506  3438  3438 D DockEventReceiver: finishStartingService: stopping service
,08-09 14:33:47.552   870  1823 I ActivityManager: Killing 3256:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-09 14:33:50.210  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:33:50.220  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:33:50.224  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:33:50.261  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-09 14:33:50.262  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-09 14:33:50.262  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 14:33:50.262  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 14:33:50.294  2573  2573 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-09 14:33:50.295  2573  2573 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-09 14:33:50.295  2573  2573 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-09 14:34:02.830   870   890 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-09 14:34:02.843  1660  1660 I Keyboard.Facilitator: onFinishInput()
,08-09 14:34:02.864   870   890 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-09 14:34:02.864   870   890 I Adreno  : Build Date                       : 10/20/15
08-09 14:34:02.864   870   890 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-09 14:34:02.864   870   890 I Adreno  : Local Branch                     : M14
08-09 14:34:02.864   870   890 I Adreno  : Remote Branch                    : 
08-09 14:34:02.864   870   890 I Adreno  : Remote Branch                    : 
08-09 14:34:02.864   870   890 I Adreno  : Reconstruct Branch               : 
,08-09 14:34:02.907   281  1700 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (333 us)
,08-09 14:34:03.592  3322  3322 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-09 14:34:03.592  3322  3322 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-09 14:34:03.647   870   890 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-09 14:34:03.648  3322  3322 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6be7353 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@7c4ee11, 16908290=android.view.AbsSavedState$1@7c4ee11}, android:focusedViewId=100}]}]
08-09 14:34:03.648  3322  3322 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-09 14:34:03.648  3322  3322 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-09 14:34:03.648  3322  3322 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-09 14:34:03.654   870   890 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-09 14:34:03.658   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
,08-09 14:34:03.658   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-09 14:34:03.659   870   888 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-09 14:34:03.916   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-09 14:34:03.920   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-09 14:34:03.921   870  1338 D SurfaceControl: Excessive delay in setPowerMode(): 263ms
,08-09 14:34:03.924   870   890 I DreamManagerService: Entering dreamland.
,08-09 14:34:03.925   870   890 I PowerManagerService: Dozing...
08-09 14:34:03.927   870   885 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-09 14:34:04.019   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-09 14:34:04.019   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-09 14:34:04.034   870  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-09 14:34:04.044   870  1312 E native  : do suspend false
,08-09 14:34:04.055  1725  3893 D NfcService: Discovery configuration equal, not updating.
,08-09 14:34:04.186   375  1285 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-09 14:34:04.186   375  1285 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-09 14:34:04.203   870  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-09 14:34:04.224   870  1312 E native  : do suspend true
,08-09 14:34:08.035  1939  2315 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-09 14:34:15.590  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:34:15.608  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:34:15.615  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:34:15.694  1515  3581 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-09 14:34:15.695  1515  3581 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-09 14:34:15.696  1515  3581 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 14:34:15.696  1515  3581 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 14:34:15.741  2573  2573 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-09 14:34:15.742  2573  2573 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-09 14:34:15.742  2573  2573 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-09 14:34:35.124   870  1314 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-09 14:34:45.051  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:34:45.059  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:34:45.063  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:34:45.098  1515  1983 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-09 14:34:45.099  1515  1983 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-09 14:34:45.099  1515  1983 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 14:34:45.099  1515  1983 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 14:34:45.133  2573  2573 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-09 14:34:45.133  2573  2573 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-09 14:34:45.133  2573  2573 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-09 14:35:02.886  1660  1775 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-09 14:35:02.886  1660  1775 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-09 14:35:02.918  1515  1515 I ConfigService: onCreate
,08-09 14:35:07.985  1515  1515 I ConfigService: onDestroy
,08-09 14:35:17.970  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:35:17.982  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:35:17.987  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:35:18.034  1515  3579 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-09 14:35:18.035  1515  3579 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-09 14:35:18.035  1515  3579 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 14:35:18.035  1515  3579 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 14:35:18.075  2573  2573 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-09 14:35:18.075  2573  2573 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-09 14:35:18.076  2573  2573 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-09 14:37:03.794  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:37:03.804  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:37:03.808  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:37:03.863  1515  1983 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket,
08-09 14:37:03.864  1515  1983 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-09 14:37:03.864  1515  1983 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 14:37:03.864  1515  1983 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 14:37:03.895  1515  1983 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-09 14:37:03.895  1515  1983 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-09 14:37:03.895  1515  1983 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-09 14:37:03.895  1515  1983 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-09 14:37:03.895  1515  1983 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-09 14:37:03.895  1515  1983 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-09 14:37:03.895  1515  1983 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-09 14:37:03.899  2573  2606 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-09 14:37:03.899  2573  2606 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-09 14:37:03.899  2573  2606 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-09 14:37:03.899  2573  2606 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-09 14:37:03.899  2573  2606 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-09 14:37:03.899  2573  2606 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-09 14:37:03.899  2573  2606 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-09 14:42:04.051  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:42:04.075  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:42:04.083  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:42:04.188  1515  3581 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-09 14:42:04.188  1515  3581 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-09 14:42:04.189  1515  3581 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 14:42:04.189  1515  3581 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 14:42:04.243  1515  3581 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-09 14:42:04.243  1515  3581 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-09 14:42:04.243  1515  3581 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-09 14:42:04.243  1515  3581 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-09 14:42:04.243  1515  3581 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-09 14:42:04.243  1515  3581 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-09 14:42:04.243  1515  3581 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-09 14:42:04.256  2573  2606 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-09 14:42:04.256  2573  2606 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-09 14:42:04.256  2573  2606 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-09 14:42:04.256  2573  2606 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-09 14:42:04.256  2573  2606 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-09 14:42:04.256  2573  2606 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-09 14:42:04.256  2573  2606 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-09 14:47:04.403  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:47:04.424  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:47:04.428  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:47:04.527  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-09 14:47:04.527  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-09 14:47:04.528  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 14:47:04.528  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 14:47:04.578  1515  1526 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-09 14:47:04.578  1515  1526 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-09 14:47:04.578  1515  1526 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-09 14:47:04.578  1515  1526 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-09 14:47:04.578  1515  1526 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-09 14:47:04.578  1515  1526 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-09 14:47:04.578  1515  1526 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-09 14:47:04.591  2573  2606 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-09 14:47:04.591  2573  2606 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-09 14:47:04.591  2573  2606 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-09 14:47:04.591  2573  2606 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-09 14:47:04.591  2573  2606 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-09 14:47:04.591  2573  2606 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-09 14:47:04.591  2573  2606 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-09 14:51:51.366   870   882 I UsageStatsService: User[0] Flushing usage stats to disk
,08-09 14:52:04.730  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:52:04.754  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:52:04.762  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 14:52:04.867  1515  3566 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-09 14:52:04.867  1515  3566 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-09 14:52:04.868  1515  3566 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 14:52:04.868  1515  3566 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 14:52:04.920  1515  3566 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-09 14:52:04.920  1515  3566 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-09 14:52:04.920  1515  3566 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-09 14:52:04.920  1515  3566 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-09 14:52:04.920  1515  3566 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-09 14:52:04.920  1515  3566 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-09 14:52:04.920  1515  3566 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-09 14:52:04.933  2573  2606 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-09 14:52:04.933  2573  2606 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-09 14:52:04.933  2573  2606 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-09 14:52:04.933  2573  2606 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-09 14:52:04.933  2573  2606 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-09 14:52:04.933  2573  2606 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-09 14:52:04.933  2573  2606 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms),08-09 14:56:47.033  3995  3995 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-09 14:56:47.038  3995  3995 D AndroidRuntime: CheckJNI is OFF
08-09 14:56:47.074  3995  3995 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-09 14:56:47.115  3995  3995 I Radio-JNI: register_android_hardware_Radio DONE
08-09 14:56:47.135  3995  3995 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-09 14:56:47.147   870   883 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-09 14:56:47.148   870   883 I ActivityManager: Killing 3322:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-09 14:56:47.244   870  1313 D WifiService: Client connection lost with reason: 4
08-09 14:56:47.244   870  1737 I WindowState: WIN DEATH: Window{9eb2cd6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-09 14:56:47.245   870  1755 D GraphicsStats: Buffer count: 2
08-09 14:56:47.275   870   893 W PackageSettings: Skipping PackageSetting{5a603c8 com.example.hello/10273} due to missing metadata
08-09 14:56:47.302   870   883 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-09 14:56:47.302   870   883 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-09 14:56:47.302   870   883 E ActivityManager: Failure starting process com.test.thalitest
08-09 14:56:47.302   870   883 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-09 14:56:47.302   870   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-09 14:56:47.302   870   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-09 14:56:47.302   870   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-09 14:56:47.302   870   883 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-09 14:56:47.302   870   883 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-09 14:56:47.302   870   883 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-09 14:56:47.302   870   883 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-09 14:56:47.302   870   883 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-09 14:56:47.302   870   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-09 14:56:47.302   870   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-09 14:56:47.302   870   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-09 14:56:47.302   870   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-09 14:56:47.302   870   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-09 14:56:47.302   870   883 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-09 14:56:47.302   870   883 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:56:47.302   870   883 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-09 14:56:47.302   870   883 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 14:56:47.302   870   883 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-09 14:56:47.303   870   883 I ActivityManager:   Force finishing activity ActivityRecord{844d57f u0 com.test.thalitest/.MainActivity t4}
08-09 14:56:47.306   870   893 I art     : Starting a blocking GC Explicit
08-09 14:56:47.315   870  1680 W ActivityManager: Spurious death for ProcessRecord{fed79a8 0:com.test.thalitest/u0a0}, curProc for 3322: null
08-09 14:56:47.367   870   893 I art     : Explicit concurrent mark sweep GC freed 46193(3MB) AllocSpace objects, 7(140KB) LOS objects, 33% free, 28MB/43MB, paused 1.058ms total 60.837ms
08-09 14:56:47.390   870   893 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-09 14:56:47.393  3995  3995 I art     : System.exit called, status: 0
08-09 14:56:47.393  3995  3995 I AndroidRuntime: VM exiting with result code 0.
08-09 14:56:47.396   870   893 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-09 14:56:47.410   870   883 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-09 14:56:47.420  1939  2039 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-09 14:56:47.424   870  1304 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-09 14:56:47.430  3203  3203 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-09 14:56:47.440  1660  1660 I Keyboard.Facilitator: resetDictionaries() : en_US
08-09 14:56:47.446  1660  4007 I Keyboard.Facilitator.DecoderInitializer: run()
08-09 14:56:47.451  1660  4007 I Decoder : createOrResetDecoder
08-09 14:56:47.470  1738  1738 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-09 14:56:47.474  1515  1515 I ConfigService: onCreate
08-09 14:56:47.489   870  1737 I ActivityManager: Start proc 4010:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-09 14:56:47.503  1660  4007 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-09 14:56:47.514   870   870 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-09 14:56:47.537   870  1823 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3322 uid 10000
08-09 14:56:47.538  1660  1660 I Keyboard.Facilitator: onFinishInput()
08-09 14:56:47.547  4010  4010 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-09 14:56:47.555  1660  4007 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-09 14:56:47.557  1660  4007 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-09 14:56:47.557  1660  4007 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-09 14:56:47.557   870   882 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-09 14:56:47.558  1660  4007 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-09 14:56:47.558  1660  4007 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-09 14:56:47.558   870   882 E PackageManager: Failed to write settings, restoring backup
08-09 14:56:47.558   870   882 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-09 14:56:47.558   870   882 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-09 14:56:47.558   870   882 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-09 14:56:47.558   870   882 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-09 14:56:47.558   870   882 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-09 14:56:47.558   870   882 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:56:47.558   870   882 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-09 14:56:47.558   870   882 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 14:56:47.559  1660  4007 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-09 14:56:47.559  1660  4007 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-09 14:56:47.559  1660  4007 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-09 14:56:47.560  1660  4007 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-09 14:56:47.560  1660  4007 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-09 14:56:47.560  1660  4007 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-09 14:56:47.560  1660  4007 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-09 14:56:47.560  1660  4007 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-09 14:56:47.563   870   883 E DropBoxManagerService: Can't write: system_server_wtf
08-09 14:56:47.563   870   883 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-09 14:56:47.563   870   883 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-09 14:56:47.563   870   883 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 14:56:47.563   870   883 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 14:56:47.563   870   883 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-09 14:56:47.563   870   883 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-09 14:56:47.563   870   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-09 14:56:47.563   870   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-09 14:56:47.563   870   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-09 14:56:47.563   870   883 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-09 14:56:47.563   870   883 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-09 14:56:47.563   870   883 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-09 14:56:47.563   870   883 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-09 14:56:47.563   870   883 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 14:56:47.563   870   883 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-09 14:56:47.563   870   883 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 14:56:47.563   870   883 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-09 14:56:47.563   870   883 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 14:56:47.563   870   883 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 14:56:47.563   870   883 E DropBoxManagerService: 	... 13 more
08-09 14:56:47.574  1758  1832 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-09 14:56:47.586   870  1737 I ActivityManager: Start proc 4026:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-09 14:56:47.587  1758  1832 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-09 14:56:47.587  1758  1832 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1758
08-09 14:56:47.587  1758  1832 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-09 14:56:47.587  1758  1832 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-09 14:56:47.587  1758  1832 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-09 14:56:47.587  1758  1832 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-09 14:56:47.587  1758  1832 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-09 14:56:47.587  1758  1832 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-09 14:56:47.587  1758  1832 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-09 14:56:47.587  1758  1832 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-09 14:56:47.587  1758  1832 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-09 14:56:47.587  1758  1832 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-09 14:56:47.587  1758  1832 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-09 14:56:47.587  1758  1832 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 14:56:47.589   870  1756 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-09 14:56:47.591   870  4034 E DropBoxManagerService: Can't write: system_app_crash
08-09 14:56:47.591   870  4034 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
08-09 14:56:47.591   870  4034 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-09 14:56:47.591   870  4034 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 14:56:47.591   870  4034 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 14:56:47.591   870  4034 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-09 14:56:47.591   870  4034 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-09 14:56:47.591   870  4034 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-09 14:56:47.591   870  4034 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 14:56:47.591   870  4034 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-09 14:56:47.591   870  4034 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 14:56:47.591   870  4034 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 14:56:47.591   870  4034 E DropBoxManagerService: 	... 5 more
08-09 14:56:47.592  1758  1832 I Process : Sending signal. PID: 1758 SIG: 9
08-09 14:56:47.612  4010  4010 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-09 14:56:47.632  4010  4039 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-09 14:56:47.641  4010  4039 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 14:56:47.643  4010  4039 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-09 14:56:47.643  4010  4039 E AndroidRuntime: Process: android.process.acore, PID: 4010
08-09 14:56:47.643  4010  4039 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 14:56:47.643  4010  4039 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 14:56:47.643  4010  4039 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 14:56:47.643  4010  4039 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 14:56:47.643  4010  4039 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 14:56:47.643  4010  4039 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 14:56:47.643  4010  4039 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 14:56:47.643  4010  4039 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 14:56:47.643  4010  4039 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 14:56:47.643  4010  4039 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 14:56:47.643  4010  4039 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 14:56:47.643  4010  4039 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 14:56:47.643  4010  4039 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 14:56:47.643  4010  4039 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 14:56:47.643  4010  4039 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-09 14:56:47.643  4010  4039 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-09 14:56:47.643  4010  4039 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-09 14:56:47.643  4010  4039 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-09 14:56:47.643  4010  4039 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-09 14:56:47.643  4010  4039 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-09 14:56:47.643  4010  4039 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-09 14:56:47.643  4010  4039 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:56:47.643  4010  4039 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-09 14:56:47.643  4010  4039 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 14:56:47.644   870  1757 I ActivityManager: Start proc 4040:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-09 14:56:47.650  4010  4039 I Process : Sending signal. PID: 4010 SIG: 9
08-09 14:56:47.651   870  4051 E DropBoxManagerService: Can't write: system_app_crash
08-09 14:56:47.651   870  4051 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
08-09 14:56:47.651   870  4051 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-09 14:56:47.651   870  4051 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 14:56:47.651   870  4051 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 14:56:47.651   870  4051 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-09 14:56:47.651   870  4051 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-09 14:56:47.651   870  4051 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-09 14:56:47.651   870  4051 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 14:56:47.651   870  4051 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-09 14:56:47.651   870  4051 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 14:56:47.651   870  4051 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 14:56:47.651   870  4051 E DropBoxManagerService: 	... 5 more
08-09 14:56:47.655   279   279 E lowmemorykiller: Error writing /proc/4010/oom_score_adj; errno=22
08-09 14:56:47.660   870  1303 W InputDispatcher: channel '9bc6a34 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
08-09 14:56:47.660   870  1303 E InputDispatcher: channel '9bc6a34 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
08-09 14:56:47.660   870  1755 D GraphicsStats: Buffer count: 1
08-09 14:56:47.660   870  1680 I WindowState: WIN DEATH: Window{9bc6a34 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-09 14:56:47.660   870  1680 W InputDispatcher: Attempted to unregister already unregistered input channel '9bc6a34 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
08-09 14:56:47.676   870  1756 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1758) has died
08-09 14:56:47.677   870  1756 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-09 14:56:47.679   870  1756 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-09 14:56:47.681   279   279 E lowmemorykiller: Error writing /proc/4010/oom_score_adj; errno=22
08-09 14:56:47.695   870  1737 I ActivityManager: Start proc 4055:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-09 14:56:47.696   279   279 E lowmemorykiller: Error writing /proc/4010/oom_score_adj; errno=22
08-09 14:56:47.708  4040  4040 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-09 14:56:47.718   870  1822 I ActivityManager: Process android.process.acore (pid 4010) has died
08-09 14:56:47.718   870  1822 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 14:56:47.754  4055  4055 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-09 14:56:47.754  4055  4055 D AndroidRuntime: Shutting down VM
08-09 14:56:47.755  1515  1515 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-09 14:56:47.757  1515  1515 D AndroidRuntime: Shutting down VM
08-09 14:56:47.758  1515  1515 E AndroidRuntime: FATAL EXCEPTION: main
08-09 14:56:47.758  1515  1515 E AndroidRuntime: Process: com.google.process.gapps, PID: 1515
08-09 14:56:47.758  1515  1515 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-09 14:56:47.758  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-09 14:56:47.758  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-09 14:56:47.758  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-09 14:56:47.758  1515  1515 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:56:47.758  1515  1515 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-09 14:56:47.758  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 14:56:47.758  1515  1515 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 14:56:47.758  1515  1515 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 14:56:47.758  1515  1515 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-09 14:56:47.758  1515  1515 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-09 14:56:47.758  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-09 14:56:47.758  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-09 14:56:47.758  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-09 14:56:47.758  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-09 14:56:47.758  1515  1515 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-09 14:56:47.758  1515  1515 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-09 14:56:47.758  1515  1515 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-09 14:56:47.758  1515  1515 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-09 14:56:47.758  1515  1515 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-09 14:56:47.758  1515  1515 E AndroidRuntime: 	... 8 more
08-09 14:56:47.761  1905  4068 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-09 14:56:47.762  1905  4068 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-09 14:56:47.765   870  4071 E DropBoxManagerService: Can't write: system_app_crash
08-09 14:56:47.765   870  4071 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
08-09 14:56:47.765   870  4071 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-09 14:56:47.765   870  4071 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 14:56:47.765   870  4071 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 14:56:47.765   870  4071 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-09 14:56:47.765   870  4071 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-09 14:56:47.765   870  4071 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-09 14:56:47.765   870  4071 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 14:56:47.765   870  4071 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-09 14:56:47.765   870  4071 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 14:56:47.765   870  4071 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 14:56:47.765   870  4071 E DropBoxManagerService: 	... 5 more
08-09 14:56:47.766  1515  1515 I Process : Sending signal. PID: 1515 SIG: 9
08-09 14:56:47.766  4055  4055 E AndroidRuntime: FATAL EXCEPTION: main
08-09 14:56:47.766  4055  4055 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4055
08-09 14:56:47.766  4055  4055 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-09 14:56:47.766  4055  4055 E AndroidRuntime: 	... 10 more
08-09 14:56:47.767   870  1822 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-09 14:56:47.768  4055  4055 I Process : Sending signal. PID: 4055 SIG: 9
08-09 14:56:47.769   870  4072 E DropBoxManagerService: Can't write: system_app_crash
08-09 14:56:47.769   870  4072 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
08-09 14:56:47.769   870  4072 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-09 14:56:47.769   870  4072 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 14:56:47.769   870  4072 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 14:56:47.769   870  4072 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-09 14:56:47.769   870  4072 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-09 14:56:47.769   870  4072 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-09 14:56:47.769   870  4072 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 14:56:47.769   870  4072 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-09 14:56:47.769   870  4072 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 14:56:47.769   870  4072 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 14:56:47.769   870  4072 E DropBoxManagerService: 	... 5 more
08-09 14:56:47.779  1905  4068 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-09 14:56:47.780  1905  4068 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-09 14:56:47.783   870  1737 I ActivityManager: Killing 1801:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
08-09 14:56:47.794   870  1313 D WifiService: Client connection lost with reason: 4
08-09 14:56:47.803   870  1313 D WifiService: Client connection lost with reason: 4
08-09 14:56:47.833   870  1822 I ActivityManager: Process com.google.process.gapps (pid 1515) has died
08-09 14:56:47.834   870  1822 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 1000ms
08-09 14:56:47.834   870  1822 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
08-09 14:56:47.834   870  1822 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
08-09 14:56:47.834   870  1822 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 31000ms
08-09 14:56:47.835   870   881 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4055) has died
08-09 14:56:47.837   870   881 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-09 14:56:47.839  1905  1905 W RocketImpressions: ClearcutLogger connection suspended: 1
08-09 14:56:47.852   870   883 I ActivityManager: Start proc 4073:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-09 14:56:47.863   870  1389 I ActivityManager: Start proc 4085:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 14:56:47.906  4073  4073 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```
