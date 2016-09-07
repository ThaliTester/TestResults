#### Test 82912030fa224b6_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-07 14:58:12.017  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:58:12.023  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-07 14:58:12.026  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-07 14:58:12.054  1500  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-07 14:58:12.055  1500  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 14:58:12.055  1500  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:58:12.055  1500  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-07 14:58:12.074  2722  2722 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-07 14:58:12.074  2722  2722 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 14:58:12.075  2722  2722 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
09-07 14:58:12.646  3455  3455 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-07 14:58:12.652  3455  3455 D AndroidRuntime: CheckJNI is OFF
09-07 14:58:12.695  3455  3455 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-07 14:58:12.745  3455  3455 I Radio-JNI: register_android_hardware_Radio DONE
09-07 14:58:12.766  3455  3455 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-07 14:58:12.770   874  1971 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-07 14:58:12.810  2053  2064 W SearchService: Abort, client detached.
09-07 14:58:12.818  3455  3455 D AndroidRuntime: Shutting down VM
09-07 14:58:12.825   874  1991 I ActivityManager: Start proc 3465:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-07 14:58:12.825  2053  2319 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@8427db1
09-07 14:58:12.826  2053  2333 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-07 14:58:12.826  2053  2053 I HotwordDetector: Closing mic
09-07 14:58:12.844  2053  2053 W ErrorReporter: reportError [type: 29, code: 917507]: null
09-07 14:58:12.890   377  2335 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-07 14:58:12.891   377  2335 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-07 14:58:12.896   377  1274 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-07 14:58:12.898  2053  2328 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-07 14:58:12.899  2053  2332 I MicroRecognitionRnrImpl: Detection finished
09-07 14:58:12.911  3465  3465 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-07 14:58:12.945  3465  3465 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-07 14:58:12.956  3465  3465 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 9754-9759)
09-07 14:58:12.957  3465  3465 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 14:58:12.981  3465  3465 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {15cba7d}
09-07 14:58:12.982  3465  3465 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 14:58:12.984  3465  3465 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-07 14:58:12.992  3465  3465 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-07 14:58:12.993  3465  3465 E SysUtils: ApplicationContext is null in ApplicationStatus
09-07 14:58:13.017  3465  3482 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
09-07 14:58:13.026  3465  3465 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-07 14:58:13.037  3465  3465 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 14:58:13.037  3465  3465 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 14:58:13.037  3465  3465 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 14:58:13.037  3465  3465 I Adreno  : Build Date                       : 10/20/15
09-07 14:58:13.037  3465  3465 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 14:58:13.037  3465  3465 I Adreno  : Local Branch                     : M14
09-07 14:58:13.037  3465  3465 I Adreno  : Remote Branch                    : 
09-07 14:58:13.037  3465  3465 I Adreno  : Remote Branch                    : 
09-07 14:58:13.037  3465  3465 I Adreno  : Reconstruct Branch               : 
,09-07 14:58:13.102   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c637e5c:true
,09-07 14:58:13.129  3465  3465 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-07 14:58:13.140  3465  3465 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-07 14:58:13.212  3465  3504 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-07 14:58:13.220  3465  3491 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-07 14:58:13.261  3465  3504 I OpenGLRenderer: Initialized EGL, version 1.4
,09-07 14:58:13.335   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +524ms
,09-07 14:58:13.344  1891  1891 I Keyboard.Facilitator: onFinishInput()
,09-07 14:58:13.410  3465  3465 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3465
,09-07 14:58:13.525  3465  3465 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-07 14:58:13.649   874  2020 I ActivityManager: Killing 2842:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,09-07 14:58:13.685  3465  3508 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1718613712
,09-07 14:58:13.690  3465  3508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 14:58:13.690  3465  3508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 14:58:13.690  3465  3508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 14:58:13.690  3465  3508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 14:58:13.690  3465  3508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-07 14:58:13.690  3465  3508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61f2c71 added. We now have 1 listener(s)
,09-07 14:58:13.691   874  2020 I ActivityManager: Killing 3166:com.qualcomm.telephony/1001 (adj 15): empty #18
,09-07 14:58:13.693  3465  3508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-07 14:58:13.693  3465  3508 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 14:58:13.694  3465  3508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 14:58:13.694  3465  3508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 14:58:13.698  3465  3508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 14:58:13.698  3465  3508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 14:58:13.698  3465  3508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 14:58:13.698  3465  3508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-07 14:58:13.698  3465  3508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 14:58:13.698  3465  3508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 14:58:13.698  3465  3508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 14:58:13.698  3465  3508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 14:58:13.698  3465  3508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 14:58:13.698  3465  3508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 14:58:13.698  3465  3508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 14:58:13.698  3465  3508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 14:58:13.698  3465  3508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 14:58:13.698  3465  3508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-07 14:58:13.698  3465  3508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2de8fc4 added. We now have 1 listener(s)
,09-07 14:58:13.699  3465  3508 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 14:58:13.703   874  1304 D WifiService: New client listening to asynchronous messages
,09-07 14:58:13.704  3465  3508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 14:58:13.704  3465  3508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-07 14:58:13.705  3465  3508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-07 14:58:13.705  3465  3508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-07 14:58:13.705  3465  3508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-07 14:58:13.755  3465  3508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 14:58:13.755  3465  3508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-07 14:58:13.758  3465  3508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 14:58:13.758  3465  3508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 14:58:13.758  3465  3508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:13.758  3465  3508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 14:58:13.758  3465  3508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 14:58:13.758  3465  3508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:58:13.758  3465  3508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:58:13.758  3465  3508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:58:13.758  3465  3508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 14:58:13.758  3465  3508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-07 14:58:13.758  3465  3508 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 14:58:13.759  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:58:13.759  3465  3508 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-07 14:58:13.782  3465  3465 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-07 14:58:14.658  3465  3516 W jxcore-log: Initializing JXcore engine
09-07 14:58:14.658  3465  3516 W jxcore-log: JXcore engine is ready
,09-07 14:58:14.694  3516  3516 W Thread-286: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8938 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-07 14:58:14.694  3516  3516 W Thread-286: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10557]" dev="sockfs" ino=10557 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-07 14:58:14.694  3516  3516 W Thread-286: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-07 14:58:14.694  3516  3516 W Thread-286: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24016]" dev="sockfs" ino=24016 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-07 14:58:14.712  3465  3516 W jxcore-log: Starting JXcore engine
,09-07 14:58:14.795  3465  3516 W jxcore-log: Platform android
09-07 14:58:14.795  3465  3516 W jxcore-log: 
09-07 14:58:14.795  3465  3516 W jxcore-log: Process ARCH arm
09-07 14:58:14.795  3465  3516 W jxcore-log: 
,09-07 14:58:15.149  3465  3516 I jxcore-log: JXcore Cordova bridge is ready!
09-07 14:58:15.149  3465  3516 I jxcore-log: 
,09-07 14:58:15.150  3465  3516 W jxcore-log: JXcore engine is started
,09-07 14:58:15.158  3465  3508 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-07 14:58:15.161  3465  3465 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-07 14:58:29.045  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 14:58:29.045  3465  3516 I jxcore-log: 
,09-07 14:58:29.048  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 14:58:29.048  3465  3516 I jxcore-log: 
,09-07 14:58:29.050  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 14:58:29.050  3465  3516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 14:58:29.050  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:29.050  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 14:58:29.050  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 14:58:29.050  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:58:29.050  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:58:29.050  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:58:29.050  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 14:58:29.051  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 14:58:29.051  3465  3516 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 14:58:29.053  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 14:58:29.053  3465  3516 I jxcore-log: 
,09-07 14:58:29.055  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 14:58:29.055  3465  3516 I jxcore-log: 
,09-07 14:58:29.405  3465  3516 I jxcore-log: Running unit tests
09-07 14:58:29.405  3465  3516 I jxcore-log: 
,09-07 14:58:29.406  3465  3516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 14:58:29.406  3465  3516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73be262 added. We now have 2 listener(s)
,09-07 14:58:29.407  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 14:58:29.407  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 14:58:29.408  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 14:58:29.408  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 14:58:29.408  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d456ff3 added. We now have 2 listener(s)
,09-07 14:58:29.408  3465  3516 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 14:58:29.408  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 14:58:29.411  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 14:58:29.411  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:29.411  3465  3516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 14:58:29.411  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:29.411  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 14:58:29.411  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 14:58:29.411  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:58:29.411  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:58:29.411  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:58:29.411  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 14:58:29.411  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:29.412  3465  3516 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 14:58:29.414  3465  3516 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 14:58:29.415  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 14:58:29.415  3465  3516 D executeNativeTests: Running unit tests
,09-07 14:58:29.505  3465  3516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 14:58:29.505  3465  3516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b3499 added. We now have 3 listener(s)
09-07 14:58:29.507  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 14:58:29.507  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 14:58:29.507  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 14:58:29.507  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 14:58:29.507  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e added. We now have 3 listener(s)
09-07 14:58:29.507  3465  3516 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 14:58:29.507  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 14:58:29.509  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 14:58:29.510  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:29.510  3465  3516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 14:58:29.510  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:29.510  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 14:58:29.510  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 14:58:29.510  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:58:29.510  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:58:29.510  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:58:29.510  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 14:58:29.510  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:29.510  3465  3516 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 14:58:29.510  3465  3516 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 14:58:29.511  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:58:29.512  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 14:58:29.512  3465  3516 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 14:58:29.512  3465  3516 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 14:58:29.512  3465  3516 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 14:58:29.513  3465  3516 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-07 14:58:29.514  3465  3516 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 14:58:29.514  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 14:58:29.514  3465  3516 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 14:58:29.514  3465  3516 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 14:58:29.514  3465  3516 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 14:58:29.515  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 14:58:29.515  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 14:58:29.515  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 14:58:29.515  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 14:58:29.516  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 14:58:29.516  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 14:58:29.516  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 14:58:29.516  3465  3516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b3499 removed from the list
,09-07 14:58:29.516  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:29.516  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e removed from the list
,09-07 14:58:29.516  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 14:58:29.516  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:58:29.517  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 14:58:29.517  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:58:29.518  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 14:58:29.518  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 14:58:29.518  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 14:58:29.518  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
,09-07 14:58:29.520  3465  3516 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-07 14:58:29.520  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 14:58:29.520  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 14:58:29.520  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 14:58:29.520  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 14:58:29.520  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:29.520  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:58:29.520  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b3499 not in the list
09-07 14:58:29.520  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:29.520  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:29.521  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
09-07 14:58:29.521  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:29.521  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:29.521  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:29.521  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:29.521  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 14:58:29.521  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 14:58:29.521  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:29.521  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:29.525  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-07 14:58:29.525  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 14:58:29.525  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 14:58:29.525  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 14:58:29.526  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 14:58:29.526  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 14:58:29.526  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 14:58:29.526  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 14:58:29.526  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 14:58:29.526  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 14:58:29.526  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 14:58:29.526  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 14:58:29.526  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 14:58:29.526  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 14:58:29.526  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 14:58:29.526  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 14:58:29.526  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-07 14:58:29.526  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 14:58:29.526  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 14:58:29.526  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 14:58:29.526  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 14:58:29.526  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 14:58:29.526  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 14:58:29.526  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 14:58:29.527  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 14:58:29.527  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 14:58:29.527  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 14:58:29.527  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 14:58:29.527  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 14:58:29.527  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 14:58:29.527  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 14:58:29.527  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 14:58:29.527  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 14:58:29.527  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 14:58:29.527  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 14:58:29.528  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:29.528  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:29.528  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b3499 not in the list
09-07 14:58:29.528  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:29.528  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:29.528  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
09-07 14:58:29.528  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:29.528  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:29.528  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:29.528  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:29.529  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 14:58:29.529  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 14:58:29.529  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:29.529  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:29.530  3465  3516 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 14:58:29.531  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 14:58:29.532  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:29.532  3465  3516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 14:58:29.532  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:29.532  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 14:58:29.532  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 14:58:29.532  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:58:29.532  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:58:29.532  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:58:29.532  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 14:58:29.532  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:29.532  3465  3516 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 14:58:29.532  3465  3516 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 14:58:29.532  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 14:58:29.532  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 14:58:29.533  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 14:58:29.533  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 14:58:29.533  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:58:29.533  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 14:58:29.535  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
09-07 14:58:29.536  3465  3516 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-07 14:58:29.536  3465  3465 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-07 14:58:29.536  3465  3516 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 14:58:29.537  3465  3516 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 14:58:30.038  3465  3465 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 14:58:32.349  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:58:32.367  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:58:32.374  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:58:32.435  1500  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 14:58:32.435  1500  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-07 14:58:32.435  1500  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:58:32.435  1500  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:58:32.477  2722  2722 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 14:58:32.478  2722  2722 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-07 14:58:32.478  2722  2722 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-07 14:58:34.540  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 14:58:34.542  3465  3516 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
,09-07 14:58:34.546  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 14:58:34.547  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
,09-07 14:58:34.547  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 14:58:34.547  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:34.548  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-07 14:58:34.548  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-07 14:58:34.548  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 14:58:34.549  3465  3516 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-07 14:58:34.549  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 14:58:34.552  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 14:58:34.554  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 14:58:34.556  3465  3516 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 14:58:34.556  3465  3465 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 14:58:34.556  3465  3465 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 14:58:34.556  3465  3465 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 14:58:34.557  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 14:58:34.557  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:34.557  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 14:58:34.557  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b3499 not in the list
09-07 14:58:34.557  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 14:58:34.557  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:34.557  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
09-07 14:58:34.557  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:34.558  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:34.558  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:58:34.558  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 14:58:34.558  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 14:58:34.558  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:34.559  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:34.560  3465  3516 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 14:58:34.562  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 14:58:34.563  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 14:58:34.563  3465  3516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 14:58:34.563  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:34.563  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 14:58:34.563  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 14:58:34.563  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:58:34.563  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:58:34.563  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:58:34.563  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 14:58:34.563  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:34.563  3465  3516 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 14:58:34.563  3465  3516 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 14:58:34.564  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 14:58:34.564  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-07 14:58:34.564  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 14:58:34.564  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 14:58:34.564  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 14:58:34.564  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:58:34.566  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
09-07 14:58:34.566  3465  3516 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-07 14:58:34.567  3465  3516 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 14:58:34.567  3465  3465 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-07 14:58:34.567  3465  3516 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 14:58:35.067  3465  3465 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 14:58:39.568  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 14:58:39.569  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 14:58:39.569  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 14:58:39.569  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:39.570  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-07 14:58:39.570  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 14:58:39.571  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 14:58:39.571  3465  3516 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-07 14:58:39.571  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 14:58:39.572  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 14:58:39.575  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 14:58:39.577  3465  3516 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 14:58:39.578  3465  3465 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 14:58:39.579  3465  3465 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 14:58:39.579  3465  3465 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 14:58:40.081  3465  3465 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 14:58:40.081  3465  3465 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 14:58:40.082  3465  3465 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 14:58:43.474   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...,
,09-07 14:58:43.486  1891  1891 I Keyboard.Facilitator: onFinishInput()
,09-07 14:58:43.500   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437,
09-07 14:58:43.500   874   894 I Adreno  : Build Date                       : 10/20/15
09-07 14:58:43.500   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
,09-07 14:58:43.500   874   894 I Adreno  : Local Branch                     : M14
09-07 14:58:43.500   874   894 I Adreno  : Remote Branch                    : 
09-07 14:58:43.500   874   894 I Adreno  : Remote Branch                    : 
,09-07 14:58:43.500   874   894 I Adreno  : Reconstruct Branch               : 
,09-07 14:58:43.537   281   303 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (666 us)
,09-07 14:58:44.210  3465  3465 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-07 14:58:44.210  3465  3465 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-07 14:58:44.244   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-07 14:58:44.248  3465  3465 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a02a3b Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@33004f8, 16908290=android.view.AbsSavedState$1@33004f8}, android:focusedViewId=100}]}]
,09-07 14:58:44.248  3465  3465 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-07 14:58:44.249  3465  3465 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-07 14:58:44.249  3465  3465 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-07 14:58:44.269   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-07 14:58:44.273   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-07 14:58:44.275   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,09-07 14:58:44.275   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-07 14:58:44.536   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-07 14:58:44.540   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
09-07 14:58:44.546   874  1329 D SurfaceControl: Excessive delay in setPowerMode(): 273ms
,09-07 14:58:44.551   874   894 I DreamManagerService: Entering dreamland.
09-07 14:58:44.555   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
09-07 14:58:44.558   874   894 I PowerManagerService: Dozing...
,09-07 14:58:44.579  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 14:58:44.580  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 14:58:44.580  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 14:58:44.580  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 14:58:44.581  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:44.581  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 14:58:44.581  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b3499 not in the list
09-07 14:58:44.581  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:44.581  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:44.582  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
09-07 14:58:44.582  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:58:44.583  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 14:58:44.584  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.584  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 14:58:44.585  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 14:58:44.585  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:44.585  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
,09-07 14:58:44.587  3465  3516 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-07 14:58:44.588  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 14:58:44.589  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 14:58:44.589  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 14:58:44.589  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 14:58:44.589  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:44.590  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:58:44.590  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b3499 not in the list
,09-07 14:58:44.590  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:44.590  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
,09-07 14:58:44.591  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
09-07 14:58:44.591  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 14:58:44.591  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:58:44.591  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:44.591  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.592  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 14:58:44.592  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 14:58:44.592  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 14:58:44.592  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
,09-07 14:58:44.593  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 14:58:44.593  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 14:58:44.593  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 14:58:44.593  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 14:58:44.593  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 14:58:44.593  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 14:58:44.593  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.593  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b3499 not in the list
09-07 14:58:44.593  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:44.593  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:44.593  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
09-07 14:58:44.593  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 14:58:44.593  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.593  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:44.594  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.594  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 14:58:44.594  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 14:58:44.594  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 14:58:44.594  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:44.595  3465  3516 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-07 14:58:44.595  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 14:58:44.595  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 14:58:44.595  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 14:58:44.595  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 14:58:44.595  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:44.595  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:58:44.595  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b3499 not in the list
09-07 14:58:44.595  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:44.596  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:44.596  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 14:58:44.596  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:44.596  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.596  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:44.596  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.596  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 14:58:44.596  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 14:58:44.596  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:44.596  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
,09-07 14:58:44.597  3465  3516 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-07 14:58:44.597  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 14:58:44.597  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 14:58:44.597  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 14:58:44.597  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 14:58:44.597  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:44.597  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.597  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b3499 not in the list
,09-07 14:58:44.598  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:44.598  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:44.598  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 14:58:44.598  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:44.598  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:58:44.598  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:44.598  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.598  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 14:58:44.598  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 14:58:44.598  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:44.599  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:44.599  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 14:58:44.599  3465  3516 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
09-07 14:58:44.599  3465  3516 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 14:58:44.599  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 14:58:44.599  3465  3516 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 14:58:44.600  3465  3516 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 14:58:44.600  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 14:58:44.600  3465  3516 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 14:58:44.600  3465  3516 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 14:58:44.600  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 14:58:44.600  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 14:58:44.600  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 14:58:44.600  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 14:58:44.600  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:44.600  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.600  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b3499 not in the list
09-07 14:58:44.601  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 14:58:44.601  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:44.601  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
09-07 14:58:44.601  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:44.601  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.601  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 14:58:44.601  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.601  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 14:58:44.601  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 14:58:44.601  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-07 14:58:44.602  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:44.602  3465  3516 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 14:58:44.602  3465  3516 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 14:58:44.602  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-07 14:58:44.607  3465  3516 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 14:58:44.607  3465  3516 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-07 14:58:44.608  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 14:58:44.608  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 14:58:44.608  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 14:58:44.608  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 14:58:44.608  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-07 14:58:44.608  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 14:58:44.608  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 14:58:44.608  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 14:58:44.608  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 14:58:44.608  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 14:58:44.609  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 14:58:44.609  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 14:58:44.609  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 14:58:44.609  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-07 14:58:44.609  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 14:58:44.609  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 14:58:44.609  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 14:58:44.609  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710],
,09-07 14:58:44.609  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 14:58:44.609  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 14:58:44.609  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 14:58:44.609  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 14:58:44.609  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 14:58:44.610  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-07 14:58:44.610  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 14:58:44.610  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 14:58:44.610  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 14:58:44.610  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 14:58:44.610  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 14:58:44.610  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 14:58:44.610  3465  3516 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,09-07 14:58:44.610  3465  3516 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 14:58:44.611  3465  3516 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 14:58:44.611  3465  3516 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 14:58:44.611  3465  3516 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 14:58:44.611  3465  3516 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 14:58:44.611  3465  3516 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-07 14:58:44.611  3465  3516 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 14:58:44.614  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-07 14:58:44.617  3465  3516 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
09-07 14:58:44.617  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-07 14:58:44.618  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-07 14:58:44.618  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-07 14:58:44.618  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,09-07 14:58:44.618  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 14:58:44.618  3465  3516 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-07 14:58:44.619  3465  3516 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 14:58:44.619  3465  3516 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 14:58:44.619  3465  3527 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 350)
09-07 14:58:44.619  3465  3527 E BluetoothDevice: Bluetooth is not enabled
09-07 14:58:44.619  3465  3527 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): null (thread ID: 350)
09-07 14:58:44.619  3465  3527 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 350)
09-07 14:58:44.619  3465  3527 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): null (thread ID: 350)
09-07 14:58:44.620  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 14:58:44.620  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 14:58:44.620  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 14:58:44.620  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 14:58:44.620  3465  3465 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> 00:11:22:33:44:55]: Failed to connect (tried 1 time(s)): null
09-07 14:58:44.620  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:44.620  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.621  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-07 14:58:44.621  3465  3465 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: Failed to connect (tried 1 time(s)): null
09-07 14:58:44.621  3465  3465 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 14:58:44.621  3465  3465 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 14:58:44.621  3465  3465 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 14:58:44.622  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b3499 not in the list
09-07 14:58:44.622  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:44.623  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:44.623  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
09-07 14:58:44.623  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:44.623  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.623  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:44.623  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.623  3465  3528 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 350
09-07 14:58:44.623  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 14:58:44.623  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 14:58:44.623  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:44.624  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:44.625  3465  3516 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-07 14:58:44.627  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 14:58:44.627  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 14:58:44.627  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 14:58:44.627  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 14:58:44.627  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:44.628  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.628  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b3499 not in the list
09-07 14:58:44.628  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:44.628  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
,09-07 14:58:44.628  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
09-07 14:58:44.628  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:44.628  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.628  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 14:58:44.628  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.628  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 14:58:44.629  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-07 14:58:44.629  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:44.629  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:44.630   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-07 14:58:44.630   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
09-07 14:58:44.632  3465  3527 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Failed to find a thread with ID 350
09-07 14:58:44.632  3465  3527 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 350)
,09-07 14:58:44.632  3465  3516 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-07 14:58:44.632  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 14:58:44.632  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 14:58:44.632  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 14:58:44.632  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 14:58:44.632  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-07 14:58:44.632  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.633  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b3499 not in the list
09-07 14:58:44.633  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:44.633  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:44.633  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
09-07 14:58:44.633  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 14:58:44.633  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.633  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:44.633  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.633  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 14:58:44.633  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 14:58:44.633  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:44.633  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list,
09-07 14:58:44.634  3465  3516 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 14:58:44.634  3465  3516 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-07 14:58:44.634  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 14:58:44.634  3465  3516 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 14:58:44.634  3465  3516 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 14:58:44.634  3465  3516 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 14:58:44.634  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-07 14:58:44.634  3465  3516 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 14:58:44.634  3465  3516 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 14:58:44.634  3465  3516 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 14:58:44.634  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 14:58:44.634  3465  3516 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-07 14:58:44.634  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 14:58:44.635  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 14:58:44.635  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 14:58:44.635  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 14:58:44.635  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:44.635  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.635  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b3499 not in the list
,09-07 14:58:44.635  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:44.635  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:44.635  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
09-07 14:58:44.635  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:44.635  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.635  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 14:58:44.635  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.636  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 14:58:44.636  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 14:58:44.636  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:44.636  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:44.637  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 14:58:44.637  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 14:58:44.637  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.637  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b3499 not in the list
09-07 14:58:44.637  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:44.637  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:44.637  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
09-07 14:58:44.637  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 14:58:44.637  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:44.641   874  1303 D WifiConfigStore: Retrieve network priorities after PNO.
09-07 14:58:44.643  1934  3529 D NfcService: Discovery configuration equal, not updating.
09-07 14:58:44.643   874  1303 E native  : do suspend false
,09-07 14:58:44.674   874  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 14:58:44.676   874  1303 E native  : do suspend true
,09-07 14:58:44.764   377  3478 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-07 14:58:44.764   377  3478 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-07 14:58:49.502  1858  2498 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient,
,09-07 14:58:49.638  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 14:58:49.638  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
,09-07 14:58:49.639  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 14:58:49.639  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:49.639  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:49.640  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b3499 not in the list
09-07 14:58:49.640  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 14:58:49.641  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 14:58:49.641  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 14:58:49.641  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 14:58:49.642  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:49.642  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:49.642  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b3499 not in the list
09-07 14:58:49.643  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:49.643  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:49.643  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
09-07 14:58:49.643  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:49.644  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:49.644  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:49.644  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:49.646  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 14:58:49.646  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 14:58:49.646  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:49.647  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:49.652  3465  3516 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-07 14:58:49.653  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 14:58:49.653  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
09-07 14:58:49.654  3465  3516 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
09-07 14:58:49.655  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-07 14:58:49.655  3465  3465 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
09-07 14:58:49.656  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 14:58:49.656  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-07 14:58:49.656  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:49.657  3465  3516 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
09-07 14:58:49.657  3465  3465 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-07 14:58:49.657  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b3499 not in the list
09-07 14:58:49.658  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:49.658  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-07 14:58:49.658  3465  3516 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 14:58:49.658  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 14:58:49.659  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 14:58:49.659  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:49.660  3465  3516 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 14:58:49.661  3465  3465 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 14:58:49.661  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:49.661  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 14:58:49.661  3465  3465 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 14:58:49.661  3465  3465 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 14:58:49.661  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 14:58:49.662  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 14:58:49.662  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 14:58:49.662  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:49.662  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:58:49.663  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b3499 not in the list
09-07 14:58:49.663  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:49.663  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:49.663  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 14:58:49.664  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:49.664  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:49.664  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 14:58:49.664  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:49.665  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 14:58:49.665  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 14:58:49.666  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:49.666  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:49.668  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 14:58:49.673  3465  3516 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 14:58:49.674  3465  3516 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 14:58:49.674  3465  3516 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-07 14:58:49.675  3465  3516 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-07 14:58:49.676  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 14:58:49.676  3465  3516 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 14:58:49.677  3465  3516 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 14:58:49.677  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 14:58:49.678  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 14:58:49.678  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 14:58:49.679  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 14:58:49.680  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 14:58:49.682  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:49.682  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b3499 not in the list
09-07 14:58:49.682  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:49.683  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:49.683  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 14:58:49.683  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:49.683  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:49.683  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:49.683  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:49.684  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 14:58:49.684  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 14:58:49.684  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:49.684  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:49.686  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 14:58:49.686  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 14:58:49.687  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 14:58:49.687  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 14:58:49.687  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:49.687  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:49.687  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b3499 not in the list
09-07 14:58:49.687  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-07 14:58:49.687  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:49.687  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
09-07 14:58:49.687  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:49.687  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-07 14:58:49.687  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:49.688  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:49.688  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 14:58:49.688  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 14:58:49.688  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 14:58:49.688  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
,09-07 14:58:49.689  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 14:58:49.689  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 14:58:49.689  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 14:58:49.689  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 14:58:49.690  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:49.690  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:49.690  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25b3499 not in the list
,09-07 14:58:49.690  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:49.690  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:49.690  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 14:58:49.690  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:49.690  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-07 14:58:49.690  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 14:58:49.690  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:58:49.691  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 14:58:49.691  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 14:58:49.691  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 14:58:49.691  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@232335e not in the list
09-07 14:58:49.692  3465  3516 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing,
09-07 14:58:49.692  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-07 14:58:49.692  3465  3516 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-07 14:58:49.693  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-07 14:58:49.693  3465  3516 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-07 14:58:49.693  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-07 14:58:49.695  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 14:58:49.695  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing],
09-07 14:58:49.696  3465  3516 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-07 14:58:49.696  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 14:58:49.696  3465  3516 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-07 14:58:49.697  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-07 14:58:49.697  3465  3516 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-07 14:58:49.697  3465  3516 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left,
09-07 14:58:49.698  3465  3516 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-07 14:58:49.698  3465  3516 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-07 14:58:49.698  3465  3516 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-07 14:58:49.698  3465  3516 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-07 14:58:49.699  3465  3516 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-07 14:58:49.699  3465  3516 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-07 14:58:49.700  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 14:58:49.700  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cc5ddd1 added. We now have 3 listener(s)
,09-07 14:58:49.700  3465  3516 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 14:58:49.704   874  1991 D WifiService: setWifiEnabled: true pid=3465, uid=10000
,09-07 14:58:49.704   874  1991 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 14:58:49.724   874   891 I ActivityManager: Start proc 3538:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-07 14:58:49.725   874  1303 D WifiConfigStore: Loading config and enabling all networks 
,09-07 14:58:49.728  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:49.728  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:58:49.728  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:49.728  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 14:58:49.728  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:58:49.728  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:58:49.728  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:58:49.728  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:58:49.728  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 14:58:49.728  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:49.728  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 14:58:49.729  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:49.729  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:58:49.729  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:49.729  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 14:58:49.729  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:58:49.729  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:58:49.729  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:58:49.729  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:58:49.729  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 14:58:49.729  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:49.729  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 14:58:49.742   874  1303 D WifiConfigStore: loaded 0 passpoint configs
,09-07 14:58:49.743   874  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-07 14:58:49.745   874  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-07 14:58:49.746   874  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-07 14:58:49.746   874  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-07 14:58:49.746   874  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-07 14:58:49.747   874  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-07 14:58:49.751   874   887 I ActivityManager: Start proc 3550:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-07 14:58:49.780  3550  3550 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-07 14:58:49.813   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-07 14:58:49.814   874  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 14:58:49.814   373   872 D CommandListener: Setting iface cfg
,09-07 14:58:49.815   874  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '109 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 109 Failed to set address (No such device)'
,09-07 14:58:49.815   874  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-07 14:58:49.823   874  1302 D WifiNative-HAL: p2pGetDeviceAddress
,09-07 14:58:49.823  3538  3538 D AdapterServiceConfig: Adding HeadsetService
,09-07 14:58:49.823  3538  3538 D AdapterServiceConfig: Adding A2dpService
,09-07 14:58:49.823   874  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-07 14:58:49.823  3538  3538 D AdapterServiceConfig: Adding HidService
09-07 14:58:49.823  3538  3538 D AdapterServiceConfig: Adding HealthService
,09-07 14:58:49.824  3538  3538 D AdapterServiceConfig: Adding PanService
09-07 14:58:49.824  3538  3538 D AdapterServiceConfig: Adding GattService
,09-07 14:58:49.824  3538  3538 D AdapterServiceConfig: Adding BluetoothMapService
09-07 14:58:49.824   874  1303 E native  : do suspend true
,09-07 14:58:49.828  3550  3550 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-07 14:58:49.845   874  2019 I ActivityManager: Killing 2806:com.google.android.calendar/u0a37 (adj 15): empty #17,
,09-07 14:58:49.856   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b92089b:true
,09-07 14:58:49.856  3538  3538 D BluetoothAdapterState: make() - Creating AdapterState
,09-07 14:58:49.859  3538  3538 I bt_bluedroid: init
,09-07 14:58:49.859  3538  3575 I BluetoothAdapterState: Entering OffState
,09-07 14:58:49.861  3538  3576 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-07 14:58:49.862  3538  3576 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-07 14:58:49.862  3538  3576 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 14:58:49.863  3538  3576 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-07 14:58:49.864  3538  3538 I bt_bluedroid: get_profile_interface socket
,09-07 14:58:49.865  3538  3538 I bt_bluedroid: get_profile_interface sdp
,09-07 14:58:49.866  3538  3579 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 14:58:49.876  3538  3579 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 14:58:49.879   874  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 14:58:49.882  3538  3549 I bt_bluedroid: config_hci_snoop_log
,09-07 14:58:49.882  1457  1457 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
09-07 14:58:49.883  1457  1457 W wpa_supplicant: wlan0: Failed to initiate AP scan
,09-07 14:58:49.883   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,09-07 14:58:49.885  3538  3575 D BluetoothAdapterState: Current state: OFF, message: 0
,09-07 14:58:49.886  3538  3575 D BluetoothAdapterProperties: Setting state to 14
09-07 14:58:49.886  3538  3575 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-07 14:58:49.888  3538  3575 D BluetoothBondStateMachine: make
,09-07 14:58:49.890  3538  3580 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-07 14:58:49.893  3538  3575 I BluetoothAdapterState: Entering PendingCommandState
09-07 14:58:49.893  3538  3538 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-07 14:58:49.895  3538  3538 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
,09-07 14:58:49.896  3538  3538 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 14:58:49.896  3538  3538 D BtGatt.GattService: Received start request. Starting profile...
09-07 14:58:49.896  3538  3538 D BtGatt.GattService: start()
09-07 14:58:49.896  3538  3538 I bt_bluedroid: get_profile_interface gatt
09-07 14:58:49.897  3538  3538 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
09-07 14:58:49.897  3538  3538 D BtGatt.AdvertiseManager: advertise manager created
,09-07 14:58:49.901  3538  3538 V BluetoothAdapterState: isTurningOff()=false
09-07 14:58:49.901  3538  3538 V BluetoothAdapterState: isTurningOn()=false
,09-07 14:58:49.901  3538  3538 V BluetoothAdapterState: isBleTurningOn()=true
09-07 14:58:49.901  3538  3538 V BluetoothAdapterState: isBleTurningOff()=false
09-07 14:58:49.901  3538  3575 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-07 14:58:49.902  3538  3575 I bt_bluedroid: enable
,09-07 14:58:49.902  3538  3576 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-07 14:58:49.902  3538  3576 I bt_hci  : start_up
,09-07 14:58:49.911  3538  3576 I bt_vendor: alloc value 0xb3a3d189
,09-07 14:58:49.911  3538  3576 I bt_vendor: init
09-07 14:58:49.911  3538  3576 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-07 14:58:49.911  3538  3576 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-07 14:58:50.017  3538  3576 D bt_hci  : start_up starting async portion
,09-07 14:58:50.018  3538  3583 I bt_hci  : event_finish_startup
,09-07 14:58:50.019  3538  3583 I bt_hci_h4: hal_open
09-07 14:58:50.019  3538  3583 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-07 14:58:50.024  3538  3583 I bt_userial_vendor: device fd = 51 open
,09-07 14:58:50.061  3538  3583 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 14:58:50.093  3538  3583 D bt_hwcfg: Chipset BCM4354A2
,09-07 14:58:50.093  3538  3583 D bt_hwcfg: Target name = [BCM4354A2]
,09-07 14:58:50.094  3538  3583 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-07 14:58:50.162  3465  3465 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 14:58:50.767  3538  3583 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-07 14:58:50.769  3538  3583 D bt_hwcfg: Settlement delay -- 100 ms
09-07 14:58:50.769  3538  3583 I bt_hwcfg: Setting fw settlement delay to 100 
,09-07 14:58:50.884  1457  1457 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,09-07 14:58:50.885  1457  1457 W wpa_supplicant: wlan0: Failed to initiate AP scan
,09-07 14:58:50.886  3538  3583 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-07 14:58:50.888  3538  3583 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-07 14:58:50.916  3538  3583 I bt_hwcfg: vendor lib fwcfg completed
09-07 14:58:50.917  3538  3583 I bt_vendor: firmware callback
09-07 14:58:50.917  3538  3583 I bt_hci  : firmware_config_callback
,09-07 14:58:50.928  3538  3585 I bt_btu  : btu_task pending for preload complete event
,09-07 14:58:50.928  3538  3585 I bt_btu_task: Bluetooth chip preload is complete
,09-07 14:58:50.929  3538  3585 I bt_btu  : btu_task received preload complete event
,09-07 14:58:50.940  3538  3585 I         : BTE_InitTraceLevels -- TRC_HCI
,09-07 14:58:50.940  3538  3585 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-07 14:58:50.941  3538  3585 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-07 14:58:50.941  3538  3585 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-07 14:58:50.942  3538  3585 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 14:58:50.942  3538  3585 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 14:58:50.942  3538  3585 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-07 14:58:50.942  3538  3585 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 14:58:50.943  3538  3585 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 14:58:50.943  3538  3585 I         : BTE_InitTraceLevels -- TRC_PAN
,09-07 14:58:50.943  3538  3585 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 14:58:50.943  3538  3585 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 14:58:50.944  3538  3585 I         : BTE_InitTraceLevels -- TRC_SMP
,09-07 14:58:50.944  3538  3585 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 14:58:50.944  3538  3585 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 14:58:51.042  1457  1457 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 14:58:51.080  3538  3585 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39bad9d
09-07 14:58:51.080  3538  3585 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39bad9d 
,09-07 14:58:51.092  3538  3579 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
09-07 14:58:51.093  3538  3579 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-07 14:58:51.094  3538  3579 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-07 14:58:51.097  3538  3579 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 14:58:51.100  3538  3579 D BluetoothAdapterProperties: Scan Mode:20
,09-07 14:58:51.101  3538  3579 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 14:58:51.101  3538  3579 D bt_hci  : do_postload posting postload work item
,09-07 14:58:51.102  3538  3583 I bt_hci  : event_postload
09-07 14:58:51.102  3538  3583 I bt_vendor: sco_config_cb
,09-07 14:58:51.102  3538  3583 I bt_hci  : sco_config_callback postload finished.
,09-07 14:58:51.104  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 14:58:51.108  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 14:58:51.109  3538  3583 I bt_vendor: low_power_mode_cb
,09-07 14:58:51.116  3538  3579 D bt_bte_conf: Device ID record 1 : primary
,09-07 14:58:51.116  3538  3579 D bt_bte_conf:   vendorId            = 000f
09-07 14:58:51.116  3538  3579 D bt_bte_conf:   vendorIdSource      = 0001
,09-07 14:58:51.116  3538  3579 D bt_bte_conf:   product             = 1200
09-07 14:58:51.116  3538  3579 D bt_bte_conf:   version             = 1436
09-07 14:58:51.117  3538  3579 D bt_bte_conf:   clientExecutableURL = 
09-07 14:58:51.117  3538  3579 D bt_bte_conf:   serviceDescription  = 
09-07 14:58:51.117  3538  3579 D bt_bte_conf:   documentationURL    = 
09-07 14:58:51.117  3538  3579 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-07 14:58:51.117  3538  3576 D bt_stack_manager: event_start_up_stack finished
,09-07 14:58:51.118  3538  3575 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-07 14:58:51.118  3538  3575 D BluetoothAdapterProperties: Setting state to 15
09-07 14:58:51.118  3538  3575 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-07 14:58:51.119  3538  3575 I BluetoothAdapterState: Entering BleOnState
,09-07 14:58:51.125  3538  3575 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-07 14:58:51.125  3538  3575 D BluetoothAdapterProperties: Setting state to 11
09-07 14:58:51.125  3538  3575 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-07 14:58:51.134  3538  3538 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
,09-07 14:58:51.137  3538  3538 D HeadsetService: Received start request. Starting profile...
,09-07 14:58:51.141  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 14:58:51.142  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:58:51.145  3538  3538 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 14:58:51.145  3538  3538 D HeadsetStateMachine: make
,09-07 14:58:51.151   874   887 I ActivityManager: Start proc 3593:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-07 14:58:51.153  3538  3538 D HeadsetStateMachine: max_hf_connections = 1
09-07 14:58:51.153  3538  3538 I bt_bluedroid: get_profile_interface handsfree
,09-07 14:58:51.154  3538  3579 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-07 14:58:51.154  3538  3579 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-07 14:58:51.157  3538  3575 I BluetoothAdapterState: Entering PendingCommandState
09-07 14:58:51.159  3538  3538 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
09-07 14:58:51.159   874   874 D BluetoothA2dp: Proxy object connected
,09-07 14:58:51.160  3538  3538 D A2dpService: Received start request. Starting profile...
09-07 14:58:51.160   874  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
09-07 14:58:51.160  3538  3538 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-07 14:58:51.161  3538  3538 I bt_bluedroid: get_profile_interface avrcp
,09-07 14:58:51.167   874  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-07 14:58:51.167  3538  3538 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-07 14:58:51.168   874  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 14:58:51.168  3538  3538 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-07 14:58:51.168  3538  3538 D A2dpStateMachine: make
,09-07 14:58:51.169  3538  3538 I bt_bluedroid: get_profile_interface a2dp
09-07 14:58:51.169  3538  3579 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-07 14:58:51.173  3538  3538 I BluetoothHidServiceJni: classInitNative: succeeds
,09-07 14:58:51.174   874  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
09-07 14:58:51.174  3538  3538 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
09-07 14:58:51.175  1349  1349 D BluetoothInputDevice: Proxy object connected
09-07 14:58:51.175  3538  3538 D HidService: Received start request. Starting profile...
09-07 14:58:51.175  3538  3538 I bt_bluedroid: get_profile_interface hidhost
,09-07 14:58:51.176  3538  3579 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb399c3e5
,09-07 14:58:51.176  1349  1349 D HidProfile: Bluetooth service connected
09-07 14:58:51.176  3538  3579 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-07 14:58:51.176  3538  3538 D HidService: setHidService(): set to: null
09-07 14:58:51.176  3538  3605 D A2dpStateMachine: Enter Disconnected: -2
09-07 14:58:51.177  3538  3538 I BluetoothHealthServiceJni: classInitNative: succeeds
09-07 14:58:51.178  3538  3538 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
,09-07 14:58:51.178  3538  3538 D HealthService: Received start request. Starting profile...
09-07 14:58:51.179  3538  3538 I bt_bluedroid: get_profile_interface health
,09-07 14:58:51.180  3538  3538 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-07 14:58:51.181  3538  3538 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
09-07 14:58:51.183  1349  1349 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 14:58:51.183  3538  3538 D PanService: Received start request. Starting profile...
09-07 14:58:51.183  1349  1349 D PanProfile: Bluetooth service connected
09-07 14:58:51.184  3538  3538 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 14:58:51.184  3538  3538 I bt_bluedroid: get_profile_interface pan
09-07 14:58:51.184  3538  3579 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-07 14:58:51.187  3538  3538 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
,09-07 14:58:51.188  1349  1349 D BluetoothMap: Proxy object connected
,09-07 14:58:51.188  3538  3538 D BluetoothMapService: Received start request. Starting profile...
,09-07 14:58:51.189  3538  3538 D BluetoothMapService: start()
09-07 14:58:51.189  1349  1349 D MapProfile: Bluetooth service connected
09-07 14:58:51.189  1349  1349 D BluetoothMap: getConnectedDevices()
09-07 14:58:51.189  1349  1349 D BluetoothMap: Bluetooth is Not enabled
,09-07 14:58:51.191  3538  3538 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-07 14:58:51.192  3538  3538 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-07 14:58:51.192  3538  3538 D BluetoothMapAppObserver: createReceiver()
09-07 14:58:51.193  3538  3538 D BluetoothMapAppObserver: initObservers()
09-07 14:58:51.193  3538  3538 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-07 14:58:51.198  3538  3538 V BluetoothAdapterState: isTurningOff()=false
,09-07 14:58:51.198  3538  3538 V BluetoothAdapterState: isTurningOn()=true
09-07 14:58:51.198  3538  3538 V BluetoothAdapterState: isBleTurningOn()=false
09-07 14:58:51.198  3538  3538 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 14:58:51.200  3538  3538 V BluetoothAdapterState: isTurningOff()=false
,09-07 14:58:51.200  3538  3538 V BluetoothAdapterState: isTurningOn()=true
09-07 14:58:51.200  3538  3538 V BluetoothAdapterState: isBleTurningOn()=false
09-07 14:58:51.200  3538  3538 V BluetoothAdapterState: isBleTurningOff()=false
09-07 14:58:51.200  3538  3538 V BluetoothAdapterState: isTurningOff()=false
09-07 14:58:51.200  3538  3538 V BluetoothAdapterState: isTurningOn()=true
,09-07 14:58:51.200  3538  3538 V BluetoothAdapterState: isBleTurningOn()=false
09-07 14:58:51.200  3538  3538 V BluetoothAdapterState: isBleTurningOff()=false
09-07 14:58:51.200  3538  3538 V BluetoothAdapterState: isTurningOff()=false
09-07 14:58:51.200  3538  3538 V BluetoothAdapterState: isTurningOn()=true
,09-07 14:58:51.200  3538  3538 V BluetoothAdapterState: isBleTurningOn()=false
09-07 14:58:51.200  3538  3538 V BluetoothAdapterState: isBleTurningOff()=false
09-07 14:58:51.200  3538  3538 V BluetoothAdapterState: isTurningOff()=false
09-07 14:58:51.200  3538  3538 V BluetoothAdapterState: isTurningOn()=true
09-07 14:58:51.200  3538  3538 V BluetoothAdapterState: isBleTurningOn()=false
09-07 14:58:51.200  3538  3538 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 14:58:51.201  3538  3538 V BluetoothAdapterState: isTurningOff()=false
09-07 14:58:51.201  3538  3538 V BluetoothAdapterState: isTurningOn()=true
09-07 14:58:51.201  3538  3538 V BluetoothAdapterState: isBleTurningOn()=false
09-07 14:58:51.201  3538  3538 V BluetoothAdapterState: isBleTurningOff()=false
09-07 14:58:51.201  3538  3575 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-07 14:58:51.201  3538  3575 D BluetoothAdapterProperties: ScanMode =  20
09-07 14:58:51.201  3538  3592 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 14:58:51.201  3538  3575 D BluetoothAdapterProperties: State =  11
09-07 14:58:51.202  3538  3575 D BluetoothAdapterProperties: Setting state to 12
,09-07 14:58:51.202  3538  3575 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-07 14:58:51.203  3538  3575 I BluetoothAdapterState: Entering OnState
,09-07 14:58:51.203  1349  2111 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 14:58:51.204  3538  3579 D BluetoothAdapterProperties: Scan Mode:21,
,09-07 14:58:51.204  3538  3579 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 14:58:51.205  1349  1360 D BluetoothPan: onBluetoothStateChange on: true
09-07 14:58:51.205  1349  1361 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 14:58:51.206  3465  3465 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-07 14:58:51.207   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 14:58:51.208   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 14:58:51.208  1349  2112 D BluetoothMap: onBluetoothStateChange: up=true
,09-07 14:58:51.209  3465  3465 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-07 14:58:51.209  1956  2124 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 14:58:51.210   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 14:58:51.210   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 14:58:51.211  3538  3538 D BluetoothMapService: onReceive
09-07 14:58:51.211  3538  3538 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 14:58:51.211  3538  3538 D BluetoothMapService: STATE_ON
,09-07 14:58:51.212  3465  3465 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-07 14:58:51.212   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,09-07 14:58:51.214  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:58:51.214  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:51.214  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:58:51.214  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:58:51.214  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 14:58:51.214  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:58:51.214  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:58:51.214  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 14:58:51.216  1349  1656 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-07 14:58:51.216  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 14:58:51.217   874  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-07 14:58:51.218  3538  3538 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-07 14:58:51.219  3538  3538 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-07 14:58:51.220  3538  3538 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 14:58:51.220  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:58:51.220  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:51.220  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:58:51.220  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:58:51.220  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 14:58:51.220  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:58:51.220  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:58:51.220  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 14:58:51.222  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 14:58:51.223  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:58:51.223  3538  3538 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 14:58:51.224  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:58:51.224  3538  3538 D ObexServerSockets: Succeed to create listening sockets 
09-07 14:58:51.224  3538  3538 D ObexServerSockets0: startAccept()
09-07 14:58:51.224  3538  3538 D ObexServerSockets0: prepareForNewConnect()
09-07 14:58:51.225  1349  1349 D BluetoothA2dp: Proxy object connected
09-07 14:58:51.225  1349  1656 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-07 14:58:51.226  3538  3538 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-07 14:58:51.226  3538  3538 D BluetoothSdpJni: SDP Create record success - handle: 0
09-07 14:58:51.226  3538  3612 D ObexServerSockets0: Accepting socket connection...
09-07 14:58:51.226  3538  3613 D ObexServerSockets0: Accepting socket connection...
,09-07 14:58:51.230  3593  3593 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-07 14:58:51.231  3538  3538 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-07 14:58:51.231  3538  3538 D ObexServerSockets0: prepareForNewConnect()
,09-07 14:58:51.238   874  2013 I ActivityManager: Killing 2992:com.google.android.gm/u0a78 (adj 15): empty #17
,09-07 14:58:51.279  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 14:58:51.293   874  2017 I ActivityManager: Start proc 3614:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-07 14:58:51.308   874   891 D BluetoothHeadset: Proxy object connected
,09-07 14:58:51.308   874   891 D BluetoothHeadset: Proxy object connected
,09-07 14:58:51.310  1956  1966 D BluetoothHeadset: Proxy object connected
,09-07 14:58:51.311   874   891 D BluetoothHeadset: Proxy object connected
,09-07 14:58:51.329  1349  2112 D BluetoothHeadset: Proxy object connected
09-07 14:58:51.330  1349  1349 D HeadsetProfile: Bluetooth service connected
,09-07 14:58:51.337  3614  3614 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-07 14:58:51.479  3614  3614 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 14:58:51.479  3614  3614 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 14:58:51.479  3614  3614 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread.main(Act,ivityThread.java:5417)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 14:58:51.479  3614  3614 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 14:58:51.479  3614  3614 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.r.k.d(PG:583)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 14:58:51.479  3614  3614 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 14:58:51.479  3614  3614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 14:58:51.480  3614  3614 D StrictMode: StrictMode policy violation; ~duration=65 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 14:58:51.480  3614  3614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 14:58:51.480  3614  3614 D StrictMode: StrictMode policy violation; ~duration=65 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 14:58:51.480  3614  3614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 14:58:51.480  3614  3614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 14:58:51.506  3593  3593 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 14:58:51.521   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7a94dc8:true
09-07 14:58:51.525  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 14:58:51.531  1457  1457 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-07 14:58:51.536  3593  3593 D LocalBluetoothProfileManager: Adding local A2DP profile
09-07 14:58:51.544  3593  3593 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-07 14:58:51.552  1349  1349 D BluetoothPbap: Proxy object connected
09-07 14:58:51.553  1349  1349 D PbapServerProfile: Bluetooth service connected
,09-07 14:58:51.555  1457  1457 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 14:58:51.555  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-07 14:58:51.557   874  1303 D WifiConfigStore: Retrieve network priorities after PNO.
09-07 14:58:51.560  3593  3593 D LocalBluetoothProfileManager: Adding local MAP profile
,09-07 14:58:51.566   874  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 14:58:51.566   874  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 14:58:51.566   874  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-07 14:58:51.561  3593  3593 D BluetoothMap: Create BluetoothMap proxy object
,09-07 14:58:51.570  3538  3643 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 14:58:51.578  3593  3593 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-07 14:58:51.581   874  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 14:58:51.590  3538  3649 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 14:58:51.591  3538  3649 I BtOppRfcommListener: Accept thread started.
,09-07 14:58:51.593   373   872 D CommandListener: Setting iface cfg
,09-07 14:58:51.595  3593  3593 D DockEventReceiver: finishStartingService: stopping service
09-07 14:58:51.596  3593  3593 D BluetoothA2dp: Proxy object connected
09-07 14:58:51.598  3593  3593 D BluetoothInputDevice: Proxy object connected
09-07 14:58:51.598   874  1303 D WifiStateMachine: Start Dhcp Watchdog 1
09-07 14:58:51.598  3593  3593 D HidProfile: Bluetooth service connected
,09-07 14:58:51.600  3593  3593 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 14:58:51.600  3593  3593 D PanProfile: Bluetooth service connected
09-07 14:58:51.600  3593  3593 D BluetoothMap: Proxy object connected
09-07 14:58:51.600  3593  3593 D MapProfile: Bluetooth service connected
09-07 14:58:51.601  3593  3593 D BluetoothMap: getConnectedDevices()
09-07 14:58:51.602  3593  3593 D BluetoothPbap: Proxy object connected
,09-07 14:58:51.602  3593  3593 D PbapServerProfile: Bluetooth service connected
,09-07 14:58:51.603   874  1971 I ActivityManager: Killing 3188:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-07 14:58:51.603   874  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-07 14:58:51.616   874  3652 D DhcpClient: Receive thread started
,09-07 14:58:51.648  3593  3608 D BluetoothHeadset: Proxy object connected
,09-07 14:58:51.649  3593  3593 D HeadsetProfile: Bluetooth service connected
,09-07 14:58:51.764   874  1303 E native  : do suspend false
,09-07 14:58:51.778   874  3650 D DhcpClient: Broadcasting DHCPDISCOVER
,09-07 14:58:51.791   874  3652 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 166644, domain null
,09-07 14:58:51.796   874  3650 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 166644 seconds
,09-07 14:58:51.799   874  3650 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-07 14:58:51.806  3614  3628 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-07 14:58:51.813   874  3652 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-07 14:58:51.814   874  3650 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-07 14:58:51.818   373   872 D CommandListener: Setting iface cfg
,09-07 14:58:51.822   874  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-07 14:58:51.826   874  1303 E native  : do suspend true
,09-07 14:58:51.826   874  3650 D DhcpClient: Scheduling renewal in 86399s
,09-07 14:58:51.836   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@62c6f15:true
,09-07 14:58:51.837   874  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-07 14:58:51.838   874  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,09-07 14:58:51.838   874  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-07 14:58:51.839   874  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-07 14:58:51.842   874  1305 D ConnectivityService: Adding iface wlan0 to network 100
,09-07 14:58:51.875   874  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-07 14:58:51.875   874  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
09-07 14:58:51.877   874  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,09-07 14:58:51.878   874  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,09-07 14:58:51.880   874  1305 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,09-07 14:58:51.886   874  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-07 14:58:51.888   874  1305 D ConnectivityService: scheduleUnvalidatedPrompt 100
09-07 14:58:51.889   874  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
09-07 14:58:51.889   874  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-07 14:58:51.889   874  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
,09-07 14:58:51.889   874  1305 D ConnectivityService:    accepting network in place of null
09-07 14:58:51.890   874  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 14:58:51.890   874  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 14:58:51.913   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 14:58:51.935   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 14:58:51.937   874  1305 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,09-07 14:58:51.941   874  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-07 14:58:51.942   874  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 14:58:51.947   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-07 14:58:51.949   874  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,09-07 14:58:51.953   874  1687 V BackupManagerService: Scheduling immediate backup pass
09-07 14:58:51.954   874   874 V BackupManagerService: Running a backup pass
09-07 14:58:51.957  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:58:51.957  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:51.957  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:58:51.957  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:58:51.957  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 14:58:51.957  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 14:58:51.957  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 14:58:51.957  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 14:58:51.961  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 14:58:51.962   874  1326 V BackupManagerService: clearing pending backups
09-07 14:58:51.965  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:58:51.965  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:51.965  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:58:51.965  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:58:51.965  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 14:58:51.965  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 14:58:51.965  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 14:58:51.965  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 14:58:51.969  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 14:58:51.970  2053  2053 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-07 14:58:51.974   874  1326 V PerformBackupTask: Beginning backup of 16 targets
,09-07 14:58:51.976  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 14:58:51.993   874  1326 D PerformBackupTask: invokeAgentForBackup on @pm@
,09-07 14:58:51.999   874  1326 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
,09-07 14:58:52.004  1713  3668 I CheckinService: Checking schedule, now: 1473253132004 next: 1473252002880
09-07 14:58:52.004  1713  3668 I CheckinService: active receiver: enabled
,09-07 14:58:52.008  1713  3668 I CheckinService: Preparing to send checkin request
,09-07 14:58:52.008  1713  3668 I EventLogService: Accumulating logs since 1473252786022
,09-07 14:58:52.016  1713  1713 D SystemUpdateService: onCreate
,09-07 14:58:52.020  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 14:58:52.022  1713  3674 I SystemUpdateService: active receiver: enabled
,09-07 14:58:52.025  1713  3674 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 14:58:52.026  1713  3674 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-07 14:58:52.026  1713  3674 I SystemUpdateService: now status is 0 (complete)
09-07 14:58:52.026  1713  3674 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 14:58:52.027  1713  3674 I SystemUpdateService: file has been verified
09-07 14:58:52.027  1713  3674 I SystemUpdateService: OTA package size = 12249756
,09-07 14:58:52.029  1713  3674 I SystemUpdateService: showing system update notification
,09-07 14:58:52.046   874  1326 I BackupRestoreController: Getting widget state for user: 0
,09-07 14:58:52.047  1713  1713 D SystemUpdateService: onDestroy
09-07 14:58:52.049  1713  3668 I EventLogService: Opted in for usage reporting
,09-07 14:58:52.067  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:58:52.070  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:58:52.081  1500  1500 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-07 14:58:52.095  1713  3687 I iu.SyncManager: SYNC; picasa accounts
,09-07 14:58:52.112  1713  3677 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,09-07 14:58:52.114  1713  1713 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,09-07 14:58:52.117  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-07 14:58:52.133  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 14:58:52.133  1713  3685 I MDM     : [151] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-07 14:58:52.133  1713  3685 W BaseAppContext: Using Auth Proxy for data requests.
09-07 14:58:52.134  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 14:58:52.142  1713  3687 I iu.UploadsManager: num queued entries: 0
,09-07 14:58:52.142  1713  3687 I iu.UploadsManager: num updated entries: 0
09-07 14:58:52.143  1713  3687 I iu.SyncManager: NEXT; no task
,09-07 14:58:52.146   874  2019 I ActivityManager: Start proc 3695:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-07 14:58:52.164  3550  3672 V GoogleAuthProtoRequest: [282] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 14:58:52.164  1713  3685 V GoogleAuthProtoRequest: [151] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 14:58:52.166  1858  1868 W GmsBackupTransport: Unknown package in backup request: @pm@
,09-07 14:58:52.168  1858  1868 V GmsBackupTransport: starting performBackup for @pm@
,09-07 14:58:52.171  1858  1868 V GmsBackupTransport: performBackup done for @pm@
,09-07 14:58:52.181  3695  3695 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
09-07 14:58:52.183  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:58:52.184  1713  3668 W EventLogAggregator: Unknown tag: snet_gcore
09-07 14:58:52.184  1713  3668 W EventLogAggregator: Unknown tag: snet_launch_service
,09-07 14:58:52.192  3695  3695 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 14:58:52.202  3695  3695 D SprintDMHelper: simOperator: 
,09-07 14:58:52.202  3695  3695 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 14:58:52.208  1500  2403 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
,09-07 14:58:52.208  1500  2403 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
09-07 14:58:52.208  1500  2367 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-07 14:58:52.208  1500  2403 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:58:52.208  1500  2367 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-07 14:58:52.208  1500  2403 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-07 14:58:52.208  1500  2367 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:58:52.208  1500  2367 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-07 14:58:52.209  1713  3668 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,09-07 14:58:52.212   874  1304 D WifiService: New client listening to asynchronous messages
,09-07 14:58:52.218   874  2013 I ActivityManager: Start proc 3712:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-07 14:58:52.229  1500  2403 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 14:58:52.229  1500  2403 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 14:58:52.229  1500  2403 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 14:58:52.229  1500  2403 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-07 14:58:52.229  1500  2403 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-07 14:58:52.229  1500  2403 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-07 14:58:52.229  1500  2403 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-07 14:58:52.230  1713  3668 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,09-07 14:58:52.235  1858  3690 W GmsBackupTransport: Error sending final backup to server: 
09-07 14:58:52.235  1858  3690 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
09-07 14:58:52.235  1858  3690 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
09-07 14:58:52.235  1858  3690 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
09-07 14:58:52.235  1858  3690 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
09-07 14:58:52.235  1858  3690 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
09-07 14:58:52.235  1858  3690 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
09-07 14:58:52.235  1858  3690 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
09-07 14:58:52.235  1858  3690 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-07 14:58:52.235  1858  3690 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-07 14:58:52.235  1858  3690 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-07 14:58:52.235  1858  3690 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-07 14:58:52.235  1858  3690 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-07 14:58:52.235  1858  3690 W GmsBackupTransport: 	... 1 more
,09-07 14:58:52.236  1858  1871 I GmsBackupTransport: Next backup will happen in 43199997 millis.
09-07 14:58:52.236   874  1326 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
,09-07 14:58:52.242  1500  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,09-07 14:58:52.242  1500  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
09-07 14:58:52.242  1713  3685 E MDM     : [151] SitrepService.a: Error sending sitrep.
09-07 14:58:52.242  1500  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:58:52.242  1500  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:58:52.262  3550  3672 W ExperimentUpdateService: [282] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,09-07 14:58:52.263  3550  3672 W ExperimentUpdateService: [282] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 14:58:52.263  3550  3672 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 14:58:52.263  3550  3672 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-07 14:58:52.263  3550  3672 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
09-07 14:58:52.263  3550  3672 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-07 14:58:52.263  3550  3672 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-07 14:58:52.263  3550  3672 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-07 14:58:52.263  3550  3672 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-07 14:58:52.263  3550  3672 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
09-07 14:58:52.263  3550  3672 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-07 14:58:52.263  3550  3672 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,09-07 14:58:52.301  1713  1713 E ConnectivityChangeReceiver: Ignoring connectivity change
,09-07 14:58:52.320   874  1689 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1713 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-07 14:58:52.337  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:58:52.389   874  1326 I BackupManagerService: Backup pass finished.
,09-07 14:58:52.392  1500  2403 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
09-07 14:58:52.392  1500  2403 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> AndroidCheckInServer without consulting the cloud.
09-07 14:58:52.392  1500  2403 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:58:52.392  1500  2403 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:58:52.418  1713  3668 W CheckinRequestBuilder: awaiting user notification for token
,09-07 14:58:52.436  1713  3682 W DriveInitializer: Awaiting to be initialized
,09-07 14:58:52.440  1713  3732 W DriveInitializer: Background init thread started
,09-07 14:58:52.451   874  1380 I ActivityManager: Start proc 3733:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,09-07 14:58:52.488  1500  3725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 14:58:52.489  1500  3725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 14:58:52.489  1500  3725 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:58:52.489  1500  3725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-07 14:58:52.496  3733  3733 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,09-07 14:58:52.514  3733  3733 I MultiDex: VM with version 2.1.0 has multidex support
,09-07 14:58:52.514  3733  3733 I MultiDex: install
09-07 14:58:52.514  3733  3733 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-07 14:58:52.522   874  2017 I ActivityManager: Start proc 3751:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-07 14:58:52.534  3269  3694 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-07 14:58:52.534  3269  3694 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 14:58:52.534  3269  3694 E HttpOperation: 	at jdm.a(PG:82)
09-07 14:58:52.534  3269  3694 E HttpOperation: 	at jcs.o(PG:406)
09-07 14:58:52.534  3269  3694 E HttpOperation: 	at jcn.a(PG:1379)
09-07 14:58:52.534  3269  3694 E HttpOperation: 	at jcs.i(PG:143)
09-07 14:58:52.534  3269  3694 E HttpOperation: 	at blb.a(PG:3937)
09-07 14:58:52.534  3269  3694 E HttpOperation: 	at czp.a(PG:18188)
09-07 14:58:52.534  3269  3694 E HttpOperation: 	at czp.a(PG:9081)
09-07 14:58:52.534  3269  3694 E HttpOperation: 	at czq.run(PG:1686)
09-07 14:58:52.534  3269  3694 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 14:58:52.534  3269  3694 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 14:58:52.534  3269  3694 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 14:58:52.534  3269  3694 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 14:58:52.534  3269  3694 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 14:58:52.534  3269  3694 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 14:58:52.534  3269  3694 E HttpOperation: 	at jdj.a(PG:4091)
09-07 14:58:52.534  3269  3694 E HttpOperation: 	at jdj.a(PG:1125)
09-07 14:58:52.534  3269  3694 E HttpOperation: 	at jdm.a(PG:77)
09-07 14:58:52.534  3269  3694 E HttpOperation: 	... 12 more
09-07 14:58:52.534  3269  3694 E HttpOperation: Caused by: faj: BadAuthentication
09-07 14:58:52.534  3269  3694 E HttpOperation: 	at fal.a(PG:38)
09-07 14:58:52.534  3269  3694 E HttpOperation: 	at jdj.a(PG:4089)
09-07 14:58:52.534  3269  3694 E HttpOperation: 	... 14 more
,09-07 14:58:52.549  1713  3732 W DriveInitializer: Background init thread ended
,09-07 14:58:52.578  3733  3733 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,09-07 14:58:52.579  1500  2403 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 14:58:52.579  1500  2403 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-07 14:58:52.579  1500  2403 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:58:52.579  1500  2403 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:58:52.590  3269  3694 E HttpOperation: [getmobileexperiments] Unexpected exception
09-07 14:58:52.590  3269  3694 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 14:58:52.590  3269  3694 E HttpOperation: 	at jdm.a(PG:82)
09-07 14:58:52.590  3269  3694 E HttpOperation: 	at jcs.o(PG:406)
09-07 14:58:52.590  3269  3694 E HttpOperation: 	at jcn.a(PG:1379)
09-07 14:58:52.590  3269  3694 E HttpOperation: 	at jcs.i(PG:143)
09-07 14:58:52.590  3269  3694 E HttpOperation: 	at hec.a(PG:42)
09-07 14:58:52.590  3269  3694 E HttpOperation: 	at hee.a(PG:102)
09-07 14:58:52.590  3269  3694 E HttpOperation: 	at czr.a(PG:65)
09-07 14:58:52.590  3269  3694 E HttpOperation: 	at kka.a(PG:108)
09-07 14:58:52.590  3269  3694 E HttpOperation: 	at czp.a(PG:19176)
09-07 14:58:52.590  3269  3694 E HttpOperation: 	at czp.a(PG:9081)
09-07 14:58:52.590  3269  3694 E HttpOperation: 	at czq.run(PG:1686)
09-07 14:58:52.590  3269  3694 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 14:58:52.590  3269  3694 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 14:58:52.590  3269  3694 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 14:58:52.590  3269  3694 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 14:58:52.590  3269  3694 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 14:58:52.590  3269  3694 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 14:58:52.590  3269  3694 E HttpOperation: 	at jdj.a(PG:4091)
09-07 14:58:52.590  3269  3694 E HttpOperation: 	at jdj.a(PG:1125)
09-07 14:58:52.590  3269  3694 E HttpOperation: 	at jdm.a(PG:77)
09-07 14:58:52.590  3269  3694 E HttpOperation: 	... 15 more
09-07 14:58:52.590  3269  3694 E HttpOperation: Caused by: faj: BadAuthentication
09-07 14:58:52.590  3269  3694 E HttpOperation: 	at fal.a(PG:38)
09-07 14:58:52.590  3269  3694 E HttpOperation: 	at jdj.a(PG:4089)
09-07 14:58:52.590  3269  3694 E HttpOperation: 	... 17 more
,09-07 14:58:52.590  3269  3694 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-07 14:58:52.590  3269  3694 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-07 14:58:52.590  3269  3694 E ExperimentLoader: 	at jdm.a(PG:82)
09-07 14:58:52.590  3269  3694 E ExperimentLoader: 	at jcs.o(PG:406)
09-07 14:58:52.590  3269  3694 E ExperimentLoader: 	at jcn.a(PG:1379)
09-07 14:58:52.590  3269  3694 E ExperimentLoader: 	at jcs.i(PG:143)
09-07 14:58:52.590  3269  3694 E ExperimentLoader: 	at hec.a(PG:42)
09-07 14:58:52.590  3269  3694 E ExperimentLoader: 	at hee.a(PG:102)
09-07 14:58:52.590  3269  3694 E ExperimentLoader: 	at czr.a(PG:65)
09-07 14:58:52.590  3269  3694 E ExperimentLoader: ,	at kka.a(PG:108)
09-07 14:58:52.590  3269  3694 E ExperimentLoader: 	at czp.a(PG:19176)
09-07 14:58:52.590  3269  3694 E ExperimentLoader: 	at czp.a(PG:9081)
09-07 14:58:52.590  3269  3694 E ExperimentLoader: 	at czq.run(PG:1686)
09-07 14:58:52.590  3269  3694 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 14:58:52.590  3269  3694 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 14:58:52.590  3269  3694 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 14:58:52.590  3269  3694 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 14:58:52.590  3269  3694 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-07 14:58:52.590  3269  3694 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 14:58:52.590  3269  3694 E ExperimentLoader: 	at jdj.a(PG:4091)
09-07 14:58:52.590  3269  3694 E ExperimentLoader: 	at jdj.a(PG:1125)
09-07 14:58:52.590  3269  3694 E ExperimentLoader: 	at jdm.a(PG:77)
09-07 14:58:52.590  3269  3694 E ExperimentLoader: 	... 15 more
09-07 14:58:52.590  3269  3694 E ExperimentLoader: Caused by: faj: BadAuthentication
09-07 14:58:52.590  3269  3694 E ExperimentLoader: 	at fal.a(PG:38)
09-07 14:58:52.590  3269  3694 E ExperimentLoader: 	at jdj.a(PG:4089)
09-07 14:58:52.590  3269  3694 E ExperimentLoader: 	... 17 more
09-07 14:58:52.606  3733  3733 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-07 14:58:52.609  3751  3751 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-07 14:58:52.644  3733  3776 D NativeLibraryUtils: Install completed successfully. count=13 extracted=0
,09-07 14:58:52.719   377   377 D WVCdm   : Instantiating CDM.
,09-07 14:58:52.719   377  1311 I WVCdm   : CdmEngine::OpenSession
09-07 14:58:52.720   377  1311 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,09-07 14:58:52.724   377  1311 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-07 14:58:52.730  3037  3746 V KeepSync: Connecting to GoogleApiClient
,09-07 14:58:52.732   874   884 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-07 14:58:52.737   377  1311 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x20
,09-07 14:58:52.737   377  1311 D DrmWidevineDash: Service_Initialize: starts!
09-07 14:58:52.737   377  1311 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-07 14:58:52.737   377  1311 D QSEECOMAPI: : App is not loaded in QSEE
,09-07 14:58:52.758  3733  3779 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-07 14:58:52.809   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 26178, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-07 14:58:52.821  1500  2403 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-07 14:58:52.821  1500  2403 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-07 14:58:52.821  1500  2403 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:58:52.821  1500  2403 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:58:52.826   874   886 I ActivityManager: Start proc 3783:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,09-07 14:58:52.837  1713  3781 V BaseAuthAsyncOperation: access token request failed
,09-07 14:58:52.839  3037  3746 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-07 14:58:52.853  3783  3783 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,09-07 14:58:52.930  3751  3751 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-07 14:58:52.930  3751  3751 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-07 14:58:52.930  3751  3751 I GAv4    :   adb logcat -s GAv4
,09-07 14:58:52.946  3751  3751 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-07 14:58:52.953  3751  3751 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-07 14:58:52.956   377  1311 D QSEECOMAPI: : Loaded image: APP id = 3
,09-07 14:58:52.957   377  1311 D DrmWidevineDash: Service_Initialize: ends! returns 0
09-07 14:58:52.958   377  1311 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2caa000
09-07 14:58:52.958   377  1311 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2caa000
,09-07 14:58:52.963   336   339 D DrmLibTime: got the req here! ret=0
,09-07 14:58:52.964   336   339 D DrmLibTime: command id, time_cmd_id = 770
09-07 14:58:52.964   336   339 D DrmLibTime: time_getutcsec starts!
09-07 14:58:52.964   336   339 D DrmLibTime: QSEE Time Listener: time_getutcsec
,09-07 14:58:52.964   336   339 D DrmLibTime: QSEE Time Listener: get_utc_seconds
09-07 14:58:52.964   336   339 D DrmLibTime: QSEE Time Listener: seconds: 1473253132
,09-07 14:58:52.964   336   339 D DrmLibTime: QSEE Time Listener: nano seconds: 964134982
,09-07 14:58:52.964   336   339 D DrmLibTime: time_getutcsec returns 0, sec = 1473253132; nsec = 964134982
09-07 14:58:52.964   336   339 D DrmLibTime: time_getutcsec finished! 
,09-07 14:58:52.964   336   339 D DrmLibTime: iotcl_continue_command finished! and return 0 
09-07 14:58:52.964   336   339 D DrmLibTime: before calling ioctl to read the next time_cmd
,09-07 14:58:52.970   377  1311 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,09-07 14:58:52.970   377  1311 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-07 14:58:52.971   377  1311 D DrmWidevineDash: hlos api version =  10
09-07 14:58:52.971   377  1311 D DrmWidevineDash: tz api version =  10
09-07 14:58:52.971   377  1311 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
09-07 14:58:52.971   377  1311 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,09-07 14:58:52.988   377  1311 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,09-07 14:58:52.988   377  1311 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
09-07 14:58:52.988   377  1311 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb2dc2134
09-07 14:58:52.989   377  1311 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
09-07 14:58:52.989   377  1311 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
09-07 14:58:52.989   377  1311 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb608ca98, dataLength=8
,09-07 14:58:52.989   377  1311 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,09-07 14:58:52.997   377  1311 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb60be200, wrapped_rsa_key_length=1280
,09-07 14:58:53.000   377  1311 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,09-07 14:58:53.000  3751  3800 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
09-07 14:58:53.000   377  1311 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-07 14:58:53.000   377  1275 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,09-07 14:58:53.000   377  1275 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
,09-07 14:58:53.001   377  1275 I WVCdm   : CdmEngine::GenerateKeyRequest
09-07 14:58:53.001   377  1275 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb468f4e0, idLength=0xb2ec0f2c
,09-07 14:58:53.011   377  1275 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,09-07 14:58:53.011   377  1275 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
09-07 14:58:53.012   377  1275 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
09-07 14:58:53.012   377  1275 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
09-07 14:58:53.012   377  1275 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
,09-07 14:58:53.012   377  1275 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
09-07 14:58:53.013   377  1275 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
09-07 14:58:53.013   377  1275 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-07 14:58:53.013   377  1275 D DrmWidevineDash: hlos api version =  10
,09-07 14:58:53.013   377  1275 D DrmWidevineDash: tz api version =  10
09-07 14:58:53.013   377  1275 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
09-07 14:58:53.013   377  1275 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
09-07 14:58:53.014   377  1275 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
09-07 14:58:53.014   377  1275 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
09-07 14:58:53.014   377  1275 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,09-07 14:58:53.015   377  1275 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
09-07 14:58:53.015   377  1275 D WVCdm   : PrepareKeyRequest: nonce=697671956
09-07 14:58:53.015   377  1275 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1989000
09-07 14:58:53.015   377  1275 D DrmWidevineDash: message_length=1624, signature=0xb3b1a500, signature_length=3001815044
,09-07 14:58:53.044  3783  3783 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-07 14:58:53.052  3783  3783 I BooksApp: Created application version: 3.6.9 (30609)
,09-07 14:58:53.073  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:58:53.075   377  1275 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,09-07 14:58:53.076   377  3477 I WVCdm   : CdmEngine::CloseSession
09-07 14:58:53.076   377  3477 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
09-07 14:58:53.076   377  3477 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
09-07 14:58:53.076   377  3477 D DrmWidevineDash: OEMCrypto_Terminate: starts!
09-07 14:58:53.077   377  3477 D DrmWidevineDash: Service_Uninitialize: starts!
09-07 14:58:53.077   377  3477 D QSEECOMAPI: : QSEECom_dealloc_memory 
09-07 14:58:53.077   377  3477 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
09-07 14:58:53.078   377  3477 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
09-07 14:58:53.078   377  3477 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,09-07 14:58:53.094  1500  2403 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-07 14:58:53.094  1500  2403 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-07 14:58:53.094  1500  2403 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:58:53.094  1500  2403 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:58:53.106  2722  2722 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 14:58:53.106  2722  2722 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-07 14:58:53.106  2722  2722 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-07 14:58:53.146  3751  3751 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-07 14:58:53.184  3783  3820 I BooksSync: Starting books sync for 61035162, extras: ade
,09-07 14:58:53.192  3751  3751 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-07 14:58:53.199  3751  3751 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9999-2)
,09-07 14:58:53.199  3751  3751 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 14:58:53.214  3751  3751 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {53697c7}
09-07 14:58:53.214  3751  3751 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 14:58:53.214  3751  3751 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-07 14:58:53.222  3751  3751 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-07 14:58:53.223  3751  3751 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-07 14:58:53.267  3751  3751 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-07 14:58:53.288  3751  3751 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 14:58:53.288  3751  3751 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 14:58:53.288  3751  3751 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 14:58:53.288  3751  3751 I Adreno  : Build Date                       : 10/20/15
09-07 14:58:53.288  3751  3751 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 14:58:53.288  3751  3751 I Adreno  : Local Branch                     : M14
09-07 14:58:53.288  3751  3751 I Adreno  : Remote Branch                    : 
09-07 14:58:53.288  3751  3751 I Adreno  : Remote Branch                    : 
09-07 14:58:53.288  3751  3751 I Adreno  : Reconstruct Branch               : 
,09-07 14:58:53.383  1500  3723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-07 14:58:53.384  1500  3723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-07 14:58:53.384  1500  3723 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:58:53.384  1500  3723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:58:53.405  3751  3839 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-07 14:58:53.408  3751  3751 I NSApplication: Starting up...
,09-07 14:58:53.419  3037  3746 E KeepSync: IOException
09-07 14:58:53.419  3037  3746 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-07 14:58:53.419  3037  3746 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-07 14:58:53.419  3037  3746 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-07 14:58:53.419  3037  3746 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-07 14:58:53.419  3037  3746 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-07 14:58:53.419  3037  3746 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-07 14:58:53.419  3037  3746 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-07 14:58:53.419  3037  3746 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-07 14:58:53.419  3037  3746 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-07 14:58:53.419  3037  3746 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-07 14:58:53.419  3037  3746 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-07 14:58:53.419  3037  3746 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-07 14:58:53.419  3037  3746 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-07 14:58:53.419  3037  3746 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-07 14:58:53.419  3037  3746 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 14:58:53.419  3037  3746 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 14:58:53.419  3037  3746 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-07 14:58:53.419  3037  3746 E KeepSync: 	... 10 more
,09-07 14:58:53.419  3037  3746 W KeepSync: Sync result 2
,09-07 14:58:53.457   874  2019 I ActivityManager: Start proc 3844:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-07 14:58:53.463   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 26191, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 14:58:53.476   874  1689 I ActivityManager: Killing 2611:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-07 14:58:53.486  3783  3857 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-07 14:58:53.591  3844  3844 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-07 14:58:53.623  1500  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 14:58:53.623  1500  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 14:58:53.623  1500  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:58:53.623  1500  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:58:53.665  1500  2367 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 14:58:53.666  1500  2367 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 14:58:53.666  1500  2367 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:58:53.666  1500  2367 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:58:53.684  3783  3857 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-07 14:58:53.685  3783  3820 E BooksSync: Soft error
09-07 14:58:53.685  3783  3820 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 14:58:53.685  3783  3820 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-07 14:58:53.686  3783  3820 E BooksSync: Sync error
09-07 14:58:53.686  3783  3820 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 14:58:53.686  3783  3820 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-07 14:58:53.686  3783  3820 I BooksSync: Finished books sync
,09-07 14:58:53.691   874  1991 I ActivityManager: Killing 2970:android.process.acore/u0a5 (adj 15): empty #17
,09-07 14:58:53.692   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 26192, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 14:58:53.998   874  1689 I ActivityManager: Killing 3349:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-07 14:58:54.089  1500  2190 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-07 14:58:54.091  1500  1500 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-07 14:58:54.098  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:58:54.100  1713  1713 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,09-07 14:58:54.127  2082  2082 D WearableService: callingUid 10011, callindPid: 2082
,09-07 14:58:54.135  1858  3867 E MDM     : [102] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-07 14:58:54.158  1713  3868 D LocationInitializer: Restart initialization of location
,09-07 14:58:54.175  1858  2040 W GCoreFlp: No location to return for getLastLocation()
09-07 14:58:54.175  1500  3869 W FusedLocationProvider: location=null
,09-07 14:58:54.715  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 14:58:54.716  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cdc78a4 added. We now have 4 listener(s)
,09-07 14:58:54.716  3465  3516 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 14:58:54.732  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 14:58:54.733  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cdc78a4 removed from the list,
09-07 14:58:54.733  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
09-07 14:58:54.733  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-07 14:58:54.735  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:58:54.736  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 14:58:54.736  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@979860d added. We now have 4 listener(s)
09-07 14:58:54.737  3465  3516 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 14:58:54.740  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:58:54.740  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@979860d removed from the list
,09-07 14:58:54.741  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
09-07 14:58:54.741  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:58:54.741  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:58:54.743  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 14:58:54.744  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aa439c2 added. We now have 4 listener(s)
09-07 14:58:54.744  3465  3516 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 14:58:54.750   874  1687 D WifiService: setWifiEnabled: false pid=3465, uid=10000
,09-07 14:58:54.750   874  1687 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 14:58:54.766  3538  3575 D BluetoothAdapterState: Current state: ON, message: 23
,09-07 14:58:54.767  3538  3575 D BluetoothAdapterProperties: Setting state to 13
09-07 14:58:54.768  3538  3575 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-07 14:58:54.768  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 14:58:54.770  3538  3575 D BluetoothAdapterProperties: onBluetoothDisable()
,09-07 14:58:54.773  3538  3575 I BluetoothAdapterState: Entering PendingCommandState
,09-07 14:58:54.781  3538  3538 D BluetoothMapService: onReceive
,09-07 14:58:54.781  3538  3538 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 14:58:54.781  3538  3538 D BluetoothMapService: STATE_TURNING_OFF
,09-07 14:58:54.782  3538  3538 D BluetoothMapService: MAP Service closeService in
,09-07 14:58:54.782  3538  3538 D BluetoothMapMasInstance0: MAP Service shutdown
09-07 14:58:54.782  3538  3538 D ObexServerSockets0: shutdown(block = true)
09-07 14:58:54.782  3538  3612 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-07 14:58:54.783  3538  3538 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-07 14:58:54.783  3538  3538 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-07 14:58:54.784  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 14:58:54.784  3465  3516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 14:58:54.784  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:54.784  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:58:54.784  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:58:54.784  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:58:54.784  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 14:58:54.784  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 14:58:54.784  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 14:58:54.785  3538  3579 D BluetoothAdapterProperties: Scan Mode:20
09-07 14:58:54.785  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:54.785  3465  3516 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 14:58:54.785  3538  3575 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-07 14:58:54.785  3538  3613 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-07 14:58:54.786  3465  3516 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 14:58:54.788  3538  3588 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-07 14:58:54.794  3538  3538 I BtOppRfcommListener: stopping Accept Thread
09-07 14:58:54.794  3538  3649 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 14:58:54.795  3538  3649 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 14:58:54.797  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:58:54.797  3593  3593 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 14:58:54.797  3538  3538 D HeadsetService: Received stop request...Stopping profile...
09-07 14:58:54.801  1956  1968 D BluetoothHeadset: Proxy object disconnected
09-07 14:58:54.802  3538  3538 D A2dpService: Received stop request...Stopping profile...
09-07 14:58:54.803  3538  3605 D A2dpStateMachine: Exit Disconnected: -1
09-07 14:58:54.803  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 14:58:54.803  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:58:54.804  3593  3604 D BluetoothHeadset: Proxy object disconnected
09-07 14:58:54.804   874  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-07 14:58:54.804   874  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-07 14:58:54.805   874  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 14:58:54.805   874   874 D BluetoothHeadset: Proxy object disconnected
,09-07 14:58:54.805   874  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 14:58:54.805  1349  1361 D BluetoothHeadset: Proxy object disconnected
09-07 14:58:54.805   874   874 D BluetoothHeadset: Proxy object disconnected
09-07 14:58:54.805   874   874 D BluetoothHeadset: Proxy object disconnected
09-07 14:58:54.808  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:54.808  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:58:54.808  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:54.808  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:58:54.808  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:58:54.808  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:58:54.808  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 14:58:54.808  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 14:58:54.808  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 14:58:54.808  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:54.808   874   874 D BluetoothA2dp: Proxy object disconnected
09-07 14:58:54.808  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 14:58:54.812  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:54.815  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:58:54.815  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:54.815  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:58:54.815  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:58:54.815  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:58:54.815  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 14:58:54.815  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 14:58:54.815  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 14:58:54.811  3538  3538 D HidService: Received stop request...Stopping profile...
,09-07 14:58:54.816  3538  3538 D HidService: Stopping Bluetooth HidService
,09-07 14:58:54.816  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:54.816  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 14:58:54.817  1349  1349 D HeadsetProfile: Bluetooth service disconnected
09-07 14:58:54.818  1349  1349 D BluetoothA2dp: Proxy object disconnected
09-07 14:58:54.818  3538  3538 V BluetoothAdapterState: isTurningOff()=true
09-07 14:58:54.818  1349  1349 D BluetoothInputDevice: Proxy object disconnected
09-07 14:58:54.818  3538  3538 V BluetoothAdapterState: isTurningOn()=false
09-07 14:58:54.818  1349  1349 D HidProfile: Bluetooth service disconnected
09-07 14:58:54.818  3538  3538 V BluetoothAdapterState: isBleTurningOn()=false
09-07 14:58:54.819  3538  3538 V BluetoothAdapterState: isBleTurningOff()=false
09-07 14:58:54.819  3538  3538 D HealthService: Received stop request...Stopping profile...
,09-07 14:58:54.820  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:58:54.821   874  1303 E native  : do suspend true
09-07 14:58:54.823  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:58:54.824  3538  3538 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 14:58:54.824  3538  3579 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-07 14:58:54.824  3538  3585 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 14:58:54.824  3538  3538 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-07 14:58:54.824  3538  3585 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 14:58:54.824  3538  3585 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 14:58:54.825  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:58:54.825  3538  3579 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-07 14:58:54.826  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:58:54.828  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 14:58:54.828  3538  3538 D PanService: Received stop request...Stopping profile...
09-07 14:58:54.831  1349  1349 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 14:58:54.831  3538  3538 D BluetoothMapService: Received stop request...Stopping profile...
09-07 14:58:54.831  3538  3538 D BluetoothMapService: stop()
09-07 14:58:54.832  3538  3538 D BluetoothMapAppObserver: deinitObservers()
09-07 14:58:54.832  3538  3538 D BluetoothMapAppObserver: removeReceiver()
,09-07 14:58:54.833  3538  3538 V BluetoothAdapterState: isTurningOff()=true
09-07 14:58:54.833  3538  3538 V BluetoothAdapterState: isTurningOn()=false
09-07 14:58:54.833  3538  3538 V BluetoothAdapterState: isBleTurningOn()=false
09-07 14:58:54.833  3538  3538 V BluetoothAdapterState: isBleTurningOff()=false
09-07 14:58:54.831  1349  1349 D PanProfile: Bluetooth service disconnected
09-07 14:58:54.834  1349  1349 D BluetoothMap: Proxy object disconnected
,09-07 14:58:54.834  1349  1349 D MapProfile: Bluetooth service disconnected
09-07 14:58:54.834  3538  3585 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 14:58:54.834  3538  3579 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-07 14:58:54.834  3538  3585 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 14:58:54.834  3538  3538 V BluetoothAdapterState: isTurningOff()=true
09-07 14:58:54.834  3538  3585 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 14:58:54.834  3538  3538 V BluetoothAdapterState: isTurningOn()=false
09-07 14:58:54.834  3538  3585 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 14:58:54.834  3538  3538 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 14:58:54.835  3538  3585 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 14:58:54.835  3538  3538 V BluetoothAdapterState: isBleTurningOff()=false
09-07 14:58:54.835  3538  3585 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 14:58:54.835  3538  3538 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 14:58:54.835  3538  3579 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 14:58:54.835  3538  3538 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 14:58:54.835  3538  3538 V BluetoothAdapterState: isTurningOff()=true
09-07 14:58:54.835  3538  3538 V BluetoothAdapterState: isTurningOn()=false
09-07 14:58:54.836  3538  3538 V BluetoothAdapterState: isBleTurningOn()=false
09-07 14:58:54.836  3538  3538 V BluetoothAdapterState: isBleTurningOff()=false
09-07 14:58:54.836  3538  3538 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 14:58:54.836  3538  3579 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-07 14:58:54.836  3538  3538 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 14:58:54.837  3593  3593 D DockEventReceiver: finishStartingService: stopping service
09-07 14:58:54.838  1349  1349 D BluetoothPbap: Proxy object disconnected
09-07 14:58:54.839  1349  1349 D PbapServerProfile: Bluetooth service disconnected
,09-07 14:58:54.839  3538  3538 V BluetoothAdapterState: isTurningOff()=true
,09-07 14:58:54.839  3538  3538 V BluetoothAdapterState: isTurningOn()=false
09-07 14:58:54.839   874  3650 D DhcpClient: Clearing IP address
09-07 14:58:54.839  3538  3538 V BluetoothAdapterState: isBleTurningOn()=false
09-07 14:58:54.839   373   872 D CommandListener: Clearing all IP addresses on wlan0
09-07 14:58:54.839  3538  3538 V BluetoothAdapterState: isBleTurningOff()=false
09-07 14:58:54.841  3538  3538 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 14:58:54.842  3538  3538 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 14:58:54.842   373   872 D CommandListener: Setting iface cfg
09-07 14:58:54.846   874  3652 D DhcpClient: Receive thread stopped
09-07 14:58:54.846  3538  3538 D BluetoothMapService: MAP Service closeService in
09-07 14:58:54.846  3538  3538 V BluetoothAdapterState: isTurningOff()=true
,09-07 14:58:54.847  3538  3538 V BluetoothAdapterState: isTurningOn()=false
09-07 14:58:54.847  3538  3538 V BluetoothAdapterState: isBleTurningOn()=false
09-07 14:58:54.847  3538  3538 V BluetoothAdapterState: isBleTurningOff()=false
09-07 14:58:54.847  3538  3575 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-07 14:58:54.847  3538  3575 D BluetoothAdapterProperties: Setting state to 15
09-07 14:58:54.847  3538  3575 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-07 14:58:54.848  3538  3538 D BluetoothMapService: cleanup()
09-07 14:58:54.848  3538  3538 D BluetoothMapService: MAP Service closeService in
09-07 14:58:54.848  3538  3575 I BluetoothAdapterState: Entering BleOnState
09-07 14:58:54.850   874  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-07 14:58:54.850  1349  2112 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 14:58:54.850   874  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-07 14:58:54.852   874  1303 D WifiStateMachine: Start Disconnecting Watchdog 1
09-07 14:58:54.853   874  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-07 14:58:54.853   396   396 E Parcel  : Reading a NULL string not supported here.
09-07 14:58:54.853   874  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 14:58:54.853   874  1303 E native  : do suspend true
09-07 14:58:54.853  1349  2111 D BluetoothPan: onBluetoothStateChange on: false
09-07 14:58:54.857  3593  3608 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 14:58:54.857  3593  3604 D BluetoothMap: onBluetoothStateChange: up=false
09-07 14:58:54.860  3593  3608 D BluetoothPan: onBluetoothStateChange on: false
,09-07 14:58:54.867  1349  1360 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 14:58:54.869  1349  1361 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 14:58:54.869  3593  3604 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 14:58:54.870  1349  2112 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 14:58:54.870   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 14:58:54.870   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 14:58:54.871  1349  2111 D BluetoothMap: onBluetoothStateChange: up=false
,09-07 14:58:54.871  1956  2121 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 14:58:54.872   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 14:58:54.872   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 14:58:54.872  3593  3608 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 14:58:54.872  3593  3604 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 14:58:54.873  3538  3575 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-07 14:58:54.873  3538  3575 D BluetoothAdapterProperties: Setting state to 16
09-07 14:58:54.873  3538  3575 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-07 14:58:54.876  3538  3575 D BluetoothAdapterProperties: onBleDisable
09-07 14:58:54.876  3538  3575 I BluetoothAdapterState: Entering PendingCommandState
09-07 14:58:54.876  3538  3576 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-07 14:58:54.877  3538  3585 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-07 14:58:54.877  3538  3585 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 14:58:54.880  3593  3593 D HeadsetProfile: Bluetooth service disconnected
09-07 14:58:54.880  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:54.880  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:58:54.880  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:54.880  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:58:54.880  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:58:54.880  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:58:54.880  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:58:54.880  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:58:54.880  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 14:58:54.880  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:54.881  3593  3593 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 14:58:54.882  3538  3579 D BluetoothAdapterProperties: Scan Mode:20
09-07 14:58:54.884  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 14:58:54.885  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 14:58:54.886  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:54.886  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:58:54.886  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:54.886  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:58:54.886  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:58:54.886  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:58:54.886  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:58:54.886  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:58:54.886  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 14:58:54.887  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:54.887  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 14:58:54.896   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 14:58:54.898  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:54.898  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:58:54.898  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:54.898  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:58:54.898  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:58:54.898  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:58:54.898  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:58:54.898  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:58:54.898  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 14:58:54.899  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:54.899  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 14:58:54.902  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 14:58:54.903  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:58:54.903  3593  3593 D DockEventReceiver: finishStartingService: stopping service
09-07 14:58:54.904  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 14:58:54.914   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 14:58:54.915   874  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-07 14:58:54.915   874  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-07 14:58:54.915   373   872 D CommandListener: Clearing all IP addresses on wlan0
09-07 14:58:54.917   874  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-07 14:58:54.920   874   891 D Tethering: MasterInitialState.processMessage what=3
09-07 14:58:54.922  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 14:58:54.923  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:58:54.924  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 14:58:54.930  2053  2053 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-07 14:58:54.936   874  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 14:58:54.939  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 14:58:54.939  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:58:54.939  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:54.939  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:58:54.939  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 14:58:54.939  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:58:54.939  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:58:54.939  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:58:54.939  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 14:58:54.939  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:54.939  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 14:58:54.941  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:54.941  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:58:54.941  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:54.941  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:58:54.941  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 14:58:54.941  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:58:54.941  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:58:54.941  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:58:54.941  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 14:58:54.941  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 14:58:54.941  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 14:58:54.942  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 14:58:54.940  1858  2279 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 14:58:54.943  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:54.943  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:58:54.943  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:54.943  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:58:54.943  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 14:58:54.943  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:58:54.943  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:58:54.943  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:58:54.943  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 14:58:54.943  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:54.943  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 14:58:54.947  1713  1713 D SystemUpdateService: onCreate
,09-07 14:58:54.949   874  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-07 14:58:54.952  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 14:58:54.954  1713  3887 I SystemUpdateService: active receiver: enabled
,09-07 14:58:54.959  1713  3887 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 14:58:54.961  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-07 14:58:54.962  1713  3887 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-07 14:58:54.962  1713  3887 I SystemUpdateService: now status is 0 (complete)
09-07 14:58:54.962  1713  3887 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 14:58:54.962  1713  3887 I SystemUpdateService: file has been verified
,09-07 14:58:54.962  1713  3887 I SystemUpdateService: OTA package size = 12249756
,09-07 14:58:54.965  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 14:58:54.966  1713  3687 I iu.UploadsManager: num queued entries: 0
,09-07 14:58:54.966  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 14:58:54.968  1713  3687 I iu.UploadsManager: num updated entries: 0
,09-07 14:58:54.969  1713  3687 I iu.SyncManager: NEXT; no task
,09-07 14:58:54.970  3695  3695 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 14:58:54.972  1713  3887 I SystemUpdateService: showing system update notification
,09-07 14:58:54.973  3695  3695 D SprintDMHelper: simOperator: 
,09-07 14:58:54.973  3695  3695 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 14:58:54.981   373   872 E Netd    : netlink response contains error (No such file or directory)
,09-07 14:58:54.982   874  1305 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-07 14:58:54.989  1713  1713 D SystemUpdateService: onDestroy
,09-07 14:58:55.046  3893  3893 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,09-07 14:58:55.078  3538  3579 I bt_hci  : shut_down
,09-07 14:58:55.080  3893  3893 I dex2oat : dex2oat took 34.450ms (threads: 4) arena alloc=196KB java alloc=63KB native alloc=1535KB free=1792KB
,09-07 14:58:55.083  3538  3583 D bt_hwcfg: hw_epilog_process
,09-07 14:58:55.083  3538  3583 I bt_vendor: low_power_mode_cb
,09-07 14:58:55.089  3733  3779 W System  : ClassLoader referenced unknown path: 
,09-07 14:58:55.109  3538  3583 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-07 14:58:55.109  3538  3583 I bt_vendor: epilog_cb
,09-07 14:58:55.110  3538  3583 I bt_hci  : epilog_finished_callback
,09-07 14:58:55.114  3538  3579 I bt_hci_h4: hal_close
09-07 14:58:55.115  3538  3579 I bt_userial_vendor: device fd = 51 close
,09-07 14:58:55.122  3733  3779 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 14:58:55.122  3733  3779 I Adreno  : Build Date                       : 10/20/15
09-07 14:58:55.122  3733  3779 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 14:58:55.122  3733  3779 I Adreno  : Local Branch                     : M14
09-07 14:58:55.122  3733  3779 I Adreno  : Remote Branch                    : 
09-07 14:58:55.122  3733  3779 I Adreno  : Remote Branch                    : 
09-07 14:58:55.122  3733  3779 I Adreno  : Reconstruct Branch               : 
,09-07 14:58:55.232  3538  3576 D bt_stack_manager: event_shut_down_stack finished.
09-07 14:58:55.235  3538  3575 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-07 14:58:55.236   377  1275 I WVCdm   : CdmEngine::OpenSession
,09-07 14:58:55.236   377  1275 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,09-07 14:58:55.237   377  1275 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
09-07 14:58:55.239   377  1275 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x20
,09-07 14:58:55.239   377  1275 D DrmWidevineDash: Service_Initialize: starts!
,09-07 14:58:55.239   377  1275 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,09-07 14:58:55.239   377  1275 D QSEECOMAPI: : App is not loaded in QSEE
,09-07 14:58:55.239  3538  3575 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-07 14:58:55.239  3538  3538 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 14:58:55.241  3538  3538 D BtGatt.GattService: Received stop request...Stopping profile...
,09-07 14:58:55.241  3538  3538 D BtGatt.GattService: stop()
,09-07 14:58:55.241  3538  3538 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 14:58:55.245  3538  3538 V BluetoothAdapterState: isTurningOff()=false
,09-07 14:58:55.247  3538  3538 V BluetoothAdapterState: isTurningOn()=false
,09-07 14:58:55.247  3538  3538 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 14:58:55.248  3538  3538 V BluetoothAdapterState: isBleTurningOff()=true
,09-07 14:58:55.248  3538  3575 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-07 14:58:55.248  3538  3575 D BluetoothAdapterProperties: Setting state to 10
09-07 14:58:55.248  3538  3575 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-07 14:58:55.249  3538  3575 I BluetoothAdapterState: Entering OffState
,09-07 14:58:55.250   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-07 14:58:55.271  3538  3538 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-07 14:58:55.271  3538  3538 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-07 14:58:55.272  3538  3538 I BluetoothServiceJni: cleanupNative: return from cleanup
09-07 14:58:55.272  3538  3576 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-07 14:58:55.274  3538  3576 D bt_stack_manager: event_clean_up_stack finished.
,09-07 14:58:55.277  3538  3538 I art     : System.exit called, status: 0
,09-07 14:58:55.277  3538  3538 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-07 14:58:55.331   874  2012 I ActivityManager: Process com.android.bluetooth (pid 3538) has died
,09-07 14:58:55.464   377  1275 D QSEECOMAPI: : Loaded image: APP id = 3
,09-07 14:58:55.468   377  1275 D DrmWidevineDash: Service_Initialize: ends! returns 0
09-07 14:58:55.470   377  1275 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2c66000
,09-07 14:58:55.470   377  1275 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2c66000
,09-07 14:58:55.485   336   339 D DrmLibTime: got the req here! ret=0
,09-07 14:58:55.486   336   339 D DrmLibTime: command id, time_cmd_id = 770
09-07 14:58:55.486   336   339 D DrmLibTime: time_getutcsec starts!
09-07 14:58:55.486   336   339 D DrmLibTime: QSEE Time Listener: time_getutcsec
,09-07 14:58:55.486   336   339 D DrmLibTime: QSEE Time Listener: get_utc_seconds
09-07 14:58:55.487   336   339 D DrmLibTime: QSEE Time Listener: seconds: 1473253135
,09-07 14:58:55.487   336   339 D DrmLibTime: QSEE Time Listener: nano seconds: 486988150
09-07 14:58:55.487   336   339 D DrmLibTime: time_getutcsec returns 0, sec = 1473253135; nsec = 486988150,
09-07 14:58:55.487   336   339 D DrmLibTime: time_getutcsec finished! 
,09-07 14:58:55.488   336   339 D DrmLibTime: iotcl_continue_command finished! and return 0 
09-07 14:58:55.488   336   339 D DrmLibTime: before calling ioctl to read the next time_cmd
,09-07 14:58:55.509   377  1275 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,09-07 14:58:55.510   377  1275 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,09-07 14:58:55.510   377  1275 D DrmWidevineDash: hlos api version =  10
09-07 14:58:55.510   377  1275 D DrmWidevineDash: tz api version =  10
09-07 14:58:55.511   377  1275 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
09-07 14:58:55.511   377  1275 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,09-07 14:58:55.525   377  1275 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,09-07 14:58:55.525   377  1275 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
,09-07 14:58:55.525   377  1275 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb2ec1134
,09-07 14:58:55.526   377  1275 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
,09-07 14:58:55.526   377  1275 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
,09-07 14:58:55.526   377  1275 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb608d038, dataLength=8
,09-07 14:58:55.527   377  1275 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
09-07 14:58:55.527   377  1275 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb2c9bc00, wrapped_rsa_key_length=1280
09-07 14:58:55.531   377  1275 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,09-07 14:58:55.531   377  1275 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-07 14:58:55.534   377  1311 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-07 14:58:55.535   377  1311 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
09-07 14:58:55.535   377  1311 I WVCdm   : CdmEngine::GenerateKeyRequest
09-07 14:58:55.535   377  1311 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb374bca0, idLength=0xb2dc1f2c
,09-07 14:58:55.564   377  1311 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,09-07 14:58:55.564   377  1311 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
09-07 14:58:55.565   377  1311 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
09-07 14:58:55.565   377  1311 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
09-07 14:58:55.565   377  1311 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
09-07 14:58:55.566   377  1311 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,09-07 14:58:55.566   377  1311 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
09-07 14:58:55.566   377  1311 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,09-07 14:58:55.567   377  1311 D DrmWidevineDash: hlos api version =  10
09-07 14:58:55.567   377  1311 D DrmWidevineDash: tz api version =  10
09-07 14:58:55.567   377  1311 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
09-07 14:58:55.568   377  1311 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
09-07 14:58:55.568   377  1311 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,09-07 14:58:55.569   377  1311 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
09-07 14:58:55.569   377  1311 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
09-07 14:58:55.569   377  1311 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
09-07 14:58:55.569   377  1311 D WVCdm   : PrepareKeyRequest: nonce=3127085578
09-07 14:58:55.570   377  1311 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb31c2000
,09-07 14:58:55.570   377  1311 D DrmWidevineDash: message_length=1658, signature=0xb60b6e80, signature_length=3000770564
,09-07 14:58:55.645   377  1311 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,09-07 14:58:55.646   377  1275 I WVCdm   : CdmEngine::CloseSession
09-07 14:58:55.646   377  1275 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,09-07 14:58:55.647   377  1275 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
09-07 14:58:55.647   377  1275 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,09-07 14:58:55.647   377  1275 D DrmWidevineDash: Service_Uninitialize: starts!
09-07 14:58:55.647   377  1275 D QSEECOMAPI: : QSEECom_dealloc_memory 
,09-07 14:58:55.647   377  1275 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
09-07 14:58:55.648   377  1275 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
09-07 14:58:55.648   377  1275 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,09-07 14:58:55.658  1713  3668 I CheckinRequestBuilder: Classify the device as Phone.
,09-07 14:58:55.672  1713  3668 I EventLogService: Opted in for usage reporting
,09-07 14:58:55.812  1713  3668 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,09-07 14:58:55.820  1713  3668 I CheckinService: Checking schedule, now: 1473253135820 next: 1473253145812
,09-07 14:58:55.820  1713  3668 I CheckinService: active receiver: disabled
,09-07 14:58:55.831  1713  3905 I CheckinService: Checking schedule, now: 1473253135831 next: 1473253145812
,09-07 14:58:55.831  1713  3905 I CheckinService: active receiver: disabled
,09-07 14:58:55.849  1500  2379 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-07 14:58:55.853  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 14:58:55.854  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 14:58:56.903   874  3640 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-07 14:58:56.908   874  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-07 14:58:57.165  1500  3683 W PhenotypeConfigurator: IOException while sending for: 
,09-07 14:58:57.278  1500  3683 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,09-07 14:58:57.564  2872  3749 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,09-07 14:58:57.564  2872  3749 I Babel   : connection state changed from UNKNOWN to CONNECTED
,09-07 14:58:57.569  2872  3749 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-07 14:58:57.806  1500  3913 I VacuumService: Vacuum at: now=1473253137806 tag=VacuumService
,09-07 14:58:58.065  3783  3806 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-07 14:58:59.150   874   885 I ActivityManager: Killing 3366:com.android.musicfx/u0a18 (adj 15): empty #17
,09-07 14:58:59.788   874  2020 D WifiService: setWifiEnabled: true pid=3465, uid=10000
09-07 14:58:59.788   874  2020 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 14:58:59.810   874  1303 D WifiConfigStore: Loading config and enabling all networks 
,09-07 14:58:59.811  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 14:58:59.811  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:58:59.811  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:59.811  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:58:59.811  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:58:59.811  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:58:59.811  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:58:59.811  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:58:59.811  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 14:58:59.811  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 14:58:59.812  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 14:58:59.815  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:59.815  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:58:59.815  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:59.815  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:58:59.815  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:58:59.815  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:58:59.815  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:58:59.815  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:58:59.815  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 14:58:59.815  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 14:58:59.815  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 14:58:59.816  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:59.816  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:58:59.816  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:58:59.816  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:58:59.816  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:58:59.816  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:58:59.816  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:58:59.816  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:58:59.816  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 14:58:59.816  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:58:59.816  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 14:58:59.845   874  1303 D WifiConfigStore: loaded 0 passpoint configs
,09-07 14:58:59.846   874  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-07 14:58:59.847   874  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-07 14:58:59.848   874  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-07 14:58:59.848   874  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-07 14:58:59.848   874  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-07 14:58:59.848   874  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-07 14:58:59.869   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-07 14:58:59.870   373   872 D CommandListener: Setting iface cfg
09-07 14:58:59.870   874  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 14:58:59.871   874  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-07 14:58:59.871   874  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-07 14:58:59.892   874  1305 D ConnectivityService: handlePromptUnvalidated 100
,09-07 14:58:59.927   874  1302 D WifiNative-HAL: p2pGetDeviceAddress
,09-07 14:58:59.928   874  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-07 14:58:59.933   874  1303 E native  : do suspend true
,09-07 14:58:59.986   874  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 14:59:00.669   874  1978 I ActivityManager: Killing 3387:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-07 14:59:01.281   874  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 14:59:01.390   874  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.62 rxSuccessRate=0.44 delta 1000 -> 1000
,09-07 14:59:01.393   874  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-07 14:59:01.393   874  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 14:59:01.410   874  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-07 14:59:01.484   874  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-07 14:59:01.486  1457  1457 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 14:59:01.923  1457  1457 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 14:59:01.962  1457  1457 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 14:59:01.964  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-07 14:59:01.974   874  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 14:59:01.989   874  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 14:59:01.990   874  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 14:59:01.990   874  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-07 14:59:02.008   874  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 14:59:02.018   373   872 D CommandListener: Setting iface cfg
,09-07 14:59:02.020   874  1303 D WifiStateMachine: Start Dhcp Watchdog 2
,09-07 14:59:02.027   874  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-07 14:59:02.095   874  3920 D DhcpClient: Receive thread started
,09-07 14:59:02.182   874  1303 E native  : do suspend false
,09-07 14:59:02.201   874  3650 D DhcpClient: Broadcasting DHCPDISCOVER
,09-07 14:59:02.215   874  3920 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172790, domain null
,09-07 14:59:02.217   874  3650 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172790 seconds
,09-07 14:59:02.224   874  3650 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-07 14:59:02.238   874  3920 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-07 14:59:02.240   874  3650 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-07 14:59:02.246   373   872 D CommandListener: Setting iface cfg
,09-07 14:59:02.257   874  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-07 14:59:02.258   874  3650 D DhcpClient: Scheduling renewal in 86399s
,09-07 14:59:02.259   874  1303 E native  : do suspend true
,09-07 14:59:02.273   874  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-07 14:59:02.275   874  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,09-07 14:59:02.276   874  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-07 14:59:02.279   874  1305 D ConnectivityService: Adding iface wlan0 to network 101
,09-07 14:59:02.290   874  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 14:59:02.347   874  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-07 14:59:02.348   874  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-07 14:59:02.350   874  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-07 14:59:02.352   874  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-07 14:59:02.354   874  1305 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-07 14:59:02.370   874  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 14:59:02.375   874  1305 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-07 14:59:02.375   874  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-07 14:59:02.375   874  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-07 14:59:02.376   874  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 14:59:02.376   874  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-07 14:59:02.376   874  1305 D ConnectivityService:    accepting network in place of null
,09-07 14:59:02.378   874  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 14:59:02.443   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 14:59:02.478   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 14:59:02.490   874  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-07 14:59:02.491   874  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 14:59:02.498   874  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-07 14:59:02.501   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-07 14:59:02.517  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 14:59:02.517  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:02.517  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:02.517  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:02.517  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:59:02.517  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:59:02.517  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 14:59:02.517  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 14:59:02.517  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 14:59:02.517  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:59:02.518  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 14:59:02.523  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 14:59:02.524  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:02.524  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:02.524  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:02.524  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:59:02.524  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:59:02.524  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 14:59:02.524  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 14:59:02.524  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 14:59:02.524  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
,09-07 14:59:02.524  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 14:59:02.526  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 14:59:02.526  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:02.526  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:02.526  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:02.526  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:59:02.526  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:59:02.526  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 14:59:02.526  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 14:59:02.526  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 14:59:02.526  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 14:59:02.526  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 14:59:02.530  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-07 14:59:02.531  2053  2053 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-07 14:59:02.533  1713  1713 D SystemUpdateService: onCreate
,09-07 14:59:02.537  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 14:59:02.541  1713  3931 I SystemUpdateService: active receiver: enabled
,09-07 14:59:02.543  1713  3931 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 14:59:02.545  1713  3931 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-07 14:59:02.545  1713  3931 I SystemUpdateService: now status is 0 (complete)
09-07 14:59:02.545  1713  3931 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 14:59:02.545  1713  3931 I SystemUpdateService: file has been verified
,09-07 14:59:02.545  1713  3931 I SystemUpdateService: OTA package size = 12249756
,09-07 14:59:02.551  1713  3931 I SystemUpdateService: showing system update notification
,09-07 14:59:02.561  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-07 14:59:02.564  1713  3687 I iu.UploadsManager: num queued entries: 0
,09-07 14:59:02.565  1713  3687 I iu.UploadsManager: num updated entries: 0
09-07 14:59:02.566  1713  3687 I iu.SyncManager: NEXT; no task
,09-07 14:59:02.568  1713  1713 D SystemUpdateService: onDestroy
,09-07 14:59:02.570  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 14:59:02.572  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 14:59:02.573  3695  3695 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 14:59:02.575  1713  3934 I MDM     : [186] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-07 14:59:02.575  1713  3934 W BaseAppContext: Using Auth Proxy for data requests.
,09-07 14:59:02.576  1713  3934 V GoogleAuthProtoRequest: [186] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 14:59:02.581  3695  3695 D SprintDMHelper: simOperator: 
,09-07 14:59:02.581  3695  3695 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 14:59:02.581  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:59:02.583  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:59:02.614  1500  3725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-07 14:59:02.614  1500  3725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-07 14:59:02.614  1500  3725 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:59:02.614  1500  3725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:59:02.629  1713  3934 E MDM     : [186] SitrepService.a: Error sending sitrep.
,09-07 14:59:03.080  2722  2732 D Finsky  : [172] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,09-07 14:59:03.098  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:59:03.175  1500  2048 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 14:59:03.175  1500  2048 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-07 14:59:03.176  1500  2048 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:59:03.177  1500  2048 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:59:03.240  2722  2732 D Finsky  : [172] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,09-07 14:59:03.488   874  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-07 14:59:04.797   874  2012 D WifiService: setWifiEnabled: false pid=3465, uid=10000
,09-07 14:59:04.798   874  2012 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 14:59:04.834  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-07 14:59:04.840   874  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-07 14:59:04.841   874  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-07 14:59:04.842   874  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 14:59:04.842   874  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 14:59:04.867   874  1303 E native  : do suspend true
,09-07 14:59:04.888   874  3650 D DhcpClient: Clearing IP address
,09-07 14:59:04.889   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-07 14:59:04.908   373   872 D CommandListener: Setting iface cfg
,09-07 14:59:04.913   874  3920 D DhcpClient: Receive thread stopped
,09-07 14:59:04.916   874  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 14:59:04.917   874  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-07 14:59:04.922   396   396 E Parcel  : Reading a NULL string not supported here.
,09-07 14:59:04.923   874  1303 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-07 14:59:04.927   874  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-07 14:59:04.928   874  1303 E native  : do suspend true
,09-07 14:59:04.932   874  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-07 14:59:04.970   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 14:59:05.016   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 14:59:05.017   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-07 14:59:05.019   874  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-07 14:59:05.019   874  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 14:59:05.026   874  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 14:59:05.034   874   891 D Tethering: MasterInitialState.processMessage what=3
09-07 14:59:05.036  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:59:05.036  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:05.036  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:05.036  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:05.036  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:59:05.036  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:59:05.036  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:59:05.036  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:59:05.036  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 14:59:05.036  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:59:05.037  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 14:59:05.039  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:59:05.039  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:05.039  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:05.039  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:05.039  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:59:05.039  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:59:05.039  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:59:05.039  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:59:05.039  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 14:59:05.039  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:59:05.039  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 14:59:05.041  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:59:05.041  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:05.041  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:05.041  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:05.041  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:59:05.041  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:59:05.041  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:59:05.041  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:59:05.041  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 14:59:05.041  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:59:05.041  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 14:59:05.055  2053  2053 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-07 14:59:05.058   874  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 14:59:05.061  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:59:05.062  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:05.062  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:05.062  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:05.062  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 14:59:05.062  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:59:05.062  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:59:05.062  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:59:05.062  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 14:59:05.062  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:59:05.062  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 14:59:05.063  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 14:59:05.063  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:05.063  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:05.063  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:05.063  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 14:59:05.063  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:59:05.063  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:59:05.063  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:59:05.063  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 14:59:05.063  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:59:05.063  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 14:59:05.065  1858  2279 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 14:59:05.065  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:59:05.065  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:05.065  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:05.065  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:05.065  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 14:59:05.065  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:59:05.065  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:59:05.065  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:59:05.065  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 14:59:05.065  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:59:05.065   874  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 14:59:05.065  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 14:59:05.079  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 14:59:05.086  1713  1713 D SystemUpdateService: onCreate
,09-07 14:59:05.089  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 14:59:05.102  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-07 14:59:05.111  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 14:59:05.112  1713  3687 I iu.UploadsManager: num queued entries: 0
,09-07 14:59:05.113  1713  3687 I iu.UploadsManager: num updated entries: 0
,09-07 14:59:05.113  1713  3687 I iu.SyncManager: NEXT; no task
,09-07 14:59:05.115  1713  3951 I SystemUpdateService: active receiver: enabled
,09-07 14:59:05.116   373   872 E Netd    : netlink response contains error (No such file or directory),
09-07 14:59:05.117   874  1305 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-07 14:59:05.117  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-07 14:59:05.119  3695  3695 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-07 14:59:05.125  3695  3695 D SprintDMHelper: simOperator: 
09-07 14:59:05.125  3695  3695 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-07 14:59:05.136  1713  3951 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 14:59:05.145  1713  3951 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-07 14:59:05.145  1713  3951 I SystemUpdateService: now status is 0 (complete)
,09-07 14:59:05.145  1713  3951 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 14:59:05.146  1713  3951 I SystemUpdateService: file has been verified
,09-07 14:59:05.146  1713  3951 I SystemUpdateService: OTA package size = 12249756
,09-07 14:59:05.153  1713  3951 I SystemUpdateService: showing system update notification
,09-07 14:59:05.170  1713  1713 D SystemUpdateService: onDestroy
,09-07 14:59:05.939   874  1294 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-07 14:59:05.977   874  1380 I ActivityManager: Start proc 3959:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-07 14:59:06.017  3959  3959 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-07 14:59:06.055  1858  1858 V GmsNetworkLocationProvi: DISABLE
,09-07 14:59:06.058  3959  3959 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-07 14:59:06.062  1858  1858 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,09-07 14:59:06.082   874   885 I ActivityManager: Killing 3315:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-07 14:59:06.112  3959  3974 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,09-07 14:59:06.152  1713  3977 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,09-07 14:59:06.165  2053  3978 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-07 14:59:06.170  1713  3977 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,09-07 14:59:06.222  1713  2337 I Icing   : updateResources: need to parse f{com.google.android.gms}
,09-07 14:59:06.225  2053  3978 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 60 ms] updated apps [took 60 ms] 
,09-07 14:59:06.439  3959  3974 D ContactDirectoryManager: Found com.google.contacts.gal.provider
,09-07 14:59:06.440  3959  3974 D ContactDirectoryManager: Found com.google.android.gm.exchange.directory.provider
,09-07 14:59:06.463   874  2013 I ActivityManager: Start proc 3982:com.google.android.gm.exchange/u0a77 for content provider com.google.android.gm.exchange/com.android.exchange.provider.ExchangeDirectoryProvider
,09-07 14:59:06.537  3982  3982 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltExchange3Google/lib/arm
,09-07 14:59:06.572   874  2017 I ActivityManager: Start proc 3994:com.google.android.gm/u0a78 for content provider com.google.android.gm/com.android.email.provider.EmailProvider
,09-07 14:59:06.603   874  1687 I ActivityManager: Killing 3783:com.google.android.apps.books/u0a34 (adj 15): empty #17
,09-07 14:59:06.661  3994  3994 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltGmail/lib/arm
,09-07 14:59:06.680   874  1689 I ActivityManager: Start proc 4006:com.google.process.gapps/u0a99 for content provider com.google.android.syncadapters.contacts/.GalProvider
,09-07 14:59:06.707   874  1978 I ActivityManager: Killing 3593:com.android.settings/1000 (adj 15): empty #17
,09-07 14:59:06.739  3994  4020 I Gmail   : getAccountsCursor
,09-07 14:59:06.771  3994  4021 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,09-07 14:59:06.773  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:59:06.804  4006  4006 W System  : ClassLoader referenced unknown path: /system/app/GoogleContactsSyncAdapter/lib/arm
,09-07 14:59:06.848  4006  4006 I GoogleHttpClient: GMS http client unavailable, use old client
,09-07 14:59:06.856  3994  3994 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-07 14:59:06.882  3959  3974 I ContactDirectoryManager: deleted 0 stale rows which don't have any relevant directory
,09-07 14:59:06.908  3994  4034 E Gmail   : Error finding the version of the Email provider.....
09-07 14:59:06.908  3994  4034 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
09-07 14:59:06.908  3994  4034 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
09-07 14:59:06.908  3994  4034 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1280)
09-07 14:59:06.908  3994  4034 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
09-07 14:59:06.908  3994  4034 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-07 14:59:06.908  3994  4034 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 14:59:06.908  3994  4034 E Gmail   : 	at android.os.Looper.loop(Looper.java:148)
09-07 14:59:06.908  3994  4034 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 14:59:06.909  3994  4034 W EmailMigration: We do not support migrating this version of the Email provider.
,09-07 14:59:06.910  3959  3974 I ContactDirectoryManager: Discovered 0 contact directories in 606ms
,09-07 14:59:06.947  3994  4036 I Gmail   : getAccountsCursor
,09-07 14:59:06.960  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:59:07.018  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:59:07.091   874  2013 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,09-07 14:59:07.129  3982  3982 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-07 14:59:07.146  3994  4043 I Gmail   : Observing account changes for notifications
,09-07 14:59:07.157  3982  3982 I Exchange: EasService.onCreate
,09-07 14:59:07.158  3994  4047 I Gmail   : getAccountsCursor
,09-07 14:59:07.174  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:59:07.174  3982  4048 I Exchange: RestartPingTask
,09-07 14:59:07.187  3994  4042 I Gmail   : notifyAccountChanged
,09-07 14:59:07.194  3994  4042 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,09-07 14:59:07.199  3982  3982 I Exchange: RestartPingsTask did not start any pings.
,09-07 14:59:07.199  3982  3982 I Exchange: PSS stopIfIdle
,09-07 14:59:07.199  3982  3982 I Exchange: PSS has no active accounts; stopping service.
,09-07 14:59:07.200  3982  3982 I Exchange: onDestroy
,09-07 14:59:07.212  3994  4042 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,09-07 14:59:07.229  3994  4042 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,09-07 14:59:07.233  3994  4042 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,09-07 14:59:07.310  3994  4036 I Gmail   : getAccountsCursor
,09-07 14:59:07.321  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:59:07.392   874  3918 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-07 14:59:07.393   874  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-07 14:59:07.601  2872  3936 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
09-07 14:59:07.602  2872  3936 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-07 14:59:07.609  2872  3936 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-07 14:59:09.853   874   891 I ActivityManager: Start proc 4049:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-07 14:59:09.977  4049  4049 D AdapterServiceConfig: Adding HeadsetService
,09-07 14:59:09.978  4049  4049 D AdapterServiceConfig: Adding A2dpService
09-07 14:59:09.978  4049  4049 D AdapterServiceConfig: Adding HidService
09-07 14:59:09.978  4049  4049 D AdapterServiceConfig: Adding HealthService
09-07 14:59:09.978  4049  4049 D AdapterServiceConfig: Adding PanService
,09-07 14:59:09.978  4049  4049 D AdapterServiceConfig: Adding GattService
09-07 14:59:09.979  4049  4049 D AdapterServiceConfig: Adding BluetoothMapService
,09-07 14:59:10.000   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8bedb70:true
,09-07 14:59:10.001  4049  4049 D BluetoothAdapterState: make() - Creating AdapterState
,09-07 14:59:10.006  4049  4049 I bt_bluedroid: init
,09-07 14:59:10.007  4049  4061 I BluetoothAdapterState: Entering OffState
,09-07 14:59:10.010  4049  4062 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-07 14:59:10.010  4049  4062 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-07 14:59:10.010  4049  4062 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 14:59:10.011  4049  4062 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-07 14:59:10.012  4049  4049 I bt_bluedroid: get_profile_interface socket
,09-07 14:59:10.016  4049  4049 I bt_bluedroid: get_profile_interface sdp
,09-07 14:59:10.018  4049  4065 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 14:59:10.021  4049  4065 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 14:59:10.023  4049  4060 I bt_bluedroid: config_hci_snoop_log
,09-07 14:59:10.026   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-07 14:59:10.033  4049  4061 D BluetoothAdapterState: Current state: OFF, message: 0
,09-07 14:59:10.033  4049  4061 D BluetoothAdapterProperties: Setting state to 14
09-07 14:59:10.034  4049  4061 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-07 14:59:10.038  4049  4061 D BluetoothBondStateMachine: make
,09-07 14:59:10.042  4049  4066 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-07 14:59:10.051  4049  4061 I BluetoothAdapterState: Entering PendingCommandState
,09-07 14:59:10.052  4049  4049 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-07 14:59:10.060  4049  4049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
,09-07 14:59:10.063  4049  4049 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 14:59:10.065  4049  4049 D BtGatt.GattService: Received start request. Starting profile...
,09-07 14:59:10.066  4049  4049 D BtGatt.GattService: start()
,09-07 14:59:10.066  4049  4049 I bt_bluedroid: get_profile_interface gatt
,09-07 14:59:10.069  4049  4049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
,09-07 14:59:10.069  4049  4049 D BtGatt.AdvertiseManager: advertise manager created
,09-07 14:59:10.085  4049  4049 V BluetoothAdapterState: isTurningOff()=false
,09-07 14:59:10.085  4049  4049 V BluetoothAdapterState: isTurningOn()=false
09-07 14:59:10.085  4049  4049 V BluetoothAdapterState: isBleTurningOn()=true
09-07 14:59:10.086  4049  4049 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 14:59:10.086  4049  4061 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-07 14:59:10.087  4049  4061 I bt_bluedroid: enable
09-07 14:59:10.087  4049  4062 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-07 14:59:10.088  4049  4062 I bt_hci  : start_up
,09-07 14:59:10.107  4049  4062 I bt_vendor: alloc value 0xb3a3d189
,09-07 14:59:10.107  4049  4062 I bt_vendor: init
09-07 14:59:10.107  4049  4062 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-07 14:59:10.108  4049  4062 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-07 14:59:10.217  4049  4062 D bt_hci  : start_up starting async portion
,09-07 14:59:10.218  4049  4069 I bt_hci  : event_finish_startup
09-07 14:59:10.218  4049  4069 I bt_hci_h4: hal_open
09-07 14:59:10.218  4049  4069 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-07 14:59:10.226  4049  4069 I bt_userial_vendor: device fd = 51 open
,09-07 14:59:10.258  4049  4069 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 14:59:10.290  4049  4069 D bt_hwcfg: Chipset BCM4354A2
09-07 14:59:10.290  4049  4069 D bt_hwcfg: Target name = [BCM4354A2]
,09-07 14:59:10.291  4049  4069 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-07 14:59:10.378   874  1305 D ConnectivityService: handlePromptUnvalidated 101
,09-07 14:59:10.950  4049  4069 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-07 14:59:10.952  4049  4069 D bt_hwcfg: Settlement delay -- 100 ms
,09-07 14:59:10.953  4049  4069 I bt_hwcfg: Setting fw settlement delay to 100 
,09-07 14:59:11.050   874  1688 I ActivityManager: Killing 3614:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,09-07 14:59:11.069  4049  4069 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 14:59:11.070  4049  4069 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-07 14:59:11.099  4049  4069 I bt_hwcfg: vendor lib fwcfg completed
,09-07 14:59:11.100  4049  4069 I bt_vendor: firmware callback
09-07 14:59:11.100  4049  4069 I bt_hci  : firmware_config_callback
,09-07 14:59:11.148  4049  4071 I bt_btu  : btu_task pending for preload complete event
,09-07 14:59:11.149  4049  4071 I bt_btu_task: Bluetooth chip preload is complete,
,09-07 14:59:11.149  4049  4071 I bt_btu  : btu_task received preload complete event
,09-07 14:59:11.156  4049  4071 I         : BTE_InitTraceLevels -- TRC_HCI
09-07 14:59:11.157  4049  4071 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 14:59:11.157  4049  4071 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-07 14:59:11.157  4049  4071 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-07 14:59:11.157  4049  4071 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 14:59:11.158  4049  4071 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 14:59:11.158  4049  4071 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 14:59:11.158  4049  4071 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 14:59:11.158  4049  4071 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 14:59:11.158  4049  4071 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 14:59:11.159  4049  4071 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 14:59:11.159  4049  4071 I         : BTE_InitTraceLevels -- TRC_GATT
,09-07 14:59:11.159  4049  4071 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 14:59:11.159  4049  4071 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 14:59:11.160  4049  4071 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 14:59:11.253   874  2017 I ActivityManager: Killing 3733:com.google.android.gms.unstable/u0a11 (adj 15): empty #17
,09-07 14:59:11.290  4049  4071 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39bad9d
,09-07 14:59:11.290  4049  4071 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39bad9d 
09-07 14:59:11.297  4049  4065 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-07 14:59:11.299  4049  4065 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-07 14:59:11.299  4049  4065 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 14:59:11.355  4049  4065 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 14:59:11.360  4049  4065 D BluetoothAdapterProperties: Scan Mode:20
,09-07 14:59:11.360  4049  4065 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 14:59:11.362  4049  4065 D bt_hci  : do_postload posting postload work item
,09-07 14:59:11.362  4049  4069 I bt_hci  : event_postload
09-07 14:59:11.362  4049  4069 I bt_vendor: sco_config_cb
09-07 14:59:11.362  4049  4069 I bt_hci  : sco_config_callback postload finished.
09-07 14:59:11.364  4049  4065 D bt_bte_conf: Device ID record 1 : primary
09-07 14:59:11.364  4049  4065 D bt_bte_conf:   vendorId            = 000f
09-07 14:59:11.364  4049  4065 D bt_bte_conf:   vendorIdSource      = 0001
,09-07 14:59:11.364  4049  4065 D bt_bte_conf:   product             = 1200
,09-07 14:59:11.364  4049  4065 D bt_bte_conf:   version             = 1436
,09-07 14:59:11.364  4049  4065 D bt_bte_conf:   clientExecutableURL = 
,09-07 14:59:11.364  4049  4065 D bt_bte_conf:   serviceDescription  = 
,09-07 14:59:11.365  4049  4065 D bt_bte_conf:   documentationURL    = 
09-07 14:59:11.365  4049  4065 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-07 14:59:11.365  4049  4062 D bt_stack_manager: event_start_up_stack finished
09-07 14:59:11.365  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:11.365  4049  4061 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-07 14:59:11.365  4049  4069 I bt_vendor: low_power_mode_cb
,09-07 14:59:11.366  4049  4061 D BluetoothAdapterProperties: Setting state to 15
09-07 14:59:11.366  4049  4061 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-07 14:59:11.366  4049  4061 I BluetoothAdapterState: Entering BleOnState
09-07 14:59:11.368  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:11.371  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:11.372  4049  4061 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-07 14:59:11.372  4049  4061 D BluetoothAdapterProperties: Setting state to 11
,09-07 14:59:11.372  4049  4061 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-07 14:59:11.384  4049  4049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
,09-07 14:59:11.386  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:11.388  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:11.388  4049  4049 D HeadsetService: Received start request. Starting profile...
,09-07 14:59:11.391  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 14:59:11.396  4049  4049 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-07 14:59:11.396  4049  4049 D HeadsetStateMachine: make
,09-07 14:59:11.402   874   887 I ActivityManager: Start proc 4078:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-07 14:59:11.407  4049  4049 D HeadsetStateMachine: max_hf_connections = 1
09-07 14:59:11.407  4049  4049 I bt_bluedroid: get_profile_interface handsfree
09-07 14:59:11.412  4049  4061 I BluetoothAdapterState: Entering PendingCommandState
,09-07 14:59:11.409  4049  4065 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-07 14:59:11.413  4049  4065 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-07 14:59:11.415  4049  4049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
,09-07 14:59:11.415  4049  4049 D A2dpService: Received start request. Starting profile...
09-07 14:59:11.416  4049  4049 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-07 14:59:11.416  4049  4049 I bt_bluedroid: get_profile_interface avrcp
,09-07 14:59:11.422  4049  4049 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-07 14:59:11.422  4049  4049 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 14:59:11.422  4049  4049 D A2dpStateMachine: make
,09-07 14:59:11.423  4049  4049 I bt_bluedroid: get_profile_interface a2dp
,09-07 14:59:11.424  4049  4065 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-07 14:59:11.425  4049  4092 D A2dpStateMachine: Enter Disconnected: -2
09-07 14:59:11.426  4049  4049 I BluetoothHidServiceJni: classInitNative: succeeds
09-07 14:59:11.427  4049  4049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
09-07 14:59:11.428  4049  4049 D HidService: Received start request. Starting profile...
,09-07 14:59:11.428  4049  4049 I bt_bluedroid: get_profile_interface hidhost
,09-07 14:59:11.428  4049  4049 D HidService: setHidService(): set to: null
09-07 14:59:11.428  4049  4065 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb399c3e5
09-07 14:59:11.428  4049  4065 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-07 14:59:11.428  4049  4049 I BluetoothHealthServiceJni: classInitNative: succeeds
09-07 14:59:11.429  4049  4049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
09-07 14:59:11.430  4049  4049 D HealthService: Received start request. Starting profile...
,09-07 14:59:11.431  4049  4049 I bt_bluedroid: get_profile_interface health
09-07 14:59:11.432  4049  4049 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-07 14:59:11.433  4049  4049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
09-07 14:59:11.433  4049  4049 D PanService: Received start request. Starting profile...
,09-07 14:59:11.433  4049  4049 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-07 14:59:11.433  4049  4049 I bt_bluedroid: get_profile_interface pan
,09-07 14:59:11.434  4049  4065 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-07 14:59:11.435  4049  4079 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 14:59:11.436  4049  4049 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
,09-07 14:59:11.437  4049  4049 D BluetoothMapService: Received start request. Starting profile...
09-07 14:59:11.437  4049  4049 D BluetoothMapService: start()
09-07 14:59:11.439  4049  4049 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER,
,09-07 14:59:11.439  4049  4049 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-07 14:59:11.439  4049  4049 D BluetoothMapAppObserver: createReceiver()
09-07 14:59:11.440  4049  4049 D BluetoothMapAppObserver: initObservers()
09-07 14:59:11.440  4049  4049 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-07 14:59:11.446  4049  4049 V BluetoothAdapterState: isTurningOff()=false
,09-07 14:59:11.446  4049  4049 V BluetoothAdapterState: isTurningOn()=true
09-07 14:59:11.446  4049  4049 V BluetoothAdapterState: isBleTurningOn()=false
09-07 14:59:11.446  4049  4049 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 14:59:11.448  4049  4049 V BluetoothAdapterState: isTurningOff()=false
,09-07 14:59:11.448  4049  4049 V BluetoothAdapterState: isTurningOn()=true
09-07 14:59:11.448  4049  4049 V BluetoothAdapterState: isBleTurningOn()=false
09-07 14:59:11.448  4049  4049 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 14:59:11.448  4049  4049 V BluetoothAdapterState: isTurningOff()=false
,09-07 14:59:11.448  4049  4049 V BluetoothAdapterState: isTurningOn()=true
,09-07 14:59:11.448  4049  4049 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 14:59:11.448  4049  4049 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 14:59:11.448  4049  4049 V BluetoothAdapterState: isTurningOff()=false
,09-07 14:59:11.448  4049  4049 V BluetoothAdapterState: isTurningOn()=true
09-07 14:59:11.448  4049  4049 V BluetoothAdapterState: isBleTurningOn()=false
09-07 14:59:11.448  4049  4049 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 14:59:11.449  4049  4049 V BluetoothAdapterState: isTurningOff()=false
09-07 14:59:11.449  4049  4049 V BluetoothAdapterState: isTurningOn()=true
09-07 14:59:11.449  4049  4049 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 14:59:11.449  4049  4049 V BluetoothAdapterState: isBleTurningOff()=false
09-07 14:59:11.449  4049  4049 V BluetoothAdapterState: isTurningOff()=false
,09-07 14:59:11.449  4049  4049 V BluetoothAdapterState: isTurningOn()=true
09-07 14:59:11.449  4049  4049 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 14:59:11.449  4049  4049 V BluetoothAdapterState: isBleTurningOff()=false
09-07 14:59:11.449  4049  4061 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-07 14:59:11.450  4049  4061 D BluetoothAdapterProperties: ScanMode =  20
09-07 14:59:11.450  4049  4061 D BluetoothAdapterProperties: State =  11
09-07 14:59:11.450  4049  4065 D BluetoothAdapterProperties: Scan Mode:21
09-07 14:59:11.451  4049  4065 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 14:59:11.451  4049  4061 D BluetoothAdapterProperties: Setting state to 12
09-07 14:59:11.451  4049  4061 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-07 14:59:11.451  1349  1361 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 14:59:11.452  4049  4061 I BluetoothAdapterState: Entering OnState
09-07 14:59:11.453  1349  2111 D BluetoothPan: onBluetoothStateChange on: true
09-07 14:59:11.454  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:11.454  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:11.454  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:11.454  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 14:59:11.454  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 14:59:11.454  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:59:11.454  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:59:11.454  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 14:59:11.455  1349  2112 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 14:59:11.455  4078  4078 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-07 14:59:11.456  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 14:59:11.456  1349  1349 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 14:59:11.456  1349  1349 D PanProfile: Bluetooth service connected
09-07 14:59:11.457  1349  2111 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 14:59:11.458  1349  1360 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 14:59:11.458  1349  1349 D BluetoothA2dp: Proxy object connected
,09-07 14:59:11.459  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:11.459  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:11.459  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:11.459  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 14:59:11.459  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 14:59:11.459  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:59:11.459  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:59:11.459  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 14:59:11.460  1349  1349 D BluetoothInputDevice: Proxy object connected
09-07 14:59:11.460  1349  1349 D HidProfile: Bluetooth service connected
09-07 14:59:11.461   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 14:59:11.461   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 14:59:11.461  1349  2111 D BluetoothMap: onBluetoothStateChange: up=true
09-07 14:59:11.461  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 14:59:11.463  1956  1968 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 14:59:11.464  1349  1349 D BluetoothMap: Proxy object connected
09-07 14:59:11.464  1349  1349 D MapProfile: Bluetooth service connected
09-07 14:59:11.464  1349  1349 D BluetoothMap: getConnectedDevices()
09-07 14:59:11.464   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 14:59:11.465   874   874 D BluetoothA2dp: Proxy object connected
09-07 14:59:11.466   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 14:59:11.466  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:11.466  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:11.466  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:11.466  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 14:59:11.466  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 14:59:11.466  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:59:11.466  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:59:11.466  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 14:59:11.466  4049  4049 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-07 14:59:11.467  4049  4049 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-07 14:59:11.467   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-07 14:59:11.468  4049  4049 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 14:59:11.469  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 14:59:11.470  4049  4049 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 14:59:11.470  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:11.471  4049  4049 D ObexServerSockets: Succeed to create listening sockets 
09-07 14:59:11.471  4049  4049 D ObexServerSockets0: startAccept()
09-07 14:59:11.471  4049  4049 D ObexServerSockets0: prepareForNewConnect()
09-07 14:59:11.472  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:11.473  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:11.473  4049  4049 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-07 14:59:11.473  4049  4049 D BluetoothSdpJni: SDP Create record success - handle: 0
09-07 14:59:11.474  4049  4099 D ObexServerSockets0: Accepting socket connection...
,09-07 14:59:11.474  4049  4049 D BluetoothMapService: onReceive
09-07 14:59:11.474  4049  4049 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 14:59:11.475  4049  4049 D BluetoothMapService: STATE_ON
09-07 14:59:11.475  4049  4100 D ObexServerSockets0: Accepting socket connection...
,09-07 14:59:11.487   874  1687 I ActivityManager: Killing 3695:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,09-07 14:59:11.495  4049  4049 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-07 14:59:11.495  4049  4049 D ObexServerSockets0: prepareForNewConnect()
,09-07 14:59:11.541  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 14:59:11.589   874  1688 I ActivityManager: Start proc 4101:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-07 14:59:11.592  1956  1966 D BluetoothHeadset: Proxy object connected
09-07 14:59:11.593   874   874 D BluetoothHeadset: Proxy object connected
,09-07 14:59:11.593  1349  2112 D BluetoothHeadset: Proxy object connected
,09-07 14:59:11.593   874   874 D BluetoothHeadset: Proxy object connected
09-07 14:59:11.593  1349  1349 D HeadsetProfile: Bluetooth service connected
,09-07 14:59:11.593   874   874 D BluetoothHeadset: Proxy object connected
,09-07 14:59:11.691  4101  4101 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-07 14:59:11.875  4101  4101 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 14:59:11.875  4101  4101 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 14:59:11.875  4101  4101 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 14:59:11.876  4101  4101 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 14:59:11.876  4101  4101 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.,a.a(PG:244)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 14:59:11.876  4101  4101 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityTh,read.java)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 14:59:11.876  4101  4101 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.r.k.d(PG:583)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 14:59:11.876  4101  4101 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 14:59:11.876  4101  4101 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 14:59:11.876  4101  4101 D StrictMode: StrictMode policy violation; ~duration=54 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 14:59:11.876  4101  4101 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 14:59:11.897  4078  4078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 14:59:11.910  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 14:59:11.917  3994  4026 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
09-07 14:59:11.919   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4b002df:true
09-07 14:59:11.928  4078  4078 D LocalBluetoothProfileManager: Adding local A2DP profile
09-07 14:59:11.938  1349  1349 D BluetoothPbap: Proxy object connected
09-07 14:59:11.938  1349  1349 D PbapServerProfile: Bluetooth service connected
09-07 14:59:11.938  4078  4078 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-07 14:59:11.956  4049  4130 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 14:59:11.962  4078  4078 D LocalBluetoothProfileManager: Adding local MAP profile
,09-07 14:59:11.963  4078  4078 D BluetoothMap: Create BluetoothMap proxy object
,09-07 14:59:11.972  4049  4134 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 14:59:11.974  4049  4134 I BtOppRfcommListener: Accept thread started.
,09-07 14:59:11.988  4078  4078 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-07 14:59:12.003  4078  4078 D DockEventReceiver: finishStartingService: stopping service
,09-07 14:59:12.004  4078  4078 D BluetoothA2dp: Proxy object connected
,09-07 14:59:12.009  4078  4078 D BluetoothInputDevice: Proxy object connected
,09-07 14:59:12.010  4078  4078 D HidProfile: Bluetooth service connected
,09-07 14:59:12.012  4078  4078 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 14:59:12.012  4078  4078 D PanProfile: Bluetooth service connected
09-07 14:59:12.012  4078  4078 D BluetoothMap: Proxy object connected
09-07 14:59:12.012  4078  4078 D MapProfile: Bluetooth service connected
09-07 14:59:12.012  4078  4078 D BluetoothMap: getConnectedDevices(),
,09-07 14:59:12.015  4078  4078 D BluetoothPbap: Proxy object connected
,09-07 14:59:12.015  4078  4078 D PbapServerProfile: Bluetooth service connected
,09-07 14:59:12.017   874  1380 I ActivityManager: Killing 3712:com.android.chrome/u0a40 (adj 15): empty #17
,09-07 14:59:12.043  4078  4090 D BluetoothHeadset: Proxy object connected
,09-07 14:59:12.044  4078  4078 D HeadsetProfile: Bluetooth service connected
,09-07 14:59:12.195  3982  4046 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-07 14:59:12.206  4101  4117 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-07 14:59:12.226   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c0a3b51:true
,09-07 14:59:14.785  1713  1713 V CheckinService: unknown intent received for checkin (Intent { flg=0x14 cmp=com.google.android.gms/.checkin.CheckinService$Receiver (has extras) })
,09-07 14:59:14.852  4049  4061 D BluetoothAdapterState: Current state: ON, message: 23
,09-07 14:59:14.852  4049  4061 D BluetoothAdapterProperties: Setting state to 13
09-07 14:59:14.852  4049  4061 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-07 14:59:14.856  4049  4061 D BluetoothAdapterProperties: onBluetoothDisable()
,09-07 14:59:14.857  4049  4065 D BluetoothAdapterProperties: Scan Mode:20
09-07 14:59:14.860  4049  4049 D BluetoothMapService: onReceive
09-07 14:59:14.860  4049  4049 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-07 14:59:14.860  4049  4049 D BluetoothMapService: STATE_TURNING_OFF
,09-07 14:59:14.860  4049  4049 D BluetoothMapService: MAP Service closeService in
09-07 14:59:14.861  4049  4049 D BluetoothMapMasInstance0: MAP Service shutdown
,09-07 14:59:14.861  4049  4049 D ObexServerSockets0: shutdown(block = true)
09-07 14:59:14.861  4049  4061 I BluetoothAdapterState: Entering PendingCommandState
09-07 14:59:14.861  4049  4061 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-07 14:59:14.861  4049  4049 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-07 14:59:14.862  4049  4099 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-07 14:59:14.862  4049  4049 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-07 14:59:14.862  4049  4100 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-07 14:59:14.862  4049  4073 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-07 14:59:14.863  4049  4049 I BtOppRfcommListener: stopping Accept Thread
09-07 14:59:14.863  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 14:59:14.863  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:14.863  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:14.863  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:14.863  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 14:59:14.863  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:59:14.863  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:59:14.863  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:59:14.863  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 14:59:14.863  4049  4134 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 14:59:14.864  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:59:14.864  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 14:59:14.864  4049  4134 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 14:59:14.866  4049  4049 D HeadsetService: Received stop request...Stopping profile...
,09-07 14:59:14.866  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:59:14.866  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:14.866  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:14.866  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:14.866  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 14:59:14.866  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:59:14.866  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:59:14.866  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:59:14.866  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 14:59:14.867  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 14:59:14.867  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 14:59:14.867  4078  4090 D BluetoothHeadset: Proxy object disconnected
09-07 14:59:14.868  1956  2121 D BluetoothHeadset: Proxy object disconnected
,09-07 14:59:14.868  4049  4049 D A2dpService: Received stop request...Stopping profile...
09-07 14:59:14.868  4049  4092 D A2dpStateMachine: Exit Disconnected: -1
09-07 14:59:14.868   874   874 D BluetoothHeadset: Proxy object disconnected
09-07 14:59:14.869  1349  1360 D BluetoothHeadset: Proxy object disconnected
09-07 14:59:14.869   874   874 D BluetoothHeadset: Proxy object disconnected
,09-07 14:59:14.869   874   874 D BluetoothHeadset: Proxy object disconnected
,09-07 14:59:14.869   874   874 D BluetoothA2dp: Proxy object disconnected
09-07 14:59:14.870  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:59:14.870  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:14.870  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:14.870  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:14.870  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 14:59:14.870  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 14:59:14.870  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:59:14.870  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:59:14.870  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 14:59:14.870  3465  3465 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 14:59:14.870  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 14:59:14.872  4049  4049 D HidService: Received stop request...Stopping profile...
09-07 14:59:14.872  4049  4049 D HidService: Stopping Bluetooth HidService
09-07 14:59:14.872  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:14.873  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:14.874  4049  4049 D HealthService: Received stop request...Stopping profile...
09-07 14:59:14.874  4049  4049 V BluetoothAdapterState: isTurningOff()=true
,09-07 14:59:14.874  4078  4078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 14:59:14.874  4049  4049 V BluetoothAdapterState: isTurningOn()=false
09-07 14:59:14.874  4049  4049 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 14:59:14.874  4049  4049 V BluetoothAdapterState: isBleTurningOff()=false
09-07 14:59:14.875  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:14.875  4049  4049 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-07 14:59:14.875  4049  4049 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 14:59:14.876  4049  4065 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-07 14:59:14.876  4049  4071 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 14:59:14.876  4049  4071 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 14:59:14.876  4049  4071 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 14:59:14.876  4049  4065 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-07 14:59:14.877  4049  4049 D PanService: Received stop request...Stopping profile...
09-07 14:59:14.879  4049  4049 D BluetoothMapService: Received stop request...Stopping profile...
09-07 14:59:14.879  4049  4049 D BluetoothMapService: stop()
09-07 14:59:14.880  4049  4049 D BluetoothMapAppObserver: deinitObservers()
09-07 14:59:14.880  4049  4049 D BluetoothMapAppObserver: removeReceiver()
09-07 14:59:14.881  4049  4049 V BluetoothAdapterState: isTurningOff()=true
09-07 14:59:14.881  4049  4049 V BluetoothAdapterState: isTurningOn()=false
09-07 14:59:14.881  1349  1349 D HeadsetProfile: Bluetooth service disconnected
,09-07 14:59:14.881  4049  4049 V BluetoothAdapterState: isBleTurningOn()=false
09-07 14:59:14.881  4049  4049 V BluetoothAdapterState: isBleTurningOff()=false
09-07 14:59:14.881  1349  1349 D BluetoothA2dp: Proxy object disconnected
09-07 14:59:14.881  1349  1349 D BluetoothInputDevice: Proxy object disconnected
,09-07 14:59:14.881  1349  1349 D HidProfile: Bluetooth service disconnected
09-07 14:59:14.881  1349  1349 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 14:59:14.881  1349  1349 D PanProfile: Bluetooth service disconnected
09-07 14:59:14.882  4049  4065 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-07 14:59:14.882  4049  4071 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 14:59:14.882  4049  4071 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 14:59:14.883  4049  4071 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 14:59:14.883  4049  4071 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 14:59:14.883  4049  4071 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 14:59:14.883  4049  4049 V BluetoothAdapterState: isTurningOff()=true
,09-07 14:59:14.883  4049  4071 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 14:59:14.883  4049  4049 V BluetoothAdapterState: isTurningOn()=false
09-07 14:59:14.883  4049  4049 V BluetoothAdapterState: isBleTurningOn()=false
09-07 14:59:14.883  4049  4049 V BluetoothAdapterState: isBleTurningOff()=false
09-07 14:59:14.883  4049  4049 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-07 14:59:14.883  4049  4065 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 14:59:14.883  4049  4049 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 14:59:14.883  4049  4049 V BluetoothAdapterState: isTurningOff()=true
09-07 14:59:14.883  1349  1349 D BluetoothMap: Proxy object disconnected
,09-07 14:59:14.884  4049  4049 V BluetoothAdapterState: isTurningOn()=false
09-07 14:59:14.884  1349  1349 D MapProfile: Bluetooth service disconnected
09-07 14:59:14.884  4049  4049 V BluetoothAdapterState: isBleTurningOn()=false
09-07 14:59:14.884  4049  4049 V BluetoothAdapterState: isBleTurningOff()=false
09-07 14:59:14.884  4049  4049 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 14:59:14.884  4049  4065 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-07 14:59:14.884  4049  4049 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 14:59:14.885  4049  4049 V BluetoothAdapterState: isTurningOff()=true
09-07 14:59:14.885  4049  4049 V BluetoothAdapterState: isTurningOn()=false
09-07 14:59:14.885  4049  4049 V BluetoothAdapterState: isBleTurningOn()=false
09-07 14:59:14.885  4049  4049 V BluetoothAdapterState: isBleTurningOff()=false
09-07 14:59:14.885  4078  4078 D HeadsetProfile: Bluetooth service disconnected
09-07 14:59:14.885  1713  4145 I CheckinService: Checking schedule, now: 1473253154885 next: 1473253145812
09-07 14:59:14.885  1713  4145 I CheckinService: active receiver: enabled
,09-07 14:59:14.885  4078  4078 D BluetoothA2dp: Proxy object disconnected
09-07 14:59:14.886  4049  4049 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 14:59:14.886  4049  4049 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 14:59:14.886  4078  4078 D BluetoothInputDevice: Proxy object disconnected
09-07 14:59:14.886  4078  4078 D HidProfile: Bluetooth service disconnected
,09-07 14:59:14.887  4049  4049 D BluetoothMapService: MAP Service closeService in
09-07 14:59:14.887  4049  4049 V BluetoothAdapterState: isTurningOff()=true
09-07 14:59:14.887  4049  4049 V BluetoothAdapterState: isTurningOn()=false
09-07 14:59:14.887  4049  4049 V BluetoothAdapterState: isBleTurningOn()=false
09-07 14:59:14.887  4049  4049 V BluetoothAdapterState: isBleTurningOff()=false
09-07 14:59:14.887  4049  4061 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-07 14:59:14.887  4049  4061 D BluetoothAdapterProperties: Setting state to 15
09-07 14:59:14.887  4049  4061 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-07 14:59:14.888  4049  4061 I BluetoothAdapterState: Entering BleOnState
,09-07 14:59:14.888  4078  4089 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 14:59:14.888  4049  4049 D BluetoothMapService: cleanup()
09-07 14:59:14.888  4049  4049 D BluetoothMapService: MAP Service closeService in
09-07 14:59:14.890  1349  1360 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 14:59:14.890  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 14:59:14.892  1349  2112 D BluetoothPan: onBluetoothStateChange on: false
09-07 14:59:14.894  1349  1361 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 14:59:14.895  4078  4089 D BluetoothPan: onBluetoothStateChange on: false
09-07 14:59:14.896  4078  4090 D BluetoothMap: onBluetoothStateChange: up=false
,09-07 14:59:14.897  1349  2111 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-07 14:59:14.897  1349  1360 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-07 14:59:14.897   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 14:59:14.898  4078  4089 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 14:59:14.898  4078  4090 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 14:59:14.898   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 14:59:14.898  1349  2112 D BluetoothMap: onBluetoothStateChange: up=false
09-07 14:59:14.899  1956  2124 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-07 14:59:14.901  4078  4089 D BluetoothPbap: onBluetoothStateChange: up=false,
09-07 14:59:14.906   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 14:59:14.906  4078  4078 D DockEventReceiver: finishStartingService: stopping service
09-07 14:59:14.906   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 14:59:14.906  4049  4061 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-07 14:59:14.907  4049  4061 D BluetoothAdapterProperties: Setting state to 16
,09-07 14:59:14.907  4049  4061 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-07 14:59:14.907  4049  4061 D BluetoothAdapterProperties: onBleDisable
09-07 14:59:14.907  4049  4061 I BluetoothAdapterState: Entering PendingCommandState
09-07 14:59:14.908  4049  4062 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-07 14:59:14.908  4049  4071 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-07 14:59:14.908  4049  4071 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 14:59:14.908  4049  4065 D BluetoothAdapterProperties: Scan Mode:20
,09-07 14:59:14.910  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 14:59:14.911  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:14.912  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:14.912  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 14:59:14.913  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 14:59:14.915  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:14.916  1500  2470 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-07 14:59:14.919  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 14:59:14.920  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 14:59:14.922  4078  4078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 14:59:14.925  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 14:59:14.929  4078  4078 D DockEventReceiver: finishStartingService: stopping service
,09-07 14:59:14.999  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:59:15.004  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:59:15.005  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:59:15.022  1500  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 14:59:15.022  1500  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 14:59:15.022  1500  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:59:15.022  1500  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:59:15.038  2722  2722 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 14:59:15.038  2722  2722 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-07 14:59:15.038  2722  2722 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-07 14:59:15.109  4049  4065 I bt_hci  : shut_down
,09-07 14:59:15.109  4049  4069 D bt_hwcfg: hw_epilog_process
,09-07 14:59:15.119  4049  4069 I bt_vendor: low_power_mode_cb
,09-07 14:59:15.142  4049  4069 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-07 14:59:15.143  4049  4069 I bt_vendor: epilog_cb
09-07 14:59:15.143  4049  4069 I bt_hci  : epilog_finished_callback
,09-07 14:59:15.147  4049  4065 I bt_hci_h4: hal_close
,09-07 14:59:15.148  4049  4065 I bt_userial_vendor: device fd = 51 close
,09-07 14:59:15.270  4049  4062 D bt_stack_manager: event_shut_down_stack finished.
,09-07 14:59:15.272  4049  4061 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-07 14:59:15.275  4049  4061 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-07 14:59:15.276  4049  4049 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 14:59:15.278  4049  4049 D BtGatt.GattService: Received stop request...Stopping profile...
,09-07 14:59:15.278  4049  4049 D BtGatt.GattService: stop()
,09-07 14:59:15.279  4049  4049 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 14:59:15.284  4049  4049 V BluetoothAdapterState: isTurningOff()=false
,09-07 14:59:15.284  4049  4049 V BluetoothAdapterState: isTurningOn()=false
09-07 14:59:15.284  4049  4049 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 14:59:15.285  4049  4049 V BluetoothAdapterState: isBleTurningOff()=true
09-07 14:59:15.286  4049  4061 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-07 14:59:15.286  4049  4061 D BluetoothAdapterProperties: Setting state to 10
,09-07 14:59:15.286  4049  4061 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-07 14:59:15.287  4049  4061 I BluetoothAdapterState: Entering OffState
,09-07 14:59:15.289   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-07 14:59:15.307  4049  4049 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-07 14:59:15.307  4049  4049 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-07 14:59:15.307  4049  4062 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-07 14:59:15.310  4049  4062 D bt_stack_manager: event_clean_up_stack finished.
09-07 14:59:15.311  4049  4049 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-07 14:59:15.313  4049  4049 I art     : System.exit called, status: 0
,09-07 14:59:15.313  4049  4049 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-07 14:59:15.377   874  2020 I ActivityManager: Process com.android.bluetooth (pid 4049) has died
,09-07 14:59:19.838  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 14:59:19.839  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:59:19.845  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 14:59:19.846  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aa439c2 removed from the list
,09-07 14:59:19.846  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 14:59:19.846  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:59:19.846  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:59:19.852  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 14:59:19.853  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cba7b10 added. We now have 4 listener(s)
09-07 14:59:19.853  3465  3516 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 14:59:19.855  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:59:19.855  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cba7b10 removed from the list
,09-07 14:59:19.855  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
09-07 14:59:19.856  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:59:19.856  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:59:19.859  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 14:59:19.859  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b457609 added. We now have 4 listener(s)
,09-07 14:59:19.859  3465  3516 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 14:59:24.870  3465  3516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 14:59:24.916   874   891 I ActivityManager: Start proc 4154:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-07 14:59:24.992   874  1294 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-07 14:59:25.046  4154  4154 D AdapterServiceConfig: Adding HeadsetService
,09-07 14:59:25.046  4154  4154 D AdapterServiceConfig: Adding A2dpService
,09-07 14:59:25.046  4154  4154 D AdapterServiceConfig: Adding HidService
,09-07 14:59:25.046  4154  4154 D AdapterServiceConfig: Adding HealthService
,09-07 14:59:25.046  4154  4154 D AdapterServiceConfig: Adding PanService
09-07 14:59:25.047  4154  4154 D AdapterServiceConfig: Adding GattService
09-07 14:59:25.047  4154  4154 D AdapterServiceConfig: Adding BluetoothMapService
,09-07 14:59:25.058  1713  4170 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,09-07 14:59:25.058   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@76a5a4e:true
09-07 14:59:25.058  4154  4154 D BluetoothAdapterState: make() - Creating AdapterState
,09-07 14:59:25.062  4154  4154 I bt_bluedroid: init
,09-07 14:59:25.062  4154  4173 I BluetoothAdapterState: Entering OffState
,09-07 14:59:25.063  4154  4175 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-07 14:59:25.063  4154  4175 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-07 14:59:25.063  4154  4175 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 14:59:25.064  4154  4175 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-07 14:59:25.064  4154  4154 I bt_bluedroid: get_profile_interface socket
,09-07 14:59:25.066  4154  4178 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-07 14:59:25.066  4154  4154 I bt_bluedroid: get_profile_interface sdp
,09-07 14:59:25.069  4154  4178 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 14:59:25.067  2053  4169 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,09-07 14:59:25.072  1713  4170 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,09-07 14:59:25.094  4154  4165 I bt_bluedroid: config_hci_snoop_log
09-07 14:59:25.095   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-07 14:59:25.095  1713  2337 I Icing   : updateResources: need to parse f{com.google.android.gms}
,09-07 14:59:25.099  4154  4173 D BluetoothAdapterState: Current state: OFF, message: 0
,09-07 14:59:25.099  4154  4173 D BluetoothAdapterProperties: Setting state to 14
09-07 14:59:25.099  4154  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-07 14:59:25.100  4154  4173 D BluetoothBondStateMachine: make
,09-07 14:59:25.102  4154  4179 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-07 14:59:25.105  4154  4154 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-07 14:59:25.107  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
,09-07 14:59:25.108  4154  4173 I BluetoothAdapterState: Entering PendingCommandState
,09-07 14:59:25.108  4154  4154 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 14:59:25.109  4154  4154 D BtGatt.GattService: Received start request. Starting profile...
09-07 14:59:25.109  4154  4154 D BtGatt.GattService: start()
09-07 14:59:25.109  4154  4154 I bt_bluedroid: get_profile_interface gatt
,09-07 14:59:25.109  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
09-07 14:59:25.109  4154  4154 D BtGatt.AdvertiseManager: advertise manager created
,09-07 14:59:25.115  4154  4154 V BluetoothAdapterState: isTurningOff()=false
,09-07 14:59:25.115  4154  4154 V BluetoothAdapterState: isTurningOn()=false
09-07 14:59:25.115  4154  4154 V BluetoothAdapterState: isBleTurningOn()=true
09-07 14:59:25.115  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
09-07 14:59:25.116  4154  4173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-07 14:59:25.116  4154  4173 I bt_bluedroid: enable
,09-07 14:59:25.116  4154  4175 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-07 14:59:25.116  4154  4175 I bt_hci  : start_up
,09-07 14:59:25.122  4154  4175 I bt_vendor: alloc value 0xb3a3d189
,09-07 14:59:25.123  4154  4175 I bt_vendor: init
09-07 14:59:25.123  4154  4175 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-07 14:59:25.123  4154  4175 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
09-07 14:59:25.124  2053  4169 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 53 ms] updated apps [took 53 ms] 
,09-07 14:59:25.139  1858  1858 V GmsNetworkLocationProvi: DISABLE
,09-07 14:59:25.151  1858  1858 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,09-07 14:59:25.227  4154  4175 D bt_hci  : start_up starting async portion
,09-07 14:59:25.228  4154  4183 I bt_hci  : event_finish_startup
09-07 14:59:25.228  4154  4183 I bt_hci_h4: hal_open
09-07 14:59:25.228  4154  4183 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0,
,09-07 14:59:25.234  4154  4183 I bt_userial_vendor: device fd = 51 open
,09-07 14:59:25.271  4154  4183 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 14:59:25.303  4154  4183 D bt_hwcfg: Chipset BCM4354A2
,09-07 14:59:25.304  4154  4183 D bt_hwcfg: Target name = [BCM4354A2],
,09-07 14:59:25.305  4154  4183 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-07 14:59:26.148  4154  4183 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-07 14:59:26.149  4154  4183 D bt_hwcfg: Settlement delay -- 100 ms
,09-07 14:59:26.150  4154  4183 I bt_hwcfg: Setting fw settlement delay to 100 
,09-07 14:59:26.267  4154  4183 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 14:59:26.269  4154  4183 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-07 14:59:26.296  4154  4183 I bt_hwcfg: vendor lib fwcfg completed
,09-07 14:59:26.297  4154  4183 I bt_vendor: firmware callback
09-07 14:59:26.297  4154  4183 I bt_hci  : firmware_config_callback
,09-07 14:59:26.309  4154  4186 I bt_btu  : btu_task pending for preload complete event
,09-07 14:59:26.309  4154  4186 I bt_btu_task: Bluetooth chip preload is complete
09-07 14:59:26.309  4154  4186 I bt_btu  : btu_task received preload complete event
,09-07 14:59:26.321  4154  4186 I         : BTE_InitTraceLevels -- TRC_HCI
,09-07 14:59:26.322  4154  4186 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 14:59:26.322  4154  4186 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-07 14:59:26.322  4154  4186 I         : BTE_InitTraceLevels -- TRC_AVDT
09-07 14:59:26.323  4154  4186 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-07 14:59:26.323  4154  4186 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 14:59:26.323  4154  4186 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 14:59:26.323  4154  4186 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 14:59:26.324  4154  4186 I         : BTE_InitTraceLevels -- TRC_GAP
,09-07 14:59:26.325  4154  4186 I         : BTE_InitTraceLevels -- TRC_PAN
,09-07 14:59:26.326  4154  4186 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 14:59:26.327  4154  4186 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 14:59:26.327  4154  4186 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 14:59:26.327  4154  4186 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 14:59:26.328  4154  4186 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 14:59:26.473  4154  4186 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39bad9d
09-07 14:59:26.473  4154  4186 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39bad9d 
,09-07 14:59:26.487  4154  4178 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
,09-07 14:59:26.489  4154  4178 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 14:59:26.490  4154  4178 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 14:59:26.497  4154  4178 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 14:59:26.501  4154  4178 D BluetoothAdapterProperties: Scan Mode:20
,09-07 14:59:26.501  4154  4178 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 14:59:26.502  4154  4178 D bt_hci  : do_postload posting postload work item
09-07 14:59:26.502  4154  4183 I bt_hci  : event_postload
,09-07 14:59:26.502  4154  4183 I bt_vendor: sco_config_cb
,09-07 14:59:26.503  4154  4183 I bt_hci  : sco_config_callback postload finished.
,09-07 14:59:26.508  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:26.510  4154  4178 D bt_bte_conf: Device ID record 1 : primary
09-07 14:59:26.510  4154  4178 D bt_bte_conf:   vendorId            = 000f
09-07 14:59:26.511  4154  4178 D bt_bte_conf:   vendorIdSource      = 0001
09-07 14:59:26.511  4154  4178 D bt_bte_conf:   product             = 1200
,09-07 14:59:26.511  4154  4183 I bt_vendor: low_power_mode_cb
09-07 14:59:26.511  4154  4178 D bt_bte_conf:   version             = 1436
09-07 14:59:26.511  4154  4178 D bt_bte_conf:   clientExecutableURL = 
09-07 14:59:26.512  4154  4178 D bt_bte_conf:   serviceDescription  = 
,09-07 14:59:26.512  4154  4178 D bt_bte_conf:   documentationURL    = 
09-07 14:59:26.512  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:26.512  4154  4178 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-07 14:59:26.512  4154  4175 D bt_stack_manager: event_start_up_stack finished
,09-07 14:59:26.513  4154  4173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-07 14:59:26.514  4154  4173 D BluetoothAdapterProperties: Setting state to 15
09-07 14:59:26.515  4154  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-07 14:59:26.516  4154  4173 I BluetoothAdapterState: Entering BleOnState
09-07 14:59:26.523  4154  4173 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-07 14:59:26.523  4154  4173 D BluetoothAdapterProperties: Setting state to 11
09-07 14:59:26.524  4154  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-07 14:59:26.534  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:26.536  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 14:59:26.538  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
,09-07 14:59:26.538  4154  4154 D HeadsetService: Received start request. Starting profile...
,09-07 14:59:26.546  4154  4154 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-07 14:59:26.546  4154  4154 D HeadsetStateMachine: make
,09-07 14:59:26.553  4154  4173 I BluetoothAdapterState: Entering PendingCommandState
,09-07 14:59:26.555  4154  4154 D HeadsetStateMachine: max_hf_connections = 1
,09-07 14:59:26.556  4154  4154 I bt_bluedroid: get_profile_interface handsfree
09-07 14:59:26.556  4154  4178 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-07 14:59:26.557  4154  4178 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-07 14:59:26.561  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
,09-07 14:59:26.561  4154  4154 D A2dpService: Received start request. Starting profile...
,09-07 14:59:26.562  4154  4154 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-07 14:59:26.563  4154  4154 I bt_bluedroid: get_profile_interface avrcp
,09-07 14:59:26.570  4154  4154 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-07 14:59:26.570  4154  4154 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 14:59:26.570  4154  4154 D A2dpStateMachine: make
09-07 14:59:26.571  4154  4154 I bt_bluedroid: get_profile_interface a2dp
,09-07 14:59:26.572  4154  4178 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-07 14:59:26.576  4154  4195 D A2dpStateMachine: Enter Disconnected: -2
,09-07 14:59:26.577  4154  4154 I BluetoothHidServiceJni: classInitNative: succeeds
,09-07 14:59:26.579  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
09-07 14:59:26.579  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 14:59:26.580  4154  4154 D HidService: Received start request. Starting profile...
09-07 14:59:26.580  4154  4154 I bt_bluedroid: get_profile_interface hidhost
,09-07 14:59:26.580  4154  4154 D HidService: setHidService(): set to: null
09-07 14:59:26.580  4154  4178 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb399c3e5
09-07 14:59:26.580  4154  4178 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-07 14:59:26.581  4154  4154 I BluetoothHealthServiceJni: classInitNative: succeeds
09-07 14:59:26.581  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
09-07 14:59:26.582  4154  4154 D HealthService: Received start request. Starting profile...
,09-07 14:59:26.585  4154  4154 I bt_bluedroid: get_profile_interface health
,09-07 14:59:26.586  4154  4154 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-07 14:59:26.587  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
,09-07 14:59:26.587  4154  4154 D PanService: Received start request. Starting profile...
09-07 14:59:26.587  4154  4154 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-07 14:59:26.587  4154  4154 I bt_bluedroid: get_profile_interface pan
,09-07 14:59:26.589  4154  4178 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-07 14:59:26.593  4154  4154 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
,09-07 14:59:26.595  4154  4154 D BluetoothMapService: Received start request. Starting profile...
,09-07 14:59:26.595  4154  4154 D BluetoothMapService: start()
,09-07 14:59:26.599  4154  4154 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-07 14:59:26.600  4154  4154 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-07 14:59:26.600  4154  4154 D BluetoothMapAppObserver: createReceiver()
,09-07 14:59:26.602  4154  4154 D BluetoothMapAppObserver: initObservers()
,09-07 14:59:26.602  4154  4154 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-07 14:59:26.613  4154  4154 V BluetoothAdapterState: isTurningOff()=false
,09-07 14:59:26.613  4154  4154 V BluetoothAdapterState: isTurningOn()=true
09-07 14:59:26.613  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
09-07 14:59:26.613  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 14:59:26.616  4154  4154 V BluetoothAdapterState: isTurningOff()=false
,09-07 14:59:26.616  4154  4154 V BluetoothAdapterState: isTurningOn()=true
09-07 14:59:26.616  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 14:59:26.616  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 14:59:26.616  4154  4154 V BluetoothAdapterState: isTurningOff()=false
09-07 14:59:26.616  4154  4193 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 14:59:26.616  4154  4154 V BluetoothAdapterState: isTurningOn()=true
09-07 14:59:26.616  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
09-07 14:59:26.616  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 14:59:26.617  4154  4154 V BluetoothAdapterState: isTurningOff()=false
,09-07 14:59:26.617  4154  4154 V BluetoothAdapterState: isTurningOn()=true
,09-07 14:59:26.617  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 14:59:26.617  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
09-07 14:59:26.617  4154  4154 V BluetoothAdapterState: isTurningOff()=false
09-07 14:59:26.617  4154  4154 V BluetoothAdapterState: isTurningOn()=true
,09-07 14:59:26.617  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
09-07 14:59:26.617  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
09-07 14:59:26.618  4154  4154 V BluetoothAdapterState: isTurningOff()=false
09-07 14:59:26.618  4154  4154 V BluetoothAdapterState: isTurningOn()=true
,09-07 14:59:26.618  4154  4154 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 14:59:26.618  4154  4154 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 14:59:26.619  4154  4173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-07 14:59:26.619  4154  4173 D BluetoothAdapterProperties: ScanMode =  20
09-07 14:59:26.619  4154  4173 D BluetoothAdapterProperties: State =  11
,09-07 14:59:26.623  4154  4178 D BluetoothAdapterProperties: Scan Mode:21
,09-07 14:59:26.623  4154  4178 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 14:59:26.624  4154  4173 D BluetoothAdapterProperties: Setting state to 12
09-07 14:59:26.624  4154  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-07 14:59:26.626  4078  4090 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 14:59:26.626  4154  4173 I BluetoothAdapterState: Entering OnState
,09-07 14:59:26.628  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:26.628  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:26.628  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:26.628  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 14:59:26.628  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 14:59:26.628  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:59:26.628  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:59:26.628  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 14:59:26.629  1349  1361 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 14:59:26.632  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 14:59:26.632  4078  4078 D BluetoothInputDevice: Proxy object connected
09-07 14:59:26.632  4078  4078 D HidProfile: Bluetooth service connected
,09-07 14:59:26.633  1349  1360 D BluetoothPan: onBluetoothStateChange on: true
09-07 14:59:26.636  4154  4154 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-07 14:59:26.637  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:26.637  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:26.637  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:26.637  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 14:59:26.637  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 14:59:26.637  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:59:26.637  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:59:26.637  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 14:59:26.637  1349  2112 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 14:59:26.638  4154  4154 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-07 14:59:26.640  4154  4154 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 14:59:26.640  4078  4089 D BluetoothPan: onBluetoothStateChange on: true
,09-07 14:59:26.642  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 14:59:26.643  4078  4090 D BluetoothMap: onBluetoothStateChange: up=true
,09-07 14:59:26.644  4154  4154 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 14:59:26.646  1349  2111 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 14:59:26.647  4154  4154 D ObexServerSockets: Succeed to create listening sockets 
,09-07 14:59:26.648  4154  4154 D ObexServerSockets0: startAccept()
09-07 14:59:26.648  4154  4154 D ObexServerSockets0: prepareForNewConnect()
,09-07 14:59:26.648  1349  1361 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-07 14:59:26.650   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 14:59:26.650  4154  4154 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-07 14:59:26.650  1349  1349 D BluetoothInputDevice: Proxy object connected
,09-07 14:59:26.650  1349  1349 D HidProfile: Bluetooth service connected
09-07 14:59:26.650  4154  4154 D BluetoothSdpJni: SDP Create record success - handle: 0
09-07 14:59:26.651  4078  4148 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 14:59:26.653  4078  4090 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 14:59:26.654   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 14:59:26.654  1349  1361 D BluetoothMap: onBluetoothStateChange: up=true
09-07 14:59:26.655  1349  1349 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 14:59:26.655  1349  1349 D PanProfile: Bluetooth service connected
09-07 14:59:26.656  1349  1349 D BluetoothA2dp: Proxy object connected
,09-07 14:59:26.657  1956  2121 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 14:59:26.657  4078  4089 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 14:59:26.659   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 14:59:26.659   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 14:59:26.660  1349  1349 D BluetoothMap: Proxy object connected
09-07 14:59:26.660  1349  1349 D MapProfile: Bluetooth service connected
09-07 14:59:26.660  1349  1349 D BluetoothMap: getConnectedDevices()
09-07 14:59:26.660   874   874 D BluetoothA2dp: Proxy object connected
09-07 14:59:26.663  4078  4078 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 14:59:26.663  4078  4078 D PanProfile: Bluetooth service connected
09-07 14:59:26.663  4078  4078 D BluetoothA2dp: Proxy object connected
09-07 14:59:26.664   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-07 14:59:26.665  4154  4202 D ObexServerSockets0: Accepting socket connection...
09-07 14:59:26.665  4078  4078 D BluetoothMap: Proxy object connected
09-07 14:59:26.665  4078  4078 D MapProfile: Bluetooth service connected
09-07 14:59:26.665  4154  4154 D BluetoothMapService: onReceive
09-07 14:59:26.665  4078  4078 D BluetoothMap: getConnectedDevices()
09-07 14:59:26.665  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:26.665  4154  4154 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 14:59:26.665  4154  4154 D BluetoothMapService: STATE_ON
09-07 14:59:26.665  4154  4201 D ObexServerSockets0: Accepting socket connection...
09-07 14:59:26.667  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 14:59:26.671  4078  4078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 14:59:26.678  4078  4078 D DockEventReceiver: finishStartingService: stopping service
,09-07 14:59:26.678  1500  1500 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 14:59:26.686  4078  4078 D BluetoothPbap: Proxy object connected
,09-07 14:59:26.686  4078  4078 D PbapServerProfile: Bluetooth service connected
,09-07 14:59:26.689  4154  4206 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 14:59:26.692  1349  1349 D BluetoothPbap: Proxy object connected
,09-07 14:59:26.692  1349  1349 D PbapServerProfile: Bluetooth service connected
,09-07 14:59:26.698  4154  4154 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-07 14:59:26.698  4154  4154 D ObexServerSockets0: prepareForNewConnect()
,09-07 14:59:26.729  4154  4212 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 14:59:26.730  4154  4212 I BtOppRfcommListener: Accept thread started.
,09-07 14:59:26.751   874   891 W BluetoothManagerService: Unable to bind with intent: Intent { act=android.bluetooth.IBluetoothHeadset cmp=com.android.bluetooth/.hfp.HeadsetService }
09-07 14:59:26.753  4078  4090 D BluetoothHeadset: Proxy object connected
09-07 14:59:26.754  4078  4078 D HeadsetProfile: Bluetooth service connected
,09-07 14:59:26.757  1956  2124 D BluetoothHeadset: Proxy object connected
09-07 14:59:26.758  4078  4148 D BluetoothHeadset: Proxy object connected
09-07 14:59:26.758   874   891 D BluetoothHeadset: Proxy object connected
09-07 14:59:26.761  1956  1968 D BluetoothHeadset: Proxy object connected
09-07 14:59:26.761   874   874 D BluetoothHeadset: Proxy object connected
09-07 14:59:26.761   874   891 D BluetoothHeadset: Proxy object connected
09-07 14:59:26.761  1349  2111 D BluetoothHeadset: Proxy object connected
,09-07 14:59:26.761   874   874 D BluetoothHeadset: Proxy object connected
,09-07 14:59:26.762   874   874 D BluetoothHeadset: Proxy object connected
09-07 14:59:26.761  1349  1349 D HeadsetProfile: Bluetooth service connected
09-07 14:59:26.764  4078  4078 D HeadsetProfile: Bluetooth service connected
,09-07 14:59:29.892  3465  3516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:29.892  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:29.892  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:29.892  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 14:59:29.892  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 14:59:29.892  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:59:29.892  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:59:29.892  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 14:59:29.899  3465  3516 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 14:59:29.899  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 14:59:29.900  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b457609 removed from the list
09-07 14:59:29.900  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 14:59:29.901  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:59:29.901  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:59:29.903  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 14:59:29.904  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a80300e added. We now have 4 listener(s)
,09-07 14:59:29.904  3465  3516 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 14:59:29.908   874  2013 D WifiService: setWifiEnabled: false pid=3465, uid=10000
,09-07 14:59:29.909   874  2013 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 14:59:34.924  3465  3516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 14:59:34.925   874  1978 D WifiService: setWifiEnabled: true pid=3465, uid=10000
,09-07 14:59:34.926   874  1978 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 14:59:34.939   874  1303 D WifiConfigStore: Loading config and enabling all networks 
,09-07 14:59:34.959  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:34.959  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:34.959  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:34.959  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:59:34.959  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 14:59:34.959  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:59:34.959  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:59:34.959  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 14:59:34.966  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 14:59:34.971   874  1303 D WifiConfigStore: loaded 0 passpoint configs
,09-07 14:59:34.972   874  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-07 14:59:34.972   874  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-07 14:59:34.973   874  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-07 14:59:34.973   874  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-07 14:59:34.974   874  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-07 14:59:34.974   874  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-07 14:59:34.976  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:34.976  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:34.976  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:34.976  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:59:34.976  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 14:59:34.976  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:59:34.976  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:59:34.976  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 14:59:34.979  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 14:59:34.988   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-07 14:59:34.989   874  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-07 14:59:34.990   373   872 D CommandListener: Setting iface cfg
,09-07 14:59:35.041   874  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-07 14:59:35.041   874  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-07 14:59:35.047   874  1303 E native  : do suspend true
,09-07 14:59:35.048   874  1302 D WifiNative-HAL: p2pGetDeviceAddress
09-07 14:59:35.049   874  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-07 14:59:35.068   874  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 14:59:35.429  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:59:35.437  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:59:35.439  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:59:35.465  1500  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 14:59:35.465  1500  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 14:59:35.465  1500  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:59:35.465  1500  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:59:35.495  2722  2722 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-07 14:59:35.495  2722  2722 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 14:59:35.495  2722  2722 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-07 14:59:36.341   874  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 14:59:36.478   874  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=1.25 rxSuccessRate=0.75 delta 1000 -> 1000
,09-07 14:59:36.480   874  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-07 14:59:36.480   874  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 14:59:36.494   874  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-07 14:59:36.558   874  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-07 14:59:36.563  1457  1457 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 14:59:36.998  1457  1457 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 14:59:38.069  1457  1457 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 14:59:38.070  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-07 14:59:38.081   874  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 14:59:38.096   874  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 14:59:38.097   874  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 14:59:38.097   874  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-07 14:59:38.113   874  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 14:59:38.122   373   872 D CommandListener: Setting iface cfg
,09-07 14:59:38.125   874  1303 D WifiStateMachine: Start Dhcp Watchdog 3
,09-07 14:59:38.132   874  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-07 14:59:38.157   874  4220 D DhcpClient: Receive thread started
,09-07 14:59:38.245   874  1303 E native  : do suspend false
,09-07 14:59:38.266   874  3650 D DhcpClient: Broadcasting DHCPDISCOVER
,09-07 14:59:38.283   874  4220 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172763, domain null
,09-07 14:59:38.285   874  3650 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172763 seconds
,09-07 14:59:38.288   874  3650 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-07 14:59:38.329   874  4220 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-07 14:59:38.330   874  3650 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-07 14:59:38.335   373   872 D CommandListener: Setting iface cfg
,09-07 14:59:38.345   874  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-07 14:59:38.347   874  3650 D DhcpClient: Scheduling renewal in 86399s
,09-07 14:59:38.348   874  1303 E native  : do suspend true
,09-07 14:59:38.370   874  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-07 14:59:38.373   874  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,09-07 14:59:38.374   874  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-07 14:59:38.376   874  1305 D ConnectivityService: Adding iface wlan0 to network 102
,09-07 14:59:38.384   874  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 14:59:38.447   874  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-07 14:59:38.447   874  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-07 14:59:38.448   874  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-07 14:59:38.450   874  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-07 14:59:38.452   874  1305 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-07 14:59:38.463   874  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-07 14:59:38.470   874  1305 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-07 14:59:38.470   874  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-07 14:59:38.470   874  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-07 14:59:38.470   874  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-07 14:59:38.470   874  1305 D ConnectivityService:    accepting network in place of null
09-07 14:59:38.471   874  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 14:59:38.471   874  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 14:59:38.516   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 14:59:38.557   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 14:59:38.563   874  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-07 14:59:38.563   874  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-07 14:59:38.565   874  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-07 14:59:38.571   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-07 14:59:38.592  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:38.592  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:38.592  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:38.592  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:59:38.592  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 14:59:38.592  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 14:59:38.592  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 14:59:38.592  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 14:59:38.595  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 14:59:38.598  2053  2053 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-07 14:59:38.600  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:38.600  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:38.600  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:38.600  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:59:38.600  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 14:59:38.600  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 14:59:38.600  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 14:59:38.600  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 14:59:38.602  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 14:59:38.619  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 14:59:38.622  1713  1713 D SystemUpdateService: onCreate
,09-07 14:59:38.625  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 14:59:38.648  1713  4232 I SystemUpdateService: active receiver: enabled
,09-07 14:59:38.672  3550  4233 V GoogleAuthProtoRequest: [283] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 14:59:38.676  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-07 14:59:38.679  1713  3687 I iu.UploadsManager: num queued entries: 0
09-07 14:59:38.679  1713  3687 I iu.UploadsManager: num updated entries: 0
09-07 14:59:38.680  1713  3687 I iu.SyncManager: NEXT; no task
,09-07 14:59:38.685  1713  4231 I CheckinService: Checking schedule, now: 1473253178685 next: 1473253145812
,09-07 14:59:38.685  1713  4231 I CheckinService: active receiver: enabled
,09-07 14:59:38.690  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 14:59:38.691  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 14:59:38.692  1713  4232 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 14:59:38.696  1713  4231 I CheckinService: Preparing to send checkin request
,09-07 14:59:38.696  1713  4231 I EventLogService: Accumulating logs since 1473253132185
,09-07 14:59:38.701  1713  4232 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-07 14:59:38.701  1713  4232 I SystemUpdateService: now status is 0 (complete)
09-07 14:59:38.701  1713  4232 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 14:59:38.702  1713  4232 I SystemUpdateService: file has been verified
09-07 14:59:38.702  1713  4232 I SystemUpdateService: OTA package size = 12249756
,09-07 14:59:38.704   874  2017 I ActivityManager: Start proc 4238:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-07 14:59:38.718  1713  4235 I MDM     : [195] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-07 14:59:38.718  1713  4235 W BaseAppContext: Using Auth Proxy for data requests.
,09-07 14:59:38.721  1713  4231 I EventLogService: Opted in for usage reporting
,09-07 14:59:38.722  1713  4235 V GoogleAuthProtoRequest: [195] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 14:59:38.740  1713  4232 I SystemUpdateService: showing system update notification,
,09-07 14:59:38.761  1500  3725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,09-07 14:59:38.761  1500  3725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
09-07 14:59:38.761  1500  3725 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:59:38.761  1500  3725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:59:38.765  4238  4238 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-07 14:59:38.769  4238  4238 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 14:59:38.775  4238  4238 D SprintDMHelper: simOperator: 
,09-07 14:59:38.776  4238  4238 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 14:59:38.781  1713  4231 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,09-07 14:59:38.797   874   886 I ActivityManager: Start proc 4251:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,09-07 14:59:38.813   874  1971 I ActivityManager: Start proc 4263:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-07 14:59:38.816  1713  4231 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,09-07 14:59:38.820  1713  1713 D SystemUpdateService: onDestroy
09-07 14:59:38.829  4251  4251 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,09-07 14:59:38.855  1500  3723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-07 14:59:38.855  1500  3723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-07 14:59:38.855  1500  3723 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:59:38.855  1500  3723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:59:38.862  3550  4233 W ExperimentUpdateService: [283] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,09-07 14:59:38.863  3550  4233 W ExperimentUpdateService: [283] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 14:59:38.863  3550  4233 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 14:59:38.863  3550  4233 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-07 14:59:38.863  3550  4233 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
09-07 14:59:38.863  3550  4233 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-07 14:59:38.863  3550  4233 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-07 14:59:38.863  3550  4233 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-07 14:59:38.863  3550  4233 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-07 14:59:38.863  3550  4233 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
09-07 14:59:38.863  3550  4233 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-07 14:59:38.863  3550  4233 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,09-07 14:59:38.871  1713  4235 E MDM     : [195] SitrepService.a: Error sending sitrep.,
,09-07 14:59:38.894  4251  4251 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-07 14:59:38.900  4251  4251 I BooksApp: Created application version: 3.6.9 (30609)
,09-07 14:59:39.022  1500  3726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 14:59:39.022  1500  3726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 14:59:39.022  1500  3726 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:59:39.022  1500  3726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:59:39.038  3269  4278 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-07 14:59:39.038  3269  4278 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 14:59:39.038  3269  4278 E HttpOperation: 	at jdm.a(PG:82)
09-07 14:59:39.038  3269  4278 E HttpOperation: 	at jcs.o(PG:406)
09-07 14:59:39.038  3269  4278 E HttpOperation: 	at jcn.a(PG:1379)
09-07 14:59:39.038  3269  4278 E HttpOperation: 	at jcs.i(PG:143)
09-07 14:59:39.038  3269  4278 E HttpOperation: 	at blb.a(PG:3937)
09-07 14:59:39.038  3269  4278 E HttpOperation: 	at czp.a(PG:18188)
09-07 14:59:39.038  3269  4278 E HttpOperation: 	at czp.a(PG:9087)
09-07 14:59:39.038  3269  4278 E HttpOperation: 	at czq.run(PG:1686)
09-07 14:59:39.038  3269  4278 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 14:59:39.038  3269  4278 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 14:59:39.038  3269  4278 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 14:59:39.038  3269  4278 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 14:59:39.038  3269  4278 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 14:59:39.038  3269  4278 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 14:59:39.038  3269  4278 E HttpOperation: 	at jdj.a(PG:4091)
09-07 14:59:39.038  3269  4278 E HttpOperation: 	at jdj.a(PG:1125)
09-07 14:59:39.038  3269  4278 E HttpOperation: 	at jdm.a(PG:77)
09-07 14:59:39.038  3269  4278 E HttpOperation: 	... 12 more
09-07 14:59:39.038  3269  4278 E HttpOperation: Caused by: faj: BadAuthentication
09-07 14:59:39.038  3269  4278 E HttpOperation: 	at fal.a(PG:38)
09-07 14:59:39.038  3269  4278 E HttpOperation: 	at jdj.a(PG:4089)
09-07 14:59:39.038  3269  4278 E HttpOperation: 	... 14 more
,09-07 14:59:39.249  4251  4283 I BooksSync: Starting books sync for 61035162, extras: ade
,09-07 14:59:39.264  1500  4287 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-07 14:59:39.285  1500  4287 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-07 14:59:39.308  1500  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 14:59:39.308  1500  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 14:59:39.308  1500  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:59:39.309  1500  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:59:39.331  3269  4295 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-07 14:59:39.331  3269  4295 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 14:59:39.331  3269  4295 E HttpOperation: 	at jdm.a(PG:82)
09-07 14:59:39.331  3269  4295 E HttpOperation: 	at jcs.o(PG:406)
09-07 14:59:39.331  3269  4295 E HttpOperation: 	at jcn.a(PG:1379)
09-07 14:59:39.331  3269  4295 E HttpOperation: 	at jcs.i(PG:143)
09-07 14:59:39.331  3269  4295 E HttpOperation: 	at blb.a(PG:3937)
09-07 14:59:39.331  3269  4295 E HttpOperation: 	at czp.a(PG:18188)
09-07 14:59:39.331  3269  4295 E HttpOperation: 	at czp.a(PG:9081)
09-07 14:59:39.331  3269  4295 E HttpOperation: 	at czq.run(PG:1686)
09-07 14:59:39.331  3269  4295 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 14:59:39.331  3269  4295 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 14:59:39.331  3269  4295 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 14:59:39.331  3269  4295 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 14:59:39.331  3269  4295 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 14:59:39.331  3269  4295 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 14:59:39.331  3269  4295 E HttpOperation: 	at jdj.a(PG:4091)
09-07 14:59:39.331  3269  4295 E HttpOperation: 	at jdj.a(PG:1125)
09-07 14:59:39.331  3269  4295 E HttpOperation: 	at jdm.a(PG:77)
09-07 14:59:39.331  3269  4295 E HttpOperation: 	... 12 more
09-07 14:59:39.331  3269  4295 E HttpOperation: Caused by: faj: BadAuthentication
09-07 14:59:39.331  3269  4295 E HttpOperation: 	at fal.a(PG:38)
09-07 14:59:39.331  3269  4295 E HttpOperation: 	at jdj.a(PG:4089)
09-07 14:59:39.331  3269  4295 E HttpOperation: 	... 14 more
,09-07 14:59:39.379  1500  2048 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 14:59:39.379  1500  2048 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 14:59:39.379  1500  2048 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:59:39.379  1500  2048 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:59:39.430  3269  4295 E HttpOperation: [getmobileexperiments] Unexpected exception
09-07 14:59:39.430  3269  4295 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 14:59:39.430  3269  4295 E HttpOperation: 	at jdm.a(PG:82)
09-07 14:59:39.430  3269  4295 E HttpOperation: 	at jcs.o(PG:406)
09-07 14:59:39.430  3269  4295 E HttpOperation: 	at jcn.a(PG:1379)
09-07 14:59:39.430  3269  4295 E HttpOperation: 	at jcs.i(PG:143)
09-07 14:59:39.430  3269  4295 E HttpOperation: 	at hec.a(PG:42)
09-07 14:59:39.430  3269  4295 E HttpOperation: 	at hee.a(PG:102)
09-07 14:59:39.430  3269  4295 E HttpOperation: 	at czr.a(PG:65)
09-07 14:59:39.430  3269  4295 E HttpOperation: 	at kka.a(PG:108)
09-07 14:59:39.430  3269  4295 E HttpOperation: 	at czp.a(PG:19176)
09-07 14:59:39.430  3269  4295 E HttpOperation: 	,at czp.a(PG:9081)
09-07 14:59:39.430  3269  4295 E HttpOperation: ,	at czq.run(PG:1686)
09-07 14:59:39.430  3269  4295 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 14:59:39.430  3269  4295 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 14:59:39.430  3269  4295 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 14:59:39.430  3269  4295 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 14:59:39.430  3269  4295 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 14:59:39.430  3269  4295 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 14:59:39.430  3269  4295 E HttpOperation: 	at jdj.a(PG:4091)
09-07 14:59:39.430  3269  4295 E HttpOperation: 	at jdj.a(PG:1125)
09-07 14:59:39.430  3269  4295 E HttpOperation: 	at jdm.a(PG:77)
09-07 14:59:39.430  3269  4295 E HttpOperation: 	... 15 more
09-07 14:59:39.430  3269  4295 E HttpOperation: Caused by: faj: BadAuthentication
09-07 14:59:39.430  3269  4295 E HttpOperation: 	at fal.a(PG:38)
09-07 14:59:39.430  3269  4295 E HttpOperation: 	at jdj.a(PG:4089)
09-07 14:59:39.430  3269  4295 E HttpOperation: 	... 17 more
,09-07 14:59:39.431  3269  4295 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-07 14:59:39.431  3269  4295 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-07 14:59:39.431  3269  4295 E ExperimentLoader: 	at jdm.a(PG:82)
09-07 14:59:39.431  3269  4295 E ExperimentLoader: 	at jcs.o(PG:406)
09-07 14:59:39.431  3269  4295 E ExperimentLoader: 	at jcn.a(PG:1379)
09-07 14:59:39.431  3269  4295 E ExperimentLoader: 	at jcs.i(PG:143)
09-07 14:59:39.431  3269  4295 E ExperimentLoader: 	at hec.a(PG:42)
09-07 14:59:39.431  3269  4295 E ExperimentLoader: 	at hee.a(PG:102)
09-07 14:59:39.431  3269  4295 E ExperimentLoader: 	at czr.a(PG:65)
09-07 14:59:39.431  3269  4295 E ExperimentLoader: 	at kka.a(PG:108)
09-07 14:59:39.431  3269  4295 E ExperimentLoader: 	at czp.a(PG:19176)
09-07 14:59:39.431  3269  4295 E ExperimentLoader: 	at czp.a(PG:9081)
09-07 14:59:39.431  3269  4295 E ExperimentLoader: 	at czq.run(PG:1686)
09-07 14:59:39.431  3269  4295 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 14:59:39.431  3269  4295 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 14:59:39.431  3269  4295 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 14:59:39.431  3269  4295 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 14:59:39.431  3269  4295 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-07 14:59:39.431  3269  4295 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 14:59:39.431  3269  4295 E ExperimentLoader: 	at jdj.a(PG:4091)
09-07 14:59:39.431  3269  4295 E ExperimentLoader: 	at jdj.a(PG:1125)
09-07 14:59:39.431  3269  4295 E ExperimentLoader: 	at jdm.a(PG:77)
09-07 14:59:39.431  3269  4295 E ExperimentLoader: 	... 15 more
09-07 14:59:39.431  3269  4295 E ExperimentLoader: Caused by: faj: BadAuthentication
09-07 14:59:39.431  3269  4295 E ExperimentLoader: 	at fal.a(PG:38)
09-07 14:59:39.431  3269  4295 E ExperimentLoader: 	at jdj.a(PG:4089)
09-07 14:59:39.431  3269  4295 E ExperimentLoader: 	... 17 more
,09-07 14:59:39.562   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 159613, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-07 14:59:39.564   874  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-07 14:59:39.641  1500  2367 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,09-07 14:59:39.641  1500  2367 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> AndroidCheckInServer without consulting the cloud.
09-07 14:59:39.641  1500  2367 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:59:39.641  1500  2367 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:59:39.692  4251  4303 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-07 14:59:39.719  1713  4231 W CheckinRequestBuilder: awaiting user notification for token
,09-07 14:59:39.754  1500  2403 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 14:59:39.754  1500  2403 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-07 14:59:39.754  1500  2403 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:59:39.755  1500  2403 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-07 14:59:39.756  3037  4300 V KeepSync: Connecting to GoogleApiClient
09-07 14:59:39.756   874   884 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-07 14:59:39.821   874  1991 I ActivityManager: Start proc 4304:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,09-07 14:59:39.860  1500  2367 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 14:59:39.861  1500  2367 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 14:59:39.862  1500  2367 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:59:39.862  1500  2367 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:59:39.879  4251  4303 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-07 14:59:39.884  4251  4283 E BooksSync: Soft error
09-07 14:59:39.884  4251  4283 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 14:59:39.884  4251  4283 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-07 14:59:39.884  4251  4283 E BooksSync: Sync error
09-07 14:59:39.884  4251  4283 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 14:59:39.884  4251  4283 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-07 14:59:39.884  4251  4283 I BooksSync: Finished books sync
,09-07 14:59:39.901   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 192700, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 14:59:39.916  1500  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-07 14:59:39.916  1500  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-07 14:59:39.916  1500  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:59:39.916  1500  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:59:39.931  1713  4314 V BaseAuthAsyncOperation: access token request failed
,09-07 14:59:39.932  3037  4300 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-07 14:59:39.941  4304  4304 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,09-07 14:59:39.942  3465  3516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:39.942  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:39.942  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:39.942  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:59:39.942  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 14:59:39.942  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 14:59:39.942  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 14:59:39.942  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 14:59:39.945  3465  3516 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 14:59:39.946  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:59:39.946  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a80300e removed from the list
09-07 14:59:39.946  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
09-07 14:59:39.946  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:59:39.946  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:59:39.953  3465  4317 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-07 14:59:39.953  3465  4317 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-07 14:59:39.958  4304  4304 I MultiDex: VM with version 2.1.0 has multidex support
,09-07 14:59:39.958  4304  4304 I MultiDex: install
09-07 14:59:39.958  4304  4304 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-07 14:59:40.017  4304  4304 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,09-07 14:59:40.058  4304  4304 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-07 14:59:40.088  1500  1500 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-07 14:59:40.088  1500  2775 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-07 14:59:40.110  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:59:40.113  1713  1713 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,09-07 14:59:40.146  2082  2082 D WearableService: callingUid 10011, callindPid: 2082
,09-07 14:59:40.161  1858  2090 E MDM     : [72] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-07 14:59:40.245  4304  4315 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-07 14:59:40.251   377  1275 D WVCdm   : Instantiating CDM.
,09-07 14:59:40.252   377   377 I WVCdm   : CdmEngine::OpenSession
09-07 14:59:40.252   377   377 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,09-07 14:59:40.255   377   377 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-07 14:59:40.256   377   377 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x20
,09-07 14:59:40.256   377   377 D DrmWidevineDash: Service_Initialize: starts!
09-07 14:59:40.256   377   377 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-07 14:59:40.257   377   377 D QSEECOMAPI: : App is not loaded in QSEE
,09-07 14:59:40.319  1713  4323 D LocationInitializer: Restart initialization of location
,09-07 14:59:40.330  4304  4320 D NativeLibraryUtils: Install completed successfully. count=13 extracted=0
,09-07 14:59:40.376  1858  2040 W GCoreFlp: No location to return for getLastLocation()
,09-07 14:59:40.377  1500  4327 W FusedLocationProvider: location=null
,09-07 14:59:40.382  1500  2367 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-07 14:59:40.382  1500  2367 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-07 14:59:40.382  1500  2367 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 14:59:40.383  1500  2367 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:59:40.415  3037  4300 E KeepSync: IOException
09-07 14:59:40.415  3037  4300 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-07 14:59:40.415  3037  4300 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-07 14:59:40.415  3037  4300 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-07 14:59:40.415  3037  4300 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-07 14:59:40.415  3037  4300 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-07 14:59:40.415  3037  4300 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-07 14:59:40.415  3037  4300 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-07 14:59:40.415  3037  4300 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-07 14:59:40.415  3037  4300 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-07 14:59:40.415  3037  4300 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-07 14:59:40.415  3037  4300 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-07 14:59:40.415  3037  4300 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-07 14:59:40.415  3037  4300 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-07 14:59:40.415  3037  4300 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-07 14:59:40.415  3037  4300 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 14:59:40.415  3037  4300 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 14:59:40.415  3037  4300 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-07 14:59:40.415  3037  4300 E KeepSync: 	... 10 more
09-07 14:59:40.416  3037  4300 W KeepSync: Sync result 2
,09-07 14:59:40.424   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 193236, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 14:59:40.576  1500  4294 I art     : Waiting for a blocking GC DisableMovingGc
,09-07 14:59:40.580  1500  4294 I art     : Starting a blocking GC DisableMovingGc
,09-07 14:59:40.610   377   377 D QSEECOMAPI: : Loaded image: APP id = 3
,09-07 14:59:40.611   377   377 D DrmWidevineDash: Service_Initialize: ends! returns 0
,09-07 14:59:40.612   377   377 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2c66000
09-07 14:59:40.612   377   377 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2c66000
,09-07 14:59:40.619   336   339 D DrmLibTime: got the req here! ret=0
,09-07 14:59:40.619   336   339 D DrmLibTime: command id, time_cmd_id = 770
09-07 14:59:40.619   336   339 D DrmLibTime: time_getutcsec starts!
,09-07 14:59:40.619   336   339 D DrmLibTime: QSEE Time Listener: time_getutcsec
09-07 14:59:40.620   336   339 D DrmLibTime: QSEE Time Listener: get_utc_seconds
,09-07 14:59:40.620   336   339 D DrmLibTime: QSEE Time Listener: seconds: 1473253180
,09-07 14:59:40.620   336   339 D DrmLibTime: QSEE Time Listener: nano seconds: 620271657
,09-07 14:59:40.620   336   339 D DrmLibTime: time_getutcsec returns 0, sec = 1473253180; nsec = 620271657
,09-07 14:59:40.621   336   339 D DrmLibTime: time_getutcsec finished! ,
,09-07 14:59:40.621   336   339 D DrmLibTime: iotcl_continue_command finished! and return 0 
09-07 14:59:40.621   336   339 D DrmLibTime: before calling ioctl to read the next time_cmd
,09-07 14:59:40.628   377   377 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,09-07 14:59:40.628   377   377 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-07 14:59:40.629   377   377 D DrmWidevineDash: hlos api version =  10
,09-07 14:59:40.629   377   377 D DrmWidevineDash: tz api version =  10
09-07 14:59:40.629   377   377 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
09-07 14:59:40.629   377   377 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,09-07 14:59:40.641   377   377 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,09-07 14:59:40.641   377   377 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
09-07 14:59:40.642   377   377 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbee78214
,09-07 14:59:40.642   377   377 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
09-07 14:59:40.642   377   377 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
09-07 14:59:40.642   377   377 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb608d668, dataLength=8
,09-07 14:59:40.643   377   377 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
09-07 14:59:40.643   377   377 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb4878e00, wrapped_rsa_key_length=1280
,09-07 14:59:40.647   377   377 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,09-07 14:59:40.647   377   377 I WVCdm   : CdmEngine::QueryKeyControlInfo
09-07 14:59:40.648   377  3477 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-07 14:59:40.648   377  3477 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
,09-07 14:59:40.648   377  3477 I WVCdm   : CdmEngine::GenerateKeyRequest
09-07 14:59:40.648   377  3477 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb2ca1260, idLength=0xb193ef2c
,09-07 14:59:40.669   377  3477 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,09-07 14:59:40.669   377  3477 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,09-07 14:59:40.671   377  3477 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
09-07 14:59:40.671   377  3477 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
,09-07 14:59:40.672   377  3477 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
,09-07 14:59:40.672   377  3477 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
,09-07 14:59:40.674   377  3477 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
,09-07 14:59:40.674   377  3477 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-07 14:59:40.677   377  3477 D DrmWidevineDash: hlos api version =  10
,09-07 14:59:40.677   377  3477 D DrmWidevineDash: tz api version =  10
09-07 14:59:40.677   377  3477 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
,09-07 14:59:40.677   377  3477 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
,09-07 14:59:40.678   377  3477 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
,09-07 14:59:40.679   377  3477 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
,09-07 14:59:40.679   377  3477 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,09-07 14:59:40.681   377  3477 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
,09-07 14:59:40.681   377  3477 D WVCdm   : PrepareKeyRequest: nonce=1807825579
,09-07 14:59:40.682   377  3477 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1989700
,09-07 14:59:40.682   377  3477 D DrmWidevineDash: message_length=1624, signature=0xb3b1aa00, signature_length=2979262468
,09-07 14:59:40.759   377  3477 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,09-07 14:59:40.761   377  3478 I WVCdm   : CdmEngine::CloseSession
,09-07 14:59:40.761   377  3478 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,09-07 14:59:40.764   377  3478 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
09-07 14:59:40.764   377  3478 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,09-07 14:59:40.767   377  3478 D DrmWidevineDash: Service_Uninitialize: starts!
,09-07 14:59:40.767   377  3478 D QSEECOMAPI: : QSEECom_dealloc_memory 
09-07 14:59:40.767   377  3478 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
,09-07 14:59:40.770   377  3478 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
09-07 14:59:40.771   377  3478 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,09-07 14:59:41.482   874  4219 D NetlinkSocketObserver: NeighborEvent{elapsedMs=208284, 192.168.1.1, [(null)], RTM_NEWNEIGH, NUD_FAILED}
,09-07 14:59:41.483   874  4219 W NetlinkSocketObserver: ALERT: NeighborEvent{elapsedMs=208284, 192.168.1.1, [(null)], RTM_NEWNEIGH, NUD_FAILED}
,09-07 14:59:41.485   874  4219 W IpReachabilityMonitor: FAILURE: LOST_PROVISIONING, NeighborEvent{elapsedMs=208284, 192.168.1.1, [(null)], RTM_NEWNEIGH, NUD_FAILED}
,09-07 14:59:41.489   874  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-07 14:59:41.505  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-07 14:59:41.512   874  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-07 14:59:41.512   874  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{5}, ntable=[]
,09-07 14:59:41.513   874  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-07 14:59:41.513   874  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 14:59:41.531   874  1303 E native  : do suspend true
,09-07 14:59:41.542   874  3650 D DhcpClient: Clearing IP address
,09-07 14:59:41.543   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-07 14:59:41.546   373   872 D CommandListener: Setting iface cfg
,09-07 14:59:41.552   874  4220 D DhcpClient: Receive thread stopped
,09-07 14:59:41.557   874  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-07 14:59:41.558   874  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] got DISCONNECTED, was satisfying 3
09-07 14:59:41.564   396   396 E Parcel  : Reading a NULL string not supported here.
,09-07 14:59:41.568   874  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 102]
,09-07 14:59:41.572   874  1303 D WifiStateMachine: Start Disconnecting Watchdog 3
,09-07 14:59:41.575   874  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-07 14:59:41.575   874  1303 E native  : do suspend true
,09-07 14:59:41.605   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 14:59:41.649   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 14:59:41.650   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-07 14:59:41.651   874  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true,
,09-07 14:59:41.651   874  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-07 14:59:41.658   874  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 14:59:41.659   874   891 D Tethering: MasterInitialState.processMessage what=3
09-07 14:59:41.669  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:41.669  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:41.669  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:41.669  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:59:41.669  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 14:59:41.669  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:59:41.669  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:59:41.669  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 14:59:41.674  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 14:59:41.677   874  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 14:59:41.679  2053  2053 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-07 14:59:41.683  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:41.683  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:41.683  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:41.683  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:59:41.683  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 14:59:41.683  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 14:59:41.683  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 14:59:41.683  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 14:59:41.688  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 14:59:41.688  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 14:59:41.693  1713  1713 D SystemUpdateService: onCreate
,09-07 14:59:41.698  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 14:59:41.713  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-07 14:59:41.717  1713  3687 I iu.UploadsManager: num queued entries: 0
,09-07 14:59:41.718  1713  3687 I iu.UploadsManager: num updated entries: 0
,09-07 14:59:41.718  1713  3687 I iu.SyncManager: NEXT; no task
,09-07 14:59:41.725  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 14:59:41.726  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-07 14:59:41.728  4238  4238 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 14:59:41.731  4238  4238 D SprintDMHelper: simOperator: 
,09-07 14:59:41.731  4238  4238 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 14:59:41.743   373   872 E Netd    : netlink response contains error (No such file or directory)
,09-07 14:59:41.744   874  1305 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-07 14:59:41.760  1713  4336 I SystemUpdateService: active receiver: enabled
,09-07 14:59:41.767  1713  4336 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 14:59:41.768  1713  4336 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-07 14:59:41.768  1713  4336 I SystemUpdateService: now status is 0 (complete)
,09-07 14:59:41.768  1713  4336 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-07 14:59:41.768  1713  4336 I SystemUpdateService: file has been verified,
09-07 14:59:41.768  1713  4336 I SystemUpdateService: OTA package size = 12249756
,09-07 14:59:41.776  1713  4336 I SystemUpdateService: showing system update notification
,09-07 14:59:41.783  1713  1713 D SystemUpdateService: onDestroy
,09-07 14:59:42.963  3465  4342 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775,
,09-07 14:59:42.965  3465  4342 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-07 14:59:42.965  3465  4317 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-07 14:59:42.965  3465  4317 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-07 14:59:42.966  3465  4317 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 14:59:42.966  3465  4342 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 14:59:42.968  3465  4317 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 14:59:42.968  3465  4342 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 14:59:42.974  3465  4344 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 380, name: OutgoingSocketThread/Sender)
,09-07 14:59:42.976  3465  4342 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-07 14:59:42.976  3465  4317 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-07 14:59:42.980  3465  4345 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 381, name: IncomingSocketThread/Sender)
,09-07 14:59:42.985  3465  4347 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 382, name: IncomingSocketThread/Receiver)
09-07 14:59:42.986  3465  4347 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 382, thread name: IncomingSocketThread/Receiver)
,09-07 14:59:42.987  3465  4347 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-07 14:59:42.987  3465  4347 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 382, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-07 14:59:42.987  3465  4346 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 383, name: OutgoingSocketThread/Receiver)
,09-07 14:59:42.990  3465  4346 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 383, thread name: OutgoingSocketThread/Receiver)
,09-07 14:59:42.990  3465  4346 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-07 14:59:42.992  3465  4346 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 383, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-07 14:59:43.190   874  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=15.00 rxSuccessRate=8.50 delta 1000 -> 994
,09-07 14:59:43.193   874  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=1 roam=3
,09-07 14:59:43.193   874  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-07 14:59:43.233   874  1303 D WifiConfigStore: Setting BSSID for "NG700"WPA_PSK to any
,09-07 14:59:43.277   874  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-07 14:59:43.280  1457  1457 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 14:59:43.484   874  4218 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-07 14:59:43.485   874  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-07 14:59:43.527  1891  1988 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-07 14:59:43.527  1891  1988 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-07 14:59:43.574  1500  1500 I ConfigService: onCreate
,09-07 14:59:43.709  1457  1457 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 14:59:43.747  1457  1457 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 14:59:43.749  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-07 14:59:43.757   874  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 14:59:43.763   874  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-07 14:59:43.763   874  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 14:59:43.763   874  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-07 14:59:43.787   874  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 14:59:43.802   373   872 D CommandListener: Setting iface cfg
,09-07 14:59:43.803   874  1303 D WifiStateMachine: Start Dhcp Watchdog 4
,09-07 14:59:43.811   874  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-07 14:59:43.839   874  4351 D DhcpClient: Receive thread started
,09-07 14:59:43.899  4251  4280 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-07 14:59:43.923   874  1303 E native  : do suspend false
,09-07 14:59:43.933   874  3650 D DhcpClient: Broadcasting DHCPDISCOVER
,09-07 14:59:43.948   874  4351 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172795, domain null
,09-07 14:59:43.948   874  3650 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172795 seconds
,09-07 14:59:43.951   874  3650 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-07 14:59:43.963   874  4351 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-07 14:59:43.963   874  3650 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-07 14:59:43.967   373   872 D CommandListener: Setting iface cfg
,09-07 14:59:43.972   874  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-07 14:59:43.975   874  1303 E native  : do suspend true
,09-07 14:59:43.976   874  3650 D DhcpClient: Scheduling renewal in 86399s
,09-07 14:59:43.989   874  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-07 14:59:43.990   874  1303 D WifiConfigStore: No blacklist allowed without epno enabled
09-07 14:59:43.990   874  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-07 14:59:43.991   874  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-07 14:59:43.992   874  1305 D ConnectivityService: Adding iface wlan0 to network 103
,09-07 14:59:44.012  2872  4285 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
09-07 14:59:44.012  2872  4285 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-07 14:59:44.014  2872  4285 I Babel   : connection state changed from CONNECTED to DISCONNECTED
09-07 14:59:44.020   874  1978 I ActivityManager: Killing 4006:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-07 14:59:44.042   874  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-07 14:59:44.042   874  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 103
,09-07 14:59:44.045   874  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 103
,09-07 14:59:44.046   874  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 103
,09-07 14:59:44.048   874  1305 D ConnectivityService: Setting Dns servers for network 103 to [/192.168.1.1]
,09-07 14:59:44.081   874  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-07 14:59:44.087   874  1305 D ConnectivityService: scheduleUnvalidatedPrompt 103
,09-07 14:59:44.087   874  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 103]
,09-07 14:59:44.087   874  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-07 14:59:44.088   874  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 14:59:44.088   874  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 103]
09-07 14:59:44.088   874  1305 D ConnectivityService:    accepting network in place of null
09-07 14:59:44.089   874  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 14:59:44.118   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 14:59:44.145   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 14:59:44.150   874  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 103] isDefaultNetwork=true
,09-07 14:59:44.150   874  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 14:59:44.152   874  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 103]
,09-07 14:59:44.161   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-07 14:59:44.183  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:44.183  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:44.183  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:44.183  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:59:44.183  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 14:59:44.183  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 14:59:44.183  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 14:59:44.183  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 14:59:44.184  2053  2053 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-07 14:59:44.187  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 14:59:44.191  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 14:59:44.191  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:44.191  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:44.191  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:59:44.191  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 14:59:44.191  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 14:59:44.191  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 14:59:44.191  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 14:59:44.193  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 14:59:44.198  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 14:59:44.202  1713  1713 D SystemUpdateService: onCreate
,09-07 14:59:44.204  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 14:59:44.220  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-07 14:59:44.222  1713  3687 I iu.UploadsManager: num queued entries: 0
,09-07 14:59:44.223  1713  3687 I iu.UploadsManager: num updated entries: 0
,09-07 14:59:44.227  1713  4364 I SystemUpdateService: active receiver: enabled
,09-07 14:59:44.229  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 14:59:44.231  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 14:59:44.233  4238  4238 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 14:59:44.238  1713  4366 I MDM     : [202] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-07 14:59:44.238  1713  4366 W BaseAppContext: Using Auth Proxy for data requests.
,09-07 14:59:44.239  4238  4238 D SprintDMHelper: simOperator: 
,09-07 14:59:44.239  4238  4238 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 14:59:44.245  1713  4366 V GoogleAuthProtoRequest: [202] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 14:59:44.254  1713  4364 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 14:59:44.267  1713  3687 I iu.SyncManager: NEXT; no task
,09-07 14:59:44.275  1713  4364 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-07 14:59:44.279  1713  4364 I SystemUpdateService: now status is 0 (complete)
09-07 14:59:44.279  1713  4364 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 14:59:44.279  1713  4364 I SystemUpdateService: file has been verified
09-07 14:59:44.279  1713  4364 I SystemUpdateService: OTA package size = 12249756
,09-07 14:59:44.298  1713  4364 I SystemUpdateService: showing system update notification
,09-07 14:59:44.310  1500  3723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-07 14:59:44.310  1500  3723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-07 14:59:44.310  1500  3723 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 14:59:44.310  1500  3723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:59:44.331  1713  1713 D SystemUpdateService: onDestroy
,09-07 14:59:44.338  1713  4366 E MDM     : [202] SitrepService.a: Error sending sitrep.
,09-07 14:59:44.519  1500  4287 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,09-07 14:59:44.571   874  4350 D NetlinkSocketObserver: NeighborEvent{elapsedMs=211372, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 14:59:45.152   874  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 102] cleared because we found a replacement network
,09-07 14:59:45.392  4373  4373 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.gms/app_fb/f.apk --oat-file=/data/user/0/com.google.android.gms/app_fb/f.dex
,09-07 14:59:45.469  4373  4373 I dex2oat : dex2oat took 77.719ms (threads: 4) arena alloc=70KB java alloc=39KB native alloc=1280KB free=1535KB
,09-07 14:59:45.475  4304  4315 W System  : ClassLoader referenced unknown path: 
,09-07 14:59:45.497  4304  4315 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 14:59:45.497  4304  4315 I Adreno  : Build Date                       : 10/20/15
09-07 14:59:45.497  4304  4315 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 14:59:45.497  4304  4315 I Adreno  : Local Branch                     : M14
09-07 14:59:45.497  4304  4315 I Adreno  : Remote Branch                    : 
09-07 14:59:45.497  4304  4315 I Adreno  : Remote Branch                    : 
09-07 14:59:45.497  4304  4315 I Adreno  : Reconstruct Branch               : 
,09-07 14:59:45.614   377  1311 D WVCdm   : Instantiating CDM.
,09-07 14:59:45.616   377  1311 I WVCdm   : CdmEngine::OpenSession
,09-07 14:59:45.616   377  1311 I WVCdm   : Level3 Library Jun 15 2015 14:09:24
,09-07 14:59:45.618   377  1311 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-07 14:59:45.620   377  1311 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x20
,09-07 14:59:45.620   377  1311 D DrmWidevineDash: Service_Initialize: starts!
09-07 14:59:45.620   377  1311 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-07 14:59:45.621   377  1311 D QSEECOMAPI: : App is not loaded in QSEE
,09-07 14:59:45.829   377  1311 D QSEECOMAPI: : Loaded image: APP id = 3
,09-07 14:59:45.832   377  1311 D DrmWidevineDash: Service_Initialize: ends! returns 0
,09-07 14:59:45.832   377  1311 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2c66000
09-07 14:59:45.833   377  1311 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2c66000
,09-07 14:59:45.841   336   339 D DrmLibTime: got the req here! ret=0
,09-07 14:59:45.841   336   339 D DrmLibTime: command id, time_cmd_id = 770
09-07 14:59:45.841   336   339 D DrmLibTime: time_getutcsec starts!
09-07 14:59:45.841   336   339 D DrmLibTime: QSEE Time Listener: time_getutcsec
,09-07 14:59:45.842   336   339 D DrmLibTime: QSEE Time Listener: get_utc_seconds
09-07 14:59:45.842   336   339 D DrmLibTime: QSEE Time Listener: seconds: 1473253185
09-07 14:59:45.842   336   339 D DrmLibTime: QSEE Time Listener: nano seconds: 842213896
,09-07 14:59:45.842   336   339 D DrmLibTime: time_getutcsec returns 0, sec = 1473253185; nsec = 842213896
09-07 14:59:45.842   336   339 D DrmLibTime: time_getutcsec finished! 
,09-07 14:59:45.843   336   339 D DrmLibTime: iotcl_continue_command finished! and return 0 
09-07 14:59:45.843   336   339 D DrmLibTime: before calling ioctl to read the next time_cmd
,09-07 14:59:45.850   377  1311 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,09-07 14:59:45.850   377  1311 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-07 14:59:45.851   377  1311 D DrmWidevineDash: hlos api version =  10
09-07 14:59:45.851   377  1311 D DrmWidevineDash: tz api version =  10
,09-07 14:59:45.851   377  1311 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
09-07 14:59:45.851   377  1311 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,09-07 14:59:45.865   377  1311 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
,09-07 14:59:45.865   377  1311 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
09-07 14:59:45.865   377  1311 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb2dc2134
09-07 14:59:45.865   377  1311 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
,09-07 14:59:45.865   377  1311 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
09-07 14:59:45.866   377  1311 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb608d6f8, dataLength=8
09-07 14:59:45.866   377  1311 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,09-07 14:59:45.867   377  1311 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb60bdc00, wrapped_rsa_key_length=1280
,09-07 14:59:45.871   377  1311 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,09-07 14:59:45.871   377  1311 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-07 14:59:45.873   377  3477 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,09-07 14:59:45.873   377  3477 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read atom size.
09-07 14:59:45.873   377  3477 I WVCdm   : CdmEngine::GenerateKeyRequest
09-07 14:59:45.873   377  3477 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb2ca11e0, idLength=0xb193ef2c
,09-07 14:59:45.886   377  3477 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,09-07 14:59:45.886   377  3477 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
09-07 14:59:45.887   377  3477 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
09-07 14:59:45.887   377  3477 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version =0x23
,09-07 14:59:45.887   377  3477 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
09-07 14:59:45.887   377  3477 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent: starts!
09-07 14:59:45.888   377  3477 D DrmWidevineDash: OEMCrypto_IsAntiRollbackHwPresent ends! ret=0, is_antirb_enabled = 1
,09-07 14:59:45.888   377  3477 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-07 14:59:45.889   377  3477 D DrmWidevineDash: hlos api version =  10
09-07 14:59:45.889   377  3477 D DrmWidevineDash: tz api version =  10
,09-07 14:59:45.889   377  3477 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 10
09-07 14:59:45.889   377  3477 D DrmWidevineDash: OEMCrypto_GetHDCPCapability starts!
09-07 14:59:45.890   377  3477 D DrmWidevineDash: OEMCrypto_GetHDCPCapability current=255, max=4
09-07 14:59:45.890   377  3477 D DrmWidevineDash: OEMCrypto_GetHDCPCapability ends! ret = 0
,09-07 14:59:45.890   377  3477 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
09-07 14:59:45.891   377  3477 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
09-07 14:59:45.891   377  3477 D WVCdm   : PrepareKeyRequest: nonce=2813449768
,09-07 14:59:45.891   377  3477 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1989700
09-07 14:59:45.891   377  3477 D DrmWidevineDash: message_length=1658, signature=0xb3b1aa00, signature_length=2979262468
,09-07 14:59:45.951   377  3477 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,09-07 14:59:45.951   377  1311 I WVCdm   : CdmEngine::CloseSession
09-07 14:59:45.951   377  1311 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
09-07 14:59:45.952   377  1311 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,09-07 14:59:45.952   377  1311 D DrmWidevineDash: OEMCrypto_Terminate: starts!
09-07 14:59:45.953   377  1311 D DrmWidevineDash: Service_Uninitialize: starts!
,09-07 14:59:45.953   377  1311 D QSEECOMAPI: : QSEECom_dealloc_memory 
09-07 14:59:45.953   377  1311 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
09-07 14:59:45.954   377  1311 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,09-07 14:59:45.954   377  1311 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,09-07 14:59:45.958  3465  3516 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-07 14:59:45.960  3465  3516 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-07 14:59:45.964  1713  4231 I CheckinRequestBuilder: Classify the device as Phone.
,09-07 14:59:45.966  3465  3516 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a02a3b Bundle[{}]
,09-07 14:59:45.967  3465  3516 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-07 14:59:45.968  3465  3516 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-07 14:59:45.969  3465  3516 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-07 14:59:45.971  3465  3516 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-07 14:59:45.973  3465  3516 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-07 14:59:45.974  3465  3516 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-07 14:59:45.976  1713  4231 I EventLogService: Opted in for usage reporting
,09-07 14:59:45.985  3465  3516 I System.out: Running OutgoingSocketThread
,09-07 14:59:45.988  3465  4382 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-07 14:59:45.988  3465  4382 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-07 14:59:46.471   874  1305 D ConnectivityService: handlePromptUnvalidated 102
,09-07 14:59:48.659  1500  1500 I ConfigService: onDestroy
,09-07 14:59:48.939  2722  3941 D Finsky  : [203] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,09-07 14:59:48.950  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:59:48.995  3465  4382 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-07 14:59:48.995  3465  4386 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-07 14:59:48.996  3465  4386 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-07 14:59:48.996  3465  4382 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-07 14:59:48.996  3465  4386 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 14:59:48.996  3465  4382 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 14:59:48.996  3465  4386 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 14:59:48.997  3465  4382 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 14:59:48.998  1500  3723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 14:59:48.998  1500  3723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-07 14:59:48.999  3465  4386 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-07 14:59:48.999  3465  4388 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 392, name: IncomingSocketThread/Sender)
09-07 14:59:48.998  1500  3723 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 14:59:49.000  1500  3723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-07 14:59:49.001  3465  4389 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 393, name: OutgoingSocketThread/Sender)
09-07 14:59:49.002  3465  4382 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-07 14:59:49.002  3465  4391 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 395, name: OutgoingSocketThread/Receiver)
09-07 14:59:49.003  3465  4391 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 395, thread name: OutgoingSocketThread/Receiver)
09-07 14:59:49.003  3465  4391 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-07 14:59:49.003  3465  4391 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 395, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-07 14:59:49.008  3465  4390 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 394, name: IncomingSocketThread/Receiver)
09-07 14:59:49.009  3465  4390 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 394, thread name: IncomingSocketThread/Receiver)
09-07 14:59:49.010  3465  4390 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-07 14:59:49.010  3465  4390 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 394, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-07 14:59:49.062  2722  3941 D Finsky  : [203] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,09-07 14:59:49.125   874   883 I art     : Background partial concurrent mark sweep GC freed 53610(3MB) AllocSpace objects, 10(380KB) LOS objects, 33% free, 29MB/43MB, paused 1.287ms total 102.422ms
,09-07 14:59:50.238   874  1925 D AlarmManagerService: Setting time of day to sec=1473253189
,09-07 14:59:49.892   874  1925 W AlarmManagerService: Unable to set rtc to 1473253189: Invalid argument
,09-07 14:59:49.894   874  4349 D NetworkMonitor/NetworkAgentInfo [WIFI () - 103]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-07 14:59:50.665   874  1971 I ActivityManager: Killing 3994:com.google.android.gm/u0a78 (adj 15): empty #17
,09-07 14:59:50.862  2872  4369 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-07 14:59:50.881   874  2020 I ActivityManager: Killing 3982:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,09-07 14:59:50.937  1713  4231 I CheckinTask: Sending checkin request (7067 bytes),
,09-07 14:59:51.652  3465  3516 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 404)
,09-07 14:59:51.655  3465  3516 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-07 14:59:51.655  3465  3516 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 405)
,09-07 14:59:51.660  3465  3516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 14:59:51.660  3465  3516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cea2f added. We now have 3 listener(s)
,09-07 14:59:51.662  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
09-07 14:59:51.662  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 14:59:51.662  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 14:59:51.663  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 14:59:51.663  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@434383c added. We now have 4 listener(s)
09-07 14:59:51.663  3465  3516 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 14:59:51.664  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 14:59:51.666  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 14:59:51.673  3465  3516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 14:59:51.673  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:51.673  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:51.673  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:59:51.673  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 14:59:51.673  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 14:59:51.673  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 14:59:51.673  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 14:59:51.676  3465  3516 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 14:59:51.677  3465  3516 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 14:59:51.677  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 14:59:51.677  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 14:59:51.677  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 14:59:51.678  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 14:59:51.678  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:59:51.678  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 14:59:51.678  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 14:59:51.678  3465  3516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cea2f removed from the list
09-07 14:59:51.678  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:59:51.678  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@434383c removed from the list
09-07 14:59:51.681  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:51.681  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 14:59:51.681  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:59:51.682  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:59:51.682  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:59:51.684  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 14:59:51.685  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 14:59:51.685  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 14:59:51.685  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@434383c not in the list
09-07 14:59:51.685  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:59:51.686  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:51.686  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:59:51.688  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 14:59:51.688  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 14:59:51.688  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 14:59:51.689  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@434383c not in the list
,09-07 14:59:51.689  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 14:59:51.714  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:59:51.715  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:59:51.715  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cea2f not in the list
,09-07 14:59:51.716  3465  3516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 14:59:51.716  3465  3516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5133f1a added. We now have 3 listener(s)
,09-07 14:59:51.719  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 14:59:51.719  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 14:59:51.719  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 14:59:51.720  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 14:59:51.720  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e87fa4b added. We now have 4 listener(s)
09-07 14:59:51.720  3465  3516 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 14:59:51.721  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 14:59:51.724  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 14:59:51.733  3465  3516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 14:59:51.733  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:51.733  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:51.733  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:59:51.733  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 14:59:51.733  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 14:59:51.733  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 14:59:51.733  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 14:59:51.737  3465  3516 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 14:59:51.737  3465  3516 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 14:59:51.740  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 14:59:51.740  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 14:59:51.740  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 14:59:51.740  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 14:59:51.741  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 14:59:51.742  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 14:59:51.744   874  1305 D ConnectivityService: handlePromptUnvalidated 103
09-07 14:59:51.747  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 14:59:51.749  3465  3516 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-07 14:59:51.749  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 14:59:51.762  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 14:59:51.768  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-07 14:59:51.769  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 14:59:51.777  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 14:59:51.777  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-07 14:59:51.779  3465  3516 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 14:59:51.781  3465  3516 D BluetoothAdapter: STATE_ON
,09-07 14:59:51.789  4154  4192 D BtGatt.GattService: registerClient() - UUID=634289bc-1a73-4fd3-a242-90eec37559c2
,09-07 14:59:51.790  4154  4178 D BtGatt.GattService: onClientRegistered() - UUID=634289bc-1a73-4fd3-a242-90eec37559c2, clientIf=5
,09-07 14:59:51.791  3465  3476 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-07 14:59:51.794  4154  4200 D BtGatt.GattService: start scan with filters
,09-07 14:59:51.801  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 14:59:51.802  4154  4182 D BtGatt.ScanManager: handling starting scan
,09-07 14:59:51.802  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 14:59:51.802  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-07 14:59:51.802  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-07 14:59:51.804  4154  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31cfb1f
,09-07 14:59:51.810  3465  3516 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 14:59:51.810  3465  3465 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 14:59:51.811  3465  3516 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 14:59:51.814  4154  4178 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-07 14:59:51.814  4154  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 14:59:51.815  4154  4182 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-07 14:59:51.817  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 14:59:51.823  4154  4178 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-07 14:59:51.824  4154  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 14:59:51.825  4154  4182 D BtGatt.ScanManager: Starting BLE batch scan
,09-07 14:59:51.826  3465  3516 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-07 14:59:51.826  4154  4182 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-07 14:59:51.826  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 14:59:51.826  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 14:59:51.827  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:59:51.827  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-07 14:59:51.827  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 14:59:51.827  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 14:59:51.828  3465  3516 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 14:59:51.828  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 14:59:51.828  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 14:59:51.828  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-07 14:59:51.829  3465  3516 D BluetoothAdapter: STATE_ON
,09-07 14:59:51.829  4154  4164 D BtGatt.GattService: stopScan() - queue size =1
,09-07 14:59:51.830  4154  4192 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-07 14:59:51.833  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-07 14:59:51.833  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-07 14:59:51.833  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-07 14:59:51.834  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-07 14:59:51.834  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-07 14:59:51.835  3465  3516 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 14:59:51.836  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 14:59:51.836  3465  3516 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-07 14:59:51.836  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 14:59:51.837  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 14:59:51.838  3465  3465 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 14:59:51.838  3465  3465 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 14:59:51.838  3465  3465 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 14:59:51.842  4154  4178 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-07 14:59:51.843  4154  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 14:59:51.851  4154  4178 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-07 14:59:51.851  4154  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 14:59:51.861  4154  4178 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-07 14:59:51.861  4154  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 14:59:51.861  4154  4182 D BtGatt.ScanManager: stopping BLe Batch
,09-07 14:59:51.872  4154  4178 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-07 14:59:51.872  4154  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 14:59:51.872  4154  4182 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 14:59:51.884  4154  4178 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-07 14:59:51.884  4154  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 14:59:52.339  3465  3465 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 14:59:52.340  3465  3465 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 14:59:52.340  3465  3465 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 14:59:54.839  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 14:59:54.840  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 14:59:54.840  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 14:59:54.841  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 14:59:54.842  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:59:54.842  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 14:59:54.842  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 14:59:54.843  3465  3516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5133f1a removed from the list
09-07 14:59:54.843  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:59:54.843  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e87fa4b removed from the list
,09-07 14:59:54.843  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
09-07 14:59:54.844  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:59:54.845  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 14:59:54.846  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:59:54.849  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 14:59:54.849  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 14:59:54.850  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:59:54.850  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e87fa4b not in the list
09-07 14:59:54.850  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:59:54.851  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:59:54.854  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 14:59:54.854  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 14:59:54.854  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 14:59:54.855  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e87fa4b not in the list
,09-07 14:59:54.855  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 14:59:54.855  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:59:54.856  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:59:54.856  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5133f1a not in the list
09-07 14:59:54.859  3465  3516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 14:59:54.859  3465  3516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a152d4 added. We now have 3 listener(s)
,09-07 14:59:54.861  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 14:59:54.861  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 14:59:54.861  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 14:59:54.861  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 14:59:54.861  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e50c7d added. We now have 4 listener(s)
09-07 14:59:54.862  3465  3516 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 14:59:54.862  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 14:59:54.866  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 14:59:54.871  3465  3516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 14:59:54.871  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:54.871  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:54.871  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:59:54.871  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 14:59:54.871  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 14:59:54.871  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 14:59:54.871  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 14:59:54.874  3465  3516 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 14:59:54.874  3465  3516 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 14:59:54.874  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 14:59:54.875  3465  3516 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-07 14:59:54.875  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-07 14:59:54.876  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 14:59:54.876  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-07 14:59:54.876  3465  3516 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 14:59:54.876  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 14:59:54.877  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 14:59:54.878  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:54.878  3465  3516 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-07 14:59:54.879  3465  3516 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 14:59:54.879  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-07 14:59:54.879  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 14:59:54.879  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 14:59:54.880  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 14:59:54.881  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:54.881  3465  4398 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 14:59:54.881  3465  3465 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-07 14:59:54.884  3465  4398 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-07 14:59:54.886  3465  3516 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-07 14:59:54.886  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 14:59:54.895  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 14:59:54.896  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-07 14:59:54.896  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 14:59:54.900  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-07 14:59:54.901  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 14:59:54.902  3465  3516 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-07 14:59:54.904  3465  3516 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-07 14:59:54.905  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-07 14:59:54.905  3465  3516 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-07 14:59:54.906  3465  3516 D BluetoothAdapter: STATE_ON
,09-07 14:59:54.913  4154  4203 D BtGatt.GattService: registerClient() - UUID=bb41ac69-88e1-4a4e-8058-8b6ea4bab085
,09-07 14:59:54.914  4154  4178 D BtGatt.GattService: onClientRegistered() - UUID=bb41ac69-88e1-4a4e-8058-8b6ea4bab085, clientIf=5
09-07 14:59:54.914  3465  3512 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-07 14:59:54.916  4154  4181 D BtGatt.AdvertiseManager: message : 0
,09-07 14:59:54.920  4154  4181 D BtGatt.AdvertiseManager: starting multi advertising
,09-07 14:59:54.934  4154  4178 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-07 14:59:54.943  4154  4178 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-07 14:59:54.945  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-07 14:59:54.945  3465  3516 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 14:59:54.947  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 14:59:54.949  3465  3465 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 14:59:54.949  3465  3465 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-07 14:59:54.949  3465  3465 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-07 14:59:54.949  3465  3465 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-07 14:59:54.950  3465  3465 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-07 14:59:54.950  3465  3465 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-07 14:59:54.953  3465  3465 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-07 14:59:54.953  3465  3465 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 14:59:54.954  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 14:59:54.954  3465  3516 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 14:59:55.162  1713  4231 I CheckinRequestBuilder: Checkin reason type: 12 attempt count: 1
,09-07 14:59:55.165  1713  4231 E ActivityThread: Failed to find provider info for com.google.android.wearable.settings
,09-07 14:59:55.320  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:59:55.323  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 14:59:55.365  1500  3725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,09-07 14:59:55.366  1500  3725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> AndroidCheckInServer without consulting the cloud.
09-07 14:59:55.366  1500  3725 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 14:59:55.366  1500  3725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 14:59:55.386  1713  4231 W CheckinRequestBuilder: awaiting user notification for token
,09-07 14:59:55.408  1713  4231 I CheckinRequestBuilder: Classify the device as Phone.
,09-07 14:59:55.423  1713  4231 I EventLogService: Opted in for usage reporting
,09-07 14:59:55.433  1713  4231 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,09-07 14:59:55.446  1713  4231 I CheckinService: Checking schedule, now: 1473253195445 next: 1473294338437
09-07 14:59:55.446  1713  4231 I CheckinService: active receiver: disabled
,09-07 14:59:55.453  3465  3465 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-07 14:59:55.462  1713  4402 I CheckinService: Checking schedule, now: 1473253195461 next: 1473294338437
09-07 14:59:55.462  1713  4402 I CheckinService: active receiver: disabled
,09-07 14:59:55.476   874  1706 I ActivityManager: Killing 3959:android.process.acore/u0a5 (adj 15): empty #17
,09-07 14:59:55.525  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 14:59:55.526  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 14:59:55.539  1500  1847 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,09-07 14:59:57.956  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 14:59:57.956  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-07 14:59:57.957  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-07 14:59:57.957  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-07 14:59:57.957  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-07 14:59:57.958  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-07 14:59:57.959  3465  4398 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed,
09-07 14:59:57.959  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-07 14:59:57.959  3465  4398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 14:59:57.960  3465  3516 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 14:59:57.960  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 14:59:57.960  3465  3465 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 14:59:57.960  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 14:59:57.960  3465  4398 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 14:59:57.961  3465  3516 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 14:59:57.961  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 14:59:57.961  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 14:59:57.964  3465  3516 D BluetoothAdapter: STATE_ON
09-07 14:59:57.964  3465  3516 D BluetoothLeScanner: could not find callback wrapper
09-07 14:59:57.964  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 14:59:57.965  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-07 14:59:57.967  4154  4181 D BtGatt.AdvertiseManager: message : 1
09-07 14:59:57.969  4154  4181 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-07 14:59:57.979  4154  4178 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-07 14:59:57.979  4154  4178 D BtGatt.GattService: Client app is not null!
,09-07 14:59:57.981  4154  4200 D BtGatt.GattService: unregisterClient() - clientIf=5
09-07 14:59:57.982  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 14:59:57.983  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-07 14:59:57.983  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-07 14:59:57.983  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-07 14:59:57.983  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-07 14:59:57.986  3465  3516 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 14:59:57.986  3465  3516 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 14:59:57.987  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 14:59:57.988  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 14:59:57.991  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 14:59:57.991  3465  3465 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 14:59:57.991  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 14:59:57.991  3465  3465 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 14:59:57.991  3465  3465 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 14:59:57.991  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 14:59:57.992  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 14:59:57.992  3465  3465 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 14:59:57.992  3465  3516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a152d4 removed from the list
09-07 14:59:57.993  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:59:57.993  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e50c7d removed from the list
,09-07 14:59:57.993  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
09-07 14:59:57.993  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:59:57.995  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:59:57.995  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:59:57.996  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 14:59:57.996  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 14:59:57.996  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:59:57.996  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e50c7d not in the list
09-07 14:59:57.996  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 14:59:57.996  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 14:59:57.997  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 14:59:57.997  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 14:59:57.997  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 14:59:57.997  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e50c7d not in the list
,09-07 14:59:57.997  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 14:59:57.997  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 14:59:57.997  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 14:59:57.998  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a152d4 not in the list
,09-07 14:59:57.998  3465  3516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 14:59:57.998  3465  3516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5eb8be added. We now have 3 listener(s)
09-07 14:59:58.000  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 14:59:58.000  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 14:59:58.000  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 14:59:58.001  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 14:59:58.001  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@592bd1f added. We now have 4 listener(s)
09-07 14:59:58.001  3465  3516 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 14:59:58.001  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 14:59:58.003  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 14:59:58.011  3465  3516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 14:59:58.011  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 14:59:58.011  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 14:59:58.011  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 14:59:58.011  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 14:59:58.011  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 14:59:58.011  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 14:59:58.011  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 14:59:58.013  3465  3516 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 14:59:58.013  3465  3516 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 14:59:58.013  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 14:59:58.013  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 14:59:58.014  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 14:59:58.014  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 14:59:58.014  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 14:59:58.018  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:58.019  3465  3516 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 14:59:58.019  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 14:59:58.023  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 14:59:58.023  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 14:59:58.024  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-07 14:59:58.025  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 14:59:58.030  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 14:59:58.030  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 14:59:58.030  3465  3516 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-07 14:59:58.031  3465  3516 D BluetoothAdapter: STATE_ON
,09-07 14:59:58.033  4154  4192 D BtGatt.GattService: registerClient() - UUID=d2eebfdb-349e-4823-b3c6-49337a16e886
,09-07 14:59:58.034  4154  4178 D BtGatt.GattService: onClientRegistered() - UUID=d2eebfdb-349e-4823-b3c6-49337a16e886, clientIf=5
,09-07 14:59:58.035  3465  3475 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-07 14:59:58.035  4154  4165 D BtGatt.GattService: start scan with filters
,09-07 14:59:58.039  4154  4182 D BtGatt.ScanManager: handling starting scan
,09-07 14:59:58.040  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-07 14:59:58.040  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 14:59:58.040  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 14:59:58.041  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 14:59:58.048  3465  3516 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 14:59:58.048  3465  3465 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 14:59:58.048  3465  3516 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 14:59:58.053  4154  4178 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-07 14:59:58.053  4154  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 14:59:58.054  4154  4182 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-07 14:59:58.054  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 14:59:58.068  4154  4178 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-07 14:59:58.069  4154  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 14:59:58.069  4154  4182 D BtGatt.ScanManager: Starting BLE batch scan
09-07 14:59:58.069  4154  4182 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-07 14:59:58.097  4154  4178 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-07 14:59:58.098  4154  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 14:59:58.114  4154  4178 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-07 14:59:58.115  4154  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 14:59:58.494  3465  3465 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 14:59:58.549  3465  3465 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-07 14:59:58.549  3465  3465 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 14:59:58.550  3465  3465 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 14:59:59.621  4154  4154 D BtGatt.ScanManager: awakened up at time 226770
,09-07 14:59:59.624  4154  4182 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 14:59:59.672  4154  4178 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=12
,09-07 14:59:59.672  4154  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 14:59:59.672  4154  4178 D BtGatt.GattService: current time is 226822073951
,09-07 14:59:59.673  4154  4178 D BtGatt.GattService: Batch record : [78, -20, -96, 83, -39, -56, 1, -128, -66, 13, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 118, 39, 0, 48, 11, -106, 2, 69, 75, 1, -128, -65, 27, 0, 0, 0, 48, 11, -106, 2, 69, 75, 1, -128, -62, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, -46, -4, -117, 6, 105, -37, 1, -128, -86, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -95, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 87, 45, 110, 28, -13, -4, 1, -128, -64, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85, 0, -126, -22, -96, 83, -39, -56, 1, -128, -62, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65, 0, -52, 11, 57, -70, 107, -17, 1, 0, -103, 5, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, 116, -43, -111, -91, -20, -29, 1, -128, -84, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -92, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -86, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 48, 11, -106, 2, 69, 75, 1, -128, -62, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0]
,09-07 14:59:59.675  4154  4178 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 118, 39]
09-07 14:59:59.677  4154  4178 D BtGatt.GattService: ScanRecord : []
09-07 14:59:59.677  4154  4178 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
09-07 14:59:59.677  4154  4178 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-07 14:59:59.678  4154  4178 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
09-07 14:59:59.678  4154  4178 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85]
09-07 14:59:59.678  4154  4178 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65]
09-07 14:59:59.679  4154  4178 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
09-07 14:59:59.679  4154  4178 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
09-07 14:59:59.679  4154  4178 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-07 14:59:59.680  4154  4178 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-07 14:59:59.680  4154  4178 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
09-07 14:59:59.688  3465  3465 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 1], added - the peer count is 1
09-07 14:59:59.689  3465  3465 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 08:EC:A9:50:75:41 1], added - the peer count is 2
09-07 14:59:59.690  3465  3465 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 08:EC:A9:50:76:27 1], added - the peer count is 3
,09-07 14:59:59.691  3465  3465 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 7C:F9:0E:34:8A:A0 1] updated - the peer count is 3
09-07 14:59:59.692  3465  3465 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:37:96:AB 1], added - the peer count is 4
,09-07 14:59:59.693  3465  3465 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,09-07 14:59:59.694  3465  3465 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 08:EC:A9:50:75:41 1], Bluetooth address: 08:EC:A9:50:75:41, device name: '', device address: ''
,09-07 14:59:59.695  3465  3465 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 08:EC:A9:50:76:27 1], Bluetooth address: 08:EC:A9:50:76:27, device name: '', device address: ''
,09-07 14:59:59.695  3465  3465 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:37:96:AB 1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: '', device address: ''
,09-07 15:00:00.862   874  4349 D NetworkMonitor/NetworkAgentInfo [WIFI () - 103]: Probably not a portal: exception java.net.SocketTimeoutException
,09-07 15:00:00.865   874  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] validation failed
,09-07 15:00:00.869   874  1303 E WifiConfigStore:  rewrite network history for "NG700"WPA_PSK
,09-07 15:00:01.065  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 15:00:01.066  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-07 15:00:01.066  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 15:00:01.067  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:00:01.067  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-07 15:00:01.067  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-07 15:00:01.068  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 15:00:01.068  3465  3516 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-07 15:00:01.068  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 15:00:01.069  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-07 15:00:01.069  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-07 15:00:01.071  3465  3516 D BluetoothAdapter: STATE_ON
09-07 15:00:01.073  4154  4203 D BtGatt.GattService: stopScan() - queue size =1
09-07 15:00:01.075  4154  4164 D BtGatt.GattService: unregisterClient() - clientIf=5
09-07 15:00:01.077  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-07 15:00:01.077  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 15:00:01.077  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 15:00:01.078  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-07 15:00:01.078  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 15:00:01.082  3465  3516 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 15:00:01.082  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-07 15:00:01.083  3465  3516 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-07 15:00:01.083  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 15:00:01.086  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 15:00:01.086  4154  4154 D BtGatt.ScanManager: awakened up at time 228235
,09-07 15:00:01.086  3465  3516 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
09-07 15:00:01.095  3465  3465 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 15:00:01.096  3465  3465 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 15:00:01.096  3465  3465 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 15:00:01.097  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 15:00:01.097  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:00:01.097  4154  4178 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-07 15:00:01.097  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 15:00:01.097  4154  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:00:01.097  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:00:01.098  4154  4182 D BtGatt.ScanManager: stopping BLe Batch
09-07 15:00:01.098  3465  3516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5eb8be removed from the list
,09-07 15:00:01.098  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:00:01.099  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@592bd1f removed from the list
09-07 15:00:01.101  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:00:01.101  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:00:01.102  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:00:01.102  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:00:01.105  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:00:01.105  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:00:01.105  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:00:01.105  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@592bd1f not in the list
,09-07 15:00:01.106  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:00:01.106  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:00:01.108  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:00:01.108  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:00:01.108  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:00:01.108  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@592bd1f not in the list
09-07 15:00:01.108  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:00:01.109  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 15:00:01.109  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:00:01.109  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5eb8be not in the list
09-07 15:00:01.111  3465  3516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 15:00:01.111  3465  3516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e370eed added. We now have 3 listener(s)
09-07 15:00:01.114  4154  4178 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-07 15:00:01.114  4154  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 15:00:01.114  4154  4182 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 15:00:01.116  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 15:00:01.116  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 15:00:01.117  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 15:00:01.117  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 15:00:01.118  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4bc122 added. We now have 4 listener(s)
,09-07 15:00:01.118  3465  3516 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 15:00:01.118  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 15:00:01.122  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 15:00:01.129  3465  3516 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 15:00:01.129  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:00:01.129  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:00:01.129  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:00:01.129  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:00:01.129  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:00:01.129  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:00:01.129  3465  3516 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 15:00:01.134  3465  3516 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 15:00:01.134  3465  3516 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 15:00:01.134  3465  3516 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 15:00:01.134  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 15:00:01.135  3465  3516 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 15:00:01.135  4154  4178 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
09-07 15:00:01.135  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:00:01.135  4154  4178 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 15:00:01.135  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:00:01.135  4154  4178 D BtGatt.GattService: current time is 228284486557
09-07 15:00:01.135  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 15:00:01.135  3465  3516 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 15:00:01.135  3465  3516 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e370eed removed from the list
09-07 15:00:01.135  4154  4178 D BtGatt.GattService: Batch record : [87, 45, 110, 28, -13, -4, 1, -128, -48, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85, 0, 48, 11, -106, 2, 69, 75, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, -126, -22, -96, 83, -39, -56, 1, -128, -60, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65, 0, 50, -35, 86, -77, -92, -11, 1, -128, -107, 2, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, -108, 37, -7, 2, 2, -37, 21, -106, -117, -54, -61, 0]
09-07 15:00:01.135  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:00:01.135  3465  3516 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4bc122 removed from the list
09-07 15:00:01.135  4154  4178 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85]
09-07 15:00:01.135  4154  4178 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
09-07 15:00:01.136  4154  4178 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 8, -20, -87, 80, 117, 65]
09-07 15:00:01.136  4154  4178 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, -108, 37, -7, 2, 2, -37, 21, -106, -117, -54, -61]
09-07 15:00:01.137  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 15:00:01.137  3465  3516 D io.jxcore.node.ConnectivityMonitor: stop
09-07 15:00:01.137  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:00:01.138  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:00:01.138  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:00:01.140  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 15:00:01.140  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:00:01.140  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 15:00:01.140  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4bc122 not in the list
09-07 15:00:01.141  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:00:01.141  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 15:00:01.141  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:00:01.143  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 15:00:01.143  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 15:00:01.143  3465  3516 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 15:00:01.143  3465  3516 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c4bc122 not in the list
09-07 15:00:01.143  3465  3516 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 15:00:01.143  3465  3516 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 15:00:01.144  3465  3516 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 15:00:01.144  3465  3516 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e370eed not in the list
,09-07 15:00:01.146  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-07 15:00:01.146  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 15:00:01.146  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-07 15:00:01.146  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 15:00:01.147  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-07 15:00:01.147  3465  3516 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-07 15:00:01.597  3465  3465 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 15:00:01.870   874  4349 D NetworkMonitor/NetworkAgentInfo [WIFI () - 103]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238
,09-07 15:00:03.167  3465  4405 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 414, name: My test thread name)
,09-07 15:00:04.359   874  4349 D NetworkMonitor/NetworkAgentInfo [WIFI () - 103]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 13:00:03 GMT], X-Android-Received-Millis=[1473253204356], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473253203058]}
,09-07 15:00:04.365   874  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-07 15:00:04.366   874  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] validation  passed
,09-07 15:00:04.367   874  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,09-07 15:00:04.373   874  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-07 15:00:04.376   874  1303 E WifiConfigStore:  rewrite network history for "NG700"WPA_PSK
,09-07 15:00:05.164  3465  3516 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 414
,09-07 15:00:05.165  3465  3516 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 414, name: My test thread name)
,09-07 15:00:05.171  3465  4408 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 415, name: My test thread name)
,09-07 15:00:05.172  3465  4408 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 415, thread name: My test thread name)
09-07 15:00:05.172  3465  4408 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 415, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-07 15:00:05.176  3465  3516 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 15:00:05.185  3465  4409 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 419, name: My test thread name)
,09-07 15:00:05.186  3465  4409 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 419, thread name: My test thread name): Test exception.
09-07 15:00:05.187  3465  4409 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 419, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-07 15:00:05.194  3465  3516 I jxcore-log: Total number of executed tests:  82
09-07 15:00:05.194  3465  3516 I jxcore-log: 
,09-07 15:00:05.195  3465  3516 I jxcore-log: Number of passed tests:  81
09-07 15:00:05.195  3465  3516 I jxcore-log: 
09-07 15:00:05.196  3465  3516 I jxcore-log: Number of failed tests:  1
09-07 15:00:05.196  3465  3516 I jxcore-log: 
,09-07 15:00:05.197  3465  3516 I jxcore-log: Number of ignored tests:  0
09-07 15:00:05.197  3465  3516 I jxcore-log: 
09-07 15:00:05.197  3465  3516 I jxcore-log: Total duration:  95685
09-07 15:00:05.197  3465  3516 I jxcore-log: 
,09-07 15:00:05.200  3465  3516 I jxcore-log: Failures: 
09-07 15:00:05.200  3465  3516 I jxcore-log:  DiscoveryManager1 isRunning should return true
09-07 15:00:05.200  3465  3516 I jxcore-log: Expected: is <true>
09-07 15:00:05.200  3465  3516 I jxcore-log:      but: was <false>
09-07 15:00:05.200  3465  3516 I jxcore-log: 
09-07 15:00:05.200  3465  3516 I jxcore-log: 
09-07 15:00:05.200  3465  3516 I jxcore-log: Failed to execute UT.
09-07 15:00:05.200  3465  3516 I jxcore-log: 
,09-07 15:00:05.208  3465  3516 I jxcore-log: Unit Test app is loaded
09-07 15:00:05.208  3465  3516 I jxcore-log: 
,09-07 15:00:05.216  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:00:05.216  3465  3516 I jxcore-log: 
,09-07 15:00:05.222  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:00:05.222  3465  3516 I jxcore-log: 
,09-07 15:00:05.224  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:00:05.224  3465  3516 I jxcore-log: 
09-07 15:00:05.225  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:00:05.225  3465  3516 I jxcore-log: 
,09-07 15:00:05.227  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 15:00:05.227  3465  3516 I jxcore-log: 
,09-07 15:00:05.228  3465  3465 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-07 15:00:05.229  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:00:05.229  3465  3516 I jxcore-log: 
,09-07 15:00:05.232  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 15:00:05.232  3465  3516 I jxcore-log: 
,09-07 15:00:05.233  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 15:00:05.233  3465  3516 I jxcore-log: 
,09-07 15:00:05.235  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 15:00:05.235  3465  3516 I jxcore-log: 
,09-07 15:00:05.236  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 15:00:05.236  3465  3516 I jxcore-log: 
09-07 15:00:05.237  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 15:00:05.237  3465  3516 I jxcore-log: 
,09-07 15:00:05.238  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 15:00:05.238  3465  3516 I jxcore-log: 
09-07 15:00:05.239  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 15:00:05.239  3465  3516 I jxcore-log: 
,09-07 15:00:05.240  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:00:05.240  3465  3516 I jxcore-log: 
09-07 15:00:05.241  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:00:05.241  3465  3516 I jxcore-log: 
,09-07 15:00:05.242  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:00:05.242  3465  3516 I jxcore-log: 
09-07 15:00:05.243  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:00:05.243  3465  3516 I jxcore-log: 
,09-07 15:00:05.243  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:00:05.243  3465  3516 I jxcore-log: 
09-07 15:00:05.244  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 15:00:05.244  3465  3516 I jxcore-log: 
09-07 15:00:05.245  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 15:00:05.245  3465  3516 I jxcore-log: 
,09-07 15:00:05.246  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 15:00:05.246  3465  3516 I jxcore-log: 
09-07 15:00:05.246  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:00:05.246  3465  3516 I jxcore-log: 
,09-07 15:00:05.248  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:00:05.248  3465  3516 I jxcore-log: 
09-07 15:00:05.249  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:00:05.249  3465  3516 I jxcore-log: 
,09-07 15:00:05.249  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 15:00:05.249  3465  3516 I jxcore-log: 
09-07 15:00:05.250  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 15:00:05.250  3465  3516 I jxcore-log: 
09-07 15:00:05.250  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 15:00:05.250  3465  3516 I jxcore-log: 
,09-07 15:00:05.251  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:00:05.251  3465  3516 I jxcore-log: 
09-07 15:00:05.251  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:00:05.251  3465  3516 I jxcore-log: 
09-07 15:00:05.252  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:00:05.252  3465  3516 I jxcore-log: 
,09-07 15:00:05.252  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 15:00:05.252  3465  3516 I jxcore-log: 
09-07 15:00:05.253  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 15:00:05.253  3465  3516 I jxcore-log: 
09-07 15:00:05.253  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 15:00:05.253  3465  3516 I jxcore-log: 
,09-07 15:00:05.254  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:00:05.254  3465  3516 I jxcore-log: 
09-07 15:00:05.254  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:00:05.254  3465  3516 I jxcore-log: 
09-07 15:00:05.255  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:00:05.255  3465  3516 I jxcore-log: 
,09-07 15:00:05.255  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 15:00:05.255  3465  3516 I jxcore-log: 
09-07 15:00:05.256  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 15:00:05.256  3465  3516 I jxcore-log: 
09-07 15:00:05.256  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 15:00:05.256  3465  3516 I jxcore-log: 
09-07 15:00:05.257  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:00:05.257  3465  3516 I jxcore-log: 
,09-07 15:00:05.257  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:00:05.257  3465  3516 I jxcore-log: 
09-07 15:00:05.258  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 15:00:05.258  3465  3516 I jxcore-log: 
09-07 15:00:05.258  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 15:00:05.258  3465  3516 I jxcore-log: 
09-07 15:00:05.259  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 15:00:05.259  3465  3516 I jxcore-log: 
,09-07 15:00:05.259  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 15:00:05.259  3465  3516 I jxcore-log: 
09-07 15:00:05.259  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 15:00:05.259  3465  3516 I jxcore-log: 
09-07 15:00:05.260  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 15:00:05.260  3465  3516 I jxcore-log: 
,09-07 15:00:05.260  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:00:05.260  3465  3516 I jxcore-log: 
09-07 15:00:05.261  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:00:05.261  3465  3516 I jxcore-log: 
09-07 15:00:05.261  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:00:05.261  3465  3516 I jxcore-log: 
,09-07 15:00:05.262  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 15:00:05.262  3465  3516 I jxcore-log: 
09-07 15:00:05.262  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 15:00:05.262  3465  3516 I jxcore-log: 
09-07 15:00:05.263  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:00:05.263  3465  3516 I jxcore-log: 
09-07 15:00:05.263  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:00:05.263  3465  3516 I jxcore-log: 
,09-07 15:00:05.264  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:00:05.264  3465  3516 I jxcore-log: 
09-07 15:00:05.265  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:00:05.265  3465  3516 I jxcore-log: 
09-07 15:00:05.265  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 15:00:05.265  3465  3516 I jxcore-log: 
,09-07 15:00:05.265  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:00:05.265  3465  3516 I jxcore-log: 
09-07 15:00:05.266  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-07 15:00:05.266  3465  3516 I jxcore-log: 
09-07 15:00:05.266  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:00:05.266  3465  3516 I jxcore-log: 
09-07 15:00:05.267  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 15:00:05.267  3465  3516 I jxcore-log: 
09-07 15:00:05.268  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-07 15:00:05.268  3465  3516 I jxcore-log: 
09-07 15:00:05.269  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-07 15:00:05.269  3465  3516 I jxcore-log: 
,09-07 15:00:05.269  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-07 15:00:05.269  3465  3516 I jxcore-log: 
09-07 15:00:05.270  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-07 15:00:05.270  3465  3516 I jxcore-log: 
09-07 15:00:05.270  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-07 15:00:05.270  3465  3516 I jxcore-log: 
09-07 15:00:05.271  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:00:05.271  3465  3516 I jxcore-log: 
,09-07 15:00:05.271  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 15:00:05.271  3465  3516 I jxcore-log: 
,09-07 15:00:05.274   874  1687 D WifiService: setWifiEnabled: true pid=3465, uid=10000
09-07 15:00:05.274   874  1687 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 15:00:05.277  3465  3516 D BluetoothAdapter: enable(): BT is already enabled..!
,09-07 15:00:05.279  3465  3516 I jxcore-log: My device name is: motorola-Nexus 6
09-07 15:00:05.279  3465  3516 I jxcore-log: 
,09-07 15:00:05.280  3465  4405 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 414, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,09-07 15:00:05.281  3465  3516 I jxcore-log: Running for NATIVE network type
09-07 15:00:05.281  3465  3516 I jxcore-log: 
,09-07 15:00:05.294  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-07 15:00:05.297   874  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-07 15:00:05.297   874  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-07 15:00:05.297   874  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 15:00:05.297   874  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 15:00:05.316   874  1303 E native  : do suspend true
,09-07 15:00:05.334   874  3650 D DhcpClient: Clearing IP address
,09-07 15:00:05.335   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-07 15:00:05.341   373   872 D CommandListener: Setting iface cfg
,09-07 15:00:05.342  1500  4397 V NativeCrypto: Read error: ssl=0x9b110200: I/O error during system call, Connection timed out
09-07 15:00:05.344   874  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 15:00:05.344   874  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] got DISCONNECTED, was satisfying 3
09-07 15:00:05.344   874  1303 D WifiStateMachine: Start Disconnecting Watchdog 4
,09-07 15:00:05.349   874  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 15:00:05.349   874  1303 E native  : do suspend true
,09-07 15:00:05.354   396   396 E Parcel  : Reading a NULL string not supported here.
09-07 15:00:05.354   874  4351 D DhcpClient: Receive thread stopped
,09-07 15:00:05.355   874  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 103]
,09-07 15:00:05.369  1500  4397 V NativeCrypto: SSL shutdown failed: ssl=0x9b110200: I/O error during system call, Broken pipe
,09-07 15:00:05.388   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 15:00:05.407   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 15:00:05.407   373   872 D CommandListener: Clearing all IP addresses on wlan0
09-07 15:00:05.408   874  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 103] isDefaultNetwork=true
09-07 15:00:05.408   874  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:00:05.410   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-07 15:00:05.411   874  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-07 15:00:05.417  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:00:05.417  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:00:05.417  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:00:05.417  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:00:05.417  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:00:05.417  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:00:05.417  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:00:05.417  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:00:05.420  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 15:00:05.422  2053  2053 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-07 15:00:05.425  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:00:05.425  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:00:05.425  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:00:05.425  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:00:05.425  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:00:05.425  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 15:00:05.425  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 15:00:05.425  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 15:00:05.426  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-07 15:00:05.426   874  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-07 15:00:05.428  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 15:00:05.440  1713  1713 D SystemUpdateService: onCreate
,09-07 15:00:05.443  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 15:00:05.455  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-07 15:00:05.461  1713  3687 I iu.UploadsManager: num queued entries: 0
09-07 15:00:05.461  1713  3687 I iu.UploadsManager: num updated entries: 0
09-07 15:00:05.462  1713  3687 I iu.SyncManager: NEXT; no task
09-07 15:00:05.463  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-07 15:00:05.464  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-07 15:00:05.466  4238  4238 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-07 15:00:05.467   373   872 E Netd    : netlink response contains error (No such file or directory)
09-07 15:00:05.468   874  1305 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-07 15:00:05.469  4238  4238 D SprintDMHelper: simOperator: 
09-07 15:00:05.469  4238  4238 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-07 15:00:05.490  1713  4419 I SystemUpdateService: active receiver: enabled
,09-07 15:00:05.494  2872  4422 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-07 15:00:05.513  1713  4419 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 15:00:05.531   874  1294 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-07 15:00:05.531  1713  4419 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-07 15:00:05.551  1713  4419 I SystemUpdateService: now status is 0 (complete)
09-07 15:00:05.551  1713  4419 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 15:00:05.551  1713  4419 I SystemUpdateService: file has been verified
,09-07 15:00:05.551  1713  4419 I SystemUpdateService: OTA package size = 12249756
,09-07 15:00:05.554   874  1978 I ActivityManager: Start proc 4424:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-07 15:00:05.585  4424  4424 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-07 15:00:05.612  1713  4419 I SystemUpdateService: showing system update notification
,09-07 15:00:05.617  1858  1858 V GmsNetworkLocationProvi: DISABLE
,09-07 15:00:05.621  1858  1858 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,09-07 15:00:05.641  4424  4424 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-07 15:00:05.656  1713  1713 D SystemUpdateService: onDestroy
,09-07 15:00:05.672  1713  4444 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
09-07 15:00:05.674  2053  4445 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
09-07 15:00:05.675  1713  4444 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,09-07 15:00:05.701  1713  2337 I Icing   : updateResources: need to parse f{com.google.android.gms}
,09-07 15:00:05.726  2053  4445 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 52 ms] updated apps [took 52 ms] 
,09-07 15:00:05.737  4424  4441 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,09-07 15:00:05.906  4424  4441 D ContactDirectoryManager: Found com.google.contacts.gal.provider
,09-07 15:00:05.906  4424  4441 D ContactDirectoryManager: Found com.google.android.gm.exchange.directory.provider
,09-07 15:00:05.923   874  1971 I ActivityManager: Start proc 4449:com.google.android.gm.exchange/u0a77 for content provider com.google.android.gm.exchange/com.android.exchange.provider.ExchangeDirectoryProvider
,09-07 15:00:05.995  4449  4449 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltExchange3Google/lib/arm
,09-07 15:00:06.028   874  2020 I ActivityManager: Start proc 4461:com.google.android.gm/u0a78 for content provider com.google.android.gm/com.android.email.provider.EmailProvider
,09-07 15:00:06.063   874  1687 I ActivityManager: Killing 4078:com.android.settings/1000 (adj 15): empty #17
,09-07 15:00:06.142  4461  4461 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltGmail/lib/arm
,09-07 15:00:06.154   874  1380 I ActivityManager: Start proc 4473:com.google.process.gapps/u0a99 for content provider com.google.android.syncadapters.contacts/.GalProvider
,09-07 15:00:06.190   874  2014 I ActivityManager: Killing 4101:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,09-07 15:00:06.230  4461  4487 I Gmail   : getAccountsCursor
,09-07 15:00:06.247  4461  4488 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,09-07 15:00:06.254  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:00:06.293  4473  4473 W System  : ClassLoader referenced unknown path: /system/app/GoogleContactsSyncAdapter/lib/arm
,09-07 15:00:06.357  4461  4461 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-07 15:00:06.378  4473  4473 I GoogleHttpClient: GMS http client unavailable, use old client
,09-07 15:00:06.396  4424  4441 I ContactDirectoryManager: deleted 0 stale rows which don't have any relevant directory
,09-07 15:00:06.437  4461  4501 E Gmail   : Error finding the version of the Email provider.....,
09-07 15:00:06.437  4461  4501 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
09-07 15:00:06.437  4461  4501 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
09-07 15:00:06.437  4461  4501 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1280)
09-07 15:00:06.437  4461  4501 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
09-07 15:00:06.437  4461  4501 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-07 15:00:06.437  4461  4501 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:00:06.437  4461  4501 E Gmail   : 	at android.os.Looper.loop(Looper.java:148)
09-07 15:00:06.437  4461  4501 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 15:00:06.438  4424  4441 I ContactDirectoryManager: Discovered 0 contact directories in 637ms
,09-07 15:00:06.437  4461  4501 W EmailMigration: We do not support migrating this version of the Email provider.
,09-07 15:00:06.484  4461  4503 I Gmail   : getAccountsCursor
,09-07 15:00:06.487  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:00:06.561  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:00:06.587   874  1978 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,09-07 15:00:06.631  4449  4449 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-07 15:00:06.633  4461  4510 I Gmail   : Observing account changes for notifications
,09-07 15:00:06.658  4449  4449 I Exchange: EasService.onCreate
,09-07 15:00:06.674  4449  4513 I Exchange: RestartPingTask
,09-07 15:00:06.705  4449  4449 I Exchange: RestartPingsTask did not start any pings.
,09-07 15:00:06.705  4449  4449 I Exchange: PSS stopIfIdle
09-07 15:00:06.705  4449  4449 I Exchange: PSS has no active accounts; stopping service.
,09-07 15:00:06.707  4449  4449 I Exchange: onDestroy
,09-07 15:00:06.726  4461  4499 I Gmail   : getAccountsCursor
,09-07 15:00:06.731  4461  4509 I Gmail   : notifyAccountChanged
,09-07 15:00:06.736  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:00:06.738  4461  4509 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,09-07 15:00:06.749  4461  4509 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,09-07 15:00:06.752  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:00:06.758  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:00:06.762  4461  4509 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,09-07 15:00:06.769  4461  4509 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,09-07 15:00:06.851  4461  4503 I Gmail   : getAccountsCursor
,09-07 15:00:06.859  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:00:06.884   874  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=55.00 rxSuccessRate=35.00 delta 1000 -> 1
,09-07 15:00:06.885   874  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=1 roam=3
09-07 15:00:06.885   874  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-07 15:00:06.932   874  1303 D WifiConfigStore: Setting BSSID for "NG700"WPA_PSK to any
,09-07 15:00:06.949   874  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-07 15:00:06.951  1457  1457 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 15:00:07.365  1457  1457 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 15:00:07.408  1457  1457 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 15:00:07.409  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-07 15:00:07.413   874  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 15:00:07.424   874  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{104}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 15:00:07.425   874  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 104] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-07 15:00:07.425   874  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 15:00:07.446   874  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 15:00:07.460   373   872 D CommandListener: Setting iface cfg
,09-07 15:00:07.464   874  1303 D WifiStateMachine: Start Dhcp Watchdog 5
,09-07 15:00:07.474   874  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-07 15:00:07.484   874  4518 D DhcpClient: Receive thread started
,09-07 15:00:07.564   874  1303 E native  : do suspend false
,09-07 15:00:07.578   874  3650 D DhcpClient: Broadcasting DHCPDISCOVER
,09-07 15:00:07.606   874  4518 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172776, domain null
,09-07 15:00:07.607   874  3650 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172776 seconds
,09-07 15:00:07.610   874  3650 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-07 15:00:07.652   874  4518 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-07 15:00:07.653   874  3650 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-07 15:00:07.659   373   872 D CommandListener: Setting iface cfg
,09-07 15:00:07.667   874  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-07 15:00:07.668   874  3650 D DhcpClient: Scheduling renewal in 86399s
,09-07 15:00:07.670   874  1303 E native  : do suspend true
,09-07 15:00:07.682   874  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-07 15:00:07.684   874  1303 D WifiConfigStore: No blacklist allowed without epno enabled
09-07 15:00:07.684   874  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 104] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-07 15:00:07.685   874  1305 D ConnectivityService: Adding iface wlan0 to network 104
,09-07 15:00:07.698   874  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 15:00:07.713   874  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-07 15:00:07.713   874  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 104
09-07 15:00:07.714   874  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 104
,09-07 15:00:07.715   874  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 104
,09-07 15:00:07.716   874  1305 D ConnectivityService: Setting Dns servers for network 104 to [/192.168.1.1]
,09-07 15:00:07.732   874  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 104]
,09-07 15:00:07.735   874  1305 D ConnectivityService: scheduleUnvalidatedPrompt 104
,09-07 15:00:07.736   874  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 104]
09-07 15:00:07.736   874  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 104]
09-07 15:00:07.736   874  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-07 15:00:07.736   874  1305 D ConnectivityService:    accepting network in place of null
09-07 15:00:07.736   874  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-07 15:00:07.737   874  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{104}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 15:00:07.760   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 15:00:07.784   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 15:00:07.788   874  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 104] isDefaultNetwork=true
,09-07 15:00:07.788   874  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 15:00:07.793   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-07 15:00:07.795   874  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 104]
,09-07 15:00:07.806  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:00:07.806  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:00:07.806  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:00:07.806  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:00:07.806  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:00:07.806  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:00:07.806  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:00:07.806  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 15:00:07.808  2053  2053 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-07 15:00:07.809  1713  1713 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-07 15:00:07.809  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 15:00:07.812  1713  1713 D SystemUpdateService: onCreate
,09-07 15:00:07.818  3465  3465 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 15:00:07.818  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 15:00:07.818  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 15:00:07.818  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 15:00:07.818  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 15:00:07.818  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 15:00:07.818  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 15:00:07.818  3465  3465 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 15:00:07.819  1713  1713 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 15:00:07.821  3465  3465 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 15:00:07.827  1713  4526 I SystemUpdateService: active receiver: enabled
,09-07 15:00:07.833  1713  4526 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 15:00:07.836  1713  1713 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-07 15:00:07.839  1713  3687 I iu.UploadsManager: num queued entries: 0
,09-07 15:00:07.839  1713  3687 I iu.UploadsManager: num updated entries: 0
09-07 15:00:07.840  1713  3687 I iu.SyncManager: NEXT; no task
09-07 15:00:07.840  1713  4526 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-07 15:00:07.841  1713  4526 I SystemUpdateService: now status is 0 (complete),
09-07 15:00:07.841  1713  4526 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 15:00:07.841  1713  4526 I SystemUpdateService: file has been verified
09-07 15:00:07.842  1713  4526 I SystemUpdateService: OTA package size = 12249756
,09-07 15:00:07.845  1713  4526 I SystemUpdateService: showing system update notification
,09-07 15:00:07.851  1713  1713 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 15:00:07.853  1713  1713 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 15:00:07.854  1713  1713 D SystemUpdateService: onDestroy
,09-07 15:00:07.856  4238  4238 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-07 15:00:07.857  1713  4530 I MDM     : [215] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-07 15:00:07.858  1713  4530 W BaseAppContext: Using Auth Proxy for data requests.
,09-07 15:00:07.859  1713  4530 V GoogleAuthProtoRequest: [215] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 15:00:07.862  4238  4238 D SprintDMHelper: simOperator: 
09-07 15:00:07.862  4238  4238 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 15:00:07.887  1500  3723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-07 15:00:07.887  1500  3723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-07 15:00:07.887  1500  3723 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:00:07.887  1500  3723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:00:07.900  1713  4530 E MDM     : [215] SitrepService.a: Error sending sitrep.
,09-07 15:00:08.131  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-07 15:00:08.131  3465  3516 I jxcore-log: 
,09-07 15:00:08.589  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-07 15:00:08.589  3465  3516 I jxcore-log: 
,09-07 15:00:08.597   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=235745, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:00:08.623  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-07 15:00:08.623  3465  3516 I jxcore-log: 
,09-07 15:00:08.788   874  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 103] cleared because we found a replacement network
,09-07 15:00:10.009  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-07 15:00:10.009  3465  3516 I jxcore-log: 
,09-07 15:00:10.253  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-07 15:00:10.253  3465  3516 I jxcore-log: 
,09-07 15:00:10.258  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-07 15:00:10.258  3465  3516 I jxcore-log: 
,09-07 15:00:10.265  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-07 15:00:10.265  3465  3516 I jxcore-log: 
,09-07 15:00:10.530  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-07 15:00:10.530  3465  3516 I jxcore-log: 
,09-07 15:00:10.547  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-07 15:00:10.547  3465  3516 I jxcore-log: 
,09-07 15:00:10.551  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-07 15:00:10.551  3465  3516 I jxcore-log: 
,09-07 15:00:10.688   874  1689 I ActivityManager: Killing 3550:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
,09-07 15:00:11.298  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-07 15:00:11.298  3465  3516 I jxcore-log: 
,09-07 15:00:11.422  4461  4492 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-07 15:00:11.466  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-07 15:00:11.466  3465  3516 I jxcore-log: 
,09-07 15:00:11.702  4449  4512 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-07 15:00:11.802  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-07 15:00:11.802  3465  3516 I jxcore-log: 
,09-07 15:00:11.815  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-07 15:00:11.815  3465  3516 I jxcore-log: 
,09-07 15:00:11.825  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-07 15:00:11.825  3465  3516 I jxcore-log: 
,09-07 15:00:11.832  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-07 15:00:11.832  3465  3516 I jxcore-log: 
,09-07 15:00:11.874  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-07 15:00:11.874  3465  3516 I jxcore-log: 
,09-07 15:00:11.922  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-07 15:00:11.922  3465  3516 I jxcore-log: 
,09-07 15:00:11.929  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-07 15:00:11.929  3465  3516 I jxcore-log: 
,09-07 15:00:11.937  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-07 15:00:11.937  3465  3516 I jxcore-log: 
,09-07 15:00:11.957  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-07 15:00:11.957  3465  3516 I jxcore-log: 
,09-07 15:00:11.963  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-07 15:00:11.963  3465  3516 I jxcore-log: ,
,09-07 15:00:11.969  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-07 15:00:11.969  3465  3516 I jxcore-log: 
,09-07 15:00:11.985  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-07 15:00:11.985  3465  3516 I jxcore-log: 
,09-07 15:00:12.012  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-07 15:00:12.012  3465  3516 I jxcore-log: 
,09-07 15:00:12.024  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-07 15:00:12.024  3465  3516 I jxcore-log: 
,09-07 15:00:12.037  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-07 15:00:12.037  3465  3516 I jxcore-log: 
,09-07 15:00:12.049  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-07 15:00:12.049  3465  3516 I jxcore-log: 
,09-07 15:00:12.065  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-07 15:00:12.065  3465  3516 I jxcore-log: 
,09-07 15:00:12.075  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-07 15:00:12.075  3465  3516 I jxcore-log: 
,09-07 15:00:12.081  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-07 15:00:12.081  3465  3516 I jxcore-log: 
,09-07 15:00:12.088  3465  3516 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-07 15:00:12.088  3465  3516 I jxcore-log: 
,09-07 15:00:12.104  3465  3516 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-07 15:00:12.105  3465  3516 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-07 15:00:12.105  3465  3516 I jxcore-log: 
,09-07 15:00:12.155  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 15:00:12.155  3465  3516 I jxcore-log: 
,09-07 15:00:12.156  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 15:00:12.156  3465  3516 I jxcore-log: 
09-07 15:00:12.156  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:00:12.156  3465  3516 I jxcore-log: 
09-07 15:00:12.157  3465  3516 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 15:00:12.157  3465  3516 I jxcore-log: 
,09-07 15:00:13.735  2872  4532 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-07 15:00:13.743   874  1689 I ActivityManager: Killing 4251:com.google.android.apps.books/u0a34 (adj 15): empty #17
,09-07 15:00:15.736   874  1305 D ConnectivityService: handlePromptUnvalidated 104
,09-07 15:00:16.500   874  4516 D NetworkMonitor/NetworkAgentInfo [WIFI () - 104]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-07 15:00:17.551   874  1687 D ConnectivityService: reportNetworkConnectivity(104, true) by 10011
,09-07 15:00:17.577   874  2014 D ConnectivityService: reportNetworkConnectivity(104, true) by 10011
,09-07 15:00:17.579   874  1706 D ConnectivityService: reportNetworkConnectivity(104, true) by 10011
,09-07 15:00:19.013   874  4516 D NetworkMonitor/NetworkAgentInfo [WIFI () - 104]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 13:00:17 GMT], X-Android-Received-Millis=[1473253219012], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473253217529]}
,09-07 15:00:19.016   874  4516 D NetworkMonitor/NetworkAgentInfo [WIFI () - 104]: Forcing reevaluation for UID 10011
,09-07 15:00:19.017   874  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-07 15:00:19.017   874  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 104] validation  passed
09-07 15:00:19.018   874  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 104]
,09-07 15:00:19.023   874  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-07 15:00:19.026   874  4516 D NetworkMonitor/NetworkAgentInfo [WIFI () - 104]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238
,09-07 15:00:20.602   874  4516 D NetworkMonitor/NetworkAgentInfo [WIFI () - 104]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 13:00:19 GMT], X-Android-Received-Millis=[1473253220600], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473253219029]}
09-07 15:00:20.609   874  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-07 15:00:20.610   874  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 104] validation  passed
,09-07 15:00:38.351  3037  4547 V KeepSync: Connecting to GoogleApiClient
,09-07 15:00:38.352   874  2012 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-07 15:00:38.379  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:00:38.388  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:00:38.458  1500  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 15:00:38.458  1500  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 15:00:38.458  1500  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:00:38.459  1500  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:00:38.501  1500  2048 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-07 15:00:38.501  1500  2048 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-07 15:00:38.501  1500  2048 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 15:00:38.501  1500  2048 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:00:38.506  3269  4548 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-07 15:00:38.506  3269  4548 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 15:00:38.506  3269  4548 E HttpOperation: 	at jdm.a(PG:82)
09-07 15:00:38.506  3269  4548 E HttpOperation: 	at jcs.o(PG:406)
09-07 15:00:38.506  3269  4548 E HttpOperation: 	at jcn.a(PG:1379)
09-07 15:00:38.506  3269  4548 E HttpOperation: 	at jcs.i(PG:143)
09-07 15:00:38.506  3269  4548 E HttpOperation: 	at blb.a(PG:3937)
09-07 15:00:38.506  3269  4548 E HttpOperation: 	at czp.a(PG:18188)
09-07 15:00:38.506  3269  4548 E HttpOperation: 	at czp.a(PG:9081)
09-07 15:00:38.506  3269  4548 E HttpOperation: 	at czq.run(PG:1686)
09-07 15:00:38.506  3269  4548 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 15:00:38.506  3269  4548 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 15:00:38.506  3269  4548 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 15:00:38.506  3269  4548 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 15:00:38.506  3269  4548 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 15:00:38.506  3269  4548 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 15:00:38.506  3269  4548 E HttpOperation: 	at jdj.a(PG:4091)
09-07 15:00:38.506  3269  4548 E HttpOperation: 	at jdj.a(PG:1125)
09-07 15:00:38.506  3269  4548 E HttpOperation: 	at jdm.a(PG:77)
09-07 15:00:38.506  3269  4548 E HttpOperation: 	... 12 more
09-07 15:00:38.506  3269  4548 E HttpOperation: Caused by: faj: BadAuthentication
09-07 15:00:38.506  3269  4548 E HttpOperation: 	at fal.a(PG:38)
09-07 15:00:38.506  3269  4548 E HttpOperation: 	at jdj.a(PG:4089)
09-07 15:00:38.506  3269  4548 E HttpOperation: 	... 14 more
,09-07 15:00:38.583  1713  4549 V BaseAuthAsyncOperation: access token request failed
,09-07 15:00:38.584  3037  4547 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-07 15:00:38.661   874  2013 I ActivityManager: Start proc 4550:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,09-07 15:00:38.685  1500  3723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 15:00:38.686  1500  3723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 15:00:38.686  1500  3723 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 15:00:38.686  1500  3723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:00:38.708  3269  4548 E HttpOperation: [getmobileexperiments] Unexpected exception
09-07 15:00:38.708  3269  4548 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 15:00:38.708  3269  4548 E HttpOperation: 	at jdm.a(PG:82)
09-07 15:00:38.708  3269  4548 E HttpOperation: 	at jcs.o(PG:406)
09-07 15:00:38.708  3269  4548 E HttpOperation: 	at jcn.a(PG:1379)
09-07 15:00:38.708  3269  4548 E HttpOperation: 	at jcs.i(PG:143)
09-07 15:00:38.708  3269  4548 E HttpOperation: 	at hec.a(PG:42)
09-07 15:00:38.708  3269  4548 E HttpOperation: 	at hee.a(PG:102)
09-07 15:00:38.708  3269  4548 E HttpOperation: 	at czr.a(PG:65)
09-07 15:00:38.708  3269  4548 E HttpOperation: 	at kka.a(PG:108)
09-07 15:00:38.708  3269  4548 E HttpOperation: 	at czp.a(PG:19176)
09-07 15:00:38.708  3269  4548 E HttpOperation: 	at czp.a(PG:9081)
09-07 15:00:38.708  3269  4548 E HttpOperation: 	at czq.run(PG:1686)
09-07 15:00:38.708  3269  4548 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 15:00:38.708  3269  4548 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 15:00:38.708  3269  4548 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 15:00:38.708  3269  4548 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 15:00:38.708  3269  4548 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 15:00:38.708  3269  4548 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 15:00:38.708  3269  4548 E HttpOperation: 	at jdj.a(PG:4091)
09-07 15:00:38.708  3269  4548 E HttpOperation: 	at jdj.a(PG:1125)
09-07 15:00:38.708  3269  4548 E HttpOperation: 	at jdm.a(PG:77)
09-07 15:00:38.708  3269  4548 E HttpOperation: 	... 15 more
09-07 15:00:38.708  3269  4548 E HttpOperation: Caused by: faj: BadAuthentication
09-07 15:00:38.708  3269  4548 E HttpOperation: 	at fal.a(PG:38)
09-07 15:00:38.708  3269  4548 E HttpOperation: 	at jdj.a(PG:4089)
09-07 15:00:38.708  3269  4548 E HttpOperation: 	... 17 more
,09-07 15:00:38.708  3269  4548 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-07 15:00:38.708  3269  4548 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-07 15:00:38.708  3269  4548 E ExperimentLoader: 	at jdm.a(PG:82)
09-07 15:00:38.708  3269  4548 E ExperimentLoader: 	at jcs.o(PG:406)
09-07 15:00:38.708  3269  4548 E ExperimentLoader: 	at jcn.a(PG:1379)
09-07 15:00:38.708  3269  4548 E ExperimentLoader: 	at jcs.i(PG:143)
09-07 15:00:38.708  3269  4548 E ExperimentLoader: 	at hec.a(PG:42)
09-07 15:00:38.708  3269  4548 E ExperimentLoader: 	at hee.a(PG:102)
09-07 15:00:38.708  3269  4548 E ExperimentLoader: 	at czr.a(PG:65)
09-07 15:00:38.708  3269  4548 E ExperimentLoader: 	at kka.a(PG:108)
09-07 15:00:38.708  3269  4548 E ExperimentLoader: 	at czp.a(PG:19176)
09-07 15:00:38.708  3269  4548 E ExperimentLoader: 	at czp.a(PG:9081)
09-07 15:00:38.708  3269  4548 E ExperimentLoader: 	at czq.run(PG:1686)
09-07 15:00:38.708  3269  4548 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 15:00:38.708  3269  4548 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 15:00:38.708  3269  4548 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 15:00:38.708  3269  4548 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 15:00:38.708  3269  4548 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-07 15:00:38.708  3269  4548 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 15:00:38.708  3269  4548 E ExperimentLoader: 	at jdj.a(PG:4091)
09-07 15:00:38.708  3269  4548 E ExperimentLoader: 	at jdj.a(PG:1125)
09-07 15:00:38.708  3269  4548 E ExperimentLoader: 	at jdm.a(PG:77)
09-07 15:00:38.708  3269  4548 E ExperimentLoader: 	... 15 more
09-07 15:00:38.708  3269  4548 E ExperimentLoader: Caused by: faj: BadAuthentication
09-07 15:00:38.708  3269  4548 E ExperimentLoader: 	at fal.a(PG:38)
09-07 15:00:38.708  3269  4548 E ExperimentLoader: 	at jdj.a(PG:4089)
09-07 15:00:38.708  3269  4548 E ExperimentLoader: 	... 17 more
,09-07 15:00:38.742  4550  4550 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-07 15:00:38.815  4550  4550 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-07 15:00:38.838   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 237057, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-07 15:00:38.844  1500  3725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-07 15:00:38.844  1500  3725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-07 15:00:38.844  1500  3725 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:00:38.844  1500  3725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:00:38.870   874   886 I ActivityManager: Start proc 4575:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,09-07 15:00:38.893  4550  4574 V GoogleAuthProtoRequest: [381] a.<init>: mAccountName set to: thalitester@gmail.com,
,09-07 15:00:38.908  4575  4575 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,09-07 15:00:38.916  3037  4547 E KeepSync: IOException
09-07 15:00:38.916  3037  4547 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-07 15:00:38.916  3037  4547 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-07 15:00:38.916  3037  4547 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-07 15:00:38.916  3037  4547 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-07 15:00:38.916  3037  4547 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-07 15:00:38.916  3037  4547 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-07 15:00:38.916  3037  4547 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-07 15:00:38.916  3037  4547 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-07 15:00:38.916  3037  4547 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-07 15:00:38.916  3037  4547 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-07 15:00:38.916  3037  4547 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-07 15:00:38.916  3037  4547 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-07 15:00:38.916  3037  4547 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-07 15:00:38.916  3037  4547 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-07 15:00:38.916  3037  4547 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 15:00:38.916  3037  4547 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 15:00:38.916  3037  4547 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-07 15:00:38.916  3037  4547 E KeepSync: 	... 10 more
09-07 15:00:38.916  3037  4547 W KeepSync: Sync result 2
,09-07 15:00:38.924  1500  3726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,09-07 15:00:38.925   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 238107, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 15:00:38.927  1500  3726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,09-07 15:00:38.927  1500  3726 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:00:38.928  1500  3726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:00:38.947  4550  4574 W ExperimentUpdateService: [381] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,09-07 15:00:38.948  4550  4574 W ExperimentUpdateService: [381] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 15:00:38.948  4550  4574 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 15:00:38.948  4550  4574 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-07 15:00:38.948  4550  4574 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
09-07 15:00:38.948  4550  4574 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-07 15:00:38.948  4550  4574 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-07 15:00:38.948  4550  4574 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-07 15:00:38.948  4550  4574 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-07 15:00:38.948  4550  4574 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
09-07 15:00:38.948  4550  4574 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-07 15:00:38.948  4550  4574 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,09-07 15:00:38.980  4575  4575 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-07 15:00:38.990  4575  4575 I BooksApp: Created application version: 3.6.9 (30609)
,09-07 15:00:39.046  4575  4592 I BooksSync: Starting books sync for 61035162, extras: ade
,09-07 15:00:39.173  4575  4598 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-07 15:00:39.227  1500  2048 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 15:00:39.227  1500  2048 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 15:00:39.227  1500  2048 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:00:39.227  1500  2048 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:00:39.268  1500  3725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 15:00:39.268  1500  3725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 15:00:39.268  1500  3725 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:00:39.268  1500  3725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:00:39.283  4575  4598 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-07 15:00:39.285  4575  4592 E BooksSync: Soft error
09-07 15:00:39.285  4575  4592 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 15:00:39.285  4575  4592 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-07 15:00:39.286  4575  4592 E BooksSync: Sync error
09-07 15:00:39.286  4575  4592 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 15:00:39.286  4575  4592 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-07 15:00:39.286  4575  4592 I BooksSync: Finished books sync
,09-07 15:00:39.295   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 239176, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 15:00:39.295   874  1991 I ActivityManager: Killing 2722:com.android.vending/u0a19 (adj 15): empty #17
09-07 15:00:39.296   279   279 E lowmemorykiller: Error writing /proc/2722/oom_score_adj; errno=22
,09-07 15:00:39.348   874  1991 I ActivityManager: Killing 4304:com.google.android.gms.unstable/u0a11 (adj 15): empty #18
,09-07 15:00:43.983  4575  4590 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-07 15:00:44.261   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:00:49.048   874   885 I ActivityManager: Start proc 4602:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,09-07 15:00:49.164  4602  4602 W System  : ClassLoader referenced unknown path: /system/priv-app/Phonesky/lib/arm
,09-07 15:00:49.253  4602  4602 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,09-07 15:00:49.318  4602  4602 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,09-07 15:00:49.337  4602  4602 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-07 15:00:49.339  4602  4602 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,09-07 15:00:49.394   874  2014 I ActivityManager: Killing 2053:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,09-07 15:00:49.415  4602  4613 D Finsky  : [377] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,09-07 15:00:49.436   874  1304 D WifiService: Client connection lost with reason: 4
,09-07 15:00:49.467  4602  4636 D Ads     : Skipping gmscore version check
,09-07 15:00:49.478  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:00:49.483  4602  4602 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,09-07 15:00:49.484  4602  4602 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,09-07 15:00:49.492  4602  4636 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,09-07 15:00:49.494  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:00:49.499  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:00:49.538  1500  2367 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 15:00:49.538  1500  2367 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-07 15:00:49.538  1500  2367 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:00:49.538  1500  2367 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:00:49.539  4602  4602 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,09-07 15:00:49.557  4602  4602 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,09-07 15:00:49.563  4602  4613 D Finsky  : [377] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,09-07 15:00:50.382   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=277530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-07 15:00:52.282  1500  2155 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-07 15:00:54.337  4602  4602 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,09-07 15:00:54.377  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:00:54.437  1500  2367 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 15:00:54.438  1500  2367 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-07 15:00:54.438  1500  2367 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:00:54.438  1500  2367 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:00:54.494  4602  4602 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-07 15:00:54.524  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:00:54.596  1500  2403 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 15:00:54.596  1500  2403 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-07 15:00:54.597  1500  2403 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:00:54.597  1500  2403 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:00:54.706  4602  4641 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,09-07 15:00:54.711  4602  4602 W Finsky  : [1] GearheadStateMonitor$3.onConnectionFailed: Could not connect to GMS for Auto connection state: ConnectionResult{statusCode=SERVICE_VERSION_UPDATE_REQUIRED, resolution=null, message=null}
,09-07 15:00:54.711  4602  4602 V Finsky  : [1] GearheadStateMonitor.access$100: mIsProjecting:false
,09-07 15:00:54.733  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,09-07 15:00:54.805  1500  2048 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 15:00:54.805  1500  2048 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-07 15:00:54.806  1500  2048 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 15:00:54.806  1500  2048 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:00:54.879  4602  4602 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-07 15:00:55.255  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:00:55.306  1500  2048 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 15:00:55.306  1500  2048 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-07 15:00:55.306  1500  2048 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:00:55.307  1500  2048 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:00:55.334  4602  4602 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-07 15:00:55.335  4602  4602 D Finsky  : [1] WearSupportService.startHygiene: disabled
,09-07 15:00:55.337  4602  4602 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,09-07 15:00:55.342  4602  4602 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 870 minutes (failures=5)
,09-07 15:00:55.353  4602  4645 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,09-07 15:01:10.090  4575  4650 I BooksSync: Starting books sync for 61035162, extras: ade
,09-07 15:01:10.122  4575  4651 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-07 15:01:10.134  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:01:10.136  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:01:10.160  1500  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 15:01:10.161  1500  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 15:01:10.161  1500  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:01:10.161  1500  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:01:10.195  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:01:10.197  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:01:10.212  1500  2367 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-07 15:01:10.212  1500  2367 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 15:01:10.212  1500  2367 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:01:10.212  1500  2367 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:01:10.225  4575  4651 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-07 15:01:10.226  4575  4650 E BooksSync: Soft error
09-07 15:01:10.226  4575  4650 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 15:01:10.226  4575  4650 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-07 15:01:10.226  4575  4650 E BooksSync: Sync error
09-07 15:01:10.226  4575  4650 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 15:01:10.226  4575  4650 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-07 15:01:10.226  4575  4650 I BooksSync: Finished books sync
,09-07 15:01:10.233   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 297092, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 15:01:10.290  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:01:10.297  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:01:10.299  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:01:10.327  1500  3725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 15:01:10.327  1500  3725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 15:01:10.327  1500  3725 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:01:10.327  1500  3725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:01:10.361  4602  4602 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 15:01:10.362  4602  4602 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 15:01:10.362  4602  4602 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,09-07 15:01:15.195   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=302343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:01:24.542   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=311690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-07 15:01:30.723  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:01:30.741  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:01:30.748  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:01:30.831  1500  2403 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-07 15:01:30.832  1500  2403 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-07 15:01:30.832  1500  2403 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:01:30.833  1500  2403 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:01:30.900  4602  4602 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-07 15:01:30.901  4602  4602 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-07 15:01:30.903  4602  4602 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,09-07 15:01:40.512  3037  4663 V KeepSync: Connecting to GoogleApiClient
,09-07 15:01:40.512   874  2013 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-07 15:01:40.538  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:01:40.546  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:01:40.598  1500  3726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-07 15:01:40.599  1500  3726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 15:01:40.599  1500  3726 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:01:40.599  1500  3726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:01:40.654  3269  4665 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-07 15:01:40.654  3269  4665 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 15:01:40.654  3269  4665 E HttpOperation: 	at jdm.a(PG:82)
09-07 15:01:40.654  3269  4665 E HttpOperation: 	at jcs.o(PG:406)
09-07 15:01:40.654  3269  4665 E HttpOperation: 	at jcn.a(PG:1379)
09-07 15:01:40.654  3269  4665 E HttpOperation: 	at jcs.i(PG:143)
09-07 15:01:40.654  3269  4665 E HttpOperation: 	at blb.a(PG:3937)
09-07 15:01:40.654  3269  4665 E HttpOperation: 	at czp.a(PG:18188)
09-07 15:01:40.654  3269  4665 E HttpOperation: 	at czp.a(PG:9081)
09-07 15:01:40.654  3269  4665 E HttpOperation: 	at czq.run(PG:1686)
09-07 15:01:40.654  3269  4665 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 15:01:40.654  3269  4665 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 15:01:40.654  3269  4665 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 15:01:40.654  3269  4665 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 15:01:40.654  3269  4665 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 15:01:40.654  3269  4665 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 15:01:40.654  3269  4665 E HttpOperation: 	at jdj.a(PG:4091)
09-07 15:01:40.654  3269  4665 E HttpOperation: 	at jdj.a(PG:1125)
09-07 15:01:40.654  3269  4665 E HttpOperation: 	at jdm.a(PG:77)
09-07 15:01:40.654  3269  4665 E HttpOperation: 	... 12 more
09-07 15:01:40.654  3269  4665 E HttpOperation: Caused by: faj: BadAuthentication
09-07 15:01:40.654  3269  4665 E HttpOperation: 	at fal.a(PG:38)
09-07 15:01:40.654  3269  4665 E HttpOperation: 	at jdj.a(PG:4089)
09-07 15:01:40.654  3269  4665 E HttpOperation: 	... 14 more
,09-07 15:01:40.665  1500  2403 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-07 15:01:40.666  1500  2403 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-07 15:01:40.666  1500  2403 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:01:40.666  1500  2403 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:01:40.759  1713  4666 V BaseAuthAsyncOperation: access token request failed
,09-07 15:01:40.761  3037  4663 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-07 15:01:40.774  1500  2048 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 15:01:40.774  1500  2048 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 15:01:40.774  1500  2048 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 15:01:40.774  1500  2048 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:01:40.798  3269  4665 E HttpOperation: [getmobileexperiments] Unexpected exception
09-07 15:01:40.798  3269  4665 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 15:01:40.798  3269  4665 E HttpOperation: 	at jdm.a(PG:82)
09-07 15:01:40.798  3269  4665 E HttpOperation: 	at jcs.o(PG:406)
09-07 15:01:40.798  3269  4665 E HttpOperation: 	at jcn.a(PG:1379)
09-07 15:01:40.798  3269  4665 E HttpOperation: 	at jcs.i(PG:143)
09-07 15:01:40.798  3269  4665 E HttpOperation: 	at hec.a(PG:42)
09-07 15:01:40.798  3269  4665 E HttpOperation: 	at hee.a(PG:102)
09-07 15:01:40.798  3269  4665 E HttpOperation: 	at czr.a(PG:65)
09-07 15:01:40.798  3269  4665 E HttpOperation: 	at kka.a(PG:108)
09-07 15:01:40.798  3269  4665 E HttpOperation: 	at czp.a(PG:19176)
09-07 15:01:40.798  3269  4665 E HttpOperation: 	at czp.a(PG:9081)
09-07 15:01:40.798  3269  4665 E HttpOperation: 	at czq.run(PG:1686)
09-07 15:01:40.798  3269  4665 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 15:01:40.798  3269  4665 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 15:01:40.798  3269  4665 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 15:01:40.798  3269  4665 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 15:01:40.798  3269  4665 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 15:01:40.798  3269  4665 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 15:01:40.798  3269  4665 E HttpOperation: 	at jdj.a(PG:4091)
09-07 15:01:40.798  3269  4665 E HttpOperation: 	at jdj.a(PG:1125)
09-07 15:01:40.798  3269  4665 E HttpOperation: 	at jdm.a(PG:77)
09-07 15:01:40.798  3269  4665 E HttpOperation: 	... 15 more
09-07 15:01:40.798  3269  4665 E HttpOperation: Caused by: faj: BadAuthentication
09-07 15:01:40.798  3269  4665 E HttpOperation: 	at fal.a(PG:38)
09-07 15:01:40.798  3269  4665 E HttpOperation: 	at jdj.a(PG:4089)
09-07 15:01:40.798  3269  4665 E HttpOperation: 	... 17 more
,09-07 15:01:40.799  3269  4665 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-07 15:01:40.799  3269  4665 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-07 15:01:40.799  3269  4665 E ExperimentLoader: 	at jdm.a(PG:82)
09-07 15:01:40.799  3269  4665 E ExperimentLoader: 	at jcs.o(PG:406)
09-07 15:01:40.799  3269  4665 E ExperimentLoader: 	at jcn.a(PG:1379)
09-07 15:01:40.799  3269  4665 E ExperimentLoader: 	at jcs.i(PG:143)
09-07 15:01:40.799  3269  4665 E ExperimentLoader: 	at hec.a(PG:42)
09-07 15:01:40.799  3269  4665 E ExperimentLoader: 	at hee.a(PG:102)
09-07 15:01:40.799  3269  4665 E ExperimentLoader: 	at czr.a(PG:65)
09-07 15:01:40.799  3269  4665 E ExperimentLoader: 	at kka.a(PG:108)
09-07 15:01:40.799  3269  4665 E ExperimentLoader: 	at czp.a(PG:19176)
09-07 15:01:40.799  3269  4665 E ExperimentLoader: 	at czp.a(PG:9081)
09-07 15:01:40.799  3269  4665 E ExperimentLoader: 	at czq.run(PG:1686)
09-07 15:01:40.799  3269  4665 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 15:01:40.799  3269  4665 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 15:01:40.799  3269  4665 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 15:01:40.799  3269  4665 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 15:01:40.799  3269  4665 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-07 15:01:40.799  3269  4665 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 15:01:40.799  3269  4665 E ExperimentLoader: 	at jdj.a(PG:4091)
09-07 15:01:40.799  3269  4665 E ExperimentLoader: 	at jdj.a(PG:1125)
09-07 15:01:40.799  3269  4665 E ExperimentLoader: 	at jdm.a(PG:77)
09-07 15:01:40.799  3269  4665 E ExperimentLoader: 	... 15 more
09-07 15:01:40.799  3269  4665 E ExperimentLoader: Caused by: faj: BadAuthentication
09-07 15:01:40.799  3269  4665 E ExperimentLoader: 	at fal.a(PG:38)
09-07 15:01:40.799  3269  4665 E ExperimentLoader: 	at jdj.a(PG:4089)
09-07 15:01:40.799  3269  4665 E ExperimentLoader: 	... 17 more
,09-07 15:01:40.874  1500  2403 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-07 15:01:40.875  1500  2403 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-07 15:01:40.875  1500  2403 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 15:01:40.875  1500  2403 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:01:40.897  3037  4663 E KeepSync: IOException
09-07 15:01:40.897  3037  4663 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-07 15:01:40.897  3037  4663 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-07 15:01:40.897  3037  4663 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-07 15:01:40.897  3037  4663 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-07 15:01:40.897  3037  4663 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-07 15:01:40.897  3037  4663 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-07 15:01:40.897  3037  4663 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-07 15:01:40.897  3037  4663 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-07 15:01:40.897  3037  4663 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-07 15:01:40.897  3037  4663 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-07 15:01:40.897  3037  4663 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-07 15:01:40.897  3037  4663 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-07 15:01:40.897  3037  4663 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-07 15:01:40.897  3037  4663 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-07 15:01:40.897  3037  4663 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 15:01:40.897  3037  4663 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 15:01:40.897  3037  4663 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-07 15:01:40.897  3037  4663 E KeepSync: 	... 10 more
09-07 15:01:40.898  3037  4663 W KeepSync: Sync result 2
,09-07 15:01:40.912   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 297487, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 15:01:40.968   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 298497, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-07 15:01:49.452   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=336600, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:01:51.175  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:01:51.188  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:01:51.193  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:01:51.261  1500  2403 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-07 15:01:51.261  1500  2403 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-07 15:01:51.262  1500  2403 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:01:51.262  1500  2403 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:01:51.312  4602  4602 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 15:01:51.313  4602  4602 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-07 15:01:51.314  4602  4602 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-07 15:01:54.755   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=341904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:02:11.460  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:02:11.466  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:02:11.468  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:02:11.498  1500  2403 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 15:02:11.498  1500  2403 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 15:02:11.498  1500  2403 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:02:11.499  1500  2403 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:02:11.535  4602  4602 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 15:02:11.535  4602  4602 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 15:02:11.535  4602  4602 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-07 15:02:11.659  4575  4669 I BooksSync: Starting books sync for 61035162, extras: ade
,09-07 15:02:11.677  4575  4670 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-07 15:02:11.707  1500  2367 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 15:02:11.707  1500  2367 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-07 15:02:11.707  1500  2367 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 15:02:11.707  1500  2367 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:02:11.755  1500  3725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 15:02:11.755  1500  3725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-07 15:02:11.755  1500  3725 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:02:11.755  1500  3725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:02:11.781  4575  4670 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-07 15:02:11.782  4575  4669 E BooksSync: Soft error
09-07 15:02:11.782  4575  4669 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 15:02:11.782  4575  4669 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-07 15:02:11.782  4575  4669 E BooksSync: Sync error
09-07 15:02:11.782  4575  4669 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 15:02:11.782  4575  4669 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-07 15:02:11.782  4575  4669 I BooksSync: Finished books sync
,09-07 15:02:11.798   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 358678, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 15:02:13.435   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=360584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:02:19.835   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=366984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:02:38.502   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=385650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:02:39.151  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:02:39.153  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:02:39.165  4550  4672 V GoogleAuthProtoRequest: [383] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 15:02:39.191  1500  2403 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,09-07 15:02:39.191  1500  2403 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
09-07 15:02:39.191  1500  2403 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 15:02:39.191  1500  2403 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:02:39.212  4550  4672 W ExperimentUpdateService: [383] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,09-07 15:02:39.212  4550  4672 W ExperimentUpdateService: [383] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 15:02:39.212  4550  4672 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 15:02:39.212  4550  4672 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-07 15:02:39.212  4550  4672 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
09-07 15:02:39.212  4550  4672 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-07 15:02:39.212  4550  4672 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-07 15:02:39.212  4550  4672 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-07 15:02:39.212  4550  4672 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-07 15:02:39.212  4550  4672 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
09-07 15:02:39.212  4550  4672 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-07 15:02:39.212  4550  4672 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,09-07 15:02:39.255  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:02:39.282  1500  2048 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 15:02:39.282  1500  2048 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 15:02:39.282  1500  2048 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:02:39.282  1500  2048 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:02:39.324  4602  4602 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-07 15:02:39.324  4602  4602 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-07 15:02:39.324  4602  4602 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-07 15:02:43.877  3037  4673 V KeepSync: Connecting to GoogleApiClient
09-07 15:02:43.878   874  2017 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-07 15:02:43.943  1500  3726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-07 15:02:43.943  1500  3726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-07 15:02:43.943  1500  3726 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:02:43.944  1500  3726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:02:43.961  1713  4674 V BaseAuthAsyncOperation: access token request failed
,09-07 15:02:43.963  3037  4673 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-07 15:02:44.007  1500  3723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-07 15:02:44.007  1500  3723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-07 15:02:44.008  1500  3723 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 15:02:44.008  1500  3723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:02:44.028  3037  4673 E KeepSync: IOException
09-07 15:02:44.028  3037  4673 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-07 15:02:44.028  3037  4673 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-07 15:02:44.028  3037  4673 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-07 15:02:44.028  3037  4673 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-07 15:02:44.028  3037  4673 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-07 15:02:44.028  3037  4673 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-07 15:02:44.028  3037  4673 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-07 15:02:44.028  3037  4673 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-07 15:02:44.028  3037  4673 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-07 15:02:44.028  3037  4673 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-07 15:02:44.028  3037  4673 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-07 15:02:44.028  3037  4673 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-07 15:02:44.028  3037  4673 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-07 15:02:44.028  3037  4673 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-07 15:02:44.028  3037  4673 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 15:02:44.028  3037  4673 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 15:02:44.028  3037  4673 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-07 15:02:44.028  3037  4673 E KeepSync: 	... 10 more
,09-07 15:02:44.028  3037  4673 W KeepSync: Sync result 2
,09-07 15:02:44.036   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 390885, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 15:02:44.901   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=392050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:02:54.893  1500  2155 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-07 15:02:59.558  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:02:59.574  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-07 15:02:59.577  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:02:59.635  1500  2048 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 15:02:59.636  1500  2048 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 15:02:59.636  1500  2048 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:02:59.636  1500  2048 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:02:59.685  4602  4602 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 15:02:59.686  4602  4602 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 15:02:59.686  4602  4602 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-07 15:03:04.582   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=411730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:03:10.995   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=418144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:03:14.291  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:03:14.293  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:03:14.341  1500  3725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 15:03:14.341  1500  3725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 15:03:14.342  1500  3725 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 15:03:14.342  1500  3725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:03:14.370  3269  4678 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-07 15:03:14.370  3269  4678 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 15:03:14.370  3269  4678 E HttpOperation: 	at jdm.a(PG:82)
09-07 15:03:14.370  3269  4678 E HttpOperation: 	at jcs.o(PG:406)
09-07 15:03:14.370  3269  4678 E HttpOperation: 	at jcn.a(PG:1379)
09-07 15:03:14.370  3269  4678 E HttpOperation: 	at jcs.i(PG:143)
09-07 15:03:14.370  3269  4678 E HttpOperation: 	at blb.a(PG:3937)
09-07 15:03:14.370  3269  4678 E HttpOperation: 	at czp.a(PG:18188)
09-07 15:03:14.370  3269  4678 E HttpOperation: 	at czp.a(PG:9081)
09-07 15:03:14.370  3269  4678 E HttpOperation: 	at czq.run(PG:1686)
09-07 15:03:14.370  3269  4678 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 15:03:14.370  3269  4678 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 15:03:14.370  3269  4678 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 15:03:14.370  3269  4678 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 15:03:14.370  3269  4678 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 15:03:14.370  3269  4678 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 15:03:14.370  3269  4678 E HttpOperation: 	at jdj.a(PG:4091)
09-07 15:03:14.370  3269  4678 E HttpOperation: 	at jdj.a(PG:1125)
09-07 15:03:14.370  3269  4678 E HttpOperation: 	at jdm.a(PG:77)
09-07 15:03:14.370  3269  4678 E HttpOperation: 	... 12 more
09-07 15:03:14.370  3269  4678 E HttpOperation: Caused by: faj: BadAuthentication
09-07 15:03:14.370  3269  4678 E HttpOperation: 	at fal.a(PG:38)
09-07 15:03:14.370  3269  4678 E HttpOperation: 	at jdj.a(PG:4089)
09-07 15:03:14.370  3269  4678 E HttpOperation: 	... 14 more
,09-07 15:03:14.447  1500  2367 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 15:03:14.448  1500  2367 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 15:03:14.448  1500  2367 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 15:03:14.448  1500  2367 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:03:14.485  3269  4678 E HttpOperation: [getmobileexperiments] Unexpected exception
09-07 15:03:14.485  3269  4678 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 15:03:14.485  3269  4678 E HttpOperation: 	at jdm.a(PG:82)
09-07 15:03:14.485  3269  4678 E HttpOperation: 	at jcs.o(PG:406)
09-07 15:03:14.485  3269  4678 E HttpOperation: 	at jcn.a(PG:1379)
09-07 15:03:14.485  3269  4678 E HttpOperation: 	at jcs.i(PG:143)
09-07 15:03:14.485  3269  4678 E HttpOperation: 	at hec.a(PG:42)
09-07 15:03:14.485  3269  4678 E HttpOperation: 	at hee.a(PG:102)
09-07 15:03:14.485  3269  4678 E HttpOperation: 	at czr.a(PG:65)
09-07 15:03:14.485  3269  4678 E HttpOperation: 	at kka.a(PG:108)
09-07 15:03:14.485  3269  4678 E HttpOperation: 	at czp.a(PG:19176)
09-07 15:03:14.485  3269  4678 E HttpOperation: 	at czp.a(PG:9081)
09-07 15:03:14.485  3269  4678 E HttpOperation: 	at czq.run(PG:1686)
09-07 15:03:14.485  3269  4678 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 15:03:14.485  3269  4678 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 15:03:14.485  3269  4678 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 15:03:14.485  3269  4678 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 15:03:14.485  3269  4678 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 15:03:14.485  3269  4678 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 15:03:14.485  3269  4678 E HttpOperation: 	at jdj.a(PG:4091)
09-07 15:03:14.485  3269  4678 E HttpOperation: 	at jdj.a(PG:1125)
09-07 15:03:14.485  3269  4678 E HttpOperation: 	at jdm.a(PG:77)
09-07 15:03:14.485  3269  4678 E HttpOperation: 	... 15 more
09-07 15:03:14.485  3269  4678 E HttpOperation: Caused by: faj: BadAuthentication
09-07 15:03:14.485  3269  4678 E HttpOperation: 	at fal.a(PG:38)
09-07 15:03:14.485  3269  4678 E HttpOperation: 	at jdj.a(PG:4089)
09-07 15:03:14.485  3269  4678 E HttpOperation: 	... 17 more
,09-07 15:03:14.485  3269  4678 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-07 15:03:14.485  3269  4678 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-07 15:03:14.485  3269  4678 E ExperimentLoader: 	at jdm.a(PG:82)
09-07 15:03:14.485  3269  4678 E ExperimentLoader: 	at jcs.o(PG:406)
09-07 15:03:14.485  3269  4678 E ExperimentLoader: 	at jcn.a(PG:1379)
09-07 15:03:14.485  3269  4678 E ExperimentLoader: 	at jcs.i(PG:143)
09-07 15:03:14.485  3269  4678 E ExperimentLoader: 	at hec.a(PG:42)
09-07 15:03:14.485  3269  4678 E ExperimentLoader: 	at hee.a(PG:102)
09-07 15:03:14.485  3269  4678 E ExperimentLoader: 	at czr.a(PG:65)
09-07 15:03:14.485  3269  4678 E ExperimentLoader: 	at kka.a(PG:108)
09-07 15:03:14.485  3269  4678 E ExperimentLoader: 	at czp.a(PG:19176)
09-07 15:03:14.485  3269  4678 E ExperimentLoader: 	at czp.a(PG:9081)
09-07 15:03:14.485  3269  4678 E ExperimentLoader: 	at czq.run(PG:1686)
09-07 15:03:14.485  3269  4678 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 15:03:14.485  3269  4678 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 15:03:14.485  3269  4678 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 15:03:14.485  3269  4678 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 15:03:14.485  3269  4678 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-07 15:03:14.485  3269  4678 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 15:03:14.485  3269  4678 E ExperimentLoader: 	at jdj.a(PG:4091)
09-07 15:03:14.485  3269  4678 E ExperimentLoader: 	at jdj.a(PG:1125)
09-07 15:03:14.485  3269  4678 E ExperimentLoader: 	at jdm.a(PG:77)
09-07 15:03:14.485  3269  4678 E ExperimentLoader: 	... 15 more
09-07 15:03:14.485  3269  4678 E ExperimentLoader: Caused by: faj: BadAuthentication
09-07 15:03:14.485  3269  4678 E ExperimentLoader: 	at fal.a(PG:38)
09-07 15:03:14.485  3269  4678 E ExperimentLoader: 	at jdj.a(PG:4089)
09-07 15:03:14.485  3269  4678 E ExperimentLoader: 	... 17 more
,09-07 15:03:14.661   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 393135, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-07 15:03:29.702   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=436850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:03:36.088   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=443237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:03:54.768   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=461917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:04:01.141   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=468290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:04:14.453  4575  4683 I BooksSync: Starting books sync for 61035162, extras: ade
,09-07 15:04:14.489  4575  4684 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-07 15:04:14.507  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:04:14.513  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:04:14.554  1500  2048 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 15:04:14.554  1500  2048 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 15:04:14.554  1500  2048 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:04:14.554  1500  2048 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:04:14.594  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:04:14.597  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:04:14.635  1500  2403 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-07 15:04:14.635  1500  2403 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-07 15:04:14.636  1500  2403 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:04:14.636  1500  2403 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:04:14.659  4575  4684 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-07 15:04:14.661  4575  4683 E BooksSync: Soft error
09-07 15:04:14.661  4575  4683 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 15:04:14.661  4575  4683 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-07 15:04:14.663  4575  4683 E BooksSync: Sync error
09-07 15:04:14.663  4575  4683 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 15:04:14.663  4575  4683 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-07 15:04:14.663  4575  4683 I BooksSync: Finished books sync
,09-07 15:04:14.676   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 481539, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 15:04:19.835   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=486983, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:04:26.208   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=493357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:04:44.902   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=512050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:04:49.765  3037  4687 V KeepSync: Connecting to GoogleApiClient
,09-07 15:04:49.766   874  1706 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-07 15:04:49.824  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:04:49.827  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:04:49.866  1500  3726 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-07 15:04:49.866  1500  3726 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-07 15:04:49.866  1500  3726 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 15:04:49.867  1500  3726 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:04:49.889  1713  4688 V BaseAuthAsyncOperation: access token request failed
,09-07 15:04:49.891  3037  4687 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-07 15:04:49.960  1500  3723 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-07 15:04:49.960  1500  3723 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-07 15:04:49.960  1500  3723 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:04:49.961  1500  3723 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:04:49.990  3037  4687 E KeepSync: IOException
09-07 15:04:49.990  3037  4687 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-07 15:04:49.990  3037  4687 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-07 15:04:49.990  3037  4687 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-07 15:04:49.990  3037  4687 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-07 15:04:49.990  3037  4687 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-07 15:04:49.990  3037  4687 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-07 15:04:49.990  3037  4687 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-07 15:04:49.990  3037  4687 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-07 15:04:49.990  3037  4687 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-07 15:04:49.990  3037  4687 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-07 15:04:49.990  3037  4687 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-07 15:04:49.990  3037  4687 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-07 15:04:49.990  3037  4687 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-07 15:04:49.990  3037  4687 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-07 15:04:49.990  3037  4687 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 15:04:49.990  3037  4687 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 15:04:49.990  3037  4687 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-07 15:04:49.990  3037  4687 E KeepSync: 	... 10 more
,09-07 15:04:49.990  3037  4687 W KeepSync: Sync result 2
,09-07 15:04:50.005   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 516833, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 15:04:51.301   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=518450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:04:55.158  1713  4399 V NativeCrypto: SSL shutdown failed: ssl=0x92f5c200: I/O error during system call, Connection timed out
,09-07 15:05:09.968   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=537117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:05:14.523  1500  2155 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-07 15:05:16.395   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=543543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:05:25.052  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:05:25.054  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:05:25.091  1500  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 15:05:25.091  1500  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 15:05:25.091  1500  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:05:25.091  1500  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:05:25.117  3269  4691 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-07 15:05:25.117  3269  4691 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 15:05:25.117  3269  4691 E HttpOperation: 	at jdm.a(PG:82)
09-07 15:05:25.117  3269  4691 E HttpOperation: 	at jcs.o(PG:406)
09-07 15:05:25.117  3269  4691 E HttpOperation: 	at jcn.a(PG:1379)
09-07 15:05:25.117  3269  4691 E HttpOperation: 	at jcs.i(PG:143)
09-07 15:05:25.117  3269  4691 E HttpOperation: 	at blb.a(PG:3937)
09-07 15:05:25.117  3269  4691 E HttpOperation: 	at czp.a(PG:18188)
09-07 15:05:25.117  3269  4691 E HttpOperation: 	at czp.a(PG:9081)
09-07 15:05:25.117  3269  4691 E HttpOperation: 	at czq.run(PG:1686)
09-07 15:05:25.117  3269  4691 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 15:05:25.117  3269  4691 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 15:05:25.117  3269  4691 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 15:05:25.117  3269  4691 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 15:05:25.117  3269  4691 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 15:05:25.117  3269  4691 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 15:05:25.117  3269  4691 E HttpOperation: 	at jdj.a(PG:4091)
09-07 15:05:25.117  3269  4691 E HttpOperation: 	at jdj.a(PG:1125)
09-07 15:05:25.117  3269  4691 E HttpOperation: 	at jdm.a(PG:77)
09-07 15:05:25.117  3269  4691 E HttpOperation: 	... 12 more
09-07 15:05:25.117  3269  4691 E HttpOperation: Caused by: faj: BadAuthentication
09-07 15:05:25.117  3269  4691 E HttpOperation: 	at fal.a(PG:38)
09-07 15:05:25.117  3269  4691 E HttpOperation: 	at jdj.a(PG:4089)
09-07 15:05:25.117  3269  4691 E HttpOperation: 	... 14 more
,09-07 15:05:25.226  1500  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 15:05:25.226  1500  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 15:05:25.226  1500  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 15:05:25.226  1500  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:05:25.248  3269  4691 E HttpOperation: [getmobileexperiments] Unexpected exception
09-07 15:05:25.248  3269  4691 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 15:05:25.248  3269  4691 E HttpOperation: 	at jdm.a(PG:82)
09-07 15:05:25.248  3269  4691 E HttpOperation: 	at jcs.o(PG:406)
09-07 15:05:25.248  3269  4691 E HttpOperation: 	at jcn.a(PG:1379)
09-07 15:05:25.248  3269  4691 E HttpOperation: 	at jcs.i(PG:143)
09-07 15:05:25.248  3269  4691 E HttpOperation: 	at hec.a(PG:42)
09-07 15:05:25.248  3269  4691 E HttpOperation: 	at hee.a(PG:102)
09-07 15:05:25.248  3269  4691 E HttpOperation: 	at czr.a(PG:65)
09-07 15:05:25.248  3269  4691 E HttpOperation: 	at kka.a(PG:108)
09-07 15:05:25.248  3269  4691 E HttpOperation: 	at czp.a(PG:19176)
09-07 15:05:25.248  3269  4691 E HttpOperation: 	at czp.a(PG:9081)
09-07 15:05:25.248  3269  4691 E HttpOperation: 	at czq.run(PG:1686)
09-07 15:05:25.248  3269  4691 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 15:05:25.248  3269  4691 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 15:05:25.248  3269  4691 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 15:05:25.248  3269  4691 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 15:05:25.248  3269  4691 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 15:05:25.248  3269  4691 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 15:05:25.248  3269  4691 E HttpOperation: 	at jdj.a(PG:4091)
09-07 15:05:25.248  3269  4691 E HttpOperation: 	at jdj.a(PG:1125)
09-07 15:05:25.248  3269  4691 E HttpOperation: 	at jdm.a(PG:77)
09-07 15:05:25.248  3269  4691 E HttpOperation: 	... 15 more
09-07 15:05:25.248  3269  4691 E HttpOperation: Caused by: faj: BadAuthentication
09-07 15:05:25.248  3269  4691 E HttpOperation: 	at fal.a(PG:38)
09-07 15:05:25.248  3269  4691 E HttpOperation: 	at jdj.a(PG:4089)
09-07 15:05:25.248  3269  4691 E HttpOperation: 	... 17 more
,09-07 15:05:25.248  3269  4691 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-07 15:05:25.248  3269  4691 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-07 15:05:25.248  3269  4691 E ExperimentLoader: 	at jdm.a(PG:82)
09-07 15:05:25.248  3269  4691 E ExperimentLoader: 	at jcs.o(PG:406)
09-07 15:05:25.248  3269  4691 E ExperimentLoader: 	at jcn.a(PG:1379)
09-07 15:05:25.248  3269  4691 E ExperimentLoader: 	at jcs.i(PG:143)
09-07 15:05:25.248  3269  4691 E ExperimentLoader: 	at hec.a(PG:42)
09-07 15:05:25.248  3269  4691 E ExperimentLoader: 	at hee.a(PG:102)
09-07 15:05:25.248  3269  4691 E ExperimentLoader: 	at czr.a(PG:65)
09-07 15:05:25.248  3269  4691 E ExperimentLoader: 	at kka.a(PG:108)
09-07 15:05:25.248  3269  4691 E ExperimentLoader: 	at czp.a(PG:19176)
09-07 15:05:25.248  3269  4691 E ExperimentLoader: 	at czp.a(PG:9081)
09-07 15:05:25.248  3269  4691 E ExperimentLoader: 	at czq.run(PG:1686)
09-07 15:05:25.248  3269  4691 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 15:05:25.248  3269  4691 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 15:05:25.248  3269  4691 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 15:05:25.248  3269  4691 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 15:05:25.248  3269  4691 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-07 15:05:25.248  3269  4691 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 15:05:25.248  3269  4691 E ExperimentLoader: 	at jdj.a(PG:4091)
09-07 15:05:25.248  3269  4691 E ExperimentLoader: 	at jdj.a(PG:1125)
09-07 15:05:25.248  3269  4691 E ExperimentLoader: 	at jdm.a(PG:77)
09-07 15:05:25.248  3269  4691 E ExperimentLoader: 	... 15 more
09-07 15:05:25.248  3269  4691 E ExperimentLoader: Caused by: faj: BadAuthentication
09-07 15:05:25.248  3269  4691 E ExperimentLoader: 	at fal.a(PG:38)
09-07 15:05:25.248  3269  4691 E ExperimentLoader: 	at jdj.a(PG:4089)
09-07 15:05:25.248  3269  4691 E ExperimentLoader: 	... 17 more
,09-07 15:05:25.346   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 551846, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-07 15:05:35.035   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=562183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:05:41.448   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=568597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:05:49.517  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:05:49.524  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:05:49.529  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:05:49.577  1500  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 15:05:49.577  1500  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-07 15:05:49.577  1500  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 15:05:49.578  1500  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:05:49.601  1500  1513 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 15:05:49.601  1500  1513 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 15:05:49.601  1500  1513 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 15:05:49.601  1500  1513 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-07 15:05:49.601  1500  1513 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-07 15:05:49.601  1500  1513 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-07 15:05:49.601  1500  1513 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-07 15:05:49.604  4602  4631 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-07 15:05:49.604  4602  4631 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-07 15:05:49.604  4602  4631 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-07 15:05:49.604  4602  4631 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-07 15:05:49.604  4602  4631 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-07 15:05:49.604  4602  4631 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-07 15:05:49.604  4602  4631 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-07 15:06:25.222   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=612370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:06:31.648   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=618797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:06:39.393  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:06:39.399  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:06:39.413  4550  4700 V GoogleAuthProtoRequest: [384] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 15:06:39.445  1500  3725 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,09-07 15:06:39.445  1500  3725 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
09-07 15:06:39.445  1500  3725 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 15:06:39.445  1500  3725 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:06:39.468  4550  4700 W ExperimentUpdateService: [384] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,09-07 15:06:39.469  4550  4700 W ExperimentUpdateService: [384] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 15:06:39.469  4550  4700 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 15:06:39.469  4550  4700 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-07 15:06:39.469  4550  4700 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
09-07 15:06:39.469  4550  4700 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-07 15:06:39.469  4550  4700 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-07 15:06:39.469  4550  4700 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-07 15:06:39.469  4550  4700 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-07 15:06:39.469  4550  4700 W ExperimentUpdateService: 	,at com.a.a.a.g.a(SourceFile:79)
09-07 15:06:39.469  4550  4700 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-07 15:06:39.469  4550  4700 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,09-07 15:06:50.342   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=637490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:06:56.755   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=643904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:07:15.408   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=662557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:07:21.821   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=668970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:07:40.475   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=687624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:07:46.875   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=694024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:08:05.542   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=712690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:08:11.929   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=719077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:08:30.609   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=737757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:08:36.995   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=744143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:08:55.675   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=762824, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:09:02.061   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=769210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:09:20.741   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=787890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:09:27.115   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=794264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:09:45.808   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=812957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:09:52.181   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=819330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:10:10.822   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=837971, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:10:17.248   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=844397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:10:35.888   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=863037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:10:42.301   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=869450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:11:00.955   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=888104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:11:07.355   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=894504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:11:14.581   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=901730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:11:32.555   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=919704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:11:39.941   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=927090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:11:57.929   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=945077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:12:05.169   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=952317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:12:23.142   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=970290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:12:30.262   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=977410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:12:48.235   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=995384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:12:55.382   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1002530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:13:13.368   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1020517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:13:20.555   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1027703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:13:38.515   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1045663, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:13:45.595   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1052743, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:14:03.582   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1070731, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:14:10.689   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1077837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:14:28.662   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1095810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:14:35.834   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1102983, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:14:53.821   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1120970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:15:00.955   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1128104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:15:17.771  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:15:17.776  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 15:15:17.784  4550  4727 V GoogleAuthProtoRequest: [385] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 15:15:17.812  1500  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,09-07 15:15:17.812  1500  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
09-07 15:15:17.812  1500  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 15:15:17.812  1500  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 15:15:17.839  4550  4727 W ExperimentUpdateService: [385] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,09-07 15:15:17.839  4550  4727 W ExperimentUpdateService: [385] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 15:15:17.839  4550  4727 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-07 15:15:17.839  4550  4727 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-07 15:15:17.839  4550  4727 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
09-07 15:15:17.839  4550  4727 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-07 15:15:17.839  4550  4727 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-07 15:15:17.839  4550  4727 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-07 15:15:17.839  4550  4727 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-07 15:15:17.839  4550  4727 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
09-07 15:15:17.839  4550  4727 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-07 15:15:17.839  4550  4727 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,09-07 15:15:18.929   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1146077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:15:29.888   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1157037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:15:44.008   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1171157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:15:51.088   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1178237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:16:09.062   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1196210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:16:26.661   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1213810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:16:31.401   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,09-07 15:16:34.235   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1221384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:16:51.728   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1238877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:16:59.302   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1246450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:17:16.795   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1263944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:17:24.395   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1271543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:17:41.862   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1289011, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:17:49.449   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1296597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:18:06.982   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1314130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:18:14.595   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1321744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:18:32.102   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1339250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:18:39.648   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1346797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:18:57.168   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1364317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:19:04.728   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1371877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:19:22.235   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1389384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:19:29.795   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1396943, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:19:47.302   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1414450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:19:54.928   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1422077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:20:12.421   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1439570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:20:19.995   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1447143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:20:37.488   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1464637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:20:45.061   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1472210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:21:02.554   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1489703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:21:10.155   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1497303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 15:21:23.542   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1510690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 15:21:35.208   874  4517 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1522357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,TIME-OUT KILL (timeout was 1400000ms),09-07 15:21:43.372  4747  4747 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-07 15:21:43.376  4747  4747 D AndroidRuntime: CheckJNI is OFF
09-07 15:21:43.412  4747  4747 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-07 15:21:43.454  4747  4747 I Radio-JNI: register_android_hardware_Radio DONE
09-07 15:21:43.474  4747  4747 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-07 15:21:43.483   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-07 15:21:43.485   874   887 I ActivityManager: Killing 3465:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-07 15:21:43.595   874  2020 I WindowState: WIN DEATH: Window{631368c u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 15:21:43.596   874  1304 D WifiService: Client connection lost with reason: 4
09-07 15:21:43.596   874  1688 D GraphicsStats: Buffer count: 2
09-07 15:21:43.617   874   897 W PackageSettings: Skipping PackageSetting{b051190 com.example.hello/10273} due to missing metadata
09-07 15:21:43.643   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-07 15:21:43.643   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-07 15:21:43.644   874   887 E ActivityManager: Failure starting process com.test.thalitest
09-07 15:21:43.644   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-07 15:21:43.644   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-07 15:21:43.644   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-07 15:21:43.644   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-07 15:21:43.644   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-07 15:21:43.644   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-07 15:21:43.644   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-07 15:21:43.644   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-07 15:21:43.644   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-07 15:21:43.644   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-07 15:21:43.644   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-07 15:21:43.644   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-07 15:21:43.644   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-07 15:21:43.644   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-07 15:21:43.644   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-07 15:21:43.644   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:21:43.644   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:21:43.644   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 15:21:43.644   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-07 15:21:43.644   874   887 I ActivityManager:   Force finishing activity ActivityRecord{2979b3d u0 com.test.thalitest/.MainActivity t4}
09-07 15:21:43.645   874   897 I art     : Starting a blocking GC Explicit
09-07 15:21:43.653   874  2014 W ActivityManager: Spurious death for ProcessRecord{449516c 0:com.test.thalitest/u0a0}, curProc for 3465: null
09-07 15:21:43.689   874   897 I art     : Explicit concurrent mark sweep GC freed 51736(4MB) AllocSpace objects, 7(140KB) LOS objects, 33% free, 29MB/44MB, paused 698us total 43.542ms
09-07 15:21:43.729   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-07 15:21:43.735  4747  4747 I art     : System.exit called, status: 0
09-07 15:21:43.735  4747  4747 I AndroidRuntime: VM exiting with result code 0.
09-07 15:21:43.791   874   897 I ActivityManager: Start proc 4760:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
09-07 15:21:43.792   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-07 15:21:43.816   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-07 15:21:43.832  1891  1891 I Keyboard.Facilitator: resetDictionaries() : en_US
09-07 15:21:43.833  4154  4154 D BluetoothMapAppObserver: onReceive
09-07 15:21:43.834  4154  4154 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-07 15:21:43.835  1858  2234 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-07 15:21:43.838   874  1294 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-07 15:21:43.850  3335  3335 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-07 15:21:43.851  1891  4773 I Keyboard.Facilitator.DecoderInitializer: run()
09-07 15:21:43.854  1891  4773 I Decoder : createOrResetDecoder
09-07 15:21:43.885   874  1301 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
09-07 15:21:43.899  1956  1956 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-07 15:21:43.910   874  1978 I ActivityManager: Start proc 4776:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-07 15:21:43.935   874  2017 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3465 uid 10000
09-07 15:21:43.935   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-07 15:21:43.947  1891  1891 I Keyboard.Facilitator: onFinishInput()
09-07 15:21:43.918  4424  4779 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-07 15:21:43.913  4424  4441 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-07 15:21:43.959  1500  1500 I ConfigService: onCreate
--------- beginning of crash
09-07 15:21:43.968  4424  4441 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-07 15:21:43.968  4424  4441 E AndroidRuntime: Process: android.process.acore, PID: 4424
09-07 15:21:43.968  4424  4441 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 15:21:43.968  4424  4441 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-07 15:21:43.968  4424  4441 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-07 15:21:43.968  4424  4441 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-07 15:21:43.968  4424  4441 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-07 15:21:43.968  4424  4441 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-07 15:21:43.968  4424  4441 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
09-07 15:21:43.968  4424  4441 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
09-07 15:21:43.968  4424  4441 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-07 15:21:43.968  4424  4441 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-07 15:21:43.968  4424  4441 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-07 15:21:43.968  4424  4441 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:21:43.968  4424  4441 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:21:43.968  4424  4441 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 15:21:43.972  1500  4789 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-07 15:21:43.972  1500  4789 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:21:43.972  1500  4789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:21:43.972  1500  4789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 15:21:43.972  1500  4789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 15:21:43.972  1500  4789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 15:21:43.972  1500  4789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 15:21:43.972  1500  4789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 15:21:43.972  1500  4789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 15:21:43.972  1500  4789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 15:21:43.972  1500  4789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 15:21:43.972  1500  4789 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 15:21:43.972  1500  4789 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 15:21:43.972  1500  4789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:21:43.972  1500  4789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:21:43.972  1500  4789 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-07 15:21:43.972  1500  4789 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-07 15:21:43.972  1500  4789 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-07 15:21:43.972  1500  4789 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-07 15:21:43.972  1500  4789 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 15:21:43.972  1500  4789 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 15:21:43.972  1500  4789 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 15:21:43.972  1500  4789 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 15:21:43.972  1500  4789 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 15:21:43.972  1500  4789 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 15:21:43.972  1500  4789 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 15:21:43.972  1500  4789 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 15:21:43.972  1500  4789 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 15:21:43.972  1500  4789 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 15:21:43.972  1500  4789 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 15:21:43.972  1500  4789 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 15:21:43.972  1500  4789 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 15:21:43.972  1500  4789 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 15:21:43.972  1500  4789 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-07 15:21:43.972  1500  4789 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-07 15:21:43.972  1500  4789 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-07 15:21:43.978  1500  4789 W SQLiteOpenHelper: Opened config.db in read-only mode
09-07 15:21:43.982  4776  4776 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-07 15:21:43.977  4424  4779 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
09-07 15:21:43.984  4424  4779 I Process : Sending signal. PID: 4424 SIG: 9
09-07 15:21:43.986  1969  2058 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-07 15:21:43.986   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-07 15:21:43.987   874   886 E PackageManager: Failed to write settings, restoring backup
09-07 15:21:43.987   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-07 15:21:43.987   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-07 15:21:43.987   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-07 15:21:43.987   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-07 15:21:43.987   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-07 15:21:43.987   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:21:43.987   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:21:43.987   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 15:21:43.991   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-07 15:21:43.991   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-07 15:21:43.991   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 15:21:43.991   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 15:21:43.991   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 15:21:43.991   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 15:21:43.991   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 15:21:43.991   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 15:21:43.991   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-07 15:21:43.991   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-07 15:21:43.991   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-07 15:21:43.991   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 15:21:43.991   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 15:21:43.991   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:21:43.991   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 15:21:43.991   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-07 15:21:43.991   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 15:21:43.991   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 15:21:43.991   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 15:21:43.991   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 15:21:43.991   874   887 E DropBoxManagerService: 	... 13 more
09-07 15:21:44.000   874  1971 I ActivityManager: Start proc 4790:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
09-07 15:21:44.001  1969  2058 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-07 15:21:44.001  1969  2058 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1969
09-07 15:21:44.001  1969  2058 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 15:21:44.001  1969  2058 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-07 15:21:44.001  1969  2058 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-07 15:21:44.001  1969  2058 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-07 15:21:44.001  1969  2058 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-07 15:21:44.001  1969  2058 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-07 15:21:44.001  1969  2058 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-07 15:21:44.001  1969  2058 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-07 15:21:44.001  1969  2058 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 15:21:44.001  1969  2058 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 15:21:44.001  1969  2058 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:21:44.001  1969  2058 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 15:21:44.007   874  2017 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 15:21:44.007   874  4800 E DropBoxManagerService: Can't write: system_app_crash
09-07 15:21:44.007   874  4800 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
09-07 15:21:44.007   874  4800 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 15:21:44.007   874  4800 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 15:21:44.007   874  4800 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 15:21:44.007   874  4800 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 15:21:44.007   874  4800 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 15:21:44.007   874  4800 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 15:21:44.007   874  4800 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 15:21:44.007   874  4800 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 15:21:44.007   874  4800 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 15:21:44.007   874  4800 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 15:21:44.007   874  4800 E DropBoxManagerService: 	... 5 more
09-07 15:21:44.011  1969  2058 I Process : Sending signal. PID: 1969 SIG: 9
09-07 15:21:44.024  1891  4773 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-07 15:21:44.057  1500  1500 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-07 15:21:44.058  1500  1500 D AndroidRuntime: Shutting down VM
09-07 15:21:44.058   279   279 E lowmemorykiller: Error writing /proc/4424/oom_score_adj; errno=22
09-07 15:21:44.059   279   279 E lowmemorykiller: Error writing /proc/4424/oom_score_adj; errno=22
09-07 15:21:44.059  1500  1500 E AndroidRuntime: FATAL EXCEPTION: main
09-07 15:21:44.059  1500  1500 E AndroidRuntime: Process: com.google.process.gapps, PID: 1500
09-07 15:21:44.059  1500  1500 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 15:21:44.059  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-07 15:21:44.059  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-07 15:21:44.059  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-07 15:21:44.059  1500  1500 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 15:21:44.059  1500  1500 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 15:21:44.059  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 15:21:44.059  1500  1500 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 15:21:44.059  1500  1500 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 15:21:44.059  1500  1500 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 15:21:44.059  1500  1500 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 15:21:44.059  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-07 15:21:44.059  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-07 15:21:44.059  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-07 15:21:44.059  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-07 15:21:44.059  1500  1500 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-07 15:21:44.059  1500  1500 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-07 15:21:44.059  1500  1500 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-07 15:21:44.059  1500  1500 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-07 15:21:44.059  1500  1500 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-07 15:21:44.059  1500  1500 E AndroidRuntime: 	... 8 more
09-07 15:21:44.063   874  4806 E DropBoxManagerService: Can't write: system_app_crash
09-07 15:21:44.063   874  4806 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
09-07 15:21:44.063   874  4806 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 15:21:44.063   874  4806 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 15:21:44.063   874  4806 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 15:21:44.063   874  4806 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 15:21:44.063   874  4806 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 15:21:44.063   874  4806 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 15:21:44.063   874  4806 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 15:21:44.063   874  4806 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 15:21:44.063   874  4806 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 15:21:44.063   874  4806 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 15:21:44.063   874  4806 E DropBoxManagerService: 	... 5 more
09-07 15:21:44.064   279   279 E lowmemorykiller: Error writing /proc/4424/oom_score_adj; errno=22
09-07 15:21:44.064  1500  1500 I Process : Sending signal. PID: 1500 SIG: 9
09-07 15:21:44.079   279   279 E lowmemorykiller: Error writing /proc/4424/oom_score_adj; errno=22
09-07 15:21:44.080   874  1971 I ActivityManager: Killing 2082:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
09-07 15:21:44.097  1891  4773 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-07 15:21:44.099  1891  4773 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-07 15:21:44.099  1891  4773 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-07 15:21:44.101  1891  4773 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-07 15:21:44.101  1891  4773 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-07 15:21:44.103  1891  4773 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-07 15:21:44.103  1891  4773 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-07 15:21:44.104  1891  4773 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-07 15:21:44.104  1891  4773 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-07 15:21:44.104  1891  4773 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-07 15:21:44.104  1891  4773 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-07 15:21:44.104  1891  4773 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-07 15:21:44.104  1891  4773 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-07 15:21:44.114   874  1304 D WifiService: Client connection lost with reason: 4
09-07 15:21:44.142   874  2020 D GraphicsStats: Buffer count: 1
09-07 15:21:44.142   874  1689 I WindowState: WIN DEATH: Window{6fd3458 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-07 15:21:44.152   874  1380 I ActivityManager: Process com.google.process.gapps (pid 1500) has died
09-07 15:21:44.153   874  1380 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
09-07 15:21:44.153   874  1380 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
09-07 15:21:44.153   874  1380 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
09-07 15:21:44.162  1713  1713 W RocketImpressions: ClearcutLogger connection suspended: 1
09-07 15:21:44.171   874  1688 I ActivityManager: Process android.process.acore (pid 4424) has died
09-07 15:21:44.171   874  1688 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30982ms
09-07 15:21:44.174   874  2020 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1969) has died
09-07 15:21:44.174   874  2020 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 30979ms
09-07 15:21:44.175   874  2020 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-07 15:21:44.190   874  1687 I ActivityManager: Start proc 4809:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
09-07 15:21:44.205   874   887 I ActivityManager: Start proc 4821:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL

```
