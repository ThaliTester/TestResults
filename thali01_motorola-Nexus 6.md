#### Test 82883341b26c908_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
,08-30 10:20:41.916   874  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
--------- beginning of main
08-30 10:20:42.574  3934  3934 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 10:20:42.579  3934  3934 D AndroidRuntime: CheckJNI is OFF
08-30 10:20:42.614  3934  3934 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 10:20:42.657  3934  3934 I Radio-JNI: register_android_hardware_Radio DONE
08-30 10:20:42.677  3934  3934 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 10:20:42.681   874   884 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 10:20:42.714  2054  2379 W SearchService: Abort, client detached.
08-30 10:20:42.724  2054  2333 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@2826186
08-30 10:20:42.724  2054  2054 I HotwordDetector: Closing mic
08-30 10:20:42.726  2054  2344 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-30 10:20:42.731  3934  3934 D AndroidRuntime: Shutting down VM
08-30 10:20:42.746   874  2028 I ActivityManager: Start proc 3943:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-30 10:20:42.786   376  2347 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-30 10:20:42.787   376  2347 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-30 10:20:42.792   376  1274 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-30 10:20:42.794  2054  2342 I MicroRecognitionRnrImpl: Detection finished
08-30 10:20:42.793  2054  2336 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-30 10:20:42.826  3943  3943 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-30 10:20:42.845  3943  3943 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 10:20:42.854  3943  3943 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5194-5198)
08-30 10:20:42.854  3943  3943 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 10:20:42.870  3943  3943 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fcc2f6f}
08-30 10:20:42.870  3943  3943 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 10:20:42.871  3943  3943 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 10:20:42.879  3943  3943 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 10:20:42.880  3943  3943 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 10:20:42.896  3943  3943 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-30 10:20:42.905  3943  3943 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 10:20:42.905  3943  3943 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 10:20:42.905  3943  3943 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 10:20:42.905  3943  3943 I Adreno  : Build Date                       : 10/20/15
08-30 10:20:42.905  3943  3943 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 10:20:42.905  3943  3943 I Adreno  : Local Branch                     : M14
08-30 10:20:42.905  3943  3943 I Adreno  : Remote Branch                    : 
08-30 10:20:42.905  3943  3943 I Adreno  : Remote Branch                    : 
08-30 10:20:42.905  3943  3943 I Adreno  : Reconstruct Branch               : 
08-30 10:20:42.954   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4f95df3:true
,08-30 10:20:42.998  3943  3943 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 10:20:43.013  3943  3943 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-30 10:20:43.062  3943  3981 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 10:20:43.071  3943  3968 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 10:20:43.100  3943  3981 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 10:20:43.233   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +497ms
,08-30 10:20:43.235  1887  1887 I Keyboard.Facilitator: onFinishInput()
,08-30 10:20:43.315  3943  3943 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3943
,08-30 10:20:43.439  3943  3943 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 10:20:43.558   874   884 I ActivityManager: Killing 2629:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-30 10:20:43.600   874   884 I ActivityManager: Killing 3208:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-30 10:20:43.745  3943  3984 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1694959312
,08-30 10:20:43.753  3943  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 10:20:43.753  3943  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 10:20:43.753  3943  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 10:20:43.753  3943  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 10:20:43.753  3943  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 10:20:43.753  3943  3984 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f4b90c3 added. We now have 1 listener(s)
,08-30 10:20:43.757  3943  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-30 10:20:43.759  3943  3984 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 10:20:43.760  3943  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 10:20:43.760  3943  3984 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 10:20:43.765  3943  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 10:20:43.765  3943  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 10:20:43.765  3943  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 10:20:43.765  3943  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-30 10:20:43.765  3943  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 10:20:43.765  3943  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 10:20:43.765  3943  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 10:20:43.765  3943  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 10:20:43.765  3943  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 10:20:43.765  3943  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 10:20:43.765  3943  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 10:20:43.765  3943  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 10:20:43.765  3943  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 10:20:43.765  3943  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-30 10:20:43.766  3943  3984 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f7b5be added. We now have 1 listener(s)
08-30 10:20:43.766  3943  3984 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 10:20:43.769  3943  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 10:20:43.769  3943  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-30 10:20:43.773  3943  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-30 10:20:43.769   874  1303 D WifiService: New client listening to asynchronous messages
08-30 10:20:43.773  3943  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 10:20:43.773  3943  3984 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 10:20:43.776  3943  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 10:20:43.777  3943  3984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-30 10:20:43.783  3943  3984 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 10:20:43.783  3943  3984 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:20:43.783  3943  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:20:43.783  3943  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:20:43.783  3943  3984 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:20:43.783  3943  3984 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:20:43.783  3943  3984 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:20:43.783  3943  3984 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:20:43.783  3943  3984 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 10:20:43.783  3943  3984 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 10:20:43.784  3943  3984 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 10:20:43.784  3943  3984 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 10:20:43.919  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:20:43.925  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:20:43.928  3943  3943 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 10:20:44.632  3943  3993 W jxcore-log: Initializing JXcore engine
,08-30 10:20:44.632  3943  3993 W jxcore-log: JXcore engine is ready
,08-30 10:20:44.666  3993  3993 W Thread-361: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-30 10:20:44.670  3993  3993 W Thread-361: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12158]" dev="sockfs" ino=12158 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-30 10:20:44.670  3993  3993 W Thread-361: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 10:20:44.670  3993  3993 W Thread-361: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26108]" dev="sockfs" ino=26108 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 10:20:44.685  3943  3993 W jxcore-log: Starting JXcore engine
,08-30 10:20:44.787  3943  3993 W jxcore-log: Platform android
08-30 10:20:44.787  3943  3993 W jxcore-log: 
,08-30 10:20:44.788  3943  3993 W jxcore-log: Process ARCH arm
08-30 10:20:44.788  3943  3993 W jxcore-log: 
,08-30 10:20:45.037  3943  3993 I jxcore-log: JXcore Cordova bridge is ready!
08-30 10:20:45.037  3943  3993 I jxcore-log: 
,08-30 10:20:45.037  3943  3993 W jxcore-log: JXcore engine is started
,08-30 10:20:45.044  3943  3984 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 10:20:45.048  3943  3943 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 10:20:51.375   874  1302 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-30 10:20:52.928  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 10:20:52.934  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 10:20:52.935  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 10:20:52.955  1497  3152 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-30 10:20:52.956  1497  3152 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-30 10:20:52.956  1497  3152 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 10:20:52.956  1497  3152 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 10:20:52.967  3690  3690 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-30 10:20:52.967  3690  3690 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-30 10:20:52.967  3690  3690 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-30 10:20:54.691  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 10:20:54.691  3943  3993 I jxcore-log: 
,08-30 10:20:54.693  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 10:20:54.693  3943  3993 I jxcore-log: 
,08-30 10:20:54.704  3943  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:20:54.704  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:20:54.704  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:20:54.704  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:20:54.704  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:20:54.704  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:20:54.704  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:20:54.704  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:20:54.712  3943  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 10:20:54.719  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 10:20:54.719  3943  3993 I jxcore-log: 
,08-30 10:20:54.726  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 10:20:54.726  3943  3993 I jxcore-log: 
,08-30 10:20:55.239  3943  3993 I jxcore-log: Unit Test app is loaded
08-30 10:20:55.239  3943  3993 I jxcore-log: 
,08-30 10:20:55.246  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:20:55.246  3943  3993 I jxcore-log: 
,08-30 10:20:55.254  3943  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 10:20:55.254  3943  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f162e0 added. We now have 2 listener(s)
,08-30 10:20:55.256  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 10:20:55.256  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 10:20:55.256  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 10:20:55.256  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 10:20:55.256  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4278999 added. We now have 2 listener(s)
08-30 10:20:55.256  3943  3993 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 10:20:55.258  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 10:20:55.259  3943  3943 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 10:20:55.260  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 10:20:55.265  3943  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:20:55.265  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:20:55.265  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:20:55.265  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:20:55.265  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:20:55.265  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:20:55.265  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:20:55.265  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:20:55.268  3943  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 10:20:55.269  3943  3993 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 10:20:55.269  3943  3993 D ExecuteNativeTests: Running unit tests
08-30 10:20:55.276  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:20:55.278  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:20:55.370  3943  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 10:20:55.370  3943  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f072f added. We now have 3 listener(s)
08-30 10:20:55.371  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 10:20:55.371  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 10:20:55.371  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 10:20:55.371  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 10:20:55.371  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0913c added. We now have 3 listener(s)
08-30 10:20:55.371  3943  3993 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 10:20:55.372  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 10:20:55.375  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 10:20:55.386  3943  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:20:55.386  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:20:55.386  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:20:55.386  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:20:55.386  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:20:55.386  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:20:55.386  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:20:55.386  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:20:55.390  3943  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 10:20:55.390  3943  3993 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 10:20:55.393  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 10:20:55.394  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 10:20:55.395  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 10:20:55.394  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:20:55.395  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 10:20:55.399  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:20:55.400  3943  3993 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-30 10:20:55.402  3943  3993 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-30 10:20:55.403  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 10:20:55.404  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 10:20:55.404  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 10:20:55.404  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 10:20:55.405  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:20:55.405  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:20:55.405  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 10:20:55.406  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 10:20:55.406  3943  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f072f removed from the list
08-30 10:20:55.406  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:20:55.406  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0913c removed from the list
08-30 10:20:55.406  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:20:55.406  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:20:55.409  3943  3993 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-30 10:20:55.410  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:20:55.410  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:20:55.410  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:20:55.411  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f072f not in the list
08-30 10:20:55.411  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:20:55.411  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0913c not in the list
,08-30 10:20:55.411  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:20:55.411  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:20:55.411  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:20:55.422  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 10:20:55.422  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-30 10:20:55.422  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 10:20:55.422  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 10:20:55.423  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 10:20:55.423  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 10:20:55.423  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 10:20:55.423  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 10:20:55.423  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 10:20:55.423  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 10:20:55.423  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 10:20:55.424  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 10:20:55.424  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-30 10:20:55.424  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 10:20:55.424  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 10:20:55.424  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 10:20:55.424  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 10:20:55.424  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 10:20:55.424  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 10:20:55.425  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 10:20:55.425  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 10:20:55.425  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 10:20:55.425  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 10:20:55.425  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-30 10:20:55.425  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 10:20:55.425  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 10:20:55.426  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 10:20:55.426  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 10:20:55.426  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 10:20:55.426  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 10:20:55.426  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 10:20:55.426  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:20:55.426  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:20:55.426  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:20:55.427  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f072f not in the list
08-30 10:20:55.427  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:20:55.427  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0913c not in the list
08-30 10:20:55.427  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:20:55.427  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:20:55.427  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:20:55.433  3943  3993 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,08-30 10:20:55.436  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 10:20:55.442  3943  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:20:55.442  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:20:55.442  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:20:55.442  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:20:55.442  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:20:55.442  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:20:55.442  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:20:55.442  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:20:55.445  3943  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 10:20:55.446  3943  3993 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 10:20:55.448  3943  3993 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,08-30 10:20:55.448  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:20:55.449  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,08-30 10:20:55.450  3943  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-30 10:20:55.452  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:20:55.454  3943  3993 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-30 10:20:55.455  3943  3993 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 10:20:55.456  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 10:20:55.457  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-30 10:20:55.458  3943  3993 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 10:20:55.459  3943  3993 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 10:20:55.459  3943  3943 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-30 10:20:55.460  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-30 10:20:55.461  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-30 10:20:55.461  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 10:20:55.461  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 10:20:55.469  3943  4004 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 10:20:55.471  3943  3993 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 10:20:55.471  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 10:20:55.472  3943  4004 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-30 10:20:55.486  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 10:20:55.490  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 10:20:55.492  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 10:20:55.495  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-30 10:20:55.496  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 10:20:55.497  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,08-30 10:20:55.498  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 10:20:55.499  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-30 10:20:55.499  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-30 10:20:55.500  3943  3993 D BluetoothAdapter: STATE_ON
,08-30 10:20:55.510  2855  3042 D BtGatt.GattService: registerClient() - UUID=6bebb84d-6af0-4aed-9c28-2b4808b1aec7
,08-30 10:20:55.512  2855  2880 D BtGatt.GattService: onClientRegistered() - UUID=6bebb84d-6af0-4aed-9c28-2b4808b1aec7, clientIf=5
,08-30 10:20:55.513  3943  3953 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-30 10:20:55.516  2855  2884 D BtGatt.AdvertiseManager: message : 0
,08-30 10:20:55.520  2855  2884 D BtGatt.AdvertiseManager: starting multi advertising
,08-30 10:20:55.555  2855  2880 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-30 10:20:55.570  2855  2880 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-30 10:20:55.574  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-30 10:20:55.574  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 10:20:55.577  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 10:20:55.581  3943  3993 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 10:20:55.582  3943  3943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 10:20:55.582  3943  3943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-30 10:20:55.583  3943  3943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-30 10:20:55.583  3943  3943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-30 10:20:55.584  3943  3943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,08-30 10:20:55.584  3943  3943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-30 10:20:55.590  3943  3943 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 10:20:55.591  3943  3943 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 10:20:56.093  3943  3943 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
08-30 10:20:56.094  3943  3943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-30 10:20:56.094  3943  3943 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 10:20:57.154  3235  4006 V KeepSync: Connecting to GoogleApiClient
,08-30 10:20:57.155   874  2028 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-30 10:20:57.235  1497  3153 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-30 10:20:57.235  1497  3153 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-30 10:20:57.236  1497  3153 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 10:20:57.236  1497  3153 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 10:20:57.264  1690  4007 V BaseAuthAsyncOperation: access token request failed
,08-30 10:20:57.266  3235  4006 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-30 10:20:57.351  1497  3152 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-30 10:20:57.352  1497  3152 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-30 10:20:57.352  1497  3152 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 10:20:57.354  1497  3152 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 10:20:57.392  3235  4006 E KeepSync: IOException
08-30 10:20:57.392  3235  4006 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-30 10:20:57.392  3235  4006 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-30 10:20:57.392  3235  4006 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-30 10:20:57.392  3235  4006 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-30 10:20:57.392  3235  4006 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-30 10:20:57.392  3235  4006 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-30 10:20:57.392  3235  4006 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-30 10:20:57.392  3235  4006 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-30 10:20:57.392  3235  4006 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-30 10:20:57.392  3235  4006 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-30 10:20:57.392  3235  4006 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-30 10:20:57.392  3235  4006 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-30 10:20:57.392  3235  4006 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-30 10:20:57.392  3235  4006 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-30 10:20:57.392  3235  4006 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 10:20:57.392  3235  4006 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-30 10:20:57.392  3235  4006 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-30 10:20:57.392  3235  4006 E KeepSync: 	... 10 more
,08-30 10:20:57.392  3235  4006 W KeepSync: Sync result 2
,08-30 10:20:57.411   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 128531, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 10:21:00.597  3943  3993 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,08-30 10:21:00.598  3943  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should affect listening to advertisements only
,08-30 10:21:00.598  3943  3993 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 10:21:05.608  3943  3993 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,08-30 10:21:05.608  3943  3993 V io.jxcore.node.ConnectivityMonitor: start: Already started
,08-30 10:21:05.609  3943  3993 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
08-30 10:21:05.609  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
,08-30 10:21:05.610  3943  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 10:21:05.610  3943  3993 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 10:21:05.611  3943  3993 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 10:21:10.622  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:10.623  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-30 10:21:10.623  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 10:21:10.623  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-30 10:21:10.627  3943  4004 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-30 10:21:10.627  3943  4004 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-30 10:21:10.626  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 10:21:10.627  3943  4004 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 10:21:10.628  3943  3993 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 10:21:10.628  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f072f not in the list
,08-30 10:21:10.628  3943  3943 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-30 10:21:10.629  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 10:21:10.630  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 10:21:10.630  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 10:21:10.631  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 10:21:10.631  3943  3943 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-30 10:21:10.633  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 10:21:10.635  3943  3993 D BluetoothAdapter: STATE_ON
,08-30 10:21:10.636  3943  3993 D BluetoothLeScanner: could not find callback wrapper
,08-30 10:21:10.637  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 10:21:10.637  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-30 10:21:10.640  2855  2884 D BtGatt.AdvertiseManager: message : 1
,08-30 10:21:10.642  2855  2884 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-30 10:21:10.661  2855  2880 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-30 10:21:10.661  2855  2880 D BtGatt.GattService: Client app is not null!
,08-30 10:21:10.664  2855  2868 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 10:21:10.665  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 10:21:10.666  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-30 10:21:10.666  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-30 10:21:10.666  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,08-30 10:21:10.666  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-30 10:21:10.670  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 10:21:10.670  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 10:21:10.671  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 10:21:10.672  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 10:21:10.676  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0913c not in the list
,08-30 10:21:10.676  3943  3943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 10:21:10.677  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 10:21:10.677  3943  3943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 10:21:10.677  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:21:10.677  3943  3943 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 10:21:10.680  3943  3993 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 10:21:10.685  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 10:21:10.697  3943  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:21:10.697  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:10.697  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:10.697  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:10.697  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:21:10.697  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:10.697  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:21:10.697  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:21:10.704  3943  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 10:21:10.705  3943  3993 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 10:21:10.706  3943  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 10:21:10.706  3943  3993 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 10:21:10.706  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 10:21:10.706  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 10:21:10.707  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 10:21:10.713  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:10.717  3943  3993 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 10:21:10.717  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 10:21:10.722  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:10.731  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 10:21:10.734  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 10:21:10.734  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 10:21:10.743  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-30 10:21:10.753  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-30 10:21:10.753  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 10:21:10.754  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 10:21:10.756  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 10:21:10.758  3943  3993 D BluetoothAdapter: STATE_ON
08-30 10:21:10.765  2855  2867 D BtGatt.GattService: registerClient() - UUID=a9499ebe-2b7e-4168-a052-17df5baa9c3b
,08-30 10:21:10.766  2855  2880 D BtGatt.GattService: onClientRegistered() - UUID=a9499ebe-2b7e-4168-a052-17df5baa9c3b, clientIf=5
,08-30 10:21:10.767  3943  3955 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 10:21:10.771  2855  3069 D BtGatt.GattService: start scan with filters
,08-30 10:21:10.780  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 10:21:10.780  2855  2885 D BtGatt.ScanManager: handling starting scan
08-30 10:21:10.780  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 10:21:10.780  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 10:21:10.780  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 10:21:10.783  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 10:21:10.784  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 10:21:10.784  3943  3943 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 10:21:10.784  2855  2885 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43bf881
08-30 10:21:10.785  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 10:21:10.788  3943  3993 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 10:21:10.799  2855  2880 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 10:21:10.799  2855  2880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 10:21:10.801  2855  2885 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 10:21:10.812  2855  2880 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 10:21:10.812  2855  2880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 10:21:10.814  2855  2885 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 10:21:10.814  2855  2885 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 10:21:10.848  2855  2880 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 10:21:10.848  2855  2880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 10:21:10.871  2855  2880 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-30 10:21:10.871  2855  2880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 10:21:11.286  3943  3943 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-30 10:21:11.287  3943  3943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 10:21:11.287  3943  3943 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 10:21:12.374  2855  2855 D BtGatt.ScanManager: awakened up at time 144718
,08-30 10:21:12.376  2855  2885 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 10:21:12.453  2855  2880 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=11
,08-30 10:21:12.453  2855  2880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 10:21:12.454  2855  2880 D BtGatt.GattService: current time is 144798297610
,08-30 10:21:12.454  2855  2880 D BtGatt.GattService: Batch record : [58, 52, -118, 26, 113, 117, 1, -128, -87, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 96, -125, 52, 37, -41, -58, 0, 87, 45, 110, 28, -13, -4, 1, -128, -68, 25, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85, 0, 106, 81, 69, -88, 5, 76, 1, -128, -82, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 68, 120, 62, -108, 74, 62, 0, 35, 97, 126, -92, 22, -56, 1, -128, -84, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -85, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -84, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -83, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -81, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -83, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 53, 33, -121, 80, 73, -44, 1, 0, -105, 5, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, 32, -99, -18, 2, 2, -29, 21, 63, -68, 1, -121, 28, 6, 8, 116, 105, 115, 54, 69, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 81, 34, 97, 112, -14, -5, 1, -128, -86, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-30 10:21:12.457  2855  2880 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 96, -125, 52, 37, -41, -58]
08-30 10:21:12.458  2855  2880 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 55, -106, -85]
,08-30 10:21:12.459  2855  2880 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 68, 120, 62, -108, 74, 62]
,08-30 10:21:12.459  2855  2880 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-30 10:21:12.459  2855  2880 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-30 10:21:12.459  2855  2880 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-30 10:21:12.460  2855  2880 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-30 10:21:12.460  2855  2880 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-30 10:21:12.461  2855  2880 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-30 10:21:12.462  2855  2880 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, 32, -99, -18, 2, 2, -29, 21, 63, -68, 1, -121, 6, 8, 116, 105, 115, 54, 69, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
08-30 10:21:12.462  2855  2880 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-30 10:21:12.471  3943  3943 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 44:78:3E:94:4A:3E 1], added - the peer count is 1
08-30 10:21:12.472  3943  3943 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:37:96:AB 1], added - the peer count is 2
08-30 10:21:12.472  3943  3943 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 60:83:34:25:D7:C6 1], added - the peer count is 3
08-30 10:21:12.472  3943  3943 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 44:78:3E:94:4A:3E 1], Bluetooth address: 44:78:3E:94:4A:3E, device name: '', device address: ''
08-30 10:21:12.473  3943  3943 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:37:96:AB 1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: '', device address: ''
08-30 10:21:12.473  3943  3943 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 60:83:34:25:D7:C6 1], Bluetooth address: 60:83:34:25:D7:C6, device name: '', device address: ''
,08-30 10:21:13.956  2855  2855 D BtGatt.ScanManager: awakened up at time 146300
,08-30 10:21:13.960  2855  2885 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 10:21:13.970  2855  2880 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 10:21:13.970  2855  2880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 10:21:15.473  2855  2855 D BtGatt.ScanManager: awakened up at time 147817
,08-30 10:21:15.475  2855  2885 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 10:21:15.487  2855  2880 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-30 10:21:15.488  2855  2880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 10:21:15.789  3943  3993 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 10:21:15.789  3943  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 10:21:15.790  3943  3993 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 10:21:15.790  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:15.790  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 10:21:15.791  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 10:21:15.791  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 10:21:15.791  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 10:21:15.792  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 10:21:15.793  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 10:21:15.793  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 10:21:15.796  3943  3993 D BluetoothAdapter: STATE_ON
,08-30 10:21:15.797  2855  2868 D BtGatt.GattService: stopScan() - queue size =1
,08-30 10:21:15.800  2855  3042 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 10:21:15.801  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 10:21:15.803  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 10:21:15.803  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 10:21:15.803  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 10:21:15.804  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 10:21:15.807  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 10:21:15.808  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 10:21:15.808  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 10:21:15.809  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 10:21:15.811  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 10:21:15.811  3943  3993 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,08-30 10:21:15.813  3943  3943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 10:21:15.814  3943  3943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 10:21:15.814  3943  3943 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 10:21:15.819  2855  2880 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 10:21:15.820  2855  2880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 10:21:15.820  2855  2885 D BtGatt.ScanManager: stopping BLe Batch
,08-30 10:21:15.837  2855  2880 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 10:21:15.837  2855  2880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 10:21:15.838  2855  2885 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 10:21:15.863  2855  2880 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-30 10:21:15.863  2855  2880 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 10:21:15.864  2855  2880 D BtGatt.GattService: current time is 148208573939
,08-30 10:21:15.865  2855  2880 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -90, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 106, 81, 69, -88, 5, 76, 1, -128, -83, 4, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 68, 120, 62, -108, 74, 62, 0, 113, 93, -26, 95, 61, 68, 1, -128, -73, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, -112, -25, -60, -2, -84, -17, 0, 58, 52, -118, 26, 113, 117, 1, -128, -86, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 96, -125, 52, 37, -41, -58, 0]
08-30 10:21:15.865  2855  2880 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-30 10:21:15.866  2855  2880 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 68, 120, 62, -108, 74, 62]
,08-30 10:21:15.867  2855  2880 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 3, -112, -25, -60, -2, -84, -17]
08-30 10:21:15.867  2855  2880 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 96, -125, 52, 37, -41, -58]
,08-30 10:21:16.315  3943  3943 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 10:21:16.316  3943  3943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 10:21:16.316  3943  3943 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 10:21:20.693   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-30 10:21:20.705  1887  1887 I Keyboard.Facilitator: onFinishInput()
,08-30 10:21:20.716   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 10:21:20.716   874   894 I Adreno  : Build Date                       : 10/20/15
08-30 10:21:20.716   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 10:21:20.716   874   894 I Adreno  : Local Branch                     : M14
08-30 10:21:20.716   874   894 I Adreno  : Remote Branch                    : 
08-30 10:21:20.716   874   894 I Adreno  : Remote Branch                    : 
08-30 10:21:20.716   874   894 I Adreno  : Reconstruct Branch               : 
,08-30 10:21:20.789   280  1729 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (215 us)
,08-30 10:21:20.814  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 10:21:20.814  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:20.815  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 10:21:20.815  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f072f not in the list
,08-30 10:21:20.815  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 10:21:20.816  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0913c not in the list
,08-30 10:21:20.816  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 10:21:20.816  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:21:20.819  3943  3993 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-30 10:21:20.821  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 10:21:20.821  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:21:20.821  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:21:20.821  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f072f not in the list
,08-30 10:21:20.822  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:20.822  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0913c not in the list
08-30 10:21:20.822  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:20.822  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:21:20.823  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:20.825  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 10:21:20.825  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:20.826  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:20.826  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:21:20.826  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f072f not in the list
08-30 10:21:20.826  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:20.826  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0913c not in the list
08-30 10:21:20.827  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:20.827  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:21:20.827  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:20.829  3943  3993 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 10:21:20.829  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:20.829  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:20.830  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:21:20.830  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f072f not in the list
08-30 10:21:20.830  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 10:21:20.830  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0913c not in the list
08-30 10:21:20.831  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:20.831  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:20.831  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:21:20.833  3943  3993 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 10:21:20.833  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:20.833  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:21:20.833  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:20.834  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f072f not in the list
,08-30 10:21:20.834  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:20.834  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0913c not in the list
08-30 10:21:20.834  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 10:21:20.835  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:20.835  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:20.836  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 10:21:20.841  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 10:21:20.841  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 10:21:20.841  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 10:21:20.841  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 10:21:20.842  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 10:21:20.842  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 10:21:20.842  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-30 10:21:20.843  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 10:21:20.843  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:20.843  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:21:20.843  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:21:20.844  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f072f not in the list
,08-30 10:21:20.844  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 10:21:20.844  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0913c not in the list
,08-30 10:21:20.844  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:20.844  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:20.845  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:20.847  3943  3993 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 10:21:20.847  3943  3993 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-30 10:21:20.847  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 10:21:20.854  3943  3993 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 10:21:20.854  3943  3993 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 10:21:20.854  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 10:21:20.854  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 10:21:20.854  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 10:21:20.854  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 10:21:20.854  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 10:21:20.855  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 10:21:20.855  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-30 10:21:20.855  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 10:21:20.855  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 10:21:20.856  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 10:21:20.856  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 10:21:20.856  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 10:21:20.856  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 10:21:20.856  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 10:21:20.856  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 10:21:20.856  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-30 10:21:20.856  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 10:21:20.856  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 10:21:20.856  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 10:21:20.856  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 10:21:20.856  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 10:21:20.856  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-30 10:21:20.857  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 10:21:20.857  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 10:21:20.857  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-30 10:21:20.857  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 10:21:20.857  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 10:21:20.857  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 10:21:20.857  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-30 10:21:20.857  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 10:21:20.857  3943  3993 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 10:21:20.857  3943  3993 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-30 10:21:20.858  3943  3993 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 10:21:20.858  3943  3993 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 10:21:20.858  3943  3993 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 10:21:20.858  3943  3993 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection,
,08-30 10:21:20.858  3943  3993 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-30 10:21:20.858  3943  3993 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 10:21:20.858  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 10:21:20.860  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-30 10:21:20.861  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-30 10:21:20.861  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 10:21:20.861  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 10:21:20.862  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-30 10:21:20.862  3943  3993 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 10:21:20.862  3943  3993 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 10:21:20.862  3943  3993 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-30 10:21:20.863  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 10:21:20.863  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:20.863  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:21:20.863  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 10:21:20.864  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f072f not in the list
08-30 10:21:20.864  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:20.864  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0913c not in the list
,08-30 10:21:20.864  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:20.867  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:21:20.867  3943  4013 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 426
08-30 10:21:20.867  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:20.864  3943  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 426)
08-30 10:21:20.869  3943  4012 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 426)
08-30 10:21:20.869  3943  3993 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-30 10:21:20.869  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:20.870  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:20.870  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:20.870  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f072f not in the list
,08-30 10:21:20.870  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:20.870  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0913c not in the list
,08-30 10:21:20.870  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:20.870  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:21:20.870  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:20.871  3943  3993 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 10:21:20.871  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:20.871  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:21:20.871  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:21:20.871  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f072f not in the list
08-30 10:21:20.871  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:20.871  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0913c not in the list
,08-30 10:21:20.871  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:20.871  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:20.871  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:20.872  3943  3993 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,08-30 10:21:20.872  3943  3993 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,08-30 10:21:20.872  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 10:21:20.872  3943  3993 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 10:21:20.872  3943  3993 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 10:21:20.872  3943  3993 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 10:21:20.872  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-30 10:21:20.872  3943  3993 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 10:21:20.873  3943  3993 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 10:21:20.873  3943  3993 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 10:21:20.873  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 10:21:20.873  3943  3993 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 10:21:20.873  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:20.873  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:20.873  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:20.873  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f072f not in the list
08-30 10:21:20.873  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:20.873  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0913c not in the list
08-30 10:21:20.873  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:20.873  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:20.873  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:20.880  3943  3993 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,08-30 10:21:20.885  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 10:21:20.898  3943  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:21:20.898  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:20.898  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:20.898  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:20.898  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:21:20.898  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:20.898  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:21:20.898  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:21:20.902  3943  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 10:21:20.902  3943  3993 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 10:21:20.902  3943  3993 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
08-30 10:21:20.902  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,08-30 10:21:20.904  3943  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-30 10:21:20.904  3943  3993 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-30 10:21:20.904  3943  3993 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 10:21:20.904  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 10:21:20.905  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 10:21:20.906  3943  3993 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-30 10:21:20.906  3943  3993 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 10:21:20.906  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-30 10:21:20.906  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-30 10:21:20.906  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 10:21:20.906  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 10:21:20.908  3943  4014 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 10:21:20.909  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:20.911  3943  4014 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-30 10:21:20.911  3943  3993 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 10:21:20.911  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:20.911  3943  3943 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 10:21:20.911  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 10:21:20.921  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 10:21:20.921  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 10:21:20.922  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 10:21:20.924  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-30 10:21:20.924  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 10:21:20.924  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
08-30 10:21:20.924  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 10:21:20.924  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 10:21:20.925  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-30 10:21:20.925  3943  3993 D BluetoothAdapter: STATE_ON
,08-30 10:21:20.929  2855  2867 D BtGatt.GattService: registerClient() - UUID=772f1a1e-8cb4-4219-a30e-75e000194200
,08-30 10:21:20.929  2855  2880 D BtGatt.GattService: onClientRegistered() - UUID=772f1a1e-8cb4-4219-a30e-75e000194200, clientIf=5
,08-30 10:21:20.930  3943  3955 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
08-30 10:21:20.931  2855  2884 D BtGatt.AdvertiseManager: message : 0
,08-30 10:21:20.934  2855  2884 D BtGatt.AdvertiseManager: starting multi advertising
,08-30 10:21:20.946  2855  2880 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-30 10:21:20.955  2855  2880 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-30 10:21:20.955  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-30 10:21:20.955  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 10:21:20.956  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 10:21:20.958  3943  3993 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 10:21:20.958  3943  3943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 10:21:20.958  3943  3943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-30 10:21:20.958  3943  3943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-30 10:21:20.958  3943  3943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-30 10:21:20.958  3943  3943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-30 10:21:20.959  3943  3943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-30 10:21:20.962  3943  3943 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-30 10:21:20.962  3943  3943 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 10:21:21.398  3943  3943 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 10:21:21.399  3943  3943 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 10:21:21.463  3943  3943 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-30 10:21:21.463  3943  3943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 10:21:21.464  3943  3943 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-30 10:21:21.465   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-30 10:21:21.465  3943  3943 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@fae9bbd Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@f8c16c, 16908290=android.view.AbsSavedState$1@f8c16c}, android:focusedViewId=100}]}]
,08-30 10:21:21.465  3943  3943 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-30 10:21:21.466  3943  3943 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-30 10:21:21.466  3943  3943 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-30 10:21:21.477   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-30 10:21:21.480   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-30 10:21:21.486   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,08-30 10:21:21.486   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-30 10:21:21.500   874   883 I art     : Background partial concurrent mark sweep GC freed 35169(2MB) AllocSpace objects, 12(300KB) LOS objects, 33% free, 29MB/43MB, paused 3.722ms total 135.399ms
,08-30 10:21:21.756   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-30 10:21:21.761   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0,
,08-30 10:21:21.768   874  1327 D SurfaceControl: Excessive delay in setPowerMode(): 287ms
08-30 10:21:21.771   874   894 I DreamManagerService: Entering dreamland.
,08-30 10:21:21.772   874   894 I PowerManagerService: Dozing...
,08-30 10:21:21.773   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-30 10:21:21.823   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-30 10:21:21.823   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-30 10:21:21.837   874  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 10:21:21.846  1962  4016 D NfcService: Discovery configuration equal, not updating.
,08-30 10:21:21.854   874  1302 E native  : do suspend false
,08-30 10:21:21.854   874  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-30 10:21:21.876   874  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 10:21:21.889   874  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 10:21:21.893   874  1302 E native  : do suspend true
,08-30 10:21:21.959   376  1275 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-30 10:21:21.959   376  1275 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-30 10:21:22.204  1497  2245 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 10:21:22.345   874  1302 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-30 10:21:25.958  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 10:21:25.958  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-30 10:21:25.959  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-30 10:21:25.959  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-30 10:21:25.960  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 10:21:25.960  3943  4014 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 10:21:25.960  3943  3993 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 10:21:25.960  3943  4014 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 10:21:25.961  3943  4014 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 10:21:25.961  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f072f not in the list
08-30 10:21:25.961  3943  3943 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 10:21:25.961  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:25.961  3943  3943 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-30 10:21:25.961  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 10:21:25.962  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 10:21:25.962  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 10:21:25.963  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 10:21:25.966  3943  3993 D BluetoothAdapter: STATE_ON
08-30 10:21:25.966  3943  3993 D BluetoothLeScanner: could not find callback wrapper
08-30 10:21:25.966  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 10:21:25.967  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-30 10:21:25.972  2855  2884 D BtGatt.AdvertiseManager: message : 1
08-30 10:21:25.976  2855  2884 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-30 10:21:25.984  2855  2880 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-30 10:21:25.984  2855  2880 D BtGatt.GattService: Client app is not null!
,08-30 10:21:25.986  2855  3069 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 10:21:25.986  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 10:21:25.987  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-30 10:21:25.987  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-30 10:21:25.987  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-30 10:21:25.987  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-30 10:21:25.988  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 10:21:25.988  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 10:21:25.989  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 10:21:25.990  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 10:21:25.993  3943  3943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 10:21:25.993  3943  3943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 10:21:25.993  3943  3943 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 10:21:25.994  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0913c not in the list
08-30 10:21:25.994  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:25.994  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:21:26.498  3943  3943 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 10:21:26.600  1849  2768 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-30 10:21:27.697  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 10:21:27.701  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 10:21:27.751  1497  3152 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 10:21:27.751  1497  3152 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 10:21:27.752  1497  3152 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 10:21:27.752  1497  3152 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 10:21:27.792  3188  4022 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-30 10:21:27.792  3188  4022 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 10:21:27.792  3188  4022 E HttpOperation: 	at jdm.a(PG:82)
08-30 10:21:27.792  3188  4022 E HttpOperation: 	at jcs.o(PG:406)
08-30 10:21:27.792  3188  4022 E HttpOperation: 	at jcn.a(PG:1379)
08-30 10:21:27.792  3188  4022 E HttpOperation: 	at jcs.i(PG:143)
08-30 10:21:27.792  3188  4022 E HttpOperation: 	at blb.a(PG:3937)
08-30 10:21:27.792  3188  4022 E HttpOperation: 	at czp.a(PG:18188)
08-30 10:21:27.792  3188  4022 E HttpOperation: 	at czp.a(PG:9081)
08-30 10:21:27.792  3188  4022 E HttpOperation: 	at czq.run(PG:1686)
08-30 10:21:27.792  3188  4022 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 10:21:27.792  3188  4022 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 10:21:27.792  3188  4022 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 10:21:27.792  3188  4022 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 10:21:27.792  3188  4022 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 10:21:27.792  3188  4022 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 10:21:27.792  3188  4022 E HttpOperation: 	at jdj.a(PG:4091)
08-30 10:21:27.792  3188  4022 E HttpOperation: 	at jdj.a(PG:1125)
08-30 10:21:27.792  3188  4022 E HttpOperation: 	at jdm.a(PG:77)
08-30 10:21:27.792  3188  4022 E HttpOperation: 	... 12 more
08-30 10:21:27.792  3188  4022 E HttpOperation: Caused by: faj: BadAuthentication
08-30 10:21:27.792  3188  4022 E HttpOperation: 	at fal.a(PG:38)
08-30 10:21:27.792  3188  4022 E HttpOperation: 	at jdj.a(PG:4089)
08-30 10:21:27.792  3188  4022 E HttpOperation: 	... 14 more
,08-30 10:21:27.866  1497  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-30 10:21:27.866  1497  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-30 10:21:27.867  1497  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 10:21:27.867  1497  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 10:21:27.892  3188  4022 E HttpOperation: [getmobileexperiments] Unexpected exception
08-30 10:21:27.892  3188  4022 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-30 10:21:27.892  3188  4022 E HttpOperation: 	at jdm.a(PG:82)
,08-30 10:21:27.892  3188  4022 E HttpOperation: 	at jcs.o(PG:406)
08-30 10:21:27.892  3188  4022 E HttpOperation: 	at jcn.a(PG:1379)
08-30 10:21:27.892  3188  4022 E HttpOperation: 	at jcs.i(PG:143)
08-30 10:21:27.892  3188  4022 E HttpOperation: 	at hec.a(PG:42)
08-30 10:21:27.892  3188  4022 E HttpOperation: 	at hee.a(PG:102)
08-30 10:21:27.892  3188  4022 E HttpOperation: 	at czr.a(PG:65)
08-30 10:21:27.892  3188  4022 E HttpOperation: 	at kka.a(PG:108)
08-30 10:21:27.892  3188  4022 E HttpOperation: 	at czp.a(PG:19176)
08-30 10:21:27.892  3188  4022 E HttpOperation: 	at czp.a(PG:9081)
08-30 10:21:27.892  3188  4022 E HttpOperation: 	at czq.run(PG:1686)
08-30 10:21:27.892  3188  4022 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 10:21:27.892  3188  4022 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 10:21:27.892  3188  4022 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 10:21:27.892  3188  4022 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 10:21:27.892  3188  4022 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-30 10:21:27.892  3188  4022 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 10:21:27.892  3188  4022 E HttpOperation: 	at jdj.a(PG:4091)
08-30 10:21:27.892  3188  4022 E HttpOperation: 	at jdj.a(PG:1125)
08-30 10:21:27.892  3188  4022 E HttpOperation: 	at jdm.a(PG:77)
08-30 10:21:27.892  3188  4022 E HttpOperation: 	... 15 more
08-30 10:21:27.892  3188  4022 E HttpOperation: Caused by: faj: BadAuthentication,
08-30 10:21:27.892  3188  4022 E HttpOperation: 	at fal.a(PG:38)
08-30 10:21:27.892  3188  4022 E HttpOperation: 	at jdj.a(PG:4089)
08-30 10:21:27.892  3188  4022 E HttpOperation: 	... 17 more
,08-30 10:21:27.893  3188  4022 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-30 10:21:27.893  3188  4022 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-30 10:21:27.893  3188  4022 E ExperimentLoader: 	at jdm.a(PG:82)
08-30 10:21:27.893  3188  4022 E ExperimentLoader: 	at jcs.o(PG:406)
08-30 10:21:27.893  3188  4022 E ExperimentLoader: 	at jcn.a(PG:1379)
08-30 10:21:27.893  3188  4022 E ExperimentLoader: 	at jcs.i(PG:143)
08-30 10:21:27.893  3188  4022 E ExperimentLoader: 	at hec.a(PG:42)
08-30 10:21:27.893  3188  4022 E ExperimentLoader: 	at hee.a(PG:102)
08-30 10:21:27.893  3188  4022 E ExperimentLoader: 	at czr.a(PG:65)
08-30 10:21:27.893  3188  4022 E ExperimentLoader: 	at kka.a(PG:108)
08-30 10:21:27.893  3188  4022 E ExperimentLoader: 	at czp.a(PG:19176)
08-30 10:21:27.893  3188  4022 E ExperimentLoader: 	at czp.a(PG:9081)
08-30 10:21:27.893  3188  4022 E ExperimentLoader: 	at czq.run(PG:1686)
08-30 10:21:27.893  3188  4022 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-30 10:21:27.893  3188  4022 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 10:21:27.893  3188  4022 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-30 10:21:27.893  3188  4022 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-30 10:21:27.893  3188  4022 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-30 10:21:27.893  3188  4022 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-30 10:21:27.893  3188  4022 E ExperimentLoader: 	at jdj.a(PG:4091)
08-30 10:21:27.893  3188  4022 E ExperimentLoader: 	at jdj.a(PG:1125)
,08-30 10:21:27.893  3188  4022 E ExperimentLoader: 	at jdm.a(PG:77)
08-30 10:21:27.893  3188  4022 E ExperimentLoader: 	... 15 more
08-30 10:21:27.893  3188  4022 E ExperimentLoader: Caused by: faj: BadAuthentication
08-30 10:21:27.893  3188  4022 E ExperimentLoader: 	at fal.a(PG:38)
08-30 10:21:27.893  3188  4022 E ExperimentLoader: 	at jdj.a(PG:4089)
08-30 10:21:27.893  3188  4022 E ExperimentLoader: 	... 17 more
,08-30 10:21:28.046   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 130402, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-30 10:21:30.997  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 10:21:30.997  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0913c not in the list
08-30 10:21:30.998  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:30.998  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:21:30.998  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:30.999  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f072f not in the list
,08-30 10:21:30.999  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:31.000  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:31.000  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:31.001  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f072f not in the list
,08-30 10:21:31.001  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:31.001  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0913c not in the list
08-30 10:21:31.001  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:31.002  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:21:31.002  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:31.006  3943  3993 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 10:21:31.007  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 10:21:31.010  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-30 10:21:31.011  3943  3993 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 10:21:31.012  3943  3993 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-30 10:21:31.012  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-30 10:21:31.012  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 10:21:31.012  3943  3943 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 10:21:31.014  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:31.014  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 10:21:31.014  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 10:21:31.014  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-30 10:21:31.015  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:31.015  3943  3993 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 10:21:31.015  3943  4024 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 10:21:31.016  3943  4024 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 10:21:31.017  3943  3943 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 10:21:31.018  3943  3943 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-30 10:21:31.018  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f072f not in the list
08-30 10:21:31.019  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:31.019  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 10:21:31.019  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 10:21:31.019  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 10:21:31.020  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:31.021  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:21:31.023  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 10:21:31.024  3943  3943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 10:21:31.024  3943  3943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 10:21:31.024  3943  3943 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 10:21:31.025  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0913c not in the list
,08-30 10:21:31.025  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:31.026  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:31.026  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:21:31.026  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f072f not in the list
08-30 10:21:31.027  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:31.027  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0913c not in the list
,08-30 10:21:31.027  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:31.027  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:31.028  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:21:31.030  3943  3993 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-30 10:21:31.032  3943  3993 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-30 10:21:31.032  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-30 10:21:31.036  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 10:21:31.036  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 10:21:31.038  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 10:21:31.038  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:21:31.038  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:31.039  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f072f not in the list
,08-30 10:21:31.039  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:31.039  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0913c not in the list
,08-30 10:21:31.039  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:31.040  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:21:31.040  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:21:31.046  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 10:21:31.046  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:31.047  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:31.047  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f072f not in the list
08-30 10:21:31.047  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:31.047  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0913c not in the list
,08-30 10:21:31.047  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:31.047  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:31.047  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:31.048  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:21:31.048  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:31.048  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:31.048  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26f072f not in the list
,08-30 10:21:31.048  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:21:31.048  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ad0913c not in the list
08-30 10:21:31.049  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:21:31.049  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:31.049  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:31.050  3943  3993 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-30 10:21:31.050  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-30 10:21:31.051  3943  3993 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 10:21:31.051  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 10:21:31.051  3943  3993 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-30 10:21:31.051  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-30 10:21:31.056  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-30 10:21:31.056  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-30 10:21:31.056  3943  3993 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-30 10:21:31.057  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 10:21:31.057  3943  3993 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 10:21:31.057  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 10:21:31.057  3943  3993 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 10:21:31.057  3943  3993 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 10:21:31.058  3943  3993 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-30 10:21:31.058  3943  3993 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 10:21:31.059  3943  3993 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 10:21:31.059  3943  3993 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 10:21:31.060  3943  3993 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 10:21:31.060  3943  3993 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-30 10:21:31.062  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 10:21:31.062  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c9663ca added. We now have 3 listener(s)
,08-30 10:21:31.062  3943  3993 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 10:21:31.066  3943  3993 D BluetoothAdapter: enable(): BT is already enabled..!
,08-30 10:21:31.066   874  2029 D WifiService: setWifiEnabled: true pid=3943, uid=10000
,08-30 10:21:31.066   874  2029 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 10:21:31.388   874  1302 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-30 10:21:31.525  3943  3943 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 10:21:36.075  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 10:21:36.075  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6ac393b added. We now have 4 listener(s)
08-30 10:21:36.076  3943  3993 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 10:21:36.092  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 10:21:36.093  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6ac393b removed from the list
08-30 10:21:36.093  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 10:21:36.093  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:36.094  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:36.097  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 10:21:36.097  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f668858 added. We now have 4 listener(s)
08-30 10:21:36.098  3943  3993 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 10:21:36.102  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 10:21:36.102  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f668858 removed from the list
08-30 10:21:36.102  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 10:21:36.103  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:21:36.103  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:21:36.105  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 10:21:36.106  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8430db1 added. We now have 4 listener(s)
08-30 10:21:36.106  3943  3993 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 10:21:36.113   874  1374 D WifiService: setWifiEnabled: false pid=3943, uid=10000
,08-30 10:21:36.113   874  1374 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 10:21:36.128  2855  2874 D BluetoothAdapterState: Current state: ON, message: 23
08-30 10:21:36.129  2855  2874 D BluetoothAdapterProperties: Setting state to 13
08-30 10:21:36.129  2855  2874 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 10:21:36.130  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 10:21:36.131  2855  2874 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 10:21:36.136  2855  2874 I BluetoothAdapterState: Entering PendingCommandState
,08-30 10:21:36.138  2855  2855 D BluetoothMapService: onReceive
,08-30 10:21:36.139  2855  2855 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:36.139  2855  2855 D BluetoothMapService: STATE_TURNING_OFF
08-30 10:21:36.140  2855  2855 D BluetoothMapService: MAP Service closeService in
08-30 10:21:36.140  2855  2855 D BluetoothMapMasInstance0: MAP Service shutdown
08-30 10:21:36.140  2855  2855 D ObexServerSockets0: shutdown(block = true)
08-30 10:21:36.141  2855  2855 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-30 10:21:36.142  2855  3071 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-30 10:21:36.142  2855  3070 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-30 10:21:36.142  2855  2855 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 10:21:36.144  2855  3039 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-30 10:21:36.144  2855  2855 I BtOppRfcommListener: stopping Accept Thread
,08-30 10:21:36.145  2855  3612 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 10:21:36.146  2855  3612 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-30 10:21:36.149  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 10:21:36.150  3943  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:21:36.150  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:36.150  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:36.150  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:36.150  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:36.150  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:36.150  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:21:36.150  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 10:21:36.152  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:36.152  3943  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:36.152  3943  3993 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 10:21:36.156  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-30 10:21:36.156  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:36.159   874  1302 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 10:21:36.159   874  1302 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-30 10:21:36.159   874  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 10:21:36.159   874  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 10:21:36.159  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:36.163  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 10:21:36.163  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:36.163  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:36.163  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:36.163  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:36.163  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:36.163  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:36.163  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:21:36.163  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 10:21:36.164  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:36.164  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 10:21:36.168  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 10:21:36.168  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:36.168  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:36.168  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:36.168  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:36.168  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:36.168  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:36.168  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:21:36.168  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:21:36.169  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:36.169  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:36.171   874   887 I ActivityManager: Start proc 4028:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-30 10:21:36.171  2855  2880 D BluetoothAdapterProperties: Scan Mode:20
,08-30 10:21:36.172  2855  2874 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-30 10:21:36.173   874  1302 E native  : do suspend true
,08-30 10:21:36.177  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:36.177  2855  2855 D HeadsetService: Received stop request...Stopping profile...
08-30 10:21:36.179  1359  1371 D BluetoothHeadset: Proxy object disconnected
08-30 10:21:36.179  1359  1359 D HeadsetProfile: Bluetooth service disconnected
08-30 10:21:36.180   874   874 D BluetoothHeadset: Proxy object disconnected
,08-30 10:21:36.180   874   874 D BluetoothHeadset: Proxy object disconnected
08-30 10:21:36.180   874   874 D BluetoothHeadset: Proxy object disconnected
,08-30 10:21:36.180  2855  2855 D A2dpService: Received stop request...Stopping profile...
,08-30 10:21:36.181  1978  1992 D BluetoothHeadset: Proxy object disconnected
,08-30 10:21:36.181  2855  3051 D A2dpStateMachine: Exit Disconnected: -1
,08-30 10:21:36.183  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:36.183   874   874 D BluetoothA2dp: Proxy object disconnected
08-30 10:21:36.183  1359  1359 D BluetoothA2dp: Proxy object disconnected
,08-30 10:21:36.184  2855  2855 V BluetoothAdapterState: isTurningOff()=true
08-30 10:21:36.184  2855  2855 V BluetoothAdapterState: isTurningOn()=false
08-30 10:21:36.184  2855  2855 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 10:21:36.184  2855  2855 V BluetoothAdapterState: isBleTurningOff()=false
08-30 10:21:36.186  2855  2855 D HidService: Received stop request...Stopping profile...
08-30 10:21:36.186  2855  2855 D HidService: Stopping Bluetooth HidService
08-30 10:21:36.187  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:36.187  1359  1359 D BluetoothInputDevice: Proxy object disconnected
08-30 10:21:36.187  1359  1359 D HidProfile: Bluetooth service disconnected
08-30 10:21:36.188   372   872 D CommandListener: Clearing all IP addresses on wlan0
,08-30 10:21:36.188   874  2121 D DhcpClient: Clearing IP address
08-30 10:21:36.190  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:36.190  2855  2855 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 10:21:36.190  2855  2880 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-30 10:21:36.190  2855  3000 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 10:21:36.191  2855  3000 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 10:21:36.191  2855  3000 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 10:21:36.191  2855  2880 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-30 10:21:36.190  2855  2855 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 10:21:36.191  2855  2855 D HealthService: Received stop request...Stopping profile...
08-30 10:21:36.192   372   872 D CommandListener: Setting iface cfg
08-30 10:21:36.193   874  2125 D DhcpClient: Receive thread stopped
08-30 10:21:36.194  2855  2855 D PanService: Received stop request...Stopping profile...
08-30 10:21:36.194  1359  1359 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 10:21:36.194  1359  1359 D PanProfile: Bluetooth service disconnected
08-30 10:21:36.194  1497  2532 V NativeCrypto: Read error: ssl=0x9b710400: I/O error during system call, Connection timed out
08-30 10:21:36.197  1497  2532 V NativeCrypto: SSL shutdown failed: ssl=0x9b710400: I/O error during system call, Broken pipe
08-30 10:21:36.197  2855  2855 V BluetoothAdapterState: isTurningOff()=true
08-30 10:21:36.197  2855  2855 V BluetoothAdapterState: isTurningOn()=false
08-30 10:21:36.197   874  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 10:21:36.197   874  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-30 10:21:36.200   874  1302 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-30 10:21:36.201   874  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 10:21:36.201   874  1302 E native  : do suspend true
08-30 10:21:36.201   874  1304 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-30 10:21:36.202   403   403 E Parcel  : Reading a NULL string not supported here.
08-30 10:21:36.197  2855  2855 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 10:21:36.205  2855  2855 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 10:21:36.207  2855  2880 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-30 10:21:36.207  2855  3000 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 10:21:36.207  2855  3000 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 10:21:36.207  2855  3000 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 10:21:36.208  2855  3000 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 10:21:36.208  2855  2855 V BluetoothAdapterState: isTurningOff()=true
,08-30 10:21:36.208  2855  3000 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 10:21:36.208  2855  2855 V BluetoothAdapterState: isTurningOn()=false
08-30 10:21:36.208  2855  3000 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 10:21:36.208  2855  2855 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 10:21:36.208  2855  2855 V BluetoothAdapterState: isBleTurningOff()=false
08-30 10:21:36.208  2855  2855 D BluetoothMapService: Received stop request...Stopping profile...
08-30 10:21:36.208  2855  2855 D BluetoothMapService: stop()
,08-30 10:21:36.209  2855  2855 D BluetoothMapAppObserver: deinitObservers()
08-30 10:21:36.209  2855  2855 D BluetoothMapAppObserver: removeReceiver()
,08-30 10:21:36.210  2855  2855 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 10:21:36.210  2855  2880 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 10:21:36.211  2855  2855 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 10:21:36.211  2855  2855 V BluetoothAdapterState: isTurningOff()=true
,08-30 10:21:36.211  2855  2855 V BluetoothAdapterState: isTurningOn()=false
,08-30 10:21:36.211  2855  2855 V BluetoothAdapterState: isBleTurningOn()=false
08-30 10:21:36.211  2855  2855 V BluetoothAdapterState: isBleTurningOff()=false
08-30 10:21:36.212  2855  2855 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-30 10:21:36.212  2855  2880 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 10:21:36.212  2855  2855 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 10:21:36.213  2855  2855 V BluetoothAdapterState: isTurningOff()=true
08-30 10:21:36.213  2855  2855 V BluetoothAdapterState: isTurningOn()=false
,08-30 10:21:36.213  2855  2855 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 10:21:36.213  2855  2855 V BluetoothAdapterState: isBleTurningOff()=false
08-30 10:21:36.213  2855  2855 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-30 10:21:36.213  2855  2855 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-30 10:21:36.215  2855  2855 D BluetoothMapService: MAP Service closeService in
,08-30 10:21:36.215  2855  2855 V BluetoothAdapterState: isTurningOff()=true
08-30 10:21:36.215  2855  2855 V BluetoothAdapterState: isTurningOn()=false
08-30 10:21:36.215  2855  2855 V BluetoothAdapterState: isBleTurningOn()=false
08-30 10:21:36.215  2855  2855 V BluetoothAdapterState: isBleTurningOff()=false
08-30 10:21:36.215  2855  2874 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 10:21:36.215  2855  2874 D BluetoothAdapterProperties: Setting state to 15
08-30 10:21:36.216  2855  2874 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-30 10:21:36.216  2855  2855 D BluetoothMapService: cleanup()
08-30 10:21:36.216  2855  2855 D BluetoothMapService: MAP Service closeService in
08-30 10:21:36.216  2855  2874 I BluetoothAdapterState: Entering BleOnState
08-30 10:21:36.216  1359  2101 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 10:21:36.216   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 10:21:36.216  1359  1371 D BluetoothMap: onBluetoothStateChange: up=false
08-30 10:21:36.217   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 10:21:36.217  1359  1370 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 10:21:36.218  1359  2101 D BluetoothPan: onBluetoothStateChange on: false
08-30 10:21:36.218  1978  2070 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 10:21:36.219  1359  1371 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 10:21:36.219  1359  1370 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 10:21:36.220   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 10:21:36.220   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 10:21:36.220  2855  2874 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-30 10:21:36.220  2855  2874 D BluetoothAdapterProperties: Setting state to 16
08-30 10:21:36.220  2855  2874 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 10:21:36.221  2855  2874 D BluetoothAdapterProperties: onBleDisable
08-30 10:21:36.221  2855  2874 I BluetoothAdapterState: Entering PendingCommandState
08-30 10:21:36.221  2855  2875 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 10:21:36.222  2855  3000 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 10:21:36.222  2855  3000 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 10:21:36.227  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:36.227  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:36.227  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:36.227  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:36.227  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:36.227  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:36.227  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:36.227  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:36.227  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:36.228  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:36.228  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:36.229  2855  2880 D BluetoothAdapterProperties: Scan Mode:20
08-30 10:21:36.230  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:36.230  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:36.230  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:36.230  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:36.230  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:36.230  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:36.230  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:36.230  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:36.230  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:36.231  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 10:21:36.231  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:36.234  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:36.234  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:36.234  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:36.234  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:36.234  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:36.234  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:36.234  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:36.234  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:36.234  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:36.234  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:36.234  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:36.236  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:36.237  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:36.237  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:36.242   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-30 10:21:36.259  4028  4028 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-30 10:21:36.266   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-30 10:21:36.267   372   872 D CommandListener: Clearing all IP addresses on wlan0
08-30 10:21:36.267   874  1304 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-30 10:21:36.267   874  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:36.269   874   891 D Tethering: MasterInitialState.processMessage what=3
08-30 10:21:36.271  3545  3545 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@f4b90c3 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-30 10:21:36.272   874  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-30 10:21:36.273  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:36.276  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:36.278  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:36.283  4028  4028 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 10:21:36.288   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9b141f4:true
08-30 10:21:36.290  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 10:21:36.290   874  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 10:21:36.293  1849  2294 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 10:21:36.294  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:36.294  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:36.294  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:36.294  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:36.294  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:36.294  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:36.294  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:36.294  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:36.294  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:36.295  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:36.295  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:36.298  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:36.298  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:36.298  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:36.298  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:36.298  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:36.298  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:36.298  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:36.298  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:36.298  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:36.298  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:36.298  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:36.299   874  1302 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 10:21:36.300  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:36.300  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:36.300  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:36.300  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:36.300  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:36.300  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:36.300  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:36.300  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:36.300  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:36.301  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:36.301  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:36.309   874  1984 I ActivityManager: Start proc 4046:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-30 10:21:36.317  4028  4028 D LocalBluetoothProfileManager: Adding local MAP profile
08-30 10:21:36.321  4028  4028 D BluetoothMap: Create BluetoothMap proxy object
08-30 10:21:36.325  4028  4028 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-30 10:21:36.330  4028  4028 D DockEventReceiver: finishStartingService: stopping service
,08-30 10:21:36.334   874  1998 I ActivityManager: Killing 3344:com.google.android.gm/u0a78 (adj 15): empty #17
08-30 10:21:36.350   372   872 E Netd    : netlink response contains error (No such file or directory)
08-30 10:21:36.351   874  1304 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-30 10:21:36.417  4046  4046 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-30 10:21:36.434  2855  2880 I bt_hci  : shut_down
,08-30 10:21:36.435  2855  2886 D bt_hwcfg: hw_epilog_process
,08-30 10:21:36.448  2855  2886 I bt_vendor: low_power_mode_cb
,08-30 10:21:36.469  2855  2886 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 10:21:36.469  2855  2886 I bt_vendor: epilog_cb
08-30 10:21:36.469  2855  2886 I bt_hci  : epilog_finished_callback
,08-30 10:21:36.475  2855  2880 I bt_hci_h4: hal_close
,08-30 10:21:36.476  2855  2880 I bt_userial_vendor: device fd = 51 close
,08-30 10:21:36.599  2855  2875 D bt_stack_manager: event_shut_down_stack finished.
,08-30 10:21:36.600  4046  4046 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 10:21:36.600  4046  4046 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 10:21:36.600  4046  4046 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 10:21:36.600  4046  4046 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 10:21:36.600  2855  2874 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-30 10:21:36.604  4046  4046 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 10:21:36.604  4046  4046 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 10:21:36.604  4046  4046 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 10:21:36.604  4046  4046 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.r.k.d(PG:583)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 10:21:36.604  4046  4046 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 10:21:36.605  4046  4046 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at and,roid.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 10:21:36.604  2855  2855 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 10:21:36.605  2855  2874 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-30 10:21:36.605  4046  4046 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at java.io.File.exists(File.java:361)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.app.ActivityT,hread.-wrap1(ActivityThread.java)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 10:21:36.605  2855  2855 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 10:21:36.606  2855  2855 D BtGatt.GattService: stop()
08-30 10:21:36.606  2855  2855 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 10:21:36.605  4046  4046 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 10:21:36.605  4046  4046 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 10:21:36.609  2855  2855 V BluetoothAdapterState: isTurningOff()=false
08-30 10:21:36.609  2855  2855 V BluetoothAdapterState: isTurningOn()=false
08-30 10:21:36.610  2855  2855 V BluetoothAdapterState: isBleTurningOn()=false
08-30 10:21:36.610  2855  2855 V BluetoothAdapterState: isBleTurningOff()=true
08-30 10:21:36.611  2855  2874 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-30 10:21:36.611  2855  2874 D BluetoothAdapterProperties: Setting state to 10
08-30 10:21:36.611  2855  2874 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-30 10:21:36.613  2855  2874 I BluetoothAdapterState: Entering OffState
08-30 10:21:36.614   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-30 10:21:36.631  4028  4028 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 10:21:36.647  2855  2855 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-30 10:21:36.647  2855  2855 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 10:21:36.647  2855  2855 I BluetoothServiceJni: cleanupNative: return from cleanup
08-30 10:21:36.648  2855  2875 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-30 10:21:36.651  2855  2875 D bt_stack_manager: event_clean_up_stack finished.
08-30 10:21:36.653  2855  2855 I art     : System.exit called, status: 0
08-30 10:21:36.653  2855  2855 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 10:21:36.674  4028  4028 D DockEventReceiver: finishStartingService: stopping service
08-30 10:21:36.684   874  2026 I ActivityManager: Killing 3545:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-30 10:21:36.847   874   884 I ActivityManager: Process com.android.bluetooth (pid 2855) has died
,08-30 10:21:36.879  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 10:21:36.891  4046  4066 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 10:21:36.921   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32295a7:true,
,08-30 10:21:36.925   874  1998 I ActivityManager: Start proc 4082:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,08-30 10:21:36.985  4082  4082 D AdapterServiceConfig: Adding HeadsetService
,08-30 10:21:36.985  4082  4082 D AdapterServiceConfig: Adding A2dpService
08-30 10:21:36.985  4082  4082 D AdapterServiceConfig: Adding HidService
08-30 10:21:36.985  4082  4082 D AdapterServiceConfig: Adding HealthService
08-30 10:21:36.985  4082  4082 D AdapterServiceConfig: Adding PanService
,08-30 10:21:36.985  4082  4082 D AdapterServiceConfig: Adding GattService
08-30 10:21:36.986  4082  4082 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 10:21:36.994  1690  1690 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 10:21:36.997  1690  1690 D SystemUpdateService: onCreate
,08-30 10:21:37.001  1690  1690 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 10:21:37.004  1690  4094 I SystemUpdateService: active receiver: enabled
,08-30 10:21:37.010  1690  4094 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 10:21:37.012  1690  1690 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 10:21:37.014  1690  4094 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-30 10:21:37.014  1690  4094 I SystemUpdateService: now status is 0 (complete)
08-30 10:21:37.015  1690  4094 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 10:21:37.015  1690  4094 I SystemUpdateService: file has been verified
08-30 10:21:37.015  1690  2510 I iu.UploadsManager: num queued entries: 0
08-30 10:21:37.015  1690  2510 I iu.UploadsManager: num updated entries: 0
08-30 10:21:37.016  1690  2510 I iu.SyncManager: NEXT; no task
08-30 10:21:37.016  1690  1690 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-30 10:21:37.016  1690  4094 I SystemUpdateService: OTA package size = 12249756
08-30 10:21:37.018  1690  1690 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 10:21:37.023  1690  4094 I SystemUpdateService: showing system update notification
,08-30 10:21:37.052   874  2289 I ActivityManager: Start proc 4096:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-30 10:21:37.054  1690  1690 D SystemUpdateService: onDestroy
,08-30 10:21:37.107  4096  4096 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-30 10:21:37.112  4096  4096 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:21:37.122  4096  4096 D SprintDMHelper: simOperator: 
,08-30 10:21:37.122  4096  4096 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 10:21:37.152   874  1374 I ActivityManager: Start proc 4108:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-30 10:21:37.155   874  1374 I ActivityManager: Killing 3449:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-30 10:21:37.320   874  2027 I ActivityManager: Start proc 4123:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-30 10:21:37.323  3631  4122 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-30 10:21:37.332   874  2029 I ActivityManager: Killing 1674:android.process.acore/u0a5 (adj 15): empty #17
,08-30 10:21:37.392  4123  4123 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-30 10:21:37.451  4123  4123 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-30 10:21:37.451  4123  4123 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-30 10:21:37.451  4123  4123 I GAv4    :   adb logcat -s GAv4
,08-30 10:21:37.468  4123  4123 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-30 10:21:37.476  4123  4123 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-30 10:21:37.511  4123  4140 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-30 10:21:37.612  4123  4123 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-30 10:21:37.651  4123  4123 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-30 10:21:37.667  4123  4123 I LibraryLoader: Time to load native libraries: 11 ms (timestamps 0-11)
,08-30 10:21:37.668  4123  4123 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 10:21:37.677  4123  4123 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c2230b3}
,08-30 10:21:37.678  4123  4123 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 10:21:37.678  4123  4123 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 10:21:37.688  4123  4123 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-30 10:21:37.689  4123  4123 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 10:21:37.708  4123  4123 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-30 10:21:37.720  4123  4123 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 10:21:37.721  4123  4123 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-30 10:21:37.721  4123  4123 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-30 10:21:37.721  4123  4123 I Adreno  : Build Date                       : 10/20/15
08-30 10:21:37.721  4123  4123 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 10:21:37.721  4123  4123 I Adreno  : Local Branch                     : M14
08-30 10:21:37.721  4123  4123 I Adreno  : Remote Branch                    : 
08-30 10:21:37.721  4123  4123 I Adreno  : Remote Branch                    : 
08-30 10:21:37.721  4123  4123 I Adreno  : Reconstruct Branch               : 
,08-30 10:21:37.786  4123  4123 I NSApplication: Starting up...
,08-30 10:21:37.799  4123  4169 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-30 10:21:37.833   874  1374 I ActivityManager: Start proc 4174:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
08-30 10:21:37.834   874  1374 I ActivityManager: Killing 3799:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-30 10:21:37.912  4174  4174 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-30 10:21:38.094   874  2026 I ActivityManager: Killing 3815:com.android.musicfx/u0a18 (adj 15): empty #17
,08-30 10:21:38.182   874   884 I ActivityManager: Start proc 4188:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-30 10:21:38.240  4188  4188 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-30 10:21:38.286  4188  4188 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-30 10:21:38.299   874  2029 I ActivityManager: Killing 3574:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-30 10:21:41.155   874  2027 D WifiService: setWifiEnabled: true pid=3943, uid=10000
,08-30 10:21:41.155   874  2027 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 10:21:41.168   874  1302 D WifiConfigStore: Loading config and enabling all networks 
,08-30 10:21:41.177  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 10:21:41.177  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:41.177  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:41.177  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:41.177  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:41.177  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:41.177  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:41.177  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:41.177  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:41.177  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:41.177  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 10:21:41.180  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 10:21:41.180  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:41.180  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:41.180  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:41.180  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:41.180  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:41.180  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:41.180  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:41.180  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:41.181  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:41.181  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 10:21:41.184  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:41.184  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:41.184  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:41.184  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:41.184  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:41.184  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:41.184  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:41.184  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:41.184  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 10:21:41.184  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:41.184  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:41.190   874  1302 D WifiConfigStore: loaded 0 passpoint configs
08-30 10:21:41.191   874  1302 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-30 10:21:41.192   874  1302 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-30 10:21:41.194   874  1302 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 10:21:41.194   874  1302 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-30 10:21:41.195   874  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-30 10:21:41.195   874  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 10:21:41.216   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 10:21:41.216   874  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 10:21:41.218   372   872 D CommandListener: Setting iface cfg
,08-30 10:21:41.227   874  1301 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '131 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 131 Failed to set address (No such device)'
,08-30 10:21:41.227   874  1302 E native  : do suspend true
08-30 10:21:41.227   874  1301 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 10:21:41.243   874  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 10:21:41.250   874  1301 D WifiNative-HAL: p2pGetDeviceAddress
,08-30 10:21:41.250   874  1301 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 10:21:42.004   874  2027 I ActivityManager: Killing 3837:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-30 10:21:42.616   874  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 10:21:42.696   874  1302 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=3.75 rxSuccessRate=3.69 delta 1000 -> 1000
,08-30 10:21:42.698   874  1302 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-30 10:21:42.699   874  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 10:21:42.718   874  1302 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 10:21:42.774   874  1302 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 10:21:42.780  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 10:21:43.219  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 10:21:43.272  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 10:21:43.273  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 10:21:43.277   874  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 10:21:43.289   874  1302 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 10:21:43.289   874  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 10:21:43.289   874  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 10:21:43.312   874  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 10:21:43.329   372   872 D CommandListener: Setting iface cfg
,08-30 10:21:43.330   874  1302 D WifiStateMachine: Start Dhcp Watchdog 2
,08-30 10:21:43.338   874  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 10:21:43.369   874  4223 D DhcpClient: Receive thread started
,08-30 10:21:43.455   874  1302 E native  : do suspend false
,08-30 10:21:43.477   874  2121 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 10:21:43.531   874  4223 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172648, domain null
,08-30 10:21:43.532   874  2121 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172648 seconds
,08-30 10:21:43.536   874  2121 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 10:21:43.568   874  4223 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 10:21:43.569   874  2121 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 10:21:43.574   372   872 D CommandListener: Setting iface cfg
,08-30 10:21:43.587   874  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 10:21:43.586   874  2121 D DhcpClient: Scheduling renewal in 86399s
08-30 10:21:43.589   874  1302 E native  : do suspend true
,08-30 10:21:43.613   874  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 10:21:43.617   874  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 10:21:43.618   874  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 10:21:43.624   874  1304 D ConnectivityService: Adding iface wlan0 to network 101
,08-30 10:21:43.628   874  1302 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 10:21:43.711   874  1304 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 10:21:43.711   874  1304 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-30 10:21:43.714   874  1304 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-30 10:21:43.717   874  1304 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-30 10:21:43.721   874  1304 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-30 10:21:43.732   874  1304 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 10:21:43.739   874  1304 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-30 10:21:43.739   874  1304 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-30 10:21:43.740   874  1304 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-30 10:21:43.740   874  1304 D ConnectivityService:    accepting network in place of null
,08-30 10:21:43.740   874  1302 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-30 10:21:43.741   874  1304 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-30 10:21:43.742   874  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 10:21:43.751   874  4222 D NetlinkSocketObserver: NeighborEvent{elapsedMs=176095, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 10:21:43.803   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 10:21:43.838   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 10:21:43.841   874  4221 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,08-30 10:21:43.844   874  1304 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-30 10:21:43.844   874  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-30 10:21:43.850   874   891 D Tethering: MasterInitialState.processMessage what=3
08-30 10:21:43.858   874  1304 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-30 10:21:43.861  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:43.861  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:43.861  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:43.861  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:43.861  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:43.861  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:43.861  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:43.861  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:21:43.861  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:21:43.862  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:43.862  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 10:21:43.868  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 10:21:43.869  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:43.869  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:43.869  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:43.869  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:43.869  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:43.869  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:43.869  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:21:43.869  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 10:21:43.869  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:43.869  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 10:21:43.872  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 10:21:43.873  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:43.873  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:43.873  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:43.873  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:21:43.873  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:43.873  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:21:43.873  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:21:43.873  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 10:21:43.873  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:43.873  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 10:21:43.895  1690  1690 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 10:21:43.900  1690  1690 D SystemUpdateService: onCreate
,08-30 10:21:43.903  1690  1690 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 10:21:43.907  3898  4232 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 10:21:43.912  1690  4233 I SystemUpdateService: active receiver: enabled
,08-30 10:21:43.924  1690  4233 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 10:21:43.937  1690  4233 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-30 10:21:43.937  1690  4233 I SystemUpdateService: now status is 0 (complete)
08-30 10:21:43.937  1690  4233 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-30 10:21:43.937  1690  4233 I SystemUpdateService: file has been verified
,08-30 10:21:43.938  1690  4233 I SystemUpdateService: OTA package size = 12249756
,08-30 10:21:43.965   874  4221 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 08:21:43 GMT], X-Android-Received-Millis=[1472545303965], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472545303886]}
,08-30 10:21:43.969  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 10:21:43.972   874  1304 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 10:21:43.973   874  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-30 10:21:43.973   874  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-30 10:21:43.981   874  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 10:21:44.012  1690  1690 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 10:21:44.028  1690  4235 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 10:21:44.028  1690  4235 W BaseAppContext: Using Auth Proxy for data requests.
,08-30 10:21:44.030  1690  4235 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 10:21:44.040  1690  4233 I SystemUpdateService: showing system update notification
,08-30 10:21:44.046  1690  2510 I iu.UploadsManager: num queued entries: 0
,08-30 10:21:44.055  1690  1690 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 10:21:44.056  1690  1690 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-30 10:21:44.058  4096  4096 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:21:44.072  4096  4096 D SprintDMHelper: simOperator: 
,08-30 10:21:44.072  4096  4096 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-30 10:21:44.085  3898  4240 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 10:21:44.093  1690  2510 I iu.UploadsManager: num updated entries: 0
,08-30 10:21:44.094  1690  2510 I iu.SyncManager: NEXT; no task
,08-30 10:21:44.136  1690  1690 D SystemUpdateService: onDestroy
,08-30 10:21:44.184  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 10:21:44.186  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 10:21:44.241  1497  4246 I VacuumService: Vacuum at: now=1472545304241 tag=VacuumService
,08-30 10:21:44.246  3631  4241 I Babel   : connection state changed from DISCONNECTED to CONNECTED,
,08-30 10:21:44.250  1497  3152 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 10:21:44.250  1497  3152 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 10:21:44.250  1497  3152 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 10:21:44.251  1497  3152 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 10:21:44.397  1497  1508 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 10:21:44.397  1497  1508 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-30 10:21:44.397  1497  1508 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 10:21:44.397  1497  1508 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 10:21:44.431  1497  1938 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 10:21:44.431  1497  1938 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-30 10:21:44.431  1497  1938 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 10:21:44.431  1497  1938 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 10:21:44.498  3898  4240 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-30 10:21:44.499  3898  4232 E BooksSync: Soft error
08-30 10:21:44.499  3898  4232 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 10:21:44.499  3898  4232 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 10:21:44.499  3898  4232 E BooksSync: Sync error
08-30 10:21:44.499  3898  4232 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 10:21:44.499  3898  4232 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 10:21:44.499  3898  4232 I BooksSync: Finished books sync
,08-30 10:21:44.515   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 163670, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 10:21:44.539  1690  4235 E MDM     : [181] SitrepService.a: Error sending sitrep.
,08-30 10:21:44.622  1497  4251 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-30 10:21:44.627  1497  4251 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 10:21:44.845   874  1304 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-30 10:21:45.389  1497  4251 W Uploader:  no longer exists, so no auth token.
,08-30 10:21:46.162   874  1688 D WifiService: setWifiEnabled: false pid=3943, uid=10000
08-30 10:21:46.163   874  1688 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 10:21:46.196  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-30 10:21:46.203   874  1302 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-30 10:21:46.203   874  1302 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-30 10:21:46.204   874  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 10:21:46.204   874  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 10:21:46.226   874  1302 E native  : do suspend true
,08-30 10:21:46.236   874  2121 D DhcpClient: Clearing IP address
,08-30 10:21:46.236   372   872 D CommandListener: Clearing all IP addresses on wlan0
,08-30 10:21:46.239   372   872 D CommandListener: Setting iface cfg
,08-30 10:21:46.242  1497  4244 V NativeCrypto: Read error: ssl=0x9a8ca000: I/O error during system call, Connection timed out
,08-30 10:21:46.243  1497  4244 V NativeCrypto: SSL shutdown failed: ssl=0x9a8ca000: I/O error during system call, Broken pipe
,08-30 10:21:46.245   874  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-30 10:21:46.247   874  1302 D WifiStateMachine: Start Disconnecting Watchdog 2
08-30 10:21:46.247   874  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-30 10:21:46.248   874  1302 E native  : do suspend true
08-30 10:21:46.250   403   403 E Parcel  : Reading a NULL string not supported here.
08-30 10:21:46.251   874  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-30 10:21:46.259   372   872 D CommandListener: Clearing all IP addresses on wlan0
08-30 10:21:46.263   874  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 10:21:46.264   874  1304 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-30 10:21:46.266   874  4223 D DhcpClient: Receive thread stopped
,08-30 10:21:46.280   874  1302 D WifiConfigStore: Retrieve network priorities after PNO.
08-30 10:21:46.282   874  1302 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-30 10:21:46.283  1849  2294 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 10:21:46.284  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:46.284  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:46.284  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:46.284  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:46.284  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:46.284  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:46.284  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:46.284  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:46.284  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:46.284  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:46.284  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 10:21:46.285  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:46.285  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:46.285  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:46.285  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:46.285  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:46.285  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:46.285  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:46.285  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:46.285  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:46.285  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 10:21:46.286  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:46.286  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:46.286  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:46.286  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:46.286  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:46.286  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:46.286  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:46.286  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:46.286  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:46.286  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 10:21:46.286  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 10:21:46.286  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 10:21:46.295   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 10:21:46.322   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 10:21:46.323   874  1304 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-30 10:21:46.323   874  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:21:46.325   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-30 10:21:46.327  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:46.328  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:46.331  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:46.334  1690  1690 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-30 10:21:46.337  1690  1690 D SystemUpdateService: onCreate
08-30 10:21:46.339  1690  1690 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 10:21:46.347  1690  1690 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 10:21:46.349  1690  2510 I iu.UploadsManager: num queued entries: 0
08-30 10:21:46.350  1690  2510 I iu.UploadsManager: num updated entries: 0
08-30 10:21:46.350  1690  2510 I iu.SyncManager: NEXT; no task
,08-30 10:21:46.364  1690  1690 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-30 10:21:46.365  1690  1690 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-30 10:21:46.366  4096  4096 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:21:46.372  4096  4096 D SprintDMHelper: simOperator: 
,08-30 10:21:46.372  4096  4096 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 10:21:46.400  3631  4274 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-30 10:21:46.387  1690  4270 I SystemUpdateService: active receiver: enabled
,08-30 10:21:46.424   372   872 E Netd    : netlink response contains error (No such file or directory)
,08-30 10:21:46.426  1690  4270 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 10:21:46.427  1690  4270 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-30 10:21:46.427  1690  4270 I SystemUpdateService: now status is 0 (complete)
,08-30 10:21:46.427  1690  4270 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 10:21:46.427  1690  4270 I SystemUpdateService: file has been verified
08-30 10:21:46.427  1690  4270 I SystemUpdateService: OTA package size = 12249756
,08-30 10:21:46.446  1690  4270 I SystemUpdateService: showing system update notification
,08-30 10:21:46.499  1497  4251 D Uploader: Network request failed class java.net.ConnectException(failed to connect to play.googleapis.com/216.58.214.42 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable))
,08-30 10:21:46.521  1690  1690 D SystemUpdateService: onDestroy
,08-30 10:21:51.218  4082  4082 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 10:21:51.218   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6ac393b:true
,08-30 10:21:51.223  4082  4082 I bt_bluedroid: init
,08-30 10:21:51.224  4082  4281 I BluetoothAdapterState: Entering OffState
,08-30 10:21:51.230  4082  4282 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 10:21:51.230  4082  4282 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-30 10:21:51.230  4082  4282 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-30 10:21:51.231  4082  4282 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 10:21:51.233  4082  4082 I bt_bluedroid: get_profile_interface socket
08-30 10:21:51.236  4082  4285 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 10:21:51.238  4082  4285 D BluetoothAdapterProperties: Name is: Nexus 6
08-30 10:21:51.238  4082  4082 I bt_bluedroid: get_profile_interface sdp
,08-30 10:21:51.246  4082  4093 I bt_bluedroid: config_hci_snoop_log
,08-30 10:21:51.250   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 10:21:51.263  4082  4281 D BluetoothAdapterState: Current state: OFF, message: 0
,08-30 10:21:51.264  4082  4281 D BluetoothAdapterProperties: Setting state to 14
08-30 10:21:51.264  4082  4281 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 10:21:51.269  4082  4281 D BluetoothBondStateMachine: make
,08-30 10:21:51.274  4082  4286 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 10:21:51.283  4082  4281 I BluetoothAdapterState: Entering PendingCommandState
,08-30 10:21:51.286  4082  4082 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 10:21:51.295  4082  4082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43bf881
,08-30 10:21:51.298  4082  4082 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 10:21:51.300  4082  4082 D BtGatt.GattService: Received start request. Starting profile...
,08-30 10:21:51.301  4082  4082 D BtGatt.GattService: start()
,08-30 10:21:51.301  4082  4082 I bt_bluedroid: get_profile_interface gatt,
,08-30 10:21:51.304  4082  4082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43bf881
,08-30 10:21:51.305  4082  4082 D BtGatt.AdvertiseManager: advertise manager created
,08-30 10:21:51.321  4082  4082 V BluetoothAdapterState: isTurningOff()=false
,08-30 10:21:51.321  4082  4082 V BluetoothAdapterState: isTurningOn()=false
08-30 10:21:51.322  4082  4082 V BluetoothAdapterState: isBleTurningOn()=true
08-30 10:21:51.322  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 10:21:51.323  4082  4281 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-30 10:21:51.324  4082  4281 I bt_bluedroid: enable
08-30 10:21:51.324  4082  4282 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-30 10:21:51.325  4082  4282 I bt_hci  : start_up
,08-30 10:21:51.333  4082  4282 I bt_vendor: alloc value 0xb39b9189
,08-30 10:21:51.333  4082  4282 I bt_vendor: init
08-30 10:21:51.333  4082  4282 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-30 10:21:51.333  4082  4282 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 10:21:51.442  4082  4282 D bt_hci  : start_up starting async portion
,08-30 10:21:51.442  4082  4289 I bt_hci  : event_finish_startup
08-30 10:21:51.443  4082  4289 I bt_hci_h4: hal_open
08-30 10:21:51.443  4082  4289 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 10:21:51.457  4082  4289 I bt_userial_vendor: device fd = 51 open
,08-30 10:21:51.483  4082  4289 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 10:21:51.515  4082  4289 D bt_hwcfg: Chipset BCM4354A2
08-30 10:21:51.515  4082  4289 D bt_hwcfg: Target name = [BCM4354A2]
,08-30 10:21:51.516  4082  4289 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 10:21:51.746   874  1304 D ConnectivityService: handlePromptUnvalidated 101
,08-30 10:21:52.186  4082  4289 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 10:21:52.187  4082  4289 D bt_hwcfg: Settlement delay -- 100 ms
,08-30 10:21:52.187  4082  4289 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 10:21:52.304  4082  4289 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 10:21:52.305  4082  4289 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 10:21:52.335  4082  4289 I bt_hwcfg: vendor lib fwcfg completed
,08-30 10:21:52.335  4082  4289 I bt_vendor: firmware callback
,08-30 10:21:52.335  4082  4289 I bt_hci  : firmware_config_callback
,08-30 10:21:52.347  4082  4291 I bt_btu  : btu_task pending for preload complete event
,08-30 10:21:52.347  4082  4291 I bt_btu_task: Bluetooth chip preload is complete
,08-30 10:21:52.347  4082  4291 I bt_btu  : btu_task received preload complete event
,08-30 10:21:52.357  4082  4291 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 10:21:52.357  4082  4291 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-30 10:21:52.357  4082  4291 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 10:21:52.358  4082  4291 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-30 10:21:52.358  4082  4291 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 10:21:52.358  4082  4291 I         : BTE_InitTraceLevels -- TRC_A2D
,08-30 10:21:52.358  4082  4291 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 10:21:52.359  4082  4291 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 10:21:52.359  4082  4291 I         : BTE_InitTraceLevels -- TRC_GAP
,08-30 10:21:52.359  4082  4291 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 10:21:52.360  4082  4291 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 10:21:52.360  4082  4291 I         : BTE_InitTraceLevels -- TRC_GATT
,08-30 10:21:52.360  4082  4291 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 10:21:52.360  4082  4291 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-30 10:21:52.361  4082  4291 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 10:21:52.495  4082  4291 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3936d9d
,08-30 10:21:52.496  4082  4291 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3936d9d 
,08-30 10:21:52.506  4082  4285 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-30 10:21:52.508  4082  4285 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 10:21:52.508  4082  4285 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 10:21:52.513  4082  4285 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 10:21:52.517  4082  4285 D BluetoothAdapterProperties: Scan Mode:20
,08-30 10:21:52.519  4082  4285 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 10:21:52.519  4082  4285 D bt_hci  : do_postload posting postload work item
,08-30 10:21:52.520  4082  4289 I bt_hci  : event_postload
,08-30 10:21:52.520  4082  4289 I bt_vendor: sco_config_cb
,08-30 10:21:52.520  4082  4289 I bt_hci  : sco_config_callback postload finished.
,08-30 10:21:52.522  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:52.524  4082  4285 D bt_bte_conf: Device ID record 1 : primary
,08-30 10:21:52.524  4082  4285 D bt_bte_conf:   vendorId            = 000f
08-30 10:21:52.524  4082  4285 D bt_bte_conf:   vendorIdSource      = 0001
08-30 10:21:52.525  4082  4285 D bt_bte_conf:   product             = 1200
,08-30 10:21:52.525  4082  4285 D bt_bte_conf:   version             = 1436
08-30 10:21:52.525  4082  4285 D bt_bte_conf:   clientExecutableURL = ,
08-30 10:21:52.525  4082  4285 D bt_bte_conf:   serviceDescription  = 
,08-30 10:21:52.526  4082  4285 D bt_bte_conf:   documentationURL    = 
,08-30 10:21:52.526  4082  4285 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-30 10:21:52.526  4082  4282 D bt_stack_manager: event_start_up_stack finished
,08-30 10:21:52.526  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:52.527  4082  4289 I bt_vendor: low_power_mode_cb
,08-30 10:21:52.528  4082  4281 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3,
08-30 10:21:52.529  4082  4281 D BluetoothAdapterProperties: Setting state to 15
,08-30 10:21:52.529  4082  4281 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 10:21:52.530  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:52.531  4082  4281 I BluetoothAdapterState: Entering BleOnState
08-30 10:21:52.536  4082  4281 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-30 10:21:52.537  4082  4281 D BluetoothAdapterProperties: Setting state to 11
,08-30 10:21:52.537  4082  4281 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-30 10:21:52.545  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:52.547  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:52.549  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:52.550  4082  4082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43bf881
08-30 10:21:52.551  4082  4082 D HeadsetService: Received start request. Starting profile...
08-30 10:21:52.555  4082  4082 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 10:21:52.555  4082  4082 D HeadsetStateMachine: make
,08-30 10:21:52.560  4082  4281 I BluetoothAdapterState: Entering PendingCommandState
,08-30 10:21:52.562  4082  4082 D HeadsetStateMachine: max_hf_connections = 1
,08-30 10:21:52.562  4082  4082 I bt_bluedroid: get_profile_interface handsfree
08-30 10:21:52.563  4082  4285 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 10:21:52.563  4082  4285 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-30 10:21:52.566  4082  4082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43bf881
,08-30 10:21:52.567  4082  4082 D A2dpService: Received start request. Starting profile...
08-30 10:21:52.567  4082  4082 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 10:21:52.568  4082  4082 I bt_bluedroid: get_profile_interface avrcp
,08-30 10:21:52.573  4082  4082 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 10:21:52.573  4082  4082 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 10:21:52.573  4082  4082 D A2dpStateMachine: make
,08-30 10:21:52.574  4082  4082 I bt_bluedroid: get_profile_interface a2dp
08-30 10:21:52.575  4082  4285 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 10:21:52.576  4082  4300 D A2dpStateMachine: Enter Disconnected: -2
,08-30 10:21:52.578  4082  4082 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 10:21:52.579  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 10:21:52.579  4082  4082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43bf881
08-30 10:21:52.580  4082  4082 D HidService: Received start request. Starting profile...
08-30 10:21:52.580  4028  4028 D BluetoothInputDevice: Proxy object connected
,08-30 10:21:52.581  4082  4082 I bt_bluedroid: get_profile_interface hidhost
08-30 10:21:52.581  4082  4082 D HidService: setHidService(): set to: null
,08-30 10:21:52.581  4082  4285 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39183e5
08-30 10:21:52.581  4082  4285 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-30 10:21:52.582  4082  4082 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 10:21:52.582  4028  4028 D HidProfile: Bluetooth service connected
08-30 10:21:52.582  4082  4082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43bf881
,08-30 10:21:52.583  4082  4082 D HealthService: Received start request. Starting profile...
08-30 10:21:52.584  4082  4082 I bt_bluedroid: get_profile_interface health
08-30 10:21:52.585  4082  4082 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 10:21:52.585  4082  4082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43bf881
,08-30 10:21:52.587  4082  4082 D PanService: Received start request. Starting profile...
08-30 10:21:52.587  4028  4028 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 10:21:52.587  4082  4082 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 10:21:52.587  4082  4082 I bt_bluedroid: get_profile_interface pan
08-30 10:21:52.587  4028  4028 D PanProfile: Bluetooth service connected
08-30 10:21:52.587  4082  4285 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 10:21:52.590  4082  4082 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43bf881
,08-30 10:21:52.591  4028  4028 D BluetoothMap: Proxy object connected
,08-30 10:21:52.591  4082  4082 D BluetoothMapService: Received start request. Starting profile...
08-30 10:21:52.591  4082  4082 D BluetoothMapService: start()
08-30 10:21:52.591  4028  4028 D MapProfile: Bluetooth service connected
,08-30 10:21:52.591  4028  4028 D BluetoothMap: getConnectedDevices()
08-30 10:21:52.592  4028  4028 D BluetoothMap: Bluetooth is Not enabled
08-30 10:21:52.593  4082  4082 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 10:21:52.594  4082  4082 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-30 10:21:52.594  4082  4082 D BluetoothMapAppObserver: createReceiver()
,08-30 10:21:52.595  4082  4082 D BluetoothMapAppObserver: initObservers()
08-30 10:21:52.595  4082  4082 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 10:21:52.602  4082  4082 V BluetoothAdapterState: isTurningOff()=false
,08-30 10:21:52.602  4082  4082 V BluetoothAdapterState: isTurningOn()=true
08-30 10:21:52.602  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
08-30 10:21:52.602  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 10:21:52.604  4082  4082 V BluetoothAdapterState: isTurningOff()=false
,08-30 10:21:52.604  4082  4082 V BluetoothAdapterState: isTurningOn()=true
08-30 10:21:52.604  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
08-30 10:21:52.604  4082  4298 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 10:21:52.604  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 10:21:52.606  4082  4082 V BluetoothAdapterState: isTurningOff()=false
,08-30 10:21:52.606  4082  4082 V BluetoothAdapterState: isTurningOn()=true
08-30 10:21:52.606  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
08-30 10:21:52.606  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
08-30 10:21:52.606  4082  4082 V BluetoothAdapterState: isTurningOff()=false
,08-30 10:21:52.607  4082  4082 V BluetoothAdapterState: isTurningOn()=true
08-30 10:21:52.607  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
08-30 10:21:52.607  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
08-30 10:21:52.607  4082  4082 V BluetoothAdapterState: isTurningOff()=false
08-30 10:21:52.607  4082  4082 V BluetoothAdapterState: isTurningOn()=true
08-30 10:21:52.607  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 10:21:52.607  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 10:21:52.607  4082  4082 V BluetoothAdapterState: isTurningOff()=false
08-30 10:21:52.607  4082  4082 V BluetoothAdapterState: isTurningOn()=true
08-30 10:21:52.607  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
08-30 10:21:52.607  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 10:21:52.608  4082  4281 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-30 10:21:52.608  4082  4281 D BluetoothAdapterProperties: ScanMode =  20
08-30 10:21:52.608  4082  4281 D BluetoothAdapterProperties: State =  11
08-30 10:21:52.609  4082  4281 D BluetoothAdapterProperties: Setting state to 12
08-30 10:21:52.609  4082  4281 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 10:21:52.610  4082  4281 I BluetoothAdapterState: Entering OnState
08-30 10:21:52.610  4028  4038 D BluetoothPan: onBluetoothStateChange on: true
,08-30 10:21:52.610  1359  2101 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 10:21:52.611   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 10:21:52.611  4028  4039 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 10:21:52.611  1359  1370 D BluetoothMap: onBluetoothStateChange: up=true
08-30 10:21:52.612  4082  4285 D BluetoothAdapterProperties: Scan Mode:21
08-30 10:21:52.612  4082  4285 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 10:21:52.613   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 10:21:52.613  1359  1359 D BluetoothMap: Proxy object connected,
08-30 10:21:52.613  1359  1359 D MapProfile: Bluetooth service connected
08-30 10:21:52.613  1359  1359 D BluetoothMap: getConnectedDevices()
08-30 10:21:52.613  1359  2101 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 10:21:52.615  4028  4038 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 10:21:52.616  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:52.616  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:52.616  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:52.616  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:52.616  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:21:52.616  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:52.616  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:52.616  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:52.616  1359  1371 D BluetoothPan: onBluetoothStateChange on: true
,08-30 10:21:52.618  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 10:21:52.618  1359  1359 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 10:21:52.618  1359  1359 D PanProfile: Bluetooth service connected
,08-30 10:21:52.618  1978  2291 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 10:21:52.619  4028  4039 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 10:21:52.619  1359  2101 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 10:21:52.620  4082  4082 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 10:21:52.621  4082  4082 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 10:21:52.621  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:52.621  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:52.621  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:52.621  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:52.621  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:21:52.621  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:52.621  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:52.621  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 10:21:52.621  1359  1359 D BluetoothInputDevice: Proxy object connected
08-30 10:21:52.621  1359  1359 D HidProfile: Bluetooth service connected
08-30 10:21:52.622  1359  1370 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 10:21:52.624  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:21:52.624   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 10:21:52.624   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 10:21:52.626   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
08-30 10:21:52.627  4082  4082 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 10:21:52.628  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:52.628  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:52.628  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:52.628  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:52.628  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:21:52.628  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:52.628  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:52.628  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:52.630  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 10:21:52.631  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:52.632  4082  4082 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 10:21:52.633  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:52.633  4028  4028 D LocalBluetoothProfileManager: Adding local A2DP profile
08-30 10:21:52.633  4082  4082 D ObexServerSockets: Succeed to create listening sockets 
08-30 10:21:52.633  4082  4082 D ObexServerSockets0: startAccept()
08-30 10:21:52.633  4082  4082 D ObexServerSockets0: prepareForNewConnect()
,08-30 10:21:52.634  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:52.635  4082  4082 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 10:21:52.635  4082  4082 D BluetoothSdpJni: SDP Create record success - handle: 0
08-30 10:21:52.636   874   874 D BluetoothA2dp: Proxy object connected
,08-30 10:21:52.637  1359  1359 D BluetoothA2dp: Proxy object connected
,08-30 10:21:52.637  4082  4307 D ObexServerSockets0: Accepting socket connection...
08-30 10:21:52.637  4082  4082 D BluetoothMapService: onReceive
08-30 10:21:52.637  4082  4082 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:52.638  4082  4082 D BluetoothMapService: STATE_ON
08-30 10:21:52.638  4082  4308 D ObexServerSockets0: Accepting socket connection...
,08-30 10:21:52.640  4028  4028 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-30 10:21:52.646  4028  4028 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 10:21:52.649  4028  4028 D BluetoothA2dp: Proxy object connected
,08-30 10:21:52.653  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 10:21:52.660  4028  4028 D DockEventReceiver: finishStartingService: stopping service
,08-30 10:21:52.662  4028  4028 D BluetoothPbap: Proxy object connected
,08-30 10:21:52.662  1359  1359 D BluetoothPbap: Proxy object connected
08-30 10:21:52.662  1359  1359 D PbapServerProfile: Bluetooth service connected
08-30 10:21:52.663  4028  4028 D PbapServerProfile: Bluetooth service connected
,08-30 10:21:52.668  4082  4082 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-30 10:21:52.668  4082  4082 D ObexServerSockets0: prepareForNewConnect()
,08-30 10:21:52.672  4082  4312 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 10:21:52.686  4082  4316 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 10:21:52.687  4082  4316 I BtOppRfcommListener: Accept thread started.
,08-30 10:21:52.713  1359  1371 D BluetoothHeadset: Proxy object connected
,08-30 10:21:52.713  1359  1359 D HeadsetProfile: Bluetooth service connected
,08-30 10:21:52.713   874   891 D BluetoothHeadset: Proxy object connected
,08-30 10:21:52.713   874   874 D BluetoothHeadset: Proxy object connected
,08-30 10:21:52.713   874   874 D BluetoothHeadset: Proxy object connected
,08-30 10:21:52.713   874   874 D BluetoothHeadset: Proxy object connected
,08-30 10:21:52.714  1978  2070 D BluetoothHeadset: Proxy object connected
,08-30 10:21:52.720  1978  1991 D BluetoothHeadset: Proxy object connected
,08-30 10:21:52.724   874   891 D BluetoothHeadset: Proxy object connected
,08-30 10:21:52.744  4028  4038 D BluetoothHeadset: Proxy object connected
,08-30 10:21:52.746  4028  4028 D HeadsetProfile: Bluetooth service connected
,08-30 10:21:56.182  4082  4281 D BluetoothAdapterState: Current state: ON, message: 23
,08-30 10:21:56.183  4082  4281 D BluetoothAdapterProperties: Setting state to 13
,08-30 10:21:56.183  4082  4281 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-30 10:21:56.185  4082  4281 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 10:21:56.188  4082  4281 I BluetoothAdapterState: Entering PendingCommandState
,08-30 10:21:56.198  4082  4082 D BluetoothMapService: onReceive
,08-30 10:21:56.198  4082  4082 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:21:56.198  4082  4082 D BluetoothMapService: STATE_TURNING_OFF
08-30 10:21:56.199  4082  4082 D BluetoothMapService: MAP Service closeService in
08-30 10:21:56.199  4082  4082 D BluetoothMapMasInstance0: MAP Service shutdown
,08-30 10:21:56.200  4082  4082 D ObexServerSockets0: shutdown(block = true)
08-30 10:21:56.201  4082  4307 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-30 10:21:56.206  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:56.206  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:56.206  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:56.206  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:56.206  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:56.206  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:56.206  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:56.206  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:56.206  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 10:21:56.207  4082  4082 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-30 10:21:56.208  4082  4308 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-30 10:21:56.209  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:56.209  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
08-30 10:21:56.210  4082  4294 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-30 10:21:56.212  4082  4082 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-30 10:21:56.213  4082  4082 I BtOppRfcommListener: stopping Accept Thread
,08-30 10:21:56.213  4082  4316 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-30 10:21:56.214  4082  4316 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 10:21:56.214  4082  4285 D BluetoothAdapterProperties: Scan Mode:20
,08-30 10:21:56.214  4082  4281 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-30 10:21:56.218  4082  4082 D HeadsetService: Received stop request...Stopping profile...
,08-30 10:21:56.218  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:56.219  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:56.219  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:56.219  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:56.219  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:56.219  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:56.219  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:56.219  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:56.219  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:56.220  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:56.220  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 10:21:56.221  4028  4028 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 10:21:56.223  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 10:21:56.223  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:21:56.223  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:21:56.223  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:21:56.223  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:21:56.223  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 10:21:56.223  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:21:56.223  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:21:56.223  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:21:56.224  3943  3943 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 10:21:56.225  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 10:21:56.227  4082  4082 V BluetoothAdapterState: isTurningOff()=true
,08-30 10:21:56.227  4082  4082 V BluetoothAdapterState: isTurningOn()=false
08-30 10:21:56.227  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
08-30 10:21:56.227  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
08-30 10:21:56.227  1359  1371 D BluetoothHeadset: Proxy object disconnected
,08-30 10:21:56.228  1359  1359 D HeadsetProfile: Bluetooth service disconnected
08-30 10:21:56.228  4082  4082 D A2dpService: Received stop request...Stopping profile...
08-30 10:21:56.229  4082  4300 D A2dpStateMachine: Exit Disconnected: -1
,08-30 10:21:56.230   874   874 D BluetoothHeadset: Proxy object disconnected
08-30 10:21:56.230   874   874 D BluetoothHeadset: Proxy object disconnected
08-30 10:21:56.230  4028  4039 D BluetoothHeadset: Proxy object disconnected
,08-30 10:21:56.230  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:56.231   874   874 D BluetoothHeadset: Proxy object disconnected
08-30 10:21:56.231  1978  2070 D BluetoothHeadset: Proxy object disconnected
08-30 10:21:56.232   874   874 D BluetoothA2dp: Proxy object disconnected
08-30 10:21:56.232  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:56.233  1359  1359 D BluetoothA2dp: Proxy object disconnected
08-30 10:21:56.234  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:56.234  4082  4082 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 10:21:56.234  4082  4082 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 10:21:56.234  4082  4291 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 10:21:56.234  4082  4291 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 10:21:56.234  4082  4291 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 10:21:56.235  4082  4285 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-30 10:21:56.235  4082  4285 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-30 10:21:56.237  4082  4082 D HidService: Received stop request...Stopping profile...
,08-30 10:21:56.237  4082  4082 D HidService: Stopping Bluetooth HidService
08-30 10:21:56.239  1359  1359 D BluetoothInputDevice: Proxy object disconnected
,08-30 10:21:56.239  1359  1359 D HidProfile: Bluetooth service disconnected
08-30 10:21:56.240  4082  4082 V BluetoothAdapterState: isTurningOff()=true
08-30 10:21:56.240  4082  4082 V BluetoothAdapterState: isTurningOn()=false
,08-30 10:21:56.240  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
08-30 10:21:56.241  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 10:21:56.244  4082  4291 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-30 10:21:56.244  4082  4291 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 10:21:56.245  4082  4291 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 10:21:56.245  4082  4291 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 10:21:56.245  4082  4291 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 10:21:56.245  4082  4082 D HealthService: Received stop request...Stopping profile...
08-30 10:21:56.245  4082  4291 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 10:21:56.245  4082  4285 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-30 10:21:56.247  4082  4082 D PanService: Received stop request...Stopping profile...
,08-30 10:21:56.248  1359  1359 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 10:21:56.248  1359  1359 D PanProfile: Bluetooth service disconnected
,08-30 10:21:56.249  4082  4082 D BluetoothMapService: Received stop request...Stopping profile...
,08-30 10:21:56.249  4082  4082 D BluetoothMapService: stop()
08-30 10:21:56.250  4082  4082 D BluetoothMapAppObserver: deinitObservers()
08-30 10:21:56.250  4082  4082 D BluetoothMapAppObserver: removeReceiver()
,08-30 10:21:56.256  4028  4028 D DockEventReceiver: finishStartingService: stopping service
,08-30 10:21:56.256  1359  1359 D BluetoothMap: Proxy object disconnected
,08-30 10:21:56.256  1359  1359 D MapProfile: Bluetooth service disconnected
,08-30 10:21:56.257  4028  4028 D HeadsetProfile: Bluetooth service disconnected
,08-30 10:21:56.257  4028  4028 D BluetoothA2dp: Proxy object disconnected
08-30 10:21:56.257  4082  4082 V BluetoothAdapterState: isTurningOff()=true
08-30 10:21:56.258  4082  4082 V BluetoothAdapterState: isTurningOn()=false
,08-30 10:21:56.258  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
08-30 10:21:56.258  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 10:21:56.258  4082  4082 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 10:21:56.258  4082  4285 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-30 10:21:56.258  4082  4082 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 10:21:56.257  4028  4028 D BluetoothInputDevice: Proxy object disconnected
,08-30 10:21:56.259  4028  4028 D HidProfile: Bluetooth service disconnected
08-30 10:21:56.259  4028  4028 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 10:21:56.259  4028  4028 D PanProfile: Bluetooth service disconnected
08-30 10:21:56.259  4082  4082 V BluetoothAdapterState: isTurningOff()=true
,08-30 10:21:56.259  4082  4082 V BluetoothAdapterState: isTurningOn()=false
,08-30 10:21:56.260  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
08-30 10:21:56.260  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 10:21:56.260  4082  4082 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 10:21:56.260  4082  4285 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-30 10:21:56.260  4082  4082 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 10:21:56.261  4082  4082 V BluetoothAdapterState: isTurningOff()=true
08-30 10:21:56.261  4082  4082 V BluetoothAdapterState: isTurningOn()=false
,08-30 10:21:56.261  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
08-30 10:21:56.261  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
08-30 10:21:56.261  4082  4082 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-30 10:21:56.261  4082  4082 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 10:21:56.262  4082  4082 D BluetoothMapService: MAP Service closeService in
,08-30 10:21:56.262  4082  4082 V BluetoothAdapterState: isTurningOff()=true
,08-30 10:21:56.262  4082  4082 V BluetoothAdapterState: isTurningOn()=false
08-30 10:21:56.262  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
08-30 10:21:56.262  4082  4082 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 10:21:56.262  4082  4082 D BluetoothMapService: cleanup()
,08-30 10:21:56.262  4082  4281 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-30 10:21:56.262  4082  4082 D BluetoothMapService: MAP Service closeService in
08-30 10:21:56.262  4082  4281 D BluetoothAdapterProperties: Setting state to 15
08-30 10:21:56.262  4082  4281 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-30 10:21:56.263  4082  4281 I BluetoothAdapterState: Entering BleOnState
08-30 10:21:56.263  4028  4038 D BluetoothPan: onBluetoothStateChange on: false
,08-30 10:21:56.264  1359  1371 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-30 10:21:56.264   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 10:21:56.265  4028  4039 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 10:21:56.266  1359  1371 D BluetoothMap: onBluetoothStateChange: up=false
08-30 10:21:56.266  1359  1359 D BluetoothPbap: Proxy object disconnected
,08-30 10:21:56.266  1359  1359 D PbapServerProfile: Bluetooth service disconnected
08-30 10:21:56.266   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 10:21:56.266  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 10:21:56.266  1359  2101 D BluetoothPbap: onBluetoothStateChange: up=false
,08-30 10:21:56.267  4028  4038 D BluetoothPbap: onBluetoothStateChange: up=false
,08-30 10:21:56.268  4028  4039 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 10:21:56.268  1359  1370 D BluetoothPan: onBluetoothStateChange on: false
08-30 10:21:56.268  4028  4038 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 10:21:56.271  1978  1991 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 10:21:56.272  4028  4038 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 10:21:56.274  1359  1371 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 10:21:56.275  1359  2101 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 10:21:56.276   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-30 10:21:56.276   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 10:21:56.278  4082  4281 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-30 10:21:56.279  4082  4281 D BluetoothAdapterProperties: Setting state to 16
08-30 10:21:56.279  4082  4281 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-30 10:21:56.279  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:56.280  4082  4281 D BluetoothAdapterProperties: onBleDisable
,08-30 10:21:56.281  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:56.282  4082  4285 D BluetoothAdapterProperties: Scan Mode:20
08-30 10:21:56.282  4082  4282 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-30 10:21:56.282  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:56.283  4082  4291 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-30 10:21:56.283  4082  4291 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-30 10:21:56.283  4082  4281 I BluetoothAdapterState: Entering PendingCommandState
08-30 10:21:56.284  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:56.285  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:21:56.285  4028  4028 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 10:21:56.286  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:21:56.291  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 10:21:56.295  4028  4028 D DockEventReceiver: finishStartingService: stopping service
,08-30 10:21:56.487  4082  4285 I bt_hci  : shut_down
,08-30 10:21:56.507  4082  4289 I bt_vendor: low_power_mode_cb
,08-30 10:21:56.523  4082  4289 D bt_hwcfg: hw_epilog_process
,08-30 10:21:56.531  4082  4289 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-30 10:21:56.531  4082  4289 I bt_vendor: epilog_cb
,08-30 10:21:56.531  4082  4289 I bt_hci  : epilog_finished_callback
,08-30 10:21:56.540  4082  4285 I bt_hci_h4: hal_close
,08-30 10:21:56.541  4082  4285 I bt_userial_vendor: device fd = 51 close
,08-30 10:21:56.657  4082  4282 D bt_stack_manager: event_shut_down_stack finished.
,08-30 10:21:56.658  4082  4281 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-30 10:21:56.667  4082  4082 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 10:21:56.666  4082  4281 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-30 10:21:56.668  4082  4082 D BtGatt.GattService: Received stop request...Stopping profile...
,08-30 10:21:56.668  4082  4082 D BtGatt.GattService: stop()
08-30 10:21:56.669  4082  4082 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 10:21:56.673  4082  4082 V BluetoothAdapterState: isTurningOff()=false
,08-30 10:21:56.674  4082  4082 V BluetoothAdapterState: isTurningOn()=false
,08-30 10:21:56.674  4082  4082 V BluetoothAdapterState: isBleTurningOn()=false
08-30 10:21:56.674  4082  4082 V BluetoothAdapterState: isBleTurningOff()=true
08-30 10:21:56.675  4082  4281 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-30 10:21:56.676  4082  4281 D BluetoothAdapterProperties: Setting state to 10
08-30 10:21:56.676  4082  4281 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-30 10:21:56.678  4082  4281 I BluetoothAdapterState: Entering OffState
,08-30 10:21:56.679   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-30 10:21:56.711  4082  4082 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-30 10:21:56.711  4082  4082 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-30 10:21:56.711  4082  4282 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-30 10:21:56.713  4082  4282 D bt_stack_manager: event_clean_up_stack finished.
,08-30 10:21:56.714  4082  4082 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 10:21:56.717  4082  4082 I art     : System.exit called, status: 0
,08-30 10:21:56.717  4082  4082 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 10:21:56.781   874   885 I ActivityManager: Process com.android.bluetooth (pid 4082) has died
,08-30 10:22:01.179  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:22:01.179  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:22:01.184  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 10:22:01.184  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8430db1 removed from the list
,08-30 10:22:01.185  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 10:22:01.185  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:22:01.185  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:22:01.188  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 10:22:01.189  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@99b2e17 added. We now have 4 listener(s)
08-30 10:22:01.189  3943  3993 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 10:22:01.191  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:01.191  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@99b2e17 removed from the list
08-30 10:22:01.191  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:22:01.192  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:01.192  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:01.194  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 10:22:01.195  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@be7d204 added. We now have 4 listener(s)
08-30 10:22:01.195  3943  3993 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 10:22:06.207  3943  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:22:06.254   874   891 I ActivityManager: Start proc 4328:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-30 10:22:06.397  4328  4328 D AdapterServiceConfig: Adding HeadsetService
,08-30 10:22:06.397  4328  4328 D AdapterServiceConfig: Adding A2dpService
,08-30 10:22:06.398  4328  4328 D AdapterServiceConfig: Adding HidService
,08-30 10:22:06.398  4328  4328 D AdapterServiceConfig: Adding HealthService
,08-30 10:22:06.398  4328  4328 D AdapterServiceConfig: Adding PanService
,08-30 10:22:06.398  4328  4328 D AdapterServiceConfig: Adding GattService
,08-30 10:22:06.398  4328  4328 D AdapterServiceConfig: Adding BluetoothMapService
,08-30 10:22:06.416   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@983ba2c:true
,08-30 10:22:06.416  4328  4328 D BluetoothAdapterState: make() - Creating AdapterState
,08-30 10:22:06.421  4328  4328 I bt_bluedroid: init
,08-30 10:22:06.421  4328  4340 I BluetoothAdapterState: Entering OffState
,08-30 10:22:06.428  4328  4341 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 10:22:06.428  4328  4341 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-30 10:22:06.428  4328  4341 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 10:22:06.429  4328  4341 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 10:22:06.431  4328  4328 I bt_bluedroid: get_profile_interface socket
,08-30 10:22:06.434  4328  4344 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-30 10:22:06.436  4328  4344 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 10:22:06.437  4328  4328 I bt_bluedroid: get_profile_interface sdp
,08-30 10:22:06.444  4328  4339 I bt_bluedroid: config_hci_snoop_log
,08-30 10:22:06.448   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-30 10:22:06.464  4328  4340 D BluetoothAdapterState: Current state: OFF, message: 0
08-30 10:22:06.465  4328  4340 D BluetoothAdapterProperties: Setting state to 14
,08-30 10:22:06.465  4328  4340 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-30 10:22:06.470  4328  4340 D BluetoothBondStateMachine: make
,08-30 10:22:06.479  4328  4345 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 10:22:06.486  4328  4340 I BluetoothAdapterState: Entering PendingCommandState
,08-30 10:22:06.489  4328  4328 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-30 10:22:06.498  4328  4328 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43bf881
,08-30 10:22:06.500  4328  4328 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 10:22:06.502  4328  4328 D BtGatt.GattService: Received start request. Starting profile...
,08-30 10:22:06.502  4328  4328 D BtGatt.GattService: start()
,08-30 10:22:06.503  4328  4328 I bt_bluedroid: get_profile_interface gatt
,08-30 10:22:06.505  4328  4328 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43bf881
,08-30 10:22:06.506  4328  4328 D BtGatt.AdvertiseManager: advertise manager created
,08-30 10:22:06.523  4328  4328 V BluetoothAdapterState: isTurningOff()=false
,08-30 10:22:06.523  4328  4328 V BluetoothAdapterState: isTurningOn()=false
,08-30 10:22:06.523  4328  4328 V BluetoothAdapterState: isBleTurningOn()=true
,08-30 10:22:06.523  4328  4328 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 10:22:06.526  4328  4340 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-30 10:22:06.527  4328  4340 I bt_bluedroid: enable
08-30 10:22:06.527  4328  4341 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-30 10:22:06.528  4328  4341 I bt_hci  : start_up
,08-30 10:22:06.549  4328  4341 I bt_vendor: alloc value 0xb3a25189
,08-30 10:22:06.549  4328  4341 I bt_vendor: init
08-30 10:22:06.549  4328  4341 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-30 10:22:06.550  4328  4341 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-30 10:22:06.661  4328  4341 D bt_hci  : start_up starting async portion
,08-30 10:22:06.662  4328  4348 I bt_hci  : event_finish_startup
,08-30 10:22:06.662  4328  4348 I bt_hci_h4: hal_open
,08-30 10:22:06.663  4328  4348 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-30 10:22:06.672  4328  4348 I bt_userial_vendor: device fd = 51 open
,08-30 10:22:06.699  4328  4348 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 10:22:06.731  4328  4348 D bt_hwcfg: Chipset BCM4354A2
,08-30 10:22:06.732  4328  4348 D bt_hwcfg: Target name = [BCM4354A2]
08-30 10:22:06.733  4328  4348 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-30 10:22:07.530  4328  4348 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-30 10:22:07.531  4328  4348 D bt_hwcfg: Settlement delay -- 100 ms
,08-30 10:22:07.532  4328  4348 I bt_hwcfg: Setting fw settlement delay to 100 
,08-30 10:22:07.648  4328  4348 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-30 10:22:07.649  4328  4348 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-30 10:22:07.679  4328  4348 I bt_hwcfg: vendor lib fwcfg completed
,08-30 10:22:07.680  4328  4348 I bt_vendor: firmware callback
,08-30 10:22:07.680  4328  4348 I bt_hci  : firmware_config_callback
,08-30 10:22:07.691  4328  4350 I bt_btu  : btu_task pending for preload complete event
,08-30 10:22:07.691  4328  4350 I bt_btu_task: Bluetooth chip preload is complete
08-30 10:22:07.692  4328  4350 I bt_btu  : btu_task received preload complete event
,08-30 10:22:07.704  4328  4350 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 10:22:07.704  4328  4350 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 10:22:07.705  4328  4350 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-30 10:22:07.705  4328  4350 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-30 10:22:07.705  4328  4350 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 10:22:07.706  4328  4350 I         : BTE_InitTraceLevels -- TRC_A2D
,08-30 10:22:07.706  4328  4350 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 10:22:07.706  4328  4350 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 10:22:07.706  4328  4350 I         : BTE_InitTraceLevels -- TRC_GAP
,08-30 10:22:07.706  4328  4350 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 10:22:07.707  4328  4350 I         : BTE_InitTraceLevels -- TRC_SDP
,08-30 10:22:07.707  4328  4350 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 10:22:07.707  4328  4350 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 10:22:07.708  4328  4350 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-30 10:22:07.708  4328  4350 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 10:22:07.846  4328  4350 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39a2d9d
,08-30 10:22:07.847  4328  4350 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39a2d9d 
,08-30 10:22:07.853  4328  4344 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-30 10:22:07.855  4328  4344 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-30 10:22:07.856  4328  4344 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-30 10:22:07.859  4328  4344 D BluetoothAdapterProperties: Name is: Nexus 6
,08-30 10:22:07.866  4328  4344 D BluetoothAdapterProperties: Scan Mode:20
08-30 10:22:07.866  4328  4344 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 10:22:07.868  4328  4344 D bt_hci  : do_postload posting postload work item
08-30 10:22:07.868  4328  4348 I bt_hci  : event_postload
08-30 10:22:07.869  4328  4348 I bt_vendor: sco_config_cb
08-30 10:22:07.869  4328  4348 I bt_hci  : sco_config_callback postload finished.
08-30 10:22:07.874  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:22:07.874  4328  4344 D bt_bte_conf: Device ID record 1 : primary
08-30 10:22:07.874  4328  4344 D bt_bte_conf:   vendorId            = 000f
08-30 10:22:07.874  4328  4344 D bt_bte_conf:   vendorIdSource      = 0001
08-30 10:22:07.875  4328  4344 D bt_bte_conf:   product             = 1200
08-30 10:22:07.875  4328  4344 D bt_bte_conf:   version             = 1436
08-30 10:22:07.875  4328  4344 D bt_bte_conf:   clientExecutableURL = 
08-30 10:22:07.875  4328  4344 D bt_bte_conf:   serviceDescription  = 
08-30 10:22:07.876  4328  4344 D bt_bte_conf:   documentationURL    = 
08-30 10:22:07.876  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:22:07.876  4328  4344 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-30 10:22:07.876  4328  4341 D bt_stack_manager: event_start_up_stack finished
08-30 10:22:07.876  4328  4348 I bt_vendor: low_power_mode_cb
08-30 10:22:07.877  4328  4340 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-30 10:22:07.877  4328  4340 D BluetoothAdapterProperties: Setting state to 15
08-30 10:22:07.877  4328  4340 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-30 10:22:07.878  4328  4340 I BluetoothAdapterState: Entering BleOnState
08-30 10:22:07.882  4328  4340 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-30 10:22:07.882  4328  4340 D BluetoothAdapterProperties: Setting state to 11
08-30 10:22:07.882  4328  4340 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-30 10:22:07.887  4328  4328 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43bf881
08-30 10:22:07.889  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:22:07.889  4328  4328 D HeadsetService: Received start request. Starting profile...
08-30 10:22:07.892  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:22:07.897  4328  4328 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 10:22:07.898  4328  4328 D HeadsetStateMachine: make
08-30 10:22:07.903  4328  4340 I BluetoothAdapterState: Entering PendingCommandState
08-30 10:22:07.910  4328  4328 D HeadsetStateMachine: max_hf_connections = 1
08-30 10:22:07.910  4328  4328 I bt_bluedroid: get_profile_interface handsfree
08-30 10:22:07.910  4328  4344 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-30 10:22:07.911  4328  4344 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-30 10:22:07.917  4328  4328 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43bf881
08-30 10:22:07.917  4328  4328 D A2dpService: Received start request. Starting profile...
08-30 10:22:07.918  4328  4328 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 10:22:07.919  4328  4328 I bt_bluedroid: get_profile_interface avrcp
08-30 10:22:07.928  4328  4328 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-30 10:22:07.928  4328  4328 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 10:22:07.928  4328  4328 D A2dpStateMachine: make
,08-30 10:22:07.931  4328  4328 I bt_bluedroid: get_profile_interface a2dp
,08-30 10:22:07.931  4328  4344 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-30 10:22:07.934  4328  4359 D A2dpStateMachine: Enter Disconnected: -2
08-30 10:22:07.934  4328  4328 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 10:22:07.935  4328  4328 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43bf881
08-30 10:22:07.936  4328  4328 D HidService: Received start request. Starting profile...
,08-30 10:22:07.936  4328  4328 I bt_bluedroid: get_profile_interface hidhost
,08-30 10:22:07.937  4328  4328 D HidService: setHidService(): set to: null
08-30 10:22:07.937  4328  4344 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39843e5
,08-30 10:22:07.937  4328  4344 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-30 10:22:07.939  4328  4328 I BluetoothHealthServiceJni: classInitNative: succeeds
08-30 10:22:07.940  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-30 10:22:07.940  4328  4328 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43bf881
08-30 10:22:07.940  4328  4328 D HealthService: Received start request. Starting profile...
,08-30 10:22:07.941  4328  4328 I bt_bluedroid: get_profile_interface health
08-30 10:22:07.942  4328  4328 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 10:22:07.943  4328  4328 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43bf881
08-30 10:22:07.943  4328  4328 D PanService: Received start request. Starting profile...
,08-30 10:22:07.944  4328  4328 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-30 10:22:07.944  4328  4328 I bt_bluedroid: get_profile_interface pan
,08-30 10:22:07.945  4328  4344 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 10:22:07.950  4328  4328 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43bf881
,08-30 10:22:07.951  4328  4328 D BluetoothMapService: Received start request. Starting profile...
08-30 10:22:07.951  4328  4328 D BluetoothMapService: start()
,08-30 10:22:07.953  4328  4328 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-30 10:22:07.954  4328  4328 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-30 10:22:07.954  4328  4328 D BluetoothMapAppObserver: createReceiver()
08-30 10:22:07.955  4328  4328 D BluetoothMapAppObserver: initObservers()
,08-30 10:22:07.955  4328  4328 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-30 10:22:07.962  4328  4328 V BluetoothAdapterState: isTurningOff()=false
,08-30 10:22:07.962  4328  4328 V BluetoothAdapterState: isTurningOn()=true
08-30 10:22:07.962  4328  4328 V BluetoothAdapterState: isBleTurningOn()=false
08-30 10:22:07.962  4328  4328 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 10:22:07.962  4328  4357 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-30 10:22:07.963  4328  4328 V BluetoothAdapterState: isTurningOff()=false
,08-30 10:22:07.963  4328  4328 V BluetoothAdapterState: isTurningOn()=true
08-30 10:22:07.963  4328  4328 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 10:22:07.964  4328  4328 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 10:22:07.964  4328  4328 V BluetoothAdapterState: isTurningOff()=false
,08-30 10:22:07.964  4328  4328 V BluetoothAdapterState: isTurningOn()=true
08-30 10:22:07.964  4328  4328 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 10:22:07.964  4328  4328 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 10:22:07.964  4328  4328 V BluetoothAdapterState: isTurningOff()=false
08-30 10:22:07.964  4328  4328 V BluetoothAdapterState: isTurningOn()=true
,08-30 10:22:07.965  4328  4328 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 10:22:07.965  4328  4328 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 10:22:07.965  4328  4328 V BluetoothAdapterState: isTurningOff()=false
,08-30 10:22:07.965  4328  4328 V BluetoothAdapterState: isTurningOn()=true
,08-30 10:22:07.965  4328  4328 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 10:22:07.965  4328  4328 V BluetoothAdapterState: isBleTurningOff()=false
,08-30 10:22:07.965  4328  4328 V BluetoothAdapterState: isTurningOff()=false
,08-30 10:22:07.965  4328  4328 V BluetoothAdapterState: isTurningOn()=true
,08-30 10:22:07.965  4328  4328 V BluetoothAdapterState: isBleTurningOn()=false
,08-30 10:22:07.965  4328  4328 V BluetoothAdapterState: isBleTurningOff()=false
08-30 10:22:07.966  4328  4340 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-30 10:22:07.966  4328  4340 D BluetoothAdapterProperties: ScanMode =  20
,08-30 10:22:07.966  4328  4340 D BluetoothAdapterProperties: State =  11
08-30 10:22:07.966  4328  4340 D BluetoothAdapterProperties: Setting state to 12
,08-30 10:22:07.966  4328  4340 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 10:22:07.967  4028  4321 D BluetoothPan: onBluetoothStateChange on: true
,08-30 10:22:07.967  4328  4344 D BluetoothAdapterProperties: Scan Mode:21
,08-30 10:22:07.967  4328  4344 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 10:22:07.968  4328  4340 I BluetoothAdapterState: Entering OnState
,08-30 10:22:07.971  1359  2101 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 10:22:07.972   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 10:22:07.972  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:22:07.972  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:07.972  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:22:07.972  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:22:07.972  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:07.972  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:22:07.972  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:22:07.972  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 10:22:07.972  4028  4038 D BluetoothMap: onBluetoothStateChange: up=true
08-30 10:22:07.974  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:22:07.974  1359  1371 D BluetoothMap: onBluetoothStateChange: up=true,
08-30 10:22:07.976   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 10:22:07.976  1359  1359 D BluetoothMap: Proxy object connected
08-30 10:22:07.976  1359  1359 D MapProfile: Bluetooth service connected
08-30 10:22:07.976  1359  1359 D BluetoothMap: getConnectedDevices()
,08-30 10:22:07.976  1359  2101 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 10:22:07.977  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:22:07.977  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:07.977  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:22:07.977  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:22:07.977  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:07.977  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:22:07.977  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:22:07.977  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 10:22:07.978  4028  4039 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 10:22:07.978  4028  4028 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 10:22:07.978  4028  4028 D PanProfile: Bluetooth service connected
08-30 10:22:07.978  4028  4028 D BluetoothMap: Proxy object connected
08-30 10:22:07.978  4028  4028 D MapProfile: Bluetooth service connected
08-30 10:22:07.978  4028  4028 D BluetoothMap: getConnectedDevices()
,08-30 10:22:07.980  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 10:22:07.980  4028  4038 D BluetoothHeadset: onBluetoothStateChange: up=true
08-30 10:22:07.980  1359  1370 D BluetoothPan: onBluetoothStateChange on: true
,08-30 10:22:07.981  4328  4328 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 10:22:07.982  4328  4328 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-30 10:22:07.983  4328  4328 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 10:22:07.984  1359  1359 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 10:22:07.984  1359  1359 D PanProfile: Bluetooth service connected
,08-30 10:22:07.984  4028  4321 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 10:22:07.985  4328  4328 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 10:22:07.986  1978  1992 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 10:22:07.986  4328  4328 D ObexServerSockets: Succeed to create listening sockets 
08-30 10:22:07.986  4328  4328 D ObexServerSockets0: startAccept()
,08-30 10:22:07.986  4328  4328 D ObexServerSockets0: prepareForNewConnect()
08-30 10:22:07.987  4028  4039 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 10:22:07.989  4328  4328 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-30 10:22:07.989  1359  2101 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-30 10:22:07.989  4328  4328 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-30 10:22:07.990  4328  4365 D ObexServerSockets0: Accepting socket connection...
08-30 10:22:07.990  4328  4366 D ObexServerSockets0: Accepting socket connection...
08-30 10:22:07.991  1359  1359 D BluetoothInputDevice: Proxy object connected
08-30 10:22:07.991  1359  1359 D HidProfile: Bluetooth service connected
08-30 10:22:07.991  1359  1371 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 10:22:07.993  1359  1359 D BluetoothA2dp: Proxy object connected
08-30 10:22:07.993   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-30 10:22:07.993   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 10:22:07.993  4028  4028 D BluetoothA2dp: Proxy object connected
,08-30 10:22:07.994   874   874 D BluetoothA2dp: Proxy object connected
,08-30 10:22:07.997  4328  4328 D BluetoothMapService: onReceive
,08-30 10:22:07.997  4328  4328 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-30 10:22:07.997  4328  4328 D BluetoothMapService: STATE_ON
08-30 10:22:07.998  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:22:07.999  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:22:08.000   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 10:22:08.004  4028  4028 D BluetoothInputDevice: Proxy object connected
,08-30 10:22:08.004  4028  4028 D HidProfile: Bluetooth service connected
,08-30 10:22:08.009  4028  4028 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 10:22:08.016  1497  1497 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-30 10:22:08.016  4028  4028 D DockEventReceiver: finishStartingService: stopping service
,08-30 10:22:08.025  4028  4028 D BluetoothPbap: Proxy object connected
,08-30 10:22:08.025  4028  4028 D PbapServerProfile: Bluetooth service connected
08-30 10:22:08.025  1359  1359 D BluetoothPbap: Proxy object connected
08-30 10:22:08.025  1359  1359 D PbapServerProfile: Bluetooth service connected
08-30 10:22:08.026  4328  4328 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-30 10:22:08.026  4328  4328 D ObexServerSockets0: prepareForNewConnect()
,08-30 10:22:08.036  4328  4372 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 10:22:08.051  4328  4376 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 10:22:08.053  4328  4376 I BtOppRfcommListener: Accept thread started.
,08-30 10:22:08.073  1359  1370 D BluetoothHeadset: Proxy object connected
,08-30 10:22:08.074   874   874 D BluetoothHeadset: Proxy object connected
,08-30 10:22:08.074   874   874 D BluetoothHeadset: Proxy object connected
08-30 10:22:08.074  1359  1359 D HeadsetProfile: Bluetooth service connected
08-30 10:22:08.074  4028  4038 D BluetoothHeadset: Proxy object connected
08-30 10:22:08.074   874   874 D BluetoothHeadset: Proxy object connected
,08-30 10:22:08.075  4028  4028 D HeadsetProfile: Bluetooth service connected
08-30 10:22:08.075  1978  2291 D BluetoothHeadset: Proxy object connected
08-30 10:22:08.076   874   891 D BluetoothHeadset: Proxy object connected
,08-30 10:22:08.080  4028  4321 D BluetoothHeadset: Proxy object connected
,08-30 10:22:08.080  4028  4028 D HeadsetProfile: Bluetooth service connected
,08-30 10:22:08.088  1978  2070 D BluetoothHeadset: Proxy object connected
,08-30 10:22:08.093   874   891 D BluetoothHeadset: Proxy object connected
,08-30 10:22:11.227  3943  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:22:11.227  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:11.227  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:22:11.227  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 10:22:11.227  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:11.227  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:22:11.227  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:22:11.227  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 10:22:11.234  3943  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 10:22:11.236  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 10:22:11.236  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@be7d204 removed from the list
08-30 10:22:11.237  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 10:22:11.237  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:11.237  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:22:11.240  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 10:22:11.240  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6c9d3ed added. We now have 4 listener(s)
08-30 10:22:11.241  3943  3993 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 10:22:11.245   874  1688 D WifiService: setWifiEnabled: false pid=3943, uid=10000
,08-30 10:22:11.245   874  1688 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 10:22:16.258  3943  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:22:16.259   874  1998 D WifiService: setWifiEnabled: true pid=3943, uid=10000
,08-30 10:22:16.260   874  1998 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-30 10:22:16.271   874  1302 D WifiConfigStore: Loading config and enabling all networks 
,08-30 10:22:16.290  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:22:16.290  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:16.290  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:22:16.290  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:22:16.290  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:16.290  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:22:16.290  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:22:16.290  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 10:22:16.294  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 10:22:16.298  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:22:16.298  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:16.298  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:22:16.298  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:22:16.298  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:16.298  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 10:22:16.298  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 10:22:16.298  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 10:22:16.301  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 10:22:16.302   874  1302 D WifiConfigStore: loaded 0 passpoint configs
,08-30 10:22:16.303   874  1302 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-30 10:22:16.303   874  1302 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-30 10:22:16.304   874  1302 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-30 10:22:16.305   874  1302 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-30 10:22:16.305   874  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-30 10:22:16.305   874  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-30 10:22:16.316   874  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 10:22:16.316   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-30 10:22:16.323   372   872 D CommandListener: Setting iface cfg
,08-30 10:22:16.368   874  1301 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '156 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 156 Failed to set address (No such device)'
,08-30 10:22:16.368   874  1301 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 10:22:16.378   874  1301 D WifiNative-HAL: p2pGetDeviceAddress
08-30 10:22:16.379   874  1302 E native  : do suspend true
,08-30 10:22:16.380   874  1301 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-30 10:22:16.437   874  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 10:22:17.817   874  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-30 10:22:17.965   874  1302 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.31 rxSuccessRate=5.88 delta 1000 -> 994
,08-30 10:22:17.966   874  1302 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-30 10:22:17.967   874  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 10:22:17.984   874  1302 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-30 10:22:18.054   874  1302 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-30 10:22:18.057  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-30 10:22:18.520  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-30 10:22:18.585  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-30 10:22:18.588  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-30 10:22:18.594   874  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-30 10:22:18.610   874  1302 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 10:22:18.610   874  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 10:22:18.610   874  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-30 10:22:18.627   874  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 10:22:18.640   372   872 D CommandListener: Setting iface cfg
08-30 10:22:18.641   874  1302 D WifiStateMachine: Start Dhcp Watchdog 3
,08-30 10:22:18.650   874  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-30 10:22:18.698   874  4386 D DhcpClient: Receive thread started
,08-30 10:22:18.799   874  1302 E native  : do suspend false
,08-30 10:22:18.828   874  2121 D DhcpClient: Broadcasting DHCPDISCOVER
,08-30 10:22:18.843   874  4386 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,08-30 10:22:18.845   874  2121 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,08-30 10:22:18.848   874  2121 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-30 10:22:18.869   874  4386 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-30 10:22:18.871   874  2121 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-30 10:22:18.876   372   872 D CommandListener: Setting iface cfg
,08-30 10:22:18.888   874  2121 D DhcpClient: Scheduling renewal in 86399s
,08-30 10:22:18.888   874  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-30 10:22:18.892   874  1302 E native  : do suspend true
,08-30 10:22:18.929   874  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-30 10:22:18.934   874  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,08-30 10:22:18.936   874  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-30 10:22:18.938   874  1304 D ConnectivityService: Adding iface wlan0 to network 102
,08-30 10:22:18.949   874  1302 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 10:22:19.020   874  1304 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-30 10:22:19.020   874  1304 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-30 10:22:19.021   874  1304 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-30 10:22:19.024   874  1304 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-30 10:22:19.027   874  1304 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-30 10:22:19.042   874  1304 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 10:22:19.050   874  1304 D ConnectivityService: scheduleUnvalidatedPrompt 102
08-30 10:22:19.051   874  1304 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-30 10:22:19.051   874  1304 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-30 10:22:19.051   874  1304 D ConnectivityService:    accepting network in place of null
,08-30 10:22:19.051   874  1302 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-30 10:22:19.052   874  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-30 10:22:19.053   874  1304 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-30 10:22:19.076   874  4385 D NetlinkSocketObserver: NeighborEvent{elapsedMs=211420, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-30 10:22:19.088   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 10:22:19.123   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-30 10:22:19.133   874  1304 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-30 10:22:19.133   874  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:22:19.143   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-30 10:22:19.140   874  1304 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-30 10:22:19.145   874  4384 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
08-30 10:22:19.166  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:22:19.166  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:19.166  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:22:19.166  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:22:19.166  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:19.166  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:19.166  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:22:19.166  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:22:19.171  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 10:22:19.171  1690  1690 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-30 10:22:19.177  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:22:19.177  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:19.177  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:22:19.177  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:22:19.177  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:19.177  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:19.177  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:22:19.177  3943  3943 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:22:19.180  3943  3943 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 10:22:19.183  1690  1690 D SystemUpdateService: onCreate
,08-30 10:22:19.190  1690  1690 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-30 10:22:19.200  1690  4395 I SystemUpdateService: active receiver: enabled
,08-30 10:22:19.206  3898  4396 I BooksSync: Starting books sync for 61035162, extras: ade
,08-30 10:22:19.211  1690  1690 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-30 10:22:19.213  1690  2510 I iu.UploadsManager: num queued entries: 0
,08-30 10:22:19.214  1690  2510 I iu.UploadsManager: num updated entries: 0
08-30 10:22:19.214  1690  2510 I iu.SyncManager: NEXT; no task
,08-30 10:22:19.219  1690  4395 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-30 10:22:19.221  1690  1690 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-30 10:22:19.222  1690  1690 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-30 10:22:19.224  4096  4096 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-30 10:22:19.227   874  4384 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 08:22:19 GMT], X-Android-Received-Millis=[1472545339227], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472545339186]}
,08-30 10:22:19.228   874  1304 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-30 10:22:19.228   874  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-30 10:22:19.228   874  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-30 10:22:19.228  1690  4398 I MDM     : [188] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-30 10:22:19.229  1690  4398 W BaseAppContext: Using Auth Proxy for data requests.
08-30 10:22:19.231   874  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-30 10:22:19.231  4096  4096 D SprintDMHelper: simOperator: 
,08-30 10:22:19.231  4096  4096 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-30 10:22:19.236  1690  4398 V GoogleAuthProtoRequest: [188] a.<init>: mAccountName set to: thalitester@gmail.com
,08-30 10:22:19.237  1690  4395 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-30 10:22:19.237  1690  4395 I SystemUpdateService: now status is 0 (complete)
08-30 10:22:19.237  1690  4395 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-30 10:22:19.237  1690  4395 I SystemUpdateService: file has been verified
,08-30 10:22:19.244  1690  4395 I SystemUpdateService: OTA package size = 12249756
,08-30 10:22:19.245  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 10:22:19.246  1497  1497 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-30 10:22:19.283  1690  4395 I SystemUpdateService: showing system update notification
,08-30 10:22:19.303  3898  4406 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-30 10:22:19.337  1690  1690 D SystemUpdateService: onDestroy
,08-30 10:22:19.341  1497  2293 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-30 10:22:19.341  1497  2293 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-30 10:22:19.341  1497  2293 I GLSUser : [GLSUser] Extracting token using key: Auth
08-30 10:22:19.341  1497  2293 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 10:22:19.342  1497  3153 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 10:22:19.342  1497  3153 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-30 10:22:19.342  1497  3153 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 10:22:19.342  1497  3153 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 10:22:19.411  1497  3152 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-30 10:22:19.411  1497  3152 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-30 10:22:19.411  1497  3152 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-30 10:22:19.411  1497  3152 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-30 10:22:19.416  3631  4402 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-30 10:22:19.428  3898  4406 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 10:22:19.429  3898  4396 E BooksSync: Soft error
08-30 10:22:19.429  3898  4396 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 10:22:19.429  3898  4396 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-30 10:22:19.429  3898  4396 E BooksSync: Sync error
08-30 10:22:19.429  3898  4396 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-30 10:22:19.429  3898  4396 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-30 10:22:19.429  3898  4396 I BooksSync: Finished books sync
,08-30 10:22:19.435  1690  4398 E MDM     : [188] SitrepService.a: Error sending sitrep.
,08-30 10:22:19.444   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 207193, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-30 10:22:20.132   874  1304 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-30 10:22:20.746  1887  1941 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-30 10:22:20.746  1887  1941 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-30 10:22:20.777  1497  1497 I ConfigService: onCreate
,08-30 10:22:21.285  3943  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 10:22:21.285  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:21.285  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:22:21.285  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:22:21.285  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:21.285  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:21.285  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:22:21.285  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:22:21.292  3943  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 10:22:21.293  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 10:22:21.294  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6c9d3ed removed from the list
,08-30 10:22:21.294  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 10:22:21.294  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:21.294  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:22:21.306  3943  4411 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-30 10:22:21.307  3943  4411 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 10:22:24.316  3943  4413 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-30 10:22:24.317  3943  4411 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-30 10:22:24.320  3943  4411 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-30 10:22:24.320  3943  4413 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-30 10:22:24.321  3943  4411 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 10:22:24.322  3943  4413 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 10:22:24.324  3943  4411 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 10:22:24.324  3943  4413 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 10:22:24.324  3943  4411 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-30 10:22:24.328  3943  4415 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 459, name: IncomingSocketThread/Sender)
,08-30 10:22:24.329  3943  4416 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 458, name: OutgoingSocketThread/Sender)
,08-30 10:22:24.330  3943  4413 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-30 10:22:24.334  3943  4417 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 460, name: OutgoingSocketThread/Receiver)
,08-30 10:22:24.335  3943  4418 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 461, name: IncomingSocketThread/Receiver)
,08-30 10:22:24.336  3943  4417 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 460, thread name: OutgoingSocketThread/Receiver)
08-30 10:22:24.336  3943  4417 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 10:22:24.336  3943  4417 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 460, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-30 10:22:24.336  3943  4418 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 461, thread name: IncomingSocketThread/Receiver)
,08-30 10:22:24.336  3943  4418 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-30 10:22:24.336  3943  4418 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 461, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-30 10:22:25.852  1497  1497 I ConfigService: onDestroy
,08-30 10:22:27.058   874  1304 D ConnectivityService: handlePromptUnvalidated 102
,08-30 10:22:27.314  3943  3993 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 10:22:27.316  3943  3993 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 10:22:27.324  3943  3993 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@fae9bbd Bundle[{}]
08-30 10:22:27.325  3943  3993 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 10:22:27.325  3943  3993 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-30 10:22:27.326  3943  3993 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-30 10:22:27.326  3943  3993 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-30 10:22:27.327  3943  3993 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-30 10:22:27.327  3943  3993 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 10:22:27.331  3943  3993 I System.out: Running OutgoingSocketThread
,08-30 10:22:27.335  3943  4419 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-30 10:22:27.335  3943  4419 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 10:22:30.346  3943  4419 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-30 10:22:30.346  3943  4419 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-30 10:22:30.346  3943  4420 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-30 10:22:30.347  3943  4420 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-30 10:22:30.347  3943  4419 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 10:22:30.347  3943  4420 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 10:22:30.350  3943  4419 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-30 10:22:30.350  3943  4420 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 10:22:30.353  3943  4422 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 470, name: OutgoingSocketThread/Sender)
08-30 10:22:30.355  3943  4420 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-30 10:22:30.356  3943  4419 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-30 10:22:30.359  3943  4423 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 471, name: IncomingSocketThread/Sender)
08-30 10:22:30.360  3943  4424 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 473, name: IncomingSocketThread/Receiver)
08-30 10:22:30.361  3943  4424 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 473, thread name: IncomingSocketThread/Receiver)
08-30 10:22:30.362  3943  4424 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-30 10:22:30.362  3943  4424 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 473, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-30 10:22:30.363  3943  4425 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 472, name: OutgoingSocketThread/Receiver)
08-30 10:22:30.364  3943  4425 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 472, thread name: OutgoingSocketThread/Receiver)
08-30 10:22:30.364  3943  4425 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-30 10:22:30.364  3943  4425 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 472, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-30 10:22:33.346  3943  3993 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 482)
,08-30 10:22:33.349  3943  3993 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 10:22:33.349  3943  3993 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 483)
,08-30 10:22:33.355  3943  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 10:22:33.355  3943  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8cfa222 added. We now have 3 listener(s)
08-30 10:22:33.357  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 10:22:33.357  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 10:22:33.357  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 10:22:33.358  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 10:22:33.358  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1a94b3 added. We now have 4 listener(s)
08-30 10:22:33.358  3943  3993 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 10:22:33.358  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 10:22:33.367  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 10:22:33.380  3943  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:22:33.380  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:33.380  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:22:33.380  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:22:33.380  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:33.380  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:33.380  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:22:33.380  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:22:33.386  3943  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 10:22:33.387  3943  3993 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 10:22:33.387  3943  3993 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 10:22:33.388  3943  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 10:22:33.388  3943  3993 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 10:22:33.388  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 10:22:33.388  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:33.388  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 10:22:33.388  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 10:22:33.388  3943  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8cfa222 removed from the list
08-30 10:22:33.388  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:33.388  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1a94b3 removed from the list
08-30 10:22:33.391  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:22:33.398  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:22:33.399  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 10:22:33.399  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:33.399  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:33.399  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:33.401  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 10:22:33.401  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 10:22:33.401  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:33.401  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1a94b3 not in the list
08-30 10:22:33.401  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:33.401  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:33.403  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 10:22:33.403  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 10:22:33.403  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:33.403  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1a94b3 not in the list
,08-30 10:22:33.403  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:22:33.403  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:33.403  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:22:33.403  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8cfa222 not in the list
08-30 10:22:33.404  3943  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 10:22:33.404  3943  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77cc1e9 added. We now have 3 listener(s)
08-30 10:22:33.406  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 10:22:33.406  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 10:22:33.406  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 10:22:33.406  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 10:22:33.406  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@669be6e added. We now have 4 listener(s)
08-30 10:22:33.406  3943  3993 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 10:22:33.407  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 10:22:33.410  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 10:22:33.418  3943  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:22:33.418  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:33.418  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:22:33.418  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:22:33.418  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:33.418  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:33.418  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:22:33.418  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:22:33.423  3943  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:33.424  3943  3993 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 10:22:33.424  3943  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 10:22:33.424  3943  3993 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 10:22:33.424  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 10:22:33.424  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 10:22:33.424  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 10:22:33.428  3943  3993 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 10:22:33.428  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 10:22:33.431  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:22:33.435  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 10:22:33.436  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 10:22:33.436  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 10:22:33.437  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:22:33.443  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 10:22:33.444  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 10:22:33.444  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 10:22:33.446  3943  3993 D BluetoothAdapter: STATE_ON
,08-30 10:22:33.449  4328  4356 D BtGatt.GattService: registerClient() - UUID=5be6e4e1-5de1-4486-9c4b-5f8e6b43b38d
,08-30 10:22:33.451  4328  4344 D BtGatt.GattService: onClientRegistered() - UUID=5be6e4e1-5de1-4486-9c4b-5f8e6b43b38d, clientIf=5
,08-30 10:22:33.452  3943  3953 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-30 10:22:33.456  4328  4368 D BtGatt.GattService: start scan with filters
,08-30 10:22:33.467  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 10:22:33.467  4328  4347 D BtGatt.ScanManager: handling starting scan
,08-30 10:22:33.467  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 10:22:33.468  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 10:22:33.468  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 10:22:33.471  4328  4347 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43bf881
,08-30 10:22:33.478  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 10:22:33.478  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 10:22:33.479  3943  3943 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 10:22:33.484  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 10:22:33.485  4328  4344 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-30 10:22:33.485  4328  4344 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 10:22:33.487  4328  4347 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 10:22:33.491  3943  3993 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 10:22:33.492  3943  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 10:22:33.492  3943  3993 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 10:22:33.492  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:22:33.492  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-30 10:22:33.493  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-30 10:22:33.493  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 10:22:33.495  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 10:22:33.496  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 10:22:33.496  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 10:22:33.496  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 10:22:33.498  3943  3993 D BluetoothAdapter: STATE_ON
08-30 10:22:33.500  4328  4344 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-30 10:22:33.501  4328  4344 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 10:22:33.501  4328  4356 D BtGatt.GattService: stopScan() - queue size =1
,08-30 10:22:33.502  4328  4368 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 10:22:33.502  4328  4347 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 10:22:33.503  4328  4347 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-30 10:22:33.503  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 10:22:33.503  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 10:22:33.503  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 10:22:33.504  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 10:22:33.504  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 10:22:33.507  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 10:22:33.508  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 10:22:33.508  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 10:22:33.508  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 10:22:33.509  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 10:22:33.510  3943  3943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 10:22:33.511  3943  3943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-30 10:22:33.511  3943  3943 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 10:22:33.523  4328  4344 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 10:22:33.524  4328  4344 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 10:22:33.532  4328  4344 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 10:22:33.532  4328  4344 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 10:22:33.547  4328  4344 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-30 10:22:33.547  4328  4344 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 10:22:33.547  4328  4347 D BtGatt.ScanManager: stopping BLe Batch
,08-30 10:22:33.558  4328  4344 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-30 10:22:33.558  4328  4344 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 10:22:33.559  4328  4347 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 10:22:33.577  4328  4344 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-30 10:22:33.577  4328  4344 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 10:22:34.013  3943  3943 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 10:22:34.013  3943  3943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 10:22:34.014  3943  3943 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 10:22:36.511  3943  3993 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 10:22:36.512  3943  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 10:22:36.512  3943  3993 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 10:22:36.513  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:22:36.513  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:22:36.514  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 10:22:36.514  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 10:22:36.515  3943  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77cc1e9 removed from the list
08-30 10:22:36.515  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:36.516  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@669be6e removed from the list
,08-30 10:22:36.516  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:22:36.516  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:36.518  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:36.519  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:22:36.523  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 10:22:36.523  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 10:22:36.524  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:36.525  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@669be6e not in the list
08-30 10:22:36.526  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:22:36.526  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:22:36.531  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 10:22:36.531  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 10:22:36.531  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:36.532  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@669be6e not in the list
08-30 10:22:36.532  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:22:36.532  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:36.532  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:36.533  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@77cc1e9 not in the list
08-30 10:22:36.534  3943  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 10:22:36.534  3943  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99e72b added. We now have 3 listener(s)
,08-30 10:22:36.539  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-30 10:22:36.539  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 10:22:36.539  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 10:22:36.540  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 10:22:36.540  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f38b788 added. We now have 4 listener(s)
08-30 10:22:36.540  3943  3993 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 10:22:36.541  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 10:22:36.547  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 10:22:36.555  3943  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:22:36.555  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:36.555  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:22:36.555  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:22:36.555  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:36.555  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:36.555  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:22:36.555  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:22:36.559  3943  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 10:22:36.560  3943  3993 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 10:22:36.560  3943  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 10:22:36.561  3943  3993 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
,08-30 10:22:36.561  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
08-30 10:22:36.561  3943  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-30 10:22:36.562  3943  3993 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-30 10:22:36.562  3943  3993 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 10:22:36.562  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 10:22:36.563  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-30 10:22:36.564  3943  3993 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-30 10:22:36.564  3943  3993 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-30 10:22:36.564  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-30 10:22:36.564  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,08-30 10:22:36.565  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 10:22:36.565  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 10:22:36.567  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:22:36.570  3943  4426 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 10:22:36.571  3943  3993 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-30 10:22:36.571  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 10:22:36.574  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:22:36.574  3943  3943 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-30 10:22:36.576  3943  4426 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-30 10:22:36.578  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 10:22:36.579  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-30 10:22:36.579  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,08-30 10:22:36.583  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-30 10:22:36.583  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 10:22:36.583  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 F8 CF C5 D9 E5 61
08-30 10:22:36.584  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 10:22:36.584  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-30 10:22:36.584  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-30 10:22:36.585  3943  3993 D BluetoothAdapter: STATE_ON
,08-30 10:22:36.590  4328  4368 D BtGatt.GattService: registerClient() - UUID=1a4fafca-dd6b-451c-bed5-415f55a7593b
,08-30 10:22:36.590  4328  4344 D BtGatt.GattService: onClientRegistered() - UUID=1a4fafca-dd6b-451c-bed5-415f55a7593b, clientIf=5
,08-30 10:22:36.591  3943  3955 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-30 10:22:36.594  4328  4346 D BtGatt.AdvertiseManager: message : 0
,08-30 10:22:36.598  4328  4346 D BtGatt.AdvertiseManager: starting multi advertising
,08-30 10:22:36.611  4328  4344 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-30 10:22:36.622  4328  4344 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-30 10:22:36.623  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-30 10:22:36.624  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 10:22:36.629  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 10:22:36.632  3943  3943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-30 10:22:36.633  3943  3943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-30 10:22:36.633  3943  3943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-30 10:22:36.633  3943  3943 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-30 10:22:36.633  3943  3943 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,08-30 10:22:36.634  3943  3943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-30 10:22:36.639  3943  3943 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-30 10:22:36.639  3943  3943 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
08-30 10:22:36.640  3943  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything,
08-30 10:22:36.641  3943  3993 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 10:22:37.141  3943  3943 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-30 10:22:39.642  3943  3993 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 10:22:39.643  3943  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-30 10:22:39.643  3943  3993 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 10:22:39.644  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-30 10:22:39.644  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 10:22:39.644  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 10:22:39.648  3943  4426 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-30 10:22:39.648  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-30 10:22:39.649  3943  4426 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 10:22:39.649  3943  3993 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 10:22:39.649  3943  4426 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-30 10:22:39.649  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 10:22:39.649  3943  3943 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 10:22:39.649  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 10:22:39.650  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 10:22:39.650  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 10:22:39.650  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 10:22:39.656  3943  3993 D BluetoothAdapter: STATE_ON
08-30 10:22:39.656  3943  3993 D BluetoothLeScanner: could not find callback wrapper
,08-30 10:22:39.657  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 10:22:39.657  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-30 10:22:39.659  4328  4346 D BtGatt.AdvertiseManager: message : 1
,08-30 10:22:39.661  4328  4346 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-30 10:22:39.668  4328  4344 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-30 10:22:39.668  4328  4344 D BtGatt.GattService: Client app is not null!
08-30 10:22:39.670  4328  4339 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-30 10:22:39.671  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 10:22:39.673  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-30 10:22:39.673  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-30 10:22:39.673  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-30 10:22:39.674  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-30 10:22:39.677  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 10:22:39.677  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 10:22:39.677  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 10:22:39.678  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 10:22:39.681  3943  3943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 10:22:39.682  3943  3943 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-30 10:22:39.682  3943  3943 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 10:22:39.682  3943  3943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 10:22:39.683  3943  3943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 10:22:39.683  3943  3943 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 10:22:39.684  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 10:22:39.684  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:39.684  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 10:22:39.684  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 10:22:39.685  3943  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99e72b removed from the list
08-30 10:22:39.685  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:39.685  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f38b788 removed from the list
,08-30 10:22:39.685  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:22:39.686  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:39.687  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:39.687  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:22:39.690  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 10:22:39.690  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 10:22:39.690  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:39.690  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f38b788 not in the list
08-30 10:22:39.691  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:39.691  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:22:39.693  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 10:22:39.693  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 10:22:39.694  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:39.694  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f38b788 not in the list
08-30 10:22:39.694  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:22:39.694  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:39.694  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:39.694  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f99e72b not in the list
08-30 10:22:39.695  3943  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 10:22:39.695  3943  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@654925d added. We now have 3 listener(s)
08-30 10:22:39.697  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 10:22:39.697  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 10:22:39.697  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 10:22:39.698  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 10:22:39.698  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@788d7d2 added. We now have 4 listener(s)
08-30 10:22:39.698  3943  3993 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 10:22:39.699  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 10:22:39.702  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 10:22:39.711  3943  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:22:39.711  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:39.711  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:22:39.711  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:22:39.711  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:39.711  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:39.711  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:22:39.711  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:22:39.716  3943  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 10:22:39.716  3943  3993 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 10:22:39.717  3943  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 10:22:39.717  3943  3993 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 10:22:39.717  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 10:22:39.718  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 10:22:39.718  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 10:22:39.721  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:22:39.725  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:22:39.725  3943  3993 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-30 10:22:39.725  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 10:22:39.732  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 10:22:39.733  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-30 10:22:39.733  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 10:22:39.739  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 10:22:39.740  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 10:22:39.740  3943  3993 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 10:22:39.742  3943  3993 D BluetoothAdapter: STATE_ON
,08-30 10:22:39.746  4328  4367 D BtGatt.GattService: registerClient() - UUID=403792ec-6f9e-403e-a82d-69ea90701abd
,08-30 10:22:39.747  4328  4344 D BtGatt.GattService: onClientRegistered() - UUID=403792ec-6f9e-403e-a82d-69ea90701abd, clientIf=5
,08-30 10:22:39.748  3943  3953 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-30 10:22:39.748  4328  4339 D BtGatt.GattService: start scan with filters
,08-30 10:22:39.754  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 10:22:39.754  4328  4347 D BtGatt.ScanManager: handling starting scan
08-30 10:22:39.754  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 10:22:39.755  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 10:22:39.755  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 10:22:39.763  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 10:22:39.764  3943  3943 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 10:22:39.765  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 10:22:39.771  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 10:22:39.773  4328  4344 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-30 10:22:39.773  4328  4344 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 10:22:39.774  4328  4347 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-30 10:22:39.789  4328  4344 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-30 10:22:39.790  4328  4344 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-30 10:22:39.790  4328  4347 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 10:22:39.790  4328  4347 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-30 10:22:39.813  4328  4344 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-30 10:22:39.813  4328  4344 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 10:22:39.822  4328  4344 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-30 10:22:39.823  4328  4344 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 10:22:40.183  3943  3943 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 10:22:40.264  3943  3943 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-30 10:22:40.265  3943  3943 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 10:22:40.265  3943  3943 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 10:22:41.328  4328  4328 D BtGatt.ScanManager: awakened up at time 233672
,08-30 10:22:41.331  4328  4347 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-30 10:22:41.380  4328  4344 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-30 10:22:41.381  4328  4344 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 10:22:41.381  4328  4344 D BtGatt.GattService: current time is 233725935628
,08-30 10:22:41.383  4328  4344 D BtGatt.GattService: Batch record : [87, 45, 110, 28, -13, -4, 1, -128, -69, 24, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 4, 124, -7, 14, 55, -106, -85, 0, 35, 97, 126, -92, 22, -56, 1, -128, -84, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -65, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -84, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -84, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -83, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -100, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-30 10:22:41.389  4328  4344 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 4, 124, -7, 14, 55, -106, -85]
,08-30 10:22:41.393  4328  4344 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-30 10:22:41.394  4328  4344 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-30 10:22:41.395  4328  4344 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-30 10:22:41.397  4328  4344 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-30 10:22:41.398  4328  4344 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-30 10:22:41.398  4328  4344 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-30 10:22:41.400  3943  3943 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:37:96:AB 4], added - the peer count is 1
,08-30 10:22:41.401  3943  3943 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:37:96:AB 4], Bluetooth address: 7C:F9:0E:37:96:AB, device name: '', device address: ''
,08-30 10:22:42.788  3943  3993 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 10:22:42.788  3943  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 10:22:42.789  3943  3993 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 10:22:42.789  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:22:42.789  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-30 10:22:42.790  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 10:22:42.790  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 10:22:42.790  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-30 10:22:42.791  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 10:22:42.792  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-30 10:22:42.792  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 10:22:42.794  3943  3993 D BluetoothAdapter: STATE_ON
08-30 10:22:42.798  4328  4368 D BtGatt.GattService: stopScan() - queue size =1
08-30 10:22:42.801  4328  4338 D BtGatt.GattService: unregisterClient() - clientIf=5
08-30 10:22:42.803  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 10:22:42.803  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 10:22:42.803  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 10:22:42.804  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 10:22:42.804  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-30 10:22:42.808  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 10:22:42.809  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 10:22:42.812  3943  3993 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 10:22:42.812  4328  4328 D BtGatt.ScanManager: awakened up at time 235156
,08-30 10:22:42.812  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 10:22:42.816  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 10:22:42.817  3943  3993 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,08-30 10:22:42.820  3943  3943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 10:22:42.821  3943  3943 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 10:22:42.821  3943  3943 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 10:22:42.822  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:22:42.822  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:22:42.823  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 10:22:42.823  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 10:22:42.823  3943  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@654925d removed from the list
08-30 10:22:42.824  4328  4344 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-30 10:22:42.824  4328  4344 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 10:22:42.824  4328  4347 D BtGatt.ScanManager: stopping BLe Batch
08-30 10:22:42.825  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:42.825  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@788d7d2 removed from the list
08-30 10:22:42.826  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:22:42.826  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:22:42.827  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:22:42.828  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:22:42.830  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 10:22:42.830  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 10:22:42.830  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 10:22:42.831  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@788d7d2 not in the list
08-30 10:22:42.831  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:22:42.831  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:42.832  4328  4344 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-30 10:22:42.832  4328  4344 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-30 10:22:42.832  4328  4347 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-30 10:22:42.832  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 10:22:42.832  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 10:22:42.833  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:42.833  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@788d7d2 not in the list
08-30 10:22:42.833  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 10:22:42.833  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:42.833  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:42.833  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@654925d not in the list
08-30 10:22:42.834  3943  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 10:22:42.834  3943  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60965cc added. We now have 3 listener(s)
,08-30 10:22:42.836  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-30 10:22:42.836  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 10:22:42.836  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 10:22:42.837  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 10:22:42.837  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ccb015 added. We now have 4 listener(s)
08-30 10:22:42.837  3943  3993 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 10:22:42.838  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 10:22:42.841  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 10:22:42.846  3943  3993 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 10:22:42.846  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 10:22:42.846  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 10:22:42.846  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 10:22:42.846  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 10:22:42.846  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 10:22:42.846  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 10:22:42.846  3943  3993 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 10:22:42.848  3943  3993 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 10:22:42.848  3943  3993 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 10:22:42.849  3943  3993 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 10:22:42.849  3943  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 10:22:42.849  3943  3993 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 10:22:42.849  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 10:22:42.849  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:42.849  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 10:22:42.849  3943  3993 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 10:22:42.849  3943  3993 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60965cc removed from the list
08-30 10:22:42.850  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:42.850  3943  3993 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ccb015 removed from the list
,08-30 10:22:42.851  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 10:22:42.852  3943  3993 D io.jxcore.node.ConnectivityMonitor: stop
08-30 10:22:42.852  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:22:42.852  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:42.853  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 10:22:42.854  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 10:22:42.855  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 10:22:42.855  3943  3943 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 10:22:42.855  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 10:22:42.855  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ccb015 not in the list
,08-30 10:22:42.855  4328  4344 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
08-30 10:22:42.855  4328  4344 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-30 10:22:42.855  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 10:22:42.856  4328  4344 D BtGatt.GattService: current time is 235200144265
08-30 10:22:42.855  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:42.856  4328  4344 D BtGatt.GattService: Batch record : [45, 37, 53, 64, -111, 126, 1, -128, -85, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 4, 68, 120, 62, -108, 74, 62, 0, -46, -4, -117, 6, 105, -37, 1, -128, -94, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
08-30 10:22:42.856  4328  4344 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 4, 68, 120, 62, -108, 74, 62]
08-30 10:22:42.856  4328  4344 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-30 10:22:42.857  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 10:22:42.857  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 10:22:42.857  3943  3993 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 10:22:42.857  3943  3993 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ccb015 not in the list
08-30 10:22:42.857  3943  3993 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 10:22:42.857  3943  3993 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 10:22:42.857  3943  3993 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 10:22:42.857  3943  3993 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60965cc not in the list
08-30 10:22:42.858  3943  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 10:22:42.858  3943  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-30 10:22:42.859  3943  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 10:22:42.859  3943  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 10:22:42.859  3943  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only,
08-30 10:22:42.859  3943  3993 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 10:22:43.323  3943  3943 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 10:22:44.874  3943  4427 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 492, name: My test thread name)
,08-30 10:22:46.872  3943  3993 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 492
,08-30 10:22:46.872  3943  3993 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 492, name: My test thread name)
,08-30 10:22:46.879  3943  4428 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 493, name: My test thread name)
,08-30 10:22:46.880  3943  4428 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 493, thread name: My test thread name)
08-30 10:22:46.880  3943  4428 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 493, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-30 10:22:46.886  3943  3993 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-30 10:22:46.896  3943  4429 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 497, name: My test thread name)
,08-30 10:22:46.896  3943  4429 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 497, thread name: My test thread name): Test exception.
,08-30 10:22:46.898  3943  4429 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 497, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-30 10:22:46.906  3943  3993 I jxcore-log: Total number of executed tests:  82
08-30 10:22:46.906  3943  3993 I jxcore-log: 
,08-30 10:22:46.907  3943  3993 I jxcore-log: Number of passed tests:  82
08-30 10:22:46.907  3943  3993 I jxcore-log: 
08-30 10:22:46.907  3943  3993 I jxcore-log: Number of failed tests:  0
08-30 10:22:46.907  3943  3993 I jxcore-log: 
,08-30 10:22:46.908  3943  4427 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 492, name: My test thread name), during the lifetime of the thread the total number of bytes read was 187 and the total number of bytes written 187
08-30 10:22:46.910  3943  3993 I jxcore-log: Number of ignored tests:  0
08-30 10:22:46.910  3943  3993 I jxcore-log: 
,08-30 10:22:46.910  3943  3993 I jxcore-log: Total duration:  111532
08-30 10:22:46.910  3943  3993 I jxcore-log: 
,08-30 10:22:46.916  3943  3993 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 10:22:46.916  3943  3993 I jxcore-log: 
,08-30 10:22:46.919  3943  3993 I jxcore-log: My device name is: motorola-Nexus 6
08-30 10:22:46.919  3943  3993 I jxcore-log: 
08-30 10:22:46.928  3943  3993 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 10:22:46.928  3943  3993 I jxcore-log: 
08-30 10:22:46.933  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:46.933  3943  3993 I jxcore-log: 
,08-30 10:22:46.936  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:46.936  3943  3993 I jxcore-log: 
,08-30 10:22:46.941  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:46.941  3943  3993 I jxcore-log: 
,08-30 10:22:46.948  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-30 10:22:46.948  3943  3993 I jxcore-log: 
,08-30 10:22:46.961  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:46.961  3943  3993 I jxcore-log: 
,08-30 10:22:46.968  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 10:22:46.968  3943  3993 I jxcore-log: 
,08-30 10:22:46.974  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-30 10:22:46.974  3943  3993 I jxcore-log: 
,08-30 10:22:46.977  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-30 10:22:46.977  3943  3993 I jxcore-log: 
,08-30 10:22:46.979  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-30 10:22:46.979  3943  3993 I jxcore-log: 
,08-30 10:22:46.982  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 10:22:46.982  3943  3993 I jxcore-log: 
,08-30 10:22:46.984  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:46.984  3943  3993 I jxcore-log: 
,08-30 10:22:46.988  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-30 10:22:46.988  3943  3993 I jxcore-log: 
,08-30 10:22:46.991  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 10:22:46.991  3943  3993 I jxcore-log: 
,08-30 10:22:46.993  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 10:22:46.993  3943  3993 I jxcore-log: 
08-30 10:22:46.994  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:46.994  3943  3993 I jxcore-log: 
,08-30 10:22:46.995  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:46.995  3943  3993 I jxcore-log: 
,08-30 10:22:46.996  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:46.996  3943  3993 I jxcore-log: 
08-30 10:22:46.997  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"},
08-30 10:22:46.997  3943  3993 I jxcore-log: 
08-30 10:22:46.998  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 10:22:46.998  3943  3993 I jxcore-log: 
,08-30 10:22:46.999  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 10:22:46.999  3943  3993 I jxcore-log: 
,08-30 10:22:47.000  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 10:22:47.000  3943  3993 I jxcore-log: 
,08-30 10:22:47.001  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-30 10:22:47.001  3943  3993 I jxcore-log: 
,08-30 10:22:47.002  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 10:22:47.002  3943  3993 I jxcore-log: 
,08-30 10:22:47.003  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 10:22:47.003  3943  3993 I jxcore-log: 
,08-30 10:22:47.004  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 10:22:47.004  3943  3993 I jxcore-log: 
,08-30 10:22:47.005  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 10:22:47.005  3943  3993 I jxcore-log: 
,08-30 10:22:47.006  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:47.006  3943  3993 I jxcore-log: 
,08-30 10:22:47.007  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:47.007  3943  3993 I jxcore-log: 
08-30 10:22:47.008  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
08-30 10:22:47.008  3943  3993 I jxcore-log: 
,08-30 10:22:47.009  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 10:22:47.009  3943  3993 I jxcore-log: 
08-30 10:22:47.010  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
,08-30 10:22:47.010  3943  3993 I jxcore-log: 
,08-30 10:22:47.011  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 10:22:47.011  3943  3993 I jxcore-log: 
,08-30 10:22:47.013  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 10:22:47.013  3943  3993 I jxcore-log: 
,08-30 10:22:47.015  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 10:22:47.015  3943  3993 I jxcore-log: 
,08-30 10:22:47.016  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 10:22:47.016  3943  3993 I jxcore-log: 
,08-30 10:22:47.017  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 10:22:47.017  3943  3993 I jxcore-log: 
,08-30 10:22:47.018  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 10:22:47.018  3943  3993 I jxcore-log: 
,08-30 10:22:47.018  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 10:22:47.018  3943  3993 I jxcore-log: 
,08-30 10:22:47.019  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 10:22:47.019  3943  3993 I jxcore-log: 
,08-30 10:22:47.020  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 10:22:47.020  3943  3993 I jxcore-log: 
,08-30 10:22:47.021  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 10:22:47.021  3943  3993 I jxcore-log: 
,08-30 10:22:47.023  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 10:22:47.023  3943  3993 I jxcore-log: 
,08-30 10:22:47.024  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 10:22:47.024  3943  3993 I jxcore-log: 
,08-30 10:22:47.025  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:47.025  3943  3993 I jxcore-log: 
,08-30 10:22:47.026  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:47.026  3943  3993 I jxcore-log: 
,08-30 10:22:47.028  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:47.028  3943  3993 I jxcore-log: 
,08-30 10:22:47.030  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:47.030  3943  3993 I jxcore-log: 
,08-30 10:22:47.031  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:47.031  3943  3993 I jxcore-log: 
,08-30 10:22:47.032  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 10:22:47.032  3943  3993 I jxcore-log: 
,08-30 10:22:47.034  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:47.034  3943  3993 I jxcore-log: 
,08-30 10:22:47.035  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-30 10:22:47.035  3943  3993 I jxcore-log: 
,08-30 10:22:47.040  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:47.040  3943  3993 I jxcore-log: 
,08-30 10:22:47.041  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 10:22:47.041  3943  3993 I jxcore-log: 
,08-30 10:22:47.042  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-30 10:22:47.042  3943  3993 I jxcore-log: 
,08-30 10:22:47.043  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
08-30 10:22:47.043  3943  3993 I jxcore-log: 
08-30 10:22:47.044  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 10:22:47.044  3943  3993 I jxcore-log: 
,08-30 10:22:47.046  3943  3993 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 10:22:47.046  3943  3993 I jxcore-log: 
,08-30 10:22:47.534  4430  4430 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 10:22:47.540  4430  4430 D AndroidRuntime: CheckJNI is OFF
,08-30 10:22:47.583  4430  4430 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 10:22:47.629  4430  4430 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 10:22:47.650  4430  4430 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 10:22:47.658   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-30 10:22:47.658   874   887 I ActivityManager: Killing 3943:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-30 10:22:47.747   874  2027 D GraphicsStats: Buffer count: 2
08-30 10:22:47.747   874  1688 I WindowState: WIN DEATH: Window{935a9e3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 10:22:47.747   874  1303 D WifiService: Client connection lost with reason: 4
,08-30 10:22:47.780   874   897 W PackageSettings: Skipping PackageSetting{efdfa2a com.example.hello/10273} due to missing metadata
,08-30 10:22:47.803   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-30 10:22:47.803   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-30 10:22:47.804   874   887 E ActivityManager: Failure starting process com.test.thalitest
08-30 10:22:47.804   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-30 10:22:47.804   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-30 10:22:47.804   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-30 10:22:47.804   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-30 10:22:47.804   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-30 10:22:47.804   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-30 10:22:47.804   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-30 10:22:47.804   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-30 10:22:47.804   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-30 10:22:47.804   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-30 10:22:47.804   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-30 10:22:47.804   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-30 10:22:47.804   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-30 10:22:47.804   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-30 10:22:47.804   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-30 10:22:47.804   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 10:22:47.804   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 10:22:47.804   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 10:22:47.804   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 10:22:47.804   874   897 I art     : Starting a blocking GC Explicit
08-30 10:22:47.805   874   887 I ActivityManager:   Force finishing activity ActivityRecord{9fd5d68 u0 com.test.thalitest/.MainActivity t2}
,08-30 10:22:47.812   874  2289 W ActivityManager: Spurious death for ProcessRecord{2b6b92d 0:com.test.thalitest/u0a0}, curProc for 3943: null
,08-30 10:22:47.846   874   897 I art     : Explicit concurrent mark sweep GC freed 18367(1174KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 765us total 40.499ms
,08-30 10:22:47.892   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 10:22:47.894  4430  4430 I art     : System.exit called, status: 0
,08-30 10:22:47.894  4430  4430 I AndroidRuntime: VM exiting with result code 0.
,08-30 10:22:47.901   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-30 10:22:47.915   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-30 10:22:47.919  4328  4328 D BluetoothMapAppObserver: onReceive
,08-30 10:22:47.919  4328  4328 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-30 10:22:47.923  1849  2239 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 10:22:47.923   874  1294 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 10:22:47.927  3785  3785 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-30 10:22:47.937  1887  1887 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-30 10:22:47.965  1978  1978 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-30 10:22:47.970  1887  4442 I Keyboard.Facilitator.DecoderInitializer: run()
,08-30 10:22:47.974   874   885 I ActivityManager: Start proc 4444:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-30 10:22:47.979  1887  4442 I Decoder : createOrResetDecoder
,08-30 10:22:48.002   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 10:22:48.018  1993  2094 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-30 10:22:48.018   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-30 10:22:48.018   874   886 E PackageManager: Failed to write settings, restoring backup
08-30 10:22:48.018   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-30 10:22:48.018   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-30 10:22:48.018   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-30 10:22:48.018   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-30 10:22:48.018   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-30 10:22:48.018   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 10:22:48.018   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 10:22:48.018   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 10:22:48.023  1497  1497 I ConfigService: onCreate
,08-30 10:22:48.023   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-30 10:22:48.023   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-30 10:22:48.023   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 10:22:48.023   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 10:22:48.023   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 10:22:48.023   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 10:22:48.023   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 10:22:48.023   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 10:22:48.023   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-30 10:22:48.023   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-30 10:22:48.023   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-30 10:22:48.023   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 10:22:48.023   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 10:22:48.023   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-30 10:22:48.023   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 10:22:48.023   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 10:22:48.023   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 10:22:48.023   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 10:22:48.023   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 10:22:48.023   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 10:22:48.023   874   887 E DropBoxManagerService: 	... 13 more
,08-30 10:22:48.030  1497  4456 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-30 10:22:48.030  1497  4456 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 10:22:48.030  1497  4456 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 10:22:48.030  1497  4456 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 10:22:48.030  1497  4456 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 10:22:48.030  1497  4456 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 10:22:48.030  1497  4456 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 10:22:48.030  1497  4456 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 10:22:48.030  1497  4456 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 10:22:48.030  1497  4456 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 10:22:48.030  1497  4456 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 10:22:48.030  1497  4456 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 10:22:48.030  1497  4456 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 10:22:48.030  1497  4456 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 10:22:48.030  1497  4456 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 10:22:48.030  1497  4456 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-30 10:22:48.030  1497  4456 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-30 10:22:48.030  1497  4456 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-30 10:22:48.030  1497  4456 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-30 10:22:48.030  1497  4456 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 10:22:48.030  1497  4456 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 10:22:48.030  1497  4456 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 10:22:48.030  1497  4456 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 10:22:48.030  1497  4456 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 10:22:48.030  1497  4456 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 10:22:48.030  1497  4456 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 10:22:48.030  1497  4456 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 10:22:48.030  1497  4456 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 10:22:48.030  1497  4456 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 10:22:48.030  1497  4456 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 10:22:48.030  1497  4456 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 10:22:48.030  1497  4456 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 10:22:48.030  1497  4456 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 10:22:48.030  1497  4456 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-30 10:22:48.030  1497  4456 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-30 10:22:48.030  1497  4456 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,08-30 10:22:48.033   874  2289 I ActivityManager: Start proc 4457:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-30 10:22:48.034  1993  2094 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-30 10:22:48.034  1993  2094 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1993
08-30 10:22:48.034  1993  2094 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 10:22:48.034  1993  2094 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 10:22:48.034  1993  2094 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 10:22:48.034  1993  2094 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 10:22:48.034  1993  2094 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 10:22:48.034  1993  2094 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 10:22:48.034  1993  2094 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-30 10:22:48.034  1993  2094 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-30 10:22:48.034  1993  2094 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 10:22:48.034  1993  2094 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 10:22:48.034  1993  2094 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 10:22:48.034  1993  2094 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 10:22:48.035  4444  4444 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-30 10:22:48.036   874  2026 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 10:22:48.037   874  4463 E DropBoxManagerService: Can't write: system_app_crash
08-30 10:22:48.037   874  4463 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-30 10:22:48.037   874  4463 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 10:22:48.037   874  4463 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 10:22:48.037   874  4463 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 10:22:48.037   874  4463 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 10:22:48.037   874  4463 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 10:22:48.037   874  4463 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 10:22:48.037   874  4463 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 10:22:48.037   874  4463 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 10:22:48.037   874  4463 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 10:22:48.037   874  4463 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 10:22:48.037   874  4463 E DropBoxManagerService: 	... 5 more
08-30 10:22:48.040  1993  2094 I Process : Sending signal. PID: 1993 SIG: 9
,08-30 10:22:48.050  1497  4456 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-30 10:22:48.067  1887  4442 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-30 10:22:48.133   874  1293 W InputDispatcher: channel '3d33141 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,08-30 10:22:48.133   874  1293 E InputDispatcher: channel '3d33141 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
08-30 10:22:48.135   874  2028 I WindowState: WIN DEATH: Window{3d33141 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-30 10:22:48.136   874  2028 W InputDispatcher: Attempted to unregister already unregistered input channel '3d33141 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
08-30 10:22:48.136   874  2290 D GraphicsStats: Buffer count: 1
,08-30 10:22:48.144  1887  4442 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-30 10:22:48.146   874  2026 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1993) has died
,08-30 10:22:48.147   874  2026 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-30 10:22:48.147  1887  4442 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-30 10:22:48.147  1887  4442 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-30 10:22:48.148   874  2026 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 10:22:48.151  1887  4442 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-30 10:22:48.151  1887  4442 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-30 10:22:48.152  1887  4442 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-30 10:22:48.152  1887  4442 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-30 10:22:48.153  1887  4442 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-30 10:22:48.153  1887  4442 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-30 10:22:48.153  1887  4442 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-30 10:22:48.165  1887  4442 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-30 10:22:48.165  1887  4442 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-30 10:22:48.165  1887  4442 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-30 10:22:48.176   874   887 I ActivityManager: Start proc 4475:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 10:22:48.206   874  4385 D NetlinkSocketObserver: NeighborEvent{elapsedMs=240550, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-30 10:22:48.208  4444  4444 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-30 10:22:48.218  1690  4484 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-30 10:22:48.219  1690  4484 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory,
,08-30 10:22:48.225  4444  4489 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 10:22:48.233   874  2028 I ActivityManager: Start proc 4490:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-30 10:22:48.238  4444  4474 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 10:22:48.238  4444  4474 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 10:22:48.238  4444  4474 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 10:22:48.238  4444  4474 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 10:22:48.238  4444  4474 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 10:22:48.238  4444  4474 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 10:22:48.238  4444  4474 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 10:22:48.238  4444  4474 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 10:22:48.238  4444  4474 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 10:22:48.238  4444  4474 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 10:22:48.238  4444  4474 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 10:22:48.238  4444  4474 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 10:22:48.238  4444  4474 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 10:22:48.238  4444  4474 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 10:22:48.238  4444  4474 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 10:22:48.238  4444  4474 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 10:22:48.238  4444  4474 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 10:22:48.238  4444  4474 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 10:22:48.238  4444  4474 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 10:22:48.238  4444  4474 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 10:22:48.238  4444  4474 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 10:22:48.238  4444  4474 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 10:22:48.238  4444  4474 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-30 10:22:48.238  4444  4474 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 10:22:48.238  4444  4474 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 10:22:48.238  4444  4474 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 10:22:48.238  4444  4474 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 10:22:48.238  4444  4474 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 10:22:48.238  4444  4474 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 10:22:48.238  4444  4474 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 10:22:48.238  4444  4474 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 10:22:48.238  4444  4474 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 10:22:48.238  4444  4474 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 10:22:48.238  4444  4474 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 10:22:48.238  4444  4474 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 10:22:48.238  4444  4474 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 10:22:48.238  4444  4474 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 10:22:48.238  4444  4474 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-30 10:22:48.238  4444  4474 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-30 10:22:48.238  4444  4474 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-30 10:22:48.238  4444  4474 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-30 10:22:48.238  4444  4474 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 10:22:48.238  4444  4474 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-30 10:22:48.238  4444  4474 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 10:22:48.248  4475  4475 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 10:22:48.248  4475  4475 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 10:22:48.249  4475  4475 D AndroidRuntime: Shutting down VM
,08-30 10:22:48.261  4475  4475 E AndroidRuntime: FATAL EXCEPTION: main
08-30 10:22:48.261  4475  4475 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4475
08-30 10:22:48.261  4475  4475 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 10:22:48.261  4475  4475 E AndroidRuntime: 	... 10 more
,08-30 10:22:48.263   874  2028 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 10:22:48.263  4475  4475 I Process : Sending signal. PID: 4475 SIG: 9
08-30 10:22:48.264   874  4502 E DropBoxManagerService: Can't write: system_app_crash
08-30 10:22:48.264   874  4502 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-30 10:22:48.264   874  4502 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 10:22:48.264   874  4502 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 10:22:48.264   874  4502 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 10:22:48.264   874  4502 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 10:22:48.264   874  4502 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 10:22:48.264   874  4502 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 10:22:48.264   874  4502 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 10:22:48.264   874  4502 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 10:22:48.264   874  4502 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 10:22:48.264   874  4502 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 10:22:48.264   874  4502 E DropBoxManagerService: 	... 5 more
,08-30 10:22:48.281  1690  4484 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-30 10:22:48.282  1690  4484 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-30 10:22:48.287  4490  4490 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-30 10:22:48.289   874  1689 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4475) has died
,08-30 10:22:48.291   874  1689 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-30 10:22:48.306   874   887 I ActivityManager: Start proc 4505:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-30 10:22:48.324  4444  4474 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-30 10:22:48.334  1497  1497 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-30 10:22:48.336  1497  1497 D AndroidRuntime: Shutting down VM
,08-30 10:22:48.337  1497  1497 E AndroidRuntime: FATAL EXCEPTION: main
08-30 10:22:48.337  1497  1497 E AndroidRuntime: Process: com.google.process.gapps, PID: 1497
08-30 10:22:48.337  1497  1497 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 10:22:48.337  1497  1497 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-30 10:22:48.337  1497  1497 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-30 10:22:48.337  1497  1497 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-30 10:22:48.337  1497  1497 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 10:22:48.337  1497  1497 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 10:22:48.337  1497  1497 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 10:22:48.337  1497  1497 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:22:48.337  1497  1497 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 10:22:48.337  1497  1497 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 10:22:48.337  1497  1497 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 10:22:48.337  1497  1497 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 10:22:48.337  1497  1497 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 10:22:48.337  1497  1497 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 10:22:48.337  1497  1497 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 10:22:48.337  1497  1497 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 10:22:48.337  1497  1497 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-30 10:22:48.337  1497  1497 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-30 10:22:48.337  1497  1497 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-30 10:22:48.337  1497  1497 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-30 10:22:48.337  1497  1497 E AndroidRuntime: 	... 8 more
,08-30 10:22:48.340  1497  1497 I Process : Sending signal. PID: 1497 SIG: 9
,08-30 10:22:48.346   874  4518 E DropBoxManagerService: Can't write: system_app_crash
08-30 10:22:48.346   874  4518 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-30 10:22:48.346   874  4518 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 10:22:48.346   874  4518 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 10:22:48.346   874  4518 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 10:22:48.346   874  4518 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 10:22:48.346   874  4518 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 10:22:48.346   874  4518 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 10:22:48.346   874  4518 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 10:22:48.346   874  4518 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 10:22:48.346   874  4518 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 10:22:48.346   874  4518 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 10:22:48.346   874  4518 E DropBoxManagerService: 	... 5 more
,08-30 10:22:48.353  4505  4505 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 10:22:48.353  4505  4505 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-30 10:22:48.353  4505  4505 D AndroidRuntime: Shutting down VM
,08-30 10:22:48.361  4444  4489 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 10:22:48.361  4444  4489 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 10:22:48.361  4505  4505 E AndroidRuntime: FATAL EXCEPTION: main
08-30 10:22:48.361  4505  4505 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4505
08-30 10:22:48.361  4505  4505 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 10:22:48.361  4505  4505 E AndroidRuntime: ,	,at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177),
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-30 10:22:48.361  4505  4505 E AndroidRuntime: 	... 10 more
,08-30 10:22:48.361  4444  4489 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-30 10:22:48.361  4444  4489 E AndroidRuntime: Process: android.process.acore, PID: 4444
08-30 10:22:48.361  4444  4489 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 10:22:48.361  4444  4489 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 10:22:48.361  4444  4489 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 10:22:48.361  4444  4489 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 10:22:48.361  4444  4489 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 10:22:48.361  4444  4489 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 10:22:48.361  4444  4489 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 10:22:48.361  4444  4489 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 10:22:48.361  4444  4489 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
,08-30 10:22:48.361  4444  4489 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 10:22:48.361  4444  4489 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 10:22:48.361  4444  4489 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 10:22:48.361  4444  4489 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 10:22:48.361  4444  4489 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 10:22:48.361  4444  4489 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-30 10:22:48.361  4444  4489 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 10:22:48.361  4444  4489 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 10:22:48.361  4444  4489 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 10:22:48.361  4444  4489 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-30 10:22:48.361  4444  4489 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 10:22:48.361  4444  4489 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 10:22:48.361  4444  4489 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 10:22:48.361  4444  4489 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 10:22:48.361  4444  4489 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 10:22:48.362   874  2028 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-30 10:22:48.363  4505  4505 I Process : Sending signal. PID: 4505 SIG: 9
08-30 10:22:48.364   874  4520 E DropBoxManagerService: Can't write: system_app_crash
08-30 10:22:48.364   874  4520 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
08-30 10:22:48.364   874  4520 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 10:22:48.364   874  4520 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 10:22:48.364   874  4520 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 10:22:48.364   874  4520 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 10:22:48.364   874  4520 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 10:22:48.364   874  4520 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 10:22:48.364   874  4520 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 10:22:48.364   874  4520 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 10:22:48.364   874  4520 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 10:22:48.364   874  4520 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 10:22:48.364   874  4520 E DropBoxManagerService: 	... 5 more
,08-30 10:22:48.369   874  4519 E DropBoxManagerService: Can't write: system_app_crash
08-30 10:22:48.369   874  4519 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-30 10:22:48.369   874  4519 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 10:22:48.369   874  4519 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 10:22:48.369   874  4519 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 10:22:48.369   874  4519 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 10:22:48.369   874  4519 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 10:22:48.369   874  4519 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 10:22:48.369   874  4519 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 10:22:48.369   874  4519 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 10:22:48.369   874  4519 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 10:22:48.369   874  4519 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 10:22:48.369   874  4519 E DropBoxManagerService: 	... 5 more
,08-30 10:22:48.374   874  1303 D WifiService: Client connection lost with reason: 4
,08-30 10:22:48.378  4444  4489 I Process : Sending signal. PID: 4444 SIG: 9
,08-30 10:22:48.379   874  1379 I ActivityManager: Process com.google.process.gapps (pid 1497) has died
,08-30 10:22:48.379   874  1379 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
08-30 10:22:48.379   874  1379 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
08-30 10:22:48.379   874  1379 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 20999ms
,08-30 10:22:48.387  1690  4484 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory

```
