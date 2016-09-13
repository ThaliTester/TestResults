#### Test 8362733795b1a33_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
09-13 16:09:12.674   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
09-13 16:09:13.348  3805  3805 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 16:09:13.353  3805  3805 D AndroidRuntime: CheckJNI is OFF
09-13 16:09:13.397  3805  3805 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 16:09:13.448  3805  3805 I Radio-JNI: register_android_hardware_Radio DONE
09-13 16:09:13.470  3805  3805 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 16:09:13.474   874  1940 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 16:09:13.530  2005  2408 W SearchService: Abort, client detached.
09-13 16:09:13.535  3805  3805 D AndroidRuntime: Shutting down VM
09-13 16:09:13.540  2005  2005 I HotwordDetector: Closing mic
09-13 16:09:13.540  2005  2340 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@ce72a1f
09-13 16:09:13.541  2005  2358 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-13 16:09:13.557   874  1963 I ActivityManager: Start proc 3815:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-13 16:09:13.600   375  2360 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-13 16:09:13.600   375  2360 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-13 16:09:13.608   375  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-13 16:09:13.609  2005  2357 I MicroRecognitionRnrImpl: Detection finished
09-13 16:09:13.610  2005  2343 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-13 16:09:13.637  3815  3815 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-13 16:09:13.659  3815  3815 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-13 16:09:13.666  3815  3815 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4113-4115)
09-13 16:09:13.666  3815  3815 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 16:09:13.677  3815  3815 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3daba0c}
09-13 16:09:13.678  3815  3815 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 16:09:13.678  3815  3815 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 16:09:13.683  3815  3815 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-13 16:09:13.684  3815  3815 E SysUtils: ApplicationContext is null in ApplicationStatus
09-13 16:09:13.695  3815  3815 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-13 16:09:13.704  3815  3815 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 16:09:13.705  3815  3815 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 16:09:13.705  3815  3815 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 16:09:13.705  3815  3815 I Adreno  : Build Date                       : 10/20/15
09-13 16:09:13.705  3815  3815 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 16:09:13.705  3815  3815 I Adreno  : Local Branch                     : M14
09-13 16:09:13.705  3815  3815 I Adreno  : Remote Branch                    : 
09-13 16:09:13.705  3815  3815 I Adreno  : Remote Branch                    : 
09-13 16:09:13.705  3815  3815 I Adreno  : Reconstruct Branch               : 
09-13 16:09:13.742   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6059767:true
,09-13 16:09:13.792  3815  3815 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 16:09:13.805  3815  3815 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-13 16:09:13.870  3815  3853 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-13 16:09:13.878  3815  3840 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-13 16:09:13.904  3815  3853 I OpenGLRenderer: Initialized EGL, version 1.4
,09-13 16:09:13.958   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +421ms
,09-13 16:09:13.959  1867  1867 I Keyboard.Facilitator: onFinishInput()
,09-13 16:09:14.011  3815  3815 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3815
,09-13 16:09:14.127  3815  3815 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 16:09:14.347  3815  3855 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1694959312
,09-13 16:09:14.357  3815  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 16:09:14.357  3815  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 16:09:14.357  3815  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 16:09:14.357  3815  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 16:09:14.357  3815  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-13 16:09:14.357  3815  3855 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c061993 added. We now have 1 listener(s)
,09-13 16:09:14.361  3815  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-13 16:09:14.362  3815  3855 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 16:09:14.363  3815  3855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:09:14.364  3815  3855 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:09:14.365   874  1963 I ActivityManager: Killing 2967:com.google.android.calendar/u0a37 (adj 15): empty #17
09-13 16:09:14.367  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 16:09:14.367  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 16:09:14.367  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 16:09:14.367  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-13 16:09:14.367  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 16:09:14.367  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 16:09:14.367  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 16:09:14.367  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 16:09:14.367  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 16:09:14.367  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 16:09:14.367  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 16:09:14.367  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 16:09:14.367  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 16:09:14.367  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 16:09:14.367  3815  3855 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ceebbef added. We now have 1 listener(s)
09-13 16:09:14.367  3815  3855 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:09:14.369   874  1309 D WifiService: New client listening to asynchronous messages
,09-13 16:09:14.370  3815  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 16:09:14.370  3815  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-13 16:09:14.370  3815  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 16:09:14.370  3815  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 16:09:14.370  3815  3855 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-13 16:09:14.402   874  1963 I ActivityManager: Killing 3206:com.google.android.gm/u0a78 (adj 15): empty #18
,09-13 16:09:14.435  3815  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:09:14.435  3815  3855 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-13 16:09:14.442  3815  3855 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-13 16:09:14.443  3815  3855 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:09:14.443  3815  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:14.443  3815  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:14.443  3815  3855 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:14.443  3815  3855 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:14.443  3815  3855 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:09:14.443  3815  3855 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:09:14.443  3815  3855 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:09:14.443  3815  3855 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-13 16:09:14.443  3815  3855 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:09:14.443  3815  3855 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 16:09:14.539  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:14.542  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:14.545  3815  3815 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 16:09:15.407  3815  3863 W jxcore-log: Initializing JXcore engine
,09-13 16:09:15.407  3815  3863 W jxcore-log: JXcore engine is ready
,09-13 16:09:15.445  3863  3863 W Thread-333: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8956 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-13 16:09:15.460  3815  3863 W jxcore-log: Starting JXcore engine
,09-13 16:09:15.445  3863  3863 W Thread-333: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12931]" dev="sockfs" ino=12931 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-13 16:09:15.445  3863  3863 W Thread-333: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-13 16:09:15.445  3863  3863 W Thread-333: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25226]" dev="sockfs" ino=25226 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-13 16:09:15.574  3815  3863 W jxcore-log: Platform android
09-13 16:09:15.574  3815  3863 W jxcore-log: 
09-13 16:09:15.574  3815  3863 W jxcore-log: Process ARCH arm
09-13 16:09:15.574  3815  3863 W jxcore-log: 
,09-13 16:09:15.826  3815  3863 I jxcore-log: JXcore Cordova bridge is ready!
09-13 16:09:15.826  3815  3863 I jxcore-log: 
,09-13 16:09:15.827  3815  3863 W jxcore-log: JXcore engine is started
,09-13 16:09:15.834  3815  3855 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 16:09:15.839  3815  3815 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 16:09:18.709   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 16:09:22.087   874  1308 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-13 16:09:23.780  1543  1543 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 16:09:23.785  1543  1543 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 16:09:23.788  1543  1543 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 16:09:23.809  1543  2171 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 16:09:23.810  1543  2171 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 16:09:23.810  1543  2171 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 16:09:23.810  1543  2171 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 16:09:23.831  3502  3502 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 16:09:23.831  3502  3502 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 16:09:23.831  3502  3502 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-13 16:09:25.712  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 16:09:25.712  3815  3863 I jxcore-log: 
,09-13 16:09:25.714  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 16:09:25.714  3815  3863 I jxcore-log: 
,09-13 16:09:25.728  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:09:25.728  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:25.728  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:25.728  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:25.728  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:25.728  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:09:25.728  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:09:25.728  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:09:25.734  3815  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:09:25.739  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 16:09:25.739  3815  3863 I jxcore-log: 
,09-13 16:09:25.747  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 16:09:25.747  3815  3863 I jxcore-log: 
,09-13 16:09:26.343  3815  3863 I jxcore-log: Unit Test app is loaded
09-13 16:09:26.343  3815  3863 I jxcore-log: 
,09-13 16:09:26.356  3815  3815 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-13 16:09:26.358  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:09:26.358  3815  3863 I jxcore-log: 
,09-13 16:09:26.363  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 16:09:26.363  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5de9c added. We now have 2 listener(s)
,09-13 16:09:26.365  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 16:09:26.365  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:09:26.365  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:09:26.365  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:09:26.365  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2b80a5 added. We now have 2 listener(s)
09-13 16:09:26.365  3815  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:09:26.366  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 16:09:26.371  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:09:26.386  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:09:26.386  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:26.386  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:26.386  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:26.386  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:26.386  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:09:26.386  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:09:26.386  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:09:26.393  3815  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:09:26.393  3815  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:09:26.394  3815  3863 D ExecuteNativeTests: Running unit tests
,09-13 16:09:26.397  3815  3863 D BluetoothAdapter: enable(): BT is already enabled..!
,09-13 16:09:26.398   874   885 D WifiService: setWifiEnabled: true pid=3815, uid=10000
,09-13 16:09:26.398   874   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 16:09:26.399  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:26.402  3815  3863 I System.out: Running UT
,09-13 16:09:26.403  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:29.509  1543  1543 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 16:09:29.513  1543  1543 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 16:09:29.565  1543  2303 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 16:09:29.566  1543  2303 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 16:09:29.566  1543  2303 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 16:09:29.566  1543  2303 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 16:09:29.600  3541  3878 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 16:09:29.600  3541  3878 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 16:09:29.600  3541  3878 E HttpOperation: 	at jdm.a(PG:82)
09-13 16:09:29.600  3541  3878 E HttpOperation: 	at jcs.o(PG:406)
09-13 16:09:29.600  3541  3878 E HttpOperation: 	at jcn.a(PG:1379)
09-13 16:09:29.600  3541  3878 E HttpOperation: 	at jcs.i(PG:143)
09-13 16:09:29.600  3541  3878 E HttpOperation: 	at blb.a(PG:3937)
09-13 16:09:29.600  3541  3878 E HttpOperation: 	at czp.a(PG:18188)
09-13 16:09:29.600  3541  3878 E HttpOperation: 	at czp.a(PG:9081)
09-13 16:09:29.600  3541  3878 E HttpOperation: 	at czq.run(PG:1686)
09-13 16:09:29.600  3541  3878 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 16:09:29.600  3541  3878 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 16:09:29.600  3541  3878 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 16:09:29.600  3541  3878 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 16:09:29.600  3541  3878 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 16:09:29.600  3541  3878 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 16:09:29.600  3541  3878 E HttpOperation: 	at jdj.a(PG:4091)
09-13 16:09:29.600  3541  3878 E HttpOperation: 	at jdj.a(PG:1125)
09-13 16:09:29.600  3541  3878 E HttpOperation: 	at jdm.a(PG:77)
09-13 16:09:29.600  3541  3878 E HttpOperation: 	... 12 more
09-13 16:09:29.600  3541  3878 E HttpOperation: Caused by: faj: BadAuthentication
09-13 16:09:29.600  3541  3878 E HttpOperation: 	at fal.a(PG:38)
09-13 16:09:29.600  3541  3878 E HttpOperation: 	at jdj.a(PG:4089)
09-13 16:09:29.600  3541  3878 E HttpOperation: 	... 14 more
,09-13 16:09:29.661  1543  1558 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-13 16:09:29.661  1543  1558 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-13 16:09:29.661  1543  1558 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 16:09:29.661  1543  1558 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 16:09:29.689  3541  3878 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 16:09:29.689  3541  3878 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 16:09:29.689  3541  3878 E HttpOperation: 	at jdm.a(PG:82)
09-13 16:09:29.689  3541  3878 E HttpOperation: 	at jcs.o(PG:406)
09-13 16:09:29.689  3541  3878 E HttpOperation: 	at jcn.a(PG:1379)
09-13 16:09:29.689  3541  3878 E HttpOperation: 	at jcs.i(PG:143)
09-13 16:09:29.689  3541  3878 E HttpOperation: 	at hec.a(PG:42)
09-13 16:09:29.689  3541  3878 E HttpOperation: 	at hee.a(PG:102)
09-13 16:09:29.689  3541  3878 E HttpOperation: 	at czr.a(PG:65)
09-13 16:09:29.689  3541  3878 E HttpOperation: 	at kka.a(PG:108)
09-13 16:09:29.689  3541  3878 E HttpOperation: 	at czp.a(PG:19176)
09-13 16:09:29.689  3541  3878 E HttpOperation: 	at czp.a(PG:9081)
09-13 16:09:29.689  3541  3878 E HttpOperation: 	at czq.run(PG:1686)
09-13 16:09:29.689  3541  3878 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 16:09:29.689  3541  3878 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 16:09:29.689  3541  3878 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 16:09:29.689  3541  3878 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 16:09:29.689  3541  3878 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 16:09:29.689  3541  3878 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 16:09:29.689  3541  3878 E HttpOperation: 	at jdj.a(PG:4091)
09-13 16:09:29.689  3541  3878 E HttpOperation: 	at jdj.a(PG:1125)
09-13 16:09:29.689  3541  3878 E HttpOperation: 	at jdm.a(PG:77)
09-13 16:09:29.689  3541  3878 E HttpOperation: 	... 15 more
09-13 16:09:29.689  3541  3878 E HttpOperation: Caused by: faj: BadAuthentication
09-13 16:09:29.689  3541  3878 E HttpOperation: 	at fal.a(PG:38)
09-13 16:09:29.689  3541  3878 E HttpOperation: 	at jdj.a(PG:4089)
09-13 16:09:29.689  3541  3878 E HttpOperation: 	... 17 more
,09-13 16:09:29.689  3541  3878 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 16:09:29.689  3541  3878 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 16:09:29.689  3541  3878 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 16:09:29.689  3541  3878 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 16:09:29.689  3541  3878 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 16:09:29.689  3541  3878 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 16:09:29.689  3541  3878 E ExperimentLoader: 	at hec.a(PG:42)
09-13 16:09:29.689  3541  3878 E ExperimentLoader: 	at hee.a(PG:102)
09-13 16:09:29.689  3541  3878 E ExperimentLoader: 	at czr.a(PG:65)
09-13 16:09:29.689  3541  3878 E ExperimentLoader: 	at kka.a(PG:108)
09-13 16:09:29.689  3541  3878 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 16:09:29.689  3541  3878 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 16:09:29.689  3541  3878 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 16:09:29.689  3541  3878 E ExperimentLoader: ,	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 16:09:29.689  3541  3878 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 16:09:29.689  3541  3878 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 16:09:29.689  3541  3878 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 16:09:29.689  3541  3878 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 16:09:29.689  3541  3878 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 16:09:29.689  3541  3878 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 16:09:29.689  3541  3878 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 16:09:29.689  3541  3878 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 16:09:29.689  3541  3878 E ExperimentLoader: 	... 15 more
09-13 16:09:29.689  3541  3878 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 16:09:29.689  3541  3878 E ExperimentLoader: 	at fal.a(PG:38)
09-13 16:09:29.689  3541  3878 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 16:09:29.689  3541  3878 E ExperimentLoader: 	... 17 more
,09-13 16:09:29.832   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 129698, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-13 16:09:36.496  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 16:09:36.496  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5661b added. We now have 3 listener(s)
,09-13 16:09:36.498  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 16:09:36.498  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:09:36.498  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 16:09:36.498  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:09:36.498  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ae3b8 added. We now have 3 listener(s)
09-13 16:09:36.498  3815  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:09:36.499  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 16:09:36.505  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:09:36.518  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:09:36.518  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:36.518  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:36.518  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:36.518  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:36.518  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:09:36.518  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:09:36.518  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:09:36.524  3815  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:09:36.524  3815  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:09:36.541  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:36.544  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 16:09:36.544  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:36.546  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 16:09:36.546  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 16:09:36.546  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:09:36.548  3815  3863 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-13 16:09:36.548  3815  3863 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 16:09:36.548  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 16:09:36.548  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 16:09:36.548  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:09:36.548  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 16:09:36.549  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:09:36.549  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:09:36.549  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:09:36.549  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 16:09:36.549  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5661b removed from the list
,09-13 16:09:36.549  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:09:36.549  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ae3b8 removed from the list
09-13 16:09:36.549  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:09:36.549  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:36.551  3815  3863 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-13 16:09:36.551  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:09:36.552  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:36.552  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:36.552  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5661b not in the list
09-13 16:09:36.552  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:09:36.552  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ae3b8 not in the list
,09-13 16:09:36.552  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:09:36.552  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:09:36.552  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:09:36.556  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-13 16:09:36.556  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-13 16:09:36.556  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 16:09:36.556  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 16:09:36.556  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 16:09:36.557  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 16:09:36.557  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 16:09:36.557  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 16:09:36.557  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 16:09:36.557  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 16:09:36.557  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 16:09:36.557  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 16:09:36.557  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 16:09:36.557  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 16:09:36.557  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 16:09:36.557  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 16:09:36.557  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 16:09:36.557  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 16:09:36.557  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 16:09:36.557  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-13 16:09:36.557  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 16:09:36.557  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 16:09:36.558  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 16:09:36.558  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 16:09:36.558  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 16:09:36.558  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 16:09:36.558  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 16:09:36.558  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 16:09:36.558  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 16:09:36.558  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 16:09:36.558  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 16:09:36.558  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:09:36.558  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:36.558  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:36.558  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5661b not in the list
09-13 16:09:36.558  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:09:36.558  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ae3b8 not in the list
09-13 16:09:36.558  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:09:36.558  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:36.558  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:36.559  3815  3863 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 16:09:36.560  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:09:36.568  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:09:36.568  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:36.568  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:36.568  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:36.568  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:36.568  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:09:36.568  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:09:36.568  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:09:36.570  3815  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:09:36.570  3815  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:09:36.570  3815  3863 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-13 16:09:36.571  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-13 16:09:36.572  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:09:36.572  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:09:36.572  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:09:36.573  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:09:36.573  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:36.573  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 16:09:36.574  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:09:36.574  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:09:36.575  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:09:36.575  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:09:36.575  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:09:36.575  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:09:36.579  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:36.579  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:09:36.579  3815  3881 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:09:36.584  3815  3863 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 16:09:36.584  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 16:09:36.584  3815  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 16:09:36.588  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 16:09:36.590  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 16:09:36.590  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 16:09:36.593  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 16:09:36.593  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 16:09:36.593  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
09-13 16:09:36.594  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:09:36.594  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:09:36.594  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 16:09:36.596  3815  3863 D BluetoothAdapter: STATE_ON
09-13 16:09:36.602  2629  2643 D BtGatt.GattService: registerClient() - UUID=1b1e3240-4042-4e30-a3b2-cc1df126c878
09-13 16:09:36.603  2629  2671 D BtGatt.GattService: onClientRegistered() - UUID=1b1e3240-4042-4e30-a3b2-cc1df126c878, clientIf=5
09-13 16:09:36.604  3815  3827 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-13 16:09:36.605  2629  2673 D BtGatt.AdvertiseManager: message : 0
09-13 16:09:36.607  2629  2673 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:09:36.627  2629  2671 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
09-13 16:09:36.640  2629  2671 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
09-13 16:09:36.641  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 16:09:36.641  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 16:09:36.643  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-13 16:09:36.645  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:09:36.646  3815  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 16:09:36.646  3815  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 16:09:36.646  3815  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 16:09:36.646  3815  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:09:36.646  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-13 16:09:36.646  3815  3863 I io.jxcore.node.ConnectionHelper: start: OK
09-13 16:09:36.648  3815  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 16:09:36.648  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 16:09:36.650  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 16:09:36.650  3815  3863 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 16:09:36.650  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-13 16:09:36.651  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 16:09:36.651  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:09:36.651  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:09:36.651  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 16:09:36.651  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 16:09:36.652  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:09:36.652  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:09:36.652  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 16:09:36.652  3815  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 16:09:36.652  3815  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:09:36.652  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:09:36.652  3815  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:09:36.652  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:09:36.652  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:09:36.653  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 16:09:36.654  3815  3863 D BluetoothAdapter: STATE_ON
,09-13 16:09:36.654  3815  3863 D BluetoothLeScanner: could not find callback wrapper
09-13 16:09:36.654  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 16:09:36.655  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 16:09:36.656  2629  2673 D BtGatt.AdvertiseManager: message : 1
09-13 16:09:36.656  2629  2673 D BtGatt.AdvertiseManager: stop advertise for client 5
09-13 16:09:36.665  2629  2671 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-13 16:09:36.665  2629  2671 D BtGatt.GattService: Client app is not null!
,09-13 16:09:36.668  2629  2642 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 16:09:36.670  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 16:09:36.671  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:09:36.671  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 16:09:36.671  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:09:36.671  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:09:36.673  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:09:36.673  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:09:36.674  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:09:36.674  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:09:36.676  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 16:09:36.676  3815  3815 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:09:36.677  3815  3815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:09:36.677  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:09:36.677  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:09:36.677  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:09:36.679  3815  3863 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 16:09:36.679  3815  3863 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-13 16:09:36.679  3815  3863 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-13 16:09:36.679  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,09-13 16:09:36.682  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:09:36.682  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:09:36.682  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:09:36.683  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:09:36.684  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:09:36.685  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 16:09:36.685  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:09:36.686  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:09:36.686  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:09:36.686  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:09:36.686  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:09:36.686  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:09:36.688  3815  3884 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:09:36.691  3815  3863 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 16:09:36.691  3815  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:09:36.691  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:09:36.697  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:09:36.698  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 16:09:36.698  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:09:36.701  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 16:09:36.701  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 16:09:36.702  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 F8 CF C5 D9 E5 61
09-13 16:09:36.702  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:09:36.702  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:09:36.702  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 16:09:36.703  3815  3863 D BluetoothAdapter: STATE_ON
,09-13 16:09:36.708  2629  2762 D BtGatt.GattService: registerClient() - UUID=60866310-232f-44f7-a3ec-c14303cf2394
,09-13 16:09:36.708  2629  2671 D BtGatt.GattService: onClientRegistered() - UUID=60866310-232f-44f7-a3ec-c14303cf2394, clientIf=5
09-13 16:09:36.709  3815  3825 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-13 16:09:36.709  2629  2673 D BtGatt.AdvertiseManager: message : 0
,09-13 16:09:36.713  2629  2673 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:09:36.730  2629  2671 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 16:09:36.741  2629  2671 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 16:09:36.742  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 16:09:36.742  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:09:36.745  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:09:36.747  3815  3863 I io.jxcore.node.ConnectionHelper: start: OK
09-13 16:09:36.747  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:09:36.747  3815  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 16:09:36.747  3815  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-13 16:09:36.747  3815  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 16:09:36.747  3815  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:09:36.747  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:09:36.749  3815  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 16:09:36.750  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:09:36.907   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 16:09:37.250  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:09:37.250  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 16:09:37.251  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:09:37.251  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:09:37.251  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 16:09:37.257  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 16:09:37.257  3815  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 16:09:37.258  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:09:37.258  3815  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 16:09:37.258  3815  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:09:37.258  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5661b not in the list
,09-13 16:09:37.258  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:09:37.259  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:09:37.259  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:09:37.259  3815  3815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:09:37.259  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:09:37.261  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 16:09:37.261  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 16:09:37.264  3815  3863 D BluetoothAdapter: STATE_ON
09-13 16:09:37.265  3815  3863 D BluetoothLeScanner: could not find callback wrapper
,09-13 16:09:37.265  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:09:37.265  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 16:09:37.268  2629  2673 D BtGatt.AdvertiseManager: message : 1
,09-13 16:09:37.271  2629  2673 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 16:09:37.299  2629  2671 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 16:09:37.299  2629  2671 D BtGatt.GattService: Client app is not null!
09-13 16:09:37.302  2629  2761 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 16:09:37.304  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 16:09:37.305  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 16:09:37.305  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 16:09:37.306  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-13 16:09:37.306  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:09:37.310  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:09:37.310  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:09:37.311  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:09:37.312  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:09:37.317  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ae3b8 not in the list
,09-13 16:09:37.317  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:09:37.317  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:09:37.318  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:09:37.318  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:37.318  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:09:37.322  3815  3863 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-13 16:09:37.326  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:09:37.336  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:09:37.336  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:37.336  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:37.336  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:37.336  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:37.336  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:09:37.336  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:09:37.336  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:09:37.339  3815  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:09:37.340  3815  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:09:37.340  3815  3863 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,09-13 16:09:37.341  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,09-13 16:09:37.342  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:09:37.342  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:09:37.342  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-13 16:09:37.342  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 16:09:37.343  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:09:37.349  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:09:37.349  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:37.350  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 16:09:37.350  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:09:37.350  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:09:37.350  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 16:09:37.351  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:09:37.351  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:09:37.351  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:09:37.351  3815  3886 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:09:37.354  3815  3863 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 16:09:37.354  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:09:37.360  3815  3886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:09:37.360  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:09:37.361  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 16:09:37.361  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:09:37.365  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 16:09:37.365  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 16:09:37.365  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
09-13 16:09:37.366  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:09:37.366  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:09:37.366  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 16:09:37.367  3815  3863 D BluetoothAdapter: STATE_ON
,09-13 16:09:37.372  2629  2772 D BtGatt.GattService: registerClient() - UUID=2d26ae36-d710-47d9-baba-46022587e7d9
,09-13 16:09:37.373  2629  2671 D BtGatt.GattService: onClientRegistered() - UUID=2d26ae36-d710-47d9-baba-46022587e7d9, clientIf=5
09-13 16:09:37.373  3815  3827 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 16:09:37.375  2629  2673 D BtGatt.AdvertiseManager: message : 0
,09-13 16:09:37.380  2629  2673 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:09:37.402  2629  2671 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 16:09:37.416  2629  2671 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 16:09:37.418  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 16:09:37.419  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:09:37.422  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:09:37.426  3815  3863 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 16:09:37.426  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:09:37.427  3815  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-13 16:09:37.427  3815  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-13 16:09:37.427  3815  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true,
,09-13 16:09:37.428  3815  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-13 16:09:37.428  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:09:37.437  3815  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:09:37.438  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:09:37.931  3815  3863 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 16:09:37.931  3815  3863 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 16:09:37.931  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-13 16:09:37.932  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 16:09:37.932  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:09:37.932  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 16:09:37.933  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 16:09:37.933  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 16:09:37.934  3815  3886 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 16:09:37.934  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 16:09:37.934  3815  3886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:09:37.934  3815  3886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:09:37.934  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 16:09:37.935  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 16:09:37.936  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:09:37.936  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:09:37.936  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 16:09:37.937  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 16:09:37.941  3815  3863 D BluetoothAdapter: STATE_ON
09-13 16:09:37.941  3815  3863 D BluetoothLeScanner: could not find callback wrapper
,09-13 16:09:37.942  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:09:37.942  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 16:09:37.945  2629  2673 D BtGatt.AdvertiseManager: message : 1
09-13 16:09:37.947  2629  2673 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 16:09:37.961  2629  2671 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 16:09:37.961  2629  2671 D BtGatt.GattService: Client app is not null!
09-13 16:09:37.962  2629  2643 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 16:09:37.964  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 16:09:37.964  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:09:37.965  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 16:09:37.965  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-13 16:09:37.965  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:09:37.967  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:09:37.967  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 16:09:37.967  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:09:37.969  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:09:37.970  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 16:09:37.971  3815  3815 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 16:09:37.971  3815  3815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 16:09:37.971  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 16:09:37.971  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,09-13 16:09:37.971  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:09:37.971  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:09:37.973  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:09:37.973  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:09:37.973  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:09:37.974  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5661b not in the list
09-13 16:09:37.974  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:09:37.974  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ae3b8 not in the list
,09-13 16:09:37.974  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:09:37.974  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:09:37.981  3815  3863 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-13 16:09:37.982  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:09:37.982  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:37.982  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:09:37.982  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5661b not in the list
09-13 16:09:37.982  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-13 16:09:37.982  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ae3b8 not in the list
09-13 16:09:37.982  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:09:37.982  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:09:37.983  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:09:37.984  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-13 16:09:37.984  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:09:37.984  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:37.984  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:37.984  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5661b not in the list
09-13 16:09:37.984  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:09:37.985  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ae3b8 not in the list
09-13 16:09:37.985  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:09:37.985  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:09:37.985  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:09:37.985  3815  3863 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 16:09:37.986  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:09:37.986  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:37.986  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:37.986  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5661b not in the list
09-13 16:09:37.989  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:09:37.989  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ae3b8 not in the list
09-13 16:09:37.989  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:09:37.990  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:37.990  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:37.991  3815  3863 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 16:09:37.991  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:09:37.991  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:37.991  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:37.991  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5661b not in the list
09-13 16:09:37.991  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:09:37.991  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ae3b8 not in the list
09-13 16:09:37.991  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:09:37.991  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:37.992  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:37.992  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 16:09:37.993  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:09:37.993  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:09:37.993  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 16:09:37.993  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:09:37.993  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:09:37.993  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 16:09:37.993  3815  3863 V org.thaliproject.p2p.btconnectorli,b.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:09:37.993  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:09:37.995  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:09:37.995  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:37.995  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:37.995  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5661b not in the list
09-13 16:09:37.995  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:09:37.995  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ae3b8 not in the list
09-13 16:09:37.995  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:09:37.995  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:37.995  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:37.996  3815  3863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:09:37.996  3815  3863 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 16:09:37.997  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 16:09:38.001  3815  3863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:09:38.001  3815  3863 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 16:09:38.001  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 16:09:38.001  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 16:09:38.001  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 16:09:38.001  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 16:09:38.001  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 16:09:38.001  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 16:09:38.001  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 16:09:38.002  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 16:09:38.002  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 16:09:38.002  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 16:09:38.002  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 16:09:38.002  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 16:09:38.002  3815  38,63 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 16:09:38.002  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 16:09:38.002  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 16:09:38.002  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 16:09:38.002  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 16:09:38.002  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 16:09:38.003  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 16:09:38.003  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 16:09:38.003  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 16:09:38.003  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 16:09:38.003  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 16:09:38.003  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 16:09:38.003  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 16:09:38.003  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 16:09:38.003  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 16:09:38.003  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 16:09:38.005  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 16:09:38.005  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 16:09:38.006  3815  3863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 16:09:38.006  3815  3863 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:09:38.006  3815  3863 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 16:09:38.006  3815  3863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:09:38.006  3815  3863 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:09:38.006  3815  3863 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 16:09:38.007  3815  3863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:09:38.007  3815  3863 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:09:38.007  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 16:09:38.013  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 16:09:38.015  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 16:09:38.015  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 16:09:38.017  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 16:09:38.017  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 16:09:38.017  3815  3863 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 16:09:38.017  3815  3863 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:09:38.017  3815  3863 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 16:09:38.017  3815  3889 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 434)
09-13 16:09:38.018  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:09:38.018  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:38.018  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:38.018  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 16:09:38.018  3815  3889 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:09:38.019  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5661b not in the list
09-13 16:09:38.019  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:09:38.020  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ae3b8 not in the list
09-13 16:09:38.020  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:09:38.020  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:38.020  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:38.020  3815  3890 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 434
09-13 16:09:38.020  3815  3890 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 434)
09-13 16:09:38.021  2629  2757 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: -1
09-13 16:09:38.021  3815  3890 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 434)
09-13 16:09:38.022  3815  3863 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 16:09:38.025  3815  3889 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 434)
09-13 16:09:38.026  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:09:38.027  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:38.027  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:38.028  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5661b not in the list
09-13 16:09:38.028  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:09:38.029  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ae3b8 not in the list
09-13 16:09:38.029  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:09:38.029  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:38.029  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:38.031  3815  3863 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 16:09:38.031  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:09:38.031  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:38.032  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:38.032  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5661b not in the list
09-13 16:09:38.032  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:09:38.032  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ae3b8 not in the list
09-13 16:09:38.032  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:09:38.032  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:38.032  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:38.034  3815  3863 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 16:09:38.034  3815  3863 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 16:09:38.034  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 16:09:38.034  3815  3863 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 16:09:38.034  3815  3863 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 16:09:38.034  3815  3863 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 16:09:38.034  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 16:09:38.034  3815  3863 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 16:09:38.034  3815  3863 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 16:09:38.035  3815  3863 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 16:09:38.035  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 16:09:38.035  3815  3863 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 16:09:38.035  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:09:38.035  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:38.035  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:38.035  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5661b not in the list
09-13 16:09:38.035  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:09:38.035  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ae3b8 not in the list
09-13 16:09:38.035  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:09:38.035  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:38.035  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:38.036  3815  3863 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-13 16:09:38.037  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:09:38.044  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:09:38.044  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:38.044  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:38.044  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:38.044  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:38.044  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:09:38.044  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:09:38.044  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:09:38.046  3815  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:09:38.046  3815  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:09:38.047  3815  3863 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-13 16:09:38.047  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-13 16:09:38.047  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:09:38.047  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:09:38.047  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:09:38.047  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:09:38.049  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 16:09:38.049  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:09:38.049  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:09:38.049  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 16:09:38.049  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:38.050  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:09:38.050  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:09:38.050  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:09:38.052  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:38.052  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:09:38.053  3815  3891 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:09:38.053  3815  3863 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 16:09:38.053  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 16:09:38.054  3815  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-13 16:09:38.056  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 16:09:38.057  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 16:09:38.057  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 16:09:38.058  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 16:09:38.058  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 16:09:38.058  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 F8 CF C5 D9 E5 61
09-13 16:09:38.058  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:09:38.058  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:09:38.058  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 16:09:38.059  3815  3863 D BluetoothAdapter: STATE_ON
09-13 16:09:38.061  2629  2761 D BtGatt.GattService: registerClient() - UUID=9ae9f809-c0f0-4e34-9c96-e374a4af3fc8
09-13 16:09:38.061  2629  2671 D BtGatt.GattService: onClientRegistered() - UUID=9ae9f809-c0f0-4e34-9c96-e374a4af3fc8, clientIf=5
09-13 16:09:38.061  3815  3825 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-13 16:09:38.062  2629  2673 D BtGatt.AdvertiseManager: message : 0
09-13 16:09:38.064  2629  2673 D BtGatt.AdvertiseManager: starting multi advertising
09-13 16:09:38.073  2629  2671 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
09-13 16:09:38.077  2629  2671 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
09-13 16:09:38.078  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 16:09:38.078  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 16:09:38.079  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-13 16:09:38.080  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:09:38.080  3815  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 16:09:38.081  3815  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 16:09:38.081  3815  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 16:09:38.081  3815  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:09:38.081  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-13 16:09:38.081  3815  3863 I io.jxcore.node.ConnectionHelper: start: OK
09-13 16:09:38.083  3815  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-13 16:09:38.083  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:09:38.584  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 16:09:38.585  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-13 16:09:38.585  3815  3815 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-13 16:09:38.585  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:09:38.586  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:09:38.586  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 16:09:38.586  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 16:09:38.587  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 16:09:38.587  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 16:09:38.587  3815  3891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-13 16:09:38.587  3815  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 16:09:38.588  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 16:09:38.588  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5661b not in the list
09-13 16:09:38.588  3815  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:09:38.588  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:09:38.588  3815  3815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:09:38.588  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:09:38.588  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:09:38.589  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:09:38.589  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 16:09:38.592  3815  3863 D BluetoothAdapter: STATE_ON
09-13 16:09:38.593  3815  3863 D BluetoothLeScanner: could not find callback wrapper
09-13 16:09:38.593  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:09:38.593  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 16:09:38.596  2629  2673 D BtGatt.AdvertiseManager: message : 1
09-13 16:09:38.597  2629  2673 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 16:09:38.622  2629  2671 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 16:09:38.622  2629  2671 D BtGatt.GattService: Client app is not null!
,09-13 16:09:38.625  2629  2762 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 16:09:38.627  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 16:09:38.627  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 16:09:38.627  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-13 16:09:38.628  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-13 16:09:38.628  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-13 16:09:38.632  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:09:38.632  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 16:09:38.632  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:09:38.634  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:09:38.639  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:09:38.640  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:09:38.641  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ae3b8 not in the list
09-13 16:09:38.642  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:09:38.642  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:09:38.645  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:09:38.651  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:09:38.651  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:09:38.651  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:09:38.652  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5661b not in the list
,09-13 16:09:38.652  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:09:38.652  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ae3b8 not in the list
09-13 16:09:38.652  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:09:38.653  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:38.653  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:38.658  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:09:38.658  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:09:38.659  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 16:09:38.659  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:09:38.659  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:09:38.659  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:09:38.659  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 16:09:38.660  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:09:38.660  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:09:38.660  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:09:38.660  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:09:38.660  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:09:38.660  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:38.661  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:09:38.661  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5661b not in the list
09-13 16:09:38.661  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:09:38.661  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:09:38.661  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:09:38.661  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:09:38.661  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:38.661  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:38.661  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:09:38.661  3815  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:09:38.661  3815  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:09:38.663  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:09:38.663  3815  3863 E org.thaliproject.p2p.btconnectorlib.Dis,coveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ae3b8 not in the list
09-13 16:09:38.663  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:09:38.663  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:38.663  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:09:38.663  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:38.663  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:09:38.663  3815  3815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:09:38.664  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:09:38.665  3815  3863 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-13 16:09:38.665  3815  3863 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-13 16:09:38.665  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-13 16:09:38.667  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 16:09:38.667  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:09:38.667  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:09:38.667  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:38.667  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:38.668  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5661b not in the list
09-13 16:09:38.668  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:09:38.668  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ae3b8 not in the list
09-13 16:09:38.668  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:09:38.668  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:38.668  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:38.672  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:09:38.673  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:38.673  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:38.673  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5661b not in the list
09-13 16:09:38.673  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:09:38.673  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ae3b8 not in the list
09-13 16:09:38.673  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:09:38.673  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:38.673  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:38.674  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:09:38.674  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:38.674  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:38.675  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a5661b not in the list,
09-13 16:09:38.675  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:09:38.675  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ae3b8 not in the list
09-13 16:09:38.675  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:09:38.675  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:38.675  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:38.676  3815  3863 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 16:09:38.676  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-13 16:09:38.679  3815  3863 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 16:09:38.679  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 16:09:38.679  3815  3863 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 16:09:38.679  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-13 16:09:38.682  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming],
09-13 16:09:38.682  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-13 16:09:38.683  3815  3863 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-13 16:09:38.683  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 16:09:38.683  3815  3863 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-13 16:09:38.683  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 16:09:38.683  3815  3863 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,09-13 16:09:38.683  3815  3863 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-13 16:09:38.684  3815  3863 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 16:09:38.684  3815  3863 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-13 16:09:38.684  3815  3863 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 16:09:38.685  3815  3863 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 16:09:38.685  3815  3863 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 16:09:38.685  3815  3863 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-13 16:09:38.686  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 16:09:38.686  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7da501 added. We now have 3 listener(s)
,09-13 16:09:38.688  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 16:09:38.688  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:09:38.688  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:09:38.688  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-13 16:09:38.688  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8bbfa6 added. We now have 3 listener(s)
09-13 16:09:38.688  3815  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:09:38.689  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 16:09:38.692  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:09:38.699  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:09:38.699  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:38.699  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:38.699  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:38.699  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:38.699  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:09:38.699  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:09:38.699  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:09:38.702  3815  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:09:38.702  3815  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:09:38.705  3815  3863 D BluetoothAdapter: enable(): BT is already enabled..!
,09-13 16:09:38.705   874  2165 D WifiService: setWifiEnabled: true pid=3815, uid=10000
,09-13 16:09:38.705   874  2165 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-13 16:09:38.705  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:38.709  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:38.716   874  1383 D WifiService: setWifiEnabled: false pid=3815, uid=10000
09-13 16:09:38.716   874  1383 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 16:09:38.741  1480  1480 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-13 16:09:38.749   874  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-13 16:09:38.750   874  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-13 16:09:38.750   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 16:09:38.751   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 16:09:38.763   874  1882 D DhcpClient: Clearing IP address
,09-13 16:09:38.763   371   872 D CommandListener: Clearing all IP addresses on wlan0
,09-13 16:09:38.767   371   872 D CommandListener: Setting iface cfg
,09-13 16:09:38.770  1543  2107 V NativeCrypto: Read error: ssl=0xab488a00: I/O error during system call, Connection timed out
,09-13 16:09:38.777  1543  2107 V NativeCrypto: SSL shutdown failed: ssl=0xab488a00: I/O error during system call, Broken pipe
09-13 16:09:38.778   874  1883 D DhcpClient: Receive thread stopped
,09-13 16:09:38.785   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-13 16:09:38.785   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-13 16:09:38.786   394   394 E Parcel  : Reading a NULL string not supported here.
,09-13 16:09:38.796   874  1308 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-13 16:09:38.798   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 16:09:38.802   874  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-13 16:09:38.803   371   872 D CommandListener: Clearing all IP addresses on wlan0
,09-13 16:09:38.824   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 16:09:38.830  2166  2328 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:09:38.830  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:38.830  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:38.830  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:38.830  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 16:09:38.830  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:38.830  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:38.830  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:38.830  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 16:09:38.831   874  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-13 16:09:38.832  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 16:09:38.835  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:38.835  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:38.835  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:38.835  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 16:09:38.835  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,09-13 16:09:38.835  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
09-13 16:09:38.835  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:38.835  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 16:09:38.838  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 16:09:38.842  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-13 16:09:38.842  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:38.842  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:38.842  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false,
09-13 16:09:38.842  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:38.842  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:38.842  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:38.842  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 16:09:38.844  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 16:09:38.851   874   887 I ActivityManager: Start proc 3902:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-13 16:09:38.851   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 16:09:38.874   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 16:09:38.875   874  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-13 16:09:38.875   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 16:09:38.878   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-13 16:09:38.879  3400  3400 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@515ddd0 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-13 16:09:38.879  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:38.880  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:38.881  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:38.902  3902  3902 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-13 16:09:38.933   371   872 E Netd    : netlink response contains error (No such file or directory)
,09-13 16:09:38.934   874  1310 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-13 16:09:38.938  3902  3902 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-13 16:09:38.951  1751  1751 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 16:09:38.954  1751  1751 D SystemUpdateService: onCreate
,09-13 16:09:38.956  1751  1751 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 16:09:38.965  1751  1751 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-13 16:09:38.972  1751  2426 I iu.UploadsManager: num queued entries: 0
,09-13 16:09:38.972  1751  2426 I iu.UploadsManager: num updated entries: 0
09-13 16:09:38.973  1751  2426 I iu.SyncManager: NEXT; no task
,09-13 16:09:38.977  1751  3932 I SystemUpdateService: active receiver: enabled
,09-13 16:09:38.978  1751  1751 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 16:09:38.984  1751  1751 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 16:09:38.986  1751  3932 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 16:09:38.988  1751  3932 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-13 16:09:38.988  1751  3932 I SystemUpdateService: now status is 0 (complete)
,09-13 16:09:38.988  1751  3932 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 16:09:38.988  1751  3932 I SystemUpdateService: file has been verified
09-13 16:09:38.988  1751  3932 I SystemUpdateService: OTA package size = 12249756
,09-13 16:09:38.993  1751  3932 I SystemUpdateService: showing system update notification
,09-13 16:09:39.005   874  2164 I ActivityManager: Start proc 3934:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-13 16:09:39.015  1751  1751 D SystemUpdateService: onDestroy
,09-13 16:09:39.017   874   884 I ActivityManager: Killing 3554:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-13 16:09:39.089  3934  3934 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-13 16:09:39.093  3934  3934 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 16:09:39.101  3934  3934 D SprintDMHelper: simOperator: 
09-13 16:09:39.101  3934  3934 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 16:09:39.136   874  2165 I ActivityManager: Start proc 3946:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-13 16:09:39.137   874  2165 I ActivityManager: Killing 3400:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-13 16:09:39.163  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 16:09:39.227  3815  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:39.234   874   885 D WifiService: setWifiEnabled: true pid=3815, uid=10000
,09-13 16:09:39.234   874   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 16:09:39.255   874  1952 I ActivityManager: Start proc 3963:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-13 16:09:39.257   874  1308 D WifiConfigStore: Loading config and enabling all networks 
09-13 16:09:39.271  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:39.271  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:39.271  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:39.271  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:39.271  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:39.271  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:39.271  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:39.271  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 16:09:39.273   874  1308 D WifiConfigStore: loaded 0 passpoint configs
09-13 16:09:39.274   874  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-13 16:09:39.275   874  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-13 16:09:39.275   874  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-13 16:09:39.275   874  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-13 16:09:39.275   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-13 16:09:39.276   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-13 16:09:39.278  3050  3960 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-13 16:09:39.279  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 16:09:39.281   874  2165 I ActivityManager: Killing 3447:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-13 16:09:39.282  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:39.282  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:39.282  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:39.282  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:39.282  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:39.282  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:39.282  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:39.282  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 16:09:39.285  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 16:09:39.288  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:39.288  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:39.288  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:39.288  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:39.288  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:39.288  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:39.288  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:39.288  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 16:09:39.290  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 16:09:39.336   371   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-13 16:09:39.339   371   872 D CommandListener: Setting iface cfg
,09-13 16:09:39.340   874  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-13 16:09:39.340   874  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 16:09:39.349   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 16:09:39.349   874  1307 D WifiNative-HAL: p2pGetDeviceAddress
,09-13 16:09:39.351   874  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-13 16:09:39.357  3963  3963 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-13 16:09:39.360   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 16:09:39.411  3963  3963 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-13 16:09:39.411  3963  3963 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 16:09:39.411  3963  3963 I GAv4    :   adb logcat -s GAv4
,09-13 16:09:39.426  3963  3963 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 16:09:39.431  3963  3963 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 16:09:39.461  3963  3980 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 16:09:39.565  3963  3963 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-13 16:09:39.612  3963  3963 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-13 16:09:39.620  3963  3963 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 67-69)
,09-13 16:09:39.620  3963  3963 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 16:09:39.635  3963  3963 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c845b00}
,09-13 16:09:39.636  3963  3963 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 16:09:39.637  3963  3963 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 16:09:39.646  3963  3963 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-13 16:09:39.648  3963  3963 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-13 16:09:39.665  3963  3963 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-13 16:09:39.680  3963  3963 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 16:09:39.681  3963  3963 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 16:09:39.681  3963  3963 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 16:09:39.681  3963  3963 I Adreno  : Build Date                       : 10/20/15
09-13 16:09:39.681  3963  3963 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 16:09:39.681  3963  3963 I Adreno  : Local Branch                     : M14
09-13 16:09:39.681  3963  3963 I Adreno  : Remote Branch                    : 
09-13 16:09:39.681  3963  3963 I Adreno  : Remote Branch                    : 
09-13 16:09:39.681  3963  3963 I Adreno  : Reconstruct Branch               : 
,09-13 16:09:39.741  3815  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:39.743  3963  3963 I NSApplication: Starting up...
,09-13 16:09:39.753  3963  4009 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-13 16:09:39.786   874  1963 I ActivityManager: Start proc 4015:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
09-13 16:09:39.787   874  1963 I ActivityManager: Killing 3485:android.process.acore/u0a5 (adj 15): empty #17
,09-13 16:09:39.836  2629  2667 D BluetoothAdapterState: Current state: ON, message: 23
,09-13 16:09:39.837  2629  2667 D BluetoothAdapterProperties: Setting state to 13
,09-13 16:09:39.837  2629  2667 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 16:09:39.844  2629  2667 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 16:09:39.850  2629  2629 D BluetoothMapService: onReceive
09-13 16:09:39.850  2629  2629 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:09:39.850  2629  2629 D BluetoothMapService: STATE_TURNING_OFF
09-13 16:09:39.850  2629  2629 D BluetoothMapService: MAP Service closeService in
,09-13 16:09:39.850  2629  2629 D BluetoothMapMasInstance0: MAP Service shutdown
09-13 16:09:39.850  2629  2629 D ObexServerSockets0: shutdown(block = true)
09-13 16:09:39.851  2629  2629 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-13 16:09:39.851  2629  2629 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 16:09:39.851  2629  2787 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-13 16:09:39.852  2629  2788 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-13 16:09:39.852  2629  2757 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-13 16:09:39.854  2629  2629 I BtOppRfcommListener: stopping Accept Thread
,09-13 16:09:39.855  2629  2667 I BluetoothAdapterState: Entering PendingCommandState
09-13 16:09:39.856  2629  2671 D BluetoothAdapterProperties: Scan Mode:20
09-13 16:09:39.856  2629  2667 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-13 16:09:39.858  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 16:09:39.858  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:39.858  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:39.858  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:39.858  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:39.858  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 16:09:39.858  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:39.858  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:39.858  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 16:09:39.858  2629  3413 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 16:09:39.858  2629  3413 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-13 16:09:39.859  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:09:39.859  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 16:09:39.862  2629  2629 D HeadsetService: Received stop request...Stopping profile...
09-13 16:09:39.864   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 16:09:39.864   874   874 D BluetoothHeadset: Proxy object disconnected
,09-13 16:09:39.864  1927  2121 D BluetoothHeadset: Proxy object disconnected
,09-13 16:09:39.865  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 16:09:39.865  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:39.865  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:39.865  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:39.865  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:39.865  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 16:09:39.865  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:39.865  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:39.865  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 16:09:39.865  1361  1374 D BluetoothHeadset: Proxy object disconnected
09-13 16:09:39.865   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 16:09:39.866  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:09:39.866  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 16:09:39.866  2629  2629 D A2dpService: Received stop request...Stopping profile...
,09-13 16:09:39.867  2629  2765 D A2dpStateMachine: Exit Disconnected: -1
09-13 16:09:39.868  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:09:39.868  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:39.868  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:39.868  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:39.868  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:39.868  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 16:09:39.868  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:39.868  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:39.868  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 16:09:39.870  2629  2629 D HidService: Received stop request...Stopping profile...
09-13 16:09:39.870   874   874 D BluetoothA2dp: Proxy object disconnected
09-13 16:09:39.870  2629  2629 D HidService: Stopping Bluetooth HidService
,09-13 16:09:39.870  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 16:09:39.871  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 16:09:39.872  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:39.872  2629  2629 V BluetoothAdapterState: isTurningOff()=true
09-13 16:09:39.872  2629  2629 V BluetoothAdapterState: isTurningOn()=false
09-13 16:09:39.873  2629  2629 V BluetoothAdapterState: isBleTurningOn()=false
09-13 16:09:39.873  2629  2629 V BluetoothAdapterState: isBleTurningOff()=false
09-13 16:09:39.873  2629  2629 D HealthService: Received stop request...Stopping profile...
09-13 16:09:39.874  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:39.875  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:39.875  2629  2629 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 16:09:39.876  2629  2671 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-13 16:09:39.876  2629  2717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 16:09:39.876  2629  2629 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 16:09:39.876  2629  2717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 16:09:39.876  2629  2717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 16:09:39.876  2629  2671 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-13 16:09:39.877  2629  2629 D PanService: Received stop request...Stopping profile...
09-13 16:09:39.879  2629  2629 D BluetoothMapService: Received stop request...Stopping profile...
09-13 16:09:39.879  2629  2629 D BluetoothMapService: stop()
09-13 16:09:39.880  2629  2629 D BluetoothMapAppObserver: deinitObservers()
09-13 16:09:39.880  2629  2629 D BluetoothMapAppObserver: removeReceiver()
,09-13 16:09:39.884  2629  2629 V BluetoothAdapterState: isTurningOff()=true
,09-13 16:09:39.884  2629  2629 V BluetoothAdapterState: isTurningOn()=false
,09-13 16:09:39.884  2629  2629 V BluetoothAdapterState: isBleTurningOn()=false
09-13 16:09:39.884  2629  2629 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 16:09:39.885  2629  2629 V BluetoothAdapterState: isTurningOff()=true
09-13 16:09:39.885  2629  2629 V BluetoothAdapterState: isTurningOn()=false
09-13 16:09:39.885  2629  2629 V BluetoothAdapterState: isBleTurningOn()=false
09-13 16:09:39.885  2629  2629 V BluetoothAdapterState: isBleTurningOff()=false
09-13 16:09:39.886  2629  2629 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-13 16:09:39.886  2629  2629 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 16:09:39.886  2629  2629 V BluetoothAdapterState: isTurningOff()=true
09-13 16:09:39.886  2629  2629 V BluetoothAdapterState: isTurningOn()=false
09-13 16:09:39.886  2629  2629 V BluetoothAdapterState: isBleTurningOn()=false
09-13 16:09:39.886  2629  2629 V BluetoothAdapterState: isBleTurningOff()=false
09-13 16:09:39.886  2629  2629 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 16:09:39.886  2629  2671 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 16:09:39.886  2629  2717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 16:09:39.886  2629  2671 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 16:09:39.887  2629  2717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 16:09:39.887  2629  2671 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-13 16:09:39.887  2629  2717 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 16:09:39.887  2629  2717 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 16:09:39.887  1361  1361 D HeadsetProfile: Bluetooth service disconnected
09-13 16:09:39.887  2629  2717 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 16:09:39.887  2629  2717 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 16:09:39.887  1361  1361 D BluetoothA2dp: Proxy object disconnected
,09-13 16:09:39.887  1361  1361 D BluetoothInputDevice: Proxy object disconnected
09-13 16:09:39.887  1361  1361 D HidProfile: Bluetooth service disconnected
09-13 16:09:39.887  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 16:09:39.888  1361  1361 D PanProfile: Bluetooth service disconnected
09-13 16:09:39.888  1361  1361 D BluetoothMap: Proxy object disconnected
09-13 16:09:39.888  1361  1361 D MapProfile: Bluetooth service disconnected
,09-13 16:09:39.889  2629  2629 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-13 16:09:39.889  2629  2629 V BluetoothAdapterState: isTurningOff()=true
,09-13 16:09:39.889  2629  2629 V BluetoothAdapterState: isTurningOn()=false
,09-13 16:09:39.889  2629  2629 V BluetoothAdapterState: isBleTurningOn()=false
09-13 16:09:39.889  2629  2629 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 16:09:39.892  4015  4015 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
09-13 16:09:39.891  2629  2629 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 16:09:39.892  2629  2629 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 16:09:39.893  2629  2629 D BluetoothMapService: MAP Service closeService in
09-13 16:09:39.893  2629  2629 V BluetoothAdapterState: isTurningOff()=true
,09-13 16:09:39.893  2629  2629 V BluetoothAdapterState: isTurningOn()=false
09-13 16:09:39.893  2629  2629 V BluetoothAdapterState: isBleTurningOn()=false
09-13 16:09:39.893  2629  2629 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 16:09:39.894  2629  2667 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-13 16:09:39.894  2629  2667 D BluetoothAdapterProperties: Setting state to 15
,09-13 16:09:39.894  2629  2667 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-13 16:09:39.894  2629  2629 D BluetoothMapService: cleanup()
09-13 16:09:39.894  2629  2629 D BluetoothMapService: MAP Service closeService in
09-13 16:09:39.894  2629  2667 I BluetoothAdapterState: Entering BleOnState
09-13 16:09:39.894  1361  1374 D BluetoothInputDevice: onBluetoothStateChange: up=false,
09-13 16:09:39.895   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 16:09:39.895  1361  2063 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 16:09:39.895   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-13 16:09:39.895  1361  3814 D BluetoothMap: onBluetoothStateChange: up=false
09-13 16:09:39.896   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 16:09:39.896  1361  1381 D BluetoothPan: onBluetoothStateChange on: false
09-13 16:09:39.897   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 16:09:39.897  1361  1374 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 16:09:39.898  1361  2063 D BluetoothPbap: onBluetoothStateChange: up=false
,09-13 16:09:39.900  1927  1938 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 16:09:39.901  2629  2667 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-13 16:09:39.901  2629  2667 D BluetoothAdapterProperties: Setting state to 16
09-13 16:09:39.901  2629  2667 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-13 16:09:39.901  2629  2667 D BluetoothAdapterProperties: onBleDisable
09-13 16:09:39.902  2629  2668 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-13 16:09:39.903  2629  2671 D BluetoothAdapterProperties: Scan Mode:20
09-13 16:09:39.903  2629  2717 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-13 16:09:39.903  2629  2717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 16:09:39.903  2629  2667 I BluetoothAdapterState: Entering PendingCommandState
09-13 16:09:39.905  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:39.906  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:39.907  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:39.908  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:39.911  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:39.912  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:40.099   874   884 I ActivityManager: Killing 3645:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-13 16:09:40.107  2629  2671 I bt_hci  : shut_down
,09-13 16:09:40.107  2629  2675 D bt_hwcfg: hw_epilog_process
09-13 16:09:40.108  2629  2675 I bt_vendor: low_power_mode_cb
,09-13 16:09:40.132  2629  2675 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-13 16:09:40.132  2629  2675 I bt_vendor: epilog_cb
09-13 16:09:40.132  2629  2675 I bt_hci  : epilog_finished_callback
,09-13 16:09:40.141  2629  2671 I bt_hci_h4: hal_close
,09-13 16:09:40.141  2629  2671 I bt_userial_vendor: device fd = 51 close
,09-13 16:09:40.206   874   884 I ActivityManager: Start proc 4032:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-13 16:09:40.257  2629  2668 D bt_stack_manager: event_shut_down_stack finished.
,09-13 16:09:40.259  2629  2667 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-13 16:09:40.261  2629  2667 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-13 16:09:40.261  2629  2629 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 16:09:40.263  2629  2629 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 16:09:40.263  2629  2629 D BtGatt.GattService: stop()
09-13 16:09:40.263  2629  2629 D BtGatt.AdvertiseManager: advertise clients cleared
,09-13 16:09:40.267  2629  2629 V BluetoothAdapterState: isTurningOff()=false
09-13 16:09:40.267  2629  2629 V BluetoothAdapterState: isTurningOn()=false
09-13 16:09:40.267  2629  2629 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 16:09:40.268  2629  2629 V BluetoothAdapterState: isBleTurningOff()=true
09-13 16:09:40.268  2629  2667 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-13 16:09:40.268  2629  2667 D BluetoothAdapterProperties: Setting state to 10
09-13 16:09:40.268  2629  2667 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-13 16:09:40.269  2629  2667 I BluetoothAdapterState: Entering OffState
09-13 16:09:40.269   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,09-13 16:09:40.280  4032  4032 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-13 16:09:40.283  2629  2629 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-13 16:09:40.284  2629  2629 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-13 16:09:40.284  2629  2668 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-13 16:09:40.286  2629  2668 D bt_stack_manager: event_clean_up_stack finished.
09-13 16:09:40.286  2629  2629 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-13 16:09:40.295  2629  2629 I art     : System.exit called, status: 0
09-13 16:09:40.295  2629  2629 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 16:09:40.307  4032  4032 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 16:09:40.315   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ca92530:true
,09-13 16:09:40.341  4032  4032 D LocalBluetoothProfileManager: Adding local MAP profile
,09-13 16:09:40.341  3815  4014 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:40.346  4032  4032 D BluetoothMap: Create BluetoothMap proxy object
,09-13 16:09:40.351   874  1957 I ActivityManager: Process com.android.bluetooth (pid 2629) has died
,09-13 16:09:40.351   874  1957 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.pbap.BluetoothPbapService in 1000ms
,09-13 16:09:40.356  1543  1543 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 16:09:40.399   874   891 I ActivityManager: Start proc 4046:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-13 16:09:40.400  4032  4032 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-13 16:09:40.429  4032  4032 D DockEventReceiver: finishStartingService: stopping service
,09-13 16:09:40.436   874   884 I ActivityManager: Killing 3663:com.android.musicfx/u0a18 (adj 15): empty #17
,09-13 16:09:40.479  4046  4046 D AdapterServiceConfig: Adding HeadsetService
,09-13 16:09:40.480  4046  4046 D AdapterServiceConfig: Adding A2dpService
09-13 16:09:40.480  4046  4046 D AdapterServiceConfig: Adding HidService
09-13 16:09:40.480  4046  4046 D AdapterServiceConfig: Adding HealthService
09-13 16:09:40.480  4046  4046 D AdapterServiceConfig: Adding PanService
,09-13 16:09:40.481  4046  4046 D AdapterServiceConfig: Adding GattService
09-13 16:09:40.481  4046  4046 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 16:09:40.495  4046  4046 D BluetoothAdapterState: make() - Creating AdapterState
09-13 16:09:40.495   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4c3a6db:true
,09-13 16:09:40.498  4046  4046 I bt_bluedroid: init
,09-13 16:09:40.498  4046  4061 I BluetoothAdapterState: Entering OffState
,09-13 16:09:40.500  4046  4062 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-13 16:09:40.501  4046  4062 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-13 16:09:40.501  4046  4062 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-13 16:09:40.501  4046  4062 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-13 16:09:40.501  4046  4046 I bt_bluedroid: get_profile_interface socket
,09-13 16:09:40.502  4046  4046 I bt_bluedroid: get_profile_interface sdp
,09-13 16:09:40.506  4046  4058 I bt_bluedroid: config_hci_snoop_log
,09-13 16:09:40.508   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-13 16:09:40.509  4046  4065 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-13 16:09:40.515  4046  4061 D BluetoothAdapterState: Current state: OFF, message: 0
,09-13 16:09:40.543   874  2165 I ActivityManager: Start proc 4066:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-13 16:09:40.544  4046  4065 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 16:09:40.545  4046  4061 D BluetoothAdapterProperties: Setting state to 14
,09-13 16:09:40.545  4046  4061 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-13 16:09:40.550  4046  4061 D BluetoothBondStateMachine: make
,09-13 16:09:40.555  4046  4071 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 16:09:40.558  4046  4061 I BluetoothAdapterState: Entering PendingCommandState
,09-13 16:09:40.561  4046  4046 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-13 16:09:40.569  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d682636
,09-13 16:09:40.573  4046  4046 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 16:09:40.574  4046  4046 D BtGatt.GattService: Received start request. Starting profile...
,09-13 16:09:40.574  4046  4046 D BtGatt.GattService: start()
09-13 16:09:40.575  4046  4046 I bt_bluedroid: get_profile_interface gatt
,09-13 16:09:40.577  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d682636
,09-13 16:09:40.577  4046  4046 D BtGatt.AdvertiseManager: advertise manager created
,09-13 16:09:40.591  4046  4046 V BluetoothAdapterState: isTurningOff()=false
,09-13 16:09:40.591  4046  4046 V BluetoothAdapterState: isTurningOn()=false
09-13 16:09:40.592  4046  4046 V BluetoothAdapterState: isBleTurningOn()=true
09-13 16:09:40.592  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 16:09:40.592  4066  4066 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
09-13 16:09:40.593  4046  4061 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-13 16:09:40.593  4046  4061 I bt_bluedroid: enable
09-13 16:09:40.593  4046  4062 D bt_stack_manager: event_start_up_stack is bringing up the stack.,
09-13 16:09:40.593  4046  4062 I bt_hci  : start_up
,09-13 16:09:40.600  4046  4062 I bt_vendor: alloc value 0xb3a71189
,09-13 16:09:40.600  4046  4062 I bt_vendor: init
09-13 16:09:40.600  4046  4062 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-13 16:09:40.600  4046  4062 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 16:09:40.709  4046  4062 D bt_hci  : start_up starting async portion
,09-13 16:09:40.710  4046  4081 I bt_hci  : event_finish_startup
,09-13 16:09:40.710  4046  4081 I bt_hci_h4: hal_open
09-13 16:09:40.710  4046  4081 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-13 16:09:40.716  4046  4081 I bt_userial_vendor: device fd = 51 open
,09-13 16:09:40.738  4066  4066 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 16:09:40.738  4066  4066 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 16:09:40.738  4066  4066 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 16:09:40.738  4066  4066 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 16:09:40.738  4066  4066 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.r.k.d(PG:583)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 16:09:40.738  4066  4066 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 16:09:40.738  4066  4066 D StrictMode: StrictMode policy violation; ~duration=57 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 16:09:40.738  4066  4066 D StrictMode: StrictMode policy violation; ~duration=57 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 16:09:40.738  4066  4066 D StrictMode: 	,at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 16:09:40.738  4066  4066 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 16:09:40.743  4032  4032 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 16:09:40.753  4046  4081 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 16:09:40.753  1543  1543 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 16:09:40.759  4032  4032 D DockEventReceiver: finishStartingService: stopping service
,09-13 16:09:40.782  4046  4081 D bt_hwcfg: Chipset BCM4354A2
,09-13 16:09:40.782  4046  4081 D bt_hwcfg: Target name = [BCM4354A2]
09-13 16:09:40.783  4046  4081 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-13 16:09:40.837   874  1383 I ActivityManager: Killing 2242:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-13 16:09:40.898  4046  4061 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-13 16:09:41.030  4066  4087 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-13 16:09:41.048   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e45eb54:true
,09-13 16:09:41.257  4046  4081 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-13 16:09:41.258  4046  4081 D bt_hwcfg: Settlement delay -- 100 ms
,09-13 16:09:41.258  4046  4081 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 16:09:41.375  4046  4081 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 16:09:41.376  4046  4081 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 16:09:41.406  4046  4081 I bt_hwcfg: vendor lib fwcfg completed
09-13 16:09:41.406  4046  4081 I bt_vendor: firmware callback
,09-13 16:09:41.406  4046  4081 I bt_hci  : firmware_config_callback
,09-13 16:09:41.409  4046  4061 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-13 16:09:41.418  4046  4105 I bt_btu  : btu_task pending for preload complete event
,09-13 16:09:41.419  4046  4105 I bt_btu_task: Bluetooth chip preload is complete
09-13 16:09:41.419  4046  4105 I bt_btu  : btu_task received preload complete event
,09-13 16:09:41.429  4046  4105 I         : BTE_InitTraceLevels -- TRC_HCI
,09-13 16:09:41.429  4046  4105 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 16:09:41.429  4046  4105 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-13 16:09:41.430  4046  4105 I         : BTE_InitTraceLevels -- TRC_AVDT
09-13 16:09:41.430  4046  4105 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 16:09:41.430  4046  4105 I         : BTE_InitTraceLevels -- TRC_A2D
,09-13 16:09:41.430  4046  4105 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 16:09:41.431  4046  4105 I         : BTE_InitTraceLevels -- TRC_BTM
09-13 16:09:41.431  4046  4105 I         : BTE_InitTraceLevels -- TRC_GAP
,09-13 16:09:41.431  4046  4105 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 16:09:41.432  4046  4105 I         : BTE_InitTraceLevels -- TRC_SDP
,09-13 16:09:41.432  4046  4105 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 16:09:41.432  4046  4105 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 16:09:41.432  4046  4105 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-13 16:09:41.433  4046  4105 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 16:09:41.574  4046  4105 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39eed9d
,09-13 16:09:41.574  4046  4105 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39eed9d 
,09-13 16:09:41.586  4046  4065 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-13 16:09:41.587  4046  4065 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 16:09:41.587  4046  4065 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 16:09:41.589  4046  4065 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 16:09:41.592  4046  4065 D BluetoothAdapterProperties: Scan Mode:20
,09-13 16:09:41.592  4046  4065 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 16:09:41.592  4046  4065 D bt_hci  : do_postload posting postload work item
09-13 16:09:41.593  4046  4081 I bt_hci  : event_postload
,09-13 16:09:41.593  4046  4081 I bt_vendor: sco_config_cb
09-13 16:09:41.594  4046  4081 I bt_hci  : sco_config_callback postload finished.
09-13 16:09:41.596  4046  4065 D bt_bte_conf: Device ID record 1 : primary
,09-13 16:09:41.596  4046  4065 D bt_bte_conf:   vendorId            = 000f
09-13 16:09:41.596  4046  4065 D bt_bte_conf:   vendorIdSource      = 0001
,09-13 16:09:41.596  4046  4065 D bt_bte_conf:   product             = 1200
09-13 16:09:41.596  4046  4065 D bt_bte_conf:   version             = 1436
,09-13 16:09:41.596  4046  4065 D bt_bte_conf:   clientExecutableURL = 
,09-13 16:09:41.597  4046  4065 D bt_bte_conf:   serviceDescription  = 
,09-13 16:09:41.597  4046  4065 D bt_bte_conf:   documentationURL    = 
,09-13 16:09:41.597  4046  4065 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-13 16:09:41.598  4046  4062 D bt_stack_manager: event_start_up_stack finished
09-13 16:09:41.600  4046  4061 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-13 16:09:41.600  4046  4061 D BluetoothAdapterProperties: Setting state to 15
,09-13 16:09:41.601  4046  4061 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-13 16:09:41.604  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:41.602  4046  4061 I BluetoothAdapterState: Entering BleOnState
09-13 16:09:41.608  4046  4081 I bt_vendor: low_power_mode_cb
09-13 16:09:41.609  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:41.610  4046  4061 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-13 16:09:41.611  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:41.611  4046  4061 D BluetoothAdapterProperties: Setting state to 11
,09-13 16:09:41.611  4046  4061 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-13 16:09:41.617  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d682636
09-13 16:09:41.619  4046  4046 D HeadsetService: Received start request. Starting profile...
09-13 16:09:41.621  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:41.622  4046  4046 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 16:09:41.623  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:41.623  4046  4046 D HeadsetStateMachine: make
09-13 16:09:41.624  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:41.634  4046  4061 I BluetoothAdapterState: Entering PendingCommandState
,09-13 16:09:41.635  4046  4046 D HeadsetStateMachine: max_hf_connections = 1
,09-13 16:09:41.635  4046  4046 I bt_bluedroid: get_profile_interface handsfree
09-13 16:09:41.635  4046  4065 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-13 16:09:41.635  4046  4065 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-13 16:09:41.639  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d682636
,09-13 16:09:41.640  4046  4046 D A2dpService: Received start request. Starting profile...
,09-13 16:09:41.641  4046  4046 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-13 16:09:41.641  4046  4046 I bt_bluedroid: get_profile_interface avrcp
,09-13 16:09:41.648  4046  4046 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-13 16:09:41.648  4046  4046 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 16:09:41.648  4046  4046 D A2dpStateMachine: make
,09-13 16:09:41.649  4046  4046 I bt_bluedroid: get_profile_interface a2dp
,09-13 16:09:41.650  4046  4065 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-13 16:09:41.652  4046  4115 D A2dpStateMachine: Enter Disconnected: -2
,09-13 16:09:41.654  4046  4046 I BluetoothHidServiceJni: classInitNative: succeeds
,09-13 16:09:41.655  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d682636
,09-13 16:09:41.655  1543  1543 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
,09-13 16:09:41.661  4032  4032 D BluetoothInputDevice: Proxy object connected
,09-13 16:09:41.662  4032  4032 D HidProfile: Bluetooth service connected
09-13 16:09:41.662  4046  4046 D HidService: Received start request. Starting profile...
09-13 16:09:41.663  4046  4046 I bt_bluedroid: get_profile_interface hidhost
09-13 16:09:41.663  4046  4065 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39d03e5
,09-13 16:09:41.663  4046  4065 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-13 16:09:41.664  4046  4046 D HidService: setHidService(): set to: null
,09-13 16:09:41.664  4046  4046 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-13 16:09:41.666  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d682636
,09-13 16:09:41.666  4046  4046 D HealthService: Received start request. Starting profile...
,09-13 16:09:41.667  4046  4046 I bt_bluedroid: get_profile_interface health
,09-13 16:09:41.668  4046  4046 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-13 16:09:41.669  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d682636
,09-13 16:09:41.670  4046  4046 D PanService: Received start request. Starting profile...
09-13 16:09:41.670  4032  4032 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 16:09:41.670  4046  4046 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-13 16:09:41.670  4046  4046 I bt_bluedroid: get_profile_interface pan
09-13 16:09:41.671  4046  4065 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-13 16:09:41.671  4032  4032 D PanProfile: Bluetooth service connected
,09-13 16:09:41.674  4046  4046 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d682636
,09-13 16:09:41.676  4032  4032 D BluetoothMap: Proxy object connected
,09-13 16:09:41.676  4046  4046 D BluetoothMapService: Received start request. Starting profile...
09-13 16:09:41.676  4046  4046 D BluetoothMapService: start()
,09-13 16:09:41.676  4032  4032 D MapProfile: Bluetooth service connected
09-13 16:09:41.677  4032  4032 D BluetoothMap: getConnectedDevices()
,09-13 16:09:41.677  4032  4032 D BluetoothMap: Bluetooth is Not enabled
09-13 16:09:41.678  4046  4046 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-13 16:09:41.679  4046  4046 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-13 16:09:41.679  4046  4046 D BluetoothMapAppObserver: createReceiver()
,09-13 16:09:41.680  4046  4046 D BluetoothMapAppObserver: initObservers()
,09-13 16:09:41.680  4046  4046 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-13 16:09:41.686  4046  4046 V BluetoothAdapterState: isTurningOff()=false
,09-13 16:09:41.686  4046  4046 V BluetoothAdapterState: isTurningOn()=true
09-13 16:09:41.686  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
09-13 16:09:41.686  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 16:09:41.688  4046  4113 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-13 16:09:41.688  4046  4046 V BluetoothAdapterState: isTurningOff()=false
09-13 16:09:41.689  4046  4046 V BluetoothAdapterState: isTurningOn()=true
09-13 16:09:41.689  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
09-13 16:09:41.689  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
09-13 16:09:41.689  4046  4046 V BluetoothAdapterState: isTurningOff()=false
,09-13 16:09:41.689  4046  4046 V BluetoothAdapterState: isTurningOn()=true
09-13 16:09:41.689  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
09-13 16:09:41.689  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
09-13 16:09:41.689  4046  4046 V BluetoothAdapterState: isTurningOff()=false
,09-13 16:09:41.689  4046  4046 V BluetoothAdapterState: isTurningOn()=true
09-13 16:09:41.689  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
09-13 16:09:41.690  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
09-13 16:09:41.690  4046  4046 V BluetoothAdapterState: isTurningOff()=false
,09-13 16:09:41.690  4046  4046 V BluetoothAdapterState: isTurningOn()=true
,09-13 16:09:41.690  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
09-13 16:09:41.690  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
09-13 16:09:41.690  4046  4046 V BluetoothAdapterState: isTurningOff()=false
09-13 16:09:41.690  4046  4046 V BluetoothAdapterState: isTurningOn()=true
09-13 16:09:41.690  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
09-13 16:09:41.690  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
09-13 16:09:41.691  4046  4061 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-13 16:09:41.691  4046  4061 D BluetoothAdapterProperties: ScanMode =  20
,09-13 16:09:41.691  4046  4061 D BluetoothAdapterProperties: State =  11
09-13 16:09:41.693  4046  4061 D BluetoothAdapterProperties: Setting state to 12
09-13 16:09:41.694  4046  4061 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 16:09:41.694  4046  4061 I BluetoothAdapterState: Entering OnState
09-13 16:09:41.694  4032  4043 D BluetoothPan: onBluetoothStateChange on: true
09-13 16:09:41.694  4046  4065 D BluetoothAdapterProperties: Scan Mode:21
09-13 16:09:41.695  4046  4065 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 16:09:41.695  4032  4042 D BluetoothMap: onBluetoothStateChange: up=true
09-13 16:09:41.695  1361  1374 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 16:09:41.698  3815  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-13 16:09:41.699  1361  1361 D BluetoothInputDevice: Proxy object connected
,09-13 16:09:41.699  1361  1361 D HidProfile: Bluetooth service connected
,09-13 16:09:41.700  4032  4043 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 16:09:41.701  4032  4042 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 16:09:41.702  3815  3815 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-13 16:09:41.703   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 16:09:41.703  1361  3814 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 16:09:41.704   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 16:09:41.705  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:41.705  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:41.705  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:41.705  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:41.705  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:41.705  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:41.705  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:41.705  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 16:09:41.705  1361  1381 D BluetoothMap: onBluetoothStateChange: up=true
09-13 16:09:41.706   874   874 D BluetoothA2dp: Proxy object connected
,09-13 16:09:41.711  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 16:09:41.715  4046  4046 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-13 16:09:41.715  4046  4046 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-13 16:09:41.716  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:41.716  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:41.716  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:41.716  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:41.716  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:41.716  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:41.716  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:41.716  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 16:09:41.717  4046  4046 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:09:41.718  1361  1361 D BluetoothMap: Proxy object connected
09-13 16:09:41.718  1361  1361 D MapProfile: Bluetooth service connected
09-13 16:09:41.718  1361  1361 D BluetoothMap: getConnectedDevices()
09-13 16:09:41.718  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 16:09:41.719   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 16:09:41.719  1361  1374 D BluetoothPan: onBluetoothStateChange on: true
09-13 16:09:41.721  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 16:09:41.721  1361  1361 D PanProfile: Bluetooth service connected
09-13 16:09:41.721   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 16:09:41.721  1361  2063 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 16:09:41.723  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:41.723  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:41.723  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:41.723  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:41.723  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:41.723  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:41.723  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:41.723  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 16:09:41.723  1361  1361 D BluetoothA2dp: Proxy object connected
09-13 16:09:41.724  1361  3814 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 16:09:41.724  4046  4046 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:09:41.725  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 16:09:41.726  4046  4046 D ObexServerSockets: Succeed to create listening sockets 
,09-13 16:09:41.726  4046  4046 D ObexServerSockets0: startAccept()
09-13 16:09:41.726  1927  1938 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 16:09:41.726  4046  4046 D ObexServerSockets0: prepareForNewConnect()
09-13 16:09:41.728   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-13 16:09:41.730  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:41.731  4046  4046 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-13 16:09:41.731  4046  4046 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-13 16:09:41.731  4046  4046 D BluetoothMapService: onReceive
09-13 16:09:41.731  4046  4046 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:09:41.732  4046  4046 D BluetoothMapService: STATE_ON
09-13 16:09:41.732  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:41.733  4032  4032 D LocalBluetoothProfileManager: Adding local A2DP profile
09-13 16:09:41.733  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:41.734  4046  4120 D ObexServerSockets0: Accepting socket connection...
09-13 16:09:41.734  4046  4122 D ObexServerSockets0: Accepting socket connection...
,09-13 16:09:41.742  4032  4032 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-13 16:09:41.749  4032  4032 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 16:09:41.751  4032  4032 D BluetoothA2dp: Proxy object connected
,09-13 16:09:41.752  4046  4046 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 16:09:41.752  4046  4046 D ObexServerSockets0: prepareForNewConnect()
,09-13 16:09:41.755  1543  1543 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 16:09:41.758  4032  4032 D DockEventReceiver: finishStartingService: stopping service
,09-13 16:09:41.768  1361  1361 D BluetoothPbap: Proxy object connected
,09-13 16:09:41.768  1361  1361 D PbapServerProfile: Bluetooth service connected
09-13 16:09:41.768  4032  4032 D BluetoothPbap: Proxy object connected
,09-13 16:09:41.768  4032  4032 D PbapServerProfile: Bluetooth service connected
,09-13 16:09:41.780  4046  4126 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:09:41.793  4046  4130 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:09:41.794  4046  4130 I BtOppRfcommListener: Accept thread started.
,09-13 16:09:41.804   874   874 D BluetoothHeadset: Proxy object connected
09-13 16:09:41.804   874   874 D BluetoothHeadset: Proxy object connected
09-13 16:09:41.804  1927  2122 D BluetoothHeadset: Proxy object connected
,09-13 16:09:41.804  1361  1381 D BluetoothHeadset: Proxy object connected
09-13 16:09:41.804  1361  1361 D HeadsetProfile: Bluetooth service connected
09-13 16:09:41.804  1361  2063 D BluetoothHeadset: Proxy object connected
09-13 16:09:41.805   874   874 D BluetoothHeadset: Proxy object connected
,09-13 16:09:41.806  1361  1361 D HeadsetProfile: Bluetooth service connected
,09-13 16:09:41.819   874   891 D BluetoothHeadset: Proxy object connected
,09-13 16:09:41.822   874   891 D BluetoothHeadset: Proxy object connected
,09-13 16:09:41.827  1927  1943 D BluetoothHeadset: Proxy object connected
,09-13 16:09:41.845  4032  4043 D BluetoothHeadset: Proxy object connected
,09-13 16:09:41.845  4032  4032 D HeadsetProfile: Bluetooth service connected
,09-13 16:09:41.912  3815  4045 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:41.917  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:09:41.918  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:09:41.940  4046  4061 D BluetoothAdapterState: Current state: ON, message: 23
,09-13 16:09:41.941  4046  4061 D BluetoothAdapterProperties: Setting state to 13
,09-13 16:09:41.941  4046  4061 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-13 16:09:41.944  4046  4061 D BluetoothAdapterProperties: onBluetoothDisable()
,09-13 16:09:41.948  4046  4061 I BluetoothAdapterState: Entering PendingCommandState
09-13 16:09:41.953  4046  4046 D BluetoothMapService: onReceive
09-13 16:09:41.953  4046  4046 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:09:41.954  4046  4046 D BluetoothMapService: STATE_TURNING_OFF
,09-13 16:09:41.954  4046  4046 D BluetoothMapService: MAP Service closeService in
09-13 16:09:41.954  4046  4046 D BluetoothMapMasInstance0: MAP Service shutdown
09-13 16:09:41.955  4046  4046 D ObexServerSockets0: shutdown(block = true)
09-13 16:09:41.956  4046  4120 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-13 16:09:41.959  4046  4046 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-13 16:09:41.960  4046  4122 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-13 16:09:41.961  4046  4107 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-13 16:09:41.961  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:09:41.962  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:41.962  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:41.962  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:41.962  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:41.962  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 16:09:41.962  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:41.962  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:41.962  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 16:09:41.964  4046  4065 D BluetoothAdapterProperties: Scan Mode:20
,09-13 16:09:41.964  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:09:41.964  4046  4061 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-13 16:09:41.964  4046  4046 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 16:09:41.965  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 16:09:41.965  4046  4046 I BtOppRfcommListener: stopping Accept Thread
09-13 16:09:41.967  4046  4130 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 16:09:41.967  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 16:09:41.967  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:41.967  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:41.967  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:41.967  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:41.967  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 16:09:41.967  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:41.967  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:41.967  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 16:09:41.968  3815  3815 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:09:41.968  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 16:09:41.968  4046  4130 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 16:09:41.972  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:41.974  4032  4032 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 16:09:41.974  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:41.974  4046  4046 D HeadsetService: Received stop request...Stopping profile...
09-13 16:09:41.981   874   874 D BluetoothHeadset: Proxy object disconnected
,09-13 16:09:41.981   874   874 D BluetoothHeadset: Proxy object disconnected
09-13 16:09:41.981  1927  2121 D BluetoothHeadset: Proxy object disconnected
09-13 16:09:41.982  4032  4042 D BluetoothHeadset: Proxy object disconnected
09-13 16:09:41.982  4046  4046 D A2dpService: Received stop request...Stopping profile...
,09-13 16:09:41.982  4046  4115 D A2dpStateMachine: Exit Disconnected: -1
09-13 16:09:41.983  1361  2063 D BluetoothHeadset: Proxy object disconnected
09-13 16:09:41.983  1361  1361 D HeadsetProfile: Bluetooth service disconnected
09-13 16:09:41.983   874   874 D BluetoothHeadset: Proxy object disconnected
,09-13 16:09:41.984   874   874 D BluetoothA2dp: Proxy object disconnected
09-13 16:09:41.985  1361  1361 D BluetoothA2dp: Proxy object disconnected
,09-13 16:09:41.985  4046  4046 D HidService: Received stop request...Stopping profile...
09-13 16:09:41.985  4046  4046 D HidService: Stopping Bluetooth HidService
,09-13 16:09:41.986  1361  1361 D BluetoothInputDevice: Proxy object disconnected
09-13 16:09:41.986  1361  1361 D HidProfile: Bluetooth service disconnected
,09-13 16:09:41.987  4046  4046 D HealthService: Received stop request...Stopping profile...
,09-13 16:09:41.989  4046  4046 D PanService: Received stop request...Stopping profile...
,09-13 16:09:41.990  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 16:09:41.990  1361  1361 D PanProfile: Bluetooth service disconnected
,09-13 16:09:41.991  4046  4046 D BluetoothMapService: Received stop request...Stopping profile...
09-13 16:09:41.991  4046  4046 D BluetoothMapService: stop()
,09-13 16:09:41.991  4032  4032 D DockEventReceiver: finishStartingService: stopping service
09-13 16:09:41.992  4046  4046 D BluetoothMapAppObserver: deinitObservers()
09-13 16:09:41.992  4046  4046 D BluetoothMapAppObserver: removeReceiver()
,09-13 16:09:41.993  1361  1361 D BluetoothMap: Proxy object disconnected
,09-13 16:09:41.993  1361  1361 D MapProfile: Bluetooth service disconnected
09-13 16:09:41.994  4046  4046 V BluetoothAdapterState: isTurningOff()=true
09-13 16:09:41.994  4046  4046 V BluetoothAdapterState: isTurningOn()=false
09-13 16:09:41.994  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 16:09:41.994  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 16:09:41.998  4032  4032 D HeadsetProfile: Bluetooth service disconnected
,09-13 16:09:41.998  1543  1543 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 16:09:41.998  4032  4032 D BluetoothA2dp: Proxy object disconnected
09-13 16:09:41.999  4032  4032 D BluetoothInputDevice: Proxy object disconnected
09-13 16:09:41.999  4032  4032 D HidProfile: Bluetooth service disconnected
,09-13 16:09:41.999  4032  4032 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 16:09:41.999  4032  4032 D PanProfile: Bluetooth service disconnected
09-13 16:09:42.000  4032  4032 D BluetoothMap: Proxy object disconnected
09-13 16:09:42.000  4032  4032 D MapProfile: Bluetooth service disconnected
,09-13 16:09:42.000  4046  4046 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 16:09:42.001  4046  4046 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-13 16:09:42.001  4046  4065 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-13 16:09:42.001  4046  4105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 16:09:42.001  4046  4105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 16:09:42.001  4046  4105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 16:09:42.001  4046  4046 V BluetoothAdapterState: isTurningOff()=true
09-13 16:09:42.001  4046  4046 V BluetoothAdapterState: isTurningOn()=false
09-13 16:09:42.002  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 16:09:42.002  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 16:09:42.003  4046  4065 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
,09-13 16:09:42.003  4046  4065 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-13 16:09:42.003  4046  4105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 16:09:42.003  4046  4046 V BluetoothAdapterState: isTurningOff()=true
09-13 16:09:42.003  4046  4105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 16:09:42.003  4046  4046 V BluetoothAdapterState: isTurningOn()=false
09-13 16:09:42.003  4046  4105 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-13 16:09:42.003  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
09-13 16:09:42.003  4046  4105 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 16:09:42.003  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 16:09:42.003  4046  4105 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 16:09:42.003  4046  4105 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 16:09:42.004  4046  4046 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-13 16:09:42.004  4046  4065 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-13 16:09:42.004  4046  4046 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 16:09:42.004  4046  4046 V BluetoothAdapterState: isTurningOff()=true
,09-13 16:09:42.005  4046  4046 V BluetoothAdapterState: isTurningOn()=false
09-13 16:09:42.005  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
09-13 16:09:42.005  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false,
09-13 16:09:42.005  4046  4046 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 16:09:42.005  4046  4065 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-13 16:09:42.005  4046  4046 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 16:09:42.006  4046  4046 V BluetoothAdapterState: isTurningOff()=true
09-13 16:09:42.006  4046  4046 V BluetoothAdapterState: isTurningOn()=false
09-13 16:09:42.006  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
09-13 16:09:42.006  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 16:09:42.006  4046  4046 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 16:09:42.006  4046  4046 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 16:09:42.007  4046  4046 D BluetoothMapService: MAP Service closeService in
09-13 16:09:42.007  4046  4046 V BluetoothAdapterState: isTurningOff()=true
09-13 16:09:42.007  4046  4046 V BluetoothAdapterState: isTurningOn()=false
09-13 16:09:42.007  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 16:09:42.007  4046  4046 V BluetoothAdapterState: isBleTurningOff()=false
09-13 16:09:42.008  4046  4046 D BluetoothMapService: cleanup()
09-13 16:09:42.008  4046  4046 D BluetoothMapService: MAP Service closeService in
,09-13 16:09:42.008  4046  4061 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-13 16:09:42.008  4046  4061 D BluetoothAdapterProperties: Setting state to 15
09-13 16:09:42.008  4046  4061 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-13 16:09:42.009  4046  4061 I BluetoothAdapterState: Entering BleOnState
09-13 16:09:42.009  4032  4043 D BluetoothPan: onBluetoothStateChange on: false
09-13 16:09:42.010  1361  1361 D BluetoothPbap: Proxy object disconnected
,09-13 16:09:42.010  1361  1361 D PbapServerProfile: Bluetooth service disconnected
09-13 16:09:42.011  4032  4042 D BluetoothMap: onBluetoothStateChange: up=false
09-13 16:09:42.012  4032  4032 D BluetoothPbap: Proxy object disconnected
,09-13 16:09:42.012  4032  4032 D PbapServerProfile: Bluetooth service disconnected
,09-13 16:09:42.013  1361  1374 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-13 16:09:42.016  4032  4043 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 16:09:42.017  4032  4043 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 16:09:42.017  4032  4134 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 16:09:42.017   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 16:09:42.018  1361  1381 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 16:09:42.018   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 16:09:42.018  1361  3814 D BluetoothMap: onBluetoothStateChange: up=false
09-13 16:09:42.018   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-13 16:09:42.019  1361  2063 D BluetoothPan: onBluetoothStateChange on: false
,09-13 16:09:42.019   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 16:09:42.019  1361  1374 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 16:09:42.019  1361  1381 D BluetoothPbap: onBluetoothStateChange: up=false
,09-13 16:09:42.020  4032  4042 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 16:09:42.020  1927  1938 D BluetoothHeadset: onBluetoothStateChange: up=false,
,09-13 16:09:42.020  4046  4061 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-13 16:09:42.021  4046  4061 D BluetoothAdapterProperties: Setting state to 16
,09-13 16:09:42.021  4046  4061 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-13 16:09:42.021  4046  4061 D BluetoothAdapterProperties: onBleDisable
,09-13 16:09:42.022  4046  4061 I BluetoothAdapterState: Entering PendingCommandState
09-13 16:09:42.022  4046  4062 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-13 16:09:42.023  4046  4105 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-13 16:09:42.023  4046  4105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 16:09:42.024  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:42.025  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:42.025  4046  4065 D BluetoothAdapterProperties: Scan Mode:20
,09-13 16:09:42.027  4032  4032 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 16:09:42.027  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:42.028  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:42.037  1543  1543 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 16:09:42.037  4032  4032 D DockEventReceiver: finishStartingService: stopping service
,09-13 16:09:42.087   874  1308 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 9, 10 -> obsolete
,09-13 16:09:42.224  4046  4065 I bt_hci  : shut_down
,09-13 16:09:42.224  4046  4081 I bt_vendor: low_power_mode_cb
09-13 16:09:42.224  4046  4081 D bt_hwcfg: hw_epilog_process
,09-13 16:09:42.248  4046  4081 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-13 16:09:42.248  4046  4081 I bt_vendor: epilog_cb
,09-13 16:09:42.248  4046  4081 I bt_hci  : epilog_finished_callback
09-13 16:09:42.249  4046  4065 I bt_hci_h4: hal_close
,09-13 16:09:42.250  4046  4065 I bt_userial_vendor: device fd = 51 close
,09-13 16:09:42.383  4046  4062 D bt_stack_manager: event_shut_down_stack finished.
09-13 16:09:42.384  4046  4061 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-13 16:09:42.390  4046  4061 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-13 16:09:42.390  4046  4046 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 16:09:42.391  4046  4046 D BtGatt.GattService: Received stop request...Stopping profile...
,09-13 16:09:42.392  4046  4046 D BtGatt.GattService: stop()
09-13 16:09:42.392  4046  4046 D BtGatt.AdvertiseManager: advertise clients cleared
,09-13 16:09:42.396  4046  4046 V BluetoothAdapterState: isTurningOff()=false
,09-13 16:09:42.397  4046  4046 V BluetoothAdapterState: isTurningOn()=false
,09-13 16:09:42.397  4046  4046 V BluetoothAdapterState: isBleTurningOn()=false
09-13 16:09:42.397  4046  4046 V BluetoothAdapterState: isBleTurningOff()=true
09-13 16:09:42.398  4046  4061 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-13 16:09:42.399  4046  4061 D BluetoothAdapterProperties: Setting state to 10
,09-13 16:09:42.399  4046  4061 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-13 16:09:42.402   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-13 16:09:42.403  4046  4061 I BluetoothAdapterState: Entering OffState
,09-13 16:09:42.437  4046  4046 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-13 16:09:42.437  4046  4046 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-13 16:09:42.438  3815  4131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:09:42.438  3815  4131 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:42.438  3815  4131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:42.438  3815  4131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:42.438  3815  4131 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:42.438  3815  4131 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 16:09:42.438  3815  4131 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:42.438  3815  4131 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:42.438  3815  4131 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 16:09:42.438  4046  4062 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-13 16:09:42.438  3815  4131 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 16:09:42.438  3815  4131 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 16:09:42.441  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:42.441  4046  4046 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-13 16:09:42.451  4046  4062 D bt_stack_manager: event_clean_up_stack finished.
,09-13 16:09:42.452  4046  4046 I art     : System.exit called, status: 0
09-13 16:09:42.452  4046  4046 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 16:09:42.542   874  2165 I ActivityManager: Process com.android.bluetooth (pid 4046) has died
,09-13 16:09:42.543   874  2165 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
,09-13 16:09:43.586   874   887 I ActivityManager: Start proc 4138:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-13 16:09:43.725  4138  4138 D AdapterServiceConfig: Adding HeadsetService
,09-13 16:09:43.726  4138  4138 D AdapterServiceConfig: Adding A2dpService
,09-13 16:09:43.727  4138  4138 D AdapterServiceConfig: Adding HidService
,09-13 16:09:43.730  4138  4138 D AdapterServiceConfig: Adding HealthService
,09-13 16:09:43.730  4138  4138 D AdapterServiceConfig: Adding PanService
09-13 16:09:43.731  4138  4138 D AdapterServiceConfig: Adding GattService
09-13 16:09:43.731  4138  4138 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 16:09:43.745  4138  4138 D BluetoothAdapterState: make() - Creating AdapterState
,09-13 16:09:43.745   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@79cec8b:true
,09-13 16:09:43.751  4138  4138 I bt_bluedroid: init
,09-13 16:09:43.752  4138  4150 I BluetoothAdapterState: Entering OffState
,09-13 16:09:43.757  4138  4151 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-13 16:09:43.758  4138  4151 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-13 16:09:43.758  4138  4151 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-13 16:09:43.758  4138  4151 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-13 16:09:43.761  4138  4138 I bt_bluedroid: get_profile_interface socket
,09-13 16:09:43.763  4138  4138 I bt_bluedroid: get_profile_interface sdp
,09-13 16:09:43.766  4138  4154 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 16:09:43.769  4138  4154 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 16:09:43.771  4138  4149 I bt_bluedroid: config_hci_snoop_log
,09-13 16:09:43.775   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-13 16:09:43.786  4138  4150 D BluetoothAdapterState: Current state: OFF, message: 0
,09-13 16:09:43.787  4138  4150 D BluetoothAdapterProperties: Setting state to 14
,09-13 16:09:43.787  4138  4150 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-13 16:09:43.792  4138  4150 D BluetoothBondStateMachine: make
,09-13 16:09:43.796  4138  4155 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 16:09:43.805  4138  4150 I BluetoothAdapterState: Entering PendingCommandState
,09-13 16:09:43.809  4138  4138 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-13 16:09:43.819  4138  4138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d682636
,09-13 16:09:43.820  4138  4138 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 16:09:43.821  4138  4138 D BtGatt.GattService: Received start request. Starting profile...
09-13 16:09:43.821  4138  4138 D BtGatt.GattService: start()
09-13 16:09:43.821  4138  4138 I bt_bluedroid: get_profile_interface gatt
,09-13 16:09:43.822  4138  4138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d682636
09-13 16:09:43.822  4138  4138 D BtGatt.AdvertiseManager: advertise manager created
,09-13 16:09:43.832  4138  4138 V BluetoothAdapterState: isTurningOff()=false
09-13 16:09:43.832  4138  4138 V BluetoothAdapterState: isTurningOn()=false
,09-13 16:09:43.832  4138  4138 V BluetoothAdapterState: isBleTurningOn()=true
09-13 16:09:43.832  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 16:09:43.833  4138  4150 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-13 16:09:43.833  4138  4150 I bt_bluedroid: enable
09-13 16:09:43.834  4138  4151 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-13 16:09:43.835  4138  4151 I bt_hci  : start_up
,09-13 16:09:43.844  4138  4151 I bt_vendor: alloc value 0xb3a71189
,09-13 16:09:43.844  4138  4151 I bt_vendor: init
09-13 16:09:43.845  4138  4151 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-13 16:09:43.845  4138  4151 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 16:09:43.952  4138  4151 D bt_hci  : start_up starting async portion
09-13 16:09:43.953  4138  4158 I bt_hci  : event_finish_startup
09-13 16:09:43.953  4138  4158 I bt_hci_h4: hal_open
09-13 16:09:43.953  4138  4158 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-13 16:09:43.955  4138  4150 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-13 16:09:43.960  4138  4158 I bt_userial_vendor: device fd = 51 open
,09-13 16:09:43.994  4138  4158 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 16:09:44.026  4138  4158 D bt_hwcfg: Chipset BCM4354A2
,09-13 16:09:44.026  4138  4158 D bt_hwcfg: Target name = [BCM4354A2]
,09-13 16:09:44.027  4138  4158 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-13 16:09:44.460  4138  4150 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-13 16:09:44.461  1543  1543 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 16:09:44.472  1543  1543 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 16:09:44.474  1543  1543 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 16:09:44.508  1543  1558 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 16:09:44.508  1543  1558 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-13 16:09:44.508  1543  1558 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 16:09:44.508  1543  1558 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 16:09:44.536  3502  3502 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 16:09:44.536  3502  3502 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 16:09:44.537  3502  3502 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-13 16:09:44.575  4138  4158 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-13 16:09:44.575  4138  4158 D bt_hwcfg: Settlement delay -- 100 ms
09-13 16:09:44.575  4138  4158 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 16:09:44.692  4138  4158 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 16:09:44.693  4138  4158 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 16:09:44.726  4138  4158 I bt_hwcfg: vendor lib fwcfg completed
,09-13 16:09:44.726  4138  4158 I bt_vendor: firmware callback
09-13 16:09:44.726  4138  4158 I bt_hci  : firmware_config_callback
,09-13 16:09:44.739  4138  4162 I bt_btu  : btu_task pending for preload complete event
,09-13 16:09:44.739  4138  4162 I bt_btu_task: Bluetooth chip preload is complete
09-13 16:09:44.740  4138  4162 I bt_btu  : btu_task received preload complete event
,09-13 16:09:44.749  4138  4162 I         : BTE_InitTraceLevels -- TRC_HCI
,09-13 16:09:44.750  4138  4162 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 16:09:44.750  4138  4162 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 16:09:44.750  4138  4162 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-13 16:09:44.751  4138  4162 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 16:09:44.751  4138  4162 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 16:09:44.751  4138  4162 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 16:09:44.752  4138  4162 I         : BTE_InitTraceLevels -- TRC_BTM
,09-13 16:09:44.752  4138  4162 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 16:09:44.752  4138  4162 I         : BTE_InitTraceLevels -- TRC_PAN
,09-13 16:09:44.752  4138  4162 I         : BTE_InitTraceLevels -- TRC_SDP
09-13 16:09:44.753  4138  4162 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 16:09:44.753  4138  4162 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 16:09:44.753  4138  4162 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 16:09:44.753  4138  4162 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 16:09:44.888  4138  4162 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39eed9d
09-13 16:09:44.888  4138  4162 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39eed9d 
09-13 16:09:44.899  4138  4154 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
09-13 16:09:44.902  4138  4154 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 16:09:44.903  4138  4154 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 16:09:44.909  4138  4154 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 16:09:44.910  4138  4154 D BluetoothAdapterProperties: Scan Mode:20
09-13 16:09:44.910  4138  4154 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 16:09:44.911  4138  4154 D bt_hci  : do_postload posting postload work item
09-13 16:09:44.911  4138  4158 I bt_hci  : event_postload
,09-13 16:09:44.911  4138  4158 I bt_vendor: sco_config_cb
,09-13 16:09:44.911  4138  4158 I bt_hci  : sco_config_callback postload finished.
,09-13 16:09:44.912  4138  4154 D bt_bte_conf: Device ID record 1 : primary
09-13 16:09:44.912  4138  4154 D bt_bte_conf:   vendorId            = 000f
,09-13 16:09:44.912  4138  4154 D bt_bte_conf:   vendorIdSource      = 0001
,09-13 16:09:44.912  4138  4154 D bt_bte_conf:   product             = 1200
09-13 16:09:44.912  4138  4154 D bt_bte_conf:   version             = 1436
09-13 16:09:44.913  4138  4154 D bt_bte_conf:   clientExecutableURL = 
09-13 16:09:44.913  4138  4154 D bt_bte_conf:   serviceDescription  = 
09-13 16:09:44.913  4138  4154 D bt_bte_conf:   documentationURL    = 
09-13 16:09:44.913  4138  4154 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-13 16:09:44.914  4138  4151 D bt_stack_manager: event_start_up_stack finished
09-13 16:09:44.914  4138  4150 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-13 16:09:44.914  4138  4150 D BluetoothAdapterProperties: Setting state to 15
09-13 16:09:44.914  4138  4150 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-13 16:09:44.915  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:44.917  4138  4150 I BluetoothAdapterState: Entering BleOnState
09-13 16:09:44.918  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:44.920  4138  4158 I bt_vendor: low_power_mode_cb
,09-13 16:09:44.920  4138  4150 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-13 16:09:44.920  4138  4150 D BluetoothAdapterProperties: Setting state to 11
09-13 16:09:44.920  4138  4150 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-13 16:09:44.925  4138  4138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d682636
,09-13 16:09:44.929  4138  4138 D HeadsetService: Received start request. Starting profile...
09-13 16:09:44.933  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:44.934  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:44.935  4138  4138 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-13 16:09:44.935  4138  4138 D HeadsetStateMachine: make
,09-13 16:09:44.947  4138  4138 D HeadsetStateMachine: max_hf_connections = 1
,09-13 16:09:44.947  4138  4138 I bt_bluedroid: get_profile_interface handsfree
09-13 16:09:44.948  4138  4154 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-13 16:09:44.948  4138  4154 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-13 16:09:44.951  4138  4138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d682636
,09-13 16:09:44.952  4138  4138 D A2dpService: Received start request. Starting profile...
09-13 16:09:44.953  4138  4138 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-13 16:09:44.953  4138  4138 I bt_bluedroid: get_profile_interface avrcp
,09-13 16:09:44.955  4138  4150 I BluetoothAdapterState: Entering PendingCommandState
,09-13 16:09:44.959  4138  4138 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-13 16:09:44.959  4138  4138 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 16:09:44.959  4138  4138 D A2dpStateMachine: make
,09-13 16:09:44.961  4138  4138 I bt_bluedroid: get_profile_interface a2dp
09-13 16:09:44.961  4138  4154 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-13 16:09:44.963  4138  4138 I BluetoothHidServiceJni: classInitNative: succeeds
,09-13 16:09:44.964  4138  4138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d682636
,09-13 16:09:44.964  4138  4138 D HidService: Received start request. Starting profile...
09-13 16:09:44.965  4138  4171 D A2dpStateMachine: Enter Disconnected: -2
09-13 16:09:44.965  4138  4138 I bt_bluedroid: get_profile_interface hidhost
09-13 16:09:44.965  4138  4154 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39d03e5
09-13 16:09:44.965  4138  4154 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-13 16:09:44.965  4138  4150 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
09-13 16:09:44.966  4138  4138 D HidService: setHidService(): set to: null
,09-13 16:09:44.968  4138  4138 I BluetoothHealthServiceJni: classInitNative: succeeds
09-13 16:09:44.969  4138  4138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d682636
09-13 16:09:44.970  1543  1543 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 16:09:44.971  4138  4138 D HealthService: Received start request. Starting profile...
,09-13 16:09:44.973  4138  4138 I bt_bluedroid: get_profile_interface health
09-13 16:09:44.973  4138  4138 V BluetoothAdapterState: isTurningOff()=false
09-13 16:09:44.973  4138  4138 V BluetoothAdapterState: isTurningOn()=true
09-13 16:09:44.973  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
09-13 16:09:44.974  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 16:09:44.975  4138  4138 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-13 16:09:44.976  4138  4138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d682636
,09-13 16:09:44.976  4138  4138 D PanService: Received start request. Starting profile...
,09-13 16:09:44.977  4138  4138 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 16:09:44.977  4138  4138 I bt_bluedroid: get_profile_interface pan
,09-13 16:09:44.978  4138  4154 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 16:09:44.979  4138  4169 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-13 16:09:44.980  4138  4138 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d682636
,09-13 16:09:44.981  4138  4138 D BluetoothMapService: Received start request. Starting profile...
09-13 16:09:44.981  4138  4138 D BluetoothMapService: start()
,09-13 16:09:44.983  4138  4138 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-13 16:09:44.984  4138  4138 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-13 16:09:44.984  4138  4138 D BluetoothMapAppObserver: createReceiver()
09-13 16:09:44.985  4138  4138 D BluetoothMapAppObserver: initObservers()
09-13 16:09:44.985  4138  4138 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-13 16:09:44.991  4138  4138 V BluetoothAdapterState: isTurningOff()=false
09-13 16:09:44.992  4138  4138 V BluetoothAdapterState: isTurningOn()=true
,09-13 16:09:44.992  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
09-13 16:09:44.992  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
09-13 16:09:44.992  4138  4138 V BluetoothAdapterState: isTurningOff()=false
09-13 16:09:44.992  4138  4138 V BluetoothAdapterState: isTurningOn()=true
09-13 16:09:44.992  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
09-13 16:09:44.992  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 16:09:44.994  4138  4138 V BluetoothAdapterState: isTurningOff()=false
,09-13 16:09:44.994  4138  4138 V BluetoothAdapterState: isTurningOn()=true
09-13 16:09:44.994  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
09-13 16:09:44.994  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
09-13 16:09:44.994  4138  4138 V BluetoothAdapterState: isTurningOff()=false
,09-13 16:09:44.994  4138  4138 V BluetoothAdapterState: isTurningOn()=true
09-13 16:09:44.994  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
09-13 16:09:44.994  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 16:09:44.994  4138  4138 V BluetoothAdapterState: isTurningOff()=false
09-13 16:09:44.994  4138  4138 V BluetoothAdapterState: isTurningOn()=true
09-13 16:09:44.995  4138  4138 V BluetoothAdapterState: isBleTurningOn()=false
09-13 16:09:44.995  4138  4138 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 16:09:44.995  4138  4150 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-13 16:09:44.995  4138  4150 D BluetoothAdapterProperties: ScanMode =  20
09-13 16:09:44.995  4138  4150 D BluetoothAdapterProperties: State =  11
,09-13 16:09:44.997  4138  4154 D BluetoothAdapterProperties: Scan Mode:21
09-13 16:09:44.997  4138  4154 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 16:09:44.998  4138  4150 D BluetoothAdapterProperties: Setting state to 12
09-13 16:09:44.998  4138  4150 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-13 16:09:44.998  4138  4150 I BluetoothAdapterState: Entering OnState
09-13 16:09:44.998  4032  4042 D BluetoothPan: onBluetoothStateChange on: true
,09-13 16:09:45.000  4032  4043 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 16:09:45.000  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:45.000  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:45.000  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:45.000  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:45.000  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:45.000  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:45.000  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:45.000  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 16:09:45.001  1361  3814 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 16:09:45.002  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 16:09:45.002  4032  4134 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 16:09:45.003  1361  1361 D BluetoothInputDevice: Proxy object connected
09-13 16:09:45.003  1361  1361 D HidProfile: Bluetooth service connected
,09-13 16:09:45.004  4032  4043 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 16:09:45.005  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:45.005  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:45.005  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:45.005  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:45.005  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:45.005  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:45.005  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:45.005  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 16:09:45.006  4032  4134 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 16:09:45.006   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 16:09:45.007  4032  4032 D BluetoothPan: BluetoothPAN Proxy object connected
,09-13 16:09:45.007  1361  2063 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 16:09:45.007  4032  4032 D PanProfile: Bluetooth service connected
,09-13 16:09:45.007  4032  4032 D BluetoothMap: Proxy object connected
,09-13 16:09:45.007  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 16:09:45.007  4032  4032 D MapProfile: Bluetooth service connected
09-13 16:09:45.007  4032  4032 D BluetoothMap: getConnectedDevices()
09-13 16:09:45.007   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 16:09:45.007   874   874 D BluetoothA2dp: Proxy object connected
09-13 16:09:45.007  1361  1374 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 16:09:45.008  4032  4032 D BluetoothA2dp: Proxy object connected
,09-13 16:09:45.009  1361  1361 D BluetoothMap: Proxy object connected
09-13 16:09:45.009  1361  1361 D MapProfile: Bluetooth service connected
09-13 16:09:45.009   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 16:09:45.009  1361  1361 D BluetoothMap: getConnectedDevices()
09-13 16:09:45.009  1361  1381 D BluetoothPan: onBluetoothStateChange on: true
09-13 16:09:45.010  4032  4032 D BluetoothInputDevice: Proxy object connected
,09-13 16:09:45.010  4032  4032 D HidProfile: Bluetooth service connected
09-13 16:09:45.010  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 16:09:45.010   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 16:09:45.010  1361  1361 D PanProfile: Bluetooth service connected
09-13 16:09:45.010  1361  1374 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 16:09:45.011  4138  4138 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 16:09:45.011  4138  4138 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-13 16:09:45.012  1361  1361 D BluetoothA2dp: Proxy object connected
,09-13 16:09:45.012  1361  3814 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 16:09:45.012  4138  4138 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:09:45.013  4032  4042 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 16:09:45.014  1927  1938 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 16:09:45.014  4138  4138 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:09:45.016   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-13 16:09:45.017  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:45.017  4138  4138 D ObexServerSockets: Succeed to create listening sockets 
,09-13 16:09:45.017  4138  4138 D ObexServerSockets0: startAccept()
09-13 16:09:45.018  4138  4138 D ObexServerSockets0: prepareForNewConnect()
09-13 16:09:45.018  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:45.019  4138  4138 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-13 16:09:45.019  4032  4032 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 16:09:45.020  4138  4138 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-13 16:09:45.020  4138  4138 D BluetoothMapService: onReceive
09-13 16:09:45.020  4138  4138 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 16:09:45.020  4138  4138 D BluetoothMapService: STATE_ON
09-13 16:09:45.021  4138  4177 D ObexServerSockets0: Accepting socket connection...
09-13 16:09:45.021  4138  4178 D ObexServerSockets0: Accepting socket connection...
,09-13 16:09:45.024  1543  1543 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 16:09:45.030  4032  4032 D DockEventReceiver: finishStartingService: stopping service
,09-13 16:09:45.032  4032  4032 D BluetoothPbap: Proxy object connected
09-13 16:09:45.032  4032  4032 D PbapServerProfile: Bluetooth service connected
,09-13 16:09:45.039  4138  4182 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:09:45.046  1361  1361 D BluetoothPbap: Proxy object connected
,09-13 16:09:45.046  1361  1361 D PbapServerProfile: Bluetooth service connected
,09-13 16:09:45.053  4138  4138 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 16:09:45.053  4138  4138 D ObexServerSockets0: prepareForNewConnect()
,09-13 16:09:45.058  4138  4186 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:09:45.060  4138  4186 I BtOppRfcommListener: Accept thread started.
,09-13 16:09:45.111   874   874 D BluetoothHeadset: Proxy object connected
,09-13 16:09:45.111   874   891 D BluetoothHeadset: Proxy object connected
09-13 16:09:45.111   874   874 D BluetoothHeadset: Proxy object connected
,09-13 16:09:45.112  1927  2122 D BluetoothHeadset: Proxy object connected
,09-13 16:09:45.114  4032  4042 D BluetoothHeadset: Proxy object connected
,09-13 16:09:45.114  4032  4134 D BluetoothHeadset: Proxy object connected
,09-13 16:09:45.115  4032  4032 D HeadsetProfile: Bluetooth service connected
,09-13 16:09:45.115  1361  2063 D BluetoothHeadset: Proxy object connected
09-13 16:09:45.115  1927  1943 D BluetoothHeadset: Proxy object connected
,09-13 16:09:45.115   874   874 D BluetoothHeadset: Proxy object connected
,09-13 16:09:45.116  1361  1361 D HeadsetProfile: Bluetooth service connected
09-13 16:09:45.124  4032  4032 D HeadsetProfile: Bluetooth service connected
,09-13 16:09:45.478  3815  4136 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:45.478  3815  4136 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:45.478  3815  4136 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:45.478  3815  4136 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:45.478  3815  4136 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:45.478  3815  4136 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:45.478  3815  4136 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:45.478  3815  4136 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 16:09:45.486  3815  4136 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 16:09:45.495  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:45.498   874  1383 D WifiService: setWifiEnabled: false pid=3815, uid=10000
,09-13 16:09:45.499   874  1383 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 16:09:45.508   874  2165 D WifiService: setWifiEnabled: false pid=3815, uid=10000
,09-13 16:09:45.509   874  2165 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 16:09:45.518   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 16:09:45.526  2166  2328 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 16:09:45.543  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:45.543  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:45.543  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:45.543  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 16:09:45.543  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:45.543  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:45.543  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:45.543  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 16:09:45.548  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 16:09:45.552  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:45.552  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:45.552  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:45.552  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 16:09:45.552  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:45.552  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:45.552  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:45.552  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 16:09:45.557  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 16:09:46.022  3815  4188 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:46.022  3815  4188 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:46.022  3815  4188 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:46.022  3815  4188 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 16:09:46.022  3815  4188 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:46.022  3815  4188 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:46.022  3815  4188 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:46.022  3815  4188 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 16:09:46.029  3815  4188 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 16:09:46.037  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:46.038   874  1963 D WifiService: setWifiEnabled: true pid=3815, uid=10000
09-13 16:09:46.038   874  1963 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 16:09:46.048   874   885 D WifiService: setWifiEnabled: true pid=3815, uid=10000
,09-13 16:09:46.048   874   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 16:09:46.052   874  1308 D WifiConfigStore: Loading config and enabling all networks 
,09-13 16:09:46.072  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:46.072  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:46.072  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:46.072  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:46.072  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:46.072  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:46.072  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:46.072  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 16:09:46.075  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 16:09:46.079  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:46.079  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:46.079  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:46.079  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:46.079  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:46.079  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:46.079  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:46.079  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 16:09:46.082  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 16:09:46.095   874  1308 D WifiConfigStore: loaded 0 passpoint configs
,09-13 16:09:46.096   874  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-13 16:09:46.096   874  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-13 16:09:46.097   874  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-13 16:09:46.097   874  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-13 16:09:46.097   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-13 16:09:46.098   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-13 16:09:46.109   371   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-13 16:09:46.110   371   872 D CommandListener: Setting iface cfg
,09-13 16:09:46.111   874  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '136 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 136 Failed to set address (No such device)'
,09-13 16:09:46.111   874  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 16:09:46.125   874  1307 D WifiNative-HAL: p2pGetDeviceAddress
09-13 16:09:46.126   874  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-13 16:09:46.126   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 16:09:46.201   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 16:09:46.561  3815  4191 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:46.561  3815  4191 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:46.561  3815  4191 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:46.561  3815  4191 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:46.561  3815  4191 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:46.561  3815  4191 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:46.561  3815  4191 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:46.561  3815  4191 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 16:09:46.569  3815  4191 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 16:09:46.577  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:09:46.580  3815  3863 D BluetoothAdapter: enable(): BT is already enabled..!
,09-13 16:09:46.581   874  1952 D WifiService: setWifiEnabled: true pid=3815, uid=10000
,09-13 16:09:46.581   874  1952 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 16:09:46.612  3815  4195 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-13 16:09:46.612  3815  4195 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 16:09:47.130  3815  4197 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-13 16:09:47.131  3815  4195 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-13 16:09:47.132  3815  4195 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-13 16:09:47.132  3815  4197 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:09:47.134  3815  4195 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:09:47.134  3815  4197 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:09:47.135  3815  4195 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:09:47.135  3815  4197 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:09:47.138  3815  4197 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-13 16:09:47.141  3815  4195 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 16:09:47.147  3815  4201 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 496, name: IncomingSocketThread/Sender)
,09-13 16:09:47.150  3815  4200 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 495, name: OutgoingSocketThread/Sender)
,09-13 16:09:47.151  3815  4202 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 498, name: IncomingSocketThread/Receiver)
,09-13 16:09:47.152  3815  4202 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 498, thread name: IncomingSocketThread/Receiver)
,09-13 16:09:47.153  3815  4202 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 16:09:47.153  3815  4202 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 498, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 16:09:47.155  3815  4203 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 497, name: OutgoingSocketThread/Receiver)
09-13 16:09:47.156  3815  4203 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 497, thread name: OutgoingSocketThread/Receiver)
,09-13 16:09:47.157  3815  4203 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-13 16:09:47.158  3815  4203 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 497, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-13 16:09:47.631  3815  3863 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-13 16:09:47.633  3815  3863 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 16:09:47.639  3815  3863 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e886fc2 Bundle[{}]
,09-13 16:09:47.641  3815  3863 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 16:09:47.641  3815  3863 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-13 16:09:47.642  3815  3863 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-13 16:09:47.642  3815  3863 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-13 16:09:47.643  3815  3863 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-13 16:09:47.643  3815  3863 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 16:09:47.650  3815  4204 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-13 16:09:47.651  3815  4204 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 16:09:47.658  3815  4206 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-13 16:09:47.658  3815  4204 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-13 16:09:47.658  3815  4206 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:09:47.658  3815  4204 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:09:47.658  3815  4204 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:09:47.658  3815  4206 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:09:47.659  3815  4204 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:09:47.660  3815  4204 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 16:09:47.661  3815  4206 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:09:47.665  3815  4206 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-13 16:09:47.665  3815  4208 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 509, name: OutgoingSocketThread/Sender)
,09-13 16:09:47.667  3815  4209 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 511, name: OutgoingSocketThread/Receiver)
,09-13 16:09:47.668  3815  4209 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 511, thread name: OutgoingSocketThread/Receiver)
,09-13 16:09:47.668  3815  4209 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-13 16:09:47.668  3815  4209 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 511, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 16:09:47.668   874  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.20 rxSuccessRate=0.40 delta 1000 -> 1000
,09-13 16:09:47.670  3815  4211 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 512, name: IncomingSocketThread/Receiver)
09-13 16:09:47.670   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-13 16:09:47.669  3815  4210 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 510, name: IncomingSocketThread/Sender)
09-13 16:09:47.670   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 16:09:47.670  3815  4211 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 512, thread name: IncomingSocketThread/Receiver)
09-13 16:09:47.670  3815  4211 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-13 16:09:47.670  3815  4211 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 512, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-13 16:09:47.684   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-13 16:09:47.725   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-13 16:09:47.726  1480  1480 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-13 16:09:48.173  3815  3863 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 521)
09-13 16:09:48.176  3815  3863 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-13 16:09:48.176  3815  3863 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 522)
,09-13 16:09:48.182  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 16:09:48.182  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8838d94 added. We now have 4 listener(s)
,09-13 16:09:48.184  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 16:09:48.184  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:09:48.184  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 16:09:48.184  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:09:48.185  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99e903d added. We now have 4 listener(s)
09-13 16:09:48.185  3815  3863 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:09:48.185  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 16:09:48.188  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:09:48.197  3815  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:09:48.197  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:48.197  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:48.197  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:48.197  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:48.197  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 16:09:48.197  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 16:09:48.197  3815  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 16:09:48.199  3815  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 16:09:48.199  3815  3863 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:09:48.201  1480  1480 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
09-13 16:09:48.202  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:48.205  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:09:48.205  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:48.205  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:09:48.205  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 16:09:48.205  3815  3863 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8838d94 removed from the list
09-13 16:09:48.205  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:09:48.206  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99e903d removed from the list
09-13 16:09:48.206  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:09:48.206  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:09:48.206  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:48.208  3815  3863 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,09-13 16:09:48.208  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,09-13 16:09:48.212  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:09:48.212  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 16:09:48.213  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:09:48.214  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:09:48.214  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 16:09:48.215  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 16:09:48.215  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 16:09:48.215  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-13 16:09:48.215  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-13 16:09:48.215  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:09:48.215  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:09:48.215  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:09:48.219  3815  3863 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 16:09:48.219  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 16:09:48.224  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 16:09:48.225  3815  4212 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:09:48.225  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 16:09:48.226  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:09:48.228  3815  4212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:09:48.229  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-13 16:09:48.229  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 16:09:48.229  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 F8 CF C5 D9 E5 61
09-13 16:09:48.229  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:09:48.230  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:09:48.230  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 16:09:48.230  1480  1480 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-13 16:09:48.230  3815  3863 D BluetoothAdapter: STATE_ON
09-13 16:09:48.231  1480  1480 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-13 16:09:48.233  4138  4187 D BtGatt.GattService: registerClient() - UUID=86b0eecc-0b2c-4186-b64b-efcb0a1b7708
,09-13 16:09:48.233   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
09-13 16:09:48.235  4138  4154 D BtGatt.GattService: onClientRegistered() - UUID=86b0eecc-0b2c-4186-b64b-efcb0a1b7708, clientIf=5
09-13 16:09:48.236  3815  3827 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 16:09:48.238  4138  4156 D BtGatt.AdvertiseManager: message : 0
,09-13 16:09:48.241   874  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 16:09:48.241   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-13 16:09:48.241   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 16:09:48.242  4138  4156 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:09:48.249   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 16:09:48.250  4138  4154 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 16:09:48.256   371   872 D CommandListener: Setting iface cfg
09-13 16:09:48.257  4138  4154 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
09-13 16:09:48.257   874  1308 D WifiStateMachine: Start Dhcp Watchdog 2
09-13 16:09:48.257  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 16:09:48.257  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:09:48.259  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:09:48.260  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:09:48.261  3815  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 16:09:48.261  3815  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-13 16:09:48.261  3815  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true,
09-13 16:09:48.261  3815  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:09:48.261  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:09:48.263  3815  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:09:48.263  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:09:48.267   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 16:09:48.268   874  1310 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-13 16:09:48.269   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-13 16:09:48.283   874  4216 D DhcpClient: Receive thread started
,09-13 16:09:48.365   874  1308 E native  : do suspend false
,09-13 16:09:48.384   874  1882 D DhcpClient: Broadcasting DHCPDISCOVER
,09-13 16:09:48.402   874  4216 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172674, domain null
,09-13 16:09:48.403   874  1882 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172674 seconds
,09-13 16:09:48.407   874  1882 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-13 16:09:48.421   874  4216 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-13 16:09:48.422   874  1882 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-13 16:09:48.427   371   872 D CommandListener: Setting iface cfg
,09-13 16:09:48.440   874  1882 D DhcpClient: Scheduling renewal in 86399s
,09-13 16:09:48.441   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-13 16:09:48.461   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-13 16:09:48.464   874  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 16:09:48.466   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-13 16:09:48.469   874  1310 D ConnectivityService: Adding iface wlan0 to network 101
,09-13 16:09:48.489   874  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 16:09:48.535   874  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-13 16:09:48.535   874  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101,
,09-13 16:09:48.539   874  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-13 16:09:48.542   874  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101,
,09-13 16:09:48.545   874  1310 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-13 16:09:48.556   874  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 16:09:48.561   874  1310 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-13 16:09:48.561   874  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-13 16:09:48.561   874  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-13 16:09:48.561   874  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-13 16:09:48.561   874  1310 D ConnectivityService:    accepting network in place of null
,09-13 16:09:48.562   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 16:09:48.562   874  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 16:09:48.608   874  4214 D NetlinkSocketObserver: NeighborEvent{elapsedMs=149057, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 16:09:48.610   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 16:09:48.655   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 16:09:48.665   874  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-13 16:09:48.665   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 16:09:48.675   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-13 16:09:48.677   874  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-13 16:09:48.684   874  4213 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-13 16:09:48.703  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:48.703  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:48.703  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:48.703  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:48.703  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:48.703  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:09:48.703  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:09:48.703  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:09:48.705  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:09:48.709  1751  1751 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 16:09:48.711  3815  3815 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 16:09:48.711  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:09:48.711  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 16:09:48.711  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:09:48.711  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:09:48.711  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:09:48.711  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:09:48.711  3815  3815 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 16:09:48.713  3815  3815 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 16:09:48.719  1751  1751 D SystemUpdateService: onCreate
,09-13 16:09:48.723  1751  1751 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 16:09:48.739  1751  4227 I SystemUpdateService: active receiver: enabled
,09-13 16:09:48.742  1751  4227 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 16:09:48.745  1751  1751 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-13 16:09:48.748  1751  2426 I iu.UploadsManager: num queued entries: 0
,09-13 16:09:48.748  1751  2426 I iu.UploadsManager: num updated entries: 0
,09-13 16:09:48.754   874  4213 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 14:09:48 GMT], X-Android-Received-Millis=[1473775788752], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473775788731]}
,09-13 16:09:48.755  1751  4227 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-13 16:09:48.755  1751  4227 I SystemUpdateService: now status is 0 (complete)
09-13 16:09:48.755  1751  4227 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-13 16:09:48.756  1751  1751 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 16:09:48.757   874  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 16:09:48.758   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-13 16:09:48.758  1751  1751 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 16:09:48.758   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 16:09:48.760  3934  3934 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 16:09:48.763   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-13 16:09:48.764  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-13 16:09:48.764  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 16:09:48.764  3815  3815 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:09:48.767  3934  3934 D SprintDMHelper: simOperator: 
09-13 16:09:48.767  3934  3934 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 16:09:48.755  1751  4227 I SystemUpdateService: file has been verified
,09-13 16:09:48.786  1751  4232 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-13 16:09:48.786  1751  4232 W BaseAppContext: Using Auth Proxy for data requests.
,09-13 16:09:48.798  1751  4232 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
,09-13 16:09:48.816  1751  4227 I SystemUpdateService: OTA package size = 12249756
,09-13 16:09:48.833  1751  2426 I iu.SyncManager: NEXT; no task
,09-13 16:09:48.837  1751  4227 I SystemUpdateService: showing system update notification
,09-13 16:09:48.859  1751  1751 D SystemUpdateService: onDestroy
,09-13 16:09:48.881  1543  2171 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-13 16:09:48.881  1543  2171 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-13 16:09:48.881  1543  2171 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 16:09:48.882  1543  2171 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 16:09:48.899  1751  4232 E MDM     : [176] SitrepService.a: Error sending sitrep.
,09-13 16:09:48.940  3050  4235 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-13 16:09:49.402   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-13 16:09:49.415   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 16:09:49.415   874   894 I Adreno  : Build Date                       : 10/20/15
09-13 16:09:49.415   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 16:09:49.415   874   894 I Adreno  : Local Branch                     : M14
09-13 16:09:49.415   874   894 I Adreno  : Remote Branch                    : 
09-13 16:09:49.415   874   894 I Adreno  : Remote Branch                    : 
09-13 16:09:49.415   874   894 I Adreno  : Reconstruct Branch               : 
09-13 16:09:49.424  1867  1867 I Keyboard.Facilitator: onFinishInput()
,09-13 16:09:49.443   280   302 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (177 us)
,09-13 16:09:49.664   874  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-13 16:09:50.049  3815  3815 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 16:09:50.049  3815  3815 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-13 16:09:50.104   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-13 16:09:50.106  3815  3815 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@e886fc2 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@ae8f339, 16908290=android.view.AbsSavedState$1@ae8f339}, android:focusedViewId=100}]}]
,09-13 16:09:50.106  3815  3815 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-13 16:09:50.106  3815  3815 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-13 16:09:50.106  3815  3815 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-13 16:09:50.116   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-13 16:09:50.123   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-13 16:09:50.125   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
09-13 16:09:50.125   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-13 16:09:50.143   874   883 I art     : Background partial concurrent mark sweep GC freed 50892(3MB) AllocSpace objects, 8(252KB) LOS objects, 33% free, 29MB/43MB, paused 2.279ms total 126.558ms
,09-13 16:09:50.380   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-13 16:09:50.384   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-13 16:09:50.385   874  1332 D SurfaceControl: Excessive delay in setPowerMode(): 262ms
,09-13 16:09:50.389   874   894 I DreamManagerService: Entering dreamland.
,09-13 16:09:50.390   874   894 I PowerManagerService: Dozing...
09-13 16:09:50.392   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-13 16:09:50.462   375  1280 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-13 16:09:50.462   375  1280 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-13 16:09:50.479   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 16:09:50.493   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 16:09:50.496  1911  4246 D NfcService: Discovery configuration equal, not updating.
,09-13 16:09:50.502   874  1308 E native  : do suspend false
,09-13 16:09:50.524   874  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 16:09:50.536   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 16:09:50.540   874  1308 E native  : do suspend true
,09-13 16:09:50.591   375  1316 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
09-13 16:09:50.592   375  1316 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-13 16:09:51.762  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-13 16:09:51.763  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 16:09:51.763  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:09:51.764  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 16:09:51.764  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:09:51.765  3815  4212 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 16:09:51.765  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:09:51.765  3815  4212 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:09:51.765  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 16:09:51.765  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 16:09:51.765  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:09:51.766  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:09:51.765  3815  4212 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 16:09:51.766  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:09:51.766  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:09:51.766  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 16:09:51.769  3815  3863 D BluetoothAdapter: STATE_ON
,09-13 16:09:51.771  3815  3863 D BluetoothLeScanner: could not find callback wrapper
09-13 16:09:51.771  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:09:51.772  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 16:09:51.775  4138  4156 D BtGatt.AdvertiseManager: message : 1
,09-13 16:09:51.777  4138  4156 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 16:09:51.786  4138  4154 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-13 16:09:51.786  4138  4154 D BtGatt.GattService: Client app is not null!
,09-13 16:09:51.788  4138  4149 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 16:09:51.790  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 16:09:51.790  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-13 16:09:51.790  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false,
09-13 16:09:51.790  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-13 16:09:51.790  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-13 16:09:51.791  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:09:51.791  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
09-13 16:09:51.791  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:09:51.792  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:09:51.795  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 16:09:51.795  3815  3815 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:09:51.795  3815  3815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 16:09:51.796  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:09:51.796  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:09:51.796  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:09:51.800  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:09:51.800  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:51.801  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:51.801  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8838d94 not in the list,
09-13 16:09:51.801  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:09:51.802  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99e903d not in the list
09-13 16:09:51.802  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 16:09:51.802  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:51.802  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:09:51.804  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 16:09:51.806  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 16:09:51.806  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 16:09:51.806  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-13 16:09:51.807  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:09:51.807  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 16:09:51.812  3815  3863 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 16:09:51.812  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:09:51.819  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:09:51.821  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 16:09:51.821  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:09:51.829  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 16:09:51.829  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-13 16:09:51.831  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 16:09:51.833  3815  3863 D BluetoothAdapter: STATE_ON
,09-13 16:09:51.838  4138  4187 D BtGatt.GattService: registerClient() - UUID=9aae912f-8298-4d0b-8257-d265057b5cf9
,09-13 16:09:51.839  4138  4154 D BtGatt.GattService: onClientRegistered() - UUID=9aae912f-8298-4d0b-8257-d265057b5cf9, clientIf=5
,09-13 16:09:51.840  3815  3827 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 16:09:51.842  4138  4167 D BtGatt.GattService: start scan with filters
,09-13 16:09:51.848  4138  4157 D BtGatt.ScanManager: handling starting scan
,09-13 16:09:51.848  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 16:09:51.849  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 16:09:51.849  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 16:09:51.850  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 16:09:51.850  4138  4157 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d682636
,09-13 16:09:51.858  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 16:09:51.859  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 16:09:51.860  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:09:51.865  4138  4154 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 16:09:51.865  4138  4154 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 16:09:51.866  4138  4157 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 16:09:51.869  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:09:51.876  4138  4154 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-13 16:09:51.876  4138  4154 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 16:09:51.877  4138  4157 D BtGatt.ScanManager: Starting BLE batch scan
,09-13 16:09:51.878  4138  4157 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 16:09:51.896  4138  4154 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 16:09:51.896  4138  4154 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 16:09:51.907  4138  4154 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-13 16:09:51.907  4138  4154 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 16:09:52.360  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-13 16:09:52.361  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:09:52.361  3815  3815 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:09:53.415  4138  4138 D BtGatt.ScanManager: awakened up at time 153864
09-13 16:09:53.417  4138  4157 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 16:09:53.483  4138  4154 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-13 16:09:53.484  4138  4154 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 16:09:53.484  4138  4154 D BtGatt.GattService: current time is 153934364313
,09-13 16:09:53.486  4138  4154 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -83, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -126, -22, -96, 83, -39, -56, 1, -128, -57, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 8, -20, -87, 80, 117, 65, 0, 71, -122, -77, 84, 69, -12, 1, -128, -93, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -102, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -82, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -84, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -126, -22, -96, 83, -39, -56, 1, -128, -57, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 8, -20, -87, 80, 117, 65, 0]
,09-13 16:09:53.491  4138  4154 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-13 16:09:53.494  4138  4154 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 8, -20, -87, 80, 117, 65]
09-13 16:09:53.494  4138  4154 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-13 16:09:53.495  4138  4154 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-13 16:09:53.496  4138  4154 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-13 16:09:53.497  4138  4154 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
09-13 16:09:53.498  4138  4154 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 8, -20, -87, 80, 117, 65]
,09-13 16:09:53.509  3815  3815 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 08:EC:A9:50:75:41 6], added - the peer count is 1
,09-13 16:09:53.512  3815  3815 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 08:EC:A9:50:75:41 6] updated - the peer count is 1
,09-13 16:09:53.513  3815  3815 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 08:EC:A9:50:75:41 6], Bluetooth address: 08:EC:A9:50:75:41, device name: '', device address: ''
,09-13 16:09:54.392   874  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 14 -> obsolete
,09-13 16:09:54.879  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:09:54.879  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:54.880  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:09:54.880  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8838d94 not in the list
09-13 16:09:54.881  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 16:09:54.881  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 16:09:54.881  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:09:54.881  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 16:09:54.882  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 16:09:54.882  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 16:09:54.886  3815  3863 D BluetoothAdapter: STATE_ON
,09-13 16:09:54.888  4138  4176 D BtGatt.GattService: stopScan() - queue size =1
09-13 16:09:54.891  4138  4148 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 16:09:54.892  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:09:54.892  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 16:09:54.892  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 16:09:54.893  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 16:09:54.893  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 16:09:54.897  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:09:54.897  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 16:09:54.897  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:09:54.898  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:09:54.899  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:09:54.899  3815  3863 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
09-13 16:09:54.902  4138  4138 D BtGatt.ScanManager: awakened up at time 155351
,09-13 16:09:54.904  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:09:54.905  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 16:09:54.905  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:09:54.905  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99e903d not in the list
09-13 16:09:54.906  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:09:54.906  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:09:54.906  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:09:54.908  3815  3863 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,09-13 16:09:54.909  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,09-13 16:09:54.911  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:09:54.911  3815  3863 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-13 16:09:54.912  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:09:54.912  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:09:54.912  4138  4154 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-13 16:09:54.912  4138  4154 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 16:09:54.913  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 16:09:54.913  4138  4157 D BtGatt.ScanManager: stopping BLe Batch
,09-13 16:09:54.914  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:09:54.914  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:09:54.914  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:09:54.914  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-13 16:09:54.914  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:09:54.914  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:09:54.914  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:09:54.919  3815  4251 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:09:54.919  3815  3863 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 16:09:54.920  3815  3863 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:09:54.922  3815  4251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 16:09:54.925  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 16:09:54.925  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 16:09:54.925  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 16:09:54.928  4138  4154 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-13 16:09:54.928  4138  4154 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 16:09:54.928  4138  4157 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-13 16:09:54.928  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 16:09:54.928  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 16:09:54.928  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 F8 CF C5 D9 E5 61
,09-13 16:09:54.929  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:09:54.929  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 16:09:54.929  3815  3863 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 16:09:54.930  3815  3863 D BluetoothAdapter: STATE_ON
,09-13 16:09:54.938  4138  4149 D BtGatt.GattService: registerClient() - UUID=abbd92ed-66e8-495b-9bd0-f43035a243a8
,09-13 16:09:54.938  4138  4154 D BtGatt.GattService: onClientRegistered() - UUID=abbd92ed-66e8-495b-9bd0-f43035a243a8, clientIf=5
09-13 16:09:54.938  3815  3827 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 16:09:54.939  4138  4156 D BtGatt.AdvertiseManager: message : 0
,09-13 16:09:54.942  4138  4156 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 16:09:54.946  4138  4154 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,09-13 16:09:54.946  4138  4154 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 16:09:54.946  4138  4154 D BtGatt.GattService: current time is 155396394031
,09-13 16:09:54.947  4138  4154 D BtGatt.GattService: Batch record : [87, 45, 110, 28, -13, -4, 1, -128, -62, 3, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 124, -7, 14, 55, -106, -85, 0, 37, -47, 14, -113, 116, -46, 1, -128, -85, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -86, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -90, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
09-13 16:09:54.947  4138  4154 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 124, -7, 14, 55, -106, -85]
09-13 16:09:54.947  4138  4154 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-13 16:09:54.947  4138  4154 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-13 16:09:54.948  4138  4154 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,09-13 16:09:54.956  4138  4154 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 16:09:54.965  4138  4154 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 16:09:54.966  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-13 16:09:54.966  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 16:09:54.968  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 16:09:54.969  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 16:09:54.969  3815  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 16:09:54.969  3815  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-13 16:09:54.969  3815  3815 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 16:09:54.969  3815  3815 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 16:09:54.969  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 16:09:54.973  3815  3815 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:09:54.973  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 16:09:55.474  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 16:09:55.475  3815  3815 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 16:09:55.475  3815  3815 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 16:09:56.567   874  1310 D ConnectivityService: handlePromptUnvalidated 101
,09-13 16:09:56.973  2166  2653 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 16:09:58.473  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 16:09:58.473  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 16:09:58.473  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 16:09:58.474  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 16:09:58.475  3815  4251 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 16:09:58.475  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:09:58.475  3815  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:09:58.475  3815  4251 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-13 16:09:58.475  3815  4251 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-13 16:09:58.476  3815  3815 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:09:58.476  3815  3815 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:09:58.477  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8838d94 not in the list
,09-13 16:09:58.478  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:09:58.478  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:09:58.478  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 16:09:58.478  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:09:58.479  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 16:09:58.482  3815  3863 D BluetoothAdapter: STATE_ON
,09-13 16:09:58.482  3815  3863 D BluetoothLeScanner: could not find callback wrapper
09-13 16:09:58.483  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:09:58.483  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-13 16:09:58.485  4138  4156 D BtGatt.AdvertiseManager: message : 1
09-13 16:09:58.489  4138  4156 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 16:09:58.499  4138  4154 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-13 16:09:58.499  4138  4154 D BtGatt.GattService: Client app is not null!
09-13 16:09:58.501  4138  4176 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 16:09:58.502  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 16:09:58.502  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 16:09:58.503  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 16:09:58.503  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 16:09:58.503  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 16:09:58.506  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:09:58.507  3815  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:09:58.507  3815  3863 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:09:58.508  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:09:58.511  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:09:58.511  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99e903d not in the list
,09-13 16:09:58.512  3815  3815 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:09:58.512  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:09:58.512  3815  3815 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:09:58.512  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:58.512  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:09:58.515  3815  3863 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:09:58.516  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:09:58.516  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:58.516  3815  3863 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8838d94 not in the list
,09-13 16:09:58.516  3815  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:09:58.517  3815  3863 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99e903d not in the list
09-13 16:09:58.517  3815  3863 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:09:58.517  3815  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 16:09:58.518  3815  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:09:58.520  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 16:09:58.520  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-13 16:09:58.521  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-13 16:09:58.521  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:09:58.521  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 16:09:58.522  3815  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 16:09:58.538  3815  4254 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 542, name: My test thread name)
,09-13 16:09:59.014  3815  3815 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 16:10:00.537  3815  3863 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 542
,09-13 16:10:00.538  3815  3863 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 542, name: My test thread name)
,09-13 16:10:00.544  3815  4255 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 543, name: My test thread name)
,09-13 16:10:00.544  3815  4255 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 543, thread name: My test thread name)
,09-13 16:10:00.545  3815  4255 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 543, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-13 16:10:00.549  3815  3863 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 16:10:00.558  3815  4256 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 547, name: My test thread name)
,09-13 16:10:00.558  3815  4256 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 547, thread name: My test thread name): Test exception.
,09-13 16:10:00.559  3815  4256 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 547, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-13 16:10:00.566  3815  3863 I jxcore-log: Total number of executed tests:  82
09-13 16:10:00.566  3815  3863 I jxcore-log: 
,09-13 16:10:00.567  3815  3863 I jxcore-log: Number of passed tests:  82
09-13 16:10:00.567  3815  3863 I jxcore-log: 
,09-13 16:10:00.568  3815  3863 I jxcore-log: Number of failed tests:  0
09-13 16:10:00.568  3815  3863 I jxcore-log: 
,09-13 16:10:00.570  3815  3863 I jxcore-log: Number of ignored tests:  0
09-13 16:10:00.570  3815  3863 I jxcore-log: 
,09-13 16:10:00.571  3815  3863 I jxcore-log: Total duration:  24067
09-13 16:10:00.571  3815  3863 I jxcore-log: 
,09-13 16:10:00.576  3815  3863 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 16:10:00.576  3815  3863 I jxcore-log: 
,09-13 16:10:00.579  3815  3863 I jxcore-log: My device name is: motorola-Nexus 6
09-13 16:10:00.579  3815  3863 I jxcore-log: 
09-13 16:10:00.582  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:10:00.582  3815  3863 I jxcore-log: 
09-13 16:10:00.584  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:10:00.584  3815  3863 I jxcore-log: 
09-13 16:10:00.585  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:10:00.585  3815  3863 I jxcore-log: 
09-13 16:10:00.588  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:10:00.588  3815  3863 I jxcore-log: 
09-13 16:10:00.589  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:10:00.589  3815  3863 I jxcore-log: 
09-13 16:10:00.592  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:10:00.592  3815  3863 I jxcore-log: 
09-13 16:10:00.594  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:10:00.594  3815  3863 I jxcore-log: 
09-13 16:10:00.595  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:10:00.595  3815  3863 I jxcore-log: 
09-13 16:10:00.596  3815  4254 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 542, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
09-13 16:10:00.597  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:10:00.597  3815  3863 I jxcore-log: 
,09-13 16:10:00.598  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 16:10:00.598  3815  3863 I jxcore-log: 
,09-13 16:10:00.599  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 16:10:00.599  3815  3863 I jxcore-log: 
,09-13 16:10:00.599  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 16:10:00.599  3815  3863 I jxcore-log: 
,09-13 16:10:00.601  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 16:10:00.601  3815  3863 I jxcore-log: 
,09-13 16:10:00.602  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 16:10:00.602  3815  3863 I jxcore-log: 
,09-13 16:10:00.603  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 16:10:00.603  3815  3863 I jxcore-log: 
,09-13 16:10:00.605  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 16:10:00.605  3815  3863 I jxcore-log: 
,09-13 16:10:00.606  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 16:10:00.606  3815  3863 I jxcore-log: 
,09-13 16:10:00.607  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 16:10:00.607  3815  3863 I jxcore-log: 
,09-13 16:10:00.608  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 16:10:00.608  3815  3863 I jxcore-log: 
09-13 16:10:00.609  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 16:10:00.609  3815  3863 I jxcore-log: 
09-13 16:10:00.610  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 16:10:00.610  3815  3863 I jxcore-log: 
09-13 16:10:00.611  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 16:10:00.611  3815  3863 I jxcore-log: 
09-13 16:10:00.612  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 16:10:00.612  3815  3863 I jxcore-log: 
09-13 16:10:00.613  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 16:10:00.613  3815  3863 I jxcore-log: 
09-13 16:10:00.614  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 16:10:00.614  3815  3863 I jxcore-log: 
09-13 16:10:00.615  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 16:10:00.615  3815  3863 I jxcore-log: 
09-13 16:10:00.616  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 16:10:00.616  3815  3863 I jxcore-log: 
09-13 16:10:00.620  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 16:10:00.620  3815  3863 I jxcore-log: 
09-13 16:10:00.621  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 16:10:00.621  3815  3863 I jxcore-log: 
09-13 16:10:00.622  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 16:10:00.622  3815  3863 I jxcore-log: 
09-13 16:10:00.622  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 16:10:00.622  3815  3863 I jxcore-log: 
09-13 16:10:00.623  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 16:10:00.623  3815  3863 I jxcore-log: 
,09-13 16:10:00.624  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 16:10:00.624  3815  3863 I jxcore-log: 
,09-13 16:10:00.624  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 16:10:00.624  3815  3863 I jxcore-log: 
,09-13 16:10:00.625  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 16:10:00.625  3815  3863 I jxcore-log: 
,09-13 16:10:00.626  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
09-13 16:10:00.626  3815  3863 I jxcore-log: 
,09-13 16:10:00.627  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:10:00.627  3815  3863 I jxcore-log: 
,09-13 16:10:00.628  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:10:00.628  3815  3863 I jxcore-log: 
,09-13 16:10:00.629  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-13 16:10:00.629  3815  3863 I jxcore-log: 
,09-13 16:10:00.631  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-13 16:10:00.631  3815  3863 I jxcore-log: 
,09-13 16:10:00.632  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 16:10:00.632  3815  3863 I jxcore-log: ,
,09-13 16:10:00.632  3815  3863 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 16:10:00.632  3815  3863 I jxcore-log: 
,09-13 16:10:01.216   874  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,09-13 16:10:01.220  4257  4257 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-13 16:10:01.225  4257  4257 D AndroidRuntime: CheckJNI is OFF
,09-13 16:10:01.266  4257  4257 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-13 16:10:01.311  4257  4257 I Radio-JNI: register_android_hardware_Radio DONE
,09-13 16:10:01.332  4257  4257 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 16:10:01.341   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-13 16:10:01.341   874   887 I ActivityManager: Killing 3815:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-13 16:10:01.434   874  2165 I WindowState: WIN DEATH: Window{70d2857 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 16:10:01.436   874  1309 D WifiService: Client connection lost with reason: 4
09-13 16:10:01.437   874   884 D GraphicsStats: Buffer count: 2
,09-13 16:10:01.445   874   897 W PackageSettings: Skipping PackageSetting{89f3aeb com.example.hello/10273} due to missing metadata
,09-13 16:10:01.493   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-13 16:10:01.493   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-13 16:10:01.494   874   887 E ActivityManager: Failure starting process com.test.thalitest
09-13 16:10:01.494   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-13 16:10:01.494   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-13 16:10:01.494   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-13 16:10:01.494   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-13 16:10:01.494   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-13 16:10:01.494   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-13 16:10:01.494   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-13 16:10:01.494   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
,09-13 16:10:01.494   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-13 16:10:01.494   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-13 16:10:01.494   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
,09-13 16:10:01.494   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-13 16:10:01.494   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-13 16:10:01.494   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-13 16:10:01.494   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-13 16:10:01.494   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:10:01.494   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:10:01.494   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 16:10:01.494   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 16:10:01.494   874   887 I ActivityManager:   Force finishing activity ActivityRecord{7edd24c u0 com.test.thalitest/.MainActivity t4}
09-13 16:10:01.496   874   897 I art     : Starting a blocking GC Explicit
,09-13 16:10:01.504   874  1383 W ActivityManager: Spurious death for ProcessRecord{a7da501 0:com.test.thalitest/u0a0}, curProc for 3815: null
,09-13 16:10:01.563   874   897 I art     : Explicit concurrent mark sweep GC freed 23827(1466KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 29MB/43MB, paused 1.071ms total 67.439ms
,09-13 16:10:01.590   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-13 16:10:01.592  4257  4257 I art     : System.exit called, status: 0
,09-13 16:10:01.592  4257  4257 I AndroidRuntime: VM exiting with result code 0.
,09-13 16:10:01.595   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-13 16:10:01.605   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-13 16:10:01.609  4138  4138 D BluetoothMapAppObserver: onReceive
,09-13 16:10:01.610  4138  4138 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-13 16:10:01.611  1867  1867 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-13 16:10:01.612  3631  3631 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-13 16:10:01.612  2166  2286 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-13 16:10:01.616   874  1300 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 16:10:01.639  1927  1927 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-13 16:10:01.657   874  2164 I ActivityManager: Start proc 4271:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-13 16:10:01.658  1867  4269 I Keyboard.Facilitator.DecoderInitializer: run()
,09-13 16:10:01.677  1867  4269 I Decoder : createOrResetDecoder
,09-13 16:10:01.686  4271  4271 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-13 16:10:01.696  1543  1543 I ConfigService: onCreate
,09-13 16:10:01.708   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-13 16:10:01.716   874  1957 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3815 uid 10000
,09-13 16:10:01.720  1941  2032 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-13 16:10:01.720   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-13 16:10:01.721   874   886 E PackageManager: Failed to write settings, restoring backup
09-13 16:10:01.721   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-13 16:10:01.721   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-13 16:10:01.721   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-13 16:10:01.721   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-13 16:10:01.721   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-13 16:10:01.721   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:10:01.721   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:10:01.721   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 16:10:01.723   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-13 16:10:01.723   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-13 16:10:01.723   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 16:10:01.723   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 16:10:01.723   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 16:10:01.723   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 16:10:01.723   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 16:10:01.723   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 16:10:01.723   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-13 16:10:01.723   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-13 16:10:01.723   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-13 16:10:01.723   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 16:10:01.723   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 16:10:01.723   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:10:01.723   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 16:10:01.723   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 16:10:01.723   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 16:10:01.723   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 16:10:01.723   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 16:10:01.723   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 16:10:01.723   874   887 E DropBoxManagerService: 	... 13 more
,09-13 16:10:01.729  1867  1867 I Keyboard.Facilitator: onFinishInput()
,09-13 16:10:01.730  1867  4269 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-13 16:10:01.733   874  1383 I ActivityManager: Start proc 4284:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-13 16:10:01.734  1941  2032 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-13 16:10:01.734  1941  2032 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1941
09-13 16:10:01.734  1941  2032 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 16:10:01.734  1941  2032 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 16:10:01.734  1941  2032 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 16:10:01.734  1941  2032 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 16:10:01.734  1941  2032 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 16:10:01.734  1941  2032 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 16:10:01.734  1941  2032 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-13 16:10:01.734  1941  2032 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-13 16:10:01.734  1941  2032 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 16:10:01.734  1941  2032 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 16:10:01.734  1941  2032 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:10:01.734  1941  2032 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 16:10:01.736   874  2165 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-13 16:10:01.738   874  4290 E DropBoxManagerService: Can't write: system_app_crash
09-13 16:10:01.738   874  4290 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
09-13 16:10:01.738   874  4290 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 16:10:01.738   874  4290 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 16:10:01.738   874  4290 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 16:10:01.738   874  4290 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 16:10:01.738   874  4290 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 16:10:01.738   874  4290 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 16:10:01.738   874  4290 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 16:10:01.738   874  4290 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 16:10:01.738   874  4290 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 16:10:01.738   874  4290 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 16:10:01.738   874  4290 E DropBoxManagerService: 	... 5 more
09-13 16:10:01.739  1941  2032 I Process : Sending signal. PID: 1941 SIG: 9
,09-13 16:10:01.783  1867  4269 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-13 16:10:01.785  1867  4269 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-13 16:10:01.785  1867  4269 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-13 16:10:01.787  1867  4269 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-13 16:10:01.787  1867  4269 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,09-13 16:10:01.788  1867  4269 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,09-13 16:10:01.788  1867  4269 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-13 16:10:01.789  1867  4269 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-13 16:10:01.789  1867  4269 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-13 16:10:01.789  1867  4269 I Keyboard.Facilitator.Delight2FileSweeper: run()
,09-13 16:10:01.790  1867  4269 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-13 16:10:01.790  1867  4269 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-13 16:10:01.790  1867  4269 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-13 16:10:01.797  4271  4271 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-13 16:10:01.818   874  2164 D GraphicsStats: Buffer count: 1
,09-13 16:10:01.819   874   884 I WindowState: WIN DEATH: Window{908d46a u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-13 16:10:01.845   874  2165 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1941) has died
,09-13 16:10:01.845   874  2165 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-13 16:10:01.846   874  2165 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-13 16:10:01.861  4271  4298 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-13 16:10:01.861  4271  4298 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 16:10:01.861  4271  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 16:10:01.861  4271  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 16:10:01.861  4271  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 16:10:01.861  4271  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 16:10:01.861  4271  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 16:10:01.861  4271  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 16:10:01.861  4271  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 16:10:01.861  4271  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 16:10:01.861  4271  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 16:10:01.861  4271  4298 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 16:10:01.861  4271  4298 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 16:10:01.861  4271  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 16:10:01.861  4271  4298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 16:10:01.861  4271  4298 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-13 16:10:01.861  4271  4298 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-13 16:10:01.861  4271  4298 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-13 16:10:01.861  4271  4298 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-13 16:10:01.861  4271  4298 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:10:01.861  4271  4298 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:10:01.861  4271  4298 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 16:10:01.863  4271  4298 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-13 16:10:01.863  4271  4298 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 16:10:01.863  4271  4298 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 16:10:01.863  4271  4298 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 16:10:01.863  4271  4298 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 16:10:01.863  4271  4298 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 16:10:01.863  4271  4298 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 16:10:01.863  4271  4298 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 16:10:01.863  4271  4298 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 16:10:01.863  4271  4298 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 16:10:01.863  4271  4298 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 16:10:01.863  4271  4298 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 16:10:01.863  4271  4298 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 16:10:01.863  4271  4298 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 16:10:01.863  4271  4298 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 16:10:01.863  4271  4298 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-13 16:10:01.863  4271  4298 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-13 16:10:01.863  4271  4298 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-13 16:10:01.863  4271  4298 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-13 16:10:01.863  4271  4298 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:10:01.863  4271  4298 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:10:01.863  4271  4298 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 16:10:01.864   874   887 I ActivityManager: Start proc 4302:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-13 16:10:01.888  4271  4317 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-13 16:10:01.889   874  1957 I ActivityManager: Start proc 4314:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-13 16:10:01.923  4314  4314 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-13 16:10:01.938  4302  4302 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 16:10:01.938  4302  4302 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 16:10:01.939  4302  4302 D AndroidRuntime: Shutting down VM
,09-13 16:10:01.946  4302  4302 E AndroidRuntime: FATAL EXCEPTION: main
09-13 16:10:01.946  4302  4302 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4302
09-13 16:10:01.946  4302  4302 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 16:10:01.946  4302  4302 E AndroidRuntime: 	... 10 more
,09-13 16:10:01.947  1543  1543 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-13 16:10:01.947  1543  1543 D AndroidRuntime: Shutting down VM
09-13 16:10:01.948  1543  1543 E AndroidRuntime: FATAL EXCEPTION: main
09-13 16:10:01.948  1543  1543 E AndroidRuntime: Process: com.google.process.gapps, PID: 1543
09-13 16:10:01.948  1543  1543 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 16:10:01.948  1543  1543 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-13 16:10:01.948  1543  1543 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-13 16:10:01.948  1543  1543 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-13 16:10:01.948  1543  1543 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:10:01.948  1543  1543 E AndroidRuntime: 	,at android.os.Looper.loop(Looper.java:148)
09-13 16:10:01.948  1543  1543 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 16:10:01.948  1543  1543 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:10:01.948  1543  1543 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 16:10:01.948  1543  1543 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 16:10:01.948  1543  1543 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 16:10:01.948  1543  1543 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 16:10:01.948  1543  1543 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 16:10:01.948  1543  1543 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 16:10:01.948  1543  1543 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 16:10:01.948  1543  1543 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 16:10:01.948  1543  1543 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-13 16:10:01.948  1543  1543 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-13 16:10:01.948  1543  1543 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-13 16:10:01.948  1543  1543 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-13 16:10:01.948  1543  1543 E AndroidRuntime: 	... 8 more
,09-13 16:10:01.948   874  1962 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-13 16:10:01.949  4302  4302 I Process : Sending signal. PID: 4302 SIG: 9
,09-13 16:10:01.949   874  4329 E DropBoxManagerService: Can't write: system_app_crash
09-13 16:10:01.949   874  4329 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
09-13 16:10:01.949   874  4329 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 16:10:01.949   874  4329 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 16:10:01.949   874  4329 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 16:10:01.949   874  4329 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 16:10:01.949   874  4329 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 16:10:01.949   874  4329 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 16:10:01.949   874  4329 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 16:10:01.949   874  4329 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 16:10:01.949   874  4329 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 16:10:01.949   874  4329 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 16:10:01.949   874  4329 E DropBoxManagerService: 	... 5 more
09-13 16:10:01.952   874  4330 E DropBoxManagerService: Can't write: system_app_crash
09-13 16:10:01.952   874  4330 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
09-13 16:10:01.952   874  4330 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 16:10:01.952   874  4330 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 16:10:01.952   874  4330 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 16:10:01.952   874  4330 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 16:10:01.952   874  4330 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 16:10:01.952   874  4330 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 16:10:01.952   874  4330 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 16:10:01.952   874  4330 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 16:10:01.952   874  4330 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 16:10:01.952   874  4330 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 16:10:01.952   874  4330 E DropBoxManagerService: 	... 5 more
09-13 16:10:01.953  1543  1543 I Process : Sending signal. PID: 1543 SIG: 9
,09-13 16:10:01.975   874   885 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
,09-13 16:10:01.976   874  1957 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4302) has died
09-13 16:10:01.978   874  1957 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-13 16:10:01.986  4271  4298 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-13 16:10:01.991   874   887 I ActivityManager: Start proc 4333:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-13 16:10:01.995   874  1309 D WifiService: Client connection lost with reason: 4
,09-13 16:10:02.001   874  1962 I ActivityManager: Process com.google.process.gapps (pid 1543) has died
,09-13 16:10:02.001   874  1962 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
,09-13 16:10:02.001   874  1962 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 10999ms
,09-13 16:10:02.001   874  1962 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 20999ms
,09-13 16:10:02.013  1751  1751 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-13 16:10:02.025   874   885 I ActivityManager: Start proc 4346:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,09-13 16:10:02.037   874  2164 I ActivityManager: Killing 3684:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-13 16:10:02.048  4271  4317 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:10:02.048  4271  4317 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 16:10:02.049  4271  4317 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-13 16:10:02.049  4271  4317 E AndroidRuntime: Process: android.process.acore, PID: 4271
09-13 16:10:02.049  4271  4317 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 16:10:02.049  4271  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 16:10:02.049  4271  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 16:10:02.049  4271  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 16:10:02.049  4271  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 16:10:02.049  4271  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 16:10:02.049  4271  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 16:10:02.049  4271  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 16:10:02.049  4271  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 16:10:02.049  4271  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 16:10:02.049  4271  4317 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 16:10:02.049  4271  4317 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 16:10:02.049  4271  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 16:10:02.049  4271  4317 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 16:10:02.049  4271  4317 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-13 16:10:02.049  4271  4317 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-13 16:10:02.049  4271  4317 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-13 16:10:02.049  4271  4317 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-13 16:10:02.049  4271  4317 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-13 16:10:02.049  4271  4317 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-13 16:10:02.049  4271  4317 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 16:10:02.049  4271  4317 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:10:02.049  4271  4317 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:10:02.049  4271  4317 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 16:10:02.052  4271  4298 I Process : Sending signal. PID: 4271 SIG: 9
,09-13 16:10:02.068  4333  4333 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 16:10:02.068  4333  4333 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 16:10:02.068  4333  4333 D AndroidRuntime: Shutting down VM

```
