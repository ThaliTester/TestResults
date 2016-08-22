#### Test 8220306079086ef_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-22 17:05:04.049  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 17:05:04.077  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-22 17:05:04.084  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-22 17:05:04.141  1508  2791 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-22 17:05:04.141  1508  2791 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-22 17:05:04.141  1508  2791 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 17:05:04.141  1508  2791 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-22 17:05:04.161  2710  2710 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-22 17:05:04.161  2710  2710 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-22 17:05:04.162  2710  2710 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
08-22 17:05:04.674  3453  3453 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-22 17:05:04.678  3453  3453 D AndroidRuntime: CheckJNI is OFF
08-22 17:05:04.714  3453  3453 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-22 17:05:04.758  3453  3453 I Radio-JNI: register_android_hardware_Radio DONE
08-22 17:05:04.777  3453  3453 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-22 17:05:04.782   873  1956 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-22 17:05:04.819  1981  1996 W SearchService: Abort, client detached.
08-22 17:05:04.841  1981  2305 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@2d5af9
08-22 17:05:04.841  1981  1981 I HotwordDetector: Closing mic
08-22 17:05:04.842  1981  2310 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-22 17:05:04.843  3453  3453 D AndroidRuntime: Shutting down VM
08-22 17:05:04.863   873  1901 I ActivityManager: Start proc 3463:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-22 17:05:04.876  1981  1981 W ErrorReporter: reportError [type: 29, code: 917507]: null
08-22 17:05:04.892   375  2312 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-22 17:05:04.893   375  2312 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-22 17:05:04.902   375  1280 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-22 17:05:04.904  1981  2308 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-22 17:05:04.905  1981  2309 I MicroRecognitionRnrImpl: Detection finished
08-22 17:05:04.949  3463  3463 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-22 17:05:04.990  3463  3463 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-22 17:05:05.001  3463  3463 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 9544-9550)
08-22 17:05:05.002  3463  3463 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-22 17:05:05.016  3463  3463 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d410689}
08-22 17:05:05.019  3463  3463 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-22 17:05:05.019  3463  3463 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-22 17:05:05.025  3463  3463 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-22 17:05:05.026  3463  3463 E SysUtils: ApplicationContext is null in ApplicationStatus
08-22 17:05:05.055  3463  3478 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
08-22 17:05:05.063  3463  3463 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-22 17:05:05.073  3463  3463 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-22 17:05:05.073  3463  3463 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-22 17:05:05.073  3463  3463 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-22 17:05:05.073  3463  3463 I Adreno  : Build Date                       : 10/20/15
08-22 17:05:05.073  3463  3463 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-22 17:05:05.073  3463  3463 I Adreno  : Local Branch                     : M14
08-22 17:05:05.073  3463  3463 I Adreno  : Remote Branch                    : 
08-22 17:05:05.073  3463  3463 I Adreno  : Remote Branch                    : 
08-22 17:05:05.073  3463  3463 I Adreno  : Reconstruct Branch               : 
,08-22 17:05:05.138   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f8de82d:true
,08-22 17:05:05.179  3463  3463 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-22 17:05:05.194  3463  3463 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-22 17:05:05.272  3463  3500 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-22 17:05:05.282  3463  3487 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-22 17:05:05.332  3463  3500 I OpenGLRenderer: Initialized EGL, version 1.4
,08-22 17:05:05.429   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +581ms
,08-22 17:05:05.442  1858  1858 I Keyboard.Facilitator: onFinishInput()
,08-22 17:05:05.531  3463  3463 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3463
,08-22 17:05:05.714   873  1374 I ActivityManager: Killing 2829:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,08-22 17:05:05.739  3463  3463 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-22 17:05:05.749   873  1374 I ActivityManager: Killing 3163:com.qualcomm.telephony/1001 (adj 15): empty #18
,08-22 17:05:06.029  3463  3503 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1714816720
,08-22 17:05:06.039  3463  3503 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-22 17:05:06.039  3463  3503 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-22 17:05:06.039  3463  3503 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-22 17:05:06.039  3463  3503 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-22 17:05:06.039  3463  3503 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-22 17:05:06.039  3463  3503 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61526bd added. We now have 1 listener(s)
,08-22 17:05:06.043  3463  3503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-22 17:05:06.044  3463  3503 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 17:05:06.044  3463  3503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 17:05:06.045  3463  3503 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 17:05:06.048  3463  3503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-22 17:05:06.048  3463  3503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-22 17:05:06.048  3463  3503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-22 17:05:06.048  3463  3503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-22 17:05:06.048  3463  3503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-22 17:05:06.048  3463  3503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-22 17:05:06.048  3463  3503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-22 17:05:06.048  3463  3503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-22 17:05:06.048  3463  3503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-22 17:05:06.048  3463  3503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-22 17:05:06.048  3463  3503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-22 17:05:06.048  3463  3503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-22 17:05:06.048  3463  3503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-22 17:05:06.048  3463  3503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-22 17:05:06.048  3463  3503 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b45780 added. We now have 1 listener(s)
08-22 17:05:06.049  3463  3503 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 17:05:06.055   873  1309 D WifiService: New client listening to asynchronous messages
,08-22 17:05:06.056  3463  3503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 17:05:06.056  3463  3503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-22 17:05:06.057  3463  3503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-22 17:05:06.057  3463  3503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-22 17:05:06.057  3463  3503 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-22 17:05:06.059  3463  3503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 17:05:06.060  3463  3503 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-22 17:05:06.062  3463  3503 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 17:05:06.062  3463  3503 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 17:05:06.062  3463  3503 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:06.062  3463  3503 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-22 17:05:06.062  3463  3503 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 17:05:06.062  3463  3503 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 17:05:06.062  3463  3503 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:06.062  3463  3503 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:06.062  3463  3503 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 17:05:06.062  3463  3503 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-22 17:05:06.062  3463  3503 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 17:05:06.063  3463  3503 I io.jxcore.node.LifeCycleMonitor: start: OK
08-22 17:05:06.064  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 17:05:06.085  3463  3463 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-22 17:05:06.989  3463  3512 W jxcore-log: Initializing JXcore engine
,08-22 17:05:06.989  3463  3512 W jxcore-log: JXcore engine is ready
,08-22 17:05:07.052  3512  3512 W Thread-286: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-22 17:05:07.055  3512  3512 W Thread-286: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9837]" dev="sockfs" ino=9837 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-22 17:05:07.055  3512  3512 W Thread-286: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-22 17:05:07.055  3512  3512 W Thread-286: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25762]" dev="sockfs" ino=25762 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-22 17:05:07.105  3463  3512 W jxcore-log: Starting JXcore engine
,08-22 17:05:07.209  3463  3512 W jxcore-log: Platform android
08-22 17:05:07.209  3463  3512 W jxcore-log: 
,08-22 17:05:07.210  3463  3512 W jxcore-log: Process ARCH arm
08-22 17:05:07.210  3463  3512 W jxcore-log: 
,08-22 17:05:07.395  3463  3512 I jxcore-log: JXcore Cordova bridge is ready!
08-22 17:05:07.395  3463  3512 I jxcore-log: 
08-22 17:05:07.396  3463  3512 W jxcore-log: JXcore engine is started
,08-22 17:05:07.406  3463  3503 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-22 17:05:07.412  3463  3463 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-22 17:05:16.982  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-22 17:05:16.982  3463  3512 I jxcore-log: 
,08-22 17:05:16.985  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-22 17:05:16.985  3463  3512 I jxcore-log: 
,08-22 17:05:16.988  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 17:05:16.988  3463  3512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 17:05:16.988  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:16.988  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-22 17:05:16.988  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 17:05:16.988  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 17:05:16.988  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:16.988  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:16.988  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 17:05:16.988  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 17:05:16.989  3463  3512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 17:05:16.992  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-22 17:05:16.992  3463  3512 I jxcore-log: 
,08-22 17:05:16.995  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-22 17:05:16.995  3463  3512 I jxcore-log: 
,08-22 17:05:17.491  3463  3512 D ExecuteNativeTests: Running unit tests
,08-22 17:05:17.550  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 17:05:17.550  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2adf77 added. We now have 2 listener(s)
08-22 17:05:17.551  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-22 17:05:17.552  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 17:05:17.552  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 17:05:17.552  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 17:05:17.552  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 added. We now have 2 listener(s)
,08-22 17:05:17.552  3463  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 17:05:17.554  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 17:05:17.558  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 17:05:17.560  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 17:05:17.561  3463  3512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 17:05:17.561  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:17.561  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-22 17:05:17.561  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 17:05:17.561  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 17:05:17.561  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:17.561  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:17.561  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 17:05:17.561  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 17:05:17.561  3463  3512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 17:05:17.562  3463  3512 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 17:05:17.564  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 17:05:17.569  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-22 17:05:17.570  3463  3512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-22 17:05:17.570  3463  3512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-22 17:05:17.575  3463  3512 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-22 17:05:17.576  3463  3512 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed,
08-22 17:05:17.576  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 17:05:17.577  3463  3512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 17:05:17.577  3463  3512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 17:05:17.578  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 17:05:17.579  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 17:05:17.580  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 17:05:17.581  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 17:05:17.581  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.581  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 17:05:17.581  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 17:05:17.581  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2adf77 removed from the list
08-22 17:05:17.581  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.581  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 removed from the list
,08-22 17:05:17.581  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
08-22 17:05:17.581  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.582  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.582  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.583  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:17.583  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:17.583  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.583  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.585  3463  3512 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-22 17:05:17.586  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 17:05:17.586  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 17:05:17.586  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 17:05:17.586  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:17.586  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.586  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.586  3463  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2adf77 not in the list
08-22 17:05:17.586  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.586  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.586  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 17:05:17.586  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.586  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.586  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.586  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.587  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:17.587  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:17.587  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.587  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
,08-22 17:05:17.594  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-22 17:05:17.594  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-22 17:05:17.595  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-22 17:05:17.595  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-22 17:05:17.595  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-22 17:05:17.595  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-22 17:05:17.595  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-22 17:05:17.595  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-22 17:05:17.595  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-22 17:05:17.595  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-22 17:05:17.595  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-22 17:05:17.595  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-22 17:05:17.595  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-22 17:05:17.595  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-22 17:05:17.595  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-22 17:05:17.596  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-22 17:05:17.596  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-22 17:05:17.596  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-22 17:05:17.596  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-22 17:05:17.596  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-22 17:05:17.596  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-22 17:05:17.596  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-22 17:05:17.596  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-22 17:05:17.596  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-22 17:05:17.596  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-22 17:05:17.596  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-22 17:05:17.596  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-22 17:05:17.596  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-22 17:05:17.596  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-22 17:05:17.596  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-22 17:05:17.597  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-22 17:05:17.597  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 17:05:17.597  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 17:05:17.597  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 17:05:17.597  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:17.597  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.597  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.597  3463  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2adf77 not in the list
08-22 17:05:17.597  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.598  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.598  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 17:05:17.598  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.598  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.598  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.598  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.598  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:17.598  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:17.598  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.599  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.599  3463  3512 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-22 17:05:17.601  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 17:05:17.602  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 17:05:17.602  3463  3512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 17:05:17.602  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:17.602  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-22 17:05:17.602  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 17:05:17.602  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 17:05:17.602  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:17.602  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:17.602  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 17:05:17.602  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 17:05:17.602  3463  3512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 17:05:17.603  3463  3512 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 17:05:17.603  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 17:05:17.603  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 17:05:17.604  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 17:05:17.604  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 17:05:17.604  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 17:05:17.604  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-22 17:05:17.608  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,08-22 17:05:17.609  3463  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,08-22 17:05:17.610  3463  3512 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-22 17:05:17.610  3463  3512 I io.jxcore.node.ConnectionHelper: start: OK
,08-22 17:05:17.610  3463  3463 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-22 17:05:17.610  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 17:05:17.611  3463  3512 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
08-22 17:05:17.612  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 17:05:17.612  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 17:05:17.612  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-22 17:05:17.612  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.612  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 17:05:17.612  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 17:05:17.612  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 17:05:17.612  3463  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 17:05:17.612  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-22 17:05:17.613  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 17:05:17.613  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 17:05:17.614  3463  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 17:05:17.614  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:17.614  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.614  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 17:05:17.614  3463  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2adf77 not in the list
08-22 17:05:17.615  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.615  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.615  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 17:05:17.615  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.614  3463  3463 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 17:05:17.615  3463  3463 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 17:05:17.616  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.617  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.617  3463  3463 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 17:05:17.617  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:17.617  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:17.617  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.617  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
,08-22 17:05:17.618  3463  3512 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-22 17:05:17.620  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 17:05:17.620  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 17:05:17.621  3463  3512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 17:05:17.621  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:17.621  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-22 17:05:17.621  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 17:05:17.621  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 17:05:17.621  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:17.621  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:17.621  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 17:05:17.621  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 17:05:17.621  3463  3512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 17:05:17.621  3463  3512 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 17:05:17.621  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 17:05:17.621  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-22 17:05:17.621  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 17:05:17.621  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 17:05:17.621  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 17:05:17.622  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 17:05:17.623  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-22 17:05:17.624  3463  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-22 17:05:17.624  3463  3512 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-22 17:05:17.625  3463  3512 I io.jxcore.node.ConnectionHelper: start: OK,
08-22 17:05:17.624  3463  3463 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-22 17:05:17.625  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 17:05:17.625  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 17:05:17.625  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-22 17:05:17.625  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 17:05:17.625  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 17:05:17.625  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 17:05:17.625  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 17:05:17.625  3463  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-22 17:05:17.625  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 17:05:17.625  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 17:05:17.626  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 17:05:17.626  3463  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 17:05:17.626  3463  3463 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 17:05:17.626  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 17:05:17.626  3463  3512 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 17:05:17.626  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 17:05:17.626  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 17:05:17.627  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:17.627  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.626  3463  3463 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 17:05:17.627  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-22 17:05:17.627  3463  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2adf77 not in the list
08-22 17:05:17.627  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.627  3463  3463 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 17:05:17.627  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
,08-22 17:05:17.627  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
08-22 17:05:17.627  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.627  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.627  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 17:05:17.628  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:17.628  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:17.628  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.628  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.628  3463  3512 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-22 17:05:17.629  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 17:05:17.629  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-22 17:05:17.629  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 17:05:17.629  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:17.629  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.629  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.629  3463  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2adf77 not in the list
08-22 17:05:17.629  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.629  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.629  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 17:05:17.630  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.630  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.630  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.630  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.630  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:17.630  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:17.630  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.630  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
,08-22 17:05:17.631  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-22 17:05:17.631  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 17:05:17.631  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 17:05:17.631  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 17:05:17.631  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-22 17:05:17.631  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.632  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.632  3463  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2adf77 not in the list
08-22 17:05:17.632  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.632  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.632  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 17:05:17.632  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.632  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.632  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.632  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.632  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:17.632  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:17.632  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.633  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
,08-22 17:05:17.633  3463  3512 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-22 17:05:17.633  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 17:05:17.633  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 17:05:17.633  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 17:05:17.633  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:17.633  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 17:05:17.633  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.634  3463  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2adf77 not in the list
08-22 17:05:17.634  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.634  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.634  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
08-22 17:05:17.634  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 17:05:17.634  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.634  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.634  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.634  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:17.634  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:17.634  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.634  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.635  3463  3512 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-22 17:05:17.635  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 17:05:17.635  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 17:05:17.635  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 17:05:17.635  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:17.635  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.635  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.636  3463  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2adf77 not in the list
08-22 17:05:17.636  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.636  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.636  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
08-22 17:05:17.636  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 17:05:17.636  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.636  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.636  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.636  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:17.636  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:17.636  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.636  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
,08-22 17:05:17.637  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-22 17:05:17.637  3463  3512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 17:05:17.637  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 17:05:17.637  3463  3512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 17:05:17.637  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-22 17:05:17.637  3463  3512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 17:05:17.638  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 17:05:17.638  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-22 17:05:17.638  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 17:05:17.638  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:17.638  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.638  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.641  3463  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2adf77 not in the list
08-22 17:05:17.641  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.641  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
,08-22 17:05:17.641  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
08-22 17:05:17.641  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.641  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.641  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.641  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.641  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:17.641  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:17.642  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.642  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list,
08-22 17:05:17.642  3463  3512 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 17:05:17.642  3463  3512 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-22 17:05:17.643  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-22 17:05:17.646  3463  3512 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-22 17:05:17.647  3463  3512 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-22 17:05:17.647  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-22 17:05:17.647  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-22 17:05:17.647  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-22 17:05:17.647  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-22 17:05:17.647  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-22 17:05:17.647  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-22 17:05:17.647  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-22 17:05:17.647  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-22 17:05:17.647  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-22 17:05:17.648  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-22 17:05:17.648  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-22 17:05:17.648  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-22 17:05:17.648  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-22 17:05:17.648  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-22 17:05:17.648  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-22 17:05:17.648  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-22 17:05:17.648  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-22 17:05:17.648  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-22 17:05:17.648  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-22 17:05:17.648  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-22 17:05:17.648  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-22 17:05:17.648  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-22 17:05:17.648  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-22 17:05:17.648  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-22 17:05:17.649  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-22 17:05:17.649  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-22 17:05:17.649  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-22 17:05:17.649  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-22 17:05:17.649  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-22 17:05:17.649  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910],
08-22 17:05:17.649  3463  3512 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-22 17:05:17.649  3463  3512 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 17:05:17.649  3463  3512 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-22 17:05:17.650  3463  3512 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 17:05:17.650  3463  3512 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 17:05:17.650  3463  3512 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-22 17:05:17.650  3463  3512 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 17:05:17.650  3463  3512 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 17:05:17.650  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-22 17:05:17.651  3463  3512 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
08-22 17:05:17.651  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-22 17:05:17.652  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-22 17:05:17.652  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-22 17:05:17.653  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-22 17:05:17.653  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-22 17:05:17.653  3463  3512 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-22 17:05:17.653  3463  3512 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-22 17:05:17.653  3463  3512 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-22 17:05:17.654  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 17:05:17.654  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-22 17:05:17.654  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 17:05:17.654  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:17.654  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 17:05:17.655  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 17:05:17.655  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-22 17:05:17.655  3463  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2adf77 not in the list
,08-22 17:05:17.655  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.655  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.655  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 17:05:17.655  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.655  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.656  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 17:05:17.656  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.656  3463  3520 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 350
,08-22 17:05:17.656  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:17.656  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:17.656  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 17:05:17.656  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.657  3463  3512 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-22 17:05:17.657  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 17:05:17.658  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 17:05:17.658  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 17:05:17.658  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 17:05:17.658  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.658  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.658  3463  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2adf77 not in the list
08-22 17:05:17.658  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.658  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
,08-22 17:05:17.658  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
08-22 17:05:17.658  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.658  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 17:05:17.658  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.658  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.659  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:17.659  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:17.659  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.659  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
,08-22 17:05:17.659  3463  3512 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-22 17:05:17.660  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 17:05:17.660  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 17:05:17.660  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 17:05:17.660  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:17.660  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.660  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 17:05:17.660  3463  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2adf77 not in the list
,08-22 17:05:17.660  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.660  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.660  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
08-22 17:05:17.660  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 17:05:17.660  3463  3519 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 350)
08-22 17:05:17.660  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.661  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.661  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 17:05:17.661  3463  3519 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 350)
08-22 17:05:17.661  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:17.661  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:17.661  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.661  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
,08-22 17:05:17.665  3463  3512 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-22 17:05:17.665  3463  3512 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,08-22 17:05:17.665  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 17:05:17.665  3463  3512 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-22 17:05:17.665  3463  3512 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-22 17:05:17.665  3463  3512 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-22 17:05:17.665  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-22 17:05:17.665  3463  3512 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-22 17:05:17.666  3463  3512 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-22 17:05:17.666  3463  3512 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,08-22 17:05:17.666  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-22 17:05:17.666  3463  3512 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-22 17:05:17.666  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 17:05:17.666  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 17:05:17.666  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 17:05:17.666  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:17.666  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.666  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 17:05:17.666  3463  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2adf77 not in the list
08-22 17:05:17.666  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.666  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.666  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 17:05:17.666  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.666  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.666  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.667  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 17:05:17.667  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:17.667  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:17.667  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.667  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
,08-22 17:05:17.668  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:17.668  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.668  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.668  3463  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2adf77 not in the list
,08-22 17:05:17.668  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.668  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.668  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
08-22 17:05:17.668  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 17:05:17.668  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.668  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.668  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.668  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:17.668  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 17:05:17.668  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.668  3463  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2adf77 not in the list
08-22 17:05:17.668  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 17:05:17.668  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 17:05:17.669  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 17:05:17.669  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 17:05:17.669  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.669  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.669  3463  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2adf77 not in the list
08-22 17:05:17.669  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.669  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.669  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 17:05:17.669  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.669  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.669  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.669  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.669  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:17.669  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:17.669  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.669  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.670  3463  3512 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-22 17:05:17.671  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 17:05:17.671  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
08-22 17:05:17.671  3463  3512 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
08-22 17:05:17.671  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-22 17:05:17.671  3463  3463 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
08-22 17:05:17.671  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:17.671  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-22 17:05:17.671  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.671  3463  3512 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
08-22 17:05:17.671  3463  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2adf77 not in the list
08-22 17:05:17.672  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.672  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-22 17:05:17.672  3463  3463 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-22 17:05:17.672  3463  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 17:05:17.672  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 17:05:17.672  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.672  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.672  3463  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 17:05:17.672  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
,08-22 17:05:17.672  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 17:05:17.672  3463  3463 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 17:05:17.672  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 17:05:17.672  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 17:05:17.672  3463  3463 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 17:05:17.673  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:17.673  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.673  3463  3463 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 17:05:17.673  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.673  3463  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2adf77 not in the list
08-22 17:05:17.673  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 17:05:17.673  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.673  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
08-22 17:05:17.673  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.673  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.673  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.673  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.673  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:17.673  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:17.673  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.673  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
,08-22 17:05:17.674  3463  3512 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-22 17:05:17.675  3463  3512 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-22 17:05:17.675  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 17:05:17.675  3463  3512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 17:05:17.675  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 17:05:17.675  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 17:05:17.675  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 17:05:17.675  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:17.675  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.675  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 17:05:17.675  3463  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2adf77 not in the list
08-22 17:05:17.675  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.675  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.675  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
08-22 17:05:17.676  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.676  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 17:05:17.676  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.676  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.676  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:17.676  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:17.676  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.676  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.681  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 17:05:17.682  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-22 17:05:17.682  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 17:05:17.682  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:17.682  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.683  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.683  3463  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2adf77 not in the list
08-22 17:05:17.683  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.683  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
,08-22 17:05:17.683  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
08-22 17:05:17.684  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.684  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.684  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.684  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.685  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:17.685  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:17.686  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 17:05:17.686  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.688  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 17:05:17.688  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 17:05:17.688  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 17:05:17.689  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:17.689  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.689  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.689  3463  3512 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a2adf77 not in the list
,08-22 17:05:17.690  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.690  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.690  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
08-22 17:05:17.690  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.691  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:17.691  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:17.691  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 17:05:17.692  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:17.692  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:17.692  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:17.693  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16197e4 not in the list
08-22 17:05:17.695  3463  3512 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-22 17:05:17.696  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 17:05:17.696  3463  3512 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-22 17:05:17.696  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 17:05:17.697  3463  3512 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-22 17:05:17.697  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-22 17:05:17.702  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-22 17:05:17.703  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-22 17:05:17.705  3463  3512 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-22 17:05:17.705  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-22 17:05:17.705  3463  3512 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-22 17:05:17.706  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-22 17:05:17.706  3463  3512 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-22 17:05:17.706  3463  3512 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-22 17:05:17.708  3463  3512 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-22 17:05:17.708  3463  3512 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-22 17:05:17.710  3463  3512 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-22 17:05:17.710  3463  3512 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-22 17:05:17.711  3463  3512 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-22 17:05:17.711  3463  3512 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-22 17:05:17.712  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 17:05:17.712  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@89a554e added. We now have 2 listener(s)
08-22 17:05:17.712  3463  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 17:05:17.714   873  1707 D WifiService: setWifiEnabled: true pid=3463, uid=10000
,08-22 17:05:17.714   873  1707 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-22 17:05:17.718  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 17:05:17.718  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@808466f added. We now have 3 listener(s)
08-22 17:05:17.718  3463  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 17:05:17.718  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 17:05:17.719  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 17:05:17.719  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 17:05:17.719  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9d5ff7c added. We now have 4 listener(s)
08-22 17:05:17.719  3463  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 17:05:17.720  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 17:05:17.720  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9ddc005 added. We now have 5 listener(s)
08-22 17:05:17.720  3463  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 17:05:17.721   873  1374 D WifiService: setWifiEnabled: false pid=3463, uid=10000
08-22 17:05:17.721   873  1374 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-22 17:05:17.730   873   890 I ActivityManager: Start proc 3523:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-22 17:05:17.731   873  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-22 17:05:17.735  3463  3463 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 17:05:17.736  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 17:05:17.736  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:17.736  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-22 17:05:17.736  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 17:05:17.736  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 17:05:17.736  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:17.736  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:17.736  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 17:05:17.736  3463  3463 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 17:05:17.736  3463  3463 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 17:05:17.747   873  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-22 17:05:17.748   873  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-22 17:05:17.748   873  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-22 17:05:17.749   873  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-22 17:05:17.749   873  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-22 17:05:17.749   873  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-22 17:05:17.749   873  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-22 17:05:17.756   873   886 I ActivityManager: Start proc 3535:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-22 17:05:17.757  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 17:05:17.760  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 17:05:17.760  3463  3512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 17:05:17.760  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:17.760  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-22 17:05:17.760  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 17:05:17.760  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 17:05:17.760  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:17.760  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:17.760  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 17:05:17.760  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 17:05:17.760  3463  3512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 17:05:17.760  3463  3512 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 17:05:17.761  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 17:05:17.811   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-22 17:05:17.812   371   871 D CommandListener: Setting iface cfg
,08-22 17:05:17.813   873  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '102 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 102 Failed to set address (No such device)'
08-22 17:05:17.813   873  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-22 17:05:17.815   873  1307 D WifiNative-HAL: p2pGetDeviceAddress
08-22 17:05:17.815   873  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-22 17:05:17.819  3523  3523 D AdapterServiceConfig: Adding HeadsetService
,08-22 17:05:17.819  3523  3523 D AdapterServiceConfig: Adding A2dpService
08-22 17:05:17.819  3523  3523 D AdapterServiceConfig: Adding HidService
08-22 17:05:17.819  3523  3523 D AdapterServiceConfig: Adding HealthService
08-22 17:05:17.820  3523  3523 D AdapterServiceConfig: Adding PanService
08-22 17:05:17.820  3523  3523 D AdapterServiceConfig: Adding GattService
08-22 17:05:17.820  3523  3523 D AdapterServiceConfig: Adding BluetoothMapService
,08-22 17:05:17.821  3535  3535 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-22 17:05:17.844   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 17:05:17.846  3463  3463 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 17:05:17.846  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 17:05:17.846  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:17.846  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-22 17:05:17.846  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 17:05:17.846  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 17:05:17.846  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:17.846  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:17.846  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 17:05:17.846  3463  3463 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-22 17:05:17.846  3463  3463 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 17:05:17.847  3463  3463 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 17:05:17.847  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 17:05:17.847  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:17.847  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-22 17:05:17.847  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 17:05:17.847  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 17:05:17.847  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:17.847  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:17.847  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 17:05:17.847  3463  3463 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 17:05:17.847  3463  3463 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 17:05:17.848  2002  2290 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 17:05:17.853   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b9ba1ca:true
,08-22 17:05:17.853  3523  3523 D BluetoothAdapterState: make() - Creating AdapterState
,08-22 17:05:17.856  3523  3523 I bt_bluedroid: init
,08-22 17:05:17.856  3523  3555 I BluetoothAdapterState: Entering OffState
,08-22 17:05:17.859  3523  3556 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-22 17:05:17.859  3523  3556 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-22 17:05:17.860  3523  3556 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-22 17:05:17.860  3523  3556 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-22 17:05:17.861  3523  3523 I bt_bluedroid: get_profile_interface socket
,08-22 17:05:17.862  3523  3523 I bt_bluedroid: get_profile_interface sdp
08-22 17:05:17.864  3523  3561 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-22 17:05:17.865  3523  3534 I bt_bluedroid: config_hci_snoop_log
,08-22 17:05:17.865  3523  3561 D BluetoothAdapterProperties: Name is: Nexus 6
,08-22 17:05:17.866   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-22 17:05:17.869  3523  3555 D BluetoothAdapterState: Current state: OFF, message: 0
08-22 17:05:17.869  3523  3555 D BluetoothAdapterProperties: Setting state to 14
08-22 17:05:17.869  3523  3555 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-22 17:05:17.870  3523  3555 D BluetoothBondStateMachine: make
08-22 17:05:17.870  3535  3535 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-22 17:05:17.872  3523  3562 I BluetoothBondStateMachine: StableState(): Entering Off State
08-22 17:05:17.873  3523  3555 I BluetoothAdapterState: Entering PendingCommandState
08-22 17:05:17.874  3523  3523 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-22 17:05:17.876  3523  3523 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
,08-22 17:05:17.876  3523  3523 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-22 17:05:17.877  3523  3523 D BtGatt.GattService: Received start request. Starting profile...
08-22 17:05:17.877  3523  3523 D BtGatt.GattService: start()
08-22 17:05:17.877  3523  3523 I bt_bluedroid: get_profile_interface gatt
08-22 17:05:17.877  3523  3523 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
,08-22 17:05:17.878  3523  3523 D BtGatt.AdvertiseManager: advertise manager created
08-22 17:05:17.882  3523  3523 V BluetoothAdapterState: isTurningOff()=false
,08-22 17:05:17.882  3523  3523 V BluetoothAdapterState: isTurningOn()=false
08-22 17:05:17.882  3523  3523 V BluetoothAdapterState: isBleTurningOn()=true
08-22 17:05:17.882  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
08-22 17:05:17.882  3523  3555 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-22 17:05:17.883  3523  3555 I bt_bluedroid: enable
08-22 17:05:17.883  3523  3556 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-22 17:05:17.883  3523  3556 I bt_hci  : start_up
,08-22 17:05:17.891   873  1421 I ActivityManager: Killing 2795:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-22 17:05:17.892  3523  3556 I bt_vendor: alloc value 0xb39b0189
08-22 17:05:17.892  3523  3556 I bt_vendor: init
,08-22 17:05:17.892  3523  3556 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-22 17:05:17.892  3523  3556 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-22 17:05:17.999  3523  3556 D bt_hci  : start_up starting async portion
,08-22 17:05:17.999  3523  3568 I bt_hci  : event_finish_startup
08-22 17:05:18.000  3523  3568 I bt_hci_h4: hal_open
08-22 17:05:18.000  3523  3568 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-22 17:05:18.005  3523  3568 I bt_userial_vendor: device fd = 51 open
,08-22 17:05:18.040  3523  3568 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-22 17:05:18.073  3523  3568 D bt_hwcfg: Chipset BCM4354A2
08-22 17:05:18.074  3523  3568 D bt_hwcfg: Target name = [BCM4354A2]
08-22 17:05:18.074  3523  3568 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-22 17:05:18.174  3463  3463 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-22 17:05:18.748  3523  3568 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-22 17:05:18.750  3523  3568 D bt_hwcfg: Settlement delay -- 100 ms
,08-22 17:05:18.750  3523  3568 I bt_hwcfg: Setting fw settlement delay to 100 
,08-22 17:05:18.868  3523  3568 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-22 17:05:18.869  3523  3568 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-22 17:05:18.898  3523  3568 I bt_hwcfg: vendor lib fwcfg completed
,08-22 17:05:18.898  3523  3568 I bt_vendor: firmware callback
08-22 17:05:18.899  3523  3568 I bt_hci  : firmware_config_callback
,08-22 17:05:18.911  3523  3570 I bt_btu  : btu_task pending for preload complete event
,08-22 17:05:18.912  3523  3570 I bt_btu_task: Bluetooth chip preload is complete
,08-22 17:05:18.912  3523  3570 I bt_btu  : btu_task received preload complete event
,08-22 17:05:18.924  3523  3570 I         : BTE_InitTraceLevels -- TRC_HCI
,08-22 17:05:18.925  3523  3570 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-22 17:05:18.925  3523  3570 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-22 17:05:18.925  3523  3570 I         : BTE_InitTraceLevels -- TRC_AVDT
08-22 17:05:18.926  3523  3570 I         : BTE_InitTraceLevels -- TRC_AVRC
08-22 17:05:18.926  3523  3570 I         : BTE_InitTraceLevels -- TRC_A2D
,08-22 17:05:18.926  3523  3570 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-22 17:05:18.926  3523  3570 I         : BTE_InitTraceLevels -- TRC_BTM
08-22 17:05:18.927  3523  3570 I         : BTE_InitTraceLevels -- TRC_GAP
,08-22 17:05:18.927  3523  3570 I         : BTE_InitTraceLevels -- TRC_PAN
08-22 17:05:18.928  3523  3570 I         : BTE_InitTraceLevels -- TRC_SDP
08-22 17:05:18.929  3523  3570 I         : BTE_InitTraceLevels -- TRC_GATT
,08-22 17:05:18.930  3523  3570 I         : BTE_InitTraceLevels -- TRC_SMP
08-22 17:05:18.930  3523  3570 I         : BTE_InitTraceLevels -- TRC_BTAPP,
08-22 17:05:18.930  3523  3570 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-22 17:05:19.063  3523  3570 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb392dd9d
,08-22 17:05:19.064  3523  3570 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb392dd9d 
,08-22 17:05:19.075  3523  3561 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-22 17:05:19.077  3523  3561 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-22 17:05:19.078  3523  3561 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61,
08-22 17:05:19.081  3523  3561 D BluetoothAdapterProperties: Name is: Nexus 6
,08-22 17:05:19.086  3523  3561 D BluetoothAdapterProperties: Scan Mode:20
,08-22 17:05:19.087  3523  3561 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-22 17:05:19.089  3523  3561 D bt_hci  : do_postload posting postload work item
,08-22 17:05:19.090  3523  3568 I bt_hci  : event_postload
08-22 17:05:19.090  3523  3568 I bt_vendor: sco_config_cb
08-22 17:05:19.090  3523  3568 I bt_hci  : sco_config_callback postload finished.
,08-22 17:05:19.091  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 17:05:19.096  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 17:05:19.100  3523  3568 I bt_vendor: low_power_mode_cb
,08-22 17:05:19.105  3523  3561 D bt_bte_conf: Device ID record 1 : primary
,08-22 17:05:19.105  3523  3561 D bt_bte_conf:   vendorId            = 000f
08-22 17:05:19.105  3523  3561 D bt_bte_conf:   vendorIdSource      = 0001
08-22 17:05:19.105  3523  3561 D bt_bte_conf:   product             = 1200
,08-22 17:05:19.105  3523  3561 D bt_bte_conf:   version             = 1436
08-22 17:05:19.106  3523  3561 D bt_bte_conf:   clientExecutableURL = 
,08-22 17:05:19.106  3523  3561 D bt_bte_conf:   serviceDescription  = 
08-22 17:05:19.106  3523  3561 D bt_bte_conf:   documentationURL    = 
,08-22 17:05:19.106  3523  3561 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-22 17:05:19.107  3523  3556 D bt_stack_manager: event_start_up_stack finished
,08-22 17:05:19.109  3523  3555 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-22 17:05:19.109  3523  3555 D BluetoothAdapterProperties: Setting state to 15
,08-22 17:05:19.109  3523  3555 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-22 17:05:19.111  3523  3555 I BluetoothAdapterState: Entering BleOnState
,08-22 17:05:19.119  3523  3555 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-22 17:05:19.119  3523  3555 D BluetoothAdapterProperties: Setting state to 11
08-22 17:05:19.119  3523  3555 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-22 17:05:19.130  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 17:05:19.131  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 17:05:19.159   873   886 I ActivityManager: Start proc 3576:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-22 17:05:19.166  3523  3523 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
,08-22 17:05:19.168  3523  3523 D HeadsetService: Received start request. Starting profile...
,08-22 17:05:19.174  3523  3555 I BluetoothAdapterState: Entering PendingCommandState
,08-22 17:05:19.175  3523  3523 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-22 17:05:19.176  3523  3523 D HeadsetStateMachine: make
,08-22 17:05:19.191  3523  3523 D HeadsetStateMachine: max_hf_connections = 1
,08-22 17:05:19.192  3523  3523 I bt_bluedroid: get_profile_interface handsfree
08-22 17:05:19.192  3523  3561 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-22 17:05:19.192  3523  3561 E bt_btif : btif_hf_upstreams_evt: Invalid index -1,
,08-22 17:05:19.198  3523  3523 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
,08-22 17:05:19.199   873   873 D BluetoothA2dp: Proxy object connected
08-22 17:05:19.199  3523  3523 D A2dpService: Received start request. Starting profile...
08-22 17:05:19.200  3523  3523 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-22 17:05:19.200  3523  3523 I bt_bluedroid: get_profile_interface avrcp
,08-22 17:05:19.202  3576  3576 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-22 17:05:19.206  3523  3523 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-22 17:05:19.206  3523  3523 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-22 17:05:19.206  3523  3523 D A2dpStateMachine: make
,08-22 17:05:19.208  3523  3523 I bt_bluedroid: get_profile_interface a2dp
,08-22 17:05:19.208  3523  3561 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-22 17:05:19.213  3523  3590 D A2dpStateMachine: Enter Disconnected: -2
,08-22 17:05:19.214  3523  3523 I BluetoothHidServiceJni: classInitNative: succeeds
,08-22 17:05:19.216  3523  3523 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
,08-22 17:05:19.218   873  1966 I ActivityManager: Killing 2985:com.google.android.gm/u0a78 (adj 15): empty #17
,08-22 17:05:19.257  1367  1367 D BluetoothInputDevice: Proxy object connected
,08-22 17:05:19.258  1367  1367 D HidProfile: Bluetooth service connected
,08-22 17:05:19.258  3523  3523 D HidService: Received start request. Starting profile...
,08-22 17:05:19.259  3523  3523 I bt_bluedroid: get_profile_interface hidhost
,08-22 17:05:19.260  3523  3523 D HidService: setHidService(): set to: null
08-22 17:05:19.260  3523  3561 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb390f3e5
08-22 17:05:19.260  3523  3561 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-22 17:05:19.262  3523  3523 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-22 17:05:19.264  3523  3523 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
,08-22 17:05:19.265  3523  3523 D HealthService: Received start request. Starting profile...
,08-22 17:05:19.269  3523  3523 I bt_bluedroid: get_profile_interface health
,08-22 17:05:19.270  3523  3523 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-22 17:05:19.272  3523  3523 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
,08-22 17:05:19.275  1367  1367 D BluetoothPan: BluetoothPAN Proxy object connected
,08-22 17:05:19.275  3523  3523 D PanService: Received start request. Starting profile...
,08-22 17:05:19.276  3523  3523 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-22 17:05:19.276  1367  1367 D PanProfile: Bluetooth service connected
08-22 17:05:19.276  3523  3523 I bt_bluedroid: get_profile_interface pan
,08-22 17:05:19.278  3523  3561 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-22 17:05:19.280  3523  3523 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
,08-22 17:05:19.281  3523  3523 D BluetoothMapService: Received start request. Starting profile...
,08-22 17:05:19.281  3523  3523 D BluetoothMapService: start()
08-22 17:05:19.281  1367  1367 D BluetoothMap: Proxy object connected
08-22 17:05:19.282  1367  1367 D MapProfile: Bluetooth service connected
08-22 17:05:19.283  1367  1367 D BluetoothMap: getConnectedDevices()
,08-22 17:05:19.287  3523  3523 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-22 17:05:19.288  3523  3523 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-22 17:05:19.288  3523  3523 D BluetoothMapAppObserver: createReceiver()
,08-22 17:05:19.288  1367  1367 D BluetoothMap: Bluetooth is Not enabled
08-22 17:05:19.289  3523  3523 D BluetoothMapAppObserver: initObservers()
08-22 17:05:19.289  3523  3523 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-22 17:05:19.308  3523  3523 V BluetoothAdapterState: isTurningOff()=false
,08-22 17:05:19.308  3523  3523 V BluetoothAdapterState: isTurningOn()=true
08-22 17:05:19.308  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
08-22 17:05:19.309  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 17:05:19.310  3523  3523 V BluetoothAdapterState: isTurningOff()=false
,08-22 17:05:19.310  3523  3523 V BluetoothAdapterState: isTurningOn()=true
08-22 17:05:19.310  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
08-22 17:05:19.311  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 17:05:19.311  3523  3588 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-22 17:05:19.313  3523  3523 V BluetoothAdapterState: isTurningOff()=false
,08-22 17:05:19.313  3523  3523 V BluetoothAdapterState: isTurningOn()=true
,08-22 17:05:19.313  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 17:05:19.313  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 17:05:19.313  3523  3523 V BluetoothAdapterState: isTurningOff()=false
,08-22 17:05:19.313  3523  3523 V BluetoothAdapterState: isTurningOn()=true
,08-22 17:05:19.313  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
08-22 17:05:19.313  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
08-22 17:05:19.314  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-22 17:05:19.314  3523  3523 V BluetoothAdapterState: isTurningOff()=false
08-22 17:05:19.314  3523  3523 V BluetoothAdapterState: isTurningOn()=true
,08-22 17:05:19.314  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 17:05:19.314  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
08-22 17:05:19.314  3523  3523 V BluetoothAdapterState: isTurningOff()=false
08-22 17:05:19.314  3523  3523 V BluetoothAdapterState: isTurningOn()=true
,08-22 17:05:19.314  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
08-22 17:05:19.314  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
08-22 17:05:19.315  3523  3555 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-22 17:05:19.315  3523  3555 D BluetoothAdapterProperties: ScanMode =  20
,08-22 17:05:19.315  3523  3555 D BluetoothAdapterProperties: State =  11
08-22 17:05:19.315  3523  3555 D BluetoothAdapterProperties: Setting state to 12
08-22 17:05:19.315  3523  3555 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-22 17:05:19.316  3523  3555 I BluetoothAdapterState: Entering OnState
08-22 17:05:19.317  1367  1379 D BluetoothMap: onBluetoothStateChange: up=true
08-22 17:05:19.317  3523  3561 D BluetoothAdapterProperties: Scan Mode:21
,08-22 17:05:19.317  3523  3561 D BluetoothAdapterProperties: Discoverable Timeout:120
08-22 17:05:19.317   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 17:05:19.318  1367  2019 D BluetoothPan: onBluetoothStateChange on: true
08-22 17:05:19.318   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-22 17:05:19.319   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 17:05:19.319  1367  1380 D BluetoothPbap: onBluetoothStateChange: up=true
08-22 17:05:19.320  1367  1379 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-22 17:05:19.323  3463  3463 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-22 17:05:19.324  1914  1943 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 17:05:19.325   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 17:05:19.326  3463  3463 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-22 17:05:19.328  3463  3463 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-22 17:05:19.333  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 17:05:19.333  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:19.333  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:19.333  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 17:05:19.333  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 17:05:19.333  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:19.333  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:19.333  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 17:05:19.335   873  1421 I ActivityManager: Start proc 3596:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-22 17:05:19.336  3463  3463 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 17:05:19.338   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-22 17:05:19.340  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 17:05:19.340  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:19.340  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:19.340  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 17:05:19.340  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 17:05:19.340  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:19.340  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:19.340  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 17:05:19.342  3463  3463 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 17:05:19.345  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 17:05:19.344  3523  3523 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-22 17:05:19.346  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 17:05:19.347  3523  3523 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-22 17:05:19.348  3523  3523 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 17:05:19.350  1367  1659 D LocalBluetoothProfileManager: Adding local A2DP profile
08-22 17:05:19.350  3523  3523 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 17:05:19.352  3523  3523 D ObexServerSockets: Succeed to create listening sockets 
08-22 17:05:19.352  3523  3523 D ObexServerSockets0: startAccept()
08-22 17:05:19.352  3523  3523 D ObexServerSockets0: prepareForNewConnect()
08-22 17:05:19.353  3523  3523 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-22 17:05:19.354  3523  3523 D BluetoothSdpJni: SDP Create record success - handle: 0
08-22 17:05:19.354  3523  3602 D ObexServerSockets0: Accepting socket connection...
08-22 17:05:19.354  3523  3523 D BluetoothMapService: onReceive
08-22 17:05:19.354  3523  3523 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-22 17:05:19.354  3523  3523 D BluetoothMapService: STATE_ON
08-22 17:05:19.355  3523  3603 D ObexServerSockets0: Accepting socket connection...
08-22 17:05:19.356  1367  1367 D BluetoothA2dp: Proxy object connected
08-22 17:05:19.358  1367  1659 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-22 17:05:19.375  3523  3523 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-22 17:05:19.375  3523  3523 D ObexServerSockets0: prepareForNewConnect()
,08-22 17:05:19.390  3596  3596 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-22 17:05:19.419   873   890 D BluetoothHeadset: Proxy object connected
,08-22 17:05:19.421   873   890 D BluetoothHeadset: Proxy object connected
,08-22 17:05:19.426  1914  1935 D BluetoothHeadset: Proxy object connected
,08-22 17:05:19.429   873   890 D BluetoothHeadset: Proxy object connected
,08-22 17:05:19.465  1367  1379 D BluetoothHeadset: Proxy object connected
,08-22 17:05:19.467  1367  1367 D HeadsetProfile: Bluetooth service connected
,08-22 17:05:19.569  3596  3596 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at java.io.File.exists(File.java:361)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 17:05:19.569  3596  3596 D StrictMode: 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 17:05:19.569  3596  3596 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-22 17:05:19.569  3596  3596 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-22 17:05:19.569  3596  3596 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.r.y.a(PG:2188)
,08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.r.e.b(PG:170)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 17:05:19.569  3596  3596 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.r.k.d(PG:583)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.r.e.b(PG:170)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app,.a.a(PG:244)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 17:05:19.569  3596  3596 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at java.io.File.exists(File.java:361)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 17:05:19.569  3596  3596 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 17:05:19.570  3596  3596 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 17:05:19.570  3596  3596 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at java.io.File.exists(File.java:361)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 17:05:19.570  3596  3596 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 17:05:19.570  3596  3596 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 17:05:19.570  3596  3596 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 17:05:19.579  3576  3576 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-22 17:05:19.591   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cff87e8:true
08-22 17:05:19.598  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-22 17:05:19.612  3576  3576 D LocalBluetoothProfileManager: Adding local A2DP profile
08-22 17:05:19.615  1367  1367 D BluetoothPbap: Proxy object connected
08-22 17:05:19.616  1367  1367 D PbapServerProfile: Bluetooth service connected
,08-22 17:05:19.622  3576  3576 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-22 17:05:19.638  3523  3627 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 17:05:19.645  3576  3576 D LocalBluetoothProfileManager: Adding local MAP profile
08-22 17:05:19.646  3576  3576 D BluetoothMap: Create BluetoothMap proxy object
08-22 17:05:19.656  3576  3576 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-22 17:05:19.658  3523  3631 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 17:05:19.661  3576  3576 D DockEventReceiver: finishStartingService: stopping service
,08-22 17:05:19.661  3523  3631 I BtOppRfcommListener: Accept thread started.
,08-22 17:05:19.663  3576  3576 D BluetoothA2dp: Proxy object connected
,08-22 17:05:19.668  3576  3576 D BluetoothInputDevice: Proxy object connected
08-22 17:05:19.668  3576  3576 D HidProfile: Bluetooth service connected
,08-22 17:05:19.671  3576  3576 D BluetoothPan: BluetoothPAN Proxy object connected
,08-22 17:05:19.672  3576  3576 D PanProfile: Bluetooth service connected
,08-22 17:05:19.672  3576  3576 D BluetoothMap: Proxy object connected
08-22 17:05:19.673  3576  3576 D MapProfile: Bluetooth service connected
,08-22 17:05:19.673  3576  3576 D BluetoothMap: getConnectedDevices()
,08-22 17:05:19.675  3576  3576 D BluetoothPbap: Proxy object connected
,08-22 17:05:19.675  3576  3576 D PbapServerProfile: Bluetooth service connected
,08-22 17:05:19.677   873  1955 I ActivityManager: Killing 3184:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-22 17:05:19.727  3576  3586 D BluetoothHeadset: Proxy object connected
,08-22 17:05:19.727  3576  3576 D HeadsetProfile: Bluetooth service connected
,08-22 17:05:19.880  3596  3617 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-22 17:05:19.901   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dac9cc7:true
,08-22 17:05:20.765   873  2236 D WifiService: setWifiEnabled: true pid=3463, uid=10000
,08-22 17:05:20.765   873  2236 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-22 17:05:20.784   873  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-22 17:05:20.800  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 17:05:20.800  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:20.800  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:20.800  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 17:05:20.800  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 17:05:20.800  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:20.800  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:20.800  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 17:05:20.804  3463  3463 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 17:05:20.812  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 17:05:20.812  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:20.812  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:20.812  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 17:05:20.812  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 17:05:20.812  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:20.812  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:20.812  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 17:05:20.814   873  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-22 17:05:20.815   873  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-22 17:05:20.815  3463  3463 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 17:05:20.816   873  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-22 17:05:20.820   873  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-22 17:05:20.821   873  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-22 17:05:20.821   873  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-22 17:05:20.821   873  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-22 17:05:20.822  1462  1462 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-22 17:05:20.902   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-22 17:05:20.905   371   871 D CommandListener: Setting iface cfg
,08-22 17:05:20.907   873  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '104 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 104 Failed to set address (No such device)'
,08-22 17:05:20.907   873  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-22 17:05:20.918   873  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-22 17:05:20.919   873  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-22 17:05:20.942   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 17:05:20.962   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 17:05:21.282  1462  1462 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-22 17:05:21.335  1462  1462 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-22 17:05:21.336  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-22 17:05:21.342   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 17:05:21.357   873  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-22 17:05:21.357   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-22 17:05:21.358   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-22 17:05:21.376   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 17:05:21.389   371   871 D CommandListener: Setting iface cfg
,08-22 17:05:21.399   873  1308 D WifiStateMachine: Start Dhcp Watchdog 1
,08-22 17:05:21.430   873  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-22 17:05:21.431   873  1310 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,08-22 17:05:21.436   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-22 17:05:21.441   873  3643 D DhcpClient: Receive thread started
,08-22 17:05:21.525   873  1308 E native  : do suspend false
,08-22 17:05:21.551   873  3642 D DhcpClient: Broadcasting DHCPDISCOVER
,08-22 17:05:21.573   873  3643 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 154310, domain null
,08-22 17:05:21.575   873  3642 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 154310 seconds
,08-22 17:05:21.579   873  3642 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-22 17:05:21.615   873  3643 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
08-22 17:05:21.616   873  3642 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-22 17:05:21.621   371   871 D CommandListener: Setting iface cfg
,08-22 17:05:21.632   873  3642 D DhcpClient: Scheduling renewal in 86399s
,08-22 17:05:21.633   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-22 17:05:21.649   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-22 17:05:21.652   873  1308 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-22 17:05:21.653   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-22 17:05:21.655   873  1310 D ConnectivityService: Adding iface wlan0 to network 100
,08-22 17:05:21.663   873  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-22 17:05:21.729   873  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-22 17:05:21.729   873  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,08-22 17:05:21.733   873  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,08-22 17:05:21.735   873  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,08-22 17:05:21.737   873  1310 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,08-22 17:05:21.748   873  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-22 17:05:21.755   873  1310 D ConnectivityService: scheduleUnvalidatedPrompt 100
,08-22 17:05:21.755   873  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
,08-22 17:05:21.756   873  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-22 17:05:21.757   873  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-22 17:05:21.758   873  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
,08-22 17:05:21.758   873  1310 D ConnectivityService:    accepting network in place of null
,08-22 17:05:21.759   873  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-22 17:05:21.783   873  3641 D NetlinkSocketObserver: NeighborEvent{elapsedMs=136330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-22 17:05:21.788   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 17:05:21.821   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 17:05:21.827   873  1310 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,08-22 17:05:21.842   873  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-22 17:05:21.843   873  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-22 17:05:21.854   873  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,08-22 17:05:21.857   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-22 17:05:21.882  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,08-22 17:05:21.882  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:21.882  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:21.882  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 17:05:21.882  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 17:05:21.882  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 17:05:21.882  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 17:05:21.882  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 17:05:21.889  3463  3463 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 17:05:21.894  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 17:05:21.894  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:21.894  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:21.894  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 17:05:21.894  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 17:05:21.894  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 17:05:21.894  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 17:05:21.894  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 17:05:21.896  1981  1981 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-22 17:05:21.896  3463  3463 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 17:05:21.946   873  1901 I ActivityManager: Start proc 3668:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-22 17:05:21.960  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 17:05:21.962  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 17:05:21.977  3668  3668 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-22 17:05:21.979  1715  3684 I iu.SyncManager: SYNC; picasa accounts
,08-22 17:05:21.999  3535  3664 V GoogleAuthProtoRequest: [282] a.<init>: mAccountName set to: thalitester@gmail.com
,08-22 17:05:22.005  1715  1715 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-22 17:05:22.007  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
08-22 17:05:22.011  1715  3660 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,08-22 17:05:22.023  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-22 17:05:22.023  1715  3684 I iu.UploadsManager: num queued entries: 0
08-22 17:05:22.023  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-22 17:05:22.026  1715  3684 I iu.UploadsManager: num updated entries: 0
,08-22 17:05:22.035  1715  3684 I iu.SyncManager: NEXT; no task
,08-22 17:05:22.035   873  1959 I ActivityManager: Start proc 3691:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-22 17:05:22.038  3668  3685 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-22 17:05:22.053  1715  3683 I MDM     : [147] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-22 17:05:22.053  1715  3683 W BaseAppContext: Using Auth Proxy for data requests.
,08-22 17:05:22.060  1715  3683 V GoogleAuthProtoRequest: [147] a.<init>: mAccountName set to: thalitester@gmail.com
,08-22 17:05:22.070  3691  3691 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-22 17:05:22.072  1508  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-22 17:05:22.072  1508  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-22 17:05:22.072  1508  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-22 17:05:22.072  1508  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 17:05:22.074  3691  3691 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-22 17:05:22.086  3691  3691 D SprintDMHelper: simOperator: 
08-22 17:05:22.086  3691  3691 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-22 17:05:22.090  3668  3685 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
08-22 17:05:22.096  1508  2030 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-22 17:05:22.096  1508  2030 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-22 17:05:22.096  1508  2030 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 17:05:22.097  1508  2030 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 17:05:22.098   873  1955 I ActivityManager: Start proc 3707:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-22 17:05:22.124  3668  3685 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-22 17:05:22.137  1715  3683 E MDM     : [147] SitrepService.a: Error sending sitrep.
,08-22 17:05:22.143   873  3662 D GpsLocationProvider: NTP server returned: 1471878323078 (Mon Aug 22 17:05:23 GMT+02:00 2016) reference: 136692 certainty: 82 system time offset: 935
,08-22 17:05:22.143   873  3662 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
08-22 17:05:22.143   873  3640 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-22 17:05:22.144   873  1886 D AlarmManagerService: Setting time of day to sec=1471878323
,08-22 17:05:23.077   873  1886 W AlarmManagerService: Unable to set rtc to 1471878323: Invalid argument
,08-22 17:05:23.083  3535  3664 W ExperimentUpdateService: [282] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-22 17:05:23.083  3535  3664 W ExperimentUpdateService: [282] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-22 17:05:23.083  3535  3664 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-22 17:05:23.083  3535  3664 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-22 17:05:23.083  3535  3664 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-22 17:05:23.083  3535  3664 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-22 17:05:23.083  3535  3664 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-22 17:05:23.083  3535  3664 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-22 17:05:23.083  3535  3664 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-22 17:05:23.083  3535  3664 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-22 17:05:23.083  3535  3664 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-22 17:05:23.083  3535  3664 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-22 17:05:23.092  1715  1715 E ConnectivityChangeReceiver: Ignoring connectivity change
,08-22 17:05:23.116   873  1707 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1715 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-22 17:05:23.163  1508  1508 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-22 17:05:23.164  3668  3668 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-22 17:05:23.263  3730  3730 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-1892950054.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-1892950054.dex
,08-22 17:05:23.284  1715  3679 W DriveInitializer: Awaiting to be initialized
,08-22 17:05:23.285  1715  3760 W DriveInitializer: Background init thread started
,08-22 17:05:23.317  3730  3730 I dex2oat : dex2oat took 53.988ms (threads: 4) arena alloc=227KB java alloc=41KB native alloc=1514KB free=1557KB
,08-22 17:05:23.336   873  3640 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 22 Aug 2016 15:05:23 GMT], X-Android-Received-Millis=[1471878323336], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471878323279]}
,08-22 17:05:23.339   873   885 I ActivityManager: Start proc 3762:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-22 17:05:23.343   873  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-22 17:05:23.343   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
08-22 17:05:23.343   873  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-22 17:05:23.344   873  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-22 17:05:23.364  3762  3762 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-22 17:05:23.410   873  1374 I ActivityManager: Start proc 3790:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-22 17:05:23.420  1508  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-22 17:05:23.420  1508  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-22 17:05:23.420  1508  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 17:05:23.420  1508  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-22 17:05:23.428  3668  3668 W InstanceID/Rpc: Found 10011,
08-22 17:05:23.439  1715  3760 W DriveInitializer: Background init thread ended
,08-22 17:05:23.467  3268  3720 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-22 17:05:23.467  3268  3720 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-22 17:05:23.467  3268  3720 E HttpOperation: 	at jdm.a(PG:82)
08-22 17:05:23.467  3268  3720 E HttpOperation: 	at jcs.o(PG:406)
08-22 17:05:23.467  3268  3720 E HttpOperation: 	at jcn.a(PG:1379)
08-22 17:05:23.467  3268  3720 E HttpOperation: 	at jcs.i(PG:143)
08-22 17:05:23.467  3268  3720 E HttpOperation: 	at blb.a(PG:3937)
08-22 17:05:23.467  3268  3720 E HttpOperation: 	at czp.a(PG:18188)
08-22 17:05:23.467  3268  3720 E HttpOperation: 	at czp.a(PG:9081)
08-22 17:05:23.467  3268  3720 E HttpOperation: 	at czq.run(PG:1686)
08-22 17:05:23.467  3268  3720 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-22 17:05:23.467  3268  3720 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-22 17:05:23.467  3268  3720 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-22 17:05:23.467  3268  3720 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-22 17:05:23.467  3268  3720 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-22 17:05:23.467  3268  3720 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-22 17:05:23.467  3268  3720 E HttpOperation: 	at jdj.a(PG:4091)
08-22 17:05:23.467  3268  3720 E HttpOperation: 	at jdj.a(PG:1125)
08-22 17:05:23.467  3268  3720 E HttpOperation: 	at jdm.a(PG:77)
08-22 17:05:23.467  3268  3720 E HttpOperation: 	... 12 more
08-22 17:05:23.467  3268  3720 E HttpOperation: Caused by: faj: BadAuthentication
08-22 17:05:23.467  3268  3720 E HttpOperation: 	at fal.a(PG:38)
08-22 17:05:23.467  3268  3720 E HttpOperation: 	at jdj.a(PG:4089)
08-22 17:05:23.467  3268  3720 E HttpOperation: 	... 14 more
,08-22 17:05:23.500  3790  3790 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-22 17:05:23.571  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 17:05:23.580  1508  2791 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-22 17:05:23.580  1508  2791 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-22 17:05:23.580  1508  2791 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-22 17:05:23.580  1508  2791 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-22 17:05:23.580  3762  3762 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-22 17:05:23.592  3762  3762 I BooksApp: Created application version: 3.6.9 (30609)
,08-22 17:05:23.605  3268  3720 E HttpOperation: [getmobileexperiments] Unexpected exception
08-22 17:05:23.605  3268  3720 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-22 17:05:23.605  3268  3720 E HttpOperation: 	at jdm.a(PG:82)
08-22 17:05:23.605  3268  3720 E HttpOperation: 	at jcs.o(PG:406)
08-22 17:05:23.605  3268  3720 E HttpOperation: 	at jcn.a(PG:1379)
08-22 17:05:23.605  3268  3720 E HttpOperation: 	at jcs.i(PG:143)
08-22 17:05:23.605  3268  3720 E HttpOperation: 	at hec.a(PG:42)
08-22 17:05:23.605  3268  3720 E HttpOperation: 	at hee.a(PG:102)
08-22 17:05:23.605  3268  3720 E HttpOperation: 	at czr.a(PG:65)
08-22 17:05:23.605  3268  3720 E HttpOperation: 	at kka.a(PG:108)
08-22 17:05:23.605  3268  3720 E HttpOperation: 	at czp.a(PG:19176)
08-22 17:05:23.605  3268  3720 E HttpOperation: 	at czp.a(PG:9081)
08-22 17:05:23.605  3268  3720 E HttpOperation: 	at czq.run(PG:1686)
08-22 17:05:23.605  3268  3720 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-22 17:05:23.605  3268  3720 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-22 17:05:23.605  3268  3720 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-22 17:05:23.605  3268  3720 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-22 17:05:23.605  3268  3720 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-22 17:05:23.605  3268  3720 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-22 17:05:23.605  3268  3720 E HttpOperation: 	at jdj.a(PG:4091)
08-22 17:05:23.605  3268  3720 E HttpOperation: 	at jdj.a(PG:1125)
08-22 17:05:23.605  3268  3720 E HttpOperation: 	at jdm.a(PG:77)
08-22 17:05:23.605  3268  3720 E HttpOperation: 	... 15 more
08-22 17:05:23.605  3268  3720 E HttpOperation: Caused by: faj: BadAuthentication
08-22 17:05:23.605  3268  3720 E HttpOperation: 	at fal.a(PG:38)
08-22 17:05:23.605  3268  3720 E HttpOperation: 	at jdj.a(PG:4089)
08-22 17:05:23.605  3268  3720 E HttpOperation: 	... 17 more
,08-22 17:05:23.605  3268  3720 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-22 17:05:23.605  3268  3720 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-22 17:05:23.605  3268  3720 E ExperimentLoader: 	at jdm.a(PG:82)
08-22 17:05:23.605  3268  3720 E ExperimentLoader: 	at jcs.o(PG:406)
08-22 17:05:23.605  3268  3720 E ExperimentLoader: 	at jcn.a(PG:1379)
08-22 17:05:23.605  3268  3720 E ExperimentLoader: 	at jcs.i(PG:143)
08-22 17:05:23.605  3268  3720 E ExperimentLoader: 	at hec.a(PG:42)
08-22 17:05:23.605  3268  3720 E ExperimentLoader: 	at hee.a(PG:102)
08-22 17:05:23.605  3268  3720 E ExperimentLoader: 	at czr.a(PG:65)
08-22 17:05:23.605  3268  3720 E ExperimentLoader: 	at kka.a(PG:108)
08-22 17:05:23.605  3268  3720 E ExperimentLoader: 	at czp.a(PG:19176)
08-22 17:05:23.605  3268  3720 E ExperimentLoader: 	at czp.a(PG:9081)
08-22 17:05:23.605  3268  3720 E ExperimentLoader: 	at czq.run(PG:1686)
08-22 17:05:23.605  3268  3720 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-22 17:05:23.605  3268  3720 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-22 17:05:23.605  3268  3720 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-22 17:05:23.605  3268  3720 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-22 17:05:23.605  3268  3720 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-22 17:05:23.605  3268  3720 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-22 17:05:23.605  3268  3720 E ExperimentLoader: 	at jdj.a(PG:4091)
08-22 17:05:23.605  3268  3720 E ExperimentLoader: 	at jdj.a(PG:1125)
08-22 17:05:23.605  3268  3720 E ExperimentLoader: 	at jdm.a(PG:77)
08-22 17:05:23.605  3268  3720 E ExperimentLoader: 	... 15 more
08-22 17:05:23.605  3268  3720 E ExperimentLoader: Caused by: faj: BadAuthentication
08-22 17:05:23.605  3268  3720 E ExperimentLoader: 	at fal.a(PG:38)
08-22 17:05:23.605  3268  3720 E ExperimentLoader: 	at jdj.a(PG:4089)
08-22 17:05:23.605  3268  3720 E ExperimentLoader: 	... 17 more
,08-22 17:05:23.712  1508  3739 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,08-22 17:05:23.736  3762  3843 I BooksSync: Starting books sync for 61035162, extras: ade
,08-22 17:05:23.759   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 25378, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-22 17:05:23.760   873  1956 I ActivityManager: Killing 2599:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-22 17:05:23.800  2867  3789 I Babel   : connection state changed from UNKNOWN to CONNECTED
,08-22 17:05:23.822   873  1421 I ActivityManager: Killing 2962:android.process.acore/u0a5 (adj 15): empty #17
,08-22 17:05:23.932  3790  3790 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-22 17:05:23.932  3790  3790 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-22 17:05:23.932  3790  3790 I GAv4    :   adb logcat -s GAv4
,08-22 17:05:23.968  3790  3790 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-22 17:05:23.977  3790  3790 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-22 17:05:24.021  3790  3856 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-22 17:05:24.129  3016  3855 V KeepSync: Connecting to GoogleApiClient
,08-22 17:05:24.138   873  1901 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-22 17:05:24.230  3790  3790 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-22 17:05:24.282  3790  3790 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-22 17:05:24.304  1508  2030 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-22 17:05:24.305  1508  2030 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-22 17:05:24.305  1508  2030 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 17:05:24.305  1508  2030 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 17:05:24.307  3790  3790 I LibraryLoader: Time to load native libraries: 9 ms (timestamps 7915-7924)
,08-22 17:05:24.307  3790  3790 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-22 17:05:24.319  1715  3873 V BaseAuthAsyncOperation: access token request failed
,08-22 17:05:24.322  3016  3855 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-22 17:05:24.330  3790  3790 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {649bf3}
,08-22 17:05:24.331  3790  3790 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-22 17:05:24.331  3790  3790 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-22 17:05:24.338  3790  3790 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-22 17:05:24.348  3790  3790 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-22 17:05:24.376  3790  3790 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-22 17:05:24.398  3790  3790 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-22 17:05:24.398  3790  3790 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-22 17:05:24.398  3790  3790 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-22 17:05:24.398  3790  3790 I Adreno  : Build Date                       : 10/20/15
08-22 17:05:24.398  3790  3790 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-22 17:05:24.398  3790  3790 I Adreno  : Local Branch                     : M14
08-22 17:05:24.398  3790  3790 I Adreno  : Remote Branch                    : 
08-22 17:05:24.398  3790  3790 I Adreno  : Remote Branch                    : 
08-22 17:05:24.398  3790  3790 I Adreno  : Reconstruct Branch               : 
,08-22 17:05:24.478  3762  3883 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-22 17:05:24.566  1508  2030 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-22 17:05:24.566  1508  2030 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-22 17:05:24.566  1508  2030 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-22 17:05:24.567  1508  2030 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 17:05:24.576  3790  3790 I NSApplication: Starting up...
,08-22 17:05:24.593   873   883 I ActivityManager: Start proc 3896:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-22 17:05:24.614  3790  3891 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-22 17:05:24.615  1508  2042 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-22 17:05:24.615  1508  2042 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-22 17:05:24.615  1508  2042 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 17:05:24.615  1508  2042 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 17:05:24.629  3896  3896 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-22 17:05:24.639  3762  3883 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-22 17:05:24.642  3762  3843 E BooksSync: Soft error
08-22 17:05:24.642  3762  3843 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-22 17:05:24.642  3762  3843 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-22 17:05:24.642  3762  3843 E BooksSync: Sync error
08-22 17:05:24.642  3762  3843 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-22 17:05:24.642  3762  3843 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-22 17:05:24.642  3762  3843 I BooksSync: Finished books sync
,08-22 17:05:24.651   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 25389, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-22 17:05:24.704   873  1707 D WifiService: setWifiEnabled: false pid=3463, uid=10000
,08-22 17:05:24.705   873  1707 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-22 17:05:24.709  1508  2030 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-22 17:05:24.710  1508  2030 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-22 17:05:24.710  1508  2030 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 17:05:24.710  1508  2030 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 17:05:24.719  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-22 17:05:24.720   873  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-22 17:05:24.721   873  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-22 17:05:24.721   873  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-22 17:05:24.721   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 17:05:24.726  3016  3855 E KeepSync: IOException
08-22 17:05:24.726  3016  3855 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-22 17:05:24.726  3016  3855 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-22 17:05:24.726  3016  3855 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-22 17:05:24.726  3016  3855 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-22 17:05:24.726  3016  3855 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-22 17:05:24.726  3016  3855 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-22 17:05:24.726  3016  3855 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-22 17:05:24.726  3016  3855 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-22 17:05:24.726  3016  3855 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-22 17:05:24.726  3016  3855 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-22 17:05:24.726  3016  3855 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-22 17:05:24.726  3016  3855 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-22 17:05:24.726  3016  3855 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-22 17:05:24.726  3016  3855 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-22 17:05:24.726  3016  3855 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-22 17:05:24.726  3016  3855 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-22 17:05:24.726  3016  3855 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-22 17:05:24.726  3016  3855 E KeepSync: 	... 10 more
,08-22 17:05:24.727  3016  3855 W KeepSync: Sync result 2
,08-22 17:05:24.731   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 25389, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-22 17:05:24.732   873  2237 I ActivityManager: Killing 3345:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-22 17:05:24.767   371   871 D CommandListener: Clearing all IP addresses on wlan0
08-22 17:05:24.767   873  3642 D DhcpClient: Clearing IP address
,08-22 17:05:24.769   371   871 D CommandListener: Setting iface cfg
,08-22 17:05:24.772  1508  3831 V NativeCrypto: Read error: ssl=0x9a30ee00: I/O error during system call, Connection timed out
,08-22 17:05:24.773  1508  3831 V NativeCrypto: SSL shutdown failed: ssl=0x9a30ee00: I/O error during system call, Broken pipe
,08-22 17:05:24.775   873  1966 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,08-22 17:05:24.775   873  3640 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,08-22 17:05:24.777   873  3640 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
08-22 17:05:24.781   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-22 17:05:24.782   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-22 17:05:24.784   873  1308 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-22 17:05:24.784   403   403 E Parcel  : Reading a NULL string not supported here.
08-22 17:05:24.785   873  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-22 17:05:24.790   873  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-22 17:05:24.792   371   871 D CommandListener: Clearing all IP addresses on wlan0
08-22 17:05:24.794   873  3640 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:401b:801::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
08-22 17:05:24.800   873  3643 D DhcpClient: Receive thread stopped
,08-22 17:05:24.804   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 17:05:24.810  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 17:05:24.810  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:24.810  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:24.810  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 17:05:24.810  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 17:05:24.810  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:24.810  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:24.810  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 17:05:24.812  3463  3463 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 17:05:24.815  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 17:05:24.815  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:24.815  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:24.815  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 17:05:24.815  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 17:05:24.815  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:24.815  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:24.815  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 17:05:24.817   873  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-22 17:05:24.817  3463  3463 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 17:05:24.818  2002  2290 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 17:05:24.836   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 17:05:24.852  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 17:05:24.855  1508  3918 I VacuumService: Vacuum at: now=1471878324855 tag=VacuumService
08-22 17:05:24.860   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 17:05:24.861   873  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-22 17:05:24.861   873  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-22 17:05:24.864   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-22 17:05:24.869  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 17:05:24.870  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 17:05:24.873  1981  1981 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-22 17:05:24.877  1508  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-22 17:05:24.877  1508  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-22 17:05:24.877  1508  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-22 17:05:24.877  1508  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 17:05:24.890  2710  2710 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-22 17:05:24.890  2710  2710 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-22 17:05:24.890  2710  2710 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-22 17:05:24.897   873  1955 I ActivityManager: Killing 3362:com.android.musicfx/u0a18 (adj 15): empty #17
,08-22 17:05:24.921   371   871 E Netd    : netlink response contains error (No such file or directory)
,08-22 17:05:24.922   873  1310 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-22 17:05:24.922   873  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-22 17:05:25.141   873  1374 I ActivityManager: Killing 2137:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-22 17:05:25.315   873  2237 I ActivityManager: Start proc 3927:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,08-22 17:05:25.393  3927  3927 W System  : ClassLoader referenced unknown path: /system/app/CalendarGooglePrebuilt/lib/arm
,08-22 17:05:25.464   873  1421 I ActivityManager: Start proc 3942:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,08-22 17:05:25.531  3942  3942 W System  : ClassLoader referenced unknown path: /system/priv-app/CalendarProvider/lib/arm
,08-22 17:05:25.573   873  1901 I ActivityManager: Start proc 3957:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,08-22 17:05:25.575   873  1901 I ActivityManager: Killing 3310:com.android.defcontainer/u0a7 (adj 15): empty #17
08-22 17:05:25.576   278   278 E lowmemorykiller: Error writing /proc/3310/oom_score_adj; errno=22
,08-22 17:05:25.649   873  1901 I ActivityManager: Killing 3383:com.google.android.apps.docs/u0a46 (adj 15): empty #18
,08-22 17:05:25.719  3942  3942 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@d410689(com.android.providers.calendar.CalendarProvider2@ba3b68e)
,08-22 17:05:25.749  3927  3927 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,08-22 17:05:25.755  3957  3957 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,08-22 17:05:25.781  3957  3957 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-22 17:05:25.781  3957  3957 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-22 17:05:25.781  3957  3957 I GAv4    :   adb logcat -s GAv4
,08-22 17:05:25.794  3957  3957 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-22 17:05:25.804  3957  3957 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-22 17:05:25.817  3957  3973 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-22 17:05:25.885   873  1421 I ActivityManager: Start proc 3976:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,08-22 17:05:25.954  3976  3976 W System  : ClassLoader referenced unknown path: /system/app/TimeService/lib/arm
,08-22 17:05:25.964  3976  3976 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1471878325964
,08-22 17:05:25.964  3976  3976 D         : TimeServiceNative: User Time to be set is 1471878325964
08-22 17:05:25.964  3976  3976 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-22 17:05:25.964  3976  3976 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-22 17:05:25.964  3976  3976 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1471878325964
,08-22 17:05:25.964  3976  3976 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-22 17:05:25.964   400   985 D QC-time-services: Daemon: Connection accepted:time_genoff
08-22 17:05:25.965   400  3988 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1471878325964
,08-22 17:05:25.966   400  3988 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1471878325964, operation = 0
08-22 17:05:25.966   400  3988 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/8/71 11:15:38
,08-22 17:05:25.967   400  3988 D QC-time-services: Daemon:Value read from RTC seconds = 32181338000
,08-22 17:05:25.967   400  3988 D QC-time-services: Daemon:new time 1471878325964 
08-22 17:05:25.967   400  3988 D QC-time-services: Daemon: delta 1439696987964 genoff 1439696987964 
,08-22 17:05:25.967   400  3988 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696987964 to memory
08-22 17:05:25.968   400  3988 D QC-time-services: Daemon:Opening File: /data/time/ats_2
,08-22 17:05:25.968   400  3988 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-22 17:05:25.979   400  3988 D QC-time-services: Updating the TOD offset
,08-22 17:05:25.979   400  3988 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696987964 to memory
,08-22 17:05:25.979   400  3988 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-22 17:05:25.980   400  3988 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-22 17:05:25.986  3976  3976 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,08-22 17:05:25.986   400  3988 E QC-time-services: Daemon:Update to modem bit set
,08-22 17:05:25.986   400  3988 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
,08-22 17:05:25.986   400  3988 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1155913525964
08-22 17:05:25.988   873   884 I ActivityManager: Killing 1981:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,08-22 17:05:26.040   873  1309 D WifiService: Client connection lost with reason: 4
,08-22 17:05:26.057   400   985 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-22 17:05:26.065   400   981 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,08-22 17:05:26.125  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-22 17:05:26.131  1715  3684 I iu.UploadsManager: num queued entries: 0
,08-22 17:05:26.132  1715  3684 I iu.UploadsManager: num updated entries: 0
08-22 17:05:26.133  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-22 17:05:26.134  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-22 17:05:26.137  1715  3684 I iu.SyncManager: NEXT; no task
,08-22 17:05:26.138  3691  3691 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-22 17:05:26.144  3691  3691 D SprintDMHelper: simOperator: 
,08-22 17:05:26.144  3691  3691 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-22 17:05:26.158  2867  3991 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-22 17:05:26.845  3942  3942 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x20000000 }
,08-22 17:05:26.847  3942  3942 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,08-22 17:05:27.716  3523  3555 D BluetoothAdapterState: Current state: ON, message: 23
,08-22 17:05:27.717  3523  3555 D BluetoothAdapterProperties: Setting state to 13
08-22 17:05:27.717  3523  3555 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-22 17:05:27.719  3523  3555 D BluetoothAdapterProperties: onBluetoothDisable()
,08-22 17:05:27.728  3523  3555 I BluetoothAdapterState: Entering PendingCommandState
,08-22 17:05:27.728  3523  3523 D BluetoothMapService: onReceive
,08-22 17:05:27.728  3523  3523 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-22 17:05:27.729  3523  3523 D BluetoothMapService: STATE_TURNING_OFF
,08-22 17:05:27.732  3523  3561 D BluetoothAdapterProperties: Scan Mode:20
08-22 17:05:27.732  3523  3555 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-22 17:05:27.730  3523  3523 D BluetoothMapService: MAP Service closeService in
08-22 17:05:27.734  3523  3523 D BluetoothMapMasInstance0: MAP Service shutdown
08-22 17:05:27.734  3523  3523 D ObexServerSockets0: shutdown(block = true)
08-22 17:05:27.735  3463  3463 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 17:05:27.735  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 17:05:27.735  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:27.735  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:27.735  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 17:05:27.735  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 17:05:27.735  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:27.735  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:27.735  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 17:05:27.737  3523  3602 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-22 17:05:27.738  3463  3463 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 17:05:27.738  3463  3463 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 17:05:27.740  3523  3523 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-22 17:05:27.740  3576  3576 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-22 17:05:27.741  3523  3603 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-22 17:05:27.742  3523  3573 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-22 17:05:27.747  3523  3523 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-22 17:05:27.748  3463  3463 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 17:05:27.748  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 17:05:27.748  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:27.748  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:27.748  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 17:05:27.748  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 17:05:27.748  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:27.748  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:27.748  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 17:05:27.748  3523  3523 D HeadsetService: Received stop request...Stopping profile...
08-22 17:05:27.748  3463  3463 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 17:05:27.748  3463  3463 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 17:05:27.750  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 17:05:27.752  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 17:05:27.753   873   873 D BluetoothHeadset: Proxy object disconnected
08-22 17:05:27.753  3576  3586 D BluetoothHeadset: Proxy object disconnected
,08-22 17:05:27.754  3523  3523 D A2dpService: Received stop request...Stopping profile...
08-22 17:05:27.754  3523  3590 D A2dpStateMachine: Exit Disconnected: -1
08-22 17:05:27.755   873   873 D BluetoothHeadset: Proxy object disconnected
08-22 17:05:27.755  1914  2047 D BluetoothHeadset: Proxy object disconnected
08-22 17:05:27.756  1367  1380 D BluetoothHeadset: Proxy object disconnected
08-22 17:05:27.756   873   873 D BluetoothHeadset: Proxy object disconnected
,08-22 17:05:27.756   873   873 D BluetoothA2dp: Proxy object disconnected
08-22 17:05:27.757  1367  1367 D HeadsetProfile: Bluetooth service disconnected
08-22 17:05:27.757  1367  1367 D BluetoothA2dp: Proxy object disconnected
08-22 17:05:27.757  3523  3523 D HidService: Received stop request...Stopping profile...
,08-22 17:05:27.758  3523  3523 D HidService: Stopping Bluetooth HidService
,08-22 17:05:27.759  1367  1367 D BluetoothInputDevice: Proxy object disconnected
,08-22 17:05:27.759  1367  1367 D HidProfile: Bluetooth service disconnected
08-22 17:05:27.759  3523  3523 D HealthService: Received stop request...Stopping profile...
08-22 17:05:27.760  3523  3523 D PanService: Received stop request...Stopping profile...
08-22 17:05:27.761  1367  1367 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-22 17:05:27.762  3576  3576 D DockEventReceiver: finishStartingService: stopping service
08-22 17:05:27.762  1367  1367 D PanProfile: Bluetooth service disconnected
,08-22 17:05:27.762  3523  3523 D BluetoothMapService: Received stop request...Stopping profile...
08-22 17:05:27.762  3523  3523 D BluetoothMapService: stop()
08-22 17:05:27.763  3523  3523 D BluetoothMapAppObserver: deinitObservers()
08-22 17:05:27.763  3523  3523 D BluetoothMapAppObserver: removeReceiver()
08-22 17:05:27.764  3576  3576 D HeadsetProfile: Bluetooth service disconnected
08-22 17:05:27.764  1367  1367 D BluetoothMap: Proxy object disconnected
08-22 17:05:27.765  1367  1367 D MapProfile: Bluetooth service disconnected
,08-22 17:05:27.765  3576  3576 D BluetoothA2dp: Proxy object disconnected
,08-22 17:05:27.765  3523  3523 I BtOppRfcommListener: stopping Accept Thread
,08-22 17:05:27.765  3523  3631 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-22 17:05:27.765  3523  3631 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-22 17:05:27.765  3576  3576 D BluetoothInputDevice: Proxy object disconnected
08-22 17:05:27.766  3523  3523 V BluetoothAdapterState: isTurningOff()=true
08-22 17:05:27.766  3523  3523 V BluetoothAdapterState: isTurningOn()=false
,08-22 17:05:27.766  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
08-22 17:05:27.766  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
08-22 17:05:27.766  3576  3576 D HidProfile: Bluetooth service disconnected
08-22 17:05:27.768  3576  3576 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-22 17:05:27.768  3576  3576 D PanProfile: Bluetooth service disconnected
08-22 17:05:27.768  3576  3576 D BluetoothMap: Proxy object disconnected
08-22 17:05:27.768  3576  3576 D MapProfile: Bluetooth service disconnected
,08-22 17:05:27.770  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-22 17:05:27.771  3523  3523 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-22 17:05:27.771  3523  3523 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-22 17:05:27.771  3523  3561 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-22 17:05:27.771  3523  3570 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 17:05:27.771  3523  3570 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 17:05:27.771  3523  3570 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 17:05:27.771  3523  3561 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-22 17:05:27.771  3523  3523 V BluetoothAdapterState: isTurningOff()=true
08-22 17:05:27.772  3523  3523 V BluetoothAdapterState: isTurningOn()=false
,08-22 17:05:27.772  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
08-22 17:05:27.772  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
08-22 17:05:27.773  3523  3570 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 17:05:27.773  3523  3570 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 17:05:27.773  3523  3570 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 17:05:27.773  3523  3570 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 17:05:27.773  3523  3570 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 17:05:27.773  3523  3570 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 17:05:27.773  3523  3561 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-22 17:05:27.774  3523  3523 V BluetoothAdapterState: isTurningOff()=true
08-22 17:05:27.774  3523  3523 V BluetoothAdapterState: isTurningOn()=false
08-22 17:05:27.774  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 17:05:27.774  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
08-22 17:05:27.774  3523  3523 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-22 17:05:27.774  3523  3523 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-22 17:05:27.774  3523  3523 V BluetoothAdapterState: isTurningOff()=true
,08-22 17:05:27.774  3523  3561 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-22 17:05:27.774  3523  3523 V BluetoothAdapterState: isTurningOn()=false
08-22 17:05:27.775  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
08-22 17:05:27.775  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
08-22 17:05:27.775  3523  3523 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-22 17:05:27.775  3523  3561 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-22 17:05:27.775  3523  3523 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-22 17:05:27.776  3523  3523 V BluetoothAdapterState: isTurningOff()=true
08-22 17:05:27.776  3523  3523 V BluetoothAdapterState: isTurningOn()=false
,08-22 17:05:27.776  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
08-22 17:05:27.776  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
08-22 17:05:27.777  3523  3523 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-22 17:05:27.777  3523  3523 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-22 17:05:27.778  3523  3523 D BluetoothMapService: MAP Service closeService in
08-22 17:05:27.778  3523  3523 V BluetoothAdapterState: isTurningOff()=true
08-22 17:05:27.778  3523  3523 V BluetoothAdapterState: isTurningOn()=false
08-22 17:05:27.778  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
08-22 17:05:27.778  3523  3523 V BluetoothAdapterState: isBleTurningOff()=false
08-22 17:05:27.778  3523  3523 D BluetoothMapService: cleanup()
08-22 17:05:27.778  3523  3523 D BluetoothMapService: MAP Service closeService in
08-22 17:05:27.779  3523  3555 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-22 17:05:27.779  3523  3555 D BluetoothAdapterProperties: Setting state to 15
08-22 17:05:27.779  3523  3555 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-22 17:05:27.779  3523  3555 I BluetoothAdapterState: Entering BleOnState
08-22 17:05:27.779  1367  1380 D BluetoothA2dp: onBluetoothStateChange: up=false
08-22 17:05:27.781  3576  3587 D BluetoothMap: onBluetoothStateChange: up=false
08-22 17:05:27.782  3576  3586 D BluetoothPbap: onBluetoothStateChange: up=false
,08-22 17:05:27.784  1367  1367 D BluetoothPbap: Proxy object disconnected
,08-22 17:05:27.784  1367  1367 D PbapServerProfile: Bluetooth service disconnected
08-22 17:05:27.785  3576  3587 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-22 17:05:27.785  1367  1379 D BluetoothMap: onBluetoothStateChange: up=false
,08-22 17:05:27.786   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-22 17:05:27.786  1367  2019 D BluetoothPan: onBluetoothStateChange on: false
08-22 17:05:27.787  3576  3586 D BluetoothPan: onBluetoothStateChange on: false,
08-22 17:05:27.787   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 17:05:27.787  3576  3587 D BluetoothA2dp: onBluetoothStateChange: up=false
08-22 17:05:27.788   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-22 17:05:27.788  3576  3586 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-22 17:05:27.788  1367  1380 D BluetoothPbap: onBluetoothStateChange: up=false
08-22 17:05:27.789  1367  1379 D BluetoothHeadset: onBluetoothStateChange: up=false,
08-22 17:05:27.789  1367  2019 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-22 17:05:27.789  1914  1935 D BluetoothHeadset: onBluetoothStateChange: up=false,
08-22 17:05:27.789   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 17:05:27.790  3523  3555 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-22 17:05:27.790  3523  3555 D BluetoothAdapterProperties: Setting state to 16
08-22 17:05:27.790  3523  3555 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-22 17:05:27.793  3523  3555 D BluetoothAdapterProperties: onBleDisable
08-22 17:05:27.793  3523  3555 I BluetoothAdapterState: Entering PendingCommandState
,08-22 17:05:27.793  3523  3556 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-22 17:05:27.793  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 17:05:27.794  3523  3561 D BluetoothAdapterProperties: Scan Mode:20
,08-22 17:05:27.794  3523  3570 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-22 17:05:27.794  3523  3570 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 17:05:27.795  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 17:05:27.795  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 17:05:27.797  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 17:05:27.798  3576  3576 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-22 17:05:27.803  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 17:05:27.803  3576  3576 D DockEventReceiver: finishStartingService: stopping service
,08-22 17:05:27.996  3523  3561 I bt_hci  : shut_down
,08-22 17:05:28.002  3523  3568 I bt_vendor: low_power_mode_cb
,08-22 17:05:28.002  3523  3568 D bt_hwcfg: hw_epilog_process
,08-22 17:05:28.024  3523  3568 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-22 17:05:28.024  3523  3568 I bt_vendor: epilog_cb
,08-22 17:05:28.024  3523  3568 I bt_hci  : epilog_finished_callback
,08-22 17:05:28.027  3523  3561 I bt_hci_h4: hal_close
,08-22 17:05:28.028  3523  3561 I bt_userial_vendor: device fd = 51 close
,08-22 17:05:28.153  3523  3556 D bt_stack_manager: event_shut_down_stack finished.
,08-22 17:05:28.154  3523  3555 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-22 17:05:28.158  3523  3523 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-22 17:05:28.159  3523  3555 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-22 17:05:28.160  3523  3523 D BtGatt.GattService: Received stop request...Stopping profile...
,08-22 17:05:28.160  3523  3523 D BtGatt.GattService: stop()
08-22 17:05:28.160  3523  3523 D BtGatt.AdvertiseManager: advertise clients cleared
,08-22 17:05:28.162  3523  3523 V BluetoothAdapterState: isTurningOff()=false
,08-22 17:05:28.163  3523  3523 V BluetoothAdapterState: isTurningOn()=false
,08-22 17:05:28.163  3523  3523 V BluetoothAdapterState: isBleTurningOn()=false
08-22 17:05:28.163  3523  3523 V BluetoothAdapterState: isBleTurningOff()=true
,08-22 17:05:28.164  3523  3555 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-22 17:05:28.164  3523  3555 D BluetoothAdapterProperties: Setting state to 10
,08-22 17:05:28.164  3523  3555 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-22 17:05:28.164  3523  3555 I BluetoothAdapterState: Entering OffState
,08-22 17:05:28.166   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-22 17:05:28.181  3523  3523 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-22 17:05:28.181  3523  3523 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-22 17:05:28.182  3523  3556 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.,
,08-22 17:05:28.185  3523  3556 D bt_stack_manager: event_clean_up_stack finished.
,08-22 17:05:28.185  3523  3523 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-22 17:05:28.187  3523  3523 I art     : System.exit called, status: 0
,08-22 17:05:28.187  3523  3523 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-22 17:05:28.222   873  1374 I ActivityManager: Process com.android.bluetooth (pid 3523) has died
,08-22 17:05:28.594  3762  3838 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-22 17:05:29.238   873  1955 I ActivityManager: Killing 3668:com.google.android.youtube/u0a86 (adj 15): empty #17
,08-22 17:05:30.520  3927  3952 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-22 17:05:30.693   873  1310 D ConnectivityService: handlePromptUnvalidated 100
,08-22 17:05:30.752   873   890 I ActivityManager: Start proc 4012:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-22 17:05:30.883  4012  4012 D AdapterServiceConfig: Adding HeadsetService
,08-22 17:05:30.883  4012  4012 D AdapterServiceConfig: Adding A2dpService
,08-22 17:05:30.884  4012  4012 D AdapterServiceConfig: Adding HidService
,08-22 17:05:30.884  4012  4012 D AdapterServiceConfig: Adding HealthService
,08-22 17:05:30.884  4012  4012 D AdapterServiceConfig: Adding PanService
,08-22 17:05:30.884  4012  4012 D AdapterServiceConfig: Adding GattService
,08-22 17:05:30.885  4012  4012 D AdapterServiceConfig: Adding BluetoothMapService
,08-22 17:05:30.900  4012  4012 D BluetoothAdapterState: make() - Creating AdapterState
08-22 17:05:30.900   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ecd72dd:true
,08-22 17:05:30.904  4012  4012 I bt_bluedroid: init
,08-22 17:05:30.905  4012  4024 I BluetoothAdapterState: Entering OffState
,08-22 17:05:30.908  4012  4025 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-22 17:05:30.908  4012  4025 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-22 17:05:30.908  4012  4025 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-22 17:05:30.908  4012  4025 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-22 17:05:30.909  4012  4012 I bt_bluedroid: get_profile_interface socket
,08-22 17:05:30.911  4012  4012 I bt_bluedroid: get_profile_interface sdp
,08-22 17:05:30.915  4012  4028 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-22 17:05:30.916  4012  4023 I bt_bluedroid: config_hci_snoop_log
,08-22 17:05:30.918  4012  4028 D BluetoothAdapterProperties: Name is: Nexus 6
08-22 17:05:30.918   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-22 17:05:30.927  4012  4024 D BluetoothAdapterState: Current state: OFF, message: 0
,08-22 17:05:30.928  4012  4024 D BluetoothAdapterProperties: Setting state to 14
08-22 17:05:30.928  4012  4024 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-22 17:05:30.932  4012  4024 D BluetoothBondStateMachine: make
,08-22 17:05:30.937  4012  4029 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-22 17:05:30.946  4012  4024 I BluetoothAdapterState: Entering PendingCommandState
,08-22 17:05:30.947  4012  4012 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-22 17:05:30.955  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
,08-22 17:05:30.957  4012  4012 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-22 17:05:30.958  4012  4012 D BtGatt.GattService: Received start request. Starting profile...
,08-22 17:05:30.958  4012  4012 D BtGatt.GattService: start()
,08-22 17:05:30.958  4012  4012 I bt_bluedroid: get_profile_interface gatt
08-22 17:05:30.960  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
,08-22 17:05:30.960  4012  4012 D BtGatt.AdvertiseManager: advertise manager created
,08-22 17:05:30.971  4012  4012 V BluetoothAdapterState: isTurningOff()=false
,08-22 17:05:30.972  4012  4012 V BluetoothAdapterState: isTurningOn()=false
08-22 17:05:30.972  4012  4012 V BluetoothAdapterState: isBleTurningOn()=true
08-22 17:05:30.972  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-22 17:05:30.973  4012  4024 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-22 17:05:30.973  4012  4024 I bt_bluedroid: enable
,08-22 17:05:30.974  4012  4025 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-22 17:05:30.974  4012  4025 I bt_hci  : start_up
,08-22 17:05:30.984  4012  4025 I bt_vendor: alloc value 0xb39b0189
08-22 17:05:30.984  4012  4025 I bt_vendor: init
08-22 17:05:30.984  4012  4025 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-22 17:05:30.984  4012  4025 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-22 17:05:31.090  4012  4025 D bt_hci  : start_up starting async portion
08-22 17:05:31.091  4012  4032 I bt_hci  : event_finish_startup
08-22 17:05:31.091  4012  4032 I bt_hci_h4: hal_open
08-22 17:05:31.091  4012  4032 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-22 17:05:31.101  4012  4032 I bt_userial_vendor: device fd = 51 open
,08-22 17:05:31.134  4012  4032 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-22 17:05:31.165  4012  4032 D bt_hwcfg: Chipset BCM4354A2
08-22 17:05:31.165  4012  4032 D bt_hwcfg: Target name = [BCM4354A2]
,08-22 17:05:31.166  4012  4032 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-22 17:05:31.852  4012  4032 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-22 17:05:31.853  4012  4032 D bt_hwcfg: Settlement delay -- 100 ms
08-22 17:05:31.854  4012  4032 I bt_hwcfg: Setting fw settlement delay to 100 
,08-22 17:05:31.970  4012  4032 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-22 17:05:31.970  4012  4032 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-22 17:05:32.001  4012  4032 I bt_hwcfg: vendor lib fwcfg completed
,08-22 17:05:32.001  4012  4032 I bt_vendor: firmware callback
,08-22 17:05:32.001  4012  4032 I bt_hci  : firmware_config_callback
,08-22 17:05:32.003   873  1956 I ActivityManager: Killing 2710:com.android.vending/u0a19 (adj 15): empty #17
,08-22 17:05:32.050  4012  4036 I bt_btu  : btu_task pending for preload complete event
,08-22 17:05:32.051  4012  4036 I bt_btu_task: Bluetooth chip preload is complete
,08-22 17:05:32.051  4012  4036 I bt_btu  : btu_task received preload complete event
,08-22 17:05:32.058  4012  4036 I         : BTE_InitTraceLevels -- TRC_HCI
,08-22 17:05:32.058  4012  4036 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-22 17:05:32.058  4012  4036 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-22 17:05:32.058  4012  4036 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-22 17:05:32.058  4012  4036 I         : BTE_InitTraceLevels -- TRC_AVRC
08-22 17:05:32.058  4012  4036 I         : BTE_InitTraceLevels -- TRC_A2D
,08-22 17:05:32.059  4012  4036 I         : BTE_InitTraceLevels -- TRC_BNEP
08-22 17:05:32.059  4012  4036 I         : BTE_InitTraceLevels -- TRC_BTM
,08-22 17:05:32.059  4012  4036 I         : BTE_InitTraceLevels -- TRC_GAP
08-22 17:05:32.059  4012  4036 I         : BTE_InitTraceLevels -- TRC_PAN
,08-22 17:05:32.059  4012  4036 I         : BTE_InitTraceLevels -- TRC_SDP
08-22 17:05:32.059  4012  4036 I         : BTE_InitTraceLevels -- TRC_GATT
,08-22 17:05:32.059  4012  4036 I         : BTE_InitTraceLevels -- TRC_SMP
08-22 17:05:32.059  4012  4036 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-22 17:05:32.059  4012  4036 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-22 17:05:32.191  4012  4036 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb392dd9d
,08-22 17:05:32.191  4012  4036 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb392dd9d 
,08-22 17:05:32.205  4012  4028 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-22 17:05:32.207  4012  4028 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-22 17:05:32.208  4012  4028 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-22 17:05:32.213  4012  4028 D BluetoothAdapterProperties: Name is: Nexus 6
,08-22 17:05:32.216  4012  4028 D BluetoothAdapterProperties: Scan Mode:20
,08-22 17:05:32.217  4012  4028 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-22 17:05:32.218  4012  4028 D bt_hci  : do_postload posting postload work item
,08-22 17:05:32.218  4012  4032 I bt_hci  : event_postload
,08-22 17:05:32.218  4012  4032 I bt_vendor: sco_config_cb
,08-22 17:05:32.218  4012  4032 I bt_hci  : sco_config_callback postload finished.
,08-22 17:05:32.221  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 17:05:32.222  4012  4028 D bt_bte_conf: Device ID record 1 : primary
08-22 17:05:32.222  4012  4028 D bt_bte_conf:   vendorId            = 000f
08-22 17:05:32.222  4012  4028 D bt_bte_conf:   vendorIdSource      = 0001
08-22 17:05:32.223  4012  4028 D bt_bte_conf:   product             = 1200
08-22 17:05:32.223  4012  4028 D bt_bte_conf:   version             = 1436
,08-22 17:05:32.223  4012  4028 D bt_bte_conf:   clientExecutableURL = 
,08-22 17:05:32.224  4012  4028 D bt_bte_conf:   serviceDescription  = 
,08-22 17:05:32.224  4012  4028 D bt_bte_conf:   documentationURL    = 
,08-22 17:05:32.224  4012  4032 I bt_vendor: low_power_mode_cb,
,08-22 17:05:32.224  4012  4028 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-22 17:05:32.224  4012  4025 D bt_stack_manager: event_start_up_stack finished
08-22 17:05:32.225  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 17:05:32.226  4012  4024 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-22 17:05:32.226  4012  4024 D BluetoothAdapterProperties: Setting state to 15
,08-22 17:05:32.227  4012  4024 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-22 17:05:32.229  4012  4024 I BluetoothAdapterState: Entering BleOnState
,08-22 17:05:32.234  4012  4024 D BluetoothAdapterState: Current state: BLE ON, message: 1,
,08-22 17:05:32.234  4012  4024 D BluetoothAdapterProperties: Setting state to 11
,08-22 17:05:32.234  4012  4024 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-22 17:05:32.242  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
,08-22 17:05:32.245  4012  4012 D HeadsetService: Received start request. Starting profile...
,08-22 17:05:32.248  4012  4012 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-22 17:05:32.253  4012  4012 D HeadsetStateMachine: make
,08-22 17:05:32.254  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 17:05:32.255  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 17:05:32.262  4012  4024 I BluetoothAdapterState: Entering PendingCommandState
,08-22 17:05:32.267  4012  4012 D HeadsetStateMachine: max_hf_connections = 1
,08-22 17:05:32.268  4012  4012 I bt_bluedroid: get_profile_interface handsfree
,08-22 17:05:32.269  4012  4028 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-22 17:05:32.269  4012  4028 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-22 17:05:32.275  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
,08-22 17:05:32.275  4012  4012 D A2dpService: Received start request. Starting profile...
,08-22 17:05:32.276  4012  4012 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-22 17:05:32.276  4012  4012 I bt_bluedroid: get_profile_interface avrcp
,08-22 17:05:32.282  4012  4012 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-22 17:05:32.282  4012  4012 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-22 17:05:32.282  4012  4012 D A2dpStateMachine: make
,08-22 17:05:32.284  4012  4012 I bt_bluedroid: get_profile_interface a2dp
,08-22 17:05:32.285  4012  4028 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-22 17:05:32.287  4012  4045 D A2dpStateMachine: Enter Disconnected: -2
,08-22 17:05:32.288  4012  4012 I BluetoothHidServiceJni: classInitNative: succeeds
,08-22 17:05:32.290  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
,08-22 17:05:32.290  4012  4012 D HidService: Received start request. Starting profile...
,08-22 17:05:32.291  4012  4012 I bt_bluedroid: get_profile_interface hidhost
,08-22 17:05:32.291  4012  4028 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb390f3e5
,08-22 17:05:32.291  4012  4028 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-22 17:05:32.292  4012  4012 D HidService: setHidService(): set to: null
,08-22 17:05:32.293  4012  4012 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-22 17:05:32.294  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-22 17:05:32.294  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
08-22 17:05:32.295  4012  4012 D HealthService: Received start request. Starting profile...
,08-22 17:05:32.297  4012  4012 I bt_bluedroid: get_profile_interface health
08-22 17:05:32.298  4012  4012 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-22 17:05:32.298  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb,
,08-22 17:05:32.299  4012  4012 D PanService: Received start request. Starting profile...
,08-22 17:05:32.299  4012  4012 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-22 17:05:32.299  4012  4012 I bt_bluedroid: get_profile_interface pan
,08-22 17:05:32.300  4012  4028 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-22 17:05:32.310  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
,08-22 17:05:32.312  4012  4012 D BluetoothMapService: Received start request. Starting profile...
,08-22 17:05:32.312  4012  4012 D BluetoothMapService: start()
,08-22 17:05:32.318  4012  4012 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-22 17:05:32.320  4012  4012 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-22 17:05:32.320  4012  4012 D BluetoothMapAppObserver: createReceiver()
,08-22 17:05:32.322  4012  4012 D BluetoothMapAppObserver: initObservers()
,08-22 17:05:32.322  4012  4012 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-22 17:05:32.340  4012  4012 V BluetoothAdapterState: isTurningOff()=false
,08-22 17:05:32.340  4012  4012 V BluetoothAdapterState: isTurningOn()=true
,08-22 17:05:32.340  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-22 17:05:32.340  4012  4043 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-22 17:05:32.340  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 17:05:32.342  4012  4012 V BluetoothAdapterState: isTurningOff()=false
,08-22 17:05:32.342  4012  4012 V BluetoothAdapterState: isTurningOn()=true
,08-22 17:05:32.342  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 17:05:32.342  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 17:05:32.343  4012  4012 V BluetoothAdapterState: isTurningOff()=false
,08-22 17:05:32.343  4012  4012 V BluetoothAdapterState: isTurningOn()=true
08-22 17:05:32.343  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 17:05:32.343  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 17:05:32.344  4012  4012 V BluetoothAdapterState: isTurningOff()=false
08-22 17:05:32.345  4012  4012 V BluetoothAdapterState: isTurningOn()=true
,08-22 17:05:32.345  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 17:05:32.345  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 17:05:32.345  4012  4012 V BluetoothAdapterState: isTurningOff()=false
08-22 17:05:32.345  4012  4012 V BluetoothAdapterState: isTurningOn()=true
,08-22 17:05:32.345  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 17:05:32.345  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-22 17:05:32.345  4012  4012 V BluetoothAdapterState: isTurningOff()=false
08-22 17:05:32.345  4012  4012 V BluetoothAdapterState: isTurningOn()=true
08-22 17:05:32.345  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 17:05:32.346  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-22 17:05:32.346  4012  4024 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-22 17:05:32.346  4012  4024 D BluetoothAdapterProperties: ScanMode =  20
08-22 17:05:32.347  4012  4024 D BluetoothAdapterProperties: State =  11
,08-22 17:05:32.349  4012  4028 D BluetoothAdapterProperties: Scan Mode:21
08-22 17:05:32.349  4012  4028 D BluetoothAdapterProperties: Discoverable Timeout:120
08-22 17:05:32.350  4012  4024 D BluetoothAdapterProperties: Setting state to 12
08-22 17:05:32.350  4012  4024 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-22 17:05:32.351  1367  1379 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 17:05:32.351  4012  4024 I BluetoothAdapterState: Entering OnState
08-22 17:05:32.354  3576  3587 D BluetoothMap: onBluetoothStateChange: up=true
08-22 17:05:32.355  1367  1367 D BluetoothA2dp: Proxy object connected
,08-22 17:05:32.356  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 17:05:32.356  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:32.356  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:32.356  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 17:05:32.356  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 17:05:32.356  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:32.356  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:32.356  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 17:05:32.358  3576  3586 D BluetoothPbap: onBluetoothStateChange: up=true
08-22 17:05:32.358  4012  4012 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-22 17:05:32.359  4012  4012 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-22 17:05:32.359  3463  3463 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 17:05:32.360  3576  4004 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-22 17:05:32.360  1367  1380 D BluetoothMap: onBluetoothStateChange: up=true
08-22 17:05:32.361  4012  4012 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 17:05:32.364  4012  4012 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 17:05:32.364   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 17:05:32.365  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 17:05:32.365  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:32.365  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:32.365  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 17:05:32.365  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 17:05:32.365  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:32.365  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:32.365  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 17:05:32.365  4012  4012 D ObexServerSockets: Succeed to create listening sockets 
08-22 17:05:32.366  4012  4012 D ObexServerSockets0: startAccept()
08-22 17:05:32.366  4012  4012 D ObexServerSockets0: prepareForNewConnect()
08-22 17:05:32.366   873   873 D BluetoothA2dp: Proxy object connected
08-22 17:05:32.369  1367  1379 D BluetoothPan: onBluetoothStateChange on: true
,08-22 17:05:32.370  4012  4012 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-22 17:05:32.369  3463  3463 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 17:05:32.370  4012  4012 D BluetoothSdpJni: SDP Create record success - handle: 0
08-22 17:05:32.371  4012  4051 D ObexServerSockets0: Accepting socket connection...
,08-22 17:05:32.373  3576  3576 D BluetoothMap: Proxy object connected
08-22 17:05:32.373  3576  3576 D MapProfile: Bluetooth service connected
08-22 17:05:32.373  1367  1367 D BluetoothMap: Proxy object connected
,08-22 17:05:32.373  3576  3576 D BluetoothMap: getConnectedDevices()
08-22 17:05:32.373  1367  1367 D MapProfile: Bluetooth service connected
,08-22 17:05:32.373  1367  1367 D BluetoothMap: getConnectedDevices()
,08-22 17:05:32.373  4012  4052 D ObexServerSockets0: Accepting socket connection...
08-22 17:05:32.375  3576  3586 D BluetoothPan: onBluetoothStateChange on: true
08-22 17:05:32.376  1367  1367 D BluetoothPan: BluetoothPAN Proxy object connected
08-22 17:05:32.376  1367  1367 D PanProfile: Bluetooth service connected
08-22 17:05:32.377   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 17:05:32.378  3576  3587 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 17:05:32.378  3576  3576 D BluetoothPan: BluetoothPAN Proxy object connected
,08-22 17:05:32.379  3576  3576 D PanProfile: Bluetooth service connected
08-22 17:05:32.380   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-22 17:05:32.380  3576  4004 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-22 17:05:32.381  3576  3576 D BluetoothA2dp: Proxy object connected
,08-22 17:05:32.384  1367  2019 D BluetoothPbap: onBluetoothStateChange: up=true
,08-22 17:05:32.387  3576  3576 D BluetoothInputDevice: Proxy object connected
,08-22 17:05:32.387  1367  1379 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 17:05:32.387  3576  3576 D HidProfile: Bluetooth service connected
,08-22 17:05:32.388  1367  1380 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-22 17:05:32.389  1367  1367 D BluetoothInputDevice: Proxy object connected
,08-22 17:05:32.389  1914  1935 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 17:05:32.390  1367  1367 D HidProfile: Bluetooth service connected
08-22 17:05:32.390   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-22 17:05:32.391   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-22 17:05:32.393  4012  4012 D BluetoothMapService: onReceive
,08-22 17:05:32.393  4012  4012 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-22 17:05:32.393  4012  4012 D BluetoothMapService: STATE_ON
,08-22 17:05:32.394  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 17:05:32.395  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 17:05:32.399  3576  3576 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 17:05:32.404  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 17:05:32.407  3576  3576 D DockEventReceiver: finishStartingService: stopping service
,08-22 17:05:32.413  1367  1367 D BluetoothPbap: Proxy object connected
,08-22 17:05:32.413  1367  1367 D PbapServerProfile: Bluetooth service connected
,08-22 17:05:32.414  3576  3576 D BluetoothPbap: Proxy object connected
,08-22 17:05:32.415  3576  3576 D PbapServerProfile: Bluetooth service connected
,08-22 17:05:32.418  4012  4012 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-22 17:05:32.419  4012  4012 D ObexServerSockets0: prepareForNewConnect()
,08-22 17:05:32.422  4012  4057 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 17:05:32.436  4012  4061 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 17:05:32.437  4012  4061 I BtOppRfcommListener: Accept thread started.
,08-22 17:05:32.461   873   873 D BluetoothHeadset: Proxy object connected
,08-22 17:05:32.461  3576  3586 D BluetoothHeadset: Proxy object connected
,08-22 17:05:32.462   873   873 D BluetoothHeadset: Proxy object connected
,08-22 17:05:32.462  3576  3576 D HeadsetProfile: Bluetooth service connected
,08-22 17:05:32.462  1914  2045 D BluetoothHeadset: Proxy object connected
08-22 17:05:32.462  1367  1379 D BluetoothHeadset: Proxy object connected
,08-22 17:05:32.463  1367  1367 D HeadsetProfile: Bluetooth service connected
08-22 17:05:32.463   873   873 D BluetoothHeadset: Proxy object connected
,08-22 17:05:32.477   873   890 D BluetoothHeadset: Proxy object connected
,08-22 17:05:32.480   873   890 D BluetoothHeadset: Proxy object connected
,08-22 17:05:32.487  1367  2019 D BluetoothHeadset: Proxy object connected
,08-22 17:05:32.488  1367  1367 D HeadsetProfile: Bluetooth service connected
,08-22 17:05:32.490  1914  1943 D BluetoothHeadset: Proxy object connected
,08-22 17:05:32.490   873   890 D BluetoothHeadset: Proxy object connected
,08-22 17:05:33.699   873  1374 I ActivityManager: Start proc 4063:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,08-22 17:05:33.717  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 17:05:33.717  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 17:05:33.806  4063  4063 W System  : ClassLoader referenced unknown path: /system/priv-app/Phonesky/lib/arm
,08-22 17:05:33.898  4063  4063 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-22 17:05:33.964  4063  4063 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,08-22 17:05:33.979  4063  4063 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-22 17:05:33.980  4063  4063 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-22 17:05:34.041   873  1707 I ActivityManager: Killing 3762:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-22 17:05:34.046  4063  4073 D Finsky  : [324] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-22 17:05:34.145  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 17:05:34.151  4063  4063 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,08-22 17:05:34.152  4063  4063 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
08-22 17:05:34.152  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,08-22 17:05:34.159  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 17:05:34.160  4063  4063 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-22 17:05:34.170  4063  4098 D Ads     : Skipping gmscore version check
,08-22 17:05:34.197  4063  4063 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-22 17:05:34.202  4063  4098 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-22 17:05:34.225  1508  2791 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-22 17:05:34.225  1508  2791 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-22 17:05:34.225  1508  2791 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-22 17:05:34.225  1508  2791 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 17:05:34.245  4063  4073 D Finsky  : [324] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-22 17:05:34.982  4063  4063 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,08-22 17:05:35.027  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 17:05:35.111  1508  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-22 17:05:35.112  1508  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-22 17:05:35.112  1508  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 17:05:35.113  1508  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 17:05:35.172  4063  4063 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-22 17:05:35.192  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 17:05:35.256  1508  2791 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-22 17:05:35.257  1508  2791 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-22 17:05:35.257  1508  2791 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-22 17:05:35.257  1508  2791 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 17:05:35.353  4063  4103 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-22 17:05:35.357  4063  4063 W Finsky  : [1] GearheadStateMonitor$3.onConnectionFailed: Could not connect to GMS for Auto connection state: ConnectionResult{statusCode=SERVICE_VERSION_UPDATE_REQUIRED, resolution=null, message=null}
,08-22 17:05:35.358  4063  4063 V Finsky  : [1] GearheadStateMonitor.access$100: mIsProjecting:false
,08-22 17:05:35.359  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 17:05:35.407  1508  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-22 17:05:35.408  1508  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-22 17:05:35.408  1508  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-22 17:05:35.408  1508  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 17:05:35.439  4063  4063 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-22 17:05:35.688  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 17:05:35.745  1508  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-22 17:05:35.745  1508  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-22 17:05:35.746  1508  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 17:05:35.746  1508  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 17:05:35.794  4063  4063 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-22 17:05:35.797  4063  4063 D Finsky  : [1] WearSupportService.startHygiene: disabled
,08-22 17:05:35.804  4063  4063 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,08-22 17:05:35.815  4063  4063 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,08-22 17:05:35.827  4063  4105 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-22 17:05:36.685   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-22 17:05:36.698  1858  1858 I Keyboard.Facilitator: onFinishInput()
,08-22 17:05:36.710   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-22 17:05:36.710   873   893 I Adreno  : Build Date                       : 10/20/15
08-22 17:05:36.710   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-22 17:05:36.710   873   893 I Adreno  : Local Branch                     : M14
08-22 17:05:36.710   873   893 I Adreno  : Remote Branch                    : 
08-22 17:05:36.710   873   893 I Adreno  : Remote Branch                    : 
08-22 17:05:36.710   873   893 I Adreno  : Reconstruct Branch               : 
,08-22 17:05:36.723  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 17:05:36.724  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@67f5781 added. We now have 6 listener(s)
08-22 17:05:36.724  3463  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 17:05:36.728  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 17:05:36.728  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fa7c026 added. We now have 7 listener(s)
08-22 17:05:36.729  3463  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 17:05:36.731  3463  3512 I System.out: IsBluetoothEnabled
,08-22 17:05:36.738  4012  4024 D BluetoothAdapterState: Current state: ON, message: 23
,08-22 17:05:36.742  4012  4024 D BluetoothAdapterProperties: Setting state to 13
08-22 17:05:36.742  4012  4024 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-22 17:05:36.744  4012  4024 D BluetoothAdapterProperties: onBluetoothDisable()
,08-22 17:05:36.745  4012  4024 I BluetoothAdapterState: Entering PendingCommandState
,08-22 17:05:36.749  4012  4028 D BluetoothAdapterProperties: Scan Mode:20
,08-22 17:05:36.755  4012  4024 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21,
,08-22 17:05:36.756  3463  3463 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 17:05:36.759  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,08-22 17:05:36.759  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:36.759  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:36.759  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 17:05:36.759  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 17:05:36.759  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:36.759  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:36.759  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 17:05:36.761  4012  4012 D HeadsetService: Received stop request...Stopping profile...
,08-22 17:05:36.766   873   873 D BluetoothHeadset: Proxy object disconnected
,08-22 17:05:36.764  3463  3463 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 17:05:36.767  3463  3463 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 17:05:36.768  3576  4004 D BluetoothHeadset: Proxy object disconnected
08-22 17:05:36.768  3576  3576 D HeadsetProfile: Bluetooth service disconnected
,08-22 17:05:36.768   873   873 D BluetoothHeadset: Proxy object disconnected
,08-22 17:05:36.768  1914  1943 D BluetoothHeadset: Proxy object disconnected
08-22 17:05:36.769  1367  1379 D BluetoothHeadset: Proxy object disconnected
,08-22 17:05:36.769  4012  4012 D A2dpService: Received stop request...Stopping profile...
08-22 17:05:36.770  1367  1367 D HeadsetProfile: Bluetooth service disconnected
,08-22 17:05:36.771   873   873 D BluetoothHeadset: Proxy object disconnected
,08-22 17:05:36.771  4012  4045 D A2dpStateMachine: Exit Disconnected: -1
,08-22 17:05:36.772   873   873 D BluetoothA2dp: Proxy object disconnected
08-22 17:05:36.772  1367  1367 D BluetoothA2dp: Proxy object disconnected
,08-22 17:05:36.774  4012  4012 D HidService: Received stop request...Stopping profile...
,08-22 17:05:36.774  4012  4012 D HidService: Stopping Bluetooth HidService
08-22 17:05:36.776  1367  1367 D BluetoothInputDevice: Proxy object disconnected
08-22 17:05:36.775  3576  3576 D BluetoothA2dp: Proxy object disconnected
08-22 17:05:36.776  1367  1367 D HidProfile: Bluetooth service disconnected
08-22 17:05:36.776  4012  4012 V BluetoothAdapterState: isTurningOff()=true
,08-22 17:05:36.776  3576  3576 D BluetoothInputDevice: Proxy object disconnected
08-22 17:05:36.777  4012  4012 V BluetoothAdapterState: isTurningOn()=false
08-22 17:05:36.777  3576  3576 D HidProfile: Bluetooth service disconnected
08-22 17:05:36.778  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-22 17:05:36.778  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-22 17:05:36.779  4012  4012 D HealthService: Received stop request...Stopping profile...
,08-22 17:05:36.788  4012  4012 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-22 17:05:36.789  4012  4012 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-22 17:05:36.790  4012  4036 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-22 17:05:36.790  4012  4036 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 17:05:36.790  4012  4036 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 17:05:36.790  4012  4028 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-22 17:05:36.790  4012  4028 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-22 17:05:36.790  4012  4012 D PanService: Received stop request...Stopping profile...
,08-22 17:05:36.791  1367  1367 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-22 17:05:36.791  1367  1367 D PanProfile: Bluetooth service disconnected
08-22 17:05:36.792  3576  3576 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-22 17:05:36.792  3576  3576 D PanProfile: Bluetooth service disconnected
,08-22 17:05:36.796  4012  4012 V BluetoothAdapterState: isTurningOff()=true
,08-22 17:05:36.796   280   301 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (167 us)
08-22 17:05:36.796  4012  4012 V BluetoothAdapterState: isTurningOn()=false
08-22 17:05:36.796  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-22 17:05:36.796  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-22 17:05:36.797  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 17:05:36.798  4012  4036 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 17:05:36.798  4012  4036 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 17:05:36.798  4012  4036 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 17:05:36.798  4012  4036 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 17:05:36.798  4012  4036 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 17:05:36.798  4012  4036 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 17:05:36.798  4012  4028 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-22 17:05:36.798  4012  4012 D BluetoothMapService: Received stop request...Stopping profile...
08-22 17:05:36.799  4012  4012 D BluetoothMapService: stop()
,08-22 17:05:36.800  4012  4012 D BluetoothMapAppObserver: deinitObservers()
08-22 17:05:36.800  4012  4012 D BluetoothMapAppObserver: removeReceiver()
08-22 17:05:36.801  4012  4012 V BluetoothAdapterState: isTurningOff()=true
08-22 17:05:36.801  4012  4012 V BluetoothAdapterState: isTurningOn()=false
08-22 17:05:36.801  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-22 17:05:36.801  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 17:05:36.802  4012  4012 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-22 17:05:36.804  4012  4012 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-22 17:05:36.804  4012  4028 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-22 17:05:36.805  4012  4012 V BluetoothAdapterState: isTurningOff()=true
08-22 17:05:36.807  4012  4012 V BluetoothAdapterState: isTurningOn()=false
,08-22 17:05:36.807  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-22 17:05:36.807  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-22 17:05:36.807  4012  4012 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-22 17:05:36.808  4012  4028 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-22 17:05:36.808  4012  4012 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-22 17:05:36.808  4012  4012 V BluetoothAdapterState: isTurningOff()=true
,08-22 17:05:36.810  4012  4012 V BluetoothAdapterState: isTurningOn()=false
,08-22 17:05:36.811  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-22 17:05:36.813  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-22 17:05:36.816  1367  1367 D BluetoothMap: Proxy object disconnected
08-22 17:05:36.816  1367  1367 D MapProfile: Bluetooth service disconnected
08-22 17:05:36.813  4012  4012 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-22 17:05:36.817  4012  4012 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-22 17:05:36.817  3576  3576 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 17:05:36.819  4012  4012 D BluetoothMapService: MAP Service closeService in
,08-22 17:05:36.819  4012  4012 D BluetoothMapMasInstance0: MAP Service shutdown
,08-22 17:05:36.820  4012  4012 D ObexServerSockets0: shutdown(block = true)
08-22 17:05:36.820  4012  4051 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-22 17:05:36.821  4012  4012 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-22 17:05:36.821  4012  4052 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-22 17:05:36.821  4012  4038 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-22 17:05:36.821  4012  4012 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-22 17:05:36.822  4012  4012 V BluetoothAdapterState: isTurningOff()=true
08-22 17:05:36.822  4012  4012 V BluetoothAdapterState: isTurningOn()=false
08-22 17:05:36.822  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-22 17:05:36.822  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-22 17:05:36.822  4012  4024 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-22 17:05:36.822  4012  4024 D BluetoothAdapterProperties: Setting state to 15
08-22 17:05:36.822  4012  4024 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-22 17:05:36.823  1367  1379 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 17:05:36.825  4012  4024 I BluetoothAdapterState: Entering BleOnState
08-22 17:05:36.827  3576  3587 D BluetoothMap: onBluetoothStateChange: up=false
08-22 17:05:36.827  4012  4012 D BluetoothMapService: cleanup()
08-22 17:05:36.827  4012  4012 D BluetoothMapService: MAP Service closeService in
,08-22 17:05:36.827  4012  4012 I BtOppRfcommListener: stopping Accept Thread
,08-22 17:05:36.829  4012  4061 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-22 17:05:36.830  4012  4061 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-22 17:05:36.838  3576  3586 D BluetoothPbap: onBluetoothStateChange: up=false
,08-22 17:05:36.839  3576  3576 D BluetoothMap: Proxy object disconnected
,08-22 17:05:36.839  3576  3576 D MapProfile: Bluetooth service disconnected
,08-22 17:05:36.840  1367  1367 D BluetoothPbap: Proxy object disconnected
08-22 17:05:36.840  3576  3587 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 17:05:36.840  1367  1367 D PbapServerProfile: Bluetooth service disconnected
08-22 17:05:36.840  1367  1379 D BluetoothMap: onBluetoothStateChange: up=false
08-22 17:05:36.840   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 17:05:36.840  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-22 17:05:36.840  1367  1380 D BluetoothPan: onBluetoothStateChange on: false
08-22 17:05:36.842  3576  4004 D BluetoothPan: onBluetoothStateChange on: false
,08-22 17:05:36.843   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 17:05:36.843  3576  3586 D BluetoothA2dp: onBluetoothStateChange: up=false
08-22 17:05:36.845   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 17:05:36.845  3576  3587 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-22 17:05:36.845  1367  2019 D BluetoothPbap: onBluetoothStateChange: up=false
08-22 17:05:36.845  1367  1379 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-22 17:05:36.846  1367  1380 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-22 17:05:36.846  1914  2047 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 17:05:36.846   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 17:05:36.847  4012  4024 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-22 17:05:36.847  4012  4024 D BluetoothAdapterProperties: Setting state to 16
,08-22 17:05:36.847  4012  4024 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-22 17:05:36.849  4012  4024 D BluetoothAdapterProperties: onBleDisable
,08-22 17:05:36.850  4012  4025 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-22 17:05:36.850  4012  4024 I BluetoothAdapterState: Entering PendingCommandState
08-22 17:05:36.850  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 17:05:36.850  4012  4028 D BluetoothAdapterProperties: Scan Mode:20
08-22 17:05:36.851  4012  4036 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-22 17:05:36.851  4012  4036 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-22 17:05:36.852  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 17:05:36.853  3576  3576 D DockEventReceiver: finishStartingService: stopping service
08-22 17:05:36.854  3576  3576 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-22 17:05:36.858  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-22 17:05:36.863  3576  3576 D DockEventReceiver: finishStartingService: stopping service
,08-22 17:05:37.053  4012  4028 I bt_hci  : shut_down
,08-22 17:05:37.068  4012  4032 D bt_hwcfg: hw_epilog_process
,08-22 17:05:37.069  4012  4032 I bt_vendor: low_power_mode_cb
,08-22 17:05:37.094  4012  4032 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-22 17:05:37.094  4012  4032 I bt_vendor: epilog_cb
,08-22 17:05:37.094  4012  4032 I bt_hci  : epilog_finished_callback,
,08-22 17:05:37.100  4012  4028 I bt_hci_h4: hal_close
,08-22 17:05:37.101  4012  4028 I bt_userial_vendor: device fd = 51 close
,08-22 17:05:37.230  4012  4025 D bt_stack_manager: event_shut_down_stack finished.
08-22 17:05:37.231  4012  4024 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-22 17:05:37.236  4012  4024 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-22 17:05:37.237  4012  4012 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-22 17:05:37.238  4012  4012 D BtGatt.GattService: Received stop request...Stopping profile...
08-22 17:05:37.238  4012  4012 D BtGatt.GattService: stop()
08-22 17:05:37.239  4012  4012 D BtGatt.AdvertiseManager: advertise clients cleared
,08-22 17:05:37.243  4012  4012 V BluetoothAdapterState: isTurningOff()=false
,08-22 17:05:37.243  4012  4012 V BluetoothAdapterState: isTurningOn()=false
,08-22 17:05:37.243  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 17:05:37.243  4012  4012 V BluetoothAdapterState: isBleTurningOff()=true
,08-22 17:05:37.244  4012  4024 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-22 17:05:37.245  4012  4024 D BluetoothAdapterProperties: Setting state to 10
,08-22 17:05:37.246  4012  4024 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-22 17:05:37.246  4012  4024 I BluetoothAdapterState: Entering OffState
,08-22 17:05:37.247   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-22 17:05:37.269  4012  4012 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-22 17:05:37.269  4012  4012 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-22 17:05:37.270  4012  4025 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-22 17:05:37.277  4012  4025 D bt_stack_manager: event_clean_up_stack finished.
08-22 17:05:37.278  4012  4012 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-22 17:05:37.280  4012  4012 I art     : System.exit called, status: 0
08-22 17:05:37.280  4012  4012 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-22 17:05:37.335   873  2237 I ActivityManager: Process com.android.bluetooth (pid 4012) has died
,08-22 17:05:37.392  3463  3463 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-22 17:05:37.392  3463  3463 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-22 17:05:37.436   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-22 17:05:37.436  3463  3463 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@70944a7 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@a5c9467, 16908290=android.view.AbsSavedState$1@a5c9467}, android:focusedViewId=100}]}]
,08-22 17:05:37.436  3463  3463 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-22 17:05:37.437  3463  3463 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-22 17:05:37.437  3463  3463 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-22 17:05:37.457   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-22 17:05:37.460   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,08-22 17:05:37.460   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-22 17:05:37.461   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-22 17:05:37.685   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-22 17:05:37.689   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-22 17:05:37.690   873  1333 D SurfaceControl: Excessive delay in setPowerMode(): 229ms
,08-22 17:05:37.694   873   893 I DreamManagerService: Entering dreamland.
,08-22 17:05:37.695   873   893 I PowerManagerService: Dozing...
,08-22 17:05:37.696   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-22 17:05:37.743  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 17:05:37.743  3463  3512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 17:05:37.743  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:37.743  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:37.743  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 17:05:37.743  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 17:05:37.743  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:37.743  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:37.743  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 17:05:37.743  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 17:05:37.744  3463  3512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 17:05:37.767   873   890 I ActivityManager: Start proc 4115:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-22 17:05:37.771   375  1281 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-22 17:05:37.771   375  1281 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-22 17:05:37.775   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 17:05:37.779   873  1308 E native  : do suspend false
,08-22 17:05:37.792  1903  4125 D NfcService: Discovery configuration equal, not updating.
,08-22 17:05:37.812   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
08-22 17:05:37.815   873  1308 E native  : do suspend true
,08-22 17:05:37.875  4115  4115 D AdapterServiceConfig: Adding HeadsetService
,08-22 17:05:37.875  4115  4115 D AdapterServiceConfig: Adding A2dpService
,08-22 17:05:37.875  4115  4115 D AdapterServiceConfig: Adding HidService
,08-22 17:05:37.876  4115  4115 D AdapterServiceConfig: Adding HealthService
08-22 17:05:37.876  4115  4115 D AdapterServiceConfig: Adding PanService
08-22 17:05:37.876  4115  4115 D AdapterServiceConfig: Adding GattService
08-22 17:05:37.876  4115  4115 D AdapterServiceConfig: Adding BluetoothMapService
,08-22 17:05:37.882   375  1317 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-22 17:05:37.883   375  1317 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-22 17:05:37.896  4115  4115 D BluetoothAdapterState: make() - Creating AdapterState
,08-22 17:05:37.896   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8210cd:true
,08-22 17:05:37.906  4115  4115 I bt_bluedroid: init
,08-22 17:05:37.906  4115  4129 I BluetoothAdapterState: Entering OffState
,08-22 17:05:37.911  4115  4131 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-22 17:05:37.911  4115  4131 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-22 17:05:37.911  4115  4131 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-22 17:05:37.911  4115  4131 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-22 17:05:37.911  4115  4115 I bt_bluedroid: get_profile_interface socket
08-22 17:05:37.913  4115  4115 I bt_bluedroid: get_profile_interface sdp,
,08-22 17:05:37.916  4115  4135 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-22 17:05:37.920  4115  4128 I bt_bluedroid: config_hci_snoop_log
08-22 17:05:37.925   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-22 17:05:37.926  4115  4135 D BluetoothAdapterProperties: Name is: Nexus 6
,08-22 17:05:37.932  4115  4129 D BluetoothAdapterState: Current state: OFF, message: 0
,08-22 17:05:37.932  4115  4129 D BluetoothAdapterProperties: Setting state to 14
08-22 17:05:37.933  4115  4129 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-22 17:05:37.934  4115  4129 D BluetoothBondStateMachine: make
,08-22 17:05:37.936  4115  4137 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-22 17:05:37.939  4115  4115 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-22 17:05:37.939  4115  4129 I BluetoothAdapterState: Entering PendingCommandState
,08-22 17:05:37.941  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
,08-22 17:05:37.941  4115  4115 D BtGatt.DebugUtils: handleDebugAction() action=null
08-22 17:05:37.942  4115  4115 D BtGatt.GattService: Received start request. Starting profile...
,08-22 17:05:37.942  4115  4115 D BtGatt.GattService: start()
,08-22 17:05:37.942  4115  4115 I bt_bluedroid: get_profile_interface gatt
08-22 17:05:37.943  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
,08-22 17:05:37.943  4115  4115 D BtGatt.AdvertiseManager: advertise manager created
,08-22 17:05:37.947  4115  4115 V BluetoothAdapterState: isTurningOff()=false
,08-22 17:05:37.947  4115  4115 V BluetoothAdapterState: isTurningOn()=false
08-22 17:05:37.947  4115  4115 V BluetoothAdapterState: isBleTurningOn()=true
,08-22 17:05:37.947  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
08-22 17:05:37.948  4115  4129 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-22 17:05:37.948  4115  4129 I bt_bluedroid: enable
08-22 17:05:37.948  4115  4131 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-22 17:05:37.949  4115  4131 I bt_hci  : start_up
,08-22 17:05:37.954  4115  4131 I bt_vendor: alloc value 0xb39b0189
,08-22 17:05:37.954  4115  4131 I bt_vendor: init
08-22 17:05:37.954  4115  4131 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-22 17:05:37.954  4115  4131 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-22 17:05:38.063  4115  4131 D bt_hci  : start_up starting async portion
08-22 17:05:38.063  4115  4140 I bt_hci  : event_finish_startup
,08-22 17:05:38.064  4115  4140 I bt_hci_h4: hal_open
08-22 17:05:38.064  4115  4140 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-22 17:05:38.073  4115  4140 I bt_userial_vendor: device fd = 51 open
,08-22 17:05:38.103  4115  4140 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-22 17:05:38.135  4115  4140 D bt_hwcfg: Chipset BCM4354A2
,08-22 17:05:38.135  4115  4140 D bt_hwcfg: Target name = [BCM4354A2]
08-22 17:05:38.136  4115  4140 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-22 17:05:38.783  4115  4140 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-22 17:05:38.784  4115  4140 D bt_hwcfg: Settlement delay -- 100 ms
,08-22 17:05:38.785  4115  4140 I bt_hwcfg: Setting fw settlement delay to 100 
,08-22 17:05:38.901  4115  4140 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-22 17:05:38.901  4115  4140 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-22 17:05:38.931  4115  4140 I bt_hwcfg: vendor lib fwcfg completed
,08-22 17:05:38.931  4115  4140 I bt_vendor: firmware callback
08-22 17:05:38.931  4115  4140 I bt_hci  : firmware_config_callback
,08-22 17:05:38.937  4115  4142 I bt_btu  : btu_task pending for preload complete event
,08-22 17:05:38.937  4115  4142 I bt_btu_task: Bluetooth chip preload is complete
,08-22 17:05:38.937  4115  4142 I bt_btu  : btu_task received preload complete event
,08-22 17:05:38.944  4115  4142 I         : BTE_InitTraceLevels -- TRC_HCI
,08-22 17:05:38.944  4115  4142 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-22 17:05:38.945  4115  4142 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-22 17:05:38.945  4115  4142 I         : BTE_InitTraceLevels -- TRC_AVDT
08-22 17:05:38.945  4115  4142 I         : BTE_InitTraceLevels -- TRC_AVRC
08-22 17:05:38.945  4115  4142 I         : BTE_InitTraceLevels -- TRC_A2D
08-22 17:05:38.945  4115  4142 I         : BTE_InitTraceLevels -- TRC_BNEP
08-22 17:05:38.946  4115  4142 I         : BTE_InitTraceLevels -- TRC_BTM
,08-22 17:05:38.946  4115  4142 I         : BTE_InitTraceLevels -- TRC_GAP
08-22 17:05:38.946  4115  4142 I         : BTE_InitTraceLevels -- TRC_PAN
08-22 17:05:38.946  4115  4142 I         : BTE_InitTraceLevels -- TRC_SDP
08-22 17:05:38.947  4115  4142 I         : BTE_InitTraceLevels -- TRC_GATT
,08-22 17:05:38.947  4115  4142 I         : BTE_InitTraceLevels -- TRC_SMP
08-22 17:05:38.947  4115  4142 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-22 17:05:38.947  4115  4142 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-22 17:05:39.076  4115  4142 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb392dd9d
08-22 17:05:39.076  4115  4142 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb392dd9d 
,08-22 17:05:39.087  4115  4135 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-22 17:05:39.089  4115  4135 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-22 17:05:39.090  4115  4135 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-22 17:05:39.093  4115  4135 D BluetoothAdapterProperties: Name is: Nexus 6
,08-22 17:05:39.098  4115  4135 D BluetoothAdapterProperties: Scan Mode:20
,08-22 17:05:39.098  4115  4135 D BluetoothAdapterProperties: Discoverable Timeout:120
08-22 17:05:39.099  4115  4135 D bt_hci  : do_postload posting postload work item
08-22 17:05:39.099  4115  4140 I bt_hci  : event_postload
08-22 17:05:39.099  4115  4140 I bt_vendor: sco_config_cb
08-22 17:05:39.099  4115  4140 I bt_hci  : sco_config_callback postload finished.
08-22 17:05:39.101  4115  4135 D bt_bte_conf: Device ID record 1 : primary
,08-22 17:05:39.101  4115  4135 D bt_bte_conf:   vendorId            = 000f
,08-22 17:05:39.102  4115  4135 D bt_bte_conf:   vendorIdSource      = 0001
,08-22 17:05:39.102  4115  4135 D bt_bte_conf:   product             = 1200
08-22 17:05:39.102  4115  4135 D bt_bte_conf:   version             = 1436
,08-22 17:05:39.102  4115  4135 D bt_bte_conf:   clientExecutableURL = 
08-22 17:05:39.102  4115  4135 D bt_bte_conf:   serviceDescription  = ,
,08-22 17:05:39.102  4115  4135 D bt_bte_conf:   documentationURL    = 
,08-22 17:05:39.103  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 17:05:39.103  4115  4135 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-22 17:05:39.103  4115  4131 D bt_stack_manager: event_start_up_stack finished
08-22 17:05:39.104  4115  4129 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-22 17:05:39.105  4115  4129 D BluetoothAdapterProperties: Setting state to 15
,08-22 17:05:39.105  4115  4129 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-22 17:05:39.106  4115  4140 I bt_vendor: low_power_mode_cb
,08-22 17:05:39.106  4115  4129 I BluetoothAdapterState: Entering BleOnState
08-22 17:05:39.112  4115  4129 D BluetoothAdapterState: Current state: BLE ON, message: 1,
08-22 17:05:39.113  4115  4129 D BluetoothAdapterProperties: Setting state to 11
08-22 17:05:39.113  4115  4129 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11,
,08-22 17:05:39.124  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 17:05:39.124  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
,08-22 17:05:39.126  4115  4115 D HeadsetService: Received start request. Starting profile...
08-22 17:05:39.131  4115  4115 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-22 17:05:39.131  4115  4115 D HeadsetStateMachine: make
,08-22 17:05:39.140  4115  4115 D HeadsetStateMachine: max_hf_connections = 1
,08-22 17:05:39.140  4115  4115 I bt_bluedroid: get_profile_interface handsfree
,08-22 17:05:39.140  4115  4135 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-22 17:05:39.141  4115  4129 I BluetoothAdapterState: Entering PendingCommandState
,08-22 17:05:39.143  4115  4135 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-22 17:05:39.146  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
,08-22 17:05:39.147  4115  4115 D A2dpService: Received start request. Starting profile...
,08-22 17:05:39.148  4115  4115 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-22 17:05:39.148  4115  4115 I bt_bluedroid: get_profile_interface avrcp
,08-22 17:05:39.155  4115  4115 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-22 17:05:39.155  4115  4115 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-22 17:05:39.156  4115  4115 D A2dpStateMachine: make
,08-22 17:05:39.157  4115  4115 I bt_bluedroid: get_profile_interface a2dp
,08-22 17:05:39.158  4115  4135 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-22 17:05:39.162  4115  4150 D A2dpStateMachine: Enter Disconnected: -2
,08-22 17:05:39.164  4115  4115 I BluetoothHidServiceJni: classInitNative: succeeds
,08-22 17:05:39.165  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 17:05:39.166  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
,08-22 17:05:39.167  4115  4115 D HidService: Received start request. Starting profile...
,08-22 17:05:39.167  4115  4115 I bt_bluedroid: get_profile_interface hidhost
,08-22 17:05:39.167  4115  4135 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb390f3e5
,08-22 17:05:39.168  4115  4135 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-22 17:05:39.167  4115  4115 D HidService: setHidService(): set to: null
08-22 17:05:39.169  4115  4115 I BluetoothHealthServiceJni: classInitNative: succeeds
08-22 17:05:39.170  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
08-22 17:05:39.171  4115  4115 D HealthService: Received start request. Starting profile...
,08-22 17:05:39.173  4115  4115 I bt_bluedroid: get_profile_interface health
,08-22 17:05:39.175  4115  4115 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-22 17:05:39.176  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
,08-22 17:05:39.177  4115  4115 D PanService: Received start request. Starting profile...
,08-22 17:05:39.177  4115  4115 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-22 17:05:39.177  4115  4115 I bt_bluedroid: get_profile_interface pan
,08-22 17:05:39.179  4115  4135 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-22 17:05:39.183  4115  4115 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
,08-22 17:05:39.185  4115  4115 D BluetoothMapService: Received start request. Starting profile...
,08-22 17:05:39.185  4115  4115 D BluetoothMapService: start()
,08-22 17:05:39.189  4115  4115 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-22 17:05:39.190  4115  4115 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-22 17:05:39.190  4115  4115 D BluetoothMapAppObserver: createReceiver()
,08-22 17:05:39.193  4115  4115 D BluetoothMapAppObserver: initObservers()
,08-22 17:05:39.193  4115  4115 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-22 17:05:39.200  4115  4115 V BluetoothAdapterState: isTurningOff()=false
08-22 17:05:39.201  4115  4115 V BluetoothAdapterState: isTurningOn()=true
08-22 17:05:39.201  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
08-22 17:05:39.201  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 17:05:39.203  4115  4115 V BluetoothAdapterState: isTurningOff()=false
,08-22 17:05:39.203  4115  4115 V BluetoothAdapterState: isTurningOn()=true
08-22 17:05:39.204  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 17:05:39.204  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
08-22 17:05:39.204  4115  4115 V BluetoothAdapterState: isTurningOff()=false
08-22 17:05:39.204  4115  4115 V BluetoothAdapterState: isTurningOn()=true
08-22 17:05:39.204  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
08-22 17:05:39.205  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
08-22 17:05:39.205  4115  4115 V BluetoothAdapterState: isTurningOff()=false
08-22 17:05:39.205  4115  4115 V BluetoothAdapterState: isTurningOn()=true
,08-22 17:05:39.205  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 17:05:39.205  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 17:05:39.205  4115  4115 V BluetoothAdapterState: isTurningOff()=false
,08-22 17:05:39.205  4115  4115 V BluetoothAdapterState: isTurningOn()=true
08-22 17:05:39.205  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
08-22 17:05:39.205  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 17:05:39.206  4115  4115 V BluetoothAdapterState: isTurningOff()=false
,08-22 17:05:39.206  4115  4115 V BluetoothAdapterState: isTurningOn()=true
08-22 17:05:39.206  4115  4115 V BluetoothAdapterState: isBleTurningOn()=false
08-22 17:05:39.206  4115  4115 V BluetoothAdapterState: isBleTurningOff()=false
08-22 17:05:39.206  4115  4148 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-22 17:05:39.207  4115  4129 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-22 17:05:39.207  4115  4129 D BluetoothAdapterProperties: ScanMode =  20
08-22 17:05:39.207  4115  4129 D BluetoothAdapterProperties: State =  11
08-22 17:05:39.209  4115  4135 D BluetoothAdapterProperties: Scan Mode:21
,08-22 17:05:39.209  4115  4129 D BluetoothAdapterProperties: Setting state to 12
08-22 17:05:39.210  4115  4129 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-22 17:05:39.210  4115  4135 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-22 17:05:39.211  4115  4129 I BluetoothAdapterState: Entering OnState
,08-22 17:05:39.211  1367  1380 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-22 17:05:39.215  3576  3586 D BluetoothMap: onBluetoothStateChange: up=true
08-22 17:05:39.216  1367  1367 D BluetoothA2dp: Proxy object connected
08-22 17:05:39.217  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 17:05:39.217  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:39.217  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:39.217  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 17:05:39.217  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 17:05:39.217  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:39.217  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:39.217  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 17:05:39.219  3576  4004 D BluetoothPbap: onBluetoothStateChange: up=true
08-22 17:05:39.221  3463  3463 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 17:05:39.221  4115  4115 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-22 17:05:39.222  3576  4004 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 17:05:39.223  4115  4115 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-22 17:05:39.223  1367  1379 D BluetoothMap: onBluetoothStateChange: up=true
08-22 17:05:39.224  4115  4115 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 17:05:39.226   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 17:05:39.227  1367  1367 D BluetoothMap: Proxy object connected
08-22 17:05:39.227  1367  1367 D MapProfile: Bluetooth service connected
08-22 17:05:39.227  1367  1367 D BluetoothMap: getConnectedDevices()
08-22 17:05:39.227  4115  4115 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 17:05:39.228  1367  2019 D BluetoothPan: onBluetoothStateChange on: true
,08-22 17:05:39.228   873   873 D BluetoothA2dp: Proxy object connected
08-22 17:05:39.229  4115  4115 D ObexServerSockets: Succeed to create listening sockets 
,08-22 17:05:39.229  4115  4115 D ObexServerSockets0: startAccept()
08-22 17:05:39.229  4115  4115 D ObexServerSockets0: prepareForNewConnect()
08-22 17:05:39.230  3576  3576 D BluetoothMap: Proxy object connected
08-22 17:05:39.230  3576  3576 D MapProfile: Bluetooth service connected
08-22 17:05:39.230  3576  3576 D BluetoothMap: getConnectedDevices()
08-22 17:05:39.230  3576  3587 D BluetoothPan: onBluetoothStateChange on: true
08-22 17:05:39.232  4115  4115 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-22 17:05:39.232  4115  4115 D BluetoothSdpJni: SDP Create record success - handle: 0
08-22 17:05:39.234   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 17:05:39.234  1367  1367 D BluetoothPan: BluetoothPAN Proxy object connected
08-22 17:05:39.235  3576  3587 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 17:05:39.235  1367  1367 D PanProfile: Bluetooth service connected
08-22 17:05:39.235  4115  4157 D ObexServerSockets0: Accepting socket connection...
08-22 17:05:39.236  3576  3576 D BluetoothPan: BluetoothPAN Proxy object connected
,08-22 17:05:39.236  4115  4156 D ObexServerSockets0: Accepting socket connection...
08-22 17:05:39.236  3576  3576 D PanProfile: Bluetooth service connected
08-22 17:05:39.238   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 17:05:39.239  3576  4004 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-22 17:05:39.239  3576  3576 D BluetoothA2dp: Proxy object connected
,08-22 17:05:39.244  3576  3576 D BluetoothInputDevice: Proxy object connected
08-22 17:05:39.244  3576  3576 D HidProfile: Bluetooth service connected
,08-22 17:05:39.245  1367  1380 D BluetoothPbap: onBluetoothStateChange: up=true
,08-22 17:05:39.248  1367  2019 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 17:05:39.249  1367  1379 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-22 17:05:39.252  1367  1367 D BluetoothInputDevice: Proxy object connected
,08-22 17:05:39.252  1367  1367 D HidProfile: Bluetooth service connected
08-22 17:05:39.253  1914  1943 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 17:05:39.253   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-22 17:05:39.256   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-22 17:05:39.258  4115  4115 D BluetoothMapService: onReceive
,08-22 17:05:39.259  4115  4115 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-22 17:05:39.259  4115  4115 D BluetoothMapService: STATE_ON
08-22 17:05:39.260  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 17:05:39.266  3576  3576 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 17:05:39.276  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-22 17:05:39.278  3576  3576 D DockEventReceiver: finishStartingService: stopping service
,08-22 17:05:39.290  3576  3576 D BluetoothPbap: Proxy object connected
08-22 17:05:39.290  3576  3576 D PbapServerProfile: Bluetooth service connected
,08-22 17:05:39.290  1367  1367 D BluetoothPbap: Proxy object connected
08-22 17:05:39.290  1367  1367 D PbapServerProfile: Bluetooth service connected
,08-22 17:05:39.292  4115  4115 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-22 17:05:39.292  4115  4115 D ObexServerSockets0: prepareForNewConnect()
,08-22 17:05:39.308  4115  4162 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 17:05:39.334   873   873 D BluetoothHeadset: Proxy object connected
,08-22 17:05:39.338  3576  4004 D BluetoothHeadset: Proxy object connected
,08-22 17:05:39.338   873   873 D BluetoothHeadset: Proxy object connected
,08-22 17:05:39.339  1914  2047 D BluetoothHeadset: Proxy object connected
,08-22 17:05:39.339  3576  3576 D HeadsetProfile: Bluetooth service connected
08-22 17:05:39.340   873   890 D BluetoothHeadset: Proxy object connected
,08-22 17:05:39.340  1367  2019 D BluetoothHeadset: Proxy object connected
,08-22 17:05:39.340  1367  1367 D HeadsetProfile: Bluetooth service connected
,08-22 17:05:39.340   873   873 D BluetoothHeadset: Proxy object connected
,08-22 17:05:39.345  4115  4168 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 17:05:39.348  1367  1380 D BluetoothHeadset: Proxy object connected
,08-22 17:05:39.348  4115  4168 I BtOppRfcommListener: Accept thread started.
08-22 17:05:39.349  1367  1367 D HeadsetProfile: Bluetooth service connected
,08-22 17:05:39.353  1914  1935 D BluetoothHeadset: Proxy object connected
,08-22 17:05:39.354   873   890 D BluetoothHeadset: Proxy object connected
,08-22 17:05:39.767  3463  3512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 17:05:39.767  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:39.767  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:39.767  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 17:05:39.767  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 17:05:39.767  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:39.767  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:39.767  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 17:05:39.774  3463  3512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 17:05:39.778  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 17:05:39.778  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d4cc214 added. We now have 8 listener(s)
,08-22 17:05:39.778  3463  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 17:05:39.784   873   884 D WifiService: setWifiEnabled: false pid=3463, uid=10000
,08-22 17:05:39.784   873   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-22 17:05:39.797  3463  3512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 17:05:39.798   873  2237 D WifiService: setWifiEnabled: true pid=3463, uid=10000
,08-22 17:05:39.799   873  2237 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-22 17:05:39.812   873  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-22 17:05:39.828  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 17:05:39.828  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:39.828  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:39.828  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 17:05:39.828  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 17:05:39.828  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:39.828  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:39.828  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 17:05:39.834  3463  3463 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 17:05:39.842   873  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-22 17:05:39.843   873  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-22 17:05:39.844   873  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-22 17:05:39.845   873  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-22 17:05:39.845   873  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-22 17:05:39.845   873  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-22 17:05:39.845   873  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-22 17:05:39.868   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-22 17:05:39.868   873  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-22 17:05:39.869   371   871 D CommandListener: Setting iface cfg
08-22 17:05:39.874   873  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-22 17:05:39.874   873  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-22 17:05:39.927   873  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-22 17:05:39.927   873  1308 E native  : do suspend true
08-22 17:05:39.927   873  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-22 17:05:39.984   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 17:05:40.823  3463  3512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,08-22 17:05:40.823  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:40.823  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:40.823  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 17:05:40.823  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 17:05:40.823  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:40.823  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:40.823  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 17:05:40.830  3463  3512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 17:05:40.844  3463  3512 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-22 17:05:40.846  3463  3512 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-22 17:05:40.852  3463  3512 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@70944a7 Bundle[{}]
,08-22 17:05:40.852  3463  3512 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-22 17:05:40.853  3463  3512 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-22 17:05:40.853  3463  3512 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-22 17:05:40.854  3463  3512 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-22 17:05:40.854  3463  3512 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-22 17:05:40.855  3463  3512 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-22 17:05:40.859  3463  3512 I System.out: Running OutgoingSocketThread,
,08-22 17:05:40.861  3463  4174 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 380)
,08-22 17:05:40.864  3463  4174 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44231
,08-22 17:05:40.864  3463  4174 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-22 17:05:41.355   873  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-22 17:05:41.443   873  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.06 rxSuccessRate=0.04 delta 1000 -> 1000
,08-22 17:05:41.445   873  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-22 17:05:41.446   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 17:05:41.463   873  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-22 17:05:41.505   873  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-22 17:05:41.507  1462  1462 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-22 17:05:41.862  3463  3512 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 381)
,08-22 17:05:41.863  3463  3512 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 381)
,08-22 17:05:41.872  3463  3512 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 386)
,08-22 17:05:41.874  3463  3512 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-22 17:05:41.875  3463  3512 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 387)
08-22 17:05:41.881  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 17:05:41.881  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c48eabd added. We now have 2 listener(s)
08-22 17:05:41.883  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-22 17:05:41.883  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 17:05:41.883  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 17:05:41.884  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 17:05:41.884  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbfb8b2 added. We now have 9 listener(s)
08-22 17:05:41.884  3463  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 17:05:41.884  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 17:05:41.888  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 17:05:41.894  3463  3512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 17:05:41.894  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:41.894  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:41.894  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 17:05:41.894  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 17:05:41.894  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:41.894  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:41.894  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 17:05:41.896  3463  3512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 17:05:41.896  3463  3512 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 17:05:41.896  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 17:05:41.897  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13deb80 added. We now have 3 listener(s)
08-22 17:05:41.898  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 17:05:41.898  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 17:05:41.899  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 17:05:41.899  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 17:05:41.899  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1e75b9 added. We now have 10 listener(s)
08-22 17:05:41.899  3463  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 17:05:41.899  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 17:05:41.899  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 17:05:41.899  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 17:05:41.900  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:41.900  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-22 17:05:41.900  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 17:05:41.900  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 17:05:41.900  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 17:05:41.900  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c48eabd removed from the list
,08-22 17:05:41.900  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:41.900  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbfb8b2 removed from the list
08-22 17:05:41.901  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 17:05:41.902  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
08-22 17:05:41.902  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 17:05:41.902  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:41.902  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:41.904  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:41.904  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:41.904  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:41.904  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dbfb8b2 not in the list
08-22 17:05:41.904  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:41.904  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 17:05:41.906  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:41.906  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:41.906  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:41.906  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1e75b9 removed from the list
08-22 17:05:41.906  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:41.906  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 17:05:41.906  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:41.906  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 17:05:41.906  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13deb80 removed from the list
08-22 17:05:41.908  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 17:05:41.908  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cecadfe added. We now have 2 listener(s)
08-22 17:05:41.910  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 17:05:41.910  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 17:05:41.910  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 17:05:41.910  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 17:05:41.910  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3da95f added. We now have 9 listener(s)
08-22 17:05:41.910  3463  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 17:05:41.911  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 17:05:41.914  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-22 17:05:41.919  3463  3512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 17:05:41.919  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:41.919  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:41.919  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 17:05:41.919  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 17:05:41.919  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:41.919  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:41.919  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 17:05:41.922  3463  3512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 17:05:41.922  3463  3512 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 17:05:41.922  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-22 17:05:41.922  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f27b475 added. We now have 3 listener(s)
08-22 17:05:41.923  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 17:05:41.924  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-22 17:05:41.924  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 17:05:41.924  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 17:05:41.924  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 17:05:41.924  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@461ac0a added. We now have 10 listener(s)
08-22 17:05:41.925  3463  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 17:05:41.925  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 17:05:41.925  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 17:05:41.925  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 17:05:41.925  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 17:05:41.925  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 17:05:41.925  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 17:05:41.932  3463  3512 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-22 17:05:41.932  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 17:05:41.938  1462  1462 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-22 17:05:41.939  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-22 17:05:41.941  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-22 17:05:41.942  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 17:05:41.954  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 17:05:41.954  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-22 17:05:41.955  3463  3512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 17:05:41.956  3463  3512 D BluetoothAdapter: STATE_ON,
,08-22 17:05:41.963  4115  4158 D BtGatt.GattService: registerClient() - UUID=ed563277-86a9-43f1-97ec-a16908b43621,
,08-22 17:05:41.964  4115  4135 D BtGatt.GattService: onClientRegistered() - UUID=ed563277-86a9-43f1-97ec-a16908b43621, clientIf=5
,08-22 17:05:41.966  3463  3508 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-22 17:05:41.967  4115  4136 D BtGatt.GattService: start scan with filters
,08-22 17:05:41.971  4115  4139 D BtGatt.ScanManager: handling starting scan
,08-22 17:05:41.971  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-22 17:05:41.972  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-22 17:05:41.972  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-22 17:05:41.973  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-22 17:05:41.975  4115  4139 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@85306cb
,08-22 17:05:41.975  1462  1462 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-22 17:05:41.975  1462  1462 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-22 17:05:41.978  3463  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 17:05:41.978  3463  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 17:05:41.979  4115  4135 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-22 17:05:41.979  4115  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 17:05:41.978  3463  3463 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 17:05:41.980  4115  4139 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-22 17:05:41.981  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-22 17:05:41.983   873  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 17:05:41.985  3463  3512 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-22 17:05:41.986  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-22 17:05:41.986  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-22 17:05:41.986  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 17:05:41.986  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 17:05:41.986  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-22 17:05:41.986  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 17:05:41.986  3463  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-22 17:05:41.987  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-22 17:05:41.987  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 17:05:41.987  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-22 17:05:41.988  4115  4135 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-22 17:05:41.988  4115  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 17:05:41.988  4115  4139 D BtGatt.ScanManager: Starting BLE batch scan
,08-22 17:05:41.988  4115  4139 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-22 17:05:41.989  3463  3512 D BluetoothAdapter: STATE_ON
,08-22 17:05:41.989  4115  4158 D BtGatt.GattService: stopScan() - queue size =1
08-22 17:05:41.990  4115  4136 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-22 17:05:41.990  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 17:05:41.990  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 17:05:41.991  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 17:05:41.991  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 17:05:41.991  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 17:05:41.992  3463  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 17:05:41.992  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-22 17:05:41.992  3463  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 17:05:41.993  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 17:05:41.993  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 17:05:41.995  3463  3463 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 17:05:41.995  3463  3463 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 17:05:41.995  3463  3463 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 17:05:41.996   873  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-22 17:05:41.996   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-22 17:05:41.996   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-22 17:05:41.997  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 17:05:41.997  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-22 17:05:41.997  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 17:05:41.998  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:41.998  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 17:05:41.998  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 17:05:41.998  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 17:05:41.998  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cecadfe removed from the list
08-22 17:05:41.998  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:41.998  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3da95f removed from the list
08-22 17:05:41.998  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 17:05:41.998  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:41.999  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:41.999  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:42.000  4115  4135 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-22 17:05:42.001  4115  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 17:05:42.001  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:42.001  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:42.001  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:42.001  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3da95f not in the list
08-22 17:05:42.001  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 17:05:42.001  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:42.003  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:42.003  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 17:05:42.003  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 17:05:42.004  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@461ac0a removed from the list
08-22 17:05:42.004  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:42.004  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:42.004  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:42.004  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-22 17:05:42.004  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f27b475 removed from the list
08-22 17:05:42.005  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 17:05:42.005  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9767ed6 added. We now have 2 listener(s)
,08-22 17:05:42.007  4115  4135 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-22 17:05:42.007  4115  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 17:05:42.010  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-22 17:05:42.010  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 17:05:42.010  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 17:05:42.011  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 17:05:42.011  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d6557 added. We now have 9 listener(s)
08-22 17:05:42.011  3463  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 17:05:42.011  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 17:05:42.015   873  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-22 17:05:42.015  4115  4135 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-22 17:05:42.015  4115  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 17:05:42.015  4115  4139 D BtGatt.ScanManager: stopping BLe Batch
08-22 17:05:42.016  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 17:05:42.021  3463  3512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 17:05:42.021  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:42.021  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:42.021  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 17:05:42.021  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 17:05:42.021  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:42.021  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:42.021  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 17:05:42.022  4115  4135 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-22 17:05:42.022  4115  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 17:05:42.022  4115  4139 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-22 17:05:42.022  3463  3512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 17:05:42.022  3463  3512 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 17:05:42.022  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 17:05:42.023  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6efd2d added. We now have 3 listener(s)
08-22 17:05:42.024  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 17:05:42.025  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 17:05:42.026  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 17:05:42.026  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 17:05:42.026  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 17:05:42.026   371   871 D CommandListener: Setting iface cfg
,08-22 17:05:42.026  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 17:05:42.026  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d33b262 added. We now have 10 listener(s)
08-22 17:05:42.026  3463  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 17:05:42.026  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 17:05:42.027   873  1308 D WifiStateMachine: Start Dhcp Watchdog 2
,08-22 17:05:42.027  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 17:05:42.027  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 17:05:42.027  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 17:05:42.027  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 17:05:42.027  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 17:05:42.028  4115  4135 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-22 17:05:42.028  4115  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 17:05:42.030  3463  3512 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-22 17:05:42.030  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 17:05:42.032  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 17:05:42.033  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-22 17:05:42.033  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 17:05:42.035  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 17:05:42.035  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 17:05:42.035  3463  3512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-22 17:05:42.036  3463  3512 D BluetoothAdapter: STATE_ON
,08-22 17:05:42.036   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
08-22 17:05:42.037  4115  4136 D BtGatt.GattService: registerClient() - UUID=7bf0879f-4c42-4634-806e-97fcd1652ab9
08-22 17:05:42.038  4115  4135 D BtGatt.GattService: onClientRegistered() - UUID=7bf0879f-4c42-4634-806e-97fcd1652ab9, clientIf=5
08-22 17:05:42.038  3463  3508 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-22 17:05:42.038  4115  4158 D BtGatt.GattService: start scan with filters
,08-22 17:05:42.040  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 17:05:42.040  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-22 17:05:42.040  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 17:05:42.040  4115  4139 D BtGatt.ScanManager: handling starting scan
08-22 17:05:42.040  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 17:05:42.042  3463  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 17:05:42.043  3463  3463 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 17:05:42.043  3463  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 17:05:42.044  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 17:05:42.046  4115  4135 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-22 17:05:42.046  4115  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 17:05:42.046  4115  4139 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-22 17:05:42.046  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
08-22 17:05:42.046  3463  3512 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-22 17:05:42.047  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 17:05:42.047  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 17:05:42.047  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 17:05:42.047  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:42.047  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 17:05:42.047  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 17:05:42.047  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 17:05:42.047  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9767ed6 removed from the list
,08-22 17:05:42.047  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:42.047  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d6557 removed from the list
08-22 17:05:42.048  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
08-22 17:05:42.048  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 17:05:42.048  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-22 17:05:42.048  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-22 17:05:42.048  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:42.048  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 17:05:42.049  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:42.049  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:42.049  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 17:05:42.049  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d6557 not in the list
08-22 17:05:42.049  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 17:05:42.049  3463  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
08-22 17:05:42.049  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 17:05:42.049  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
08-22 17:05:42.050  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-22 17:05:42.050  3463  3512 D BluetoothAdapter: STATE_ON
,08-22 17:05:42.051  4115  4135 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-22 17:05:42.051  4115  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 17:05:42.051  4115  4158 D BtGatt.GattService: stopScan() - queue size =1
08-22 17:05:42.051  4115  4139 D BtGatt.ScanManager: Starting BLE batch scan
08-22 17:05:42.051  4115  4139 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-22 17:05:42.051  4115  4155 D BtGatt.GattService: unregisterClient() - clientIf=5
08-22 17:05:42.052  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 17:05:42.052  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 17:05:42.052  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-22 17:05:42.052  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 17:05:42.052  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-22 17:05:42.053  3463  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 17:05:42.053  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 17:05:42.053  3463  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 17:05:42.053  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 17:05:42.054  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:42.054  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:42.054  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:42.055  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:42.055  3463  3463 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 17:05:42.055  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d33b262 removed from the list
,08-22 17:05:42.055  3463  3463 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 17:05:42.055  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:42.055  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:42.055  3463  3463 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 17:05:42.055  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:42.055  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 17:05:42.055  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6efd2d removed from the list
08-22 17:05:42.056  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 17:05:42.056  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69e92ae added. We now have 2 listener(s)
08-22 17:05:42.058  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 17:05:42.058  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 17:05:42.058  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 17:05:42.058  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 17:05:42.058  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c9a84f added. We now have 9 listener(s)
08-22 17:05:42.058  3463  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 17:05:42.059  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 17:05:42.060  4115  4135 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-22 17:05:42.060  4115  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 17:05:42.061  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 17:05:42.061   873  4178 D DhcpClient: Receive thread started
,08-22 17:05:42.064  4115  4135 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1,
08-22 17:05:42.064  4115  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 17:05:42.064  3463  3512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 17:05:42.064  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:42.064  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:42.064  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 17:05:42.064  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,08-22 17:05:42.064  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:42.064  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:42.064  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 17:05:42.066  3463  3512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 17:05:42.067  3463  3512 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-22 17:05:42.067  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 17:05:42.067  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cfa4e5 added. We now have 3 listener(s)
,08-22 17:05:42.068  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 17:05:42.069  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 17:05:42.069  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 17:05:42.069  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 17:05:42.069  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 17:05:42.069  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 17:05:42.069  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c52bba added. We now have 10 listener(s)
08-22 17:05:42.069  3463  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 17:05:42.070  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 17:05:42.070  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 17:05:42.070  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 17:05:42.070  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 17:05:42.070  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 17:05:42.070  4115  4135 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-22 17:05:42.071  4115  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 17:05:42.071  4115  4139 D BtGatt.ScanManager: stopping BLe Batch
08-22 17:05:42.072  3463  3512 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-22 17:05:42.072  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 17:05:42.075  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 17:05:42.075  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-22 17:05:42.076  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 17:05:42.076  4115  4135 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-22 17:05:42.077  4115  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 17:05:42.077  4115  4139 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-22 17:05:42.079  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 17:05:42.079  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 17:05:42.079  3463  3512 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
08-22 17:05:42.080  3463  3512 D BluetoothAdapter: STATE_ON
,08-22 17:05:42.082  4115  4135 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-22 17:05:42.082  4115  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 17:05:42.082  4115  4128 D BtGatt.GattService: registerClient() - UUID=82c509ab-c61a-429a-a52f-a870fbf59e9f
,08-22 17:05:42.083  4115  4135 D BtGatt.GattService: onClientRegistered() - UUID=82c509ab-c61a-429a-a52f-a870fbf59e9f, clientIf=5
,08-22 17:05:42.083  3463  3508 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-22 17:05:42.083  4115  4158 D BtGatt.GattService: start scan with filters
,08-22 17:05:42.085  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-22 17:05:42.085  4115  4139 D BtGatt.ScanManager: handling starting scan
08-22 17:05:42.085  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-22 17:05:42.085  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 17:05:42.085  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 17:05:42.087  3463  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 17:05:42.087  3463  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-22 17:05:42.087  3463  3463 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 17:05:42.088  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 17:05:42.091  4115  4135 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-22 17:05:42.091  4115  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 17:05:42.091  4115  4139 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0,
,08-22 17:05:42.092  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 17:05:42.092  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-22 17:05:42.092  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 17:05:42.092  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:42.092  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 17:05:42.092  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-22 17:05:42.092  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 17:05:42.092  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69e92ae removed from the list
,08-22 17:05:42.092  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 17:05:42.092  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c9a84f removed from the list
08-22 17:05:42.092  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 17:05:42.092  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 17:05:42.093  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-22 17:05:42.093  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-22 17:05:42.093  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 17:05:42.093  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 17:05:42.093  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:42.093  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-22 17:05:42.093  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:42.093  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c9a84f not in the list
,08-22 17:05:42.093  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-22 17:05:42.094  3463  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-22 17:05:42.094  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-22 17:05:42.094  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-22 17:05:42.094  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-22 17:05:42.094  3463  3512 D BluetoothAdapter: STATE_ON
08-22 17:05:42.095  4115  4128 D BtGatt.GattService: stopScan() - queue size =1
08-22 17:05:42.095  4115  4158 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-22 17:05:42.095  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-22 17:05:42.095  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 17:05:42.095  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 17:05:42.095  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 17:05:42.096  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 17:05:42.096  4115  4135 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-22 17:05:42.096  4115  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 17:05:42.096  4115  4139 D BtGatt.ScanManager: Starting BLE batch scan
08-22 17:05:42.096  4115  4139 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-22 17:05:42.096  3463  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 17:05:42.097  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 17:05:42.097  3463  3512 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-22 17:05:42.097  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 17:05:42.097  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:42.098  3463  3463 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 17:05:42.098  3463  3463 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-22 17:05:42.098  3463  3463 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 17:05:42.098  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 17:05:42.098  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:42.098  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 17:05:42.098  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c52bba removed from the list
,08-22 17:05:42.098  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:42.098  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 17:05:42.098  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 17:05:42.098  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-22 17:05:42.098  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7cfa4e5 removed from the list
08-22 17:05:42.099  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 17:05:42.099  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8a4986 added. We now have 2 listener(s)
08-22 17:05:42.100  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-22 17:05:42.100  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 17:05:42.100  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 17:05:42.100  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 17:05:42.100  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fec5247 added. We now have 9 listener(s)
08-22 17:05:42.101  3463  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-22 17:05:42.101  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 17:05:42.103  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 17:05:42.105  3463  3512 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 17:05:42.105  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:42.105  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:42.105  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 17:05:42.105  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 17:05:42.105  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 17:05:42.105  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 17:05:42.105  3463  3512 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 17:05:42.106  4115  4135 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-22 17:05:42.106  4115  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 17:05:42.107  3463  3512 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 17:05:42.107  3463  3512 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 17:05:42.108  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 17:05:42.108  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 17:05:42.109  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 17:05:42.109  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4368b9d added. We now have 3 listener(s)
,08-22 17:05:42.110  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 17:05:42.110  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 17:05:42.110  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 17:05:42.110  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 17:05:42.110  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2317812 added. We now have 10 listener(s)
08-22 17:05:42.110  3463  3512 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 17:05:42.110  3463  3512 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 17:05:42.110  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 17:05:42.110  3463  3512 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 17:05:42.110  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:42.111  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 17:05:42.111  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 17:05:42.111  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 17:05:42.111  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b8a4986 removed from the list
08-22 17:05:42.111  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:42.111  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fec5247 removed from the list
08-22 17:05:42.111  3463  3512 D io.jxcore.node.ConnectivityMonitor: stop
08-22 17:05:42.111  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:42.111  4115  4135 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-22 17:05:42.111  4115  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 17:05:42.111  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:42.111  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:42.112  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:42.112  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 17:05:42.112  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:42.112  3463  3512 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fec5247 not in the list
08-22 17:05:42.113  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:42.113  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:42.113  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 17:05:42.113  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 17:05:42.113  3463  3512 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 17:05:42.114  3463  3512 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2317812 removed from the list
08-22 17:05:42.114  3463  3512 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 17:05:42.114  3463  3512 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 17:05:42.114  3463  3512 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 17:05:42.114  3463  3512 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-22 17:05:42.114  3463  3512 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4368b9d removed from the list
08-22 17:05:42.115  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-22 17:05:42.115  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-22 17:05:42.115  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-22 17:05:42.115  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 17:05:42.115  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-22 17:05:42.115  3463  3512 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-22 17:05:42.117  4115  4135 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-22 17:05:42.117  4115  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 17:05:42.117  4115  4139 D BtGatt.ScanManager: stopping BLe Batch
08-22 17:05:42.121  3463  4179 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 394, name: My test thread name)
08-22 17:05:42.121  3463  4179 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 394, thread name: My test thread name)
08-22 17:05:42.121  3463  4179 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 394, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-22 17:05:42.123  4115  4135 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-22 17:05:42.123  4115  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 17:05:42.123  4115  4139 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-22 17:05:42.124  3463  4180 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 396, name: My test thread name)
08-22 17:05:42.124  3463  4180 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 396, thread name: My test thread name)
08-22 17:05:42.124  3463  4180 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 396, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-22 17:05:42.127  3463  3512 E com.test.thalitest.ThaliTestRunner: DiscoveryManager1 isRunning should return true
08-22 17:05:42.127  3463  3512 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
08-22 17:05:42.127  3463  3512 E com.test.thalitest.ThaliTestRunner:      but: was <false>
08-22 17:05:42.127  3463  3512 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-22 17:05:42.127  3463  3512 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 79
08-22 17:05:42.127  3463  3512 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  1
,08-22 17:05:42.127  3463  3512 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-22 17:05:42.127  4115  4135 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-22 17:05:42.127  4115  4135 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 17:05:42.127  3463  3512 D com.test.thalitest.ThaliTestRunner: Total duration: 24578 ms
08-22 17:05:42.129  3463  3512 I jxcore-log: Total number of executed tests:  80
08-22 17:05:42.129  3463  3512 I jxcore-log: 
08-22 17:05:42.129  3463  3512 I jxcore-log: Number of passed tests:  79
08-22 17:05:42.129  3463  3512 I jxcore-log: 
,08-22 17:05:42.130  3463  3512 I jxcore-log: Number of failed tests:  1
08-22 17:05:42.130  3463  3512 I jxcore-log: 
08-22 17:05:42.130  3463  3512 I jxcore-log: Number of ignored tests:  0
08-22 17:05:42.130  3463  3512 I jxcore-log: 
08-22 17:05:42.130  3463  3512 I jxcore-log: Total duration:  24578
08-22 17:05:42.130  3463  3512 I jxcore-log: 
,08-22 17:05:42.131  3463  3512 I jxcore-log: Failed to execute UT.
08-22 17:05:42.131  3463  3512 I jxcore-log: 
08-22 17:05:42.131  3463  3512 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-22 17:05:42.131  3463  3512 I jxcore-log: 
,08-22 17:05:42.134  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 17:05:42.134  3463  3512 I jxcore-log: 
08-22 17:05:42.138  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 17:05:42.138  3463  3512 I jxcore-log: 
08-22 17:05:42.139  3463  3463 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-22 17:05:42.140  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 17:05:42.140  3463  3512 I jxcore-log: 
08-22 17:05:42.141  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 17:05:42.141  3463  3512 I jxcore-log: 
08-22 17:05:42.142  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-22 17:05:42.142  3463  3512 I jxcore-log: 
08-22 17:05:42.143  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-22 17:05:42.143  3463  3512 I jxcore-log: 
08-22 17:05:42.145   873  1308 E native  : do suspend false
08-22 17:05:42.145  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 17:05:42.145  3463  3512 I jxcore-log: 
08-22 17:05:42.147  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 17:05:42.147  3463  3512 I jxcore-log: 
,08-22 17:05:42.148  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 17:05:42.148  3463  3512 I jxcore-log: 
,08-22 17:05:42.149  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 17:05:42.149  3463  3512 I jxcore-log: 
08-22 17:05:42.149  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 17:05:42.149  3463  3512 I jxcore-log: 
08-22 17:05:42.150  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 17:05:42.150  3463  3512 I jxcore-log: 
08-22 17:05:42.151  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 17:05:42.151  3463  3512 I jxcore-log: 
08-22 17:05:42.151  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 17:05:42.151  3463  3512 I jxcore-log: 
,08-22 17:05:42.152  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 17:05:42.152  3463  3512 I jxcore-log: 
08-22 17:05:42.153  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 17:05:42.153  3463  3512 I jxcore-log: 
08-22 17:05:42.153  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 17:05:42.153  3463  3512 I jxcore-log: 
,08-22 17:05:42.154  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 17:05:42.154  3463  3512 I jxcore-log: 
,08-22 17:05:42.155  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 17:05:42.155  3463  3512 I jxcore-log: 
,08-22 17:05:42.155  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 17:05:42.155  3463  3512 I jxcore-log: 
,08-22 17:05:42.156  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 17:05:42.156  3463  3512 I jxcore-log: 
08-22 17:05:42.156   873  3642 D DhcpClient: Broadcasting DHCPDISCOVER
,08-22 17:05:42.156  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 17:05:42.156  3463  3512 I jxcore-log: 
,08-22 17:05:42.157  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 17:05:42.157  3463  3512 I jxcore-log: 
08-22 17:05:42.158  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 17:05:42.158  3463  3512 I jxcore-log: 
,08-22 17:05:42.158  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 17:05:42.158  3463  3512 I jxcore-log: 
,08-22 17:05:42.159  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 17:05:42.159  3463  3512 I jxcore-log: 
,08-22 17:05:42.160  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 17:05:42.160  3463  3512 I jxcore-log: 
,08-22 17:05:42.160  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 17:05:42.160  3463  3512 I jxcore-log: 
08-22 17:05:42.161  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 17:05:42.161  3463  3512 I jxcore-log: 
,08-22 17:05:42.161  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 17:05:42.161  3463  3512 I jxcore-log: 
,08-22 17:05:42.162  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 17:05:42.162  3463  3512 I jxcore-log: 
,08-22 17:05:42.163  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 17:05:42.163  3463  3512 I jxcore-log: 
,08-22 17:05:42.169   873  4178 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172781, domain null
,08-22 17:05:42.169   873  3642 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172781 seconds
08-22 17:05:42.171   873  3642 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-22 17:05:42.200   873  4178 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-22 17:05:42.201   873  3642 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-22 17:05:42.204   371   871 D CommandListener: Setting iface cfg
,08-22 17:05:42.215   873  3642 D DhcpClient: Scheduling renewal in 86399s
,08-22 17:05:42.215   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-22 17:05:42.218   873  1308 E native  : do suspend true
,08-22 17:05:42.242   873  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-22 17:05:42.243   873  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-22 17:05:42.244   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-22 17:05:42.246   873  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-22 17:05:42.247   873  1310 D ConnectivityService: Adding iface wlan0 to network 101
,08-22 17:05:42.291   873  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-22 17:05:42.291   873  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-22 17:05:42.292   873  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-22 17:05:42.293   873  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-22 17:05:42.294   873  1310 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-22 17:05:42.300   873  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-22 17:05:42.304   873  1310 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-22 17:05:42.304   873  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-22 17:05:42.304   873  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101],
,08-22 17:05:42.304   873  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-22 17:05:42.304   873  1310 D ConnectivityService:    accepting network in place of null
,08-22 17:05:42.305   873  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-22 17:05:42.305   873  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-22 17:05:42.334   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 17:05:42.350   873  4177 D NetlinkSocketObserver: NeighborEvent{elapsedMs=155966, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-22 17:05:42.388   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 17:05:42.390   873  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-22 17:05:42.391   873  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-22 17:05:42.393   873  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-22 17:05:42.394   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-22 17:05:42.400  3463  3463 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 17:05:42.400  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 17:05:42.400  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 17:05:42.400  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 17:05:42.400  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 17:05:42.400  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 17:05:42.400  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 17:05:42.400  3463  3463 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 17:05:42.402  3463  3463 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 17:05:42.403  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 17:05:42.403  3463  3512 I jxcore-log: 
,08-22 17:05:42.438  1715  1715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-22 17:05:42.441  1715  3684 I iu.UploadsManager: num queued entries: 0
,08-22 17:05:42.441  1715  3684 I iu.UploadsManager: num updated entries: 0
,08-22 17:05:42.446  1715  1715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-22 17:05:42.447  1715  1715 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-22 17:05:42.449  3691  3691 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-22 17:05:42.453  3691  3691 D SprintDMHelper: simOperator: 
,08-22 17:05:42.453  3691  3691 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-22 17:05:42.460  1715  4193 I MDM     : [171] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-22 17:05:42.464  1715  4193 W BaseAppContext: Using Auth Proxy for data requests.
,08-22 17:05:42.483  1715  4193 V GoogleAuthProtoRequest: [171] a.<init>: mAccountName set to: thalitester@gmail.com
,08-22 17:05:42.493  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 17:05:42.495  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 17:05:42.495  3463  3463 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-22 17:05:42.496  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 17:05:42.496  3463  3512 I jxcore-log: ,
,08-22 17:05:42.505  1715  3684 I iu.SyncManager: NEXT; no task
,08-22 17:05:42.531  1508  2042 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-22 17:05:42.531  1508  2042 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-22 17:05:42.531  1508  2042 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-22 17:05:42.531  1508  2042 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 17:05:42.548  1715  4193 E MDM     : [171] SitrepService.a: Error sending sitrep.
,08-22 17:05:42.556  3463  3463 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-22 17:05:42.557  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 17:05:42.557  3463  3512 I jxcore-log: 
,08-22 17:05:42.581  2002  2487 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-22 17:05:42.598  3463  3463 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-22 17:05:42.599  3463  3512 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 17:05:42.599  3463  3512 I jxcore-log: 
,08-22 17:05:42.661   873  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 3, 6 -> obsolete
,08-22 17:05:42.803   873  4176 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-22 17:05:42.873  4181  4181 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-22 17:05:42.879  4181  4181 D AndroidRuntime: CheckJNI is OFF
,08-22 17:05:42.922  4181  4181 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-22 17:05:42.970  4181  4181 I Radio-JNI: register_android_hardware_Radio DONE
,08-22 17:05:42.993  4181  4181 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-22 17:05:43.005   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-22 17:05:43.006   873   886 I ActivityManager: Killing 3463:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-22 17:05:43.101  2867  4195 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-22 17:05:43.114   873  1901 D GraphicsStats: Buffer count: 2
,08-22 17:05:43.114   873  1707 I WindowState: WIN DEATH: Window{f66369d u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-22 17:05:43.115   873  1309 D WifiService: Client connection lost with reason: 4
,08-22 17:05:43.149   873   896 W PackageSettings: Skipping PackageSetting{c57b70c com.example.hello/10273} due to missing metadata
,08-22 17:05:43.178   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-22 17:05:43.178   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-22 17:05:43.179   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-22 17:05:43.179   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-22 17:05:43.179   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-22 17:05:43.179   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-22 17:05:43.179   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-22 17:05:43.179   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-22 17:05:43.179   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-22 17:05:43.179   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-22 17:05:43.179   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-22 17:05:43.179   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-22 17:05:43.179   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-22 17:05:43.179   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-22 17:05:43.179   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-22 17:05:43.179   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-22 17:05:43.179   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-22 17:05:43.179   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-22 17:05:43.179   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 17:05:43.179   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-22 17:05:43.179   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-22 17:05:43.179   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-22 17:05:43.179   873   886 I ActivityManager:   Force finishing activity ActivityRecord{fbde75a u0 com.test.thalitest/.MainActivity t2}
,08-22 17:05:43.182   873   896 I art     : Starting a blocking GC Explicit
,08-22 17:05:43.191   873  1955 W ActivityManager: Spurious death for ProcessRecord{84539dd 0:com.test.thalitest/u0a0}, curProc for 3463: null
,08-22 17:05:43.253   873   896 I art     : Explicit concurrent mark sweep GC freed 17233(1128KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.542ms total 69.361ms
,08-22 17:05:43.288  1508  4208 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-22 17:05:43.289  1508  4208 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-22 17:05:43.291   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-22 17:05:43.297  4181  4181 I art     : System.exit called, status: 0
08-22 17:05:43.297  4181  4181 I AndroidRuntime: VM exiting with result code 0.
,08-22 17:05:43.308   873   896 I ActivityManager: Start proc 4214:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-22 17:05:43.309   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-22 17:05:43.322   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-22 17:05:43.326  4115  4115 D BluetoothMapAppObserver: onReceive
,08-22 17:05:43.326  4115  4115 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-22 17:05:43.329  2002  2257 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-22 17:05:43.330   873  1300 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-22 17:05:43.335  3331  3331 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-22 17:05:43.335  1858  1858 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-22 17:05:43.338  1858  4226 I Keyboard.Facilitator.DecoderInitializer: run()
,08-22 17:05:43.340  1858  4226 I Decoder : createOrResetDecoder
,08-22 17:05:43.385   873   884 I ActivityManager: Start proc 4229:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-22 17:05:43.389  1914  1914 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-22 17:05:43.390  1508  1508 I ConfigService: onCreate
,08-22 17:05:43.391   873  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-22 17:05:43.423  1858  4226 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-22 17:05:43.434   873  1901 I ActivityManager: Killing 3957:com.google.android.deskclock/u0a44 (adj 15): empty #17
,08-22 17:05:43.445   873  1374 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3463 uid 10000
,08-22 17:05:43.446  1858  1858 I Keyboard.Facilitator: onFinishInput()
,08-22 17:05:43.476   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-22 17:05:43.479  4229  4229 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-22 17:05:43.489  1929  2022 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-22 17:05:43.489   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-22 17:05:43.490   873   885 E PackageManager: Failed to write settings, restoring backup
08-22 17:05:43.490   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-22 17:05:43.490   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-22 17:05:43.490   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-22 17:05:43.490   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-22 17:05:43.490   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-22 17:05:43.490   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 17:05:43.490   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-22 17:05:43.490   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-22 17:05:43.494   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-22 17:05:43.494   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-22 17:05:43.494   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-22 17:05:43.494   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 17:05:43.494   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 17:05:43.494   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 17:05:43.494   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-22 17:05:43.494   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-22 17:05:43.494   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-22 17:05:43.494   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-22 17:05:43.494   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-22 17:05:43.494   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-22 17:05:43.494   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-22 17:05:43.494   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-22 17:05:43.494   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-22 17:05:43.494   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-22 17:05:43.494   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 17:05:43.494   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 17:05:43.494   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 17:05:43.494   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 17:05:43.494   873   886 E DropBoxManagerService: 	... 13 more
,08-22 17:05:43.502   873  2236 I ActivityManager: Start proc 4245:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-22 17:05:43.502  1929  2022 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-22 17:05:43.502  1929  2022 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1929
08-22 17:05:43.502  1929  2022 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-22 17:05:43.502  1929  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-22 17:05:43.502  1929  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-22 17:05:43.502  1929  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-22 17:05:43.502  1929  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-22 17:05:43.502  1929  2022 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-22 17:05:43.502  1929  2022 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-22 17:05:43.502  1929  2022 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-22 17:05:43.502  1929  2022 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-22 17:05:43.502  1929  2022 E AndroidRuntime: ,	at android.os.Handler.dispatchMessage(Handler.java:95)
08-22 17:05:43.502  1929  2022 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-22 17:05:43.502  1929  2022 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-22 17:05:43.504   873  1421 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-22 17:05:43.507   873  4252 E DropBoxManagerService: Can't write: system_app_crash
08-22 17:05:43.507   873  4252 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
08-22 17:05:43.507   873  4252 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-22 17:05:43.507   873  4252 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 17:05:43.507   873  4252 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 17:05:43.507   873  4252 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 17:05:43.507   873  4252 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-22 17:05:43.507   873  4252 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-22 17:05:43.507   873  4252 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 17:05:43.507   873  4252 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 17:05:43.507   873  4252 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 17:05:43.507   873  4252 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 17:05:43.507   873  4252 E DropBoxManagerService: 	... 5 more
,08-22 17:05:43.511  1929  2022 I Process : Sending signal. PID: 1929 SIG: 9
,08-22 17:05:43.512  1858  4226 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-22 17:05:43.514  1858  4226 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-22 17:05:43.514  1858  4226 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-22 17:05:43.515  1858  4226 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-22 17:05:43.516  1858  4226 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-22 17:05:43.516  1858  4226 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-22 17:05:43.516  1858  4226 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-22 17:05:43.517  1858  4226 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-22 17:05:43.517  1858  4226 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-22 17:05:43.517  1858  4226 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-22 17:05:43.517  1858  4226 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-22 17:05:43.517  1858  4226 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-22 17:05:43.517  1858  4226 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-22 17:05:43.523   873  4176 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 22 Aug 2016 15:05:43 GMT], X-Android-Received-Millis=[1471878343523], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471878343092]}
08-22 17:05:43.524   873  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-22 17:05:43.524   873  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-22 17:05:43.524   873  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-22 17:05:43.525   873  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-22 17:05:43.565  4229  4229 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-22 17:05:43.578  4229  4261 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-22 17:05:43.578  4229  4261 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 17:05:43.578  4229  4261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 17:05:43.578  4229  4261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 17:05:43.578  4229  4261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 17:05:43.578  4229  4261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 17:05:43.578  4229  4261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 17:05:43.578  4229  4261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 17:05:43.578  4229  4261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 17:05:43.578  4229  4261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 17:05:43.578  4229  4261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 17:05:43.578  4229  4261 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 17:05:43.578  4229  4261 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 17:05:43.578  4229  4261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 17:05:43.578  4229  4261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-22 17:05:43.578  4229  4261 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-22 17:05:43.578  4229  4261 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-22 17:05:43.578  4229  4261 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-22 17:05:43.578  4229  4261 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-22 17:05:43.578  4229  4261 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 17:05:43.578  4229  4261 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-22 17:05:43.578  4229  4261 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-22 17:05:43.580  4229  4264 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-22 17:05:43.584   873  2236 D GraphicsStats: Buffer count: 1
,08-22 17:05:43.586   873  2237 I WindowState: WIN DEATH: Window{c5e2363 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-22 17:05:43.598  4229  4261 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-22 17:05:43.598  4229  4261 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 17:05:43.598  4229  4261 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 17:05:43.598  4229  4261 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 17:05:43.598  4229  4261 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 17:05:43.598  4229  4261 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 17:05:43.598  4229  4261 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 17:05:43.598  4229  4261 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 17:05:43.598  4229  4261 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 17:05:43.598  4229  4261 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 17:05:43.598  4229  4261 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 17:05:43.598  4229  4261 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 17:05:43.598  4229  4261 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 17:05:43.598  4229  4261 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 17:05:43.598  4229  4261 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-22 17:05:43.598  4229  4261 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-22 17:05:43.598  4229  4261 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-22 17:05:43.598  4229  4261 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-22 17:05:43.598  4229  4261 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-22 17:05:43.598  4229  4261 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 17:05:43.598  4229  4261 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-22 17:05:43.598  4229  4261 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-22 17:05:43.624   873   884 I ActivityManager: Start proc 4266:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-22 17:05:43.626   873  2236 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1929) has died
08-22 17:05:43.626   873  2236 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-22 17:05:43.628   873  2236 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-22 17:05:43.638  4229  4261 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-22 17:05:43.643  4229  4264 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-22 17:05:43.643  4229  4264 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-22 17:05:43.643  4229  4264 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-22 17:05:43.643  4229  4264 E AndroidRuntime: Process: android.process.acore, PID: 4229
08-22 17:05:43.643  4229  4264 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 17:05:43.643  4229  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 17:05:43.643  4229  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 17:05:43.643  4229  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 17:05:43.643  4229  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 17:05:43.643  4229  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 17:05:43.643  4229  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 17:05:43.643  4229  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 17:05:43.643  4229  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 17:05:43.643  4229  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 17:05:43.643  4229  4264 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 17:05:43.643  4229  4264 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 17:05:43.643  4229  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 17:05:43.643  4229  4264 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 17:05:43.643  4229  4264 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-22 17:05:43.643  4229  4264 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-22 17:05:43.643  4229  4264 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-22 17:05:43.643  4229  4264 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-22 17:05:43.643  4229  4264 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-22 17:05:43.643  4229  4264 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-22 17:05:43.643  4229  4264 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-22 17:05:43.643  4229  4264 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 17:05:43.643  4229  4264 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-22 17:05:43.643  4229  4264 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-22 17:05:43.645   873   886 I ActivityManager: Start proc 4278:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-22 17:05:43.649   873  4283 E DropBoxManagerService: Can't write: system_app_crash
08-22 17:05:43.649   873  4283 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-22 17:05:43.649   873  4283 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-22 17:05:43.649   873  4283 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 17:05:43.649   873  4283 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 17:05:43.649   873  4283 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 17:05:43.649   873  4283 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-22 17:05:43.649   873  4283 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-22 17:05:43.649   873  4283 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 17:05:43.649   873  4283 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 17:05:43.649   873  4283 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 17:05:43.649   873  4283 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 17:05:43.649   873  4283 E DropBoxManagerService: 	... 5 more
,08-22 17:05:43.654  4229  4264 I Process : Sending signal. PID: 4229 SIG: 9
,08-22 17:05:43.663   278   278 E lowmemorykiller: Error writing /proc/4229/oom_score_adj; errno=22
,08-22 17:05:43.668  4266  4266 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-22 17:05:43.672   278   278 E lowmemorykiller: Error writing /proc/4229/oom_score_adj; errno=22
,08-22 17:05:43.693  4278  4278 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 17:05:43.693  4278  4278 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-22 17:05:43.694  4278  4278 D AndroidRuntime: Shutting down VM
,08-22 17:05:43.698  1508  1508 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-22 17:05:43.699  1508  1508 D AndroidRuntime: Shutting down VM
08-22 17:05:43.700  1508  1508 E AndroidRuntime: FATAL EXCEPTION: main
08-22 17:05:43.700  1508  1508 E AndroidRuntime: Process: com.google.process.gapps, PID: 1508
08-22 17:05:43.700  1508  1508 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-22 17:05:43.700  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-22 17:05:43.700  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-22 17:05:43.700  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-22 17:05:43.700  1508  1508 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 17:05:43.700  1508  1508 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-22 17:05:43.700  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 17:05:43.700  1508  1508 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 17:05:43.700  1508  1508 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 17:05:43.700  1508  1508 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 17:05:43.700  1508  1508 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-22 17:05:43.700  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-22 17:05:43.700  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-22 17:05:43.700  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-22 17:05:43.700  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-22 17:05:43.700  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-22 17:05:43.700  1508  1508 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-22 17:05:43.700  1508  1508 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-22 17:05:43.700  1508  1508 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-22 17:05:43.700  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-22 17:05:43.700  1508  1508 E AndroidRuntime: 	... 8 more
,08-22 17:05:43.701  4278  4278 E AndroidRuntime: FATAL EXCEPTION: main
08-22 17:05:43.701  4278  4278 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4278
08-22 17:05:43.701  4278  4278 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-22 17:05:43.701  4278  4278 E AndroidRuntime: 	... 10 more
,08-22 17:05:43.704   873  4295 E DropBoxManagerService: Can't write: system_app_crash
08-22 17:05:43.704   873  4295 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-22 17:05:43.704   873  4295 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-22 17:05:43.704   873  4295 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 17:05:43.704   873  4295 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 17:05:43.704   873  4295 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 17:05:43.704   873  4295 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-22 17:05:43.704   873  4295 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-22 17:05:43.704   873  4295 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 17:05:43.704   873  4295 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 17:05:43.704   873  4295 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 17:05:43.704   873  4295 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 17:05:43.704   873  4295 E DropBoxManagerService: 	... 5 more
,08-22 17:05:43.704   873  1374 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-22 17:05:43.705   873  4296 E DropBoxManagerService: Can't write: system_app_crash
08-22 17:05:43.705   873  4296 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-22 17:05:43.705   873  4296 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-22 17:05:43.705   873  4296 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 17:05:43.705   873  4296 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 17:05:43.705   873  4296 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 17:05:43.705   873  4296 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-22 17:05:43.705   873  4296 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-22 17:05:43.705   873  4296 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 17:05:43.705   873  4296 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 17:05:43.705   873  4296 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 17:05:43.705   873  4296 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 17:05:43.705   873  4296 E DropBoxManagerService: 	... 5 more
08-22 17:05:43.708   278   278 E lowmemorykiller: Error writing /proc/4229/oom_score_adj; errno=22
08-22 17:05:43.709  4278  4278 I Process : Sending signal. PID: 4278 SIG: 9
,08-22 17:05:43.709  1508  1508 I Process : Sending signal. PID: 1508 SIG: 9
08-22 17:05:43.717   278   278 E lowmemorykiller: Error writing /proc/4229/oom_score_adj; errno=22
,08-22 17:05:43.733   873  1955 I ActivityManager: Killing 3976:com.qualcomm.timeservice/1000 (adj 15): empty #17
,08-22 17:05:43.763   873  1309 D WifiService: Client connection lost with reason: 4
,08-22 17:05:43.764  1715  4294 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@71650c0
08-22 17:05:43.765   873   884 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4278) has died
,08-22 17:05:43.766   873   884 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-22 17:05:43.775   873  1421 I ActivityManager: Process android.process.acore (pid 4229) has died
,08-22 17:05:43.775   873  1421 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-22 17:05:43.777   873  2236 I ActivityManager: Process com.google.process.gapps (pid 1508) has died
,08-22 17:05:43.777   873  2236 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
,08-22 17:05:43.778   873  2236 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 10999ms
,08-22 17:05:43.778   873  2236 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.playlog.uploader.UploaderService in 20999ms
,08-22 17:05:43.778   873  2236 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
,08-22 17:05:43.778   873  2236 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerIntentService in 30999ms
,08-22 17:05:43.778   873  2236 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.phenotype.service.PhenotypeIntentService in 30999ms
08-22 17:05:43.778   873  2236 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 30999ms
,08-22 17:05:43.779   873  2236 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 40998ms
,08-22 17:05:43.783  1715  1715 W RocketImpressions: ClearcutLogger connection suspended: 1,
,08-22 17:05:43.803   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
