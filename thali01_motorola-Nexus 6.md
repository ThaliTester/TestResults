#### Test 83084099a4f621d_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
08-29 14:39:36.234   873  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
--------- beginning of main
08-29 14:39:36.570   873  1313 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
08-29 14:39:36.880   873  1915 D AlarmManagerService: Setting time of day to sec=1472474376
08-29 14:39:36.996   873  1915 W AlarmManagerService: Unable to set rtc to 1472474376: Invalid argument
08-29 14:39:37.107  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 14:39:37.118  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 14:39:37.122  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 14:39:37.166  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-29 14:39:37.166  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 14:39:37.168  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:39:37.169  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-29 14:39:37.202  3528  3528 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-29 14:39:37.202  3528  3528 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 14:39:37.203  3528  3528 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,08-29 14:39:38.211  3854  3854 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 14:39:38.216  3854  3854 D AndroidRuntime: CheckJNI is OFF
08-29 14:39:38.259  3854  3854 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 14:39:38.309  3854  3854 I Radio-JNI: register_android_hardware_Radio DONE
08-29 14:39:38.331  3854  3854 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-29 14:39:38.335   873  2078 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 14:39:38.375  2032  2045 W SearchService: Abort, client detached.
08-29 14:39:38.384  3854  3854 D AndroidRuntime: Shutting down VM
08-29 14:39:38.386  2032  2032 I HotwordDetector: Closing mic
08-29 14:39:38.386  2032  2334 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@2b9200f
08-29 14:39:38.387  2032  2345 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-29 14:39:38.410   873  2004 I ActivityManager: Start proc 3863:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-29 14:39:38.454   375  2348 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-29 14:39:38.456   375  2348 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-29 14:39:38.462   375  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-29 14:39:38.465  2032  2344 I MicroRecognitionRnrImpl: Detection finished
08-29 14:39:38.465  2032  2341 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-29 14:39:38.492  3863  3863 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-29 14:39:38.513  3863  3863 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 14:39:38.520  3863  3863 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4133-4135)
08-29 14:39:38.520  3863  3863 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 14:39:38.536  3863  3863 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6238bca}
08-29 14:39:38.536  3863  3863 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 14:39:38.536  3863  3863 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 14:39:38.543  3863  3863 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 14:39:38.544  3863  3863 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 14:39:38.564  3863  3863 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-29 14:39:38.574  3863  3863 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 14:39:38.574  3863  3863 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 14:39:38.574  3863  3863 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 14:39:38.574  3863  3863 I Adreno  : Build Date                       : 10/20/15
08-29 14:39:38.574  3863  3863 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 14:39:38.574  3863  3863 I Adreno  : Local Branch                     : M14
08-29 14:39:38.574  3863  3863 I Adreno  : Remote Branch                    : 
08-29 14:39:38.574  3863  3863 I Adreno  : Remote Branch                    : 
08-29 14:39:38.574  3863  3863 I Adreno  : Reconstruct Branch               : 
,08-29 14:39:38.634   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b45555e:true
,08-29 14:39:38.681  3863  3863 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 14:39:38.697  3863  3863 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-29 14:39:38.768  3863  3903 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 14:39:38.780  3863  3888 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 14:39:38.806  3863  3903 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 14:39:38.871   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +482ms
,08-29 14:39:38.874  1878  1878 I Keyboard.Facilitator: onFinishInput()
,08-29 14:39:38.939  3863  3863 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3863
,08-29 14:39:39.020  3863  3863 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 14:39:39.213  3863  3906 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1665009360
,08-29 14:39:39.220  3863  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 14:39:39.220  3863  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 14:39:39.220  3863  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 14:39:39.220  3863  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 14:39:39.220  3863  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 14:39:39.220  3863  3906 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f27312e added. We now have 1 listener(s)
,08-29 14:39:39.224  3863  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-29 14:39:39.226  3863  3906 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 14:39:39.226  3863  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:39:39.227  3863  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-29 14:39:39.230  3863  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 14:39:39.230  3863  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 14:39:39.230  3863  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 14:39:39.230  3863  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-29 14:39:39.230  3863  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 14:39:39.230  3863  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 14:39:39.230  3863  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 14:39:39.230  3863  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 14:39:39.230  3863  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 14:39:39.230  3863  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 14:39:39.230  3863  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 14:39:39.230  3863  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 14:39:39.230  3863  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 14:39:39.230  3863  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-29 14:39:39.230  3863  3906 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94db565 added. We now have 1 listener(s)
08-29 14:39:39.230  3863  3906 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:39:39.232   873  1314 D WifiService: New client listening to asynchronous messages
08-29 14:39:39.233  3863  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 14:39:39.233  3863  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 14:39:39.233  3863  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 14:39:39.233  3863  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 14:39:39.233  3863  3906 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-29 14:39:39.236  3863  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:39:39.236  3863  3906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-29 14:39:39.241  3863  3906 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-29 14:39:39.241  3863  3906 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:39:39.241  3863  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:39:39.241  3863  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:39:39.241  3863  3906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:39:39.241  3863  3906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:39:39.241  3863  3906 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:39:39.241  3863  3906 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:39:39.241  3863  3906 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:39:39.241  3863  3906 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 14:39:39.241  3863  3906 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 14:39:39.242   873   884 I ActivityManager: Killing 3083:com.google.android.talk/u0a61 (adj 15): empty #17
08-29 14:39:39.242  3863  3906 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 14:39:39.336   873   884 I ActivityManager: Killing 2984:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-29 14:39:39.368   873  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 14:39:39.376  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:39:39.378  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:39:39.380  3863  3863 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 14:39:40.341  3863  3915 W jxcore-log: Initializing JXcore engine
08-29 14:39:40.341  3863  3915 W jxcore-log: JXcore engine is ready
,08-29 14:39:40.376  3915  3915 W Thread-337: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8806 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-29 14:39:40.379  3915  3915 W Thread-337: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10233]" dev="sockfs" ino=10233 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-29 14:39:40.379  3915  3915 W Thread-337: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-29 14:39:40.379  3915  3915 W Thread-337: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25986]" dev="sockfs" ino=25986 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 14:39:40.404  3863  3915 W jxcore-log: Starting JXcore engine
,08-29 14:39:40.573  3863  3915 W jxcore-log: Platform android
08-29 14:39:40.573  3863  3915 W jxcore-log: 
,08-29 14:39:40.573  3863  3915 W jxcore-log: Process ARCH arm
08-29 14:39:40.573  3863  3915 W jxcore-log: 
,08-29 14:39:40.873  3863  3915 I jxcore-log: JXcore Cordova bridge is ready!
08-29 14:39:40.873  3863  3915 I jxcore-log: 
,08-29 14:39:40.873  3863  3915 W jxcore-log: JXcore engine is started
,08-29 14:39:40.884  3863  3906 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 14:39:40.889  3863  3863 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 14:39:41.942   873  1854 D NetlinkSocketObserver: NeighborEvent{elapsedMs=127557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 14:39:57.247  3863  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 14:39:57.247  3863  3915 I jxcore-log: 
,08-29 14:39:57.250  3863  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 14:39:57.250  3863  3915 I jxcore-log: 
,08-29 14:39:57.261  3863  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:39:57.261  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:39:57.261  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:39:57.261  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:39:57.261  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:39:57.261  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:39:57.261  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:39:57.261  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:39:57.266  3863  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:39:57.269  3863  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 14:39:57.269  3863  3915 I jxcore-log: 
,08-29 14:39:57.271  3863  3915 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 14:39:57.271  3863  3915 I jxcore-log: 
,08-29 14:39:57.529   873  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 14:39:57.632  3863  3915 I jxcore-log: Running unit tests
08-29 14:39:57.632  3863  3915 I jxcore-log: 
,08-29 14:39:57.632  3863  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:39:57.632  3863  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9404215 added. We now have 2 listener(s)
08-29 14:39:57.634  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 14:39:57.634  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:39:57.634  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:39:57.634  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:39:57.634  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5bcb92a added. We now have 2 listener(s)
,08-29 14:39:57.634  3863  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:39:57.635  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 14:39:57.638  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:39:57.646  3863  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:39:57.646  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:39:57.646  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:39:57.646  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:39:57.646  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:39:57.646  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:39:57.646  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:39:57.646  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:39:57.650  3863  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:39:57.650  3863  3915 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 14:39:57.651  3863  3915 D ExecuteNativeTests: Running unit tests
,08-29 14:39:57.656  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:39:57.664  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:39:57.713  3863  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 14:39:57.713  3863  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 added. We now have 3 listener(s)
,08-29 14:39:57.714  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 14:39:57.714  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:39:57.714  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:39:57.714  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 14:39:57.714  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 added. We now have 3 listener(s)
08-29 14:39:57.715  3863  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:39:57.715  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 14:39:57.720  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:39:57.741  3863  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:39:57.741  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:39:57.741  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:39:57.741  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:39:57.741  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:39:57.741  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:39:57.741  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:39:57.741  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:39:57.747  3863  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:39:57.747  3863  3915 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 14:39:57.750  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 14:39:57.752  3863  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 14:39:57.752  3863  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 14:39:57.752  3863  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 14:39:57.753  3863  3915 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-29 14:39:57.753  3863  3915 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-29 14:39:57.753  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 14:39:57.754  3863  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 14:39:57.754  3863  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 14:39:57.754  3863  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 14:39:57.754  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:39:57.754  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:39:57.755  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:39:57.755  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:39:57.755  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:39:57.755  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 14:39:57.755  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:39:57.755  3863  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 removed from the list
,08-29 14:39:57.755  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:39:57.755  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 removed from the list
08-29 14:39:57.756  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:39:57.758  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:39:57.759  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:39:57.759  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:39:57.759  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:39:57.759  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:39:57.760  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 14:39:57.760  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:39:57.760  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:39:57.760  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
,08-29 14:39:57.762  3863  3915 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 14:39:57.762  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 14:39:57.762  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:39:57.762  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:39:57.762  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:39:57.763  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:39:57.763  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:39:57.763  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 not in the list
08-29 14:39:57.763  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:39:57.763  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:39:57.763  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 14:39:57.763  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:39:57.763  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:39:57.763  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:39:57.763  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:39:57.764  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:39:57.764  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 14:39:57.764  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:39:57.764  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
,08-29 14:39:57.768  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 14:39:57.768  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-29 14:39:57.768  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 14:39:57.768  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 14:39:57.768  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 14:39:57.768  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 14:39:57.768  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 14:39:57.768  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-29 14:39:57.768  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 14:39:57.768  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 14:39:57.768  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 14:39:57.768  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 14:39:57.768  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 14:39:57.768  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 14:39:57.768  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-29 14:39:57.769  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 14:39:57.769  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 14:39:57.769  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 14:39:57.769  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-29 14:39:57.769  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 14:39:57.769  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 14:39:57.769  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 14:39:57.769  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 14:39:57.769  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 14:39:57.769  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 14:39:57.769  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 14:39:57.769  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 14:39:57.769  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 14:39:57.769  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-29 14:39:57.769  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 14:39:57.769  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 14:39:57.769  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:39:57.769  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:39:57.769  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:39:57.770  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:39:57.770  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:39:57.770  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:39:57.770  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 not in the list
08-29 14:39:57.770  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:39:57.770  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
,08-29 14:39:57.770  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:39:57.770  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:39:57.770  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:39:57.770  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:39:57.770  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:39:57.771  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:39:57.771  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:39:57.771  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:39:57.771  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:39:57.771  3863  3915 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 14:39:57.772  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:39:57.775  3863  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:39:57.775  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:39:57.775  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:39:57.775  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:39:57.775  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:39:57.775  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:39:57.775  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:39:57.775  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:39:57.777  3863  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:39:57.778  3863  3915 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 14:39:57.778  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 14:39:57.778  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 14:39:57.778  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 14:39:57.778  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:39:57.779  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 14:39:57.780  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:39:57.781  3863  3915 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 14:39:57.781  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 14:39:57.781  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:39:57.786  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 14:39:57.788  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 14:39:57.788  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 14:39:57.791  3863  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-29 14:39:57.793  3863  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-29 14:39:57.794  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 14:39:57.794  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 14:39:57.794  3863  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 14:39:57.795  3863  3915 D BluetoothAdapter: STATE_ON
,08-29 14:39:57.798  2401  2437 D BtGatt.GattService: registerClient() - UUID=2f8acea5-20a2-4871-8479-9ac3030bbbbf
,08-29 14:39:57.799  2401  2420 D BtGatt.GattService: onClientRegistered() - UUID=2f8acea5-20a2-4871-8479-9ac3030bbbbf, clientIf=5
08-29 14:39:57.799  3863  3874 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 14:39:57.800  2401  2412 D BtGatt.GattService: start scan with filters
,08-29 14:39:57.802  2401  2423 D BtGatt.ScanManager: handling starting scan
,08-29 14:39:57.803  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 14:39:57.803  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 14:39:57.803  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 14:39:57.803  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 14:39:57.803  2401  2423 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ecbba04
,08-29 14:39:57.806  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 14:39:57.806  3863  3863 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 14:39:57.807  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 14:39:57.808  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 14:39:57.810  2401  2420 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 14:39:57.810  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:39:57.811  2401  2423 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 14:39:57.811  3863  3915 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 14:39:57.815  2401  2420 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 14:39:57.815  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:39:57.815  2401  2423 D BtGatt.ScanManager: Starting BLE batch scan
08-29 14:39:57.815  2401  2423 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 14:39:57.824  2401  2420 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 14:39:57.824  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:39:57.829  2401  2420 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 14:39:57.829  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:39:58.308  3863  3863 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-29 14:39:58.309  3863  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:39:58.309  3863  3863 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 14:39:59.352  2401  2401 D BtGatt.ScanManager: awakened up at time 144967
,08-29 14:39:59.354  2401  2423 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 14:39:59.423  2401  2420 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-29 14:39:59.423  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:39:59.424  2401  2420 D BtGatt.GattService: current time is 145039231123
,08-29 14:39:59.425  2401  2420 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -85, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -83, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -68, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -68, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, -52, 11, 57, -70, 107, -17, 1, 0, -102, 3, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, 116, -43, -111, -91, -20, -29, 1, -128, -102, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -88, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-29 14:39:59.429  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-29 14:39:59.431  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-29 14:39:59.432  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-29 14:39:59.433  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-29 14:39:59.433  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
,08-29 14:39:59.434  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-29 14:39:59.435  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-29 14:39:59.507  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:39:59.513  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:39:59.515  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:39:59.537  1511  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-29 14:39:59.537  1511  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 14:39:59.537  1511  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:39:59.537  1511  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:39:59.564  3528  3528 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-29 14:39:59.564  3528  3528 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 14:39:59.564  3528  3528 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-29 14:40:00.564   873  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 14:40:00.926  2401  2401 D BtGatt.ScanManager: awakened up at time 146541
,08-29 14:40:00.928  2401  2423 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 14:40:00.976  2401  2420 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-29 14:40:00.977  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:40:00.977  2401  2420 D BtGatt.GattService: current time is 146593035027
,08-29 14:40:00.978  2401  2420 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -84, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -90, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -91, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -73, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -64, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -78, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-29 14:40:00.979  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-29 14:40:00.980  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-29 14:40:00.981  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-29 14:40:00.982  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-29 14:40:00.983  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-29 14:40:00.984  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-29 14:40:02.179  2401  2401 D BtGatt.ScanManager: awakened up at time 147794
08-29 14:40:02.180  2401  2423 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 14:40:02.197  2401  2420 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 14:40:02.198  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:40:02.424  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 14:40:02.425  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 14:40:02.425  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 14:40:02.426  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:40:02.485  3565  3928 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 14:40:02.485  3565  3928 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 14:40:02.485  3565  3928 E HttpOperation: 	at jdm.a(PG:82)
08-29 14:40:02.485  3565  3928 E HttpOperation: 	at jcs.o(PG:406)
08-29 14:40:02.485  3565  3928 E HttpOperation: 	at jcn.a(PG:1379)
08-29 14:40:02.485  3565  3928 E HttpOperation: 	at jcs.i(PG:143)
08-29 14:40:02.485  3565  3928 E HttpOperation: 	at blb.a(PG:3937)
08-29 14:40:02.485  3565  3928 E HttpOperation: 	at czp.a(PG:18188)
08-29 14:40:02.485  3565  3928 E HttpOperation: 	at czp.a(PG:9081)
08-29 14:40:02.485  3565  3928 E HttpOperation: 	at czq.run(PG:1686)
08-29 14:40:02.485  3565  3928 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 14:40:02.485  3565  3928 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 14:40:02.485  3565  3928 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 14:40:02.485  3565  3928 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 14:40:02.485  3565  3928 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 14:40:02.485  3565  3928 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 14:40:02.485  3565  3928 E HttpOperation: 	at jdj.a(PG:4091)
08-29 14:40:02.485  3565  3928 E HttpOperation: 	at jdj.a(PG:1125)
08-29 14:40:02.485  3565  3928 E HttpOperation: 	at jdm.a(PG:77)
08-29 14:40:02.485  3565  3928 E HttpOperation: 	... 12 more
08-29 14:40:02.485  3565  3928 E HttpOperation: Caused by: faj: BadAuthentication
08-29 14:40:02.485  3565  3928 E HttpOperation: 	at fal.a(PG:38)
08-29 14:40:02.485  3565  3928 E HttpOperation: 	at jdj.a(PG:4089)
08-29 14:40:02.485  3565  3928 E HttpOperation: 	... 14 more
,08-29 14:40:02.578  1511  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-29 14:40:02.579  1511  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 14:40:02.579  1511  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 14:40:02.581  1511  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:40:02.603  3565  3928 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 14:40:02.603  3565  3928 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 14:40:02.603  3565  3928 E HttpOperation: 	at jdm.a(PG:82)
08-29 14:40:02.603  3565  3928 E HttpOperation: 	at jcs.o(PG:406)
08-29 14:40:02.603  3565  3928 E HttpOperation: 	at jcn.a(PG:1379)
08-29 14:40:02.603  3565  3928 E HttpOperation: 	at jcs.i(PG:143)
08-29 14:40:02.603  3565  3928 E HttpOperation: 	at hec.a(PG:42)
08-29 14:40:02.603  3565  3928 E HttpOperation: 	at hee.a(PG:102)
08-29 14:40:02.603  3565  3928 E HttpOperation: 	at czr.a(PG:65)
08-29 14:40:02.603  3565  3928 E HttpOperation: 	at kka.a(PG:108)
08-29 14:40:02.603  3565  3928 E HttpOperation: 	at czp.a(PG:19176)
08-29 14:40:02.603  3565  3928 E HttpOperation: 	at czp.a(PG:9081)
08-29 14:40:02.603  3565  3928 E HttpOperation: 	at czq.run(PG:1686)
08-29 14:40:02.603  3565  3928 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 14:40:02.603  3565  3928 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 14:40:02.603  3565  3928 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 14:40:02.603  3565  3928 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 14:40:02.603  3565  3928 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 14:40:02.603  3565  3928 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 14:40:02.603  3565  3928 E HttpOperation: 	at jdj.a(PG:4091)
08-29 14:40:02.603  3565  3928 E HttpOperation: 	at jdj.a(PG:1125)
08-29 14:40:02.603  3565  3928 E HttpOperation: 	at jdm.a(PG:77)
08-29 14:40:02.603  3565  3928 E HttpOperation: 	... 15 more
08-29 14:40:02.603  3565  3928 E HttpOperation: Caused by: faj: BadAuthentication
08-29 14:40:02.603  3565  3928 E HttpOperation: 	at fal.a(PG:38)
08-29 14:40:02.603  3565  3928 E HttpOperation: 	at jdj.a(PG:4089)
08-29 14:40:02.603  3565  3928 E HttpOperation: 	... 17 more
,08-29 14:40:02.604  3565  3928 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 14:40:02.604  3565  3928 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 14:40:02.604  3565  3928 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 14:40:02.604  3565  3928 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 14:40:02.604  3565  3928 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 14:40:02.604  3565  3928 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 14:40:02.604  3565  3928 E ExperimentLoader: 	at hec.a(PG:42)
08-29 14:40:02.604  3565  3928 E ExperimentLoader: 	at hee.a(PG:102)
08-29 14:40:02.604  3565  3928 E ExperimentLoader: 	at czr.a(PG:65)
08-29 14:40:02.604  3565  3928 E ExperimentLoader: 	at kka.a(PG:108)
08-29 14:40:02.604  3565  3928 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 14:40:02.604  3565  3928 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 14:40:02.604  3565  3928 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 14:40:02.604  3565  3928 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 14:40:02.604  3565  3928 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 14:40:02.604  3565  3928 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 14:40:02.604  3565  3928 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 14:40:02.604  3565  3928 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 14:40:02.604  3565  3928 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 14:40:02.604  3565  3928 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 14:40:02.604  3565  3928 E ExperimentLoader: 	at jdj.a(PG:1125)
08-29 14:40:02.604  3565  3928 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 14:40:02.604  3565  3928 E ExperimentLoader: 	... 15 more
08-29 14:40:02.604  3565  3928 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 14:40:02.604  3565  3928 E ExperimentLoader: 	at fal.a(PG:38)
08-29 14:40:02.604  3565  3928 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 14:40:02.604  3565  3928 E ExperimentLoader: 	... 17 more
,08-29 14:40:02.761   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 147760, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-29 14:40:02.817  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 14:40:02.818  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:40:02.818  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 14:40:02.818  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:02.819  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 14:40:02.819  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 14:40:02.819  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 14:40:02.819  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 14:40:02.820  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 14:40:02.821  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 14:40:02.821  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 14:40:02.823  3863  3915 D BluetoothAdapter: STATE_ON
08-29 14:40:02.824  2401  2446 D BtGatt.GattService: stopScan() - queue size =1
,08-29 14:40:02.829  2401  2437 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 14:40:02.830  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:40:02.830  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 14:40:02.830  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 14:40:02.830  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 14:40:02.831  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 14:40:02.831  2401  2401 D BtGatt.ScanManager: awakened up at time 148446
08-29 14:40:02.837  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:40:02.837  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 14:40:02.837  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 14:40:02.839  2401  2420 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 14:40:02.839  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:40:02.840  2401  2423 D BtGatt.ScanManager: stopping BLe Batch
,08-29 14:40:02.839  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 14:40:02.841  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 14:40:02.842  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:40:02.842  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:40:02.843  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 14:40:02.843  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 not in the list
,08-29 14:40:02.843  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:02.843  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:02.843  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:40:02.843  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:40:02.843  3863  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:40:02.843  3863  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:40:02.844  3863  3863 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 14:40:02.845  2401  2420 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 14:40:02.845  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:40:02.845  2401  2423 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 14:40:02.853  2401  2420 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 14:40:02.853  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:40:02.858  3759  3930 I BooksSync: Starting books sync for 61035162, extras: ade
,08-29 14:40:02.872  3759  3931 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-29 14:40:02.898  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 14:40:02.898  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 14:40:02.898  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 14:40:02.899  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:40:02.971  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 14:40:02.971  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 14:40:02.972  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:40:02.972  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:40:03.017  3759  3931 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-29 14:40:03.023  3759  3930 E BooksSync: Soft error
08-29 14:40:03.023  3759  3930 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 14:40:03.023  3759  3930 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 14:40:03.023  3759  3930 E BooksSync: Sync error
08-29 14:40:03.023  3759  3930 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 14:40:03.023  3759  3930 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 14:40:03.024  3759  3930 I BooksSync: Finished books sync
,08-29 14:40:03.044   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 148013, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 14:40:03.345  3863  3863 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 14:40:04.316   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-29 14:40:04.326  1878  1878 I Keyboard.Facilitator: onFinishInput()
,08-29 14:40:04.336   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 14:40:04.336   873   893 I Adreno  : Build Date                       : 10/20/15
08-29 14:40:04.336   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 14:40:04.336   873   893 I Adreno  : Local Branch                     : M14
08-29 14:40:04.336   873   893 I Adreno  : Remote Branch                    : 
08-29 14:40:04.336   873   893 I Adreno  : Remote Branch                    : 
08-29 14:40:04.336   873   893 I Adreno  : Reconstruct Branch               : 
,08-29 14:40:04.373   281  2018 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (200 us)
,08-29 14:40:04.982  3863  3863 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 14:40:04.982  3863  3863 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-29 14:40:05.042   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-29 14:40:05.044  3863  3863 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@74c7270 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@23e3e83, 16908290=android.view.AbsSavedState$1@23e3e83}, android:focusedViewId=100}]}]
,08-29 14:40:05.044  3863  3863 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-29 14:40:05.044  3863  3863 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 14:40:05.045  3863  3863 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-29 14:40:05.058   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-29 14:40:05.062   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-29 14:40:05.063   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-29 14:40:05.063   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-29 14:40:05.289   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-29 14:40:05.297   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-29 14:40:05.299   873  1340 D SurfaceControl: Excessive delay in setPowerMode(): 236ms
,08-29 14:40:05.302   873   893 I DreamManagerService: Entering dreamland.
,08-29 14:40:05.303   873   893 I PowerManagerService: Dozing...
,08-29 14:40:05.305   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-29 14:40:05.351   375  1321 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-29 14:40:05.351   375  1321 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-29 14:40:05.364   873  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 14:40:05.370  1938  3937 D NfcService: Discovery configuration equal, not updating.
,08-29 14:40:05.374   873  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-29 14:40:05.375   873  1313 E native  : do suspend false
,08-29 14:40:05.387   873  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 14:40:05.401   873  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 14:40:05.404   873  1313 E native  : do suspend true
,08-29 14:40:05.490   375  1286 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-29 14:40:05.490   375  1286 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-29 14:40:05.872   873  1313 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-29 14:40:07.846  3863  3915 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 14:40:07.852  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:40:07.867  3863  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:40:07.867  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:07.867  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:07.867  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:40:07.867  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:40:07.867  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:40:07.867  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:40:07.867  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:40:07.874  3863  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:40:07.875  3863  3915 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 14:40:07.875  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 14:40:07.876  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 14:40:07.879  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 14:40:07.880  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:40:07.882  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:07.882  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 14:40:07.889  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:40:07.893  3863  3915 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 14:40:07.893  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 14:40:07.906  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 14:40:07.907  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 14:40:07.908  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 14:40:07.914  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 14:40:07.914  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 14:40:07.914  3863  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 14:40:07.915  3863  3915 D BluetoothAdapter: STATE_ON
,08-29 14:40:07.918  2401  2412 D BtGatt.GattService: registerClient() - UUID=310068d8-99cb-4d90-ae7c-b7b756df826e
,08-29 14:40:07.919  2401  2420 D BtGatt.GattService: onClientRegistered() - UUID=310068d8-99cb-4d90-ae7c-b7b756df826e, clientIf=5
,08-29 14:40:07.920  3863  3874 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 14:40:07.921  2401  2445 D BtGatt.GattService: start scan with filters
,08-29 14:40:07.925  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 14:40:07.925  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 14:40:07.925  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 14:40:07.925  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 14:40:07.926  2401  2423 D BtGatt.ScanManager: handling starting scan
,08-29 14:40:07.929  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 14:40:07.929  3863  3863 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 14:40:07.930  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 14:40:07.931  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 14:40:07.934  3863  3915 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 14:40:07.937  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 14:40:07.937  3863  3915 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 14:40:07.937  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:40:07.937  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 14:40:07.937  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:40:07.937  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 14:40:07.938  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 14:40:07.938  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 14:40:07.938  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 14:40:07.938  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 14:40:07.938  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 14:40:07.938  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 14:40:07.941  2401  2420 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 14:40:07.942  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:40:07.942  2401  2423 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 14:40:07.943  3863  3915 D BluetoothAdapter: STATE_ON
08-29 14:40:07.944  2401  2446 D BtGatt.GattService: stopScan() - queue size =1
08-29 14:40:07.945  2401  2413 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 14:40:07.945  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 14:40:07.945  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 14:40:07.945  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 14:40:07.945  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 14:40:07.945  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 14:40:07.946  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:40:07.947  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 14:40:07.947  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 14:40:07.947  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 14:40:07.948  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 14:40:07.949  3863  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 14:40:07.949  3863  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:40:07.949  3863  3863 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:40:07.949  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:40:07.949  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:07.949  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 14:40:07.950  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 not in the list
,08-29 14:40:07.950  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:07.950  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:07.950  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:40:07.950  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:07.950  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:07.951  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:07.951  2401  2420 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 14:40:07.951  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:40:07.952  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:40:07.952  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:07.952  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:07.951  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:40:07.952  2401  2423 D BtGatt.ScanManager: Starting BLE batch scan
08-29 14:40:07.952  3863  3915 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 14:40:07.952  2401  2423 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 14:40:07.954  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:40:07.959  3863  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:40:07.959  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:07.959  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:07.959  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:40:07.959  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:40:07.959  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:40:07.959  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:40:07.959  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 14:40:07.961  3863  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:40:07.961  3863  3915 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 14:40:07.964  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:07.966  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 14:40:07.967  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-29 14:40:07.968  2401  2420 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 14:40:07.968  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:07.969  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 14:40:07.969  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:40:07.969  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 14:40:07.969  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:40:07.976  2401  2420 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 14:40:07.976  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:40:07.976  3863  3915 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 14:40:07.977  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 14:40:07.982  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 14:40:07.982  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 14:40:07.982  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 14:40:07.984  2401  2420 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 14:40:07.984  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:40:07.985  2401  2423 D BtGatt.ScanManager: stopping BLe Batch
08-29 14:40:07.986  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 14:40:07.986  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 14:40:07.986  3863  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 14:40:07.986  3863  3915 D BluetoothAdapter: STATE_ON
08-29 14:40:07.988  2401  2437 D BtGatt.GattService: registerClient() - UUID=070a55fc-ba15-47f8-a084-11dd7e443df4
08-29 14:40:07.988  2401  2420 D BtGatt.GattService: onClientRegistered() - UUID=070a55fc-ba15-47f8-a084-11dd7e443df4, clientIf=5
08-29 14:40:07.989  3863  3935 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 14:40:07.989  2401  2446 D BtGatt.GattService: start scan with filters
,08-29 14:40:07.990  2401  2420 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-29 14:40:07.991  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:40:07.991  2401  2423 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 14:40:07.991  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 14:40:07.991  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 14:40:07.991  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 14:40:07.991  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 14:40:07.994  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 14:40:07.994  3863  3863 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 14:40:07.994  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 14:40:07.996  2401  2420 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 14:40:07.996  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:40:07.996  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 14:40:07.997  2401  2423 D BtGatt.ScanManager: handling starting scan
08-29 14:40:07.998  3863  3915 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 14:40:08.002  2401  2420 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 14:40:08.002  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:40:08.003  2401  2423 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 14:40:08.007  2401  2420 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-29 14:40:08.008  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:40:08.008  2401  2423 D BtGatt.ScanManager: Starting BLE batch scan
08-29 14:40:08.008  2401  2423 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 14:40:08.016  2401  2420 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 14:40:08.016  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:40:08.025  2401  2420 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 14:40:08.025  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:40:08.495  3863  3863 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-29 14:40:08.495  3863  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 14:40:08.496  3863  3863 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 14:40:09.436  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:40:09.441  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:40:09.460  3816  3941 V GoogleAuthProtoRequest: [322] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 14:40:09.523  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-29 14:40:09.524  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-29 14:40:09.524  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:40:09.525  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:40:09.533  2401  2401 D BtGatt.ScanManager: awakened up at time 155148
,08-29 14:40:09.535  2401  2423 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 14:40:09.568  3816  3941 W ExperimentUpdateService: [322] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-29 14:40:09.570  3816  3941 W ExperimentUpdateService: [322] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 14:40:09.570  3816  3941 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 14:40:09.570  3816  3941 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-29 14:40:09.570  3816  3941 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-29 14:40:09.570  3816  3941 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-29 14:40:09.570  3816  3941 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-29 14:40:09.570  3816  3941 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-29 14:40:09.570  3816  3941 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-29 14:40:09.570  3816  3941 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-29 14:40:09.570  3816  3941 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-29 14:40:09.570  3816  3941 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-29 14:40:09.577  2401  2420 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
08-29 14:40:09.577  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:40:09.577  2401  2420 D BtGatt.GattService: current time is 155192928124
08-29 14:40:09.577  2401  2420 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -104, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -86, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -83, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -89, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -86, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-29 14:40:09.578  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-29 14:40:09.578  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-29 14:40:09.578  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-29 14:40:09.579  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-29 14:40:09.579  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-29 14:40:09.901  1511  3942 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-29 14:40:09.910  1511  3942 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-29 14:40:09.957  1511  3942 W Uploader:  no longer exists, so no auth token.
,08-29 14:40:10.081  2401  2401 D BtGatt.ScanManager: awakened up at time 155696
,08-29 14:40:10.083  2401  2423 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 14:40:10.149  2401  2420 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-29 14:40:10.150  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:40:10.150  2401  2420 D BtGatt.GattService: current time is 155765918337
,08-29 14:40:10.151  2401  2420 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -84, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -79, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -92, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -95, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -72, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -81, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -78, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-29 14:40:10.152  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-29 14:40:10.153  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-29 14:40:10.153  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-29 14:40:10.154  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-29 14:40:10.155  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-29 14:40:10.155  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-29 14:40:10.156  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-29 14:40:11.654  2401  2401 D BtGatt.ScanManager: awakened up at time 157269
,08-29 14:40:11.657  2401  2423 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 14:40:11.687  2401  2420 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-29 14:40:11.687  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:40:11.688  2401  2420 D BtGatt.GattService: current time is 157303955897
,08-29 14:40:11.689  2401  2420 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -63, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -66, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -89, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -74, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
08-29 14:40:11.690  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
08-29 14:40:11.691  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-29 14:40:11.692  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-29 14:40:11.693  2401  2420 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-29 14:40:12.998  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 14:40:12.999  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:40:12.999  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 14:40:13.000  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:13.000  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-29 14:40:13.000  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 14:40:13.000  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 14:40:13.001  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 14:40:13.001  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 14:40:13.002  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 14:40:13.002  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 14:40:13.004  3863  3915 D BluetoothAdapter: STATE_ON
08-29 14:40:13.006  2401  2445 D BtGatt.GattService: stopScan() - queue size =1
,08-29 14:40:13.009  2401  2437 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 14:40:13.013  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 14:40:13.013  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 14:40:13.013  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 14:40:13.014  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 14:40:13.014  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 14:40:13.019  2401  2401 D BtGatt.ScanManager: awakened up at time 158634
,08-29 14:40:13.021  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 14:40:13.022  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 14:40:13.022  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 14:40:13.022  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 14:40:13.023  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 14:40:13.026  3863  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 14:40:13.027  2401  2420 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-29 14:40:13.027  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:40:13.027  2401  2423 D BtGatt.ScanManager: stopping BLe Batch
08-29 14:40:13.028  3863  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:40:13.028  3863  3863 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 14:40:13.040  2401  2420 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 14:40:13.041  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:40:13.041  2401  2423 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 14:40:13.054  2401  2420 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 14:40:13.055  2401  2420 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:40:13.529  3863  3863 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 14:40:13.530  3863  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:40:13.530  3863  3863 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 14:40:16.700   873  1313 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-29 14:40:18.027  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 14:40:18.028  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:40:18.029  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 14:40:18.029  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:40:18.029  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.030  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 14:40:18.030  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 not in the list
08-29 14:40:18.030  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:40:18.030  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:18.031  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:40:18.031  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:40:18.033  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.033  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:40:18.036  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:40:18.037  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:40:18.037  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:18.037  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
,08-29 14:40:18.039  3863  3915 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 14:40:18.042  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 14:40:18.042  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:40:18.042  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 14:40:18.043  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:40:18.043  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.043  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:18.044  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 not in the list
08-29 14:40:18.044  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:18.044  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:18.045  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:40:18.046  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.046  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:40:18.046  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.046  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:18.048  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:40:18.048  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:40:18.048  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:18.048  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:18.049  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 14:40:18.049  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:40:18.049  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:40:18.049  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:40:18.049  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 14:40:18.049  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.050  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:18.050  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 not in the list
08-29 14:40:18.050  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:18.050  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:18.050  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:40:18.050  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.050  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:18.050  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.050  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:18.051  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 14:40:18.052  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:40:18.052  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:18.052  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:18.052  3863  3915 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 14:40:18.053  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:40:18.053  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:40:18.053  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:40:18.053  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:40:18.053  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.053  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:18.053  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 not in the list
08-29 14:40:18.053  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:18.053  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:18.053  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:40:18.054  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.054  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:18.054  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.054  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:40:18.055  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:40:18.056  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:40:18.056  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:18.056  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:18.056  3863  3915 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 14:40:18.057  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:40:18.057  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:40:18.057  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:40:18.057  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 14:40:18.057  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.057  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:18.057  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 not in the list
08-29 14:40:18.057  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:18.057  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:18.057  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:40:18.057  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.058  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:18.058  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.058  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:40:18.059  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:40:18.059  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:40:18.059  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:18.059  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:18.060  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 14:40:18.060  3863  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 14:40:18.060  3863  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 14:40:18.060  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 14:40:18.060  3863  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 14:40:18.060  3863  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 14:40:18.060  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 14:40:18.061  3863  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 14:40:18.061  3863  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 14:40:18.061  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:40:18.061  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:40:18.061  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:40:18.061  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:40:18.061  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.061  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:18.061  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 not in the list
,08-29 14:40:18.062  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:18.062  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:18.062  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:40:18.062  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.062  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:18.062  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.062  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:18.063  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:40:18.063  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:40:18.063  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:18.064  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:18.065  3863  3915 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 14:40:18.065  3863  3915 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 14:40:18.065  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 14:40:18.069  3863  3915 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 14:40:18.070  3863  3915 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 14:40:18.070  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 14:40:18.070  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 14:40:18.070  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 14:40:18.070  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 14:40:18.070  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 14:40:18.071  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 14:40:18.071  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 14:40:18.071  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 14:40:18.071  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 14:40:18.071  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-29 14:40:18.071  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 14:40:18.071  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 14:40:18.071  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-29 14:40:18.071  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 14:40:18.071  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 14:40:18.071  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 14:40:18.072  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 14:40:18.072  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 14:40:18.072  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-29 14:40:18.072  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 14:40:18.072  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 14:40:18.072  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 14:40:18.072  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-29 14:40:18.072  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 14:40:18.072  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 14:40:18.072  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-29 14:40:18.072  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 14:40:18.073  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 14:40:18.073  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 14:40:18.073  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 14:40:18.073  3863  3915 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-29 14:40:18.073  3863  3915 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 14:40:18.074  3863  3915 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 14:40:18.074  3863  3915 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 14:40:18.074  3863  3915 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 14:40:18.074  3863  3915 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 14:40:18.074  3863  3915 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 14:40:18.074  3863  3915 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 14:40:18.074  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-29 14:40:18.077  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 14:40:18.079  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 14:40:18.079  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-29 14:40:18.079  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 14:40:18.080  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 14:40:18.080  3863  3915 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 14:40:18.080  3863  3915 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 14:40:18.080  3863  3915 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 14:40:18.081  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:40:18.081  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:40:18.081  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:40:18.081  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:40:18.081  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.081  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:18.082  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-29 14:40:18.084  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 not in the list
08-29 14:40:18.084  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:18.084  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:18.085  3863  3950 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 402)
,08-29 14:40:18.086  3863  3951 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 402
08-29 14:40:18.086  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:40:18.086  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.086  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:40:18.086  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.086  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:18.088  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:40:18.088  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:40:18.088  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:18.088  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
,08-29 14:40:18.090  3863  3915 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-29 14:40:18.091  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:40:18.091  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:40:18.091  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:40:18.091  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:40:18.091  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.091  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:18.092  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 not in the list
,08-29 14:40:18.092  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:18.092  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:18.092  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:40:18.092  3863  3950 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 14:40:18.092  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.092  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:18.093  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.093  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:40:18.094  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:40:18.094  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:40:18.094  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:18.094  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
,08-29 14:40:18.095  3863  3915 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 14:40:18.095  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 14:40:18.095  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:40:18.095  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:40:18.095  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:40:18.096  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.096  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:18.096  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 not in the list
08-29 14:40:18.096  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:18.096  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:18.096  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:40:18.096  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.096  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:18.096  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.096  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:40:18.100  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 14:40:18.100  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:40:18.100  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:18.101  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
,08-29 14:40:18.103  3863  3915 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 14:40:18.103  3863  3915 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 14:40:18.103  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 14:40:18.104  3863  3915 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 14:40:18.104  3863  3915 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 14:40:18.104  3863  3915 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,08-29 14:40:18.105  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 14:40:18.105  3863  3915 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 14:40:18.105  3863  3915 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 14:40:18.105  3863  3915 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 14:40:18.106  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 14:40:18.106  3863  3915 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,08-29 14:40:18.106  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:40:18.107  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:40:18.107  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:40:18.107  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 14:40:18.107  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.108  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:18.108  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 not in the list
08-29 14:40:18.108  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:18.108  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
,08-29 14:40:18.108  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:40:18.108  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.108  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:18.109  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.109  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:18.110  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:40:18.110  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 14:40:18.110  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:18.110  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:18.111  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:40:18.111  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.111  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:18.111  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 not in the list
08-29 14:40:18.111  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:40:18.111  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:18.111  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:40:18.111  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:18.111  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:40:19.838  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:40:19.854  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:40:19.860  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:40:19.915  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-29 14:40:19.915  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 14:40:19.916  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 14:40:19.916  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:40:19.963  3528  3528 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-29 14:40:19.964  3528  3528 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-29 14:40:19.965  3528  3528 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-29 14:40:23.112  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:40:23.113  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
,08-29 14:40:23.113  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:40:23.113  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:40:23.114  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:23.114  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 not in the list
08-29 14:40:23.115  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:40:23.115  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:40:23.115  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:40:23.116  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:40:23.116  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:40:23.116  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:23.117  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 not in the list
08-29 14:40:23.117  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:40:23.117  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:23.118  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:40:23.118  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:23.118  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:40:23.119  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:23.119  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:40:23.123  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:40:23.123  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 14:40:23.123  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:23.124  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:23.128  3863  3915 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 14:40:23.130  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:40:23.132  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 14:40:23.134  3863  3915 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 14:40:23.134  3863  3915 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 14:40:23.135  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 14:40:23.135  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 14:40:23.135  3863  3863 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 14:40:23.136  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:40:23.136  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 14:40:23.136  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 14:40:23.136  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-29 14:40:23.137  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:23.137  3863  3915 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 14:40:23.137  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 not in the list
08-29 14:40:23.137  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:23.137  3863  3863 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-29 14:40:23.137  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 14:40:23.138  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 14:40:23.138  3863  3952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 14:40:23.138  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 14:40:23.138  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:23.138  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:23.138  3863  3952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-29 14:40:23.142  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 14:40:23.142  3863  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 14:40:23.143  3863  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:40:23.142  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:23.143  3863  3863 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 14:40:23.143  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:40:23.143  3863  3863 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:40:23.143  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:40:23.144  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:40:23.145  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:40:23.145  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:40:23.146  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:23.146  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 not in the list
,08-29 14:40:23.147  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:23.148  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
,08-29 14:40:23.148  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:40:23.150  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:23.150  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:40:23.150  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:23.151  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:40:23.154  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:40:23.154  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 14:40:23.154  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:23.154  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
,08-29 14:40:23.157  3863  3915 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-29 14:40:23.158  3863  3915 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 14:40:23.158  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 14:40:23.159  3863  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 14:40:23.159  3863  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 14:40:23.159  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:40:23.160  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:40:23.160  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 14:40:23.161  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 14:40:23.162  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:40:23.162  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:23.162  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 not in the list
08-29 14:40:23.162  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:23.163  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:23.163  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 14:40:23.163  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:23.163  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:23.163  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:23.163  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:23.165  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 14:40:23.165  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:40:23.165  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:23.165  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
,08-29 14:40:23.173  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:40:23.173  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:40:23.173  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:40:23.173  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:40:23.173  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:23.173  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:40:23.173  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 not in the list
08-29 14:40:23.173  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:23.173  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:23.173  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:40:23.174  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:23.174  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:23.174  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:40:23.174  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:23.175  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:40:23.175  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:40:23.175  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:23.175  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:23.176  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 14:40:23.176  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:40:23.176  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 14:40:23.176  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:40:23.176  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:23.177  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:23.177  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27753e8 not in the list
08-29 14:40:23.177  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:23.177  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:23.177  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:40:23.177  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:23.177  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:23.177  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:40:23.177  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:23.179  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:40:23.179  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:40:23.179  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:23.179  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cf9a01 not in the list
08-29 14:40:23.180  3863  3915 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 14:40:23.180  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 14:40:23.181  3863  3915 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-29 14:40:23.181  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 14:40:23.181  3863  3915 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 14:40:23.181  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 14:40:23.184  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 14:40:23.184  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 14:40:23.185  3863  3915 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-29 14:40:23.185  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 14:40:23.185  3863  3915 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-29 14:40:23.185  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 14:40:23.186  3863  3915 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 14:40:23.186  3863  3915 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 14:40:23.186  3863  3915 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 14:40:23.186  3863  3915 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 14:40:23.187  3863  3915 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 14:40:23.187  3863  3915 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 14:40:23.187  3863  3915 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 14:40:23.187  3863  3915 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 14:40:23.188  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:40:23.188  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b1b8718 added. We now have 3 listener(s)
,08-29 14:40:23.189  3863  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:40:23.191  3863  3915 D BluetoothAdapter: enable(): BT is already enabled..!
,08-29 14:40:23.192   873  1698 D WifiService: setWifiEnabled: true pid=3863, uid=10000
08-29 14:40:23.193   873  1698 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 14:40:23.225  2401  2432 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-29 14:40:23.225  2401  2434 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
08-29 14:40:23.226  3863  3950 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 402)
,08-29 14:40:23.644  3863  3863 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 14:40:24.650  1511  3942 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-29 14:40:24.651  1511  3942 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-29 14:40:24.651  1511  3942 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:40:24.651  1511  3942 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:40:24.674  1511  3942 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-29 14:40:24.674  1511  3942 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-29 14:40:24.674  1511  3942 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-29 14:40:24.674  1511  3942 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-29 14:40:24.674  1511  3942 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-29 14:40:24.674  1511  3942 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-29 14:40:24.674  1511  3942 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-29 14:40:24.674  1511  3942 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-29 14:40:24.674  1511  3942 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-29 14:40:24.674  1511  3942 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-29 14:40:24.674  1511  3942 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-29 14:40:24.674  1511  3942 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-29 14:40:24.674  1511  3942 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-29 14:40:25.042  1511  3942 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-29 14:40:25.043  1511  3942 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-29 14:40:25.043  1511  3942 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:40:25.044  1511  3942 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:40:25.094  1511  3942 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-29 14:40:25.094  1511  3942 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-29 14:40:25.094  1511  3942 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-29 14:40:25.094  1511  3942 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-29 14:40:25.094  1511  3942 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-29 14:40:25.094  1511  3942 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-29 14:40:25.094  1511  3942 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-29 14:40:25.094  1511  3942 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-29 14:40:25.094  1511  3942 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-29 14:40:25.094  1511  3942 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-29 14:40:25.094  1511  3942 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-29 14:40:25.094  1511  3942 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-29 14:40:25.094  1511  3942 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-29 14:40:25.647  1511  3942 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-29 14:40:25.647  1511  3942 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-29 14:40:25.648  1511  3942 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:40:25.648  1511  3942 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:40:25.695  1511  3942 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-29 14:40:25.695  1511  3942 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-29 14:40:25.695  1511  3942 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-29 14:40:25.695  1511  3942 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-29 14:40:25.695  1511  3942 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-29 14:40:25.695  1511  3942 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-29 14:40:25.695  1511  3942 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-29 14:40:25.695  1511  3942 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-29 14:40:25.695  1511  3942 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-29 14:40:25.695  1511  3942 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-29 14:40:25.695  1511  3942 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-29 14:40:25.695  1511  3942 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-29 14:40:25.695  1511  3942 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-29 14:40:28.202  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:40:28.203  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2720571 added. We now have 4 listener(s)
,08-29 14:40:28.203  3863  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:40:28.219  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:40:28.220  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2720571 removed from the list
08-29 14:40:28.220  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 14:40:28.220  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:28.221  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:28.223  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 14:40:28.223  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e9aef56 added. We now have 4 listener(s)
08-29 14:40:28.224  3863  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:40:28.227  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:40:28.228  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e9aef56 removed from the list
,08-29 14:40:28.228  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:40:28.228  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:28.229  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:40:28.231  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:40:28.231  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f684bd7 added. We now have 4 listener(s)
08-29 14:40:28.232  3863  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:40:28.239   873  1963 D WifiService: setWifiEnabled: false pid=3863, uid=10000
,08-29 14:40:28.239   873  1963 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 14:40:28.253  2401  2416 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 14:40:28.254  2401  2416 D BluetoothAdapterProperties: Setting state to 13
,08-29 14:40:28.254  2401  2416 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 14:40:28.257  2401  2416 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 14:40:28.263  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:40:28.264  2401  2416 I BluetoothAdapterState: Entering PendingCommandState
08-29 14:40:28.265  2401  2401 D BluetoothMapService: onReceive
08-29 14:40:28.265  2401  2401 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:40:28.265  2401  2401 D BluetoothMapService: STATE_TURNING_OFF
08-29 14:40:28.265  2401  2401 D BluetoothMapService: MAP Service closeService in
08-29 14:40:28.265  2401  2401 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 14:40:28.266  2401  2401 D ObexServerSockets0: shutdown(block = true)
08-29 14:40:28.266  2401  2401 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-29 14:40:28.267  2401  2401 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 14:40:28.267  2401  2434 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 14:40:28.267  2401  2447 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 14:40:28.270  2401  2448 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 14:40:28.275  2401  2401 I BtOppRfcommListener: stopping Accept Thread
08-29 14:40:28.276  2401  3419 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 14:40:28.277  1446  1446 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-29 14:40:28.277  2401  3419 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 14:40:28.283  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:28.283  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:28.283  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:28.283  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:28.283  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:40:28.283  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:28.283  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:40:28.283  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:40:28.283  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:40:28.283   873  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 14:40:28.283   873  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 14:40:28.283   873  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 14:40:28.283   873  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 14:40:28.285  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:28.285  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:40:28.286  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:28.286  3863  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:40:28.286  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:28.286  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:28.286  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:40:28.286  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:28.286  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:40:28.286  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:40:28.286  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:40:28.287  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:28.287  3863  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:40:28.287  3863  3915 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 14:40:28.289  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:40:28.289  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:28.289  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:28.289  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:28.289  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:40:28.289  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:28.289  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:40:28.289  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:40:28.289  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:40:28.290  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:28.290  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:40:28.293  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:28.294   873  1313 E native  : do suspend true
,08-29 14:40:28.295   873   886 I ActivityManager: Start proc 3960:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-29 14:40:28.295  2401  2420 D BluetoothAdapterProperties: Scan Mode:20
,08-29 14:40:28.296  2401  2416 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-29 14:40:28.297  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:40:28.300  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:40:28.301  2401  2401 D HeadsetService: Received stop request...Stopping profile...
,08-29 14:40:28.302  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:28.302  2401  2401 D A2dpService: Received stop request...Stopping profile...
08-29 14:40:28.303  2401  2440 D A2dpStateMachine: Exit Disconnected: -1
08-29 14:40:28.303  1383  1904 D BluetoothHeadset: Proxy object disconnected
08-29 14:40:28.303  1953  2108 D BluetoothHeadset: Proxy object disconnected
08-29 14:40:28.304   873   873 D BluetoothHeadset: Proxy object disconnected
08-29 14:40:28.304   873   873 D BluetoothHeadset: Proxy object disconnected
08-29 14:40:28.304   873   873 D BluetoothHeadset: Proxy object disconnected
08-29 14:40:28.304   873   873 D BluetoothA2dp: Proxy object disconnected
08-29 14:40:28.305  2401  2401 D HidService: Received stop request...Stopping profile...
,08-29 14:40:28.305  2401  2401 D HidService: Stopping Bluetooth HidService
08-29 14:40:28.306  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:28.307  2401  2401 D HealthService: Received stop request...Stopping profile...
08-29 14:40:28.308  2401  2401 V BluetoothAdapterState: isTurningOff()=true
08-29 14:40:28.308  2401  2401 V BluetoothAdapterState: isTurningOn()=false
08-29 14:40:28.308  2401  2401 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:40:28.308  2401  2401 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:40:28.308   371   872 D CommandListener: Clearing all IP addresses on wlan0
08-29 14:40:28.308   873  1860 D DhcpClient: Clearing IP address
08-29 14:40:28.309  2401  2401 D PanService: Received stop request...Stopping profile...
08-29 14:40:28.310  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:28.311  1511  2107 V NativeCrypto: Read error: ssl=0xaedbdc00: I/O error during system call, Connection timed out
08-29 14:40:28.312   371   872 D CommandListener: Setting iface cfg
,08-29 14:40:28.312  2401  2401 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-29 14:40:28.312  2401  2420 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-29 14:40:28.313  2401  2432 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 14:40:28.313  2401  2401 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 14:40:28.313  2401  2432 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 14:40:28.313  2401  2432 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 14:40:28.313  2401  2420 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 14:40:28.313  1511  2107 V NativeCrypto: SSL shutdown failed: ssl=0xaedbdc00: I/O error during system call, Broken pipe
08-29 14:40:28.314  2401  2401 D BluetoothMapService: Received stop request...Stopping profile...
08-29 14:40:28.314  2401  2401 D BluetoothMapService: stop()
08-29 14:40:28.316   873   883 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-29 14:40:28.316   873  1852 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-29 14:40:28.319   873  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-29 14:40:28.319   873  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-29 14:40:28.319   873  1313 D WifiStateMachine: Start Disconnecting Watchdog 1
08-29 14:40:28.319  2401  2401 D BluetoothMapAppObserver: deinitObservers()
,08-29 14:40:28.319   873  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 14:40:28.319  2401  2401 D BluetoothMapAppObserver: removeReceiver()
08-29 14:40:28.319   873  1313 E native  : do suspend true
,08-29 14:40:28.324   400   400 E Parcel  : Reading a NULL string not supported here.
08-29 14:40:28.324   873  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-29 14:40:28.327   873  1852 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-29 14:40:28.327  2401  2401 V BluetoothAdapterState: isTurningOff()=true
08-29 14:40:28.327  2401  2401 V BluetoothAdapterState: isTurningOn()=false
08-29 14:40:28.327  2401  2401 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:40:28.327  2401  2401 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:40:28.326  1383  1383 D HeadsetProfile: Bluetooth service disconnected
08-29 14:40:28.328  1383  1383 D BluetoothA2dp: Proxy object disconnected
08-29 14:40:28.328  1383  1383 D BluetoothInputDevice: Proxy object disconnected
08-29 14:40:28.328  1383  1383 D HidProfile: Bluetooth service disconnected
,08-29 14:40:28.328  1383  1383 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 14:40:28.328  1383  1383 D PanProfile: Bluetooth service disconnected
08-29 14:40:28.328  1383  1383 D BluetoothMap: Proxy object disconnected
08-29 14:40:28.329  1383  1383 D MapProfile: Bluetooth service disconnected
08-29 14:40:28.329  2401  2420 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 14:40:28.329  2401  2432 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 14:40:28.329  2401  2432 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 14:40:28.329  2401  2432 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 14:40:28.329  2401  2401 V BluetoothAdapterState: isTurningOff()=true
,08-29 14:40:28.329  2401  2432 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 14:40:28.329  2401  2432 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 14:40:28.329  2401  2401 V BluetoothAdapterState: isTurningOn()=false
08-29 14:40:28.329  2401  2432 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 14:40:28.329  2401  2401 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:40:28.329  2401  2401 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:40:28.330  2401  2401 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 14:40:28.330  2401  2420 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 14:40:28.330  2401  2401 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 14:40:28.330  2401  2401 V BluetoothAdapterState: isTurningOff()=true
08-29 14:40:28.330  2401  2401 V BluetoothAdapterState: isTurningOn()=false
08-29 14:40:28.330  2401  2401 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 14:40:28.330  2401  2401 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:40:28.331  2401  2401 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 14:40:28.331  2401  2420 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 14:40:28.332  2401  2401 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-29 14:40:28.332  2401  2401 V BluetoothAdapterState: isTurningOff()=true
08-29 14:40:28.332  2401  2401 V BluetoothAdapterState: isTurningOn()=false
08-29 14:40:28.332  2401  2401 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:40:28.332  2401  2401 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:40:28.332  2401  2401 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 14:40:28.332  2401  2401 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 14:40:28.335  2401  2401 D BluetoothMapService: MAP Service closeService in
08-29 14:40:28.335  2401  2401 V BluetoothAdapterState: isTurningOff()=true
08-29 14:40:28.335  2401  2401 V BluetoothAdapterState: isTurningOn()=false
08-29 14:40:28.335  2401  2401 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:40:28.335  2401  2401 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:40:28.335  2401  2416 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 14:40:28.335  2401  2416 D BluetoothAdapterProperties: Setting state to 15
08-29 14:40:28.335  2401  2401 D BluetoothMapService: cleanup()
08-29 14:40:28.335  2401  2401 D BluetoothMapService: MAP Service closeService in
08-29 14:40:28.335  2401  2416 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 14:40:28.336  2401  2416 I BluetoothAdapterState: Entering BleOnState
08-29 14:40:28.336  1953  2108 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:40:28.338   873  1873 D DhcpClient: Receive thread stopped
08-29 14:40:28.339   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:40:28.339  1383  1904 D BluetoothPan: onBluetoothStateChange on: false
08-29 14:40:28.340   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:40:28.340  1383  1396 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 14:40:28.341   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 14:40:28.342  1383  1395 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 14:40:28.342  1383  1904 D BluetoothMap: onBluetoothStateChange: up=false
08-29 14:40:28.343  1383  1396 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:40:28.343  1383  1395 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 14:40:28.344   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:40:28.344  2401  2416 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 14:40:28.344  2401  2416 D BluetoothAdapterProperties: Setting state to 16
08-29 14:40:28.345  2401  2416 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 14:40:28.345  2401  2416 D BluetoothAdapterProperties: onBleDisable
08-29 14:40:28.345  2401  2416 I BluetoothAdapterState: Entering PendingCommandState
08-29 14:40:28.346  2401  2417 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 14:40:28.347  2401  2432 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 14:40:28.347  2401  2432 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 14:40:28.350  2401  2420 D BluetoothAdapterProperties: Scan Mode:20
08-29 14:40:28.355  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:28.355  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:28.355  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:28.355  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:28.355  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:40:28.355  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:28.355  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name:, null
08-29 14:40:28.355  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:40:28.355  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:40:28.356  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:28.356  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:40:28.357  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:28.357  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:28.357  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:28.357  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:28.357  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:40:28.357  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:28.357  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:40:28.357  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:40:28.357  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:40:28.358  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:28.358  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:40:28.358   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 14:40:28.359  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:28.359  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:28.359  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:28.359  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:28.359  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:40:28.359  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:28.359  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:40:28.359  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:40:28.359  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:40:28.360  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:28.360  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:40:28.361  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:28.362  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:28.363  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:28.369  3960  3960 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-29 14:40:28.378  3960  3960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 14:40:28.380   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 14:40:28.381   873  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 14:40:28.381   873  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 14:40:28.383   873   890 D Tethering: MasterInitialState.processMessage what=3
08-29 14:40:28.383   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@98dbadd:true
08-29 14:40:28.383   371   872 D CommandListener: Clearing all IP addresses on wlan0
08-29 14:40:28.385  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 14:40:28.386  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:28.388  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:28.389  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:28.389  3434  3434 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@f4d0ac4 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-29 14:40:28.401   873  1376 I ActivityManager: Start proc 3978:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-29 14:40:28.408  3960  3960 D LocalBluetoothProfileManager: Adding local MAP profile
08-29 14:40:28.412  3960  3960 D BluetoothMap: Create BluetoothMap proxy object
08-29 14:40:28.416  3960  3960 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-29 14:40:28.428  3960  3960 D DockEventReceiver: finishStartingService: stopping service
,08-29 14:40:28.436   873  1972 I ActivityManager: Killing 3587:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-29 14:40:28.443   371   872 E Netd    : netlink response contains error (No such file or directory)
,08-29 14:40:28.444   873  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 14:40:28.446  3978  3978 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-29 14:40:28.469   873  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 14:40:28.483   873  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 14:40:28.488   873  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 14:40:28.491  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:40:28.491  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:28.491  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:28.491  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:28.491  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:40:28.491  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:28.491  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:40:28.491  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:40:28.491  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:40:28.492  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:40:28.494  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:40:28.496  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:28.496  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:28.496  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:28.496  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:28.496  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:40:28.496  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:28.496  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:40:28.496  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:40:28.496  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:40:28.496  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:28.496  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:40:28.492  2056  2322 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:40:28.498  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:28.498  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:28.498  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:28.498  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:28.498  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:40:28.498  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:28.498  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:40:28.498  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:40:28.498  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:40:28.501  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:40:28.501  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:40:28.554  2401  2420 I bt_hci  : shut_down
08-29 14:40:28.554  2401  2424 D bt_hwcfg: hw_epilog_process
,08-29 14:40:28.556  2401  2424 I bt_vendor: low_power_mode_cb
,08-29 14:40:28.586  2401  2424 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-29 14:40:28.586  2401  2424 I bt_vendor: epilog_cb
,08-29 14:40:28.587  2401  2424 I bt_hci  : epilog_finished_callback
,08-29 14:40:28.591  2401  2420 I bt_hci_h4: hal_close
,08-29 14:40:28.592  2401  2420 I bt_userial_vendor: device fd = 51 close
,08-29 14:40:28.605  3978  3978 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 14:40:28.605  3978  3978 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 14:40:28.605  3978  3978 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 14:40:28.609  3978  3978 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 14:40:28.609  3978  3978 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 14:40:28.609  3978  3978 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 14:40:28.609  397,8  3978 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 14:40:28.609  3978  3978 D StrictMode: StrictMode policy violation; ~duration=84 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:4,0:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 14:40:28.609  3978  3978 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 14:40:28.609  3978  3978 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 14:40:28.609  3978  3978 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 14:40:28.610  3978  3978 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 14:40:28.610  3978  3978 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 14:40:28.610  3978  3978 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 14:40:28.610  3978  3978 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 14:40:28.610  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 14:40:28.610  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 14:40:28.610  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 14:40:28.610  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 14:40:28.610  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 14:40:28.610  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 14:40:28.610  3978  3978 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 14:40:28.610  3978  3978 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 14:40:28.610  3978  3978 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 14:40:28.610  3978  3978 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 14:40:28.610  3978  3978 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 14:40:28.610  3978  3978 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 14:40:28.610  3978  3978 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 14:40:28.610  3978  3978 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 14:40:28.610  3978  3978 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:40:28.610  3978  3978 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 14:40:28.610  3978  3978 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 14:40:28.648   873  1963 I ActivityManager: Start proc 4011:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-29 14:40:28.649   873  1963 I ActivityManager: Killing 3434:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-29 14:40:28.803  4011  4011 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-29 14:40:28.809  2401  2417 D bt_stack_manager: event_shut_down_stack finished.
,08-29 14:40:28.810  2401  2416 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 14:40:28.812  2401  2401 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 14:40:28.812  2401  2416 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 14:40:28.813  2401  2401 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 14:40:28.813  2401  2401 D BtGatt.GattService: stop()
,08-29 14:40:28.813  2401  2401 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 14:40:28.815  2401  2401 V BluetoothAdapterState: isTurningOff()=false
,08-29 14:40:28.815  2401  2401 V BluetoothAdapterState: isTurningOn()=false
08-29 14:40:28.815  2401  2401 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:40:28.815  2401  2401 V BluetoothAdapterState: isBleTurningOff()=true
,08-29 14:40:28.815  2401  2416 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 14:40:28.816  2401  2416 D BluetoothAdapterProperties: Setting state to 10
08-29 14:40:28.816  2401  2416 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 14:40:28.816  2401  2416 I BluetoothAdapterState: Entering OffState
,08-29 14:40:28.821   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-29 14:40:28.832  2401  2401 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 14:40:28.832  2401  2401 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 14:40:28.832  2401  2401 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 14:40:28.833  2401  2417 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 14:40:28.835  2401  2417 D bt_stack_manager: event_clean_up_stack finished.
,08-29 14:40:28.845  2401  2401 I art     : System.exit called, status: 0
,08-29 14:40:28.845  2401  2401 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 14:40:28.934   873  1405 I ActivityManager: Process com.android.bluetooth (pid 2401) has died
,08-29 14:40:28.976  3978  4008 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 14:40:29.075  4011  4031 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-29 14:40:29.075  4011  4031 I Babel_SMS: MmsConfig.loadMmsSettings
,08-29 14:40:29.082  4011  4031 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-29 14:40:29.082  4011  4031 I Babel_SMS: MmsConfig.loadFromDatabase
,08-29 14:40:29.112  4011  4031 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-29 14:40:29.112  4011  4031 I Babel_SMS: MmsConfig.loadFromResources
,08-29 14:40:29.115  4011  4031 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-29 14:40:29.120  4011  4031 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-29 14:40:29.147  4011  4011 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 14:40:29.150  4011  4011 I Babel_Crash: startup - clean
,08-29 14:40:29.160   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@143d575:true
,08-29 14:40:29.173  4011  4011 I Babel_telephony: TeleModule.launchCompleted
,08-29 14:40:29.185   873   884 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-29 14:40:29.196  4011  4011 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-29 14:40:29.203  4011  4011 W Babel   : BAM#gBA: invalid account id: -1
,08-29 14:40:29.203  4011  4011 W Babel   : BAM#gBA: invalid account id: -1
08-29 14:40:29.203  4011  4011 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-29 14:40:29.215  4011  4036 I Babel   : deleted: false for 0
,08-29 14:40:29.215   873  2123 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-29 14:40:29.230  3960  3960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 14:40:29.272   873  1972 I ActivityManager: Start proc 4039:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
08-29 14:40:29.274  3960  3960 D DockEventReceiver: finishStartingService: stopping service
,08-29 14:40:29.289  4011  4011 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 14:40:29.348  4011  4011 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-29 14:40:29.368  4011  4011 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 14:40:29.376  4011  4011 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 14:40:29.380  4011  4011 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 14:40:29.398  4011  4011 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 14:40:29.406  4011  4011 I vclib   : onServiceConnected
,08-29 14:40:29.430  4039  4039 D AdapterServiceConfig: Adding HeadsetService
,08-29 14:40:29.430  4039  4039 D AdapterServiceConfig: Adding A2dpService
08-29 14:40:29.430  4039  4039 D AdapterServiceConfig: Adding HidService
,08-29 14:40:29.430  4039  4039 D AdapterServiceConfig: Adding HealthService
08-29 14:40:29.430  4039  4039 D AdapterServiceConfig: Adding PanService
,08-29 14:40:29.430  4039  4039 D AdapterServiceConfig: Adding GattService
,08-29 14:40:29.431  4039  4039 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 14:40:29.434   873   883 I ActivityManager: Killing 3620:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-29 14:40:29.479  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 14:40:29.493  1721  1721 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 14:40:29.496  1721  1721 D SystemUpdateService: onCreate
,08-29 14:40:29.502  1721  1721 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 14:40:29.511  1721  4051 I SystemUpdateService: active receiver: enabled
,08-29 14:40:29.518  1721  4051 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 14:40:29.522  1721  4051 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-29 14:40:29.522  1721  4051 I SystemUpdateService: now status is 0 (complete)
08-29 14:40:29.522  1721  4051 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 14:40:29.522  1721  4051 I SystemUpdateService: file has been verified
,08-29 14:40:29.523  1721  4051 I SystemUpdateService: OTA package size = 12249756
,08-29 14:40:29.527  1721  1721 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 14:40:29.532  1721  2474 I iu.UploadsManager: num queued entries: 0,
,08-29 14:40:29.533  1721  2474 I iu.UploadsManager: num updated entries: 0
,08-29 14:40:29.536  1721  2474 I iu.SyncManager: NEXT; no task
,08-29 14:40:29.541  1721  4051 I SystemUpdateService: showing system update notification
,08-29 14:40:29.547  1721  1721 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 14:40:29.549  1721  1721 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 14:40:29.568   873   884 I ActivityManager: Start proc 4053:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-29 14:40:29.570  1721  1721 D SystemUpdateService: onDestroy
,08-29 14:40:29.599  4053  4053 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-29 14:40:29.602  4053  4053 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:40:29.607  4053  4053 D SprintDMHelper: simOperator: 
,08-29 14:40:29.607  4053  4053 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 14:40:29.620   873  1376 I ActivityManager: Start proc 4065:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-29 14:40:29.621   873  1376 I ActivityManager: Killing 3510:android.process.acore/u0a5 (adj 15): empty #17
,08-29 14:40:29.752   873  2122 I ActivityManager: Start proc 4080:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-29 14:40:29.755  4011  4079 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-29 14:40:29.759   873   883 I ActivityManager: Killing 3658:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-29 14:40:29.836  4080  4080 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-29 14:40:29.899  4080  4080 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-29 14:40:29.899  4080  4080 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 14:40:29.899  4080  4080 I GAv4    :   adb logcat -s GAv4
,08-29 14:40:29.920  4080  4080 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 14:40:29.926  4080  4080 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 14:40:29.963  4080  4097 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 14:40:30.079  4080  4080 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-29 14:40:30.119  4080  4080 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-29 14:40:30.130  4080  4080 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 5738-5745)
,08-29 14:40:30.130  4080  4080 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 14:40:30.139  4080  4080 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fd841de}
,08-29 14:40:30.139  4080  4080 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-29 14:40:30.139  4080  4080 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 14:40:30.147  4080  4080 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-29 14:40:30.148  4080  4080 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 14:40:30.170  4080  4080 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-29 14:40:30.185  4080  4080 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 14:40:30.185  4080  4080 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 14:40:30.186  4080  4080 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-29 14:40:30.186  4080  4080 I Adreno  : Build Date                       : 10/20/15
08-29 14:40:30.186  4080  4080 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 14:40:30.186  4080  4080 I Adreno  : Local Branch                     : M14
08-29 14:40:30.186  4080  4080 I Adreno  : Remote Branch                    : 
08-29 14:40:30.186  4080  4080 I Adreno  : Remote Branch                    : 
08-29 14:40:30.186  4080  4080 I Adreno  : Reconstruct Branch               : 
,08-29 14:40:30.248  4080  4080 I NSApplication: Starting up...
,08-29 14:40:30.258  4080  4126 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-29 14:40:30.288   873  2123 I ActivityManager: Start proc 4131:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-29 14:40:30.293   873  1697 I ActivityManager: Killing 3673:com.android.musicfx/u0a18 (adj 15): empty #17
,08-29 14:40:30.387  4131  4131 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-29 14:40:30.568   873  1405 I ActivityManager: Killing 2236:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-29 14:40:33.290   873  1376 D WifiService: setWifiEnabled: true pid=3863, uid=10000
,08-29 14:40:33.290   873  1376 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 14:40:33.305   873  1313 D WifiConfigStore: Loading config and enabling all networks 
08-29 14:40:33.313  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:40:33.313  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:33.313  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:33.313  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:33.313  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:40:33.313  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:33.313  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:40:33.313  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:40:33.313  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:40:33.314  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:33.314  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:40:33.317  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:33.318  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:33.318  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:33.318  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:33.318  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:40:33.318  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:33.318  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:40:33.318  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:40:33.318  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:40:33.318  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:33.318  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:40:33.320  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:40:33.320  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:33.320  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:33.320  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:33.320  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:40:33.320  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:33.320  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:40:33.320  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:40:33.320  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:40:33.321  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:33.322  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:40:33.340   873  1313 D WifiConfigStore: loaded 0 passpoint configs
,08-29 14:40:33.341   873  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-29 14:40:33.342   873  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 14:40:33.343   873  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 14:40:33.343   873  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-29 14:40:33.344   873  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-29 14:40:33.344   873  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 14:40:33.358   371   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 14:40:33.358   873  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 14:40:33.360   371   872 D CommandListener: Setting iface cfg
,08-29 14:40:33.368   873  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '131 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 131 Failed to set address (No such device)'
,08-29 14:40:33.369   873  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 14:40:33.370   873  1313 E native  : do suspend true
,08-29 14:40:33.379   873  1312 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 14:40:33.385   873  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 14:40:33.386   873  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 14:40:34.037   873   883 I ActivityManager: Killing 3703:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-29 14:40:34.746   873  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 14:40:34.777   873  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.81 rxSuccessRate=6.75 delta 1000 -> 994
,08-29 14:40:34.778   873  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-29 14:40:34.778   873  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 14:40:34.791   873  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 14:40:34.819   873  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 14:40:34.822  1446  1446 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 14:40:35.246  1446  1446 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 14:40:35.302  1446  1446 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 14:40:35.303  1446  1446 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 14:40:35.310   873  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 14:40:35.329   873  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 14:40:35.330   873  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-29 14:40:35.331   873  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 14:40:35.360   873  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 14:40:35.383   371   872 D CommandListener: Setting iface cfg
,08-29 14:40:35.383   873  1313 D WifiStateMachine: Start Dhcp Watchdog 2
,08-29 14:40:35.390   873  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 14:40:35.442   873  4157 D DhcpClient: Receive thread started
,08-29 14:40:35.528   873  1313 E native  : do suspend false
,08-29 14:40:35.532  2056  2760 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-29 14:40:35.552   873  1860 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 14:40:35.569   873  4157 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172641, domain null
,08-29 14:40:35.570   873  1860 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172641 seconds
,08-29 14:40:35.575   873  1860 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 14:40:35.589   873  4157 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 14:40:35.590   873  1860 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 14:40:35.597   371   872 D CommandListener: Setting iface cfg
,08-29 14:40:35.607   873  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 14:40:35.609   873  1860 D DhcpClient: Scheduling renewal in 86399s
,08-29 14:40:35.610   873  1313 E native  : do suspend true,
,08-29 14:40:35.632   873  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 14:40:35.636   873  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 14:40:35.637   873  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-29 14:40:35.639   873  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 14:40:35.640   873  1315 D ConnectivityService: Adding iface wlan0 to network 101
,08-29 14:40:35.684   873  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 14:40:35.684   873  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-29 14:40:35.687   873  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-29 14:40:35.688   873  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-29 14:40:35.690   873  1315 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-29 14:40:35.700   873  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 14:40:35.705   873  1315 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-29 14:40:35.706   873  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-29 14:40:35.706   873  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-29 14:40:35.706   873  1315 D ConnectivityService:    accepting network in place of null
08-29 14:40:35.706   873  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-29 14:40:35.707   873  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 14:40:35.708   873  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 14:40:35.729   873  4156 D NetlinkSocketObserver: NeighborEvent{elapsedMs=181344, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 14:40:35.745   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 14:40:35.800   873  4155 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.78,2a00:1450:4001:818::200e
,08-29 14:40:35.813   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 14:40:35.819   873  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-29 14:40:35.819   873  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:40:35.825   873  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-29 14:40:35.828   873   890 D Tethering: MasterInitialState.processMessage what=3
08-29 14:40:35.833  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:40:35.833  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:35.833  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:35.833  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:35.833  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:40:35.833  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:35.833  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:40:35.833  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:40:35.833  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 14:40:35.833  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:35.833  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:40:35.838  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:35.838  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:35.838  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:35.838  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:35.838  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:40:35.838  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:35.838  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:40:35.838  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:40:35.838  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:40:35.839  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:35.839  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:40:35.843  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:35.843  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:35.843  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:35.843  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:35.843  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:40:35.843  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:35.843  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:40:35.843  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:40:35.843  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 14:40:35.844  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:35.844  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:40:35.859  1721  1721 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 14:40:35.863  1721  1721 D SystemUpdateService: onCreate
,08-29 14:40:35.868  1721  1721 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 14:40:35.876  1721  4167 I SystemUpdateService: active receiver: enabled
,08-29 14:40:35.884  1721  4167 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 14:40:35.886  1721  1721 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 14:40:35.889  1721  2474 I iu.UploadsManager: num queued entries: 0
,08-29 14:40:35.891   873  4155 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 12:40:35 GMT], X-Android-Received-Millis=[1472474435891], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472474435844]}
,08-29 14:40:35.892   873  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-29 14:40:35.892   873  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-29 14:40:35.892   873  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-29 14:40:35.894   873  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-29 14:40:35.896  1721  1721 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 14:40:35.898  1721  1721 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 14:40:35.900  4053  4053 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:40:35.906  4053  4053 D SprintDMHelper: simOperator: 
,08-29 14:40:35.906  4053  4053 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 14:40:35.909  1721  4170 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-29 14:40:35.909  1721  4170 W BaseAppContext: Using Auth Proxy for data requests.
,08-29 14:40:35.916  1721  4170 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 14:40:35.927  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-29 14:40:35.930  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:40:35.931  1721  4167 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-29 14:40:35.939  1721  4167 I SystemUpdateService: now status is 0 (complete)
08-29 14:40:35.939  1721  4167 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 14:40:35.939  1721  4167 I SystemUpdateService: file has been verified
08-29 14:40:35.939  1721  4167 I SystemUpdateService: OTA package size = 12249756
,08-29 14:40:35.932  1721  2474 I iu.UploadsManager: num updated entries: 0
,08-29 14:40:35.944  1721  2474 I iu.SyncManager: NEXT; no task
,08-29 14:40:35.960  1721  4167 I SystemUpdateService: showing system update notification
,08-29 14:40:35.966  3780  4165 V KeepSync: Connecting to GoogleApiClient
,08-29 14:40:35.966   873  1405 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 14:40:35.984  1511  2173 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 14:40:35.984  1511  2173 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-29 14:40:35.985  1511  2173 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:40:35.985  1511  2173 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:40:36.006  1721  4170 E MDM     : [179] SitrepService.a: Error sending sitrep.
,08-29 14:40:36.010  1721  1721 D SystemUpdateService: onDestroy
,08-29 14:40:36.038  1511  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-29 14:40:36.038  1511  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-29 14:40:36.038  1511  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:40:36.038  1511  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:40:36.040  4011  4173 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 14:40:36.062  1721  4177 V BaseAuthAsyncOperation: access token request failed
,08-29 14:40:36.063  3780  4165 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 14:40:36.129  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-29 14:40:36.129  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-29 14:40:36.129  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 14:40:36.130  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:40:36.158  3780  4165 E KeepSync: IOException
08-29 14:40:36.158  3780  4165 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 14:40:36.158  3780  4165 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 14:40:36.158  3780  4165 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 14:40:36.158  3780  4165 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 14:40:36.158  3780  4165 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 14:40:36.158  3780  4165 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 14:40:36.158  3780  4165 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 14:40:36.158  3780  4165 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 14:40:36.158  3780  4165 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 14:40:36.158  3780  4165 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 14:40:36.158  3780  4165 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 14:40:36.158  3780  4165 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 14:40:36.158  3780  4165 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 14:40:36.158  3780  4165 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 14:40:36.158  3780  4165 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 14:40:36.158  3780  4165 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 14:40:36.158  3780  4165 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 14:40:36.158  3780  4165 E KeepSync: 	... 10 more
08-29 14:40:36.158  3780  4165 W KeepSync: Sync result 2
,08-29 14:40:36.171   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 149251, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 14:40:36.819   873  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-29 14:40:38.297   873   883 D WifiService: setWifiEnabled: false pid=3863, uid=10000
,08-29 14:40:38.297   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 14:40:38.335  1446  1446 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 14:40:38.344   873  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 14:40:38.344   873  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 14:40:38.345   873  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 14:40:38.345   873  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 14:40:38.364   873  1313 E native  : do suspend true
,08-29 14:40:38.381   873  1860 D DhcpClient: Clearing IP address
,08-29 14:40:38.381   371   872 D CommandListener: Clearing all IP addresses on wlan0
08-29 14:40:38.388  1511  4179 V NativeCrypto: Read error: ssl=0x9b060e00: I/O error during system call, Connection timed out
,08-29 14:40:38.388   371   872 D CommandListener: Setting iface cfg
08-29 14:40:38.392  1511  4179 V NativeCrypto: SSL shutdown failed: ssl=0x9b060e00: I/O error during system call, Broken pipe
,08-29 14:40:38.400   873  1698 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-29 14:40:38.400   873  4155 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-29 14:40:38.407   873  4155 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-29 14:40:38.409   873  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,08-29 14:40:38.409   873  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-29 14:40:38.418   873  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 14:40:38.421   873  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-29 14:40:38.421   873  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-29 14:40:38.421   873  1313 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-29 14:40:38.422   400   400 E Parcel  : Reading a NULL string not supported here.
,08-29 14:40:38.422   873  4157 D DhcpClient: Receive thread stopped
08-29 14:40:38.427   873  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 14:40:38.429   873  1313 E native  : do suspend true
,08-29 14:40:38.434   873  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-29 14:40:38.474   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 14:40:38.536   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 14:40:38.536   371   872 D CommandListener: Clearing all IP addresses on wlan0,
,08-29 14:40:38.541   873  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-29 14:40:38.541   873  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:40:38.553   873  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-29 14:40:38.554   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-29 14:40:38.573  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:40:38.574  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:38.574  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:38.574  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:38.574  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:40:38.574  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:38.574  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:40:38.574  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:40:38.574  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:40:38.574  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:38.575  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:40:38.576  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:40:38.577  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:38.577  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:38.577  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:38.577  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:40:38.577  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:38.577  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:40:38.577  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:40:38.577  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:40:38.577  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:38.577  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:40:38.578  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:40:38.578  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:38.578  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:38.578  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:38.578  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:40:38.578  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:38.578  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:40:38.578  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:40:38.578  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:40:38.578  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:38.578  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:40:38.585   873  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 14:40:38.587  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:38.587  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:38.587  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:38.587  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:38.587  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:40:38.587  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:38.587  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:40:38.587  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:40:38.587  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:40:38.587  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:40:38.588  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:40:38.588  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:38.588  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:38.588  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:38.588  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:38.588  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:40:38.588  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:38.588  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:40:38.588  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:40:38.588  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:40:38.588  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:38.589  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:40:38.589  1721  1721 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) },
08-29 14:40:38.589  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:38.589  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:38.589  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:38.589  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:38.589  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:40:38.589  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:38.589  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:40:38.589  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:40:38.589  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:40:38.589  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:38.590  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:40:38.590   873  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 14:40:38.590  2056  2322 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 14:40:38.592  1721  1721 D SystemUpdateService: onCreate
08-29 14:40:38.597  1721  1721 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 14:40:38.601  1721  4190 I SystemUpdateService: active receiver: enabled
,08-29 14:40:38.610  1721  4190 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 14:40:38.610  1721  1721 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 14:40:38.618  1721  2474 I iu.UploadsManager: num queued entries: 0
,08-29 14:40:38.618  1721  2474 I iu.UploadsManager: num updated entries: 0
08-29 14:40:38.619  1721  2474 I iu.SyncManager: NEXT; no task
,08-29 14:40:38.623  1721  4190 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-29 14:40:38.623  1721  4190 I SystemUpdateService: now status is 0 (complete)
08-29 14:40:38.623  1721  4190 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 14:40:38.623  1721  4190 I SystemUpdateService: file has been verified
,08-29 14:40:38.625  1721  1721 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 14:40:38.626  1721  1721 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 14:40:38.628  4053  4053 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:40:38.632  4053  4053 D SprintDMHelper: simOperator: 
08-29 14:40:38.632  4053  4053 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 14:40:38.635   371   872 E Netd    : netlink response contains error (No such file or directory)
08-29 14:40:38.636   873  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 14:40:38.645  1721  4190 I SystemUpdateService: OTA package size = 12249756
,08-29 14:40:38.656  4011  4194 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 14:40:38.674  1721  4190 I SystemUpdateService: showing system update notification
,08-29 14:40:38.684  1721  1721 D SystemUpdateService: onDestroy
,08-29 14:40:43.336  4039  4039 D BluetoothAdapterState: make() - Creating AdapterState
08-29 14:40:43.336   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@286607e:true
,08-29 14:40:43.341  4039  4039 I bt_bluedroid: init
,08-29 14:40:43.342  4039  4198 I BluetoothAdapterState: Entering OffState
,08-29 14:40:43.348  4039  4199 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-29 14:40:43.348  4039  4199 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 14:40:43.348  4039  4199 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 14:40:43.349  4039  4199 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 14:40:43.350  4039  4039 I bt_bluedroid: get_profile_interface socket
,08-29 14:40:43.353  4039  4039 I bt_bluedroid: get_profile_interface sdp
,08-29 14:40:43.356  4039  4202 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 14:40:43.358  4039  4049 I bt_bluedroid: config_hci_snoop_log
,08-29 14:40:43.359  4039  4202 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 14:40:43.360   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 14:40:43.368  4039  4198 D BluetoothAdapterState: Current state: OFF, message: 0
08-29 14:40:43.368  4039  4198 D BluetoothAdapterProperties: Setting state to 14
,08-29 14:40:43.369  4039  4198 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 14:40:43.374  4039  4198 D BluetoothBondStateMachine: make
,08-29 14:40:43.380  4039  4203 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 14:40:43.387  4039  4198 I BluetoothAdapterState: Entering PendingCommandState
,08-29 14:40:43.388  4039  4039 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 14:40:43.391  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ecbba04
,08-29 14:40:43.392  4039  4039 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 14:40:43.393  4039  4039 D BtGatt.GattService: Received start request. Starting profile...
,08-29 14:40:43.393  4039  4039 D BtGatt.GattService: start()
08-29 14:40:43.393  4039  4039 I bt_bluedroid: get_profile_interface gatt
,08-29 14:40:43.395  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ecbba04
,08-29 14:40:43.395  4039  4039 D BtGatt.AdvertiseManager: advertise manager created
,08-29 14:40:43.404  4039  4039 V BluetoothAdapterState: isTurningOff()=false
08-29 14:40:43.404  4039  4039 V BluetoothAdapterState: isTurningOn()=false
,08-29 14:40:43.404  4039  4039 V BluetoothAdapterState: isBleTurningOn()=true
08-29 14:40:43.404  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:40:43.405  4039  4198 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 14:40:43.406  4039  4198 I bt_bluedroid: enable
08-29 14:40:43.406  4039  4199 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 14:40:43.407  4039  4199 I bt_hci  : start_up
,08-29 14:40:43.414  4039  4199 I bt_vendor: alloc value 0xb3979189
08-29 14:40:43.414  4039  4199 I bt_vendor: init
,08-29 14:40:43.414  4039  4199 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 14:40:43.414  4039  4199 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 14:40:43.524  4039  4199 D bt_hci  : start_up starting async portion
,08-29 14:40:43.525  4039  4206 I bt_hci  : event_finish_startup
,08-29 14:40:43.525  4039  4206 I bt_hci_h4: hal_open
08-29 14:40:43.525  4039  4206 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 14:40:43.535  4039  4206 I bt_userial_vendor: device fd = 51 open
,08-29 14:40:43.565  4039  4206 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 14:40:43.597  4039  4206 D bt_hwcfg: Chipset BCM4354A2
,08-29 14:40:43.597  4039  4206 D bt_hwcfg: Target name = [BCM4354A2]
,08-29 14:40:43.598  4039  4206 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 14:40:43.711   873  1315 D ConnectivityService: handlePromptUnvalidated 101
,08-29 14:40:44.263  4039  4206 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 14:40:44.265  4039  4206 D bt_hwcfg: Settlement delay -- 100 ms
08-29 14:40:44.265  4039  4206 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 14:40:44.382  4039  4206 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 14:40:44.383  4039  4206 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 14:40:44.412  4039  4206 I bt_hwcfg: vendor lib fwcfg completed
,08-29 14:40:44.413  4039  4206 I bt_vendor: firmware callback
,08-29 14:40:44.413  4039  4206 I bt_hci  : firmware_config_callback
,08-29 14:40:44.424  4039  4208 I bt_btu  : btu_task pending for preload complete event
,08-29 14:40:44.425  4039  4208 I bt_btu_task: Bluetooth chip preload is complete
,08-29 14:40:44.425  4039  4208 I bt_btu  : btu_task received preload complete event
,08-29 14:40:44.437  4039  4208 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 14:40:44.438  4039  4208 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 14:40:44.438  4039  4208 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 14:40:44.438  4039  4208 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 14:40:44.439  4039  4208 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 14:40:44.439  4039  4208 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 14:40:44.439  4039  4208 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-29 14:40:44.439  4039  4208 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 14:40:44.440  4039  4208 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 14:40:44.440  4039  4208 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 14:40:44.440  4039  4208 I         : BTE_InitTraceLevels -- TRC_SDP
,08-29 14:40:44.441  4039  4208 I         : BTE_InitTraceLevels -- TRC_GATT
,08-29 14:40:44.441  4039  4208 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 14:40:44.441  4039  4208 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 14:40:44.442  4039  4208 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 14:40:44.578  4039  4208 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38f6d9d
,08-29 14:40:44.579  4039  4208 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38f6d9d 
,08-29 14:40:44.586  4039  4202 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 14:40:44.588  4039  4202 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 14:40:44.589  4039  4202 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 14:40:44.592  4039  4202 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 14:40:44.597  4039  4202 D BluetoothAdapterProperties: Scan Mode:20
,08-29 14:40:44.598  4039  4202 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 14:40:44.598  4039  4202 D bt_hci  : do_postload posting postload work item
,08-29 14:40:44.599  4039  4206 I bt_hci  : event_postload
08-29 14:40:44.599  4039  4206 I bt_vendor: sco_config_cb
,08-29 14:40:44.599  4039  4206 I bt_hci  : sco_config_callback postload finished.
08-29 14:40:44.601  4039  4202 D bt_bte_conf: Device ID record 1 : primary
08-29 14:40:44.602  4039  4202 D bt_bte_conf:   vendorId            = 000f
08-29 14:40:44.602  4039  4202 D bt_bte_conf:   vendorIdSource      = 0001
,08-29 14:40:44.602  4039  4202 D bt_bte_conf:   product             = 1200
08-29 14:40:44.602  4039  4202 D bt_bte_conf:   version             = 1436
08-29 14:40:44.603  4039  4202 D bt_bte_conf:   clientExecutableURL = 
,08-29 14:40:44.603  4039  4202 D bt_bte_conf:   serviceDescription  = 
08-29 14:40:44.603  4039  4202 D bt_bte_conf:   documentationURL    = 
08-29 14:40:44.603  4039  4202 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 14:40:44.604  4039  4199 D bt_stack_manager: event_start_up_stack finished
,08-29 14:40:44.606  4039  4198 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 14:40:44.606  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:44.608  4039  4198 D BluetoothAdapterProperties: Setting state to 15
08-29 14:40:44.609  4039  4198 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 14:40:44.610  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:44.610  4039  4206 I bt_vendor: low_power_mode_cb
08-29 14:40:44.612  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:40:44.612  4039  4198 I BluetoothAdapterState: Entering BleOnState
08-29 14:40:44.614  4039  4198 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 14:40:44.615  4039  4198 D BluetoothAdapterProperties: Setting state to 11
08-29 14:40:44.615  4039  4198 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 14:40:44.623  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:40:44.625  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:40:44.627  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:44.629  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ecbba04
08-29 14:40:44.630  4039  4039 D HeadsetService: Received start request. Starting profile...
,08-29 14:40:44.633  4039  4039 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 14:40:44.633  4039  4039 D HeadsetStateMachine: make
,08-29 14:40:44.638  4039  4198 I BluetoothAdapterState: Entering PendingCommandState
,08-29 14:40:44.641  4039  4039 D HeadsetStateMachine: max_hf_connections = 1
,08-29 14:40:44.641  4039  4039 I bt_bluedroid: get_profile_interface handsfree
08-29 14:40:44.641  4039  4202 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 14:40:44.642  4039  4202 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 14:40:44.646  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ecbba04
,08-29 14:40:44.647  4039  4039 D A2dpService: Received start request. Starting profile...
,08-29 14:40:44.647  4039  4039 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 14:40:44.648  4039  4039 I bt_bluedroid: get_profile_interface avrcp
,08-29 14:40:44.655  4039  4039 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 14:40:44.655  4039  4039 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 14:40:44.655  4039  4039 D A2dpStateMachine: make
,08-29 14:40:44.658  4039  4039 I bt_bluedroid: get_profile_interface a2dp
,08-29 14:40:44.658  4039  4202 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 14:40:44.661  4039  4217 D A2dpStateMachine: Enter Disconnected: -2
,08-29 14:40:44.662  4039  4039 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 14:40:44.663  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ecbba04
08-29 14:40:44.663  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 14:40:44.666  3960  3960 D BluetoothInputDevice: Proxy object connected
,08-29 14:40:44.666  4039  4039 D HidService: Received start request. Starting profile...
08-29 14:40:44.666  4039  4039 I bt_bluedroid: get_profile_interface hidhost
08-29 14:40:44.667  4039  4039 D HidService: setHidService(): set to: null
08-29 14:40:44.667  4039  4202 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38d83e5
08-29 14:40:44.667  3960  3960 D HidProfile: Bluetooth service connected
08-29 14:40:44.667  4039  4202 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-29 14:40:44.667  4039  4039 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 14:40:44.668  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ecbba04
08-29 14:40:44.669  4039  4039 D HealthService: Received start request. Starting profile...
,08-29 14:40:44.672  4039  4039 I bt_bluedroid: get_profile_interface health
,08-29 14:40:44.673  4039  4039 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 14:40:44.673  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ecbba04
08-29 14:40:44.675  3960  3960 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 14:40:44.675  4039  4039 D PanService: Received start request. Starting profile...
08-29 14:40:44.675  3960  3960 D PanProfile: Bluetooth service connected
,08-29 14:40:44.675  4039  4039 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-29 14:40:44.676  4039  4039 I bt_bluedroid: get_profile_interface pan
08-29 14:40:44.676  4039  4202 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 14:40:44.680  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ecbba04
08-29 14:40:44.681  3960  3960 D BluetoothMap: Proxy object connected
08-29 14:40:44.681  4039  4039 D BluetoothMapService: Received start request. Starting profile...
08-29 14:40:44.681  4039  4039 D BluetoothMapService: start()
08-29 14:40:44.682  3960  3960 D MapProfile: Bluetooth service connected
08-29 14:40:44.682  3960  3960 D BluetoothMap: getConnectedDevices()
,08-29 14:40:44.682  3960  3960 D BluetoothMap: Bluetooth is Not enabled
08-29 14:40:44.684  4039  4039 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-29 14:40:44.685  4039  4039 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-29 14:40:44.685  4039  4039 D BluetoothMapAppObserver: createReceiver()
08-29 14:40:44.687  4039  4039 D BluetoothMapAppObserver: initObservers()
08-29 14:40:44.687  4039  4039 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 14:40:44.697  4039  4039 V BluetoothAdapterState: isTurningOff()=false
,08-29 14:40:44.697  4039  4039 V BluetoothAdapterState: isTurningOn()=true
08-29 14:40:44.697  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:40:44.697  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 14:40:44.701  4039  4039 V BluetoothAdapterState: isTurningOff()=false
,08-29 14:40:44.701  4039  4215 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 14:40:44.701  4039  4039 V BluetoothAdapterState: isTurningOn()=true
08-29 14:40:44.701  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:40:44.701  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:40:44.702  4039  4039 V BluetoothAdapterState: isTurningOff()=false
08-29 14:40:44.702  4039  4039 V BluetoothAdapterState: isTurningOn()=true
,08-29 14:40:44.702  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 14:40:44.704  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 14:40:44.704  4039  4039 V BluetoothAdapterState: isTurningOff()=false
,08-29 14:40:44.705  4039  4039 V BluetoothAdapterState: isTurningOn()=true
08-29 14:40:44.705  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 14:40:44.705  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 14:40:44.705  4039  4039 V BluetoothAdapterState: isTurningOff()=false
,08-29 14:40:44.705  4039  4039 V BluetoothAdapterState: isTurningOn()=true
,08-29 14:40:44.705  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:40:44.705  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:40:44.706  4039  4039 V BluetoothAdapterState: isTurningOff()=false
08-29 14:40:44.706  4039  4039 V BluetoothAdapterState: isTurningOn()=true
08-29 14:40:44.706  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:40:44.706  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 14:40:44.707  4039  4198 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 14:40:44.707  4039  4198 D BluetoothAdapterProperties: ScanMode =  20
08-29 14:40:44.707  4039  4198 D BluetoothAdapterProperties: State =  11
08-29 14:40:44.707  4039  4198 D BluetoothAdapterProperties: Setting state to 12
08-29 14:40:44.707  4039  4198 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 14:40:44.709  4039  4198 I BluetoothAdapterState: Entering OnState
08-29 14:40:44.709  1953  2108 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 14:40:44.711  3960  3971 D BluetoothPan: onBluetoothStateChange on: true
08-29 14:40:44.711   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 14:40:44.711  4039  4202 D BluetoothAdapterProperties: Scan Mode:21
08-29 14:40:44.712  1383  1395 D BluetoothPan: onBluetoothStateChange on: true
08-29 14:40:44.712  4039  4202 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 14:40:44.715   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 14:40:44.715  1383  1383 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 14:40:44.716  1383  1383 D PanProfile: Bluetooth service connected
08-29 14:40:44.716  4039  4039 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 14:40:44.716  1383  1396 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 14:40:44.717  4039  4039 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 14:40:44.718   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 14:40:44.719  3960  3973 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 14:40:44.720  4039  4039 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 14:40:44.721  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:44.721  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:44.721  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:44.721  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:40:44.721  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:40:44.721  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:40:44.721  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:40:44.721  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:40:44.721  1383  1904 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 14:40:44.725  1383  1395 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 14:40:44.725  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:40:44.726  4039  4039 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 14:40:44.729  1383  1383 D BluetoothMap: Proxy object connected
,08-29 14:40:44.729  1383  1383 D MapProfile: Bluetooth service connected
,08-29 14:40:44.729  1383  1383 D BluetoothMap: getConnectedDevices()
08-29 14:40:44.729  3960  3971 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 14:40:44.730  1383  1396 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 14:40:44.731  4039  4039 D ObexServerSockets: Succeed to create listening sockets 
08-29 14:40:44.731  1383  1395 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 14:40:44.731  4039  4039 D ObexServerSockets0: startAccept()
,08-29 14:40:44.731  4039  4039 D ObexServerSockets0: prepareForNewConnect()
08-29 14:40:44.733  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-29 14:40:44.733  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:44.733  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:44.733  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:40:44.733  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:40:44.733  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:40:44.733  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:40:44.733  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:40:44.734  1383  1383 D BluetoothInputDevice: Proxy object connected
08-29 14:40:44.734  1383  1383 D HidProfile: Bluetooth service connected
08-29 14:40:44.734   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 14:40:44.734  3960  3973 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 14:40:44.738  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:40:44.740   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 14:40:44.743  3960  3960 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-29 14:40:44.745  4039  4039 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 14:40:44.745  4039  4039 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 14:40:44.746  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:44.746  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:44.746  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:44.746  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:40:44.746  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:40:44.746  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:40:44.746  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:40:44.746  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:40:44.747  4039  4224 D ObexServerSockets0: Accepting socket connection...
,08-29 14:40:44.747   873   873 D BluetoothA2dp: Proxy object connected
08-29 14:40:44.747  4039  4039 D BluetoothMapService: onReceive
08-29 14:40:44.747  4039  4039 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 14:40:44.747  4039  4039 D BluetoothMapService: STATE_ON
08-29 14:40:44.748  1383  1383 D BluetoothA2dp: Proxy object connected
,08-29 14:40:44.748  4039  4225 D ObexServerSockets0: Accepting socket connection...
08-29 14:40:44.751  3960  3960 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-29 14:40:44.751  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:40:44.753  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:44.754  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:44.755  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:40:44.760  3960  3960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 14:40:44.762  3960  3960 D BluetoothA2dp: Proxy object connected
,08-29 14:40:44.767  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 14:40:44.773  3960  3960 D DockEventReceiver: finishStartingService: stopping service
,08-29 14:40:44.776  1383  1383 D BluetoothPbap: Proxy object connected
,08-29 14:40:44.776  1383  1383 D PbapServerProfile: Bluetooth service connected
08-29 14:40:44.777  3960  3960 D BluetoothPbap: Proxy object connected
08-29 14:40:44.777  4039  4039 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 14:40:44.777  4039  4039 D ObexServerSockets0: prepareForNewConnect()
08-29 14:40:44.777  3960  3960 D PbapServerProfile: Bluetooth service connected
,08-29 14:40:44.785  4039  4229 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 14:40:44.799  4039  4233 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 14:40:44.800  4039  4233 I BtOppRfcommListener: Accept thread started.
,08-29 14:40:44.812  1383  1904 D BluetoothHeadset: Proxy object connected
08-29 14:40:44.812  1383  1383 D HeadsetProfile: Bluetooth service connected
08-29 14:40:44.812   873   890 D BluetoothHeadset: Proxy object connected
08-29 14:40:44.812  1953  1965 D BluetoothHeadset: Proxy object connected
08-29 14:40:44.812   873   873 D BluetoothHeadset: Proxy object connected
08-29 14:40:44.812   873   873 D BluetoothHeadset: Proxy object connected
,08-29 14:40:44.816   873   890 D BluetoothHeadset: Proxy object connected
,08-29 14:40:44.813   873   873 D BluetoothHeadset: Proxy object connected
,08-29 14:40:44.831  1383  1395 D BluetoothHeadset: Proxy object connected
08-29 14:40:44.831  1383  1383 D HeadsetProfile: Bluetooth service connected
,08-29 14:40:44.833   873   890 D BluetoothHeadset: Proxy object connected
,08-29 14:40:44.854  3960  3971 D BluetoothHeadset: Proxy object connected
,08-29 14:40:44.855  3960  3960 D HeadsetProfile: Bluetooth service connected
,08-29 14:40:47.884  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:40:47.897  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:40:47.901  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:40:47.950  1511  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-29 14:40:47.951  1511  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 14:40:47.951  1511  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:40:47.951  1511  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:40:47.991  3528  3528 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-29 14:40:47.992  3528  3528 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 14:40:47.993  3528  3528 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-29 14:40:48.316  4039  4198 D BluetoothAdapterState: Current state: ON, message: 23
,08-29 14:40:48.317  4039  4198 D BluetoothAdapterProperties: Setting state to 13
,08-29 14:40:48.317  4039  4198 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 14:40:48.319  4039  4198 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 14:40:48.321  4039  4198 I BluetoothAdapterState: Entering PendingCommandState
,08-29 14:40:48.325  4039  4202 D BluetoothAdapterProperties: Scan Mode:20
,08-29 14:40:48.330  4039  4039 D BluetoothMapService: onReceive
,08-29 14:40:48.330  4039  4039 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:40:48.330  4039  4039 D BluetoothMapService: STATE_TURNING_OFF
08-29 14:40:48.331  4039  4039 D BluetoothMapService: MAP Service closeService in
08-29 14:40:48.331  4039  4039 D BluetoothMapMasInstance0: MAP Service shutdown
,08-29 14:40:48.331  4039  4039 D ObexServerSockets0: shutdown(block = true)
08-29 14:40:48.332  4039  4039 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 14:40:48.332  4039  4039 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 14:40:48.332  4039  4224 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-29 14:40:48.333  4039  4210 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 14:40:48.333  4039  4225 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 14:40:48.334  4039  4039 I BtOppRfcommListener: stopping Accept Thread
08-29 14:40:48.334  4039  4233 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 14:40:48.334  4039  4198 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 14:40:48.334  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:40:48.335  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:48.335  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:48.335  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:48.335  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:40:48.335  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:48.335  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:40:48.335  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:40:48.335  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:40:48.335  4039  4233 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 14:40:48.338  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:48.338  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:40:48.346  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:40:48.346  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:48.346  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:48.346  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:48.346  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:40:48.346  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:48.346  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:40:48.346  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:40:48.346  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:40:48.347  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:48.347  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:40:48.349  4039  4039 D HeadsetService: Received stop request...Stopping profile...
08-29 14:40:48.350  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 14:40:48.350  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:40:48.350  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:40:48.350  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:40:48.350  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:40:48.350  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 14:40:48.350  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:40:48.350  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:40:48.350  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:40:48.351  3863  3863 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 14:40:48.351  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:40:48.352  1383  1396 D BluetoothHeadset: Proxy object disconnected
08-29 14:40:48.352  1953  2282 D BluetoothHeadset: Proxy object disconnected
08-29 14:40:48.352   873   873 D BluetoothHeadset: Proxy object disconnected
,08-29 14:40:48.353  4039  4039 D A2dpService: Received stop request...Stopping profile...
08-29 14:40:48.353  3960  3973 D BluetoothHeadset: Proxy object disconnected
08-29 14:40:48.353  4039  4217 D A2dpStateMachine: Exit Disconnected: -1
08-29 14:40:48.353   873   873 D BluetoothHeadset: Proxy object disconnected
08-29 14:40:48.353   873   873 D BluetoothHeadset: Proxy object disconnected
08-29 14:40:48.354  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:40:48.355   873   873 D BluetoothA2dp: Proxy object disconnected
08-29 14:40:48.355  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:48.356  3960  3960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 14:40:48.356  4039  4039 D HidService: Received stop request...Stopping profile...
08-29 14:40:48.356  4039  4039 D HidService: Stopping Bluetooth HidService
,08-29 14:40:48.357  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:40:48.360  3960  3960 D HeadsetProfile: Bluetooth service disconnected
08-29 14:40:48.360  3960  3960 D BluetoothA2dp: Proxy object disconnected
08-29 14:40:48.361  4039  4039 D HealthService: Received stop request...Stopping profile...
08-29 14:40:48.364  3960  3960 D DockEventReceiver: finishStartingService: stopping service
,08-29 14:40:48.364  1383  1383 D HeadsetProfile: Bluetooth service disconnected
08-29 14:40:48.364  1383  1383 D BluetoothA2dp: Proxy object disconnected
08-29 14:40:48.365  1383  1383 D BluetoothInputDevice: Proxy object disconnected
08-29 14:40:48.365  1383  1383 D HidProfile: Bluetooth service disconnected
,08-29 14:40:48.368  3960  3960 D BluetoothInputDevice: Proxy object disconnected
,08-29 14:40:48.368  4039  4039 V BluetoothAdapterState: isTurningOff()=true
08-29 14:40:48.368  3960  3960 D HidProfile: Bluetooth service disconnected
08-29 14:40:48.368  4039  4039 V BluetoothAdapterState: isTurningOn()=false
08-29 14:40:48.368  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:40:48.368  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:40:48.369  4039  4039 D PanService: Received stop request...Stopping profile...
,08-29 14:40:48.370  1383  1383 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 14:40:48.370  1383  1383 D PanProfile: Bluetooth service disconnected
08-29 14:40:48.370  3960  3960 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 14:40:48.370  3960  3960 D PanProfile: Bluetooth service disconnected
,08-29 14:40:48.372  4039  4039 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 14:40:48.372  4039  4202 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 14:40:48.372  4039  4208 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 14:40:48.372  4039  4039 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 14:40:48.372  4039  4208 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 14:40:48.372  4039  4208 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 14:40:48.372  4039  4202 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 14:40:48.373  4039  4039 D BluetoothMapService: Received stop request...Stopping profile...
08-29 14:40:48.373  4039  4039 D BluetoothMapService: stop()
,08-29 14:40:48.373  4039  4039 D BluetoothMapAppObserver: deinitObservers()
08-29 14:40:48.373  4039  4039 D BluetoothMapAppObserver: removeReceiver()
08-29 14:40:48.374  1383  1383 D BluetoothMap: Proxy object disconnected
08-29 14:40:48.374  1383  1383 D MapProfile: Bluetooth service disconnected
08-29 14:40:48.375  3960  3960 D BluetoothMap: Proxy object disconnected
08-29 14:40:48.375  3960  3960 D MapProfile: Bluetooth service disconnected
,08-29 14:40:48.375  4039  4039 V BluetoothAdapterState: isTurningOff()=true
08-29 14:40:48.375  4039  4039 V BluetoothAdapterState: isTurningOn()=false
08-29 14:40:48.375  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:40:48.375  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 14:40:48.376  4039  4202 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 14:40:48.376  4039  4039 V BluetoothAdapterState: isTurningOff()=true
08-29 14:40:48.376  4039  4208 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 14:40:48.376  4039  4039 V BluetoothAdapterState: isTurningOn()=false
08-29 14:40:48.376  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:40:48.376  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:40:48.376  4039  4208 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 14:40:48.376  4039  4208 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 14:40:48.376  4039  4208 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 14:40:48.377  4039  4208 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 14:40:48.377  4039  4208 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 14:40:48.377  4039  4039 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 14:40:48.377  4039  4202 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 14:40:48.377  4039  4039 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-29 14:40:48.379  4039  4039 V BluetoothAdapterState: isTurningOff()=true
,08-29 14:40:48.379  4039  4039 V BluetoothAdapterState: isTurningOn()=false
,08-29 14:40:48.379  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:40:48.379  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:40:48.379  4039  4039 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 14:40:48.379  4039  4202 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 14:40:48.380  4039  4039 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 14:40:48.380  4039  4039 V BluetoothAdapterState: isTurningOff()=true
08-29 14:40:48.380  4039  4039 V BluetoothAdapterState: isTurningOn()=false
08-29 14:40:48.380  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:40:48.380  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 14:40:48.381  4039  4039 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 14:40:48.381  4039  4039 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-29 14:40:48.381  4039  4039 D BluetoothMapService: MAP Service closeService in
08-29 14:40:48.381  4039  4039 V BluetoothAdapterState: isTurningOff()=true
08-29 14:40:48.381  4039  4039 V BluetoothAdapterState: isTurningOn()=false
08-29 14:40:48.381  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:40:48.381  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:40:48.382  4039  4198 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 14:40:48.382  4039  4198 D BluetoothAdapterProperties: Setting state to 15
,08-29 14:40:48.382  4039  4198 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 14:40:48.382  4039  4198 I BluetoothAdapterState: Entering BleOnState
08-29 14:40:48.383  1953  1964 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 14:40:48.383  3960  3973 D BluetoothPan: onBluetoothStateChange on: false
08-29 14:40:48.384   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 14:40:48.384  4039  4039 D BluetoothMapService: cleanup()
,08-29 14:40:48.384  4039  4039 D BluetoothMapService: MAP Service closeService in
,08-29 14:40:48.384  1383  1396 D BluetoothPan: onBluetoothStateChange on: false
08-29 14:40:48.385   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:40:48.385  1383  1904 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 14:40:48.386   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 14:40:48.386  3960  3973 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 14:40:48.387  1383  1396 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 14:40:48.387  3960  3971 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:40:48.387  1383  1395 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 14:40:48.388  3960  3973 D BluetoothMap: onBluetoothStateChange: up=false
08-29 14:40:48.389  1383  1904 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:40:48.389  1383  1396 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 14:40:48.389  3960  3971 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 14:40:48.390   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 14:40:48.390  3960  3973 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 14:40:48.390  4039  4198 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 14:40:48.390  4039  4198 D BluetoothAdapterProperties: Setting state to 16
08-29 14:40:48.391  4039  4198 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 14:40:48.391  4039  4198 D BluetoothAdapterProperties: onBleDisable
08-29 14:40:48.391  4039  4198 I BluetoothAdapterState: Entering PendingCommandState
08-29 14:40:48.391  4039  4199 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 14:40:48.393  4039  4208 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 14:40:48.393  4039  4208 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 14:40:48.394  4039  4202 D BluetoothAdapterProperties: Scan Mode:20
08-29 14:40:48.394  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:48.394  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 14:40:48.395  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:48.397  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:48.398  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:48.399  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:48.400  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:40:48.402  3960  3960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 14:40:48.407  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 14:40:48.413  3960  3960 D DockEventReceiver: finishStartingService: stopping service
,08-29 14:40:48.604  4039  4202 I bt_hci  : shut_down
,08-29 14:40:48.616  4039  4206 I bt_vendor: low_power_mode_cb
,08-29 14:40:48.616  4039  4206 D bt_hwcfg: hw_epilog_process
,08-29 14:40:48.643  4039  4206 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 14:40:48.643  4039  4206 I bt_vendor: epilog_cb
,08-29 14:40:48.644  4039  4206 I bt_hci  : epilog_finished_callback
,08-29 14:40:48.650  4039  4202 I bt_hci_h4: hal_close
,08-29 14:40:48.652  4039  4202 I bt_userial_vendor: device fd = 51 close
,08-29 14:40:48.769  4039  4199 D bt_stack_manager: event_shut_down_stack finished.
,08-29 14:40:48.771  4039  4198 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 14:40:48.780  4039  4039 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 14:40:48.780  4039  4198 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-29 14:40:48.783  4039  4039 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 14:40:48.784  4039  4039 D BtGatt.GattService: stop()
,08-29 14:40:48.784  4039  4039 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 14:40:48.791  4039  4039 V BluetoothAdapterState: isTurningOff()=false
,08-29 14:40:48.791  4039  4039 V BluetoothAdapterState: isTurningOn()=false
08-29 14:40:48.791  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 14:40:48.792  4039  4039 V BluetoothAdapterState: isBleTurningOff()=true
08-29 14:40:48.792  4039  4198 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 14:40:48.793  4039  4198 D BluetoothAdapterProperties: Setting state to 10
,08-29 14:40:48.793  4039  4198 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 14:40:48.795  4039  4198 I BluetoothAdapterState: Entering OffState
08-29 14:40:48.797   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 14:40:48.814  4039  4039 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-29 14:40:48.814  4039  4039 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 14:40:48.814  4039  4039 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 14:40:48.816  4039  4199 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-29 14:40:48.819  4039  4199 D bt_stack_manager: event_clean_up_stack finished.
,08-29 14:40:48.821  4039  4039 I art     : System.exit called, status: 0
08-29 14:40:48.821  4039  4039 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 14:40:48.878   873  1405 I ActivityManager: Process com.android.bluetooth (pid 4039) has died
,08-29 14:40:53.315  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:40:53.316  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:40:53.320  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:40:53.320  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f684bd7 removed from the list
08-29 14:40:53.320  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:40:53.321  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:53.321  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:40:53.324  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:40:53.325  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f5087ad added. We now have 4 listener(s)
,08-29 14:40:53.325  3863  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:40:53.327  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:40:53.327  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f5087ad removed from the list
08-29 14:40:53.327  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 14:40:53.327  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:40:53.328  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:40:53.330  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 14:40:53.330  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b6eaae2 added. We now have 4 listener(s)
08-29 14:40:53.331  3863  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:40:58.344  3863  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:40:58.395   873   890 I ActivityManager: Start proc 4243:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 14:40:58.527  4243  4243 D AdapterServiceConfig: Adding HeadsetService
,08-29 14:40:58.527  4243  4243 D AdapterServiceConfig: Adding A2dpService
,08-29 14:40:58.527  4243  4243 D AdapterServiceConfig: Adding HidService
,08-29 14:40:58.528  4243  4243 D AdapterServiceConfig: Adding HealthService
08-29 14:40:58.528  4243  4243 D AdapterServiceConfig: Adding PanService
08-29 14:40:58.528  4243  4243 D AdapterServiceConfig: Adding GattService
08-29 14:40:58.528  4243  4243 D AdapterServiceConfig: Adding BluetoothMapService
,08-29 14:40:58.543   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@437e36d:true
,08-29 14:40:58.544  4243  4243 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 14:40:58.552  4243  4243 I bt_bluedroid: init
,08-29 14:40:58.552  4243  4255 I BluetoothAdapterState: Entering OffState
,08-29 14:40:58.556  4243  4256 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 14:40:58.556  4243  4256 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-29 14:40:58.556  4243  4256 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 14:40:58.556  4243  4256 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 14:40:58.558  4243  4243 I bt_bluedroid: get_profile_interface socket
,08-29 14:40:58.561  4243  4259 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 14:40:58.563  4243  4243 I bt_bluedroid: get_profile_interface sdp
,08-29 14:40:58.564  4243  4259 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 14:40:58.568  4243  4254 I bt_bluedroid: config_hci_snoop_log
,08-29 14:40:58.572   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 14:40:58.583  4243  4255 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 14:40:58.584  4243  4255 D BluetoothAdapterProperties: Setting state to 14
08-29 14:40:58.584  4243  4255 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-29 14:40:58.587  4243  4255 D BluetoothBondStateMachine: make
,08-29 14:40:58.592  4243  4260 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 14:40:58.598  4243  4255 I BluetoothAdapterState: Entering PendingCommandState
,08-29 14:40:58.600  4243  4243 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 14:40:58.609  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ecbba04
,08-29 14:40:58.611  4243  4243 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 14:40:58.612  4243  4243 D BtGatt.GattService: Received start request. Starting profile...
08-29 14:40:58.613  4243  4243 D BtGatt.GattService: start()
,08-29 14:40:58.613  4243  4243 I bt_bluedroid: get_profile_interface gatt
,08-29 14:40:58.615  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ecbba04
08-29 14:40:58.616  4243  4243 D BtGatt.AdvertiseManager: advertise manager created
,08-29 14:40:58.633  4243  4243 V BluetoothAdapterState: isTurningOff()=false
,08-29 14:40:58.633  4243  4243 V BluetoothAdapterState: isTurningOn()=false
08-29 14:40:58.633  4243  4243 V BluetoothAdapterState: isBleTurningOn()=true
08-29 14:40:58.634  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 14:40:58.636  4243  4255 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-29 14:40:58.637  4243  4255 I bt_bluedroid: enable
08-29 14:40:58.637  4243  4256 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 14:40:58.638  4243  4256 I bt_hci  : start_up
,08-29 14:40:58.660  4243  4256 I bt_vendor: alloc value 0xb39ca189
08-29 14:40:58.661  4243  4256 I bt_vendor: init
,08-29 14:40:58.661  4243  4256 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 14:40:58.661  4243  4256 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 14:40:58.771  4243  4256 D bt_hci  : start_up starting async portion
,08-29 14:40:58.772  4243  4263 I bt_hci  : event_finish_startup
08-29 14:40:58.772  4243  4263 I bt_hci_h4: hal_open
08-29 14:40:58.772  4243  4263 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 14:40:58.786  4243  4263 I bt_userial_vendor: device fd = 51 open
,08-29 14:40:58.813  4243  4263 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 14:40:58.845  4243  4263 D bt_hwcfg: Chipset BCM4354A2
08-29 14:40:58.845  4243  4263 D bt_hwcfg: Target name = [BCM4354A2]
08-29 14:40:58.846  4243  4263 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-29 14:40:59.732  4243  4263 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 14:40:59.734  4243  4263 D bt_hwcfg: Settlement delay -- 100 ms
,08-29 14:40:59.734  4243  4263 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 14:40:59.852  4243  4263 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 14:40:59.854  4243  4263 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-29 14:40:59.882  4243  4263 I bt_hwcfg: vendor lib fwcfg completed
,08-29 14:40:59.882  4243  4263 I bt_vendor: firmware callback
08-29 14:40:59.882  4243  4263 I bt_hci  : firmware_config_callback
,08-29 14:40:59.896  4243  4265 I bt_btu  : btu_task pending for preload complete event
,08-29 14:40:59.896  4243  4265 I bt_btu_task: Bluetooth chip preload is complete
08-29 14:40:59.896  4243  4265 I bt_btu  : btu_task received preload complete event
,08-29 14:40:59.906  4243  4265 I         : BTE_InitTraceLevels -- TRC_HCI
08-29 14:40:59.906  4243  4265 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 14:40:59.907  4243  4265 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 14:40:59.907  4243  4265 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 14:40:59.907  4243  4265 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 14:40:59.907  4243  4265 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 14:40:59.908  4243  4265 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-29 14:40:59.908  4243  4265 I         : BTE_InitTraceLevels -- TRC_BTM
,08-29 14:40:59.908  4243  4265 I         : BTE_InitTraceLevels -- TRC_GAP
,08-29 14:40:59.909  4243  4265 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 14:40:59.909  4243  4265 I         : BTE_InitTraceLevels -- TRC_SDP
,08-29 14:40:59.909  4243  4265 I         : BTE_InitTraceLevels -- TRC_GATT
,08-29 14:40:59.909  4243  4265 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 14:40:59.909  4243  4265 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-29 14:40:59.910  4243  4265 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 14:41:00.056  4243  4265 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3947d9d
,08-29 14:41:00.056  4243  4265 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3947d9d 
,08-29 14:41:00.070  4243  4259 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 14:41:00.072  4243  4259 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 14:41:00.075  4243  4259 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-29 14:41:00.078  4243  4259 D BluetoothAdapterProperties: Name is: Nexus 6
,08-29 14:41:00.081  4243  4259 D BluetoothAdapterProperties: Scan Mode:20
,08-29 14:41:00.083  4243  4259 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 14:41:00.083  4243  4259 D bt_hci  : do_postload posting postload work item
08-29 14:41:00.083  4243  4263 I bt_hci  : event_postload
08-29 14:41:00.084  4243  4263 I bt_vendor: sco_config_cb
,08-29 14:41:00.084  4243  4263 I bt_hci  : sco_config_callback postload finished.
08-29 14:41:00.087  4243  4259 D bt_bte_conf: Device ID record 1 : primary
08-29 14:41:00.088  4243  4259 D bt_bte_conf:   vendorId            = 000f
08-29 14:41:00.088  4243  4259 D bt_bte_conf:   vendorIdSource      = 0001
08-29 14:41:00.088  4243  4259 D bt_bte_conf:   product             = 1200
08-29 14:41:00.089  4243  4259 D bt_bte_conf:   version             = 1436
08-29 14:41:00.089  4243  4259 D bt_bte_conf:   clientExecutableURL = 
08-29 14:41:00.089  4243  4259 D bt_bte_conf:   serviceDescription  = 
,08-29 14:41:00.089  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:41:00.090  4243  4259 D bt_bte_conf:   documentationURL    = 
08-29 14:41:00.090  4243  4259 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 14:41:00.090  4243  4256 D bt_stack_manager: event_start_up_stack finished
08-29 14:41:00.091  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:41:00.092  4243  4255 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-29 14:41:00.093  4243  4255 D BluetoothAdapterProperties: Setting state to 15
08-29 14:41:00.093  4243  4255 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 14:41:00.094  4243  4255 I BluetoothAdapterState: Entering BleOnState
,08-29 14:41:00.095  4243  4263 I bt_vendor: low_power_mode_cb
,08-29 14:41:00.099  4243  4255 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-29 14:41:00.099  4243  4255 D BluetoothAdapterProperties: Setting state to 11
08-29 14:41:00.099  4243  4255 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 14:41:00.104  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ecbba04
,08-29 14:41:00.105  4243  4243 D HeadsetService: Received start request. Starting profile...
,08-29 14:41:00.110  4243  4243 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 14:41:00.110  4243  4243 D HeadsetStateMachine: make
08-29 14:41:00.115  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:41:00.117  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:41:00.123  4243  4255 I BluetoothAdapterState: Entering PendingCommandState
08-29 14:41:00.126  4243  4243 D HeadsetStateMachine: max_hf_connections = 1
08-29 14:41:00.126  4243  4243 I bt_bluedroid: get_profile_interface handsfree
08-29 14:41:00.126  4243  4259 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-29 14:41:00.127  4243  4259 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-29 14:41:00.130  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ecbba04
08-29 14:41:00.131  4243  4243 D A2dpService: Received start request. Starting profile...
,08-29 14:41:00.132  4243  4243 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 14:41:00.132  4243  4243 I bt_bluedroid: get_profile_interface avrcp
,08-29 14:41:00.140  4243  4243 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 14:41:00.140  4243  4243 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 14:41:00.140  4243  4243 D A2dpStateMachine: make
08-29 14:41:00.141  4243  4243 I bt_bluedroid: get_profile_interface a2dp
,08-29 14:41:00.142  4243  4259 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-29 14:41:00.144  4243  4274 D A2dpStateMachine: Enter Disconnected: -2
,08-29 14:41:00.145  4243  4243 I BluetoothHidServiceJni: classInitNative: succeeds
08-29 14:41:00.146  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ecbba04
08-29 14:41:00.147  4243  4243 D HidService: Received start request. Starting profile...
08-29 14:41:00.147  4243  4243 I bt_bluedroid: get_profile_interface hidhost
08-29 14:41:00.147  4243  4243 D HidService: setHidService(): set to: null
,08-29 14:41:00.147  4243  4259 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39293e5
08-29 14:41:00.147  4243  4259 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-29 14:41:00.148  4243  4243 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 14:41:00.149  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ecbba04
08-29 14:41:00.149  4243  4243 D HealthService: Received start request. Starting profile...
,08-29 14:41:00.151  4243  4243 I bt_bluedroid: get_profile_interface health
,08-29 14:41:00.151  4243  4243 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 14:41:00.152  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ecbba04
,08-29 14:41:00.153  4243  4243 D PanService: Received start request. Starting profile...
08-29 14:41:00.153  4243  4243 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 14:41:00.153  4243  4243 I bt_bluedroid: get_profile_interface pan
,08-29 14:41:00.154  4243  4259 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 14:41:00.156  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ecbba04
,08-29 14:41:00.156  4243  4243 D BluetoothMapService: Received start request. Starting profile...
08-29 14:41:00.156  4243  4243 D BluetoothMapService: start()
,08-29 14:41:00.158  4243  4243 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 14:41:00.159  4243  4243 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 14:41:00.159  4243  4243 D BluetoothMapAppObserver: createReceiver()
08-29 14:41:00.160  4243  4243 D BluetoothMapAppObserver: initObservers()
08-29 14:41:00.160  4243  4243 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-29 14:41:00.169  4243  4243 V BluetoothAdapterState: isTurningOff()=false
,08-29 14:41:00.169  4243  4243 V BluetoothAdapterState: isTurningOn()=true
08-29 14:41:00.169  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:41:00.169  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:41:00.170  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 14:41:00.172  4243  4243 V BluetoothAdapterState: isTurningOff()=false
,08-29 14:41:00.172  4243  4243 V BluetoothAdapterState: isTurningOn()=true
08-29 14:41:00.172  4243  4271 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 14:41:00.172  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 14:41:00.172  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 14:41:00.172  4243  4243 V BluetoothAdapterState: isTurningOff()=false
,08-29 14:41:00.172  4243  4243 V BluetoothAdapterState: isTurningOn()=true
08-29 14:41:00.172  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 14:41:00.172  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:41:00.172  4243  4243 V BluetoothAdapterState: isTurningOff()=false
,08-29 14:41:00.172  4243  4243 V BluetoothAdapterState: isTurningOn()=true
08-29 14:41:00.172  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:41:00.172  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:41:00.173  4243  4243 V BluetoothAdapterState: isTurningOff()=false
,08-29 14:41:00.173  4243  4243 V BluetoothAdapterState: isTurningOn()=true
,08-29 14:41:00.173  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
08-29 14:41:00.173  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:41:00.173  4243  4243 V BluetoothAdapterState: isTurningOff()=false
08-29 14:41:00.173  4243  4243 V BluetoothAdapterState: isTurningOn()=true
08-29 14:41:00.173  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 14:41:00.173  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
08-29 14:41:00.173  4243  4255 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 14:41:00.173  4243  4255 D BluetoothAdapterProperties: ScanMode =  20
08-29 14:41:00.174  4243  4255 D BluetoothAdapterProperties: State =  11
08-29 14:41:00.175  4243  4259 D BluetoothAdapterProperties: Scan Mode:21
08-29 14:41:00.175  4243  4259 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 14:41:00.175  4243  4255 D BluetoothAdapterProperties: Setting state to 12
08-29 14:41:00.175  4243  4255 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 14:41:00.175  4243  4255 I BluetoothAdapterState: Entering OnState
,08-29 14:41:00.175  1953  2108 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 14:41:00.177  3960  3973 D BluetoothPan: onBluetoothStateChange on: true
08-29 14:41:00.178   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 14:41:00.179  1383  1395 D BluetoothPan: onBluetoothStateChange on: true
08-29 14:41:00.179  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:41:00.179  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:41:00.179  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:41:00.179  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:41:00.179  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:41:00.179  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:41:00.179  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:41:00.179  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:41:00.180   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 14:41:00.180  1383  1904 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 14:41:00.180  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:41:00.180  1383  1383 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 14:41:00.180  1383  1383 D PanProfile: Bluetooth service connected
08-29 14:41:00.182   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 14:41:00.182  3960  3973 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 14:41:00.183   873   873 D BluetoothA2dp: Proxy object connected
08-29 14:41:00.184  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:41:00.184  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:41:00.184  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:41:00.184  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:41:00.184  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:41:00.184  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:41:00.184  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:41:00.184  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:41:00.184  1383  1396 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 14:41:00.185  1383  1383 D BluetoothA2dp: Proxy object connected
08-29 14:41:00.185  3960  3971 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 14:41:00.185  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 14:41:00.186  1383  1904 D BluetoothMap: onBluetoothStateChange: up=true
08-29 14:41:00.186  4243  4243 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 14:41:00.187  4243  4243 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 14:41:00.187  3960  3973 D BluetoothMap: onBluetoothStateChange: up=true
08-29 14:41:00.188  4243  4243 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 14:41:00.189  1383  1395 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 14:41:00.189  3960  3960 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 14:41:00.189  3960  3960 D PanProfile: Bluetooth service connected
08-29 14:41:00.190  4243  4243 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 14:41:00.190  1383  1396 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 14:41:00.191  4243  4243 D ObexServerSockets: Succeed to create listening sockets 
,08-29 14:41:00.191  4243  4243 D ObexServerSockets0: startAccept()
08-29 14:41:00.191  4243  4243 D ObexServerSockets0: prepareForNewConnect()
08-29 14:41:00.192  4243  4243 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 14:41:00.193  4243  4243 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-29 14:41:00.193  4243  4280 D ObexServerSockets0: Accepting socket connection...
,08-29 14:41:00.195  4243  4281 D ObexServerSockets0: Accepting socket connection...
,08-29 14:41:00.195  1383  1383 D BluetoothInputDevice: Proxy object connected
08-29 14:41:00.195  1383  1383 D HidProfile: Bluetooth service connected
08-29 14:41:00.196  3960  3973 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 14:41:00.197  1383  1383 D BluetoothMap: Proxy object connected
08-29 14:41:00.197  1383  1383 D MapProfile: Bluetooth service connected
08-29 14:41:00.197  1383  1383 D BluetoothMap: getConnectedDevices()
,08-29 14:41:00.198   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 14:41:00.199  3960  3971 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 14:41:00.201  3960  3960 D BluetoothMap: Proxy object connected
,08-29 14:41:00.202   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 14:41:00.203  4243  4243 D BluetoothMapService: onReceive
08-29 14:41:00.203  4243  4243 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-29 14:41:00.203  4243  4243 D BluetoothMapService: STATE_ON
08-29 14:41:00.204  3960  3960 D MapProfile: Bluetooth service connected
08-29 14:41:00.204  3960  3960 D BluetoothMap: getConnectedDevices()
,08-29 14:41:00.205  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:41:00.205  3960  3960 D BluetoothA2dp: Proxy object connected
08-29 14:41:00.206  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:41:00.207  3960  3960 D BluetoothInputDevice: Proxy object connected
08-29 14:41:00.207  3960  3960 D HidProfile: Bluetooth service connected
,08-29 14:41:00.212  3960  3960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 14:41:00.218  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 14:41:00.219  3960  3960 D DockEventReceiver: finishStartingService: stopping service
,08-29 14:41:00.223  3960  3960 D BluetoothPbap: Proxy object connected
,08-29 14:41:00.223  3960  3960 D PbapServerProfile: Bluetooth service connected
08-29 14:41:00.224  4243  4243 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 14:41:00.224  4243  4243 D ObexServerSockets0: prepareForNewConnect()
,08-29 14:41:00.226  4243  4285 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 14:41:00.229  1383  1383 D BluetoothPbap: Proxy object connected
,08-29 14:41:00.229  1383  1383 D PbapServerProfile: Bluetooth service connected
,08-29 14:41:00.244  4243  4291 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 14:41:00.246  4243  4291 I BtOppRfcommListener: Accept thread started.
,08-29 14:41:00.278  1383  1395 D BluetoothHeadset: Proxy object connected
,08-29 14:41:00.278  1383  1383 D HeadsetProfile: Bluetooth service connected
,08-29 14:41:00.279  1953  1965 D BluetoothHeadset: Proxy object connected
,08-29 14:41:00.279   873   873 D BluetoothHeadset: Proxy object connected
08-29 14:41:00.279   873   890 D BluetoothHeadset: Proxy object connected
08-29 14:41:00.279  3960  4282 D BluetoothHeadset: Proxy object connected
08-29 14:41:00.280   873   873 D BluetoothHeadset: Proxy object connected
08-29 14:41:00.280   873   873 D BluetoothHeadset: Proxy object connected
08-29 14:41:00.280   873   890 D BluetoothHeadset: Proxy object connected
08-29 14:41:00.280  3960  3960 D HeadsetProfile: Bluetooth service connected
,08-29 14:41:00.286  3960  3973 D BluetoothHeadset: Proxy object connected
,08-29 14:41:00.286  3960  3960 D HeadsetProfile: Bluetooth service connected
,08-29 14:41:00.301  1383  1395 D BluetoothHeadset: Proxy object connected
,08-29 14:41:00.302  1383  1383 D HeadsetProfile: Bluetooth service connected
08-29 14:41:00.302   873   890 D BluetoothHeadset: Proxy object connected
,08-29 14:41:02.074  1511  2163 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-29 14:41:03.364  3863  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:41:03.364  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:41:03.364  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:41:03.364  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 14:41:03.364  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:41:03.364  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:41:03.364  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:41:03.364  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:41:03.371  3863  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:41:03.373  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:41:03.373  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b6eaae2 removed from the list
,08-29 14:41:03.374  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:41:03.374  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:41:03.374  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:41:03.377  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:41:03.377  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fbce73 added. We now have 4 listener(s)
08-29 14:41:03.378  3863  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:41:03.381   873  2123 D WifiService: setWifiEnabled: false pid=3863, uid=10000
,08-29 14:41:03.382   873  2123 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 14:41:04.363  1878  1926 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-29 14:41:04.363  1878  1926 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-29 14:41:04.410  1511  1511 I ConfigService: onCreate
,08-29 14:41:08.223  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:41:08.235  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:41:08.237  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:41:08.281  1511  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-29 14:41:08.282  1511  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 14:41:08.282  1511  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:41:08.282  1511  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:41:08.318  3528  3528 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-29 14:41:08.318  3528  3528 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-29 14:41:08.319  3528  3528 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-29 14:41:08.393  3863  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:41:08.394   873  2125 D WifiService: setWifiEnabled: true pid=3863, uid=10000
08-29 14:41:08.395   873  2125 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 14:41:08.412   873  1313 D WifiConfigStore: Loading config and enabling all networks 
,08-29 14:41:08.424  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:41:08.424  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:41:08.424  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:41:08.424  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:41:08.424  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:41:08.424  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:41:08.424  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:41:08.424  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 14:41:08.430  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:41:08.436  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:41:08.436  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:41:08.436  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:41:08.436  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:41:08.436  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:41:08.436  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 14:41:08.436  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 14:41:08.436  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 14:41:08.439  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 14:41:08.448   873  1313 D WifiConfigStore: loaded 0 passpoint configs
,08-29 14:41:08.449   873  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-29 14:41:08.450   873  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-29 14:41:08.451   873  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 14:41:08.451   873  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-29 14:41:08.451   873  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-29 14:41:08.451   873  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 14:41:08.460   371   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 14:41:08.460   873  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 14:41:08.461   371   872 D CommandListener: Setting iface cfg
,08-29 14:41:08.512   873  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '156 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 156 Failed to set address (No such device)'
,08-29 14:41:08.512   873  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 14:41:08.518   873  1313 E native  : do suspend true
,08-29 14:41:08.531   873  1312 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 14:41:08.532   873  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-29 14:41:08.543   873  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 14:41:09.502  1511  1511 I ConfigService: onDestroy
,08-29 14:41:09.950   873  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-29 14:41:10.075   873  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.62 rxSuccessRate=8.19 delta 1000 -> 994
08-29 14:41:10.077   873  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-29 14:41:10.077   873  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 14:41:10.091   873  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-29 14:41:10.132   873  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-29 14:41:10.133  1446  1446 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-29 14:41:10.590  1446  1446 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-29 14:41:10.672  1446  1446 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 14:41:10.675  1446  1446 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-29 14:41:10.683   873  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-29 14:41:10.698   873  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 14:41:10.698   873  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 14:41:10.699   873  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-29 14:41:10.715   873  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 14:41:10.728   371   872 D CommandListener: Setting iface cfg
,08-29 14:41:10.728   873  1313 D WifiStateMachine: Start Dhcp Watchdog 3
,08-29 14:41:10.744   873  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-29 14:41:10.772   873  4303 D DhcpClient: Receive thread started
,08-29 14:41:10.872   873  1313 E native  : do suspend false
,08-29 14:41:10.899   873  1860 D DhcpClient: Broadcasting DHCPDISCOVER
,08-29 14:41:10.914   873  4303 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,08-29 14:41:10.915   873  1860 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,08-29 14:41:10.919   873  1860 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-29 14:41:10.935   873  4303 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-29 14:41:10.936   873  1860 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-29 14:41:10.941   371   872 D CommandListener: Setting iface cfg
,08-29 14:41:10.953   873  1860 D DhcpClient: Scheduling renewal in 86399s
,08-29 14:41:10.954   873  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-29 14:41:10.959   873  1313 E native  : do suspend true
,08-29 14:41:10.989   873  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-29 14:41:10.994   873  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-29 14:41:10.996   873  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-29 14:41:10.999   873  1315 D ConnectivityService: Adding iface wlan0 to network 102
,08-29 14:41:11.013   873  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-29 14:41:11.058   873  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-29 14:41:11.059   873  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-29 14:41:11.063   873  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-29 14:41:11.066   873  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-29 14:41:11.069   873  1315 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-29 14:41:11.084   873  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 14:41:11.090   873  1315 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-29 14:41:11.090   873  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-29 14:41:11.090   873  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-29 14:41:11.091   873  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 14:41:11.091   873  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-29 14:41:11.091   873  1315 D ConnectivityService:    accepting network in place of null
08-29 14:41:11.093   873  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-29 14:41:11.142   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 14:41:11.171   371   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-29 14:41:11.181   873  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-29 14:41:11.183   873  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:41:11.191   873  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-29 14:41:11.211  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:41:11.211  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:41:11.211  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:41:11.211  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:41:11.211  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:41:11.211  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:41:11.211  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:41:11.211  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:41:11.211   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-29 14:41:11.213  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:41:11.219  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:41:11.219  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:41:11.219  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:41:11.219  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:41:11.219  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:41:11.219  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:41:11.219  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:41:11.219  3863  3863 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 14:41:11.221  3863  3863 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 14:41:11.223  1721  1721 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 14:41:11.233  1721  1721 D SystemUpdateService: onCreate
,08-29 14:41:11.238  1721  1721 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 14:41:11.262  1721  1721 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 14:41:11.266  1721  4312 I SystemUpdateService: active receiver: enabled
,08-29 14:41:11.269  1721  2474 I iu.UploadsManager: num queued entries: 0
,08-29 14:41:11.273  1721  2474 I iu.UploadsManager: num updated entries: 0
,08-29 14:41:11.275  1721  4312 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-29 14:41:11.280  1721  1721 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 14:41:11.282  1721  1721 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-29 14:41:11.288  4053  4053 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 14:41:11.289  1721  4314 I MDM     : [185] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-29 14:41:11.289  1721  4314 W BaseAppContext: Using Auth Proxy for data requests.
,08-29 14:41:11.291  1721  4314 V GoogleAuthProtoRequest: [185] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 14:41:11.294  4053  4053 D SprintDMHelper: simOperator: 
,08-29 14:41:11.294  4053  4053 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 14:41:11.312  1721  4312 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-29 14:41:11.312  1721  4312 I SystemUpdateService: now status is 0 (complete)
08-29 14:41:11.312  1721  4312 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-29 14:41:11.312  1721  4312 I SystemUpdateService: file has been verified
,08-29 14:41:11.313  1721  4312 I SystemUpdateService: OTA package size = 12249756
,08-29 14:41:11.327  1721  2474 I iu.SyncManager: NEXT; no task
,08-29 14:41:11.371  1721  4312 I SystemUpdateService: showing system update notification
,08-29 14:41:11.404   873  4302 D NetlinkSocketObserver: NeighborEvent{elapsedMs=217019, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 14:41:11.408  1721  1721 D SystemUpdateService: onDestroy
,08-29 14:41:11.419  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-29 14:41:11.419  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-29 14:41:11.419  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:41:11.419  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:41:11.437  3780  4317 V KeepSync: Connecting to GoogleApiClient
,08-29 14:41:11.438   873  2122 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 14:41:11.442  1721  4314 E MDM     : [185] SitrepService.a: Error sending sitrep.
,08-29 14:41:11.499  1511  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-29 14:41:11.499  1511  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-29 14:41:11.499  1511  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:41:11.499  1511  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:41:11.514  1721  4322 V BaseAuthAsyncOperation: access token request failed
,08-29 14:41:11.515  3780  4317 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 14:41:11.539   873  4301 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.14,2a00:1450:4001:810::200e
,08-29 14:41:11.562  1511  2877 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-29 14:41:11.562  1511  2877 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-29 14:41:11.563  1511  2877 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:41:11.563  1511  2877 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:41:11.583  3780  4317 E KeepSync: IOException
08-29 14:41:11.583  3780  4317 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 14:41:11.583  3780  4317 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 14:41:11.583  3780  4317 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 14:41:11.583  3780  4317 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 14:41:11.583  3780  4317 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 14:41:11.583  3780  4317 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 14:41:11.583  3780  4317 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 14:41:11.583  3780  4317 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 14:41:11.583  3780  4317 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 14:41:11.583  3780  4317 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 14:41:11.583  3780  4317 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 14:41:11.583  3780  4317 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 14:41:11.583  3780  4317 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 14:41:11.583  3780  4317 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 14:41:11.583  3780  4317 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 14:41:11.583  3780  4317 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 14:41:11.583  3780  4317 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 14:41:11.583  3780  4317 E KeepSync: 	... 10 more
,08-29 14:41:11.583  3780  4317 W KeepSync: Sync result 2
,08-29 14:41:11.593   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 212773, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 14:41:11.626  4011  4318 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-29 14:41:11.855   873  4301 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 29 Aug 2016 12:41:11 GMT], X-Android-Received-Millis=[1472474471853], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472474471624]}
,08-29 14:41:11.858   873  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 14:41:11.860   873  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-29 14:41:11.860   873  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-29 14:41:11.867   873  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 14:41:12.180   873  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-29 14:41:13.425  3863  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 14:41:13.425  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:41:13.425  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:41:13.425  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:41:13.425  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:41:13.425  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:41:13.425  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:41:13.425  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:41:13.429  3863  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:41:13.430  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:41:13.430  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fbce73 removed from the list
08-29 14:41:13.430  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
08-29 14:41:13.430  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:41:13.431  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:41:13.437  3863  4326 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-29 14:41:13.437  3863  4326 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 14:41:16.448  3863  4327 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-29 14:41:16.449  3863  4326 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-29 14:41:16.450  3863  4327 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-29 14:41:16.450  3863  4326 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-29 14:41:16.452  3863  4327 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 14:41:16.452  3863  4326 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 14:41:16.453  3863  4326 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 14:41:16.454  3863  4327 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 14:41:16.455  3863  4326 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-29 14:41:16.456  3863  4327 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-29 14:41:16.461  3863  4329 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 433, name: OutgoingSocketThread/Sender)
08-29 14:41:16.463  3863  4330 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 434, name: IncomingSocketThread/Sender)
08-29 14:41:16.469  3863  4331 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 435, name: OutgoingSocketThread/Receiver)
,08-29 14:41:16.470  3863  4332 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 436, name: IncomingSocketThread/Receiver)
,08-29 14:41:16.470  3863  4331 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 435, thread name: OutgoingSocketThread/Receiver)
,08-29 14:41:16.471  3863  4331 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-29 14:41:16.472  3863  4331 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 435, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-29 14:41:16.472  3863  4332 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 436, thread name: IncomingSocketThread/Receiver)
08-29 14:41:16.472  3863  4332 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-29 14:41:16.474  3863  4332 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 436, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-29 14:41:19.097   873  1315 D ConnectivityService: handlePromptUnvalidated 102
,08-29 14:41:19.448  3863  3915 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 14:41:19.450  3863  3915 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 14:41:19.456  3863  3915 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@74c7270 Bundle[{}]
,08-29 14:41:19.457  3863  3915 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 14:41:19.457  3863  3915 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-29 14:41:19.458  3863  3915 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-29 14:41:19.458  3863  3915 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-29 14:41:19.459  3863  3915 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-29 14:41:19.459  3863  3915 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 14:41:19.463  3863  3915 I System.out: Running OutgoingSocketThread
,08-29 14:41:19.467  3863  4333 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-29 14:41:19.468  3863  4333 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 14:41:22.477  3863  4334 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-29 14:41:22.477  3863  4334 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-29 14:41:22.477  3863  4334 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 14:41:22.478  3863  4333 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-29 14:41:22.478  3863  4333 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-29 14:41:22.479  3863  4334 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-29 14:41:22.479  3863  4333 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 14:41:22.483  3863  4336 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 445, name: IncomingSocketThread/Sender)
08-29 14:41:22.485  3863  4333 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-29 14:41:22.486  3863  4334 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-29 14:41:22.489  3863  4333 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-29 14:41:22.494  3863  4337 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 446, name: IncomingSocketThread/Receiver)
,08-29 14:41:22.495  3863  4337 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 446, thread name: IncomingSocketThread/Receiver)
08-29 14:41:22.495  3863  4338 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 447, name: OutgoingSocketThread/Sender)
08-29 14:41:22.495  3863  4337 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-29 14:41:22.496  3863  4337 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 446, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-29 14:41:22.497  3863  4339 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 448, name: OutgoingSocketThread/Receiver)
08-29 14:41:22.497  3863  4339 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 448, thread name: OutgoingSocketThread/Receiver)
08-29 14:41:22.497  3863  4339 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-29 14:41:22.497  3863  4339 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 448, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-29 14:41:25.479  3863  3915 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 457)
,08-29 14:41:25.482  3863  3915 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-29 14:41:25.482  3863  3915 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 458)
,08-29 14:41:25.488  3863  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:41:25.488  3863  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e102130 added. We now have 3 listener(s)
,08-29 14:41:25.490  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 14:41:25.490  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:41:25.490  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 14:41:25.490  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:41:25.490  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21af1a9 added. We now have 4 listener(s)
08-29 14:41:25.490  3863  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 14:41:25.491  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 14:41:25.498  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:41:25.507  3863  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:41:25.507  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:41:25.507  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:41:25.507  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:41:25.507  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:41:25.507  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:41:25.507  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:41:25.507  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:41:25.511  3863  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:41:25.511  3863  3915 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 14:41:25.512  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 14:41:25.512  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 14:41:25.512  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 14:41:25.512  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 14:41:25.512  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:41:25.512  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 14:41:25.512  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 14:41:25.512  3863  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e102130 removed from the list
08-29 14:41:25.512  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:41:25.512  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21af1a9 removed from the list
,08-29 14:41:25.516  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:41:25.518  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:41:25.518  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 14:41:25.519  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:41:25.521  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:41:25.521  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:41:25.522  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 14:41:25.522  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:41:25.522  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:41:25.522  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21af1a9 not in the list
08-29 14:41:25.523  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:41:25.523  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:41:25.523  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:41:25.524  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 14:41:25.524  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:41:25.524  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21af1a9 not in the list
08-29 14:41:25.524  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:41:25.524  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:41:25.524  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:41:25.524  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e102130 not in the list
,08-29 14:41:25.525  3863  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 14:41:25.525  3863  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53adecf added. We now have 3 listener(s)
08-29 14:41:25.527  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 14:41:25.527  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 14:41:25.527  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 14:41:25.527  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:41:25.527  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0e205c added. We now have 4 listener(s)
08-29 14:41:25.527  3863  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:41:25.529  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 14:41:25.531  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:41:25.536  3863  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:41:25.536  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:41:25.536  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:41:25.536  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:41:25.536  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:41:25.536  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:41:25.536  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:41:25.536  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:41:25.538  3863  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:41:25.539  3863  3915 D io.jxcore.node.ConnectivityMonitor: start: OK,
,08-29 14:41:25.540  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 14:41:25.540  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 14:41:25.540  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 14:41:25.540  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 14:41:25.540  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 14:41:25.541  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:41:25.544  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:41:25.545  3863  3915 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 14:41:25.545  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 14:41:25.549  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 14:41:25.549  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 14:41:25.549  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 14:41:25.553  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 14:41:25.553  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 14:41:25.553  3863  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 14:41:25.554  3863  3915 D BluetoothAdapter: STATE_ON
,08-29 14:41:25.557  4243  4279 D BtGatt.GattService: registerClient() - UUID=d9e9a78e-66da-43df-9809-48f29ebadcbc
,08-29 14:41:25.559  4243  4259 D BtGatt.GattService: onClientRegistered() - UUID=d9e9a78e-66da-43df-9809-48f29ebadcbc, clientIf=5
,08-29 14:41:25.560  3863  3874 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 14:41:25.561  4243  4254 D BtGatt.GattService: start scan with filters
,08-29 14:41:25.565  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 14:41:25.565  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 14:41:25.565  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 14:41:25.565  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 14:41:25.565  4243  4262 D BtGatt.ScanManager: handling starting scan
,08-29 14:41:25.568  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 14:41:25.568  4243  4262 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ecbba04,
08-29 14:41:25.568  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 14:41:25.568  3863  3863 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 14:41:25.570  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 14:41:25.573  3863  3915 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 14:41:25.573  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:41:25.573  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 14:41:25.574  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:41:25.574  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-29 14:41:25.574  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 14:41:25.574  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
,08-29 14:41:25.577  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 14:41:25.577  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 14:41:25.577  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 14:41:25.577  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 14:41:25.577  4243  4259 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 14:41:25.578  3863  3915 D BluetoothAdapter: STATE_ON,
08-29 14:41:25.578  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:41:25.579  4243  4253 D BtGatt.GattService: stopScan() - queue size =1
,08-29 14:41:25.580  4243  4272 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 14:41:25.580  4243  4262 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 14:41:25.580  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:41:25.580  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 14:41:25.580  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 14:41:25.580  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 14:41:25.581  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 14:41:25.582  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:41:25.583  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 14:41:25.583  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 14:41:25.583  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 14:41:25.584  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 14:41:25.586  3863  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:41:25.586  3863  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 14:41:25.586  3863  3863 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 14:41:25.587  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-29 14:41:25.588  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:41:25.589  4243  4262 D BtGatt.ScanManager: Starting BLE batch scan
08-29 14:41:25.589  4243  4262 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 14:41:25.603  4243  4259 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 14:41:25.604  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:41:25.615  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-29 14:41:25.615  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:41:25.628  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-29 14:41:25.628  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 14:41:25.628  4243  4262 D BtGatt.ScanManager: stopping BLe Batch
,08-29 14:41:25.641  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 14:41:25.641  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:41:25.642  4243  4262 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 14:41:25.659  4243  4259 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 14:41:25.659  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 14:41:26.087  3863  3863 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-29 14:41:26.088  3863  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:41:26.088  3863  3863 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 14:41:28.586  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 14:41:28.587  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:41:28.587  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 14:41:28.587  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 14:41:28.588  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:41:28.588  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 14:41:28.588  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 14:41:28.590  3863  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53adecf removed from the list
,08-29 14:41:28.590  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:41:28.591  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0e205c removed from the list
,08-29 14:41:28.591  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 14:41:28.592  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:41:28.596  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:41:28.596  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:41:28.600  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:41:28.600  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:41:28.601  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:41:28.601  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0e205c not in the list
08-29 14:41:28.602  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 14:41:28.602  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:41:28.605  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 14:41:28.606  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 14:41:28.606  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 14:41:28.606  3863  3915 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0e205c not in the list
,08-29 14:41:28.606  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 14:41:28.607  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:41:28.607  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 14:41:28.607  3863  3915 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53adecf not in the list
,08-29 14:41:28.609  3863  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 14:41:28.610  3863  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe2ce1 added. We now have 3 listener(s)
,08-29 14:41:28.615  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-29 14:41:28.616  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 14:41:28.616  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 14:41:28.616  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 14:41:28.617  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ebda06 added. We now have 4 listener(s)
08-29 14:41:28.617  3863  3915 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 14:41:28.618  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 14:41:28.623  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:41:28.631  3863  3915 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 14:41:28.631  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 14:41:28.631  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 14:41:28.631  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 14:41:28.631  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 14:41:28.631  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 14:41:28.631  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 14:41:28.631  3863  3915 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 14:41:28.635  3863  3915 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 14:41:28.636  3863  3915 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 14:41:28.637  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-29 14:41:28.638  3863  3915 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-29 14:41:28.639  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,08-29 14:41:28.641  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-29 14:41:28.641  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-29 14:41:28.642  3863  3915 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 14:41:28.641  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 14:41:28.643  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:41:28.645  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-29 14:41:28.645  3863  3915 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 14:41:28.645  3863  3915 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-29 14:41:28.646  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 14:41:28.646  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,08-29 14:41:28.646  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 14:41:28.646  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 14:41:28.651  3863  3863 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 14:41:28.651  3863  3863 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 14:41:28.650  3863  4341 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 14:41:28.653  3863  3915 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 14:41:28.653  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 14:41:28.656  3863  4341 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-29 14:41:28.659  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 14:41:28.660  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 14:41:28.660  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 14:41:28.664  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-29 14:41:28.664  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-29 14:41:28.665  3863  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,08-29 14:41:28.666  3863  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 14:41:28.666  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-29 14:41:28.666  3863  3915 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-29 14:41:28.667  3863  3915 D BluetoothAdapter: STATE_ON
,08-29 14:41:28.671  4243  4253 D BtGatt.GattService: registerClient() - UUID=45d39299-0e60-4be8-876c-762e23dda4a9
,08-29 14:41:28.672  4243  4259 D BtGatt.GattService: onClientRegistered() - UUID=45d39299-0e60-4be8-876c-762e23dda4a9, clientIf=5
,08-29 14:41:28.673  3863  3935 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-29 14:41:28.676  4243  4261 D BtGatt.AdvertiseManager: message : 0
,08-29 14:41:28.683  4243  4261 D BtGatt.AdvertiseManager: starting multi advertising
,08-29 14:41:28.702  4243  4259 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-29 14:41:28.718  4243  4259 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-29 14:41:28.721  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-29 14:41:28.722  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 14:41:28.730  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 14:41:28.734  3863  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-29 14:41:28.735  3863  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-29 14:41:28.736  3863  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-29 14:41:28.736  3863  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-29 14:41:28.736  3863  3863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-29 14:41:28.736  3863  3863 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-29 14:41:28.741  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-29 14:41:28.747  3863  3863 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 14:41:28.747  3863  3863 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-29 14:41:29.248  3863  3863 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-29 14:41:29.249  3863  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 14:41:29.249  3863  3863 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 14:41:31.743  3863  3915 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 14:41:31.743  3863  3915 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-29 14:41:31.744  3863  3915 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 14:41:31.744  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 14:41:31.745  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-29 14:41:31.745  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 14:41:31.747  3863  4341 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 14:41:31.747  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-29 14:41:31.748  3863  4341 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 14:41:31.748  3863  3915 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 14:41:31.748  3863  4341 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 14:41:31.748  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-29 14:41:31.748  3863  3863 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 14:41:31.748  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 14:41:31.749  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-29 14:41:31.749  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 14:41:31.749  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 14:41:31.752  3863  3915 D BluetoothAdapter: STATE_ON
08-29 14:41:31.753  3863  3915 D BluetoothLeScanner: could not find callback wrapper
08-29 14:41:31.753  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 14:41:31.753  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-29 14:41:31.756  4243  4261 D BtGatt.AdvertiseManager: message : 1
,08-29 14:41:31.757  4243  4261 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-29 14:41:31.766  4243  4259 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-29 14:41:31.767  4243  4259 D BtGatt.GattService: Client app is not null!
,08-29 14:41:31.768  4243  4279 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-29 14:41:31.769  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 14:41:31.770  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-29 14:41:31.770  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-29 14:41:31.770  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-29 14:41:31.770  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-29 14:41:31.771  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 14:41:31.772  3863  3915 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 14:41:31.772  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 14:41:31.773  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 14:41:31.776  3863  3863 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-29 14:41:31.776  3863  3863 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-29 14:41:31.776  3863  3915 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-29 14:41:31.777  3863  3915 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 14:41:31.777  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
08-29 14:41:31.777  3863  3863 D AndroidRuntime: Shutting down VM
08-29 14:41:31.777  3863  3915 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 14:41:31.777  3863  3915 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe2ce1 removed from the list
,--------- beginning of crash
08-29 14:41:31.778  3863  3863 E AndroidRuntime: FATAL EXCEPTION: main
08-29 14:41:31.778  3863  3863 E AndroidRuntime: Process: com.test.thalitest, PID: 3863
08-29 14:41:31.778  3863  3863 E AndroidRuntime: java.lang.NullPointerException: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
08-29 14:41:31.778  3863  3863 E AndroidRuntime: 	at io.jxcore.node.StartStopOperationHandler.checkCurrentOperationStatus(StartStopOperationHandler.java:105)
08-29 14:41:31.778  3863  3863 E AndroidRuntime: 	at io.jxcore.node.ConnectionHelper.onConnectionManagerStateChanged(ConnectionHelper.java:360)
08-29 14:41:31.778  3863  3863 E AndroidRuntime: 	at org.thaliproject.p2p.btconnectorlib.ConnectionManager$4.run(ConnectionManager.java:447)
08-29 14:41:31.778  3863  3863 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 14:41:31.778  3863  3863 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,08-29 14:41:31.778  3863  3863 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 14:41:31.778  3863  3863 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 14:41:31.778  3863  3863 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 14:41:31.778  3863  3863 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 14:41:31.778  3863  3863 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 14:41:31.778  3863  3915 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 14:41:31.778  3863  3915 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ebda06 removed from the list
08-29 14:41:31.778  3863  3915 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 14:41:31.778  3863  3915 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 14:41:31.784   873  1376 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
,08-29 14:41:31.794  3863  3863 I Process : Sending signal. PID: 3863 SIG: 9
,08-29 14:41:31.908   873  1314 D WifiService: Client connection lost with reason: 4
,08-29 14:41:31.918   873  2083 D GraphicsStats: Buffer count: 2
,08-29 14:41:31.919   873   883 I WindowState: WIN DEATH: Window{79fd20e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 14:41:31.949   873  1963 I ActivityManager: Process com.test.thalitest (pid 3863) has died
,08-29 14:41:31.996   873  1405 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3863 uid 10000
,08-29 14:41:31.998  1878  1878 I Keyboard.Facilitator: onFinishInput()
,08-29 14:41:41.176   873  4302 D NetlinkSocketObserver: NeighborEvent{elapsedMs=246790, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 14:41:42.779  3780  4344 V KeepSync: Connecting to GoogleApiClient
08-29 14:41:42.779   873   884 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 14:41:42.850  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:41:42.854  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:41:42.906  1511  2877 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-29 14:41:42.907  1511  2877 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-29 14:41:42.907  1511  2877 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 14:41:42.907  1511  2877 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:41:42.946  1721  4345 V BaseAuthAsyncOperation: access token request failed
,08-29 14:41:42.948  3780  4344 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 14:41:43.038  1511  2173 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-29 14:41:43.038  1511  2173 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-29 14:41:43.038  1511  2173 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:41:43.038  1511  2173 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:41:43.076  3780  4344 E KeepSync: IOException
08-29 14:41:43.076  3780  4344 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 14:41:43.076  3780  4344 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 14:41:43.076  3780  4344 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 14:41:43.076  3780  4344 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 14:41:43.076  3780  4344 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 14:41:43.076  3780  4344 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 14:41:43.076  3780  4344 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 14:41:43.076  3780  4344 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 14:41:43.076  3780  4344 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 14:41:43.076  3780  4344 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 14:41:43.076  3780  4344 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 14:41:43.076  3780  4344 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 14:41:43.076  3780  4344 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 14:41:43.076  3780  4344 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 14:41:43.076  3780  4344 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 14:41:43.076  3780  4344 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 14:41:43.076  3780  4344 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 14:41:43.076  3780  4344 E KeepSync: 	... 10 more
08-29 14:41:43.076  3780  4344 W KeepSync: Sync result 2
,08-29 14:41:43.092   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 248233, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 14:42:02.971   873  4302 D NetlinkSocketObserver: NeighborEvent{elapsedMs=268586, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 14:42:09.750  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:42:09.752  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:42:09.778  3816  4347 V GoogleAuthProtoRequest: [324] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 14:42:09.800  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-29 14:42:09.800  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-29 14:42:09.800  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:42:09.800  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:42:09.815  3816  4347 W ExperimentUpdateService: [324] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
08-29 14:42:09.815  3816  4347 W ExperimentUpdateService: [324] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 14:42:09.815  3816  4347 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 14:42:09.815  3816  4347 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-29 14:42:09.815  3816  4347 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-29 14:42:09.815  3816  4347 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-29 14:42:09.815  3816  4347 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-29 14:42:09.815  3816  4347 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-29 14:42:09.815  3816  4347 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-29 14:42:09.815  3816  4347 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-29 14:42:09.815  3816  4347 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-29 14:42:09.815  3816  4347 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-29 14:42:13.236  3759  4350 I BooksSync: Starting books sync for 61035162, extras: ade
,08-29 14:42:13.325  3759  4352 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-29 14:42:13.367  1511  2173 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 14:42:13.368  1511  2173 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-29 14:42:13.368  1511  2173 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:42:13.368  1511  2173 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,08-29 14:42:13.416  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 14:42:13.416  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 14:42:13.416  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 14:42:13.416  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:42:13.450  3565  4351 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 14:42:13.450  3565  4351 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 14:42:13.450  3565  4351 E HttpOperation: 	at jdm.a(PG:82)
08-29 14:42:13.450  3565  4351 E HttpOperation: 	at jcs.o(PG:406)
08-29 14:42:13.450  3565  4351 E HttpOperation: 	at jcn.a(PG:1379)
08-29 14:42:13.450  3565  4351 E HttpOperation: 	at jcs.i(PG:143)
08-29 14:42:13.450  3565  4351 E HttpOperation: 	at blb.a(PG:3937)
08-29 14:42:13.450  3565  4351 E HttpOperation: 	at czp.a(PG:18188)
08-29 14:42:13.450  3565  4351 E HttpOperation: 	at czp.a(PG:9081)
08-29 14:42:13.450  3565  4351 E HttpOperation: 	at czq.run(PG:1686)
08-29 14:42:13.450  3565  4351 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 14:42:13.450  3565  4351 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 14:42:13.450  3565  4351 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 14:42:13.450  3565  4351 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 14:42:13.450  3565  4351 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 14:42:13.450  3565  4351 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 14:42:13.450  3565  4351 E HttpOperation: 	at jdj.a(PG:4091)
08-29 14:42:13.450  3565  4351 E HttpOperation: 	at jdj.a(PG:1125)
08-29 14:42:13.450  3565  4351 E HttpOperation: 	at jdm.a(PG:77)
08-29 14:42:13.450  3565  4351 E HttpOperation: 	... 12 more
08-29 14:42:13.450  3565  4351 E HttpOperation: Caused by: faj: BadAuthentication
08-29 14:42:13.450  3565  4351 E HttpOperation: 	at fal.a(PG:38)
08-29 14:42:13.450  3565  4351 E HttpOperation: 	at jdj.a(PG:4089)
08-29 14:42:13.450  3565  4351 E HttpOperation: 	... 14 more
,08-29 14:42:13.493  1511  2877 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 14:42:13.493  1511  2877 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-29 14:42:13.493  1511  2877 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:42:13.493  1511  2877 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:42:13.529  3759  4352 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-29 14:42:13.530  3759  4350 E BooksSync: Soft error
08-29 14:42:13.530  3759  4350 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 14:42:13.530  3759  4350 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-29 14:42:13.530  3759  4350 E BooksSync: Sync error
08-29 14:42:13.530  3759  4350 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 14:42:13.530  3759  4350 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-29 14:42:13.530  3759  4350 I BooksSync: Finished books sync
,08-29 14:42:13.536  1511  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-29 14:42:13.536  1511  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-29 14:42:13.536  1511  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:42:13.536  1511  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:42:13.544   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 269257, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 14:42:13.558  3565  4351 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 14:42:13.558  3565  4351 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 14:42:13.558  3565  4351 E HttpOperation: 	at jdm.a(PG:82)
08-29 14:42:13.558  3565  4351 E HttpOperation: 	at jcs.o(PG:406)
08-29 14:42:13.558  3565  4351 E HttpOperation: 	at jcn.a(PG:1379)
08-29 14:42:13.558  3565  4351 E HttpOperation: 	at jcs.i(PG:143)
08-29 14:42:13.558  3565  4351 E HttpOperation: 	at hec.a(PG:42)
08-29 14:42:13.558  3565  4351 E HttpOperation: 	at hee.a(PG:102)
08-29 14:42:13.558  3565  4351 E HttpOperation: 	at czr.a(PG:65)
08-29 14:42:13.558  3565  4351 E HttpOperation: 	at kka.a(PG:108)
08-29 14:42:13.558  3565  4351 E HttpOperation: 	at czp.a(PG:19176)
08-29 14:42:13.558  3565  4351 E HttpOperation: 	at czp.a(PG:9081)
08-29 14:42:13.558  3565  4351 E HttpOperation: 	at czq.run(PG:1686)
08-29 14:42:13.558  3565  4351 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 14:42:13.558  3565  4351 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 14:42:13.558  3565  4351 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 14:42:13.558  3565  4351 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 14:42:13.558  3565  4351 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 14:42:13.558  3565  4351 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 14:42:13.558  3565  4351 E HttpOperation: 	at jdj.a(PG:4091)
08-29 14:42:13.558  3565  4351 E HttpOperation: 	at jdj.a(PG:1125)
08-29 14:42:13.558  3565  4351 E HttpOperation: 	at jdm.a(PG:77)
08-29 14:42:13.558  3565  4351 E HttpOperation: 	... 15 more
08-29 14:42:13.558  3565  4351 E HttpOperation: Caused by: faj: BadAuthentication
08-29 14:42:13.558  3565  4351 E HttpOperation: 	at fal.a(PG:38)
08-29 14:42:13.558  3565  4351 E HttpOperation: 	at jdj.a(PG:4089)
08-29 14:42:13.558  3565  4351 E HttpOperation: 	... 17 more
,08-29 14:42:13.559  3565  4351 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 14:42:13.559  3565  4351 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 14:42:13.559  3565  4351 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 14:42:13.559  3565  4351 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 14:42:13.559  3565  4351 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 14:42:13.559  3565  4351 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 14:42:13.559  3565  4351 E ExperimentLoader: 	at hec.a(PG:42)
08-29 14:42:13.559  3565  4351 E ExperimentLoader: 	at hee.a(PG:102)
08-29 14:42:13.559  3565  4351 E ExperimentLoader: 	at czr.a(PG:65)
08-29 14:42:13.559  3565  4351 E ExperimentLoader: 	at kka.a(PG:108)
08-29 14:42:13.559  3565  4351 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 14:42:13.559  3565  4351 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 14:42:13.559  3565  4351 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 14:42:13.559  3565  4351 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 14:42:13.559  3565  4351 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 14:42:13.559  3565  4351 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 14:42:13.559  3565  4351 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 14:42:13.559  3565  4351 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 14:42:13.559  3565  4351 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 14:42:13.559  3565  4351 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 14:42:13.559  3565  4351 E ExperimentLoader: 	at jdj.a(PG:1125)
08-29 14:42:13.559  3565  4351 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 14:42:13.559  3565  4351 E ExperimentLoader: 	... 15 more
08-29 14:42:13.559  3565  4351 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 14:42:13.559  3565  4351 E ExperimentLoader: 	at fal.a(PG:38)
08-29 14:42:13.559  3565  4351 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 14:42:13.559  3565  4351 E ExperimentLoader: 	... 17 more
,08-29 14:42:13.695   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 269072, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-29 14:42:31.718   873  4302 D NetlinkSocketObserver: NeighborEvent{elapsedMs=297332, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 14:42:32.040  1878  1926 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-29 14:42:32.040  1878  1926 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-29 14:42:32.077  1511  1511 I ConfigService: onCreate
,08-29 14:42:37.141  1511  1511 I ConfigService: onDestroy
,08-29 14:42:44.726  3759  4360 I BooksSync: Starting books sync for 61035162, extras: ade
,08-29 14:42:44.752  3759  4361 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-29 14:42:44.765  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:42:44.767  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:42:44.798  1511  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 14:42:44.798  1511  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-29 14:42:44.798  1511  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:42:44.798  1511  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:42:44.828  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:42:44.832  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:42:44.866  1511  2877 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-29 14:42:44.866  1511  2877 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 14:42:44.866  1511  2877 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 14:42:44.866  1511  2877 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:42:44.891  3759  4361 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-29 14:42:44.892  3759  4360 E BooksSync: Soft error
08-29 14:42:44.892  3759  4360 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 14:42:44.892  3759  4360 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 14:42:44.892  3759  4360 E BooksSync: Sync error
08-29 14:42:44.892  3759  4360 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 14:42:44.892  3759  4360 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-29 14:42:44.892  3759  4360 I BooksSync: Finished books sync
,08-29 14:42:44.905   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 310226, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 14:42:58.584   873  4302 D NetlinkSocketObserver: NeighborEvent{elapsedMs=324199, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 14:43:15.170  3780  4364 V KeepSync: Connecting to GoogleApiClient
,08-29 14:43:15.171   873   884 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 14:43:15.228  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:43:15.229  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:43:15.262  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-29 14:43:15.262  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-29 14:43:15.262  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 14:43:15.262  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:43:15.288  1721  4367 V BaseAuthAsyncOperation: access token request failed
,08-29 14:43:15.292  3780  4364 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 14:43:15.371  1511  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 14:43:15.371  1511  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 14:43:15.371  1511  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:43:15.371  1511  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:43:15.419  3565  4366 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 14:43:15.419  3565  4366 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 14:43:15.419  3565  4366 E HttpOperation: 	at jdm.a(PG:82)
08-29 14:43:15.419  3565  4366 E HttpOperation: 	at jcs.o(PG:406)
08-29 14:43:15.419  3565  4366 E HttpOperation: 	at jcn.a(PG:1379)
08-29 14:43:15.419  3565  4366 E HttpOperation: 	at jcs.i(PG:143)
08-29 14:43:15.419  3565  4366 E HttpOperation: 	at blb.a(PG:3937)
08-29 14:43:15.419  3565  4366 E HttpOperation: 	at czp.a(PG:18188)
08-29 14:43:15.419  3565  4366 E HttpOperation: 	at czp.a(PG:9081)
08-29 14:43:15.419  3565  4366 E HttpOperation: 	at czq.run(PG:1686)
08-29 14:43:15.419  3565  4366 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 14:43:15.419  3565  4366 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 14:43:15.419  3565  4366 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 14:43:15.419  3565  4366 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 14:43:15.419  3565  4366 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 14:43:15.419  3565  4366 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 14:43:15.419  3565  4366 E HttpOperation: 	at jdj.a(PG:4091)
08-29 14:43:15.419  3565  4366 E HttpOperation: 	at jdj.a(PG:1125)
08-29 14:43:15.419  3565  4366 E HttpOperation: 	at jdm.a(PG:77)
08-29 14:43:15.419  3565  4366 E HttpOperation: 	... 12 more
08-29 14:43:15.419  3565  4366 E HttpOperation: Caused by: faj: BadAuthentication
08-29 14:43:15.419  3565  4366 E HttpOperation: 	at fal.a(PG:38)
08-29 14:43:15.419  3565  4366 E HttpOperation: 	at jdj.a(PG:4089)
08-29 14:43:15.419  3565  4366 E HttpOperation: 	... 14 more
,08-29 14:43:15.561  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 14:43:15.561  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 14:43:15.561  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:43:15.561  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:43:15.566  1511  2173 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-29 14:43:15.566  1511  2173 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-29 14:43:15.566  1511  2173 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 14:43:15.566  1511  2173 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:43:15.577  3565  4366 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 14:43:15.577  3565  4366 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 14:43:15.577  3565  4366 E HttpOperation: 	at jdm.a(PG:82)
08-29 14:43:15.577  3565  4366 E HttpOperation: 	at jcs.o(PG:406)
08-29 14:43:15.577  3565  4366 E HttpOperation: 	at jcn.a(PG:1379)
08-29 14:43:15.577  3565  4366 E HttpOperation: 	at jcs.i(PG:143)
08-29 14:43:15.577  3565  4366 E HttpOperation: 	at hec.a(PG:42)
08-29 14:43:15.577  3565  4366 E HttpOperation: 	at hee.a(PG:102)
08-29 14:43:15.577  3565  4366 E HttpOperation: 	at czr.a(PG:65)
08-29 14:43:15.577  3565  4366 E HttpOperation: 	at kka.a(PG:108)
08-29 14:43:15.577  3565  4366 E HttpOperation: 	at czp.a(PG:19176)
08-29 14:43:15.577  3565  4366 E HttpOperation: 	at czp.a(PG:9081)
08-29 14:43:15.577  3565  4366 E HttpOperation: 	at czq.run(PG:1686)
08-29 14:43:15.577  3565  4366 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 14:43:15.577  3565  4366 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 14:43:15.577  3565  4366 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 14:43:15.577  3565  4366 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 14:43:15.577  3565  4366 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 14:43:15.577  3565  4366 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 14:43:15.577  3565  4366 E HttpOperation: 	at jdj.a(PG:4091)
08-29 14:43:15.577  3565  4366 E HttpOperation: 	at jdj.a(PG:1125)
08-29 14:43:15.577  3565  4366 E HttpOperation: 	at jdm.a(PG:77)
08-29 14:43:15.577  3565  4366 E HttpOperation: 	... 15 more
08-29 14:43:15.577  3565  4366 E HttpOperation: Caused by: faj: BadAuthentication
08-29 14:43:15.577  3565  4366 E HttpOperation: 	at fal.a(PG:38)
08-29 14:43:15.577  3565  4366 E HttpOperation: 	at jdj.a(PG:4089)
08-29 14:43:15.577  3565  4366 E HttpOperation: 	... 17 more
08-29 14:43:15.577  3565  4366 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 14:43:15.577  3565  4366 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 14:43:15.577  3565  4366 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 14:43:15.577  3565  4366 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 14:43:15.577  3565  4366 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 14:43:15.577  3565  4366 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 14:43:15.577  3565  4366 E ExperimentLoader: 	at hec.a(PG:42)
08-29 14:43:15.577  3565  4366 E ExperimentLoader: 	at hee.a(PG:102)
08-29 14:43:15.577  3565  4366 E ExperimentLoader: 	at czr.a(PG:65)
08-29 14:43:15.577  3565  4366 E ExperimentLoader: 	at kka.a(PG:108)
08-29 14:43:15.577  3565  4366 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 14:43:15.577  3565  4366 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 14:43:15.577  3565  4366 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 14:43:15.577  3565  4366 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 14:43:15.577  3565  4366 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 14:43:15.577  3565  4366 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 14:43:15.577  3565  4366 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 14:43:15.577  3565  4366 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 14:43:15.577  3565  4366 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 14:43:15.577  3565  4366 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 14:43:15.577  3565  4366 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-29 14:43:15.577  3565  4366 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 14:43:15.577  3565  4366 E ExperimentLoader: 	... 15 more
08-29 14:43:15.577  3565  4366 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 14:43:15.577  3565  4366 E ExperimentLoader: 	at fal.a(PG:38)
08-29 14:43:15.577  3565  4366 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 14:43:15.577  3565  4366 E ExperimentLoader: 	... 17 more
,08-29 14:43:15.620  3780  4364 E KeepSync: IOException
08-29 14:43:15.620  3780  4364 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 14:43:15.620  3780  4364 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 14:43:15.620  3780  4364 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 14:43:15.620  3780  4364 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 14:43:15.620  3780  4364 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 14:43:15.620  3780  4364 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 14:43:15.620  3780  4364 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 14:43:15.620  3780  4364 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 14:43:15.620  3780  4364 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 14:43:15.620  3780  4364 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 14:43:15.620  3780  4364 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 14:43:15.620  3780  4364 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 14:43:15.620  3780  4364 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 14:43:15.620  3780  4364 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 14:43:15.620  3780  4364 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 14:43:15.620  3780  4364 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 14:43:15.620  3780  4364 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 14:43:15.620  3780  4364 E KeepSync: 	... 10 more
,08-29 14:43:15.620  3780  4364 W KeepSync: Sync result 2
,08-29 14:43:15.629   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 310758, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 14:43:15.686   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 312069, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-29 14:43:27.289   873  4302 D NetlinkSocketObserver: NeighborEvent{elapsedMs=352904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 14:43:38.080  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:43:38.091  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:43:38.092  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:43:38.144  1511  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-29 14:43:38.145  1511  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-29 14:43:38.145  1511  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:43:38.146  1511  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:43:38.169  1511  2011 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-29 14:43:38.169  1511  2011 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-29 14:43:38.169  1511  2011 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-29 14:43:38.169  1511  2011 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-29 14:43:38.169  1511  2011 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-29 14:43:38.169  1511  2011 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-29 14:43:38.169  1511  2011 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-29 14:43:38.173  3528  3557 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-29 14:43:38.173  3528  3557 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-29 14:43:38.173  3528  3557 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-29 14:43:38.173  3528  3557 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-29 14:43:38.173  3528  3557 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-29 14:43:38.173  3528  3557 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-29 14:43:38.173  3528  3557 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-29 14:43:43.209   873  4302 D NetlinkSocketObserver: NeighborEvent{elapsedMs=368824, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 14:43:47.145  3759  4375 I BooksSync: Starting books sync for 61035162, extras: ade
,08-29 14:43:47.187  3759  4376 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-29 14:43:47.214  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:43:47.218  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:43:47.266  1511  2877 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 14:43:47.266  1511  2877 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-29 14:43:47.267  1511  2877 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 14:43:47.267  1511  2877 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:43:47.336  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:43:47.342  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:43:47.392  1511  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 14:43:47.392  1511  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 14:43:47.392  1511  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:43:47.392  1511  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:43:47.419  3759  4376 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-29 14:43:47.420  3759  4375 E BooksSync: Soft error
08-29 14:43:47.420  3759  4375 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 14:43:47.420  3759  4375 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-29 14:43:47.420  3759  4375 E BooksSync: Sync error
08-29 14:43:47.420  3759  4375 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 14:43:47.420  3759  4375 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-29 14:43:47.420  3759  4375 I BooksSync: Finished books sync
,08-29 14:43:47.424   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 372653, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 14:44:07.290   873  4302 D NetlinkSocketObserver: NeighborEvent{elapsedMs=392905, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 14:44:21.535  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:44:21.538  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:44:21.576  1511  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 14:44:21.576  1511  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-29 14:44:21.576  1511  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 14:44:21.576  1511  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:44:21.610  3565  4379 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 14:44:21.610  3565  4379 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 14:44:21.610  3565  4379 E HttpOperation: 	at jdm.a(PG:82)
08-29 14:44:21.610  3565  4379 E HttpOperation: 	at jcs.o(PG:406)
08-29 14:44:21.610  3565  4379 E HttpOperation: 	at jcn.a(PG:1379)
08-29 14:44:21.610  3565  4379 E HttpOperation: 	at jcs.i(PG:143)
08-29 14:44:21.610  3565  4379 E HttpOperation: 	at blb.a(PG:3937)
08-29 14:44:21.610  3565  4379 E HttpOperation: 	at czp.a(PG:18188)
08-29 14:44:21.610  3565  4379 E HttpOperation: 	at czp.a(PG:9081)
08-29 14:44:21.610  3565  4379 E HttpOperation: 	at czq.run(PG:1686)
08-29 14:44:21.610  3565  4379 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 14:44:21.610  3565  4379 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 14:44:21.610  3565  4379 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 14:44:21.610  3565  4379 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 14:44:21.610  3565  4379 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 14:44:21.610  3565  4379 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 14:44:21.610  3565  4379 E HttpOperation: 	at jdj.a(PG:4091)
08-29 14:44:21.610  3565  4379 E HttpOperation: 	at jdj.a(PG:1125)
08-29 14:44:21.610  3565  4379 E HttpOperation: 	at jdm.a(PG:77)
08-29 14:44:21.610  3565  4379 E HttpOperation: 	... 12 more
08-29 14:44:21.610  3565  4379 E HttpOperation: Caused by: faj: BadAuthentication
08-29 14:44:21.610  3565  4379 E HttpOperation: 	at fal.a(PG:38)
08-29 14:44:21.610  3565  4379 E HttpOperation: 	at jdj.a(PG:4089)
08-29 14:44:21.610  3565  4379 E HttpOperation: 	... 14 more
,08-29 14:44:21.676  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 14:44:21.676  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-29 14:44:21.676  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 14:44:21.676  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:44:21.709  3565  4379 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 14:44:21.709  3565  4379 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 14:44:21.709  3565  4379 E HttpOperation: 	at jdm.a(PG:82)
08-29 14:44:21.709  3565  4379 E HttpOperation: 	at jcs.o(PG:406)
08-29 14:44:21.709  3565  4379 E HttpOperation: 	at jcn.a(PG:1379)
08-29 14:44:21.709  3565  4379 E HttpOperation: 	at jcs.i(PG:143)
08-29 14:44:21.709  3565  4379 E HttpOperation: 	at hec.a(PG:42)
08-29 14:44:21.709  3565  4379 E HttpOperation: 	at hee.a(PG:102)
08-29 14:44:21.709  3565  4379 E HttpOperation: 	at czr.a(PG:65)
08-29 14:44:21.709  3565  4379 E HttpOperation: 	at kka.a(PG:108)
08-29 14:44:21.709  3565  4379 E HttpOperation: 	at czp.a(PG:19176)
08-29 14:44:21.709  3565  4379 E HttpOperation: 	at czp.a(PG:9081)
08-29 14:44:21.709  3565  4379 E HttpOperation: 	at czq.run(PG:1686)
08-29 14:44:21.709  3565  4379 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 14:44:21.709  3565  4379 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 14:44:21.709  3565  4379 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 14:44:21.709  3565  4379 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 14:44:21.709  3565  4379 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 14:44:21.709  3565  4379 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 14:44:21.709  3565  4379 E HttpOperation: 	at jdj.a(PG:4091)
08-29 14:44:21.709  3565  4379 E HttpOperation: 	at jdj.a(PG:1125)
08-29 14:44:21.709  3565  4379 E HttpOperation: 	at jdm.a(PG:77)
08-29 14:44:21.709  3565  4379 E HttpOperation: 	... 15 more
08-29 14:44:21.709  3565  4379 E HttpOperation: Caused by: faj: BadAuthentication
08-29 14:44:21.709  3565  4379 E HttpOperation: 	at fal.a(PG:38)
08-29 14:44:21.709  3565  4379 E HttpOperation: 	at jdj.a(PG:4089)
08-29 14:44:21.709  3565  4379 E HttpOperation: 	... 17 more
08-29 14:44:21.709  3565  4379 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 14:44:21.709  3565  4379 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 14:44:21.709  3565  4379 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 14:44:21.709  3565  4379 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 14:44:21.709  3565  4379 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 14:44:21.709  3565  4379 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 14:44:21.709  3565  4379 E ExperimentLoader: 	at hec.a(PG:42)
08-29 14:44:21.709  3565  4379 E ExperimentLoader: 	at hee.a(PG:102)
08-29 14:44:21.709  3565  4379 E ExperimentLoader: 	at czr.a(PG:65)
08-29 14:44:21.709  3565  4379 E ExperimentLoader: 	at kka.a(PG:108)
08-29 14:44:21.709  3565  4379 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 14:44:21.709  3565  4379 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 14:44:21.709  3565  4379 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 14:44:21.709  3565  4379 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 14:44:21.709  3565  4379 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 14:44:21.709  3565  4379 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 14:44:21.709  3565  4379 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 14:44:21.709  3565  4379 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 14:44:21.709  3565  4379 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 14:44:21.709  3565  4379 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 14:44:21.709  3565  4379 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-29 14:44:21.709  3565  4379 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 14:44:21.709  3565  4379 E ExperimentLoader: 	... 15 more
08-29 14:44:21.709  3565  4379 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 14:44:21.709  3565  4379 E ExperimentLoader: 	at fal.a(PG:38)
08-29 14:44:21.709  3565  4379 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 14:44:21.709  3565  4379 E ExperimentLoader: 	... 17 more
,08-29 14:44:21.843   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 406817, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-29 14:44:31.050   873  4302 D NetlinkSocketObserver: NeighborEvent{elapsedMs=416664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 14:45:00.091   873  4302 D NetlinkSocketObserver: NeighborEvent{elapsedMs=445706, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 14:45:16.771   873  4302 D NetlinkSocketObserver: NeighborEvent{elapsedMs=462385, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 14:45:19.814  3780  4384 V KeepSync: Connecting to GoogleApiClient
,08-29 14:45:19.815   873  1697 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-29 14:45:19.870  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:45:19.874  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:45:19.911  1511  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-29 14:45:19.912  1511  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-29 14:45:19.912  1511  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:45:19.912  1511  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:45:19.936  1721  4385 V BaseAuthAsyncOperation: access token request failed
,08-29 14:45:19.937  3780  4384 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-29 14:45:20.009  1511  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-29 14:45:20.010  1511  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-29 14:45:20.010  1511  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:45:20.010  1511  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:45:20.036  3780  4384 E KeepSync: IOException
08-29 14:45:20.036  3780  4384 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-29 14:45:20.036  3780  4384 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-29 14:45:20.036  3780  4384 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-29 14:45:20.036  3780  4384 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-29 14:45:20.036  3780  4384 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-29 14:45:20.036  3780  4384 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-29 14:45:20.036  3780  4384 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-29 14:45:20.036  3780  4384 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-29 14:45:20.036  3780  4384 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-29 14:45:20.036  3780  4384 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-29 14:45:20.036  3780  4384 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-29 14:45:20.036  3780  4384 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-29 14:45:20.036  3780  4384 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-29 14:45:20.036  3780  4384 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-29 14:45:20.036  3780  4384 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 14:45:20.036  3780  4384 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-29 14:45:20.036  3780  4384 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-29 14:45:20.036  3780  4384 E KeepSync: 	... 10 more
08-29 14:45:20.036  3780  4384 W KeepSync: Sync result 2
,08-29 14:45:20.047   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 465344, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 14:45:45.637   873  4302 D NetlinkSocketObserver: NeighborEvent{elapsedMs=491252, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 14:45:51.775  3759  4387 I BooksSync: Starting books sync for 61035162, extras: ade
,08-29 14:45:51.796  3759  4388 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-29 14:45:51.810  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:45:51.812  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:45:51.838  1511  2877 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 14:45:51.838  1511  2877 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-29 14:45:51.838  1511  2877 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:45:51.838  1511  2877 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:45:51.872  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:45:51.874  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:45:51.900  1511  2173 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-29 14:45:51.900  1511  2173 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-29 14:45:51.900  1511  2173 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:45:51.900  1511  2173 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:45:51.915  3759  4388 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-29 14:45:51.916  3759  4387 E BooksSync: Soft error
08-29 14:45:51.916  3759  4387 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 14:45:51.916  3759  4387 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-29 14:45:51.916  3759  4387 E BooksSync: Sync error
08-29 14:45:51.916  3759  4387 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-29 14:45:51.916  3759  4387 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-29 14:45:51.917  3759  4387 I BooksSync: Finished books sync
,08-29 14:45:51.926   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 497303, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-29 14:46:16.677   873  4302 D NetlinkSocketObserver: NeighborEvent{elapsedMs=522292, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 14:46:33.214  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:46:33.216  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:46:33.264  1511  2011 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-29 14:46:33.265  1511  2011 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-29 14:46:33.265  1511  2011 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:46:33.265  1511  2011 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:46:33.300  3565  4391 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-29 14:46:33.300  3565  4391 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 14:46:33.300  3565  4391 E HttpOperation: 	at jdm.a(PG:82)
08-29 14:46:33.300  3565  4391 E HttpOperation: 	at jcs.o(PG:406)
08-29 14:46:33.300  3565  4391 E HttpOperation: 	at jcn.a(PG:1379)
08-29 14:46:33.300  3565  4391 E HttpOperation: 	at jcs.i(PG:143)
08-29 14:46:33.300  3565  4391 E HttpOperation: 	at blb.a(PG:3937)
08-29 14:46:33.300  3565  4391 E HttpOperation: 	at czp.a(PG:18188)
08-29 14:46:33.300  3565  4391 E HttpOperation: 	at czp.a(PG:9081)
08-29 14:46:33.300  3565  4391 E HttpOperation: 	at czq.run(PG:1686)
08-29 14:46:33.300  3565  4391 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 14:46:33.300  3565  4391 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 14:46:33.300  3565  4391 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 14:46:33.300  3565  4391 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 14:46:33.300  3565  4391 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 14:46:33.300  3565  4391 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 14:46:33.300  3565  4391 E HttpOperation: 	at jdj.a(PG:4091)
08-29 14:46:33.300  3565  4391 E HttpOperation: 	at jdj.a(PG:1125)
08-29 14:46:33.300  3565  4391 E HttpOperation: 	at jdm.a(PG:77)
08-29 14:46:33.300  3565  4391 E HttpOperation: 	... 12 more
08-29 14:46:33.300  3565  4391 E HttpOperation: Caused by: faj: BadAuthentication
08-29 14:46:33.300  3565  4391 E HttpOperation: 	at fal.a(PG:38)
08-29 14:46:33.300  3565  4391 E HttpOperation: 	at jdj.a(PG:4089)
08-29 14:46:33.300  3565  4391 E HttpOperation: 	... 14 more
,08-29 14:46:33.403  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-29 14:46:33.403  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-29 14:46:33.403  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 14:46:33.403  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:46:33.423  3565  4391 E HttpOperation: [getmobileexperiments] Unexpected exception
08-29 14:46:33.423  3565  4391 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-29 14:46:33.423  3565  4391 E HttpOperation: 	at jdm.a(PG:82)
08-29 14:46:33.423  3565  4391 E HttpOperation: 	at jcs.o(PG:406)
08-29 14:46:33.423  3565  4391 E HttpOperation: 	at jcn.a(PG:1379)
08-29 14:46:33.423  3565  4391 E HttpOperation: 	at jcs.i(PG:143)
08-29 14:46:33.423  3565  4391 E HttpOperation: 	at hec.a(PG:42)
08-29 14:46:33.423  3565  4391 E HttpOperation: 	at hee.a(PG:102)
08-29 14:46:33.423  3565  4391 E HttpOperation: 	at czr.a(PG:65)
08-29 14:46:33.423  3565  4391 E HttpOperation: 	at kka.a(PG:108)
08-29 14:46:33.423  3565  4391 E HttpOperation: 	at czp.a(PG:19176)
08-29 14:46:33.423  3565  4391 E HttpOperation: 	at czp.a(PG:9081)
08-29 14:46:33.423  3565  4391 E HttpOperation: 	at czq.run(PG:1686)
08-29 14:46:33.423  3565  4391 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 14:46:33.423  3565  4391 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 14:46:33.423  3565  4391 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 14:46:33.423  3565  4391 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 14:46:33.423  3565  4391 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-29 14:46:33.423  3565  4391 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 14:46:33.423  3565  4391 E HttpOperation: 	at jdj.a(PG:4091)
08-29 14:46:33.423  3565  4391 E HttpOperation: 	at jdj.a(PG:1125)
08-29 14:46:33.423  3565  4391 E HttpOperation: 	at jdm.a(PG:77)
08-29 14:46:33.423  3565  4391 E HttpOperation: 	... 15 more
08-29 14:46:33.423  3565  4391 E HttpOperation: Caused by: faj: BadAuthentication
08-29 14:46:33.423  3565  4391 E HttpOperation: 	at fal.a(PG:38)
08-29 14:46:33.423  3565  4391 E HttpOperation: 	at jdj.a(PG:4089)
08-29 14:46:33.423  3565  4391 E HttpOperation: 	... 17 more
,08-29 14:46:33.423  3565  4391 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-29 14:46:33.423  3565  4391 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-29 14:46:33.423  3565  4391 E ExperimentLoader: 	at jdm.a(PG:82)
08-29 14:46:33.423  3565  4391 E ExperimentLoader: 	at jcs.o(PG:406)
08-29 14:46:33.423  3565  4391 E ExperimentLoader: 	at jcn.a(PG:1379)
08-29 14:46:33.423  3565  4391 E ExperimentLoader: 	at jcs.i(PG:143)
08-29 14:46:33.423  3565  4391 E ExperimentLoader: 	at hec.a(PG:42)
08-29 14:46:33.423  3565  4391 E ExperimentLoader: 	at hee.a(PG:102)
08-29 14:46:33.423  3565  4391 E ExperimentLoader: 	at czr.a(PG:65)
08-29 14:46:33.423  3565  4391 E ExperimentLoader: 	at kka.a(PG:108)
08-29 14:46:33.423  3565  4391 E ExperimentLoader: 	at czp.a(PG:19176)
08-29 14:46:33.423  3565  4391 E ExperimentLoader: 	at czp.a(PG:9081)
08-29 14:46:33.423  3565  4391 E ExperimentLoader: 	at czq.run(PG:1686)
08-29 14:46:33.423  3565  4391 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-29 14:46:33.423  3565  4391 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-29 14:46:33.423  3565  4391 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 14:46:33.423  3565  4391 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 14:46:33.423  3565  4391 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-29 14:46:33.423  3565  4391 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-29 14:46:33.423  3565  4391 E ExperimentLoader: 	at jdj.a(PG:4091)
08-29 14:46:33.423  3565  4391 E ExperimentLoader: 	at jdj.a(PG:1125)
08-29 14:46:33.423  3565  4391 E ExperimentLoader: 	at jdm.a(PG:77)
08-29 14:46:33.423  3565  4391 E ExperimentLoader: 	... 15 more
08-29 14:46:33.423  3565  4391 E ExperimentLoader: Caused by: faj: BadAuthentication
08-29 14:46:33.423  3565  4391 E ExperimentLoader: 	at fal.a(PG:38)
08-29 14:46:33.423  3565  4391 E ExperimentLoader: 	at jdj.a(PG:4089)
08-29 14:46:33.423  3565  4391 E ExperimentLoader: 	... 17 more
,08-29 14:46:33.580   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 538490, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-29 14:46:45.476   873  4302 D NetlinkSocketObserver: NeighborEvent{elapsedMs=551091, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 14:46:53.476   873  4302 D NetlinkSocketObserver: NeighborEvent{elapsedMs=559091, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 14:47:22.278   873  4302 D NetlinkSocketObserver: NeighborEvent{elapsedMs=587892, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE},
,08-29 14:47:30.276   873  4302 D NetlinkSocketObserver: NeighborEvent{elapsedMs=595891, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 14:47:59.077   873  4302 D NetlinkSocketObserver: NeighborEvent{elapsedMs=624692, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 14:48:10.320  3528  3528 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,08-29 14:48:10.408  1721  4401 I EventLogService: Opted in for usage reporting
,08-29 14:48:10.419  1721  4401 I EventLogService: Aggregate from 1472473007381 (log), 1472473007381 (data)
,08-29 14:48:10.478  1721  4401 W EventLogAggregator: Unknown tag: snet_gcore
08-29 14:48:10.478  1721  4401 W EventLogAggregator: Unknown tag: snet_launch_service
,08-29 14:48:10.522  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:48:10.526  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:48:10.528  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:48:10.549  3816  4402 V GoogleAuthProtoRequest: [325] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 14:48:10.569  1721  4401 I ServiceDumpSys: dumping service [account]
,08-29 14:48:10.578  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-29 14:48:10.578  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-29 14:48:10.579  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:48:10.579  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:48:10.617  3528  3528 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-29 14:48:10.625  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:48:10.631  1511  2877 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-29 14:48:10.631  1511  2877 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-29 14:48:10.631  1511  2877 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:48:10.631  1511  2877 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:48:10.673  3816  4402 W ExperimentUpdateService: [325] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-29 14:48:10.673  1511  2173 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-29 14:48:10.673  1511  2173 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-29 14:48:10.674  1511  2173 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 14:48:10.674  1511  2173 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-29 14:48:10.674  3816  4402 W ExperimentUpdateService: [325] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 14:48:10.674  3816  4402 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 14:48:10.674  3816  4402 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-29 14:48:10.674  3816  4402 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-29 14:48:10.674  3816  4402 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-29 14:48:10.674  3816  4402 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-29 14:48:10.674  3816  4402 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-29 14:48:10.674  3816  4402 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-29 14:48:10.674  3816  4402 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-29 14:48:10.674  3816  4402 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-29 14:48:10.674  3816  4402 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-29 14:48:10.766  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:48:10.838  1511  2173 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-29 14:48:10.838  1511  2173 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-29 14:48:10.839  1511  2173 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 14:48:10.839  1511  2173 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:48:10.879  3528  3528 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-29 14:48:11.382  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:48:11.446  1511  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-29 14:48:11.447  1511  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-29 14:48:11.447  1511  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 14:48:11.447  1511  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:48:11.504  3528  3528 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-29 14:48:11.507  3528  3528 D Finsky  : [1] WearSupportService.startHygiene: disabled
,08-29 14:48:11.511  3528  3528 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,08-29 14:48:11.524  3528  3634 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-29 14:48:11.527  3528  3528 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,08-29 14:48:26.228  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:48:26.243  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:48:26.249  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:48:26.302  1511  2877 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-29 14:48:26.302  1511  2877 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.,
08-29 14:48:26.303  1511  2877 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-29 14:48:26.303  1511  2877 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:48:26.347  3528  3528 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-29 14:48:26.347  3528  3528 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-29 14:48:26.348  3528  3528 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,08-29 14:48:43.596   873  4302 D NetlinkSocketObserver: NeighborEvent{elapsedMs=669210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 14:48:46.563  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:48:46.575  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:48:46.579  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:48:46.626  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-29 14:48:46.626  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-29 14:48:46.627  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:48:46.627  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:48:46.672  3528  3528 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-29 14:48:46.673  3528  3528 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 14:48:46.673  3528  3528 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,08-29 14:49:06.982  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:49:06.996  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:49:07.001  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:49:07.074  1511  2173 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-29 14:49:07.074  1511  2173 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-29 14:49:07.076  1511  2173 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:49:07.077  1511  2173 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:49:07.126  3528  3528 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-29 14:49:07.127  3528  3528 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-29 14:49:07.127  3528  3528 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-29 14:49:12.355   873  4302 D NetlinkSocketObserver: NeighborEvent{elapsedMs=697970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 14:49:27.497  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:49:27.515  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:49:27.522  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:49:27.612  1511  2877 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-29 14:49:27.613  1511  2877 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-29 14:49:27.613  1511  2877 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:49:27.614  1511  2877 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:49:27.687  3528  3528 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-29 14:49:27.688  3528  3528 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-29 14:49:27.689  3528  3528 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-29 14:49:48.056  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:49:48.064  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:49:48.068  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:49:48.127  1511  2877 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-29 14:49:48.128  1511  2877 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 14:49:48.129  1511  2877 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:49:48.129  1511  2877 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:49:48.177  3528  3528 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-29 14:49:48.178  3528  3528 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-29 14:49:48.179  3528  3528 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-29 14:50:08.419  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:50:08.430  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:50:08.433  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:50:08.480  1511  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-29 14:50:08.480  1511  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-29 14:50:08.480  1511  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:50:08.481  1511  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:50:08.522  3528  3528 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-29 14:50:08.522  3528  3528 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-29 14:50:08.522  3528  3528 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-29 14:56:12.296  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:56:12.299  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-29 14:56:12.322  3816  4425 V GoogleAuthProtoRequest: [326] a.<init>: mAccountName set to: thalitester@gmail.com
,08-29 14:56:12.372  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-29 14:56:12.372  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-29 14:56:12.372  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-29 14:56:12.372  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-29 14:56:12.415  3816  4425 W ExperimentUpdateService: [326] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
08-29 14:56:12.416  3816  4425 W ExperimentUpdateService: [326] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 14:56:12.416  3816  4425 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-29 14:56:12.416  3816  4425 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-29 14:56:12.416  3816  4425 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-29 14:56:12.416  3816  4425 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-29 14:56:12.416  3816  4425 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-29 14:56:12.416  3816  4425 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-29 14:56:12.416  3816  4425 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-29 14:56:12.416  3816  4425 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-29 14:56:12.416  3816  4425 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-29 14:56:12.416  3816  4425 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-29 14:56:17.302   873  4302 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1122917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-29 14:56:27.182   873  4302 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1132797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-29 14:57:52.845   873   885 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms),08-29 15:03:09.273  4447  4447 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 15:03:09.278  4447  4447 D AndroidRuntime: CheckJNI is OFF
08-29 15:03:09.313  4447  4447 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 15:03:09.356  4447  4447 I Radio-JNI: register_android_hardware_Radio DONE
08-29 15:03:09.377  4447  4447 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-29 15:03:09.388   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-29 15:03:09.505   873   896 W PackageSettings: Skipping PackageSetting{a99b0c1 com.example.hello/10273} due to missing metadata
08-29 15:03:09.544   873   896 I art     : Starting a blocking GC Explicit
08-29 15:03:09.584   873   896 I art     : Explicit concurrent mark sweep GC freed 16962(1127KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 655us total 39.377ms
08-29 15:03:09.604   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-29 15:03:09.612  4447  4447 I art     : System.exit called, status: 0
08-29 15:03:09.612  4447  4447 I AndroidRuntime: VM exiting with result code 0.
08-29 15:03:09.661   873   896 I ActivityManager: Start proc 4460:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-29 15:03:09.661   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-29 15:03:09.692  4243  4243 D BluetoothMapAppObserver: onReceive
08-29 15:03:09.692  4243  4243 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-29 15:03:09.693  2056  2298 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-29 15:03:09.698   873  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-29 15:03:09.699  3644  3644 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-29 15:03:09.719  1878  1878 I Keyboard.Facilitator: resetDictionaries() : en_US
08-29 15:03:09.726  1878  4474 I Keyboard.Facilitator.DecoderInitializer: run()
08-29 15:03:09.732  1878  4474 I Decoder : createOrResetDecoder
08-29 15:03:09.757  1953  1953 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-29 15:03:09.759   873  1311 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
08-29 15:03:09.770   873  2123 I ActivityManager: Start proc 4475:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-29 15:03:09.779  1511  1511 I ConfigService: onCreate
08-29 15:03:09.786  1511  4486 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-29 15:03:09.786  1511  4486 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:03:09.786  1511  4486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:03:09.786  1511  4486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:03:09.786  1511  4486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:03:09.786  1511  4486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:03:09.786  1511  4486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:03:09.786  1511  4486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:03:09.786  1511  4486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:03:09.786  1511  4486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:03:09.786  1511  4486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:03:09.786  1511  4486 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:03:09.786  1511  4486 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:03:09.786  1511  4486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:03:09.786  1511  4486 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 15:03:09.786  1511  4486 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-29 15:03:09.786  1511  4486 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-29 15:03:09.786  1511  4486 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:03:09.788  1511  4486 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-29 15:03:09.788  1511  4486 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:03:09.788  1511  4486 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:03:09.788  1511  4486 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:03:09.788  1511  4486 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:03:09.788  1511  4486 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:03:09.788  1511  4486 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:03:09.788  1511  4486 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:03:09.788  1511  4486 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:03:09.788  1511  4486 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:03:09.788  1511  4486 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:03:09.788  1511  4486 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:03:09.788  1511  4486 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:03:09.788  1511  4486 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:03:09.788  1511  4486 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 15:03:09.788  1511  4486 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-29 15:03:09.788  1511  4486 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-29 15:03:09.788  1511  4486 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:03:09.793  1511  4486 W SQLiteOpenHelper: Opened config.db in read-only mode
08-29 15:03:09.816   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-29 15:03:09.825  1878  4474 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-29 15:03:09.843  1966  2055 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-29 15:03:09.844   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-29 15:03:09.845   873   885 E PackageManager: Failed to write settings, restoring backup
08-29 15:03:09.845   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-29 15:03:09.845   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-29 15:03:09.845   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-29 15:03:09.845   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-29 15:03:09.845   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-29 15:03:09.845   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:03:09.845   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:03:09.845   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 15:03:09.849  4475  4475 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-29 15:03:09.850   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-29 15:03:09.850   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-29 15:03:09.850   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 15:03:09.850   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 15:03:09.850   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 15:03:09.850   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 15:03:09.850   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 15:03:09.850   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 15:03:09.850   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-29 15:03:09.850   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-29 15:03:09.850   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-29 15:03:09.850   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 15:03:09.850   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 15:03:09.850   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:03:09.850   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 15:03:09.850   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 15:03:09.850   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 15:03:09.850   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 15:03:09.850   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 15:03:09.850   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 15:03:09.850   873   886 E DropBoxManagerService: 	... 13 more
08-29 15:03:09.859   873  2123 I ActivityManager: Start proc 4489:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-29 15:03:09.859  1966  2055 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-29 15:03:09.859  1966  2055 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1966
08-29 15:03:09.859  1966  2055 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 15:03:09.859  1966  2055 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 15:03:09.859  1966  2055 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 15:03:09.859  1966  2055 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 15:03:09.859  1966  2055 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 15:03:09.859  1966  2055 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 15:03:09.859  1966  2055 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-29 15:03:09.859  1966  2055 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-29 15:03:09.859  1966  2055 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 15:03:09.859  1966  2055 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 15:03:09.859  1966  2055 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:03:09.859  1966  2055 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 15:03:09.862   873  2125 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 15:03:09.862   873  4496 E DropBoxManagerService: Can't write: system_app_crash
08-29 15:03:09.862   873  4496 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-29 15:03:09.862   873  4496 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 15:03:09.862   873  4496 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 15:03:09.862   873  4496 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 15:03:09.862   873  4496 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 15:03:09.862   873  4496 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 15:03:09.862   873  4496 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 15:03:09.862   873  4496 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 15:03:09.862   873  4496 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 15:03:09.862   873  4496 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 15:03:09.862   873  4496 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 15:03:09.862   873  4496 E DropBoxManagerService: 	... 5 more
08-29 15:03:09.867  1966  2055 I Process : Sending signal. PID: 1966 SIG: 9
08-29 15:03:09.870  1878  4474 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-29 15:03:09.872  1878  4474 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-29 15:03:09.872  1878  4474 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-29 15:03:09.874  1878  4474 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-29 15:03:09.874  1878  4474 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-29 15:03:09.875  1878  4474 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-29 15:03:09.875  1878  4474 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-29 15:03:09.876  1878  4474 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-29 15:03:09.876  1878  4474 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-29 15:03:09.876  1878  4474 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-29 15:03:09.876  1878  4474 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-29 15:03:09.876  1878  4474 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-29 15:03:09.876  1878  4474 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-29 15:03:09.915  4475  4475 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-29 15:03:09.929  4475  4510 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-29 15:03:09.932   873  2004 D GraphicsStats: Buffer count: 1
08-29 15:03:09.932   873  1376 I WindowState: WIN DEATH: Window{840ae07 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-29 15:03:09.938   873  1697 I ActivityManager: Start proc 4511:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-29 15:03:09.947  4475  4506 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 15:03:09.947  4475  4506 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:03:09.947  4475  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:03:09.947  4475  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:03:09.947  4475  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:03:09.947  4475  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:03:09.947  4475  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:03:09.947  4475  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:03:09.947  4475  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:03:09.947  4475  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:03:09.947  4475  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:03:09.947  4475  4506 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:03:09.947  4475  4506 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:03:09.947  4475  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:03:09.947  4475  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 15:03:09.947  4475  4506 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 15:03:09.947  4475  4506 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 15:03:09.947  4475  4506 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 15:03:09.947  4475  4506 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 15:03:09.947  4475  4506 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:03:09.947  4475  4506 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:03:09.947  4475  4506 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 15:03:09.947  4475  4506 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-29 15:03:09.947  4475  4506 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:03:09.947  4475  4506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:03:09.947  4475  4506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:03:09.947  4475  4506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:03:09.947  4475  4506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:03:09.947  4475  4506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:03:09.947  4475  4506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:03:09.947  4475  4506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:03:09.947  4475  4506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:03:09.947  4475  4506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:03:09.947  4475  4506 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:03:09.947  4475  4506 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:03:09.947  4475  4506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:03:09.947  4475  4506 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 15:03:09.947  4475  4506 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-29 15:03:09.947  4475  4506 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-29 15:03:09.947  4475  4506 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-29 15:03:09.947  4475  4506 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-29 15:03:09.947  4475  4506 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:03:09.947  4475  4506 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:03:09.947  4475  4506 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 15:03:09.947   873  2083 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1966) has died
08-29 15:03:09.948   873  2083 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-29 15:03:09.953   873  2083 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-29 15:03:09.970   873   886 I ActivityManager: Start proc 4523:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 15:03:09.987  4511  4511 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:03:10.021  4523  4523 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:03:10.021  4523  4523 D AndroidRuntime: Shutting down VM
08-29 15:03:10.027  1511  1511 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-29 15:03:10.028  1511  1511 D AndroidRuntime: Shutting down VM
08-29 15:03:10.029  1511  1511 E AndroidRuntime: FATAL EXCEPTION: main
08-29 15:03:10.029  1511  1511 E AndroidRuntime: Process: com.google.process.gapps, PID: 1511
08-29 15:03:10.029  1511  1511 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 15:03:10.029  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-29 15:03:10.029  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-29 15:03:10.029  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-29 15:03:10.029  1511  1511 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:03:10.029  1511  1511 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:03:10.029  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:03:10.029  1511  1511 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:03:10.029  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:03:10.029  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:03:10.029  1511  1511 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 15:03:10.029  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 15:03:10.029  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 15:03:10.029  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 15:03:10.029  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 15:03:10.029  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 15:03:10.029  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-29 15:03:10.029  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-29 15:03:10.029  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-29 15:03:10.029  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-29 15:03:10.029  1511  1511 E AndroidRuntime: 	... 8 more
08-29 15:03:10.032  4523  4523 E AndroidRuntime: FATAL EXCEPTION: main
08-29 15:03:10.032  4523  4523 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4523
08-29 15:03:10.032  4523  4523 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 15:03:10.032  4523  4523 E AndroidRuntime: 	... 10 more
08-29 15:03:10.033   873  4539 E DropBoxManagerService: Can't write: system_app_crash
08-29 15:03:10.033   873  4539 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-29 15:03:10.033   873  4539 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 15:03:10.033   873  4539 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 15:03:10.033   873  4539 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 15:03:10.033   873  4539 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 15:03:10.033   873  4539 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 15:03:10.033   873  4539 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 15:03:10.033   873  4539 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 15:03:10.033   873  4539 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 15:03:10.033   873  4539 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 15:03:10.033   873  4539 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 15:03:10.033   873  4539 E DropBoxManagerService: 	... 5 more
08-29 15:03:10.036   873  2122 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 15:03:10.037  4523  4523 I Process : Sending signal. PID: 4523 SIG: 9
08-29 15:03:10.037   873  4540 E DropBoxManagerService: Can't write: system_app_crash
08-29 15:03:10.037   873  4540 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-29 15:03:10.037   873  4540 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 15:03:10.037   873  4540 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 15:03:10.037   873  4540 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 15:03:10.037   873  4540 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 15:03:10.037   873  4540 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 15:03:10.037   873  4540 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 15:03:10.037   873  4540 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 15:03:10.037   873  4540 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 15:03:10.037   873  4540 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 15:03:10.037   873  4540 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 15:03:10.037   873  4540 E DropBoxManagerService: 	... 5 more
08-29 15:03:10.045  1511  1511 I Process : Sending signal. PID: 1511 SIG: 9
08-29 15:03:10.061   873  2123 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4523) has died
08-29 15:03:10.062   873  2123 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-29 15:03:10.076   873   886 I ActivityManager: Start proc 4542:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 15:03:10.079   873  2004 I ActivityManager: Killing 3474:com.android.providers.calendar/u0a3 (adj 15): empty #17
08-29 15:03:10.080  1721  4538 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 352)
08-29 15:03:10.080  1721  4538 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@caaa7
08-29 15:03:10.089   873  1314 D WifiService: Client connection lost with reason: 4
08-29 15:03:10.093  4475  4506 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:03:10.100  4475  4510 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 15:03:10.100  4475  4510 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 15:03:10.100  4475  4510 E AndroidRuntime: Process: android.process.acore, PID: 4475
08-29 15:03:10.100  4475  4510 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:03:10.100  4475  4510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:03:10.100  4475  4510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:03:10.100  4475  4510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:03:10.100  4475  4510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:03:10.100  4475  4510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:03:10.100  4475  4510 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:03:10.100  4475  4510 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:03:10.100  4475  4510 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:03:10.100  4475  4510 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:03:10.100  4475  4510 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:03:10.100  4475  4510 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:03:10.100  4475  4510 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:03:10.100  4475  4510 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 15:03:10.100  4475  4510 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-29 15:03:10.100  4475  4510 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 15:03:10.100  4475  4510 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 15:03:10.100  4475  4510 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 15:03:10.100  4475  4510 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 15:03:10.100  4475  4510 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 15:03:10.100  4475  4510 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 15:03:10.100  4475  4510 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:03:10.100  4475  4510 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:03:10.100  4475  4510 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 15:03:10.101  4475  4506 I Process : Sending signal. PID: 4475 SIG: 9
08-29 15:03:10.132   873   884 I ActivityManager: Process com.google.process.gapps (pid 1511) has died
08-29 15:03:10.133   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
08-29 15:03:10.133   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
08-29 15:03:10.133   873   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
08-29 15:03:10.143   873  1697 I ActivityManager: Process android.process.acore (pid 4475) has died
08-29 15:03:10.144   873  1697 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30989ms
08-29 15:03:10.149  1721  1721 W RocketImpressions: ClearcutLogger connection suspended: 1
08-29 15:03:10.156   873  2004 I ActivityManager: Start proc 4554:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
08-29 15:03:10.161   873  4564 E DropBoxManagerService: Can't write: system_app_crash
08-29 15:03:10.161   873  4564 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-29 15:03:10.161   873  4564 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 15:03:10.161   873  4564 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 15:03:10.161   873  4564 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 15:03:10.161   873  4564 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 15:03:10.161   873  4564 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 15:03:10.161   873  4564 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 15:03:10.161   873  4564 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 15:03:10.161   873  4564 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 15:03:10.161   873  4564 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 15:03:10.161   873  4564 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 15:03:10.161   873  4564 E DropBoxManagerService: 	... 5 more
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:03:10.167  4542  4542 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:03:10.168  4542  4542 D AndroidRuntime: Shutting down VM
08-29 15:03:10.183  4542  4542 E AndroidRuntime: FATAL EXCEPTION: main
08-29 15:03:10.183  4542  4542 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4542
08-29 15:03:10.183  4542  4542 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 15:03:10.183  4542  4542 E AndroidRuntime: 	... 10 more
08-29 15:03:10.185   873  1698 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-29 15:03:10.186   873  4569 E DropBoxManagerService: Can't write: system_app_crash
08-29 15:03:10.186   873  4569 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
08-29 15:03:10.186   873  4569 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 15:03:10.186   873  4569 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 15:03:10.186   873  4569 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 15:03:10.186   873  4569 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 15:03:10.186   873  4569 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 15:03:10.186   873  4569 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 15:03:10.186   873  4569 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 15:03:10.186   873  4569 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 15:03:10.186   873  4569 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 15:03:10.186   873  4569 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 15:03:10.186   873  4569 E DropBoxManagerService: 	... 5 more
08-29 15:03:10.186  4542  4542 I Process : Sending signal. PID: 4542 SIG: 9
08-29 15:03:10.201  4554  4554 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
08-29 15:03:10.204  1721  1721 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-29 15:03:10.204  1721  1721 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-29 15:03:10.210  1721  1721 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-29 15:03:10.210  1721  1721 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-29 15:03:10.216  1721  4571 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-29 15:03:10.219  4554  4554 I MultiDex: VM with version 2.1.0 has multidex support
08-29 15:03:10.219  4554  4554 I MultiDex: install
08-29 15:03:10.219  4554  4554 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-29 15:03:10.221   873  1972 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2712)
08-29 15:03:10.222   873  1972 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver}
08-29 15:03:10.222   873  1972 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
08-29 15:03:10.222   873  1972 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 15:03:10.222   873  1972 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
08-29 15:03:10.222   873  1972 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
08-29 15:03:10.222   873  1972 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
08-29 15:03:10.222   873  1972 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
08-29 15:03:10.222   873  1972 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17118)
08-29 15:03:10.222   873  1972 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
08-29 15:03:10.222   873  1972 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
08-29 15:03:10.222   873  1972 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
08-29 15:03:10.237  1721  4571 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-29 15:03:10.237  1721  4571 E AndroidRuntime: Process: com.google.android.gms, PID: 1721
08-29 15:03:10.237  1721  4571 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 15:03:10.237  1721  4571 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-29 15:03:10.237  1721  4571 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-29 15:03:10.237  1721  4571 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-29 15:03:10.237  1721  4571 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-29 15:03:10.237  1721  4571 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-29 15:03:10.237  1721  4571 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-29 15:03:10.237  1721  4571 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-29 15:03:10.237  1721  4571 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-29 15:03:10.237  1721  4571 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-29 15:03:10.237  1721  4571 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 15:03:10.237  1721  4571 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 15:03:10.237  1721  4571 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-29 15:03:10.237  1721  4571 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-29 15:03:10.237  1721  4571 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-29 15:03:10.237  1721  4571 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-29 15:03:10.237  1721  4571 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 15:03:10.237  1721  4571 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 15:03:10.237  1721  4571 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-29 15:03:10.246   873  1972 I ActivityManager: Start proc 4573:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
08-29 15:03:10.248   873  1984 W ActivityManager: Spurious death for ProcessRecord{ec18218 4573:com.google.android.googlequicksearchbox/u0a28}, curProc for 4542: null
08-29 15:03:10.248  2032  4570 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-29 15:03:10.251  4554  4554 W System,  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-29 15:03:10.253   873  4583 E DropBoxManagerService: Can't write: system_app_crash
08-29 15:03:10.253   873  4583 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop134.tmp: open failed: EROFS (Read-only file system)
08-29 15:03:10.253   873  4583 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 15:03:10.253   873  4583 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 15:03:10.253   873  4583 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 15:03:10.253   873  4583 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 15:03:10.253   873  4583 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 15:03:10.253   873  4583 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 15:03:10.253   873  4583 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 15:03:10.253   873  4583 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 15:03:10.253   873  4583 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 15:03:10.253   873  4583 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 15:03:10.253   873  4583 E DropBoxManagerService: 	... 5 more
08-29 15:03:10.271  1721  4571 I Process : Sending signal. PID: 1721 SIG: 9
08-29 15:03:10.298  2032  4570 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-29 15:03:10.304  4554  4554 I GservicesProvider: Gservices pushing to system: true; secure/global: true
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:03:10.307  4554  4554 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:03:10.307  4554  4554 D AndroidRuntime: Shutting down VM
08-29 15:03:10.311  4554  4554 E AndroidRuntime: FATAL EXCEPTION: main
08-29 15:03:10.311  4554  4554 E AndroidRuntime: Process: com.google.process.gapps, PID: 4554
08-29 15:03:10.311  4554  4554 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 15:03:10.311  4554  4554 E AndroidRuntime: 	... 10 more
08-29 15:03:10.313   279   279 E lowmemorykiller: Error writing /proc/1721/oom_score_adj; errno=22
08-29 15:03:10.318   873  2078 W ActivityManager: Process com.google.android.gms has crashed too many times: killing!
08-29 15:03:10.318   873  2078 I ActivityManager: Killing 4554:com.google.process.gapps/u0a11 (adj 0): crash
08-29 15:03:10.319   873  4586 E DropBoxManagerService: Can't write: system_app_crash
08-29 15:03:10.319   873  4586 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop135.tmp: open failed: EROFS (Read-only file system)
08-29 15:03:10.319   873  4586 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 15:03:10.319   873  4586 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 15:03:10.319   873  4586 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 15:03:10.319   873  4586 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 15:03:10.319   873  4586 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 15:03:10.319   873  4586 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 15:03:10.319   873  4586 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 15:03:10.319   873  4586 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 15:03:10.319   873  4586 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 15:03:10.319   873  4586 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 15:03:10.319   873  4586 E DropBoxManagerService: 	... 5 more
08-29 15:03:10.322  4489  4508 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 292)
08-29 15:03:10.322  4489  4508 W GmsClient: service died
08-29 15:03:10.324  2032  4570 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
08-29 15:03:10.324  2032  4570 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-29 15:03:10.324  2032  4570 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 2032
08-29 15:03:10.324  2032  4570 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 15:03:10.324  2032  4570 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-29 15:03:10.324  2032  4570 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-29 15:03:10.324  2032  4570 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-29 15:03:10.324  2032  4570 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-29 15:03:10.324  2032  4570 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-29 15:03:10.324  2032  4570 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-29 15:03:10.324  2032  4570 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-29 15:03:10.324  2032  4570 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-29 15:03:10.324  2032  4570 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-29 15:03:10.324  2032  4570 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-29 15:03:10.324  2032  4570 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-29 15:03:10.324  2032  4570 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-29 15:03:10.324  2032  4570 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-29 15:03:10.324  2032  4570 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-29 15:03:10.324  2032  4570 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 15:03:10.324  2032  4570 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:03:10.324  2032  4570 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:03:10.324  2032  4570 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 15:03:10.326  4489  4489 E SilentFeedbackService: GoogleApiClient silent feedback connection failed with result: 8
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 15:03:10.373  4573  4573 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 15:03:10.373  4573  4573 D AndroidRuntime: Shutting down VM
08-29 15:03:10.386   873  2125 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@cace256)
08-29 15:03:10.391   873  1315 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:03:10.394   873  1315 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 15:03:10.397   873  2078 W ActivityManager: Failure disconnecting service ComponentInfo{com.google.android.gms/com.google.android.gms.clearcut.service.ClearcutLoggerService} to connection android.os.BinderProxy@94adede (in com.google.android.gms)
08-29 15:03:10.397   873  2078 W ActivityManager: android.os.DeadObjectException
08-29 15:03:10.397   873  2078 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 15:03:10.397   873  2078 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
08-29 15:03:10.397   873  2078 W ActivityManager: 	at android.app.IServiceConnection$Stub$Proxy.connected(IServiceConnection.java:92)
08-29 15:03:10.397   873  2078 W ActivityManager: 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1704)
08-29 15:03:10.397   873  2078 W ActivityManager: 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2336)
08-29 15:03:10.397   873  2078 W ActivityManager: 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15543)
08-29 15:03:10.397   873  2078 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4567)
08-29 15:03:10.397   873  2078 W ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 15:03:10.397   873  2078 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppCrashLocked(ActivityManagerService.java:12031)
08-29 15:03:10.397   873  2078 W ActivityManager: 	at com.android.server.am.ActivityManagerService.makeAppCrashingLocked(ActivityManagerService.java:11933)
08-29 15:03:10.397   873  2078 W ActivityManager: 	at com.android.server.am.ActivityManagerService.crashApplication(ActivityManagerService.java:12622)
08-29 15:03:10.397   873  2078 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12129)
08-29 15:03:10.397   873  2078 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12111)
08-29 15:03:10.397   873  2078 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1458)
08-29 15:03:10.397   873  2078 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
08-29 15:03:10.397   873  2078 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:453)

```
