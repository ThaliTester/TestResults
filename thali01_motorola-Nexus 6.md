#### Test 8362733784eab4b_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
09-08 13:33:52.939   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
09-08 13:33:53.584  3811  3811 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-08 13:33:53.588  3811  3811 D AndroidRuntime: CheckJNI is OFF
09-08 13:33:53.625  3811  3811 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-08 13:33:53.667  3811  3811 I Radio-JNI: register_android_hardware_Radio DONE
09-08 13:33:53.688  3811  3811 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-08 13:33:53.693   874  2035 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-08 13:33:53.737  2058  2411 W SearchService: Abort, client detached.
09-08 13:33:53.741  2058  2058 I HotwordDetector: Closing mic
09-08 13:33:53.742  2058  2330 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@3af035e
09-08 13:33:53.743  2058  2336 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-08 13:33:53.747  3811  3811 D AndroidRuntime: Shutting down VM
09-08 13:33:53.773   874   885 I ActivityManager: Start proc 3820:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-08 13:33:53.810   376  2338 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-08 13:33:53.811   376  2338 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-08 13:33:53.817   376  1280 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-08 13:33:53.819  2058  2335 I MicroRecognitionRnrImpl: Detection finished
09-08 13:33:53.819  2058  2332 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-08 13:33:53.861  3820  3820 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-08 13:33:53.911  3820  3820 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-08 13:33:53.920  3820  3820 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2423-2427)
09-08 13:33:53.920  3820  3820 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 13:33:53.937  3820  3820 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1cb8bf1}
09-08 13:33:53.937  3820  3820 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 13:33:53.937  3820  3820 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 13:33:53.943  3820  3820 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-08 13:33:53.945  3820  3820 E SysUtils: ApplicationContext is null in ApplicationStatus
09-08 13:33:53.963  3820  3820 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-08 13:33:53.972  3820  3820 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 13:33:53.972  3820  3820 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 13:33:53.973  3820  3820 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 13:33:53.973  3820  3820 I Adreno  : Build Date                       : 10/20/15
09-08 13:33:53.973  3820  3820 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 13:33:53.973  3820  3820 I Adreno  : Local Branch                     : M14
09-08 13:33:53.973  3820  3820 I Adreno  : Remote Branch                    : 
09-08 13:33:53.973  3820  3820 I Adreno  : Remote Branch                    : 
09-08 13:33:53.973  3820  3820 I Adreno  : Reconstruct Branch               : 
,09-08 13:33:54.036   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c55e06b:true
09-08 13:33:54.108  3820  3820 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-08 13:33:54.125  3820  3820 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
09-08 13:33:54.183  3820  3859 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-08 13:33:54.198  3820  3845 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
09-08 13:33:54.252  3820  3859 I OpenGLRenderer: Initialized EGL, version 1.4
09-08 13:33:54.322   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +562ms
09-08 13:33:54.327  1893  1893 I Keyboard.Facilitator: onFinishInput()
09-08 13:33:54.412  3820  3820 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3820
09-08 13:33:54.595  3820  3820 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-08 13:33:54.612   874  2033 I ActivityManager: Killing 2997:com.google.android.calendar/u0a37 (adj 15): empty #17
09-08 13:33:54.640   874  2033 I ActivityManager: Killing 3178:com.google.android.apps.maps/u0a65 (adj 15): empty #18
09-08 13:33:54.777  3820  3862 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1701381840
09-08 13:33:54.787  3820  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-08 13:33:54.787  3820  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-08 13:33:54.787  3820  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-08 13:33:54.787  3820  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-08 13:33:54.787  3820  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-08 13:33:54.787  3820  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bfb57a5 added. We now have 1 listener(s)
09-08 13:33:54.796  3820  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
09-08 13:33:54.798  3820  3862 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 13:33:54.800  3820  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 13:33:54.800  3820  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 13:33:54.807  3820  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-08 13:33:54.807  3820  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-08 13:33:54.807  3820  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-08 13:33:54.807  3820  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-08 13:33:54.807  3820  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-08 13:33:54.807  3820  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-08 13:33:54.807  3820  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-08 13:33:54.807  3820  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-08 13:33:54.807  3820  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-08 13:33:54.807  3820  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-08 13:33:54.807  3820  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-08 13:33:54.807  3820  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-08 13:33:54.807  3820  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-08 13:33:54.807  3820  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-08 13:33:54.807  3820  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa74b88 added. We now have 1 listener(s)
09-08 13:33:54.808  3820  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 13:33:54.812   874  1309 D WifiService: New client listening to asynchronous messages
09-08 13:33:54.812  3820  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 13:33:54.812  3820  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-08 13:33:54.812  3820  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-08 13:33:54.813  3820  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-08 13:33:54.813  3820  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-08 13:33:54.817  3820  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:33:54.818  3820  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
09-08 13:33:54.827  3820  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-08 13:33:54.827  3820  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:33:54.827  3820  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:33:54.827  3820  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:33:54.827  3820  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:33:54.827  3820  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:33:54.827  3820  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:33:54.827  3820  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:33:54.827  3820  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 13:33:54.827  3820  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-08 13:33:54.827  3820  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 13:33:54.828  3820  3862 I io.jxcore.node.LifeCycleMonitor: start: OK
09-08 13:33:54.831  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:33:54.837  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:33:54.861  3820  3820 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-08 13:33:55.965   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-08 13:33:56.163  3820  3869 W jxcore-log: Initializing JXcore engine
,09-08 13:33:56.163  3820  3869 W jxcore-log: JXcore engine is ready
,09-08 13:33:56.210  3869  3869 W Thread-325: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8951 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-08 13:33:56.210  3869  3869 W Thread-325: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11739]" dev="sockfs" ino=11739 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-08 13:33:56.210  3869  3869 W Thread-325: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-08 13:33:56.210  3869  3869 W Thread-325: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26241]" dev="sockfs" ino=26241 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-08 13:33:56.227  3820  3869 W jxcore-log: Starting JXcore engine
,09-08 13:33:56.341  3820  3869 W jxcore-log: Platform android
09-08 13:33:56.341  3820  3869 W jxcore-log: 
,09-08 13:33:56.341  3820  3869 W jxcore-log: Process ARCH arm
09-08 13:33:56.341  3820  3869 W jxcore-log: 
,09-08 13:33:56.526  3820  3869 I jxcore-log: JXcore Cordova bridge is ready!
09-08 13:33:56.526  3820  3869 I jxcore-log: 
09-08 13:33:56.527  3820  3869 W jxcore-log: JXcore engine is started
,09-08 13:33:56.534  3820  3862 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-08 13:33:56.541  3820  3820 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-08 13:33:58.993   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-08 13:34:02.023   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-08 13:34:04.030  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 13:34:04.037  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 13:34:04.038  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 13:34:04.056  1501  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 13:34:04.057  1501  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 13:34:04.057  1501  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 13:34:04.057  1501  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 13:34:04.071  3563  3563 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 13:34:04.071  3563  3563 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-08 13:34:04.072  3563  3563 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-08 13:34:05.046   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-08 13:34:05.368   874  1308 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-08 13:34:06.248  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-08 13:34:06.248  3820  3869 I jxcore-log: 
,09-08 13:34:06.251  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-08 13:34:06.251  3820  3869 I jxcore-log: 
,09-08 13:34:06.263  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:06.263  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:06.263  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:06.263  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:06.263  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:06.263  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:06.263  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:06.263  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 13:34:06.268  3820  3869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 13:34:06.271  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-08 13:34:06.271  3820  3869 I jxcore-log: 
,09-08 13:34:06.273  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-08 13:34:06.273  3820  3869 I jxcore-log: 
,09-08 13:34:06.772  2708  2910 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
,09-08 13:34:06.799  3820  3869 I jxcore-log: Unit Test app is loaded
09-08 13:34:06.799  3820  3869 I jxcore-log: 
,09-08 13:34:06.805  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:06.805  3820  3869 I jxcore-log: 
,09-08 13:34:06.811  3820  3869 D executeNativeTests: Running unit tests
,09-08 13:34:06.812  3820  3869 D BluetoothAdapter: enable(): BT is already enabled..!
,09-08 13:34:06.813   874  1989 D WifiService: setWifiEnabled: true pid=3820, uid=10000
09-08 13:34:06.813   874  1989 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 13:34:06.823  3820  3820 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-08 13:34:08.083   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-08 13:34:09.922  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 13:34:09.922  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7097b35 added. We now have 2 listener(s)
09-08 13:34:09.923  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 13:34:09.923  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 13:34:09.923  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 13:34:09.923  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 13:34:09.923  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@291cbca added. We now have 2 listener(s)
09-08 13:34:09.923  3820  3869 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 13:34:09.924  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 13:34:09.929  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 13:34:09.952  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:09.952  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:09.952  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:09.952  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:09.952  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:09.952  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:09.952  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:09.952  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 13:34:09.956  3820  3869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:09.956  3820  3869 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 13:34:09.967  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:09.969  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 13:34:09.969  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 13:34:09.969  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 13:34:09.970  3820  3869 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-08 13:34:09.971  3820  3869 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-08 13:34:09.971  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 13:34:09.971  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 13:34:09.971  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 13:34:09.971  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 13:34:09.971  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 13:34:09.971  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 13:34:09.972  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-08 13:34:09.972  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7097b35 removed from the list
,09-08 13:34:09.972  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:09.972  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@291cbca removed from the list
,09-08 13:34:09.973  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:09.973  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 13:34:09.973  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:09.979  3820  3869 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-08 13:34:09.981  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:09.981  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 13:34:09.981  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:09.982  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7097b35 not in the list
,09-08 13:34:09.982  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 13:34:09.982  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@291cbca not in the list
,09-08 13:34:09.983  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 13:34:09.984  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:09.984  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:09.993  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 13:34:09.993  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-08 13:34:09.993  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 13:34:09.993  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 13:34:09.993  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 13:34:09.993  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 13:34:09.994  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 13:34:09.994  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 13:34:09.994  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-08 13:34:09.994  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 13:34:09.994  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 13:34:09.994  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 13:34:09.994  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 13:34:09.994  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 13:34:09.994  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-08 13:34:09.995  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 13:34:09.995  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 13:34:09.995  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 13:34:09.995  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 13:34:09.995  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 13:34:09.995  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 13:34:09.995  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-08 13:34:09.995  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 13:34:09.995  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 13:34:09.995  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 13:34:09.995  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 13:34:09.996  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 13:34:09.996  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 13:34:09.996  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-08 13:34:09.996  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 13:34:09.996  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 13:34:09.996  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:09.996  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:09.996  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:09.997  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7097b35 not in the list
09-08 13:34:09.997  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:09.997  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@291cbca not in the list
,09-08 13:34:09.997  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:09.997  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:09.997  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:09.998  3820  3869 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-08 13:34:10.000  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 13:34:10.007  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:10.007  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:10.007  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:10.007  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:10.007  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:10.007  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:10.007  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:10.007  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 13:34:10.010  3820  3869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:10.010  3820  3869 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 13:34:10.010  3820  3869 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-08 13:34:10.010  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-08 13:34:10.011  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 13:34:10.011  3820  3869 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-08 13:34:10.011  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-08 13:34:10.012  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:10.012  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:10.012  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 13:34:10.014  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:10.014  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-08 13:34:10.014  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 13:34:10.015  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-08 13:34:10.015  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 13:34:10.015  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 13:34:10.015  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:10.015  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 13:34:10.017  3820  3881 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 13:34:10.019  3820  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-08 13:34:10.020  3820  3869 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 13:34:10.020  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 13:34:10.027  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 13:34:10.030  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 13:34:10.031  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 13:34:10.035  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-08 13:34:10.036  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 13:34:10.036  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
09-08 13:34:10.038  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-08 13:34:10.038  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 13:34:10.038  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-08 13:34:10.040  3820  3869 D BluetoothAdapter: STATE_ON
,09-08 13:34:10.048  2708  2917 D BtGatt.GattService: registerClient() - UUID=45de6b31-97b1-4814-8678-4f1381b55c89
,09-08 13:34:10.049  2708  2760 D BtGatt.GattService: onClientRegistered() - UUID=45de6b31-97b1-4814-8678-4f1381b55c89, clientIf=5
,09-08 13:34:10.051  3820  3832 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-08 13:34:10.054  2708  2762 D BtGatt.AdvertiseManager: message : 0
,09-08 13:34:10.060  2708  2762 D BtGatt.AdvertiseManager: starting multi advertising
,09-08 13:34:10.075  2708  2760 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-08 13:34:10.088  2708  2760 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-08 13:34:10.091  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-08 13:34:10.092  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 13:34:10.097  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 13:34:10.101  3820  3869 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 13:34:10.102  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 13:34:10.103  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-08 13:34:10.103  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-08 13:34:10.104  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-08 13:34:10.104  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-08 13:34:10.105  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-08 13:34:10.114  3820  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 13:34:10.116  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 13:34:10.609  3820  3869 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 13:34:10.610  3820  3869 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-08 13:34:10.610  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-08 13:34:10.611  3820  3869 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 13:34:10.611  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 13:34:10.611  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 13:34:10.612  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-08 13:34:10.613  3820  3881 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 13:34:10.613  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 13:34:10.613  3820  3881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-08 13:34:10.613  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 13:34:10.614  3820  3881 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 13:34:10.614  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 13:34:10.615  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 13:34:10.615  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 13:34:10.616  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-08 13:34:10.617  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 13:34:10.622  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 13:34:10.626  3820  3869 D BluetoothAdapter: STATE_ON
,09-08 13:34:10.627  3820  3869 D BluetoothLeScanner: could not find callback wrapper
09-08 13:34:10.628  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 13:34:10.628  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-08 13:34:10.631  2708  2762 D BtGatt.AdvertiseManager: message : 1
,09-08 13:34:10.632  2708  2762 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-08 13:34:10.654  2708  2760 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-08 13:34:10.654  2708  2760 D BtGatt.GattService: Client app is not null!
,09-08 13:34:10.657  2708  2909 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 13:34:10.658  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 13:34:10.659  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-08 13:34:10.660  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-08 13:34:10.660  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-08 13:34:10.661  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-08 13:34:10.664  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 13:34:10.665  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 13:34:10.668  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 13:34:10.670  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 13:34:10.675  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 13:34:10.675  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 13:34:10.676  3820  3820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-08 13:34:10.677  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-08 13:34:10.678  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 13:34:10.679  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 13:34:10.679  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 13:34:10.682  3820  3869 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-08 13:34:10.683  3820  3869 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-08 13:34:10.684  3820  3869 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,09-08 13:34:10.684  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,09-08 13:34:10.686  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 13:34:10.686  3820  3869 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-08 13:34:10.687  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-08 13:34:10.687  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 13:34:10.690  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-08 13:34:10.691  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
,09-08 13:34:10.691  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-08 13:34:10.691  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 13:34:10.691  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 13:34:10.691  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 13:34:10.691  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:10.691  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 13:34:10.693  3820  3884 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 13:34:10.695  3820  3869 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 13:34:10.696  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 13:34:10.696  3820  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-08 13:34:10.700  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 13:34:10.701  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 13:34:10.701  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 13:34:10.703  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-08 13:34:10.703  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 13:34:10.703  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 F8 CF C5 D9 E5 61
,09-08 13:34:10.703  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 13:34:10.703  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 13:34:10.704  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-08 13:34:10.704  3820  3869 D BluetoothAdapter: STATE_ON
09-08 13:34:10.707  2708  2721 D BtGatt.GattService: registerClient() - UUID=68d6d619-e4cf-429d-8c94-6b034337ed67
,09-08 13:34:10.708  2708  2760 D BtGatt.GattService: onClientRegistered() - UUID=68d6d619-e4cf-429d-8c94-6b034337ed67, clientIf=5
09-08 13:34:10.709  3820  3832 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-08 13:34:10.710  2708  2762 D BtGatt.AdvertiseManager: message : 0
,09-08 13:34:10.715  2708  2762 D BtGatt.AdvertiseManager: starting multi advertising
,09-08 13:34:10.729  2708  2760 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-08 13:34:10.738  2708  2760 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-08 13:34:10.739  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-08 13:34:10.739  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 13:34:10.741  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 13:34:10.743  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 13:34:10.743  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-08 13:34:10.743  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-08 13:34:10.743  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-08 13:34:10.743  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-08 13:34:10.743  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-08 13:34:10.744  3820  3869 I io.jxcore.node.ConnectionHelper: start: OK
09-08 13:34:10.746  3820  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 13:34:10.747  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 13:34:10.754  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 13:34:10.755  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 13:34:10.755  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 13:34:10.755  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 13:34:10.755  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 13:34:10.755  3820  3884 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 13:34:10.756  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 13:34:10.756  3820  3884 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 13:34:10.756  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 13:34:10.756  3820  3884 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-08 13:34:10.756  3820  3820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 13:34:10.756  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7097b35 not in the list
09-08 13:34:10.757  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:10.757  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 13:34:10.757  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 13:34:10.757  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 13:34:10.757  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 13:34:10.759  3820  3869 D BluetoothAdapter: STATE_ON
09-08 13:34:10.759  3820  3869 D BluetoothLeScanner: could not find callback wrapper
09-08 13:34:10.760  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 13:34:10.760  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-08 13:34:10.761  2708  2762 D BtGatt.AdvertiseManager: message : 1
09-08 13:34:10.763  2708  2762 D BtGatt.AdvertiseManager: stop advertise for client 5
09-08 13:34:10.781  2708  2760 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-08 13:34:10.781  2708  2760 D BtGatt.GattService: Client app is not null!
09-08 13:34:10.784  2708  2917 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 13:34:10.785  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 13:34:10.785  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-08 13:34:10.786  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-08 13:34:10.786  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-08 13:34:10.787  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-08 13:34:10.788  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 13:34:10.789  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 13:34:10.789  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 13:34:10.790  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 13:34:10.792  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 13:34:10.792  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 13:34:10.792  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 13:34:10.792  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@291cbca not in the list
09-08 13:34:10.792  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:10.793  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:10.794  3820  3869 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-08 13:34:10.800  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:10.812  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:10.812  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:10.812  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:10.812  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:10.812  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:10.812  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:10.812  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:10.812  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 13:34:10.816  3820  3869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:10.817  3820  3869 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 13:34:10.817  3820  3869 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-08 13:34:10.817  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-08 13:34:10.817  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 13:34:10.817  3820  3869 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-08 13:34:10.817  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 13:34:10.818  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:10.821  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 13:34:10.821  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 13:34:10.822  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:10.822  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 13:34:10.822  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 13:34:10.823  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 13:34:10.823  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:10.823  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 13:34:10.826  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:10.826  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 13:34:10.831  3820  3869 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 13:34:10.832  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 13:34:10.834  3820  3886 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 13:34:10.837  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 13:34:10.838  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 13:34:10.838  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 13:34:10.840  3820  3886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-08 13:34:10.841  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-08 13:34:10.842  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 13:34:10.842  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
09-08 13:34:10.842  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 13:34:10.843  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 13:34:10.843  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-08 13:34:10.844  3820  3869 D BluetoothAdapter: STATE_ON
09-08 13:34:10.847  2708  2917 D BtGatt.GattService: registerClient() - UUID=0d4976a6-ef6f-4d60-b04a-f5e6a114c031
09-08 13:34:10.848  2708  2760 D BtGatt.GattService: onClientRegistered() - UUID=0d4976a6-ef6f-4d60-b04a-f5e6a114c031, clientIf=5
09-08 13:34:10.848  3820  3832 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-08 13:34:10.849  2708  2762 D BtGatt.AdvertiseManager: message : 0
09-08 13:34:10.854  2708  2762 D BtGatt.AdvertiseManager: starting multi advertising
09-08 13:34:10.869  2708  2760 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-08 13:34:10.882  2708  2760 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-08 13:34:10.883  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-08 13:34:10.883  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 13:34:10.888  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 13:34:10.891  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 13:34:10.891  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-08 13:34:10.891  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-08 13:34:10.891  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-08 13:34:10.892  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-08 13:34:10.892  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-08 13:34:10.893  3820  3869 I io.jxcore.node.ConnectionHelper: start: OK
09-08 13:34:10.896  3820  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-08 13:34:10.896  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 13:34:11.397  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-08 13:34:11.398  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 13:34:11.398  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-08 13:34:11.398  3820  3869 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 13:34:11.399  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-08 13:34:11.399  3820  3869 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 13:34:11.399  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 13:34:11.400  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 13:34:11.400  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 13:34:11.401  3820  3886 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 13:34:11.402  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 13:34:11.402  3820  3886 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 13:34:11.402  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 13:34:11.402  3820  3886 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 13:34:11.402  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 13:34:11.403  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 13:34:11.403  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 13:34:11.403  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 13:34:11.404  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 13:34:11.404  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-08 13:34:11.406  3820  3869 D BluetoothAdapter: STATE_ON
,09-08 13:34:11.407  3820  3869 D BluetoothLeScanner: could not find callback wrapper
09-08 13:34:11.407  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 13:34:11.407  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-08 13:34:11.410  2708  2762 D BtGatt.AdvertiseManager: message : 1
09-08 13:34:11.411  2708  2762 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-08 13:34:11.434  2708  2760 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-08 13:34:11.435  2708  2760 D BtGatt.GattService: Client app is not null!
,09-08 13:34:11.438  2708  2721 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 13:34:11.439  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 13:34:11.439  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-08 13:34:11.440  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-08 13:34:11.440  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-08 13:34:11.440  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-08 13:34:11.444  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 13:34:11.444  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 13:34:11.445  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 13:34:11.447  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 13:34:11.451  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 13:34:11.451  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 13:34:11.452  3820  3820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 13:34:11.452  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 13:34:11.453  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 13:34:11.454  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 13:34:11.457  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:11.457  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:11.457  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 13:34:11.457  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7097b35 not in the list
09-08 13:34:11.458  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 13:34:11.458  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@291cbca not in the list
09-08 13:34:11.458  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 13:34:11.459  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:11.461  3820  3869 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-08 13:34:11.461  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:11.461  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:11.461  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:11.461  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7097b35 not in the list
09-08 13:34:11.461  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:11.461  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@291cbca not in the list
09-08 13:34:11.462  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:11.462  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:11.462  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:11.463  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 13:34:11.463  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:11.463  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:11.463  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:11.463  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7097b35 not in the list
,09-08 13:34:11.463  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:11.463  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@291cbca not in the list
09-08 13:34:11.463  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 13:34:11.463  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:11.463  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:11.464  3820  3869 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-08 13:34:11.464  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 13:34:11.464  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:11.465  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:11.465  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7097b35 not in the list
,09-08 13:34:11.465  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:11.465  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@291cbca not in the list
09-08 13:34:11.465  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:11.465  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 13:34:11.465  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:11.466  3820  3869 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-08 13:34:11.466  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 13:34:11.466  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:11.466  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:11.466  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7097b35 not in the list
09-08 13:34:11.466  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 13:34:11.466  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@291cbca not in the list
,09-08 13:34:11.466  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:11.467  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 13:34:11.467  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:11.467  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 13:34:11.468  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 13:34:11.468  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 13:34:11.468  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 13:34:11.468  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 13:34:11.468  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 13:34:11.468  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:11.468  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:11.468  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:11.468  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7097b35 not in the list
09-08 13:34:11.468  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:11.469  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@291cbca not in the list
,09-08 13:34:11.469  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:11.469  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:11.469  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:11.470  3820  3869 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 13:34:11.470  3820  3869 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 13:34:11.470  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 13:34:11.473  3820  3869 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 13:34:11.473  3820  3869 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-08 13:34:11.474  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 13:34:11.474  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 13:34:11.474  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 13:34:11.474  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-08 13:34:11.474  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 13:34:11.474  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 13:34:11.474  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 13:34:11.474  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 13:34:11.474  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 13:34:11.474  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 13:34:11.474  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 13:34:11.475  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-08 13:34:11.475  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 13:34:11.475  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 13:34:11.475  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 13:34:11.475  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 13:34:11.475  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 13:34:11.475  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-08 13:34:11.475  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 13:34:11.475  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 13:34:11.475  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-08 13:34:11.475  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 13:34:11.476  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-08 13:34:11.476  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 13:34:11.476  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 13:34:11.476  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 13:34:11.476  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 13:34:11.476  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 13:34:11.477  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-08 13:34:11.477  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-08 13:34:11.477  3820  3869 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-08 13:34:11.477  3820  3869 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-08 13:34:11.478  3820  3869 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-08 13:34:11.478  3820  3869 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-08 13:34:11.478  3820  3869 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-08 13:34:11.478  3820  3869 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-08 13:34:11.478  3820  3869 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 13:34:11.478  3820  3869 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-08 13:34:11.478  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-08 13:34:11.483  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-08 13:34:11.483  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-08 13:34:11.484  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-08 13:34:11.484  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-08 13:34:11.484  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-08 13:34:11.484  3820  3869 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-08 13:34:11.485  3820  3869 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 13:34:11.485  3820  3869 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-08 13:34:11.486  3820  3890 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 426)
09-08 13:34:11.486  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 13:34:11.486  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:11.486  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:11.486  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-08 13:34:11.487  3820  3890 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 13:34:11.487  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7097b35 not in the list
09-08 13:34:11.487  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:11.487  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@291cbca not in the list
,09-08 13:34:11.487  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:11.487  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:11.487  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:11.489  3820  3869 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-08 13:34:11.489  3820  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 426
09-08 13:34:11.489  3820  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 426)
09-08 13:34:11.490  3820  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 426)
,09-08 13:34:11.490  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:11.490  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:11.490  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:11.490  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7097b35 not in the list
,09-08 13:34:11.490  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 13:34:11.490  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@291cbca not in the list
09-08 13:34:11.490  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:11.490  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:11.490  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:11.491  3820  3869 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-08 13:34:11.491  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:11.492  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:11.492  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:11.492  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7097b35 not in the list
09-08 13:34:11.492  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:11.492  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@291cbca not in the list
09-08 13:34:11.492  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 13:34:11.492  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:11.492  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:11.493  3820  3890 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 426)
09-08 13:34:11.495  3820  3869 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,09-08 13:34:11.495  3820  3869 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-08 13:34:11.495  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-08 13:34:11.496  3820  3869 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-08 13:34:11.496  3820  3869 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-08 13:34:11.496  3820  3869 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-08 13:34:11.496  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 13:34:11.496  3820  3869 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,09-08 13:34:11.496  3820  3869 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 13:34:11.497  3820  3869 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,09-08 13:34:11.497  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 13:34:11.497  3820  3869 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-08 13:34:11.497  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:11.497  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 13:34:11.497  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:11.497  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7097b35 not in the list
,09-08 13:34:11.498  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:11.498  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@291cbca not in the list
,09-08 13:34:11.498  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 13:34:11.498  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 13:34:11.498  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:11.500  3820  3869 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-08 13:34:11.502  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:11.506  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:11.506  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:11.506  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:11.506  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:11.506  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:11.506  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:11.506  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:11.506  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 13:34:11.508  3820  3869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:11.508  3820  3869 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 13:34:11.508  3820  3869 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-08 13:34:11.508  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-08 13:34:11.509  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 13:34:11.509  3820  3869 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-08 13:34:11.509  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 13:34:11.509  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 13:34:11.510  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 13:34:11.510  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:11.511  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 13:34:11.511  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 13:34:11.511  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-08 13:34:11.511  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 13:34:11.511  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 13:34:11.511  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 13:34:11.515  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:11.515  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 13:34:11.515  3820  3892 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 13:34:11.515  3820  3869 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 13:34:11.516  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 13:34:11.517  3820  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-08 13:34:11.519  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 13:34:11.520  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 13:34:11.520  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 13:34:11.521  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-08 13:34:11.522  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 13:34:11.522  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 F8 CF C5 D9 E5 61
,09-08 13:34:11.522  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 13:34:11.522  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-08 13:34:11.522  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-08 13:34:11.523  3820  3869 D BluetoothAdapter: STATE_ON
09-08 13:34:11.525  2708  2917 D BtGatt.GattService: registerClient() - UUID=f8c130e1-5008-4d99-8238-b3e0aae59233
09-08 13:34:11.525  2708  2760 D BtGatt.GattService: onClientRegistered() - UUID=f8c130e1-5008-4d99-8238-b3e0aae59233, clientIf=5
09-08 13:34:11.526  3820  3831 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-08 13:34:11.527  2708  2762 D BtGatt.AdvertiseManager: message : 0
,09-08 13:34:11.529  2708  2762 D BtGatt.AdvertiseManager: starting multi advertising
,09-08 13:34:11.540  2708  2760 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-08 13:34:11.546  2708  2760 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-08 13:34:11.547  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-08 13:34:11.547  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 13:34:11.549  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 13:34:11.550  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 13:34:11.550  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-08 13:34:11.550  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-08 13:34:11.550  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-08 13:34:11.550  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-08 13:34:11.550  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-08 13:34:11.551  3820  3869 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 13:34:11.553  3820  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-08 13:34:11.553  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 13:34:12.053  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-08 13:34:12.054  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 13:34:12.054  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 13:34:12.055  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 13:34:12.056  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 13:34:12.057  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 13:34:12.058  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 13:34:12.061  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 13:34:12.060  3820  3892 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 13:34:12.061  3820  3892 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 13:34:12.061  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 13:34:12.061  3820  3892 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 13:34:12.061  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7097b35 not in the list
09-08 13:34:12.061  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 13:34:12.062  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:12.062  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 13:34:12.062  3820  3820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 13:34:12.062  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 13:34:12.062  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 13:34:12.063  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 13:34:12.066  3820  3869 D BluetoothAdapter: STATE_ON
09-08 13:34:12.066  3820  3869 D BluetoothLeScanner: could not find callback wrapper
09-08 13:34:12.066  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 13:34:12.067  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-08 13:34:12.069  2708  2762 D BtGatt.AdvertiseManager: message : 1
09-08 13:34:12.070  2708  2762 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-08 13:34:12.092  2708  2760 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-08 13:34:12.093  2708  2760 D BtGatt.GattService: Client app is not null!
09-08 13:34:12.095  2708  2722 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 13:34:12.096  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 13:34:12.097  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-08 13:34:12.098  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-08 13:34:12.100  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-08 13:34:12.101  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-08 13:34:12.104  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 13:34:12.104  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 13:34:12.105  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 13:34:12.106  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 13:34:12.110  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 13:34:12.111  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 13:34:12.111  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 13:34:12.112  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@291cbca not in the list
,09-08 13:34:12.112  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:12.112  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:12.120  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 13:34:12.120  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 13:34:12.120  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:12.120  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7097b35 not in the list
,09-08 13:34:12.121  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:12.121  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@291cbca not in the list,
09-08 13:34:12.121  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 13:34:12.122  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:12.122  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:12.125  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-08 13:34:12.125  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 13:34:12.127  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 13:34:12.128  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 13:34:12.128  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-08 13:34:12.128  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 13:34:12.128  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-08 13:34:12.128  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 13:34:12.130  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 13:34:12.130  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 13:34:12.131  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-08 13:34:12.131  3820  3895 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 13:34:12.131  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 13:34:12.132  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:12.133  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 13:34:12.133  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-08 13:34:12.134  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7097b35 not in the list
09-08 13:34:12.134  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:12.134  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 13:34:12.135  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 13:34:12.136  3820  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 13:34:12.136  3820  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-08 13:34:12.135  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 13:34:12.136  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:12.136  3820  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-08 13:34:12.136  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:12.138  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 13:34:12.138  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@291cbca not in the list
,09-08 13:34:12.138  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:12.139  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:12.138  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 13:34:12.139  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:12.139  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 13:34:12.139  3820  3820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 13:34:12.139  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 13:34:12.141  3820  3869 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-08 13:34:12.141  3820  3869 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-08 13:34:12.141  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 13:34:12.141  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 13:34:12.142  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:12.142  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 13:34:12.142  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:12.142  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7097b35 not in the list
,09-08 13:34:12.142  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:12.142  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@291cbca not in the list,
09-08 13:34:12.142  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:12.142  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:12.142  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:12.150  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 13:34:12.150  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:12.150  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:12.150  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7097b35 not in the list
09-08 13:34:12.150  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 13:34:12.150  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@291cbca not in the list
09-08 13:34:12.150  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:12.150  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,09-08 13:34:12.151  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:12.152  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:12.152  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 13:34:12.152  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:12.152  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7097b35 not in the list
,09-08 13:34:12.152  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:12.152  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@291cbca not in the list
,09-08 13:34:12.152  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 13:34:12.152  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:12.152  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:12.153  3820  3869 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-08 13:34:12.154  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-08 13:34:12.154  3820  3869 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-08 13:34:12.154  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-08 13:34:12.154  3820  3869 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-08 13:34:12.154  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 13:34:12.157  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-08 13:34:12.157  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-08 13:34:12.158  3820  3869 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-08 13:34:12.158  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 13:34:12.158  3820  3869 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-08 13:34:12.158  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 13:34:12.158  3820  3869 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-08 13:34:12.158  3820  3869 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-08 13:34:12.159  3820  3869 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-08 13:34:12.159  3820  3869 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-08 13:34:12.160  3820  3869 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-08 13:34:12.160  3820  3869 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-08 13:34:12.160  3820  3869 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-08 13:34:12.160  3820  3869 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-08 13:34:12.164  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 13:34:12.164  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb72f2b added. We now have 2 listener(s)
,09-08 13:34:12.166  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 13:34:12.166  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 13:34:12.166  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 13:34:12.166  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 13:34:12.166  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa05f88 added. We now have 2 listener(s)
09-08 13:34:12.166  3820  3869 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 13:34:12.167  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 13:34:12.174  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 13:34:12.182  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:12.182  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:12.182  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:12.182  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:12.182  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:12.182  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:12.182  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:12.182  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 13:34:12.185  3820  3869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 13:34:12.185  3820  3869 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 13:34:12.189  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 13:34:12.189  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:12.189  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:12.190  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 13:34:12.190  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 13:34:12.190  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb72f2b removed from the list
09-08 13:34:12.190  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:12.190  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aa05f88 removed from the list
,09-08 13:34:12.194  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:12.194  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:12.194  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:12.197  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 13:34:12.197  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2b1546 added. We now have 2 listener(s),
,09-08 13:34:12.203  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 13:34:12.203  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 13:34:12.203  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 13:34:12.204  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 13:34:12.204  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f79307 added. We now have 2 listener(s)
,09-08 13:34:12.205  3820  3869 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 13:34:12.206  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 13:34:12.212  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 13:34:12.221  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:12.221  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:12.221  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:12.221  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:12.221  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:12.221  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:12.221  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:12.221  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 13:34:12.227  3820  3869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 13:34:12.228  3820  3869 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 13:34:12.228  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:12.228  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 13:34:12.229  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 13:34:12.229  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 13:34:12.229  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2b1546 removed from the list
09-08 13:34:12.230  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:12.230  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5f79307 removed from the list
,09-08 13:34:12.233  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:12.233  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:12.233  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:12.236  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 13:34:12.237  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d479a5d added. We now have 2 listener(s)
,09-08 13:34:12.241  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:12.243  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 13:34:12.243  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 13:34:12.244  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 13:34:12.244  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 13:34:12.244  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9733fd2 added. We now have 2 listener(s)
,09-08 13:34:12.245  3820  3869 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 13:34:12.246  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 13:34:12.252  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 13:34:12.261  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:12.261  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:12.261  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:12.261  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:12.261  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:12.261  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:12.261  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:12.261  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 13:34:12.266  3820  3869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 13:34:12.267  3820  3869 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 13:34:12.272   874  1982 D WifiService: setWifiEnabled: false pid=3820, uid=10000
,09-08 13:34:12.272   874  1982 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 13:34:12.272  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:12.278  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:12.307  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 13:34:12.313   874  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-08 13:34:12.313   874  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-08 13:34:12.313   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 13:34:12.313   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 13:34:12.333   874  2092 D DhcpClient: Clearing IP address
,09-08 13:34:12.334   372   872 D CommandListener: Setting iface cfg
,09-08 13:34:12.339   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-08 13:34:12.342   874  2103 D DhcpClient: Receive thread stopped
,09-08 13:34:12.348  1501  2529 V NativeCrypto: Read error: ssl=0x9b2cb000: I/O error during system call, Connection timed out
,09-08 13:34:12.353   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-08 13:34:12.354   874  1308 D WifiStateMachine: Start Disconnecting Watchdog 1
09-08 13:34:12.354   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-08 13:34:12.355  1501  2529 V NativeCrypto: SSL shutdown failed: ssl=0x9b2cb000: I/O error during system call, Broken pipe
09-08 13:34:12.357   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 13:34:12.360   372   872 D CommandListener: Clearing all IP addresses on wlan0
09-08 13:34:12.365   395   395 E Parcel  : Reading a NULL string not supported here.
,09-08 13:34:12.374   874  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-08 13:34:12.379   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 13:34:12.388  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,09-08 13:34:12.388  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:12.388  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:12.388  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 13:34:12.388  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:12.388  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 13:34:12.388  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 13:34:12.388  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 13:34:12.389   874  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-08 13:34:12.393  1882  2318 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 13:34:12.393  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 13:34:12.399  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:12.399  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:12.399  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:12.399  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
,09-08 13:34:12.399  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:12.399  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 13:34:12.399  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 13:34:12.399  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 13:34:12.400  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 13:34:12.401   874   887 I ActivityManager: Start proc 3899:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-08 13:34:12.416   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 13:34:12.435  3899  3899 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-08 13:34:12.441   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 13:34:12.441   874  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-08 13:34:12.442   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:12.443   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-08 13:34:12.447  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:12.448  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:12.451  3472  3472 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@97e78b3 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-08 13:34:12.451  2058  2058 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-08 13:34:12.479  3899  3899 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-08 13:34:12.493  1724  1724 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 13:34:12.496  1724  1724 D SystemUpdateService: onCreate
,09-08 13:34:12.500  1724  1724 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 13:34:12.505   372   872 E Netd    : netlink response contains error (No such file or directory)
,09-08 13:34:12.510  1724  1724 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 13:34:12.515  1724  2505 I iu.UploadsManager: num queued entries: 0
,09-08 13:34:12.516  1724  3930 I SystemUpdateService: active receiver: enabled
,09-08 13:34:12.518  1724  1724 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 13:34:12.519  1724  1724 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 13:34:12.528  1724  2505 I iu.UploadsManager: num updated entries: 0
,09-08 13:34:12.529  1724  2505 I iu.SyncManager: NEXT; no task
,09-08 13:34:12.531   874  2035 I ActivityManager: Start proc 3932:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-08 13:34:12.534  1724  3930 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 13:34:12.535  1724  3930 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-08 13:34:12.535  1724  3930 I SystemUpdateService: now status is 0 (complete)
09-08 13:34:12.535  1724  3930 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-08 13:34:12.536  1724  3930 I SystemUpdateService: file has been verified
09-08 13:34:12.536  1724  3930 I SystemUpdateService: OTA package size = 12249756
,09-08 13:34:12.542  1724  3930 I SystemUpdateService: showing system update notification
,09-08 13:34:12.552  1724  1724 D SystemUpdateService: onDestroy
,09-08 13:34:12.553   874  1391 I ActivityManager: Killing 3276:com.google.android.gm/u0a78 (adj 15): empty #17
,09-08 13:34:12.572  3932  3932 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-08 13:34:12.575  3932  3932 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:12.586  3932  3932 D SprintDMHelper: simOperator: 
,09-08 13:34:12.586  3932  3932 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 13:34:12.625   874  1391 I ActivityManager: Start proc 3944:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-08 13:34:12.626   874  1391 I ActivityManager: Killing 3472:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-08 13:34:12.640  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 13:34:12.739   874   885 I ActivityManager: Start proc 3959:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-08 13:34:12.742  3137  3958 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-08 13:34:12.747   874  1384 I ActivityManager: Killing 2782:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-08 13:34:12.798  3959  3959 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-08 13:34:12.856  3959  3959 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-08 13:34:12.856  3959  3959 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-08 13:34:12.856  3959  3959 I GAv4    :   adb logcat -s GAv4
,09-08 13:34:12.877  3959  3959 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-08 13:34:12.882  3959  3959 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-08 13:34:12.912  3959  3977 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-08 13:34:13.011  3959  3959 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-08 13:34:13.054  3959  3959 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-08 13:34:13.062  3959  3959 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1566-1569)
,09-08 13:34:13.062  3959  3959 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 13:34:13.074  3959  3959 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {42a7415}
,09-08 13:34:13.075  3959  3959 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 13:34:13.075  3959  3959 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-08 13:34:13.085  3959  3959 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-08 13:34:13.087  3959  3959 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 13:34:13.103  3959  3959 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-08 13:34:13.119  3959  3959 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-08 13:34:13.119  3959  3959 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 13:34:13.119  3959  3959 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 13:34:13.119  3959  3959 I Adreno  : Build Date                       : 10/20/15
09-08 13:34:13.119  3959  3959 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 13:34:13.119  3959  3959 I Adreno  : Local Branch                     : M14
09-08 13:34:13.119  3959  3959 I Adreno  : Remote Branch                    : 
09-08 13:34:13.119  3959  3959 I Adreno  : Remote Branch                    : 
09-08 13:34:13.119  3959  3959 I Adreno  : Reconstruct Branch               : 
,09-08 13:34:13.176  3959  4006 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-08 13:34:13.186  3959  3959 I NSApplication: Starting up...
,09-08 13:34:13.221   874  2035 I ActivityManager: Start proc 4011:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-08 13:34:13.222   874  2035 I ActivityManager: Killing 1669:android.process.acore/u0a5 (adj 15): empty #17
09-08 13:34:13.223   278   278 E lowmemorykiller: Error writing /proc/1669/oom_score_adj; errno=22
,09-08 13:34:13.290  4011  4011 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-08 13:34:13.478   874  1384 I ActivityManager: Killing 3676:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-08 13:34:15.288   874   885 D WifiService: setWifiEnabled: true pid=3820, uid=10000
,09-08 13:34:15.289   874   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 13:34:15.303   874  1308 D WifiConfigStore: Loading config and enabling all networks 
,09-08 13:34:15.319  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:15.319  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:15.319  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:15.319  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:15.319  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:15.319  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 13:34:15.319  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 13:34:15.319  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 13:34:15.324  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 13:34:15.333  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:15.333  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:15.333  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:15.333  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:15.333  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:15.333  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 13:34:15.333  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 13:34:15.333  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 13:34:15.334   874  1308 D WifiConfigStore: loaded 0 passpoint configs
,09-08 13:34:15.334   874  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-08 13:34:15.335   874  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-08 13:34:15.336   874  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-08 13:34:15.336   874  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-08 13:34:15.337   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-08 13:34:15.337   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-08 13:34:15.339  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 13:34:15.350   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-08 13:34:15.352   372   872 D CommandListener: Setting iface cfg
,09-08 13:34:15.352   874  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=12.50 rxSuccessRate=16.75 delta 1000 -> 994
,09-08 13:34:15.352   874  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-08 13:34:15.353   874  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-08 13:34:15.355   874  1307 D WifiNative-HAL: p2pGetDeviceAddress
09-08 13:34:15.356   874  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-08 13:34:15.361   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-08 13:34:15.361   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 13:34:15.367   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 13:34:15.417   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 13:34:15.419  1460  1460 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 13:34:16.618  2708  2899 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-08 13:34:16.619  2708  2906 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
,09-08 13:34:16.737  1460  1460 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 13:34:16.793  1460  1460 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 13:34:16.793  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 13:34:16.798   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 13:34:16.810   874  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 13:34:16.811   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-08 13:34:16.811   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 13:34:16.834   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 13:34:16.855   372   872 D CommandListener: Setting iface cfg
,09-08 13:34:16.856   874  1308 D WifiStateMachine: Start Dhcp Watchdog 2
,09-08 13:34:16.875   874  1310 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-08 13:34:16.883   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 13:34:16.906   874  4037 D DhcpClient: Receive thread started
,09-08 13:34:16.989   874  1308 E native  : do suspend false
,09-08 13:34:17.011   874  2092 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 13:34:18.306  3820  3869 D BluetoothAdapter: enable(): BT is already enabled..!
,09-08 13:34:19.333  2708  2756 D BluetoothAdapterState: Current state: ON, message: 23
,09-08 13:34:19.333  2708  2756 D BluetoothAdapterProperties: Setting state to 13
09-08 13:34:19.333  2708  2756 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-08 13:34:19.335  2708  2756 D BluetoothAdapterProperties: onBluetoothDisable()
,09-08 13:34:19.342  2708  2756 I BluetoothAdapterState: Entering PendingCommandState
,09-08 13:34:19.352  2708  2708 D BluetoothMapService: onReceive
,09-08 13:34:19.352  2708  2708 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-08 13:34:19.353  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 13:34:19.354  2708  2708 D BluetoothMapService: STATE_TURNING_OFF
09-08 13:34:19.354  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:19.354  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:19.354  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:19.354  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:19.354  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 13:34:19.354  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 13:34:19.354  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 13:34:19.354  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 13:34:19.355  2708  2708 D BluetoothMapService: MAP Service closeService in
,09-08 13:34:19.355  2708  2708 D BluetoothMapMasInstance0: MAP Service shutdown
09-08 13:34:19.355  2708  2708 D ObexServerSockets0: shutdown(block = true)
09-08 13:34:19.356  2708  2918 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-08 13:34:19.356  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 13:34:19.357  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 13:34:19.358  2708  2708 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-08 13:34:19.359  2708  2919 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-08 13:34:19.360  2708  2906 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-08 13:34:19.360  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 13:34:19.361  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:19.361  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:19.361  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:19.361  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:19.361  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false,
09-08 13:34:19.361  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 13:34:19.361  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 13:34:19.361  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 13:34:19.361  2708  2708 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 13:34:19.361  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 13:34:19.361  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 13:34:19.361  2708  2708 I BtOppRfcommListener: stopping Accept Thread
09-08 13:34:19.362  2708  3480 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-08 13:34:19.363  2708  3480 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 13:34:19.372   874   887 I ActivityManager: Start proc 4044:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-08 13:34:19.373  2708  2760 D BluetoothAdapterProperties: Scan Mode:20
09-08 13:34:19.373  2708  2756 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-08 13:34:19.378  2708  2708 D HeadsetService: Received stop request...Stopping profile...
09-08 13:34:19.378   874  2092 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 13:34:19.380  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:19.383   874   874 D BluetoothHeadset: Proxy object disconnected
,09-08 13:34:19.383   874   874 D BluetoothHeadset: Proxy object disconnected
09-08 13:34:19.383   874   874 D BluetoothHeadset: Proxy object disconnected
09-08 13:34:19.383  1973  1987 D BluetoothHeadset: Proxy object disconnected
09-08 13:34:19.384  1365  2110 D BluetoothHeadset: Proxy object disconnected
09-08 13:34:19.384  1365  1365 D HeadsetProfile: Bluetooth service disconnected
,09-08 13:34:19.384  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:19.385  2708  2708 D A2dpService: Received stop request...Stopping profile...
09-08 13:34:19.386  2708  2912 D A2dpStateMachine: Exit Disconnected: -1
09-08 13:34:19.387  1365  1365 D BluetoothA2dp: Proxy object disconnected
09-08 13:34:19.388   874   874 D BluetoothA2dp: Proxy object disconnected
09-08 13:34:19.388  2708  2708 V BluetoothAdapterState: isTurningOff()=true
09-08 13:34:19.388  2708  2708 V BluetoothAdapterState: isTurningOn()=false
09-08 13:34:19.388  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
09-08 13:34:19.388  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 13:34:19.389  2708  2708 D HidService: Received stop request...Stopping profile...
09-08 13:34:19.389  2708  2708 D HidService: Stopping Bluetooth HidService
09-08 13:34:19.391  1365  1365 D BluetoothInputDevice: Proxy object disconnected
09-08 13:34:19.391  1365  1365 D HidProfile: Bluetooth service disconnected
,09-08 13:34:19.392  2708  2708 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-08 13:34:19.392  2708  2708 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-08 13:34:19.393  2708  2760 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-08 13:34:19.393  2708  2899 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 13:34:19.393  2708  2899 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 13:34:19.393  2708  2899 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 13:34:19.393  2708  2760 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-08 13:34:19.393  2708  2708 D HealthService: Received stop request...Stopping profile...
09-08 13:34:19.395  2708  2708 D PanService: Received stop request...Stopping profile...
,09-08 13:34:19.396  1365  1365 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 13:34:19.396  1365  1365 D PanProfile: Bluetooth service disconnected
,09-08 13:34:19.397  2708  2708 V BluetoothAdapterState: isTurningOff()=true
09-08 13:34:19.397  2708  2708 V BluetoothAdapterState: isTurningOn()=false
09-08 13:34:19.397  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
09-08 13:34:19.400  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false
09-08 13:34:19.402  2708  2708 D BluetoothMapService: Received stop request...Stopping profile...
09-08 13:34:19.402  2708  2708 D BluetoothMapService: stop()
09-08 13:34:19.403  2708  2899 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 13:34:19.403  2708  2899 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 13:34:19.403  2708  2899 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 13:34:19.403  2708  2899 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 13:34:19.403  2708  2899 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 13:34:19.403  2708  2899 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 13:34:19.403  2708  2760 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-08 13:34:19.403  2708  2708 D BluetoothMapAppObserver: deinitObservers()
09-08 13:34:19.403  2708  2708 D BluetoothMapAppObserver: removeReceiver()
,09-08 13:34:19.404  1365  1365 D BluetoothMap: Proxy object disconnected
09-08 13:34:19.405  1365  1365 D MapProfile: Bluetooth service disconnected
09-08 13:34:19.405  2708  2708 V BluetoothAdapterState: isTurningOff()=true
09-08 13:34:19.405  2708  2708 V BluetoothAdapterState: isTurningOn()=false
,09-08 13:34:19.405  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
09-08 13:34:19.405  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false
09-08 13:34:19.406  2708  2708 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 13:34:19.406  2708  2708 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 13:34:19.406  2708  2760 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 13:34:19.407  2708  2708 V BluetoothAdapterState: isTurningOff()=true
,09-08 13:34:19.407  2708  2708 V BluetoothAdapterState: isTurningOn()=false
,09-08 13:34:19.407  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
09-08 13:34:19.407  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 13:34:19.407  2708  2708 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-08 13:34:19.407  2708  2760 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-08 13:34:19.408  2708  2708 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 13:34:19.408  2708  2708 V BluetoothAdapterState: isTurningOff()=true
09-08 13:34:19.408  2708  2708 V BluetoothAdapterState: isTurningOn()=false
09-08 13:34:19.408  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
09-08 13:34:19.408  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false
09-08 13:34:19.409  2708  2708 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-08 13:34:19.409  2708  2708 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 13:34:19.410  2708  2708 D BluetoothMapService: MAP Service closeService in
09-08 13:34:19.410  2708  2708 V BluetoothAdapterState: isTurningOff()=true
09-08 13:34:19.411  2708  2708 V BluetoothAdapterState: isTurningOn()=false
09-08 13:34:19.411  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
09-08 13:34:19.411  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false
09-08 13:34:19.412  2708  2756 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-08 13:34:19.412  2708  2756 D BluetoothAdapterProperties: Setting state to 15
,09-08 13:34:19.412  2708  2756 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-08 13:34:19.413  2708  2756 I BluetoothAdapterState: Entering BleOnState
09-08 13:34:19.413  1365  2113 D BluetoothPan: onBluetoothStateChange on: false
09-08 13:34:19.414  2708  2708 D BluetoothMapService: cleanup()
09-08 13:34:19.414   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 13:34:19.414  2708  2708 D BluetoothMapService: MAP Service closeService in
09-08 13:34:19.414  1365  1378 D BluetoothPbap: onBluetoothStateChange: up=false
,09-08 13:34:19.415  1365  2110 D BluetoothMap: onBluetoothStateChange: up=false
09-08 13:34:19.415   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 13:34:19.416  1973  2286 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 13:34:19.416  1365  1377 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 13:34:19.417   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 13:34:19.417  1365  2113 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 13:34:19.417   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 13:34:19.417  1365  1378 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 13:34:19.418  2708  2756 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-08 13:34:19.418  2708  2756 D BluetoothAdapterProperties: Setting state to 16
09-08 13:34:19.418  2708  2756 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-08 13:34:19.419  2708  2756 D BluetoothAdapterProperties: onBleDisable
09-08 13:34:19.419  2708  2756 I BluetoothAdapterState: Entering PendingCommandState
09-08 13:34:19.419  2708  2757 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-08 13:34:19.419   874  4037 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172800, domain null
09-08 13:34:19.420   874  2092 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-08 13:34:19.420  2708  2899 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-08 13:34:19.420  2708  2899 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 13:34:19.421  2708  2760 D BluetoothAdapterProperties: Scan Mode:20
,09-08 13:34:19.422   874  2092 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
09-08 13:34:19.422  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:19.424  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:19.425  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:19.426  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:19.439  4044  4044 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-08 13:34:19.449  4044  4044 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 13:34:19.454   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10c90bf:true
,09-08 13:34:19.455  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 13:34:19.477   874  1982 I ActivityManager: Start proc 4056:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-08 13:34:19.482  4044  4044 D LocalBluetoothProfileManager: Adding local MAP profile
,09-08 13:34:19.485  4044  4044 D BluetoothMap: Create BluetoothMap proxy object
,09-08 13:34:19.489  4044  4044 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-08 13:34:19.495  4044  4044 D DockEventReceiver: finishStartingService: stopping service
,09-08 13:34:19.498   874  1982 I ActivityManager: Killing 3692:com.android.musicfx/u0a18 (adj 15): empty #17
,09-08 13:34:19.546  4056  4056 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-08 13:34:19.624  2708  2760 I bt_hci  : shut_down
09-08 13:34:19.624  2708  2765 D bt_hwcfg: hw_epilog_process
,09-08 13:34:19.629  2708  2765 I bt_vendor: low_power_mode_cb
,09-08 13:34:19.650  2708  2765 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-08 13:34:19.650  2708  2765 I bt_vendor: epilog_cb
09-08 13:34:19.650  2708  2765 I bt_hci  : epilog_finished_callback
,09-08 13:34:19.653  2708  2760 I bt_hci_h4: hal_close
,09-08 13:34:19.654  2708  2760 I bt_userial_vendor: device fd = 51 close
,09-08 13:34:19.708  4056  4056 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 13:34:19.708  4056  4056 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 13:34:19.708  4056  4056 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 13:34:19.708  4056  4056 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 13:34:19.708  4056  4056 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.r.k.d(PG:583)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 13:34:19.708  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 13:34:19.709  4056  4056 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 13:34:19.709  4056  4056 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 13:34:19.709  4056  4056 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 13:34:19.709  4056  4056 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 13:34:19.714  4044  4044 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 13:34:19.719  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 13:34:19.722  4044  4044 D DockEventReceiver: finishStartingService: stopping service
,09-08 13:34:19.735   874  1982 I ActivityManager: Killing 3515:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-08 13:34:19.789  2708  2757 D bt_stack_manager: event_shut_down_stack finished.
,09-08 13:34:19.790  2708  2756 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-08 13:34:19.791  2708  2708 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 13:34:19.792  2708  2756 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-08 13:34:19.792  2708  2708 D BtGatt.GattService: Received stop request...Stopping profile...
,09-08 13:34:19.793  2708  2708 D BtGatt.GattService: stop()
09-08 13:34:19.793  2708  2708 D BtGatt.AdvertiseManager: advertise clients cleared
,09-08 13:34:19.796  2708  2708 V BluetoothAdapterState: isTurningOff()=false
09-08 13:34:19.797  2708  2708 V BluetoothAdapterState: isTurningOn()=false
,09-08 13:34:19.797  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
09-08 13:34:19.797  2708  2708 V BluetoothAdapterState: isBleTurningOff()=true
09-08 13:34:19.798  2708  2756 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-08 13:34:19.798  2708  2756 D BluetoothAdapterProperties: Setting state to 10
09-08 13:34:19.798  2708  2756 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-08 13:34:19.799  2708  2756 I BluetoothAdapterState: Entering OffState
,09-08 13:34:19.801   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-08 13:34:19.818  2708  2708 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-08 13:34:19.818  2708  2708 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-08 13:34:19.818  2708  2757 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-08 13:34:19.821  2708  2757 D bt_stack_manager: event_clean_up_stack finished.
,09-08 13:34:19.821  2708  2708 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 13:34:19.825  2708  2708 I art     : System.exit called, status: 0
,09-08 13:34:19.826  2708  2708 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 13:34:19.882   874  2035 I ActivityManager: Process com.android.bluetooth (pid 2708) has died
,09-08 13:34:19.987  4056  4078 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-08 13:34:20.013   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cb75c3e:true
,09-08 13:34:20.339  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 13:34:20.340  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:20.344  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 13:34:20.345  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 13:34:20.345  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:20.345  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-08 13:34:20.346  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d479a5d removed from the list
,09-08 13:34:20.346  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 13:34:20.347  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9733fd2 removed from the list
,09-08 13:34:20.347  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 13:34:20.347  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 13:34:20.347  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:20.351  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 13:34:20.351  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f6997a0 added. We now have 2 listener(s)
,09-08 13:34:20.359  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 13:34:20.360  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 13:34:20.360  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 13:34:20.361  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 13:34:20.361  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e87f59 added. We now have 2 listener(s)
09-08 13:34:20.361  3820  3869 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 13:34:20.363  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 13:34:20.370  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 13:34:20.372  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 13:34:20.372  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:20.372  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:20.372  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:20.372  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:20.372  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 13:34:20.372  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 13:34:20.372  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 13:34:20.372  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 13:34:20.373  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 13:34:20.373  3820  3869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 13:34:20.373  3820  3869 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 13:34:20.374  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:20.374  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 13:34:20.375  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 13:34:20.375  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 13:34:20.375  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f6997a0 removed from the list
09-08 13:34:20.375  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 13:34:20.376  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:20.376  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e87f59 removed from the list
,09-08 13:34:20.377  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:20.378  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:20.378  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:20.380  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 13:34:20.381  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@125dbff added. We now have 2 listener(s)
,09-08 13:34:20.387  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 13:34:20.387  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 13:34:20.387  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 13:34:20.388  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 13:34:20.388  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c608dcc added. We now have 2 listener(s)
09-08 13:34:20.389  3820  3869 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 13:34:20.390  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 13:34:20.394  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 13:34:20.396  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 13:34:20.396  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:20.396  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:20.396  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:20.396  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:20.396  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 13:34:20.396  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 13:34:20.396  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 13:34:20.396  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 13:34:20.396  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 13:34:20.397  3820  3869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 13:34:20.397  3820  3869 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 13:34:20.399  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:20.401  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:21.438   874  2092 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 13:34:21.455   874  4037 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 13:34:21.456   874  2092 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 13:34:21.461   372   872 D CommandListener: Setting iface cfg
,09-08 13:34:21.473   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-08 13:34:21.475   874  2092 D DhcpClient: Scheduling renewal in 86399s
,09-08 13:34:21.492   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 13:34:21.496   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-08 13:34:21.497   874  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 13:34:21.499   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-08 13:34:21.501   874  1310 D ConnectivityService: Adding iface wlan0 to network 101
,09-08 13:34:21.520   874  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 13:34:21.571   874  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-08 13:34:21.571   874  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-08 13:34:21.573   874  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-08 13:34:21.575   874  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-08 13:34:21.577   874  1310 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-08 13:34:21.587   874  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-08 13:34:21.592   874  1310 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-08 13:34:21.592   874  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-08 13:34:21.592   874  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-08 13:34:21.593   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 13:34:21.593   874  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-08 13:34:21.593   874  1310 D ConnectivityService:    accepting network in place of null
,09-08 13:34:21.594   874  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 13:34:21.606   874  4036 D NetlinkSocketObserver: NeighborEvent{elapsedMs=140113, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 13:34:21.629   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 13:34:21.663   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 13:34:21.668   874  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-08 13:34:21.668   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:21.671   874  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-08 13:34:21.678   874   891 D Tethering: MasterInitialState.processMessage what=3
09-08 13:34:21.682   874  4035 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-08 13:34:21.688  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 13:34:21.688  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:21.688  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:21.688  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:21.688  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:21.688  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 13:34:21.688  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:21.688  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:21.688  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 13:34:21.688  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 13:34:21.689  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:21.691  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 13:34:21.691  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:21.691  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:21.691  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:21.691  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:21.691  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 13:34:21.691  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:21.691  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:21.691  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 13:34:21.691  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 13:34:21.691  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 13:34:21.697  2058  2058 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-08 13:34:21.701  1724  1724 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 13:34:21.704  1724  1724 D SystemUpdateService: onCreate
,09-08 13:34:21.708  1724  1724 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 13:34:21.710  1724  4102 I SystemUpdateService: active receiver: enabled
,09-08 13:34:21.714  1724  4102 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 13:34:21.720  1724  4102 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-08 13:34:21.720  1724  4102 I SystemUpdateService: now status is 0 (complete)
09-08 13:34:21.720  1724  4102 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 13:34:21.720  1724  4102 I SystemUpdateService: file has been verified
09-08 13:34:21.720  1724  4102 I SystemUpdateService: OTA package size = 12249756
,09-08 13:34:21.723  1724  4102 I SystemUpdateService: showing system update notification
,09-08 13:34:21.730  1724  1724 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 13:34:21.734  1724  2505 I iu.UploadsManager: num queued entries: 0
,09-08 13:34:21.735  1724  2505 I iu.UploadsManager: num updated entries: 0
,09-08 13:34:21.735  1724  4108 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-08 13:34:21.735  1724  4108 W BaseAppContext: Using Auth Proxy for data requests.
09-08 13:34:21.736  1724  4108 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 13:34:21.737  1724  1724 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 13:34:21.738  1724  1724 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-08 13:34:21.741  3932  3932 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:21.741  1724  2505 I iu.SyncManager: NEXT; no task
,09-08 13:34:21.745  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 13:34:21.746  1724  1724 D SystemUpdateService: onDestroy
,09-08 13:34:21.747  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 13:34:21.752  3932  3932 D SprintDMHelper: simOperator: 
,09-08 13:34:21.753  3932  3932 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-08 13:34:21.760   874  4035 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 11:34:21 GMT], X-Android-Received-Millis=[1473334461759], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473334461733]}
,09-08 13:34:21.763   874  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-08 13:34:21.763   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-08 13:34:21.763   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-08 13:34:21.765   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 13:34:21.789  1501  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-08 13:34:21.789  1501  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-08 13:34:21.789  1501  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 13:34:21.789  1501  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 13:34:21.809  1724  4108 E MDM     : [176] SitrepService.a: Error sending sitrep.
,09-08 13:34:21.846  1501  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-08 13:34:21.846  1501  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 13:34:21.846  1501  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 13:34:21.846  1501  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 13:34:21.862  3024  4105 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 13:34:21.862  3024  4105 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 13:34:21.862  3024  4105 E HttpOperation: 	at jdm.a(PG:82)
09-08 13:34:21.862  3024  4105 E HttpOperation: 	at jcs.o(PG:406)
09-08 13:34:21.862  3024  4105 E HttpOperation: 	at jcn.a(PG:1379)
09-08 13:34:21.862  3024  4105 E HttpOperation: 	at jcs.i(PG:143)
09-08 13:34:21.862  3024  4105 E HttpOperation: 	at blb.a(PG:3937)
09-08 13:34:21.862  3024  4105 E HttpOperation: 	at czp.a(PG:18188)
09-08 13:34:21.862  3024  4105 E HttpOperation: 	at czp.a(PG:9081)
09-08 13:34:21.862  3024  4105 E HttpOperation: 	at czq.run(PG:1686)
09-08 13:34:21.862  3024  4105 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 13:34:21.862  3024  4105 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 13:34:21.862  3024  4105 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 13:34:21.862  3024  4105 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 13:34:21.862  3024  4105 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 13:34:21.862  3024  4105 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 13:34:21.862  3024  4105 E HttpOperation: 	at jdj.a(PG:4091)
09-08 13:34:21.862  3024  4105 E HttpOperation: 	at jdj.a(PG:1125)
09-08 13:34:21.862  3024  4105 E HttpOperation: 	at jdm.a(PG:77)
09-08 13:34:21.862  3024  4105 E HttpOperation: 	... 12 more
09-08 13:34:21.862  3024  4105 E HttpOperation: Caused by: faj: BadAuthentication
09-08 13:34:21.862  3024  4105 E HttpOperation: 	at fal.a(PG:38)
09-08 13:34:21.862  3024  4105 E HttpOperation: 	at jdj.a(PG:4089)
09-08 13:34:21.862  3024  4105 E HttpOperation: 	... 14 more
,09-08 13:34:21.900  1501  2093 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 13:34:21.900  1501  2093 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 13:34:21.900  1501  2093 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 13:34:21.900  1501  2093 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 13:34:21.926  3024  4105 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 13:34:21.926  3024  4105 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 13:34:21.926  3024  4105 E HttpOperation: 	at jdm.a(PG:82)
09-08 13:34:21.926  3024  4105 E HttpOperation: 	at jcs.o(PG:406)
09-08 13:34:21.926  3024  4105 E HttpOperation: 	at jcn.a(PG:1379)
09-08 13:34:21.926  3024  4105 E HttpOperation: 	at jcs.i(PG:143)
09-08 13:34:21.926  3024  4105 E HttpOperation: 	at hec.a(PG:42)
09-08 13:34:21.926  3024  4105 E HttpOperation: 	at hee.a(PG:102)
09-08 13:34:21.926  3024  4105 E HttpOperation: 	at czr.a(PG:65)
09-08 13:34:21.926  3024  4105 E HttpOperation: 	at kka.a(PG:108)
09-08 13:34:21.926  3024  4105 E HttpOperation: 	at czp.a(PG:19176)
09-08 13:34:21.926  3024  4105 E HttpOperation: 	at czp.a(PG:9081)
09-08 13:34:21.926  3024  4105 E HttpOperation: 	at czq.run(PG:1686)
09-08 13:34:21.926  3024  4105 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 13:34:21.926  3024  4105 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 13:34:21.926  3024  4105 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 13:34:21.926  3024  4105 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 13:34:21.926  3024  4105 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 13:34:21.926  3024  4105 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 13:34:21.926  3024  4105 E HttpOperation: 	at jdj.a(PG:4091)
09-08 13:34:21.926  3024  4105 E HttpOperation: 	at jdj.a(PG:1125)
09-08 13:34:21.926  3024  4105 E HttpOperation: 	at jdm.a(PG:77)
09-08 13:34:21.926  3024  4105 E HttpOperation: 	... 15 more
09-08 13:34:21.926  3024  4105 E HttpOperation: Caused by: faj: BadAuthentication
09-08 13:34:21.926  3024  4105 E HttpOperation: 	at fal.a(PG:38)
09-08 13:34:21.926  3024  4105 E HttpOperation: 	at jdj.a(PG:4089)
09-08 13:34:21.926  3024  4105 E HttpOperation: 	... 17 more
,09-08 13:34:21.927  3024  4105 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 13:34:21.927  3024  4105 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 13:34:21.927  3024  4105 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 13:34:21.927  3024  4105 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 13:34:21.927  3024  4105 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 13:34:21.927  3024  4105 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 13:34:21.927  3024  4105 E ExperimentLoader: 	at hec.a(PG:42)
09-08 13:34:21.927  3024  4105 E ExperimentLoader: 	at hee.a(PG:102)
09-08 13:34:21.927  3024  4105 E ExperimentLoader: 	at czr.a(PG:65)
09-08 13:34:21.927  3024  4105 E ExperimentLoader: 	at kka.a(PG:108)
09-08 13:34:21.927  3024  4105 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 13:34:21.927  3024  4105 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 13:34:21.927  3024  4105 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 13:34:21.927  3024  4105 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 13:34:21.927  3024  4105 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 13:34:21.927  3024  4105 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 13:34:21.927  3024  4105 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
,09-08 13:34:21.927  3024  4105 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 13:34:21.927  3024  4105 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 13:34:21.927  3024  4105 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 13:34:21.927  3024  4105 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 13:34:21.927  3024  4105 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 13:34:21.927  3024  4105 E ExperimentLoader: 	... 15 more
09-08 13:34:21.927  3024  4105 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 13:34:21.927  3024  4105 E ExperimentLoader: 	at fal.a(PG:38)
09-08 13:34:21.927  3024  4105 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 13:34:21.927  3024  4105 E ExperimentLoader: 	... 17 more
,09-08 13:34:21.945  3137  4111 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 13:34:22.057   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 131488, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 13:34:22.669   874  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-08 13:34:22.911   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-08 13:34:23.410  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:23.458   874   891 I ActivityManager: Start proc 4121:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-08 13:34:23.590  4121  4121 D AdapterServiceConfig: Adding HeadsetService
,09-08 13:34:23.590  4121  4121 D AdapterServiceConfig: Adding A2dpService
,09-08 13:34:23.590  4121  4121 D AdapterServiceConfig: Adding HidService
,09-08 13:34:23.591  4121  4121 D AdapterServiceConfig: Adding HealthService
09-08 13:34:23.591  4121  4121 D AdapterServiceConfig: Adding PanService
,09-08 13:34:23.591  4121  4121 D AdapterServiceConfig: Adding GattService
09-08 13:34:23.591  4121  4121 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 13:34:23.605  4121  4121 D BluetoothAdapterState: make() - Creating AdapterState
09-08 13:34:23.605   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d1967bd:true
,09-08 13:34:23.612  4121  4121 I bt_bluedroid: init
,09-08 13:34:23.613  4121  4133 I BluetoothAdapterState: Entering OffState
,09-08 13:34:23.618  4121  4134 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 13:34:23.619  4121  4134 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-08 13:34:23.619  4121  4134 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-08 13:34:23.620  4121  4134 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-08 13:34:23.621  4121  4121 I bt_bluedroid: get_profile_interface socket
,09-08 13:34:23.623  4121  4121 I bt_bluedroid: get_profile_interface sdp
,09-08 13:34:23.628  4121  4132 I bt_bluedroid: config_hci_snoop_log
,09-08 13:34:23.628  4121  4137 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 13:34:23.630  4121  4137 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 13:34:23.631   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-08 13:34:23.642  4121  4133 D BluetoothAdapterState: Current state: OFF, message: 0
,09-08 13:34:23.643  4121  4133 D BluetoothAdapterProperties: Setting state to 14
09-08 13:34:23.643  4121  4133 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-08 13:34:23.648  4121  4133 D BluetoothBondStateMachine: make
,09-08 13:34:23.653  4121  4138 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 13:34:23.663  4121  4133 I BluetoothAdapterState: Entering PendingCommandState
,09-08 13:34:23.663  4121  4121 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 13:34:23.669  4121  4121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c520f3
,09-08 13:34:23.671  4121  4121 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 13:34:23.672  4121  4121 D BtGatt.GattService: Received start request. Starting profile...
,09-08 13:34:23.672  4121  4121 D BtGatt.GattService: start()
,09-08 13:34:23.672  4121  4121 I bt_bluedroid: get_profile_interface gatt
,09-08 13:34:23.674  4121  4121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c520f3
,09-08 13:34:23.674  4121  4121 D BtGatt.AdvertiseManager: advertise manager created
,09-08 13:34:23.687  4121  4121 V BluetoothAdapterState: isTurningOff()=false
,09-08 13:34:23.688  4121  4121 V BluetoothAdapterState: isTurningOn()=false
09-08 13:34:23.688  4121  4121 V BluetoothAdapterState: isBleTurningOn()=true
09-08 13:34:23.688  4121  4121 V BluetoothAdapterState: isBleTurningOff()=false
09-08 13:34:23.689  4121  4133 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-08 13:34:23.690  4121  4133 I bt_bluedroid: enable
09-08 13:34:23.690  4121  4134 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-08 13:34:23.691  4121  4134 I bt_hci  : start_up
,09-08 13:34:23.714  4121  4134 I bt_vendor: alloc value 0xb3a17189
,09-08 13:34:23.714  4121  4134 I bt_vendor: init
09-08 13:34:23.714  4121  4134 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-08 13:34:23.714  4121  4134 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 13:34:23.822  4121  4134 D bt_hci  : start_up starting async portion
,09-08 13:34:23.822  4121  4141 I bt_hci  : event_finish_startup
,09-08 13:34:23.823  4121  4141 I bt_hci_h4: hal_open
09-08 13:34:23.823  4121  4141 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 13:34:23.832  4121  4141 I bt_userial_vendor: device fd = 51 open
,09-08 13:34:23.863  4121  4141 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 13:34:23.896  4121  4141 D bt_hwcfg: Chipset BCM4354A2
,09-08 13:34:23.896  4121  4141 D bt_hwcfg: Target name = [BCM4354A2]
09-08 13:34:23.897  4121  4141 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 13:34:24.447  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,09-08 13:34:24.481  4121  4141 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 13:34:24.481  1501  2313 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-08 13:34:24.482  1501  2313 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 13:34:24.482  1501  2313 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 13:34:24.482  1501  2313 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-08 13:34:24.482  4121  4141 D bt_hwcfg: Settlement delay -- 100 ms
09-08 13:34:24.483  4121  4141 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 13:34:24.499  3563  3563 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 13:34:24.499  3563  3563 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-08 13:34:24.500  3563  3563 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-08 13:34:24.525   874   883 I art     : Background partial concurrent mark sweep GC freed 54064(3MB) AllocSpace objects, 7(180KB) LOS objects, 33% free, 29MB/43MB, paused 1.318ms total 102.464ms
,09-08 13:34:24.600  4121  4141 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-08 13:34:24.600  4121  4141 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 13:34:24.630  4121  4141 I bt_hwcfg: vendor lib fwcfg completed
09-08 13:34:24.631  4121  4141 I bt_vendor: firmware callback
,09-08 13:34:24.631  4121  4141 I bt_hci  : firmware_config_callback
,09-08 13:34:24.641  4121  4143 I bt_btu  : btu_task pending for preload complete event,
09-08 13:34:24.641  4121  4143 I bt_btu_task: Bluetooth chip preload is complete
,09-08 13:34:24.642  4121  4143 I bt_btu  : btu_task received preload complete event
,09-08 13:34:24.650  4121  4143 I         : BTE_InitTraceLevels -- TRC_HCI
,09-08 13:34:24.650  4121  4143 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-08 13:34:24.650  4121  4143 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-08 13:34:24.650  4121  4143 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-08 13:34:24.650  4121  4143 I         : BTE_InitTraceLevels -- TRC_AVRC
09-08 13:34:24.650  4121  4143 I         : BTE_InitTraceLevels -- TRC_A2D
,09-08 13:34:24.651  4121  4143 I         : BTE_InitTraceLevels -- TRC_BNEP
09-08 13:34:24.651  4121  4143 I         : BTE_InitTraceLevels -- TRC_BTM
,09-08 13:34:24.651  4121  4143 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 13:34:24.651  4121  4143 I         : BTE_InitTraceLevels -- TRC_PAN
,09-08 13:34:24.651  4121  4143 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 13:34:24.651  4121  4143 I         : BTE_InitTraceLevels -- TRC_GATT
,09-08 13:34:24.651  4121  4143 I         : BTE_InitTraceLevels -- TRC_SMP
09-08 13:34:24.651  4121  4143 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-08 13:34:24.651  4121  4143 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 13:34:24.781  4121  4143 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3994d9d
,09-08 13:34:24.781  4121  4143 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3994d9d 
,09-08 13:34:24.794  4121  4137 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-08 13:34:24.797  4121  4137 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-08 13:34:24.797  4121  4137 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 13:34:24.803  4121  4137 D BluetoothAdapterProperties: Name is: Nexus 6,
,09-08 13:34:24.806  4121  4137 D BluetoothAdapterProperties: Scan Mode:20
,09-08 13:34:24.806  4121  4137 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 13:34:24.807  4121  4137 D bt_hci  : do_postload posting postload work item
,09-08 13:34:24.807  4121  4141 I bt_hci  : event_postload
09-08 13:34:24.807  4121  4141 I bt_vendor: sco_config_cb
09-08 13:34:24.807  4121  4141 I bt_hci  : sco_config_callback postload finished.
09-08 13:34:24.810  4121  4137 D bt_bte_conf: Device ID record 1 : primary
,09-08 13:34:24.810  4121  4137 D bt_bte_conf:   vendorId            = 000f
09-08 13:34:24.810  4121  4137 D bt_bte_conf:   vendorIdSource      = 0001
09-08 13:34:24.811  4121  4137 D bt_bte_conf:   product             = 1200
09-08 13:34:24.811  4121  4137 D bt_bte_conf:   version             = 1436
09-08 13:34:24.811  4121  4137 D bt_bte_conf:   clientExecutableURL = 
09-08 13:34:24.811  4121  4137 D bt_bte_conf:   serviceDescription  = 
09-08 13:34:24.812  4121  4137 D bt_bte_conf:   documentationURL    = 
09-08 13:34:24.812  4121  4137 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-08 13:34:24.812  4121  4134 D bt_stack_manager: event_start_up_stack finished
09-08 13:34:24.813  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:24.814  4121  4133 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-08 13:34:24.814  4121  4133 D BluetoothAdapterProperties: Setting state to 15
09-08 13:34:24.814  4121  4141 I bt_vendor: low_power_mode_cb
09-08 13:34:24.814  4121  4133 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-08 13:34:24.817  4121  4133 I BluetoothAdapterState: Entering BleOnState
09-08 13:34:24.819  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:24.822  4121  4133 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-08 13:34:24.822  4121  4133 D BluetoothAdapterProperties: Setting state to 11
09-08 13:34:24.822  4121  4133 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-08 13:34:24.829  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:24.833  4121  4121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c520f3
09-08 13:34:24.835  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:24.839  4121  4121 D HeadsetService: Received start request. Starting profile...
,09-08 13:34:24.846  4121  4121 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-08 13:34:24.846  4121  4133 I BluetoothAdapterState: Entering PendingCommandState
09-08 13:34:24.846  4121  4121 D HeadsetStateMachine: make
,09-08 13:34:24.854  4121  4121 D HeadsetStateMachine: max_hf_connections = 1
,09-08 13:34:24.854  4121  4121 I bt_bluedroid: get_profile_interface handsfree
,09-08 13:34:24.854  4121  4137 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-08 13:34:24.855  4121  4137 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-08 13:34:24.858  4121  4121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c520f3
,09-08 13:34:24.859  4121  4121 D A2dpService: Received start request. Starting profile...
,09-08 13:34:24.864  4121  4121 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-08 13:34:24.864  4121  4121 I bt_bluedroid: get_profile_interface avrcp
,09-08 13:34:24.869  4121  4121 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 13:34:24.869  4121  4121 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-08 13:34:24.869  4121  4121 D A2dpStateMachine: make
09-08 13:34:24.870  4121  4121 I bt_bluedroid: get_profile_interface a2dp
09-08 13:34:24.871  4121  4137 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-08 13:34:24.874  4121  4152 D A2dpStateMachine: Enter Disconnected: -2
09-08 13:34:24.875  4121  4121 I BluetoothHidServiceJni: classInitNative: succeeds
,09-08 13:34:24.875  4121  4121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c520f3
,09-08 13:34:24.876  4121  4121 D HidService: Received start request. Starting profile...
09-08 13:34:24.876  4121  4121 I bt_bluedroid: get_profile_interface hidhost
09-08 13:34:24.877  4121  4137 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39763e5
,09-08 13:34:24.877  4121  4137 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-08 13:34:24.877  4044  4044 D BluetoothInputDevice: Proxy object connected
09-08 13:34:24.877  4121  4121 D HidService: setHidService(): set to: null
09-08 13:34:24.877  4121  4121 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-08 13:34:24.878  4121  4121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c520f3
,09-08 13:34:24.878  4044  4044 D HidProfile: Bluetooth service connected
09-08 13:34:24.878  4121  4121 D HealthService: Received start request. Starting profile...
,09-08 13:34:24.880  4121  4121 I bt_bluedroid: get_profile_interface health
,09-08 13:34:24.880  4121  4121 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-08 13:34:24.881  4121  4121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c520f3
,09-08 13:34:24.882  4121  4121 D PanService: Received start request. Starting profile...
09-08 13:34:24.882  4121  4121 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-08 13:34:24.882  4044  4044 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 13:34:24.882  4121  4121 I bt_bluedroid: get_profile_interface pan
09-08 13:34:24.883  4121  4137 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-08 13:34:24.884  4044  4044 D PanProfile: Bluetooth service connected
,09-08 13:34:24.885  4121  4121 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c520f3
,09-08 13:34:24.886  4121  4121 D BluetoothMapService: Received start request. Starting profile...
09-08 13:34:24.886  4044  4044 D BluetoothMap: Proxy object connected
09-08 13:34:24.886  4121  4121 D BluetoothMapService: start()
,09-08 13:34:24.887  4044  4044 D MapProfile: Bluetooth service connected
,09-08 13:34:24.887  4044  4044 D BluetoothMap: getConnectedDevices()
09-08 13:34:24.887  4044  4044 D BluetoothMap: Bluetooth is Not enabled
09-08 13:34:24.888  4121  4121 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-08 13:34:24.888  4121  4121 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-08 13:34:24.889  4121  4121 D BluetoothMapAppObserver: createReceiver()
09-08 13:34:24.889  4121  4121 D BluetoothMapAppObserver: initObservers()
09-08 13:34:24.889  4121  4121 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-08 13:34:24.899  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 13:34:24.900  4121  4121 V BluetoothAdapterState: isTurningOff()=false
,09-08 13:34:24.900  4121  4121 V BluetoothAdapterState: isTurningOn()=true
09-08 13:34:24.900  4121  4121 V BluetoothAdapterState: isBleTurningOn()=false
09-08 13:34:24.900  4121  4121 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 13:34:24.902  4121  4121 V BluetoothAdapterState: isTurningOff()=false
09-08 13:34:24.902  4121  4121 V BluetoothAdapterState: isTurningOn()=true
09-08 13:34:24.902  4121  4121 V BluetoothAdapterState: isBleTurningOn()=false
09-08 13:34:24.902  4121  4150 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
09-08 13:34:24.902  4121  4121 V BluetoothAdapterState: isBleTurningOff()=false
09-08 13:34:24.902  4121  4121 V BluetoothAdapterState: isTurningOff()=false
09-08 13:34:24.902  4121  4121 V BluetoothAdapterState: isTurningOn()=true
09-08 13:34:24.902  4121  4121 V BluetoothAdapterState: isBleTurningOn()=false
09-08 13:34:24.902  4121  4121 V BluetoothAdapterState: isBleTurningOff()=false
09-08 13:34:24.903  4121  4121 V BluetoothAdapterState: isTurningOff()=false
09-08 13:34:24.903  4121  4121 V BluetoothAdapterState: isTurningOn()=true
,09-08 13:34:24.903  4121  4121 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 13:34:24.903  4121  4121 V BluetoothAdapterState: isBleTurningOff()=false
09-08 13:34:24.904  4121  4121 V BluetoothAdapterState: isTurningOff()=false
09-08 13:34:24.904  4121  4121 V BluetoothAdapterState: isTurningOn()=true
09-08 13:34:24.904  4121  4121 V BluetoothAdapterState: isBleTurningOn()=false
09-08 13:34:24.904  4121  4121 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 13:34:24.904  4121  4121 V BluetoothAdapterState: isTurningOff()=false
09-08 13:34:24.904  4121  4121 V BluetoothAdapterState: isTurningOn()=true
,09-08 13:34:24.904  4121  4121 V BluetoothAdapterState: isBleTurningOn()=false
09-08 13:34:24.904  4121  4121 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 13:34:24.905  4121  4133 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-08 13:34:24.905  4121  4133 D BluetoothAdapterProperties: ScanMode =  20
09-08 13:34:24.905  4121  4133 D BluetoothAdapterProperties: State =  11
,09-08 13:34:24.907  4121  4137 D BluetoothAdapterProperties: Scan Mode:21
09-08 13:34:24.907  4121  4137 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 13:34:24.907  4121  4133 D BluetoothAdapterProperties: Setting state to 12
,09-08 13:34:24.907  4121  4133 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-08 13:34:24.908  1365  1378 D BluetoothPan: onBluetoothStateChange on: true
09-08 13:34:24.908  4121  4133 I BluetoothAdapterState: Entering OnState
,09-08 13:34:24.910  3820  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-08 13:34:24.912  3820  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-08 13:34:24.912  1365  1365 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 13:34:24.912  1365  1365 D PanProfile: Bluetooth service connected
09-08 13:34:24.913   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 13:34:24.913  4044  4055 D BluetoothPbap: onBluetoothStateChange: up=true
,09-08 13:34:24.915  1365  1377 D BluetoothPbap: onBluetoothStateChange: up=true
,09-08 13:34:24.916  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:24.916  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:24.916  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:24.916  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:24.916  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:24.916  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:24.916  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:24.916  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 13:34:24.918  4121  4121 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 13:34:24.918  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:24.918  4121  4121 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-08 13:34:24.919  1365  2110 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 13:34:24.920  4121  4121 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 13:34:24.923  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:24.923  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:24.923  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:24.923  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:24.923  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:24.923  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:24.923  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:24.923  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 13:34:24.923  4121  4121 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 13:34:24.925  1365  1365 D BluetoothMap: Proxy object connected
,09-08 13:34:24.925  1365  1365 D MapProfile: Bluetooth service connected
09-08 13:34:24.925  1365  1365 D BluetoothMap: getConnectedDevices()
09-08 13:34:24.926  4121  4121 D ObexServerSockets: Succeed to create listening sockets 
09-08 13:34:24.926  4121  4121 D ObexServerSockets0: startAccept()
09-08 13:34:24.926  4121  4121 D ObexServerSockets0: prepareForNewConnect()
09-08 13:34:24.926  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:24.926   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 13:34:24.927  4044  4054 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 13:34:24.927  4044  4055 D BluetoothPan: onBluetoothStateChange on: true
09-08 13:34:24.927  1973  1987 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 13:34:24.928  1365  1378 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-08 13:34:24.929  4121  4121 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-08 13:34:24.929  4121  4121 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-08 13:34:24.929  1365  1365 D BluetoothInputDevice: Proxy object connected
09-08 13:34:24.929   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 13:34:24.929  1365  1365 D HidProfile: Bluetooth service connected
09-08 13:34:24.930  1365  2113 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 13:34:24.930  4121  4157 D ObexServerSockets0: Accepting socket connection...
09-08 13:34:24.930  4121  4158 D ObexServerSockets0: Accepting socket connection...
,09-08 13:34:24.932  4044  4054 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-08 13:34:24.932  1365  1365 D BluetoothA2dp: Proxy object connected
,09-08 13:34:24.932   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-08 13:34:24.933   874   874 D BluetoothA2dp: Proxy object connected
09-08 13:34:24.933  1365  1378 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 13:34:24.935  4121  4121 D BluetoothMapService: onReceive
,09-08 13:34:24.935  4121  4121 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 13:34:24.936  4121  4121 D BluetoothMapService: STATE_ON
09-08 13:34:24.937   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-08 13:34:24.939  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 13:34:24.939  4044  4044 D LocalBluetoothProfileManager: Adding local A2DP profile
09-08 13:34:24.941  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:24.944  4044  4044 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-08 13:34:24.948  4044  4044 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 13:34:24.951  4044  4044 D BluetoothA2dp: Proxy object connected
,09-08 13:34:24.954  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 13:34:24.956  4044  4044 D DockEventReceiver: finishStartingService: stopping service
,09-08 13:34:24.961  4121  4121 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-08 13:34:24.961  4121  4121 D ObexServerSockets0: prepareForNewConnect()
09-08 13:34:24.961  4044  4044 D BluetoothPbap: Proxy object connected
09-08 13:34:24.961  4044  4044 D PbapServerProfile: Bluetooth service connected
,09-08 13:34:24.962  1365  1365 D BluetoothPbap: Proxy object connected
09-08 13:34:24.962  1365  1365 D PbapServerProfile: Bluetooth service connected
,09-08 13:34:24.970  4121  4165 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 13:34:24.983  4121  4169 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 13:34:24.984  4121  4169 I BtOppRfcommListener: Accept thread started.
,09-08 13:34:25.014   874   874 D BluetoothHeadset: Proxy object connected
,09-08 13:34:25.014   874   874 D BluetoothHeadset: Proxy object connected
09-08 13:34:25.014   874   874 D BluetoothHeadset: Proxy object connected
09-08 13:34:25.014  1973  2286 D BluetoothHeadset: Proxy object connected
09-08 13:34:25.015  1365  2113 D BluetoothHeadset: Proxy object connected
,09-08 13:34:25.015  1365  1365 D HeadsetProfile: Bluetooth service connected
,09-08 13:34:25.026   874   891 D BluetoothHeadset: Proxy object connected
,09-08 13:34:25.027  1973  2152 D BluetoothHeadset: Proxy object connected
,09-08 13:34:25.029   874   891 D BluetoothHeadset: Proxy object connected
,09-08 13:34:25.033  1365  1377 D BluetoothHeadset: Proxy object connected
,09-08 13:34:25.033  1365  1365 D HeadsetProfile: Bluetooth service connected
,09-08 13:34:25.047  4044  4055 D BluetoothHeadset: Proxy object connected
,09-08 13:34:25.048  4044  4044 D HeadsetProfile: Bluetooth service connected
,09-08 13:34:25.374   874  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,09-08 13:34:26.428  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:26.428  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 13:34:26.428  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:26.429  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 13:34:26.429  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-08 13:34:26.430  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@125dbff removed from the list
09-08 13:34:26.430  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:26.430  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c608dcc removed from the list
09-08 13:34:26.432  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:26.432  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:26.436  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 13:34:26.436  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fdaf72a added. We now have 2 listener(s)
,09-08 13:34:26.443  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 13:34:26.444  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 13:34:26.444  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 13:34:26.445  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 13:34:26.445  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c06391b added. We now have 2 listener(s)
,09-08 13:34:26.445  3820  3869 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 13:34:26.447  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 13:34:26.456  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 13:34:26.464  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:26.464  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:26.464  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:26.464  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:26.464  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:26.464  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:26.464  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:26.464  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 13:34:26.467  3820  3869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 13:34:26.467  3820  3869 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 13:34:26.469   874  1927 D WifiService: setWifiEnabled: false pid=3820, uid=10000
,09-08 13:34:26.470   874  1927 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-08 13:34:26.471  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:26.474  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:26.498  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 13:34:26.502   874  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-08 13:34:26.502   874  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-08 13:34:26.502   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 13:34:26.502   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 13:34:26.531   874  2092 D DhcpClient: Clearing IP address
,09-08 13:34:26.533   372   872 D CommandListener: Setting iface cfg
,09-08 13:34:26.536   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-08 13:34:26.538   874  4037 D DhcpClient: Receive thread stopped
,09-08 13:34:26.540  1501  4116 V NativeCrypto: Read error: ssl=0x9b2cb600: I/O error during system call, Connection timed out
,09-08 13:34:26.544  1501  4116 V NativeCrypto: SSL shutdown failed: ssl=0x9b2cb600: I/O error during system call, Broken pipe
,09-08 13:34:26.549   874  1863 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,09-08 13:34:26.550   874  4035 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
09-08 13:34:26.554   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-08 13:34:26.554   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-08 13:34:26.557   874  1308 D WifiStateMachine: Start Disconnecting Watchdog 2
09-08 13:34:26.559   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 13:34:26.561   395   395 E Parcel  : Reading a NULL string not supported here.
09-08 13:34:26.564   874  4035 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-08 13:34:26.569   874  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-08 13:34:26.618   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 13:34:26.664   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 13:34:26.665   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-08 13:34:26.665   874  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-08 13:34:26.666   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:26.671   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-08 13:34:26.677  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:26.677  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:26.677  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:26.677  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:26.677  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:26.677  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 13:34:26.677  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 13:34:26.677  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 13:34:26.679  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 13:34:26.686  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:26.686  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:26.686  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:26.686  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:26.686  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:26.686  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 13:34:26.686  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 13:34:26.686  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 13:34:26.689  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 13:34:26.699  1724  1724 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 13:34:26.701  2058  2058 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-08 13:34:26.707  1724  1724 D SystemUpdateService: onCreate
,09-08 13:34:26.710  1724  1724 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 13:34:26.719  1724  1724 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 13:34:26.725  1724  2505 I iu.UploadsManager: num queued entries: 0
,09-08 13:34:26.726  1724  2505 I iu.UploadsManager: num updated entries: 0
,09-08 13:34:26.728  1724  4180 I SystemUpdateService: active receiver: enabled
,09-08 13:34:26.730  1724  1724 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 13:34:26.731  1724  1724 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 13:34:26.733  3932  3932 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:26.737  3932  3932 D SprintDMHelper: simOperator: 
,09-08 13:34:26.737  3932  3932 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 13:34:26.762  3137  4184 I Babel   : connection state changed from CONNECTED to DISCONNECTED
09-08 13:34:26.764   372   872 E Netd    : netlink response contains error (No such file or directory)
,09-08 13:34:26.765  1724  4180 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 13:34:26.766   874  1310 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-08 13:34:26.766   874  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-08 13:34:26.773  1724  2505 I iu.SyncManager: NEXT; no task
,09-08 13:34:26.774  1724  4180 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-08 13:34:26.774  1724  4180 I SystemUpdateService: now status is 0 (complete)
,09-08 13:34:26.774  1724  4180 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 13:34:26.774  1724  4180 I SystemUpdateService: file has been verified
09-08 13:34:26.775  1724  4180 I SystemUpdateService: OTA package size = 12249756
,09-08 13:34:26.775   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 13:34:26.779  1882  2318 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 13:34:26.781  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:26.781  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:26.781  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:26.781  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 13:34:26.781  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:26.781  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 13:34:26.781  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 13:34:26.781  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 13:34:26.786  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 13:34:26.790  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:26.790  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:26.790  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:26.790  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 13:34:26.790  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:26.790  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 13:34:26.790  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 13:34:26.790  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 13:34:26.793  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 13:34:26.793  1724  4180 I SystemUpdateService: showing system update notification
,09-08 13:34:26.802   874  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-08 13:34:26.807  1724  1724 D SystemUpdateService: onDestroy
,09-08 13:34:29.483  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:29.484   874  1863 D WifiService: setWifiEnabled: true pid=3820, uid=10000
09-08 13:34:29.485   874  1863 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 13:34:29.499   874  1308 D WifiConfigStore: Loading config and enabling all networks 
,09-08 13:34:29.516  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:29.516  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:29.516  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:29.516  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:29.516  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:29.516  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 13:34:29.516  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 13:34:29.516  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 13:34:29.520  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 13:34:29.528  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:29.528  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:29.528  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:29.528  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:29.528  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:29.528  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 13:34:29.528  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 13:34:29.528  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 13:34:29.532   874  1308 D WifiConfigStore: loaded 0 passpoint configs
,09-08 13:34:29.533   874  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-08 13:34:29.534   874  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-08 13:34:29.534  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 13:34:29.535   874  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-08 13:34:29.535   874  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-08 13:34:29.535   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-08 13:34:29.535   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-08 13:34:29.551   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-08 13:34:29.552   874  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.31 rxSuccessRate=10.31 delta 1000 -> 994
09-08 13:34:29.553   372   872 D CommandListener: Setting iface cfg
09-08 13:34:29.554   874  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-08 13:34:29.554   874  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-08 13:34:29.559   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-08 13:34:29.560   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 13:34:29.567   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 13:34:29.592   874  1310 D ConnectivityService: handlePromptUnvalidated 101
,09-08 13:34:29.597   874  1307 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 13:34:29.598   874  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-08 13:34:29.640   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 13:34:29.642  1460  1460 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 13:34:30.068  1460  1460 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 13:34:30.110  1460  1460 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 13:34:30.110  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 13:34:30.116   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 13:34:30.121   874  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-08 13:34:30.122   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 13:34:30.122   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 13:34:30.134   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 13:34:30.145   372   872 D CommandListener: Setting iface cfg
,09-08 13:34:30.147   874  1308 D WifiStateMachine: Start Dhcp Watchdog 3
,09-08 13:34:30.158   874  1310 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-08 13:34:30.159   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 13:34:30.172   874  4192 D DhcpClient: Receive thread started
,09-08 13:34:30.253   874  1308 E native  : do suspend false
,09-08 13:34:30.264   874  2092 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 13:34:30.288   874  4192 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172792, domain null
,09-08 13:34:30.289   874  2092 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172792 seconds
,09-08 13:34:30.292   874  2092 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 13:34:30.317   874  4192 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 13:34:30.318   874  2092 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 13:34:30.323   372   872 D CommandListener: Setting iface cfg
,09-08 13:34:30.334   874  2092 D DhcpClient: Scheduling renewal in 86399s
,09-08 13:34:30.335   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-08 13:34:30.346   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 13:34:30.347   874  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 13:34:30.347   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-08 13:34:30.347   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-08 13:34:30.353   874  1310 D ConnectivityService: Adding iface wlan0 to network 102
,09-08 13:34:30.354   874  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 13:34:30.415   874  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-08 13:34:30.415   874  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-08 13:34:30.417   874  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-08 13:34:30.418   874  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-08 13:34:30.419   874  1310 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-08 13:34:30.426   874  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 13:34:30.432   874  1310 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-08 13:34:30.432   874  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-08 13:34:30.432   874  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,09-08 13:34:30.432   874  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-08 13:34:30.432   874  1310 D ConnectivityService:    accepting network in place of null
09-08 13:34:30.433   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 13:34:30.433   874  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-08 13:34:30.436   874  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,09-08 13:34:30.481   874  4191 D NetlinkSocketObserver: NeighborEvent{elapsedMs=148988, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 13:34:30.487   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 13:34:30.520   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 13:34:30.530   874  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-08 13:34:30.531   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 13:34:30.539   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-08 13:34:30.542   874  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-08 13:34:30.558  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:30.558  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:30.558  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:30.558  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:30.558  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:30.558  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:30.558  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:30.558  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 13:34:30.561  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 13:34:30.561   874  4190 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-08 13:34:30.566  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 13:34:30.566  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:30.566  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:30.566  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:30.566  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:30.566  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:30.566  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:30.566  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 13:34:30.568  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 13:34:30.571  1724  1724 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 13:34:30.576  2058  2058 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-08 13:34:30.582  1724  1724 D SystemUpdateService: onCreate
,09-08 13:34:30.587  1724  1724 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 13:34:30.602  1724  4201 I SystemUpdateService: active receiver: enabled
,09-08 13:34:30.609  1724  4201 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 13:34:30.609  1724  1724 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 13:34:30.615  1724  2505 I iu.UploadsManager: num queued entries: 0
,09-08 13:34:30.618  1724  1724 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-08 13:34:30.619  1724  1724 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 13:34:30.620   874  4190 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 11:34:30 GMT], X-Android-Received-Millis=[1473334470619], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473334470598]}
,09-08 13:34:30.623   874  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-08 13:34:30.623   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-08 13:34:30.623   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-08 13:34:30.624  3932  3932 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-08 13:34:30.625  1724  4204 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-08 13:34:30.625  1724  4204 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 13:34:30.629  1724  4204 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 13:34:30.628   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-08 13:34:30.631  3932  3932 D SprintDMHelper: simOperator: 
09-08 13:34:30.631  3932  3932 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 13:34:30.622  1724  4201 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-08 13:34:30.635  1724  4201 I SystemUpdateService: now status is 0 (complete)
,09-08 13:34:30.635  1724  4201 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-08 13:34:30.635  1724  4201 I SystemUpdateService: file has been verified
,09-08 13:34:30.635  1724  4201 I SystemUpdateService: OTA package size = 12249756
,09-08 13:34:30.653  1724  2505 I iu.UploadsManager: num updated entries: 0
,09-08 13:34:30.661  1724  2505 I iu.SyncManager: NEXT; no task
,09-08 13:34:30.661  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 13:34:30.665  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 13:34:30.666  1724  4201 I SystemUpdateService: showing system update notification
,09-08 13:34:30.705  1724  1724 D SystemUpdateService: onDestroy
,09-08 13:34:30.706  1501  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-08 13:34:30.707  1501  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-08 13:34:30.707  1501  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 13:34:30.708  1501  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 13:34:30.721  1724  4204 E MDM     : [182] SitrepService.a: Error sending sitrep.
,09-08 13:34:30.764  3137  4207 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 13:34:31.530   874  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-08 13:34:32.504  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:32.505  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 13:34:32.505  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 13:34:32.506  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 13:34:32.506  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-08 13:34:32.506  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fdaf72a removed from the list
,09-08 13:34:32.508  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:32.510  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c06391b removed from the list
09-08 13:34:32.510  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:32.510  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:32.526  3820  4214 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-08 13:34:32.526  3820  4214 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 13:34:33.044  3820  4216 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-08 13:34:33.044  3820  4214 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-08 13:34:33.045  3820  4216 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-08 13:34:33.045  3820  4214 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-08 13:34:33.046  3820  4214 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 13:34:33.047  3820  4216 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 13:34:33.049  3820  4216 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 13:34:33.049  3820  4214 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 13:34:33.052  3820  4219 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 489, name: IncomingSocketThread/Sender)
,09-08 13:34:33.054  3820  4214 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-08 13:34:33.054  3820  4216 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-08 13:34:33.065  3820  4221 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 491, name: OutgoingSocketThread/Receiver)
,09-08 13:34:33.066  3820  4220 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 488, name: OutgoingSocketThread/Sender)
,09-08 13:34:33.067  3820  4221 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 491, thread name: OutgoingSocketThread/Receiver)
,09-08 13:34:33.067  3820  4221 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-08 13:34:33.068  3820  4221 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 491, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-08 13:34:33.068  3820  4222 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 490, name: IncomingSocketThread/Receiver)
09-08 13:34:33.070  3820  4222 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 490, thread name: IncomingSocketThread/Receiver)
09-08 13:34:33.070  3820  4222 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-08 13:34:33.070  3820  4222 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 490, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-08 13:34:33.184   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 13:34:33.549  3820  3869 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-08 13:34:33.551  3820  3869 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-08 13:34:33.557  3820  3869 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@186d94f Bundle[{}]
,09-08 13:34:33.558  3820  3869 I io.jxcore.node.LifeCycleMonitor: start: OK
09-08 13:34:33.558  3820  3869 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-08 13:34:33.559  3820  3869 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-08 13:34:33.559  3820  3869 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-08 13:34:33.560  3820  3869 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-08 13:34:33.560  3820  3869 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-08 13:34:33.569  3820  4223 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-08 13:34:33.569  3820  4223 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 13:34:33.581  3820  4223 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-08 13:34:33.581  3820  4223 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-08 13:34:33.582  3820  4223 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 13:34:33.583  3820  4223 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 13:34:33.584  3820  4225 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-08 13:34:33.584  3820  4225 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-08 13:34:33.584  3820  4225 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 13:34:33.586  3820  4227 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 502, name: OutgoingSocketThread/Sender)
,09-08 13:34:33.586  3820  4225 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 13:34:33.586  3820  4228 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 504, name: IncomingSocketThread/Sender)
09-08 13:34:33.587  3820  4223 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-08 13:34:33.588  3820  4229 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 503, name: OutgoingSocketThread/Receiver)
09-08 13:34:33.589  3820  4229 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 503, thread name: OutgoingSocketThread/Receiver)
09-08 13:34:33.589  3820  4229 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-08 13:34:33.589  3820  4229 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 503, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-08 13:34:33.590  3820  4225 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-08 13:34:33.590  3820  4230 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 505, name: IncomingSocketThread/Receiver)
09-08 13:34:33.592  3820  4230 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 505, thread name: IncomingSocketThread/Receiver)
09-08 13:34:33.592  3820  4230 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-08 13:34:33.592  3820  4230 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 505, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-08 13:34:34.391   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-08 13:34:34.400  1893  1893 I Keyboard.Facilitator: onFinishInput()
,09-08 13:34:34.417   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 13:34:34.417   874   894 I Adreno  : Build Date                       : 10/20/15
09-08 13:34:34.417   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 13:34:34.417   874   894 I Adreno  : Local Branch                     : M14
09-08 13:34:34.417   874   894 I Adreno  : Remote Branch                    : 
09-08 13:34:34.417   874   894 I Adreno  : Remote Branch                    : 
09-08 13:34:34.417   874   894 I Adreno  : Reconstruct Branch               : 
,09-08 13:34:34.462   280   897 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (320 us)
,09-08 13:34:35.127  3820  3820 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-08 13:34:35.128  3820  3820 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-08 13:34:35.165   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-08 13:34:35.166  3820  3820 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@186d94f Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@9d9c091, 16908290=android.view.AbsSavedState$1@9d9c091}, android:focusedViewId=100}]}]
09-08 13:34:35.166  3820  3820 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-08 13:34:35.167  3820  3820 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-08 13:34:35.167  3820  3820 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-08 13:34:35.172   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
09-08 13:34:35.177   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-08 13:34:35.183   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
09-08 13:34:35.184   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-08 13:34:35.410   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-08 13:34:35.414   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-08 13:34:35.420   874  1334 D SurfaceControl: Excessive delay in setPowerMode(): 243ms
,09-08 13:34:35.426   874   894 I DreamManagerService: Entering dreamland.
09-08 13:34:35.427   874   894 I PowerManagerService: Dozing...
,09-08 13:34:35.428   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-08 13:34:35.480   376  1317 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-08 13:34:35.481   376  1317 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-08 13:34:35.498   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 13:34:35.504  1960  4235 D NfcService: Discovery configuration equal, not updating.
,09-08 13:34:35.515   874  1308 E native  : do suspend false
,09-08 13:34:35.537   874  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 13:34:35.550   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 13:34:35.559   874  1308 E native  : do suspend true
,09-08 13:34:35.615   376  1281 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-08 13:34:35.615   376  1281 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-08 13:34:36.004   874  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 16 -> obsolete
,09-08 13:34:36.594  3820  3869 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 514)
,09-08 13:34:36.596  3820  3869 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-08 13:34:36.597  3820  3869 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 515)
,09-08 13:34:36.602  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 13:34:36.602  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b895bf6 added. We now have 2 listener(s)
,09-08 13:34:36.604  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 13:34:36.604  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 13:34:36.604  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 13:34:36.604  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 13:34:36.604  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c54bf7 added. We now have 2 listener(s)
09-08 13:34:36.604  3820  3869 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 13:34:36.605  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 13:34:36.608  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 13:34:36.619  3820  3869 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 13:34:36.619  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 13:34:36.619  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 13:34:36.619  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 13:34:36.619  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 13:34:36.619  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 13:34:36.619  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 13:34:36.619  3820  3869 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 13:34:36.624  3820  3869 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 13:34:36.624  3820  3869 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 13:34:36.628  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:36.632  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 13:34:36.636  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 13:34:36.637  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:36.637  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 13:34:36.637  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 13:34:36.637  3820  3869 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b895bf6 removed from the list
09-08 13:34:36.638  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 13:34:36.638  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c54bf7 removed from the list
09-08 13:34:36.638  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:36.638  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:36.641  3820  3869 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,09-08 13:34:36.641  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,09-08 13:34:36.643  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 13:34:36.643  3820  3869 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-08 13:34:36.643  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-08 13:34:36.643  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 13:34:36.645  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-08 13:34:36.646  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-08 13:34:36.646  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 13:34:36.647  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING,
09-08 13:34:36.647  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-08 13:34:36.648  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 13:34:36.649  3820  4239 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 13:34:36.649  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 13:34:36.650  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 13:34:36.654  3820  4239 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-08 13:34:36.662  3820  3869 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 13:34:36.662  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 13:34:36.670  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 13:34:36.670  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 13:34:36.671  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 13:34:36.673  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-08 13:34:36.673  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 13:34:36.673  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 F8 CF C5 D9 E5 61
09-08 13:34:36.674  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-08 13:34:36.674  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 13:34:36.674  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-08 13:34:36.675  3820  3869 D BluetoothAdapter: STATE_ON
,09-08 13:34:36.680  4121  4161 D BtGatt.GattService: registerClient() - UUID=5855abc8-9747-4f84-887c-24240e09ab3f
,09-08 13:34:36.682  4121  4137 D BtGatt.GattService: onClientRegistered() - UUID=5855abc8-9747-4f84-887c-24240e09ab3f, clientIf=5
,09-08 13:34:36.683  3820  3832 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-08 13:34:36.685  4121  4139 D BtGatt.AdvertiseManager: message : 0
,09-08 13:34:36.689  4121  4139 D BtGatt.AdvertiseManager: starting multi advertising
,09-08 13:34:36.713  4121  4137 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-08 13:34:36.728  4121  4137 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-08 13:34:36.729  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-08 13:34:36.730  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 13:34:36.733  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 13:34:36.735  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 13:34:36.736  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-08 13:34:36.736  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-08 13:34:36.736  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-08 13:34:36.736  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-08 13:34:36.737  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-08 13:34:36.742  3820  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-08 13:34:36.742  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 13:34:37.244  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-08 13:34:37.244  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 13:34:37.244  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 13:34:37.639  1501  2149 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-08 13:34:38.438   874  1310 D ConnectivityService: handlePromptUnvalidated 102
,09-08 13:34:40.240  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-08 13:34:40.240  3820  3869 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-08 13:34:40.241  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 13:34:40.241  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-08 13:34:40.241  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-08 13:34:40.244  3820  4239 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 13:34:40.244  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 13:34:40.244  3820  4239 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 13:34:40.244  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-08 13:34:40.244  3820  4239 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-08 13:34:40.245  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 13:34:40.245  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 13:34:40.246  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 13:34:40.246  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 13:34:40.247  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 13:34:40.247  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 13:34:40.249  3820  3869 D BluetoothAdapter: STATE_ON
09-08 13:34:40.250  3820  3869 D BluetoothLeScanner: could not find callback wrapper
,09-08 13:34:40.250  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 13:34:40.250  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-08 13:34:40.253  4121  4139 D BtGatt.AdvertiseManager: message : 1
09-08 13:34:40.254  4121  4139 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-08 13:34:40.264  4121  4137 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-08 13:34:40.265  4121  4137 D BtGatt.GattService: Client app is not null!
,09-08 13:34:40.267  4121  4161 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 13:34:40.268  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 13:34:40.268  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-08 13:34:40.268  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-08 13:34:40.268  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-08 13:34:40.268  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-08 13:34:40.271  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 13:34:40.271  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 13:34:40.272  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 13:34:40.273  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:40.276  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 13:34:40.276  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-08 13:34:40.277  3820  3820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-08 13:34:40.277  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 13:34:40.277  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-08 13:34:40.278  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
,09-08 13:34:40.281  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 13:34:40.281  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 13:34:40.281  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:40.282  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b895bf6 not in the list
,09-08 13:34:40.282  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:40.282  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c54bf7 not in the list
,09-08 13:34:40.282  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:40.283  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-08 13:34:40.283  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:40.285  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 13:34:40.286  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 13:34:40.287  3820  3869 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 13:34:40.287  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-08 13:34:40.287  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 13:34:40.287  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 13:34:40.296  3820  3869 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 13:34:40.297  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 13:34:40.305  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 13:34:40.305  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 13:34:40.306  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 13:34:40.312  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 13:34:40.312  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-08 13:34:40.313  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 13:34:40.315  3820  3869 D BluetoothAdapter: STATE_ON
,09-08 13:34:40.319  4121  4160 D BtGatt.GattService: registerClient() - UUID=4cb3985e-291e-443d-b1f1-96cfb16ac97f
,09-08 13:34:40.319  4121  4137 D BtGatt.GattService: onClientRegistered() - UUID=4cb3985e-291e-443d-b1f1-96cfb16ac97f, clientIf=5
09-08 13:34:40.320  3820  3975 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 13:34:40.322  4121  4148 D BtGatt.GattService: start scan with filters
,09-08 13:34:40.327  4121  4140 D BtGatt.ScanManager: handling starting scan
,09-08 13:34:40.327  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 13:34:40.329  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 13:34:40.329  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-08 13:34:40.329  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-08 13:34:40.330  4121  4140 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c520f3
,09-08 13:34:40.334  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 13:34:40.335  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 13:34:40.335  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 13:34:40.337  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,09-08 13:34:40.342  4121  4137 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 13:34:40.342  4121  4137 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 13:34:40.343  4121  4140 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 13:34:40.352  4121  4137 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 13:34:40.352  4121  4137 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 13:34:40.353  4121  4140 D BtGatt.ScanManager: Starting BLE batch scan
,09-08 13:34:40.353  4121  4140 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 13:34:40.376  4121  4137 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 13:34:40.376  4121  4137 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 13:34:40.391  4121  4137 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 13:34:40.392  4121  4137 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 13:34:40.813  1882  2647 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-08 13:34:40.836  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 13:34:40.837  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 13:34:40.837  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 13:34:41.575   874  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 16 -> obsolete
,09-08 13:34:41.896  4121  4121 D BtGatt.ScanManager: awakened up at time 160403
,09-08 13:34:41.898  4121  4140 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 13:34:41.987  4121  4137 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=14
09-08 13:34:41.987  4121  4137 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 13:34:41.988  4121  4137 D BtGatt.GattService: current time is 160495564488
,09-08 13:34:41.992  4121  4137 D BtGatt.GattService: Batch record : [78, -20, -96, 83, -39, -56, 1, -128, -93, 26, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 118, 39, 0, -4, -21, -104, -53, -127, 121, 1, -128, -89, 23, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -112, -25, -60, -2, -84, -17, 0, 87, 45, 110, 28, -13, -4, 1, -128, -74, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 55, -106, -85, 0, -126, -22, -96, 83, -39, -56, 1, -128, -68, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 117, 65, 0, 116, -43, -111, -91, -20, -29, 1, -128, -78, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -79, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -80, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -79, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, -19, 96, -26, 83, -128, 123, 1, -128, -37, 16, 0, 0, 0, -46, -4, -117, 6, 105, -37, 1, -128, -81, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, -19, 96, -26, 83, -128, 123, 1, -128, -36, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 52, -118, -96, 0, 37, -47, 14, -113, 116, -46, 1, -128, -95, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -126, -22, -96, 83, -39, -56, 1, -128, -68, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 117, 65, 0, -19, 96, -26, 83, -128, 123, 1, -128, -38, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 52, -118, -96, 0]
,09-08 13:34:41.998  4121  4137 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 118, 39]
,09-08 13:34:42.001  4121  4137 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -112, -25, -60, -2, -84, -17]
,09-08 13:34:42.002  4121  4137 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 55, -106, -85]
,09-08 13:34:42.002  4121  4137 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 117, 65]
,09-08 13:34:42.003  4121  4137 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
09-08 13:34:42.004  4121  4137 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-08 13:34:42.005  4121  4137 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
09-08 13:34:42.005  4121  4137 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,09-08 13:34:42.006  4121  4137 D BtGatt.GattService: ScanRecord : []
,09-08 13:34:42.007  4121  4137 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-08 13:34:42.008  4121  4137 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 52, -118, -96]
,09-08 13:34:42.009  4121  4137 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 13:34:42.010  4121  4137 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 8, -20, -87, 80, 117, 65]
,09-08 13:34:42.010  4121  4137 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 124, -7, 14, 52, -118, -96]
,09-08 13:34:42.023  3820  3820 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 90:E7:C4:FE:AC:EF 5], added - the peer count is 1
,09-08 13:34:42.024  3820  3820 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 5], added - the peer count is 2
,09-08 13:34:42.025  3820  3820 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 08:EC:A9:50:76:27 5], added - the peer count is 3
,09-08 13:34:42.026  3820  3820 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 08:EC:A9:50:75:41 5], added - the peer count is 4
,09-08 13:34:42.028  3820  3820 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 7C:F9:0E:34:8A:A0 5] updated - the peer count is 4
,09-08 13:34:42.028  3820  3820 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: Timestamp of peer [<no peer name> 08:EC:A9:50:75:41 5] updated - the peer count is 4
,09-08 13:34:42.029  3820  3820 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:37:96:AB 5], added - the peer count is 5
,09-08 13:34:42.030  3820  3820 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 90:E7:C4:FE:AC:EF 5], Bluetooth address: 90:E7:C4:FE:AC:EF, device name: '', device address: ''
,09-08 13:34:42.031  3820  3820 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 5], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,09-08 13:34:42.032  3820  3820 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 08:EC:A9:50:76:27 5], Bluetooth address: 08:EC:A9:50:76:27, device name: '', device address: ''
,09-08 13:34:42.033  3820  3820 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 08:EC:A9:50:75:41 5], Bluetooth address: 08:EC:A9:50:75:41, device name: '', device address: ''
,09-08 13:34:42.034  3820  3820 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:37:96:AB 5], Bluetooth address: 7C:F9:0E:37:96:AB, device name: '', device address: ''
,09-08 13:34:43.344  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 13:34:43.345  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 13:34:43.345  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 13:34:43.345  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b895bf6 not in the list
09-08 13:34:43.346  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:43.346  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 13:34:43.346  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 13:34:43.347  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 13:34:43.347  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 13:34:43.348  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 13:34:43.350  3820  3869 D BluetoothAdapter: STATE_ON
09-08 13:34:43.352  4121  4160 D BtGatt.GattService: stopScan() - queue size =1
,09-08 13:34:43.355  4121  4148 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 13:34:43.356  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 13:34:43.357  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 13:34:43.357  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 13:34:43.358  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 13:34:43.359  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 13:34:43.362  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 13:34:43.363  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 13:34:43.363  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 13:34:43.364  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 13:34:43.365  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:43.365  3820  3869 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,09-08 13:34:43.368  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 13:34:43.368  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c54bf7 not in the list
09-08 13:34:43.368  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-08 13:34:43.368  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 13:34:43.368  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 13:34:43.369  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 13:34:43.369  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:43.376  4121  4121 D BtGatt.ScanManager: awakened up at time 161883
,09-08 13:34:43.377  3820  3869 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,09-08 13:34:43.376  4121  4137 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 13:34:43.380  4121  4137 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 13:34:43.381  4121  4140 D BtGatt.ScanManager: stopping BLe Batch
09-08 13:34:43.382  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,09-08 13:34:43.382  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 13:34:43.383  3820  3869 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-08 13:34:43.383  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 13:34:43.383  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:43.386  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-08 13:34:43.387  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-08 13:34:43.388  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 13:34:43.388  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 13:34:43.388  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 13:34:43.388  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 13:34:43.388  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 13:34:43.389  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 13:34:43.390  4121  4137 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 13:34:43.391  4121  4137 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 13:34:43.391  3820  4243 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 13:34:43.391  4121  4140 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-08 13:34:43.396  3820  3869 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 13:34:43.396  3820  4243 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-08 13:34:43.396  3820  3869 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 13:34:43.401  4121  4137 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 13:34:43.401  4121  4137 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 13:34:43.406  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 13:34:43.407  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings,
09-08 13:34:43.407  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 13:34:43.410  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-08 13:34:43.410  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 13:34:43.410  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 F8 CF C5 D9 E5 61
09-08 13:34:43.411  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 13:34:43.411  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 13:34:43.411  3820  3869 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-08 13:34:43.412  3820  3869 D BluetoothAdapter: STATE_ON
09-08 13:34:43.415  4121  4160 D BtGatt.GattService: registerClient() - UUID=fb36a958-c0ba-4995-9178-1fc04f5a33ec
09-08 13:34:43.416  4121  4137 D BtGatt.GattService: onClientRegistered() - UUID=fb36a958-c0ba-4995-9178-1fc04f5a33ec, clientIf=5
,09-08 13:34:43.416  3820  3831 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-08 13:34:43.418  4121  4139 D BtGatt.AdvertiseManager: message : 0
,09-08 13:34:43.420  4121  4139 D BtGatt.AdvertiseManager: starting multi advertising
,09-08 13:34:43.430  4121  4137 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-08 13:34:43.432  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 13:34:43.436  4121  4137 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-08 13:34:43.436  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-08 13:34:43.436  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 13:34:43.438  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 13:34:43.439  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 13:34:43.440  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-08 13:34:43.440  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-08 13:34:43.440  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-08 13:34:43.440  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-08 13:34:43.440  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-08 13:34:43.443  3820  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 13:34:43.443  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 13:34:43.539  1501  4246 I VacuumService: Vacuum at: now=1473334483539 tag=VacuumService
,09-08 13:34:43.616  1501  4247 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-08 13:34:43.618  1501  4247 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-08 13:34:43.649  1501  4247 W Uploader:  no longer exists, so no auth token.
,09-08 13:34:43.944  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-08 13:34:43.944  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 13:34:43.945  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 13:34:44.662   874  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 16 -> obsolete
,09-08 13:34:45.037  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 13:34:45.040  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 13:34:45.097  1501  4247 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-08 13:34:45.097  1501  4247 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-08 13:34:45.097  1501  4247 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 13:34:45.097  1501  4247 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 13:34:45.121  1501  4247 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 13:34:45.121  1501  4247 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 13:34:45.121  1501  4247 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 13:34:45.121  1501  4247 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 13:34:45.121  1501  4247 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-08 13:34:45.121  1501  4247 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-08 13:34:45.121  1501  4247 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-08 13:34:45.121  1501  4247 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-08 13:34:45.121  1501  4247 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-08 13:34:45.121  1501  4247 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-08 13:34:45.121  1501  4247 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-08 13:34:45.121  1501  4247 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-08 13:34:45.121  1501  4247 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-08 13:34:45.434  1501  4247 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-08 13:34:45.435  1501  4247 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-08 13:34:45.435  1501  4247 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 13:34:45.436  1501  4247 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 13:34:45.482  1501  4247 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 13:34:45.482  1501  4247 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 13:34:45.482  1501  4247 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 13:34:45.482  1501  4247 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 13:34:45.482  1501  4247 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-08 13:34:45.482  1501  4247 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-08 13:34:45.482  1501  4247 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-08 13:34:45.482  1501  4247 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-08 13:34:45.482  1501  4247 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-08 13:34:45.482  1501  4247 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-08 13:34:45.482  1501  4247 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-08 13:34:45.482  1501  4247 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-08 13:34:45.482  1501  4247 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-08 13:34:46.025  1501  4247 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-08 13:34:46.025  1501  4247 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-08 13:34:46.025  1501  4247 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 13:34:46.025  1501  4247 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 13:34:46.051  1501  4247 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 13:34:46.051  1501  4247 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 13:34:46.051  1501  4247 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 13:34:46.051  1501  4247 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 13:34:46.051  1501  4247 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-08 13:34:46.051  1501  4247 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-08 13:34:46.051  1501  4247 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-08 13:34:46.051  1501  4247 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-08 13:34:46.051  1501  4247 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-08 13:34:46.051  1501  4247 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-08 13:34:46.051  1501  4247 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-08 13:34:46.051  1501  4247 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-08 13:34:46.051  1501  4247 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-08 13:34:46.944  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 13:34:46.945  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 13:34:46.945  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-08 13:34:46.945  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-08 13:34:46.946  3820  4243 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 13:34:46.947  3820  4243 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 13:34:46.947  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 13:34:46.947  3820  4243 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 13:34:46.947  3820  3869 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 13:34:46.948  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b895bf6 not in the list
09-08 13:34:46.948  3820  3820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-08 13:34:46.948  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:46.948  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-08 13:34:46.948  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 13:34:46.948  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 13:34:46.949  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 13:34:46.949  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 13:34:46.962  3820  3869 D BluetoothAdapter: STATE_ON
,09-08 13:34:46.962  3820  3869 D BluetoothLeScanner: could not find callback wrapper
09-08 13:34:46.963  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 13:34:46.964  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-08 13:34:46.965  4121  4139 D BtGatt.AdvertiseManager: message : 1
,09-08 13:34:46.966  4121  4139 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-08 13:34:46.970  4121  4137 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-08 13:34:46.970  4121  4137 D BtGatt.GattService: Client app is not null!
,09-08 13:34:46.972  4121  4160 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 13:34:46.974  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 13:34:46.974  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-08 13:34:46.974  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-08 13:34:46.975  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-08 13:34:46.975  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-08 13:34:46.978  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 13:34:46.978  3820  3869 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 13:34:46.978  3820  3869 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 13:34:46.980  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:46.983  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 13:34:46.983  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 13:34:46.983  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c54bf7 not in the list
,09-08 13:34:46.984  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 13:34:46.984  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 13:34:46.984  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 13:34:46.984  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:46.986  3820  3869 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 13:34:46.986  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 13:34:46.987  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 13:34:46.987  3820  3869 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b895bf6 not in the list
09-08 13:34:46.987  3820  3869 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 13:34:46.987  3820  3869 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c54bf7 not in the list
09-08 13:34:46.988  3820  3869 D io.jxcore.node.ConnectivityMonitor: stop
09-08 13:34:46.988  3820  3869 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 13:34:46.988  3820  3869 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 13:34:46.990  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-08 13:34:46.991  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-08 13:34:46.991  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-08 13:34:46.991  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 13:34:46.992  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-08 13:34:46.992  3820  3869 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 13:34:47.010  3820  4260 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 535, name: My test thread name)
,09-08 13:34:47.485  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 13:34:49.008  3820  3869 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 535
,09-08 13:34:49.009  3820  3869 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 535, name: My test thread name)
,09-08 13:34:49.015  3820  4261 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 536, name: My test thread name)
,09-08 13:34:49.016  3820  4261 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 536, thread name: My test thread name)
,09-08 13:34:49.016  3820  4260 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 535, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
09-08 13:34:49.016  3820  4261 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 536, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-08 13:34:49.022  3820  3869 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 13:34:49.030  3820  4262 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 540, name: My test thread name)
,09-08 13:34:49.031  3820  4262 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 540, thread name: My test thread name): Test exception.
09-08 13:34:49.031  3820  4262 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 540, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-08 13:34:49.039  3820  3869 I jxcore-log: Total number of executed tests:  82
09-08 13:34:49.039  3820  3869 I jxcore-log: 
,09-08 13:34:49.040  3820  3869 I jxcore-log: Number of passed tests:  82
09-08 13:34:49.040  3820  3869 I jxcore-log: 
09-08 13:34:49.041  3820  3869 I jxcore-log: Number of failed tests:  0
09-08 13:34:49.041  3820  3869 I jxcore-log: 
,09-08 13:34:49.043  3820  3869 I jxcore-log: Number of ignored tests:  0
09-08 13:34:49.043  3820  3869 I jxcore-log: 
,09-08 13:34:49.044  3820  3869 I jxcore-log: Total duration:  39114
09-08 13:34:49.044  3820  3869 I jxcore-log: 
,09-08 13:34:49.050  3820  3869 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-08 13:34:49.050  3820  3869 I jxcore-log: 
,09-08 13:34:49.053  3820  3869 I jxcore-log: My device name is: motorola-Nexus 6
09-08 13:34:49.053  3820  3869 I jxcore-log: 
09-08 13:34:49.062  3820  3869 I jxcore-log: WARN testUtils: myNameCallback not set!
09-08 13:34:49.062  3820  3869 I jxcore-log: 
,09-08 13:34:49.069  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:49.069  3820  3869 I jxcore-log: 
,09-08 13:34:49.070  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:49.070  3820  3869 I jxcore-log: 
,09-08 13:34:49.072  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-08 13:34:49.072  3820  3869 I jxcore-log: 
,09-08 13:34:49.074  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:49.074  3820  3869 I jxcore-log: 
,09-08 13:34:49.077  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-08 13:34:49.077  3820  3869 I jxcore-log: 
,09-08 13:34:49.079  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:49.079  3820  3869 I jxcore-log: 
,09-08 13:34:49.080  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-08 13:34:49.080  3820  3869 I jxcore-log: 
09-08 13:34:49.080  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:49.080  3820  3869 I jxcore-log: 
,09-08 13:34:49.081  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:49.081  3820  3869 I jxcore-log: 
09-08 13:34:49.082  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:49.082  3820  3869 I jxcore-log: 
,09-08 13:34:49.083  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 13:34:49.083  3820  3869 I jxcore-log: 
09-08 13:34:49.084  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 13:34:49.084  3820  3869 I jxcore-log: 
,09-08 13:34:49.085  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 13:34:49.085  3820  3869 I jxcore-log: 
,09-08 13:34:49.086  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 13:34:49.086  3820  3869 I jxcore-log: 
,09-08 13:34:49.087  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 13:34:49.087  3820  3869 I jxcore-log: 
09-08 13:34:49.088  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 13:34:49.088  3820  3869 I jxcore-log: 
,09-08 13:34:49.088  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 13:34:49.088  3820  3869 I jxcore-log: 
09-08 13:34:49.089  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
,09-08 13:34:49.089  3820  3869 I jxcore-log: 
09-08 13:34:49.090  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 13:34:49.090  3820  3869 I jxcore-log: 
,09-08 13:34:49.091  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
,09-08 13:34:49.091  3820  3869 I jxcore-log: ,
09-08 13:34:49.092  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:49.092  3820  3869 I jxcore-log: 
09-08 13:34:49.093  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:49.093  3820  3869 I jxcore-log: 
09-08 13:34:49.094  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:49.094  3820  3869 I jxcore-log: 
09-08 13:34:49.095  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:49.095  3820  3869 I jxcore-log: 
,09-08 13:34:49.096  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 13:34:49.096  3820  3869 I jxcore-log: 
09-08 13:34:49.097  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 13:34:49.097  3820  3869 I jxcore-log: 
,09-08 13:34:49.098  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 13:34:49.098  3820  3869 I jxcore-log: 
,09-08 13:34:49.099  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 13:34:49.099  3820  3869 I jxcore-log: 
09-08 13:34:49.100  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 13:34:49.100  3820  3869 I jxcore-log: 
,09-08 13:34:49.101  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 13:34:49.101  3820  3869 I jxcore-log: 
09-08 13:34:49.101  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:49.101  3820  3869 I jxcore-log: 
,09-08 13:34:49.102  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:49.102  3820  3869 I jxcore-log: 
,09-08 13:34:49.104  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 13:34:49.104  3820  3869 I jxcore-log: 
09-08 13:34:49.104  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-08 13:34:49.104  3820  3869 I jxcore-log: 
09-08 13:34:49.105  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 13:34:49.105  3820  3869 I jxcore-log: 
,09-08 13:34:49.107  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-08 13:34:49.107  3820  3869 I jxcore-log: 
09-08 13:34:49.108  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-08 13:34:49.108  3820  3869 I jxcore-log: 
09-08 13:34:49.109  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-08 13:34:49.109  3820  3869 I jxcore-log: 
09-08 13:34:49.109  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-08 13:34:49.109  3820  3869 I jxcore-log: 
,09-08 13:34:49.110  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-08 13:34:49.110  3820  3869 I jxcore-log: 
,09-08 13:34:49.110  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-08 13:34:49.110  3820  3869 I jxcore-log: 
,09-08 13:34:49.111  3820  3869 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 13:34:49.111  3820  3869 I jxcore-log: 
,09-08 13:34:49.689  4263  4263 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-08 13:34:49.695  4263  4263 D AndroidRuntime: CheckJNI is OFF
,09-08 13:34:49.738  4263  4263 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-08 13:34:49.780  4263  4263 I Radio-JNI: register_android_hardware_Radio DONE
,09-08 13:34:49.802  4263  4263 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-08 13:34:49.814   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-08 13:34:49.816   874   887 I ActivityManager: Killing 3820:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-08 13:34:49.899   874   898 W PackageSettings: Skipping PackageSetting{cbf6794 com.example.hello/10273} due to missing metadata
,09-08 13:34:49.921   874  1309 D WifiService: Client connection lost with reason: 4
,09-08 13:34:49.921   874  1391 I WindowState: WIN DEATH: Window{853ba5b u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-08 13:34:49.922   874  2040 D GraphicsStats: Buffer count: 2
,09-08 13:34:49.926   874   898 I art     : Starting a blocking GC Explicit
,09-08 13:34:49.947   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-08 13:34:49.948   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-08 13:34:49.952   874   887 E ActivityManager: Failure starting process com.test.thalitest
09-08 13:34:49.952   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-08 13:34:49.952   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-08 13:34:49.952   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-08 13:34:49.952   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-08 13:34:49.952   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-08 13:34:49.952   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-08 13:34:49.952   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-08 13:34:49.952   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-08 13:34:49.952   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-08 13:34:49.952   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-08 13:34:49.952   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-08 13:34:49.952   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-08 13:34:49.952   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-08 13:34:49.952   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-08 13:34:49.952   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-08 13:34:49.952   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 13:34:49.952   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-08 13:34:49.952   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 13:34:49.952   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-08 13:34:49.953   874   887 I ActivityManager:   Force finishing activity ActivityRecord{3a51980 u0 com.test.thalitest/.MainActivity t4}
,09-08 13:34:49.958   874  2037 W ActivityManager: Spurious death for ProcessRecord{c46968d 0:com.test.thalitest/u0a0}, curProc for 3820: null
,09-08 13:34:49.985   874   898 I art     : Explicit concurrent mark sweep GC freed 37398(2MB) AllocSpace objects, 8(200KB) LOS objects, 33% free, 29MB/43MB, paused 794us total 58.523ms
09-08 13:34:50.008   874   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-08 13:34:50.010  4263  4263 I art     : System.exit called, status: 0
09-08 13:34:50.010  4263  4263 I AndroidRuntime: VM exiting with result code 0.
09-08 13:34:50.012   874   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-08 13:34:50.019   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-08 13:34:50.023  4121  4121 D BluetoothMapAppObserver: onReceive
09-08 13:34:50.023  4121  4121 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-08 13:34:50.023  1882  2271 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-08 13:34:50.027   874  1300 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-08 13:34:50.038  3662  3662 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-08 13:34:50.062  1893  1893 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-08 13:34:50.072  1973  1973 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-08 13:34:50.075  1893  4278 I Keyboard.Facilitator.DecoderInitializer: run()
,09-08 13:34:50.075   874  2037 I ActivityManager: Start proc 4276:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-08 13:34:50.083  1893  4278 I Decoder : createOrResetDecoder
,09-08 13:34:50.093  1501  1501 I ConfigService: onCreate
,09-08 13:34:50.105   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-08 13:34:50.119  1893  4278 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-08 13:34:50.136   874   886 E PackageManager: Failed to write settings, restoring backup
09-08 13:34:50.136   874   886 E PackageManager: java.io.IOException: write failed: EBADF (Bad file descriptor)
09-08 13:34:50.136   874   886 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:498)
09-08 13:34:50.136   874   886 E PackageManager: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
09-08 13:34:50.136   874   886 E PackageManager: 	at java.io.OutputStreamWriter.flushBytes(OutputStreamWriter.java:170)
09-08 13:34:50.136   874   886 E PackageManager: 	at java.io.OutputStreamWriter.convert(OutputStreamWriter.java:184)
09-08 13:34:50.136   874   886 E PackageManager: 	at java.io.OutputStreamWriter.write(OutputStreamWriter.java:269)
09-08 13:34:50.136   874   886 E PackageManager: 	at java.io.BufferedWriter.write(BufferedWriter.java:236)
09-08 13:34:50.136   874   886 E PackageManager: 	at org.kxml2.io.KXmlSerializer.writeEscaped(KXmlSerializer.java:131)
09-08 13:34:50.136   874   886 E PackageManager: 	at org.kxml2.io.KXmlSerializer.attribute(KXmlSerializer.java:469)
09-08 13:34:50.136   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissions(Settings.java:4812)
09-08 13:34:50.136   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4635)
09-08 13:34:50.136   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-08 13:34:50.136   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-08 13:34:50.136   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 13:34:50.136   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-08 13:34:50.136   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 13:34:50.136   874   886 E PackageManager: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
09-08 13:34:50.136   874   886 E PackageManager: 	at libcore.io.Posix.writeBytes(Native Method)
09-08 13:34:50.136   874   886 E PackageManager: 	at libcore.io.Posix.write(Posix.java:271)
09-08 13:34:50.136   874   886 E PackageManager: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
09-08 13:34:50.136   874   886 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:493)
09-08 13:34:50.136   874   886 E PackageManager: 	... 14 more
,09-08 13:34:50.137  4276  4276 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-08 13:34:50.140   874  1982 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3820 uid 10000
,09-08 13:34:50.142  1893  1893 I Keyboard.Facilitator: onFinishInput()
,09-08 13:34:50.147  1893  4278 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-08 13:34:50.151  1893  4278 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-08 13:34:50.151  1893  4278 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-08 13:34:50.153  1893  4278 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-08 13:34:50.153  1893  4278 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-08 13:34:50.154   874  2033 I ActivityManager: Start proc 4291:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-08 13:34:50.155  1992  2086 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-08 13:34:50.155  1992  2086 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1992
09-08 13:34:50.155  1992  2086 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
09-08 13:34:50.155  1992  2086 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 13:34:50.155  1992  2086 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-08 13:34:50.155  1992  2086 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 13:34:50.155  1992  2086 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 13:34:50.155  1992  2086 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-08 13:34:50.155  1992  2086 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-08 13:34:50.155  1992  2086 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-08 13:34:50.155  1992  2086 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 13:34:50.155  1992  2086 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 13:34:50.155  1992  2086 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 13:34:50.155  1992  2086 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-08 13:34:50.158   874  2035 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-08 13:34:50.163   874  4297 E DropBoxManagerService: Can't write: system_app_crash
09-08 13:34:50.163   874  4297 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-08 13:34:50.163   874  4297 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 13:34:50.163   874  4297 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 13:34:50.163   874  4297 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 13:34:50.163   874  4297 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 13:34:50.163   874  4297 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 13:34:50.163   874  4297 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 13:34:50.163   874  4297 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 13:34:50.163   874  4297 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 13:34:50.163   874  4297 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 13:34:50.163   874  4297 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 13:34:50.163   874  4297 E DropBoxManagerService: 	... 5 more
,09-08 13:34:50.165  1893  4278 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-08 13:34:50.165  1893  4278 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-08 13:34:50.166  1893  4278 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-08 13:34:50.166  1893  4278 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-08 13:34:50.166  1893  4278 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-08 13:34:50.166  1893  4278 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-08 13:34:50.166  1893  4278 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-08 13:34:50.167  1893  4278 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-08 13:34:50.173  1992  2086 I Process : Sending signal. PID: 1992 SIG: 9,
,09-08 13:34:50.217  4276  4276 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-08 13:34:50.227   874  1391 D GraphicsStats: Buffer count: 1
,09-08 13:34:50.227   874   885 I WindowState: WIN DEATH: Window{f7f2b58 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-08 13:34:50.237   874   884 I ActivityManager: Start proc 4309:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-08 13:34:50.243   874  1988 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1992) has died
09-08 13:34:50.243   874  1988 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-08 13:34:50.245   874  1988 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-08 13:34:50.254  4276  4308 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-08 13:34:50.264   874   887 I ActivityManager: Start proc 4322:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-08 13:34:50.280  4309  4309 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-08 13:34:50.291  4276  4305 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-08 13:34:50.291  4276  4305 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 13:34:50.291  4276  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 13:34:50.291  4276  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 13:34:50.291  4276  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 13:34:50.291  4276  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 13:34:50.291  4276  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 13:34:50.291  4276  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 13:34:50.291  4276  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 13:34:50.291  4276  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 13:34:50.291  4276  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 13:34:50.291  4276  4305 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 13:34:50.291  4276  4305 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 13:34:50.291  4276  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 13:34:50.291  4276  4305 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 13:34:50.291  4276  4305 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-08 13:34:50.291  4276  4305 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-08 13:34:50.291  4276  4305 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-08 13:34:50.291  4276  4305 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-08 13:34:50.291  4276  4305 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 13:34:50.291  4276  4305 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 13:34:50.291  4276  4305 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-08 13:34:50.311  4322  4322 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 13:34:50.311  4322  4322 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 13:34:50.311  4322  4322 D AndroidRuntime: Shutting down VM
,09-08 13:34:50.319  4322  4322 E AndroidRuntime: FATAL EXCEPTION: main
09-08 13:34:50.319  4322  4322 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4322
09-08 13:34:50.319  4322  4322 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-08 13:34:50.319  4322  4322 E AndroidRuntime: 	... 10 more
,09-08 13:34:50.325   874  1982 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-08 13:34:50.326  4322  4322 I Process : Sending signal. PID: 4322 SIG: 9
,09-08 13:34:50.328   874  4336 E DropBoxManagerService: Can't write: system_app_crash
09-08 13:34:50.328   874  4336 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-08 13:34:50.328   874  4336 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 13:34:50.328   874  4336 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 13:34:50.328   874  4336 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 13:34:50.328   874  4336 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 13:34:50.328   874  4336 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 13:34:50.328   874  4336 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 13:34:50.328   874  4336 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 13:34:50.328   874  4336 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 13:34:50.328   874  4336 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 13:34:50.328   874  4336 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 13:34:50.328   874  4336 E DropBoxManagerService: 	... 5 more
,09-08 13:34:50.344  1724  4334 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-08 13:34:50.344  1724  4334 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-08 13:34:50.349  1501  1501 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-08 13:34:50.350  1501  1501 D AndroidRuntime: Shutting down VM
,09-08 13:34:50.351  1501  1501 E AndroidRuntime: FATAL EXCEPTION: main
09-08 13:34:50.351  1501  1501 E AndroidRuntime: Process: com.google.process.gapps, PID: 1501
09-08 13:34:50.351  1501  1501 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 13:34:50.351  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-08 13:34:50.351  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-08 13:34:50.351  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-08 13:34:50.351  1501  1501 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 13:34:50.351  1501  1501 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 13:34:50.351  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 13:34:50.351  1501  1501 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 13:34:50.351  1501  1501 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 13:34:50.351  1501  1501 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 13:34:50.351  1501  1501 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 13:34:50.351  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 13:34:50.351  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-08 13:34:50.351  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 13:34:50.351  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 13:34:50.351  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-08 13:34:50.351  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-08 13:34:50.351  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-08 13:34:50.351  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-08 13:34:50.351  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-08 13:34:50.351  1501  1501 E AndroidRuntime: 	... 8 more
,09-08 13:34:50.353  4276  4305 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-08 13:34:50.353  4276  4305 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 13:34:50.353  4276  4305 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 13:34:50.353  4276  4305 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 13:34:50.353  4276  4305 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 13:34:50.353  4276  4305 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 13:34:50.353  4276  4305 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 13:34:50.353  4276  4305 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 13:34:50.353  4276  4305 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 13:34:50.353  4276  4305 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 13:34:50.353  4276  4305 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 13:34:50.353  4276  4305 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 13:34:50.353  4276  4305 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 13:34:50.353  4276  4305 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 13:34:50.353  4276  4305 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 13:34:50.353  4276  4305 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-08 13:34:50.353  4276  4305 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-08 13:34:50.353  4276  4305 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-08 13:34:50.353  4276  4305 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-08 13:34:50.353  4276  4305 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 13:34:50.353  4276  4305 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-08 13:34:50.353  4276  4305 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-08 13:34:50.354  1501  1501 I Process : Sending signal. PID: 1501 SIG: 9
09-08 13:34:50.354   874  4339 E DropBoxManagerService: Can't write: system_app_crash
09-08 13:34:50.354   874  4339 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-08 13:34:50.354   874  4339 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 13:34:50.354   874  4339 E DropBoxManagerService: 	,at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 13:34:50.354   874  4339 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 13:34:50.354   874  4339 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 13:34:50.354   874  4339 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 13:34:50.354   874  4339 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 13:34:50.354   874  4339 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 13:34:50.354   874  4339 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 13:34:50.354   874  4339 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 13:34:50.354   874  4339 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 13:34:50.354   874  4339 E DropBoxManagerService: 	... 5 more
,09-08 13:34:50.364   874  1988 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4322) has died
,09-08 13:34:50.365   874  1988 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-08 13:34:50.370  1724  4334 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,09-08 13:34:50.371  1724  4334 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-08 13:34:50.379   874   887 I ActivityManager: Start proc 4340:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-08 13:34:50.390   874  1982 I ActivityManager: Killing 3714:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-08 13:34:50.419   874  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 16 -> obsolete
,09-08 13:34:50.537   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
