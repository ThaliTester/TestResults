#### Test 797510152beef86_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-11 06:32:13.976  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-11 06:32:14.003  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-11 06:32:14.013  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-11 06:32:14.097  1499  1904 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-11 06:32:14.097  1499  1904 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-11 06:32:14.098  1499  1904 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 06:32:14.098  1499  1904 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-11 06:32:14.133  2581  2581 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-11 06:32:14.134  2581  2581 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-11 06:32:14.135  2581  2581 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-11 06:32:14.626  3322  3322 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-11 06:32:14.631  3322  3322 D AndroidRuntime: CheckJNI is OFF
08-11 06:32:14.666  3322  3322 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-11 06:32:14.710  3322  3322 I Radio-JNI: register_android_hardware_Radio DONE
08-11 06:32:14.731  3322  3322 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-11 06:32:14.736   872  1375 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 06:32:14.790  1805  2176 W SearchService: Abort, client detached.
08-11 06:32:14.801  3322  3322 D AndroidRuntime: Shutting down VM
08-11 06:32:14.805  1805  2126 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@ac382e1
08-11 06:32:14.805  1805  2144 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-11 06:32:14.805  1805  1805 I HotwordDetector: Closing mic
08-11 06:32:14.818   872  2015 I ActivityManager: Start proc 3332:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-11 06:32:14.828  1805  1805 W ErrorReporter: reportError [type: 29, code: 917507]: null
08-11 06:32:14.865   374  2146 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-11 06:32:14.866   374  2146 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-11 06:32:14.874   374  1276 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-11 06:32:14.877  1805  2143 I MicroRecognitionRnrImpl: Detection finished
08-11 06:32:14.877  1805  2141 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-11 06:32:14.899  3332  3332 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-11 06:32:14.919  3332  3332 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-11 06:32:14.926  3332  3332 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9069-9072)
08-11 06:32:14.926  3332  3332 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 06:32:14.942  3332  3332 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7e6b78a}
08-11 06:32:14.943  3332  3332 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 06:32:14.943  3332  3332 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-11 06:32:14.949  3332  3332 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-11 06:32:14.950  3332  3332 E SysUtils: ApplicationContext is null in ApplicationStatus
08-11 06:32:14.987  3332  3348 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
08-11 06:32:14.993  3332  3332 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-11 06:32:15.003  3332  3332 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 06:32:15.003  3332  3332 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 06:32:15.003  3332  3332 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 06:32:15.003  3332  3332 I Adreno  : Build Date                       : 10/20/15
08-11 06:32:15.003  3332  3332 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 06:32:15.003  3332  3332 I Adreno  : Local Branch                     : M14
08-11 06:32:15.003  3332  3332 I Adreno  : Remote Branch                    : 
08-11 06:32:15.003  3332  3332 I Adreno  : Remote Branch                    : 
08-11 06:32:15.003  3332  3332 I Adreno  : Reconstruct Branch               : 
,08-11 06:32:15.106   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4bc5e14:true
,08-11 06:32:15.137  3332  3332 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-11 06:32:15.149  3332  3332 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-11 06:32:15.217  3332  3371 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-11 06:32:15.229  3332  3357 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-11 06:32:15.274  3332  3371 I OpenGLRenderer: Initialized EGL, version 1.4
,08-11 06:32:15.364   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +560ms
,08-11 06:32:15.371  1650  1650 I Keyboard.Facilitator: onFinishInput()
,08-11 06:32:15.471  3332  3332 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3332
,08-11 06:32:15.628   872  1375 I ActivityManager: Killing 2317:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,08-11 06:32:15.635  3332  3332 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 06:32:15.681   872  1375 I ActivityManager: Killing 3004:com.qualcomm.telephony/1001 (adj 15): empty #18
,08-11 06:32:15.807  3332  3373 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1681393360
,08-11 06:32:15.814  3332  3373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 06:32:15.814  3332  3373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 06:32:15.814  3332  3373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 06:32:15.814  3332  3373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 06:32:15.814  3332  3373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-11 06:32:15.814  3332  3373 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18c0e69 added. We now have 1 listener(s)
,08-11 06:32:15.817  3332  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-11 06:32:15.818  3332  3373 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-11 06:32:15.819  3332  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-11 06:32:15.819  3332  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-11 06:32:15.823  3332  3373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 06:32:15.823  3332  3373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 06:32:15.823  3332  3373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 06:32:15.823  3332  3373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-11 06:32:15.823  3332  3373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 06:32:15.823  3332  3373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 06:32:15.823  3332  3373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 06:32:15.823  3332  3373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 06:32:15.823  3332  3373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 06:32:15.823  3332  3373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 06:32:15.823  3332  3373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 06:32:15.823  3332  3373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 06:32:15.823  3332  3373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 06:32:15.823  3332  3373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-11 06:32:15.823  3332  3373 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e4741c added. We now have 1 listener(s)
,08-11 06:32:15.823  3332  3373 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 06:32:15.828   872  1309 D WifiService: New client listening to asynchronous messages
,08-11 06:32:15.831  3332  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 06:32:15.831  3332  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-11 06:32:15.831  3332  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-11 06:32:15.831  3332  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-11 06:32:15.831  3332  3373 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-11 06:32:15.833  3332  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 06:32:15.833  3332  3373 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-11 06:32:15.836  3332  3373 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:32:15.836  3332  3373 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 06:32:15.836  3332  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:32:15.836  3332  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-11 06:32:15.836  3332  3373 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:32:15.836  3332  3373 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 06:32:15.836  3332  3373 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:32:15.836  3332  3373 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:32:15.836  3332  3373 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 06:32:15.836  3332  3373 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-11 06:32:15.836  3332  3373 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-11 06:32:15.837  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:32:15.838  3332  3373 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-11 06:32:15.864  3332  3332 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 06:32:16.832  3332  3382 W jxcore-log: Initializing JXcore engine
,08-11 06:32:16.832  3332  3382 W jxcore-log: JXcore engine is ready
,08-11 06:32:16.933  3382  3382 W Thread-286: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-11 06:32:16.933  3382  3382 W Thread-286: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12539]" dev="sockfs" ino=12539 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-11 06:32:16.933  3382  3382 W Thread-286: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-11 06:32:16.933  3382  3382 W Thread-286: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[22981]" dev="sockfs" ino=22981 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-11 06:32:16.951  3332  3382 W jxcore-log: Starting JXcore engine
,08-11 06:32:17.044  3332  3382 W jxcore-log: Platform android
08-11 06:32:17.044  3332  3382 W jxcore-log: 
08-11 06:32:17.044  3332  3382 W jxcore-log: Process ARCH arm
08-11 06:32:17.044  3332  3382 W jxcore-log: 
,08-11 06:32:17.268  3332  3382 I jxcore-log: JXcore Cordova bridge is ready!
08-11 06:32:17.268  3332  3382 I jxcore-log: 
,08-11 06:32:17.269  3332  3382 W jxcore-log: JXcore engine is started
,08-11 06:32:17.276  3332  3373 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-11 06:32:17.282  3332  3332 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-11 06:32:33.063  3332  3382 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 06:32:33.063  3332  3382 I jxcore-log: 
,08-11 06:32:33.065  3332  3382 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 06:32:33.065  3332  3382 I jxcore-log: 
,08-11 06:32:33.069  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:32:33.069  3332  3382 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 06:32:33.069  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:32:33.069  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-11 06:32:33.069  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:32:33.069  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 06:32:33.069  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:32:33.069  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:32:33.069  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 06:32:33.070  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:32:33.071  3332  3382 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 06:32:33.078  3332  3382 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 06:32:33.078  3332  3382 I jxcore-log: 
,08-11 06:32:33.086  3332  3382 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 06:32:33.086  3332  3382 I jxcore-log: 
,08-11 06:32:33.445  3332  3382 I jxcore-log: Running unit tests
08-11 06:32:33.445  3332  3382 I jxcore-log: 
,08-11 06:32:33.446  3332  3382 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 06:32:33.446  3332  3382 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2c59b9 added. We now have 2 listener(s)
,08-11 06:32:33.448  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-11 06:32:33.448  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 06:32:33.448  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-11 06:32:33.448  3332  3382 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 06:32:33.448  3332  3382 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a4ec1fe added. We now have 2 listener(s)
08-11 06:32:33.449  3332  3382 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 06:32:33.450  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 06:32:33.454  3332  3382 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 06:32:33.455  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:32:33.456  3332  3382 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 06:32:33.456  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:32:33.456  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-11 06:32:33.456  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:32:33.456  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 06:32:33.456  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:32:33.456  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:32:33.456  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 06:32:33.456  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 06:32:33.456  3332  3382 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 06:32:33.457  3332  3382 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 06:32:33.458  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 06:32:33.458  3332  3382 D ExecuteNativeTests: Running unit tests
,08-11 06:32:33.544  3332  3382 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 06:32:33.544  3332  3382 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1761fdc added. We now have 3 listener(s)
,08-11 06:32:33.545  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-11 06:32:33.545  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 06:32:33.545  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 06:32:33.545  3332  3382 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 06:32:33.545  3332  3382 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 added. We now have 3 listener(s)
08-11 06:32:33.545  3332  3382 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 06:32:33.546  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 06:32:33.551  3332  3382 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 06:32:33.552  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:32:33.553  3332  3382 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 06:32:33.553  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:32:33.553  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-11 06:32:33.553  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:32:33.553  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 06:32:33.553  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:32:33.553  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:32:33.553  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 06:32:33.553  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:32:33.553  3332  3382 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 06:32:33.554  3332  3382 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 06:32:33.558  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:32:33.560  3332  3382 I System.out: Running UT from: ConnectionHelperTest
,08-11 06:32:33.562  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-11 06:32:33.563  3332  3382 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 06:32:33.564  3332  3382 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-11 06:32:33.564  3332  3382 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-11 06:32:33.570  3332  3382 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-11 06:32:33.571  3332  3382 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-11 06:32:33.572  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-11 06:32:33.572  3332  3382 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-11 06:32:33.573  3332  3382 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-11 06:32:33.574  3332  3382 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-11 06:32:33.574  3332  3382 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 06:32:33.575  3332  3382 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 06:32:33.575  3332  3382 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 06:32:33.575  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 06:32:33.575  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:33.575  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 06:32:33.576  3332  3382 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-11 06:32:33.576  3332  3382 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1761fdc removed from the list
,08-11 06:32:33.576  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:33.576  3332  3382 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 removed from the list
,08-11 06:32:33.576  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
08-11 06:32:33.576  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 06:32:33.576  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 06:32:33.577  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:33.577  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 06:32:33.577  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 06:32:33.577  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:33.578  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
,08-11 06:32:33.578  3332  3382 I System.out: Running UT from: ConnectionHelperTest
08-11 06:32:33.579  3332  3382 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-11 06:32:33.580  3332  3382 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 06:32:33.580  3332  3382 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 06:32:33.580  3332  3382 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 06:32:33.580  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 06:32:33.580  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:33.580  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:33.581  3332  3382 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1761fdc not in the list
08-11 06:32:33.581  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:33.581  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
,08-11 06:32:33.581  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
08-11 06:32:33.581  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:33.581  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:33.581  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:33.581  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:33.582  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 06:32:33.582  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 06:32:33.582  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:33.582  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:33.585  3332  3382 I System.out: Running UT from: ConnectionHelperTest
08-11 06:32:33.590  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-11 06:32:33.590  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-11 06:32:33.590  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-11 06:32:33.590  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-11 06:32:33.590  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-11 06:32:33.590  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-11 06:32:33.590  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-11 06:32:33.590  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-11 06:32:33.590  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-11 06:32:33.590  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-11 06:32:33.591  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-11 06:32:33.591  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-11 06:32:33.591  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-11 06:32:33.591  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-11 06:32:33.591  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-11 06:32:33.591  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-11 06:32:33.591  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-11 06:32:33.591  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-11 06:32:33.591  3332  3382 D io.jxcore.node.ConnectionM,odel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-11 06:32:33.591  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-11 06:32:33.591  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-11 06:32:33.591  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-11 06:32:33.591  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-11 06:32:33.591  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-11 06:32:33.591  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-11 06:32:33.591  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-11 06:32:33.591  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-11 06:32:33.592  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-11 06:32:33.592  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-11 06:32:33.592  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-11 06:32:33.592  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-11 06:32:33.592  3332  3382 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 06:32:33.592  3332  3382 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 06:32:33.592  3332  3382 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 06:32:33.592  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 06:32:33.592  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:33.592  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:33.592  3332  3382 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1761fdc not in the list
08-11 06:32:33.592  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:33.592  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:33.592  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
08-11 06:32:33.592  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:33.592  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:33.592  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:33.592  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:33.593  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 06:32:33.593  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 06:32:33.593  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:33.593  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:33.594  3332  3382 I System.out: Running UT from: ConnectionHelperTest
08-11 06:32:33.594  3332  3382 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-11 06:32:33.595  3332  3382 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 06:32:33.596  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:32:33.596  3332  3382 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 06:32:33.596  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:32:33.596  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-11 06:32:33.596  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:32:33.596  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 06:32:33.596  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:32:33.596  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:32:33.596  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 06:32:33.596  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:32:33.596  3332  3382 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 06:32:33.596  3332  3382 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 06:32:33.597  3332  3382 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 06:32:33.597  3332  3382 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 06:32:33.597  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-11 06:32:33.597  3332  3382 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 06:32:33.597  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:32:33.597  3332  3382 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-11 06:32:33.602  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-11 06:32:33.602  3332  3382 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-11 06:32:33.603  3332  3332 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-11 06:32:33.603  3332  3382 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-11 06:32:33.603  3332  3382 I io.jxcore.node.ConnectionHelper: start: OK
,08-11 06:32:34.104  3332  3332 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 06:32:34.346  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:32:34.356  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:32:34.360  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:32:34.407  1499  1903 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-11 06:32:34.407  1499  1903 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-11 06:32:34.407  1499  1903 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 06:32:34.408  1499  1903 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 06:32:34.453  2581  2581 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-11 06:32:34.454  2581  2581 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-11 06:32:34.455  2581  2581 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-11 06:32:35.865   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-11 06:32:35.876  1650  1650 I Keyboard.Facilitator: onFinishInput()
,08-11 06:32:35.881   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 06:32:35.881   872   892 I Adreno  : Build Date                       : 10/20/15
08-11 06:32:35.881   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 06:32:35.881   872   892 I Adreno  : Local Branch                     : M14
08-11 06:32:35.881   872   892 I Adreno  : Remote Branch                    : 
08-11 06:32:35.881   872   892 I Adreno  : Remote Branch                    : 
08-11 06:32:35.881   872   892 I Adreno  : Reconstruct Branch               : 
,08-11 06:32:35.910   280   307 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (196 us)
,08-11 06:32:36.530  3332  3332 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-11 06:32:36.530  3332  3332 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-11 06:32:36.588   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-11 06:32:36.594  3332  3332 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@bcf5c30 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@d220e61, 16908290=android.view.AbsSavedState$1@d220e61}, android:focusedViewId=100}]}]
08-11 06:32:36.594  3332  3332 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-11 06:32:36.595  3332  3332 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-11 06:32:36.596  3332  3332 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-11 06:32:36.597   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-11 06:32:36.606   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-11 06:32:36.606   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-11 06:32:36.607   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-11 06:32:36.834   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-11 06:32:36.839   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-11 06:32:36.840   872  1332 D SurfaceControl: Excessive delay in setPowerMode(): 234ms
,08-11 06:32:36.845   872   892 I DreamManagerService: Entering dreamland.
,08-11 06:32:36.846   872   892 I PowerManagerService: Dozing...
,08-11 06:32:36.847   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-11 06:32:36.928   374  3344 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-11 06:32:36.929   374  3344 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-11 06:32:36.944   872  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 06:32:36.948   872  1308 E native  : do suspend false
,08-11 06:32:36.967  1701  3391 D NfcService: Discovery configuration equal, not updating.
,08-11 06:32:37.007   872  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 06:32:37.017   872  1308 E native  : do suspend true
,08-11 06:32:37.058   374  1316 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-11 06:32:37.059   374  1316 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-11 06:32:37.310  1499  2010 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-11 06:32:38.607  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 06:32:38.609  3332  3382 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
,08-11 06:32:38.613  3332  3382 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 06:32:38.614  3332  3382 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 06:32:38.614  3332  3382 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-11 06:32:38.615  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 06:32:38.615  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-11 06:32:38.615  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 06:32:38.615  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-11 06:32:38.616  3332  3382 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-11 06:32:38.616  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-11 06:32:38.619  3332  3382 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-11 06:32:38.621  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 06:32:38.622  3332  3382 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 06:32:38.623  3332  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-11 06:32:38.623  3332  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 06:32:38.625  3332  3332 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 06:32:38.625  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 06:32:38.625  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:38.626  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 06:32:38.626  3332  3382 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1761fdc not in the list
08-11 06:32:38.626  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:38.627  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:38.627  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
08-11 06:32:38.627  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:38.629  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:38.629  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:38.630  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 06:32:38.630  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 06:32:38.630  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:38.631  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
,08-11 06:32:38.634  3332  3382 I System.out: Running UT from: ConnectionHelperTest
,08-11 06:32:38.634  3332  3382 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-11 06:32:38.638  3332  3382 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 06:32:38.639  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:32:38.639  3332  3382 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 06:32:38.639  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:32:38.639  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-11 06:32:38.639  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:32:38.639  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 06:32:38.639  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:32:38.639  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:32:38.639  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 06:32:38.639  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 06:32:38.639  3332  3382 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 06:32:38.639  3332  3382 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-11 06:32:38.640  3332  3382 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-11 06:32:38.640  3332  3382 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 06:32:38.640  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-11 06:32:38.640  3332  3382 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 06:32:38.641  3332  3382 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-11 06:32:38.641  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:32:38.643  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-11 06:32:38.643  3332  3382 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-11 06:32:38.644  3332  3382 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-11 06:32:38.644  3332  3382 I io.jxcore.node.ConnectionHelper: start: OK
08-11 06:32:38.644  3332  3332 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,08-11 06:32:39.145  3332  3332 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 06:32:41.030  1821  2316 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-11 06:32:43.644  3332  3382 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 06:32:43.645  3332  3382 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 06:32:43.645  3332  3382 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-11 06:32:43.646  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 06:32:43.646  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-11 06:32:43.646  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 06:32:43.646  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-11 06:32:43.647  3332  3382 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-11 06:32:43.647  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-11 06:32:43.648  3332  3382 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-11 06:32:43.649  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 06:32:43.651  3332  3382 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 06:32:43.652  3332  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-11 06:32:43.652  3332  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 06:32:43.653  3332  3332 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 06:32:44.154  3332  3332 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 06:32:44.155  3332  3332 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 06:32:44.155  3332  3332 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 06:32:48.653  3332  3382 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 06:32:48.653  3332  3382 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 06:32:48.653  3332  3382 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 06:32:48.654  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 06:32:48.654  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.655  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 06:32:48.655  3332  3382 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1761fdc not in the list
08-11 06:32:48.655  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:48.656  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
,08-11 06:32:48.656  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
08-11 06:32:48.656  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.658  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.659  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 06:32:48.660  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 06:32:48.660  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 06:32:48.660  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 06:32:48.661  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:48.663  3332  3382 I System.out: Running UT from: ConnectionHelperTest
08-11 06:32:48.663  3332  3382 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-11 06:32:48.665  3332  3382 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 06:32:48.666  3332  3382 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 06:32:48.666  3332  3382 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 06:32:48.667  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 06:32:48.667  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 06:32:48.667  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.668  3332  3382 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1761fdc not in the list
08-11 06:32:48.668  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 06:32:48.668  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:48.668  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
08-11 06:32:48.669  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.669  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.669  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.670  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.673  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 06:32:48.673  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 06:32:48.673  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:48.674  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
,08-11 06:32:48.676  3332  3382 I System.out: Running UT from: ConnectionHelperTest
08-11 06:32:48.677  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-11 06:32:48.677  3332  3382 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 06:32:48.677  3332  3382 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 06:32:48.678  3332  3382 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 06:32:48.678  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 06:32:48.678  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 06:32:48.678  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.679  3332  3382 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1761fdc not in the list
08-11 06:32:48.679  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:48.679  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:48.679  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
08-11 06:32:48.680  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.680  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.680  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.680  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.682  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 06:32:48.682  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 06:32:48.682  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 06:32:48.682  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:48.684  3332  3382 I System.out: Running UT from: ConnectionHelperTest
08-11 06:32:48.684  3332  3382 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-11 06:32:48.685  3332  3382 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 06:32:48.685  3332  3382 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 06:32:48.685  3332  3382 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 06:32:48.686  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 06:32:48.686  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.686  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.686  3332  3382 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1761fdc not in the list
08-11 06:32:48.687  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:48.687  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:48.687  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
08-11 06:32:48.687  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.688  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.688  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.688  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.689  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 06:32:48.689  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 06:32:48.689  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:48.689  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:48.690  3332  3382 I System.out: Running UT from: ConnectionHelperTest
,08-11 06:32:48.690  3332  3382 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-11 06:32:48.690  3332  3382 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 06:32:48.691  3332  3382 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 06:32:48.691  3332  3382 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 06:32:48.691  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 06:32:48.691  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.691  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.691  3332  3382 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1761fdc not in the list
,08-11 06:32:48.691  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:48.692  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:48.692  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
08-11 06:32:48.692  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.692  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.692  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.692  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 06:32:48.693  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 06:32:48.693  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 06:32:48.693  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:48.693  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:48.694  3332  3382 I System.out: Running UT from: ConnectionHelperTest
,08-11 06:32:48.694  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-11 06:32:48.695  3332  3382 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 06:32:48.695  3332  3382 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 06:32:48.695  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-11 06:32:48.695  3332  3382 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 06:32:48.695  3332  3382 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 06:32:48.696  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-11 06:32:48.696  3332  3382 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 06:32:48.696  3332  3382 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-11 06:32:48.696  3332  3382 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 06:32:48.696  3332  3382 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 06:32:48.696  3332  3382 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 06:32:48.696  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 06:32:48.696  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.696  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.697  3332  3382 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1761fdc not in the list
08-11 06:32:48.697  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:48.697  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
,08-11 06:32:48.698  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
08-11 06:32:48.698  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.698  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.699  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.699  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 06:32:48.700  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-11 06:32:48.701  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 06:32:48.701  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:48.701  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list,
08-11 06:32:48.703  3332  3382 I System.out: Running UT from: ConnectionHelperTest
08-11 06:32:48.703  3332  3382 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-11 06:32:48.703  3332  3382 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-11 06:32:48.703  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-11 06:32:48.707  3332  3382 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-11 06:32:48.707  3332  3382 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-11 06:32:48.707  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-11 06:32:48.708  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-11 06:32:48.708  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-11 06:32:48.708  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-11 06:32:48.708  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-11 06:32:48.708  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-11 06:32:48.708  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-11 06:32:48.708  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-11 06:32:48.708  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-11 06:32:48.708  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-11 06:32:48.709  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-11 06:32:48.709  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-11 06:32:48.709  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-11 06:32:48.709  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-11 06:32:48.709  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-11 06:32:48.709  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-11 06:32:48.709  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-11 06:32:48.710  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-11 06:32:48.710  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-11 06:32:48.710  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-11 06:32:48.710  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-11 06:32:48.710  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-11 06:32:48.710  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-11 06:32:48.710  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-11 06:32:48.710  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-11 06:32:48.710  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-11 06:32:48.711  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-11 06:32:48.711  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-11 06:32:48.711  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-11 06:32:48.711  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-11 06:32:48.711  3332  3382 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-11 06:32:48.712  3332  3382 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-11 06:32:48.712  3332  3382 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-11 06:32:48.713  3332  3382 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-11 06:32:48.713  3332  3382 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-11 06:32:48.713  3332  3382 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-11 06:32:48.713  3332  3382 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-11 06:32:48.713  3332  3382 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-11 06:32:48.713  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-11 06:32:48.717  3332  3382 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
08-11 06:32:48.718  3332  3382 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-11 06:32:48.720  3332  3382 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-11 06:32:48.720  3332  3382 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-11 06:32:48.721  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-11 06:32:48.721  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-11 06:32:48.721  3332  3382 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-11 06:32:48.721  3332  3382 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-11 06:32:48.721  3332  3382 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-11 06:32:48.723  3332  3382 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 06:32:48.723  3332  3382 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 06:32:48.723  3332  3382 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 06:32:48.723  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 06:32:48.723  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.724  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.724  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-11 06:32:48.725  3332  3396 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 350)
08-11 06:32:48.725  3332  3382 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1761fdc not in the list
08-11 06:32:48.725  3332  3396 E BluetoothDevice: Bluetooth is not enabled
08-11 06:32:48.725  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:48.726  3332  3396 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): null (thread ID: 350)
08-11 06:32:48.726  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:48.726  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
08-11 06:32:48.726  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.726  3332  3397 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 350
08-11 06:32:48.726  3332  3396 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 350)
08-11 06:32:48.726  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.727  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.727  3332  3396 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): null (thread ID: 350)
08-11 06:32:48.727  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.728  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 06:32:48.728  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 06:32:48.728  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:48.728  3332  3332 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> 00:11:22:33:44:55]: Failed to connect (tried 1 time(s)): null
08-11 06:32:48.728  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:48.730  3332  3382 I System.out: Running UT from: ConnectionHelperTest
08-11 06:32:48.730  3332  3332 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: Failed to connect (tried 1 time(s)): null
08-11 06:32:48.731  3332  3332 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-11 06:32:48.730  3332  3382 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-11 06:32:48.731  3332  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 06:32:48.731  3332  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 06:32:48.732  3332  3382 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 06:32:48.732  3332  3382 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 06:32:48.732  3332  3382 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 06:32:48.732  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 06:32:48.732  3332  3396 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Failed to find a thread with ID 350
08-11 06:32:48.732  3332  3396 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 350)
08-11 06:32:48.733  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.733  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.733  3332  3382 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1761fdc not in the list
08-11 06:32:48.733  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:48.733  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:48.733  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
08-11 06:32:48.733  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.733  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.733  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.733  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.734  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 06:32:48.734  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 06:32:48.734  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:48.734  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:48.735  3332  3382 I System.out: Running UT from: ConnectionHelperTest
08-11 06:32:48.735  3332  3382 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-11 06:32:48.735  3332  3382 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 06:32:48.735  3332  3382 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 06:32:48.735  3332  3382 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 06:32:48.735  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 06:32:48.735  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.735  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.735  3332  3382 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1761fdc not in the list
08-11 06:32:48.735  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:48.736  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:48.736  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
08-11 06:32:48.736  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.736  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.736  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.736  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.736  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 06:32:48.736  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 06:32:48.736  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:48.737  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:48.737  3332  3382 I System.out: Running UT from: ConnectionHelperTest
08-11 06:32:48.737  3332  3382 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-11 06:32:48.737  3332  3382 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-11 06:32:48.737  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-11 06:32:48.737  3332  3382 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-11 06:32:48.737  3332  3382 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-11 06:32:48.738  3332  3382 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-11 06:32:48.738  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-11 06:32:48.738  3332  3382 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-11 06:32:48.738  3332  3382 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-11 06:32:48.738  3332  3382 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-11 06:32:48.738  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-11 06:32:48.738  3332  3382 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-11 06:32:48.738  3332  3382 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 06:32:48.738  3332  3382 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 06:32:48.738  3332  3382 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 06:32:48.738  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 06:32:48.738  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.738  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.738  3332  3382 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1761fdc not in the list
08-11 06:32:48.739  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:48.739  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:48.739  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
08-11 06:32:48.739  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.739  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.739  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.739  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.739  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 06:32:48.739  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 06:32:48.739  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:48.739  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:48.740  3332  3382 I System.out: Running UT from: ConnectionHelperTest
08-11 06:32:48.740  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 06:32:48.740  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.740  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:48.740  3332  3382 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1761fdc not in the list
,08-11 06:32:48.740  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:48.740  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:48.740  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
08-11 06:32:48.740  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:48.740  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 06:32:53.741  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 06:32:53.742  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:53.742  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 06:32:53.742  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:53.742  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:53.743  3332  3382 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1761fdc not in the list
,08-11 06:32:53.743  3332  3382 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 06:32:53.744  3332  3382 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 06:32:53.744  3332  3382 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 06:32:53.745  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 06:32:53.746  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:53.746  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:53.746  3332  3382 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1761fdc not in the list
,08-11 06:32:53.747  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 06:32:53.747  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:53.747  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 06:32:53.748  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:53.748  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:53.748  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 06:32:53.748  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:53.750  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 06:32:53.750  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 06:32:53.751  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:53.751  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:53.753  3332  3382 I System.out: Running UT from: ConnectionHelperTest
,08-11 06:32:53.756  3332  3382 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-11 06:32:53.758  3332  3382 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 06:32:53.758  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
08-11 06:32:53.759  3332  3382 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
08-11 06:32:53.759  3332  3332 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
,08-11 06:32:53.759  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 06:32:53.759  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 06:32:53.760  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-11 06:32:53.760  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 06:32:53.760  3332  3382 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
08-11 06:32:53.760  3332  3332 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-11 06:32:53.760  3332  3382 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1761fdc not in the list
,08-11 06:32:53.760  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:53.760  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-11 06:32:53.760  3332  3382 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-11 06:32:53.761  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-11 06:32:53.761  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 06:32:53.761  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:53.761  3332  3382 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 06:32:53.762  3332  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-11 06:32:53.762  3332  3332 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-11 06:32:53.762  3332  3332 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 06:32:53.762  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
,08-11 06:32:53.762  3332  3382 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,08-11 06:32:53.762  3332  3382 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 06:32:53.763  3332  3382 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 06:32:53.763  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 06:32:53.763  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 06:32:53.763  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 06:32:53.763  3332  3382 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1761fdc not in the list,
,08-11 06:32:53.763  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 06:32:53.763  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
,08-11 06:32:53.763  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 06:32:53.763  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:53.764  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 06:32:53.764  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:53.764  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 06:32:53.764  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 06:32:53.764  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 06:32:53.764  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:53.764  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:53.765  3332  3382 I System.out: Running UT from: ConnectionHelperTest
08-11 06:32:53.765  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-11 06:32:53.765  3332  3382 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 06:32:53.765  3332  3382 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 06:32:53.766  3332  3382 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-11 06:32:53.766  3332  3382 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-11 06:32:53.766  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-11 06:32:53.766  3332  3382 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 06:32:53.766  3332  3382 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 06:32:53.766  3332  3382 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 06:32:53.766  3332  3382 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 06:32:53.767  3332  3382 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 06:32:53.767  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 06:32:53.767  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:53.767  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:53.767  3332  3382 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1761fdc not in the list
08-11 06:32:53.767  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:53.768  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:53.768  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
08-11 06:32:53.768  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:53.768  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:53.768  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:53.768  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:53.768  3332  3382 I org.thaliproject.p2p.btconnectorlib.D,iscoveryManager: stopAdvertising
08-11 06:32:53.769  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 06:32:53.769  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:53.769  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:53.769  3332  3382 I System.out: Running UT from: ConnectionHelperTest
08-11 06:32:53.771  3332  3382 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 06:32:53.771  3332  3382 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 06:32:53.771  3332  3382 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 06:32:53.772  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 06:32:53.772  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:53.772  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:53.772  3332  3382 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1761fdc not in the list
08-11 06:32:53.772  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:53.772  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:53.772  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
08-11 06:32:53.772  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:53.773  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:53.773  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-11 06:32:53.773  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 06:32:53.773  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 06:32:53.773  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 06:32:53.773  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:53.773  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:53.774  3332  3382 I System.out: Running UT from: ConnectionHelperTest
08-11 06:32:53.774  3332  3382 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 06:32:53.774  3332  3382 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 06:32:53.774  3332  3382 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 06:32:53.775  3332  3382 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 06:32:53.775  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:53.775  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:53.775  3332  3382 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1761fdc not in the list
08-11 06:32:53.775  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:53.775  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:53.775  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
08-11 06:32:53.775  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:53.775  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:53.775  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:53.776  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:53.776  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 06:32:53.776  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 06:32:53.776  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:53.776  3332  3382 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d28c8e5 not in the list
08-11 06:32:53.777  3332  3382 I System.out: Running UT from: ConnectionModelTest
08-11 06:32:53.778  3332  3382 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-11 06:32:53.778  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-11 06:32:53.778  3332  3382 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-11 06:32:53.778  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-11 06:32:53.778  3332  3382 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-11 06:32:53.778  3332  3,382 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-11 06:32:53.779  3332  3382 I System.out: Running UT from: ConnectionModelTest
08-11 06:32:53.780  3332  3382 I System.out: Running UT from: ConnectionModelTest
08-11 06:32:53.781  3332  3382 I System.out: Running UT from: ConnectionModelTest
08-11 06:32:53.781  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-11 06:32:53.781  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-11 06:32:53.782  3332  3382 I System.out: Running UT from: ConnectionModelTest
08-11 06:32:53.782  3332  3382 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-11 06:32:53.783  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left,
,08-11 06:32:53.783  3332  3382 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1,
08-11 06:32:53.783  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-11 06:32:53.783  3332  3382 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-11 06:32:53.783  3332  3382 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-11 06:32:53.783  3332  3382 I System.out: Running UT from: ConnectionModelTest
08-11 06:32:53.784  3332  3382 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed,
08-11 06:32:53.784  3332  3382 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-11 06:32:53.784  3332  3382 I System.out: Running UT from: ConnectionModelTest,
08-11 06:32:53.785  3332  3382 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-11 06:32:53.785  3332  3382 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-11 06:32:53.785  3332  3382 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-11 06:32:53.785  3332  3382 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-11 06:32:53.786  3332  3382 I System.out: Running UT from: ConnectionModelTest
08-11 06:32:53.786  3332  3382 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 06:32:53.786  3332  3382 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8048e74 added. We now have 3 listener(s)
08-11 06:32:53.787  3332  3382 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 06:32:53.788   872  2015 D WifiService: setWifiEnabled: true pid=3332, uid=10000
08-11 06:32:53.788   872  2015 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 06:32:53.793  3332  3382 I System.out: Running UT from: ConnectivityMonitorTest
08-11 06:32:53.793  3332  3382 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 06:32:53.794  3332  3382 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f102f9d added. We now have 4 listener(s)
08-11 06:32:53.794  3332  3382 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 06:32:53.795  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:32:53.795  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:32:53.796  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 06:32:53.796  3332  3382 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f102f9d removed from the list
08-11 06:32:53.796  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
08-11 06:32:53.796  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:53.796  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:53.797  3332  3382 I System.out: Running UT from: ConnectivityMonitorTest
08-11 06:32:53.797  3332  3382 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 06:32:53.797  3332  3382 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8d44c12 added. We now have 4 listener(s)
,08-11 06:32:53.797  3332  3382 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 06:32:53.798  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 06:32:53.798  3332  3382 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8d44c12 removed from the list
08-11 06:32:53.798  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
08-11 06:32:53.798  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:32:53.799  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:32:53.799  3332  3382 I System.out: Running UT from: ConnectivityMonitorTest
,08-11 06:32:53.799  3332  3382 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 06:32:53.799  3332  3382 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@97e0fe3 added. We now have 4 listener(s)
08-11 06:32:53.799  3332  3382 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 06:32:53.800   872  1738 D WifiService: setWifiEnabled: false pid=3332, uid=10000
08-11 06:32:53.800   872  1738 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 06:32:53.814   872   889 I ActivityManager: Start proc 3400:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-11 06:32:53.814   872  1308 D WifiConfigStore: Loading config and enabling all networks 
08-11 06:32:53.817  3332  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:32:53.817  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:32:53.817  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:32:53.817  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-11 06:32:53.817  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 06:32:53.817  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 06:32:53.817  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:32:53.817  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:32:53.817  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 06:32:53.817  3332  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:32:53.817  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 06:32:53.818  3332  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:32:53.818  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:32:53.818  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:32:53.818  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-11 06:32:53.818  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 06:32:53.818  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 06:32:53.818  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:32:53.818  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:32:53.818  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 06:32:53.818  3332  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:32:53.818  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 06:32:53.833   872   885 I ActivityManager: Start proc 3412:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-11 06:32:53.836  3332  3382 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 06:32:53.837   872  1308 D WifiConfigStore: loaded 0 passpoint configs
08-11 06:32:53.837  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:32:53.837  3332  3382 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-11 06:32:53.837  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:32:53.837  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-11 06:32:53.837  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 06:32:53.837  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 06:32:53.837  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:32:53.837  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:32:53.837  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 06:32:53.837  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:32:53.837  3332  3382 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 06:32:53.837  3332  3382 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 06:32:53.838  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:32:53.838   872  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-11 06:32:53.839   872  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-11 06:32:53.840   872  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-11 06:32:53.841   872  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2,
08-11 06:32:53.841   872  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-11 06:32:53.841   872  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-11 06:32:53.860  3412  3412 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-11 06:32:53.891   370   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-11 06:32:53.891   872  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-11 06:32:53.892   370   870 D CommandListener: Setting iface cfg
,08-11 06:32:53.893   872  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '34 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 34 Failed to set address (No such device)'
,08-11 06:32:53.893   872  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-11 06:32:53.899   872  1308 E native  : do suspend true
08-11 06:32:53.899  3400  3400 D AdapterServiceConfig: Adding HeadsetService
,08-11 06:32:53.899  3400  3400 D AdapterServiceConfig: Adding A2dpService
08-11 06:32:53.899  3400  3400 D AdapterServiceConfig: Adding HidService
08-11 06:32:53.900  3400  3400 D AdapterServiceConfig: Adding HealthService
08-11 06:32:53.900  3400  3400 D AdapterServiceConfig: Adding PanService
08-11 06:32:53.900  3400  3400 D AdapterServiceConfig: Adding GattService
08-11 06:32:53.900  3400  3400 D AdapterServiceConfig: Adding BluetoothMapService
,08-11 06:32:53.907  3412  3412 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
08-11 06:32:53.907   872  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-11 06:32:53.907   872  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-11 06:32:53.926  1460  1460 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,08-11 06:32:53.926  1460  1460 W wpa_supplicant: wlan0: Failed to initiate AP scan
,08-11 06:32:53.928   872  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 06:32:53.931  3332  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:32:53.931  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:32:53.931  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:32:53.931  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-11 06:32:53.931  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:32:53.931  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 06:32:53.931  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:32:53.931  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:32:53.931  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 06:32:53.931  3332  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 06:32:53.931  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 06:32:53.932  3332  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:32:53.933  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:32:53.933  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:32:53.933  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-11 06:32:53.933  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:32:53.933  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 06:32:53.933  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:32:53.933  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:32:53.933  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 06:32:53.933  3332  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:32:53.933  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 06:32:53.933  3332  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:32:53.933  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:32:53.933  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:32:53.933  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-11 06:32:53.933  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:32:53.933  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 06:32:53.933  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:32:53.933  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:32:53.933  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 06:32:53.933  3332  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:32:53.933  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 06:32:53.935  1821  2047 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 06:32:53.935   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dd3596e:true
08-11 06:32:53.936  3400  3400 D BluetoothAdapterState: make() - Creating AdapterState
,08-11 06:32:53.940  3400  3400 I bt_bluedroid: init
,08-11 06:32:53.941  3400  3438 I BluetoothAdapterState: Entering OffState
,08-11 06:32:53.943   872  1734 I ActivityManager: Killing 2669:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-11 06:32:53.943  3400  3440 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-11 06:32:53.944  3400  3440 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-11 06:32:53.944  3400  3440 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-11 06:32:53.945  3400  3440 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-11 06:32:53.946  3400  3400 I bt_bluedroid: get_profile_interface socket
,08-11 06:32:53.947  3400  3443 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-11 06:32:53.948  3400  3400 I bt_bluedroid: get_profile_interface sdp
,08-11 06:32:54.010  3400  3443 D BluetoothAdapterProperties: Name is: Nexus 6
,08-11 06:32:54.014  3400  3411 I bt_bluedroid: config_hci_snoop_log
,08-11 06:32:54.017   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-11 06:32:54.025  3400  3438 D BluetoothAdapterState: Current state: OFF, message: 0
,08-11 06:32:54.025  3400  3438 D BluetoothAdapterProperties: Setting state to 14
,08-11 06:32:54.025  3400  3438 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-11 06:32:54.029  3400  3438 D BluetoothBondStateMachine: make
,08-11 06:32:54.032  3400  3444 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-11 06:32:54.040  3400  3400 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-11 06:32:54.041  3400  3438 I BluetoothAdapterState: Entering PendingCommandState
,08-11 06:32:54.042  3400  3400 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f87c4
,08-11 06:32:54.043  3400  3400 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-11 06:32:54.043  3400  3400 D BtGatt.GattService: Received start request. Starting profile...
08-11 06:32:54.044  3400  3400 D BtGatt.GattService: start()
08-11 06:32:54.044  3400  3400 I bt_bluedroid: get_profile_interface gatt
,08-11 06:32:54.044  3400  3400 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f87c4
08-11 06:32:54.045  3400  3400 D BtGatt.AdvertiseManager: advertise manager created
,08-11 06:32:54.049  3400  3400 V BluetoothAdapterState: isTurningOff()=false
08-11 06:32:54.049  3400  3400 V BluetoothAdapterState: isTurningOn()=false
08-11 06:32:54.049  3400  3400 V BluetoothAdapterState: isBleTurningOn()=true
08-11 06:32:54.049  3400  3400 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 06:32:54.049  3400  3438 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-11 06:32:54.049  3400  3438 I bt_bluedroid: enable
08-11 06:32:54.050  3400  3440 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-11 06:32:54.050  3400  3440 I bt_hci  : start_up
,08-11 06:32:54.059  3400  3440 I bt_vendor: alloc value 0xb39e5189
08-11 06:32:54.059  3400  3440 I bt_vendor: init
08-11 06:32:54.060  3400  3440 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-11 06:32:54.060  3400  3440 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-11 06:32:54.167  3400  3440 D bt_hci  : start_up starting async portion
,08-11 06:32:54.167  3400  3447 I bt_hci  : event_finish_startup
,08-11 06:32:54.168  3400  3447 I bt_hci_h4: hal_open
08-11 06:32:54.168  3400  3447 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-11 06:32:54.174  3400  3447 I bt_userial_vendor: device fd = 51 open
,08-11 06:32:54.208  3400  3447 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-11 06:32:54.240  3400  3447 D bt_hwcfg: Chipset BCM4354A2
,08-11 06:32:54.240  3400  3447 D bt_hwcfg: Target name = [BCM4354A2]
08-11 06:32:54.241  3400  3447 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-11 06:32:54.263  3332  3332 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 06:32:54.901  3400  3447 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-11 06:32:54.903  3400  3447 D bt_hwcfg: Settlement delay -- 100 ms
,08-11 06:32:54.903  3400  3447 I bt_hwcfg: Setting fw settlement delay to 100 
,08-11 06:32:55.020  3400  3447 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-11 06:32:55.021  3400  3447 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-11 06:32:55.051  3400  3447 I bt_hwcfg: vendor lib fwcfg completed
,08-11 06:32:55.051  3400  3447 I bt_vendor: firmware callback
08-11 06:32:55.051  3400  3447 I bt_hci  : firmware_config_callback
,08-11 06:32:55.062  3400  3449 I bt_btu  : btu_task pending for preload complete event
,08-11 06:32:55.063  3400  3449 I bt_btu_task: Bluetooth chip preload is complete
,08-11 06:32:55.063  3400  3449 I bt_btu  : btu_task received preload complete event
,08-11 06:32:55.074  3400  3449 I         : BTE_InitTraceLevels -- TRC_HCI
,08-11 06:32:55.074  3400  3449 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-11 06:32:55.074  3400  3449 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-11 06:32:55.075  3400  3449 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-11 06:32:55.075  3400  3449 I         : BTE_InitTraceLevels -- TRC_AVRC
08-11 06:32:55.075  3400  3449 I         : BTE_InitTraceLevels -- TRC_A2D
08-11 06:32:55.076  3400  3449 I         : BTE_InitTraceLevels -- TRC_BNEP
08-11 06:32:55.076  3400  3449 I         : BTE_InitTraceLevels -- TRC_BTM
08-11 06:32:55.076  3400  3449 I         : BTE_InitTraceLevels -- TRC_GAP
08-11 06:32:55.076  3400  3449 I         : BTE_InitTraceLevels -- TRC_PAN
08-11 06:32:55.077  3400  3449 I         : BTE_InitTraceLevels -- TRC_SDP
08-11 06:32:55.077  3400  3449 I         : BTE_InitTraceLevels -- TRC_GATT
08-11 06:32:55.077  3400  3449 I         : BTE_InitTraceLevels -- TRC_SMP
08-11 06:32:55.078  3400  3449 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-11 06:32:55.078  3400  3449 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-11 06:32:55.208  3400  3449 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3962d9d
,08-11 06:32:55.208  3400  3449 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3962d9d 
,08-11 06:32:55.220  3400  3443 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-11 06:32:55.221  3400  3443 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-11 06:32:55.222  3400  3443 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-11 06:32:55.225  3400  3443 D BluetoothAdapterProperties: Name is: Nexus 6
,08-11 06:32:55.229  3400  3443 D BluetoothAdapterProperties: Scan Mode:20
,08-11 06:32:55.230  3400  3443 D BluetoothAdapterProperties: Discoverable Timeout:120
08-11 06:32:55.230  3400  3443 D bt_hci  : do_postload posting postload work item
08-11 06:32:55.231  3400  3447 I bt_hci  : event_postload
08-11 06:32:55.231  3400  3447 I bt_vendor: sco_config_cb
08-11 06:32:55.231  3400  3447 I bt_hci  : sco_config_callback postload finished.
08-11 06:32:55.233  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 06:32:55.238  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 06:32:55.241  3400  3443 D bt_bte_conf: Device ID record 1 : primary,
08-11 06:32:55.241  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:32:55.241  3400  3443 D bt_bte_conf:   vendorId            = 000f
08-11 06:32:55.241  3400  3443 D bt_bte_conf:   vendorIdSource      = 0001
08-11 06:32:55.242  3400  3443 D bt_bte_conf:   product             = 1200
08-11 06:32:55.242  3400  3443 D bt_bte_conf:   version             = 1436
08-11 06:32:55.242  3400  3443 D bt_bte_conf:   clientExecutableURL = 
08-11 06:32:55.242  3400  3443 D bt_bte_conf:   serviceDescription  = 
08-11 06:32:55.243  3400  3443 D bt_bte_conf:   documentationURL    = 
08-11 06:32:55.243  3400  3443 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-11 06:32:55.243  3400  3440 D bt_stack_manager: event_start_up_stack finished
08-11 06:32:55.244  3400  3447 I bt_vendor: low_power_mode_cb
08-11 06:32:55.245  3400  3438 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-11 06:32:55.245  3400  3438 D BluetoothAdapterProperties: Setting state to 15
08-11 06:32:55.246  3400  3438 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-11 06:32:55.246  3400  3438 I BluetoothAdapterState: Entering BleOnState
,08-11 06:32:55.251  3400  3438 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-11 06:32:55.251  3400  3438 D BluetoothAdapterProperties: Setting state to 11
08-11 06:32:55.251  3400  3438 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-11 06:32:55.255  3400  3400 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f87c4
,08-11 06:32:55.256  3400  3400 D HeadsetService: Received start request. Starting profile...
,08-11 06:32:55.266  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-11 06:32:55.268  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 06:32:55.268  3400  3400 I BluetoothHeadsetServiceJni: classInitNative: succeeds,
08-11 06:32:55.269  3400  3400 D HeadsetStateMachine: make,
08-11 06:32:55.269  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 06:32:55.278   872   885 I ActivityManager: Start proc 3456:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-11 06:32:55.279  3400  3438 I BluetoothAdapterState: Entering PendingCommandState
,08-11 06:32:55.280  3400  3400 D HeadsetStateMachine: max_hf_connections = 1,
08-11 06:32:55.280  3400  3400 I bt_bluedroid: get_profile_interface handsfree
08-11 06:32:55.280  3400  3443 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-11 06:32:55.281  3400  3443 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-11 06:32:55.283  3400  3400 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f87c4
,08-11 06:32:55.284   872   872 D BluetoothA2dp: Proxy object connected
,08-11 06:32:55.284  3400  3400 D A2dpService: Received start request. Starting profile...
08-11 06:32:55.285  3400  3400 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-11 06:32:55.285  3400  3400 I bt_bluedroid: get_profile_interface avrcp
08-11 06:32:55.292  3400  3400 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController,
08-11 06:32:55.292  3400  3400 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-11 06:32:55.292  3400  3400 D A2dpStateMachine: make
,08-11 06:32:55.297  3400  3400 I bt_bluedroid: get_profile_interface a2dp
,08-11 06:32:55.298  3400  3443 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-11 06:32:55.302  3400  3400 I BluetoothHidServiceJni: classInitNative: succeeds
,08-11 06:32:55.302  3400  3466 D A2dpStateMachine: Enter Disconnected: -2
08-11 06:32:55.302  3400  3400 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f87c4
,08-11 06:32:55.304  1364  1364 D BluetoothInputDevice: Proxy object connected
08-11 06:32:55.304  3400  3400 D HidService: Received start request. Starting profile...
,08-11 06:32:55.304  3400  3400 I bt_bluedroid: get_profile_interface hidhost
08-11 06:32:55.304  3400  3400 D HidService: setHidService(): set to: null
08-11 06:32:55.304  1364  1364 D HidProfile: Bluetooth service connected
08-11 06:32:55.304  3400  3443 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39443e5
08-11 06:32:55.304  3400  3443 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-11 06:32:55.304  3400  3400 I BluetoothHealthServiceJni: classInitNative: succeeds
08-11 06:32:55.305  3400  3400 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f87c4
08-11 06:32:55.306  3400  3400 D HealthService: Received start request. Starting profile...
,08-11 06:32:55.307  3400  3400 I bt_bluedroid: get_profile_interface health
,08-11 06:32:55.308  3400  3400 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-11 06:32:55.309  3400  3400 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f87c4
,08-11 06:32:55.310  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
,08-11 06:32:55.310  3400  3400 D PanService: Received start request. Starting profile...
,08-11 06:32:55.310  3400  3400 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-11 06:32:55.310  3400  3400 I bt_bluedroid: get_profile_interface pan
,08-11 06:32:55.310  3400  3443 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-11 06:32:55.310  1364  1364 D PanProfile: Bluetooth service connected
,08-11 06:32:55.317  3400  3400 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f87c4
,08-11 06:32:55.318  1364  1364 D BluetoothMap: Proxy object connected
08-11 06:32:55.318  1364  1364 D MapProfile: Bluetooth service connected
,08-11 06:32:55.318  1364  1364 D BluetoothMap: getConnectedDevices(),
,08-11 06:32:55.319  1364  1364 D BluetoothMap: Bluetooth is Not enabled
,08-11 06:32:55.319  3400  3400 D BluetoothMapService: Received start request. Starting profile...
,08-11 06:32:55.319  3400  3400 D BluetoothMapService: start()
,08-11 06:32:55.321  3400  3400 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-11 06:32:55.321  3400  3400 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-11 06:32:55.321  3400  3400 D BluetoothMapAppObserver: createReceiver()
08-11 06:32:55.322  3400  3400 D BluetoothMapAppObserver: initObservers()
,08-11 06:32:55.322  3400  3400 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-11 06:32:55.327  3400  3400 V BluetoothAdapterState: isTurningOff()=false
,08-11 06:32:55.327  3400  3400 V BluetoothAdapterState: isTurningOn()=true
08-11 06:32:55.327  3400  3400 V BluetoothAdapterState: isBleTurningOn()=false
08-11 06:32:55.327  3400  3400 V BluetoothAdapterState: isBleTurningOff()=false
08-11 06:32:55.329  3400  3455 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-11 06:32:55.329  3400  3400 V BluetoothAdapterState: isTurningOff()=false
,08-11 06:32:55.329  3400  3400 V BluetoothAdapterState: isTurningOn()=true
08-11 06:32:55.329  3400  3400 V BluetoothAdapterState: isBleTurningOn()=false
08-11 06:32:55.330  3400  3400 V BluetoothAdapterState: isBleTurningOff()=false
08-11 06:32:55.330  3400  3400 V BluetoothAdapterState: isTurningOff()=false
,08-11 06:32:55.330  3400  3400 V BluetoothAdapterState: isTurningOn()=true
08-11 06:32:55.330  3400  3400 V BluetoothAdapterState: isBleTurningOn()=false
08-11 06:32:55.330  3400  3400 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 06:32:55.330  3400  3400 V BluetoothAdapterState: isTurningOff()=false
08-11 06:32:55.330  3400  3400 V BluetoothAdapterState: isTurningOn()=true
08-11 06:32:55.330  3400  3400 V BluetoothAdapterState: isBleTurningOn()=false
08-11 06:32:55.330  3400  3400 V BluetoothAdapterState: isBleTurningOff()=false
08-11 06:32:55.330  3400  3400 V BluetoothAdapterState: isTurningOff()=false
,08-11 06:32:55.330  3400  3400 V BluetoothAdapterState: isTurningOn()=true
,08-11 06:32:55.330  3400  3400 V BluetoothAdapterState: isBleTurningOn()=false
08-11 06:32:55.330  3400  3400 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 06:32:55.330  3400  3400 V BluetoothAdapterState: isTurningOff()=false
,08-11 06:32:55.331  3400  3400 V BluetoothAdapterState: isTurningOn()=true
,08-11 06:32:55.331  3400  3400 V BluetoothAdapterState: isBleTurningOn()=false
08-11 06:32:55.331  3400  3400 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 06:32:55.331  3400  3438 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-11 06:32:55.331  3400  3438 D BluetoothAdapterProperties: ScanMode =  20
,08-11 06:32:55.331  3400  3438 D BluetoothAdapterProperties: State =  11
,08-11 06:32:55.331  3400  3438 D BluetoothAdapterProperties: Setting state to 12
,08-11 06:32:55.331  3400  3438 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-11 06:32:55.332  3400  3443 D BluetoothAdapterProperties: Scan Mode:21
,08-11 06:32:55.332  3400  3443 D BluetoothAdapterProperties: Discoverable Timeout:120
08-11 06:32:55.332  3400  3438 I BluetoothAdapterState: Entering OnState
08-11 06:32:55.332  1364  1376 D BluetoothPbap: onBluetoothStateChange: up=true
08-11 06:32:55.334  1364  2007 D BluetoothPan: onBluetoothStateChange on: true
08-11 06:32:55.334   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 06:32:55.334  3332  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-11 06:32:55.335  1364  1382 D BluetoothMap: onBluetoothStateChange: up=true
08-11 06:32:55.336   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-11 06:32:55.336   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 06:32:55.336   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 06:32:55.336  3332  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-11 06:32:55.337  1717  1732 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 06:32:55.338  1364  1376 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-11 06:32:55.339  3332  3332 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-11 06:32:55.340  3400  3400 D BluetoothMapService: onReceive
08-11 06:32:55.340  3400  3400 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-11 06:32:55.340  3400  3400 D BluetoothMapService: STATE_ON
08-11 06:32:55.340   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-11 06:32:55.343  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:32:55.343  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:32:55.343  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 06:32:55.343  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:32:55.343  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 06:32:55.343  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:32:55.343  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:32:55.343  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 06:32:55.343  1364  1667 D LocalBluetoothProfileManager: Adding local A2DP profile
08-11 06:32:55.345  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 06:32:55.347  3400  3400 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-11 06:32:55.347  3456  3456 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-11 06:32:55.347  3400  3400 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-11 06:32:55.348  1364  1667 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-11 06:32:55.348  1364  1364 D BluetoothA2dp: Proxy object connected
08-11 06:32:55.349  3400  3400 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 06:32:55.350  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:32:55.350  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:32:55.350  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 06:32:55.350  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:32:55.350  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 06:32:55.350  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:32:55.350  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:32:55.350  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 06:32:55.351  3400  3400 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 06:32:55.352  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 06:32:55.352  3400  3400 D ObexServerSockets: Succeed to create listening sockets 
,08-11 06:32:55.352  3400  3400 D ObexServerSockets0: startAccept()
08-11 06:32:55.352  3400  3400 D ObexServerSockets0: prepareForNewConnect()
08-11 06:32:55.354  3400  3400 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-11 06:32:55.354  3400  3400 D BluetoothSdpJni: SDP Create record success - handle: 0
08-11 06:32:55.355  3400  3477 D ObexServerSockets0: Accepting socket connection...
08-11 06:32:55.355  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:32:55.355  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:32:55.355  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 06:32:55.355  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:32:55.355  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 06:32:55.355  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:32:55.355  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:32:55.355  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 06:32:55.355  3400  3478 D ObexServerSockets0: Accepting socket connection...
,08-11 06:32:55.356  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 06:32:55.358  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:32:55.359  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:32:55.360  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:32:55.360  3400  3400 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-11 06:32:55.360  3400  3400 D ObexServerSockets0: prepareForNewConnect()
,08-11 06:32:55.363   872  1706 I ActivityManager: Killing 2841:com.google.android.gm/u0a78 (adj 15): empty #17
,08-11 06:32:55.404  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 06:32:55.419   872   882 I ActivityManager: Start proc 3479:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-11 06:32:55.436   872   889 D BluetoothHeadset: Proxy object connected
,08-11 06:32:55.437   872   889 D BluetoothHeadset: Proxy object connected
08-11 06:32:55.437   872   889 D BluetoothHeadset: Proxy object connected
08-11 06:32:55.438  1717  1733 D BluetoothHeadset: Proxy object connected
,08-11 06:32:55.459  1364  2007 D BluetoothHeadset: Proxy object connected
,08-11 06:32:55.459  1364  1364 D HeadsetProfile: Bluetooth service connected
,08-11 06:32:55.473  3479  3479 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-11 06:32:55.607  3479  3479 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 06:32:55.607  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at java.io.File.exists(File.java:361)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 06:32:55.607  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 06:32:55.621  3479  3479 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 06:32:55.621  3479  3479 D StrictMode: ,	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 06:32:55.621  3479  3479 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 06:32:55.621  3479  3479 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.r.e.b(PG:170)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 06:32:55.621  3479  3479 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.r.k.d(PG:583)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.r.e.b(PG:170)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 06:32:55.621  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 06:32:55.622  3479  3479 D StrictMode: StrictMode policy violation; ~duration=51 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at java.io.File.exists(File.java:361)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 06:32:55.622  3479  3479 D StrictMode: StrictMode policy violation; ~duration=51 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at java.io.File.exists(File.java:361)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 06:32:55.622  3479  3479 D StrictMode: StrictMode policy violation; ~duration=50 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 06:32:55.622  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 06:32:55.630  3456  3456 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-11 06:32:55.637   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c5cbcdf:true
,08-11 06:32:55.643  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 06:32:55.651  3456  3456 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-11 06:32:55.659  3456  3456 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-11 06:32:55.671  1364  1364 D BluetoothPbap: Proxy object connected
,08-11 06:32:55.671  1364  1364 D PbapServerProfile: Bluetooth service connected
,08-11 06:32:55.674  3456  3456 D LocalBluetoothProfileManager: Adding local MAP profile
,08-11 06:32:55.675  3456  3456 D BluetoothMap: Create BluetoothMap proxy object
,08-11 06:32:55.682  3456  3456 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-11 06:32:55.687  3400  3506 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 06:32:55.695  3456  3456 D DockEventReceiver: finishStartingService: stopping service
,08-11 06:32:55.696  3456  3456 D BluetoothA2dp: Proxy object connected
,08-11 06:32:55.700  3456  3456 D BluetoothInputDevice: Proxy object connected
08-11 06:32:55.700  3456  3456 D HidProfile: Bluetooth service connected
,08-11 06:32:55.701  3456  3456 D BluetoothPan: BluetoothPAN Proxy object connected
08-11 06:32:55.702  3456  3456 D PanProfile: Bluetooth service connected
08-11 06:32:55.702  3456  3456 D BluetoothMap: Proxy object connected
08-11 06:32:55.702  3456  3456 D MapProfile: Bluetooth service connected
,08-11 06:32:55.702  3456  3456 D BluetoothMap: getConnectedDevices()
08-11 06:32:55.704  3400  3512 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 06:32:55.704  3456  3456 D BluetoothPbap: Proxy object connected
,08-11 06:32:55.705  3400  3512 I BtOppRfcommListener: Accept thread started.
08-11 06:32:55.705  3456  3456 D PbapServerProfile: Bluetooth service connected
08-11 06:32:55.707   872  2016 I ActivityManager: Killing 3024:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-11 06:32:55.761  3456  3472 D BluetoothHeadset: Proxy object connected
,08-11 06:32:55.762  3456  3456 D HeadsetProfile: Bluetooth service connected
,08-11 06:32:55.911  3479  3497 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-11 06:32:55.932   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ffe2551:true
,08-11 06:32:58.844   872   882 D WifiService: setWifiEnabled: true pid=3332, uid=10000
,08-11 06:32:58.845   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled,
,08-11 06:32:58.859   872  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-11 06:32:58.876  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:32:58.876  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:32:58.876  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 06:32:58.876  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 06:32:58.876  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 06:32:58.876  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:32:58.876  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:32:58.876  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 06:32:58.881  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 06:32:58.887   872  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-11 06:32:58.888   872  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-11 06:32:58.889  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:32:58.889  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:32:58.889  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 06:32:58.889  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 06:32:58.889  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 06:32:58.889  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:32:58.889  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:32:58.889  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 06:32:58.889   872  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-11 06:32:58.890   872  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-11 06:32:58.890   872  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-11 06:32:58.890   872  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-11 06:32:58.890   872  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-11 06:32:58.891  1460  1460 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-11 06:32:58.894  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 06:32:58.899  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:32:58.899  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:32:58.899  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 06:32:58.899  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 06:32:58.899  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 06:32:58.899  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:32:58.899  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:32:58.899  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 06:32:58.902  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 06:32:58.963   872  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-11 06:32:58.963   370   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-11 06:32:58.963  1460  1460 E wpa_supplicant: PNO: In assoc process
,08-11 06:32:58.964   872  1308 E WifiStateMachine:  Fail to set up pno, want true now false
08-11 06:32:58.965   370   870 D CommandListener: Setting iface cfg
08-11 06:32:58.966   872  1308 E native  : do suspend true
,08-11 06:32:58.967   872  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '36 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 36 Failed to set address (No such device)'
,08-11 06:32:58.968   872  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-11 06:32:58.980   872  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 06:32:58.985   872  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-11 06:32:58.986   872  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-11 06:32:59.353  1460  1460 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-11 06:32:59.393  1460  1460 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-11 06:32:59.394  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-11 06:32:59.402   872  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 06:32:59.426   872  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-11 06:32:59.426   872  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-11 06:32:59.427   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-11 06:32:59.452   872  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 06:32:59.473   370   870 D CommandListener: Setting iface cfg
,08-11 06:32:59.492   872  1308 D WifiStateMachine: Start Dhcp Watchdog 1
,08-11 06:32:59.499   872  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-11 06:32:59.523   872  3523 D DhcpClient: Receive thread started
,08-11 06:32:59.610   872  1308 E native  : do suspend false
,08-11 06:32:59.636   872  3522 D DhcpClient: Broadcasting DHCPDISCOVER
,08-11 06:32:59.651   872  3523 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 124318, domain null
,08-11 06:32:59.653   872  3522 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 124318 seconds
,08-11 06:32:59.658   872  3522 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-11 06:32:59.672   872  3523 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-11 06:32:59.674   872  3522 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-11 06:32:59.679   370   870 D CommandListener: Setting iface cfg
,08-11 06:32:59.690   872  3522 D DhcpClient: Scheduling renewal in 86399s
,08-11 06:32:59.690   872  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-11 06:32:59.694   872  1308 E native  : do suspend true
,08-11 06:32:59.718   872  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-11 06:32:59.720   872  1308 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-11 06:32:59.721   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-11 06:32:59.727   872  1310 D ConnectivityService: Adding iface wlan0 to network 100
,08-11 06:32:59.736   872  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-11 06:32:59.798   872  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-11 06:32:59.799   872  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,08-11 06:32:59.801   872  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,08-11 06:32:59.803   872  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,08-11 06:32:59.805   872  1310 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,08-11 06:32:59.822   872  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-11 06:32:59.837   872  1310 D ConnectivityService: scheduleUnvalidatedPrompt 100
08-11 06:32:59.838   872  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
,08-11 06:32:59.839   872  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-11 06:32:59.841   872  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-11 06:32:59.842   872  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
,08-11 06:32:59.842   872  1310 D ConnectivityService:    accepting network in place of null
,08-11 06:32:59.845   872  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-11 06:32:59.849   872  3521 D NetlinkSocketObserver: NeighborEvent{elapsedMs=173992, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 06:32:59.920   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 06:32:59.921   872  3520 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=89.25.215.93,2a00:1450:400d:802::200e
,08-11 06:32:59.961   872  3520 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 11 Aug 2016 04:33:00 GMT], X-Android-Received-Millis=[1470889979958], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470889979949]}
,08-11 06:32:59.973   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 06:32:59.976   872  1310 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,08-11 06:32:59.988   872  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-11 06:32:59.989   872  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-11 06:33:00.004   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-11 06:33:00.008   872  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,08-11 06:33:00.009   872  1413 V BackupManagerService: Scheduling immediate backup pass
08-11 06:33:00.010   872   872 V BackupManagerService: Running a backup pass
,08-11 06:33:00.012   872  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-11 06:33:00.013   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
08-11 06:33:00.013   872  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-11 06:33:00.017   872  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-11 06:33:00.017   872  1331 V BackupManagerService: clearing pending backups
08-11 06:33:00.021   872  1331 V PerformBackupTask: Beginning backup of 16 targets
08-11 06:33:00.024  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:33:00.024  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:33:00.024  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 06:33:00.024  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 06:33:00.024  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 06:33:00.024  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 06:33:00.024  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 06:33:00.024  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 06:33:00.034  1805  1805 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-11 06:33:00.046   872  1331 D PerformBackupTask: invokeAgentForBackup on @pm@
,08-11 06:33:00.047  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 06:33:00.052  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:33:00.052  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:33:00.052  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 06:33:00.052  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 06:33:00.052  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 06:33:00.052  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 06:33:00.052  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 06:33:00.052  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 06:33:00.057  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 06:33:00.063  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:33:00.063  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:33:00.063  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 06:33:00.063  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 06:33:00.063  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 06:33:00.063  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 06:33:00.063  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,08-11 06:33:00.063  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 06:33:00.063  1863  1863 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-11 06:33:00.065  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 06:33:00.066  1863  1863 D SystemUpdateService: onCreate
08-11 06:33:00.070   872  1331 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
,08-11 06:33:00.070  1863  1863 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-11 06:33:00.071   872  1684 D AlarmManagerService: Setting time of day to sec=1470889980
08-11 06:33:00.063   872  1684 W AlarmManagerService: Unable to set rtc to 1470889980: Invalid argument
08-11 06:33:00.065  1863  3541 I SystemUpdateService: active receiver: enabled
,08-11 06:33:00.074  1863  3540 I CheckinService: Checking schedule, now: 1470889980074 next: 1470848053564
,08-11 06:33:00.074  1863  3540 I CheckinService: active receiver: enabled
08-11 06:33:00.074  1863  3541 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-11 06:33:00.076  1863  3540 I CheckinService: Preparing to send checkin request
08-11 06:33:00.076  1863  3540 I EventLogService: Accumulating logs since 1470889713210
08-11 06:33:00.076  1863  3541 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-11 06:33:00.076  1863  3541 I SystemUpdateService: now status is 0 (complete)
08-11 06:33:00.076  1863  3541 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-11 06:33:00.077  1863  3541 I SystemUpdateService: file has been verified
08-11 06:33:00.077  1863  3541 I SystemUpdateService: OTA package size = 12249756
08-11 06:33:00.080  1863  3541 I SystemUpdateService: showing system update notification
,08-11 06:33:00.109  1863  1863 D SystemUpdateService: onDestroy
08-11 06:33:00.111  1863  3540 I EventLogService: Opted in for usage reporting
,08-11 06:33:00.114   872  3549 D GpsLocationProvider: NTP server returned: 1470889980497 (Thu Aug 11 06:33:00 GMT+02:00 2016) reference: 174216 certainty: 7 system time offset: 383
,08-11 06:33:00.114   872  3549 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,08-11 06:33:00.120   872  1331 I BackupRestoreController: Getting widget state for user: 0
,08-11 06:33:00.125   872  1725 I ActivityManager: Start proc 3551:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-11 06:33:00.144  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-11 06:33:00.148  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:33:00.178  1863  3567 I iu.SyncManager: SYNC; picasa accounts
,08-11 06:33:00.183  3551  3551 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
08-11 06:33:00.183  1863  1863 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-11 06:33:00.185  1863  1863 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-11 06:33:00.189  3412  3545 V GoogleAuthProtoRequest: [283] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 06:33:00.192  1863  3567 I iu.UploadsManager: num queued entries: 0
,08-11 06:33:00.193  1863  3567 I iu.UploadsManager: num updated entries: 0
,08-11 06:33:00.195  1863  1863 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-11 06:33:00.196  1863  1863 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-11 06:33:00.197  1863  3566 I MDM     : [186] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-11 06:33:00.197  1863  3566 W BaseAppContext: Using Auth Proxy for data requests.
,08-11 06:33:00.199  1863  3567 I iu.SyncManager: NEXT; no task
,08-11 06:33:00.207   872  2016 I ActivityManager: Start proc 3570:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-11 06:33:00.219  1863  3566 V GoogleAuthProtoRequest: [186] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 06:33:00.230  1821  1832 W GmsBackupTransport: Unknown package in backup request: @pm@
,08-11 06:33:00.231  1821  1832 V GmsBackupTransport: starting performBackup for @pm@
,08-11 06:33:00.235  1821  1832 V GmsBackupTransport: performBackup done for @pm@
,08-11 06:33:00.244  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:33:00.245  1863  3550 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,08-11 06:33:00.247  1863  3540 W EventLogAggregator: Unknown tag: snet_gcore
,08-11 06:33:00.248  1863  3540 W EventLogAggregator: Unknown tag: snet_launch_service
,08-11 06:33:00.251  3570  3570 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-11 06:33:00.261  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
,08-11 06:33:00.261  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
08-11 06:33:00.261  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 06:33:00.261  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 06:33:00.271  1499  1510 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-11 06:33:00.271  1499  1510 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 06:33:00.271  1499  1510 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 06:33:00.271  1499  1510 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-11 06:33:00.271  1499  1510 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-11 06:33:00.271  1499  1510 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-11 06:33:00.271  1499  1510 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-11 06:33:00.253  3570  3570 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-11 06:33:00.274  1821  2046 W GmsBackupTransport: Error sending final backup to server: 
08-11 06:33:00.274  1821  2046 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
08-11 06:33:00.274  1821  2046 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
08-11 06:33:00.274  1821  2046 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
08-11 06:33:00.274  1821  2046 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
08-11 06:33:00.274  1821  2046 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
08-11 06:33:00.274  1821  2046 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
08-11 06:33:00.274  1821  2046 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
08-11 06:33:00.274  1821  2046 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-11 06:33:00.274  1821  2046 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-11 06:33:00.274  1821  2046 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-11 06:33:00.274  1821  2046 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-11 06:33:00.274  1821  2046 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-11 06:33:00.274  1821  2046 W GmsBackupTransport: 	... 1 more
,08-11 06:33:00.275  1821  2256 I GmsBackupTransport: Next backup will happen in 43199997 millis.
08-11 06:33:00.275   872  1331 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
,08-11 06:33:00.268  1863  3540 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,08-11 06:33:00.278  1499  1904 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-11 06:33:00.278  1499  1904 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-11 06:33:00.279  1499  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-11 06:33:00.279  1499  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-11 06:33:00.279  1499  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 06:33:00.279  1499  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 06:33:00.283  1499  1904 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 06:33:00.283  1499  1904 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 06:33:00.287   872  1309 D WifiService: New client listening to asynchronous messages
,08-11 06:33:00.290  1863  3540 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,08-11 06:33:00.299  3412  3545 W ExperimentUpdateService: [283] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-11 06:33:00.299  3412  3545 W ExperimentUpdateService: [283] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 06:33:00.299  3412  3545 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 06:33:00.299  3412  3545 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-11 06:33:00.299  3412  3545 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-11 06:33:00.299  3412  3545 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-11 06:33:00.299  3412  3545 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-11 06:33:00.299  3412  3545 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-11 06:33:00.299  3412  3545 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-11 06:33:00.299  3412  3545 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-11 06:33:00.299  3412  3545 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-11 06:33:00.299  3412  3545 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-11 06:33:00.301  3570  3570 D SprintDMHelper: simOperator: 
,08-11 06:33:00.306  3570  3570 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-11 06:33:00.324   872  1738 I ActivityManager: Start proc 3588:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-11 06:33:00.352  1863  3566 E MDM     : [186] SitrepService.a: Error sending sitrep.
,08-11 06:33:00.375   872  1331 I BackupManagerService: Backup pass finished.
,08-11 06:33:00.383   872  1703 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1863 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-11 06:33:00.392  1499  1499 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-11 06:33:00.501  1499  1904 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,08-11 06:33:00.501  1499  1904 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> AndroidCheckInServer without consulting the cloud.
08-11 06:33:00.501  1499  1904 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 06:33:00.501  1499  1904 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 06:33:00.528  3551  3584 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-11 06:33:00.550   872   884 I ActivityManager: Start proc 3614:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-11 06:33:00.567  3614  3614 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-11 06:33:00.589  1499  2048 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 06:33:00.589  1499  2048 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 06:33:00.589  1499  2048 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 06:33:00.590  1499  2048 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 06:33:00.599  1863  3540 W CheckinRequestBuilder: awaiting user notification for token
,08-11 06:33:00.614  1863  3563 W DriveInitializer: Awaiting to be initialized
,08-11 06:33:00.614  1863  3628 W DriveInitializer: Background init thread started
,08-11 06:33:00.618  3137  3576 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 06:33:00.618  3137  3576 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 06:33:00.618  3137  3576 E HttpOperation: 	at jdm.a(PG:82)
08-11 06:33:00.618  3137  3576 E HttpOperation: 	at jcs.o(PG:406)
08-11 06:33:00.618  3137  3576 E HttpOperation: 	at jcn.a(PG:1379)
08-11 06:33:00.618  3137  3576 E HttpOperation: 	at jcs.i(PG:143)
08-11 06:33:00.618  3137  3576 E HttpOperation: 	at blb.a(PG:3937)
08-11 06:33:00.618  3137  3576 E HttpOperation: 	at czp.a(PG:18188)
08-11 06:33:00.618  3137  3576 E HttpOperation: 	at czp.a(PG:9081)
08-11 06:33:00.618  3137  3576 E HttpOperation: 	at czq.run(PG:1686)
08-11 06:33:00.618  3137  3576 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 06:33:00.618  3137  3576 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 06:33:00.618  3137  3576 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 06:33:00.618  3137  3576 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 06:33:00.618  3137  3576 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 06:33:00.618  3137  3576 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 06:33:00.618  3137  3576 E HttpOperation: 	at jdj.a(PG:4091)
08-11 06:33:00.618  3137  3576 E HttpOperation: 	at jdj.a(PG:1125)
08-11 06:33:00.618  3137  3576 E HttpOperation: 	at jdm.a(PG:77)
08-11 06:33:00.618  3137  3576 E HttpOperation: 	... 12 more
08-11 06:33:00.618  3137  3576 E HttpOperation: Caused by: faj: BadAuthentication
08-11 06:33:00.618  3137  3576 E HttpOperation: 	at fal.a(PG:38)
08-11 06:33:00.618  3137  3576 E HttpOperation: 	at jdj.a(PG:4089)
08-11 06:33:00.618  3137  3576 E HttpOperation: 	... 14 more
,08-11 06:33:00.642   872   883 I ActivityManager: Start proc 3630:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,08-11 06:33:00.698  3630  3630 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-11 06:33:00.711  1499  2048 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 06:33:00.712  1499  2048 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-11 06:33:00.712  1499  2048 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 06:33:00.712  1499  2048 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-11 06:33:00.724  3630  3630 I MultiDex: VM with version 2.1.0 has multidex support
,08-11 06:33:00.724  3630  3630 I MultiDex: install
,08-11 06:33:00.724  3630  3630 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-11 06:33:00.734  1863  3628 W DriveInitializer: Background init thread ended
,08-11 06:33:00.735  3137  3576 E HttpOperation: [getmobileexperiments] Unexpected exception
08-11 06:33:00.735  3137  3576 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 06:33:00.735  3137  3576 E HttpOperation: 	at jdm.a(PG:82)
08-11 06:33:00.735  3137  3576 E HttpOperation: 	at jcs.o(PG:406)
08-11 06:33:00.735  3137  3576 E HttpOperation: 	at jcn.a(PG:1379)
08-11 06:33:00.735  3137  3576 E HttpOperation: 	at jcs.i(PG:143)
08-11 06:33:00.735  3137  3576 E HttpOperation: 	at hec.a(PG:42)
08-11 06:33:00.735  3137  3576 E HttpOperation: 	at hee.a(PG:102)
08-11 06:33:00.735  3137  3576 E HttpOperation: 	at czr.a(PG:65)
08-11 06:33:00.735  3137  3576 E HttpOperation: 	at kka.a(PG:108)
08-11 06:33:00.735  3137  3576 E HttpOperation: 	at czp.a(PG:19176)
08-11 06:33:00.735  3137  3576 E HttpOperation: 	at czp.a(PG:9081)
08-11 06:33:00.735  3137  3576 E HttpOperation: 	at czq.run(PG:1686)
08-11 06:33:00.735  3137  3576 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 06:33:00.735  3137  3576 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 06:33:00.735  3137  3576 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 06:33:00.735  3137  3576 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 06:33:00.735  3137  3576 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 06:33:00.735  3137  3576 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 06:33:00.735  3137  3576 E HttpOperation: 	at jdj.a(PG:4091)
08-11 06:33:00.735  3137  3576 E HttpOperation: 	at jdj.a(PG:1125)
08-11 06:33:00.735  3137  3576 E HttpOperation: 	at jdm.a(PG:77)
08-11 06:33:00.735  3137  3576 E HttpOperation: 	... 15 more
08-11 06:33:00.735  3137  3576 E HttpOperation: Caused by: faj: BadAuthentication
08-11 06:33:00.735  3137  3576 E HttpOperation: 	at fal.a(PG:38)
08-11 06:33:00.735  3137  3576 E HttpOperation: 	at jdj.a(PG:4089)
08-11 06:33:00.735  3137  3576 E HttpOperation: 	... 17 more
,08-11 06:33:00.735  3137  3576 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 06:33:00.735  3137  3576 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 06:33:00.735  3137  3576 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 06:33:00.735  3137  3576 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 06:33:00.735  3137  3576 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 06:33:00.735  3137  3576 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 06:33:00.735  3137  3576 E ExperimentLoader: 	at hec.a(PG:42)
08-11 06:33:00.735  3137  3576 E ExperimentLoader: 	at hee.a(PG:102)
08-11 06:33:00.735  3137  3576 E ExperimentLoader: 	at czr.a(PG:65)
08-11 06:33:00.735  3137  3576 E ExperimentLoader: 	at kka.a(PG:108)
08-11 06:33:00.735  3137  3576 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 06:33:00.735  3137  3576 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 06:33:00.735  3137  3576 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 06:33:00.735  3137  3576 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 06:33:00.735  3137  3576 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 06:33:00.735  3137  3576 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 06:33:00.735  3137  3576 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 06:33:00.735  3137  3576 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-11 06:33:00.735  3137  3576 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 06:33:00.735  3137  3576 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 06:33:00.735  3137  3576 E ExperimentLoader: 	at jdj.a(PG:1125)
08-11 06:33:00.735  3137  3576 E ExperimentLoader: 	at jdm.a(PG:77)
08-11 06:33:00.735  3137  3576 E ExperimentLoader: 	... 15 more
08-11 06:33:00.735  3137  3576 E ExperimentLoader: Caused by: faj: BadAuthentication
08-11 06:33:00.735  3137  3576 E ExperimentLoader: 	at fal.a(PG:38)
08-11 06:33:00.735  3137  3576 E ExperimentLoader: 	at jdj.a(PG:4089)
08-11 06:33:00.735  3137  3576 E ExperimentLoader: 	... 17 more
08-11 06:33:00.761  1499  3607 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,08-11 06:33:00.796  3630  3630 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-11 06:33:00.811  3614  3614 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-11 06:33:00.819  3614  3614 I BooksApp: Created application version: 3.6.9 (30609)
,08-11 06:33:00.843  3630  3630 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-11 06:33:00.876  3551  3584 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-11 06:33:00.888  3630  3668 D NativeLibraryUtils: Install completed successfully. count=13 extracted=0
08-11 06:33:00.890   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 23368, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
08-11 06:33:00.902  3551  3584 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-11 06:33:00.942   374  1316 D WVCdm   : Instantiating CDM.
,08-11 06:33:00.943   374  1277 I WVCdm   : CdmEngine::OpenSession
08-11 06:33:00.943   374  1277 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,08-11 06:33:00.946   374  1277 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-11 06:33:00.950   374  1277 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x20
,08-11 06:33:00.950   374  1277 D DrmWidevineDash: Service_Initialize: starts!
08-11 06:33:00.950   374  1277 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-11 06:33:00.950   374  1277 D QSEECOMAPI: : App is not loaded in QSEE
,08-11 06:33:00.964  3630  3643 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-11 06:33:00.976   872  1725 I ActivityManager: Start proc 3678:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
08-11 06:33:01.003  3551  3551 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-11 06:33:01.006  3614  3667 I BooksSync: Starting books sync for 61035162, extras: ade
,08-11 06:33:01.026  3678  3678 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-11 06:33:01.044  2354  3676 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-11 06:33:01.076  3677  3677 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads1946493458.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads1946493458.dex
,08-11 06:33:01.117  2871  3672 V KeepSync: Connecting to GoogleApiClient
,08-11 06:33:01.117   872   882 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-11 06:33:01.145  3677  3677 I dex2oat : dex2oat took 69.404ms (threads: 4) arena alloc=200KB java alloc=29KB native alloc=1385KB free=1430KB
,08-11 06:33:01.168   374  1277 D QSEECOMAPI: : Loaded image: APP id = 3
,08-11 06:33:01.169   374  1277 D DrmWidevineDash: Service_Initialize: ends! returns 0
,08-11 06:33:01.170   374  1277 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2be0000
08-11 06:33:01.170   374  1277 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2be0000
,08-11 06:33:01.176  3551  3551 W InstanceID/Rpc: Found 10011
,08-11 06:33:01.177   338   343 D DrmLibTime: got the req here! ret=0
08-11 06:33:01.177   338   343 D DrmLibTime: command id, time_cmd_id = 770
08-11 06:33:01.177   338   343 D DrmLibTime: time_getutcsec starts!
08-11 06:33:01.177   338   343 D DrmLibTime: QSEE Time Listener: time_getutcsec
08-11 06:33:01.177   338   343 D DrmLibTime: QSEE Time Listener: get_utc_seconds
,08-11 06:33:01.177   338   343 D DrmLibTime: QSEE Time Listener: seconds: 1470889981
08-11 06:33:01.177   338   343 D DrmLibTime: QSEE Time Listener: nano seconds: 177226673
08-11 06:33:01.177   338   343 D DrmLibTime: time_getutcsec returns 0, sec = 1470889981; nsec = 177226673
08-11 06:33:01.177   338   343 D DrmLibTime: time_getutcsec finished! 
08-11 06:33:01.177   338   343 D DrmLibTime: iotcl_continue_command finished! and return 0 
,08-11 06:33:01.177   338   343 D DrmLibTime: before calling ioctl to read the next time_cmd
,08-11 06:33:01.189   374  1277 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,08-11 06:33:01.189   374  1277 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-11 06:33:01.190   374  1277 D DrmWidevineDash: hlos api version =  10
08-11 06:33:01.190   374  1277 D DrmWidevineDash: tz api version =  10
08-11 06:33:01.190   374  1277 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
08-11 06:33:01.190   374  1277 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
08-11 06:33:01.193  1499  1904 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-11 06:33:01.193  1499  1904 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-11 06:33:01.193  1499  1904 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 06:33:01.193  1499  1904 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 06:33:01.217   374  1277 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,08-11 06:33:01.217   374  1277 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-11 06:33:01.217   374  1277 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb2f41134
08-11 06:33:01.217   374  1277 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
,08-11 06:33:01.217   374  1277 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
,08-11 06:33:01.217   374  1277 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb466d388, dataLength=8
08-11 06:33:01.218   374  1277 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-11 06:33:01.222   374  1277 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb2c77c00, wrapped_rsa_key_length=1280
,08-11 06:33:01.225   374  1277 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,08-11 06:33:01.225   374  1277 I WVCdm   : CdmEngine::QueryKeyControlInfo
08-11 06:33:01.226   374  3344 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-11 06:33:01.226   374  3344 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
,08-11 06:33:01.226   374  3344 I WVCdm   : CdmEngine::GenerateKeyRequest
08-11 06:33:01.226   374  3344 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb464f6e0, idLength=0xb18bff2c
,08-11 06:33:01.238   374  3344 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,08-11 06:33:01.238   374  3344 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,08-11 06:33:01.238   374  3344 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,08-11 06:33:01.238   374  3344 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
08-11 06:33:01.238   374  3344 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
08-11 06:33:01.238   374  3344 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
08-11 06:33:01.239   374  3344 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
08-11 06:33:01.239   374  3344 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-11 06:33:01.240   374  3344 D DrmWidevineDash: hlos api version =  10
,08-11 06:33:01.240   374  3344 D DrmWidevineDash: tz api version =  10
08-11 06:33:01.240   374  3344 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
,08-11 06:33:01.240   374  3344 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,08-11 06:33:01.241   374  3344 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
08-11 06:33:01.241   374  3344 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
08-11 06:33:01.241   374  3344 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,08-11 06:33:01.242   374  3344 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-11 06:33:01.242   374  3344 D WVCdm   : PrepareKeyRequest: nonce=1193531043
08-11 06:33:01.242   374  3344 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1b08000
08-11 06:33:01.242   374  3344 D DrmWidevineDash: message_length=1624, signature=0xb3ac9a00, signature_length=2978742276
,08-11 06:33:01.258  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:33:01.271  1863  3727 V BaseAuthAsyncOperation: access token request failed
,08-11 06:33:01.275  2871  3672 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-11 06:33:01.286  1499  2659 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,08-11 06:33:01.286  1499  2659 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud.
,08-11 06:33:01.286  1499  2659 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 06:33:01.286  1499  2659 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 06:33:01.296  1863  3749 E Ads     : [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ae: BadAuthentication
,08-11 06:33:01.313   374  3344 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-11 06:33:01.314   374   374 I WVCdm   : CdmEngine::CloseSession
08-11 06:33:01.314   374   374 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
08-11 06:33:01.315   374   374 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-11 06:33:01.315   374   374 D DrmWidevineDash: OEMCrypto_Terminate: starts!
08-11 06:33:01.315   374   374 D DrmWidevineDash: Service_Uninitialize: starts!
08-11 06:33:01.315   374   374 D QSEECOMAPI: : QSEECom_dealloc_memory 
,08-11 06:33:01.315   374   374 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
08-11 06:33:01.316   374   374 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
08-11 06:33:01.316   374   374 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-11 06:33:01.407  3678  3678 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-11 06:33:01.407  3678  3678 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-11 06:33:01.407  3678  3678 I GAv4    :   adb logcat -s GAv4
,08-11 06:33:01.426  3678  3678 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-11 06:33:01.444  3678  3678 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-11 06:33:01.497   374  1316 I WVCdm   : CdmEngine::OpenSession
08-11 06:33:01.497   374  1316 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,08-11 06:33:01.503   374  1316 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-11 06:33:01.507   374  1316 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x20
08-11 06:33:01.507   374  1316 D DrmWidevineDash: Service_Initialize: starts!
08-11 06:33:01.507   374  1316 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-11 06:33:01.508   374  1316 D QSEECOMAPI: : App is not loaded in QSEE
,08-11 06:33:01.511  3678  3765 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-11 06:33:01.586  3614  3772 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-11 06:33:01.669  1499  2657 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 06:33:01.669  1499  2657 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 06:33:01.669  1499  2657 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 06:33:01.669  1499  2657 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 06:33:01.700  1499  2659 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 06:33:01.700  1499  2659 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.,
,08-11 06:33:01.700  1499  2659 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 06:33:01.700  1499  2659 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 06:33:01.713  3614  3772 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-11 06:33:01.715  3614  3667 E BooksSync: Soft error
08-11 06:33:01.715  3614  3667 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 06:33:01.715  3614  3667 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-11 06:33:01.715  3614  3667 E BooksSync: Sync error,
08-11 06:33:01.715  3614  3667 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 06:33:01.715  3614  3667 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-11 06:33:01.718  3614  3667 I BooksSync: Finished books sync
,08-11 06:33:01.723   872  1413 I ActivityManager: Killing 2463:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-11 06:33:01.724   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 23376, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 06:33:01.759  3678  3678 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-11 06:33:01.769   374  1316 D QSEECOMAPI: : Loaded image: APP id = 3
,08-11 06:33:01.770   374  1316 D DrmWidevineDash: Service_Initialize: ends! returns 0
,08-11 06:33:01.771   374  1316 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2be0000
,08-11 06:33:01.771   374  1316 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2be0000
,08-11 06:33:01.776   338   343 D DrmLibTime: got the req here! ret=0
,08-11 06:33:01.777   338   343 D DrmLibTime: command id, time_cmd_id = 770
,08-11 06:33:01.777   338   343 D DrmLibTime: time_getutcsec starts!
,08-11 06:33:01.777   338   343 D DrmLibTime: QSEE Time Listener: time_getutcsec
,08-11 06:33:01.777   338   343 D DrmLibTime: QSEE Time Listener: get_utc_seconds
,08-11 06:33:01.777   338   343 D DrmLibTime: QSEE Time Listener: seconds: 1470889981
,08-11 06:33:01.777   338   343 D DrmLibTime: QSEE Time Listener: nano seconds: 777492670
,08-11 06:33:01.777   338   343 D DrmLibTime: time_getutcsec returns 0, sec = 1470889981; nsec = 777492670
,08-11 06:33:01.777   338   343 D DrmLibTime: time_getutcsec finished! 
,08-11 06:33:01.778   338   343 D DrmLibTime: iotcl_continue_command finished! and return 0 
08-11 06:33:01.778   338   343 D DrmLibTime: before calling ioctl to read the next time_cmd
,08-11 06:33:01.784   374  1316 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
08-11 06:33:01.785   374  1316 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-11 06:33:01.785   374  1316 D DrmWidevineDash: hlos api version =  10
08-11 06:33:01.785   374  1316 D DrmWidevineDash: tz api version =  10
08-11 06:33:01.785   374  1316 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
,08-11 06:33:01.786   374  1316 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,08-11 06:33:01.797   374  1316 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,08-11 06:33:01.797   374  1316 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
,08-11 06:33:01.797   374  1316 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb2e42134
08-11 06:33:01.798   374  1316 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-11 06:33:01.798   374  1316 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
,08-11 06:33:01.798   374  1316 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb608d6c8, dataLength=8
,08-11 06:33:01.799   374  1316 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
08-11 06:33:01.799   374  1316 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb60be200, wrapped_rsa_key_length=1280
,08-11 06:33:01.802   374  1316 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,08-11 06:33:01.802   374  1316 I WVCdm   : CdmEngine::QueryKeyControlInfo
08-11 06:33:01.803   374   374 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-11 06:33:01.803   374   374 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
08-11 06:33:01.803   374   374 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-11 06:33:01.804   374   374 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb3368b20, idLength=0xbeea400c
,08-11 06:33:01.815  3678  3678 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-11 06:33:01.817   374   374 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,08-11 06:33:01.817   374   374 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
08-11 06:33:01.818   374   374 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,08-11 06:33:01.818   374   374 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
,08-11 06:33:01.818   374   374 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
08-11 06:33:01.818   374   374 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,08-11 06:33:01.819   374   374 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
,08-11 06:33:01.819   374   374 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,08-11 06:33:01.819   374   374 D DrmWidevineDash: hlos api version =  10
,08-11 06:33:01.819   374   374 D DrmWidevineDash: tz api version =  10
08-11 06:33:01.819   374   374 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
,08-11 06:33:01.819   374   374 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
08-11 06:33:01.820   374   374 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,08-11 06:33:01.820   374   374 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
08-11 06:33:01.820   374   374 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,08-11 06:33:01.821   374   374 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-11 06:33:01.821   374   374 D WVCdm   : PrepareKeyRequest: nonce=2018550567
,08-11 06:33:01.821   374   374 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1b08700
08-11 06:33:01.821   374   374 D DrmWidevineDash: message_length=1655, signature=0xb60b7380, signature_length=3203023076
08-11 06:33:01.823  3678  3678 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5975-5978)
,08-11 06:33:01.823  3678  3678 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-11 06:33:01.844  3678  3678 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4bb1c4c}
08-11 06:33:01.844  3678  3678 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 06:33:01.845  3678  3678 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-11 06:33:01.850  3678  3678 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-11 06:33:01.851  3678  3678 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-11 06:33:01.872  3678  3678 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-11 06:33:01.888  3678  3678 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-11 06:33:01.888  3678  3678 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 06:33:01.888  3678  3678 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 06:33:01.888  3678  3678 I Adreno  : Build Date                       : 10/20/15
08-11 06:33:01.888  3678  3678 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 06:33:01.888  3678  3678 I Adreno  : Local Branch                     : M14
08-11 06:33:01.888  3678  3678 I Adreno  : Remote Branch                    : 
08-11 06:33:01.888  3678  3678 I Adreno  : Remote Branch                    : 
08-11 06:33:01.888  3678  3678 I Adreno  : Reconstruct Branch               : 
,08-11 06:33:01.899   374   374 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-11 06:33:01.899   374  3344 I WVCdm   : CdmEngine::CloseSession
08-11 06:33:01.899   374  3344 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,08-11 06:33:01.900   374  3344 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-11 06:33:01.900   374  3344 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,08-11 06:33:01.901   374  3344 D DrmWidevineDash: Service_Uninitialize: starts!
08-11 06:33:01.901   374  3344 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-11 06:33:01.901   374  3344 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
,08-11 06:33:01.901   374  3344 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
08-11 06:33:01.901   374  3344 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-11 06:33:01.924  1499  2657 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-11 06:33:01.924  1499  2657 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-11 06:33:01.924  1499  2657 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 06:33:01.924  1499  2657 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 06:33:01.952  2871  3672 E KeepSync: IOException
08-11 06:33:01.952  2871  3672 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-11 06:33:01.952  2871  3672 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-11 06:33:01.952  2871  3672 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-11 06:33:01.952  2871  3672 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-11 06:33:01.952  2871  3672 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-11 06:33:01.952  2871  3672 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-11 06:33:01.952  2871  3672 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-11 06:33:01.952  2871  3672 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-11 06:33:01.952  2871  3672 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-11 06:33:01.952  2871  3672 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-11 06:33:01.952  2871  3672 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-11 06:33:01.952  2871  3672 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-11 06:33:01.952  2871  3672 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-11 06:33:01.952  2871  3672 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-11 06:33:01.952  2871  3672 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 06:33:01.952  2871  3672 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 06:33:01.952  2871  3672 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-11 06:33:01.952  2871  3672 E KeepSync: 	... 10 more
,08-11 06:33:01.953  2871  3672 W KeepSync: Sync result 2
,08-11 06:33:01.959   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 23377, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
08-11 06:33:01.960   872  1706 I ActivityManager: Killing 2747:android.process.acore/u0a5 (adj 15): empty #17
,08-11 06:33:01.981  3799  3799 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,08-11 06:33:01.983  3678  3808 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-11 06:33:02.012  3799  3799 I dex2oat : dex2oat took 31.811ms (threads: 4) arena alloc=144KB java alloc=71KB native alloc=1535KB free=1536KB
,08-11 06:33:02.016  3630  3643 W System  : ClassLoader referenced unknown path: 
,08-11 06:33:02.016  3678  3678 I NSApplication: Starting up...
,08-11 06:33:02.032  3630  3643 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 06:33:02.032  3630  3643 I Adreno  : Build Date                       : 10/20/15
08-11 06:33:02.032  3630  3643 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 06:33:02.032  3630  3643 I Adreno  : Local Branch                     : M14
08-11 06:33:02.032  3630  3643 I Adreno  : Remote Branch                    : 
08-11 06:33:02.032  3630  3643 I Adreno  : Remote Branch                    : 
08-11 06:33:02.032  3630  3643 I Adreno  : Reconstruct Branch               : 
,08-11 06:33:02.033   872  1375 I ActivityManager: Start proc 3817:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-11 06:33:02.034   872  1375 I ActivityManager: Killing 3219:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-11 06:33:02.101  3817  3817 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-11 06:33:02.114  3630  3643 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 06:33:02.114  3630  3643 I Adreno  : Build Date                       : 10/20/15
08-11 06:33:02.114  3630  3643 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 06:33:02.114  3630  3643 I Adreno  : Local Branch                     : M14
08-11 06:33:02.114  3630  3643 I Adreno  : Remote Branch                    : 
08-11 06:33:02.114  3630  3643 I Adreno  : Remote Branch                    : 
08-11 06:33:02.114  3630  3643 I Adreno  : Reconstruct Branch               : 
,08-11 06:33:02.203  3643  3643 W Binder_2: type=1400 audit(0.0:8): avc: denied { read } for name="/" dev="tmpfs" ino=10241 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:device:s0 tclass=dir permissive=0
,08-11 06:33:02.238  1863  3540 I CheckinRequestBuilder: Classify the device as Phone.
,08-11 06:33:02.244  1863  3540 I EventLogService: Opted in for usage reporting
,08-11 06:33:02.486   872  2015 I ActivityManager: Killing 3234:com.android.musicfx/u0a18 (adj 15): empty #17
08-11 06:33:02.486  1863  3540 W System.err: java.lang.Exception: Error converting session
08-11 06:33:02.488  1863  3540 W System.err: 	at com.google.android.gms.org.conscrypt.a.log(SourceFile:302)
,08-11 06:33:02.488  1863  3540 W System.err: 	at com.google.android.gms.org.conscrypt.a.toSession(SourceFile:268)
08-11 06:33:02.488  1863  3540 W System.err: 	at com.google.android.gms.org.conscrypt.ClientSessionContext.getSession(SourceFile:87)
08-11 06:33:02.489  1863  3540 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getCachedClientSession(SourceFile:711)
08-11 06:33:02.489  1863  3540 W System.err: 	at com.google.android.gms.org.conscrypt.SSLParametersImpl.getSessionToReuse(SourceFile:377)
08-11 06:33:02.489  1863  3540 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSocketImpl.startHandshake(SourceFile:296)
08-11 06:33:02.489  1863  3540 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.a(SourceFile:258)
08-11 06:33:02.490  1863  3540 W System.err: 	at com.google.android.gms.common.net.SSLCertificateSocketFactory.createSocket(SourceFile:558)
08-11 06:33:02.490  1863  3540 W System.err: 	at com.android.okhttp.internal.http.SocketConnector.connectTls(SocketConnector.java:89)
08-11 06:33:02.490  1863  3540 W System.err: 	at com.android.okhttp.Connection.connect(Connection.java:143)
08-11 06:33:02.490  1863  3540 W System.err: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
08-11 06:33:02.491  1863  3540 W System.err: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
08-11 06:33:02.491  1863  3540 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
08-11 06:33:02.491  1863  3540 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
08-11 06:33:02.491  1863  3540 W System.err: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
08-11 06:33:02.492  1863  3540 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
08-11 06:33:02.492  1863  3540 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:114)
08-11 06:33:02.492  1863  3540 W System.err: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:245)
,08-11 06:33:02.492  1863  3540 W System.err: 	at com.android.okhttp.internal.huc.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
08-11 06:33:02.493  1863  3540 W System.err: 	at com.android.okhttp.internal.huc.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java)
08-11 06:33:02.493  1863  3540 W System.err: 	at com.google.android.gms.checkin.k.a(SourceFile:360)
08-11 06:33:02.493  1863  3540 W System.err: 	at com.google.android.gms.checkin.k.a(SourceFile:235)
08-11 06:33:02.493  1863  3540 W System.err: 	at com.google.android.gms.checkin.g.a(SourceFile:571)
08-11 06:33:02.494  1863  3540 W System.err: 	at com.google.android.gms.checkin.g.doInBackground(SourceFile:544)
,08-11 06:33:02.494  1863  3540 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
08-11 06:33:02.494  1863  3540 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 06:33:02.494  1863  3540 W System.err: 	at java.lang.Thread.run(Thread.java:818)
,08-11 06:33:02.494  1863  3540 W System.err: Caused by: java.io.IOException: Invalid session data
,08-11 06:33:02.496  1863  3540 W System.err: 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.<init>(SourceFile:88)
,08-11 06:33:02.497  1863  3540 W System.err: 	at com.google.android.gms.org.conscrypt.a.toSession(SourceFile:267)
08-11 06:33:02.498  1863  3540 W System.err: 	... 25 more
,08-11 06:33:02.531   872  2015 I ActivityManager: Killing 3053:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-11 06:33:02.622  1499  2300 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-11 06:33:02.625  1499  1499 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-11 06:33:02.638  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:33:02.640  1863  1863 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-11 06:33:02.647  1863  3540 I CheckinTask: Sending checkin request (9625 bytes)
,08-11 06:33:02.669   872  1738 I ActivityManager: Start proc 3843:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,08-11 06:33:02.681  1863  3852 D LocationInitializer: Restart initialization of location
,08-11 06:33:02.719  3843  3843 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-11 06:33:02.731  3843  3843 I MultiDex: VM with version 2.1.0 has multidex support
,08-11 06:33:02.731  3843  3843 I MultiDex: install
08-11 06:33:02.732  3843  3843 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-11 06:33:02.766  1821  1927 W GCoreFlp: No location to return for getLastLocation()
,08-11 06:33:02.766  1499  3855 W FusedLocationProvider: location=null
,08-11 06:33:02.773  1499  1903 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,08-11 06:33:02.773  1499  1903 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud.
08-11 06:33:02.773  1499  1903 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 06:33:02.773  1499  1903 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 06:33:02.783  2354  3839 E Babel   : UserRecoverableAuthException.
,08-11 06:33:02.784  2354  3839 E Babel   : efr: BadAuthentication
08-11 06:33:02.784  2354  3839 E Babel   : 	at efp.a(Unknown Source)
08-11 06:33:02.784  2354  3839 E Babel   : 	at efp.a(Unknown Source)
08-11 06:33:02.784  2354  3839 E Babel   : 	at efp.a(Unknown Source)
08-11 06:33:02.784  2354  3839 E Babel   : 	at g.a(Unknown Source)
08-11 06:33:02.784  2354  3839 E Babel   : 	at cbh.a(SourceFile:3092)
08-11 06:33:02.784  2354  3839 E Babel   : 	at cbh.a(SourceFile:1136)
08-11 06:33:02.784  2354  3839 E Babel   : 	at cyr.a(SourceFile:4333)
08-11 06:33:02.784  2354  3839 E Babel   : 	at cyr.a(SourceFile:1419)
08-11 06:33:02.784  2354  3839 E Babel   : 	at ctk.a(SourceFile:492)
08-11 06:33:02.784  2354  3839 E Babel   : 	at ctk.a(SourceFile:1468)
08-11 06:33:02.784  2354  3839 E Babel   : 	at cst.a(SourceFile:4416)
08-11 06:33:02.784  2354  3839 E Babel   : 	at cbv.b(SourceFile:106)
08-11 06:33:02.784  2354  3839 E Babel   : 	at cbs.d(SourceFile:335)
08-11 06:33:02.784  2354  3839 E Babel   : 	at cbt.run(SourceFile:81)
08-11 06:33:02.784  2354  3839 E Babel   : Error getting auth token
,08-11 06:33:02.784  2354  3839 E Babel   : dxq
08-11 06:33:02.784  2354  3839 E Babel   : 	at g.a(Unknown Source)
08-11 06:33:02.784  2354  3839 E Babel   : 	at cbh.a(SourceFile:3092)
08-11 06:33:02.784  2354  3839 E Babel   : 	at cbh.a(SourceFile:1136)
08-11 06:33:02.784  2354  3839 E Babel   : 	at cyr.a(SourceFile:4333)
08-11 06:33:02.784  2354  3839 E Babel   : 	at cyr.a(SourceFile:1419)
08-11 06:33:02.784  2354  3839 E Babel   : 	at ctk.a(SourceFile:492)
08-11 06:33:02.784  2354  3839 E Babel   : 	at ctk.a(SourceFile:1468)
08-11 06:33:02.784  2354  3839 E Babel   : 	at cst.a(SourceFile:4416)
08-11 06:33:02.784  2354  3839 E Babel   : 	at cbv.b(SourceFile:106)
08-11 06:33:02.784  2354  3839 E Babel   : 	at cbs.d(SourceFile:335)
08-11 06:33:02.784  2354  3839 E Babel   : 	at cbt.run(SourceFile:81)
,08-11 06:33:02.786  3843  3843 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-11 06:33:02.799  2354  3839 E Babel   : Account registration failed 1-Redacted-21
,08-11 06:33:02.799  2354  3839 E Babel   : dao: null -- null
08-11 06:33:02.799  2354  3839 E Babel   : 	at cbh.a(SourceFile:3124)
08-11 06:33:02.799  2354  3839 E Babel   : 	at cbh.a(SourceFile:1136)
08-11 06:33:02.799  2354  3839 E Babel   : 	at cyr.a(SourceFile:4333)
08-11 06:33:02.799  2354  3839 E Babel   : 	at cyr.a(SourceFile:1419)
08-11 06:33:02.799  2354  3839 E Babel   : 	at ctk.a(SourceFile:492)
08-11 06:33:02.799  2354  3839 E Babel   : 	at ctk.a(SourceFile:1468)
08-11 06:33:02.799  2354  3839 E Babel   : 	at cst.a(SourceFile:4416)
08-11 06:33:02.799  2354  3839 E Babel   : 	at cbv.b(SourceFile:106)
08-11 06:33:02.799  2354  3839 E Babel   : 	at cbs.d(SourceFile:335)
08-11 06:33:02.799  2354  3839 E Babel   : 	at cbt.run(SourceFile:81)
,08-11 06:33:02.806  2354  3839 I art     : Note: end time exceeds epoch: 
,08-11 06:33:02.810  3843  3843 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-11 06:33:02.814  1499  2309 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-11 06:33:02.816  1499  1499 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-11 06:33:02.824  3843  3843 D WearableService: callingUid 10011, callindPid: 3843
,08-11 06:33:02.824  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-11 06:33:02.826  1863  1863 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-11 06:33:02.846  1499  1904 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,08-11 06:33:02.846  1499  1904 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud.
08-11 06:33:02.846  1499  1904 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 06:33:02.846  1499  1904 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 06:33:02.852  3843  3867 D NativeLibraryUtils: Install completed successfully. count=13 extracted=0
,08-11 06:33:02.854  1821  2257 E MDM     : [115] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-11 06:33:02.857  1863  3870 D LocationInitializer: Restart initialization of location
,08-11 06:33:02.858  1821  2257 E MDM     : [115] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-11 06:33:02.863  2354  3866 E Babel   : Unexpected exception while authenticating.
,08-11 06:33:02.863  2354  3866 E Babel   : efs: User intervention required. Notification has been pushed.
08-11 06:33:02.863  2354  3866 E Babel   : 	at efp.b(Unknown Source)
08-11 06:33:02.863  2354  3866 E Babel   : 	at efp.b(Unknown Source)
08-11 06:33:02.863  2354  3866 E Babel   : 	at g.a(Unknown Source)
08-11 06:33:02.863  2354  3866 E Babel   : 	at cbh.b(SourceFile:1151)
08-11 06:33:02.863  2354  3866 E Babel   : 	at def.run(SourceFile:5617)
08-11 06:33:02.863  2354  3866 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 06:33:02.863  2354  3866 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 06:33:02.863  2354  3866 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,08-11 06:33:02.875  1821  1927 W GCoreFlp: No location to return for getLastLocation()
,08-11 06:33:02.875  1499  3871 W FusedLocationProvider: location=null
,08-11 06:33:03.012  1863  3540 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,08-11 06:33:03.014  1863  3540 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,08-11 06:33:03.237  1499  2657 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,08-11 06:33:03.238  1499  2657 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> AndroidCheckInServer without consulting the cloud.
,08-11 06:33:03.238  1499  2657 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 06:33:03.239  1499  2657 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 06:33:03.280  1863  3540 W CheckinRequestBuilder: awaiting user notification for token
,08-11 06:33:03.324  1863  3540 I CheckinRequestBuilder: Classify the device as Phone.
,08-11 06:33:03.339  1863  3540 I EventLogService: Opted in for usage reporting
,08-11 06:33:03.354  1863  3540 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-11 06:33:03.365  1863  3540 I CheckinService: Checking schedule, now: 1470889983365 next: 1470931126354
08-11 06:33:03.365  1863  3540 I CheckinService: active receiver: disabled
,08-11 06:33:03.406  1863  1863 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-11 06:33:03.410  1863  1863 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-11 06:33:03.420  1499  2636 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-11 06:33:03.842   872  1375 D WifiService: setWifiEnabled: false pid=3332, uid=10000
,08-11 06:33:03.843   872  1375 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 06:33:03.878  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-11 06:33:03.882   872  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-11 06:33:03.882   872  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-11 06:33:03.882   872  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-11 06:33:03.882   872  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 06:33:03.901   872  1308 E native  : do suspend true
,08-11 06:33:03.915   872  3522 D DhcpClient: Clearing IP address
08-11 06:33:03.915   370   870 D CommandListener: Clearing all IP addresses on wlan0
,08-11 06:33:03.920  1499  3605 V NativeCrypto: Read error: ssl=0x9a8f6400: I/O error during system call, Connection timed out
,08-11 06:33:03.924   370   870 D CommandListener: Setting iface cfg
,08-11 06:33:03.925  1499  3605 V NativeCrypto: SSL shutdown failed: ssl=0x9a8f6400: I/O error during system call, Broken pipe
,08-11 06:33:03.932   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-11 06:33:03.932   872  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-11 06:33:03.937   393   393 E Parcel  : Reading a NULL string not supported here.
,08-11 06:33:03.943   872  1308 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-11 06:33:03.944   872  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-11 06:33:03.945   872  1308 E native  : do suspend true
,08-11 06:33:03.947   872  3523 D DhcpClient: Receive thread stopped
,08-11 06:33:03.954   872  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-11 06:33:03.988   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 06:33:04.032   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 06:33:04.032   370   870 D CommandListener: Clearing all IP addresses on wlan0
08-11 06:33:04.033   872  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-11 06:33:04.033   872  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-11 06:33:04.034   872  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-11 06:33:04.037   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-11 06:33:04.043  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:33:04.043  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:33:04.043  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 06:33:04.043  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 06:33:04.043  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 06:33:04.043  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:33:04.043  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:33:04.043  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 06:33:04.045  1805  1805 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-11 06:33:04.046  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 06:33:04.049  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:33:04.049  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:33:04.049  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 06:33:04.049  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 06:33:04.049  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 06:33:04.049  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:33:04.049  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:33:04.049  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 06:33:04.051  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 06:33:04.052   872  1308 D WifiConfigStore: Retrieve network priorities after PNO.
08-11 06:33:04.056  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:33:04.056  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:33:04.056  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 06:33:04.056  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:33:04.056  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 06:33:04.056  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:33:04.056  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:33:04.056  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 06:33:04.058  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 06:33:04.061   872  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-11 06:33:04.062  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:33:04.062  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:33:04.062  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 06:33:04.062  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:33:04.062  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 06:33:04.062  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:33:04.062  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:33:04.062  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 06:33:04.064  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 06:33:04.065  1821  2047 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 06:33:04.067  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:33:04.067  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:33:04.067  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 06:33:04.067  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:33:04.067  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 06:33:04.067  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:33:04.067  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:33:04.067  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 06:33:04.069  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 06:33:04.070  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 06:33:04.078  1499  3883 I VacuumService: Vacuum at: now=1470889984078 tag=VacuumService
,08-11 06:33:04.078  1863  1863 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-11 06:33:04.081  1863  1863 D SystemUpdateService: onCreate
,08-11 06:33:04.084  1863  1863 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) },
,08-11 06:33:04.087  1863  3885 I SystemUpdateService: active receiver: enabled
,08-11 06:33:04.090  1863  3885 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-11 06:33:04.092  1863  1863 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-11 06:33:04.094  1863  3567 I iu.UploadsManager: num queued entries: 0
,08-11 06:33:04.094  1863  3885 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-11 06:33:04.095  1863  3885 I SystemUpdateService: now status is 0 (complete)
,08-11 06:33:04.096  1863  3885 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-11 06:33:04.096  1863  3885 I SystemUpdateService: file has been verified
08-11 06:33:04.097  1863  3885 I SystemUpdateService: OTA package size = 12249756
08-11 06:33:04.097  1863  3567 I iu.UploadsManager: num updated entries: 0
,08-11 06:33:04.099  1863  1863 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-11 06:33:04.100  1863  1863 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-11 06:33:04.101  1863  3567 I iu.SyncManager: NEXT; no task
08-11 06:33:04.102  1863  3885 I SystemUpdateService: showing system update notification
,08-11 06:33:04.113  3570  3570 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-11 06:33:04.114   370   870 E Netd    : netlink response contains error (No such file or directory)
08-11 06:33:04.115  1863  1863 D SystemUpdateService: onDestroy
,08-11 06:33:04.118  3570  3570 D SprintDMHelper: simOperator: 
,08-11 06:33:04.118  3570  3570 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-11 06:33:04.154  2354  3888 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-11 06:33:05.827  3614  3660 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-11 06:33:07.833   872  1310 D ConnectivityService: handlePromptUnvalidated 100
,08-11 06:33:07.863   872  1413 I ActivityManager: Killing 3185:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-11 06:33:07.982   872  1375 I ActivityManager: Killing 3257:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-11 06:33:08.085   872  1703 I ActivityManager: Killing 1805:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,08-11 06:33:08.194   872  1309 D WifiService: Client connection lost with reason: 4
,08-11 06:33:08.860  3400  3438 D BluetoothAdapterState: Current state: ON, message: 23
08-11 06:33:08.860  3400  3438 D BluetoothAdapterProperties: Setting state to 13
08-11 06:33:08.860  3400  3438 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-11 06:33:08.862  3400  3438 D BluetoothAdapterProperties: onBluetoothDisable()
,08-11 06:33:08.864  3400  3438 I BluetoothAdapterState: Entering PendingCommandState
,08-11 06:33:08.871  3400  3400 D BluetoothMapService: onReceive
,08-11 06:33:08.872  3400  3400 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-11 06:33:08.872  3400  3400 D BluetoothMapService: STATE_TURNING_OFF
,08-11 06:33:08.874  3400  3400 D BluetoothMapService: MAP Service closeService in
08-11 06:33:08.877  3400  3443 D BluetoothAdapterProperties: Scan Mode:20
,08-11 06:33:08.877  3400  3400 D BluetoothMapMasInstance0: MAP Service shutdown
08-11 06:33:08.877  3400  3400 D ObexServerSockets0: shutdown(block = true)
,08-11 06:33:08.878  3400  3438 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-11 06:33:08.879  3400  3477 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-11 06:33:08.884  3332  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:33:08.884  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,08-11 06:33:08.884  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:33:08.884  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 06:33:08.884  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:33:08.884  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 06:33:08.884  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:33:08.884  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:33:08.884  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 06:33:08.886  3400  3400 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-11 06:33:08.886  3332  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:33:08.887  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 06:33:08.886  3400  3400 D ObexServerSockets0: shutdown called from another thread - interrupt().,
08-11 06:33:08.889  3400  3451 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-11 06:33:08.890  3400  3478 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-11 06:33:08.892  3400  3400 I BtOppRfcommListener: stopping Accept Thread
,08-11 06:33:08.892  3400  3512 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-11 06:33:08.892  3400  3512 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-11 06:33:08.895  3400  3400 D HeadsetService: Received stop request...Stopping profile...
,08-11 06:33:08.895  3456  3456 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-11 06:33:08.896  3332  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:33:08.896  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:33:08.896  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:33:08.896  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 06:33:08.896  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:33:08.896  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 06:33:08.896  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:33:08.896  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:33:08.896  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 06:33:08.897  3332  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 06:33:08.897  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 06:33:08.900  3332  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:33:08.900  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:33:08.900  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:33:08.900  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 06:33:08.900  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:33:08.900  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 06:33:08.900  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:33:08.900  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:33:08.900  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 06:33:08.901  3332  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 06:33:08.901  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 06:33:08.902  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 06:33:08.903  3456  3472 D BluetoothHeadset: Proxy object disconnected
,08-11 06:33:08.903  1717  1732 D BluetoothHeadset: Proxy object disconnected
,08-11 06:33:08.903  3400  3400 D A2dpService: Received stop request...Stopping profile...
08-11 06:33:08.903   872   872 D BluetoothHeadset: Proxy object disconnected
,08-11 06:33:08.904  1364  2007 D BluetoothHeadset: Proxy object disconnected
,08-11 06:33:08.904  3400  3466 D A2dpStateMachine: Exit Disconnected: -1
08-11 06:33:08.904   872   872 D BluetoothHeadset: Proxy object disconnected,
08-11 06:33:08.904   872   872 D BluetoothHeadset: Proxy object disconnected
08-11 06:33:08.904  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 06:33:08.905   872   872 D BluetoothA2dp: Proxy object disconnected
08-11 06:33:08.906  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:33:08.906  3400  3400 D HidService: Received stop request...Stopping profile...
,08-11 06:33:08.906  3400  3400 D HidService: Stopping Bluetooth HidService
08-11 06:33:08.910  3456  3456 D DockEventReceiver: finishStartingService: stopping service,
08-11 06:33:08.911  1364  1364 D HeadsetProfile: Bluetooth service disconnected
,08-11 06:33:08.911  1364  1364 D BluetoothA2dp: Proxy object disconnected
08-11 06:33:08.912  1364  1364 D BluetoothInputDevice: Proxy object disconnected
08-11 06:33:08.912  1364  1364 D HidProfile: Bluetooth service disconnected
,08-11 06:33:08.909  3400  3400 V BluetoothAdapterState: isTurningOff()=true
08-11 06:33:08.912  3400  3400 V BluetoothAdapterState: isTurningOn()=false,
,08-11 06:33:08.912  3400  3400 V BluetoothAdapterState: isBleTurningOn()=false
08-11 06:33:08.912  3400  3400 V BluetoothAdapterState: isBleTurningOff()=false
08-11 06:33:08.912  3456  3456 D HeadsetProfile: Bluetooth service disconnected
,08-11 06:33:08.913  3400  3400 D HealthService: Received stop request...Stopping profile...
08-11 06:33:08.913  3456  3456 D BluetoothA2dp: Proxy object disconnected
08-11 06:33:08.914  3456  3456 D BluetoothInputDevice: Proxy object disconnected
,08-11 06:33:08.914  3456  3456 D HidProfile: Bluetooth service disconnected
08-11 06:33:08.916  3400  3400 D PanService: Received stop request...Stopping profile...
08-11 06:33:08.918  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-11 06:33:08.918  1364  1364 D PanProfile: Bluetooth service disconnected
08-11 06:33:08.919  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 06:33:08.919  3400  3400 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-11 06:33:08.920  3400  3443 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-11 06:33:08.920  3400  3449 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 06:33:08.920  3400  3449 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 06:33:08.920  3400  3449 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-11 06:33:08.921  3456  3456 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-11 06:33:08.921  3400  3443 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-11 06:33:08.921  3456  3456 D PanProfile: Bluetooth service disconnected
08-11 06:33:08.921  3400  3400 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-11 06:33:08.922  3400  3400 D BluetoothMapService: Received stop request...Stopping profile...
,08-11 06:33:08.922  3400  3400 D BluetoothMapService: stop()
08-11 06:33:08.923  3400  3400 D BluetoothMapAppObserver: deinitObservers()
08-11 06:33:08.923  3400  3400 D BluetoothMapAppObserver: removeReceiver()
08-11 06:33:08.924  3456  3456 D BluetoothMap: Proxy object disconnected
,08-11 06:33:08.924  3456  3456 D MapProfile: Bluetooth service disconnected
08-11 06:33:08.924  1364  1364 D BluetoothMap: Proxy object disconnected
08-11 06:33:08.924  1364  1364 D MapProfile: Bluetooth service disconnected
08-11 06:33:08.925  3400  3400 V BluetoothAdapterState: isTurningOff()=true
,08-11 06:33:08.925  3400  3400 V BluetoothAdapterState: isTurningOn()=false
08-11 06:33:08.925  3400  3400 V BluetoothAdapterState: isBleTurningOn()=false
08-11 06:33:08.925  3400  3400 V BluetoothAdapterState: isBleTurningOff()=false
08-11 06:33:08.927  3400  3449 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 06:33:08.927  3400  3449 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-11 06:33:08.928  3400  3449 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 06:33:08.928  3400  3449 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-11 06:33:08.928  3400  3449 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 06:33:08.928  3400  3449 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 06:33:08.928  3400  3443 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-11 06:33:08.928  3400  3400 V BluetoothAdapterState: isTurningOff()=true
08-11 06:33:08.928  3400  3400 V BluetoothAdapterState: isTurningOn()=false
,08-11 06:33:08.929  3400  3400 V BluetoothAdapterState: isBleTurningOn()=false
,08-11 06:33:08.929  3400  3400 V BluetoothAdapterState: isBleTurningOff()=false,
08-11 06:33:08.929  3400  3400 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-11 06:33:08.929  3400  3443 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-11 06:33:08.929  3400  3400 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-11 06:33:08.930  3400  3400 V BluetoothAdapterState: isTurningOff()=true
08-11 06:33:08.931  3400  3400 V BluetoothAdapterState: isTurningOn()=false
08-11 06:33:08.931  3400  3400 V BluetoothAdapterState: isBleTurningOn()=false
,08-11 06:33:08.931  3400  3400 V BluetoothAdapterState: isBleTurningOff()=false
08-11 06:33:08.931  3400  3400 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-11 06:33:08.931  3400  3443 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-11 06:33:08.931  3400  3400 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-11 06:33:08.933  3400  3400 V BluetoothAdapterState: isTurningOff()=true
08-11 06:33:08.933  1364  1364 D BluetoothPbap: Proxy object disconnected
08-11 06:33:08.933  3400  3400 V BluetoothAdapterState: isTurningOn()=false
,08-11 06:33:08.933  1364  1364 D PbapServerProfile: Bluetooth service disconnected
08-11 06:33:08.933  3400  3400 V BluetoothAdapterState: isBleTurningOn()=false
08-11 06:33:08.933  3456  3456 D BluetoothPbap: Proxy object disconnected
08-11 06:33:08.934  3400  3400 V BluetoothAdapterState: isBleTurningOff()=false
08-11 06:33:08.934  3456  3456 D PbapServerProfile: Bluetooth service disconnected
08-11 06:33:08.934  3400  3400 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-11 06:33:08.934  3400  3400 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-11 06:33:08.934  3400  3400 D BluetoothMapService: MAP Service closeService in
08-11 06:33:08.935  3400  3400 V BluetoothAdapterState: isTurningOff()=true
08-11 06:33:08.935  3400  3400 V BluetoothAdapterState: isTurningOn()=false
08-11 06:33:08.935  3400  3400 V BluetoothAdapterState: isBleTurningOn()=false
08-11 06:33:08.935  3400  3400 V BluetoothAdapterState: isBleTurningOff()=false
08-11 06:33:08.935  3400  3438 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-11 06:33:08.935  3400  3438 D BluetoothAdapterProperties: Setting state to 15
08-11 06:33:08.935  3400  3438 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-11 06:33:08.936  3400  3438 I BluetoothAdapterState: Entering BleOnState
,08-11 06:33:08.936  3400  3400 D BluetoothMapService: cleanup()
08-11 06:33:08.936  3400  3400 D BluetoothMapService: MAP Service closeService in
08-11 06:33:08.936  3456  3469 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 06:33:08.937  3456  3472 D BluetoothA2dp: onBluetoothStateChange: up=false
08-11 06:33:08.937  3456  3469 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-11 06:33:08.938  1364  1376 D BluetoothPbap: onBluetoothStateChange: up=false
08-11 06:33:08.939  3456  3472 D BluetoothMap: onBluetoothStateChange: up=false
08-11 06:33:08.942  1364  2007 D BluetoothPan: onBluetoothStateChange on: false
,08-11 06:33:08.943  1364  1382 D BluetoothA2dp: onBluetoothStateChange: up=false
08-11 06:33:08.943   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-11 06:33:08.943  1364  1376 D BluetoothMap: onBluetoothStateChange: up=false
08-11 06:33:08.944   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-11 06:33:08.944   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-11 06:33:08.944  3456  3469 D BluetoothPan: onBluetoothStateChange on: false
,08-11 06:33:08.945  1364  2007 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-11 06:33:08.945   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-11 06:33:08.945  1717  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-11 06:33:08.945  3456  3472 D BluetoothPbap: onBluetoothStateChange: up=false
,08-11 06:33:08.946  1364  1382 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-11 06:33:08.947  3400  3438 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-11 06:33:08.947  3400  3438 D BluetoothAdapterProperties: Setting state to 16
08-11 06:33:08.947  3400  3438 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-11 06:33:08.947  3400  3438 D BluetoothAdapterProperties: onBleDisable
,08-11 06:33:08.948  3400  3438 I BluetoothAdapterState: Entering PendingCommandState
08-11 06:33:08.948  3400  3440 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-11 06:33:08.949  3400  3449 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-11 06:33:08.949  3400  3449 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-11 06:33:08.950  3400  3443 D BluetoothAdapterProperties: Scan Mode:20
08-11 06:33:08.950  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:33:08.952  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:33:08.952  3456  3456 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 ,
08-11 06:33:08.954  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:33:08.956  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-11 06:33:08.958  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:33:08.959  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 06:33:08.960  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 06:33:08.966  3456  3456 D DockEventReceiver: finishStartingService: stopping service
,08-11 06:33:09.156  3400  3443 I bt_hci  : shut_down
,08-11 06:33:09.173  3400  3447 I bt_vendor: low_power_mode_cb
,08-11 06:33:09.180  3400  3447 D bt_hwcfg: hw_epilog_process
,08-11 06:33:09.192  3400  3447 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-11 06:33:09.192  3400  3447 I bt_vendor: epilog_cb
,08-11 06:33:09.192  3400  3447 I bt_hci  : epilog_finished_callback
,08-11 06:33:09.200  3400  3443 I bt_hci_h4: hal_close
,08-11 06:33:09.201  3400  3443 I bt_userial_vendor: device fd = 51 close
,08-11 06:33:09.325  3400  3440 D bt_stack_manager: event_shut_down_stack finished.
,08-11 06:33:09.326  3400  3438 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-11 06:33:09.331  3400  3438 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-11 06:33:09.331  3400  3400 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-11 06:33:09.332  3400  3400 D BtGatt.GattService: Received stop request...Stopping profile...
,08-11 06:33:09.332  3400  3400 D BtGatt.GattService: stop()
08-11 06:33:09.332  3400  3400 D BtGatt.AdvertiseManager: advertise clients cleared
,08-11 06:33:09.336  3400  3400 V BluetoothAdapterState: isTurningOff()=false
,08-11 06:33:09.336  3400  3400 V BluetoothAdapterState: isTurningOn()=false
,08-11 06:33:09.336  3400  3400 V BluetoothAdapterState: isBleTurningOn()=false
,08-11 06:33:09.337  3400  3400 V BluetoothAdapterState: isBleTurningOff()=true
08-11 06:33:09.337  3400  3438 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-11 06:33:09.338  3400  3438 D BluetoothAdapterProperties: Setting state to 10
08-11 06:33:09.338  3400  3438 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-11 06:33:09.339  3400  3438 I BluetoothAdapterState: Entering OffState
08-11 06:33:09.341   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-11 06:33:09.360  3400  3400 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-11 06:33:09.360  3400  3400 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-11 06:33:09.360  3400  3440 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-11 06:33:09.360  3400  3400 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-11 06:33:09.365  3400  3440 D bt_stack_manager: event_clean_up_stack finished.
,08-11 06:33:09.368  3400  3400 I art     : System.exit called, status: 0
,08-11 06:33:09.368  3400  3400 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-11 06:33:09.403  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:33:09.413  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:33:09.418  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:33:09.428   872   883 I ActivityManager: Process com.android.bluetooth (pid 3400) has died
,08-11 06:33:09.461  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-11 06:33:09.461  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-11 06:33:09.462  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 06:33:09.463  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 06:33:09.503  2581  2581 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-11 06:33:09.504  2581  2581 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-11 06:33:09.505  2581  2581 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-11 06:33:10.900  2581  2592 D Finsky  : [177] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-11 06:33:10.917  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:33:10.982  1499  2659 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-11 06:33:10.982  1499  2659 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-11 06:33:10.983  1499  2659 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 06:33:10.983  1499  2659 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 06:33:11.037  2581  2592 D Finsky  : [177] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-11 06:33:13.141  1863  1872 E System  : Uncaught exception thrown by finalizer
,08-11 06:33:13.141  1863  1872 E System  : java.lang.NullPointerException: ssl_session == null
08-11 06:33:13.141  1863  1872 E System  : 	at com.google.android.gms.org.conscrypt.NativeCrypto.SSL_SESSION_free(Native Method)
08-11 06:33:13.141  1863  1872 E System  : 	at com.google.android.gms.org.conscrypt.OpenSSLSessionImpl.finalize(SourceFile:485)
08-11 06:33:13.141  1863  1872 E System  : 	at java.lang.Daemons$FinalizerDaemon.doFinalize(Daemons.java:202)
08-11 06:33:13.141  1863  1872 E System  : 	at java.lang.Daemons$FinalizerDaemon.run(Daemons.java:185)
08-11 06:33:13.141  1863  1872 E System  : 	at java.lang.Thread.run(Thread.java:818)
,08-11 06:33:13.491   872  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-11 06:33:13.504   872   885 I ActivityManager: Start proc 3905:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher
,08-11 06:33:13.594  1821  1821 V GmsNetworkLocationProvi: DISABLE
,08-11 06:33:13.601  1821  1821 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,08-11 06:33:13.766   872  1738 I ActivityManager: Start proc 3924:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
,08-11 06:33:13.798   872  1720 I ActivityManager: Start proc 3936:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-11 06:33:13.832  3924  3924 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
,08-11 06:33:13.867  3936  3936 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-11 06:33:13.873   872   889 I ActivityManager: Start proc 3954:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-11 06:33:13.907  3936  3936 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-11 06:33:13.924   872  1734 I ActivityManager: Killing 3551:com.google.android.youtube/u0a86 (adj 15): empty #17
,08-11 06:33:13.981  3936  3966 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,08-11 06:33:14.004  3954  3954 D AdapterServiceConfig: Adding HeadsetService
,08-11 06:33:14.004  3954  3954 D AdapterServiceConfig: Adding A2dpService
08-11 06:33:14.004  3954  3954 D AdapterServiceConfig: Adding HidService
08-11 06:33:14.005  3954  3954 D AdapterServiceConfig: Adding HealthService
08-11 06:33:14.005  3954  3954 D AdapterServiceConfig: Adding PanService
08-11 06:33:14.005  3954  3954 D AdapterServiceConfig: Adding GattService
,08-11 06:33:14.006  3954  3954 D AdapterServiceConfig: Adding BluetoothMapService
08-11 06:33:14.013  1863  3969 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,08-11 06:33:14.022  1863  3969 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-11 06:33:14.039  3954  3954 D BluetoothAdapterState: make() - Creating AdapterState
,08-11 06:33:14.039   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5ac3942:true
,08-11 06:33:14.042  3954  3954 I bt_bluedroid: init
,08-11 06:33:14.042  3954  3972 I BluetoothAdapterState: Entering OffState
,08-11 06:33:14.045  1863  2151 I Icing   : updateResources: need to parse f{com.google.android.gms}
,08-11 06:33:14.046  3954  3973 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-11 06:33:14.046  3954  3973 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-11 06:33:14.046  3954  3973 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-11 06:33:14.046  3954  3973 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-11 06:33:14.047  3954  3954 I bt_bluedroid: get_profile_interface socket
,08-11 06:33:14.049  3954  3954 I bt_bluedroid: get_profile_interface sdp
,08-11 06:33:14.050  3954  3976 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-11 06:33:14.052  3954  3976 D BluetoothAdapterProperties: Name is: Nexus 6
,08-11 06:33:14.052  3905  3971 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-11 06:33:14.053  3954  3967 I bt_bluedroid: config_hci_snoop_log
,08-11 06:33:14.054   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-11 06:33:14.057  3954  3972 D BluetoothAdapterState: Current state: OFF, message: 0
,08-11 06:33:14.057  3954  3972 D BluetoothAdapterProperties: Setting state to 14
08-11 06:33:14.057  3954  3972 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-11 06:33:14.058  3954  3972 D BluetoothBondStateMachine: make
,08-11 06:33:14.060  3954  3978 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-11 06:33:14.063  3954  3972 I BluetoothAdapterState: Entering PendingCommandState
,08-11 06:33:14.063  3954  3954 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-11 06:33:14.066  3954  3954 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f87c4
08-11 06:33:14.067  3954  3954 D BtGatt.DebugUtils: handleDebugAction() action=null
08-11 06:33:14.067  3954  3954 D BtGatt.GattService: Received start request. Starting profile...
08-11 06:33:14.067  3954  3954 D BtGatt.GattService: start()
,08-11 06:33:14.067  3954  3954 I bt_bluedroid: get_profile_interface gatt
08-11 06:33:14.068  3954  3954 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f87c4
08-11 06:33:14.068  3954  3954 D BtGatt.AdvertiseManager: advertise manager created
,08-11 06:33:14.072  3954  3954 V BluetoothAdapterState: isTurningOff()=false
,08-11 06:33:14.072  3954  3954 V BluetoothAdapterState: isTurningOn()=false
08-11 06:33:14.073  3954  3954 V BluetoothAdapterState: isBleTurningOn()=true
08-11 06:33:14.073  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
08-11 06:33:14.073  3954  3972 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-11 06:33:14.073  3954  3972 I bt_bluedroid: enable
08-11 06:33:14.073  3954  3973 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-11 06:33:14.074  3954  3973 I bt_hci  : start_up
,08-11 06:33:14.079  3954  3973 I bt_vendor: alloc value 0xb39e5189
,08-11 06:33:14.080  3954  3973 I bt_vendor: init
08-11 06:33:14.080  3954  3973 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-11 06:33:14.080  3954  3973 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-11 06:33:14.187  3954  3973 D bt_hci  : start_up starting async portion
,08-11 06:33:14.189  3954  3982 I bt_hci  : event_finish_startup
,08-11 06:33:14.189  3954  3982 I bt_hci_h4: hal_open
08-11 06:33:14.189  3954  3982 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-11 06:33:14.196  3954  3982 I bt_userial_vendor: device fd = 51 open,
,08-11 06:33:14.232  3954  3982 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-11 06:33:14.261  3954  3982 D bt_hwcfg: Chipset BCM4354A2
,08-11 06:33:14.261  3954  3982 D bt_hwcfg: Target name = [BCM4354A2]
,08-11 06:33:14.261  3954  3982 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-11 06:33:14.266  3905  3971 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 212 ms] updated apps [took 212 ms] 
,08-11 06:33:14.380  3936  3966 D ContactDirectoryManager: Found com.google.contacts.gal.provider
08-11 06:33:14.380  3936  3966 D ContactDirectoryManager: Found com.google.android.gm.exchange.directory.provider
,08-11 06:33:14.410   872  1725 I ActivityManager: Start proc 3985:com.google.android.gm.exchange/u0a77 for content provider com.google.android.gm.exchange/com.android.exchange.provider.ExchangeDirectoryProvider
,08-11 06:33:14.452   872  2015 I ActivityManager: Killing 3614:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-11 06:33:14.554  3985  3985 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltExchange3Google/lib/arm
,08-11 06:33:14.644   872   882 I ActivityManager: Start proc 3997:com.google.android.gm/u0a78 for content provider com.google.android.gm/com.android.email.provider.EmailProvider
,08-11 06:33:14.702   872  2015 I ActivityManager: Start proc 4009:com.google.process.gapps/u0a99 for content provider com.google.android.syncadapters.contacts/.GalProvider
,08-11 06:33:14.708   872  1375 I ActivityManager: Killing 3570:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,08-11 06:33:14.768   872  1703 I ActivityManager: Killing 3588:com.android.chrome/u0a40 (adj 15): empty #17
,08-11 06:33:14.772  3954  3982 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-11 06:33:14.773  3954  3982 D bt_hwcfg: Settlement delay -- 100 ms
08-11 06:33:14.773  3954  3982 I bt_hwcfg: Setting fw settlement delay to 100 
,08-11 06:33:14.810  3997  3997 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltGmail/lib/arm
,08-11 06:33:14.863  4009  4009 W System  : ClassLoader referenced unknown path: /system/app/GoogleContactsSyncAdapter/lib/arm
,08-11 06:33:14.889  3954  3982 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-11 06:33:14.889  3954  3982 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-11 06:33:14.904  3997  4024 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,08-11 06:33:14.908  4009  4009 I GoogleHttpClient: GMS http client unavailable, use old client
,08-11 06:33:14.921  3954  3982 I bt_hwcfg: vendor lib fwcfg completed
,08-11 06:33:14.922  3954  3982 I bt_vendor: firmware callback
08-11 06:33:14.922  3954  3982 I bt_hci  : firmware_config_callback
,08-11 06:33:14.931  3954  4029 I bt_btu  : btu_task pending for preload complete event
,08-11 06:33:14.932  3954  4029 I bt_btu_task: Bluetooth chip preload is complete
08-11 06:33:14.932  3954  4029 I bt_btu  : btu_task received preload complete event
08-11 06:33:14.933  3936  3966 I ContactDirectoryManager: deleted 0 stale rows which don't have any relevant directory
,08-11 06:33:14.940  3954  4029 I         : BTE_InitTraceLevels -- TRC_HCI
,08-11 06:33:14.940  3954  4029 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-11 06:33:14.940  3954  4029 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-11 06:33:14.940  3954  4029 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-11 06:33:14.941  3954  4029 I         : BTE_InitTraceLevels -- TRC_AVRC
08-11 06:33:14.941  3954  4029 I         : BTE_InitTraceLevels -- TRC_A2D
08-11 06:33:14.941  3954  4029 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-11 06:33:14.941  3954  4029 I         : BTE_InitTraceLevels -- TRC_BTM
08-11 06:33:14.942  3954  4029 I         : BTE_InitTraceLevels -- TRC_GAP
08-11 06:33:14.942  3954  4029 I         : BTE_InitTraceLevels -- TRC_PAN
08-11 06:33:14.942  3954  4029 I         : BTE_InitTraceLevels -- TRC_SDP,
08-11 06:33:14.942  3954  4029 I         : BTE_InitTraceLevels -- TRC_GATT
08-11 06:33:14.942  3954  4029 I         : BTE_InitTraceLevels -- TRC_SMP
08-11 06:33:14.942  3954  4029 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-11 06:33:14.942  3954  4029 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-11 06:33:14.970  3936  3966 I ContactDirectoryManager: Discovered 0 contact directories in 768ms
,08-11 06:33:15.010  3997  3997 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-11 06:33:15.065  3954  4029 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3962d9d
,08-11 06:33:15.065  3954  4029 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3962d9d 
,08-11 06:33:15.073  3954  3976 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-11 06:33:15.075  3954  3976 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-11 06:33:15.075  3997  4038 E Gmail   : Error finding the version of the Email provider.....
08-11 06:33:15.075  3997  4038 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
08-11 06:33:15.075  3997  4038 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
08-11 06:33:15.075  3997  4038 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1280)
08-11 06:33:15.075  3997  4038 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
08-11 06:33:15.075  3997  4038 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-11 06:33:15.075  3997  4038 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 06:33:15.075  3997  4038 E Gmail   : 	at android.os.Looper.loop(Looper.java:148)
08-11 06:33:15.075  3997  4038 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 06:33:15.075  3997  4038 W EmailMigration: We do not support migrating this version of the Email provider.
,08-11 06:33:15.076  3954  3976 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-11 06:33:15.078  3954  3976 D BluetoothAdapterProperties: Name is: Nexus 6
,08-11 06:33:15.080  3997  4023 I Gmail   : getAccountsCursor
,08-11 06:33:15.086  3954  3976 D BluetoothAdapterProperties: Scan Mode:20
08-11 06:33:15.086  3954  3976 D BluetoothAdapterProperties: Discoverable Timeout:120
08-11 06:33:15.087  3954  3976 D bt_hci  : do_postload posting postload work item
08-11 06:33:15.087  3954  3982 I bt_hci  : event_postload
08-11 06:33:15.087  3954  3982 I bt_vendor: sco_config_cb
08-11 06:33:15.087  3954  3982 I bt_hci  : sco_config_callback postload finished.
08-11 06:33:15.088  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:33:15.089  3954  3982 I bt_vendor: low_power_mode_cb
08-11 06:33:15.089  3954  3976 D bt_bte_conf: Device ID record 1 : primary
08-11 06:33:15.089  3954  3976 D bt_bte_conf:   vendorId            = 000f
08-11 06:33:15.089  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:33:15.089  3954  3976 D bt_bte_conf:   vendorIdSource      = 0001
08-11 06:33:15.089  3954  3976 D bt_bte_conf:   product             = 1200
08-11 06:33:15.089  3954  3976 D bt_bte_conf:   version             = 1436
08-11 06:33:15.089  3954  3976 D bt_bte_conf:   clientExecutableURL = 
08-11 06:33:15.089  3954  3976 D bt_bte_conf:   serviceDescription  = 
08-11 06:33:15.089  3954  3976 D bt_bte_conf:   documentationURL    = 
,08-11 06:33:15.089  3954  3976 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-11 06:33:15.090  3954  3973 D bt_stack_manager: event_start_up_stack finished
,08-11 06:33:15.090  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 06:33:15.090  3954  3972 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-11 06:33:15.090  3954  3972 D BluetoothAdapterProperties: Setting state to 15
08-11 06:33:15.090  3954  3972 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-11 06:33:15.091  3954  3972 I BluetoothAdapterState: Entering BleOnState
,08-11 06:33:15.101  3954  3972 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-11 06:33:15.101  3954  3972 D BluetoothAdapterProperties: Setting state to 11
08-11 06:33:15.102  3954  3972 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-11 06:33:15.104  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:33:15.106  3954  3954 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f87c4
,08-11 06:33:15.108  3954  3954 D HeadsetService: Received start request. Starting profile...
,08-11 06:33:15.110  3954  3954 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-11 06:33:15.111  3954  3954 D HeadsetStateMachine: make
,08-11 06:33:15.122  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 06:33:15.124  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:33:15.125  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 06:33:15.128  3954  3972 I BluetoothAdapterState: Entering PendingCommandState
,08-11 06:33:15.132  3954  3954 D HeadsetStateMachine: max_hf_connections = 1
,08-11 06:33:15.132  3954  3954 I bt_bluedroid: get_profile_interface handsfree
,08-11 06:33:15.133  3954  3976 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-11 06:33:15.135  3954  3976 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-11 06:33:15.138  3954  3954 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f87c4
,08-11 06:33:15.139  3954  3954 D A2dpService: Received start request. Starting profile...
,08-11 06:33:15.142  3954  3954 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-11 06:33:15.142  3954  3954 I bt_bluedroid: get_profile_interface avrcp
,08-11 06:33:15.148  3954  3954 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-11 06:33:15.148  3954  3954 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-11 06:33:15.149  3954  3954 D A2dpStateMachine: make
,08-11 06:33:15.151  3954  3954 I bt_bluedroid: get_profile_interface a2dp
,08-11 06:33:15.151  3954  3976 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-11 06:33:15.154  3954  4050 D A2dpStateMachine: Enter Disconnected: -2
,08-11 06:33:15.154  3954  3954 I BluetoothHidServiceJni: classInitNative: succeeds
,08-11 06:33:15.155  3954  3954 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f87c4
,08-11 06:33:15.156  3954  3954 D HidService: Received start request. Starting profile...
08-11 06:33:15.156  3954  3954 I bt_bluedroid: get_profile_interface hidhost
08-11 06:33:15.156  3954  3954 D HidService: setHidService(): set to: null
08-11 06:33:15.156  3954  3976 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39443e5,
08-11 06:33:15.156  3954  3976 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-11 06:33:15.157  3954  3954 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-11 06:33:15.157  3954  3954 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f87c4
08-11 06:33:15.158  3954  3954 D HealthService: Received start request. Starting profile...
,08-11 06:33:15.159  3954  3954 I bt_bluedroid: get_profile_interface health
08-11 06:33:15.160  3954  3954 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-11 06:33:15.161  3954  3954 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f87c4
08-11 06:33:15.161  3954  3954 D PanService: Received start request. Starting profile...
08-11 06:33:15.161  3954  3954 D BluetoothPanServiceJni: initializeNative(L110): pan
08-11 06:33:15.162  3954  3954 I bt_bluedroid: get_profile_interface pan
,08-11 06:33:15.162  3954  3976 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-11 06:33:15.169  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 06:33:15.173  3954  3954 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27f87c4
,08-11 06:33:15.173  3954  3954 D BluetoothMapService: Received start request. Starting profile...
08-11 06:33:15.173  3954  3954 D BluetoothMapService: start()
,08-11 06:33:15.176  3954  3954 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-11 06:33:15.181  3954  3954 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-11 06:33:15.181  3954  3954 D BluetoothMapAppObserver: createReceiver()
08-11 06:33:15.183  3954  3954 D BluetoothMapAppObserver: initObservers()
08-11 06:33:15.183  3954  3954 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-11 06:33:15.190  3954  3954 V BluetoothAdapterState: isTurningOff()=false
,08-11 06:33:15.190  3954  3954 V BluetoothAdapterState: isTurningOn()=true
08-11 06:33:15.190  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
08-11 06:33:15.191  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 06:33:15.191  3954  4045 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-11 06:33:15.193   872  1720 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,08-11 06:33:15.193  3954  3954 V BluetoothAdapterState: isTurningOff()=false
08-11 06:33:15.193  3954  3954 V BluetoothAdapterState: isTurningOn()=true
08-11 06:33:15.193  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
,08-11 06:33:15.193  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
08-11 06:33:15.193  3954  3954 V BluetoothAdapterState: isTurningOff()=false
08-11 06:33:15.194  3954  3954 V BluetoothAdapterState: isTurningOn()=true
,08-11 06:33:15.194  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
08-11 06:33:15.194  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
08-11 06:33:15.194  3954  3954 V BluetoothAdapterState: isTurningOff()=false
,08-11 06:33:15.194  3954  3954 V BluetoothAdapterState: isTurningOn()=true
08-11 06:33:15.194  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
08-11 06:33:15.195  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 06:33:15.195  3954  3954 V BluetoothAdapterState: isTurningOff()=false
08-11 06:33:15.195  3954  3954 V BluetoothAdapterState: isTurningOn()=true
08-11 06:33:15.195  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
08-11 06:33:15.195  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 06:33:15.196  3954  3954 V BluetoothAdapterState: isTurningOff()=false
08-11 06:33:15.197  3954  3954 V BluetoothAdapterState: isTurningOn()=true
08-11 06:33:15.197  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
,08-11 06:33:15.197  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 06:33:15.197  3954  3972 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-11 06:33:15.197  3954  3972 D BluetoothAdapterProperties: ScanMode =  20
08-11 06:33:15.197  3954  3972 D BluetoothAdapterProperties: State =  11
,08-11 06:33:15.200  3954  3976 D BluetoothAdapterProperties: Scan Mode:21
08-11 06:33:15.200  3954  3976 D BluetoothAdapterProperties: Discoverable Timeout:120
08-11 06:33:15.200  3954  3972 D BluetoothAdapterProperties: Setting state to 12
08-11 06:33:15.200  3954  3972 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-11 06:33:15.201  3954  3972 I BluetoothAdapterState: Entering OnState
08-11 06:33:15.201  3456  3472 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 06:33:15.202  3456  3469 D BluetoothA2dp: onBluetoothStateChange: up=true
08-11 06:33:15.205  3456  3472 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-11 06:33:15.205  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:33:15.205  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:33:15.205  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 06:33:15.205  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:33:15.205  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 06:33:15.205  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:33:15.205  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:33:15.205  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 06:33:15.207  3954  3954 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-11 06:33:15.207  3954  3954 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-11 06:33:15.208  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 06:33:15.208  1364  2007 D BluetoothPbap: onBluetoothStateChange: up=true
,08-11 06:33:15.209  3954  3954 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 06:33:15.212  3954  3954 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 06:33:15.212  3456  3469 D BluetoothMap: onBluetoothStateChange: up=true
08-11 06:33:15.213  3954  3954 D ObexServerSockets: Succeed to create listening sockets 
,08-11 06:33:15.213  3954  3954 D ObexServerSockets0: startAccept()
08-11 06:33:15.213  3954  3954 D ObexServerSockets0: prepareForNewConnect()
08-11 06:33:15.213  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:33:15.213  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:33:15.213  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 06:33:15.213  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:33:15.213  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 06:33:15.213  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:33:15.213  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:33:15.213  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 06:33:15.215  3954  3954 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-11 06:33:15.215  3954  3954 D BluetoothSdpJni: SDP Create record success - handle: 0
08-11 06:33:15.215  1364  1382 D BluetoothPan: onBluetoothStateChange on: true
08-11 06:33:15.215  3954  4057 D ObexServerSockets0: Accepting socket connection...
08-11 06:33:15.216  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 06:33:15.217  3456  3456 D BluetoothA2dp: Proxy object connected
,08-11 06:33:15.219  1364  1376 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-11 06:33:15.219  3954  4058 D ObexServerSockets0: Accepting socket connection...
,08-11 06:33:15.223  1364  1364 D BluetoothA2dp: Proxy object connected
,08-11 06:33:15.223   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-11 06:33:15.223  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:33:15.223  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:33:15.223  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 06:33:15.223  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:33:15.223  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 06:33:15.223  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:33:15.223  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:33:15.223  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 06:33:15.223  1364  1382 D BluetoothMap: onBluetoothStateChange: up=true
08-11 06:33:15.226  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
08-11 06:33:15.226  1364  1364 D PanProfile: Bluetooth service connected
08-11 06:33:15.227  1364  1364 D BluetoothMap: Proxy object connected
,08-11 06:33:15.227  1364  1364 D MapProfile: Bluetooth service connected
08-11 06:33:15.227  1364  1364 D BluetoothMap: getConnectedDevices()
08-11 06:33:15.227  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 06:33:15.227   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-11 06:33:15.228   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 06:33:15.228   872   872 D BluetoothA2dp: Proxy object connected
,08-11 06:33:15.228  3456  3472 D BluetoothPan: onBluetoothStateChange on: true
08-11 06:33:15.230  3456  3456 D BluetoothInputDevice: Proxy object connected
,08-11 06:33:15.230  3456  3456 D HidProfile: Bluetooth service connected
08-11 06:33:15.230  1364  2007 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 06:33:15.231   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 06:33:15.231  1717  1852 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-11 06:33:15.232  3456  3469 D BluetoothPbap: onBluetoothStateChange: up=true
,08-11 06:33:15.232  3456  3456 D BluetoothMap: Proxy object connected
,08-11 06:33:15.232  3456  3456 D MapProfile: Bluetooth service connected
08-11 06:33:15.232  3456  3456 D BluetoothMap: getConnectedDevices()
08-11 06:33:15.234  1364  1376 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-11 06:33:15.236  1364  1364 D BluetoothInputDevice: Proxy object connected
08-11 06:33:15.236  1364  1364 D HidProfile: Bluetooth service connected
,08-11 06:33:15.238   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-11 06:33:15.238  3954  3954 D BluetoothMapService: onReceive
,08-11 06:33:15.238  3954  3954 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-11 06:33:15.238  3954  3954 D BluetoothMapService: STATE_ON
08-11 06:33:15.240  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:33:15.241  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:33:15.243  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:33:15.243  3456  3456 D BluetoothPan: BluetoothPAN Proxy object connected
08-11 06:33:15.243  3456  3456 D PanProfile: Bluetooth service connected
,08-11 06:33:15.249  3456  3456 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-11 06:33:15.256  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 06:33:15.261  3985  3985 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-11 06:33:15.266  1364  1364 D BluetoothPbap: Proxy object connected
08-11 06:33:15.266  3456  3456 D DockEventReceiver: finishStartingService: stopping service
,08-11 06:33:15.266  1364  1364 D PbapServerProfile: Bluetooth service connected
08-11 06:33:15.266  3954  3954 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-11 06:33:15.266  3954  3954 D ObexServerSockets0: prepareForNewConnect()
,08-11 06:33:15.269  3456  3456 D BluetoothPbap: Proxy object connected
,08-11 06:33:15.269  3456  3456 D PbapServerProfile: Bluetooth service connected
08-11 06:33:15.273  3954  4066 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 06:33:15.291  3997  4055 I Gmail   : Observing account changes for notifications
,08-11 06:33:15.295  3954  4070 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 06:33:15.296  3954  4070 I BtOppRfcommListener: Accept thread started.
,08-11 06:33:15.302  3985  3985 I Exchange: EasService.onCreate
,08-11 06:33:15.302  3456  3472 D BluetoothHeadset: Proxy object connected
,08-11 06:33:15.303  3456  3456 D HeadsetProfile: Bluetooth service connected
08-11 06:33:15.303  1717  1733 D BluetoothHeadset: Proxy object connected
08-11 06:33:15.303   872   872 D BluetoothHeadset: Proxy object connected
,08-11 06:33:15.303  1364  2007 D BluetoothHeadset: Proxy object connected
,08-11 06:33:15.304  1364  1364 D HeadsetProfile: Bluetooth service connected
08-11 06:33:15.304   872   872 D BluetoothHeadset: Proxy object connected
08-11 06:33:15.304   872   872 D BluetoothHeadset: Proxy object connected
,08-11 06:33:15.310  3985  4072 I Exchange: RestartPingTask
,08-11 06:33:15.324   872   889 D BluetoothHeadset: Proxy object connected
,08-11 06:33:15.327  3985  3985 I Exchange: RestartPingsTask did not start any pings.
,08-11 06:33:15.327  3985  3985 I Exchange: PSS stopIfIdle
08-11 06:33:15.327  3985  3985 I Exchange: PSS has no active accounts; stopping service.
,08-11 06:33:15.328  3985  3985 I Exchange: onDestroy
,08-11 06:33:15.329   872   889 D BluetoothHeadset: Proxy object connected
,08-11 06:33:15.330  1364  1376 D BluetoothHeadset: Proxy object connected
,08-11 06:33:15.330  1364  1364 D HeadsetProfile: Bluetooth service connected
,08-11 06:33:15.332   872   889 D BluetoothHeadset: Proxy object connected
,08-11 06:33:15.332  1717  1732 D BluetoothHeadset: Proxy object connected
,08-11 06:33:18.678   872   883 I ActivityManager: Killing 3678:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,08-11 06:33:18.860  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 06:33:18.861  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 06:33:18.919   872   882 I ActivityManager: Killing 3412:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
,08-11 06:33:20.070  3997  4033 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-11 06:33:20.332  3985  4063 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-11 06:33:23.865  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 06:33:23.865  3332  3382 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@97e0fe3 removed from the list
,08-11 06:33:23.866  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
08-11 06:33:23.866  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 06:33:23.866  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 06:33:23.868  3332  3382 I System.out: Running UT from: ConnectivityMonitorTest
,08-11 06:33:23.868  3332  3382 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 06:33:23.869  3332  3382 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@af7c73f added. We now have 4 listener(s)
,08-11 06:33:23.869  3332  3382 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 06:33:23.872  3332  3382 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 06:33:23.872  3332  3382 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@af7c73f removed from the list
08-11 06:33:23.872  3332  3382 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 06:33:23.872  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 06:33:23.873  3332  3382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 06:33:23.874  3332  3382 I System.out: Running UT from: ConnectivityMonitorTest
,08-11 06:33:23.874  3332  3382 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-11 06:33:23.875  3332  3382 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ef380c added. We now have 4 listener(s)
08-11 06:33:23.875  3332  3382 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 06:33:23.877  3332  3382 I System.out: IsBluetoothEnabled
,08-11 06:33:23.884  3954  3972 D BluetoothAdapterState: Current state: ON, message: 23
08-11 06:33:23.884  3954  3972 D BluetoothAdapterProperties: Setting state to 13
,08-11 06:33:23.884  3954  3972 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-11 06:33:23.886  3954  3972 D BluetoothAdapterProperties: onBluetoothDisable()
,08-11 06:33:23.887  3954  3972 I BluetoothAdapterState: Entering PendingCommandState
,08-11 06:33:23.906  3954  3954 D BluetoothMapService: onReceive
08-11 06:33:23.906  3954  3954 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-11 06:33:23.907  3954  3976 D BluetoothAdapterProperties: Scan Mode:20
08-11 06:33:23.907  3954  3954 D BluetoothMapService: STATE_TURNING_OFF
,08-11 06:33:23.907  3954  3972 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-11 06:33:23.907  3954  3954 D BluetoothMapService: MAP Service closeService in
08-11 06:33:23.907  3954  3954 D BluetoothMapMasInstance0: MAP Service shutdown
08-11 06:33:23.907  3954  3954 D ObexServerSockets0: shutdown(block = true)
,08-11 06:33:23.909  3954  3954 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-11 06:33:23.909  3954  4058 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-11 06:33:23.909  3332  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:33:23.909  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:33:23.909  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:33:23.909  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 06:33:23.909  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:33:23.909  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 06:33:23.909  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:33:23.909  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:33:23.909  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 06:33:23.910  3954  4042 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-11 06:33:23.911  3954  3954 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-11 06:33:23.912  3332  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:33:23.912  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 06:33:23.912  3954  4057 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-11 06:33:23.914  3456  3456 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-11 06:33:23.915  3332  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:33:23.915  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:33:23.915  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:33:23.915  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 06:33:23.915  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:33:23.915  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 06:33:23.915  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:33:23.915  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:33:23.915  3332  3332 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 06:33:23.915  3954  3954 D HeadsetService: Received stop request...Stopping profile...
08-11 06:33:23.916  3332  3332 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 06:33:23.916  3332  3332 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 06:33:23.916  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 06:33:23.916  3332  3382 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 06:33:23.916  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 06:33:23.916  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 06:33:23.916  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 06:33:23.916  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 06:33:23.916  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 06:33:23.916  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 06:33:23.916  3332  3382 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 06:33:23.917  3332  3382 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 06:33:23.917  3332  3382 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 06:33:23.920  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:33:23.921  3456  3472 D BluetoothHeadset: Proxy object disconnected
,08-11 06:33:23.922  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:33:23.922  1717  1733 D BluetoothHeadset: Proxy object disconnected
08-11 06:33:23.922  3954  3954 I BtOppRfcommListener: stopping Accept Thread
08-11 06:33:23.922   872   872 D BluetoothHeadset: Proxy object disconnected
08-11 06:33:23.922  3954  4070 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 06:33:23.923  1364  1382 D BluetoothHeadset: Proxy object disconnected
,08-11 06:33:23.923  3954  4070 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-11 06:33:23.923   872   872 D BluetoothHeadset: Proxy object disconnected
08-11 06:33:23.923   872   872 D BluetoothHeadset: Proxy object disconnected
,08-11 06:33:23.923  3954  3972 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
08-11 06:33:23.923  3954  3972 I BluetoothAdapterState: Deferring BLE_TURN_ON request...
08-11 06:33:23.924  3954  3954 D A2dpService: Received stop request...Stopping profile...
08-11 06:33:23.924  3954  4050 D A2dpStateMachine: Exit Disconnected: -1
08-11 06:33:23.925   872   872 D BluetoothA2dp: Proxy object disconnected
08-11 06:33:23.928  3954  3954 D HidService: Received stop request...Stopping profile...
,08-11 06:33:23.928  3954  3954 D HidService: Stopping Bluetooth HidService
08-11 06:33:23.929  1364  1364 D HeadsetProfile: Bluetooth service disconnected
08-11 06:33:23.930  1364  1364 D BluetoothA2dp: Proxy object disconnected
08-11 06:33:23.930  1364  1364 D BluetoothInputDevice: Proxy object disconnected
08-11 06:33:23.930  3954  3954 D HealthService: Received stop request...Stopping profile...
,08-11 06:33:23.930  1364  1364 D HidProfile: Bluetooth service disconnected
08-11 06:33:23.931  3954  3954 D PanService: Received stop request...Stopping profile...
08-11 06:33:23.931  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-11 06:33:23.931  1364  1364 D PanProfile: Bluetooth service disconnected
,08-11 06:33:23.932  3954  3954 V BluetoothAdapterState: isTurningOff()=true
08-11 06:33:23.932  3954  3954 V BluetoothAdapterState: isTurningOn()=false
08-11 06:33:23.932  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
08-11 06:33:23.932  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 06:33:23.933  3954  3954 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-11 06:33:23.933  3954  3954 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-11 06:33:23.933  3954  3976 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-11 06:33:23.933  3954  4029 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 06:33:23.933  3954  4029 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 06:33:23.933  3954  4029 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 06:33:23.933  3954  3976 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-11 06:33:23.934  3456  3456 D DockEventReceiver: finishStartingService: stopping service
08-11 06:33:23.934  3954  3954 D BluetoothMapService: Received stop request...Stopping profile...
08-11 06:33:23.934  3954  3954 D BluetoothMapService: stop()
08-11 06:33:23.935  3954  3954 D BluetoothMapAppObserver: deinitObservers()
,08-11 06:33:23.935  3954  3954 D BluetoothMapAppObserver: removeReceiver()
,08-11 06:33:23.936  1364  1364 D BluetoothMap: Proxy object disconnected
08-11 06:33:23.936  1364  1364 D MapProfile: Bluetooth service disconnected
08-11 06:33:23.937  3456  3456 D HeadsetProfile: Bluetooth service disconnected
08-11 06:33:23.937  3456  3456 D BluetoothA2dp: Proxy object disconnected
,08-11 06:33:23.938  3456  3456 D BluetoothInputDevice: Proxy object disconnected
,08-11 06:33:23.938  3456  3456 D HidProfile: Bluetooth service disconnected
,08-11 06:33:23.938  3456  3456 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-11 06:33:23.938  3456  3456 D PanProfile: Bluetooth service disconnected
08-11 06:33:23.940  3456  3456 D BluetoothMap: Proxy object disconnected
08-11 06:33:23.940  3456  3456 D MapProfile: Bluetooth service disconnected
,08-11 06:33:23.941  3954  3954 V BluetoothAdapterState: isTurningOff()=true
,08-11 06:33:23.941  3954  3954 V BluetoothAdapterState: isTurningOn()=false
,08-11 06:33:23.941  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
,08-11 06:33:23.941  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
08-11 06:33:23.942  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-11 06:33:23.942  3954  3976 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-11 06:33:23.942  3954  4029 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 06:33:23.942  3954  4029 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 06:33:23.943  3954  4029 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-11 06:33:23.943  3954  4029 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 06:33:23.943  3954  4029 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 06:33:23.943  3954  4029 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 06:33:23.943  3954  3954 V BluetoothAdapterState: isTurningOff()=true
,08-11 06:33:23.943  3954  3954 V BluetoothAdapterState: isTurningOn()=false
08-11 06:33:23.943  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
08-11 06:33:23.943  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
08-11 06:33:23.943  3954  3954 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-11 06:33:23.944  3954  3976 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-11 06:33:23.944  3954  3954 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-11 06:33:23.944  3954  3954 V BluetoothAdapterState: isTurningOff()=true
,08-11 06:33:23.944  3954  3954 V BluetoothAdapterState: isTurningOn()=false
08-11 06:33:23.944  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
,08-11 06:33:23.944  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 06:33:23.944  3954  3954 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-11 06:33:23.944  3954  3976 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-11 06:33:23.944  3954  3954 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-11 06:33:23.945  3954  3954 V BluetoothAdapterState: isTurningOff()=true
,08-11 06:33:23.945  3954  3954 V BluetoothAdapterState: isTurningOn()=false
08-11 06:33:23.945  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
08-11 06:33:23.945  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
08-11 06:33:23.945  3954  3954 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-11 06:33:23.946  3954  3954 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-11 06:33:23.947  3954  3954 D BluetoothMapService: MAP Service closeService in
08-11 06:33:23.947  3954  3954 V BluetoothAdapterState: isTurningOff()=true
,08-11 06:33:23.947  3954  3954 V BluetoothAdapterState: isTurningOn()=false
,08-11 06:33:23.947  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
,08-11 06:33:23.947  3954  3954 V BluetoothAdapterState: isBleTurningOff()=false
08-11 06:33:23.947  3954  3954 D BluetoothMapService: cleanup()
08-11 06:33:23.947  3954  3954 D BluetoothMapService: MAP Service closeService in
,08-11 06:33:23.948  3954  3972 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-11 06:33:23.948  3954  3972 D BluetoothAdapterProperties: Setting state to 15
,08-11 06:33:23.948  3954  3972 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-11 06:33:23.948  3954  3972 I BluetoothAdapterState: Entering BleOnState
08-11 06:33:23.948  3954  3972 D BluetoothAdapterState: Current state: BLE ON, message: 0
08-11 06:33:23.949  3456  4056 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-11 06:33:23.949  3456  3472 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-11 06:33:23.949  1364  1364 D BluetoothPbap: Proxy object disconnected
,08-11 06:33:23.949  1364  1364 D PbapServerProfile: Bluetooth service disconnected
08-11 06:33:23.949  3456  3469 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-11 06:33:23.950  1364  1376 D BluetoothPbap: onBluetoothStateChange: up=false
08-11 06:33:23.950  3456  3456 D BluetoothPbap: Proxy object disconnected
08-11 06:33:23.950  3456  3456 D PbapServerProfile: Bluetooth service disconnected
08-11 06:33:23.953  3456  3472 D BluetoothMap: onBluetoothStateChange: up=false
08-11 06:33:23.953  1364  1382 D BluetoothPan: onBluetoothStateChange on: false
08-11 06:33:23.954  1364  2007 D BluetoothA2dp: onBluetoothStateChange: up=false
08-11 06:33:23.954   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 06:33:23.955  1364  1376 D BluetoothMap: onBluetoothStateChange: up=false
,08-11 06:33:23.955   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-11 06:33:23.955   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 06:33:23.955  3456  3469 D BluetoothPan: onBluetoothStateChange on: false
,08-11 06:33:23.956  1364  1382 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 06:33:23.956   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 06:33:23.956  1717  1732 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 06:33:23.956  3456  4056 D BluetoothPbap: onBluetoothStateChange: up=false
08-11 06:33:23.957  1364  2007 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-11 06:33:23.957  3954  3972 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-11 06:33:23.958  3954  3972 D BluetoothAdapterProperties: Setting state to 16
08-11 06:33:23.958  3954  3972 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-11 06:33:23.958  3954  3972 D BluetoothAdapterProperties: onBleDisable
08-11 06:33:23.958  3954  3972 I BluetoothAdapterState: Entering PendingCommandState
08-11 06:33:23.958  3954  3973 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-11 06:33:23.959  3954  4029 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-11 06:33:23.959  3954  4029 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-11 06:33:23.960  3954  3976 D BluetoothAdapterProperties: Scan Mode:20
08-11 06:33:23.965  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:33:23.966  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-11 06:33:23.966  3456  3456 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-11 06:33:23.967  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:33:23.968  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 06:33:23.971  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 06:33:23.978  3456  3456 D DockEventReceiver: finishStartingService: stopping service
,08-11 06:33:24.165  3954  3976 I bt_hci  : shut_down
,08-11 06:33:24.175  3954  3982 D bt_hwcfg: hw_epilog_process
,08-11 06:33:24.176  3954  3982 I bt_vendor: low_power_mode_cb
,08-11 06:33:24.203  3954  3982 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-11 06:33:24.203  3954  3982 I bt_vendor: epilog_cb
08-11 06:33:24.203  3954  3982 I bt_hci  : epilog_finished_callback
,08-11 06:33:24.211  3954  3976 I bt_hci_h4: hal_close
,08-11 06:33:24.212  3954  3976 I bt_userial_vendor: device fd = 51 close
,08-11 06:33:24.343  3954  3973 D bt_stack_manager: event_shut_down_stack finished.
,08-11 06:33:24.344  3954  3972 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-11 06:33:24.350  3954  3954 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-11 06:33:24.351  3954  3972 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-11 06:33:24.352  3954  3954 D BtGatt.GattService: Received stop request...Stopping profile...
,08-11 06:33:24.352  3954  3954 D BtGatt.GattService: stop()
08-11 06:33:24.352  3954  3954 D BtGatt.AdvertiseManager: advertise clients cleared
08-11 06:33:24.357  3954  3954 V BluetoothAdapterState: isTurningOff()=false
,08-11 06:33:24.357  3954  3954 V BluetoothAdapterState: isTurningOn()=false
08-11 06:33:24.357  3954  3954 V BluetoothAdapterState: isBleTurningOn()=false
,08-11 06:33:24.358  3954  3954 V BluetoothAdapterState: isBleTurningOff()=true
08-11 06:33:24.359  3954  3972 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-11 06:33:24.359  3954  3972 D BluetoothAdapterProperties: Setting state to 10
08-11 06:33:24.359  3954  3972 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-11 06:33:24.363  3954  3972 I BluetoothAdapterState: Entering OffState
,08-11 06:33:24.376  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 06:33:24.380  3332  3332 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 06:33:24.380  3456  3456 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-11 06:33:24.390  3456  3456 D DockEventReceiver: finishStartingService: stopping service
,08-11 06:33:24.393  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 06:33:35.908  1650  1778 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-11 06:33:35.909  1650  1778 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-11 06:33:35.945  1499  1499 I ConfigService: onCreate
,08-11 06:33:40.410  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:33:40.416  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:33:40.421  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:33:40.450  1499  2048 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-11 06:33:40.450  1499  2048 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-11 06:33:40.450  1499  2048 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 06:33:40.450  1499  2048 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 06:33:40.489  2581  2581 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-11 06:33:40.490  2581  2581 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-11 06:33:40.490  2581  2581 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-11 06:33:41.020  1499  1499 I ConfigService: onDestroy
,08-11 06:34:04.093   872  1310 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-11 06:35:01.981  1499  2010 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-11 06:35:36.948  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:35:36.955  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:35:36.957  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:35:37.002  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-11 06:35:37.002  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-11 06:35:37.002  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 06:35:37.003  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 06:35:37.032  1499  1510 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-11 06:35:37.032  1499  1510 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 06:35:37.032  1499  1510 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 06:35:37.032  1499  1510 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-11 06:35:37.032  1499  1510 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-11 06:35:37.032  1499  1510 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-11 06:35:37.032  1499  1510 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-11 06:35:37.041  2581  2614 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-11 06:35:37.041  2581  2614 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-11 06:35:37.041  2581  2614 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-11 06:35:37.041  2581  2614 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-11 06:35:37.041  2581  2614 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-11 06:35:37.041  2581  2614 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-11 06:35:37.041  2581  2614 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-11 06:38:03.004  1863  3872 V NativeCrypto: SSL shutdown failed: ssl=0x90df8e00: I/O error during system call, Connection timed out
,08-11 06:40:37.203  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:40:37.227  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:40:37.234  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:40:37.321  1499  2659 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-11 06:40:37.321  1499  2659 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-11 06:40:37.322  1499  2659 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 06:40:37.324  1499  2659 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 06:40:37.377  1499  2659 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-11 06:40:37.377  1499  2659 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 06:40:37.377  1499  2659 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 06:40:37.377  1499  2659 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-11 06:40:37.377  1499  2659 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-11 06:40:37.377  1499  2659 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-11 06:40:37.377  1499  2659 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-11 06:40:37.394  2581  2614 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-11 06:40:37.394  2581  2614 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-11 06:40:37.394  2581  2614 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-11 06:40:37.394  2581  2614 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-11 06:40:37.394  2581  2614 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-11 06:40:37.394  2581  2614 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-11 06:40:37.394  2581  2614 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-11 06:45:37.537  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:45:37.550  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:45:37.554  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:45:37.633  1499  2659 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-11 06:45:37.633  1499  2659 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-11 06:45:37.633  1499  2659 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 06:45:37.634  1499  2659 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 06:45:37.684  1499  2659 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.,
08-11 06:45:37.684  1499  2659 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 06:45:37.684  1499  2659 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 06:45:37.684  1499  2659 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-11 06:45:37.684  1499  2659 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-11 06:45:37.684  1499  2659 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-11 06:45:37.684  1499  2659 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-11 06:45:37.700  2581  2614 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-11 06:45:37.700  2581  2614 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-11 06:45:37.700  2581  2614 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-11 06:45:37.700  2581  2614 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-11 06:45:37.700  2581  2614 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-11 06:45:37.700  2581  2614 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-11 06:45:37.700  2581  2614 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-11 06:50:24.149   872   884 I UsageStatsService: User[0] Flushing usage stats to disk
,08-11 06:50:37.855  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:50:37.873  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:50:37.879  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:50:37.964  1499  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-11 06:50:37.964  1499  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-11 06:50:37.965  1499  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 06:50:37.965  1499  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 06:50:38.006  1499  1511 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-11 06:50:38.006  1499  1511 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 06:50:38.006  1499  1511 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 06:50:38.006  1499  1511 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-11 06:50:38.006  1499  1511 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-11 06:50:38.006  1499  1511 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-11 06:50:38.006  1499  1511 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-11 06:50:38.016  2581  2614 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-11 06:50:38.016  2581  2614 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-11 06:50:38.016  2581  2614 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-11 06:50:38.016  2581  2614 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-11 06:50:38.016  2581  2614 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-11 06:50:38.016  2581  2614 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-11 06:50:38.016  2581  2614 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-11 06:55:38.161  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:55:38.179  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:55:38.185  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 06:55:38.262  1499  2659 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-11 06:55:38.262  1499  2659 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-11 06:55:38.262  1499  2659 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 06:55:38.263  1499  2659 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 06:55:38.306  1499  2659 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-11 06:55:38.306  1499  2659 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 06:55:38.306  1499  2659 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 06:55:38.306  1499  2659 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-11 06:55:38.306  1499  2659 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-11 06:55:38.306  1499  2659 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-11 06:55:38.306  1499  2659 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-11 06:55:38.315  2581  2614 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-11 06:55:38.315  2581  2614 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-11 06:55:38.315  2581  2614 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-11 06:55:38.315  2581  2614 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-11 06:55:38.315  2581  2614 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-11 06:55:38.315  2581  2614 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-11 06:55:38.315  2581  2614 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms),08-11 06:55:45.670  4171  4171 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-11 06:55:45.675  4171  4171 D AndroidRuntime: CheckJNI is OFF
08-11 06:55:45.711  4171  4171 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-11 06:55:45.750  4171  4171 I Radio-JNI: register_android_hardware_Radio DONE
08-11 06:55:45.772  4171  4171 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-11 06:55:45.793   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-11 06:55:45.793   872   885 I ActivityManager: Killing 3332:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-11 06:55:45.897   872  1738 D GraphicsStats: Buffer count: 2
08-11 06:55:45.898   872  1720 I WindowState: WIN DEATH: Window{dbd7444 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 06:55:45.899   872  1309 D WifiService: Client connection lost with reason: 4
08-11 06:55:45.909   872   895 W PackageSettings: Skipping PackageSetting{23bef81 com.example.hello/10273} due to missing metadata
08-11 06:55:45.944   872   895 I art     : Starting a blocking GC Explicit
08-11 06:55:45.942   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-11 06:55:45.946   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-11 06:55:45.950   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-11 06:55:45.950   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-11 06:55:45.950   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-11 06:55:45.950   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-11 06:55:45.950   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-11 06:55:45.950   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-11 06:55:45.950   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-11 06:55:45.950   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-11 06:55:45.950   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-11 06:55:45.950   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-11 06:55:45.950   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-11 06:55:45.950   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-11 06:55:45.950   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-11 06:55:45.950   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-11 06:55:45.950   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-11 06:55:45.950   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-11 06:55:45.950   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 06:55:45.950   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-11 06:55:45.950   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 06:55:45.950   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-11 06:55:45.952   872   885 I ActivityManager:   Force finishing activity ActivityRecord{623b395 u0 com.test.thalitest/.MainActivity t8}
08-11 06:55:45.968   872  1703 W ActivityManager: Spurious death for ProcessRecord{ffdaf7a 0:com.test.thalitest/u0a0}, curProc for 3332: null
08-11 06:55:45.994   872   895 I art     : Explicit concurrent mark sweep GC freed 37071(2MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 689us total 49.161ms
08-11 06:55:46.033   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-11 06:55:46.036  4171  4171 I art     : System.exit called, status: 0
08-11 06:55:46.036  4171  4171 I AndroidRuntime: VM exiting with result code 0.
08-11 06:55:46.050   872   895 I ActivityManager: Start proc 4184:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-11 06:55:46.050   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-11 06:55:46.071   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-11 06:55:46.083   872  1297 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-11 06:55:46.086  3205  3205 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-11 06:55:46.090  1650  1650 I Keyboard.Facilitator: resetDictionaries() : en_US
08-11 06:55:46.090  1821  2019 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-11 06:55:46.096  1650  4197 I Keyboard.Facilitator.DecoderInitializer: run()
08-11 06:55:46.121  1717  1717 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-11 06:55:46.122  1650  4197 I Decoder : createOrResetDecoder
08-11 06:55:46.159   872   882 I ActivityManager: Start proc 4201:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-11 06:55:46.179  1499  1499 I ConfigService: onCreate
08-11 06:55:46.180  3936  3966 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjF2F2C5900) - 
--------- beginning of crash
08-11 06:55:46.184  3936  3966 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
08-11 06:55:46.184  3936  3966 E AndroidRuntime: Process: android.process.acore, PID: 3936
08-11 06:55:46.184  3936  3966 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
08-11 06:55:46.184  3936  3966 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-11 06:55:46.184  3936  3966 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-11 06:55:46.184  3936  3966 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
08-11 06:55:46.184  3936  3966 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
08-11 06:55:46.184  3936  3966 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
08-11 06:55:46.184  3936  3966 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
08-11 06:55:46.184  3936  3966 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
08-11 06:55:46.184  3936  3966 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
08-11 06:55:46.184  3936  3966 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-11 06:55:46.184  3936  3966 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 06:55:46.184  3936  3966 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 06:55:46.184  3936  3966 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 06:55:46.187  3936  4200 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-11 06:55:46.193  1499  4212 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-11 06:55:46.193  1499  4212 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 06:55:46.193  1499  4212 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 06:55:46.193  1499  4212 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 06:55:46.193  1499  4212 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 06:55:46.193  1499  4212 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 06:55:46.193  1499  4212 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 06:55:46.193  1499  4212 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 06:55:46.193  1499  4212 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 06:55:46.193  1499  4212 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 06:55:46.193  1499  4212 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 06:55:46.193  1499  4212 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 06:55:46.193  1499  4212 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 06:55:46.193  1499  4212 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 06:55:46.193  1499  4212 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 06:55:46.193  1499  4212 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-11 06:55:46.193  1499  4212 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-11 06:55:46.193  1499  4212 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-11 06:55:46.194   872  2016 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3332 uid 10000
08-11 06:55:46.195  1650  1650 I Keyboard.Facilitator: onFinishInput()
08-11 06:55:46.198  4201  4201 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-11 06:55:46.200  1499  4212 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-11 06:55:46.200  1499  4212 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 06:55:46.200  1499  4212 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 06:55:46.200  1499  4212 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 06:55:46.200  1499  4212 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 06:55:46.200  1499  4212 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 06:55:46.200  1499  4212 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 06:55:46.200  1499  4212 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 06:55:46.200  1499  4212 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 06:55:46.200  1499  4212 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 06:55:46.200  1499  4212 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 06:55:46.200  1499  4212 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 06:55:46.200  1499  4212 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 06:55:46.200  1499  4212 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 06:55:46.200  1499  4212 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 06:55:46.200  1499  4212 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-11 06:55:46.200  1499  4212 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-11 06:55:46.200  1499  4212 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-11 06:55:46.205   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-11 06:55:46.210  1499  4212 W SQLiteOpenHelper: Opened config.db in read-only mode
08-11 06:55:46.236  1739  1850 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-11 06:55:46.237   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-11 06:55:46.238   872   884 E PackageManager: Failed to write settings, restoring backup
08-11 06:55:46.238   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-11 06:55:46.238   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-11 06:55:46.238   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-11 06:55:46.238   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-11 06:55:46.238   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-11 06:55:46.238   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 06:55:46.238   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-11 06:55:46.238   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 06:55:46.242   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-11 06:55:46.242   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-11 06:55:46.242   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 06:55:46.242   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 06:55:46.242   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 06:55:46.242   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 06:55:46.242   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 06:55:46.242   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 06:55:46.242   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-11 06:55:46.242   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-11 06:55:46.242   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-11 06:55:46.242   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 06:55:46.242   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 06:55:46.242   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-11 06:55:46.242   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 06:55:46.242   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-11 06:55:46.242   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 06:55:46.242   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 06:55:46.242   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 06:55:46.242   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 06:55:46.242   872   885 E DropBoxManagerService: 	... 13 more
08-11 06:55:46.250   872   883 I ActivityManager: Start proc 4214:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-11 06:55:46.251  1739  1850 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-11 06:55:46.251  1739  1850 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1739
08-11 06:55:46.251  1739  1850 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 06:55:46.251  1739  1850 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 06:55:46.251  1739  1850 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-11 06:55:46.251  1739  1850 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-11 06:55:46.251  1739  1850 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 06:55:46.251  1739  1850 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-11 06:55:46.251  1739  1850 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-11 06:55:46.251  1739  1850 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-11 06:55:46.251  1739  1850 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 06:55:46.251  1739  1850 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 06:55:46.251  1739  1850 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 06:55:46.251  1739  1850 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 06:55:46.253   872  1738 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-11 06:55:46.253   872  4221 E DropBoxManagerService: Can't write: system_app_crash
08-11 06:55:46.253   872  4221 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
08-11 06:55:46.253   872  4221 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 06:55:46.253   872  4221 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 06:55:46.253   872  4221 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 06:55:46.253   872  4221 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 06:55:46.253   872  4221 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 06:55:46.253   872  4221 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 06:55:46.253   872  4221 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 06:55:46.253   872  4221 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 06:55:46.253   872  4221 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 06:55:46.253   872  4221 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 06:55:46.253   872  4221 E DropBoxManagerService: 	... 5 more
08-11 06:55:46.256  1739  1850 I Process : Sending signal. PID: 1739 SIG: 9
08-11 06:55:46.277  1650  4197 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-11 06:55:46.291   872  4228 E DropBoxManagerService: Can't write: system_app_crash
08-11 06:55:46.291   872  4228 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
08-11 06:55:46.291   872  4228 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 06:55:46.291   872  4228 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 06:55:46.291   872  4228 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 06:55:46.291   872  4228 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 06:55:46.291   872  4228 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 06:55:46.291   872  4228 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 06:55:46.291   872  4228 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 06:55:46.291   872  4228 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 06:55:46.291   872  4228 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 06:55:46.291   872  4228 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 06:55:46.291   872  4228 E DropBoxManagerService: 	... 5 more
08-11 06:55:46.297  3936  3966 I Process : Sending signal. PID: 3936 SIG: 9
08-11 06:55:46.315   278   278 E lowmemorykiller: Error writing /proc/3936/oom_score_adj; errno=22
08-11 06:55:46.315   872  1725 I ActivityManager: Killing 2871:com.google.android.keep/u0a79 (adj 15): empty #17
08-11 06:55:46.330  1650  4197 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-11 06:55:46.332  1650  4197 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-11 06:55:46.333  1650  4197 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-11 06:55:46.334  1650  4197 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-11 06:55:46.335  1650  4197 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-11 06:55:46.337  1650  4197 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-11 06:55:46.337  1650  4197 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-11 06:55:46.341  1650  4197 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-11 06:55:46.341  1650  4197 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-11 06:55:46.341  1650  4197 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-11 06:55:46.341  1650  4197 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-11 06:55:46.341  1650  4197 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-11 06:55:46.341  1650  4197 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-11 06:55:46.345  1499  1499 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-11 06:55:46.346  1499  1499 D AndroidRuntime: Shutting down VM
08-11 06:55:46.348  1499  1499 E AndroidRuntime: FATAL EXCEPTION: main
08-11 06:55:46.348  1499  1499 E AndroidRuntime: Process: com.google.process.gapps, PID: 1499
08-11 06:55:46.348  1499  1499 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 06:55:46.348  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-11 06:55:46.348  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-11 06:55:46.348  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-11 06:55:46.348  1499  1499 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 06:55:46.348  1499  1499 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 06:55:46.348  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 06:55:46.348  1499  1499 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 06:55:46.348  1499  1499 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 06:55:46.348  1499  1499 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 06:55:46.348  1499  1499 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 06:55:46.348  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 06:55:46.348  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-11 06:55:46.348  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-11 06:55:46.348  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 06:55:46.348  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-11 06:55:46.348  1499  1499 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-11 06:55:46.348  1499  1499 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-11 06:55:46.348  1499  1499 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-11 06:55:46.348  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-11 06:55:46.348  1499  1499 E AndroidRuntime: 	... 8 more
08-11 06:55:46.352   872  1706 D GraphicsStats: Buffer count: 1
08-11 06:55:46.353   872  1375 I WindowState: WIN DEATH: Window{7dc3f07 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-11 06:55:46.371   872   883 I ActivityManager: Process android.process.acore (pid 3936) has died
08-11 06:55:46.371   872   883 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
08-11 06:55:46.373   872  1734 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1739) has died
08-11 06:55:46.373   872  1734 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-11 06:55:46.375   872  1734 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-11 06:55:46.385   872  4233 E DropBoxManagerService: Can't write: system_app_crash
08-11 06:55:46.385   872  4233 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
08-11 06:55:46.385   872  4233 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 06:55:46.385   872  4233 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 06:55:46.385   872  4233 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 06:55:46.385   872  4233 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 06:55:46.385   872  4233 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 06:55:46.385   872  4233 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 06:55:46.385   872  4233 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 06:55:46.385   872  4233 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 06:55:46.385   872  4233 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 06:55:46.385   872  4233 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 06:55:46.385   872  4233 E DropBoxManagerService: 	... 5 more
08-11 06:55:46.394   872   885 I ActivityManager: Start proc 4234:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-11 06:55:46.401  1499  1499 I Process : Sending signal. PID: 1499 SIG: 9
08-11 06:55:46.441  1863  4247 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 352)
08-11 06:55:46.442  1863  4247 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@8724dab
08-11 06:55:46.442   872   883 I ActivityManager: Process com.google.process.gapps (pid 1499) early provider death
08-11 06:55:46.451   872  1309 D WifiService: Client connection lost with reason: 4
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 06:55:46.455  4234  4234 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 06:55:46.455  4234  4234 D AndroidRuntime: Shutting down VM
08-11 06:55:46.458   872   883 I ActivityManager: Process com.google.process.gapps (pid 1499) has died
08-11 06:55:46.459   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
08-11 06:55:46.459   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 10999ms
08-11 06:55:46.459   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 20999ms
08-11 06:55:46.459   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 30999ms
08-11 06:55:46.460   872  1738 W ActivityManager: Spurious death for ProcessRecord{8b77540 0:com.google.process.gapps/u0a11}, curProc for 1499: null
08-11 06:55:46.466  1863  1863 W RocketImpressions: ClearcutLogger connection suspended: 1
08-11 06:55:46.488   872  1706 I ActivityManager: Start proc 4248:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
08-11 06:55:46.493  4234  4234 E AndroidRuntime: FATAL EXCEPTION: main
08-11 06:55:46.493  4234  4234 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4234
08-11 06:55:46.493  4234  4234 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-11 06:55:46.493  4234  4234 E AndroidRuntime: 	... 10 more
08-11 06:55:46.495   872  1738 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-11 06:55:46.497  4234  4234 I Process : Sending signal. PID: 4234 SIG: 9
08-11 06:55:46.499   872  4257 E DropBoxManagerService: Can't write: system_app_crash
08-11 06:55:46.499   872  4257 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
08-11 06:55:46.499   872  4257 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 06:55:46.499   872  4257 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 06:55:46.499   872  4257 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 06:55:46.499   872  4257 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 06:55:46.499   872  4257 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 06:55:46.499   872  4257 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 06:55:46.499   872  4257 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 06:55:46.499   872  4257 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 06:55:46.499   872  4257 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 06:55:46.499   872  4257 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 06:55:46.499   872  4257 E DropBoxManagerService: 	... 5 more
08-11 06:55:46.526   872  1703 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4234) has died
08-11 06:55:46.527   872  1703 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-11 06:55:46.534   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
