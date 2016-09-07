#### Test 83627337a1c904e_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-07 09:34:24.538   876  1871 D NetlinkSocketObserver: NeighborEvent{elapsedMs=111944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-07 09:34:25.213  3811  3811 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-07 09:34:25.218  3811  3811 D AndroidRuntime: CheckJNI is OFF
09-07 09:34:25.260  3811  3811 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-07 09:34:25.310  3811  3811 I Radio-JNI: register_android_hardware_Radio DONE
09-07 09:34:25.332  3811  3811 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-07 09:34:25.336   876   887 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-07 09:34:25.371  2062  2077 W SearchService: Abort, client detached.
09-07 09:34:25.379  2062  2062 I HotwordDetector: Closing mic
09-07 09:34:25.379  2062  2343 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@44c09f4
09-07 09:34:25.380  3811  3811 D AndroidRuntime: Shutting down VM
09-07 09:34:25.380  2062  2362 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-07 09:34:25.423   876  1727 I ActivityManager: Start proc 3820:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-07 09:34:25.460   378  2365 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-07 09:34:25.461   378  2365 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-07 09:34:25.466   378  1290 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-07 09:34:25.468  2062  2357 I MicroRecognitionRnrImpl: Detection finished
09-07 09:34:25.469  2062  2350 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-07 09:34:25.521  3820  3820 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-07 09:34:25.549  3820  3820 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-07 09:34:25.556  3820  3820 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2959-2963)
09-07 09:34:25.557  3820  3820 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 09:34:25.579  3820  3820 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c019524}
09-07 09:34:25.579  3820  3820 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 09:34:25.579  3820  3820 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-07 09:34:25.586  3820  3820 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-07 09:34:25.588  3820  3820 E SysUtils: ApplicationContext is null in ApplicationStatus
09-07 09:34:25.601  3820  3820 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-07 09:34:25.611  3820  3820 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 09:34:25.611  3820  3820 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 09:34:25.611  3820  3820 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 09:34:25.611  3820  3820 I Adreno  : Build Date                       : 10/20/15
09-07 09:34:25.611  3820  3820 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 09:34:25.611  3820  3820 I Adreno  : Local Branch                     : M14
09-07 09:34:25.611  3820  3820 I Adreno  : Remote Branch                    : 
09-07 09:34:25.611  3820  3820 I Adreno  : Remote Branch                    : 
09-07 09:34:25.611  3820  3820 I Adreno  : Reconstruct Branch               : 
09-07 09:34:25.658   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22be58d:true
09-07 09:34:25.694  3820  3820 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-07 09:34:25.708  3820  3820 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
09-07 09:34:25.751  3820  3858 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-07 09:34:25.765  3820  3845 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
09-07 09:34:25.806  3820  3858 I OpenGLRenderer: Initialized EGL, version 1.4
09-07 09:34:25.863   876   894 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +457ms
09-07 09:34:25.870  1894  1894 I Keyboard.Facilitator: onFinishInput()
09-07 09:34:25.933  3820  3820 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3820
09-07 09:34:26.025  3820  3820 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-07 09:34:26.173  3820  3861 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1697777360
09-07 09:34:26.178  3820  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 09:34:26.178  3820  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 09:34:26.178  3820  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 09:34:26.178  3820  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 09:34:26.178  3820  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-07 09:34:26.179  3820  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a1a608b added. We now have 1 listener(s)
09-07 09:34:26.182  3820  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
09-07 09:34:26.183  3820  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 09:34:26.184  3820  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 09:34:26.184  3820  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 09:34:26.188  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 09:34:26.188  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 09:34:26.188  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 09:34:26.188  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-07 09:34:26.188  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 09:34:26.188  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 09:34:26.188  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 09:34:26.188  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 09:34:26.188  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 09:34:26.188  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 09:34:26.188  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 09:34:26.188  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 09:34:26.188  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 09:34:26.188  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-07 09:34:26.189  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e6f7e26 added. We now have 1 listener(s)
09-07 09:34:26.189  3820  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 09:34:26.192   876  1321 D WifiService: New client listening to asynchronous messages
09-07 09:34:26.193  3820  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 09:34:26.193  3820  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-07 09:34:26.193  3820  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-07 09:34:26.193  3820  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-07 09:34:26.193  3820  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-07 09:34:26.198  3820  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:34:26.201  3820  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
09-07 09:34:26.215  3820  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-07 09:34:26.215  3820  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:34:26.215  3820  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:34:26.215  3820  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:34:26.215  3820  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:34:26.215  3820  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:34:26.215  3820  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:34:26.215  3820  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:34:26.215  3820  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:34:26.216  3820  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-07 09:34:26.216  3820  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 09:34:26.217  3820  3861 I io.jxcore.node.LifeCycleMonitor: start: OK
09-07 09:34:26.218  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:34:26.219  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:34:26.249  3820  3820 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-07 09:34:26.266   876  1707 I ActivityManager: Killing 3241:com.google.android.gm/u0a78 (adj 15): empty #17
09-07 09:34:26.319   876  1707 I ActivityManager: Killing 3152:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,09-07 09:34:27.186  3820  3869 W jxcore-log: Initializing JXcore engine
,09-07 09:34:27.186  3820  3869 W jxcore-log: JXcore engine is ready
,09-07 09:34:27.220  3869  3869 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8949 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-07 09:34:27.220  3869  3869 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10762]" dev="sockfs" ino=10762 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-07 09:34:27.220  3869  3869 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-07 09:34:27.220  3869  3869 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26415]" dev="sockfs" ino=26415 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-07 09:34:27.236  3820  3869 W jxcore-log: Starting JXcore engine
,09-07 09:34:27.314  3820  3869 W jxcore-log: Platform android
09-07 09:34:27.314  3820  3869 W jxcore-log: 
,09-07 09:34:27.314  3820  3869 W jxcore-log: Process ARCH arm
09-07 09:34:27.314  3820  3869 W jxcore-log: 
,09-07 09:34:27.544  3820  3869 I jxcore-log: JXcore Cordova bridge is ready!
09-07 09:34:27.544  3820  3869 I jxcore-log: 
09-07 09:34:27.545  3820  3869 W jxcore-log: JXcore engine is started
,09-07 09:34:27.557  3820  3861 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-07 09:34:27.563  3820  3820 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-07 09:34:35.670   876  1319 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-07 09:34:35.711  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:34:35.716  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:34:35.717  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:34:35.737  1524  2441 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 09:34:35.737  1524  2441 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 09:34:35.737  1524  2441 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 09:34:35.737  1524  2441 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,09-07 09:34:35.754  3541  3541 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 09:34:35.755  3541  3541 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-07 09:34:35.755  3541  3541 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-07 09:34:37.362  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 09:34:37.362  3820  3869 I jxcore-log: 
,09-07 09:34:37.365  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 09:34:37.365  3820  3869 I jxcore-log: 
,09-07 09:34:37.377  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:34:37.377  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:34:37.377  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:34:37.377  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:34:37.377  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:34:37.377  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:34:37.377  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:34:37.377  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 09:34:37.382  3820  3869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 09:34:37.385  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 09:34:37.385  3820  3869 I jxcore-log: 
,09-07 09:34:37.387  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 09:34:37.387  3820  3869 I jxcore-log: 
,09-07 09:34:37.900  3820  3869 I jxcore-log: Unit Test app is loaded
09-07 09:34:37.900  3820  3869 I jxcore-log: 
,09-07 09:34:37.906  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:34:37.906  3820  3869 I jxcore-log: 
,09-07 09:34:37.911  3820  3869 D executeNativeTests: Running unit tests
,09-07 09:34:37.927  3820  3820 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-07 09:34:37.970  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 09:34:37.970  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fa5238 added. We now have 2 listener(s)
,09-07 09:34:37.971  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 09:34:37.971  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 09:34:37.971  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 09:34:37.971  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 09:34:37.971  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f24211 added. We now have 2 listener(s)
09-07 09:34:37.971  3820  3869 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 09:34:37.972  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 09:34:37.974  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:34:37.979  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:34:37.979  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:34:37.979  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:34:37.979  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:34:37.979  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:34:37.979  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:34:37.979  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:34:37.979  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 09:34:37.981  3820  3869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 09:34:37.981  3820  3869 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 09:34:38.007  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:34:38.010  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:34:38.016  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 09:34:38.017  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 09:34:38.017  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 09:34:38.022  3820  3869 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-07 09:34:38.023  3820  3869 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-07 09:34:38.023  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 09:34:38.024  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 09:34:38.024  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 09:34:38.027  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:34:38.027  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 09:34:38.027  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 09:34:38.027  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 09:34:38.027  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fa5238 removed from the list
,09-07 09:34:38.027  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:34:38.027  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f24211 removed from the list
09-07 09:34:38.027  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:34:38.028  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:34:38.033  3820  3869 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-07 09:34:38.034  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 09:34:38.034  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:34:38.034  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:34:38.035  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fa5238 not in the list
,09-07 09:34:38.035  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:34:38.035  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f24211 not in the list
09-07 09:34:38.035  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:34:38.035  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:34:38.035  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:34:38.044  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-07 09:34:38.044  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-07 09:34:38.044  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 09:34:38.044  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-07 09:34:38.044  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 09:34:38.044  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-07 09:34:38.044  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 09:34:38.044  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-07 09:34:38.044  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 09:34:38.044  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 09:34:38.044  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-07 09:34:38.044  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-07 09:34:38.044  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 09:34:38.044  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-07 09:34:38.045  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 09:34:38.045  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-07 09:34:38.045  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 09:34:38.045  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 09:34:38.045  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 09:34:38.045  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 09:34:38.045  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 09:34:38.045  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 09:34:38.045  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 09:34:38.045  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 09:34:38.045  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 09:34:38.045  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 09:34:38.045  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 09:34:38.045  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 09:34:38.045  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 09:34:38.046  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 09:34:38.046  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 09:34:38.046  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:34:38.046  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:34:38.046  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:34:38.047  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fa5238 not in the list
09-07 09:34:38.047  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:34:38.047  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f24211 not in the list
09-07 09:34:38.047  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:34:38.047  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:34:38.047  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:34:38.048  3820  3869 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-07 09:34:38.049  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:34:38.054  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:34:38.054  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:34:38.054  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:34:38.054  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:34:38.054  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:34:38.054  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:34:38.054  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:34:38.054  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 09:34:38.056  3820  3869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 09:34:38.056  3820  3869 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 09:34:38.056  3820  3869 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-07 09:34:38.057  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-07 09:34:38.057  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 09:34:38.057  3820  3869 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-07 09:34:38.057  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 09:34:38.057  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:34:38.058  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 09:34:38.058  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:34:38.061  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:34:38.062  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-07 09:34:38.062  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 09:34:38.062  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 09:34:38.063  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 09:34:38.063  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 09:34:38.063  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:34:38.063  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 09:34:38.064  3820  3881 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 09:34:38.067  3820  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-07 09:34:38.067  3820  3869 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 09:34:38.067  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 09:34:38.075  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 09:34:38.077  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-07 09:34:38.078  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 09:34:38.080  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-07 09:34:38.081  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 09:34:38.081  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-07 09:34:38.082  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 09:34:38.082  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 09:34:38.082  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-07 09:34:38.083  3820  3869 D BluetoothAdapter: STATE_ON
,09-07 09:34:38.090  2721  2919 D BtGatt.GattService: registerClient() - UUID=6254cf16-0a21-4d02-82c6-85e1f9b585ef
,09-07 09:34:38.091  2721  2775 D BtGatt.GattService: onClientRegistered() - UUID=6254cf16-0a21-4d02-82c6-85e1f9b585ef, clientIf=5
09-07 09:34:38.091  3820  3831 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-07 09:34:38.092  2721  2781 D BtGatt.AdvertiseManager: message : 0
,09-07 09:34:38.096  2721  2781 D BtGatt.AdvertiseManager: starting multi advertising
,09-07 09:34:38.110  2721  2775 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-07 09:34:38.119  2721  2775 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-07 09:34:38.121  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-07 09:34:38.121  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 09:34:38.127  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 09:34:38.131  3820  3869 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 09:34:38.132  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 09:34:38.132  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-07 09:34:38.132  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-07 09:34:38.132  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-07 09:34:38.133  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-07 09:34:38.133  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-07 09:34:38.135  3820  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-07 09:34:38.136  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 09:34:38.637  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-07 09:34:38.638  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 09:34:38.638  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 09:34:40.844  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:34:40.847  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:34:40.904  1524  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-07 09:34:40.905  1524  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-07 09:34:40.905  1524  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 09:34:40.905  1524  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:34:40.951  3010  3885 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-07 09:34:40.951  3010  3885 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 09:34:40.951  3010  3885 E HttpOperation: 	at jdm.a(PG:82)
09-07 09:34:40.951  3010  3885 E HttpOperation: 	at jcs.o(PG:406)
09-07 09:34:40.951  3010  3885 E HttpOperation: 	at jcn.a(PG:1379)
09-07 09:34:40.951  3010  3885 E HttpOperation: 	at jcs.i(PG:143)
09-07 09:34:40.951  3010  3885 E HttpOperation: 	at blb.a(PG:3937)
09-07 09:34:40.951  3010  3885 E HttpOperation: 	at czp.a(PG:18188)
09-07 09:34:40.951  3010  3885 E HttpOperation: 	at czp.a(PG:9081)
09-07 09:34:40.951  3010  3885 E HttpOperation: 	at czq.run(PG:1686)
09-07 09:34:40.951  3010  3885 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 09:34:40.951  3010  3885 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 09:34:40.951  3010  3885 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 09:34:40.951  3010  3885 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 09:34:40.951  3010  3885 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 09:34:40.951  3010  3885 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 09:34:40.951  3010  3885 E HttpOperation: 	at jdj.a(PG:4091)
09-07 09:34:40.951  3010  3885 E HttpOperation: 	at jdj.a(PG:1125)
09-07 09:34:40.951  3010  3885 E HttpOperation: 	at jdm.a(PG:77)
09-07 09:34:40.951  3010  3885 E HttpOperation: 	... 12 more
09-07 09:34:40.951  3010  3885 E HttpOperation: Caused by: faj: BadAuthentication
09-07 09:34:40.951  3010  3885 E HttpOperation: 	at fal.a(PG:38)
09-07 09:34:40.951  3010  3885 E HttpOperation: 	at jdj.a(PG:4089)
09-07 09:34:40.951  3010  3885 E HttpOperation: 	... 14 more
,09-07 09:34:41.022  1524  2052 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 09:34:41.022  1524  2052 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 09:34:41.022  1524  2052 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 09:34:41.022  1524  2052 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:34:41.039  3010  3885 E HttpOperation: [getmobileexperiments] Unexpected exception
09-07 09:34:41.039  3010  3885 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 09:34:41.039  3010  3885 E HttpOperation: 	at jdm.a(PG:82)
09-07 09:34:41.039  3010  3885 E HttpOperation: 	at jcs.o(PG:406)
09-07 09:34:41.039  3010  3885 E HttpOperation: 	at jcn.a(PG:1379)
09-07 09:34:41.039  3010  3885 E HttpOperation: 	at jcs.i(PG:143)
09-07 09:34:41.039  3010  3885 E HttpOperation: 	at hec.a(PG:42)
09-07 09:34:41.039  3010  3885 E HttpOperation: 	at hee.a(PG:102)
09-07 09:34:41.039  3010  3885 E HttpOperation: 	at czr.a(PG:65)
09-07 09:34:41.039  3010  3885 E HttpOperation: 	at kka.a(PG:108)
09-07 09:34:41.039  3010  3885 E HttpOperation: 	at czp.a(PG:19176)
09-07 09:34:41.039  3010  3885 E HttpOperation: 	at czp.a(PG:9081)
09-07 09:34:41.039  3010  3885 E HttpOperation: 	at czq.run(PG:1686)
09-07 09:34:41.039  3010  3885 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 09:34:41.039  3010  3885 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 09:34:41.039  3010  3885 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 09:34:41.039  3010  3885 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 09:34:41.039  3010  3885 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 09:34:41.039  3010  3885 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 09:34:41.039  3010  3885 E HttpOperation: 	at jdj.a(PG:4091)
09-07 09:34:41.039  3010  3885 E HttpOperation: 	at jdj.a(PG:1125)
09-07 09:34:41.039  3010  3885 E HttpOperation: 	at jdm.a(PG:77)
09-07 09:34:41.039  3010  3885 E HttpOperation: 	... 15 more
09-07 09:34:41.039  3010  3885 E HttpOperation: Caused by: faj: BadAuthentication
09-07 09:34:41.039  3010  3885 E HttpOperation: 	at fal.a(PG:38)
09-07 09:34:41.039  3010  3885 E HttpOperation: 	at jdj.a(PG:4089)
09-07 09:34:41.039  3010  3885 E HttpOperation: 	... 17 more
,09-07 09:34:41.040  3010  3885 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
09-07 09:34:41.040  3010  3885 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-07 09:34:41.040  3010  3885 E ExperimentLoader: 	at jdm.a(PG:82)
09-07 09:34:41.040  3010  3885 E ExperimentLoader: 	at jcs.o(PG:406)
09-07 09:34:41.040  3010  3885 E ExperimentLoader: 	at jcn.a(PG:1379)
09-07 09:34:41.040  3010  3885 E ExperimentLoader: 	at jcs.i(PG:143)
09-07 09:34:41.040  3010  3885 E ExperimentLoader: 	at hec.a(PG:42)
09-07 09:34:41.040  3010  3885 E ExperimentLoader: 	at hee.a(PG:102)
09-07 09:34:41.040  3010  3885 E ExperimentLoader: 	at czr.a(PG:65)
09-07 09:34:41.040  3010  3885 E ExperimentLoader: 	at kka.a(PG:108)
09-07 09:34:41.040  3010  3885 E ExperimentLoader: 	at czp.a(PG:19176)
09-07 09:34:41.040  3010  3885 E ExperimentLoader: 	at czp.a(PG:9081)
09-07 09:34:41.040  3010  3885 E ExperimentLoader: 	at czq.run(PG:1686)
09-07 09:34:41.040  3010  3885 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 09:34:41.040  3010  3885 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 09:34:41.040  3010  3885 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 09:34:41.040  3010  3885 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 09:34:41.040  3010  3885 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-07 09:34:41.040  3010  3885 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 09:34:41.040  3010  3885 E ExperimentLoader: 	at jdj.a(PG:4091),
09-07 09:34:41.040  3010  3885 E ExperimentLoader: 	at jdj.a(PG:1125)
09-07 09:34:41.040  3010  3885 E ExperimentLoader: 	at jdm.a(PG:77)
09-07 09:34:41.040  3010  3885 E ExperimentLoader: 	... 15 more
09-07 09:34:41.040  3010  3885 E ExperimentLoader: Caused by: faj: BadAuthentication
09-07 09:34:41.040  3010  3885 E ExperimentLoader: 	at fal.a(PG:38)
09-07 09:34:41.040  3010  3885 E ExperimentLoader: 	at jdj.a(PG:4089)
09-07 09:34:41.040  3010  3885 E ExperimentLoader: 	... 17 more
,09-07 09:34:41.157   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 127973, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-07 09:34:44.139  3820  3869 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 09:34:44.141  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-07 09:34:44.141  3820  3869 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-07 09:34:44.141  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-07 09:34:44.142  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-07 09:34:44.142  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-07 09:34:44.145  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 09:34:44.145  3820  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 09:34:44.145  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 09:34:44.145  3820  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 09:34:44.145  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 09:34:44.146  3820  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 09:34:44.146  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 09:34:44.146  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 09:34:44.146  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 09:34:44.146  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 09:34:44.148  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 09:34:44.151  3820  3869 D BluetoothAdapter: STATE_ON
09-07 09:34:44.152  3820  3869 D BluetoothLeScanner: could not find callback wrapper
09-07 09:34:44.152  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 09:34:44.153  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-07 09:34:44.156  2721  2781 D BtGatt.AdvertiseManager: message : 1
09-07 09:34:44.157  2721  2781 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-07 09:34:44.168  2721  2775 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-07 09:34:44.168  2721  2775 D BtGatt.GattService: Client app is not null!
,09-07 09:34:44.171  2721  2733 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-07 09:34:44.172  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 09:34:44.172  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-07 09:34:44.173  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-07 09:34:44.173  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-07 09:34:44.173  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-07 09:34:44.176  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 09:34:44.177  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-07 09:34:44.177  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 09:34:44.179  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,09-07 09:34:44.182  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 09:34:44.183  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-07 09:34:44.183  3820  3820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
,09-07 09:34:44.184  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 09:34:44.184  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 09:34:44.184  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 09:34:44.686  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 09:34:47.188  3820  3869 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-07 09:34:47.189  3820  3869 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-07 09:34:47.189  3820  3869 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,09-07 09:34:47.190  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-07 09:34:47.190  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 09:34:47.191  3820  3869 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-07 09:34:47.191  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 09:34:47.191  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:34:47.195  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-07 09:34:47.197  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 09:34:47.197  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 09:34:47.198  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 09:34:47.198  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-07 09:34:47.198  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 09:34:47.198  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:34:47.199  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 09:34:47.208  3820  3889 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 09:34:47.212  3820  3869 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-07 09:34:47.212  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 09:34:47.212  3820  3889 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-07 09:34:47.218  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 09:34:47.220  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 09:34:47.220  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 09:34:47.222  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-07 09:34:47.223  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-07 09:34:47.223  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 F8 CF C5 D9 E5 61
,09-07 09:34:47.223  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-07 09:34:47.223  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 09:34:47.223  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-07 09:34:47.225  3820  3869 D BluetoothAdapter: STATE_ON
09-07 09:34:47.228  2721  2736 D BtGatt.GattService: registerClient() - UUID=e6fe4e92-f394-46dd-87e7-9a20318b852c
09-07 09:34:47.229  2721  2775 D BtGatt.GattService: onClientRegistered() - UUID=e6fe4e92-f394-46dd-87e7-9a20318b852c, clientIf=5
09-07 09:34:47.229  3820  3832 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-07 09:34:47.231  2721  2781 D BtGatt.AdvertiseManager: message : 0
,09-07 09:34:47.235  2721  2781 D BtGatt.AdvertiseManager: starting multi advertising
,09-07 09:34:47.246  2721  2775 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-07 09:34:47.257  2721  2775 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-07 09:34:47.257  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-07 09:34:47.257  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,09-07 09:34:47.259  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-07 09:34:47.261  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 09:34:47.261  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-07 09:34:47.261  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-07 09:34:47.261  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-07 09:34:47.261  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-07 09:34:47.261  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-07 09:34:47.262  3820  3869 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 09:34:47.264  3820  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-07 09:34:47.264  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 09:34:47.765  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-07 09:34:47.766  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 09:34:47.766  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 09:34:50.267  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:34:50.267  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 09:34:50.268  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-07 09:34:50.268  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 09:34:50.269  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 09:34:50.269  3820  3889 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-07 09:34:50.269  3820  3889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 09:34:50.269  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 09:34:50.270  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fa5238 not in the list
09-07 09:34:50.270  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 09:34:50.270  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:34:50.270  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-07 09:34:50.270  3820  3889 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-07 09:34:50.270  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 09:34:50.271  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 09:34:50.271  3820  3820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 09:34:50.271  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-07 09:34:50.274  3820  3869 D BluetoothAdapter: STATE_ON
09-07 09:34:50.274  3820  3869 D BluetoothLeScanner: could not find callback wrapper
09-07 09:34:50.274  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-07 09:34:50.275  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-07 09:34:50.277  2721  2781 D BtGatt.AdvertiseManager: message : 1
09-07 09:34:50.278  2721  2781 D BtGatt.AdvertiseManager: stop advertise for client 5
09-07 09:34:50.290  2721  2775 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-07 09:34:50.291  2721  2775 D BtGatt.GattService: Client app is not null!
,09-07 09:34:50.292  2721  2927 D BtGatt.GattService: unregisterClient() - clientIf=5
09-07 09:34:50.293  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 09:34:50.293  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-07 09:34:50.293  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-07 09:34:50.293  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-07 09:34:50.293  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-07 09:34:50.295  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 09:34:50.295  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 09:34:50.295  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 09:34:50.296  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 09:34:50.307  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 09:34:50.307  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 09:34:50.307  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 09:34:50.308  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f24211 not in the list
09-07 09:34:50.308  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:34:50.308  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:34:50.309  3820  3869 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-07 09:34:50.311  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:34:50.316  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:34:50.316  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:34:50.316  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:34:50.316  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:34:50.316  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:34:50.316  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:34:50.316  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:34:50.316  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 09:34:50.319  3820  3869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 09:34:50.319  3820  3869 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 09:34:50.322  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:34:50.322  3820  3869 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,09-07 09:34:50.323  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,09-07 09:34:50.325  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:34:50.325  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 09:34:50.325  3820  3869 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-07 09:34:50.326  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-07 09:34:50.326  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:34:50.327  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-07 09:34:50.328  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-07 09:34:50.328  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-07 09:34:50.328  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 09:34:50.328  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-07 09:34:50.328  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-07 09:34:50.328  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:34:50.329  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 09:34:50.329  3820  3891 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 09:34:50.333  3820  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-07 09:34:50.334  3820  3869 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-07 09:34:50.334  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 09:34:50.338  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 09:34:50.338  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 09:34:50.338  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 09:34:50.340  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-07 09:34:50.341  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 09:34:50.341  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
09-07 09:34:50.341  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 09:34:50.341  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 09:34:50.341  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-07 09:34:50.342  3820  3869 D BluetoothAdapter: STATE_ON
,09-07 09:34:50.344  2721  2733 D BtGatt.GattService: registerClient() - UUID=29c5ced4-c19d-4a1b-8ec3-03225004af1b
09-07 09:34:50.344  2721  2775 D BtGatt.GattService: onClientRegistered() - UUID=29c5ced4-c19d-4a1b-8ec3-03225004af1b, clientIf=5
09-07 09:34:50.345  3820  3832 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-07 09:34:50.345  2721  2781 D BtGatt.AdvertiseManager: message : 0
09-07 09:34:50.348  2721  2781 D BtGatt.AdvertiseManager: starting multi advertising
,09-07 09:34:50.359  2721  2775 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-07 09:34:50.365  2721  2775 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-07 09:34:50.366  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-07 09:34:50.366  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 09:34:50.367  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 09:34:50.368  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 09:34:50.369  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-07 09:34:50.369  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-07 09:34:50.369  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-07 09:34:50.369  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-07 09:34:50.369  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-07 09:34:50.370  3820  3869 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 09:34:50.371  3820  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 09:34:50.372  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 09:34:50.873  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-07 09:34:50.873  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 09:34:50.874  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 09:34:56.066  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:34:56.078  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:34:56.082  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:34:56.121  1524  2307 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 09:34:56.121  1524  2307 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 09:34:56.121  1524  2307 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 09:34:56.121  1524  2307 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:34:56.151  3541  3541 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 09:34:56.152  3541  3541 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 09:34:56.153  3541  3541 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-07 09:34:56.374  3820  3869 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 09:34:56.375  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-07 09:34:56.375  3820  3869 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-07 09:34:56.375  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-07 09:34:56.375  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 09:34:56.376  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 09:34:56.376  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-07 09:34:56.376  3820  3891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 09:34:56.377  3820  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 09:34:56.377  3820  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-07 09:34:56.378  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 09:34:56.379  3820  3820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 09:34:56.379  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 09:34:56.379  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-07 09:34:56.379  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 09:34:56.379  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 09:34:56.380  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 09:34:56.380  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 09:34:56.383  3820  3869 D BluetoothAdapter: STATE_ON
09-07 09:34:56.383  3820  3869 D BluetoothLeScanner: could not find callback wrapper
09-07 09:34:56.384  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-07 09:34:56.384  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-07 09:34:56.387  2721  2781 D BtGatt.AdvertiseManager: message : 1
09-07 09:34:56.388  2721  2781 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-07 09:34:56.397  2721  2775 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-07 09:34:56.397  2721  2775 D BtGatt.GattService: Client app is not null!
,09-07 09:34:56.399  2721  2733 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-07 09:34:56.400  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-07 09:34:56.400  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-07 09:34:56.400  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-07 09:34:56.400  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-07 09:34:56.400  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-07 09:34:56.402  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 09:34:56.402  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 09:34:56.402  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 09:34:56.402  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 09:34:56.406  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 09:34:56.406  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-07 09:34:56.406  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 09:34:56.407  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 09:34:56.407  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 09:34:56.909  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 09:34:59.411  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:34:59.411  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:34:59.412  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 09:34:59.412  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fa5238 not in the list
09-07 09:34:59.412  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:34:59.413  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f24211 not in the list
,09-07 09:34:59.413  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:34:59.414  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:34:59.417  3820  3869 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-07 09:34:59.419  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:34:59.419  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:34:59.420  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:34:59.420  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fa5238 not in the list
09-07 09:34:59.421  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 09:34:59.421  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f24211 not in the list
09-07 09:34:59.421  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:34:59.421  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 09:34:59.422  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:34:59.425  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 09:34:59.425  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:34:59.426  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 09:34:59.426  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:34:59.426  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fa5238 not in the list
09-07 09:34:59.427  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 09:34:59.427  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f24211 not in the list
09-07 09:34:59.427  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:34:59.428  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 09:34:59.428  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:34:59.441  3820  3869 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-07 09:34:59.441  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:34:59.441  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:34:59.441  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:34:59.441  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fa5238 not in the list
09-07 09:34:59.441  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:34:59.441  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f24211 not in the list
09-07 09:34:59.441  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:34:59.441  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 09:34:59.441  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:34:59.442  3820  3869 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-07 09:34:59.442  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:34:59.442  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:34:59.442  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:34:59.442  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fa5238 not in the list
,09-07 09:34:59.442  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:34:59.442  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f24211 not in the list
09-07 09:34:59.443  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 09:34:59.443  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 09:34:59.443  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:34:59.443  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 09:34:59.445  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 09:34:59.446  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 09:34:59.446  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 09:34:59.446  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 09:34:59.446  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 09:34:59.446  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 09:34:59.446  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:34:59.446  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:34:59.446  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fa5238 not in the list
09-07 09:34:59.446  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 09:34:59.446  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f24211 not in the list
09-07 09:34:59.447  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:34:59.447  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:34:59.447  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:34:59.447  3820  3869 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 09:34:59.448  3820  3869 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 09:34:59.448  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 09:34:59.451  3820  3869 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-07 09:34:59.452  3820  3869 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-07 09:34:59.452  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 09:34:59.452  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 09:34:59.452  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 09:34:59.452  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 09:34:59.452  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-07 09:34:59.452  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 09:34:59.452  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 09:34:59.452  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 09:34:59.452  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-07 09:34:59.452  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 09:34:59.453  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 09:34:59.453  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 09:34:59.453  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-07 09:34:59.453  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-07 09:34:59.453  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 09:34:59.453  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 09:34:59.453  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 09:34:59.453  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 09:34:59.453  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 09:34:59.453  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 09:34:59.453  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-07 09:34:59.454  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 09:34:59.454  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 09:34:59.454  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 09:34:59.454  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 09:34:59.454  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 09:34:59.454  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-07 09:34:59.454  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-07 09:34:59.454  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 09:34:59.454  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-07 09:34:59.454  3820  3869 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-07 09:34:59.455  3820  3869 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 09:34:59.455  3820  3869 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 09:34:59.455  3820  3869 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 09:34:59.455  3820  3869 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-07 09:34:59.455  3820  3869 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 09:34:59.455  3820  3869 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 09:34:59.456  3820  3869 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 09:34:59.456  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-07 09:34:59.462  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-07 09:34:59.465  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-07 09:34:59.465  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-07 09:34:59.465  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 09:34:59.466  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 09:34:59.466  3820  3869 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-07 09:34:59.466  3820  3869 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 09:34:59.466  3820  3869 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 09:34:59.467  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:34:59.467  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:34:59.467  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:34:59.468  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-07 09:34:59.468  3820  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 429)
09-07 09:34:59.469  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fa5238 not in the list
09-07 09:34:59.469  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:34:59.469  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f24211 not in the list
09-07 09:34:59.469  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:34:59.469  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:34:59.470  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:34:59.470  3820  3896 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 429
,09-07 09:34:59.470  3820  3869 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-07 09:34:59.471  3820  3895 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 09:34:59.471  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:34:59.471  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:34:59.471  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:34:59.471  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fa5238 not in the list
09-07 09:34:59.471  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 09:34:59.471  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f24211 not in the list
09-07 09:34:59.471  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:34:59.471  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:34:59.472  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:34:59.472  3820  3869 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-07 09:34:59.473  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:34:59.474  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:34:59.474  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:34:59.474  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fa5238 not in the list
09-07 09:34:59.474  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:34:59.474  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f24211 not in the list
,09-07 09:34:59.474  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:34:59.474  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:34:59.474  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:34:59.475  3820  3869 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 09:34:59.475  3820  3869 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-07 09:34:59.475  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 09:34:59.475  3820  3869 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 09:34:59.475  3820  3869 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-07 09:34:59.476  3820  3869 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 09:34:59.476  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 09:34:59.476  3820  3869 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 09:34:59.476  3820  3869 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 09:34:59.476  3820  3869 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 09:34:59.476  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-07 09:34:59.476  3820  3869 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-07 09:34:59.476  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:34:59.476  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:34:59.476  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:34:59.477  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fa5238 not in the list
09-07 09:34:59.477  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:34:59.477  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f24211 not in the list
,09-07 09:34:59.477  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:34:59.477  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:34:59.477  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:34:59.478  3820  3869 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-07 09:34:59.480  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:34:59.487  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:34:59.487  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:34:59.487  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:34:59.487  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:34:59.487  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:34:59.487  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:34:59.487  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:34:59.487  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 09:34:59.490  3820  3869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 09:34:59.490  3820  3869 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 09:34:59.491  3820  3869 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
,09-07 09:34:59.491  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-07 09:34:59.491  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 09:34:59.491  3820  3869 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-07 09:34:59.491  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 09:34:59.492  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:34:59.492  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 09:34:59.493  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 09:34:59.493  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 09:34:59.493  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:34:59.493  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 09:34:59.493  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 09:34:59.493  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:34:59.494  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 09:34:59.494  3820  3897 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 09:34:59.496  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:34:59.496  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 09:34:59.497  3820  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-07 09:34:59.498  3820  3869 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 09:34:59.498  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 09:34:59.504  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 09:34:59.505  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings,
09-07 09:34:59.505  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 09:34:59.508  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-07 09:34:59.508  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 09:34:59.508  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 F8 CF C5 D9 E5 61
09-07 09:34:59.509  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 09:34:59.509  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 09:34:59.509  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-07 09:34:59.510  3820  3869 D BluetoothAdapter: STATE_ON
,09-07 09:34:59.513  2721  2927 D BtGatt.GattService: registerClient() - UUID=cffdf279-1a94-4f7c-a0b9-bad5aca872dc
,09-07 09:34:59.514  2721  2775 D BtGatt.GattService: onClientRegistered() - UUID=cffdf279-1a94-4f7c-a0b9-bad5aca872dc, clientIf=5
09-07 09:34:59.514  3820  3831 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-07 09:34:59.515  2721  2781 D BtGatt.AdvertiseManager: message : 0
,09-07 09:34:59.519  2721  2781 D BtGatt.AdvertiseManager: starting multi advertising
,09-07 09:34:59.535  2721  2775 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-07 09:34:59.546  2721  2775 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-07 09:34:59.547  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-07 09:34:59.547  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 09:34:59.550  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 09:34:59.552  3820  3869 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 09:34:59.553  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 09:34:59.554  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-07 09:34:59.554  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-07 09:34:59.554  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-07 09:34:59.555  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-07 09:34:59.555  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-07 09:34:59.563  3820  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 09:34:59.564  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 09:35:00.065  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-07 09:35:00.066  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-07 09:35:00.066  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 09:35:04.610  2721  2902 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-07 09:35:04.612  3820  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 429)
,09-07 09:35:04.614  2721  2916 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
,09-07 09:35:05.557  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 09:35:05.557  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-07 09:35:05.558  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 09:35:05.558  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-07 09:35:05.558  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 09:35:05.559  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-07 09:35:05.559  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fa5238 not in the list
,09-07 09:35:05.559  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 09:35:05.560  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:35:05.560  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 09:35:05.560  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-07 09:35:05.561  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 09:35:05.561  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 09:35:05.561  3820  3897 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 09:35:05.561  3820  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-07 09:35:05.562  3820  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 09:35:05.566  3820  3869 D BluetoothAdapter: STATE_ON
09-07 09:35:05.566  3820  3869 D BluetoothLeScanner: could not find callback wrapper
09-07 09:35:05.566  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 09:35:05.566  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-07 09:35:05.568  2721  2781 D BtGatt.AdvertiseManager: message : 1
09-07 09:35:05.570  2721  2781 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-07 09:35:05.580  2721  2775 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-07 09:35:05.580  2721  2775 D BtGatt.GattService: Client app is not null!
09-07 09:35:05.582  2721  2736 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-07 09:35:05.583  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 09:35:05.584  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-07 09:35:05.584  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-07 09:35:05.584  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-07 09:35:05.585  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-07 09:35:05.587  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 09:35:05.588  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 09:35:05.588  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 09:35:05.589  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 09:35:05.593  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 09:35:05.594  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f24211 not in the list
,09-07 09:35:05.594  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 09:35:05.594  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:35:05.594  3820  3820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-07 09:35:05.594  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:35:05.595  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 09:35:05.640   876   896 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-07 09:35:05.645  1894  1894 I Keyboard.Facilitator: onFinishInput()
,09-07 09:35:05.647   876   896 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 09:35:05.647   876   896 I Adreno  : Build Date                       : 10/20/15
09-07 09:35:05.647   876   896 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 09:35:05.647   876   896 I Adreno  : Local Branch                     : M14
09-07 09:35:05.647   876   896 I Adreno  : Remote Branch                    : 
09-07 09:35:05.647   876   896 I Adreno  : Remote Branch                    : 
09-07 09:35:05.647   876   896 I Adreno  : Reconstruct Branch               : 
,09-07 09:35:05.678   281  1335 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (185 us)
,09-07 09:35:06.096  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 09:35:06.293  3820  3820 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-07 09:35:06.293  3820  3820 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-07 09:35:06.334   876   896 V KeyguardServiceDelegate: onScreenTurnedOff()
09-07 09:35:06.334  3820  3820 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e667f9a Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@212b226, 16908290=android.view.AbsSavedState$1@212b226}, android:focusedViewId=100}]}]
09-07 09:35:06.335  3820  3820 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-07 09:35:06.335  3820  3820 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-07 09:35:06.335  3820  3820 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-07 09:35:06.363   876   896 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-07 09:35:06.366   876   894 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-07 09:35:06.369   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
09-07 09:35:06.369   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0,
,09-07 09:35:06.594   281   344 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-07 09:35:06.596   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-07 09:35:06.602   876  1347 D SurfaceControl: Excessive delay in setPowerMode(): 236ms
,09-07 09:35:06.608   876   896 I DreamManagerService: Entering dreamland.
,09-07 09:35:06.612   876   896 I PowerManagerService: Dozing...
,09-07 09:35:06.614   876   891 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-07 09:35:06.660   378  1329 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-07 09:35:06.660   378  1329 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-07 09:35:06.671   876  1319 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 09:35:06.676  1951  3904 D NfcService: Discovery configuration equal, not updating.
,09-07 09:35:06.679   876  1319 E native  : do suspend false
,09-07 09:35:06.689   876  1319 D WifiConfigStore: No blacklist allowed without epno enabled
,09-07 09:35:06.702   876  1319 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 09:35:06.705   876  1319 E native  : do suspend true
,09-07 09:35:06.800   378  1291 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-07 09:35:06.801   378  1291 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-07 09:35:07.176   876  1319 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-07 09:35:08.601  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 09:35:08.601  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 09:35:08.602  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:35:08.602  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fa5238 not in the list
09-07 09:35:08.602  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 09:35:08.604  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f24211 not in the list
09-07 09:35:08.605  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 09:35:08.605  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:08.606  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:35:08.615  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-07 09:35:08.615  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:35:08.618  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-07 09:35:08.622  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 09:35:08.622  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-07 09:35:08.622  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 09:35:08.622  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 09:35:08.622  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 09:35:08.624  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 09:35:08.624  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-07 09:35:08.625  3820  3909 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 09:35:08.625  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 09:35:08.625  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown,
09-07 09:35:08.625  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:35:08.625  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-07 09:35:08.626  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-07 09:35:08.626  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fa5238 not in the list
09-07 09:35:08.626  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 09:35:08.627  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 09:35:08.627  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 09:35:08.627  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 09:35:08.628  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:08.628  3820  3909 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-07 09:35:08.629  3820  3909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 09:35:08.629  3820  3909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-07 09:35:08.628  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:35:08.633  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 09:35:08.633  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 09:35:08.634  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-07 09:35:08.633  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f24211 not in the list
09-07 09:35:08.634  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 09:35:08.634  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 09:35:08.634  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:35:08.634  3820  3820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 09:35:08.634  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 09:35:08.636  3820  3869 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-07 09:35:08.636  3820  3869 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 09:35:08.636  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-07 09:35:08.638  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 09:35:08.639  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:35:08.639  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:08.639  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:35:08.639  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fa5238 not in the list
09-07 09:35:08.639  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 09:35:08.639  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f24211 not in the list
09-07 09:35:08.639  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:35:08.639  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 09:35:08.639  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:35:08.647  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:35:08.648  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:08.648  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:35:08.648  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fa5238 not in the list
09-07 09:35:08.648  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:35:08.648  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f24211 not in the list
09-07 09:35:08.648  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:35:08.648  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:08.648  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:35:08.649  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:35:08.650  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:08.650  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:35:08.650  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4fa5238 not in the list
09-07 09:35:08.650  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:35:08.650  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f24211 not in the list
09-07 09:35:08.650  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:35:08.650  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:08.650  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:35:08.651  3820  3869 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-07 09:35:08.651  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 09:35:08.652  3820  3869 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-07 09:35:08.652  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 09:35:08.652  3820  3869 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-07 09:35:08.652  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-07 09:35:08.656  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-07 09:35:08.656  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-07 09:35:08.656  3820  3869 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-07 09:35:08.657  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-07 09:35:08.657  3820  3869 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-07 09:35:08.657  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 09:35:08.657  3820  3869 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-07 09:35:08.657  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-07 09:35:08.658  3820  3869 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-07 09:35:08.658  3820  3869 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-07 09:35:08.658  3820  3869 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-07 09:35:08.658  3820  3869 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-07 09:35:08.659  3820  3869 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-07 09:35:08.659  3820  3869 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-07 09:35:08.660  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 09:35:08.660  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a19e67 added. We now have 2 listener(s)
09-07 09:35:08.660  3820  3869 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 09:35:08.664  3820  3869 D BluetoothAdapter: enable(): BT is already enabled..!
09-07 09:35:08.664   876  1707 D WifiService: setWifiEnabled: true pid=3820, uid=10000
09-07 09:35:08.664   876  1707 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 09:35:08.666  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 09:35:08.666  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4be0414 added. We now have 3 listener(s)
09-07 09:35:08.666  3820  3869 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 09:35:08.674  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 09:35:08.674  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@59e04bd added. We now have 4 listener(s)
,09-07 09:35:08.674  3820  3869 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 09:35:08.676  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 09:35:08.676  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e7cab2 added. We now have 5 listener(s)
09-07 09:35:08.676  3820  3869 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 09:35:08.678   876   887 D WifiService: setWifiEnabled: false pid=3820, uid=10000
09-07 09:35:08.678   876   887 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 09:35:08.685  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:35:08.687  2721  2770 D BluetoothAdapterState: Current state: ON, message: 23
,09-07 09:35:08.687  2721  2770 D BluetoothAdapterProperties: Setting state to 13,
,09-07 09:35:08.687  2721  2770 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-07 09:35:08.688  2721  2770 D BluetoothAdapterProperties: onBluetoothDisable()
,09-07 09:35:08.689  2721  2770 I BluetoothAdapterState: Entering PendingCommandState,
,09-07 09:35:08.690  2721  2775 D BluetoothAdapterProperties: Scan Mode:20
,09-07 09:35:08.690  2721  2770 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-07 09:35:08.692  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 09:35:08.692  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:35:08.692  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:08.692  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:35:08.692  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:35:08.692  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:35:08.692  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:35:08.692  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:35:08.692  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:35:08.696  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 09:35:08.696  3820  3869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 09:35:08.697  3820  3869 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 09:35:08.704  2721  2721 D HeadsetService: Received stop request...Stopping profile...
,09-07 09:35:08.704  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-07 09:35:08.704  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:35:08.708   876  1319 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-07 09:35:08.708   876  1319 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-07 09:35:08.708  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:08.708   876  1319 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-07 09:35:08.708   876  1319 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 09:35:08.713  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 09:35:08.713  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:35:08.713  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:08.713  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:35:08.713  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:35:08.713  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:35:08.713  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:35:08.713  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:35:08.713  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 09:35:08.714  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 09:35:08.714  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 09:35:08.715   876  1319 E native  : do suspend true
,09-07 09:35:08.717  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:35:08.720  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:35:08.722  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:35:08.727   876  1872 D DhcpClient: Clearing IP address
,09-07 09:35:08.727   876   889 I ActivityManager: Start proc 3912:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-07 09:35:08.728   374   874 D CommandListener: Clearing all IP addresses on wlan0
09-07 09:35:08.730   876   876 D BluetoothHeadset: Proxy object disconnected
09-07 09:35:08.731  1391  1402 D BluetoothHeadset: Proxy object disconnected
09-07 09:35:08.731   876   876 D BluetoothHeadset: Proxy object disconnected
09-07 09:35:08.731  2721  2721 D A2dpService: Received stop request...Stopping profile...
,09-07 09:35:08.731  1966  2119 D BluetoothHeadset: Proxy object disconnected
09-07 09:35:08.731   876   876 D BluetoothHeadset: Proxy object disconnected
09-07 09:35:08.731  2721  2922 D A2dpStateMachine: Exit Disconnected: -1
09-07 09:35:08.733   876   876 D BluetoothA2dp: Proxy object disconnected
09-07 09:35:08.734  1391  1391 D HeadsetProfile: Bluetooth service disconnected
09-07 09:35:08.734  1391  1391 D BluetoothA2dp: Proxy object disconnected
09-07 09:35:08.734  2721  2721 D HidService: Received stop request...Stopping profile...
09-07 09:35:08.734  1524  2501 V NativeCrypto: Read error: ssl=0x9af7d000: I/O error during system call, Connection timed out
,09-07 09:35:08.734  2721  2721 D HidService: Stopping Bluetooth HidService
09-07 09:35:08.735   374   874 D CommandListener: Setting iface cfg
09-07 09:35:08.736  2721  2721 D BluetoothMapService: onReceive
09-07 09:35:08.736  2721  2721 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 09:35:08.736  2721  2721 D BluetoothMapService: STATE_TURNING_OFF
,09-07 09:35:08.736  2721  2721 D HealthService: Received stop request...Stopping profile...
09-07 09:35:08.736  1524  2501 V NativeCrypto: SSL shutdown failed: ssl=0x9af7d000: I/O error during system call, Broken pipe
09-07 09:35:08.739   876  1727 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,09-07 09:35:08.739   876  1869 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-07 09:35:08.739   876  1908 D DhcpClient: Receive thread stopped
09-07 09:35:08.740  1391  1391 D BluetoothInputDevice: Proxy object disconnected
,09-07 09:35:08.740  1391  1391 D HidProfile: Bluetooth service disconnected
09-07 09:35:08.741  2721  2721 V BluetoothAdapterState: isTurningOff()=true
09-07 09:35:08.741  2721  2721 V BluetoothAdapterState: isTurningOn()=false
,09-07 09:35:08.741  2721  2721 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:35:08.741  2721  2721 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:35:08.742   876  1319 D WifiStateMachine: Start Disconnecting Watchdog 1
09-07 09:35:08.742   876  1869 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-07 09:35:08.742   876  1319 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 09:35:08.742   876  1319 E native  : do suspend true
,09-07 09:35:08.742   876  1323 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-07 09:35:08.743  2721  2721 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 09:35:08.743  2721  2721 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 09:35:08.743   876  1323 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-07 09:35:08.743   876  1323 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-07 09:35:08.743  2721  2902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 09:35:08.743  2721  2902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 09:35:08.743  2721  2902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 09:35:08.743  2721  2775 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-07 09:35:08.744  2721  2775 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-07 09:35:08.744   876  1323 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-07 09:35:08.744  2721  2721 D PanService: Received stop request...Stopping profile...
09-07 09:35:08.746   876  1323 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-07 09:35:08.748  1391  1391 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 09:35:08.748  1391  1391 D PanProfile: Bluetooth service disconnected
09-07 09:35:08.749  2721  2721 V BluetoothAdapterState: isTurningOff()=true
09-07 09:35:08.749  2721  2721 V BluetoothAdapterState: isTurningOn()=false
09-07 09:35:08.749  2721  2721 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 09:35:08.749  2721  2721 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:35:08.750   412   412 E Parcel  : Reading a NULL string not supported here.
09-07 09:35:08.751  2721  2902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 09:35:08.751  2721  2902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 09:35:08.751  2721  2902 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 09:35:08.751  2721  2902 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 09:35:08.751  2721  2902 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 09:35:08.751  2721  2902 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-07 09:35:08.751  2721  2775 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-07 09:35:08.751  2721  2721 D BluetoothMapService: Received stop request...Stopping profile...
09-07 09:35:08.752  2721  2721 D BluetoothMapService: stop()
09-07 09:35:08.752  2721  2721 D BluetoothMapAppObserver: deinitObservers()
09-07 09:35:08.752  2721  2721 D BluetoothMapAppObserver: removeReceiver()
09-07 09:35:08.754  2721  2721 V BluetoothAdapterState: isTurningOff()=true
09-07 09:35:08.754  2721  2721 V BluetoothAdapterState: isTurningOn()=false
09-07 09:35:08.754  2721  2721 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:35:08.754  2721  2721 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:35:08.755  2721  2721 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-07 09:35:08.755  2721  2721 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 09:35:08.755  2721  2775 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 09:35:08.755  2721  2721 I BtOppRfcommListener: stopping Accept Thread
09-07 09:35:08.755  2721  3468 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 09:35:08.755  2721  3468 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 09:35:08.756  2721  2721 V BluetoothAdapterState: isTurningOff()=true
09-07 09:35:08.756  2721  2721 V BluetoothAdapterState: isTurningOn()=false
09-07 09:35:08.756  2721  2721 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:35:08.756  2721  2721 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:35:08.757  2721  2721 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-07 09:35:08.757  2721  2775 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-07 09:35:08.757  2721  2721 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 09:35:08.757  2721  2721 V BluetoothAdapterState: isTurningOff()=true
09-07 09:35:08.757  2721  2721 V BluetoothAdapterState: isTurningOn()=false
09-07 09:35:08.757  2721  2721 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:35:08.757  2721  2721 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:35:08.758  2721  2721 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-07 09:35:08.758  2721  2721 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 09:35:08.759  2721  2721 D BluetoothMapService: MAP Service closeService in
09-07 09:35:08.759  2721  2721 D BluetoothMapMasInstance0: MAP Service shutdown
09-07 09:35:08.759  2721  2721 D ObexServerSockets0: shutdown(block = true)
09-07 09:35:08.759  2721  2928 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-07 09:35:08.760  2721  2721 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-07 09:35:08.760   876  1323 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-07 09:35:08.761  2721  2929 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-07 09:35:08.762  2721  2916 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-07 09:35:08.762  2721  2721 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-07 09:35:08.762  2721  2721 V BluetoothAdapterState: isTurningOff()=true
09-07 09:35:08.762  2721  2721 V BluetoothAdapterState: isTurningOn()=false
09-07 09:35:08.762  2721  2721 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:35:08.763  2721  2721 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:35:08.763  2721  2770 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-07 09:35:08.763  2721  2721 D BluetoothMapService: cleanup()
09-07 09:35:08.763  2721  2721 D BluetoothMapService: MAP Service closeService in
,09-07 09:35:08.763  2721  2770 D BluetoothAdapterProperties: Setting state to 15
09-07 09:35:08.764  2721  2770 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-07 09:35:08.764  2721  2770 I BluetoothAdapterState: Entering BleOnState
09-07 09:35:08.764   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 09:35:08.764   876   893 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 09:35:08.764  1966  1976 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 09:35:08.765  1391  2093 D BluetoothPan: onBluetoothStateChange on: false
09-07 09:35:08.768   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 09:35:08.768  1391  1404 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 09:35:08.769   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 09:35:08.769  1391  1402 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 09:35:08.770  1391  2093 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 09:35:08.770  1391  1404 D BluetoothMap: onBluetoothStateChange: up=false
09-07 09:35:08.770  1391  1402 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 09:35:08.772  2721  2770 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-07 09:35:08.772  2721  2770 D BluetoothAdapterProperties: Setting state to 16
09-07 09:35:08.772  2721  2770 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-07 09:35:08.773  2721  2770 D BluetoothAdapterProperties: onBleDisable
,09-07 09:35:08.773  2721  2770 I BluetoothAdapterState: Entering PendingCommandState
09-07 09:35:08.774  2721  2771 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-07 09:35:08.774  2721  2775 D BluetoothAdapterProperties: Scan Mode:20
09-07 09:35:08.775  2721  2902 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-07 09:35:08.775  2721  2902 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 09:35:08.776  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:35:08.776  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:35:08.776  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:08.776  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:35:08.776  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:35:08.776  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:35:08.776  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:35:08.776  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:35:08.776  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 09:35:08.776  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:35:08.776  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 09:35:08.778  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:35:08.778  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:35:08.778  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:08.778  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:35:08.778  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:35:08.778  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:35:08.778  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:35:08.778  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:35:08.778  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 09:35:08.779  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:35:08.779  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 09:35:08.780  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:08.781  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:35:08.792  3912  3912 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-07 09:35:08.799   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 09:35:08.801  3912  3912 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 09:35:08.806  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 09:35:08.809   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9ac736:true
,09-07 09:35:08.817   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 09:35:08.817   374   874 D CommandListener: Clearing all IP addresses on wlan0
09-07 09:35:08.818   876  1323 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-07 09:35:08.818   876  1708 I ActivityManager: Start proc 3929:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-07 09:35:08.818   876  1323 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 09:35:08.821   876  1319 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 09:35:08.822   876   893 D Tethering: MasterInitialState.processMessage what=3
09-07 09:35:08.823  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:08.825  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:35:08.829  3414  3414 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@60534e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-07 09:35:08.848   876  1319 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 09:35:08.850   876  1319 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 09:35:08.851  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:35:08.851  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:35:08.851  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:08.851  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:35:08.851  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 09:35:08.851  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:35:08.851  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:35:08.851  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:35:08.851  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 09:35:08.851  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:35:08.851  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 09:35:08.853  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:35:08.853  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:35:08.853  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:08.853  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:35:08.853  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 09:35:08.853  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:35:08.853  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:35:08.853  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:35:08.853  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 09:35:08.853  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:35:08.853  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 09:35:08.854  2123  2334 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:35:08.862  3912  3912 D LocalBluetoothProfileManager: Adding local MAP profile
,09-07 09:35:08.866  3912  3912 D BluetoothMap: Create BluetoothMap proxy object
,09-07 09:35:08.870   374   874 E Netd    : netlink response contains error (No such file or directory)
,09-07 09:35:08.871   876  1323 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-07 09:35:08.874  3929  3929 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-07 09:35:08.880  3912  3912 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-07 09:35:08.890  3912  3912 D DockEventReceiver: finishStartingService: stopping service
,09-07 09:35:08.896   876  1708 I ActivityManager: Killing 2994:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-07 09:35:08.977  2721  2775 I bt_hci  : shut_down
,09-07 09:35:08.978  2721  2795 D bt_hwcfg: hw_epilog_process
,09-07 09:35:08.987  2721  2795 I bt_vendor: low_power_mode_cb
,09-07 09:35:09.015  2721  2795 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-07 09:35:09.015  2721  2795 I bt_vendor: epilog_cb
09-07 09:35:09.015  2721  2795 I bt_hci  : epilog_finished_callback
,09-07 09:35:09.020  2721  2775 I bt_hci_h4: hal_close
,09-07 09:35:09.021  2721  2775 I bt_userial_vendor: device fd = 51 close
,09-07 09:35:09.053  3929  3929 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 09:35:09.053  3929  3929 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76),
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 09:35:09.053  3929  3929 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206),
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 09:35:09.053  3929  3929 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:10,2)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 09:35:09.053  3929  3929 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.r.k.d(PG:583)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:35:09.053  3929  3929 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 09:35:09.054  3929  3929 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 09:35:09.054  3929  3929 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 09:35:09.054  3929  3929 D StrictMode: StrictMode policy violation; ~duration=68 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:35:09.054  3929  3929 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 09:35:09.064  3912  3912 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 09:35:09.075  3912  3912 D DockEventReceiver: finishStartingService: stopping service
09-07 09:35:09.078  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 09:35:09.082   876  1708 I ActivityManager: Killing 3414:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-07 09:35:09.136  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 09:35:09.164  2721  2771 D bt_stack_manager: event_shut_down_stack finished.
,09-07 09:35:09.166  2721  2770 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-07 09:35:09.171  2721  2721 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 09:35:09.172  2721  2721 D BtGatt.GattService: Received stop request...Stopping profile...
,09-07 09:35:09.172  2721  2721 D BtGatt.GattService: stop()
09-07 09:35:09.172  2721  2721 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 09:35:09.173  2721  2770 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-07 09:35:09.175  1750  1750 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 09:35:09.177  2721  2721 V BluetoothAdapterState: isTurningOff()=false
,09-07 09:35:09.177  2721  2721 V BluetoothAdapterState: isTurningOn()=false
09-07 09:35:09.177  2721  2721 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 09:35:09.177  2721  2721 V BluetoothAdapterState: isBleTurningOff()=true
09-07 09:35:09.178  2721  2770 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-07 09:35:09.179  2721  2770 D BluetoothAdapterProperties: Setting state to 10
,09-07 09:35:09.179  2721  2770 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-07 09:35:09.180  2721  2770 I BluetoothAdapterState: Entering OffState
,09-07 09:35:09.181  1750  1750 D SystemUpdateService: onCreate
09-07 09:35:09.182   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-07 09:35:09.185  1750  1750 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 09:35:09.191  2721  2721 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-07 09:35:09.192  2721  2721 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-07 09:35:09.192  2721  2721 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-07 09:35:09.193  2721  2771 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-07 09:35:09.195  2721  2771 D bt_stack_manager: event_clean_up_stack finished.
,09-07 09:35:09.199  1750  1750 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-07 09:35:09.201  1750  2467 I iu.UploadsManager: num queued entries: 0
,09-07 09:35:09.201  1750  2467 I iu.UploadsManager: num updated entries: 0
,09-07 09:35:09.207  2721  2721 I art     : System.exit called, status: 0
09-07 09:35:09.207  2721  2721 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-07 09:35:09.224  1750  3964 I SystemUpdateService: active receiver: enabled
,09-07 09:35:09.226  1750  1750 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 09:35:09.227  1750  1750 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 09:35:09.237  1750  2467 I iu.SyncManager: NEXT; no task
,09-07 09:35:09.243  1750  3964 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 09:35:09.245  1750  3964 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-07 09:35:09.245  1750  3964 I SystemUpdateService: now status is 0 (complete)
09-07 09:35:09.245  1750  3964 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-07 09:35:09.245  1750  3964 I SystemUpdateService: file has been verified
09-07 09:35:09.245  1750  3964 I SystemUpdateService: OTA package size = 12249756
,09-07 09:35:09.251   876   886 I ActivityManager: Start proc 3967:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-07 09:35:09.270  1750  3964 I SystemUpdateService: showing system update notification
,09-07 09:35:09.271   876  1707 I ActivityManager: Process com.android.bluetooth (pid 2721) has died
,09-07 09:35:09.300  1750  1750 D SystemUpdateService: onDestroy
,09-07 09:35:09.311  3967  3967 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-07 09:35:09.314  3967  3967 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 09:35:09.326  3967  3967 D SprintDMHelper: simOperator: 
,09-07 09:35:09.326  3967  3967 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 09:35:09.343   876   886 I ActivityManager: Start proc 3980:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-07 09:35:09.344   876   886 I ActivityManager: Killing 3496:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-07 09:35:09.355  3929  3959 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-07 09:35:09.362   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3df0bb1:true
,09-07 09:35:09.480   876  1979 I ActivityManager: Start proc 3995:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-07 09:35:09.482  3106  3997 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-07 09:35:09.532  3995  3995 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-07 09:35:09.586  3995  3995 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-07 09:35:09.586  3995  3995 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-07 09:35:09.586  3995  3995 I GAv4    :   adb logcat -s GAv4
,09-07 09:35:09.601  3995  3995 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-07 09:35:09.608  3995  3995 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-07 09:35:09.646  3995  4013 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-07 09:35:09.747  3995  3995 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-07 09:35:09.789  3995  3995 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-07 09:35:09.802  3995  3995 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 7201-7208)
,09-07 09:35:09.802  3995  3995 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 09:35:09.815  3995  3995 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9433898}
,09-07 09:35:09.816  3995  3995 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 09:35:09.816  3995  3995 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-07 09:35:09.826  3995  3995 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-07 09:35:09.828  3995  3995 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-07 09:35:09.843  3995  3995 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-07 09:35:09.859  3995  3995 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-07 09:35:09.859  3995  3995 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 09:35:09.859  3995  3995 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 09:35:09.859  3995  3995 I Adreno  : Build Date                       : 10/20/15
09-07 09:35:09.859  3995  3995 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 09:35:09.859  3995  3995 I Adreno  : Local Branch                     : M14
09-07 09:35:09.859  3995  3995 I Adreno  : Remote Branch                    : 
09-07 09:35:09.859  3995  3995 I Adreno  : Remote Branch                    : 
09-07 09:35:09.859  3995  3995 I Adreno  : Reconstruct Branch               : 
,09-07 09:35:09.922  3995  3995 I NSApplication: Starting up...
,09-07 09:35:09.932  3995  4042 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-07 09:35:09.971   876  1727 I ActivityManager: Start proc 4047:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-07 09:35:09.972   876  1727 I ActivityManager: Killing 1711:android.process.acore/u0a5 (adj 15): empty #17
,09-07 09:35:10.050  4047  4047 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-07 09:35:10.247   876  1709 I ActivityManager: Killing 3652:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-07 09:35:10.322   876  1727 I ActivityManager: Start proc 4061:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-07 09:35:10.396  4061  4061 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-07 09:35:10.449  4061  4061 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-07 09:35:10.512   876  1405 I ActivityManager: Killing 3667:com.android.musicfx/u0a18 (adj 15): empty #17
,09-07 09:35:11.570  2123  2659 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-07 09:35:11.702   876  1980 D WifiService: setWifiEnabled: true pid=3820, uid=10000
09-07 09:35:11.702   876  1980 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 09:35:11.717   876  1319 D WifiConfigStore: Loading config and enabling all networks 
,09-07 09:35:11.726  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:35:11.726  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:35:11.726  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:11.726  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:35:11.726  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:35:11.726  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:35:11.726  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:35:11.726  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:35:11.726  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 09:35:11.726  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:35:11.727  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 09:35:11.730  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:35:11.730  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:35:11.730  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:11.730  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:35:11.730  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:35:11.730  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:35:11.730  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:35:11.730  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false,
09-07 09:35:11.730  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 09:35:11.731  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 09:35:11.731  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 09:35:11.755   876  1319 D WifiConfigStore: loaded 0 passpoint configs
,09-07 09:35:11.757   876  1319 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-07 09:35:11.757   876  1319 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-07 09:35:11.758   876  1319 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-07 09:35:11.758   876  1319 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-07 09:35:11.759   876  1319 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-07 09:35:11.759   876  1319 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-07 09:35:11.775   374   874 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-07 09:35:11.775   876  1319 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 09:35:11.778   374   874 D CommandListener: Setting iface cfg
,09-07 09:35:11.784   876  1318 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-07 09:35:11.784   876  1318 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-07 09:35:11.786   876  1319 E native  : do suspend true
,09-07 09:35:11.793   876  1318 D WifiNative-HAL: p2pGetDeviceAddress
,09-07 09:35:11.799   876  1318 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-07 09:35:11.802   876  1319 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 09:35:13.095   876  1319 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 09:35:13.152   876  1319 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=3.06 rxSuccessRate=6.50 delta 1000 -> 1000
,09-07 09:35:13.154   876  1319 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-07 09:35:13.155   876  1319 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 09:35:13.173   876  1319 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-07 09:35:13.230   876  1319 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-07 09:35:13.235  1471  1471 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 09:35:13.674  1471  1471 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 09:35:13.721  1471  1471 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 09:35:13.723  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-07 09:35:13.729   876  1319 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 09:35:13.749   876  1319 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 09:35:13.750   876  1319 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 09:35:13.750   876  1323 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-07 09:35:13.780   876  1319 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 09:35:13.805   374   874 D CommandListener: Setting iface cfg
,09-07 09:35:13.808   876  1319 D WifiStateMachine: Start Dhcp Watchdog 2
,09-07 09:35:13.833   876  1319 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-07 09:35:13.842   876  4094 D DhcpClient: Receive thread started
,09-07 09:35:13.930   876  1319 E native  : do suspend false
,09-07 09:35:13.942   876  1872 D DhcpClient: Broadcasting DHCPDISCOVER
,09-07 09:35:13.958   876  4094 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172662, domain null
,09-07 09:35:13.959   876  1872 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172662 seconds
,09-07 09:35:13.961   876  1872 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-07 09:35:13.981   876  4094 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-07 09:35:13.981   876  1872 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-07 09:35:13.985   374   874 D CommandListener: Setting iface cfg
,09-07 09:35:13.989   876  1319 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-07 09:35:13.991   876  1872 D DhcpClient: Scheduling renewal in 86399s
09-07 09:35:13.991   876  1319 E native  : do suspend true
,09-07 09:35:14.005   876  1319 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-07 09:35:14.005   876  1319 D WifiConfigStore: No blacklist allowed without epno enabled
09-07 09:35:14.006   876  1323 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-07 09:35:14.008   876  1319 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-07 09:35:14.008   876  1323 D ConnectivityService: Adding iface wlan0 to network 101
,09-07 09:35:14.042   876  1323 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-07 09:35:14.042   876  1323 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-07 09:35:14.043   876  1323 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-07 09:35:14.044   876  1323 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-07 09:35:14.045   876  1323 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-07 09:35:14.051   876  1323 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 09:35:14.056   876  1323 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-07 09:35:14.056   876  1323 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-07 09:35:14.056   876  1319 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-07 09:35:14.057   876  1319 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 09:35:14.057   876  1323 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-07 09:35:14.057   876  1323 D ConnectivityService:    accepting network in place of null
09-07 09:35:14.057   876  1323 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 09:35:14.077   876  4093 D NetlinkSocketObserver: NeighborEvent{elapsedMs=161483, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 09:35:14.100   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 09:35:14.133   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 09:35:14.136   876  1323 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-07 09:35:14.136   876  1323 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 09:35:14.151   876   893 D Tethering: MasterInitialState.processMessage what=3
,09-07 09:35:14.146   876  1323 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-07 09:35:14.155  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:35:14.155  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:35:14.155  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:14.155  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:35:14.155  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:35:14.155  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:35:14.155  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:35:14.155  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:35:14.155  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 09:35:14.156  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:35:14.156  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 09:35:14.161  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:35:14.161  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:35:14.161  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:14.161  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:35:14.161  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:35:14.161  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:35:14.161  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:35:14.161  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:35:14.161  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:35:14.161  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:35:14.162  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 09:35:14.163  1750  1750 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 09:35:14.167  1750  1750 D SystemUpdateService: onCreate
,09-07 09:35:14.169  1750  1750 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 09:35:14.174  1750  4106 I SystemUpdateService: active receiver: enabled
,09-07 09:35:14.177  1750  4106 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 09:35:14.178   876  4092 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-07 09:35:14.180  1750  4106 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-07 09:35:14.180  1750  4106 I SystemUpdateService: now status is 0 (complete)
09-07 09:35:14.180  1750  4106 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 09:35:14.180  1750  4106 I SystemUpdateService: file has been verified
09-07 09:35:14.181  1750  4106 I SystemUpdateService: OTA package size = 12249756
,09-07 09:35:14.187  1750  4106 I SystemUpdateService: showing system update notification
,09-07 09:35:14.192  1750  1750 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-07 09:35:14.193  1750  2467 I iu.UploadsManager: num queued entries: 0
,09-07 09:35:14.194  1750  2467 I iu.UploadsManager: num updated entries: 0
09-07 09:35:14.194  1750  2467 I iu.SyncManager: NEXT; no task
,09-07 09:35:14.198  1750  1750 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 09:35:14.199  1750  1750 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 09:35:14.202  3967  3967 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-07 09:35:14.203  1750  4109 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-07 09:35:14.203  1750  1750 D SystemUpdateService: onDestroy
09-07 09:35:14.203  1750  4109 W BaseAppContext: Using Auth Proxy for data requests.
09-07 09:35:14.204  1750  4109 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
09-07 09:35:14.207  3967  3967 D SprintDMHelper: simOperator: 
,09-07 09:35:14.207  3967  3967 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 09:35:14.213  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:35:14.218  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:35:14.254   876  4092 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 07:35:14 GMT], X-Android-Received-Millis=[1473233714252], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473233714221]}
,09-07 09:35:14.254  1524  2302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-07 09:35:14.254  1524  2302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-07 09:35:14.254  1524  2302 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 09:35:14.254  1524  2302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:35:14.256   876  1323 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-07 09:35:14.256   876  1323 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-07 09:35:14.257   876  1323 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 09:35:14.262   876  1323 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-07 09:35:14.277  1750  4109 E MDM     : [178] SitrepService.a: Error sending sitrep.
,09-07 09:35:14.331  3106  4111 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-07 09:35:14.489   876   886 I ActivityManager: Killing 3478:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-07 09:35:14.709   876  1978 D WifiService: setWifiEnabled: false pid=3820, uid=10000
,09-07 09:35:14.710   876  1978 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 09:35:14.745  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-07 09:35:14.757   876  1319 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-07 09:35:14.757   876  1319 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-07 09:35:14.758   876  1319 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 09:35:14.758   876  1319 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 09:35:14.783   876  1319 E native  : do suspend true
,09-07 09:35:14.795   876  1872 D DhcpClient: Clearing IP address
,09-07 09:35:14.796   374   874 D CommandListener: Clearing all IP addresses on wlan0
,09-07 09:35:14.801   374   874 D CommandListener: Setting iface cfg
,09-07 09:35:14.803  1524  4118 V NativeCrypto: Read error: ssl=0x9af7d000: I/O error during system call, Connection timed out
,09-07 09:35:14.811  1524  4118 V NativeCrypto: SSL shutdown failed: ssl=0x9af7d000: I/O error during system call, Broken pipe
,09-07 09:35:14.817   876  1537 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,09-07 09:35:14.817   876  4092 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
09-07 09:35:14.818   876  4092 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-07 09:35:14.818   876  4094 D DhcpClient: Receive thread stopped
09-07 09:35:14.819   876  1319 D WifiStateMachine: Start Disconnecting Watchdog 2
09-07 09:35:14.819   876  1323 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 09:35:14.820   876  1323 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-07 09:35:14.820   876  1319 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 09:35:14.820   876  1319 E native  : do suspend true
,09-07 09:35:14.830   412   412 E Parcel  : Reading a NULL string not supported here.
,09-07 09:35:14.836   374   874 D CommandListener: Clearing all IP addresses on wlan0
09-07 09:35:14.841   876  1319 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 09:35:14.841   876  1323 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-07 09:35:14.846   876  4092 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,09-07 09:35:14.855   876  1319 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 09:35:14.857  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:35:14.857  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:35:14.857  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:14.857  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:35:14.857  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 09:35:14.857  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:35:14.857  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:35:14.857  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:35:14.857  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 09:35:14.857  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:35:14.858  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 09:35:14.859  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 09:35:14.859  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:35:14.859  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:14.859  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:35:14.859  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 09:35:14.859  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:35:14.859  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:35:14.859  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:35:14.859  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 09:35:14.859  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:35:14.860  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 09:35:14.861   876  1319 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-07 09:35:14.866  2123  2334 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:35:14.878   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 09:35:14.902   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 09:35:14.904   876  1323 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-07 09:35:14.904   876  1323 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 09:35:14.908   876   893 D Tethering: MasterInitialState.processMessage what=3
,09-07 09:35:14.908  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:35:14.909  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:14.926  1750  1750 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 09:35:14.931  1750  1750 D SystemUpdateService: onCreate
,09-07 09:35:14.933  1750  1750 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 09:35:14.945  1750  1750 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-07 09:35:14.951  1750  2467 I iu.UploadsManager: num queued entries: 0
,09-07 09:35:14.954  1750  4128 I SystemUpdateService: active receiver: enabled
,09-07 09:35:14.956  1750  1750 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 09:35:14.957  1750  1750 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 09:35:14.959  3967  3967 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 09:35:14.964  3967  3967 D SprintDMHelper: simOperator: 
,09-07 09:35:14.964  3967  3967 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-07 09:35:14.971   374   874 E Netd    : netlink response contains error (No such file or directory)
,09-07 09:35:14.972   876  1323 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-07 09:35:14.951  1750  2467 I iu.UploadsManager: num updated entries: 0
,09-07 09:35:14.990  1750  2467 I iu.SyncManager: NEXT; no task
,09-07 09:35:14.990  1750  4128 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 09:35:14.995  3106  4132 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-07 09:35:14.998  1750  4128 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-07 09:35:14.998  1750  4128 I SystemUpdateService: now status is 0 (complete)
09-07 09:35:14.998  1750  4128 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 09:35:14.998  1750  4128 I SystemUpdateService: file has been verified
09-07 09:35:14.998  1750  4128 I SystemUpdateService: OTA package size = 12249756
,09-07 09:35:15.001  1750  4128 I SystemUpdateService: showing system update notification
,09-07 09:35:15.012  1750  1750 D SystemUpdateService: onDestroy
,09-07 09:35:15.137   876  1323 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-07 09:35:17.768   876   893 I ActivityManager: Start proc 4134:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-07 09:35:17.874  4134  4134 D AdapterServiceConfig: Adding HeadsetService
,09-07 09:35:17.875  4134  4134 D AdapterServiceConfig: Adding A2dpService
,09-07 09:35:17.875  4134  4134 D AdapterServiceConfig: Adding HidService
09-07 09:35:17.875  4134  4134 D AdapterServiceConfig: Adding HealthService
,09-07 09:35:17.875  4134  4134 D AdapterServiceConfig: Adding PanService
09-07 09:35:17.875  4134  4134 D AdapterServiceConfig: Adding GattService
,09-07 09:35:17.876  4134  4134 D AdapterServiceConfig: Adding BluetoothMapService
,09-07 09:35:17.894  4134  4134 D BluetoothAdapterState: make() - Creating AdapterState
09-07 09:35:17.894   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6df5c51:true
,09-07 09:35:17.899  4134  4134 I bt_bluedroid: init
,09-07 09:35:17.901  4134  4146 I BluetoothAdapterState: Entering OffState
,09-07 09:35:17.906  4134  4147 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-07 09:35:17.907  4134  4147 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-07 09:35:17.907  4134  4147 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 09:35:17.908  4134  4147 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-07 09:35:17.910  4134  4134 I bt_bluedroid: get_profile_interface socket
,09-07 09:35:17.914  4134  4134 I bt_bluedroid: get_profile_interface sdp
,09-07 09:35:17.915  4134  4150 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 09:35:17.918  4134  4150 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 09:35:17.922  4134  4145 I bt_bluedroid: config_hci_snoop_log
,09-07 09:35:17.925   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-07 09:35:17.936  4134  4146 D BluetoothAdapterState: Current state: OFF, message: 0
,09-07 09:35:17.936  4134  4146 D BluetoothAdapterProperties: Setting state to 14
09-07 09:35:17.937  4134  4146 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-07 09:35:17.941  4134  4146 D BluetoothBondStateMachine: make
,09-07 09:35:17.945  4134  4151 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-07 09:35:17.954  4134  4146 I BluetoothAdapterState: Entering PendingCommandState
,09-07 09:35:17.955  4134  4134 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-07 09:35:17.963  4134  4134 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48688e
,09-07 09:35:17.965  4134  4134 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 09:35:17.966  4134  4134 D BtGatt.GattService: Received start request. Starting profile...
09-07 09:35:17.968  4134  4134 D BtGatt.GattService: start()
,09-07 09:35:17.968  4134  4134 I bt_bluedroid: get_profile_interface gatt
09-07 09:35:17.969  4134  4134 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48688e
09-07 09:35:17.969  4134  4134 D BtGatt.AdvertiseManager: advertise manager created
,09-07 09:35:17.983  4134  4134 V BluetoothAdapterState: isTurningOff()=false
,09-07 09:35:17.983  4134  4134 V BluetoothAdapterState: isTurningOn()=false
09-07 09:35:17.983  4134  4134 V BluetoothAdapterState: isBleTurningOn()=true
09-07 09:35:17.983  4134  4134 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 09:35:17.983  4134  4146 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-07 09:35:17.985  4134  4146 I bt_bluedroid: enable
09-07 09:35:17.986  4134  4147 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-07 09:35:17.987  4134  4147 I bt_hci  : start_up
,09-07 09:35:18.007  4134  4147 I bt_vendor: alloc value 0xb3a3f189
,09-07 09:35:18.007  4134  4147 I bt_vendor: init
09-07 09:35:18.008  4134  4147 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-07 09:35:18.008  4134  4147 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-07 09:35:18.115  4134  4147 D bt_hci  : start_up starting async portion
09-07 09:35:18.115  4134  4154 I bt_hci  : event_finish_startup
09-07 09:35:18.116  4134  4154 I bt_hci_h4: hal_open
,09-07 09:35:18.116  4134  4154 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-07 09:35:18.125  4134  4154 I bt_userial_vendor: device fd = 51 open
,09-07 09:35:18.157  4134  4154 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 09:35:18.189  4134  4154 D bt_hwcfg: Chipset BCM4354A2
,09-07 09:35:18.190  4134  4154 D bt_hwcfg: Target name = [BCM4354A2]
,09-07 09:35:18.191  4134  4154 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-07 09:35:18.851  4134  4154 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-07 09:35:18.853  4134  4154 D bt_hwcfg: Settlement delay -- 100 ms
,09-07 09:35:18.853  4134  4154 I bt_hwcfg: Setting fw settlement delay to 100 
,09-07 09:35:18.970  4134  4154 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 09:35:18.971  4134  4154 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-07 09:35:19.000  4134  4154 I bt_hwcfg: vendor lib fwcfg completed
,09-07 09:35:19.000  4134  4154 I bt_vendor: firmware callback
09-07 09:35:19.001  4134  4154 I bt_hci  : firmware_config_callback
,09-07 09:35:19.011  4134  4156 I bt_btu  : btu_task pending for preload complete event
,09-07 09:35:19.012  4134  4156 I bt_btu_task: Bluetooth chip preload is complete
,09-07 09:35:19.012  4134  4156 I bt_btu  : btu_task received preload complete event
,09-07 09:35:19.022  4134  4156 I         : BTE_InitTraceLevels -- TRC_HCI
,09-07 09:35:19.022  4134  4156 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 09:35:19.022  4134  4156 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-07 09:35:19.023  4134  4156 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-07 09:35:19.023  4134  4156 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 09:35:19.023  4134  4156 I         : BTE_InitTraceLevels -- TRC_A2D
,09-07 09:35:19.024  4134  4156 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 09:35:19.024  4134  4156 I         : BTE_InitTraceLevels -- TRC_BTM
,09-07 09:35:19.024  4134  4156 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 09:35:19.024  4134  4156 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 09:35:19.025  4134  4156 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 09:35:19.025  4134  4156 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 09:35:19.025  4134  4156 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 09:35:19.025  4134  4156 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 09:35:19.026  4134  4156 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 09:35:19.156  4134  4156 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39bcd9d
,09-07 09:35:19.156  4134  4156 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39bcd9d 
,09-07 09:35:19.167  4134  4150 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-07 09:35:19.168  4134  4150 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-07 09:35:19.169  4134  4150 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-07 09:35:19.172  4134  4150 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 09:35:19.176  4134  4150 D BluetoothAdapterProperties: Scan Mode:20
,09-07 09:35:19.176  4134  4150 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 09:35:19.177  4134  4150 D bt_hci  : do_postload posting postload work item
,09-07 09:35:19.178  4134  4154 I bt_hci  : event_postload
09-07 09:35:19.178  4134  4154 I bt_vendor: sco_config_cb
,09-07 09:35:19.178  4134  4154 I bt_hci  : sco_config_callback postload finished.
,09-07 09:35:19.179  4134  4150 D bt_bte_conf: Device ID record 1 : primary
09-07 09:35:19.180  4134  4150 D bt_bte_conf:   vendorId            = 000f
09-07 09:35:19.180  4134  4150 D bt_bte_conf:   vendorIdSource      = 0001
09-07 09:35:19.180  4134  4150 D bt_bte_conf:   product             = 1200
09-07 09:35:19.180  4134  4150 D bt_bte_conf:   version             = 1436
09-07 09:35:19.180  4134  4150 D bt_bte_conf:   clientExecutableURL = 
,09-07 09:35:19.181  4134  4150 D bt_bte_conf:   serviceDescription  = 
,09-07 09:35:19.181  4134  4150 D bt_bte_conf:   documentationURL    = 
,09-07 09:35:19.181  4134  4150 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-07 09:35:19.181  4134  4147 D bt_stack_manager: event_start_up_stack finished
09-07 09:35:19.182  4134  4146 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-07 09:35:19.183  4134  4146 D BluetoothAdapterProperties: Setting state to 15
09-07 09:35:19.183  4134  4146 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-07 09:35:19.185  4134  4154 I bt_vendor: low_power_mode_cb
09-07 09:35:19.186  4134  4146 I BluetoothAdapterState: Entering BleOnState
09-07 09:35:19.187  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:19.191  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:19.192  4134  4146 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-07 09:35:19.192  4134  4146 D BluetoothAdapterProperties: Setting state to 11
09-07 09:35:19.192  4134  4146 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-07 09:35:19.201  4134  4134 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48688e
09-07 09:35:19.204  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:19.205  4134  4134 D HeadsetService: Received start request. Starting profile...
09-07 09:35:19.206  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:35:19.211  4134  4146 I BluetoothAdapterState: Entering PendingCommandState
,09-07 09:35:19.212  4134  4134 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-07 09:35:19.212  4134  4134 D HeadsetStateMachine: make
,09-07 09:35:19.224  4134  4134 D HeadsetStateMachine: max_hf_connections = 1
,09-07 09:35:19.224  4134  4134 I bt_bluedroid: get_profile_interface handsfree
09-07 09:35:19.224  4134  4150 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-07 09:35:19.224  4134  4150 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-07 09:35:19.230  4134  4134 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48688e
,09-07 09:35:19.231  4134  4134 D A2dpService: Received start request. Starting profile...
,09-07 09:35:19.232  4134  4134 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-07 09:35:19.232  4134  4134 I bt_bluedroid: get_profile_interface avrcp
,09-07 09:35:19.239  4134  4134 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-07 09:35:19.240  4134  4134 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 09:35:19.240  4134  4134 D A2dpStateMachine: make
,09-07 09:35:19.241  4134  4134 I bt_bluedroid: get_profile_interface a2dp
,09-07 09:35:19.243  4134  4150 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-07 09:35:19.244  4134  4166 D A2dpStateMachine: Enter Disconnected: -2
,09-07 09:35:19.245  4134  4134 I BluetoothHidServiceJni: classInitNative: succeeds
,09-07 09:35:19.246  4134  4134 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48688e
,09-07 09:35:19.247  4134  4134 D HidService: Received start request. Starting profile...
,09-07 09:35:19.248  4134  4134 I bt_bluedroid: get_profile_interface hidhost
,09-07 09:35:19.248  4134  4134 D HidService: setHidService(): set to: null,
,09-07 09:35:19.248  4134  4150 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb399e3e5
,09-07 09:35:19.248  4134  4150 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-07 09:35:19.248  4134  4134 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-07 09:35:19.249  4134  4134 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48688e
,09-07 09:35:19.250  4134  4134 D HealthService: Received start request. Starting profile...
,09-07 09:35:19.252  4134  4134 I bt_bluedroid: get_profile_interface health
09-07 09:35:19.253  4134  4134 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-07 09:35:19.253  4134  4134 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48688e
09-07 09:35:19.254  3912  3912 D BluetoothInputDevice: Proxy object connected
09-07 09:35:19.255  4134  4134 D PanService: Received start request. Starting profile...
,09-07 09:35:19.255  4134  4134 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 09:35:19.255  3912  3912 D HidProfile: Bluetooth service connected
09-07 09:35:19.255  4134  4134 I bt_bluedroid: get_profile_interface pan
09-07 09:35:19.256  4134  4150 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-07 09:35:19.256  3912  3912 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 09:35:19.257  3912  3912 D PanProfile: Bluetooth service connected
09-07 09:35:19.260  4134  4134 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48688e
,09-07 09:35:19.262  4134  4134 D BluetoothMapService: Received start request. Starting profile...
09-07 09:35:19.262  4134  4134 D BluetoothMapService: start()
09-07 09:35:19.262  3912  3912 D BluetoothMap: Proxy object connected
,09-07 09:35:19.264  3912  3912 D MapProfile: Bluetooth service connected
,09-07 09:35:19.265  3912  3912 D BluetoothMap: getConnectedDevices()
,09-07 09:35:19.266  4134  4134 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-07 09:35:19.267  3912  3912 D BluetoothMap: Bluetooth is Not enabled
09-07 09:35:19.267  4134  4134 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-07 09:35:19.267  4134  4134 D BluetoothMapAppObserver: createReceiver()
,09-07 09:35:19.269  4134  4134 D BluetoothMapAppObserver: initObservers()
,09-07 09:35:19.269  4134  4134 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-07 09:35:19.282  4134  4134 V BluetoothAdapterState: isTurningOff()=false
09-07 09:35:19.282  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 09:35:19.282  4134  4134 V BluetoothAdapterState: isTurningOn()=true
09-07 09:35:19.282  4134  4134 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 09:35:19.282  4134  4134 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:35:19.285  4134  4134 V BluetoothAdapterState: isTurningOff()=false
,09-07 09:35:19.285  4134  4134 V BluetoothAdapterState: isTurningOn()=true
09-07 09:35:19.285  4134  4134 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 09:35:19.286  4134  4134 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:35:19.286  4134  4134 V BluetoothAdapterState: isTurningOff()=false
09-07 09:35:19.286  4134  4134 V BluetoothAdapterState: isTurningOn()=true
09-07 09:35:19.286  4134  4134 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 09:35:19.286  4134  4134 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:35:19.286  4134  4134 V BluetoothAdapterState: isTurningOff()=false
09-07 09:35:19.286  4134  4134 V BluetoothAdapterState: isTurningOn()=true
09-07 09:35:19.286  4134  4134 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 09:35:19.286  4134  4164 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 09:35:19.286  4134  4134 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:35:19.286  4134  4134 V BluetoothAdapterState: isTurningOff()=false
,09-07 09:35:19.287  4134  4134 V BluetoothAdapterState: isTurningOn()=true
09-07 09:35:19.287  4134  4134 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 09:35:19.287  4134  4134 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 09:35:19.287  4134  4134 V BluetoothAdapterState: isTurningOff()=false
,09-07 09:35:19.287  4134  4134 V BluetoothAdapterState: isTurningOn()=true
,09-07 09:35:19.287  4134  4134 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 09:35:19.287  4134  4134 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:35:19.287  4134  4146 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-07 09:35:19.287  4134  4146 D BluetoothAdapterProperties: ScanMode =  20
,09-07 09:35:19.287  4134  4146 D BluetoothAdapterProperties: State =  11
09-07 09:35:19.288  4134  4146 D BluetoothAdapterProperties: Setting state to 12
09-07 09:35:19.288  4134  4146 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-07 09:35:19.289   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 09:35:19.289   876   893 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 09:35:19.290  4134  4150 D BluetoothAdapterProperties: Scan Mode:21
,09-07 09:35:19.290  4134  4150 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 09:35:19.291  1966  1976 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 09:35:19.291  4134  4146 I BluetoothAdapterState: Entering OnState
09-07 09:35:19.291   876   876 D BluetoothA2dp: Proxy object connected
09-07 09:35:19.292  1391  1402 D BluetoothPan: onBluetoothStateChange on: true
,09-07 09:35:19.293  3820  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-07 09:35:19.294   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 09:35:19.294  1391  1391 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 09:35:19.294  1391  1391 D PanProfile: Bluetooth service connected
,09-07 09:35:19.294  1391  1404 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 09:35:19.296   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 09:35:19.296  1391  1391 D BluetoothA2dp: Proxy object connected
09-07 09:35:19.297  1391  1402 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 09:35:19.297  3820  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-07 09:35:19.299  1391  1391 D BluetoothInputDevice: Proxy object connected
,09-07 09:35:19.300  1391  1391 D HidProfile: Bluetooth service connected
09-07 09:35:19.300  3912  3924 D BluetoothPan: onBluetoothStateChange on: true
09-07 09:35:19.301  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:35:19.301  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:19.301  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:35:19.301  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 09:35:19.301  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:35:19.301  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:35:19.301  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:35:19.301  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 09:35:19.300  4134  4134 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-07 09:35:19.303  3912  3922 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 09:35:19.303  3912  3924 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 09:35:19.303  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 09:35:19.304  4134  4134 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-07 09:35:19.305  1391  1404 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 09:35:19.306  1391  2093 D BluetoothMap: onBluetoothStateChange: up=true
,09-07 09:35:19.308  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:35:19.308  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:19.308  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:35:19.308  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 09:35:19.308  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:35:19.308  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:35:19.308  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:35:19.308  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 09:35:19.308  4134  4134 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 09:35:19.309  1391  1391 D BluetoothMap: Proxy object connected
09-07 09:35:19.309  1391  1391 D MapProfile: Bluetooth service connected
,09-07 09:35:19.309  1391  1391 D BluetoothMap: getConnectedDevices()
09-07 09:35:19.311  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 09:35:19.312  1391  1404 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 09:35:19.312  4134  4134 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 09:35:19.314  4134  4134 D ObexServerSockets: Succeed to create listening sockets 
09-07 09:35:19.314  4134  4134 D ObexServerSockets0: startAccept()
09-07 09:35:19.314  4134  4134 D ObexServerSockets0: prepareForNewConnect()
,09-07 09:35:19.316  3912  3922 D BluetoothMap: onBluetoothStateChange: up=true
09-07 09:35:19.316  4134  4134 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-07 09:35:19.317  4134  4134 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-07 09:35:19.318  4134  4172 D ObexServerSockets0: Accepting socket connection...
,09-07 09:35:19.318   876   876 I Telecom : BluetoothPhoneService: queryPhoneState
09-07 09:35:19.320  4134  4134 D BluetoothMapService: onReceive
,09-07 09:35:19.320  4134  4134 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 09:35:19.320  4134  4134 D BluetoothMapService: STATE_ON
09-07 09:35:19.321  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:19.322  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:35:19.322  4134  4173 D ObexServerSockets0: Accepting socket connection...
09-07 09:35:19.325  3912  3912 D LocalBluetoothProfileManager: Adding local A2DP profile
09-07 09:35:19.329  3912  3912 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-07 09:35:19.334  3912  3912 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 09:35:19.336  3912  3912 D BluetoothA2dp: Proxy object connected
,09-07 09:35:19.339  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 09:35:19.344  3912  3912 D DockEventReceiver: finishStartingService: stopping service
,09-07 09:35:19.348  1391  1391 D BluetoothPbap: Proxy object connected
09-07 09:35:19.348  1391  1391 D PbapServerProfile: Bluetooth service connected
09-07 09:35:19.347  3912  3912 D BluetoothPbap: Proxy object connected
09-07 09:35:19.348  4134  4134 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-07 09:35:19.348  4134  4134 D ObexServerSockets0: prepareForNewConnect()
,09-07 09:35:19.348  3912  3912 D PbapServerProfile: Bluetooth service connected
,09-07 09:35:19.354  4134  4177 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 09:35:19.365  4134  4181 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 09:35:19.366  4134  4181 I BtOppRfcommListener: Accept thread started.
,09-07 09:35:19.391   876   876 D BluetoothHeadset: Proxy object connected
,09-07 09:35:19.392  1391  1404 D BluetoothHeadset: Proxy object connected
,09-07 09:35:19.392  1391  1391 D HeadsetProfile: Bluetooth service connected
09-07 09:35:19.392   876   876 D BluetoothHeadset: Proxy object connected
09-07 09:35:19.392  1966  2283 D BluetoothHeadset: Proxy object connected
09-07 09:35:19.393   876   876 D BluetoothHeadset: Proxy object connected
,09-07 09:35:19.394   876   893 D BluetoothHeadset: Proxy object connected
,09-07 09:35:19.398   876   893 D BluetoothHeadset: Proxy object connected
,09-07 09:35:19.406  1391  2093 D BluetoothHeadset: Proxy object connected
09-07 09:35:19.406  1391  1391 D HeadsetProfile: Bluetooth service connected
,09-07 09:35:19.432  3912  3924 D BluetoothHeadset: Proxy object connected
09-07 09:35:19.433  3912  3912 D HeadsetProfile: Bluetooth service connected
,09-07 09:35:20.733  4134  4146 D BluetoothAdapterState: Current state: ON, message: 23
,09-07 09:35:20.734  4134  4146 D BluetoothAdapterProperties: Setting state to 13
09-07 09:35:20.734  4134  4146 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-07 09:35:20.736  4134  4146 D BluetoothAdapterProperties: onBluetoothDisable()
,09-07 09:35:20.743  4134  4146 I BluetoothAdapterState: Entering PendingCommandState
,09-07 09:35:20.746  4134  4134 D BluetoothMapService: onReceive
,09-07 09:35:20.747  4134  4134 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 09:35:20.747  4134  4134 D BluetoothMapService: STATE_TURNING_OFF
09-07 09:35:20.748  4134  4150 D BluetoothAdapterProperties: Scan Mode:20
,09-07 09:35:20.750  4134  4146 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-07 09:35:20.748  4134  4134 D BluetoothMapService: MAP Service closeService in
,09-07 09:35:20.751  4134  4134 D BluetoothMapMasInstance0: MAP Service shutdown
09-07 09:35:20.751  4134  4134 D ObexServerSockets0: shutdown(block = true)
09-07 09:35:20.752  4134  4172 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-07 09:35:20.753  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:35:20.754  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:35:20.754  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:20.754  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:35:20.754  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 09:35:20.754  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:35:20.754  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:35:20.754  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:35:20.754  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 09:35:20.755  4134  4134 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-07 09:35:20.755  4134  4173 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-07 09:35:20.758  4134  4158 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-07 09:35:20.758  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:35:20.758  4134  4134 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-07 09:35:20.758  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 09:35:20.759  4134  4134 I BtOppRfcommListener: stopping Accept Thread
,09-07 09:35:20.759  4134  4181 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 09:35:20.761  4134  4181 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 09:35:20.762  3912  3912 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 09:35:20.764  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:35:20.764  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:35:20.764  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:20.764  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:35:20.764  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 09:35:20.764  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 09:35:20.764  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:35:20.764  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:35:20.764  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 09:35:20.767  4134  4134 D HeadsetService: Received stop request...Stopping profile...
09-07 09:35:20.767  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 09:35:20.767  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 09:35:20.768   876   876 D BluetoothHeadset: Proxy object disconnected
09-07 09:35:20.769  1391  1402 D BluetoothHeadset: Proxy object disconnected
09-07 09:35:20.770  3912  3924 D BluetoothHeadset: Proxy object disconnected
09-07 09:35:20.770   876   876 D BluetoothHeadset: Proxy object disconnected
09-07 09:35:20.770  1966  2119 D BluetoothHeadset: Proxy object disconnected
09-07 09:35:20.770  4134  4134 D A2dpService: Received stop request...Stopping profile...
,09-07 09:35:20.771  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:20.771   876   876 D BluetoothHeadset: Proxy object disconnected
09-07 09:35:20.771  4134  4166 D A2dpStateMachine: Exit Disconnected: -1
09-07 09:35:20.772  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:35:20.775   876   876 D BluetoothA2dp: Proxy object disconnected
,09-07 09:35:20.777  4134  4134 D HidService: Received stop request...Stopping profile...
,09-07 09:35:20.778  4134  4134 D HidService: Stopping Bluetooth HidService
,09-07 09:35:20.778  1391  1391 D HeadsetProfile: Bluetooth service disconnected
,09-07 09:35:20.779  1391  1391 D BluetoothA2dp: Proxy object disconnected
09-07 09:35:20.779  4134  4134 D HealthService: Received stop request...Stopping profile...
09-07 09:35:20.779  1391  1391 D BluetoothInputDevice: Proxy object disconnected
09-07 09:35:20.779  1391  1391 D HidProfile: Bluetooth service disconnected
,09-07 09:35:20.780  4134  4134 D PanService: Received stop request...Stopping profile...
,09-07 09:35:20.781  1391  1391 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 09:35:20.781  1391  1391 D PanProfile: Bluetooth service disconnected
,09-07 09:35:20.782  4134  4134 D BluetoothMapService: Received stop request...Stopping profile...
09-07 09:35:20.782  4134  4134 D BluetoothMapService: stop()
09-07 09:35:20.782  4134  4134 D BluetoothMapAppObserver: deinitObservers()
09-07 09:35:20.783  4134  4134 D BluetoothMapAppObserver: removeReceiver()
09-07 09:35:20.783  3912  3912 D DockEventReceiver: finishStartingService: stopping service
09-07 09:35:20.784  1391  1391 D BluetoothMap: Proxy object disconnected
09-07 09:35:20.784  1391  1391 D MapProfile: Bluetooth service disconnected
,09-07 09:35:20.784  3912  3912 D HeadsetProfile: Bluetooth service disconnected
09-07 09:35:20.784  3912  3912 D BluetoothA2dp: Proxy object disconnected
09-07 09:35:20.785  3912  3912 D BluetoothInputDevice: Proxy object disconnected
09-07 09:35:20.785  3912  3912 D HidProfile: Bluetooth service disconnected
,09-07 09:35:20.785  3912  3912 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 09:35:20.786  3912  3912 D PanProfile: Bluetooth service disconnected
,09-07 09:35:20.786  4134  4134 V BluetoothAdapterState: isTurningOff()=true
09-07 09:35:20.786  4134  4134 V BluetoothAdapterState: isTurningOn()=false
09-07 09:35:20.786  4134  4134 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:35:20.786  4134  4134 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 09:35:20.789  4134  4134 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-07 09:35:20.789  4134  4134 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 09:35:20.790  4134  4150 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-07 09:35:20.790  4134  4156 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 09:35:20.790  4134  4156 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 09:35:20.790  4134  4156 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 09:35:20.790  4134  4150 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
,09-07 09:35:20.792  4134  4134 V BluetoothAdapterState: isTurningOff()=true
,09-07 09:35:20.792  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 09:35:20.792  4134  4134 V BluetoothAdapterState: isTurningOn()=false
09-07 09:35:20.792  4134  4134 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:35:20.792  4134  4134 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 09:35:20.793  4134  4150 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-07 09:35:20.793  4134  4156 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 09:35:20.793  4134  4156 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 09:35:20.793  4134  4156 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 09:35:20.793  4134  4156 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 09:35:20.793  4134  4156 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 09:35:20.793  4134  4156 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-07 09:35:20.796  3912  3912 D BluetoothMap: Proxy object disconnected
,09-07 09:35:20.797  3912  3912 D MapProfile: Bluetooth service disconnected
,09-07 09:35:20.797  4134  4134 V BluetoothAdapterState: isTurningOff()=true
09-07 09:35:20.797  4134  4134 V BluetoothAdapterState: isTurningOn()=false
,09-07 09:35:20.797  4134  4134 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 09:35:20.797  4134  4134 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 09:35:20.797  4134  4134 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 09:35:20.797  4134  4134 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 09:35:20.798  4134  4134 V BluetoothAdapterState: isTurningOff()=true
,09-07 09:35:20.798  4134  4134 V BluetoothAdapterState: isTurningOn()=false
09-07 09:35:20.798  4134  4134 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:35:20.798  4134  4150 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-07 09:35:20.798  4134  4134 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:35:20.798  4134  4134 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-07 09:35:20.798  4134  4150 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-07 09:35:20.798  4134  4134 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 09:35:20.799  4134  4134 V BluetoothAdapterState: isTurningOff()=true
,09-07 09:35:20.799  4134  4134 V BluetoothAdapterState: isTurningOn()=false
,09-07 09:35:20.799  4134  4134 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:35:20.799  4134  4134 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:35:20.799  4134  4134 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 09:35:20.799  4134  4134 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 09:35:20.800  4134  4134 D BluetoothMapService: MAP Service closeService in
09-07 09:35:20.800  4134  4134 V BluetoothAdapterState: isTurningOff()=true
09-07 09:35:20.800  4134  4134 V BluetoothAdapterState: isTurningOn()=false
09-07 09:35:20.800  4134  4134 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:35:20.800  4134  4134 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:35:20.801  4134  4146 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-07 09:35:20.801  4134  4146 D BluetoothAdapterProperties: Setting state to 15
09-07 09:35:20.801  4134  4146 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-07 09:35:20.802  4134  4146 I BluetoothAdapterState: Entering BleOnState
09-07 09:35:20.802   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 09:35:20.802   876   893 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 09:35:20.802  4134  4134 D BluetoothMapService: cleanup()
09-07 09:35:20.802  4134  4134 D BluetoothMapService: MAP Service closeService in
09-07 09:35:20.802  1966  1977 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 09:35:20.803  1391  1402 D BluetoothPan: onBluetoothStateChange on: false
09-07 09:35:20.804  1391  1391 D BluetoothPbap: Proxy object disconnected
09-07 09:35:20.804  1391  1391 D PbapServerProfile: Bluetooth service disconnected
09-07 09:35:20.804   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 09:35:20.804  1391  1402 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 09:35:20.805  3912  3924 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 09:35:20.805   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 09:35:20.805  1391  2093 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 09:35:20.805  3912  3912 D BluetoothPbap: Proxy object disconnected
09-07 09:35:20.805  3912  3912 D PbapServerProfile: Bluetooth service disconnected
09-07 09:35:20.808  3912  3924 D BluetoothPan: onBluetoothStateChange on: false
09-07 09:35:20.810  3912  3922 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 09:35:20.810  3912  3924 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 09:35:20.811  3912  3922 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 09:35:20.811  1391  1404 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 09:35:20.812  1391  1402 D BluetoothMap: onBluetoothStateChange: up=false
09-07 09:35:20.812  1391  2093 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 09:35:20.813  3912  3924 D BluetoothMap: onBluetoothStateChange: up=false
,09-07 09:35:20.815  4134  4146 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-07 09:35:20.815  4134  4146 D BluetoothAdapterProperties: Setting state to 16
09-07 09:35:20.815  4134  4146 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-07 09:35:20.817  4134  4146 D BluetoothAdapterProperties: onBleDisable
09-07 09:35:20.817  4134  4146 I BluetoothAdapterState: Entering PendingCommandState
,09-07 09:35:20.817  4134  4147 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-07 09:35:20.818  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:35:20.818  4134  4156 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-07 09:35:20.818  4134  4156 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 09:35:20.819  4134  4150 D BluetoothAdapterProperties: Scan Mode:20
,09-07 09:35:20.819  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:20.821  3912  3912 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 09:35:20.821  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:20.822  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:35:20.825  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 09:35:20.829  3912  3912 D DockEventReceiver: finishStartingService: stopping service
,09-07 09:35:21.018  4134  4150 I bt_hci  : shut_down
09-07 09:35:21.019  4134  4154 D bt_hwcfg: hw_epilog_process
,09-07 09:35:21.033  4134  4154 I bt_vendor: low_power_mode_cb
,09-07 09:35:21.056  4134  4154 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-07 09:35:21.056  4134  4154 I bt_vendor: epilog_cb
09-07 09:35:21.056  4134  4154 I bt_hci  : epilog_finished_callback
,09-07 09:35:21.063  4134  4150 I bt_hci_h4: hal_close
,09-07 09:35:21.065  4134  4150 I bt_userial_vendor: device fd = 51 close
,09-07 09:35:21.190  4134  4147 D bt_stack_manager: event_shut_down_stack finished.
,09-07 09:35:21.191  4134  4146 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-07 09:35:21.198  4134  4146 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-07 09:35:21.199  4134  4134 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 09:35:21.200  4134  4134 D BtGatt.GattService: Received stop request...Stopping profile...
09-07 09:35:21.201  4134  4134 D BtGatt.GattService: stop()
09-07 09:35:21.201  4134  4134 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 09:35:21.206  4134  4134 V BluetoothAdapterState: isTurningOff()=false
,09-07 09:35:21.207  4134  4134 V BluetoothAdapterState: isTurningOn()=false
09-07 09:35:21.207  4134  4134 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 09:35:21.208  4134  4134 V BluetoothAdapterState: isBleTurningOff()=true
,09-07 09:35:21.209  4134  4146 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-07 09:35:21.211  4134  4146 D BluetoothAdapterProperties: Setting state to 10
,09-07 09:35:21.211  4134  4146 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-07 09:35:21.213  4134  4146 I BluetoothAdapterState: Entering OffState
,09-07 09:35:21.215   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-07 09:35:21.245  4134  4134 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-07 09:35:21.246  4134  4134 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-07 09:35:21.246  4134  4147 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-07 09:35:21.256  4134  4147 D bt_stack_manager: event_clean_up_stack finished.
09-07 09:35:21.256  4134  4134 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-07 09:35:21.258  4134  4134 I art     : System.exit called, status: 0
,09-07 09:35:21.258  4134  4134 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-07 09:35:21.318   876  1980 I ActivityManager: Process com.android.bluetooth (pid 4134) has died
,09-07 09:35:22.063   876  1323 D ConnectivityService: handlePromptUnvalidated 101
,09-07 09:35:22.842  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:35:22.848  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:35:22.850  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:35:22.873  1524  2307 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 09:35:22.873  1524  2307 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-07 09:35:22.873  1524  2307 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 09:35:22.873  1524  2307 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:35:22.894  3541  3541 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-07 09:35:22.894  3541  3541 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-07 09:35:22.894  3541  3541 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-07 09:35:23.731  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 09:35:23.731  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:35:23.738  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 09:35:23.739  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b814d80 added. We now have 6 listener(s)
,09-07 09:35:23.739  3820  3869 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 09:35:23.743  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 09:35:23.743  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cab2fb9 added. We now have 7 listener(s)
09-07 09:35:23.744  3820  3869 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 09:35:23.745  3820  3869 I System.out: IsBluetoothEnabled
,09-07 09:35:23.755  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:35:23.794   876   893 I ActivityManager: Start proc 4191:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-07 09:35:23.909  4191  4191 D AdapterServiceConfig: Adding HeadsetService
,09-07 09:35:23.909  4191  4191 D AdapterServiceConfig: Adding A2dpService
09-07 09:35:23.910  4191  4191 D AdapterServiceConfig: Adding HidService
09-07 09:35:23.910  4191  4191 D AdapterServiceConfig: Adding HealthService
,09-07 09:35:23.910  4191  4191 D AdapterServiceConfig: Adding PanService
09-07 09:35:23.910  4191  4191 D AdapterServiceConfig: Adding GattService
09-07 09:35:23.911  4191  4191 D AdapterServiceConfig: Adding BluetoothMapService
,09-07 09:35:23.926  4191  4191 D BluetoothAdapterState: make() - Creating AdapterState
,09-07 09:35:23.926   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a5448b:true
,09-07 09:35:23.934  4191  4191 I bt_bluedroid: init
,09-07 09:35:23.934  4191  4203 I BluetoothAdapterState: Entering OffState
,09-07 09:35:23.940  4191  4204 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-07 09:35:23.940  4191  4204 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-07 09:35:23.941  4191  4204 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 09:35:23.941  4191  4204 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-07 09:35:23.943  4191  4191 I bt_bluedroid: get_profile_interface socket
,09-07 09:35:23.945  4191  4207 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 09:35:23.948  4191  4191 I bt_bluedroid: get_profile_interface sdp
,09-07 09:35:23.948  4191  4207 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 09:35:23.955  4191  4202 I bt_bluedroid: config_hci_snoop_log
,09-07 09:35:23.959   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-07 09:35:23.972  4191  4203 D BluetoothAdapterState: Current state: OFF, message: 0
,09-07 09:35:23.973  4191  4203 D BluetoothAdapterProperties: Setting state to 14
,09-07 09:35:23.974  4191  4203 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-07 09:35:23.979  4191  4203 D BluetoothBondStateMachine: make
,09-07 09:35:23.985  4191  4208 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-07 09:35:23.992  4191  4203 I BluetoothAdapterState: Entering PendingCommandState
,09-07 09:35:23.995  4191  4191 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-07 09:35:24.005  4191  4191 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48688e
,09-07 09:35:24.007  4191  4191 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 09:35:24.008  4191  4191 D BtGatt.GattService: Received start request. Starting profile...
,09-07 09:35:24.009  4191  4191 D BtGatt.GattService: start()
,09-07 09:35:24.009  4191  4191 I bt_bluedroid: get_profile_interface gatt
,09-07 09:35:24.012  4191  4191 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48688e
09-07 09:35:24.012  4191  4191 D BtGatt.AdvertiseManager: advertise manager created
,09-07 09:35:24.022  4191  4191 V BluetoothAdapterState: isTurningOff()=false
,09-07 09:35:24.022  4191  4191 V BluetoothAdapterState: isTurningOn()=false
09-07 09:35:24.022  4191  4191 V BluetoothAdapterState: isBleTurningOn()=true
09-07 09:35:24.022  4191  4191 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 09:35:24.023  4191  4203 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-07 09:35:24.024  4191  4203 I bt_bluedroid: enable,
09-07 09:35:24.024  4191  4204 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-07 09:35:24.025  4191  4204 I bt_hci  : start_up
,09-07 09:35:24.045  4191  4204 I bt_vendor: alloc value 0xb3a3f189
,09-07 09:35:24.046  4191  4204 I bt_vendor: init
,09-07 09:35:24.046  4191  4204 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-07 09:35:24.046  4191  4204 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-07 09:35:24.154  4191  4204 D bt_hci  : start_up starting async portion
,09-07 09:35:24.155  4191  4211 I bt_hci  : event_finish_startup
,09-07 09:35:24.155  4191  4211 I bt_hci_h4: hal_open
09-07 09:35:24.155  4191  4211 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-07 09:35:24.165  4191  4211 I bt_userial_vendor: device fd = 51 open
,09-07 09:35:24.197  4191  4211 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 09:35:24.229  4191  4211 D bt_hwcfg: Chipset BCM4354A2
,09-07 09:35:24.230  4191  4211 D bt_hwcfg: Target name = [BCM4354A2]
09-07 09:35:24.231  4191  4211 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-07 09:35:24.887  4191  4211 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-07 09:35:24.888  4191  4211 D bt_hwcfg: Settlement delay -- 100 ms
09-07 09:35:24.888  4191  4211 I bt_hwcfg: Setting fw settlement delay to 100 
,09-07 09:35:25.005  4191  4211 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 09:35:25.006  4191  4211 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-07 09:35:25.036  4191  4211 I bt_hwcfg: vendor lib fwcfg completed
,09-07 09:35:25.036  4191  4211 I bt_vendor: firmware callback
09-07 09:35:25.037  4191  4211 I bt_hci  : firmware_config_callback
,09-07 09:35:25.048  4191  4213 I bt_btu  : btu_task pending for preload complete event
,09-07 09:35:25.048  4191  4213 I bt_btu_task: Bluetooth chip preload is complete
,09-07 09:35:25.048  4191  4213 I bt_btu  : btu_task received preload complete event
,09-07 09:35:25.058  4191  4213 I         : BTE_InitTraceLevels -- TRC_HCI
,09-07 09:35:25.058  4191  4213 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 09:35:25.058  4191  4213 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-07 09:35:25.059  4191  4213 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-07 09:35:25.059  4191  4213 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 09:35:25.059  4191  4213 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 09:35:25.059  4191  4213 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 09:35:25.059  4191  4213 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 09:35:25.060  4191  4213 I         : BTE_InitTraceLevels -- TRC_GAP
,09-07 09:35:25.060  4191  4213 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 09:35:25.060  4191  4213 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 09:35:25.060  4191  4213 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 09:35:25.060  4191  4213 I         : BTE_InitTraceLevels -- TRC_SMP
,09-07 09:35:25.060  4191  4213 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 09:35:25.061  4191  4213 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 09:35:25.197  4191  4213 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39bcd9d
,09-07 09:35:25.197  4191  4213 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39bcd9d 
,09-07 09:35:25.206  4191  4207 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-07 09:35:25.208  4191  4207 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 09:35:25.209  4191  4207 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 09:35:25.212  4191  4207 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 09:35:25.224  4191  4207 D BluetoothAdapterProperties: Scan Mode:20
,09-07 09:35:25.224  4191  4207 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 09:35:25.225  4191  4207 D bt_hci  : do_postload posting postload work item
,09-07 09:35:25.225  4191  4211 I bt_hci  : event_postload
,09-07 09:35:25.226  4191  4211 I bt_vendor: sco_config_cb
,09-07 09:35:25.226  4191  4211 I bt_hci  : sco_config_callback postload finished.
,09-07 09:35:25.228  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:25.230  4191  4207 D bt_bte_conf: Device ID record 1 : primary
,09-07 09:35:25.230  4191  4207 D bt_bte_conf:   vendorId            = 000f
09-07 09:35:25.230  4191  4207 D bt_bte_conf:   vendorIdSource      = 0001
09-07 09:35:25.231  4191  4207 D bt_bte_conf:   product             = 1200
09-07 09:35:25.231  4191  4207 D bt_bte_conf:   version             = 1436
09-07 09:35:25.231  4191  4207 D bt_bte_conf:   clientExecutableURL = 
09-07 09:35:25.231  4191  4207 D bt_bte_conf:   serviceDescription  = 
09-07 09:35:25.232  4191  4207 D bt_bte_conf:   documentationURL    = 
09-07 09:35:25.232  4191  4207 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-07 09:35:25.232  4191  4204 D bt_stack_manager: event_start_up_stack finished
09-07 09:35:25.236  4191  4203 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-07 09:35:25.236  4191  4203 D BluetoothAdapterProperties: Setting state to 15
09-07 09:35:25.237  4191  4211 I bt_vendor: low_power_mode_cb
09-07 09:35:25.237  4191  4203 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-07 09:35:25.239  4191  4203 I BluetoothAdapterState: Entering BleOnState
,09-07 09:35:25.245  4191  4203 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-07 09:35:25.245  4191  4203 D BluetoothAdapterProperties: Setting state to 11
,09-07 09:35:25.246  4191  4203 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-07 09:35:25.256  4191  4191 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48688e
,09-07 09:35:25.258  4191  4191 D HeadsetService: Received start request. Starting profile...
,09-07 09:35:25.266  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:35:25.268  4191  4191 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-07 09:35:25.269  4191  4191 D HeadsetStateMachine: make
,09-07 09:35:25.276  4191  4203 I BluetoothAdapterState: Entering PendingCommandState
,09-07 09:35:25.279  4191  4191 D HeadsetStateMachine: max_hf_connections = 1
,09-07 09:35:25.279  4191  4191 I bt_bluedroid: get_profile_interface handsfree
,09-07 09:35:25.279  4191  4207 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-07 09:35:25.280  4191  4207 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-07 09:35:25.284  4191  4191 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48688e
,09-07 09:35:25.285  4191  4191 D A2dpService: Received start request. Starting profile...
,09-07 09:35:25.286  4191  4191 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-07 09:35:25.286  4191  4191 I bt_bluedroid: get_profile_interface avrcp
,09-07 09:35:25.295  4191  4191 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-07 09:35:25.295  4191  4191 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 09:35:25.295  4191  4191 D A2dpStateMachine: make
,09-07 09:35:25.298  4191  4191 I bt_bluedroid: get_profile_interface a2dp
,09-07 09:35:25.298  4191  4207 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048,
09-07 09:35:25.300  4191  4221 D A2dpStateMachine: Enter Disconnected: -2
,09-07 09:35:25.301  4191  4191 I BluetoothHidServiceJni: classInitNative: succeeds
,09-07 09:35:25.302  4191  4191 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48688e
09-07 09:35:25.302  4191  4191 D HidService: Received start request. Starting profile...
,09-07 09:35:25.303  4191  4191 I bt_bluedroid: get_profile_interface hidhost
09-07 09:35:25.303  4191  4191 D HidService: setHidService(): set to: null
,09-07 09:35:25.303  4191  4207 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb399e3e5
09-07 09:35:25.303  4191  4207 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-07 09:35:25.304  4191  4191 I BluetoothHealthServiceJni: classInitNative: succeeds
09-07 09:35:25.304  4191  4191 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48688e
09-07 09:35:25.305  4191  4191 D HealthService: Received start request. Starting profile...,
09-07 09:35:25.306  4191  4191 I bt_bluedroid: get_profile_interface health
,09-07 09:35:25.307  4191  4191 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-07 09:35:25.308  4191  4191 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48688e
,09-07 09:35:25.308  4191  4191 D PanService: Received start request. Starting profile...
09-07 09:35:25.309  4191  4191 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-07 09:35:25.309  4191  4191 I bt_bluedroid: get_profile_interface pan
09-07 09:35:25.309  4191  4207 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-07 09:35:25.320  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 09:35:25.321  4191  4191 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48688e
,09-07 09:35:25.323  4191  4191 D BluetoothMapService: Received start request. Starting profile...
,09-07 09:35:25.323  4191  4191 D BluetoothMapService: start()
,09-07 09:35:25.328  4191  4191 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-07 09:35:25.330  4191  4191 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-07 09:35:25.330  4191  4191 D BluetoothMapAppObserver: createReceiver()
,09-07 09:35:25.332  4191  4191 D BluetoothMapAppObserver: initObservers()
,09-07 09:35:25.333  4191  4191 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-07 09:35:25.344  4191  4191 V BluetoothAdapterState: isTurningOff()=false
,09-07 09:35:25.344  4191  4191 V BluetoothAdapterState: isTurningOn()=true
09-07 09:35:25.344  4191  4191 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:35:25.344  4191  4219 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 09:35:25.344  4191  4191 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 09:35:25.346  4191  4191 V BluetoothAdapterState: isTurningOff()=false
,09-07 09:35:25.346  4191  4191 V BluetoothAdapterState: isTurningOn()=true
09-07 09:35:25.346  4191  4191 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:35:25.346  4191  4191 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:35:25.347  4191  4191 V BluetoothAdapterState: isTurningOff()=false
09-07 09:35:25.347  4191  4191 V BluetoothAdapterState: isTurningOn()=true
,09-07 09:35:25.347  4191  4191 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:35:25.347  4191  4191 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:35:25.347  4191  4191 V BluetoothAdapterState: isTurningOff()=false
09-07 09:35:25.347  4191  4191 V BluetoothAdapterState: isTurningOn()=true
09-07 09:35:25.347  4191  4191 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 09:35:25.347  4191  4191 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:35:25.347  4191  4191 V BluetoothAdapterState: isTurningOff()=false
09-07 09:35:25.348  4191  4191 V BluetoothAdapterState: isTurningOn()=true
09-07 09:35:25.348  4191  4191 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:35:25.348  4191  4191 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:35:25.348  4191  4191 V BluetoothAdapterState: isTurningOff()=false
09-07 09:35:25.348  4191  4191 V BluetoothAdapterState: isTurningOn()=true
09-07 09:35:25.349  4191  4191 V BluetoothAdapterState: isBleTurningOn()=false
09-07 09:35:25.349  4191  4191 V BluetoothAdapterState: isBleTurningOff()=false
09-07 09:35:25.349  4191  4203 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-07 09:35:25.349  4191  4203 D BluetoothAdapterProperties: ScanMode =  20
09-07 09:35:25.349  4191  4203 D BluetoothAdapterProperties: State =  11
09-07 09:35:25.350  4191  4203 D BluetoothAdapterProperties: Setting state to 12
09-07 09:35:25.350  4191  4203 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-07 09:35:25.350  4191  4203 I BluetoothAdapterState: Entering OnState
09-07 09:35:25.350   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 09:35:25.351   876   893 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 09:35:25.353  1966  1977 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 09:35:25.353  4191  4207 D BluetoothAdapterProperties: Scan Mode:21
09-07 09:35:25.353  4191  4207 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 09:35:25.353   876   876 D BluetoothA2dp: Proxy object connected
,09-07 09:35:25.354  1391  1402 D BluetoothPan: onBluetoothStateChange on: true
,09-07 09:35:25.356   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 09:35:25.356  1391  2093 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 09:35:25.358  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:35:25.358  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:25.358  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:35:25.358  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 09:35:25.358  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:35:25.358  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:35:25.358  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:35:25.358  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 09:35:25.360  1391  1391 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 09:35:25.360  1391  1391 D PanProfile: Bluetooth service connected
09-07 09:35:25.361  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 09:35:25.362  1391  1391 D BluetoothA2dp: Proxy object connected
09-07 09:35:25.362  3912  3922 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 09:35:25.363  4191  4191 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-07 09:35:25.364  4191  4191 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-07 09:35:25.365  4191  4191 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 09:35:25.365   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 09:35:25.366  1391  1402 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 09:35:25.368  4191  4191 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 09:35:25.369  3912  3924 D BluetoothPan: onBluetoothStateChange on: true
,09-07 09:35:25.369  4191  4191 D ObexServerSockets: Succeed to create listening sockets 
09-07 09:35:25.369  4191  4191 D ObexServerSockets0: startAccept()
09-07 09:35:25.369  4191  4191 D ObexServerSockets0: prepareForNewConnect()
,09-07 09:35:25.371  3912  3922 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-07 09:35:25.371  4191  4191 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-07 09:35:25.372  4191  4191 D BluetoothSdpJni: SDP Create record success - handle: 0
09-07 09:35:25.373  1391  1391 D BluetoothInputDevice: Proxy object connected
09-07 09:35:25.374  1391  1391 D HidProfile: Bluetooth service connected
,09-07 09:35:25.372  3912  3912 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 09:35:25.375  3912  3912 D PanProfile: Bluetooth service connected
09-07 09:35:25.375  4191  4229 D ObexServerSockets0: Accepting socket connection...
,09-07 09:35:25.376  4191  4230 D ObexServerSockets0: Accepting socket connection...
09-07 09:35:25.375  3912  3924 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 09:35:25.379  3912  3922 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 09:35:25.382  1391  1404 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 09:35:25.384  3912  3912 D BluetoothInputDevice: Proxy object connected
,09-07 09:35:25.384  1391  1402 D BluetoothMap: onBluetoothStateChange: up=true
09-07 09:35:25.384  3912  3912 D HidProfile: Bluetooth service connected
,09-07 09:35:25.388  1391  2093 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 09:35:25.390  1391  1391 D BluetoothMap: Proxy object connected
,09-07 09:35:25.390  3912  3924 D BluetoothMap: onBluetoothStateChange: up=true
09-07 09:35:25.390  1391  1391 D MapProfile: Bluetooth service connected
09-07 09:35:25.390  1391  1391 D BluetoothMap: getConnectedDevices()
,09-07 09:35:25.394   876   876 I Telecom : BluetoothPhoneService: queryPhoneState
,09-07 09:35:25.394  3912  3912 D BluetoothA2dp: Proxy object connected
09-07 09:35:25.395  4191  4191 D BluetoothMapService: onReceive
09-07 09:35:25.395  4191  4191 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-07 09:35:25.396  4191  4191 D BluetoothMapService: STATE_ON
,09-07 09:35:25.398  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:35:25.399  3912  3912 D BluetoothMap: Proxy object connected
09-07 09:35:25.399  3912  3912 D MapProfile: Bluetooth service connected
09-07 09:35:25.399  3912  3912 D BluetoothMap: getConnectedDevices()
,09-07 09:35:25.409  3912  3912 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 09:35:25.416  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 09:35:25.420  3912  3912 D DockEventReceiver: finishStartingService: stopping service
,09-07 09:35:25.429  4191  4191 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-07 09:35:25.429  4191  4191 D ObexServerSockets0: prepareForNewConnect()
09-07 09:35:25.430  1391  1391 D BluetoothPbap: Proxy object connected
09-07 09:35:25.430  1391  1391 D PbapServerProfile: Bluetooth service connected
,09-07 09:35:25.431  3912  3912 D BluetoothPbap: Proxy object connected
09-07 09:35:25.431  3912  3912 D PbapServerProfile: Bluetooth service connected
,09-07 09:35:25.440  4191  4235 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 09:35:25.456   876   876 D BluetoothHeadset: Proxy object connected
,09-07 09:35:25.456  1391  1402 D BluetoothHeadset: Proxy object connected
09-07 09:35:25.456  1391  1391 D HeadsetProfile: Bluetooth service connected
,09-07 09:35:25.457   876   893 D BluetoothHeadset: Proxy object connected
,09-07 09:35:25.458  3912  4228 D BluetoothHeadset: Proxy object connected
09-07 09:35:25.458   876   876 D BluetoothHeadset: Proxy object connected
09-07 09:35:25.458  1966  2283 D BluetoothHeadset: Proxy object connected
,09-07 09:35:25.459   876   876 D BluetoothHeadset: Proxy object connected
09-07 09:35:25.460  4191  4239 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 09:35:25.463  4191  4239 I BtOppRfcommListener: Accept thread started.
,09-07 09:35:25.464  3912  3912 D HeadsetProfile: Bluetooth service connected
,09-07 09:35:25.465  3912  3922 D BluetoothHeadset: Proxy object connected
,09-07 09:35:25.466   876   893 D BluetoothHeadset: Proxy object connected
,09-07 09:35:25.474  3912  3912 D HeadsetProfile: Bluetooth service connected
,09-07 09:35:25.484  1391  1404 D BluetoothHeadset: Proxy object connected
,09-07 09:35:25.484  1391  1391 D HeadsetProfile: Bluetooth service connected
,09-07 09:35:25.777  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:35:25.777  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:25.777  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:35:25.777  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 09:35:25.777  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:35:25.777  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:35:25.777  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:35:25.777  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 09:35:25.783  3820  3869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 09:35:25.789  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 09:35:25.789  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f83dffe added. We now have 8 listener(s)
09-07 09:35:25.789  3820  3869 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 09:35:25.799   876   886 D WifiService: setWifiEnabled: false pid=3820, uid=10000
,09-07 09:35:25.799   876   886 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 09:35:25.812  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:35:25.813   876  1979 D WifiService: setWifiEnabled: true pid=3820, uid=10000
09-07 09:35:25.813   876  1979 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 09:35:25.830   876  1319 D WifiConfigStore: Loading config and enabling all networks 
,09-07 09:35:25.851  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:35:25.851  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:25.851  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:35:25.851  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:35:25.851  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:35:25.851  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:35:25.851  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:35:25.851  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 09:35:25.855  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 09:35:25.858   876  1319 D WifiConfigStore: loaded 0 passpoint configs
,09-07 09:35:25.859   876  1319 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-07 09:35:25.860   876  1319 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-07 09:35:25.861   876  1319 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-07 09:35:25.861   876  1319 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-07 09:35:25.861   876  1319 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-07 09:35:25.861   876  1319 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-07 09:35:25.877   374   874 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-07 09:35:25.878   876  1319 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 09:35:25.879   374   874 D CommandListener: Setting iface cfg
09-07 09:35:25.879   876  1318 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-07 09:35:25.879   876  1318 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-07 09:35:25.935   876  1319 E native  : do suspend true
,09-07 09:35:25.950   876  1318 D WifiNative-HAL: p2pGetDeviceAddress
,09-07 09:35:25.951   876  1318 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-07 09:35:25.963   876  1319 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 09:35:26.837  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:35:26.837  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:26.837  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:35:26.837  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:35:26.837  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:35:26.837  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 09:35:26.837  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 09:35:26.837  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 09:35:26.845  3820  3869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 09:35:26.861  3820  4245 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-07 09:35:26.862  3820  4245 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-07 09:35:27.274   876  1319 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-07 09:35:27.418   876  1319 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=1.20 rxSuccessRate=2.00 delta 1000 -> 1000
,09-07 09:35:27.420   876  1319 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-07 09:35:27.420   876  1319 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 09:35:27.439   876  1319 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-07 09:35:27.511   876  1319 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-07 09:35:27.515  1471  1471 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 09:35:27.945  1471  1471 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 09:35:27.998  1471  1471 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 09:35:27.998  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
09-07 09:35:28.003   876  1319 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 09:35:28.018   876  1319 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-07 09:35:28.018   876  1319 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 09:35:28.018   876  1323 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-07 09:35:28.042   876  1319 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 09:35:28.061   374   874 D CommandListener: Setting iface cfg
,09-07 09:35:28.062   876  1319 D WifiStateMachine: Start Dhcp Watchdog 3
,09-07 09:35:28.068   876  1319 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-07 09:35:28.114   876  4249 D DhcpClient: Receive thread started
,09-07 09:35:28.200   876  1319 E native  : do suspend false
,09-07 09:35:28.222   876  1872 D DhcpClient: Broadcasting DHCPDISCOVER
,09-07 09:35:28.251   876  4249 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172785, domain null
,09-07 09:35:28.252   876  1872 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172785 seconds
,09-07 09:35:28.255   876  1872 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-07 09:35:28.273   876  4249 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-07 09:35:28.274   876  1872 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-07 09:35:28.279   374   874 D CommandListener: Setting iface cfg
,09-07 09:35:28.289   876  1319 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-07 09:35:28.290   876  1872 D DhcpClient: Scheduling renewal in 86399s
09-07 09:35:28.292   876  1319 E native  : do suspend true
,09-07 09:35:28.312   876  1319 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-07 09:35:28.316   876  1319 D WifiConfigStore: No blacklist allowed without epno enabled
,09-07 09:35:28.317   876  1323 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-07 09:35:28.318   876  1323 D ConnectivityService: Adding iface wlan0 to network 102
,09-07 09:35:28.328   876  1319 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 09:35:28.365   876  1323 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-07 09:35:28.365   876  1323 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-07 09:35:28.366   876  1323 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-07 09:35:28.368   876  1323 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-07 09:35:28.369   876  1323 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-07 09:35:28.380   876  1323 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-07 09:35:28.386   876  1323 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-07 09:35:28.386   876  1323 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-07 09:35:28.386   876  1323 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-07 09:35:28.386   876  1323 D ConnectivityService:    accepting network in place of null
09-07 09:35:28.387   876  1319 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-07 09:35:28.387   876  1319 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 09:35:28.388   876  1323 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 09:35:28.410   876  4248 D NetlinkSocketObserver: NeighborEvent{elapsedMs=175816, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 09:35:28.445   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 09:35:28.486   374   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 09:35:28.488   876  4247 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-07 09:35:28.494   876  1323 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-07 09:35:28.495   876  1323 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 09:35:28.503   876  1323 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-07 09:35:28.503   876   893 D Tethering: MasterInitialState.processMessage what=3
,09-07 09:35:28.517  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 09:35:28.517  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:28.517  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:35:28.517  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:35:28.517  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:35:28.517  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:35:28.517  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:35:28.517  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:35:28.521  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 09:35:28.536  1750  1750 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 09:35:28.548  1750  1750 D SystemUpdateService: onCreate
,09-07 09:35:28.553  1750  1750 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 09:35:28.558   876  4247 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 07:35:28 GMT], X-Android-Received-Millis=[1473233728557], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473233728531]}
,09-07 09:35:28.560   876  1323 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-07 09:35:28.560   876  1323 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-07 09:35:28.560   876  1323 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-07 09:35:28.561   876  1323 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-07 09:35:28.568  1750  4258 I SystemUpdateService: active receiver: enabled
,09-07 09:35:28.574  1750  4258 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 09:35:28.580  1750  4258 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-07 09:35:28.580  1750  4258 I SystemUpdateService: now status is 0 (complete)
,09-07 09:35:28.583  1750  4258 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-07 09:35:28.584  1750  4258 I SystemUpdateService: file has been verified
,09-07 09:35:28.589  1750  4258 I SystemUpdateService: OTA package size = 12249756
,09-07 09:35:28.593  3760  4262 I BooksSync: Starting books sync for 61035162, extras: ade
,09-07 09:35:28.600  1750  4258 I SystemUpdateService: showing system update notification
,09-07 09:35:28.606  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:35:28.635  1750  1750 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-07 09:35:28.644  1750  2467 I iu.UploadsManager: num queued entries: 0
,09-07 09:35:28.655  1750  1750 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 09:35:28.657  1750  1750 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 09:35:28.659  3967  3967 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 09:35:28.666  1750  4264 I MDM     : [184] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-07 09:35:28.666  1750  4264 W BaseAppContext: Using Auth Proxy for data requests.
,09-07 09:35:28.669  3967  3967 D SprintDMHelper: simOperator: 
,09-07 09:35:28.669  3967  3967 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 09:35:28.676  1750  4264 V GoogleAuthProtoRequest: [184] a.<init>: mAccountName set to: thalitester@gmail.com
,09-07 09:35:28.682  1750  2467 I iu.UploadsManager: num updated entries: 0
,09-07 09:35:28.686  1750  2467 I iu.SyncManager: NEXT; no task,
,09-07 09:35:28.740  3760  4268 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-07 09:35:28.760  3750  4260 V KeepSync: Connecting to GoogleApiClient
09-07 09:35:28.761   876  1979 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-07 09:35:28.768  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:35:28.772  1750  1750 D SystemUpdateService: onDestroy
,09-07 09:35:28.773  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:35:28.834  1524  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 09:35:28.834  1524  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-07 09:35:28.834  1524  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 09:35:28.834  1524  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:35:28.846  3106  4267 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-07 09:35:28.847  1524  4271 I VacuumService: Vacuum at: now=1473233728847 tag=VacuumService
,09-07 09:35:28.900  1524  2441 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-07 09:35:28.900  1524  2441 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-07 09:35:28.900  1524  2441 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 09:35:28.900  1524  2441 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:35:28.901  1524  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-07 09:35:28.902  1524  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-07 09:35:28.902  1524  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 09:35:28.902  1524  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:35:28.938  3760  4268 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-07 09:35:28.939  3760  4262 E BooksSync: Soft error
09-07 09:35:28.939  3760  4262 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 09:35:28.939  3760  4262 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-07 09:35:28.939  3760  4262 E BooksSync: Sync error
09-07 09:35:28.939  3760  4262 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-07 09:35:28.939  3760  4262 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-07 09:35:28.939  3760  4262 I BooksSync: Finished books sync
09-07 09:35:28.941  1750  4274 V BaseAuthAsyncOperation: access token request failed
,09-07 09:35:28.942  3750  4260 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-07 09:35:28.953   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 163390, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 09:35:29.007  1524  2052 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-07 09:35:29.008  1524  2052 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-07 09:35:29.008  1524  2052 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 09:35:29.008  1524  2052 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:35:29.057  1750  4264 E MDM     : [184] SitrepService.a: Error sending sitrep.
,09-07 09:35:29.076  1524  4273 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-07 09:35:29.078  1524  4273 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-07 09:35:29.126  1524  4273 W Uploader:  no longer exists, so no auth token.
,09-07 09:35:29.171  1524  2302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-07 09:35:29.171  1524  2302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-07 09:35:29.171  1524  2302 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 09:35:29.171  1524  2302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:35:29.185  3750  4260 E KeepSync: IOException
09-07 09:35:29.185  3750  4260 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-07 09:35:29.185  3750  4260 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-07 09:35:29.185  3750  4260 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-07 09:35:29.185  3750  4260 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-07 09:35:29.185  3750  4260 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-07 09:35:29.185  3750  4260 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-07 09:35:29.185  3750  4260 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-07 09:35:29.185  3750  4260 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-07 09:35:29.185  3750  4260 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-07 09:35:29.185  3750  4260 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-07 09:35:29.185  3750  4260 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-07 09:35:29.185  3750  4260 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-07 09:35:29.185  3750  4260 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-07 09:35:29.185  3750  4260 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-07 09:35:29.185  3750  4260 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 09:35:29.185  3750  4260 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 09:35:29.185  3750  4260 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-07 09:35:29.185  3750  4260 E KeepSync: 	... 10 more
,09-07 09:35:29.185  3750  4260 W KeepSync: Sync result 2
,09-07 09:35:29.193   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 162820, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 09:35:29.875  3820  4245 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-07 09:35:29.877  3820  4245 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-07 09:35:29.877  3820  4284 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-07 09:35:29.877  3820  4245 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 09:35:29.878  3820  4284 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-07 09:35:29.878  3820  4284 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 09:35:29.878  3820  4245 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-07 09:35:29.879  3820  4284 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 09:35:29.882  3820  4245 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-07 09:35:29.882  3820  4284 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-07 09:35:29.886  3820  4287 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 486, name: OutgoingSocketThread/Sender)
09-07 09:35:29.886  3820  4288 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 487, name: IncomingSocketThread/Sender)
,09-07 09:35:29.886  3820  4289 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 488, name: OutgoingSocketThread/Receiver)
,09-07 09:35:29.888  3820  4290 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 489, name: IncomingSocketThread/Receiver)
09-07 09:35:29.888  3820  4289 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 488, thread name: OutgoingSocketThread/Receiver)
09-07 09:35:29.888  3820  4289 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-07 09:35:29.888  3820  4289 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 488, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-07 09:35:29.889  3820  4290 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 489, thread name: IncomingSocketThread/Receiver)
09-07 09:35:29.889  3820  4290 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-07 09:35:29.889  3820  4290 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 489, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-07 09:35:30.501  1524  4273 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-07 09:35:30.501  1524  4273 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-07 09:35:30.501  1524  4273 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 09:35:30.501  1524  4273 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:35:30.517  1524  4273 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-07 09:35:30.517  1524  4273 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 09:35:30.517  1524  4273 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 09:35:30.517  1524  4273 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 09:35:30.517  1524  4273 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-07 09:35:30.517  1524  4273 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-07 09:35:30.517  1524  4273 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-07 09:35:30.517  1524  4273 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-07 09:35:30.517  1524  4273 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-07 09:35:30.517  1524  4273 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-07 09:35:30.517  1524  4273 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-07 09:35:30.517  1524  4273 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-07 09:35:30.517  1524  4273 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-07 09:35:31.017  1524  4273 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-07 09:35:31.018  1524  4273 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-07 09:35:31.018  1524  4273 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 09:35:31.018  1524  4273 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:35:31.037  1524  4273 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-07 09:35:31.037  1524  4273 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 09:35:31.037  1524  4273 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 09:35:31.037  1524  4273 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 09:35:31.037  1524  4273 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-07 09:35:31.037  1524  4273 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-07 09:35:31.037  1524  4273 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-07 09:35:31.037  1524  4273 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-07 09:35:31.037  1524  4273 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-07 09:35:31.037  1524  4273 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-07 09:35:31.037  1524  4273 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-07 09:35:31.037  1524  4273 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-07 09:35:31.037  1524  4273 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-07 09:35:31.196  1524  4273 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-07 09:35:31.196  1524  4273 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-07 09:35:31.196  1524  4273 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 09:35:31.197  1524  4273 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:35:31.213  1524  4273 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-07 09:35:31.213  1524  4273 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 09:35:31.213  1524  4273 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 09:35:31.213  1524  4273 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 09:35:31.213  1524  4273 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-07 09:35:31.213  1524  4273 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-07 09:35:31.213  1524  4273 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-07 09:35:31.213  1524  4273 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-07 09:35:31.213  1524  4273 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-07 09:35:31.213  1524  4273 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-07 09:35:31.213  1524  4273 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-07 09:35:31.213  1524  4273 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-07 09:35:31.213  1524  4273 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-07 09:35:32.882  3820  3869 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-07 09:35:32.886  3820  3869 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-07 09:35:32.894  3820  3869 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e667f9a Bundle[{}]
,09-07 09:35:32.896  3820  3869 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-07 09:35:32.896  3820  3869 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-07 09:35:32.899  3820  3869 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-07 09:35:32.902  3820  3869 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-07 09:35:32.905  3820  3869 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-07 09:35:32.907  3820  3869 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-07 09:35:32.919  3820  4296 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-07 09:35:32.919  3820  4296 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-07 09:35:32.932  3820  4296 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-07 09:35:32.933  3820  4296 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-07 09:35:32.933  3820  4296 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 09:35:32.934  3820  4296 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 09:35:32.935  3820  4298 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-07 09:35:32.935  3820  4298 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-07 09:35:32.936  3820  4301 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 500, name: OutgoingSocketThread/Sender)
,09-07 09:35:32.937  3820  4296 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-07 09:35:32.939  3820  4302 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 501, name: OutgoingSocketThread/Receiver)
,09-07 09:35:32.939  3820  4298 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 09:35:32.940  3820  4302 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 501, thread name: OutgoingSocketThread/Receiver)
,09-07 09:35:32.940  3820  4302 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-07 09:35:32.940  3820  4302 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 501, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207,
,09-07 09:35:32.943  3820  4298 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 09:35:32.944  3820  4298 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-07 09:35:32.946  3820  4304 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 503, name: IncomingSocketThread/Receiver)
,09-07 09:35:32.947  3820  4304 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 503, thread name: IncomingSocketThread/Receiver)
09-07 09:35:32.947  3820  4304 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-07 09:35:32.947  3820  4304 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 503, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-07 09:35:32.948  3820  4303 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 502, name: IncomingSocketThread/Sender)
,09-07 09:35:35.943  3820  3869 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 512)
,09-07 09:35:35.945  3820  3869 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-07 09:35:35.946  3820  3869 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 513)
,09-07 09:35:35.953  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 09:35:35.954  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d9f35f added. We now have 2 listener(s)
,09-07 09:35:35.959  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 09:35:35.959  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 09:35:35.959  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 09:35:35.960  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 09:35:35.960  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dc1ac added. We now have 9 listener(s)
,09-07 09:35:35.960  3820  3869 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 09:35:35.960  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 09:35:35.964  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:35:35.974  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:35:35.974  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:35.974  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 09:35:35.974  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:35:35.974  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:35:35.974  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:35:35.974  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:35:35.974  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 09:35:35.977  3820  3869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 09:35:35.978  3820  3869 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 09:35:35.983  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 09:35:35.983  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 09:35:35.983  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 09:35:35.984  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 09:35:35.984  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d9f35f removed from the list
,09-07 09:35:35.984  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 09:35:35.984  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dc1ac removed from the list,
,09-07 09:35:35.984  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:35:35.984  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 09:35:35.984  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:35:35.986  3820  3869 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-07 09:35:35.986  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-07 09:35:35.988  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 09:35:35.988  3820  3869 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-07 09:35:35.988  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 09:35:35.989  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:35:35.990  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 09:35:35.991  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:35.991  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 09:35:35.991  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 09:35:35.992  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 09:35:35.992  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 09:35:35.993  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 09:35:35.993  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:35:35.993  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 09:35:35.994  3820  4305 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 09:35:36.001  3820  3869 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 09:35:36.001  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 09:35:36.001  3820  4305 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-07 09:35:36.007  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 09:35:36.009  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-07 09:35:36.009  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 09:35:36.013  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-07 09:35:36.014  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 09:35:36.014  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 F8 CF C5 D9 E5 61
,09-07 09:35:36.015  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-07 09:35:36.015  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 09:35:36.016  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-07 09:35:36.017  3820  3869 D BluetoothAdapter: STATE_ON
,09-07 09:35:36.021  4191  4231 D BtGatt.GattService: registerClient() - UUID=c7ec6c86-13ef-4d91-813b-7ce74fe5a2cc
,09-07 09:35:36.023  4191  4207 D BtGatt.GattService: onClientRegistered() - UUID=c7ec6c86-13ef-4d91-813b-7ce74fe5a2cc, clientIf=5
,09-07 09:35:36.024  3820  3832 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-07 09:35:36.028  4191  4209 D BtGatt.AdvertiseManager: message : 0
,09-07 09:35:36.032  4191  4209 D BtGatt.AdvertiseManager: starting multi advertising
,09-07 09:35:36.059  4191  4207 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-07 09:35:36.079  4191  4207 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-07 09:35:36.082  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-07 09:35:36.083  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 09:35:36.092  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 09:35:36.097  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 09:35:36.098  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-07 09:35:36.098  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-07 09:35:36.098  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-07 09:35:36.099  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-07 09:35:36.099  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-07 09:35:36.108  3820  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 09:35:36.109  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 09:35:36.394   876  1323 D ConnectivityService: handlePromptUnvalidated 102
,09-07 09:35:36.609  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-07 09:35:36.610  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 09:35:36.610  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 09:35:42.102  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-07 09:35:42.102  3820  3869 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 09:35:42.103  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 09:35:42.103  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-07 09:35:42.103  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-07 09:35:42.105  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 09:35:42.106  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-07 09:35:42.106  3820  4305 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-07 09:35:42.106  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 09:35:42.106  3820  4305 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 09:35:42.107  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 09:35:42.106  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 09:35:42.107  3820  4305 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 09:35:42.107  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 09:35:42.107  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 09:35:42.107  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 09:35:42.110  3820  3869 D BluetoothAdapter: STATE_ON
09-07 09:35:42.110  3820  3869 D BluetoothLeScanner: could not find callback wrapper
09-07 09:35:42.111  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 09:35:42.111  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-07 09:35:42.114  4191  4209 D BtGatt.AdvertiseManager: message : 1
09-07 09:35:42.115  4191  4209 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-07 09:35:42.125  4191  4207 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0,
09-07 09:35:42.126  4191  4207 D BtGatt.GattService: Client app is not null!
,09-07 09:35:42.127  4191  4226 D BtGatt.GattService: unregisterClient() - clientIf=5,
,09-07 09:35:42.129  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 09:35:42.129  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-07 09:35:42.129  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-07 09:35:42.129  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-07 09:35:42.129  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-07 09:35:42.132  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 09:35:42.132  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 09:35:42.132  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 09:35:42.134  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:35:42.136  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 09:35:42.137  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-07 09:35:42.137  3820  3820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-07 09:35:42.137  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 09:35:42.138  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 09:35:42.138  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 09:35:42.640  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 09:35:43.116  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:35:43.142  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,09-07 09:35:43.149  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 09:35:43.223  1524  2441 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 09:35:43.223  1524  2441 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-07 09:35:43.224  1524  2441 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 09:35:43.224  1524  2441 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 09:35:43.233   876   885 I art     : Background partial concurrent mark sweep GC freed 62149(3MB) AllocSpace objects, 10(236KB) LOS objects, 33% free, 29MB/43MB, paused 1.762ms total 111.600ms
,09-07 09:35:43.262  3541  3541 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 09:35:43.262  3541  3541 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 09:35:43.262  3541  3541 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-07 09:35:45.141  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 09:35:45.142  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:45.142  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:35:45.142  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d9f35f not in the list
,09-07 09:35:45.143  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:35:45.143  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dc1ac not in the list
09-07 09:35:45.143  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 09:35:45.144  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:45.144  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:35:45.147  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 09:35:45.149  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 09:35:45.150  3820  3869 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-07 09:35:45.150  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 09:35:45.150  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:35:45.151  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 09:35:45.165  3820  3869 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-07 09:35:45.166  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 09:35:45.178  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 09:35:45.180  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-07 09:35:45.180  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 09:35:45.191  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-07 09:35:45.191  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-07 09:35:45.192  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-07 09:35:45.194  3820  3869 D BluetoothAdapter: STATE_ON
,09-07 09:35:45.198  4191  4227 D BtGatt.GattService: registerClient() - UUID=8f011b31-b8eb-4da6-a0ec-32d3fa235a9b
,09-07 09:35:45.199  4191  4207 D BtGatt.GattService: onClientRegistered() - UUID=8f011b31-b8eb-4da6-a0ec-32d3fa235a9b, clientIf=5
09-07 09:35:45.200  3820  3832 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-07 09:35:45.203  4191  4231 D BtGatt.GattService: start scan with filters
,09-07 09:35:45.214  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-07 09:35:45.214  4191  4210 D BtGatt.ScanManager: handling starting scan
09-07 09:35:45.215  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 09:35:45.215  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 09:35:45.215  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 09:35:45.219  4191  4210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@48688e
,09-07 09:35:45.225  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 09:35:45.226  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 09:35:45.226  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-07 09:35:45.228  4191  4207 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-07 09:35:45.228  4191  4207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 09:35:45.230  4191  4210 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-07 09:35:45.235  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 09:35:45.250  4191  4207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-07 09:35:45.250  4191  4207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 09:35:45.252  4191  4210 D BtGatt.ScanManager: Starting BLE batch scan
,09-07 09:35:45.252  4191  4210 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-07 09:35:45.290  4191  4207 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-07 09:35:45.290  4191  4207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,09-07 09:35:45.313  4191  4207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-07 09:35:45.314  4191  4207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 09:35:45.726  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-07 09:35:45.727  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 09:35:45.727  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 09:35:46.816  4191  4191 D BtGatt.ScanManager: awakened up at time 194222
,09-07 09:35:46.822  4191  4210 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-07 09:35:46.876  4191  4207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=9
,09-07 09:35:46.876  4191  4207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 09:35:46.877  4191  4207 D BtGatt.GattService: current time is 194283405278
,09-07 09:35:46.879  4191  4207 D BtGatt.GattService: Batch record : [1, 114, 78, -122, -79, 117, 1, -128, -65, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 52, -118, -96, 0, 87, 45, 110, 28, -13, -4, 1, -128, -66, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 55, -106, -85, 0, 116, -43, -111, -91, -20, -29, 1, -128, -83, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -89, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -88, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -82, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -91, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -85, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 87, 45, 110, 28, -13, -4, 1, -128, -66, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 55, -106, -85, 0]
,09-07 09:35:46.882  4191  4207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 52, -118, -96]
,09-07 09:35:46.884  4191  4207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 55, -106, -85]
,09-07 09:35:46.885  4191  4207 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-07 09:35:46.886  4191  4207 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-07 09:35:46.887  4191  4207 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-07 09:35:46.887  4191  4207 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-07 09:35:46.888  4191  4207 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-07 09:35:46.889  4191  4207 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-07 09:35:46.890  4191  4207 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 55, -106, -85]
,09-07 09:35:46.899  3820  3820 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:37:96:AB 5], added - the peer count is 1
,09-07 09:35:46.900  3820  3820 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 5], added - the peer count is 2
,09-07 09:35:46.903  3820  3820 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 7C:F9:0E:37:96:AB 5] updated - the peer count is 2
,09-07 09:35:46.903  3820  3820 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:37:96:AB 5], Bluetooth address: 7C:F9:0E:37:96:AB, device name: '', device address: ''
,09-07 09:35:46.905  3820  3820 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 5], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,09-07 09:35:48.245  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 09:35:48.245  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:48.245  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 09:35:48.246  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d9f35f not in the list
09-07 09:35:48.246  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 09:35:48.246  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 09:35:48.247  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 09:35:48.247  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 09:35:48.248  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 09:35:48.248  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 09:35:48.251  3820  3869 D BluetoothAdapter: STATE_ON
,09-07 09:35:48.253  4191  4231 D BtGatt.GattService: stopScan() - queue size =1
09-07 09:35:48.255  4191  4201 D BtGatt.GattService: unregisterClient() - clientIf=5
09-07 09:35:48.257  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 09:35:48.257  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 09:35:48.258  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 09:35:48.258  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 09:35:48.259  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 09:35:48.262  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 09:35:48.264  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-07 09:35:48.264  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-07 09:35:48.267  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 09:35:48.267  4191  4191 D BtGatt.ScanManager: awakened up at time 195673
09-07 09:35:48.272  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:35:48.272  3820  3869 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,09-07 09:35:48.276  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 09:35:48.276  4191  4207 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-07 09:35:48.276  4191  4207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 09:35:48.276  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 09:35:48.277  4191  4210 D BtGatt.ScanManager: stopping BLe Batch
09-07 09:35:48.277  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dc1ac not in the list
,09-07 09:35:48.277  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 09:35:48.277  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:35:48.278  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:48.278  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:35:48.282  3820  3869 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,09-07 09:35:48.282  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
09-07 09:35:48.285  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-07 09:35:48.286  4191  4207 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-07 09:35:48.286  4191  4207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-07 09:35:48.286  3820  3869 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-07 09:35:48.287  4191  4210 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-07 09:35:48.287  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 09:35:48.287  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 09:35:48.291  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 09:35:48.292  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-07 09:35:48.292  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 09:35:48.293  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 09:35:48.293  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 09:35:48.294  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-07 09:35:48.294  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:35:48.294  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 09:35:48.296  4191  4207 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-07 09:35:48.296  4191  4207 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-07 09:35:48.303  3820  3869 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-07 09:35:48.304  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 09:35:48.304  3820  4309 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 09:35:48.306  3820  4309 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-07 09:35:48.313  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 09:35:48.314  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-07 09:35:48.314  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 09:35:48.318  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-07 09:35:48.318  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 09:35:48.318  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 F8 CF C5 D9 E5 61
09-07 09:35:48.319  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-07 09:35:48.319  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-07 09:35:48.319  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-07 09:35:48.321  3820  3869 D BluetoothAdapter: STATE_ON
,09-07 09:35:48.324  4191  4227 D BtGatt.GattService: registerClient() - UUID=c1aa1ca6-d50a-4273-8c57-c58e8af8f00a
,09-07 09:35:48.324  4191  4207 D BtGatt.GattService: onClientRegistered() - UUID=c1aa1ca6-d50a-4273-8c57-c58e8af8f00a, clientIf=5
09-07 09:35:48.325  3820  3831 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-07 09:35:48.325  4191  4209 D BtGatt.AdvertiseManager: message : 0
,09-07 09:35:48.327  4191  4209 D BtGatt.AdvertiseManager: starting multi advertising
,09-07 09:35:48.339  4191  4207 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-07 09:35:48.344  4191  4207 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-07 09:35:48.345  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-07 09:35:48.345  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 09:35:48.346  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 09:35:48.348  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-07 09:35:48.348  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-07 09:35:48.348  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-07 09:35:48.348  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-07 09:35:48.348  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-07 09:35:48.348  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-07 09:35:48.350  3820  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-07 09:35:48.351  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-07 09:35:48.852  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-07 09:35:48.852  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-07 09:35:48.852  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 09:35:54.351  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 09:35:54.352  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-07 09:35:54.352  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-07 09:35:54.352  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 09:35:54.353  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 09:35:54.353  3820  4309 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-07 09:35:54.354  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 09:35:54.354  3820  4309 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 09:35:54.354  3820  4309 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 09:35:54.354  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 09:35:54.354  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d9f35f not in the list
09-07 09:35:54.354  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:35:54.355  3820  3820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 09:35:54.355  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 09:35:54.355  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 09:35:54.355  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 09:35:54.356  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 09:35:54.358  3820  3869 D BluetoothAdapter: STATE_ON
09-07 09:35:54.359  3820  3869 D BluetoothLeScanner: could not find callback wrapper
09-07 09:35:54.359  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 09:35:54.359  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-07 09:35:54.362  4191  4209 D BtGatt.AdvertiseManager: message : 1
09-07 09:35:54.363  4191  4209 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-07 09:35:54.374  4191  4207 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-07 09:35:54.374  4191  4207 D BtGatt.GattService: Client app is not null!
,09-07 09:35:54.377  4191  4201 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-07 09:35:54.378  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-07 09:35:54.378  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-07 09:35:54.379  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-07 09:35:54.379  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-07 09:35:54.379  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-07 09:35:54.383  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 09:35:54.384  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-07 09:35:54.384  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 09:35:54.386  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:35:54.389  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 09:35:54.390  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 09:35:54.390  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 09:35:54.391  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dc1ac not in the list
09-07 09:35:54.391  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 09:35:54.392  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:54.392  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:35:54.395  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:35:54.395  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:54.395  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:35:54.396  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d9f35f not in the list
,09-07 09:35:54.396  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:35:54.396  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dc1ac not in the list
09-07 09:35:54.396  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:35:54.397  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:54.397  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:35:54.399  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-07 09:35:54.400  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 09:35:54.400  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-07 09:35:54.401  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 09:35:54.401  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-07 09:35:54.401  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-07 09:35:54.421  3820  4311 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 533, name: My test thread name)
,09-07 09:35:54.892  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 09:35:56.421  3820  3869 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 533
09-07 09:35:56.421  3820  3869 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 533, name: My test thread name)
,09-07 09:35:56.428  3820  4312 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 534, name: My test thread name)
,09-07 09:35:56.428  3820  4312 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 534, thread name: My test thread name)
09-07 09:35:56.429  3820  4312 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 534, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-07 09:35:56.435  3820  3869 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-07 09:35:56.445  3820  4313 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 538, name: My test thread name)
09-07 09:35:56.446  3820  4313 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 538, thread name: My test thread name): Test exception.
09-07 09:35:56.447  3820  4313 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 538, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-07 09:35:56.450  3820  3869 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 82
09-07 09:35:56.450  3820  3869 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 82
09-07 09:35:56.451  3820  3869 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,09-07 09:35:56.451  3820  3869 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-07 09:35:56.451  3820  3869 D com.test.thalitest.ThaliTestRunner: Total duration: 78481 ms
,09-07 09:35:56.459  3820  3869 I jxcore-log: Total number of executed tests:  82
09-07 09:35:56.459  3820  3869 I jxcore-log: 
,09-07 09:35:56.460  3820  3869 I jxcore-log: Number of passed tests:  82
09-07 09:35:56.460  3820  3869 I jxcore-log: 
09-07 09:35:56.461  3820  3869 I jxcore-log: Number of failed tests:  0
09-07 09:35:56.461  3820  3869 I jxcore-log: 
,09-07 09:35:56.465  3820  3869 I jxcore-log: Number of ignored tests:  0
09-07 09:35:56.465  3820  3869 I jxcore-log: 
,09-07 09:35:56.466  3820  3869 I jxcore-log: Total duration:  78481
09-07 09:35:56.466  3820  3869 I jxcore-log: 
,09-07 09:35:56.474  3820  3869 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-07 09:35:56.474  3820  3869 I jxcore-log: 
,09-07 09:35:56.474  3820  4311 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 533, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
09-07 09:35:56.477  3820  3869 I jxcore-log: My device name is: motorola-Nexus 6
09-07 09:35:56.477  3820  3869 I jxcore-log: 
09-07 09:35:56.483  3820  3869 I jxcore-log: WARN testUtils: myNameCallback not set!
09-07 09:35:56.483  3820  3869 I jxcore-log: 
09-07 09:35:56.486  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:35:56.486  3820  3869 I jxcore-log: 
09-07 09:35:56.487  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:35:56.487  3820  3869 I jxcore-log: 
09-07 09:35:56.489  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-07 09:35:56.489  3820  3869 I jxcore-log: 
09-07 09:35:56.491  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 09:35:56.491  3820  3869 I jxcore-log: 
09-07 09:35:56.494  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-07 09:35:56.494  3820  3869 I jxcore-log: 
09-07 09:35:56.496  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:35:56.496  3820  3869 I jxcore-log: 
09-07 09:35:56.497  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-07 09:35:56.497  3820  3869 I jxcore-log: 
09-07 09:35:56.499  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 09:35:56.499  3820  3869 I jxcore-log: 
,09-07 09:35:56.500  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:35:56.500  3820  3869 I jxcore-log: 
,09-07 09:35:56.502  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-07 09:35:56.502  3820  3869 I jxcore-log: 
,09-07 09:35:56.504  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 09:35:56.504  3820  3869 I jxcore-log: 
,09-07 09:35:56.506  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:35:56.506  3820  3869 I jxcore-log: 
,09-07 09:35:56.509  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:35:56.509  3820  3869 I jxcore-log: 
,09-07 09:35:56.511  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 09:35:56.511  3820  3869 I jxcore-log: 
,09-07 09:35:56.514  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 09:35:56.514  3820  3869 I jxcore-log: 
,09-07 09:35:56.516  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 09:35:56.516  3820  3869 I jxcore-log: 
,09-07 09:35:56.521  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 09:35:56.521  3820  3869 I jxcore-log: 
,09-07 09:35:56.525  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 09:35:56.525  3820  3869 I jxcore-log: 
,09-07 09:35:56.529  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 09:35:56.529  3820  3869 I jxcore-log: 
,09-07 09:35:56.531  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 09:35:56.531  3820  3869 I jxcore-log: 
,09-07 09:35:56.532  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:35:56.532  3820  3869 I jxcore-log: 
09-07 09:35:56.533  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:35:56.533  3820  3869 I jxcore-log: 
,09-07 09:35:56.534  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 09:35:56.534  3820  3869 I jxcore-log: 
09-07 09:35:56.535  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 09:35:56.535  3820  3869 I jxcore-log: 
,09-07 09:35:56.536  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 09:35:56.536  3820  3869 I jxcore-log: 
,09-07 09:35:56.537  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 09:35:56.537  3820  3869 I jxcore-log: 
,09-07 09:35:56.538  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 09:35:56.538  3820  3869 I jxcore-log: 
,09-07 09:35:56.539  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 09:35:56.539  3820  3869 I jxcore-log: 
,09-07 09:35:56.540  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 09:35:56.540  3820  3869 I jxcore-log: 
,09-07 09:35:56.541  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 09:35:56.541  3820  3869 I jxcore-log: 
,09-07 09:35:56.542  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 09:35:56.542  3820  3869 I jxcore-log: 
09-07 09:35:56.543  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 09:35:56.543  3820  3869 I jxcore-log: 
,09-07 09:35:56.544  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:35:56.544  3820  3869 I jxcore-log: 
,09-07 09:35:56.545  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:35:56.545  3820  3869 I jxcore-log: 
,09-07 09:35:56.546  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-07 09:35:56.546  3820  3869 I jxcore-log: 
,09-07 09:35:56.547  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 09:35:56.547  3820  3869 I jxcore-log: 
,09-07 09:35:56.548  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-07 09:35:56.548  3820  3869 I jxcore-log: 
,09-07 09:35:56.550  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-07 09:35:56.550  3820  3869 I jxcore-log: 
09-07 09:35:56.551  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-07 09:35:56.551  3820  3869 I jxcore-log: 
,09-07 09:35:56.553  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-07 09:35:56.553  3820  3869 I jxcore-log: 
09-07 09:35:56.554  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 09:35:56.554  3820  3869 I jxcore-log: 
,09-07 09:35:57.121  4314  4314 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-07 09:35:57.126  4314  4314 D AndroidRuntime: CheckJNI is OFF
,09-07 09:35:57.163  4314  4314 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-07 09:35:57.202  4314  4314 I Radio-JNI: register_android_hardware_Radio DONE
,09-07 09:35:57.220  4314  4314 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-07 09:35:57.232   876   889 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-07 09:35:57.233   876   889 I ActivityManager: Killing 3820:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-07 09:35:57.331   876   899 W PackageSettings: Skipping PackageSetting{b1224e3 com.example.hello/10273} due to missing metadata
,09-07 09:35:57.335   876   887 D GraphicsStats: Buffer count: 2
,09-07 09:35:57.335   876  1405 I WindowState: WIN DEATH: Window{3ae4bfd u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-07 09:35:57.336   876  1321 D WifiService: Client connection lost with reason: 4
,09-07 09:35:57.372   876   889 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-07 09:35:57.372   876   889 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-07 09:35:57.373   876   889 E ActivityManager: Failure starting process com.test.thalitest
09-07 09:35:57.373   876   889 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-07 09:35:57.373   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-07 09:35:57.373   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-07 09:35:57.373   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-07 09:35:57.373   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-07 09:35:57.373   876   889 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-07 09:35:57.373   876   889 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-07 09:35:57.373   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-07 09:35:57.373   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-07 09:35:57.373   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-07 09:35:57.373   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-07 09:35:57.373   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-07 09:35:57.373   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-07 09:35:57.373   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-07 09:35:57.373   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-07 09:35:57.373   876   889 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:35:57.373   876   889 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:35:57.373   876   889 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 09:35:57.373   876   889 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-07 09:35:57.373   876   889 I ActivityManager:   Force finishing activity ActivityRecord{afff53a u0 com.test.thalitest/.MainActivity t4}
09-07 09:35:57.374   876   899 I art     : Starting a blocking GC Explicit
,09-07 09:35:57.383   876  1707 W ActivityManager: Spurious death for ProcessRecord{e3018f9 0:com.test.thalitest/u0a0}, curProc for 3820: null
,09-07 09:35:57.416   876   899 I art     : Explicit concurrent mark sweep GC freed 17764(1169KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 692us total 41.665ms
,09-07 09:35:57.444   876   899 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-07 09:35:57.448  4314  4314 I art     : System.exit called, status: 0
09-07 09:35:57.448  4314  4314 I AndroidRuntime: VM exiting with result code 0.
,09-07 09:35:57.450   876   899 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-07 09:35:57.480   876   889 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-07 09:35:57.484  1894  1894 I Keyboard.Facilitator: resetDictionaries() : en_US
09-07 09:35:57.487  4191  4191 D BluetoothMapAppObserver: onReceive
09-07 09:35:57.487  4191  4191 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-07 09:35:57.488  1894  4325 I Keyboard.Facilitator.DecoderInitializer: run()
,09-07 09:35:57.491  1894  4325 I Decoder : createOrResetDecoder
,09-07 09:35:57.493  2123  2304 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-07 09:35:57.497  3638  3638 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-07 09:35:57.503   876  1311 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-07 09:35:57.522  1966  1966 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-07 09:35:57.557   876  1980 I ActivityManager: Start proc 4328:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-07 09:35:57.562  1524  1524 I ConfigService: onCreate
,09-07 09:35:57.586   876   876 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-07 09:35:57.602  1894  4325 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-07 09:35:57.625   876   886 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3820 uid 10000
,09-07 09:35:57.626  1894  1894 I Keyboard.Facilitator: onFinishInput()
,09-07 09:35:57.633  4328  4328 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-07 09:35:57.641  1981  2094 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-07 09:35:57.642   876   888 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-07 09:35:57.643  1894  4325 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-07 09:35:57.643   876   888 E PackageManager: Failed to write settings, restoring backup
09-07 09:35:57.643   876   888 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-07 09:35:57.643   876   888 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-07 09:35:57.643   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-07 09:35:57.643   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-07 09:35:57.643   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-07 09:35:57.643   876   888 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:35:57.643   876   888 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:35:57.643   876   888 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 09:35:57.646  1894  4325 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-07 09:35:57.646  1894  4325 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-07 09:35:57.648  1894  4325 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-07 09:35:57.648  1894  4325 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-07 09:35:57.649  1894  4325 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-07 09:35:57.649  1894  4325 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-07 09:35:57.652   876   889 E DropBoxManagerService: Can't write: system_server_wtf
09-07 09:35:57.652   876   889 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-07 09:35:57.652   876   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 09:35:57.652   876   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 09:35:57.652   876   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 09:35:57.652   876   889 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 09:35:57.652   876   889 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 09:35:57.652   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 09:35:57.652   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-07 09:35:57.652   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-07 09:35:57.652   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-07 09:35:57.652   876   889 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 09:35:57.652   876   889 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 09:35:57.652   876   889 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:35:57.652   876   889 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 09:35:57.652   876   889 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-07 09:35:57.652   876   889 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 09:35:57.652   876   889 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 09:35:57.652   876   889 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 09:35:57.652   876   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 09:35:57.652   876   889 E DropBoxManagerService: 	... 13 more
,09-07 09:35:57.650  1894  4325 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-07 09:35:57.653  1894  4325 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-07 09:35:57.653  1894  4325 I Keyboard.Facilitator.Delight2FileSweeper: run()
,09-07 09:35:57.653  1894  4325 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-07 09:35:57.653  1894  4325 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-07 09:35:57.653  1894  4325 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-07 09:35:57.653   876  1727 I ActivityManager: Start proc 4342:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
,09-07 09:35:57.654  1981  2094 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-07 09:35:57.654  1981  2094 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1981
09-07 09:35:57.654  1981  2094 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 09:35:57.654  1981  2094 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-07 09:35:57.654  1981  2094 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-07 09:35:57.654  1981  2094 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-07 09:35:57.654  1981  2094 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-07 09:35:57.654  1981  2094 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-07 09:35:57.654  1981  2094 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-07 09:35:57.654  1981  2094 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-07 09:35:57.654  1981  2094 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 09:35:57.654  1981  2094 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 09:35:57.654  1981  2094 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:35:57.654  1981  2094 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 09:35:57.656   876  1979 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 09:35:57.656   876  4347 E DropBoxManagerService: Can't write: system_app_crash
09-07 09:35:57.656   876  4347 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
09-07 09:35:57.656   876  4347 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 09:35:57.656   876  4347 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 09:35:57.656   876  4347 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 09:35:57.656   876  4347 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 09:35:57.656   876  4347 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 09:35:57.656   876  4347 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 09:35:57.656   876  4347 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 09:35:57.656   876  4347 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 09:35:57.656   876  4347 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 09:35:57.656   876  4347 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 09:35:57.656   876  4347 E DropBoxManagerService: 	... 5 more
,09-07 09:35:57.661  1981  2094 I Process : Sending signal. PID: 1981 SIG: 9
,09-07 09:35:57.708  4328  4328 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-07 09:35:57.715   876  1405 D GraphicsStats: Buffer count: 1
,09-07 09:35:57.715   876  1980 I WindowState: WIN DEATH: Window{1a2b943 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-07 09:35:57.732   876  1978 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1981) has died
,09-07 09:35:57.732   876  1978 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-07 09:35:57.734   876  1978 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-07 09:35:57.739  4328  4359 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-07 09:35:57.751   876   889 I ActivityManager: Start proc 4360:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-07 09:35:57.764   876  1709 I ActivityManager: Start proc 4372:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-07 09:35:57.784  4328  4356 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-07 09:35:57.784  4328  4356 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 09:35:57.784  4328  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 09:35:57.784  4328  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 09:35:57.784  4328  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 09:35:57.784  4328  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 09:35:57.784  4328  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 09:35:57.784  4328  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 09:35:57.784  4328  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 09:35:57.784  4328  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 09:35:57.784  4328  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 09:35:57.784  4328  4356 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 09:35:57.784  4328  4356 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 09:35:57.784  4328  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 09:35:57.784  4328  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 09:35:57.784  4328  4356 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-07 09:35:57.784  4328  4356 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-07 09:35:57.784  4328  4356 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-07 09:35:57.784  4328  4356 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-07 09:35:57.784  4328  4356 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:35:57.784  4328  4356 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:35:57.784  4328  4356 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 09:35:57.785  4328  4356 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-07 09:35:57.785  4328  4356 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 09:35:57.785  4328  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 09:35:57.785  4328  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 09:35:57.785  4328  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 09:35:57.785  4328  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 09:35:57.785  4328  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 09:35:57.785  4328  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 09:35:57.785  4328  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 09:35:57.785  4328  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 09:35:57.785  4328  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 09:35:57.785  4328  4356 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 09:35:57.785  4328  4356 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 09:35:57.785  4328  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 09:35:57.785  4328  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 09:35:57.785  4328  4356 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-07 09:35:57.785  4328  4356 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-07 09:35:57.785  4328  4356 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-07 09:35:57.785  4328  4356 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-07 09:35:57.785  4328  4356 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:35:57.785  4328  4356 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:35:57.785  4328  4356 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 09:35:57.797  4360  4360 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:35:57.797  4360  4360 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 09:35:57.798  4360  4360 D AndroidRuntime: Shutting down VM
,09-07 09:35:57.803  4360  4360 E AndroidRuntime: FATAL EXCEPTION: main
09-07 09:35:57.803  4360  4360 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4360
09-07 09:35:57.803  4360  4360 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 09:35:57.803  4360  4360 E AndroidRuntime: 	... 10 more
09-07 09:35:57.804   876  1709 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 09:35:57.805   876  4385 E DropBoxManagerService: Can't write: system_app_crash
09-07 09:35:57.805   876  4385 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-07 09:35:57.805   876  4385 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 09:35:57.805   876  4385 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 09:35:57.805   876  4385 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 09:35:57.805   876  4385 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 09:35:57.805   876  4385 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 09:35:57.805   876  4385 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 09:35:57.805   876  4385 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 09:35:57.805   876  4385 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 09:35:57.805   876  4385 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 09:35:57.805   876  4385 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 09:35:57.805   876  4385 E DropBoxManagerService: 	... 5 more
,09-07 09:35:57.810  4360  4360 I Process : Sending signal. PID: 4360 SIG: 9
,09-07 09:35:57.815  4372  4372 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-07 09:35:57.823  1750  4386 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-07 09:35:57.824  1750  4386 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-07 09:35:57.838   876  1537 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4360) has died
,09-07 09:35:57.839   876  1537 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-07 09:35:57.844  1750  4386 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-07 09:35:57.845  1750  4386 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-07 09:35:57.850  1524  1524 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-07 09:35:57.852  1524  1524 D AndroidRuntime: Shutting down VM
,09-07 09:35:57.853   876   889 I ActivityManager: Start proc 4390:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-07 09:35:57.854  1524  1524 E AndroidRuntime: FATAL EXCEPTION: main
09-07 09:35:57.854  1524  1524 E AndroidRuntime: Process: com.google.process.gapps, PID: 1524
09-07 09:35:57.854  1524  1524 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 09:35:57.854  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-07 09:35:57.854  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-07 09:35:57.854  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-07 09:35:57.854  1524  1524 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:35:57.854  1524  1524 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:35:57.854  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:35:57.854  1524  1524 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:35:57.854  1524  1524 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:35:57.854  1524  1524 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 09:35:57.854  1524  1524 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 09:35:57.854  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-07 09:35:57.854  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-07 09:35:57.854  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-07 09:35:57.854  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-07 09:35:57.854  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-07 09:35:57.854  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-07 09:35:57.854  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-07 09:35:57.854  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-07 09:35:57.854  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-07 09:35:57.854  1524  1524 E AndroidRuntime: 	... 8 more
,09-07 09:35:57.858   876  4398 E DropBoxManagerService: Can't write: system_app_crash
09-07 09:35:57.858   876  4398 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-07 09:35:57.858   876  4398 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 09:35:57.858   876  4398 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 09:35:57.858   876  4398 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 09:35:57.858   876  4398 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 09:35:57.858   876  4398 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 09:35:57.858   876  4398 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 09:35:57.858   876  4398 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 09:35:57.858   876  4398 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 09:35:57.858   876  4398 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 09:35:57.858   876  4398 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 09:35:57.858   876  4398 E DropBoxManagerService: 	... 5 more
,09-07 09:35:57.860  1524  1524 I Process : Sending signal. PID: 1524 SIG: 9
,09-07 09:35:57.875   876  1707 I ActivityManager: Killing 3690:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-07 09:35:57.899  4390  4390 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:35:57.899  4390  4390 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 09:35:57.899  4390  4390 D AndroidRuntime: Shutting down VM
,09-07 09:35:57.905  4328  4356 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-07 09:35:57.910  4328  4359 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:35:57.910  4328  4359 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 09:35:57.910  4328  4359 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-07 09:35:57.910  4328  4359 E AndroidRuntime: Process: android.process.acore, PID: 4328
09-07 09:35:57.910  4328  4359 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 09:35:57.910  4328  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 09:35:57.910  4328  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 09:35:57.910  4328  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 09:35:57.910  4328  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 09:35:57.910  4328  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 09:35:57.910  4328  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 09:35:57.910  4328  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 09:35:57.910  4328  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 09:35:57.910  4328  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 09:35:57.910  4328  4359 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 09:35:57.910  4328  4359 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 09:35:57.910  4328  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 09:35:57.910  4328  4359 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 09:35:57.910  4328  4359 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-07 09:35:57.910  4328  4359 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-07 09:35:57.910  4328  4359 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-07 09:35:57.910  4328  4359 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-07 09:35:57.910  4328  4359 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-07 09:35:57.910  4328  4359 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-07 09:35:57.910  4328  4359 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-07 09:35:57.910  4328  4359 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:35:57.910  4328  4359 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:35:57.910  4328  4359 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 09:35:57.911  4328  4356 I Process : Sending signal. PID: 4328 SIG: 9
,09-07 09:35:57.915   876  1321 D WifiService: Client connection lost with reason: 4
,09-07 09:35:57.919   876  1537 I ActivityManager: Process com.google.process.gapps (pid 1524) has died
,09-07 09:35:57.919   876  1537 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
09-07 09:35:57.919   876  1537 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 10999ms
09-07 09:35:57.919   876  1537 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
09-07 09:35:57.920  1750  1750 W RocketImpressions: ClearcutLogger connection suspended: 1
09-07 09:35:57.922   876  4404 E DropBoxManagerService: Can't write: system_app_crash
09-07 09:35:57.922   876  4404 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-07 09:35:57.922   876  4404 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 09:35:57.922   876  4404 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 09:35:57.922   876  4404 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 09:35:57.922   876  4404 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 09:35:57.922   876  4404 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 09:35:57.922   876  4404 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 09:35:57.922   876  4404 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 09:35:57.922   876  4404 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 09:35:57.922   876  4404 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 09:35:57.922   876  4404 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 09:35:57.922   876  4404 E DropBoxManagerService: 	... 5 more
,09-07 09:35:57.928  4390  4390 E AndroidRuntime: FATAL EXCEPTION: main
09-07 09:35:57.928  4390  4390 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4390
09-07 09:35:57.928  4390  4390 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 09:35:57.928  4390  4390 E AndroidRuntime: 	... 10 more
,09-07 09:35:57.931   876  1707 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-07 09:35:57.932  4390  4390 I Process : Sending signal. PID: 4390 SIG: 9
09-07 09:35:57.932   876  4405 E DropBoxManagerService: Can't write: system_app_crash
09-07 09:35:57.932   876  4405 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-07 09:35:57.932   876  4405 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 09:35:57.932   876  4405 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 09:35:57.932   876  4405 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 09:35:57.932   876  4405 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 09:35:57.932   876  4405 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 09:35:57.932   876  4405 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 09:35:57.932   876  4405 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 09:35:57.932   876  4405 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 09:35:57.932   876  4405 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 09:35:57.932   876  4405 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 09:35:57.932   876  4405 E DropBoxManagerService: 	... 5 more
,09-07 09:35:57.952   876  1709 I ActivityManager: Start proc 4407:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,09-07 09:35:57.958   876   887 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4390) has died
,09-07 09:35:57.960   876   887 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0

```
