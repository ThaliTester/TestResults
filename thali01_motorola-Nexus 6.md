#### Test 79751015d87d04c_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-10 15:08:25.291  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:08:25.305  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 15:08:25.312  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 15:08:25.365  1523  1920 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-10 15:08:25.365  1523  1920 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 15:08:25.365  1523  1920 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:08:25.366  1523  1920 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-10 15:08:25.405  2602  2602 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-10 15:08:25.406  2602  2602 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-10 15:08:25.406  2602  2602 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-10 15:08:26.030  3325  3325 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-10 15:08:26.035  3325  3325 D AndroidRuntime: CheckJNI is OFF
08-10 15:08:26.071  3325  3325 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-10 15:08:26.113  3325  3325 I Radio-JNI: register_android_hardware_Radio DONE
08-10 15:08:26.134  3325  3325 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-10 15:08:26.139   875   885 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-10 15:08:26.185  1820  2022 W SearchService: Abort, client detached.
08-10 15:08:26.199  3325  3325 D AndroidRuntime: Shutting down VM
08-10 15:08:26.202  1820  1820 I HotwordDetector: Closing mic
08-10 15:08:26.202  1820  2153 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@86c167f
08-10 15:08:26.203  1820  2159 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-10 15:08:26.229   875  1703 I ActivityManager: Start proc 3334:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-10 15:08:26.249   378  2161 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-10 15:08:26.251   378  2161 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-10 15:08:26.252  1820  1820 W ErrorReporter: reportError [type: 29, code: 917507]: null
08-10 15:08:26.258   378  1288 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-10 15:08:26.262  1820  2158 I MicroRecognitionRnrImpl: Detection finished
08-10 15:08:26.266  1820  2157 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-10 15:08:26.348  3334  3334 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-10 15:08:26.379  3334  3334 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-10 15:08:26.426  3334  3334 I LibraryLoader: Time to load native libraries: 40 ms (timestamps 1601-1641)
08-10 15:08:26.426  3334  3334 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 15:08:26.453  3334  3334 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {bc33ba2}
,08-10 15:08:26.454  3334  3334 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 15:08:26.455  3334  3334 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-10 15:08:26.461  3334  3334 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-10 15:08:26.464  3334  3334 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-10 15:08:26.513  3334  3349 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,08-10 15:08:26.522  3334  3334 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-10 15:08:26.536  3334  3334 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-10 15:08:26.536  3334  3334 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 15:08:26.536  3334  3334 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 15:08:26.536  3334  3334 I Adreno  : Build Date                       : 10/20/15
08-10 15:08:26.536  3334  3334 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 15:08:26.536  3334  3334 I Adreno  : Local Branch                     : M14
08-10 15:08:26.536  3334  3334 I Adreno  : Remote Branch                    : 
08-10 15:08:26.536  3334  3334 I Adreno  : Remote Branch                    : 
08-10 15:08:26.536  3334  3334 I Adreno  : Reconstruct Branch               : 
,08-10 15:08:26.622   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@960d0d:true
,08-10 15:08:26.705  3334  3334 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-10 15:08:26.723  3334  3334 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-10 15:08:26.798  3334  3372 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-10 15:08:26.811  3334  3358 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-10 15:08:26.851  3334  3372 I OpenGLRenderer: Initialized EGL, version 1.4
,08-10 15:08:26.938   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +723ms
,08-10 15:08:26.943  1670  1670 I Keyboard.Facilitator: onFinishInput()
,08-10 15:08:27.069  3334  3334 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3334
,08-10 15:08:27.082   875   885 I ActivityManager: Killing 2332:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,08-10 15:08:27.135   875   885 I ActivityManager: Killing 3002:com.qualcomm.telephony/1001 (adj 15): empty #18
,08-10 15:08:27.296  3334  3334 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-10 15:08:27.447  3334  3374 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1698760400
,08-10 15:08:27.454  3334  3374 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-10 15:08:27.454  3334  3374 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-10 15:08:27.454  3334  3374 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-10 15:08:27.454  3334  3374 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-10 15:08:27.454  3334  3374 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-10 15:08:27.454  3334  3374 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5447186 added. We now have 1 listener(s)
,08-10 15:08:27.461  3334  3374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-10 15:08:27.462  3334  3374 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 15:08:27.464  3334  3374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-10 15:08:27.465  3334  3374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 15:08:27.471  3334  3374 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-10 15:08:27.471  3334  3374 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-10 15:08:27.471  3334  3374 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-10 15:08:27.471  3334  3374 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-10 15:08:27.471  3334  3374 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-10 15:08:27.471  3334  3374 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-10 15:08:27.471  3334  3374 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-10 15:08:27.471  3334  3374 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-10 15:08:27.471  3334  3374 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-10 15:08:27.471  3334  3374 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-10 15:08:27.471  3334  3374 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-10 15:08:27.471  3334  3374 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-10 15:08:27.471  3334  3374 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-10 15:08:27.471  3334  3374 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-10 15:08:27.471  3334  3374 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@234d39d added. We now have 1 listener(s)
08-10 15:08:27.472  3334  3374 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 15:08:27.474   875  1319 D WifiService: New client listening to asynchronous messages
,08-10 15:08:27.474  3334  3374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 15:08:27.474  3334  3374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-10 15:08:27.475  3334  3374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-10 15:08:27.475  3334  3374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-10 15:08:27.475  3334  3374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-10 15:08:27.476  3334  3374 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 15:08:27.476  3334  3374 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-10 15:08:27.478  3334  3374 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 15:08:27.478  3334  3374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 15:08:27.478  3334  3374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:08:27.478  3334  3374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 15:08:27.478  3334  3374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 15:08:27.478  3334  3374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 15:08:27.478  3334  3374 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:08:27.478  3334  3374 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:08:27.478  3334  3374 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 15:08:27.478  3334  3374 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-10 15:08:27.478  3334  3374 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 15:08:27.479  3334  3374 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-10 15:08:27.627  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 15:08:27.630  3334  3334 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-10 15:08:28.420  3334  3385 W jxcore-log: Initializing JXcore engine
,08-10 15:08:28.420  3334  3385 W jxcore-log: JXcore engine is ready
,08-10 15:08:28.479  3385  3385 W Thread-287: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8932 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-10 15:08:28.483  3385  3385 W Thread-287: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12153]" dev="sockfs" ino=12153 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-10 15:08:28.483  3385  3385 W Thread-287: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-10 15:08:28.483  3385  3385 W Thread-287: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[23114]" dev="sockfs" ino=23114 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-10 15:08:28.497  3334  3385 W jxcore-log: Starting JXcore engine
,08-10 15:08:28.641  3334  3385 W jxcore-log: Platform android
08-10 15:08:28.641  3334  3385 W jxcore-log: 
08-10 15:08:28.641  3334  3385 W jxcore-log: Process ARCH arm
08-10 15:08:28.641  3334  3385 W jxcore-log: 
,08-10 15:08:28.884  3334  3385 I jxcore-log: JXcore Cordova bridge is ready!
08-10 15:08:28.884  3334  3385 I jxcore-log: 
08-10 15:08:28.884  3334  3385 W jxcore-log: JXcore engine is started
,08-10 15:08:28.891  3334  3374 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-10 15:08:28.897  3334  3334 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-10 15:08:44.665  3334  3385 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-10 15:08:44.665  3334  3385 I jxcore-log: 
,08-10 15:08:44.668  3334  3385 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-10 15:08:44.668  3334  3385 I jxcore-log: 
,08-10 15:08:44.669  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:08:44.669  3334  3385 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 15:08:44.669  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:08:44.669  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 15:08:44.669  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 15:08:44.669  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 15:08:44.669  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:08:44.669  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:08:44.669  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 15:08:44.670  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:08:44.670  3334  3385 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 15:08:44.672  3334  3385 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-10 15:08:44.672  3334  3385 I jxcore-log: 
08-10 15:08:44.674  3334  3385 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-10 15:08:44.674  3334  3385 I jxcore-log: 
,08-10 15:08:44.887   875   895 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...,
,08-10 15:08:44.902  1670  1670 I Keyboard.Facilitator: onFinishInput()
,08-10 15:08:44.930   875   895 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 15:08:44.930   875   895 I Adreno  : Build Date                       : 10/20/15
08-10 15:08:44.930   875   895 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 15:08:44.930   875   895 I Adreno  : Local Branch                     : M14
08-10 15:08:44.930   875   895 I Adreno  : Remote Branch                    : 
08-10 15:08:44.930   875   895 I Adreno  : Remote Branch                    : 
08-10 15:08:44.930   875   895 I Adreno  : Reconstruct Branch               : 
,08-10 15:08:44.970   280  1310 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (164 us)
,08-10 15:08:45.040  3334  3385 D ExecuteNativeTests: Running unit tests
,08-10 15:08:45.103  3334  3385 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 15:08:45.103  3334  3385 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a3988 added. We now have 2 listener(s)
08-10 15:08:45.104  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 15:08:45.104  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 15:08:45.104  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 15:08:45.104  3334  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 15:08:45.104  3334  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 added. We now have 2 listener(s)
08-10 15:08:45.104  3334  3385 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 15:08:45.105  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 15:08:45.106  3334  3385 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 15:08:45.106  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:08:45.106  3334  3385 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 15:08:45.106  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:08:45.106  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 15:08:45.106  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 15:08:45.106  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 15:08:45.106  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:08:45.106  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:08:45.106  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 15:08:45.106  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:08:45.106  3334  3385 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 15:08:45.107  3334  3385 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 15:08:45.107  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 15:08:45.108  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 15:08:45.108  3334  3385 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 15:08:45.108  3334  3385 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-10 15:08:45.109  3334  3385 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-10 15:08:45.109  3334  3385 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-10 15:08:45.109  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-10 15:08:45.109  3334  3385 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 15:08:45.109  3334  3385 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-10 15:08:45.110  3334  3385 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 15:08:45.110  3334  3385 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 15:08:45.110  3334  3385 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 15:08:45.110  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 15:08:45.110  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.110  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 15:08:45.110  3334  3385 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 15:08:45.110  3334  3385 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a3988 removed from the list
08-10 15:08:45.110  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.111  3334  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 removed from the list
,08-10 15:08:45.111  3334  3385 D io.jxcore.node.ConnectivityMonitor: stop
08-10 15:08:45.111  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.111  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 15:08:45.111  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.112  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 15:08:45.112  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 15:08:45.112  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.112  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.113  3334  3385 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-10 15:08:45.113  3334  3385 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 15:08:45.113  3334  3385 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-10 15:08:45.113  3334  3385 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 15:08:45.113  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 15:08:45.114  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.114  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.114  3334  3385 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a3988 not in the list
08-10 15:08:45.114  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.114  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.114  3334  3385 D io.jxcore.node.ConnectivityMonitor: stop
08-10 15:08:45.114  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.114  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.114  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 15:08:45.114  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.114  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 15:08:45.114  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 15:08:45.114  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.114  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
,08-10 15:08:45.118  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-10 15:08:45.118  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-10 15:08:45.118  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-10 15:08:45.118  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-10 15:08:45.118  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-10 15:08:45.118  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-10 15:08:45.118  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-10 15:08:45.118  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-10 15:08:45.118  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-10 15:08:45.118  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-10 15:08:45.118  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-10 15:08:45.119  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-10 15:08:45.119  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-10 15:08:45.119  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-10 15:08:45.119  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-10 15:08:45.119  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-10 15:08:45.119  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-10 15:08:45.119  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-10 15:08:45.119  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-10 15:08:45.119  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-10 15:08:45.119  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-10 15:08:45.119  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-10 15:08:45.119  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-10 15:08:45.119  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-10 15:08:45.119  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-10 15:08:45.119  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-10 15:08:45.119  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-10 15:08:45.119  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-10 15:08:45.119  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-10 15:08:45.119  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-10 15:08:45.119  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-10 15:08:45.119  3334  3385 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 15:08:45.119  3334  3385 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 15:08:45.120  3334  3385 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 15:08:45.120  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 15:08:45.120  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.120  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.120  3334  3385 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a3988 not in the list
08-10 15:08:45.120  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.120  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.120  3334  3385 D io.jxcore.node.ConnectivityMonitor: stop
08-10 15:08:45.120  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.120  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.120  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.120  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.120  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-10 15:08:45.121  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 15:08:45.121  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.121  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.121  3334  3385 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-10 15:08:45.122  3334  3385 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 15:08:45.122  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:08:45.122  3334  3385 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 15:08:45.122  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:08:45.122  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 15:08:45.122  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 15:08:45.122  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 15:08:45.122  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:08:45.122  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:08:45.122  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 15:08:45.122  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:08:45.123  3334  3385 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 15:08:45.123  3334  3385 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 15:08:45.123  3334  3385 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 15:08:45.123  3334  3385 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 15:08:45.123  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 15:08:45.123  3334  3385 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 15:08:45.123  3334  3385 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 15:08:45.123  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 15:08:45.125  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,08-10 15:08:45.125  3334  3385 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,08-10 15:08:45.125  3334  3385 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 15:08:45.125  3334  3385 I io.jxcore.node.ConnectionHelper: start: OK
08-10 15:08:45.125  3334  3334 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-10 15:08:45.126  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:08:45.126  3334  3385 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
08-10 15:08:45.127  3334  3385 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 15:08:45.127  3334  3385 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 15:08:45.127  3334  3385 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-10 15:08:45.127  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.127  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 15:08:45.127  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-10 15:08:45.127  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 15:08:45.127  3334  3385 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-10 15:08:45.128  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 15:08:45.128  3334  3385 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-10 15:08:45.128  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 15:08:45.129  3334  3385 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 15:08:45.129  3334  3334 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 15:08:45.129  3334  3334 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 15:08:45.129  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 15:08:45.129  3334  3334 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 15:08:45.129  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.129  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 15:08:45.129  3334  3385 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a3988 not in the list
08-10 15:08:45.129  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.129  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.129  3334  3385 D io.jxcore.node.ConnectivityMonitor: stop
08-10 15:08:45.129  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.129  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.129  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.130  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 15:08:45.130  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 15:08:45.130  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.130  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.131  3334  3385 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-10 15:08:45.132  3334  3385 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 15:08:45.132  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:08:45.132  3334  3385 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 15:08:45.132  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:08:45.132  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 15:08:45.132  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 15:08:45.132  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 15:08:45.132  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:08:45.132  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:08:45.132  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - active n,etwork type is Wi-Fi: false
08-10 15:08:45.132  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:08:45.132  3334  3385 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 15:08:45.132  3334  3385 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 15:08:45.132  3334  3385 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 15:08:45.132  3334  3385 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 15:08:45.132  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 15:08:45.132  3334  3385 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 15:08:45.132  3334  3385 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 15:08:45.133  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 15:08:45.133  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-10 15:08:45.134  3334  3385 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-10 15:08:45.134  3334  3385 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 15:08:45.134  3334  3385 I io.jxcore.node.ConnectionHelper: start: OK
08-10 15:08:45.134  3334  3334 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-10 15:08:45.134  3334  3385 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 15:08:45.134  3334  3385 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 15:08:45.134  3334  3385 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-10 15:08:45.134  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.134  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 15:08:45.134  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 15:08:45.134  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 15:08:45.134  3334  3385 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 15:08:45.134  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 15:08:45.134  3334  3385 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 15:08:45.135  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 15:08:45.135  3334  3385 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 15:08:45.135  3334  3334 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 15:08:45.135  3334  3334 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 15:08:45.135  3334  3334 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 15:08:45.135  3334  3385 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 15:08:45.135  3334  3385 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-10 15:08:45.135  3334  3385 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 15:08:45.135  3334  3385 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 15:08:45.135  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 15:08:45.135  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.135  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 15:08:45.135  3334  3385 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a3988 not in the list
08-10 15:08:45.135  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.135  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.135  3334  3385 D io.jxcore.node.ConnectivityMonitor: stop
08-10 15:08:45.135  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.136  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.136  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.136  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 15:08:45.136  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 15:08:45.136  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.136  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.137  3334  3385 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-10 15:08:45.137  3334  3385 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 15:08:45.137  3334  3385 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 15:08:45.137  3334  3385 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 15:08:45.137  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 15:08:45.137  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.137  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.137  3334  3385 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a3988 not in the list
08-10 15:08:45.137  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.137  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.137  3334  3385 D io.jxcore.node.ConnectivityMonitor: stop
08-10 15:08:45.137  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.137  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.137  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.138  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.138  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 15:08:45.138  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 15:08:45.138  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.138  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.139  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 15:08:45.139  3334  3385 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 15:08:45.139  3334  3385 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 15:08:45.139  3334  3385 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 15:08:45.139  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 15:08:45.139  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.139  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.139  3334  3385 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a3988 not in the list
08-10 15:08:45.139  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.139  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.139  3334  3385 D io.jxcore.node.ConnectivityMonitor: stop
08-10 15:08:45.139  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.139  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.140  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.140  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.140  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 15:08:45.140  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 15:08:45.140  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.140  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.140  3334  3385 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-10 15:08:45.140  3334  3385 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 15:08:45.141  3334  3385 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 15:08:45.141  3334  3385 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 15:08:45.141  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 15:08:45.141  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.141  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.141  3334  3385 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a3988 not in the list
08-10 15:08:45.141  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.141  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.141  3334  3385 D io.jxcore.node.ConnectivityMonitor: stop
08-10 15:08:45.141  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.141  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.141  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.141  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.141  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 15:08:45.141  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 15:08:45.141  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.141  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.142  3334  3385 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-10 15:08:45.142  3334  3385 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 15:08:45.142  3334  3385 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 15:08:45.142  3334  3385 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 15:08:45.142  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 15:08:45.142  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.142  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.142  3334  3385 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a3988 not in the list
08-10 15:08:45.142  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.142  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.142  3334  3385 D io.jxcore.node.ConnectivityMonitor: stop
08-10 15:08:45.142  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.142  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.142  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.142  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.143  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 15:08:45.143  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 15:08:45.143  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.143  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.143  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 15:08:45.144  3334  3385 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 15:08:45.144  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 15:08:45.144  3334  3385 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 15:08:45.144  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 15:08:45.144  3334  3385 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 15:08:45.144  3334  3385 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 15:08:45.144  3334  3385 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 15:08:45.144  3334  3385 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 15:08:45.144  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 15:08:45.144  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.144  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.144  3334  3385 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a3988 not in the list
08-10 15:08:45.144  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.144  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.144  3334  3385 D io.jxcore.node.ConnectivityMonitor: stop
08-10 15:08:45.144  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.144  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.144  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.144  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.145  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 15:08:45.145  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 15:08:45.145  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.145  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.145  3334  3385 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 15:08:45.146  3334  3385 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-10 15:08:45.146  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-10 15:08:45.148  3334  3385 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 15:08:45.148  3334  3385 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-10 15:08:45.148  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-10 15:08:45.148  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-10 15:08:45.148  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-10 15:08:45.148  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-10 15:08:45.148  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-10 15:08:45.148  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-10 15:08:45.148  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-10 15:08:45.148  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-10 15:08:45.148  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-10 15:08:45.148  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-10 15:08:45.148  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-10 15:08:45.148  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-10 15:08:45.148  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-10 15:08:45.148  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-10 15:08:45.148  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-10 15:08:45.149  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-10 15:08:45.149  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-10 15:08:45.149  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-10 15:08:45.149  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-10 15:08:45.149  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-10 15:08:45.149  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-10 15:08:45.149  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-10 15:08:45.149  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-10 15:08:45.149  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-10 15:08:45.149  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-10 15:08:45.149  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-10 15:08:45.149  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-10 15:08:45.149  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-10 15:08:45.149  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-10 15:08:45.149  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-10 15:08:45.149  3334  3385 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-10 15:08:45.149  3334  3385 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 15:08:45.150  3334  3385 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-10 15:08:45.150  3334  3385 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 15:08:45.150  3334  3385 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 15:08:45.150  3334  3385 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-10 15:08:45.150  3334  3385 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 15:08:45.150  3334  3385 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 15:08:45.150  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-10 15:08:45.151  3334  3385 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
08-10 15:08:45.151  3334  3385 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-10 15:08:45.151  3334  3385 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-10 15:08:45.152  3334  3385 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-10 15:08:45.152  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-10 15:08:45.152  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-10 15:08:45.152  3334  3385 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-10 15:08:45.152  3334  3385 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 15:08:45.152  3334  3385 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-10 15:08:45.153  3334  3385 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 15:08:45.153  3334  3385 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 15:08:45.153  3334  3385 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 15:08:45.153  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 15:08:45.153  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.153  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.153  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-10 15:08:45.155  3334  3385 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a3988 not in the list
08-10 15:08:45.155  3334  3393 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 351)
08-10 15:08:45.155  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.156  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.156  3334  3385 D io.jxcore.node.ConnectivityMonitor: stop
08-10 15:08:45.156  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.156  3334  3394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 351
08-10 15:08:45.156  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.156  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.156  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.156  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 15:08:45.156  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 15:08:45.156  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.156  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.157  3334  3393 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 351)
08-10 15:08:45.157  3334  3385 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-10 15:08:45.157  3334  3385 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 15:08:45.157  3334  3385 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 15:08:45.157  3334  3385 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 15:08:45.158  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 15:08:45.158  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.158  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.158  3334  3385 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a3988 not in the list
08-10 15:08:45.158  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.158  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.158  3334  3385 D io.jxcore.node.ConnectivityMonitor: stop
08-10 15:08:45.158  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.158  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.159  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.159  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.159  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 15:08:45.159  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 15:08:45.159  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.159  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.160  3334  3385 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-10 15:08:45.160  3334  3385 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 15:08:45.160  3334  3385 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 15:08:45.160  3334  3385 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 15:08:45.160  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 15:08:45.160  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.160  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.160  3334  3385 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a3988 not in the list
08-10 15:08:45.160  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.160  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.160  3334  3385 D io.jxcore.node.ConnectivityMonitor: stop
08-10 15:08:45.160  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.160  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.160  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.160  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.161  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 15:08:45.161  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 15:08:45.161  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.161  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.161  3334  3385 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-10 15:08:45.161  3334  3385 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-10 15:08:45.161  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 15:08:45.161  3334  3385 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-10 15:08:45.161  3334  3385 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-10 15:08:45.161  3334  3385 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-10 15:08:45.161  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 15:08:45.161  3334  3385 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-10 15:08:45.162  3334  3385 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-10 15:08:45.162  3334  3385 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-10 15:08:45.162  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 15:08:45.162  3334  3385 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-10 15:08:45.162  3334  3385 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 15:08:45.162  3334  3385 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 15:08:45.162  3334  3385 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 15:08:45.162  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 15:08:45.162  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.162  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.162  3334  3385 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a3988 not in the list
08-10 15:08:45.162  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.162  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.162  3334  3385 D io.jxcore.node.ConnectivityMonitor: stop
08-10 15:08:45.162  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.162  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.162  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.162  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.163  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 15:08:45.163  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 15:08:45.163  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.163  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.163  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 15:08:45.163  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.163  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.163  3334  3385 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a3988 not in the list
08-10 15:08:45.163  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.163  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.164  3334  3385 D io.jxcore.node.ConnectivityMonitor: stop
08-10 15:08:45.164  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.164  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.164  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.164  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.164  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 15:08:45.164  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.164  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.164  3334  3385 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a3988 not in the list
08-10 15:08:45.164  3334  3385 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 15:08:45.164  3334  3385 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 15:08:45.164  3334  3385 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 15:08:45.164  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 15:08:45.164  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.165  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.165  3334  3385 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a3988 not in the list
08-10 15:08:45.165  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.165  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.165  3334  3385 D io.jxcore.node.ConnectivityMonitor: stop
08-10 15:08:45.165  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.165  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.165  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.165  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.165  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 15:08:45.165  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 15:08:45.165  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.165  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.166  3334  3385 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-10 15:08:45.166  3334  3385 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 15:08:45.166  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
08-10 15:08:45.166  3334  3385 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
08-10 15:08:45.166  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 15:08:45.167  3334  3334 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
08-10 15:08:45.167  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 15:08:45.167  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-10 15:08:45.167  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.167  3334  3385 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
08-10 15:08:45.167  3334  3385 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a3988 not in the list
08-10 15:08:45.167  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.167  3334  3334 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-10 15:08:45.167  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 15:08:45.167  3334  3385 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 15:08:45.167  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 15:08:45.167  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.167  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.168  3334  3385 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 15:08:45.168  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.168  3334  3385 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 15:08:45.168  3334  3385 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 15:08:45.168  3334  3334 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 15:08:45.168  3334  3385 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 15:08:45.168  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 15:08:45.168  3334  3334 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 15:08:45.168  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.168  3334  3334 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
,08-10 15:08:45.168  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 15:08:45.168  3334  3385 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a3988 not in the list
08-10 15:08:45.168  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.168  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
,08-10 15:08:45.168  3334  3385 D io.jxcore.node.ConnectivityMonitor: stop
08-10 15:08:45.168  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.168  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-10 15:08:45.169  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.169  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.169  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 15:08:45.169  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 15:08:45.169  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 15:08:45.169  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.170  3334  3385 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-10 15:08:45.170  3334  3385 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-10 15:08:45.170  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 15:08:45.172  3334  3385 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-10 15:08:45.172  3334  3385 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 15:08:45.172  3334  3385 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 15:08:45.172  3334  3385 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 15:08:45.172  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 15:08:45.172  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.172  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.173  3334  3385 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a3988 not in the list
,08-10 15:08:45.173  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.173  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.173  3334  3385 D io.jxcore.node.ConnectivityMonitor: stop
08-10 15:08:45.173  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.173  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.173  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.173  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.174  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 15:08:45.174  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 15:08:45.174  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 15:08:45.174  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.176  3334  3385 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 15:08:45.176  3334  3385 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 15:08:45.176  3334  3385 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 15:08:45.176  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 15:08:45.176  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.176  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.176  3334  3385 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a3988 not in the list
08-10 15:08:45.176  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.176  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.176  3334  3385 D io.jxcore.node.ConnectivityMonitor: stop
08-10 15:08:45.176  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 15:08:45.176  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.176  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.176  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.177  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 15:08:45.177  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 15:08:45.177  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.177  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.177  3334  3385 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 15:08:45.178  3334  3385 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 15:08:45.178  3334  3385 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 15:08:45.178  3334  3385 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 15:08:45.178  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.178  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.178  3334  3385 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57a3988 not in the list
,08-10 15:08:45.178  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.178  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.178  3334  3385 D io.jxcore.node.ConnectivityMonitor: stop
08-10 15:08:45.178  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.178  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.178  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 15:08:45.178  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 15:08:45.179  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-10 15:08:45.179  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 15:08:45.179  3334  3385 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 15:08:45.179  3334  3385 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c21f21 not in the list
08-10 15:08:45.179  3334  3385 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-10 15:08:45.179  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-10 15:08:45.179  3334  3385 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-10 15:08:45.179  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 15:08:45.180  3334  3385 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-10 15:08:45.180  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 15:08:45.181  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 15:08:45.181  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-10 15:08:45.181  3334  3385 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-10 15:08:45.182  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-10 15:08:45.182  3334  3385 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-10 15:08:45.182  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-10 15:08:45.182  3334  3385 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-10 15:08:45.182  3334  3385 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-10 15:08:45.182  3334  3385 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-10 15:08:45.182  3334  3385 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-10 15:08:45.182  3334  3385 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-10 15:08:45.183  3334  3385 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-10 15:08:45.183  3334  3385 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-10 15:08:45.183  3334  3385 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-10 15:08:45.183  3334  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 15:08:45.183  3334  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bdf9aa3 added. We now have 2 listener(s)
08-10 15:08:45.183  3334  3385 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 15:08:45.184   875  1387 D WifiService: setWifiEnabled: true pid=3334, uid=10000
08-10 15:08:45.185   875  1387 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-10 15:08:45.195  3334  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 15:08:45.196  3334  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c64b1a0 added. We now have 3 listener(s)
,08-10 15:08:45.196  3334  3385 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 15:08:45.197  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:08:45.197  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:08:45.197  3334  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 15:08:45.197  3334  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6be9159 added. We now have 4 listener(s)
08-10 15:08:45.197  3334  3385 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 15:08:45.198   875   892 I ActivityManager: Start proc 3396:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
08-10 15:08:45.198  3334  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 15:08:45.198  3334  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@343311e added. We now have 5 listener(s)
08-10 15:08:45.198  3334  3385 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 15:08:45.199   875  1318 D WifiConfigStore: Loading config and enabling all networks 
08-10 15:08:45.199   875  1388 D WifiService: setWifiEnabled: false pid=3334, uid=10000
,08-10 15:08:45.199   875  1388 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-10 15:08:45.200  3334  3334 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:08:45.200  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 15:08:45.200  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:08:45.200  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 15:08:45.200  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 15:08:45.200  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 15:08:45.200  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:08:45.200  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:08:45.200  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 15:08:45.200  3334  3334 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:08:45.201  3334  3334 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 15:08:45.211   875  1318 D WifiConfigStore: loaded 0 passpoint configs
08-10 15:08:45.213   875  1318 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-10 15:08:45.214   875   888 I ActivityManager: Start proc 3407:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-10 15:08:45.214   875  1318 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-10 15:08:45.215   875  1318 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-10 15:08:45.215   875  1318 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-10 15:08:45.215   875  1318 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-10 15:08:45.215   875  1318 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-10 15:08:45.216  3334  3385 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 15:08:45.217  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:08:45.217  3334  3385 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 15:08:45.217  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:08:45.217  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 15:08:45.217  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 15:08:45.217  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 15:08:45.217  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:08:45.217  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:08:45.217  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 15:08:45.217  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 15:08:45.217  3334  3385 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 15:08:45.217  3334  3385 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 15:08:45.218  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 15:08:45.254  3407  3407 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-10 15:08:45.273   374   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-10 15:08:45.274   374   873 D CommandListener: Setting iface cfg
,08-10 15:08:45.276   875  1317 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '34 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 34 Failed to set address (No such device)'
08-10 15:08:45.276   875  1317 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-10 15:08:45.284   875  1317 D WifiNative-HAL: p2pGetDeviceAddress
08-10 15:08:45.284   875  1317 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-10 15:08:45.284  3396  3396 D AdapterServiceConfig: Adding HeadsetService
08-10 15:08:45.285  3396  3396 D AdapterServiceConfig: Adding A2dpService
08-10 15:08:45.285  3396  3396 D AdapterServiceConfig: Adding HidService
08-10 15:08:45.285  3396  3396 D AdapterServiceConfig: Adding HealthService
08-10 15:08:45.285  3396  3396 D AdapterServiceConfig: Adding PanService
08-10 15:08:45.285  3396  3396 D AdapterServiceConfig: Adding GattService
08-10 15:08:45.285  3396  3396 D AdapterServiceConfig: Adding BluetoothMapService
08-10 15:08:45.288  3334  3334 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:08:45.288  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 15:08:45.288  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:08:45.288  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 15:08:45.288  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 15:08:45.288  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 15:08:45.288  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:08:45.288  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:08:45.288  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 15:08:45.288  3334  3334 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:08:45.288  3334  3334 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 15:08:45.289  3334  3334 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:08:45.289  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 15:08:45.289  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:08:45.289  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 15:08:45.289  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 15:08:45.289  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 15:08:45.289  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:08:45.289  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:08:45.289  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 15:08:45.289  3334  3334 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:08:45.289  3334  3334 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 15:08:45.289   875  1318 D WifiConfigStore: Retrieve network priorities after PNO.
08-10 15:08:45.290  1866  2060 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 15:08:45.306  3407  3407 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-10 15:08:45.317   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@90fedf6:true
,08-10 15:08:45.318  3396  3396 D BluetoothAdapterState: make() - Creating AdapterState
,08-10 15:08:45.321  3396  3396 I bt_bluedroid: init
08-10 15:08:45.321  3396  3434 I BluetoothAdapterState: Entering OffState
,08-10 15:08:45.325  3396  3435 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-10 15:08:45.326  3396  3435 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-10 15:08:45.326  3396  3435 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-10 15:08:45.326  3396  3435 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-10 15:08:45.328  3396  3396 I bt_bluedroid: get_profile_interface socket
,08-10 15:08:45.329  3396  3396 I bt_bluedroid: get_profile_interface sdp
08-10 15:08:45.329  3396  3438 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-10 15:08:45.330  3396  3438 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 15:08:45.332   875  1388 I ActivityManager: Killing 2694:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-10 15:08:45.376  3396  3418 I bt_bluedroid: config_hci_snoop_log
,08-10 15:08:45.376   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-10 15:08:45.381  3396  3434 D BluetoothAdapterState: Current state: OFF, message: 0
08-10 15:08:45.381  3396  3434 D BluetoothAdapterProperties: Setting state to 14
,08-10 15:08:45.381  3396  3434 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-10 15:08:45.382  3396  3434 D BluetoothBondStateMachine: make
,08-10 15:08:45.384  3396  3439 I BluetoothBondStateMachine: StableState(): Entering Off State
08-10 15:08:45.387  3396  3434 I BluetoothAdapterState: Entering PendingCommandState
,08-10 15:08:45.388  3396  3396 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-10 15:08:45.390  3396  3396 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1802b1c
,08-10 15:08:45.390  3396  3396 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 15:08:45.392  3396  3396 D BtGatt.GattService: Received start request. Starting profile...
,08-10 15:08:45.393  3396  3396 D BtGatt.GattService: start()
08-10 15:08:45.393  3396  3396 I bt_bluedroid: get_profile_interface gatt
08-10 15:08:45.394  3396  3396 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1802b1c
,08-10 15:08:45.394  3396  3396 D BtGatt.AdvertiseManager: advertise manager created
,08-10 15:08:45.402  3396  3396 V BluetoothAdapterState: isTurningOff()=false
,08-10 15:08:45.402  3396  3396 V BluetoothAdapterState: isTurningOn()=false
,08-10 15:08:45.402  3396  3396 V BluetoothAdapterState: isBleTurningOn()=true
08-10 15:08:45.402  3396  3396 V BluetoothAdapterState: isBleTurningOff()=false
08-10 15:08:45.402  3396  3434 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-10 15:08:45.402  3396  3434 I bt_bluedroid: enable
08-10 15:08:45.403  3396  3435 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-10 15:08:45.403  3396  3435 I bt_hci  : start_up
,08-10 15:08:45.412  3396  3435 I bt_vendor: alloc value 0xb39fd189
,08-10 15:08:45.413  3396  3435 I bt_vendor: init
08-10 15:08:45.413  3396  3435 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-10 15:08:45.413  3396  3435 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-10 15:08:45.519  3396  3435 D bt_hci  : start_up starting async portion
,08-10 15:08:45.520  3396  3442 I bt_hci  : event_finish_startup
,08-10 15:08:45.520  3396  3442 I bt_hci_h4: hal_open
08-10 15:08:45.521  3396  3442 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-10 15:08:45.527  3396  3442 I bt_userial_vendor: device fd = 51 open
,08-10 15:08:45.563  3396  3442 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 15:08:45.575  3334  3334 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-10 15:08:45.575  3334  3334 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-10 15:08:45.594  3396  3442 D bt_hwcfg: Chipset BCM4354A2
,08-10 15:08:45.594  3396  3442 D bt_hwcfg: Target name = [BCM4354A2]
08-10 15:08:45.595  3396  3442 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-10 15:08:45.628   875   895 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-10 15:08:45.629  3334  3334 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ff2dd08 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@ded412a, 16908290=android.view.AbsSavedState$1@ded412a}, android:focusedViewId=100}]}]
08-10 15:08:45.630  3334  3334 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-10 15:08:45.630  3334  3334 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-10 15:08:45.631  3334  3334 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-10 15:08:45.642   875   895 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-10 15:08:45.653   875   893 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-10 15:08:45.655   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,08-10 15:08:45.655   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-10 15:08:45.669  3334  3334 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 15:08:45.926   280   339 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-10 15:08:45.929   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-10 15:08:45.930   875  1343 D SurfaceControl: Excessive delay in setPowerMode(): 277ms
,08-10 15:08:45.938   875   895 I DreamManagerService: Entering dreamland.
,08-10 15:08:45.942   875   895 I PowerManagerService: Dozing...
,08-10 15:08:45.943   875   890 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-10 15:08:45.995   378   378 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-10 15:08:45.995   378   378 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-10 15:08:46.009   875  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 15:08:46.015   875  1318 E native  : do suspend false
,08-10 15:08:46.029  1734  3445 D NfcService: Discovery configuration equal, not updating.
,08-10 15:08:46.074   875  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 15:08:46.081   875  1318 E native  : do suspend true
,08-10 15:08:46.138   378  1471 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-10 15:08:46.139   378  1471 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-10 15:08:46.381  3396  3442 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-10 15:08:46.383  3396  3442 D bt_hwcfg: Settlement delay -- 100 ms
08-10 15:08:46.383  3396  3442 I bt_hwcfg: Setting fw settlement delay to 100 
,08-10 15:08:46.505  3396  3442 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 15:08:46.506  3396  3442 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-10 15:08:46.533  3396  3442 I bt_hwcfg: vendor lib fwcfg completed
,08-10 15:08:46.533  3396  3442 I bt_vendor: firmware callback
08-10 15:08:46.533  3396  3442 I bt_hci  : firmware_config_callback
,08-10 15:08:46.546  3396  3449 I bt_btu  : btu_task pending for preload complete event
,08-10 15:08:46.547  3396  3449 I bt_btu_task: Bluetooth chip preload is complete
08-10 15:08:46.547  3396  3449 I bt_btu  : btu_task received preload complete event
,08-10 15:08:46.557  3396  3449 I         : BTE_InitTraceLevels -- TRC_HCI
08-10 15:08:46.558  3396  3449 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-10 15:08:46.558  3396  3449 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-10 15:08:46.558  3396  3449 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-10 15:08:46.558  3396  3449 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-10 15:08:46.559  3396  3449 I         : BTE_InitTraceLevels -- TRC_A2D
08-10 15:08:46.559  3396  3449 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-10 15:08:46.559  3396  3449 I         : BTE_InitTraceLevels -- TRC_BTM
08-10 15:08:46.559  3396  3449 I         : BTE_InitTraceLevels -- TRC_GAP
08-10 15:08:46.560  3396  3449 I         : BTE_InitTraceLevels -- TRC_PAN
,08-10 15:08:46.560  3396  3449 I         : BTE_InitTraceLevels -- TRC_SDP
08-10 15:08:46.560  3396  3449 I         : BTE_InitTraceLevels -- TRC_GATT
08-10 15:08:46.560  3396  3449 I         : BTE_InitTraceLevels -- TRC_SMP
08-10 15:08:46.561  3396  3449 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-10 15:08:46.561  3396  3449 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-10 15:08:46.708  3396  3449 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb397ad9d
,08-10 15:08:46.708  3396  3449 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb397ad9d 
,08-10 15:08:46.722  3396  3438 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-10 15:08:46.724  3396  3438 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-10 15:08:46.725  3396  3438 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 15:08:46.728  3396  3438 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 15:08:46.733  3396  3438 D BluetoothAdapterProperties: Scan Mode:20
,08-10 15:08:46.734  3396  3438 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 15:08:46.734  3396  3438 D bt_hci  : do_postload posting postload work item
08-10 15:08:46.734  3396  3442 I bt_hci  : event_postload
08-10 15:08:46.735  3396  3442 I bt_vendor: sco_config_cb
,08-10 15:08:46.735  3396  3442 I bt_hci  : sco_config_callback postload finished.
08-10 15:08:46.739  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 15:08:46.745  3396  3442 I bt_vendor: low_power_mode_cb
,08-10 15:08:46.746  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 15:08:46.748  3396  3438 D bt_bte_conf: Device ID record 1 : primary
08-10 15:08:46.748  3396  3438 D bt_bte_conf:   vendorId            = 000f
08-10 15:08:46.748  3396  3438 D bt_bte_conf:   vendorIdSource      = 0001
,08-10 15:08:46.748  3396  3438 D bt_bte_conf:   product             = 1200
,08-10 15:08:46.748  3396  3438 D bt_bte_conf:   version             = 1436
08-10 15:08:46.748  3396  3438 D bt_bte_conf:   clientExecutableURL = 
08-10 15:08:46.748  3396  3438 D bt_bte_conf:   serviceDescription  = 
,08-10 15:08:46.748  3396  3438 D bt_bte_conf:   documentationURL    = 
,08-10 15:08:46.748  3396  3438 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-10 15:08:46.749  3396  3435 D bt_stack_manager: event_start_up_stack finished
08-10 15:08:46.749  3396  3434 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-10 15:08:46.749  3396  3434 D BluetoothAdapterProperties: Setting state to 15
08-10 15:08:46.749  3396  3434 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-10 15:08:46.751  3396  3434 I BluetoothAdapterState: Entering BleOnState
,08-10 15:08:46.754  3396  3434 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-10 15:08:46.754  3396  3434 D BluetoothAdapterProperties: Setting state to 11
08-10 15:08:46.754  3396  3434 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-10 15:08:46.758  3396  3396 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1802b1c
,08-10 15:08:46.761  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 15:08:46.763  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 15:08:46.763  3396  3396 D HeadsetService: Received start request. Starting profile...
08-10 15:08:46.766  3396  3396 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-10 15:08:46.766  3396  3396 D HeadsetStateMachine: make
,08-10 15:08:46.780   875   888 I ActivityManager: Start proc 3458:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-10 15:08:46.784  3396  3396 D HeadsetStateMachine: max_hf_connections = 1
,08-10 15:08:46.785  3396  3396 I bt_bluedroid: get_profile_interface handsfree
,08-10 15:08:46.786  3396  3438 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-10 15:08:46.786  3396  3438 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-10 15:08:46.792  3396  3434 I BluetoothAdapterState: Entering PendingCommandState
,08-10 15:08:46.795  3396  3396 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1802b1c
,08-10 15:08:46.796   875   875 D BluetoothA2dp: Proxy object connected
,08-10 15:08:46.796  3396  3396 D A2dpService: Received start request. Starting profile...
08-10 15:08:46.797  3396  3396 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-10 15:08:46.797  3396  3396 I bt_bluedroid: get_profile_interface avrcp
,08-10 15:08:46.802  3396  3396 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-10 15:08:46.803  3396  3396 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-10 15:08:46.803  3396  3396 D A2dpStateMachine: make
,08-10 15:08:46.804  3396  3396 I bt_bluedroid: get_profile_interface a2dp
,08-10 15:08:46.806  3396  3438 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-10 15:08:46.808  3396  3471 D A2dpStateMachine: Enter Disconnected: -2
08-10 15:08:46.808  3396  3396 I BluetoothHidServiceJni: classInitNative: succeeds
08-10 15:08:46.808  3396  3396 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1802b1c
08-10 15:08:46.809  1373  1373 D BluetoothInputDevice: Proxy object connected
08-10 15:08:46.809  3396  3396 D HidService: Received start request. Starting profile...
08-10 15:08:46.810  3396  3396 I bt_bluedroid: get_profile_interface hidhost
08-10 15:08:46.810  1373  1373 D HidProfile: Bluetooth service connected
08-10 15:08:46.810  3396  3396 D HidService: setHidService(): set to: null
08-10 15:08:46.811  3396  3396 I BluetoothHealthServiceJni: classInitNative: succeeds
08-10 15:08:46.811  3396  3438 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb395c3e5
08-10 15:08:46.811  3396  3438 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-10 15:08:46.811  3396  3396 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1802b1c
08-10 15:08:46.812  3396  3396 D HealthService: Received start request. Starting profile...
,08-10 15:08:46.813  3396  3396 I bt_bluedroid: get_profile_interface health
,08-10 15:08:46.814  3396  3457 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-10 15:08:46.815  3396  3396 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-10 15:08:46.816  3396  3396 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1802b1c
,08-10 15:08:46.817  3396  3396 D PanService: Received start request. Starting profile...,
,08-10 15:08:46.817  1373  1373 D BluetoothPan: BluetoothPAN Proxy object connected
,08-10 15:08:46.817  3396  3396 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-10 15:08:46.817  3396  3396 I bt_bluedroid: get_profile_interface pan
08-10 15:08:46.818  3396  3438 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-10 15:08:46.818  1373  1373 D PanProfile: Bluetooth service connected
08-10 15:08:46.820  3396  3396 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1802b1c
,08-10 15:08:46.821  1373  1373 D BluetoothMap: Proxy object connected
,08-10 15:08:46.821  3396  3396 D BluetoothMapService: Received start request. Starting profile...
08-10 15:08:46.821  3396  3396 D BluetoothMapService: start()
08-10 15:08:46.821  1373  1373 D MapProfile: Bluetooth service connected
08-10 15:08:46.822  1373  1373 D BluetoothMap: getConnectedDevices()
08-10 15:08:46.822  3458  3458 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-10 15:08:46.822  1373  1373 D BluetoothMap: Bluetooth is Not enabled
08-10 15:08:46.823  3396  3396 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-10 15:08:46.824  3396  3396 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-10 15:08:46.824  3396  3396 D BluetoothMapAppObserver: createReceiver()
,08-10 15:08:46.825  3396  3396 D BluetoothMapAppObserver: initObservers()
,08-10 15:08:46.825  3396  3396 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-10 15:08:46.831  3396  3396 V BluetoothAdapterState: isTurningOff()=false
,08-10 15:08:46.831  3396  3396 V BluetoothAdapterState: isTurningOn()=true
,08-10 15:08:46.831  3396  3396 V BluetoothAdapterState: isBleTurningOn()=false
08-10 15:08:46.831  3396  3396 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 15:08:46.833  3396  3396 V BluetoothAdapterState: isTurningOff()=false
08-10 15:08:46.833  3396  3396 V BluetoothAdapterState: isTurningOn()=true
08-10 15:08:46.833  3396  3396 V BluetoothAdapterState: isBleTurningOn()=false
08-10 15:08:46.833  3396  3396 V BluetoothAdapterState: isBleTurningOff()=false
08-10 15:08:46.833  3396  3396 V BluetoothAdapterState: isTurningOff()=false
08-10 15:08:46.833  3396  3396 V BluetoothAdapterState: isTurningOn()=true
08-10 15:08:46.833  3396  3396 V BluetoothAdapterState: isBleTurningOn()=false
08-10 15:08:46.833  3396  3396 V BluetoothAdapterState: isBleTurningOff()=false
08-10 15:08:46.833  3396  3396 V BluetoothAdapterState: isTurningOff()=false
,08-10 15:08:46.833  3396  3396 V BluetoothAdapterState: isTurningOn()=true
08-10 15:08:46.833  3396  3396 V BluetoothAdapterState: isBleTurningOn()=false
08-10 15:08:46.834  3396  3396 V BluetoothAdapterState: isBleTurningOff()=false
08-10 15:08:46.834  3396  3396 V BluetoothAdapterState: isTurningOff()=false
08-10 15:08:46.834  3396  3396 V BluetoothAdapterState: isTurningOn()=true
08-10 15:08:46.834  3396  3396 V BluetoothAdapterState: isBleTurningOn()=false
08-10 15:08:46.834  3396  3396 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 15:08:46.834  3396  3396 V BluetoothAdapterState: isTurningOff()=false
08-10 15:08:46.834  3396  3396 V BluetoothAdapterState: isTurningOn()=true
08-10 15:08:46.834  3396  3396 V BluetoothAdapterState: isBleTurningOn()=false
08-10 15:08:46.834  3396  3396 V BluetoothAdapterState: isBleTurningOff()=false
08-10 15:08:46.835   875  1388 I ActivityManager: Killing 2828:com.google.android.gm/u0a78 (adj 15): empty #17
08-10 15:08:46.835  3396  3434 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-10 15:08:46.835  3396  3434 D BluetoothAdapterProperties: ScanMode =  20
08-10 15:08:46.835  3396  3434 D BluetoothAdapterProperties: State =  11
08-10 15:08:46.835  3396  3434 D BluetoothAdapterProperties: Setting state to 12
08-10 15:08:46.835  3396  3434 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-10 15:08:46.836  3396  3434 I BluetoothAdapterState: Entering OnState
08-10 15:08:46.836  1373  1389 D BluetoothMap: onBluetoothStateChange: up=true
08-10 15:08:46.836  1373  1848 D BluetoothPan: onBluetoothStateChange on: true
08-10 15:08:46.837  1373  1385 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-10 15:08:46.837  1749  1926 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 15:08:46.853  3396  3396 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-10 15:08:46.854  3396  3396 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-10 15:08:46.874  3396  3438 D BluetoothAdapterProperties: Scan Mode:21
,08-10 15:08:46.874  3396  3438 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-10 15:08:46.878   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 15:08:46.878   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-10 15:08:46.878   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 15:08:46.881  1373  1389 D BluetoothPbap: onBluetoothStateChange: up=true
,08-10 15:08:46.881  3396  3396 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 15:08:46.884  3334  3334 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-10 15:08:46.890   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 15:08:46.890  3334  3334 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-10 15:08:46.895   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
,08-10 15:08:46.896  3334  3334 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-10 15:08:46.899  3396  3396 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 15:08:46.902  3396  3396 D ObexServerSockets: Succeed to create listening sockets 
,08-10 15:08:46.902  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 15:08:46.902  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:08:46.902  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 15:08:46.902  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 15:08:46.902  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 15:08:46.902  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:08:46.902  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:08:46.902  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 15:08:46.902  3396  3396 D ObexServerSockets0: startAccept()
08-10 15:08:46.902  3396  3396 D ObexServerSockets0: prepareForNewConnect()
,08-10 15:08:46.904  3334  3334 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 15:08:46.907  3396  3396 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-10 15:08:46.907  3396  3396 D BluetoothSdpJni: SDP Create record success - handle: 0
08-10 15:08:46.909  1373  1682 D LocalBluetoothProfileManager: Adding local A2DP profile
08-10 15:08:46.909  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 15:08:46.909  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:08:46.909  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 15:08:46.909  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 15:08:46.909  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 15:08:46.909  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:08:46.909  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:08:46.909  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 15:08:46.910  3396  3478 D ObexServerSockets0: Accepting socket connection...
08-10 15:08:46.911  3396  3396 D BluetoothMapService: onReceive
,08-10 15:08:46.911  3396  3396 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 15:08:46.911  3396  3396 D BluetoothMapService: STATE_ON
08-10 15:08:46.911  3396  3477 D ObexServerSockets0: Accepting socket connection...
08-10 15:08:46.911  3334  3334 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 15:08:46.911  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 15:08:46.914  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 15:08:46.915  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 15:08:46.927   875   885 I ActivityManager: Start proc 3479:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-10 15:08:46.929  1373  1682 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-10 15:08:46.929  1373  1373 D BluetoothA2dp: Proxy object connected
,08-10 15:08:46.931  3396  3396 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-10 15:08:46.931  3396  3396 D ObexServerSockets0: prepareForNewConnect()
,08-10 15:08:46.964  3479  3479 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-10 15:08:46.978  1749  1762 D BluetoothHeadset: Proxy object connected
,08-10 15:08:46.979   875   892 D BluetoothHeadset: Proxy object connected
08-10 15:08:46.980   875   892 D BluetoothHeadset: Proxy object connected
,08-10 15:08:46.990   875   892 D BluetoothHeadset: Proxy object connected
,08-10 15:08:47.032  1373  1385 D BluetoothHeadset: Proxy object connected
,08-10 15:08:47.033  1373  1373 D HeadsetProfile: Bluetooth service connected
,08-10 15:08:47.108  3479  3479 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at java.io.File.exists(File.java:361)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 15:08:47.108  3479  3479 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 15:08:47.108  3479  3479 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 15:08:47.108  3479  3479 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.r.e.b(PG:170)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 15:08:47.108  3479  3479 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.r.k.d(PG:583)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.r.e.b(PG:170)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 15:08:47.108  3479  3479 D StrictMode: StrictMode policy violation; ~duration=56 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at java.io.File.exists(File.java:361)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 15:08:47.108  3479  3479 D StrictMode: StrictMode policy violation; ~duration=56 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at java.io.File.exists(File.java:361)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 15:08:47.108  3479  3479 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 15:08:47.108  3479  3479 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 15:08:47.114  3458  3458 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-10 15:08:47.123  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 15:08:47.124   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9e609bf:true
,08-10 15:08:47.143  3458  3458 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-10 15:08:47.145  1373  1373 D BluetoothPbap: Proxy object connected
,08-10 15:08:47.146  1373  1373 D PbapServerProfile: Bluetooth service connected
,08-10 15:08:47.147  3458  3458 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-10 15:08:47.157  3458  3458 D LocalBluetoothProfileManager: Adding local MAP profile
,08-10 15:08:47.161  3458  3458 D BluetoothMap: Create BluetoothMap proxy object
,08-10 15:08:47.165  3396  3508 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 15:08:47.170  3458  3458 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-10 15:08:47.181  3458  3458 D DockEventReceiver: finishStartingService: stopping service
,08-10 15:08:47.183  3458  3458 D BluetoothA2dp: Proxy object connected
,08-10 15:08:47.186  3396  3514 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 15:08:47.186  3458  3458 D BluetoothInputDevice: Proxy object connected
08-10 15:08:47.186  3458  3458 D HidProfile: Bluetooth service connected
08-10 15:08:47.187  3396  3514 I BtOppRfcommListener: Accept thread started.
08-10 15:08:47.188  3458  3458 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 15:08:47.188  3458  3458 D PanProfile: Bluetooth service connected
08-10 15:08:47.188  3458  3458 D BluetoothMap: Proxy object connected
,08-10 15:08:47.189  3458  3458 D MapProfile: Bluetooth service connected
,08-10 15:08:47.189  3458  3458 D BluetoothMap: getConnectedDevices()
,08-10 15:08:47.191  3458  3458 D BluetoothPbap: Proxy object connected
08-10 15:08:47.191  3458  3458 D PbapServerProfile: Bluetooth service connected
08-10 15:08:47.195   875   886 I ActivityManager: Killing 3023:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-10 15:08:47.254  3458  3469 D BluetoothHeadset: Proxy object connected
,08-10 15:08:47.255  3458  3458 D HeadsetProfile: Bluetooth service connected
,08-10 15:08:47.325  3479  3503 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-10 15:08:47.349   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6813bd8:true
,08-10 15:08:48.223   875   885 D WifiService: setWifiEnabled: true pid=3334, uid=10000
,08-10 15:08:48.223   875   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 15:08:48.235   875  1318 D WifiConfigStore: Loading config and enabling all networks 
,08-10 15:08:48.257  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 15:08:48.257  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:08:48.257  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 15:08:48.257  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 15:08:48.257  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 15:08:48.257  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:08:48.257  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:08:48.257  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 15:08:48.267   875  1318 D WifiConfigStore: loaded 0 passpoint configs
,08-10 15:08:48.269  3334  3334 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 15:08:48.269   875  1318 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-10 15:08:48.270   875  1318 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-10 15:08:48.271   875  1318 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-10 15:08:48.271   875  1318 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-10 15:08:48.271   875  1318 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-10 15:08:48.271   875  1318 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-10 15:08:48.272  1464  1464 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-10 15:08:48.288  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 15:08:48.288  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:08:48.288  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 15:08:48.288  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 15:08:48.288  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 15:08:48.288  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:08:48.288  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:08:48.288  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 15:08:48.291  3334  3334 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 15:08:48.366   374   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-10 15:08:48.366   875  1318 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-10 15:08:48.367  1464  1464 E wpa_supplicant: PNO: In assoc process
,08-10 15:08:48.368   374   873 D CommandListener: Setting iface cfg
,08-10 15:08:48.369   875  1318 E WifiStateMachine:  Fail to set up pno, want true now false
08-10 15:08:48.370   875  1317 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '36 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 36 Failed to set address (No such device)'
08-10 15:08:48.370   875  1317 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-10 15:08:48.372   875  1318 E native  : do suspend true
,08-10 15:08:48.386   875  1317 D WifiNative-HAL: p2pGetDeviceAddress
,08-10 15:08:48.392   875  1317 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-10 15:08:48.399   875  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 15:08:48.739  1464  1464 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-10 15:08:48.780  1464  1464 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-10 15:08:48.781  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-10 15:08:48.784   875  1318 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 15:08:48.793   875  1318 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-10 15:08:48.793   875  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 15:08:48.794   875  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-10 15:08:48.815   875  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 15:08:48.825   374   873 D CommandListener: Setting iface cfg
,08-10 15:08:48.832   875  1318 D WifiStateMachine: Start Dhcp Watchdog 1
,08-10 15:08:48.847   875  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-10 15:08:48.877   875  3524 D DhcpClient: Receive thread started
,08-10 15:08:48.977   875  1318 E native  : do suspend false
,08-10 15:08:49.015   875  3523 D DhcpClient: Broadcasting DHCPDISCOVER
,08-10 15:08:49.032   875  3524 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 169563, domain null
,08-10 15:08:49.035   875  3523 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 169563 seconds
,08-10 15:08:49.039   875  3523 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-10 15:08:49.055   875  3524 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-10 15:08:49.057   875  3523 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-10 15:08:49.062   374   873 D CommandListener: Setting iface cfg
,08-10 15:08:49.075   875  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-10 15:08:49.075   875  3523 D DhcpClient: Scheduling renewal in 86399s
08-10 15:08:49.078   875  1318 E native  : do suspend true
,08-10 15:08:49.108   875  1318 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-10 15:08:49.113   875  1318 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-10 15:08:49.116   875  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-10 15:08:49.123   875  1320 D ConnectivityService: Adding iface wlan0 to network 100
,08-10 15:08:49.136   875  1318 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-10 15:08:49.186   875  1320 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-10 15:08:49.187   875  1320 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,08-10 15:08:49.192   875  1320 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,08-10 15:08:49.195   875  1320 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,08-10 15:08:49.199   875  1320 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,08-10 15:08:49.220   875  1320 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-10 15:08:49.227   875  1320 D ConnectivityService: scheduleUnvalidatedPrompt 100
08-10 15:08:49.227   875  1320 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
08-10 15:08:49.229   875  1320 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
08-10 15:08:49.229   875  1318 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-10 15:08:49.229   875  1320 D ConnectivityService:    accepting network in place of null
,08-10 15:08:49.230   875  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-10 15:08:49.230   875  1320 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-10 15:08:49.241   875  3522 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154451, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 15:08:49.279   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 15:08:49.308   875  3521 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.110,2a00:1450:4001:816::200e
,08-10 15:08:49.316   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 15:08:49.321   875  1320 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,08-10 15:08:49.333   875  1320 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-10 15:08:49.333   875  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 15:08:49.339   875  1320 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,08-10 15:08:49.342   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-10 15:08:49.347   875   885 V BackupManagerService: Scheduling immediate backup pass
08-10 15:08:49.349   875   875 V BackupManagerService: Running a backup pass
,08-10 15:08:49.350   875  1337 V BackupManagerService: clearing pending backups
08-10 15:08:49.359  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 15:08:49.359  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:08:49.359  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 15:08:49.359  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 15:08:49.359  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 15:08:49.359  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 15:08:49.359  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 15:08:49.359  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 15:08:49.362  3334  3334 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 15:08:49.366  1980  1980 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-10 15:08:49.369  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 15:08:49.369  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:08:49.369  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 15:08:49.369  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 15:08:49.369  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 15:08:49.369  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 15:08:49.369  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 15:08:49.369  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 15:08:49.371  1980  1980 D SystemUpdateService: onCreate
,08-10 15:08:49.372  3334  3334 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 15:08:49.375  1980  1980 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-10 15:08:49.378   875  1337 V PerformBackupTask: Beginning backup of 16 targets
,08-10 15:08:49.379  1980  3538 I SystemUpdateService: active receiver: enabled
08-10 15:08:49.385  1980  3538 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-10 15:08:49.400   875  1719 D AlarmManagerService: Setting time of day to sec=1470834529
,08-10 15:08:49.782   875  1719 W AlarmManagerService: Unable to set rtc to 1470834529: Invalid argument
08-10 15:08:49.782   875  3521 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Aug 2016 13:08:49 GMT], X-Android-Received-Millis=[1470834529399], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470834529369]}
,08-10 15:08:49.790  1980  3538 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-10 15:08:49.790  1980  3538 I SystemUpdateService: now status is 0 (complete)
08-10 15:08:49.790  1980  3538 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-10 15:08:49.790  1980  3538 I SystemUpdateService: file has been verified
08-10 15:08:49.790  1980  3538 I SystemUpdateService: OTA package size = 12249756
08-10 15:08:49.790   875  1337 D PerformBackupTask: invokeAgentForBackup on @pm@
,08-10 15:08:49.794  1980  3538 I SystemUpdateService: showing system update notification
,08-10 15:08:49.797   875  1320 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-10 15:08:49.797   875  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
08-10 15:08:49.797   875  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-10 15:08:49.798   875  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-10 15:08:49.809   875  1337 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
,08-10 15:08:49.818  1980  1980 D SystemUpdateService: onDestroy
,08-10 15:08:49.834   875  1337 I BackupRestoreController: Getting widget state for user: 0
,08-10 15:08:49.837   875   886 I ActivityManager: Start proc 3548:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-10 15:08:49.851   875  3562 D GpsLocationProvider: NTP server returned: 1470834529782 (Wed Aug 10 15:08:49 GMT+02:00 2016) reference: 154614 certainty: 10 system time offset: -69
,08-10 15:08:49.852   875  3562 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,08-10 15:08:49.857  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 15:08:49.859  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:08:49.867  3548  3548 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-10 15:08:49.875  1980  3566 I iu.SyncManager: SYNC; picasa accounts
,08-10 15:08:49.883  1980  1980 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-10 15:08:49.885  1980  1980 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-10 15:08:49.889  1980  3566 I iu.UploadsManager: num queued entries: 0
,08-10 15:08:49.893  1980  1980 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-10 15:08:49.894  1980  1980 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-10 15:08:49.902  1980  3566 I iu.UploadsManager: num updated entries: 0
,08-10 15:08:49.905  1980  3566 I iu.SyncManager: NEXT; no task
08-10 15:08:49.905   875  1387 I ActivityManager: Start proc 3570:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-10 15:08:49.912  1980  3565 I MDM     : [189] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-10 15:08:49.912  1980  3565 W BaseAppContext: Using Auth Proxy for data requests.
,08-10 15:08:49.921  1980  3561 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,08-10 15:08:49.934  1980  3565 V GoogleAuthProtoRequest: [189] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 15:08:49.948  3407  3545 V GoogleAuthProtoRequest: [282] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 15:08:49.953  3548  3568 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-10 15:08:49.967  3570  3570 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-10 15:08:49.970  3570  3570 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-10 15:08:49.975  1866  3517 W GmsBackupTransport: Unknown package in backup request: @pm@
,08-10 15:08:49.983  3570  3570 D SprintDMHelper: simOperator: 
,08-10 15:08:49.982  1866  3517 V GmsBackupTransport: starting performBackup for @pm@
,08-10 15:08:49.984  3570  3570 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-10 15:08:49.997   875  2230 I ActivityManager: Start proc 3591:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-10 15:08:50.012  1866  3517 V GmsBackupTransport: performBackup done for @pm@
,08-10 15:08:50.018  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-10 15:08:50.018  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-10 15:08:50.018  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:08:50.018  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:08:50.039  1523  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-10 15:08:50.039  1523  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-10 15:08:50.039  1523  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:08:50.039  1523  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:08:50.043  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:08:50.067  3548  3568 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-10 15:08:50.070  1523  2680 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
,08-10 15:08:50.070  1523  2680 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
,08-10 15:08:50.070  1523  2680 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:08:50.070  1523  2680 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:08:50.080  1523  2680 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 15:08:50.080  1523  2680 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 15:08:50.080  1523  2680 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 15:08:50.080  1523  2680 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-10 15:08:50.080  1523  2680 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-10 15:08:50.080  1523  2680 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-10 15:08:50.080  1523  2680 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 15:08:50.091  1980  3565 E MDM     : [189] SitrepService.a: Error sending sitrep.
,08-10 15:08:50.094  1866  1877 W GmsBackupTransport: Error sending final backup to server: 
08-10 15:08:50.094  1866  1877 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
08-10 15:08:50.094  1866  1877 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
08-10 15:08:50.094  1866  1877 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
08-10 15:08:50.094  1866  1877 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
08-10 15:08:50.094  1866  1877 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
08-10 15:08:50.094  1866  1877 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
08-10 15:08:50.094  1866  1877 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
08-10 15:08:50.094  1866  1877 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-10 15:08:50.094  1866  1877 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-10 15:08:50.094  1866  1877 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-10 15:08:50.094  1866  1877 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-10 15:08:50.094  1866  1877 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-10 15:08:50.094  1866  1877 W GmsBackupTransport: 	... 1 more
,08-10 15:08:50.097  1866  1878 I GmsBackupTransport: Next backup will happen in 43199990 millis.
,08-10 15:08:50.097   875  1337 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
,08-10 15:08:50.107  3548  3568 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-10 15:08:50.112  3407  3545 W ExperimentUpdateService: [282] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-10 15:08:50.113  3407  3545 W ExperimentUpdateService: [282] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 15:08:50.113  3407  3545 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 15:08:50.113  3407  3545 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-10 15:08:50.113  3407  3545 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-10 15:08:50.113  3407  3545 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-10 15:08:50.113  3407  3545 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-10 15:08:50.113  3407  3545 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-10 15:08:50.113  3407  3545 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-10 15:08:50.113  3407  3545 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-10 15:08:50.113  3407  3545 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-10 15:08:50.113  3407  3545 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-10 15:08:50.135   875  1703 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1980 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-10 15:08:50.210  3548  3548 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-10 15:08:50.232   875  1337 I BackupManagerService: Backup pass finished.
,08-10 15:08:50.241  3614  3614 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads1751737927.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads1751737927.dex
,08-10 15:08:50.340   875   885 I ActivityManager: Start proc 3647:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-10 15:08:50.362  1523  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 15:08:50.362  1523  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 15:08:50.362  1523  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:08:50.362  1523  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-10 15:08:50.363  3614  3614 I dex2oat : dex2oat took 127.391ms (threads: 4) arena alloc=251KB java alloc=29KB native alloc=1514KB free=1557KB
,08-10 15:08:50.377  3548  3548 W InstanceID/Rpc: Found 10011
,08-10 15:08:50.379  3647  3647 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-10 15:08:50.404  3140  3588 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 15:08:50.404  3140  3588 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 15:08:50.404  3140  3588 E HttpOperation: 	at jdm.a(PG:82)
08-10 15:08:50.404  3140  3588 E HttpOperation: 	at jcs.o(PG:406)
08-10 15:08:50.404  3140  3588 E HttpOperation: 	at jcn.a(PG:1379)
08-10 15:08:50.404  3140  3588 E HttpOperation: 	at jcs.i(PG:143)
08-10 15:08:50.404  3140  3588 E HttpOperation: 	at blb.a(PG:3937)
08-10 15:08:50.404  3140  3588 E HttpOperation: 	at czp.a(PG:18188)
08-10 15:08:50.404  3140  3588 E HttpOperation: 	at czp.a(PG:9081)
08-10 15:08:50.404  3140  3588 E HttpOperation: 	at czq.run(PG:1686)
08-10 15:08:50.404  3140  3588 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 15:08:50.404  3140  3588 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 15:08:50.404  3140  3588 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 15:08:50.404  3140  3588 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 15:08:50.404  3140  3588 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 15:08:50.404  3140  3588 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 15:08:50.404  3140  3588 E HttpOperation: 	at jdj.a(PG:4091)
08-10 15:08:50.404  3140  3588 E HttpOperation: 	at jdj.a(PG:1125)
08-10 15:08:50.404  3140  3588 E HttpOperation: 	at jdm.a(PG:77)
08-10 15:08:50.404  3140  3588 E HttpOperation: 	... 12 more
08-10 15:08:50.404  3140  3588 E HttpOperation: Caused by: faj: BadAuthentication
08-10 15:08:50.404  3140  3588 E HttpOperation: 	at fal.a(PG:38)
08-10 15:08:50.404  3140  3588 E HttpOperation: 	at jdj.a(PG:4089)
08-10 15:08:50.404  3140  3588 E HttpOperation: 	... 14 more
,08-10 15:08:50.421   875   887 I ActivityManager: Start proc 3685:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-10 15:08:50.455  1980  3567 W DriveInitializer: Awaiting to be initialized
,08-10 15:08:50.455  2348  3646 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-10 15:08:50.456  1980  3702 W DriveInitializer: Background init thread started
,08-10 15:08:50.462  3685  3685 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-10 15:08:50.609  1866  2331 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-10 15:08:50.654  1523  1523 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-10 15:08:50.660  1980  1988 I art     : Background partial concurrent mark sweep GC freed 9279(769KB) AllocSpace objects, 18(360KB) LOS objects, 39% free, 24MB/40MB, paused 6.071ms total 30.898ms
,08-10 15:08:50.675  1980  3702 W DriveInitializer: Background init thread ended
,08-10 15:08:50.704  3685  3685 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-10 15:08:50.706  1523  2687 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-10 15:08:50.706  1523  2687 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 15:08:50.707  1523  2687 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:08:50.707  1523  2687 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:08:50.715  3685  3685 I BooksApp: Created application version: 3.6.9 (30609)
,08-10 15:08:50.720  3140  3588 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 15:08:50.720  3140  3588 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 15:08:50.720  3140  3588 E HttpOperation: 	at jdm.a(PG:82)
08-10 15:08:50.720  3140  3588 E HttpOperation: 	at jcs.o(PG:406)
08-10 15:08:50.720  3140  3588 E HttpOperation: 	at jcn.a(PG:1379)
08-10 15:08:50.720  3140  3588 E HttpOperation: 	at jcs.i(PG:143)
08-10 15:08:50.720  3140  3588 E HttpOperation: 	at hec.a(PG:42)
08-10 15:08:50.720  3140  3588 E HttpOperation: 	at hee.a(PG:102)
08-10 15:08:50.720  3140  3588 E HttpOperation: 	at czr.a(PG:65)
08-10 15:08:50.720  3140  3588 E HttpOperation: 	at kka.a(PG:108)
08-10 15:08:50.720  3140  3588 E HttpOperation: 	at czp.a(PG:19176)
08-10 15:08:50.720  3140  3588 E HttpOperation: 	at czp.a(PG:9081)
08-10 15:08:50.720  3140  3588 E HttpOperation: 	at czq.run(PG:1686)
08-10 15:08:50.720  3140  3588 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 15:08:50.720  3140  3588 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 15:08:50.720  3140  3588 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 15:08:50.720  3140  3588 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 15:08:50.720  3140  3588 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 15:08:50.720  3140  3588 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 15:08:50.720  3140  3588 E HttpOperation: 	at jdj.a(PG:4091)
08-10 15:08:50.720  3140  3588 E HttpOperation: 	at jdj.a(PG:1125)
08-10 15:08:50.720  3140  3588 E HttpOperation: 	at jdm.a(PG:77)
08-10 15:08:50.720  3140  3588 E HttpOperation: 	... 15 more
08-10 15:08:50.720  3140  3588 E HttpOperation: Caused by: faj: BadAuthentication
08-10 15:08:50.720  3140  3588 E HttpOperation: 	at fal.a(PG:38)
08-10 15:08:50.720  3140  3588 E HttpOperation: 	at jdj.a(PG:4089)
08-10 15:08:50.720  3140  3588 E HttpOperation: 	... 17 more
08-10 15:08:50.721  3140  3588 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 15:08:50.721  3140  3588 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 15:08:50.721  3140  3588 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 15:08:50.721  3140  3588 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 15:08:50.721  3140  3588 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 15:08:50.721  3140  3588 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 15:08:50.721  3140  3588 E ExperimentLoader: 	at hec.a(PG:42)
08-10 15:08:50.721  3140  3588 E ExperimentLoader: 	at hee.a(PG:102)
08-10 15:08:50.721  3140  3588 E ExperimentLoader: 	at czr.a(PG:65)
08-10 15:08:50.721  3140  3588 E ExperimentLoader: 	at kka.a(PG:108)
08-10 15:08:50.721  3140  3588 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 15:08:50.721  3140  3588 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 15:08:50.721  3140  3588 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 15:08:50.721  3140  3588 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 15:08:50.721  3140  3588 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 15:08:50.721  3140  3588 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 15:08:50.721  3140  3588 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 15:08:50.721  3140  3588 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 15:08:50.721  3140  3588 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 15:08:50.721  3140  3588 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 15:08:50.721  3140  3588 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-10 15:08:50.721  3140  3588 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 15:08:50.721  3140  3588 E ExperimentLoader: 	... 15 more
08-10 15:08:50.721  3140  3588 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 15:08:50.721  3140  3588 E ExperimentLoader: 	at fal.a(PG:38)
08-10 15:08:50.721  3140  3588 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 15:08:50.721  3140  3588 E ExperimentLoader: 	... 17 more
,08-10 15:08:50.829   875  1387 I ActivityManager: Killing 2482:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-10 15:08:50.830   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 23625, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 15:08:50.918  3685  3730 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 15:08:50.945  3647  3647 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-10 15:08:50.945  3647  3647 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-10 15:08:50.945  3647  3647 I GAv4    :   adb logcat -s GAv4
,08-10 15:08:50.963  3647  3647 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-10 15:08:50.968  3647  3647 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-10 15:08:51.011  3647  3739 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-10 15:08:51.055  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:08:51.091  1523  3721 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,08-10 15:08:51.102  2880  3736 V KeepSync: Connecting to GoogleApiClient
,08-10 15:08:51.102   875  1388 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 15:08:51.175  3647  3647 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-10 15:08:51.176  1523  2688 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-10 15:08:51.176  1523  2688 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-10 15:08:51.176  1523  2688 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 15:08:51.176  1523  2688 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:08:51.198  1980  3757 V BaseAuthAsyncOperation: access token request failed
,08-10 15:08:51.200  2880  3736 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 15:08:51.238  3647  3647 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-10 15:08:51.247  3647  3647 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 6077-6081)
,08-10 15:08:51.247  3647  3647 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 15:08:51.264  3647  3647 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6b830a4}
,08-10 15:08:51.265  3647  3647 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 15:08:51.265  3647  3647 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-10 15:08:51.278  3647  3647 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-10 15:08:51.279  3647  3647 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-10 15:08:51.293  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:08:51.320  3647  3647 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-10 15:08:51.333  1523  2679 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-10 15:08:51.333  1523  2679 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-10 15:08:51.333  1523  2679 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:08:51.333  1523  2679 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:08:51.356  2602  2602 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-10 15:08:51.357  2602  2602 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-10 15:08:51.357  2602  2602 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-10 15:08:51.372  3647  3647 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 15:08:51.372  3647  3647 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 15:08:51.373  3647  3647 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 15:08:51.373  3647  3647 I Adreno  : Build Date                       : 10/20/15
08-10 15:08:51.373  3647  3647 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 15:08:51.373  3647  3647 I Adreno  : Local Branch                     : M14
08-10 15:08:51.373  3647  3647 I Adreno  : Remote Branch                    : 
08-10 15:08:51.373  3647  3647 I Adreno  : Remote Branch                    : 
08-10 15:08:51.373  3647  3647 I Adreno  : Reconstruct Branch               : 
,08-10 15:08:51.493  3647  3647 I NSApplication: Starting up...
,08-10 15:08:51.507  3647  3774 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-10 15:08:51.541   875   886 I ActivityManager: Start proc 3781:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-10 15:08:51.548   875   886 I ActivityManager: Killing 2747:android.process.acore/u0a5 (adj 15): empty #17
,08-10 15:08:51.551  3685  3786 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 15:08:51.610   875  1387 D WifiService: setWifiEnabled: false pid=3334, uid=10000
08-10 15:08:51.610   875  1387 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 15:08:51.641  1464  1464 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-10 15:08:51.645   875  1318 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-10 15:08:51.646   875  1318 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-10 15:08:51.646   875  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-10 15:08:51.647   875  1318 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 15:08:51.664   875  1318 E native  : do suspend true
,08-10 15:08:51.676   875  3523 D DhcpClient: Clearing IP address
,08-10 15:08:51.676   374   873 D CommandListener: Clearing all IP addresses on wlan0
,08-10 15:08:51.680   374   873 D CommandListener: Setting iface cfg
,08-10 15:08:51.680  1523  3609 V NativeCrypto: Read error: ssl=0x9a8e7200: I/O error during system call, Connection timed out
,08-10 15:08:51.682  1523  3609 V NativeCrypto: SSL shutdown failed: ssl=0x9a8e7200: I/O error during system call, Broken pipe
,08-10 15:08:51.685   875  1710 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-10 15:08:51.685   875  3521 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-10 15:08:51.686   875  3521 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.110,2a00:1450:4001:816::200e
08-10 15:08:51.688   875  3524 D DhcpClient: Receive thread stopped
,08-10 15:08:51.690   875  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-10 15:08:51.690   875  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-10 15:08:51.690   875  1318 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-10 15:08:51.691   875  1318 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-10 15:08:51.691   875  1318 E native  : do suspend true
,08-10 15:08:51.691   875  3521 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:816::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-10 15:08:51.693   397   397 E Parcel  : Reading a NULL string not supported here.
,08-10 15:08:51.695  1523  2679 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 15:08:51.695  1523  2679 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-10 15:08:51.695  1523  2679 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 15:08:51.695  1523  2679 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:08:51.700   875  1320 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-10 15:08:51.714  1523  2687 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-10 15:08:51.714  1523  2687 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-10 15:08:51.717  1523  2687 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:08:51.717  1523  2687 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:08:51.729  3781  3781 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-10 15:08:51.736   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 15:08:51.759   374   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 15:08:51.759   374   873 D CommandListener: Clearing all IP addresses on wlan0
08-10 15:08:51.760   875  1320 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-10 15:08:51.760   875  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 15:08:51.761   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-10 15:08:51.765   875  1318 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-10 15:08:51.768  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 15:08:51.768  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:08:51.768  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 15:08:51.768  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 15:08:51.768  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 15:08:51.768  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:08:51.768  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:08:51.768  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 15:08:51.770  3334  3334 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 15:08:51.772  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 15:08:51.772  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:08:51.772  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 15:08:51.772  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 15:08:51.772  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 15:08:51.772  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:08:51.772  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:08:51.772  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 15:08:51.773  3334  3334 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 15:08:51.779   875  1318 D WifiConfigStore: Retrieve network priorities after PNO.
08-10 15:08:51.782  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 15:08:51.782  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:08:51.782  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 15:08:51.782  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 15:08:51.782  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 15:08:51.782  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:08:51.782  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:08:51.782  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 15:08:51.784  3334  3334 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 15:08:51.784  1866  2060 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-10 15:08:51.786   875  1318 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-10 15:08:51.788  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 15:08:51.788  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:08:51.788  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 15:08:51.788  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 15:08:51.788  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 15:08:51.788  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:08:51.788  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:08:51.788  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 15:08:51.790  3334  3334 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 15:08:51.810  1523  3808 I VacuumService: Vacuum at: now=1470834531810 tag=VacuumService
,08-10 15:08:51.816   374   873 E Netd    : netlink response contains error (No such file or directory)
,08-10 15:08:51.817   875  1320 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-10 15:08:51.825  2880  3736 E KeepSync: IOException
08-10 15:08:51.825  2880  3736 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 15:08:51.825  2880  3736 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 15:08:51.825  2880  3736 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 15:08:51.825  2880  3736 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 15:08:51.825  2880  3736 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 15:08:51.825  2880  3736 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 15:08:51.825  2880  3736 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 15:08:51.825  2880  3736 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 15:08:51.825  2880  3736 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 15:08:51.825  2880  3736 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 15:08:51.825  2880  3736 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 15:08:51.825  2880  3736 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 15:08:51.825  2880  3736 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 15:08:51.825  2880  3736 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 15:08:51.825  2880  3736 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 15:08:51.825  2880  3736 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 15:08:51.825  2880  3736 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 15:08:51.825  2880  3736 E KeepSync: 	... 10 more
,08-10 15:08:51.825  2880  3736 W KeepSync: Sync result 2
,08-10 15:08:51.843  1523  2245 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 15:08:51.844  1523  2245 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 15:08:51.844  1523  2245 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:08:51.844  1523  2245 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:08:51.855  3685  3786 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 15:08:51.857  3685  3730 E BooksSync: Soft error
08-10 15:08:51.857  3685  3730 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 15:08:51.857  3685  3730 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 15:08:51.857  3685  3730 E BooksSync: Sync error
08-10 15:08:51.857  3685  3730 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 15:08:51.857  3685  3730 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 15:08:51.857  3685  3730 I BooksSync: Finished books sync
,08-10 15:08:51.905   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 23635, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
08-10 15:08:51.907   875  1388 I ActivityManager: Killing 3220:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-10 15:08:51.932   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 23634, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 15:08:51.933   875   886 I ActivityManager: Killing 3237:com.android.musicfx/u0a18 (adj 15): empty #17
,08-10 15:08:51.997  1523  3809 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-10 15:08:51.998  1523  3809 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-10 15:08:52.019  1523  3809 W Uploader:  no longer exists, so no auth token.
,08-10 15:08:52.029  1523  3809 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,08-10 15:08:52.268   875  3797 I ActivityManager: Killing 3058:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-10 15:08:52.400  1980  3817 I EventLogService: Opted in for usage reporting
,08-10 15:08:52.401  1980  3817 I EventLogService: Aggregate from 1470832716136 (log), 1470832716136 (data)
,08-10 15:08:52.425  2348  3820 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-10 15:08:52.436  1980  1980 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-10 15:08:52.444  1980  1980 D SystemUpdateService: onCreate
,08-10 15:08:52.446  1980  1980 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-10 15:08:52.450  1980  3821 I SystemUpdateService: active receiver: enabled
,08-10 15:08:52.454  1980  3821 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-10 15:08:52.457  1980  3821 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-10 15:08:52.457  1980  3821 I SystemUpdateService: now status is 0 (complete)
08-10 15:08:52.457  1980  3821 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-10 15:08:52.458  1980  3821 I SystemUpdateService: file has been verified
,08-10 15:08:52.459  1980  3821 I SystemUpdateService: OTA package size = 12249756
,08-10 15:08:52.462  1980  3821 I SystemUpdateService: showing system update notification
,08-10 15:08:52.468  1980  1980 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-10 15:08:52.471  1980  3566 I iu.UploadsManager: num queued entries: 0
,08-10 15:08:52.471  1980  3566 I iu.UploadsManager: num updated entries: 0
,08-10 15:08:52.473  1980  3566 I iu.SyncManager: NEXT; no task
,08-10 15:08:52.475  1980  1980 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-10 15:08:52.477  1980  1980 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-10 15:08:52.479  3570  3570 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-10 15:08:52.483  1980  1980 D SystemUpdateService: onDestroy
,08-10 15:08:52.484  3570  3570 D SprintDMHelper: simOperator: 
,08-10 15:08:52.484  3570  3570 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-10 15:08:52.514  1980  3817 W EventLogAggregator: Unknown tag: snet_gcore
,08-10 15:08:52.514  1980  3817 W EventLogAggregator: Unknown tag: snet_launch_service
,08-10 15:08:52.561  1980  3817 I ServiceDumpSys: dumping service [account]
,08-10 15:08:54.623  3396  3434 D BluetoothAdapterState: Current state: ON, message: 23
,08-10 15:08:54.624  3396  3434 D BluetoothAdapterProperties: Setting state to 13
,08-10 15:08:54.624  3396  3434 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-10 15:08:54.626  3396  3434 D BluetoothAdapterProperties: onBluetoothDisable()
08-10 15:08:54.629  3396  3434 I BluetoothAdapterState: Entering PendingCommandState
,08-10 15:08:54.633  3396  3396 D BluetoothMapService: onReceive
08-10 15:08:54.633  3396  3396 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 15:08:54.633  3396  3396 D BluetoothMapService: STATE_TURNING_OFF
08-10 15:08:54.634  3396  3396 D BluetoothMapService: MAP Service closeService in
,08-10 15:08:54.634  3396  3396 D BluetoothMapMasInstance0: MAP Service shutdown
08-10 15:08:54.635  3396  3396 D ObexServerSockets0: shutdown(block = true)
,08-10 15:08:54.636  3396  3477 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-10 15:08:54.643  3396  3396 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-10 15:08:54.644  3334  3334 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:08:54.645  3396  3396 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-10 15:08:54.645  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 15:08:54.645  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:08:54.645  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 15:08:54.645  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 15:08:54.645  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 15:08:54.645  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:08:54.645  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:08:54.645  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 15:08:54.645  3396  3451 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-10 15:08:54.645  3396  3478 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-10 15:08:54.647  3396  3396 I BtOppRfcommListener: stopping Accept Thread
08-10 15:08:54.647  3334  3334 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:08:54.647  3334  3334 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 15:08:54.648  3396  3514 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 15:08:54.649  3396  3514 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-10 15:08:54.649  3458  3458 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 15:08:54.651  3396  3438 D BluetoothAdapterProperties: Scan Mode:20
08-10 15:08:54.651  3396  3434 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-10 15:08:54.655  3334  3334 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:08:54.655  3396  3396 D HeadsetService: Received stop request...Stopping profile...
08-10 15:08:54.655  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 15:08:54.655  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:08:54.655  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 15:08:54.655  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 15:08:54.655  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 15:08:54.655  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:08:54.655  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:08:54.655  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 15:08:54.656  3334  3334 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:08:54.657  3334  3334 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 15:08:54.659  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 15:08:54.660   875   875 D BluetoothHeadset: Proxy object disconnected
08-10 15:08:54.661   875   875 D BluetoothHeadset: Proxy object disconnected
08-10 15:08:54.661  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 15:08:54.661   875   875 D BluetoothHeadset: Proxy object disconnected
08-10 15:08:54.661  1373  1389 D BluetoothHeadset: Proxy object disconnected
08-10 15:08:54.661  1749  1762 D BluetoothHeadset: Proxy object disconnected
08-10 15:08:54.662  3458  3468 D BluetoothHeadset: Proxy object disconnected
,08-10 15:08:54.670  3396  3396 V BluetoothAdapterState: isTurningOff()=true
,08-10 15:08:54.670  3396  3396 V BluetoothAdapterState: isTurningOn()=false
,08-10 15:08:54.670  3396  3396 V BluetoothAdapterState: isBleTurningOn()=false
08-10 15:08:54.670  1373  1373 D HeadsetProfile: Bluetooth service disconnected
08-10 15:08:54.670  3396  3396 V BluetoothAdapterState: isBleTurningOff()=false
08-10 15:08:54.672  3458  3458 D DockEventReceiver: finishStartingService: stopping service
08-10 15:08:54.672  3396  3396 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-10 15:08:54.672  3396  3449 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 15:08:54.672  3396  3449 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 15:08:54.672  3396  3449 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 15:08:54.672  3396  3438 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-10 15:08:54.672  3396  3438 E bt_btif : btif_hf_upstreams_evt: Invalid index 99,
,08-10 15:08:54.673  3396  3396 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 15:08:54.674  3458  3458 D HeadsetProfile: Bluetooth service disconnected
,08-10 15:08:54.675  3396  3396 D A2dpService: Received stop request...Stopping profile...
,08-10 15:08:54.675  3396  3471 D A2dpStateMachine: Exit Disconnected: -1
,08-10 15:08:54.677  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 15:08:54.681  1373  1373 D BluetoothA2dp: Proxy object disconnected
,08-10 15:08:54.681   875   875 D BluetoothA2dp: Proxy object disconnected,
08-10 15:08:54.681  3458  3458 D BluetoothA2dp: Proxy object disconnected
,08-10 15:08:54.682  3396  3396 D HidService: Received stop request...Stopping profile...
,08-10 15:08:54.682  3396  3396 D HidService: Stopping Bluetooth HidService
,08-10 15:08:54.683  1373  1373 D BluetoothInputDevice: Proxy object disconnected
,08-10 15:08:54.683  1373  1373 D HidProfile: Bluetooth service disconnected
,08-10 15:08:54.684  3458  3458 D BluetoothInputDevice: Proxy object disconnected
,08-10 15:08:54.684  3458  3458 D HidProfile: Bluetooth service disconnected
08-10 15:08:54.684  3396  3396 D HealthService: Received stop request...Stopping profile...
08-10 15:08:54.687  3396  3396 D PanService: Received stop request...Stopping profile...
,08-10 15:08:54.688  1373  1373 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-10 15:08:54.688  1373  1373 D PanProfile: Bluetooth service disconnected
,08-10 15:08:54.688  3396  3396 D BluetoothMapService: Received stop request...Stopping profile...
,08-10 15:08:54.688  3458  3458 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 15:08:54.688  3396  3396 D BluetoothMapService: stop()
08-10 15:08:54.688  3458  3458 D PanProfile: Bluetooth service disconnected
,08-10 15:08:54.689  3396  3396 D BluetoothMapAppObserver: deinitObservers()
,08-10 15:08:54.689  3396  3396 D BluetoothMapAppObserver: removeReceiver()
08-10 15:08:54.690  3458  3458 D BluetoothMap: Proxy object disconnected
08-10 15:08:54.690  1373  1373 D BluetoothMap: Proxy object disconnected
08-10 15:08:54.690  3458  3458 D MapProfile: Bluetooth service disconnected
,08-10 15:08:54.690  1373  1373 D MapProfile: Bluetooth service disconnected
08-10 15:08:54.691  3458  3458 D BluetoothPbap: Proxy object disconnected
08-10 15:08:54.691  3458  3458 D PbapServerProfile: Bluetooth service disconnected
08-10 15:08:54.691  1373  1373 D BluetoothPbap: Proxy object disconnected,
08-10 15:08:54.692  3396  3396 V BluetoothAdapterState: isTurningOff()=true
08-10 15:08:54.692  1373  1373 D PbapServerProfile: Bluetooth service disconnected
,08-10 15:08:54.692  3396  3396 V BluetoothAdapterState: isTurningOn()=false
08-10 15:08:54.692  3396  3396 V BluetoothAdapterState: isBleTurningOn()=false
08-10 15:08:54.692  3396  3396 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 15:08:54.695  3396  3449 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 15:08:54.695  3396  3449 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 15:08:54.696  3396  3449 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 15:08:54.696  3396  3449 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 15:08:54.696  3396  3449 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-10 15:08:54.696  3396  3449 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 15:08:54.696  3396  3438 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-10 15:08:54.696  3396  3396 V BluetoothAdapterState: isTurningOff()=true
08-10 15:08:54.696  3396  3396 V BluetoothAdapterState: isTurningOn()=false
08-10 15:08:54.696  3396  3396 V BluetoothAdapterState: isBleTurningOn()=false,
08-10 15:08:54.696  3396  3396 V BluetoothAdapterState: isBleTurningOff()=false
08-10 15:08:54.696  3396  3396 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-10 15:08:54.696  3396  3396 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-10 15:08:54.696  3396  3396 V BluetoothAdapterState: isTurningOff()=true
,08-10 15:08:54.696  3396  3438 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-10 15:08:54.697  3396  3396 V BluetoothAdapterState: isTurningOn()=false
08-10 15:08:54.697  3396  3396 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 15:08:54.697  3396  3396 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 15:08:54.697  3396  3396 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-10 15:08:54.697  3396  3438 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-10 15:08:54.697  3396  3396 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-10 15:08:54.698  3396  3396 V BluetoothAdapterState: isTurningOff()=true
08-10 15:08:54.698  3396  3396 V BluetoothAdapterState: isTurningOn()=false
08-10 15:08:54.698  3396  3396 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 15:08:54.698  3396  3396 V BluetoothAdapterState: isBleTurningOff()=false
08-10 15:08:54.698  3396  3396 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-10 15:08:54.698  3396  3396 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object,
08-10 15:08:54.699  3396  3396 D BluetoothMapService: MAP Service closeService in
08-10 15:08:54.699  3396  3396 V BluetoothAdapterState: isTurningOff()=true
08-10 15:08:54.699  3396  3396 V BluetoothAdapterState: isTurningOn()=false
,08-10 15:08:54.699  3396  3396 V BluetoothAdapterState: isBleTurningOn()=false
08-10 15:08:54.699  3396  3396 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 15:08:54.700  3396  3434 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-10 15:08:54.700  3396  3434 D BluetoothAdapterProperties: Setting state to 15
08-10 15:08:54.700  3396  3434 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-10 15:08:54.700  3396  3434 I BluetoothAdapterState: Entering BleOnState
08-10 15:08:54.700  3396  3396 D BluetoothMapService: cleanup()
08-10 15:08:54.701  3396  3396 D BluetoothMapService: MAP Service closeService in
,08-10 15:08:54.701  3458  3469 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 15:08:54.702  1373  1385 D BluetoothMap: onBluetoothStateChange: up=false
,08-10 15:08:54.702  1373  1389 D BluetoothPan: onBluetoothStateChange on: false
08-10 15:08:54.703  3458  3468 D BluetoothMap: onBluetoothStateChange: up=false
08-10 15:08:54.703  1373  1848 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-10 15:08:54.704  3458  3469 D BluetoothPbap: onBluetoothStateChange: up=false
08-10 15:08:54.704  1749  1773 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 15:08:54.705  3458  3468 D BluetoothPan: onBluetoothStateChange on: false
08-10 15:08:54.705   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 15:08:54.705  1373  1385 D BluetoothHeadset: onBluetoothStateChange: up=false,
08-10 15:08:54.706   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 15:08:54.706  1373  1389 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-10 15:08:54.706  3458  3469 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 15:08:54.707   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 15:08:54.707  3458  3468 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 15:08:54.707  1373  1848 D BluetoothPbap: onBluetoothStateChange: up=false
,08-10 15:08:54.708   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 15:08:54.708  3396  3434 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-10 15:08:54.708  3396  3434 D BluetoothAdapterProperties: Setting state to 16
08-10 15:08:54.708  3396  3434 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-10 15:08:54.709  3396  3434 D BluetoothAdapterProperties: onBleDisable
,08-10 15:08:54.709  3396  3434 I BluetoothAdapterState: Entering PendingCommandState
08-10 15:08:54.709  3396  3435 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-10 15:08:54.711  3396  3449 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-10 15:08:54.711  3396  3449 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 15:08:54.711  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 15:08:54.712  3396  3438 D BluetoothAdapterProperties: Scan Mode:20
,08-10 15:08:54.713  3458  3458 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-10 15:08:54.715  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 15:08:54.716  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 15:08:54.718  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
08-10 15:08:54.719  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 15:08:54.722  3458  3458 D DockEventReceiver: finishStartingService: stopping service
,08-10 15:08:54.914  3396  3438 I bt_hci  : shut_down
,08-10 15:08:54.914  3396  3442 D bt_hwcfg: hw_epilog_process
,08-10 15:08:54.928  3396  3442 I bt_vendor: low_power_mode_cb
,08-10 15:08:54.956  3396  3442 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-10 15:08:54.956  3396  3442 I bt_vendor: epilog_cb
08-10 15:08:54.956  3396  3442 I bt_hci  : epilog_finished_callback
,08-10 15:08:54.960  3396  3438 I bt_hci_h4: hal_close
,08-10 15:08:54.961  3396  3438 I bt_userial_vendor: device fd = 51 close
,08-10 15:08:55.078  3396  3435 D bt_stack_manager: event_shut_down_stack finished.
,08-10 15:08:55.078  3396  3434 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-10 15:08:55.080  3396  3396 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 15:08:55.080  3396  3434 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-10 15:08:55.081  3396  3396 D BtGatt.GattService: Received stop request...Stopping profile...
,08-10 15:08:55.081  3396  3396 D BtGatt.GattService: stop()
08-10 15:08:55.082  3396  3396 D BtGatt.AdvertiseManager: advertise clients cleared
,08-10 15:08:55.086  3396  3396 V BluetoothAdapterState: isTurningOff()=false
,08-10 15:08:55.086  3396  3396 V BluetoothAdapterState: isTurningOn()=false
08-10 15:08:55.087  3396  3396 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 15:08:55.087  3396  3396 V BluetoothAdapterState: isBleTurningOff()=true
08-10 15:08:55.087  3396  3434 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-10 15:08:55.088  3396  3434 D BluetoothAdapterProperties: Setting state to 10
08-10 15:08:55.088  3396  3434 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-10 15:08:55.090  3396  3434 I BluetoothAdapterState: Entering OffState
,08-10 15:08:55.091   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-10 15:08:55.106  3396  3396 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-10 15:08:55.106  3396  3396 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-10 15:08:55.106  3396  3435 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-10 15:08:55.108  3396  3435 D bt_stack_manager: event_clean_up_stack finished.
,08-10 15:08:55.108  3396  3396 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-10 15:08:55.110  3396  3396 I art     : System.exit called, status: 0
,08-10 15:08:55.110  3396  3396 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-10 15:08:55.160   875   886 I ActivityManager: Process com.android.bluetooth (pid 3396) has died
,08-10 15:08:55.719  3685  3727 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-10 15:08:57.615   875  1320 D ConnectivityService: handlePromptUnvalidated 100
,08-10 15:08:57.667   875   892 I ActivityManager: Start proc 3843:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-10 15:08:57.786  3843  3843 D AdapterServiceConfig: Adding HeadsetService
,08-10 15:08:57.786  3843  3843 D AdapterServiceConfig: Adding A2dpService
,08-10 15:08:57.786  3843  3843 D AdapterServiceConfig: Adding HidService
,08-10 15:08:57.787  3843  3843 D AdapterServiceConfig: Adding HealthService
08-10 15:08:57.787  3843  3843 D AdapterServiceConfig: Adding PanService
,08-10 15:08:57.787  3843  3843 D AdapterServiceConfig: Adding GattService
08-10 15:08:57.787  3843  3843 D AdapterServiceConfig: Adding BluetoothMapService
,08-10 15:08:57.803   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@925d362:true
,08-10 15:08:57.803  3843  3843 D BluetoothAdapterState: make() - Creating AdapterState
,08-10 15:08:57.808  3843  3843 I bt_bluedroid: init
,08-10 15:08:57.809  3843  3855 I BluetoothAdapterState: Entering OffState
,08-10 15:08:57.817  3843  3856 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-10 15:08:57.818  3843  3856 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-10 15:08:57.818  3843  3856 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-10 15:08:57.818  3843  3856 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-10 15:08:57.820  3843  3843 I bt_bluedroid: get_profile_interface socket
08-10 15:08:57.822  3843  3843 I bt_bluedroid: get_profile_interface sdp
,08-10 15:08:57.826  3843  3854 I bt_bluedroid: config_hci_snoop_log
,08-10 15:08:57.827   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-10 15:08:57.829  3843  3859 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 15:08:57.831  3843  3859 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 15:08:57.835  3843  3855 D BluetoothAdapterState: Current state: OFF, message: 0
,08-10 15:08:57.836  3843  3855 D BluetoothAdapterProperties: Setting state to 14
,08-10 15:08:57.837  3843  3855 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-10 15:08:57.841  3843  3855 D BluetoothBondStateMachine: make
,08-10 15:08:57.844  3843  3861 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-10 15:08:57.849  3843  3855 I BluetoothAdapterState: Entering PendingCommandState
,08-10 15:08:57.849  3843  3843 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-10 15:08:57.852  3843  3843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1802b1c
,08-10 15:08:57.854  3843  3843 D BtGatt.DebugUtils: handleDebugAction() action=null
08-10 15:08:57.854  3843  3843 D BtGatt.GattService: Received start request. Starting profile...
,08-10 15:08:57.855  3843  3843 D BtGatt.GattService: start()
,08-10 15:08:57.855  3843  3843 I bt_bluedroid: get_profile_interface gatt
08-10 15:08:57.856  3843  3843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1802b1c
,08-10 15:08:57.856  3843  3843 D BtGatt.AdvertiseManager: advertise manager created
,08-10 15:08:57.864  3843  3843 V BluetoothAdapterState: isTurningOff()=false
,08-10 15:08:57.864  3843  3843 V BluetoothAdapterState: isTurningOn()=false
08-10 15:08:57.864  3843  3843 V BluetoothAdapterState: isBleTurningOn()=true
,08-10 15:08:57.864  3843  3843 V BluetoothAdapterState: isBleTurningOff()=false
08-10 15:08:57.865  3843  3855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-10 15:08:57.865  3843  3855 I bt_bluedroid: enable
,08-10 15:08:57.865  3843  3856 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-10 15:08:57.866  3843  3856 I bt_hci  : start_up
,08-10 15:08:57.880  3843  3856 I bt_vendor: alloc value 0xb39fd189
,08-10 15:08:57.880  3843  3856 I bt_vendor: init
08-10 15:08:57.880  3843  3856 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-10 15:08:57.880  3843  3856 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found,
,08-10 15:08:57.987  3843  3856 D bt_hci  : start_up starting async portion
,08-10 15:08:57.987  3843  3865 I bt_hci  : event_finish_startup
08-10 15:08:57.987  3843  3865 I bt_hci_h4: hal_open
,08-10 15:08:57.987  3843  3865 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-10 15:08:57.993  3843  3865 I bt_userial_vendor: device fd = 51 open
,08-10 15:08:58.030  3843  3865 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 15:08:58.062  3843  3865 D bt_hwcfg: Chipset BCM4354A2
,08-10 15:08:58.062  3843  3865 D bt_hwcfg: Target name = [BCM4354A2]
08-10 15:08:58.063  3843  3865 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-10 15:08:58.716  3843  3865 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-10 15:08:58.717  3843  3865 D bt_hwcfg: Settlement delay -- 100 ms
,08-10 15:08:58.718  3843  3865 I bt_hwcfg: Setting fw settlement delay to 100 
,08-10 15:08:58.834  3843  3865 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 15:08:58.836  3843  3865 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-10 15:08:58.866  3843  3865 I bt_hwcfg: vendor lib fwcfg completed
,08-10 15:08:58.866  3843  3865 I bt_vendor: firmware callback
,08-10 15:08:58.866  3843  3865 I bt_hci  : firmware_config_callback
,08-10 15:08:58.879  3843  3867 I bt_btu  : btu_task pending for preload complete event
,08-10 15:08:58.879  3843  3867 I bt_btu_task: Bluetooth chip preload is complete
,08-10 15:08:58.879  3843  3867 I bt_btu  : btu_task received preload complete event
,08-10 15:08:58.890  3843  3867 I         : BTE_InitTraceLevels -- TRC_HCI
,08-10 15:08:58.891  3843  3867 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-10 15:08:58.891  3843  3867 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-10 15:08:58.891  3843  3867 I         : BTE_InitTraceLevels -- TRC_AVDT
08-10 15:08:58.892  3843  3867 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-10 15:08:58.892  3843  3867 I         : BTE_InitTraceLevels -- TRC_A2D
08-10 15:08:58.892  3843  3867 I         : BTE_InitTraceLevels -- TRC_BNEP
08-10 15:08:58.892  3843  3867 I         : BTE_InitTraceLevels -- TRC_BTM
,08-10 15:08:58.893  3843  3867 I         : BTE_InitTraceLevels -- TRC_GAP
08-10 15:08:58.893  3843  3867 I         : BTE_InitTraceLevels -- TRC_PAN
08-10 15:08:58.893  3843  3867 I         : BTE_InitTraceLevels -- TRC_SDP
,08-10 15:08:58.893  3843  3867 I         : BTE_InitTraceLevels -- TRC_GATT
08-10 15:08:58.894  3843  3867 I         : BTE_InitTraceLevels -- TRC_SMP
08-10 15:08:58.894  3843  3867 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-10 15:08:58.894  3843  3867 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-10 15:08:59.024  3843  3867 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb397ad9d
,08-10 15:08:59.024  3843  3867 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb397ad9d 
,08-10 15:08:59.036  3843  3859 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-10 15:08:59.037  3843  3859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-10 15:08:59.038  3843  3859 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 15:08:59.044  3843  3859 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 15:08:59.047  3843  3859 D BluetoothAdapterProperties: Scan Mode:20
,08-10 15:08:59.050  3843  3859 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-10 15:08:59.050  3843  3859 D bt_hci  : do_postload posting postload work item
,08-10 15:08:59.050  3843  3865 I bt_hci  : event_postload
08-10 15:08:59.050  3843  3865 I bt_vendor: sco_config_cb
08-10 15:08:59.050  3843  3865 I bt_hci  : sco_config_callback postload finished.
,08-10 15:08:59.053  3843  3859 D bt_bte_conf: Device ID record 1 : primary
,08-10 15:08:59.053  3843  3859 D bt_bte_conf:   vendorId            = 000f
08-10 15:08:59.053  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 15:08:59.054  3843  3859 D bt_bte_conf:   vendorIdSource      = 0001
08-10 15:08:59.054  3843  3859 D bt_bte_conf:   product             = 1200
08-10 15:08:59.054  3843  3859 D bt_bte_conf:   version             = 1436
,08-10 15:08:59.054  3843  3859 D bt_bte_conf:   clientExecutableURL = 
08-10 15:08:59.054  3843  3859 D bt_bte_conf:   serviceDescription  = 
08-10 15:08:59.054  3843  3859 D bt_bte_conf:   documentationURL    = 
08-10 15:08:59.055  3843  3859 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-10 15:08:59.055  3843  3856 D bt_stack_manager: event_start_up_stack finished
08-10 15:08:59.057  3843  3865 I bt_vendor: low_power_mode_cb
08-10 15:08:59.057  3843  3855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-10 15:08:59.058  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 15:08:59.058  3843  3855 D BluetoothAdapterProperties: Setting state to 15
08-10 15:08:59.058  3843  3855 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-10 15:08:59.059  3843  3855 I BluetoothAdapterState: Entering BleOnState
08-10 15:08:59.064  3843  3855 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-10 15:08:59.064  3843  3855 D BluetoothAdapterProperties: Setting state to 11
,08-10 15:08:59.068  3843  3855 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-10 15:08:59.075  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 15:08:59.077  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 15:08:59.080  3843  3843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1802b1c
,08-10 15:08:59.080  3843  3843 D HeadsetService: Received start request. Starting profile...
08-10 15:08:59.083  3843  3843 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-10 15:08:59.084  3843  3843 D HeadsetStateMachine: make
,08-10 15:08:59.091  3843  3855 I BluetoothAdapterState: Entering PendingCommandState
,08-10 15:08:59.092  3843  3843 D HeadsetStateMachine: max_hf_connections = 1
,08-10 15:08:59.092  3843  3843 I bt_bluedroid: get_profile_interface handsfree
,08-10 15:08:59.093  3843  3859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-10 15:08:59.093  3843  3859 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-10 15:08:59.098  3843  3843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1802b1c
,08-10 15:08:59.098  3843  3843 D A2dpService: Received start request. Starting profile...
,08-10 15:08:59.099  3843  3843 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-10 15:08:59.099  3843  3843 I bt_bluedroid: get_profile_interface avrcp
,08-10 15:08:59.104  3843  3843 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-10 15:08:59.105  3843  3843 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-10 15:08:59.105  3843  3843 D A2dpStateMachine: make
,08-10 15:08:59.106  3843  3843 I bt_bluedroid: get_profile_interface a2dp
08-10 15:08:59.106  3843  3859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-10 15:08:59.110  3843  3876 D A2dpStateMachine: Enter Disconnected: -2
,08-10 15:08:59.111  3843  3843 I BluetoothHidServiceJni: classInitNative: succeeds
,08-10 15:08:59.112  3843  3843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1802b1c
,08-10 15:08:59.112  3843  3843 D HidService: Received start request. Starting profile...
08-10 15:08:59.113  3843  3843 I bt_bluedroid: get_profile_interface hidhost
08-10 15:08:59.113  3843  3859 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb395c3e5
,08-10 15:08:59.113  3843  3843 D HidService: setHidService(): set to: null
08-10 15:08:59.113  3843  3859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-10 15:08:59.115  3843  3843 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-10 15:08:59.116  3843  3843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1802b1c
,08-10 15:08:59.117  3843  3843 D HealthService: Received start request. Starting profile...
,08-10 15:08:59.119  3843  3843 I bt_bluedroid: get_profile_interface health
,08-10 15:08:59.120  3843  3843 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-10 15:08:59.121  3843  3843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1802b1c
,08-10 15:08:59.122  3843  3843 D PanService: Received start request. Starting profile...
,08-10 15:08:59.122  3843  3843 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-10 15:08:59.123  3843  3843 I bt_bluedroid: get_profile_interface pan
08-10 15:08:59.124  3843  3859 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-10 15:08:59.128  3843  3843 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1802b1c
,08-10 15:08:59.130  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 15:08:59.131  3843  3843 D BluetoothMapService: Received start request. Starting profile...
08-10 15:08:59.131  3843  3843 D BluetoothMapService: start()
,08-10 15:08:59.137  3843  3843 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-10 15:08:59.139  3843  3843 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-10 15:08:59.139  3843  3843 D BluetoothMapAppObserver: createReceiver()
,08-10 15:08:59.142  3843  3843 D BluetoothMapAppObserver: initObservers()
,08-10 15:08:59.142  3843  3843 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-10 15:08:59.149  3843  3843 V BluetoothAdapterState: isTurningOff()=false
,08-10 15:08:59.149  3843  3843 V BluetoothAdapterState: isTurningOn()=true
08-10 15:08:59.149  3843  3843 V BluetoothAdapterState: isBleTurningOn()=false
08-10 15:08:59.149  3843  3843 V BluetoothAdapterState: isBleTurningOff()=false
08-10 15:08:59.150  3843  3874 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-10 15:08:59.151  3843  3843 V BluetoothAdapterState: isTurningOff()=false
,08-10 15:08:59.151  3843  3843 V BluetoothAdapterState: isTurningOn()=true
08-10 15:08:59.151  3843  3843 V BluetoothAdapterState: isBleTurningOn()=false
08-10 15:08:59.151  3843  3843 V BluetoothAdapterState: isBleTurningOff()=false
08-10 15:08:59.151  3843  3843 V BluetoothAdapterState: isTurningOff()=false
08-10 15:08:59.151  3843  3843 V BluetoothAdapterState: isTurningOn()=true
,08-10 15:08:59.152  3843  3843 V BluetoothAdapterState: isBleTurningOn()=false
08-10 15:08:59.152  3843  3843 V BluetoothAdapterState: isBleTurningOff()=false
08-10 15:08:59.152  3843  3843 V BluetoothAdapterState: isTurningOff()=false
08-10 15:08:59.152  3843  3843 V BluetoothAdapterState: isTurningOn()=true
08-10 15:08:59.152  3843  3843 V BluetoothAdapterState: isBleTurningOn()=false
08-10 15:08:59.152  3843  3843 V BluetoothAdapterState: isBleTurningOff()=false
08-10 15:08:59.152  3843  3843 V BluetoothAdapterState: isTurningOff()=false
08-10 15:08:59.152  3843  3843 V BluetoothAdapterState: isTurningOn()=true
08-10 15:08:59.152  3843  3843 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 15:08:59.152  3843  3843 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 15:08:59.153  3843  3843 V BluetoothAdapterState: isTurningOff()=false
,08-10 15:08:59.153  3843  3843 V BluetoothAdapterState: isTurningOn()=true
,08-10 15:08:59.153  3843  3843 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 15:08:59.153  3843  3843 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 15:08:59.154  3843  3855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-10 15:08:59.154  3843  3855 D BluetoothAdapterProperties: ScanMode =  20
,08-10 15:08:59.154  3843  3855 D BluetoothAdapterProperties: State =  11
,08-10 15:08:59.157  3843  3859 D BluetoothAdapterProperties: Scan Mode:21
,08-10 15:08:59.157  3843  3859 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-10 15:08:59.157  3843  3855 D BluetoothAdapterProperties: Setting state to 12
,08-10 15:08:59.157  3843  3855 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-10 15:08:59.159  3458  3469 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 15:08:59.159  3843  3855 I BluetoothAdapterState: Entering OnState
08-10 15:08:59.160  1373  1389 D BluetoothMap: onBluetoothStateChange: up=true
,08-10 15:08:59.162  1373  1848 D BluetoothPan: onBluetoothStateChange on: true
,08-10 15:08:59.163  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 15:08:59.163  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:08:59.163  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 15:08:59.163  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 15:08:59.163  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
08-10 15:08:59.163  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-10 15:08:59.163  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:08:59.163  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 15:08:59.165  1373  1373 D BluetoothMap: Proxy object connected
,08-10 15:08:59.165  1373  1373 D MapProfile: Bluetooth service connected
,08-10 15:08:59.165  3458  3468 D BluetoothMap: onBluetoothStateChange: up=true
08-10 15:08:59.165  1373  1373 D BluetoothMap: getConnectedDevices(),
08-10 15:08:59.166  3334  3334 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
,08-10 15:08:59.167  1373  1373 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 15:08:59.167  1373  1373 D PanProfile: Bluetooth service connected
,08-10 15:08:59.167  3458  3458 D BluetoothMap: Proxy object connected
,08-10 15:08:59.167  1373  1848 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-10 15:08:59.168  3458  3458 D MapProfile: Bluetooth service connected
08-10 15:08:59.168  3458  3458 D BluetoothMap: getConnectedDevices(),
,08-10 15:08:59.169  3843  3843 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-10 15:08:59.171  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 15:08:59.171  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:08:59.171  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 15:08:59.171  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
,08-10 15:08:59.171  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 15:08:59.171  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:08:59.171  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:08:59.171  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 15:08:59.172  3843  3843 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-10 15:08:59.173  3334  3334 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 15:08:59.173  3458  3469 D BluetoothPbap: onBluetoothStateChange: up=true,
08-10 15:08:59.174  3843  3843 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
08-10 15:08:59.176  1749  1773 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 15:08:59.176  3458  3468 D BluetoothPan: onBluetoothStateChange on: true
,08-10 15:08:59.176  3843  3843 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 15:08:59.178  3843  3843 D ObexServerSockets: Succeed to create listening sockets 
,08-10 15:08:59.178  3843  3843 D ObexServerSockets0: startAccept()
08-10 15:08:59.178  3843  3843 D ObexServerSockets0: prepareForNewConnect()
08-10 15:08:59.178   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 15:08:59.179  3458  3458 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 15:08:59.179  1373  1385 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 15:08:59.179  3458  3458 D PanProfile: Bluetooth service connected
08-10 15:08:59.179   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-10 15:08:59.180  1373  1389 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 15:08:59.181  3843  3843 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-10 15:08:59.181  3843  3843 D BluetoothSdpJni: SDP Create record success - handle: 0
08-10 15:08:59.182  3458  3469 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-10 15:08:59.183  1373  1373 D BluetoothInputDevice: Proxy object connected
08-10 15:08:59.183  1373  1373 D HidProfile: Bluetooth service connected
08-10 15:08:59.184   875   875 D BluetoothA2dp: Proxy object connected
,08-10 15:08:59.184  3843  3884 D ObexServerSockets0: Accepting socket connection...
08-10 15:08:59.185   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 15:08:59.185  3458  3468 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-10 15:08:59.185  3843  3883 D ObexServerSockets0: Accepting socket connection...
08-10 15:08:59.186  1373  1373 D BluetoothA2dp: Proxy object connected
08-10 15:08:59.187  3458  3458 D BluetoothA2dp: Proxy object connected
08-10 15:08:59.187  1373  1389 D BluetoothPbap: onBluetoothStateChange: up=true
08-10 15:08:59.189  3458  3458 D BluetoothInputDevice: Proxy object connected
08-10 15:08:59.189  3458  3458 D HidProfile: Bluetooth service connected
08-10 15:08:59.189   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 15:08:59.192   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
08-10 15:08:59.194  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 15:08:59.194  3843  3843 D BluetoothMapService: onReceive
08-10 15:08:59.194  3843  3843 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 15:08:59.194  3843  3843 D BluetoothMapService: STATE_ON
08-10 15:08:59.195  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 15:08:59.198  3458  3458 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-10 15:08:59.205  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 15:08:59.206  3458  3458 D DockEventReceiver: finishStartingService: stopping service
,08-10 15:08:59.214  3458  3458 D BluetoothPbap: Proxy object connected
,08-10 15:08:59.214  3458  3458 D PbapServerProfile: Bluetooth service connected
,08-10 15:08:59.219  3843  3843 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-10 15:08:59.219  3843  3843 D ObexServerSockets0: prepareForNewConnect()
,08-10 15:08:59.220  1373  1373 D BluetoothPbap: Proxy object connected,
,08-10 15:08:59.221  1373  1373 D PbapServerProfile: Bluetooth service connected
,08-10 15:08:59.222  3843  3889 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 15:08:59.239  3843  3893 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 15:08:59.241  3843  3893 I BtOppRfcommListener: Accept thread started.
,08-10 15:08:59.261   875   875 D BluetoothHeadset: Proxy object connected
,08-10 15:08:59.261   875   875 D BluetoothHeadset: Proxy object connected
,08-10 15:08:59.261   875   875 D BluetoothHeadset: Proxy object connected
,08-10 15:08:59.262  1373  1848 D BluetoothHeadset: Proxy object connected
,08-10 15:08:59.262  1373  1373 D HeadsetProfile: Bluetooth service connected
,08-10 15:08:59.263  1749  1888 D BluetoothHeadset: Proxy object connected
,08-10 15:08:59.263  3458  3881 D BluetoothHeadset: Proxy object connected
,08-10 15:08:59.263  3458  3458 D HeadsetProfile: Bluetooth service connected,
,08-10 15:08:59.277  1749  1926 D BluetoothHeadset: Proxy object connected
,08-10 15:08:59.278   875   892 D BluetoothHeadset: Proxy object connected
,08-10 15:08:59.280  1373  1385 D BluetoothHeadset: Proxy object connected
,08-10 15:08:59.280  1373  1373 D HeadsetProfile: Bluetooth service connected
,08-10 15:08:59.285   875   892 D BluetoothHeadset: Proxy object connected
,08-10 15:08:59.289   875   892 D BluetoothHeadset: Proxy object connected
,08-10 15:09:00.626  3334  3385 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 15:09:00.626  3334  3385 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 15:09:00.804  2602  2613 D Finsky  : [177] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-10 15:09:00.826  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:09:00.838  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:09:00.841  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:09:00.898  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-10 15:09:00.899  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-10 15:09:00.900  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 15:09:00.900  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:09:00.965  2602  2613 D Finsky  : [177] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-10 15:09:03.634  3334  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 15:09:03.634  3334  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@85bbb1b added. We now have 6 listener(s)
,08-10 15:09:03.635  3334  3385 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 15:09:03.641  3334  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 15:09:03.642  3334  3385 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f314b8 added. We now have 7 listener(s)
08-10 15:09:03.642  3334  3385 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 15:09:03.645  3334  3385 I System.out: IsBluetoothEnabled
,08-10 15:09:03.656  3843  3855 D BluetoothAdapterState: Current state: ON, message: 23
,08-10 15:09:03.657  3843  3855 D BluetoothAdapterProperties: Setting state to 13
,08-10 15:09:03.657  3843  3855 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-10 15:09:03.659  3843  3855 D BluetoothAdapterProperties: onBluetoothDisable()
,08-10 15:09:03.667  3843  3843 D BluetoothMapService: onReceive
08-10 15:09:03.667  3843  3843 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-10 15:09:03.670  3843  3843 D BluetoothMapService: STATE_TURNING_OFF
,08-10 15:09:03.672  3843  3843 D BluetoothMapService: MAP Service closeService in
08-10 15:09:03.672  3843  3843 D BluetoothMapMasInstance0: MAP Service shutdown
08-10 15:09:03.672  3843  3843 D ObexServerSockets0: shutdown(block = true)
08-10 15:09:03.673  3843  3883 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-10 15:09:03.674  3843  3843 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-10 15:09:03.674  3843  3843 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-10 15:09:03.675  3843  3884 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-10 15:09:03.675  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:09:03.675  3334  3385 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 15:09:03.675  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:09:03.675  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 15:09:03.675  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 15:09:03.675  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 15:09:03.675  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:09:03.675  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:09:03.675  3334  3385 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 15:09:03.676  3843  3859 D BluetoothAdapterProperties: Scan Mode:20
08-10 15:09:03.676  3843  3870 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-10 15:09:03.677  3843  3855 I BluetoothAdapterState: Entering PendingCommandState
08-10 15:09:03.677  3843  3855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-10 15:09:03.680  3334  3334 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:09:03.680  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 15:09:03.680  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:09:03.680  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 15:09:03.680  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 15:09:03.680  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 15:09:03.680  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 15:09:03.680  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 15:09:03.680  3334  3334 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 15:09:03.681  3334  3385 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 15:09:03.681  3334  3385 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 15:09:03.685  3843  3843 I BtOppRfcommListener: stopping Accept Thread
08-10 15:09:03.685  3843  3893 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 15:09:03.686  3334  3334 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is, disabled - will return stored value
08-10 15:09:03.687  3334  3334 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 15:09:03.687  3843  3893 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-10 15:09:03.688  3843  3855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,08-10 15:09:03.688  3843  3855 I BluetoothAdapterState: Deferring BLE_TURN_ON request...
08-10 15:09:03.689  3843  3843 D HeadsetService: Received stop request...Stopping profile...
,08-10 15:09:03.689  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 15:09:03.691  3458  3458 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-10 15:09:03.694   875   875 D BluetoothHeadset: Proxy object disconnected
08-10 15:09:03.694   875   875 D BluetoothHeadset: Proxy object disconnected
08-10 15:09:03.694   875   875 D BluetoothHeadset: Proxy object disconnected
,08-10 15:09:03.695  1373  1848 D BluetoothHeadset: Proxy object disconnected
08-10 15:09:03.695  3843  3843 D A2dpService: Received stop request...Stopping profile...
08-10 15:09:03.695  3843  3876 D A2dpStateMachine: Exit Disconnected: -1
08-10 15:09:03.696  1749  1762 D BluetoothHeadset: Proxy object disconnected
,08-10 15:09:03.697  3458  3469 D BluetoothHeadset: Proxy object disconnected
08-10 15:09:03.697   875   875 D BluetoothA2dp: Proxy object disconnected
,08-10 15:09:03.698  1373  1373 D HeadsetProfile: Bluetooth service disconnected
08-10 15:09:03.698  3843  3843 D HidService: Received stop request...Stopping profile...
08-10 15:09:03.698  1373  1373 D BluetoothA2dp: Proxy object disconnected
08-10 15:09:03.698  3843  3843 D HidService: Stopping Bluetooth HidService
08-10 15:09:03.700  1373  1373 D BluetoothInputDevice: Proxy object disconnected
,08-10 15:09:03.700  1373  1373 D HidProfile: Bluetooth service disconnected
08-10 15:09:03.700  3843  3843 D HealthService: Received stop request...Stopping profile...
,08-10 15:09:03.701  3843  3843 D PanService: Received stop request...Stopping profile...
,08-10 15:09:03.702  1373  1373 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-10 15:09:03.703  1373  1373 D PanProfile: Bluetooth service disconnected
08-10 15:09:03.703  3843  3843 D BluetoothMapService: Received stop request...Stopping profile...
08-10 15:09:03.703  3843  3843 D BluetoothMapService: stop()
08-10 15:09:03.704  3843  3843 D BluetoothMapAppObserver: deinitObservers()
,08-10 15:09:03.704  3843  3843 D BluetoothMapAppObserver: removeReceiver()
,08-10 15:09:03.705  3458  3458 D DockEventReceiver: finishStartingService: stopping service
,08-10 15:09:03.706  1373  1373 D BluetoothMap: Proxy object disconnected
08-10 15:09:03.706  1373  1373 D MapProfile: Bluetooth service disconnected
08-10 15:09:03.706  3458  3458 D BluetoothA2dp: Proxy object disconnected
,08-10 15:09:03.706  3458  3458 D HeadsetProfile: Bluetooth service disconnected
08-10 15:09:03.706  3458  3458 D BluetoothInputDevice: Proxy object disconnected
08-10 15:09:03.707  3458  3458 D HidProfile: Bluetooth service disconnected
08-10 15:09:03.707  3458  3458 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 15:09:03.707  3458  3458 D PanProfile: Bluetooth service disconnected
08-10 15:09:03.707  3843  3843 V BluetoothAdapterState: isTurningOff()=true
,08-10 15:09:03.707  3843  3843 V BluetoothAdapterState: isTurningOn()=false
08-10 15:09:03.707  3843  3843 V BluetoothAdapterState: isBleTurningOn()=false
08-10 15:09:03.707  3843  3843 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 15:09:03.709  3458  3458 D BluetoothMap: Proxy object disconnected
08-10 15:09:03.709  3458  3458 D MapProfile: Bluetooth service disconnected
08-10 15:09:03.709  3843  3843 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-10 15:09:03.709  3843  3843 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-10 15:09:03.709  3843  3859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-10 15:09:03.710  3843  3867 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 15:09:03.710  3843  3867 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 15:09:03.710  3843  3867 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 15:09:03.710  3843  3859 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-10 15:09:03.712  3843  3843 V BluetoothAdapterState: isTurningOff()=true
,08-10 15:09:03.712  3843  3843 V BluetoothAdapterState: isTurningOn()=false
08-10 15:09:03.712  3843  3843 V BluetoothAdapterState: isBleTurningOn()=false
08-10 15:09:03.712  3843  3843 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 15:09:03.713  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 15:09:03.714  3843  3859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-10 15:09:03.714  3843  3867 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 15:09:03.714  3843  3867 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 15:09:03.714  3843  3867 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 15:09:03.714  3843  3867 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 15:09:03.714  3843  3867 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 15:09:03.714  3843  3867 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-10 15:09:03.714  3843  3843 V BluetoothAdapterState: isTurningOff()=true
08-10 15:09:03.714  3843  3843 V BluetoothAdapterState: isTurningOn()=false
08-10 15:09:03.714  3843  3843 V BluetoothAdapterState: isBleTurningOn()=false
08-10 15:09:03.714  3843  3843 V BluetoothAdapterState: isBleTurningOff()=false
08-10 15:09:03.715  3843  3843 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-10 15:09:03.715  3843  3859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-10 15:09:03.715  3843  3843 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-10 15:09:03.716  3843  3843 V BluetoothAdapterState: isTurningOff()=true
08-10 15:09:03.716  3843  3843 V BluetoothAdapterState: isTurningOn()=false
08-10 15:09:03.716  3843  3843 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 15:09:03.716  3843  3843 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 15:09:03.716  3843  3843 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-10 15:09:03.716  3843  3859 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-10 15:09:03.717  3843  3843 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 15:09:03.717  3843  3843 V BluetoothAdapterState: isTurningOff()=true
,08-10 15:09:03.717  3843  3843 V BluetoothAdapterState: isTurningOn()=false
08-10 15:09:03.717  3843  3843 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 15:09:03.717  3843  3843 V BluetoothAdapterState: isBleTurningOff()=false
08-10 15:09:03.718  3843  3843 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-10 15:09:03.718  3843  3843 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-10 15:09:03.718  3843  3843 D BluetoothMapService: MAP Service closeService in
08-10 15:09:03.718  3843  3843 V BluetoothAdapterState: isTurningOff()=true
,08-10 15:09:03.719  3843  3843 V BluetoothAdapterState: isTurningOn()=false
08-10 15:09:03.719  3843  3843 V BluetoothAdapterState: isBleTurningOn()=false
08-10 15:09:03.719  3843  3843 V BluetoothAdapterState: isBleTurningOff()=false,
08-10 15:09:03.719  3843  3855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-10 15:09:03.719  3843  3855 D BluetoothAdapterProperties: Setting state to 15
08-10 15:09:03.719  3843  3855 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15,
08-10 15:09:03.720  3843  3855 I BluetoothAdapterState: Entering BleOnState
08-10 15:09:03.720  3843  3855 D BluetoothAdapterState: Current state: BLE ON, message: 0
08-10 15:09:03.720  3458  3468 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 15:09:03.720  3843  3843 D BluetoothMapService: cleanup()
08-10 15:09:03.720  3843  3843 D BluetoothMapService: MAP Service closeService in
,08-10 15:09:03.721  1373  1389 D BluetoothMap: onBluetoothStateChange: up=false
,08-10 15:09:03.722  1373  1385 D BluetoothPan: onBluetoothStateChange on: false
08-10 15:09:03.722  1373  1373 D BluetoothPbap: Proxy object disconnected
08-10 15:09:03.722  1373  1373 D PbapServerProfile: Bluetooth service disconnected
,08-10 15:09:03.723  3458  3469 D BluetoothMap: onBluetoothStateChange: up=false
08-10 15:09:03.725  1373  1848 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-10 15:09:03.726  3458  3468 D BluetoothPbap: onBluetoothStateChange: up=false
08-10 15:09:03.726  1749  1773 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 15:09:03.727  3458  3881 D BluetoothPan: onBluetoothStateChange on: false
,08-10 15:09:03.727   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 15:09:03.727  1373  1389 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 15:09:03.728   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-10 15:09:03.728  1373  1385 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 15:09:03.729  3458  3469 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-10 15:09:03.729   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 15:09:03.730  3458  3468 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 15:09:03.730  1373  1848 D BluetoothPbap: onBluetoothStateChange: up=false
,08-10 15:09:03.731   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 15:09:03.731  3843  3855 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-10 15:09:03.731  3843  3855 D BluetoothAdapterProperties: Setting state to 16
08-10 15:09:03.731  3843  3855 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-10 15:09:03.732  3843  3855 D BluetoothAdapterProperties: onBleDisable
08-10 15:09:03.732  3843  3855 I BluetoothAdapterState: Entering PendingCommandState
08-10 15:09:03.732  3843  3856 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-10 15:09:03.733  3843  3859 D BluetoothAdapterProperties: Scan Mode:20
08-10 15:09:03.734  3843  3867 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-10 15:09:03.734  3843  3867 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 15:09:03.734  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 15:09:03.736  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 15:09:03.739  3458  3458 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 15:09:03.744  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 15:09:03.750  3458  3458 D DockEventReceiver: finishStartingService: stopping service
,08-10 15:09:03.935  3843  3859 I bt_hci  : shut_down
,08-10 15:09:03.935  3843  3865 D bt_hwcfg: hw_epilog_process
,08-10 15:09:03.945  3843  3865 I bt_vendor: low_power_mode_cb
,08-10 15:09:03.972  3843  3865 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-10 15:09:03.972  3843  3865 I bt_vendor: epilog_cb
08-10 15:09:03.972  3843  3865 I bt_hci  : epilog_finished_callback
,08-10 15:09:03.980  3843  3859 I bt_hci_h4: hal_close
08-10 15:09:03.981  3843  3859 I bt_userial_vendor: device fd = 51 close
,08-10 15:09:04.107  3843  3856 D bt_stack_manager: event_shut_down_stack finished.
,08-10 15:09:04.108  3843  3855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-10 15:09:04.115  3843  3855 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-10 15:09:04.116  3843  3843 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 15:09:04.117  3843  3843 D BtGatt.GattService: Received stop request...Stopping profile...
08-10 15:09:04.118  3843  3843 D BtGatt.GattService: stop()
08-10 15:09:04.118  3843  3843 D BtGatt.AdvertiseManager: advertise clients cleared
,08-10 15:09:04.124  3843  3843 V BluetoothAdapterState: isTurningOff()=false
,08-10 15:09:04.125  3843  3843 V BluetoothAdapterState: isTurningOn()=false
,08-10 15:09:04.125  3843  3843 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 15:09:04.125  3843  3843 V BluetoothAdapterState: isBleTurningOff()=true
08-10 15:09:04.128  3843  3855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-10 15:09:04.128  3843  3855 D BluetoothAdapterProperties: Setting state to 10
08-10 15:09:04.129  3843  3855 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-10 15:09:04.131  3843  3855 I BluetoothAdapterState: Entering OffState
08-10 15:09:04.143  3334  3334 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 15:09:04.151  3458  3458 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 15:09:04.159  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 15:09:04.163  3458  3458 D DockEventReceiver: finishStartingService: stopping service
,08-10 15:09:04.713   875  3795 I ActivityManager: Killing 3186:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-10 15:09:12.356  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:09:12.364  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:09:12.366  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:09:12.400  1523  2245 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-10 15:09:12.400  1523  2245 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-10 15:09:12.400  1523  2245 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:09:12.400  1523  2245 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:09:12.432  2602  2602 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 15:09:12.432  2602  2602 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-10 15:09:12.433  2602  2602 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-10 15:09:32.634  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:09:32.641  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:09:32.643  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:09:32.680  1523  2679 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-10 15:09:32.680  1523  2679 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-10 15:09:32.680  1523  2679 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:09:32.680  1523  2679 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:09:32.704  2602  2602 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 15:09:32.704  2602  2602 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-10 15:09:32.704  2602  2602 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-10 15:09:45.325  1670  1776 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-10 15:09:45.325  1670  1776 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-10 15:09:45.357  1523  1523 I ConfigService: onCreate
,08-10 15:09:50.431  1523  1523 I ConfigService: onDestroy
,08-10 15:09:51.806   875  1320 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-10 15:10:51.856  1523  2012 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-10 15:11:46.514  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:11:46.522  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:11:46.526  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:11:46.584  1523  2679 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-10 15:11:46.585  1523  2679 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-10 15:11:46.585  1523  2679 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:11:46.585  1523  2679 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:11:46.624  1523  2679 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 15:11:46.624  1523  2679 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 15:11:46.624  1523  2679 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 15:11:46.624  1523  2679 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-10 15:11:46.624  1523  2679 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-10 15:11:46.624  1523  2679 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-10 15:11:46.624  1523  2679 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 15:11:46.634  2602  2632 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 15:11:46.634  2602  2632 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-10 15:11:46.634  2602  2632 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-10 15:11:46.634  2602  2632 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-10 15:11:46.634  2602  2632 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-10 15:11:46.634  2602  2632 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-10 15:11:46.634  2602  2632 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 15:16:46.798  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:16:46.819  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:16:46.827  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:16:46.933  1523  1920 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-10 15:16:46.933  1523  1920 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-10 15:16:46.933  1523  1920 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 15:16:46.933  1523  1920 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:16:46.946  1523  1920 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 15:16:46.946  1523  1920 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 15:16:46.946  1523  1920 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 15:16:46.946  1523  1920 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-10 15:16:46.946  1523  1920 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-10 15:16:46.946  1523  1920 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-10 15:16:46.946  1523  1920 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 15:16:46.949  2602  2632 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 15:16:46.949  2602  2632 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-10 15:16:46.949  2602  2632 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-10 15:16:46.949  2602  2632 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-10 15:16:46.949  2602  2632 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-10 15:16:46.949  2602  2632 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-10 15:16:46.949  2602  2632 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 15:18:44.145  2602  2602 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,08-10 15:18:44.172  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:18:44.188  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:18:44.193  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:18:44.253  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-10 15:18:44.254  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-10 15:18:44.254  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:18:44.255  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:18:44.303  2602  2602 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-10 15:18:44.325  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:18:44.379  1523  1920 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-10 15:18:44.380  1523  1920 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-10 15:18:44.380  1523  1920 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:18:44.381  1523  1920 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:18:44.459  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:18:44.530  1523  2680 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-10 15:18:44.530  1523  2680 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-10 15:18:44.531  1523  2680 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 15:18:44.531  1523  2680 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:18:44.597  2602  2602 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-10 15:18:44.944  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:18:44.983  1523  2679 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-10 15:18:44.984  1523  2679 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-10 15:18:44.984  1523  2679 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:18:44.984  1523  2679 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:18:45.011  2602  2602 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
08-10 15:18:45.012  2602  2602 D Finsky  : [1] WearSupportService.startHygiene: disabled
08-10 15:18:45.012  2602  2602 D Finsky  : [1] DailyHygiene.access$600: Logging device features
08-10 15:18:45.016  2602  2602 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,08-10 15:18:45.017  2602  3168 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-10 15:19:00.007  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:19:00.018  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:19:00.020  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:19:00.086  1523  2687 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-10 15:19:00.086  1523  2687 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-10 15:19:00.087  1523  2687 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:19:00.087  1523  2687 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:19:00.135  2602  2602 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 15:19:00.135  2602  2602 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-10 15:19:00.136  2602  2602 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,08-10 15:19:20.503  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:19:20.521  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:19:20.530  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:19:20.607  1523  2687 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-10 15:19:20.608  1523  2687 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 15:19:20.608  1523  2687 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:19:20.609  1523  2687 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:19:20.672  2602  2602 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 15:19:20.673  2602  2602 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-10 15:19:20.675  2602  2602 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,08-10 15:19:41.205  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:19:41.231  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:19:41.238  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:19:41.297  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-10 15:19:41.298  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 15:19:41.298  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:19:41.299  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:19:41.347  2602  2602 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 15:19:41.347  2602  2602 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-10 15:19:41.348  2602  2602 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.,
,08-10 15:20:01.607  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:20:01.620  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:20:01.623  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:20:01.682  1523  2679 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-10 15:20:01.683  1523  2679 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-10 15:20:01.683  1523  2679 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:20:01.684  1523  2679 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:20:01.732  2602  2602 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 15:20:01.733  2602  2602 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-10 15:20:01.733  2602  2602 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-10 15:20:22.077  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:20:22.091  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:20:22.098  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:20:22.170  1523  2688 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-10 15:20:22.171  1523  2688 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 15:20:22.171  1523  2688 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:20:22.172  1523  2688 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:20:22.242  2602  2602 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 15:20:22.243  2602  2602 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-10 15:20:22.245  2602  2602 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-10 15:20:42.725  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:20:42.741  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:20:42.744  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:20:42.805  1523  1920 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-10 15:20:42.805  1523  1920 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-10 15:20:42.806  1523  1920 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:20:42.806  1523  1920 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:20:42.871  2602  2602 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 15:20:42.874  2602  2602 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-10 15:20:42.876  2602  2602 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-10 15:21:47.084  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:21:47.102  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:21:47.105  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:21:47.151  1523  1920 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-10 15:21:47.151  1523  1920 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-10 15:21:47.151  1523  1920 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:21:47.151  1523  1920 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:21:47.188  1523  1920 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 15:21:47.188  1523  1920 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 15:21:47.188  1523  1920 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 15:21:47.188  1523  1920 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-10 15:21:47.188  1523  1920 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-10 15:21:47.188  1523  1920 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-10 15:21:47.188  1523  1920 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 15:21:47.203  2602  2632 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 15:21:47.203  2602  2632 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-10 15:21:47.203  2602  2632 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-10 15:21:47.203  2602  2632 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-10 15:21:47.203  2602  2632 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-10 15:21:47.203  2602  2632 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-10 15:21:47.203  2602  2632 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 15:26:33.663   875   887 I UsageStatsService: User[0] Flushing usage stats to disk
,08-10 15:26:47.346  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:26:47.365  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:26:47.372  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:26:47.457  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-10 15:26:47.457  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-10 15:26:47.457  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:26:47.458  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:26:47.493  1523  1535 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 15:26:47.493  1523  1535 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 15:26:47.493  1523  1535 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 15:26:47.493  1523  1535 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-10 15:26:47.493  1523  1535 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-10 15:26:47.493  1523  1535 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-10 15:26:47.493  1523  1535 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 15:26:47.503  2602  2632 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 15:26:47.503  2602  2632 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-10 15:26:47.503  2602  2632 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-10 15:26:47.503  2602  2632 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-10 15:26:47.503  2602  2632 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-10 15:26:47.503  2602  2632 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-10 15:26:47.503  2602  2632 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 15:31:47.653  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:31:47.675  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:31:47.683  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 15:31:47.771  1523  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-10 15:31:47.771  1523  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-10 15:31:47.772  1523  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 15:31:47.772  1523  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 15:31:47.823  1523  1534 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 15:31:47.823  1523  1534 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 15:31:47.823  1523  1534 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 15:31:47.823  1523  1534 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-10 15:31:47.823  1523  1534 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-10 15:31:47.823  1523  1534 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-10 15:31:47.823  1523  1534 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 15:31:47.837  2602  2632 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 15:31:47.837  2602  2632 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-10 15:31:47.837  2602  2632 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-10 15:31:47.837  2602  2632 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-10 15:31:47.837  2602  2632 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-10 15:31:47.837  2602  2632 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-10 15:31:47.837  2602  2632 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms),08-10 15:31:57.465  4000  4000 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-10 15:31:57.469  4000  4000 D AndroidRuntime: CheckJNI is OFF
08-10 15:31:57.505  4000  4000 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-10 15:31:57.546  4000  4000 I Radio-JNI: register_android_hardware_Radio DONE
08-10 15:31:57.568  4000  4000 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-10 15:31:57.588   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-10 15:31:57.589   875   888 I ActivityManager: Killing 3334:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-10 15:31:57.684   875  2115 I WindowState: WIN DEATH: Window{ab1537d u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-10 15:31:57.685   875   885 D GraphicsStats: Buffer count: 2
08-10 15:31:57.687   875  1319 D WifiService: Client connection lost with reason: 4
08-10 15:31:57.730   875   898 W PackageSettings: Skipping PackageSetting{3801679 com.example.hello/10273} due to missing metadata
08-10 15:31:57.758   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-10 15:31:57.758   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-10 15:31:57.759   875   888 E ActivityManager: Failure starting process com.test.thalitest
08-10 15:31:57.759   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-10 15:31:57.759   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-10 15:31:57.759   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-10 15:31:57.759   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-10 15:31:57.759   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-10 15:31:57.759   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-10 15:31:57.759   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-10 15:31:57.759   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-10 15:31:57.759   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-10 15:31:57.759   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-10 15:31:57.759   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-10 15:31:57.759   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-10 15:31:57.759   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-10 15:31:57.759   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-10 15:31:57.759   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-10 15:31:57.759   875   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:31:57.759   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:31:57.759   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 15:31:57.759   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-10 15:31:57.759   875   898 I art     : Starting a blocking GC Explicit
08-10 15:31:57.760   875   888 I ActivityManager:   Force finishing activity ActivityRecord{eb5b6ba u0 com.test.thalitest/.MainActivity t8}
08-10 15:31:57.768   875  3794 W ActivityManager: Spurious death for ProcessRecord{6d4f91f 0:com.test.thalitest/u0a0}, curProc for 3334: null
08-10 15:31:57.800   875   898 I art     : Explicit concurrent mark sweep GC freed 23983(1699KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/43MB, paused 722us total 40.213ms
08-10 15:31:57.835   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-10 15:31:57.839  4000  4000 I art     : System.exit called, status: 0
08-10 15:31:57.840  4000  4000 I AndroidRuntime: VM exiting with result code 0.
08-10 15:31:57.851   875   898 I ActivityManager: Start proc 4013:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-10 15:31:57.851   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-10 15:31:57.864   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-10 15:31:57.870   875  1308 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-10 15:31:57.879  1866  2024 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-10 15:31:57.890  1670  1670 I Keyboard.Facilitator: resetDictionaries() : en_US
08-10 15:31:57.889  3206  3206 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-10 15:31:57.932  1749  1749 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-10 15:31:57.936  1670  4027 I Keyboard.Facilitator.DecoderInitializer: run()
08-10 15:31:57.949   875  1710 I ActivityManager: Start proc 4030:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-10 15:31:57.962   875  3794 I ActivityManager: Killing 3266:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-10 15:31:57.970  1670  4027 I Decoder : createOrResetDecoder
08-10 15:31:57.975   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-10 15:31:57.983   875  3608 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3334 uid 10000
08-10 15:31:57.984  1670  1670 I Keyboard.Facilitator: onFinishInput()
08-10 15:31:58.026  1523  1523 I ConfigService: onCreate
08-10 15:31:58.028  1763  1841 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-10 15:31:58.028   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-10 15:31:58.029   875   887 E PackageManager: Failed to write settings, restoring backup
08-10 15:31:58.029   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-10 15:31:58.029   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-10 15:31:58.029   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-10 15:31:58.029   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-10 15:31:58.029   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-10 15:31:58.029   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:31:58.029   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:31:58.029   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 15:31:58.034   875   888 E DropBoxManagerService: Can't write: system_server_wtf
08-10 15:31:58.034   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-10 15:31:58.034   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 15:31:58.034   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 15:31:58.034   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 15:31:58.034   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 15:31:58.034   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 15:31:58.034   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 15:31:58.034   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-10 15:31:58.034   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-10 15:31:58.034   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-10 15:31:58.034   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 15:31:58.034   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 15:31:58.034   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:31:58.034   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 15:31:58.034   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-10 15:31:58.034   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 15:31:58.034   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 15:31:58.034   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 15:31:58.034   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 15:31:58.034   875   888 E DropBoxManagerService: 	... 13 more
08-10 15:31:58.036  1523  4043 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-10 15:31:58.036  1523  4043 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 15:31:58.036  1523  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 15:31:58.036  1523  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 15:31:58.036  1523  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 15:31:58.036  1523  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 15:31:58.036  1523  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 15:31:58.036  1523  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 15:31:58.036  1523  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 15:31:58.036  1523  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 15:31:58.036  1523  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 15:31:58.036  1523  4043 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 15:31:58.036  1523  4043 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 15:31:58.036  1523  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 15:31:58.036  1523  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 15:31:58.036  1523  4043 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-10 15:31:58.036  1523  4043 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-10 15:31:58.036  1523  4043 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-10 15:31:58.039  4030  4030 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-10 15:31:58.042  1523  4043 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-10 15:31:58.042  1523  4043 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 15:31:58.042  1523  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 15:31:58.042  1523  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 15:31:58.042  1523  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 15:31:58.042  1523  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 15:31:58.042  1523  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 15:31:58.042  1523  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 15:31:58.042  1523  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 15:31:58.042  1523  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 15:31:58.042  1523  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 15:31:58.042  1523  4043 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 15:31:58.042  1523  4043 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 15:31:58.042  1523  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 15:31:58.042  1523  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 15:31:58.042  1523  4043 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-10 15:31:58.042  1523  4043 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-10 15:31:58.042  1523  4043 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-10 15:31:58.042   875   886 I ActivityManager: Start proc 4044:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-10 15:31:58.043  1763  1841 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-10 15:31:58.043  1763  1841 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1763
08-10 15:31:58.043  1763  1841 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-10 15:31:58.043  1763  1841 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-10 15:31:58.043  1763  1841 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-10 15:31:58.043  1763  1841 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-10 15:31:58.043  1763  1841 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-10 15:31:58.043  1763  1841 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-10 15:31:58.043  1763  1841 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-10 15:31:58.043  1763  1841 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-10 15:31:58.043  1763  1841 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 15:31:58.043  1763  1841 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 15:31:58.043  1763  1841 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:31:58.043  1763  1841 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 15:31:58.045   875  1388 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-10 15:31:58.045   875  4050 E DropBoxManagerService: Can't write: system_app_crash
08-10 15:31:58.045   875  4050 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
08-10 15:31:58.045   875  4050 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 15:31:58.045   875  4050 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 15:31:58.045   875  4050 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 15:31:58.045   875  4050 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 15:31:58.045   875  4050 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 15:31:58.045   875  4050 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 15:31:58.045   875  4050 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 15:31:58.045   875  4050 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 15:31:58.045   875  4050 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 15:31:58.045   875  4050 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 15:31:58.045   875  4050 E DropBoxManagerService: 	... 5 more
08-10 15:31:58.046  1523  4043 W SQLiteOpenHelper: Opened config.db in read-only mode
08-10 15:31:58.051  1763  1841 I Process : Sending signal. PID: 1763 SIG: 9
08-10 15:31:58.073  1670  4027 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-10 15:31:58.124  1670  4027 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-10 15:31:58.125  1670  4027 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-10 15:31:58.125  1670  4027 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-10 15:31:58.126  1670  4027 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-10 15:31:58.127  1670  4027 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-10 15:31:58.127  1670  4027 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-10 15:31:58.127  1670  4027 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-10 15:31:58.128  1670  4027 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-10 15:31:58.128  1670  4027 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-10 15:31:58.128  1670  4027 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-10 15:31:58.128  1670  4027 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-10 15:31:58.128  1670  4027 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-10 15:31:58.128  1670  4027 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-10 15:31:58.163   875  1307 W InputDispatcher: channel 'dfc0ea9 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
08-10 15:31:58.163   875  1307 E InputDispatcher: channel 'dfc0ea9 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
08-10 15:31:58.164   875   886 D GraphicsStats: Buffer count: 1
08-10 15:31:58.164   875  2115 I WindowState: WIN DEATH: Window{dfc0ea9 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-10 15:31:58.164   875  2115 W InputDispatcher: Attempted to unregister already unregistered input channel 'dfc0ea9 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
08-10 15:31:58.179  4030  4030 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-10 15:31:58.180   875   886 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1763) has died
08-10 15:31:58.180   875   886 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-10 15:31:58.181   875   886 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-10 15:31:58.194  4030  4061 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-10 15:31:58.194  4030  4061 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 15:31:58.194  4030  4061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 15:31:58.194  4030  4061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 15:31:58.194  4030  4061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 15:31:58.194  4030  4061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 15:31:58.194  4030  4061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 15:31:58.194  4030  4061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 15:31:58.194  4030  4061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 15:31:58.194  4030  4061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 15:31:58.194  4030  4061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 15:31:58.194  4030  4061 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 15:31:58.194  4030  4061 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 15:31:58.194  4030  4061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 15:31:58.194  4030  4061 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 15:31:58.194  4030  4061 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-10 15:31:58.194  4030  4061 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-10 15:31:58.194  4030  4061 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-10 15:31:58.194  4030  4061 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-10 15:31:58.194  4030  4061 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:31:58.194  4030  4061 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:31:58.194  4030  4061 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 15:31:58.195  4030  4061 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-10 15:31:58.195  4030  4061 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 15:31:58.195  4030  4061 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 15:31:58.195  4030  4061 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 15:31:58.195  4030  4061 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 15:31:58.195  4030  4061 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 15:31:58.195  4030  4061 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 15:31:58.195  4030  4061 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 15:31:58.195  4030  4061 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 15:31:58.195  4030  4061 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 15:31:58.195  4030  4061 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 15:31:58.195  4030  4061 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 15:31:58.195  4030  4061 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 15:31:58.195  4030  4061 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 15:31:58.195  4030  4061 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 15:31:58.195  4030  4061 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-10 15:31:58.195  4030  4061 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-10 15:31:58.195  4030  4061 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-10 15:31:58.195  4030  4061 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-10 15:31:58.195  4030  4061 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:31:58.195  4030  4061 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:31:58.195  4030  4061 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 15:31:58.211   875   888 I ActivityManager: Start proc 4065:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-10 15:31:58.227   875  3794 I ActivityManager: Start proc 4078:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-10 15:31:58.232  4030  4076 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-10 15:31:58.245  1980  4064 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-10 15:31:58.246  1980  4064 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-10 15:31:58.260  4078  4078 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 15:31:58.270  4065  4065 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 15:31:58.270  4065  4065 D AndroidRuntime: Shutting down VM
08-10 15:31:58.279  4065  4065 E AndroidRuntime: FATAL EXCEPTION: main
08-10 15:31:58.279  4065  4065 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4065
08-10 15:31:58.279  4065  4065 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-10 15:31:58.279  4065  4065 E AndroidRuntime: 	... 10 more
08-10 15:31:58.280  1523  1523 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-10 15:31:58.281   875  3797 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-10 15:31:58.281  1523  1523 D AndroidRuntime: Shutting down VM
08-10 15:31:58.283   875  4092 E DropBoxManagerService: Can't write: system_app_crash
08-10 15:31:58.283   875  4092 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
08-10 15:31:58.283   875  4092 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 15:31:58.283   875  4092 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 15:31:58.283   875  4092 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 15:31:58.283   875  4092 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 15:31:58.283   875  4092 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 15:31:58.283   875  4092 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 15:31:58.283   875  4092 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 15:31:58.283   875  4092 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 15:31:58.283   875  4092 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 15:31:58.283   875  4092 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 15:31:58.283   875  4092 E DropBoxManagerService: 	... 5 more
08-10 15:31:58.284  4065  4065 I Process : Sending signal. PID: 4065 SIG: 9
08-10 15:31:58.292  1980  4064 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-10 15:31:58.293  1980  4064 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-10 15:31:58.293  1523  1523 E AndroidRuntime: FATAL EXCEPTION: main
08-10 15:31:58.293  1523  1523 E AndroidRuntime: Process: com.google.process.gapps, PID: 1523
08-10 15:31:58.293  1523  1523 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-10 15:31:58.293  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-10 15:31:58.293  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-10 15:31:58.293  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-10 15:31:58.293  1523  1523 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:31:58.293  1523  1523 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:31:58.293  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 15:31:58.293  1523  1523 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 15:31:58.293  1523  1523 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 15:31:58.293  1523  1523 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 15:31:58.293  1523  1523 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-10 15:31:58.293  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-10 15:31:58.293  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-10 15:31:58.293  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-10 15:31:58.293  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-10 15:31:58.293  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-10 15:31:58.293  1523  1523 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-10 15:31:58.293  1523  1523 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-10 15:31:58.293  1523  1523 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-10 15:31:58.293  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-10 15:31:58.293  1523  1523 E AndroidRuntime: 	... 8 more
08-10 15:31:58.306  4030  4061 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:31:58.311  4030  4076 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 15:31:58.312  4030  4076 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-10 15:31:58.312  4030  4076 E AndroidRuntime: Process: android.process.acore, PID: 4030
08-10 15:31:58.312  4030  4076 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 15:31:58.312  4030  4076 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 15:31:58.312  4030  4076 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 15:31:58.312  4030  4076 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 15:31:58.312  4030  4076 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 15:31:58.312  4030  4076 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 15:31:58.312  4030  4076 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 15:31:58.312  4030  4076 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 15:31:58.312  4030  4076 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 15:31:58.312  4030  4076 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 15:31:58.312  4030  4076 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 15:31:58.312  4030  4076 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 15:31:58.312  4030  4076 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 15:31:58.312  4030  4076 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-10 15:31:58.312  4030  4076 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-10 15:31:58.312  4030  4076 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-10 15:31:58.312  4030  4076 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-10 15:31:58.312  4030  4076 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-10 15:31:58.312  4030  4076 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-10 15:31:58.312  4030  4076 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-10 15:31:58.312  4030  4076 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-10 15:31:58.312  4030  4076 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:31:58.312  4030  4076 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 15:31:58.312  4030  4076 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 15:31:58.313  4030  4061 I Process : Sending signal. PID: 4030 SIG: 9
08-10 15:31:58.328   875  2230 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4065) has died
08-10 15:31:58.329   875  2230 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-10 15:31:58.335  1523  1523 I Process : Sending signal. PID: 1523 SIG: 9
08-10 15:31:58.338   875  4094 E DropBoxManagerService: Can't write: system_app_crash
08-10 15:31:58.338   875  4094 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
08-10 15:31:58.338   875  4094 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 15:31:58.338   875  4094 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 15:31:58.338   875  4094 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 15:31:58.338   875  4094 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 15:31:58.338   875  4094 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 15:31:58.338   875  4094 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 15:31:58.338   875  4094 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 15:31:58.338   875  4094 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 15:31:58.338   875  4094 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 15:31:58.338   875  4094 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 15:31:58.338   875  4094 E DropBoxManagerService: 	... 5 more
08-10 15:31:58.346   875   888 I ActivityManager: Start proc 4095:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-10 15:31:58.355   280   339 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
